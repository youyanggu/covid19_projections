---
layout: default
title: About covid19-projections.com
permalink: /about/
---

## Table of contents
* [About the Model](#about-the-model)
* [Who We Are](#who-we-are)
* [How Our Model is Different](#how-our-model-is-different)
* [Historical Performance **(Updated Oct 5)**](#historical-performance)
* [Comparison of Late August US Projections *(Updated Daily)*](#comparison-of-late-august-us-projections)
* [Comparison of Current US Projections *(Updated Daily)*](#comparison-of-current-us-projections)
* [Historical US Projections *(Updated Daily)*](#historical-us-projections)
* [CDC Projections Over Time](#cdc-projections-over-time)
* [Data and Output](#data-and-output)
* [Assumptions](#assumptions)
  * [Confidence Intervals](#confidence-intervals)
  * [Social Distancing](#social-distancing)
  * [Second Wave](#second-wave)
  * [Post Reopening](#post-reopening)
  * [Fall Wave](#fall-wave)
  * [Infections Estimate](#infections-estimate)
  * [Effective Reproduction Number (R)](#effective-reproduction-number-r)
  * [Infection Fatality Rate (IFR)](#infection-fatality-rate-ifr)
  * [Undetected Deaths](#undetected-deaths)
* [Limitations](#limitations)
* [Twitter Threads **(New Aug 27)**](#twitter-threads)
* [Concerns with the IHME model *(Updated Jun 12)*](#concerns-with-the-ihme-model)
  * [Comparison of Data Sources *(New Jun 12)*](#comparison-of-data-sources)
  * [May 4 Revision](#may-4-revision)
  * [June 8 Revision](#june-8-revision)
  * [June 10 Revision *(New Jun 10)*](#june-8-revision)
  * [State Reopening Timeline](#state-reopening-timeline)
* [Media Coverage](#online-coverage)
* [How to Cite](#how-to-cite)
* [Updates](#updates)

## About the Model

Our COVID-19 prediction model adds the power of artificial intelligence on top of a classic infectious disease model. We developed a simulator based on the [SEIR model](http://leonidzhukov.net/hse/2014/socialnetworks/papers/2000SiamRev.pdf) ([Wikipedia](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SEIR_model)) to simulate the COVID-19 epidemic in each region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. We utilize daily deaths data reported by each region to forecast future reported deaths. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

Our SEIR model is [open source](https://github.com/youyanggu/yyg-seir-simulator). Our projections are uploaded daily [onto GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections). Everything is written in Python 3, and [plotly](https://plotly.com/) is used for plotting. This website is hosted using [GitHub Pages](https://pages.github.com/).

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. Here, we use a pure data-driven approach by letting the machine do the learning. We are currently making projections for: the United States, all 50 US states (plus DC, PR, VI, GU, MP) and 70 countries (including all 27 EU countries). Combined, these 71 countries account for >95% of all global COVID-19 deaths. See map below for a visualization of countries we have projections for.

You can also directly access our [US](/#view-projections) and [global](/#global-projections) projections.

[Back to Top](#top)

## Who We Are

*covid19-projections.com* is made by [Youyang Gu](https://youyanggu.com), an independent data scientist. Youyang completed his Bachelor's degree at the Massachusetts Institute of Technology (MIT), double majoring in Electrical Engineering & Computer Science and Mathematics. He also received his Master's degree at MIT, completing his thesis as part of the [Natural Language Processing group](http://nlp.csail.mit.edu/) at the [MIT Computer Science & Artificial Intelligence Laboratory](https://www.csail.mit.edu/). His expertise is in using machine learning to understand data and make accurate predictions. You can contact him [on Twitter](https://twitter.com/youyanggu) or by using the [Contact](/contact) page.

[Back to Top](#top)

### Additional Links

* [Model Details](/model-details/) - More in-depth description of how our model works.
* [Estimating True Infections](/estimating-true-infections) - Our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19.
* [Youyang Gu August 13 Talk](https://www.youtube.com/watch?v=f88bYflJYEo) - Presentation from Youyang Gu about the model

### Coverage Map

![World Map](/assets/images/world_map.png)

[Back to Top](#top)

## How Our Model is Different

* *Daily updates*: Because our model is purely data-driven, it is quick to run and easy to regenerate. Unlike other models that are only updated only once every few days, our model is updated on a daily basis, leading to more accurate projections. We have generated daily projections since we began the project on April 1. No other model offers this level of update frequency.

* *No public funding*: We are one of the only models [used by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that receives no public funding, making us a completely independent entity.

* *No conflicts of interest*: Similar to the previous point, we are truly an independent entity that operates without outside influence or outside investors. Other groups may have collaborations with industry and government entities, or are developing their work for the purpose of publication. We only have one purpose: to create the most accurate projections.

* *Deaths data only*: Our model only uses daily deaths data as reported by [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series). Unlike other models, we do not use additional data sources such as cases, testing, mobility, temperature, age distribution, air traffic, etc. While supplementary data sources may be helpful, they can also introduce additional noise and complexity which can [notably skew results](#mobility-data).

* *Minimal assumptions*: Because our model uses machine learning to learn the inputs and parameters, we minimize the number of assumptions we have to introduce. This allows us to avoid certain biases that can be present when incorporating various assumptions.

* *Open data:* We upload all of our raw data/projections daily onto [our GitHub page](https://github.com/youyanggu/covid19_projections). All of the data used on this website can be downloaded.

* *Open source:* Our underlying SEIR model is [open source](https://github.com/youyanggu/yyg-seir-simulator).

* *Strong historical performance:* We evaluate the performance of our model on a [weekly basis](#historical-performance). The code and data to evaluate models are also [open-source](https://github.com/youyanggu/covid19-forecast-hub-evaluation).

* *Accounts for reopenings*: We were one of the first models used by the CDC that factors in individual state-by-state or country-by-country reopenings, allowing us to make more realistic projections. Rather than pre-setting the type of reopening (e.g. full vs partial reopening), we allow our model to learn the effects based on the data.

* *Realistic simulations*: Unlike other models that try to create complex mathematical equations to "fit a curve" or estimate the growth rate, we try to simulate the disease exactly how they progress in reality: we start off with the entire population in a region, then on each day a certain proportion becomes infected, and those individuals spread the infections to others, and so forth. This makes our model easy to interpret and understand.

* *Flexibility to create scenarios*: Because of model's realistic and flexible properties, we are able to generate varoius hypotheticals, such as what happens if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater). We have also generated hypotheticals on what would happen in each region if there are [no reopenings](https://twitter.com/youyanggu/status/1260678487221796864). A model that simply uses a curve fitting function or tries to track the growth rate will not be able to generate such hypotheticals.

* *Full disclosures of assumptions/limitations:* We describe our [assumptions](#assumptions) and [limitations](#limitations) in the sections below in order to be transparent about what our model can and cannot do. This is something we encourage all other models to provide in a clear manner.

* *Region-agnostic*: Our model is agnostic to the region, enabling us to make projections for all 50 US states (plus DC, PR, VI, Guam), 30+ US counties, and 70+ countries. To our best knowledge, this is the most comprehensive public model in terms of coverage. Due to our machine learning layer, we also do not require manual tuning for each region, allowing us to focus our time on improving our projections.

* *No differential equations*: Unlike traditional SEIR models, our model does not use differential equations. As a result, we can skip the significant computations required to solve systems of ordinary differential equations. Instead, we follow a more traditional discrete mathematics approach by using a discrete state machine with probabilistic transitions. All of the math in our model can be understood by a motivated high school student.

* *Fast*: As a result of the simplicity described above, we are able to make fast computations using limited resources. We can generate all of our projections in under 30 minutes on a laptop.

* *Estimating testing targets*: Because our model keeps an estimate of the number of newly infected individuals each day, we can use this estimate to determine a how many tests each region should ideally perform each day. We base our estimates on Harvard Global Health Institute’s [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that assumes 10 contacts per infected individual. You can download our estimates [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* *Learning the reproduction number (R)*: One of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R. We are able learn the effective reproduction number over time and generate a plot of how the R value changes across all of our projections. Learn more about our R estimates [below](#effective-reproduction-number).

* *Learning the infection fatality rate (IFR)*: Rather than rely on various non-consensus studies on the infection fatality rate (IFR), our model can also learn the best value for the IFR in each region. Learn more about our IFR estimates [below](#infection-fatality-rate-ifr).

* *Learning when people started social distancing*: It turns out that many people began social distancing before a region's formal lockdown order is issued. Our model is able to learn the exact dates when people in a region started social distancing, which are often independent of the stay-at-home orders. For example, in New York, this inflection point is determined to be around March 14, which closely matches the [NYC subway ridership data](https://twitter.com/youyanggu/status/1248844841733128192). For the US as a whole, we estimate that date to be around March 18. You can see what happens if everyone in the US reacted [one week earlier](/us-1weekearlier) (March 11) or [one week later](/us-1weeklater) (March 25).

* *Strong validation system*: Many of the other models tend to overfit to the data. We have a strong validation system to make sure that all of our updates pass out-of-sample validation before they can be included in the model. This allows us to better differentiate the signal from the noise and be more resistant to outliers. Because all of our assumptions and projections are tested/verified on all 50 states as well as over 70 countries, we are able to create more robust projections.

[Back to Top](#top)

## Historical Performance

*Last Updated:* October 5

A model isn't very useful if it's not accurate. Below is our analysis on how various models considered by the CDC have performed over the past few weeks. Because the CDC receives weekly projections from every Monday, we use projections from past Mondays to evaluate the models.

We have open-sourced the code and data used to evaluate COVID-19 models: [https://github.com/youyanggu/covid19-forecast-hub-evaluation](https://github.com/youyanggu/covid19-forecast-hub-evaluation). We believe in a fully transparent evaluation methodology, and publicly releasing all of our code and data is the best way to do so. Learn more about our evaluation methodology [on GitHub](https://github.com/youyanggu/covid19-forecast-hub-evaluation#details).

[Click here](/historical-performance) to see our past weekly performance evaluations and for more explanations behind the evaluations. We believe it's important to look at past evaluations to get a more comprehensive idea of model consistency/accuracy.

### Evaluation of historical 4 week ahead US state-by-state projections

This is a metric that shows the *consistency* of model projections over the period of several months.

[Raw data on GitHub](https://github.com/youyanggu/covid19-forecast-hub-evaluation/blob/master/summary/summary_4_weeks_ahead_states.csv)

![4 week ahead states comparison](/assets/images/4_week_ahead_states.png)

### Evaluation of historical 4 week ahead US nationwide projections

Because US country-wide projections only contains a single forecast per week, there is much higher variance week-to-week compared to state-by-state projections, where there are 50+ forecasts each week. As a result, we believe state-by-state evaluations is a better indicator of model performance. This same concept is why we play 7-game series for NBA/NHL/MLB playoffs.

[Raw data on GitHub](https://github.com/youyanggu/covid19-forecast-hub-evaluation/blob/master/summary/summary_4_weeks_ahead_us.csv)

![4 week ahead US comparison](/assets/images/4_week_ahead_us.png)

### Evaluation of past US state-by-state projections on reported deaths as of October 3

This is a metric that shows the *recent accuracy* of model projections.

[Raw data on GitHub](https://github.com/youyanggu/covid19-forecast-hub-evaluation/blob/master/summary/summary_states_2020-10-03.csv)

![States comparison](/assets/images/2020-10-03_comparison_states.png)

### Evaluation of past US nationwide projections on reported deaths as of October 3

[Raw data on GitHub](https://github.com/youyanggu/covid19-forecast-hub-evaluation/blob/master/summary/summary_us_2020-10-03.csv)

![US comparison](/assets/images/2020-10-03_comparison_us.png)

[Back to Top](#top)

## Comparison of Late August US Projections

Below, we show our late August forecasts compared with IHME's late August forecasts. To view additional comparison plots with IHME, click [here](/model-comparison-ihme).

{% include iframe_ihme_comparison_aug27.html %}

[Back to Top](#top)

## Comparison of Current US Projections

We compare our current projections to that of the Institute for Health Metrics and Evaluation (IHME). To see our full US projections, click [here](/us).

{% include iframe_current.html %}

[Back to Top](#top)

## Historical US Projections

Below, we show how our (C19Pro) August 4 and November 1 projections for the US has changed over time, compared to IHME. Note that the true value on August 4 fell within our model's confidence intervals over 90% of the time. To see our current US projections, click [here](/us).

To view additional comparison plots with IHME, click [here](/model-comparison-ihme).

{% include iframe_historical.html %}

[Back to Top](#top)

## CDC Projections Over Time

Below, we present our weekly CDC projections over time.

{% include iframe_cdc_comparison.html %}

[Back to Top](#top)

## Data and Output

To make our projections, we use the daily death total provided by [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series), what is considered by experts to be the "gold standard" reference data. We do not use case-related data in our modeling due to reasoning alluded to [here](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/). With that said, we do look at case and hospitalization data to help determine the bounds for our search grid, as changes in cases lead changes in deaths.

While we do not use testing data in our model, we sometimes use US testing data from [The COVID Tracking Project](https://covidtracking.com/) in our research and graphs.

Every day, raw daily projections for all 50 US states and select international countries will be uploaded onto our [GitHub page](https://github.com/youyanggu/covid19_projections/tree/master/projections). We are projecting future deaths as reported by Johns Hopkins CSSE.

[Back to Top](#top)

## Assumptions

### Epidemiological Assumptions

We use a considation of resources provided [by Models of Infectious Disease Agent Study (MIDAS)](https://midasnetwork.us/covid-19/#resources) to set standard parameters such as incubation and infectious period. Most of these parameters have a wide consensus among experts. For example, we assume a 5-day incubation period (on average) and a 7-day infectious period (on average). These assumptions are probabilistic and roughly normally distributed. This means that an infected individual would be infectious between Day 2 to Day 8 after exposure, with Day 4-6 being the most infectious. For the purpose of calculating current infections, we assume an average individual is infected for 15 days. The exact values of the above parameters do not significantly change our projections.

Not everyone who are "currently infected" are infectious. To get a sense of the number of individuals that are *infectious*, we recommend dividing the "currently infected" number by half. To get the number of individuals who are at *peak infectiousness*, we recommend dividing the "currently infected" number by ~5.

[Back to Top](#top)

### Confidence Intervals

The future is not set in stone: a single policy change or a small change in the assumptions can cause a large impact in how the epidemic progresses. That's why in addition to our mean estimate, we also provide a 95% confidence interval to reflect this uncertainty. For example, if we predict 150,760 deaths with a range of 88-294k, it means that we are 95% confident that the true deaths will be between 88-294k. Note that these confidence intervals are generated given that our above assumptions hold true. There are many real-world variables that can cause our assumptions to be inaccurate and affect the true outcome. We will try our best to address any inaccurate assumptions as time goes on.

In addition to the 95% confidence interval, we present the mean estimate. This value is usually higher than the median/most likely estimate because it is accounting for a longer tail on the higher end of the estimates. So for example, if our mean estimate for September 2020 US deaths is 180k, our median/most likely estimate may be 170k. This is because the upper bound of the deaths is technically unbounded, while the lower bound is bounded by the current death total. This causes a skew in the distribution of death projections, leading to a mean estimate that is higher than the median estimate.

Our daily deaths confidence intervals are meant to be looked at from a rolling mean basis, rather than a daily incident basis. For example, if a state reports deaths every other day (e.g. 0, 200, 0, 100), a confidence interval that covers daily incident deaths can only use [0, 200], which is not very informative. A confidence interval such as [55, 95] would be more informative, despite not overlapping with any of the four daily incident deaths. Hence, we recommend using a 7-day rolling mean when evaluating our confidence intervals.

We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a mean outcome. If the true results fall within the range, that is within the expected outcome of this model. When citing our projections, we highly recommend including our confidence intervals when referencing our projections (i.e. 21,342 (15-34k) deaths).

[Back to Top](#top)

### Social Distancing

* US states: We assume heavy social distancing until the reopening date and moderate social distancing afterwards. We use the reopening date as outlined by [the New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). For states with a staggered reopening, we use the date for which restaurants are allowed to reopen. For states where there is no concrete reopening date (states highlighted in yellow on the NYT map), we assume a reopening date of June 1. Reopening will likely cause a second wave of infections in states where the outbreak has not yet been fully contained.

* European countries: We assume heavy social distancing until mid-May and moderate social distancing afterwards.

* Non-US and Non-European countries: We try our best to keep track of when each country plans to reopen. If there is no news, we assume social distancing through August.

[Back to Top](#top)

#### Heavy vs moderate social distancing

Heavy social distancing is what many states and countries enacted in the initial stages of the epidemic: stay-at-home orders, closed non-essential businesses, etc. Infection rates typically decrease ~60%, going from an R<sub>0</sub> of around 2-3 to an R of 0.6-1.0. As long as R, a measure of how many people an infected person infects on average, is less than 1, infections will decrease over time. If R is greater than 1, then the infection curve will rise. Hence, the ultimate goal is to keep R under 1.

Moderate social distancing is what we assume will happen once states and countries gradually begin relaxing their social distancing guidelines. Some establishments will reopen, but people will still be somewhat cognizant about maintaining social distancing. Most states and countries will have guidelines that aim to maximize social distancing and minimize close contact, such as enforcing capacity limits and recommending mask-wearing. We assume that infection rates will increase by approximately 0-30%, resulting in an R of around 0.8-1.2. This is based on analysis of R values in regions where there were no lockdowns, such as Sweden and South Dakota. Note that this is still a lower infection rate than what it was prior to the outbreak for most regions.

If regions impose stricter social distancing guidelines than our assumptions listed above, then we will likely see a lower infections and death rate than the current projections. Conversely, if regions impose looser guidelines, then we will likely see a higher infections and death rate. For example, if California reopens before June 1, there will be an increased chance of an earlier resurgence. Or if a state required all residents to wear masks, the likelihood of a steep increase in infections will decrease, according to some recent studies ([[1]](https://www.nature.com/articles/s41591-020-0843-2), [[2]](https://www.preprints.org/manuscript/202004.0203/v1), [[3]](https://www.sciencetimes.com/articles/25410/20200421/austria-90-drop-coronavirus-cases-requiring-people-wear-face-masks.htm)).

[Back to Top](#top)

#### Second wave

In regions where the outbreak has not yet been fully contained, it is possible that reopening will cause a second wave of infections if states fail to maintain sufficient social distancing. We assume that regions that have reopened will take actions to reduce transmission, such as increased contact tracing, mandatory mask wearing, improved treatments, capacity limits, etc. Over time, the aforementioned actions, as well as the natural progression of the virus, will lead to a reduction in the transmission rate.

In states where a second wave is prevalent, infections appear to reach a peak before undergoing a decline, despite a lack of concrete mitigation measures. One theory is that there is a certain subset of the population that are more susceptible to contracting the virus (old age, co-morbidities, unwillingness to take precautions, etc). Once that group is exhausted, it becomes harder for the virus to spread, leading to a decline in transmission despite no government intervention. Note that this is merely a theory to explain the observed data.

As of June 1, our model no longer assumes a second lockdown.

[Back to Top](#top)

#### Post-reopening

After the initial ramp-up period of a reopening (1-2 months), we assume that the spread will decrease over time due to improvements in contact tracing, increased mask wearing, greater awareness within the population, and increased population immunity. In the initial stages of the reopening, this phenomenon will likely be dwarfed by the act of the reopening itself, hence leading to a plateau or increase in cases. But after the rate of reopening for a region has plateaued 1-2 months later, we expect to see a gradual decline in transmission and hence a decline in infections and deaths. Of course, this assumption is highly subject to change based on the data.

Looking at the data, we noticed that as various states reach 10-35% prevalence, infections begin to slow down, despite no significant interventions. This seem to suggest that the effective herd immunity threshold under the current conditions of social distancing and intervention measures may be lower than the 60-80% values previous reported in March/April. Nevertheless, it's important to note that transmission does not stop once HIT is reached - it simply slows down. See our write-up, [Estimating True Infections](https://covid19-projections.com/estimating-true-infections), for a more in-depth analysis on this topic.

Starting on July 22, we use two logistic (sigmoid) functions to approximate the R_t curve from the reopening. We use two parameters, the maximum reopen R_t and the inflection rate to determine the shape. These two parameters are then learned by our machine learning layer based on the data. You can learn more by looking at our [open-source code](https://github.com/youyanggu/yyg-seir-simulator/blob/master/README.md#REOPEN_INFLECTION).

Prior to July 22, we assume a very small daily decay in the transmission rate (R) starting from roughly 30 days after reopening (~0-0.5%). The decay is compoundly applied until the R drops below 1, at which point we stop applying further decays. As the exact value of the decay is unknown ahead of time, we initially sample this decay from a random distribution. As time goes on and we obtain more data regarding the post-reopening effects, our model will learn this decay.

[Back to Top](#top)

#### Fall Wave

The future is uncertain, and many things can happen between now and fall that will change the trajectory of this epidemic. While we believe a September increase in deaths is [unlikely](https://twitter.com/youyanggu/status/1271395005219745792), we do think it is possible that the rate of transmission may increase as we head towards winter. A few reasons for that include: seasonality of the virus, more time spent indoors, increased mobility as schools reopen and people return to work, and the potential loss of acquired immunity.

We currently assume a 0-0.5% daily increase in the transmission rate (R_t) starting in the end of summer (August). Initially, we randomly sample this value from a triangle distribution in our simulations. This results in a wider confidence interval to account for the increased uncertainty. As more data comes in over time, our machine learning algorithm will be able to better learn this value. It's important to recognize that while a fall wave is very likely, that severity of the wave is still very much uncertain.

We do not explicitly model school reopenings, but as of our late September update, we are incorporating an increase in the infection rate due to school reopenings. It is still unclear to what extent this will translate to deaths.

We are currently not changing the infection fatality rate (IFR) from the summer. But there has been studies ([Kifer et al.](https://www.medrxiv.org/content/10.1101/2020.07.11.20147157v2.full.pdf)) showing that the fatality rate may increase during the winter months due to factors such as lower indoor humidity.

Because our point estimates are mean estimates rather than median estimates, it is possible for our Rt mean estimates to remain below 1 while the new infections mean estimates increase (due to the skewness of the distribution).

[Back to Top](#top)

### Infections Estimate

The current and total infections estimates in our projections are at the core of our SEIR model. We use those estimates to make forecasts regarding future deaths according to the specifications of the SEIR model. The total infections estimate includes **all** individuals who have ever been infected by the virus, including asymptomatic individuals as well as those who were never tested. The current infections estimate is based on how many people are currently infected at that time point (total - recovered). To compute current infections, we assume that individuals are infected for an average of 15 days. We estimate that the true number of total infections is likely 5-15x higher than reported cases for most regions.

[Back to Top](#top)

### Effective Reproduction Number (R)

One of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2.4-2.8, while for New York City, the R<sub>0</sub> is 5.4-5.8. This means that on average, an infected person in New York City will infect 5.4 to 5.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf). We are able to generate a plot of how the R value changes over time for all of our projections. To see our estimates of R values for every state and country, see our [Infections Tracker](/infections-tracker/) page.

Our R estimates are merely estimates rather than precise values, and *is only based on deaths data*. We correct for reporting lags, so how deaths are changing today is a reflection of how the R value was changing 3-4 weeks ago. We then apply additional assumptions explained in this section to interpolate the R value since then. As a result, the current R value estimates are more of a byproduct of our assumptions than a result of any measurable data. As we receive more data in the future, we then update our R estimates to most closely reflect the observed data.

[Rt.live](https://rt.live) is a good resource for looking at R_t estimates using case data rather than deaths data.

[Back to Top](#top)

### Infection Fatality Rate (IFR)

**Note that our IFR estimates is subject to change based on new data. The exact IFR value does not significantly affect our death estimates.**

**August 5 Update:** See our writeup, [Estimating True infections](/estimating-true-infections), for our in-depth analysis on the infection fatality rate and its relationship with cases, deaths, and test positivity rates.

We estimate that infection fatality rate (IFR) for COVID-19 in the US through April is between [0.9-1.2%](https://twitter.com/youyanggu/status/1256051255253757953). This matches a [May 7 study](https://www.healthaffairs.org/doi/full/10.1377/hlthaff.2020.00455) that estimates the IFR to be slightly less than 1.3% after accounting for asymptomatic cases. We also found that most countries in Europe (with the the exceptions of United Kingdom, Spain, and Eastern Europe) have an IFR closer to 0.75%, which matches [this May 6 study](https://www.medrxiv.org/content/10.1101/2020.05.03.20089854v1).

Prior to June, we use the following initial IFR in our projections:
- 0.75% IFR: Japan, South Korea, Iceland, Norway, Switzerland, all EU countries except Spain
- 1% IFR: US and all other countries

Since June 1, 2020, we use a variable IFR that decreases over time to reflect a lower median age of infections, improving treatments, and possible seasonality of the virus. Hence, we decrease the initial IFR linearly over the span of 3 months until it is 30% of the original IFR. The initial IFR for reach region is determined by looking at the case fatality ratio and median age, and ranges from 0.3%-1.5%. For example, we estimate the initial IFR in New York state is 1.25%, while the initial IFR in Utah is 0.4%. Through the end of April, we estimate the IFR in the US to be around 0.7%, which is [corroborated by CDC's best estimate scenario](https://www.cdc.gov/coronavirus/2019-ncov/hcp/planning-scenarios.html), which cites a study from April. By August 2020, we estimate an implied IFR of 0.2-0.4% in most of the US and Europe. For later-impacted regions like Latin America, we wait an additional 3 months before beginning to decrease the IFR. After the summer, we gradually increase the IFR by ~0.2% per day to account for the shifting age distribution and the potential seasonality of the virus.

We want to note that our IFR estimate is based on *reported deaths*, rather than *true deaths*. Since [the US](https://www.nytimes.com/interactive/2020/05/05/us/coronavirus-death-toll-us.html) and [many other regions](https://www.nytimes.com/interactive/2020/04/21/world/coronavirus-missing-deaths.html) around the world regularly underreport COVID-19 deaths, our IFR estimates is likely to be a lower bound for the true IFR. Once you adjust for age and account for "true" deaths (such as by looking at excess deaths), the true IFR can be much higher. Hence, for the US, even though we use an implied IFR of ~0.3% in our modeling for the 2020 summer wave, we believe that the true IFR is closer to 0.4-0.7%.

Data from the first half of 2020 for [global](https://www.ijidonline.com/article/S1201-9712(20)32180-9/fulltext) ([#2](https://www.medrxiv.org/content/10.1101/2020.05.11.20098780v1)), [Europe](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)31357-X/fulltext), and [US](https://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/covid-19/report-23-united-states/) IFR estimates point to a 0.5-1% IFR to be a reasonable estimate. One of the largest antibody studies thus far estimated a [1.2% IFR](https://www.mscbs.gob.es/gabinetePrensa/notaPrensa/pdf/ENE-C140520115618104.pdf) for Spain. Since those studies have been published, it is possible that IFR has lowered due to improved treatments.

We include asymptomatic individuals in our estimates, as they can also be infectious. [CDC](https://www.cdc.gov/coronavirus/2019-ncov/hcp/planning-scenarios.html) and [other studies](https://www.nature.com/articles/s41586-020-2488-1) ([#2](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2769235)) have shown that there is "no statistically significant difference in the viral load of symptomatic versus asymptomatic infections". Other recent studies suggest that asymptomatic individuals may be slightly lesss infectious, but not by much. Note that asymptomatic individuals are different than pre-symptomatic individuals.

[Back to Top](#top)

### Undetected Deaths

In our June 15 model update, we incorporated the concept of undetected deaths to better estimate the number of true infections in the early stages of the pandemic. In the first weeks of the pandemic for each region, we assume a significant percentage of deaths will be undetected/unreported due to a lack of testing. We assume that this percentage will decrease over time until it reaches a negligible amount. So if there are 100 true deaths and 20% are undetected, then only 80 deaths will be reported/projected. While it is possible that the undetected deaths ratio may be higher, the exact value does not signficantly affect our projections.

As a result of this update, the number of true infected individuals in our projections have increased. However, we believe that even after this update, that we are still undercounting the true deaths in a region.

For further analysis of "excess deaths", see [official CDC data](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html), reporting by [The New York Times](https://www.nytimes.com/interactive/2020/05/05/us/coronavirus-death-toll-us.html), [Financial Times](https://www.ft.com/content/6bd88b7d-3386-4543-b2e9-0d5c6fac846c), or [The Economist](https://www.economist.com/graphic-detail/2020/04/16/tracking-covid-19-excess-deaths-across-countries).

[Back to Top](#top)

## Limitations

We want to be as clear as possible regarding what our model can and cannot do. While we try our best to make accurate projections, no model is perfect. Here we present some of the known limitations of our model.

### Data Accuracy

A model is only as good as the data we feed it. If the data is not accurate, then it would be difficult to make accurate projections downstream. We only use official reported deaths in our modeling.

[Back to Top](#top)

### School Reopening

While we factor in a [fall wave](#fall-wave) in our projections that may result in an increase in transmission, we do not explicitly model school reopenings. As of August, it is still unclear what the effect of school reopenings will be, and how it will differ from district to district and from state to state. We want to wait until we have more data before incorporating this phenomenon into our model.

[Back to Top](#top)

### Death Reporting and Excess Deaths

Some countries report probable deaths while others only report laboratory-confirmed deaths. This difference explains why countries with comprehensive reporting like Belgium have the [highest death rates](https://www.npr.org/sections/coronavirus-live-updates/2020/04/22/841005901/why-belgiums-death-rate-is-so-high-it-counts-lots-of-suspected-covid-19-cases).

On June 8, the Washington Post published [an investigation](https://www.washingtonpost.com/investigations/cdc-wants-states-to-count-probable-coronavirus-cases-and-deaths-but-most-arent-doing-it/2020/06/07/4aac9a58-9d0a-11ea-b60c-3be060a4f8e1_story.html) showing that "at least 24 [US] states are not heeding the national guidelines on reporting probable cases and deaths, despite previously identifying probable cases in other national outbreaks." We made a series of Tweets about it [here](https://twitter.com/youyanggu/status/1270461343892566016).

Differences in how countries/states report deaths can lead to unfair comparisons and also skew projections. For example, New York City reported close to 5,000 probable deaths between April 14-23, but have not reported any probable deaths since. This was an increase of 30% over the existing death total at the time. As a result, early April projections under-projected the number of deaths for New York, while our late April and early May projections over-projected the number of deaths for New York.

Because the accuracy of our projections rely on consistent reporting of deaths, any inconsistencies may skew our projections.

While we attempt to predict the official death total, the true death total will be higher due to underreporting at various levels. [The New York Times](https://www.nytimes.com/interactive/2020/04/21/world/coronavirus-missing-deaths.html), [The Economist](https://www.economist.com/graphic-detail/2020/07/15/tracking-covid-19-excess-deaths-across-countries), and the [Financial Times](https://www.ft.com/content/6bd88b7d-3386-4543-b2e9-0d5c6fac846c) are currently tracking these excess deaths. Also see work by the [Weinberger Lab](https://weinbergerlab.github.io/excess_pi_covid/) at Yale School of Medicine.

[Back to Top](#top)

### Additional Limitations

* *Day-of-week factors*: We currently do not account for day-of-week factors in death reporting. According to [our analysis](https://twitter.com/youyanggu/status/1251779534422073344), deaths reported on Sunday/Monday are about 60% of that of Tuesday-Thursday. So we expect on average that our projections will be higher than Sunday/Monday reports and lower than our Tuesday-Thursday reports. 

* *Confidence intervals*: Due to the aforementioned day-of-week factors and various reporting noises (e.g. states sometimes report 0 on one day and make up for it on the next day), we recommend smoothing daily reported deaths before comparing them to our daily confidence intervals.

* *Data frequency*: Because our model uses only the daily death totals from each region to make projections, it will be more effective for regions where there are more available deaths data (such as New York) than regions where there are only a few reported deaths (such as Wyoming).

* *Summer seasonality*: In the spring, we did not explicitly factor in seasonality changes. A [May 8 study](https://www.cmaj.ca/content/cmaj/early/2020/05/08/cmaj.200920.full.pdf) of 144 geopolitical areas finds no significant correlation between temperature and transmission. However, if seasonality effects are reflected in the data, we will implicitly factor it in. It is possible that the effects of warmer temperatures may be partially offset by lockdown fatigue.

* *Lockdown fatigue / holidays*: As shown in various mobility data and [our analysis](https://twitter.com/youyanggu/status/1255034262006333440) of the NYC subway data, an increasing number of people have been moving around in the weeks following a lockdown. This may contribute to an increase in infections in the weeks following the lockdown/mitigation. Similarly, holidays may be a source of "superspreader" events, which we currently do not explicitly incorporate.

* *Testing data*: In May, there were various reports regarding the accuracy and integrity of data that some US states have been reporting (e.g. see [The Atlantic](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/) and [Associated Press](https://apnews.com/6dbd9ad370add2ba299c7da46c25004f)). We express similar concerns, and hope that states will do their best to report accurate data.

* *Reporting differences*: Different countries follow different guidelines on how they are reporting COVID-19 deaths. For example, Belgium is one of the most comprehensive countries when it comes to death reporting: they report all probable deaths as well as nursing home deaths. In contrast, United Kingdom only began including care home deaths starting on April 29, having only reported hospital deaths previously. Because we are projecting future reported deaths, our model assumes that the reporting guidelines remains constant for each country.

* *Reporting delay*: There is a delay between when a death occurs and when it is reported to the local/state health department. This delay can range anywhere from 1 day to over 30 days, although the vast majority of deaths are reported within 10 days. Prior to July 22, we do not explicitly incorporate this reporting delay. But starting July 22, we began to include this delay in our modeling. We assume that ~50% of deaths are reported within 5 days and ~80% of deaths are reported within 10 days.

* *End date*: We are only making projections for a few weeks to a few months ahead, but this does not mean that the epidemic will stop afterwards. Deaths will continue to rise even after we stop making projections.

* *Asymtomatic individuals* : Our model is based on infectious individuals only. It's unclear to what degree asymptomatic individuals are infectious.

* *International projections*: Our model was created and optimized for the United States. We include our projections for over 70 countries, but we want to caution that the model was not optimized for international countries. So if you plan on citing our model's international projections, please be sure to also consult each country's health experts.

* *Affecting the future*: Our projections are not set in stone and do not exist in a vacuum. If everyone saw our projections and heeded the advice of experts to continuously practice social distancing, the infections and deaths will decrease over time, leading to a final tally that is lower than our projection. That does not mean that our projection were "wrong". In fact, our greatest hope is the scenario described above where we can help prevent future infections and deaths, causing our projections to be an overestimate. For example, a early March [Imperial College study](https://www.nytimes.com/2020/03/17/world/europe/coronavirus-imperial-college-johnson.html) estimated that 2.2 million people would die in the US if mitigations were not implemented. This helped lead to a wave of lockdowns and stay-at-home orders, thereby significantly reducing deaths. That does not mean that the Imperial College study was "wrong" - their study helped shape the outcome of the future.

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

[Back to Top](#top)

## Twitter Threads

Last Updated: September 11

Due to the fast-paced environment of COVID-19 developments and our limited team (of one), Twitter is our preferred method of posting announcements, sharing results and fasciliating discussion. Below is a comprehensive list of our Tweets since late April:

### Research

[August 10](https://twitter.com/youyanggu/status/1292898685173534722) - Role of immunity vs behavior vs interventions (Louisiana case study)<br>
[August 5](https://twitter.com/youyanggu/status/1291092311045283841) - Estimating true infections<br>
[July 24](https://twitter.com/youyanggu/status/1286795355561107457) - Implied infection fatality rate<br>

### Miscellaneous

[September 4](https://twitter.com/youyanggu/status/1301915424456609793) - Forecasting uncertainty<br>
[August 27](https://twitter.com/youyanggu/status/1299016969631531008) - Following the science<br>
[August 13](https://twitter.com/youyanggu/status/1293944308110852099) - Talk announcement<br>
[August 12](https://twitter.com/youyanggu/status/1293586474319912961) - Common pitfalls when estimating true infections<br>
[July 31](https://twitter.com/youyanggu/status/1289284529052700678) - True infections estimates<br>
[July 19](https://twitter.com/youyanggu/status/1284927997448007687) - CDC Forecast Hub<br>
[July 13](https://twitter.com/youyanggu/status/1282624622022852609) - Deaths lag infections<br>
[July 11](https://twitter.com/youyanggu/status/1282028087870459904) - Rise in infections/deaths<br>
[July 9](https://twitter.com/youyanggu/status/1281246408083939332) - Testing bottleneck<br>
[July 3](https://twitter.com/youyanggu/status/1279096904807256064) - Sample comparison with IHME<br>
[July 2](https://twitter.com/youyanggu/status/1278725117808443394) - Second wave<br>
[June 25](https://twitter.com/youyanggu/status/1276075048521121793) - Trivia<br>
[June 24](https://twitter.com/youyanggu/status/1275855071708958722) - Open source SEIR simulator<br>
[June 21](https://twitter.com/youyanggu/status/1274792488285462539) - IHME's lack of representation<br>
[June 13](https://twitter.com/youyanggu/status/1271945547176226816) - Subway ridership analysis<br>
[June 12](https://twitter.com/youyanggu/status/1271329063634743306) - IHME September projections<br>
[June 9](https://twitter.com/youyanggu/status/1270461343892566016) - Probable deaths reporting<br>
[May 29](https://twitter.com/youyanggu/status/1266455964191846400) - Self-quarantine scenario<br>
[May 28](https://twitter.com/youyanggu/status/1266103565870747648) - CNN projection accuracy<br>
[May 20](https://twitter.com/youyanggu/status/1263283908914761729) - OpenTable analysis<br>
[May 16](https://twitter.com/youyanggu/status/1261815392856489984) - Seroprevalence in Stockholm<br>
[May 16](https://twitter.com/youyanggu/status/1261755888781545479) - New feature: Rt over time<br>
[May 15](https://twitter.com/youyanggu/status/1261422993256792066) - Shopping simulation<br>
[May 14](https://twitter.com/youyanggu/status/1261075742021963777) - Social distancing 1 week earlier scenario<br>
[May 13](https://twitter.com/youyanggu/status/1260678487221796864) - New feature: no reopenings<br>
[May 2](https://twitter.com/youyanggu/status/1256739926839668736) - NY serology survey<br>
[April 30](https://twitter.com/youyanggu/status/1256051255253757953) - Infections fatality rate<br>
[April 29](https://twitter.com/youyanggu/status/1255663596387725314) - Model added to CDC website<br>
[April 28](https://twitter.com/youyanggu/status/1255034262006333440) - NYC subway ridership analysis<br>
[April 26](https://twitter.com/youyanggu/status/1254505012396343296) - Rt estimates<br>
[April 25](https://twitter.com/youyanggu/status/1253964427801444353) - Death milestone probabilities<br>

### Projections updates

[September 22](https://twitter.com/youyanggu/status/1308498742451015680)<br>
[September 15](https://twitter.com/youyanggu/status/1305937870075703296)<br>
[September 9](https://twitter.com/youyanggu/status/1303784487030063110)<br>
[September 1](https://twitter.com/youyanggu/status/1300881541468483586)<br>
[August 25](https://twitter.com/youyanggu/status/1298297201626685441)<br>
[August 18](https://twitter.com/youyanggu/status/1295784724418514944)<br>
[July 29](https://twitter.com/youyanggu/status/1288494932441944064)<br>
[July 23](https://twitter.com/youyanggu/status/1286421296474202115)<br>
[July 17](https://twitter.com/youyanggu/status/1284225315703791619)<br>
[July 8](https://twitter.com/youyanggu/status/1280916457698836481)<br>
[June 19](https://twitter.com/youyanggu/status/1274047713454297090)<br>
[June 11](https://twitter.com/youyanggu/status/1271041545458692096)<br>
[June 1](https://twitter.com/youyanggu/status/1267551592837832704)<br>
[May 13](https://twitter.com/youyanggu/status/1260646026542641152)<br>
[May 1](https://twitter.com/youyanggu/status/1256149242260807680)<br>
[May 26](https://twitter.com/youyanggu/status/1265360604220362753)<br>
[May 27](https://twitter.com/youyanggu/status/1265752914011684865)<br>
[May 20](https://twitter.com/youyanggu/status/1263208199756234753)<br>

### Model evaluations

[July 14](https://twitter.com/youyanggu/status/1283102532236181504)<br>
[June 29](https://twitter.com/youyanggu/status/1277679302797033475) - Baseline comparison with IHME<br>
[June 23](https://twitter.com/youyanggu/status/1275490419271512067)<br>
[June 17](https://twitter.com/youyanggu/status/1273304784796176384) - Open source model evaluation<br>
[May 18](https://twitter.com/youyanggu/status/1262477877435437056)<br>
[May 17](https://twitter.com/youyanggu/status/1262149966249652224)<br>
[May 9](https://twitter.com/youyanggu/status/1259242623228719104)<br>
[May 4](https://twitter.com/youyanggu/status/1257434380856889346)<br>
[April 27](https://twitter.com/youyanggu/status/1254866622646386689)<br>
[April 24](https://twitter.com/youyanggu/status/1253611229689475075)<br>

### Maps

[June 27](https://twitter.com/youyanggu/status/1276765403281268736)<br>
[June 24](https://twitter.com/youyanggu/status/1275683113109250048)<br>
[June 15](https://twitter.com/youyanggu/status/1272499124739301376)<br>
[June 8](https://twitter.com/youyanggu/status/1270091682826969088)<br>
[June 12](https://twitter.com/youyanggu/status/1271531383265964033)<br>
[June 6](https://twitter.com/youyanggu/status/1269379382352605184)<br>
[June 5](https://twitter.com/youyanggu/status/1269017578682253312)<br>

### Testing targets

[June 7](https://twitter.com/youyanggu/status/1269536626591412232)<br>
[May 30](https://twitter.com/youyanggu/status/1266843764649152512)<br>
[May 24](https://twitter.com/youyanggu/status/1264666253974573056)<br>
[May 17](https://twitter.com/youyanggu/status/1261882918839836672)<br>

[Back to Top](#top)

## Concerns with the IHME model

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House and media.

We present a series of Tweets highlighting the issues with the IHME model:

[Sep 15](https://twitter.com/youyanggu/status/1305937874194440192)<br>
[Sep 11](https://twitter.com/youyanggu/status/1301915424456609793)<br>
[July 3](https://twitter.com/youyanggu/status/1279096904807256064)<br>
[June 29](https://twitter.com/youyanggu/status/1277679302797033475)<br>
[June 21](https://twitter.com/youyanggu/status/1274792488285462539)<br>
[June 12](https://twitter.com/youyanggu/status/1271329063634743306)<br>
[May 9](https://twitter.com/youyanggu/status/1259242623228719104)<br>
[April 20](https://twitter.com/youyanggu/status/1252104719549362176)<br>
[April 12](https://twitter.com/youyanggu/status/1249243436881829888)

Below, you can find a comparison of our past projections (C19Pro) with IHME for the US, New York, New Jersey, and California, some of the most heavily impacted regions. You can find comparisons of late May projections in the [Historical Performance](#late-may-projections) section. [Click here](/model-comparison-ihme) to view additional comparison plots.

{% include iframe_ihme_comparison_daily_filt.html %}

As you can see from the graphs above, IHME's projections have historically failed to accurately capture the true trajectory for these regions. Below, we will go into further details as to why IHME has been and still is a flawed model.

There are existing news articles such as [Vox](https://www.vox.com/future-perfect/2020/5/2/21241261/coronavirus-modeling-us-deaths-ihme-pandemic), [STAT News](https://www.statnews.com/2020/04/17/influential-covid-19-model-uses-flawed-methods-shouldnt-guide-policies-critics-say/), [CNN](https://www.cnn.com/2020/04/13/health/ihme-model-death-predictions/index.html), and [Quartz](https://qz.com/1840186/what-the-ihme-covid-19-model-can-and-cant-tell-the-us/) that agree with our concerns.

In the words of Ruth Etzioni, an epidemiologist at Seattle’s Fred Hutchinson Cancer Research Center, “that \[the IHME model\] is being used for policy decisions and its results interpreted wrongly is a travesty unfolding before our eyes.”

[Back to Top](#top)

### Baseline Comparison: C19Pro vs IHME

If on June 1, you simply assume each state/country's average daily deaths from the week before will be unchanged for the next 4 weeks, you can make a better forecasts than IHME. This is equivalent to extending a straight line on the daily deaths plots.

![Baseline comparison US](/assets/images/baseline_comparison_june27.png)

![Baseline comparison Global](/assets/images/baseline_comparison_global_june27.png)

The pattern is similar for other dates as well. See our [open source evaluation](https://github.com/youyanggu/covid19-forecast-hub-evaluation) for more.

[Back to Top](#top)

### Late May Projections

Below you can find some of our late May projections for 4 of the most heavily impacted states since reopening: Florida, California, Arizona, Texas.

[Click here](/model-comparison-ihme) to view more plots of historical projections.

{% include iframe_ihme_may28.html %}

[Back to Top](#top)

### Comparison of Data Sources

Here is a comparison of the data sources we use in our model versus what IHME uses (from their [June 11 press release](http://www.healthdata.org/news-release/ihme-models-show-second-wave-covid-19-beginning-september-15-us)). More is not always better.

| covid19-projections.com | IHME
| --- | --- |
| Daily deaths | Daily deaths
| | Case data
| | Testing data
| | Mobility data
| | Pneumonia seasonality
| | Mask use
| | Population density
| | Air pollution
| | Low altitude
| | Annual pneumonia death rate
| | Smoking data
| | Self-reported contacts

### May 4 Revision

On May 4, IHME completely overhauled their previous model and increased their projections from 72k to 132k US deaths by August. Whereas they were previously underprojecting, they are now overprojecting the month of May. At the time of their new update on May 4, there were 68,919 deaths in the US. They projected that there will be 17,201 deaths in the week ending on May 11. In fact, there were only 11,757 deaths. IHME overshot their 1-week projections by 43%. Meanwhile, we projected 10,676 deaths from May 4 through May 11, an error of less than 10%.

IHME went from severely underprojecting their estimates to now overprojecting their estimates, as you can see in the below comparison of May 4 projections. Furthermore, as recently as May 12, they were still projecting 0 deaths by August 4. Their model should not be relied on for accurate projections.

{% include iframe_ihme_may10.html %}

[Back to Top](#top)

### June 8 Revision

On June 8, IHME again revised their model to show a more realistic August projection. Their August 4 projections has now increased from 0 (0-0) deaths in their May 10 projections to 550 (264-1203) deaths in their revised June 8 projections. As the saying goes, better late than never.

![IHME May 10 projections](/assets/images/ihme_may10.png)
![IHME June 8 projections](/assets/images/ihme_jun8.png)

[Back to Top](#top)

### June 10 Revision

In their June 10 update, IHME is projecting deaths to decrease from June through August, and then increase from 400 deaths per day on September 1 to 1,000 deaths per day on October 1. Their [press release](http://www.healthdata.org/news-release/ihme-models-show-second-wave-covid-19-beginning-september-15-us) headline is titled: "IHME models show second wave of COVID-19 beginning September 15 in US". The cite back-to-school and "pneumonia seasonality" as reasons for this fall spike.

Unfortunately, is no scientific data that supports this claim. In reality, pneumonia/influenza deaths are actually the lowest in August and September, [according to the CDC](https://www.cdc.gov/flu/weekly/index.htm). The same pattern [holds true](https://wwwnc.cdc.gov/eid/article/9/5/02-0556_article) for bacterial pneumonia. Regarding back-to-school, schools in Europe have managed to successfully reopen with [no rise in cases](https://www.politico.com/news/2020/06/10/european-school-reopeningsreduce-virus-concerns-for-most-312595). Furthermore, children (age <18) account for [less than 2%](https://www.cdc.gov/mmwr/volumes/69/wr/mm6914e4.htm) of all reported COVID-19 cases. Hence, it makes little sense for deaths to decrease when all of America goes back to work, but for deaths to increase when children go back to school.

[Back to Top](#top)

### Sample Summary of IHME Inaccurate Predictions

In their April 15 projections, the death total that IHME projected will take *four months* to reach was in fact exceeded in *six days*:

|  | April 21 Total Deaths | IHME Aug proj. deaths from Apr 15 | Our Aug proj. deaths from Apr 15
| --- | --- | --- | --- |
| New York | 19,104 | 14,542 | 33,384
| New Jersey | 4,753 | 4,407 | 12,056
| Michigan | 2,575 | 2,373 | 8,196
| Illinois | 1,468 | 1,248 | 4,163
| Italy | 24,648 | 21,130 | 40,216
| Spain | 21,282 | 18,713 | 31,854
| France | 20,829 | 17,448 | 41,643

As you can see above, their models made misguided projections for almost all of the worst impacted regions in the world. The most alarming thing is that they continue to make low projections. Below is their projections from April 21. All of the below projections were exceeded by May 2, just a mere 11 days later:

|  | May 2 Total Deaths | IHME Aug proj. deaths from Apr 21 | Our Aug proj. deaths from Apr 21
| --- | --- | --- | --- |
| New York | 24,198 | 23,741 | 35,238
| New Jersey | 7,742 | 7,116 | 13,651
| Michigan | 4,021 | 3,361 | 6,798
| Illinois | 2,559 | 2,093 | 6,653
| Italy | 28,710 | 26,600 | 44,683
| Spain | 25,100 | 24,624 | 31,854
| France | 24,763 | 23,104 | 41,643

As scientists, we update our models as new data becomes available. Models are going to make wrong predictions, but it's important that we correct them as soon as new data shows otherwise. The problem with IHME is that they refused to recognize and update their wrong assumptions for many weeks. Throughout April, millions of Americans were falsely led to believe that the epidemic would be over by June because of IHME's projections.

On April 30, the director of the IHME, Dr. Chris Murray, [appeared on CNN](https://www.cnn.com/videos/health/2020/05/01/entire-april-30-coronavirus-town-hall-part-3-sot-vpx.cnn) and continued to advocate their model's 72,000 deaths projection by August. On that day, the US reported 63,000 deaths, with 13,000 deaths coming from the previous week alone. Four days later, IHME nearly doubled their projections to 135,000 deaths by August. One week after Dr. Murray's CNN appearance, the US surpassed his 72,000 deaths by August estimate. It seems like an ill-advised decision to go on national television and proclaim 72,000 deaths by August only to double the projections a mere four days later.

Unfortunately, by the time IHME revised their projections in May, millions of Americans have heard their 60,000-70,000 estimate. It may take a while to undo that misconception and undo the policies that were put in place as a result of this misleading estimate.

[Back to Top](#top)

### US June-August

As recently as May 3, IHME projected 304 (0-1644) **total** deaths in the US from June 1 to August 4, a span of two months. The US reported 768 deaths on June 1. So a single day's death total exceeded IHME's estimate for two months.

### Update time

New data is extremely important when making projections such as these. That's why we update our model daily based on the new data we receive. Projections using today's data is much more valuable than projections from 2-3 days ago. However, due to certain constraints, IHME is only able to update their model 1-2 times a week: *"Our ambition to produce daily updates has proven to be unrealistic given the relative size of our team and the effort required to fully process, review, and vet large amounts of data alongside implementing model updates."* 

![IHME days before update](/assets/images/ihme_days_before_update.png)

[Back to Top](#top)

### Mobility Data

On [April 17](http://www.healthdata.org/news-release/ihme-hold-media-briefing-4-pm-eastern-today-details-below), IHME stated that they are incorporating new cell phone mobility data which indicate that people have been properly practicing social distancing: *"These data suggest that mobility and presumably social contact have declined in certain states earlier than the organization’s modeling predicted, especially in the South."* As a result, IHME lowered their projections from 68k deaths to 60k deaths by August. Their critical flaw is that they assume a linear relationship between lower mobility and lower infection - this is not the case.

Most transmissions do not happen with strangers, but rather close contacts. Even if you reduce your mobility by 90%, you do not reduce your transmission by 90%. The data from Italy shows that it only reduces by around 60%. That's the difference between 20k and 40k+ deaths. IHME was likely making the wrong assumption that a 90% reduction in mobility will decrease transmission by 90%. [Here](https://twitter.com/mugecevik/status/1257392347010215947) is a compilation from infectious disease expert Dr. Muge Cevik showing that household contacts were the most likely to be infected.

We posted [a Tweet](https://twitter.com/youyanggu/status/1248844841733128192) on April 11 about MTA (NYC) and BART (Bay Area) subway ridership being down 90% in March. However, the deaths have only dropped around 25% in NY, while CA has yet to see sharp decrease in deaths in April, more than a month after the drop in ridership.

Interestingly, after IHME suddenly revised their projections from 72k to 130k on May 4, the director of IHME offered this explanation for why they raised their estimates: *"...we're seeing just explosive increases in mobility in a number of states that we expect will translate into more cases and deaths."* This is directly contradictory to their press release just [2 weeks earlier](http://www.healthdata.org/news-release/ihme-hold-media-briefing-4-pm-eastern-today-details-below) stating that mobility has been lower than predicted. Any 2-week differences in mobility should not explain this sudden jump in projections - only a flawed methodology would.

[Back to Top](#top)

### State Reopening Timeline

In their [April 17](http://www.healthdata.org/sites/default/files/files/Projects/COVID/Estimation_update_041720.pdf) press release, IHME released estimates of when they believe each state will have a prevalence of fewer than 1 case per 1 million. They noted that 35 states will reach under 1 prevalent infection per 1 million before June 8, and that *"states such as Louisiana, Michigan, and Washington, may fall below the 1 prevalent infection per 1,000,000 threshold around mid-May."*

As of May 15, Louisiana, Michigan, and Washington are reporting 30-90 confirmed cases per million *each day*. Furthermore, prevalent infections are 5-15x higher than reported cases since most cases are mild and thus not tested/reported. As a result, we estimate [Louisiana](/us-la) and [Michigan](/us-mi) to have around 7,000 prevalent infections per million, which is **7,000 times higher** than IHME's April 17 estimates. An analysis for many of the remaining states show a similar high degree of error. Hence, IHME's estimates have been off by a factor of more than *3 orders of magnitude*.

Unfortunately, it is likely that many individuals and policy-makers used IHME's misguided reopening timelines to shape decisions with regards to reopening. Their reopening timelines were picked up and widely disseminated by [many media outlets](http://www.google.com/search?q=ihme+reopening+timeline), both local and national. Any policies guided by these estimates can have repercussions weeks and months down the road.

[Back to Top](#top)

### Technical Flaw

*May 4 Update: IHME completely overhauled their previous model to now use an SEIR model. Our model is based in SEIR and that has not changed since we first began making projections on April 1.*

On top of everything we mentioned above, their model is also inherently flawed from a mathematical perspective. They try to model COVID-19 infections using a [Gaussian error function](https://en.wikipedia.org/wiki/Error_function). The problem is that the Gaussian error function is by design *symmetric*, meaning that the curve comes down from the peak at the same rate as it goes up. Unfortunately, this has not been the case for COVID-19: we come down from the peak at a much slower pace. This leads to a significant under-projection in IHME's model, which we have thoroughly highlighted. University of Washington biology professor Dr. Carl T. Bergostrom discussed this in more detail in this highly informative [series of Tweets](https://twitter.com/CT_Bergstrom/status/1250304069119275009).

[Click here](#historical-us-projections) to see how our projections have changed over time, compared with the IHME model. For a comparison of April projections for several heavily-impacted states and countries, [click here](/model-comparison-ihme).

To conclude, we believe that a successful model must be able to quickly determine what is realistic and what is not, and the above examples highlights our main concerns with the IHME model.

[Back to Top](#top)

## Online Coverage

### Media

National
* [The New Yorker](https://www.newyorker.com/science/elements/what-will-cold-and-flu-season-mean-for-the-coronavirus-pandemic) - Oct 1
* [Business Insider](https://www.businessinsider.com/coronavirus-global-death-toll-may-be-higher-1-million-2020-9) - Sep 29
* [CNBC](https://www.nbcnews.com/science/science-news/vindicated-covid-19-models-warn-pandemic-far-over-n1240934) - Sep 24
* [The Hill](https://thehill.com/policy/healthcare/517918-rising-coronavirus-cases-spark-fears-of-harsh-winter) - Sep 24
* [ProPublica](https://www.propublica.org/article/america-is-about-to-lose-its-200-000th-life-to-coronavirus-how-many-more-have-to-die) - Sep 14
* [Business Insider](https://www.businessinsider.com/us-states-unintentional-herd-immunity-strategy-curbed-covid-spread-2020-8) - Sep 12
* [The Atlantic](https://www.theatlantic.com/health/archive/2020/09/pandemic-intuition-nightmare-spiral-winter/616204/) - Sep 9
* [Yahoo News](https://news.yahoo.com/a-new-covid-19-forecast-predicts-more-than-400000-deaths-by-the-end-of-2020-will-the-fall-wave-really-be-that-big-215402962.html) - Sep 9
* [CNBC](https://www.cnbc.com/2020/09/04/key-coronavirus-forecast-predicts-over-410000-total-us-deaths-by-jan-1.html) - Sep 4
* [Washington Post](https://www.washingtonpost.com/politics/2020/08/26/six-months-ago-trump-said-that-coronavirus-cases-would-soon-go-zero-they-didnt/) - Aug 26
* [Bloomberg](https://www.bloomberg.com/opinion/articles/2020-08-13/covid-spread-is-forcing-scientists-to-rethink-herd-immunity) - Aug 13
* [Washington Post](https://www.washingtonpost.com/politics/2020/07/23/trumps-right-that-with-less-testing-we-record-fewer-cases-fact-thats-already-happening/) - Jul 23
* [ProPublica](https://www.propublica.org/article/how-to-understand-covid-19-numbers) - Jul 21
* [StatNews](https://www.statnews.com/2020/07/20/trump-said-more-covid19-testing-creates-more-cases-we-did-the-math/) - Jul 21
* [AFP](https://www.barrons.com/news/us-covid-19-epidemic-projected-to-worsen-01594826104) - Jul 15
* [Bloomberg](https://www.bloomberg.com/opinion/articles/2020-07-01/covid-19-cases-in-arizona-florida-texas-aren-t-on-same-scale) - Jul 1
* [AFP](https://news.yahoo.com/us-presses-reopening-virus-first-wave-lingers-170209777.html) - Jun 12
* [NPR](https://www.npr.org/sections/health-shots/2020/06/12/876224115/coronavirus-second-wave-nope-were-still-stuck-in-the-first-one) - Jun 11
* [CNN](https://www.cnn.com/2020/06/08/health/florida-coronavirus-cases-update/index.html) - Jun 8
* [The Economist](https://www.economist.com/graphic-detail/2020/05/23/early-projections-of-covid-19-in-america-underestimated-its-severity) - May 21
* [The Wall Street Journal](https://www.wsj.com/articles/states-dont-agree-on-how-to-determine-when-it-is-safe-to-reopen-11590075635) - May 21
* [New York Times](https://www.nytimes.com/interactive/2020/05/12/upshot/coronavirus-models.html) - May 12
* [NPR](https://www.npr.org/sections/health-shots/2020/05/07/851610771/u-s-coronavirus-testing-still-falls-short-hows-your-state-doing) - May 7
* [MarketWatch](https://www.marketwatch.com/story/will-some-people-be-affected-badly-yes-trump-says-us-must-reopen-coronavirus-deaths-projected-to-hit-100000-in-weeks-2020-05-06) - May 6
* [CNN](https://www.cnn.com/2020/05/05/health/states-early-reopening-impact/index.html) - May 5
* [New York Times](https://www.nytimes.com/2020/05/05/us/coronavirus-deaths-cases-united-states.html) - May 5
* [The Wall Street Journal](https://www.wsj.com/articles/the-tricky-math-behind-coronavirus-death-predictions-11588719034) - May 5
* [USA Today](https://www.usatoday.com/story/news/nation/2020/05/01/coronavirus-us-may-hit-10000-deaths-record-cases-may/3062216001/) - May 1
* [StatNews](https://www.statnews.com/2020/04/30/coronavirus-death-projections-compare-causes-of-death) - Apr 30
* [TheHill](https://thehill.com/changing-america/well-being/prevention-cures/495459-reopening-georgia-could-lead-to-a-doubling-of) - Apr 30
* [New York Post](https://nypost.com/2020/04/29/georgia-coronavirus-death-rate-could-double-as-lockdown-eases/) - Apr 29
* [CNN](https://www.cnn.com/2020/04/28/health/georgia-coronavirus-death-projections/index.html) - Apr 28

Magazines/General News
* [Reason](https://reason.com/2020/09/29/is-the-covid-19-herd-immunity-threshold-as-low-as-15-percent/) - Sep 29
* [IEEE Spectrum](https://spectrum.ieee.org/artificial-intelligence/medical-ai/why-modeling-the-spread-of-covid19-is-so-damn-hard) - Sep 22
* [The Street](https://www.thestreet.com/lifestyle/health/u-s-covid-cases-quickly-approach-6-million) - Aug 30
* [New York Magazine](https://nymag.com/intelligencer/2020/08/the-human-cost-of-the-pandemic-may-dwarf-its-death-toll.html) - Aug 17
* [MIT Technology Review](https://www.technologyreview.com/2020/08/11/1006366/immunity-slowing-down-coronavirus-parts-us/) - Aug 11
* [New York Magazine](https://nymag.com/intelligencer/2020/08/reasons-for-covid-19-optimism-on-t-cells-and-herd-immunity.html) - Aug 9
* [Reason](https://reason.com/2020/07/20/daily-covid-19-deaths-in-the-u-s-continue-to-rise/) - Jul 20
* [Vox](https://www.vox.com/2020/7/15/21317776/covid-19-coronavirus-florida-arizona-texas-california-hospitals) - Jul 16
* [GQ](https://www.gq.com/story/the-slowly-rising-tide-of-covid) - Jun 18
* [IEEE Spectrum](https://spectrum.ieee.org/the-human-os/biomedical/ethics/will-protests-increase-spread-covid19-coronavirus) - Jun 11
* [GeekWire](https://www.geekwire.com/2020/coronavirus-projections-converge-amid-concerns-pandemic-resurgence/) - Jun 9
* [Reason](https://reason.com/2020/05/28/as-lockdowns-are-lifted-is-the-covid-19-reproductive-number-rising-or-falling/) - May 28
* [Bustle](https://www.bustle.com/p/is-it-safe-to-go-to-bars-restaurants-as-coronavirus-restrictions-ease-heres-what-experts-say-22904245) - May 22
* [The Bulwark](https://thebulwark.com/what-winning-the-war-on-covid-19-looks-like/) - May 21
* [Harvard Global Health Institute](https://globalepidemics.org/2020/05/10/modeling-uncertainty-how-to-make-sense-of-changing-predictions/) - May 10
* [Reason](https://reason.com/2020/05/01/covid-19-modeling-how-many-coronavirus-deaths-by-the-end-of-summer/) - May 1

Local
* [The Advocate (NOLA)](https://www.nola.com/news/coronavirus/article_ab2aaae8-f2f8-11ea-9dce-c71905235ea5.html) - Sep 10
* [Washington Examiner](https://www.washingtonexaminer.com/news/the-six-states-at-risk-of-covid-19-surges) - Aug 19
* [Milwaukee Journal Sentinel](https://www.jsonline.com/story/news/2020/08/17/what-wisconsin-covid-19-data-deaths-cases-hospitalizations-means/3301480001/) - Aug 17
* [Miami Herald](https://www.miamiherald.com/news/coronavirus/article244930467.html) - Aug 14
* [The Advocate (NOLA)](https://www.nola.com/news/coronavirus/article_1f5a0286-dbd6-11ea-b428-c3a872847e9b.html) - Aug 11
* [SF Gate](https://www.sfgate.com/news/editorspicks/article/California-coronavirus-COVID-19-herd-immunity-how-15469055.php) - Aug 10
* [The Mercury News](https://www.mercurynews.com/2020/06/25/graph-half-of-californias-coronavirus-deaths-by-oct-1-projected-in-los-angeles-county/) - Jun 25
* [The Advocate (NOLA)](https://www.nola.com/news/coronavirus/article_b4ec117c-b020-11ea-a690-03d2e5a9e00e.html) - Jun 17
* [The Mercury News](https://www.mercurynews.com/2020/05/26/graph-number-of-coronavirus-deaths-projected-in-santa-clara-county-by-sept-1/) - May 26
* [The Mercury News](https://www.mercurynews.com/2020/05/04/california-prediction-artificial-intelligence-driven-model-tracks-coronavirus-infections-deaths/) - May 4
* [Seattle Times](https://www.seattletimes.com/seattle-news/health/a-second-wave-of-coronavirus-infections-could-begin-in-september-uw-model-suggests/) - Jun 11
* [Seattle Times](https://www.seattletimes.com/seattle-news/health/mathematical-models-help-predict-the-trajectory-of-the-coronavirus-outbreak-but-can-they-be-believed/) - May 3
* [Star Tribune](https://www.startribune.com/health-experts-reopening-businesses-in-minnesota-will-spread-covid-19-but-how-much/570443112/) - May 13
* [Boston 25 News](https://www.boston25news.com/news/health/model-shows-key-covid-19-statistic-rising-mass/NKYYFT7KD5F2XL6DFVT4GH4AZY/) - Jun 4
* [Newsday](https://www.newsday.com/news/health/coronavirus/infectious-coronavirus-model-pandemic-1.45185224) - Jun 4
* [Courthouse News](https://www.courthousenews.com/atlanta-businesses-navigate-uncharted-waters-as-georgia-reopens/) - May 6
* [KUOW-FM](https://www.kuow.org/stories/updates-on-the-coronavirus-pandemic-in-washington-state) - May 18
* [Arizona Republic](https://www.azcentral.com/story/news/local/arizona-health/2020/06/09/number-covid-19-going-up-arizona-increased-hospitalization/5328560002/) - Jun 9
* [ABC15 Arizona](https://www.abc15.com/news/state/arizona-sees-21-deaths-reported-in-24-hours) - Apr 21
* [The Center Square](https://www.thecentersquare.com/florida/dueling-models-one-says-florida-s-covid-19-peak-has-passed-another-says-worst-to/article_2037bd12-a12d-11ea-b293-6fe15cef2ecb.html) - May 28

International
* [Huffington Post (France)](https://www.huffingtonpost.fr/entry/la-recrudescence-actuelle-du-covid-19-est-inquietante-mais-peut-etre-jugulee_fr_5f771e38c5b66377b280e82d) - Oct 2
* [El Pais (Spain)](https://elpais.com/politica/2020/10/01/actualidad/1601543892_815336.html) - Oct 2
* [World Journal (Chinese)](https://www.worldjournal.com/wj/story/121468/4889710) - Sep 26
* [El Universal (Mexico)](https://www.eluniversal.com.mx/opinion/carlos-m-urzua/mortandad-estimada-debido-al-coronavirus) - Aug 17
* [La Tercera (Chile)](https://www.latercera.com/la-tercera-pm/noticia/youyang-gu-creador-de-la-plataforma-covid19-projections-creemos-que-el-peak-para-chile-sera-en-los-proximos-30-dias-con-200-a-300-muertes-diarias/JYVJDO5WFZE6LKDODQMSKW2YHY/) - Jun 22
* [CNN Chile](https://www.cnnchile.com/coronavirus/creador-covid19-projections-estima-22-mil-muertes-chile_20200623/) - Jun 23
* [Reforma (Mexico)](https://refor.ma/5T-caimff) - May 28
* [Alto Nivel (Mexico)](https://www.altonivel.com.mx/tecnologia/este-cientifico-del-mit-calcula-cuantos-moriran-por-covid-19-en-eu-y-en-mexico/) - May 21
* [Univision (Mexico)](https://www.univision.com/local/arizona-ktvw/encienden-alarmas-en-arizona-por-incremento-de-contagios-por-coronavirus) - Jun 9
* [Mexico Desconcido](https://www.mexicodesconocido.com.mx/un-cientifico-del-mit-calcula-cuantos-moriran-por-covid-19-en-mexico-y-eu.html) - May 24
* [Paris Match (France)](https://www.parismatch.com/Actu/International/Coronavirus-dans-19-Etats-americains-les-contaminations-augmentent-toujours-1689046) - Jun 10
* [Outlook India](https://www.outlookindia.com/newsscroll/concerned-over-how-quickly-covid19-cases-are-rising-in-india-indianorigin-expert/1872706) - Jun 21

Others
* [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html)
* [FiveThirtyEight](https://projects.fivethirtyeight.com/covid-forecasts/)
* [Our World in Data](https://ourworldindata.org/covid-models)
* [California COVID Assessment Tool](https://calcat.covid19.ca.gov/cacovidmodels/)
* [Wikipedia](https://en.wikipedia.org/wiki/Youyang_Gu_COVID_model)

[Back to Top](#top)

## How to Cite

`Gu, Y. COVID-19 projections using machine learning. https://covid19-projections.com. Accessed <ACCESS_DATE>.`

[Back to Top](#top)

## Updates

2020-10-05
* Final model update

2020-07-22
* We released a major update that tries to better account for increases in cases and deaths from the reopening. See [Update Notes on Twitter](https://twitter.com/youyanggu/status/1286421296474202115)

2020-07-08
* Extended projection end date from October 1 to November 1

2020-06-23
* We have open-sourced the underlying [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator) behind our model

2020-06-16
* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models’ historical point forecasts in a transparent, rigorous, and non-biased manner

2020-06-15
* Switch main data source from Johns Hopkins [Daily Reports](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports) to Johns Hopkins [Time Series Summary](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)

2020-06-11
* Extended projection end date from September 1 to October 1

2020-06-06
* We launched a new [Maps](/maps) page that contains visualizations of our projections for both US states and global countries

2020-05-26
* Add 7 new countries (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), 2 Canadian provinces (Alberta, British Columbia), and 20 US counties

2020-05-25
* Extended projection end date from August 4 to September 1

2020-05-19
* Add 2 Canadian provinces (Ontario, Quebec) and 14 US counties

2020-05-16
* Add plots for the effective reproduction value (R_t) over time. Raw data also available [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).

2020-05-14
* Add hypothetical of how the US would fare if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

2020-05-13
* Add projections that assume no reopening by appending `-noreopen` to the projections URL (e.g. [covid19-projections.com/us-noreopen](/us-noreopen))

2020-05-12
* Add projections for 23 additional countries: Algeria, Argentina, Bangladesh, Chile, Colombia, Dominican Republic, Ecuador, Egypt, Iceland, Israel, Japan, Malaysia, Moldova, Morocco, Nigeria, Pakistan, Panama, Peru, Saudi Arabia, Serbia, South Africa, South Korea, Ukraine

2020-05-06
* Add R0 and post-mitigation R estimates [to GitHub](https://github.com/youyanggu/covid19_projections/tree/master/r_values)

2020-04-30
* Update US states reopening timelines according to the [New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html)

2020-04-28
* Add daily combined projections [to Github](https://github.com/youyanggu/covid19_projections/tree/master/projections/combined)

2020-04-26
* Add plots for R-value estimates for every state and country to Infections Tracker page

2020-04-24
* Forecasts added to the [CDC website](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html)

2020-04-23
* Incorporate probable deaths into projections, following updated [CDC guidelines](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html)

2020-04-20
* First projections submitted to the Centers for Disease Control and Prevention (CDC).

2020-04-15
* Incorporate the relaxing of social distancing in June (see our [Assumptions](/about#assumptions) page)

2020-04-13
* Switch main data source from [COVID Tracking Project](https://covidtracking.com/) to [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports)

2020-04-12
* Add Norway and Russia to projections

2020-04-09
* Add Infections Tracker page that estimates the number of infections in each US state

2020-04-08
* Increase projected end date from June 30 to August 4
* Add plots for the number of infected individuals

2020-04-07
* Add projections for all European Union countries and 7 additional countries: Brazil, Canada, India, Indonesia, Mexico, Philippines, Turkey

2020-04-05
* Launch [covid19-projections.com](https://covid19-projections.com/)
* Add graphs for each state

2020-04-04
* Separate global data from US data

2020-04-03
* Add 9 international countries for projections: Belgium, France, Germany, Iran, Italy, Netherlands, Spain, Switzerland, United Kingdom

2020-04-02
* Add lower and upper bounds to projections; also project date of peak deaths
* Incorporate international data and add projections for Italy

2020-04-01
* Add first projections for the US and individual states

2020-03-30
* Begin project
