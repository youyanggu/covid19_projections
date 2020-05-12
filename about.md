---
layout: default
title: About covid19-projections.com
permalink: /about/
---

## Table of contents
* [About the Model](#about-the-model)
* [How Our Model is Different](#how-our-model-is-different)
* [Concerns with the IHME model](#concerns-with-the-ihme-model)
* [Historical Performance](#historical-performance)
* [Data and Output](#data-and-output)
* [Assumptions](#assumptions)
* [Limitations](#limitations)
* [Historical US Projections](#historical-us-projections)
* [Government/Media Coverage](#online-coverage)
* [Who We Are](#who-we-are)
* [Updates](#updates)

## About the Model

Our COVID-19 prediction model adds the power of artificial intelligence on top of a classic infectious disease model. We developed a simulator based on the [SEIR model](http://leonidzhukov.net/hse/2014/socialnetworks/papers/2000SiamRev.pdf) ([Wikipedia](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SEIR_model)) to simulate the COVID-19 epidemic in each region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. We utilize daily deaths data reported by each region to forecast future reported deaths. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. Here, we use a pure data-driven approach by letting the machine do the learning.

We are currently making projections for: the United States, all 50 US states (plus DC, PR, VI, Guam) and 40 countries (including all 27 EU countries). Combined, these 41 countries account for around 95% of all global COVID-19 deaths, as of May 11.

[Click here](/model-details/) to read a more in-depth description of how our model operates.

[Back to Top](#top)

## How Our Model is Different

Firstly, we are the only model [shared by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that receives no public funding, making us a completely independent entity.

We are also one of the only models shared by the CDC that factors in individual state-by-state or country-by-country reopenings, allowing us to make more realistic projections.

Next, unlike other models that try to create complex mathematical equations to "fit a curve", we try to simulate the disease exactly how they progress in reality: we start off with the entire population in a region, then on each day a certain proportion becomes infected, and those individuals spread the infections to others, and so forth. This makes our model easy to interpret and understand.

As an example, one of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2-2.2, while for New York state, the R<sub>0</sub> is 3.4-3.8. This means that on average, an infected person in New York will infect 3.4 to 3.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf) from China.

To see our estimates of R values for every state and country, see our [Infections Tracker](https://covid19-projections.com/infections-tracker/) page.

We can learn more from the model than just the R<sub>0</sub>. For example, our model determined that the true mortality rate (IFR) for COVID-19 in the United States is [around 1%](https://twitter.com/youyanggu/status/1256051255253757953). This is largely consistent with what [scientists have found](https://www.healthaffairs.org/doi/full/10.1377/hlthaff.2020.00455), despite the fact that the case mortality rate is much higher (e.g. Italy is at 13-14%). The model can also determine when people in a region started social distancing. For New York, this inflection point is determined to be around March 14, which closely matches the [NYC subway ridership data](https://twitter.com/youyanggu/status/1248844841733128192).

We have a strong validation system to make sure that all of our updates pass out-of-sample validation before they can be included in the model. This allows us to better differentiate the signal from the noise and be more resistant to outliers. Because all of our assumptions and projections are verified on all 50 states as well as 40 countries, we are able to create more robust projections.

Our model is agnostic to the region, enabling us to make projections for all 50 US states (plus DC, PR, VI, Guam) and 40 countries. To our best knowledge, this is the most comprehensive model in terms of coverage. Furthermore, unlike other models, we do not require accessory data such as mobile phone data, case data, or temperature data. The only input data we require is the daily death reports from Johns Hopkins.

See an [analysis of our model](https://twitter.com/CT_Bergstrom/status/1255343846445195266) by Dr. Carl T. Bergstrom, Professor of Biology at the Univeristy of Washington. 

Another strength of our model is that because it is purely data-driven, it is quick to run and easy to regenerate. Unlike other models that are only updated once every few days, our model is updated on a daily basis, leading to more accurate projections.

[Back to Top](#top)

## Concerns with the IHME model

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House and media. We compare our projections (C19Pro) with IHME below for US, New York, Michigan, New Jersey, California and Italy, some of the most heavily impacted regions.

{% include iframe_ny_comparison.html %}

As you can see from the plots above, IHME's projections failed to accurately capture the true trajectory for these regions. Our projections, meanwhile, have been significantly more accurate. Below, we will go into further details as to why IHME is a flawed model.

There are existing news articles such as [Vox](https://www.vox.com/future-perfect/2020/5/2/21241261/coronavirus-modeling-us-deaths-ihme-pandemic), [STAT News](https://www.statnews.com/2020/04/17/influential-covid-19-model-uses-flawed-methods-shouldnt-guide-policies-critics-say/), [CNN](https://www.cnn.com/2020/04/13/health/ihme-model-death-predictions/index.html), and [Quartz](https://qz.com/1840186/what-the-ihme-covid-19-model-can-and-cant-tell-the-us/) that agree with our concerns.

In the words of Ruth Etzioni, an epidemiologist at Seattle’s Fred Hutchinson Cancer Research Center, “that \[the IHME model\] is being used for policy decisions and its results interpreted wrongly is a travesty unfolding before our eyes.”

[Back to Top](#top)

### Sample Summary of IHME Inaccurate Predictions

In their April 15 model, the death toll that IHME projected will take *four months* to reach was in fact exceeded in *six days*:

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

As of April 11, IHME projects 225 (0 - 1,180) deaths in the US from June 1 to August 4. While we hope the US only has 225 total deaths from June to August (an average of 3 deaths per day), we believe this is an underestimate. The upper range of 1,180 (18 deaths per day) also appears to be an under-projection *for an upper range*.

### Update time

New data is extremely important when making projections such as these. That's why we update our model daily based on the new data we receive. Projections using today's data is much more valuable than projections from 2-3 days ago. However, due to certain constraints, IHME is only able to update their model 1-2 times a week: *"Our ambition to produce daily updates has proven to be unrealistic given the relative size of our team and the effort required to fully process, review, and vet large amounts of data alongside implementing model updates."* 

### Mobility Data

On [April 17](http://www.healthdata.org/news-release/ihme-hold-media-briefing-4-pm-eastern-today-details-below), IHME stated that they are incorporating new cell phone mobility data which indicate that people have been properly practicing social distancing: *"These data suggest that mobility and presumably social contact have declined in certain states earlier than the organization’s modeling predicted, especially in the South."* As a result, IHME lowered their projections from 68k deaths to 60k deaths by August. Their critical flaw is that they assume a linear relationship between lower mobility and lower infection - this is not the case.

Most transmissions do not happen with strangers, but rather close contacts. Even if you reduce your mobility by 90%, you do not reduce your transmission by 90%. The data from Italy shows that it only reduces by around 60%. That's the difference between 20k and 40k+ deaths. IHME was likely making the wrong assumption that a 90% reduction in mobility will decrease transmission by 90%. [Here](https://twitter.com/mugecevik/status/1257392347010215947) is a compilation from infectious disease expert Dr. Muge Cevik showing that household contacts were the most likely to be infected.

We posted [a Tweet](https://twitter.com/youyanggu/status/1248844841733128192) on April 11 about MTA (NYC) and BART (Bay Area) subway ridership being down 90% in March. However, the deaths have only dropped around 25% in NY, while CA has yet to see sharp decrease in deaths in April, more than a month after the drop in ridership.

Interestingly, after IHME suddenly revised their projections from 72k to 130k on May 4, the director of IHME offered this explanation for why they raised their estimates: *"...we're seeing just explosive increases in mobility in a number of states that we expect will translate into more cases and deaths."* This is directly contradictory to their press release just 2 weeks earlier stating that mobility has been lower than predicted. Any 2-week differences in mobility should not explain this sudden jump in projections - only a flawed methodology would.

### State Reopening Timeline

In their [April 17](http://www.healthdata.org/sites/default/files/files/Projects/COVID/Estimation_update_041720.pdf) press release, IHME released estimates of when they believe each state will have a prevalence of fewer than 1 case per 1 million. They noted that 35 states will reach under 1 prevalent infection per 1 million before June 8, and that *"states such as Louisiana, Michigan, and Washington, may fall below the 1 prevalent infection per 1,000,000 threshold around mid-May."*

As of May 11, Louisiana, Michigan, and Washington are reporting 30-80 confirmed cases per million *each day*. Furthermore, prevalent infections are 5-15x higher than reported cases since most cases are mild and thus not tested/reported. As a result, we estimate [Louisiana](/us-la) and [Michigan](/us-mi) to have around 7,000 prevalent infections per million, which is 7,000 times higher than IHME's April 17 estimates. An analysis for many of the remaining states show a similar high degree of error. Hence, IHME's estimates have been off by a factor of more than *3 orders of magnitude*.

Unfortunately, it is likely that many individuals and policy-makers used IHME's misguided reopening timelines to shape decisions with regards to reopening. Their reopening timelines were picked up and widely disseminated by [many media outlets](http://www.google.com/search?q=ihme+reopening+timeline), both local and national. Any policies guided by these estimates can have repercussions weeks and months down the road.

### Technical Flaw

*May 4 Update: IHME completely overhauled their previous model to now use an SEIR model. Our model is based in SEIR and that has not changed since we first began making projections on April 1.*

On top of everything we mentioned above, their model is also inherently flawed from a mathematical perspective. They try to model COVID-19 infections using a [Gaussian error function](https://en.wikipedia.org/wiki/Error_function). The problem is that the Gaussian error function is by design *symmetric*, meaning that the curve comes down from the peak at the same rate as it goes up. Unfortunately, this has not been the case for COVID-19: we come down from the peak at a much slower pace. This leads to a significant under-projection in IHME's model, which we have thoroughly highlighted. University of Washington biology professor Dr. Carl T. Bergostrom discussed this in more detail in this highly informative [series of Tweets](https://twitter.com/CT_Bergstrom/status/1250304069119275009).

### May 4 update

On May 4, IHME completely overhauled their previous model and increased their projections from 72k to 132k US deaths by August. Whereas they were previously underprojecting, they are now overprojecting the first two weeks of May.

[Click here](#historical-us-projections) to see how our projections have changed over time, compared with the IHME model. For a comparison of April projections for several heavily-impacted states and countries, [click here](/model-comparison-ihme).

To conclude, we believe that a successful model must be able to quickly determine what is realistic and what is not, and the above examples highlights our main concerns with the IHME model.

[Back to Top](#top)

## Historical Performance

A model isn't very useful if it's not accurate. Below is our analysis on how various models considered by the CDC have performed over the past few weeks. Because the CDC receives weekly projections from every Monday, we use projections from past Mondays to evaluate the models.

Note that the IHME model, a model frequently cited by the White House and media, consistently performs in the bottom half of all models for both its US projections and state-by-state projections. Furthermore, many models are unable to consistently outperform a baseline model that simply uses the previous week's average deaths to make future projections.

[Click here](/historical-performance) to see performance evaluations for past dates (e.g. May 2).

### May 9 evaluation of US projections

![US comparison](/assets/images/2020-05-09_comparison_us.png)

### May 9 evaluation state-by-state projections

![States comparison](/assets/images/2020-05-09_comparison_states.png)

For state-by-state projections, we priortize minimizing the mean error rather than the median error, which is reflected in the results. If our objective is to minimize median error, it would be optimal to simply use the prior week's projections, as indicated by the strong performance of the baseline model.

While past performance is not necessarily indicative of future performance, we believe it's important to consider a model's historical accuracy and not just a model's future forecasts and/or the creator's name recognition. It is also important to make sure that a model can perform better than the baseline.

Projections taken from: [https://github.com/reichlab/covid19-forecast-hub](https://github.com/reichlab/covid19-forecast-hub)

Truth data from Johns Hopkins: [https://github.com/CSSEGISandData/COVID-19](https://github.com/CSSEGISandData/COVID-19)

[Back to Top](#top)

## Data and Output

To make our projections, we use the daily death total provided by [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports), what is considered by experts to be the "gold standard" reference data. We do not use case-related data in our modeling due to reasoning alluded to [here](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/).

Every day, raw daily projections for all 50 US states and select international countries will be uploaded onto our [GitHub page](https://github.com/youyanggu/covid19_projections/tree/master/projections). We are projecting future deaths as reported by Johns Hopkins CSSE. For the US, this includes both **confirmed and probable deaths**.

[Back to Top](#top)

## Assumptions

### Social Distancing

* US states: We assume heavy social distancing until the reopening date and moderate social distancing afterwards. We use the reopening date as outlined by [the New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). For states with a staggered reopening, we use the date for which restaurants are allowed to reopen. For states where there is no concrete reopening date (states highlighted in yellow on the NYT map), we assume a reopening date of June 1. Reopening will likely cause a second wave of infections in states where the outbreak has not yet been fully contained.

* European countries: We assume heavy social distancing until mid-May and moderate social distancing afterwards.

* Non-US and Non-European countries: Because it is difficult to track when each country plans to reopen, we assume heavy social distancing through August.

#### Heavy vs moderate social distancing

Heavy social distancing is what we have now in many states and countries: stay-at-home orders, closed non-essential businesses, etc. Infection rates typically decrease ~60%, going from an R<sub>0</sub> of around 2 to an R of 0.6-1.0. As long as R, a measure of how many people an infected person infects on average, is less than 1, infections will decrease over time. If R is greater than 1, then the infection curve will rise. Hence, the ultimate goal is to keep R under 1.

Moderate social distancing is what we assume will happen once states and countries gradually begin relaxing their social distancing guidelines. Some establishments will reopen, but people will still be somewhat cognizant about maintaining social distancing. Most states and countries will have guidelines that aim to maximize social distancing and minimize close contact, such as enforcing capacity limits and recommending mask-wearing. We assume that infection rates will increase 0-20%, resulting in an R of around 0.8-1.2. Note that this is still a lower infection rate than what it was prior to the outbreak for most regions.

If regions impose stricter social distancing guidelines than our assumptions listed above, then we will likely see a lower infections and death rate than the current projections. Conversely, if regions impose looser guidelines, then we will likely see a higher infections and death rate. For example, if California reopens before June 1, there will be an increased chance of an earlier resurgence. Or if a state required all residents to wear masks, the likelihood of a steep increase in infections will decrease, according to some recent studies ([[1]](https://www.nature.com/articles/s41591-020-0843-2), [[2]](https://www.preprints.org/manuscript/202004.0203/v1), [[3]](https://www.sciencetimes.com/articles/25410/20200421/austria-90-drop-coronavirus-cases-requiring-people-wear-face-masks.htm)).

#### Second wave

In regions where the outbreak has not yet been fully contained, it is possible that reopening will cause a second wave of infections if states fail to maintain sufficient social distancing.

#### Second lockdown

We assume that states with a second outbreak will take actions to reduce transmission, such as increased contact tracing, mandatory mask wearing, improved treatment, etc. In the case where the infections curve continue to rise exponentially after a reopening, it may become necessary for regions to impose a second lockdown. A second lockdown was seen in numerous Asian countries where a second wave occurred, including in [Japan](https://time.com/5826918/hokkaido-coronavirus-lockdown/), [Hong Kong](https://fortune.com/2020/04/21/hong-kong-coronavirus-second-wave-response/), and [Singapore](https://www.usnews.com/news/world-report/articles/2020-04-24/singapore-sees-second-wave-of-coronavirus-with-900-new-cases). Our model incorporates the concept of a second lockdown, which we estimate will happen approximately 30 days after the reopening. A second lockdown is only necessary if the effective reproductive number (R) is greater than 1.

### Infections Estimate

The current and total infections estimates in our projections are at the core of our SEIR model. We use those estimates to make forecasts regarding future deaths according to the specifications of the SEIR model. The total infections estimate includes **all** individuals who have ever been infected by the virus, including asymptomatic individuals as well as those who were never tested. The current infections estimate is based on how many people are currently infected at that time point (total - recovered). To compute current infections, we assume that individuals are infected for an average of 15 days. We estimate that the true number of total infections is likely 5-15x higher than reported cases for most regions.

### Infection Fatality Rate (IFR)

We estimate that true mortality rate (IFR) for COVID-19 in the US is [around 1%](https://twitter.com/youyanggu/status/1256051255253757953). We also found that with the exception of United Kingdom, Sweden, and Spain, most countries in Europe have an IFR closer to 0.5%. Hence, in our projections, we use 0.5% for those European countries and 1% for all other countries.

[Back to Top](#top)

## Limitations

We want to be as clear as possible regarding what our model can and cannot do. While we try our best to make accurate projections, no model is perfect. The future is not set in stone: a single policy change or a small change in the assumptions can cause a large impact in how the epidemic progresses. 

That's why in addition to our most likely estimate, we also provide a 95% confidence interval to reflect this uncertainty. For example, if we predict 150,760 deaths with a range of 88-294k, it means that there is roughly a 95% chance that the true deaths will be between 88-294k. Note that these confidence intervals are generated given that our above assumptions hold true. There are many real-world variables that can cause our assumptions to be inaccurate and affect the true outcome. We will try our best to address any inaccurate assumptions as time goes on.

*We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a most likely outcome. If the true results fall within the range, that is within the expected outcome of this model. We highly recommend that you include our range when referencing our projections (i.e. 21,342 (15-34k) deaths).*

### Additional limitations

* Day-of-week factors: We currently do not account for day-of-week factors in death reporting. According to [our analysis](https://twitter.com/youyanggu/status/1251779534422073344), deaths reported on Sunday/Monday are about 60% of that of Tuesday-Thursday. So we expect on average that our projections will be higher than Sunday/Monday reports and lower than our Tuesday-Thursday reports. 

* Confidence intervals: Due to the aforementioned day-of-week factors and various reporting noises (e.g. states sometimes report 0 on one day and make up for it on the next day), we recommend smoothing daily reported deaths before comparing them to our daily confidence intervals.

* Data frequency: Because our model uses only the daily death totals from each region to make projections, it will be more effective for regions where there are more available deaths data (such as New York) than regions where there are only a few reported deaths (such as Wyoming).

* Seasonality: We currently do not explicitly factor in seasonality changes. A [May 8 study](https://www.cmaj.ca/content/cmaj/early/2020/05/08/cmaj.200920.full.pdf) of 144 geopolitical areas finds no significant correlation between temperature transmission. However, if seasonality effects are reflected in the data, we will implicitly factor it in. It is possible that the effects of warmer temperatures may be partially offset by lockdown fatigue.

* Lockdown fatigue: As shown in various mobility data and [our analysis](https://twitter.com/youyanggu/status/1255034262006333440) of the NYC subway data, an increasingly number of people have been moving around in the weeks following a lockdown. This may contribute to an increase in infections in the weeks following the lockdown/mitigation.

* Reporting differences: Different countries follow different guidelines on how they are reporting COVID-19 deaths. For example, Belgium is one of the most comprehensive countries when it comes to death reporting: they report all probable deaths as well as nursing home deaths. In contrast, United Kingdom only began including care home deaths starting on April 29, having only reported hospital deaths previously. Because we are projecting future reported deaths, our model assumes that the reporting guidelines remains constant for each country.

* Excess deaths: While we attempt to predict the official death total, the true death total will be higher due to underreporting at various levels. [The New York Times](https://www.nytimes.com/interactive/2020/04/21/world/coronavirus-missing-deaths.html) and [Financial Times](https://www.ft.com/content/6bd88b7d-3386-4543-b2e9-0d5c6fac846c) are currently tracking these excess deaths.

* End date: We are only making projections for 10-18 weeks ahead, but this does not mean that the epidemic will stop afterwards. Deaths will continue to rise even after we stop making projections. We are also currently not factoring in a fall wave, which was the [most deadly wave](https://www.cdc.gov/flu/pandemic-resources/1918-commemoration/three-waves.htm) in the 1918 Flu Pandemic.

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

[Back to Top](#top)

## Historical US Projections

Below, we show how our (C19Pro) August 4 projections for the US has changed over time, compared to IHME. We also show a comparison of the latest projections.

Note that for the entire month of April, IHME projected between 60,000-73,000 deaths by August, all while deaths increased by an average of 2,000 per day. All of their August projections from April were surpassed by May 6.

Also note that while we update our projections daily, IHME only updates their projections once or twice a week.

{% include iframe_historical.html %}

[Back to Top](#top)

## Online Coverage

### Government

* [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html)
* [Washington State COVID-19 Dashboard](https://coronavirus.wa.gov/what-you-need-know/covid-19-risk-assessment-dashboard)

### Media

* [CNN](https://www.cnn.com/2020/05/05/health/states-early-reopening-impact/index.html) - May 5
* [StatNews](https://www.statnews.com/2020/04/30/coronavirus-death-projections-compare-causes-of-death) - Apr 30
* [MarketWatch](https://www.marketwatch.com/story/will-some-people-be-affected-badly-yes-trump-says-us-must-reopen-coronavirus-deaths-projected-to-hit-100000-in-weeks-2020-05-06) - May 6
* [CNN](https://www.cnn.com/2020/04/28/health/georgia-coronavirus-death-projections/index.html) - Apr 28
* [TheHill](https://thehill.com/changing-america/well-being/prevention-cures/495459-reopening-georgia-could-lead-to-a-doubling-of) - Apr 30
* [The Mercury News](https://www.mercurynews.com/2020/05/04/california-prediction-artificial-intelligence-driven-model-tracks-coronavirus-infections-deaths/) - May 4
* [New York Times](https://www.nytimes.com/2020/05/05/us/coronavirus-deaths-cases-united-states.html) - May 5
* [NPR](https://www.npr.org/sections/health-shots/2020/05/07/851610771/u-s-coronavirus-testing-still-falls-short-hows-your-state-doing) - May 7
* [USA Today](https://www.usatoday.com/story/news/nation/2020/05/01/coronavirus-us-may-hit-10000-deaths-record-cases-may/3062216001/) - May 1
* [New York Post](https://nypost.com/2020/04/29/georgia-coronavirus-death-rate-could-double-as-lockdown-eases/) - Apr 29
* [Reason](https://reason.com/2020/05/01/covid-19-modeling-how-many-coronavirus-deaths-by-the-end-of-summer/) - May 1
* [Courthouse News](https://www.courthousenews.com/atlanta-businesses-navigate-uncharted-waters-as-georgia-reopens/) - May 6
* [ABC15 Arizona](https://www.abc15.com/news/state/arizona-sees-21-deaths-reported-in-24-hours) - April 21

[Back to Top](#top)

## Who We Are

*covid19-projections.com* is made by Youyang Gu, an independent data scientist. Youyang completed his Bachelor's degree at the Massachusetts Institute of Technology (MIT), double majoring in Electrical Engineering & Computer Science and Mathematics. He also received his Masters degree at MIT, completing his thesis as part of the [Natural Language Processing group](http://nlp.csail.mit.edu/) at the [MIT Computer Science & Artificial Intelligence Laboratory](https://www.csail.mit.edu/). His expertise is in using machine learning to understand data and make accurate predictions. You can contact him [on Twitter](https://twitter.com/youyanggu) or by using the [Contact](/contact) page.

[Back to Top](#top)

## Updates

2020-05-06
* Add R-value estimates [to Github](https://github.com/youyanggu/covid19_projections/tree/master/r_values)

2020-04-30
* Update US states reopening timelines according to the [New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html)

2020-04-28
* Add daily combined projections [to Github](https://github.com/youyanggu/covid19_projections/tree/master/projections/combined)

2020-04-24
* Forecasts added to the [CDC website](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html)

2020-04-23
* Incorporate probable deaths into projections, following updated [CDC guidelines](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html)

2020-04-15
* Incorporate the relaxing of social distancing in June (see our [Assumptions](/about#assumptions) page)

2020-04-13
* Switch data source to [JHU CSSE Daily Reports](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports)

2020-04-12
* Add Norway and Russia to projections

2020-04-09
* Add Infections Tracker page that estimates the number of infections in each US state

2020-04-08
* Add estimate for the number of infected individuals

2020-04-07
* Add projections for all European Union countries and 10 non-European Union countries

2020-04-05
* Launch [covid19-projections.com](https://covid19-projections.com/)
* Add graphs for each state

2020-04-04
* Separate global data from US data

2020-04-03
* Add 9 international countries for projections

2020-04-02
* Add lower and upper bounds to projections; also project date of peak deaths
* Incorporate international data and add projections for Italy

2020-04-01
* Incorporate US states data and add projections for every state

2020-03-31
* Add first projections for New York and California

2020-03-30
* Begin project
