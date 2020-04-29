---
layout: default
title: COVID-19 Projections Using Machine Learning
permalink: /about/
---

## Table of contents
* [About the model](#about-the-model)
* [How our model is different](#how-our-model-is-different)
* [Concerns with the IHME model](#concerns-with-the-ihme-model)
* [Data and Output](#data-and-output)
* [Contact](#contact)
* [Assumptions](#assumptions)
* [Limitations](#limitations)
* [Model Comparison with IHME](#model-comparison-with-ihme)
* [Updates](#updates)

## Projections

To view our projections, visit our [home page](/).

## About the model

Our COVID-19 prediction model adds the power of artificial intelligence on top of a classic infectious disease model. We developed a simulator based on the [SEIR/SEIS model](http://leonidzhukov.net/hse/2014/socialnetworks/papers/2000SiamRev.pdf) ([Wikipedia](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SEIS_model)) to simulate the COVID-19 epidemic in each given country/state/region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. We utilize daily deaths data reported by each state/country to forecast future deaths. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. Here, we use a pure data-driven approach by letting the machine do the learning.

[Click here](/model-details/) to read a more in-depth description of how our model operates.

## How our model is different

Firstly, we are the only model [shared by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that receives no public funding, making us a completely independent entity.

We are also the only model shared by the CDC that factors in individual state-by-state or country-by-country re-openings, allowing us to make more realistic projections. See an [analysis of our model](https://twitter.com/CT_Bergstrom/status/1255343846445195266) by Dr. Carl T. Bergstrom, Professor of Biology at the Univeristy of Washington. 

Next, unlike other models that try to create complex mathematical equations to "fit a curve" without an intuitive explanation as to why it works, we try to simulate what is happening in the real world. We model the disease exactly how they progress in reality: we start off with the entire population in a region, then a certain proportion gets infected, and those individuals spread the infections to others, and so forth. This makes our model easy to interpret and understand.

As an example, one of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2-2.2, while for New York state, the R<sub>0</sub> is 3.4-3.8. This means that on average, an infected person in New York will infect 3.4 to 3.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf) from China.

To see our estimates of R values for every state and country, see our [Infections Tracker](https://covid19-projections.com/infections-tracker/) page.

We can learn more from the model than just the R<sub>0</sub>. For example, our model determined that the true mortality rate for COVID-19 in most regions in the world is less than 1%. This is again consistent with what scientists have found, despite the fact that the official mortality rate is much higher (e.g. Italy is at 13-14%). The model can also determine when people in a region started social-distancing. For New York, this inflection point is determined to be on March 13-14, which closely matches the [NYC subway ridership data](https://twitter.com/youyanggu/status/1248844841733128192).

We have a strong validation system to make sure that all of our updates pass out-of-sample validation before they can be included in the model. This allows us to better differentiate the signal from the noise and be more resistant to outliers.

Another strength of our model is that because it is purely data-driven, it is quick to run and easy to regenerate. Unlike other models that are only updated once every few days, our model is updated on a daily basis, leading to more accurate projections.

[Back to Top](#top)

## Concerns with the IHME model

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House and media. We compare our projections (C19Pro) with IHME below for New York, Michigan, New Jersey, and Italy, four of the most heavily-impacted regions.

{% include iframe_ny_comparison.html %}

As you can see from the plots above, IHME's projections failed to accurately capture the true trajectory for these regions. Our projections, meanwhile, have been significantly more accurate. Below, we will go into further details as to why IHME is a flawed model.

There are existing news articles such as [STAT News](https://www.statnews.com/2020/04/17/influential-covid-19-model-uses-flawed-methods-shouldnt-guide-policies-critics-say/), [CNN](https://www.cnn.com/2020/04/13/health/ihme-model-death-predictions/index.html), and [Quartz](https://qz.com/1840186/what-the-ihme-covid-19-model-can-and-cant-tell-the-us/) that agree with our concerns.

In the words of Ruth Etzioni, an epidemiologist at Seattle’s Fred Hutchinson Cancer Research Center, “that \[the IHME model\] is being used for policy decisions and its results interpreted wrongly is a travesty unfolding before our eyes.”

In essence, their model is based on fitting a mathethetical curve with no basis in epidemiology or disease modeling. As a result, some of their projections do not pass what we call the "common sense test". Below are a few more examples.

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

As you can see above, their models made misguided projections for almost all of the worst-impacted regions in the world. The most alarming thing is that they continue to make low projections. Below is their projections from April 21. It doesn't take an expert to recognize that most of these IHME projections will also be exceeded in less than 2 weeks:

|  | April 26 Total Deaths | IHME Aug proj. deaths from Apr 21 | Our Aug proj. deaths from Apr 21
| --- | --- | --- | --- |
| New York | 22,668 | 23,741 | 35,238
| New Jersey | 6,044 | 7,116 | 13,651
| Michigan | 3,407 | 3,361 | 6,798
| Illinois | 1,983 | 2,093 | 6,653
| Italy | 26,977 | 26,600 | 44,683
| Spain | 23,521 | 24,624 | 31,854
| France | 23,327 | 23,104 | 41,643

As scientists, we update our models as new data becomes available. Models are going to make wrong predictions, but it's important that we correct them as soon as new data shows otherwise. The problem with IHME is that they refuse to recognize their wrong assumptions. Hence, they are perpetually making the same mistake over and over again: under-projecting.

[Back to Top](#top)

### US June-August

As of April 11, IHME projects 225 (0 - 1,180) deaths in the US from June 1 to August 4. While we hope the US only has 225 total deaths from June to August (an average of 3 deaths per day), we believe this is an underestimate. The upper range of 1,180 (18 deaths per day) also appears to be an under-projection *for an upper range*. [Click here](#model-comparison-with-ihme) for our most recent estimates for June - August.

### Update time

New data is extremely important when making projections such as these. That's why we update our model daily based on the new data we receive. Projections using today's data is much more valuable than projections from 2-3 days ago. However, due to certain constraints, IHME is only able to update their model 1-3 times a week: *"Our ambition to produce daily updates has proven to be unrealistic given the relative size of our team and the effort required to fully process, review, and vet large amounts of data alongside implementing model updates."* 

### Mobility Data

On April 17, IHME stated that they have new [cell phone data](http://www.healthdata.org/covid/updates) which indicated that people are properly social distancing. As a result, IHME lowered their projections from 68k deaths to 60k deaths by August. But their critical flaw is that they assume a linear relationship between lower mobility and lower infection - this is not the case.

Most transmissions do not happen with strangers, but rather close contacts. Even if you reduce your mobility by 90%, you do not reduce your transmission by 90%. The data from Italy shows that it only reduces by around 60%. That's the difference between 20k and 40k+ deaths. IHME is likely making the wrong assumption that a 90% reduction in mobility will decrease transmission by 90%.

We posted [a Tweet](https://twitter.com/youyanggu/status/1248844841733128192) on April 11 about MTA (NYC) and BART (Bay Area) subway ridership being down 90% in March. However, the deaths have only dropped around 25% in NY, while CA has yet to see sharp decrease in deaths in April, more than a month after the drop in ridership.

### Mathematical Flaw

On top of everything we mentioned above, their model is also inherently flawed from a mathematical perspective. They try to model COVID-19 infections using a [Gaussian error function](https://en.wikipedia.org/wiki/Error_function). The problem is that the Gaussian error function is by design *symmetric*, meaning that the curve comes down from the peak at the same rate as it goes up. Unfortunately, this has not been the case for COVID-19: we come down from the peak at a much slower pace. This leads to a significant under-projection in IHME's model, which we have thoroughly highlighted. University of Washington biology professor Dr. Carl T. Bergostrom discussed this in more detail in this highly informative [series of Tweets](https://twitter.com/CT_Bergstrom/status/1250304069119275009).

To conclude, we believe that a successful model must be able to quickly determine what is realistic and what is not, and the above examples highlights our main concerns with the IHME model.

[Back to Top](#top)

## Data and Output

To make our projections, we use the daily death total provided by [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports), what is considered by experts to be the "gold standard" reference data. We do not use case-related data in our modeling due to reasonings alluded to [here](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/).

Every day, raw daily projections for all 50 US states and select international countries will be uploaded onto our [GitHub page](https://github.com/youyanggu/covid19_projections/tree/master/projections). We are projecting future deaths as reported by Johns Hopkins CSSE. For the US, this includes both **confirmed and probable deaths**

Because the model factors in new data on a daily basis, it will be more accurate over time as more data becomes available. We are currently in the process of submitting our findings for publication, but due to the current circumstances we are prioritizing the public release of our research.

## Contact

We enourage questions/insights/feedback! Please reach out to Youyang Gu on Twitter via [@youyanggu](https://twitter.com/youyanggu) or [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

[Back to Top](#top)

## Assumptions

For US and European countries, we assume heavy social distancing until June 1, 2020 and moderate social distancing from June 1 onwards. This more accurately reflects the current sentiment expressed by US and European government officials that it is imperative to re-open the economy, even before the virus is fully contained. This will likely cause a second wave of infections and is reflected by the higher death tolls in our June-August projections.

*Note: For Georgia, we use May 1 instead of June 1 to reflect the governor's intention of an early re-opening of the state.*

#### Heavy vs moderate social distancing

Heavy social distancing is what we have now in many states and countries: stay-at-home orders, closed non-essential businesses, etc. Infection rates typically decrease ~60%, going from an R<sub>0</sub> of around 2 to a R of 0.6-1.0. Moderate social distancing is what we think will happen once states gradually begin opening up. Some establishments will re-open, but people will still be somewhat cognizant about maintaining social distancing. We assume that infection rates will increase 0-20%, with an R of around 0.8-1.2. Note that this still assumes a much lower infection rate than what it was pre-COVID.

If states fail to maintain moderate social distancing during their re-openings, we think the infection rate can become much steeper in June-August than we are currently projecting.

We also take into account that a certain percentage of recovered individuals will be immune, and thus the susceptible population will decrease over time.

If states and countries relax social distancing measures prior to June 1, then the death toll may be higher than projected, while the reverse holds true as well. In addition, if states and countries fully lift social distancing measures prior to August, we may also see a higher death toll than projected.

For non-US and non-European countries, we assume continued social distancing until August 2020.

[Back to Top](#top)

## Limitations

We want to be as clear as possible regarding what our model can and cannot do. While we try our best to make accurate projections, no model is perfect. The future is not set in stone: a single policy change or a small change in the assumptions can cause a large impact in how the epidemic progresses. 

That's why in addition to our most likely estimate, we also provide a 95% confidence interval to reflect this uncertainty. For example, if we predict 150,760 deaths with a range of 88-294k, it means that there is roughly a 95% chance that the true deaths will be between 88-294k. There are too many real-world variables that can affect the outcome, which results in this large range.

*We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a most likely outcome. If the true results fall within the range, that is within the expected outcome of this model. We highly recommend that you include our range when referencing our projections (i.e. 21,342 (15-34k) deaths).*

Because our model uses only the daily death totals from each region to make projections, it will be more effective for regions where there more available data.

We currently do not factor in seasonality changes, as there has not been sufficient data/research into this area.

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

Also note that while we attempt to predict the *official* death total, the true death total may be higher due to underreporting at various levels. The New York Times is currently tracking these [excess deaths](https://www.nytimes.com/interactive/2020/04/21/world/coronavirus-missing-deaths.html).

[Back to Top](#top)

## Model Comparison with IHME

Click [here](/model-comparison-ihme) to see how our projections have changed over time, compared with the IHME model.

## Updates

2020-04-28
* Model referenced [on CNN](https://www.cnn.com/2020/04/28/health/georgia-coronavirus-death-projections/index.html)

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
* Add projections for all EU countries and 10 non-EU countries

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
* Add first projections for NY and CA

2020-03-30
* Begin project
