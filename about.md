---
layout: default
title: About
permalink: /about/
---

## Table of contents
* [About the model](#about-the-model)
* [How our model is different](#how-our-model-is-different)
* [Concerns with the IHME model](#concerns-with-the-ihme-model)
* [Data](#data)
* [Contact](#contact)
* [Assumptions](#assumptions)
* [Model Comparison with IHME](#model-comparison-with-ihme)
* [Updates](#updates)

## About the model

Our COVID-19 prediction model adds the power of artificial intelligence on top of a classic infectious disease model. We developed a simulator based on the [SEIS model](http://leonidzhukov.net/hse/2014/socialnetworks/papers/2000SiamRev.pdf) ([Wiki](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SEIS_model)) to simulate the COVID-19 epidemic in each given country/state/region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputsand the actual results. We utilize daily deaths data reported by each state/country to forecast future deaths. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. Here, we use a pure data-driven approach by letting the machine do the learning.

[Click here](/model-details/) to read a more in-depth description of how our model operates.

## How our model is different

Unlike many models that try to create complex mathematical equations to "fit a curve" without an intuitive explanation as to why it works, we try to simulate what is happening in the real world. This makes our model easy to interpret and understand.

As an example, one of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2-2.2, while for New York state, the R<sub>0</sub> is 3.6-3.8. This means that on average, an infected person in New York will infect 3.6 to 3.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf) from China.

We can learn more from the model than just the R<sub>0</sub>. For example, our model determined that the true mortality rate for COVID-19 in most regions in the world is less than 1%. This is again consistent with what scientists have found, despite the fact that the official mortality rate is much higher (e.g. Italy is at 13%). The model can also determine when people in a region started social-distancing. For New York, this inflection point is determined to be on March 13-14, which closely matches the [NYC subway ridership data](https://twitter.com/youyanggu/status/1248844841733128192).

We have a strong validation system to make sure that all of our updates pass out-of-sample validation before they can be included in the model. This allows us to better differentiate the signal from the noise and be more resistant to outliers.

Another strength of our model is that because it is purely data-driven, it is quick to run and easy to regenerate. No daily tuning needs to be done - it just needs the raw data. Unlike other models that can only be updated once every few days, our entire model takes 10 minutes to generate and is updated on a daily basis, leading to more accurate projections.

[Back to Top](#top)

## Concerns with the IHME model

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House and media.

Unfortunately, the IHME model is deeply flawed. There are existing news articles such as [STAT News](https://www.statnews.com/2020/04/17/influential-covid-19-model-uses-flawed-methods-shouldnt-guide-policies-critics-say/), [CNN](https://www.cnn.com/2020/04/13/health/ihme-model-death-predictions/index.html), and [Quartz](https://qz.com/1840186/what-the-ihme-covid-19-model-can-and-cant-tell-the-us/) that agree with our concerns.

In the words of Ruth Etzioni, an epidemiologist at Seattle’s Fred Hutchinson Cancer Research Center, “that \[the IHME model\] is being used for policy decisions and its results interpreted wrongly is a travesty unfolding before our eyes.”

In essence, their model is based on fitting a mathethetical curve with no basis in epidemiology or disease modeling. As a result, some of their projections do not pass what we call the "common sense test". Below are a few examples.

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

As you can see above, their models made incredibly misguided projections for almost all of the worst-impacted regions in the world. The most alarming thing is that they continue to make low projections. Below is their projections from April 21. It doesn't take a scientist to recognize that most of these IHME projections will also be exceeded in less than 2 weeks:

|  | April 21 Total Deaths | IHME Aug proj. deaths from Apr 21 | Our Aug proj. deaths from Apr 21
| --- | --- | --- | --- |
| New York | 19,104 | 23,741 |35,238
| New Jersey | 4,753 | 7,116 | 13,651
| Michigan | 2,575 | 3,361 | 6,798
| Illinois | 1,468 | 2,093 | 6,653
| Italy | 24,648 | 26,600 | 44,683
| Spain | 21,282 | 24,624 | 31,854
| France | 20,829 | 23,104 | 41,643

As scientists, we update our models as new data becomes available. Model are going to make wrong predictions, but it's important that we correct them as soon as new data shows otherwise. The problem with IHME is that they refuse to recognize their wrong assumptions. Hence, they are perpetually making the same mistake over and over again: under-projection.

[Back to Top](#top)

### Italy

On April 11, 2020, IHME was projecting 19,691 - 21,377 deaths for Italy. However, Italy was already at over 19,000 deaths at the time and they have been reporting 500+ deaths for the past 3 weeks. The IHME confidence interval is unrealistic. See our Tweet [here](https://twitter.com/youyanggu/status/1249243436881829888) for a graphical explanation. [Click here](#model-comparison-with-ihme) for our most recent estimates for Italy.

*April 18 Update:* Italy has reported 23,227 deaths, already 2,000 more deaths than IHME's upper range for August.

### New York

New York reached its peak of 800 deaths on April 9-10. As of April 11, the IHME model was projecting 42-196 deaths for NY on April 24, 14 days after the peak. That is a decrease of 90% from the peak. However, 15 days after Italy reached its peak deaths at 917, they still reported 619 deaths. So assuming that New York deaths will drop 90% in 15 days when Italy dropped only 30% was an extremely optimistic viewpoint. As of April 11, we forecasted that NY will report 206 - 514 deaths on April 24.

On April 11, IHME also was projecting 13,463 (9,382 - 24,236) total deaths for New York. Due to the reason above, we believe this is an underestimate. [Click here](#model-comparison-with-ihme) for our most recent estimates for New York.

*April 18 Update:* New York has reported 17,671 deaths, already 4,000 more deaths than IHME's projection for August.

### US June-August

As of April 11, IHME projects 225 (0 - 1,180) deaths in the US from June 1 to August 4. While we hope the US only has 225 total deaths from June to August (an average of 3 deaths per day), we believe this is an underestimate. The upper range of 1,180 (18 deaths per day) also appears to be an under-projection *for an upper range*. [Click here](#model-comparison-with-ihme) for our most recent estimates for June - August.

### Update time

New data is extremely important when making projections such as these. That's why we update our model daily based on the new data we receive. Projections using today's data is much more valuable than projections from 2-3 days ago. However, due to certain constraints, IHME is only able to update their model [3 times a week](http://www.healthdata.org/covid/updates): *"Our ambition to produce daily updates has proven to be unrealistic given the relative size of our team and the effort required to fully process, review, and vet large amounts of data alongside implementing model updates."* 

### April 17 Update

On April 17, IHME stated that they have new [cell phone data](http://www.healthdata.org/covid/updates) which indicated that people are properly social distancing. As a result, IHME lowered their projections from 68k deaths to 60k deaths by August. But their severe flaw is that they assume a linear relationship between lower mobility and lower infection - this is not the case.

Most transmissions do not happen with strangers, but rather close contacts. Even if you reduce your mobility by 90%, you do not reduce your transmission by 90%. The data from Italy shows that it only reduces by around 60%. That's the difference between 20k and 40k+ deaths. IHME is likely making the wrong assumption that a 90% reduction in mobility will decrease transmission by 90%.

We posted [a Tweet](https://twitter.com/youyanggu/status/1248844841733128192) on April 11 about MTA (NYC) and BART (Bay Area) subway ridership being down 90% in March. However, the deaths have only dropped around 25% in NY, while CA have not seen any decrease in deaths, more than a month after the drop in ridership.

### Mathematical Flaw

On top of everything we mentioned above, their model is also inherently flawed from a mathematical perspective. They try to model COVID-19 infections using a [Gaussian error function](https://en.wikipedia.org/wiki/Error_function). The problem is that the Gaussian error function is by design *symmetric*, meaning that the curve comes down from the peak at the same rate as it goes up. Unfortunately, this is definitely NOT the case for COVID-19 - we come down from the peak much, much slower. This leads to a significant under-projection in IHME's model, which we have thoroughly highlighted. University of Washington biology professor Dr. Carl T. Bergostrom discussed this in more detail in this highly informative [series of Tweets](https://twitter.com/CT_Bergstrom/status/1250304069119275009).

To conclude, we believe that a successful model must be able to quickly determine what is realistic and what is not, and the above examples highlights our main concerns with the IHME model. IHME is making grossly unfounded assumptions that is going to lead to dire consequences if their work is used by policy-makers.

We encourage everyone to judge a model by their results, not by who created them. There is no doubt that IHME is a widely legitimate entity. However, their COVID-19 model has been undoubtly inaccurate so far.

[Back to Top](#top)

## Data

To make our projections, we use the daily death total provided by [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports), what is considered by experts to be the "gold standard" reference data. We do not use case-related data in our modeling due to reasonings alluded to [here](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/).

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/tree/master/projections). Because the model factors in new data on a daily basis, it will be more accurate over time as more data becomes available. We are currently in the process of submitting our findings for publication, but due to the current circumstances we are prioritizing the public release of our research.

## Contact

We enourage questions/insights/feedback! Please reach out to Youyang Gu on Twitter via [@youyanggu](https://twitter.com/youyanggu) or [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

## Assumptions

### Projections since April 15, 2020

For US and European countries, we assume heavy social distancing until June 1, 2020 and moderate social distancing from June 1 onwards. This more accurately reflects the current sentiment expressed by US and European government officials that it is imperative to re-open the economy, even before the virus is fully contained. This will likely cause a second wave of infections and is reflected by the higher death tolls in our June-August projections.

*Note: For Georgia, we use May 1 instead of June 1 to reflect the governor's intention of an early re-opening of the state.*

#### Heavy vs moderate social distancing

Heavy social distancing is what we have now in many states and countries: stay-at-home orders, closed non-essential businesses, etc. Infection rates typically decrease ~60%, going from an R<sub>0</sub> of around 2 to a R of 0.6-1.0. Moderate social distancing is what we think will happen once states gradually begin opening up. Some establishments will re-open, but people will still be somewhat cognizant about maintaining social distancing. We assume that infection rates will increase 0-20%, with an R of around 0.8-1.2. Note that this still assumes a much lower infection rate than what it was pre-COVID.

If states fail to maintain moderate social distancing during their re-openings, we think the infection rate can become much steeper in June-August than we are currently projecting.

We also take into account that a certain percentage of recovered individuals will be immune, and thus the susceptible population will decrease over time.

If states and countries relax social distancing measures prior to June 1, then the death toll may be higher than projected, while the reverse holds true as well. In addition, if states and countries fully lift social distancing measures prior to August, we may also see a higher death toll than projected.

For non-US and non-European countries, we assume continued social distancing until August 2020 (same as prior to Apr 15).

### Projections prior to April 15, 2020

Our model assumes continued social distancing until August 2020. The exact extent of social distancing is region-specific and will be learned by the model. If social distancing is relaxed prior to August, the number of infections and deaths may become higher than projected. If social distancing is tightened (e.g. to the level of the Wuhan / Hubei lockdowns in China), the number of infections and deaths may become lower. Since this assumption may be unrealistic, the true deaths may be higher than we are forecasting.

### Additional Assumptions

In additional to our most likely estimate, we also provide a 95% confidence interval. So for example, if we predict 62k deaths with a range of 38-105k, it means that there is roughly a 95% chance that the true deaths will be between 38-105k. There are too many real-world variables that can affect the outcome, which results in this large range.

Because our model uses only the daily death totals from each region to make projections, it will be more effective for regions where there more available data.

We currently do not factor in seasonality changes, as there has not been sufficient data/research into this area.

*We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a most likely outcome. If the true results fall within the range, that is within the expected outcome of this model. We highly recommend that you include our range when using our projections (i.e. 21,342 (15-34k) deaths).*

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

Also note that while we attempt to predict the *official* death total, the true death total may be higher due to [underreporting at various levels](https://www.nytimes.com/2020/04/05/us/coronavirus-deaths-undercount.html).

[Back to Top](#top)

## Model Comparison with IHME

We will compare our daily projections with the IHME projections for several heavily-impacted regions where our estimates widely differ: US, New York, Michigan, Connecticut, Italy, and France. Note that while we update our projections daily, IHME only updates their projections three times a week.

\* Starting on April 15, we assume a relaxing of social distancing in US and Europe starting on June 1, leading to higher projections.
/** Starting on April 23, we include probable deaths in our US projections, following new [CDC guidelines](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html) from April 14 onwards to include both confirmed and probable deaths.

A ~~strikethrough~~ means that the current deaths have already exceeded the total projected deaths by August 4.

| Date | Our US proj. death total | IHME US proj. death total
| --- | --- | --- |
| April 9, 2020 | 62,225 (37-106k) | 60,415 (31-127k)
| April 10, 2020 | 70,699 (41-125k) | 61,545 (26-156k)
| April 11, 2020 | 75,870 (43-137k) | 61,545 (26-156k)
| April 12, 2020 | 71,959 (43-125k) | 61,545 (26-156k)
| April 13, 2020 | 71,731 (45-121k) | 68,841 (30-176k)
| April 14, 2020 | 85,431 (50-157k) | 68,841 (30-176k)
| April 15, 2020\* | 114,416 (55-231k) | 68,841 (30-176k)
| April 16, 2020 | 111,673 (55-232k) | 68,841 (30-176k)
| April 17, 2020 | 120,541 (69-229k) | 60,308 (34-141k)
| April 18, 2020 | 121,830 (70-227k) | 60,308 (34-141k)
| April 19, 2020 | 120,633 (70-227k) | 60,308 (34-141k)
| April 20, 2020 | 117,123 (69-229k) | 60,308 (34-141k)
| April 21, 2020 | 129,658 (71-281k) | 65,976 (45-125k)
| April 22, 2020 | 139,165 (76-292k) | 67,641 (48-124k)
| April 23, 2020** | 172,746 (92-327k) | 67,641 (48-124k)

| Date | Our US Jun-Aug proj. death total | IHME US Jun-Aug proj. death total
| --- | --- | --- |
| April 9, 2020 | 5,125 (0.8-17k) | 51 (0-0.2k)
| April 10, 2020 | 5,782 (0.8-20k) | 225 (0-1200)
| April 11, 2020 | 8,373 (0.9-30k) | 225 (0-1200)
| April 12, 2020 | 7,637 (0.7-27k) | 225 (0-1200)
| April 13, 2020 | 8,081 (1.0-28k) | 620 (3-2900)
| April 14, 2020 | 14,368 (1.9-51k) | 620 (3-2900)
| April 15, 2020\* | 28,354 (2.4-102k) | 620 (3-2900)
| April 16, 2020 | 26,828 (2.1-105k) | 620 (3-2900)
| April 17, 2020 | 29,829 (4.2-104k) | 36 (0-300)
| April 18, 2020 | 31,386 (4.3-104k) | 36 (0-300)
| April 19, 2020 | 29,993 (4.8-104k) | 36 (0-300)
| April 20, 2020 | 29,277 (4.0-108k) | 36 (0-300)
| April 21, 2020 | 37,886 (4.2-151k) | 126 (0-560)
| April 22, 2020 | 43,073 (4.6-160k) | 197 (0-954)
| April 23, 2020** | 60,104 (8.2-181k) | 197 (0-954)

| Date | Our NY proj. death total | IHME NY proj. death total
| --- | --- | --- |
| April 9, 2020 | ~~17,371~~ (13-24k) | ~~13,306~~ (9-22k)
| April 10, 2020 | 21,342 (14-35k) | ~~13,463~~ (9-25k)
| April 11, 2020 | 21,703 (15-31k) | ~~13,463~~ (9-25k)
| April 12, 2020 | 21,479 (15-29k) | ~~13,463~~ (9-25k)
| April 13, 2020 | 20,738 (16-27k) | ~~14,542~~ (11-23k)
| April 14, 2020 | 25,019 (18-40k) | ~~14,542~~ (11-23k)
| April 15, 2020\* | 33,384 (20-51k) | ~~14,542~~ (11-23k)
| April 16, 2020 | 31,418 (20-56k) | ~~14,542~~ (11-23k)
| April 17, 2020 | 39,193 (29-57k) | 21,812 (13-43k)
| April 18, 2020 | 37,996 (28-56k) | 21,812 (13-43k)
| April 19, 2020 | 38,193 (28-56k) | 21,812 (13-43k)
| April 20, 2020 | 36,527 (26-58k) | 21,812 (13-43k)
| April 21, 2020 | 35,238 (26-58k) | 23,741 (18-36k)
| April 22, 2020 | 32,470 (26-50k) | 23,232 (19-33k)
| April 23, 2020** | 44,689 (33-58k) | 23,232 (19-33k)

| Date | Our MI proj. death total | IHME MI proj. death total
| --- | --- | --- |
| April 9, 2020 | 4,733 (2.7-8.8k) | ~~2,103~~ (1.3-3.7k)
| April 10, 2020 | 6,747 (3.9-12k) | ~~1,977~~ (1.3-3.6k)
| April 11, 2020 | 6,421 (3.7-11k) | ~~1,977~~ (1.3-3.6k)
| April 12, 2020 | 6,138 (3.6-10k) | ~~1,977~~ (1.3-3.6k)
| April 13, 2020 | 6,268 (3.9-10k) | ~~2,373~~ (1.7-4.1k)
| April 14, 2020 | 7,402 (3.9-15k) | ~~2,373~~ (1.7-4.1k)
| April 15, 2020\* | 8,196 (3.7-19k) | ~~2,373~~ (1.7-4.1k)
| April 16, 2020 | 7,631 (3.5-18k) | ~~2,373~~ (1.7-4.1k)
| April 17, 2020 | 9,029 (4.2-18k) | 3,304 (2.1-6.8k)
| April 18, 2020 | 7,619 (4.1-16k) | 3,304 (2.1-6.8k)
| April 19, 2020 | 7,588 (4.2-16k) | 3,304 (2.1-6.8k)
| April 20, 2020 | 7,573 (4.2-16k) | 3,304 (2.1-6.8k)
| April 21, 2020 | 6,798 (4.2-16k) | 3,361 (2.6-5.4k)
| April 22, 2020 | 7,859 (5.1-17k) | 3,379 (2.7-5.1k)
| April 23, 2020** | 11,230 (5.3-22k) | 3,379 (2.7-5.1k)

| Date | Our Italy proj. death total | IHME Italy proj. death total
| --- | --- | --- |
| April 9, 2020 | 29,402 (22-40k) | ~~20,300~~ (19-22k)
| April 10, 2020 | 29,908 (23-39k) | ~~20,333~~ (19-22k)
| April 11, 2020 | 33,829 (24-49k) | ~~20,333~~ (19-22k)
| April 12, 2020 | 32,909 (24-47k) | ~~20,333~~ (19-22k)
| April 13, 2020 | 33,596 (25-47k) | ~~21,130~~ (20-23k)
| April 14, 2020 | 35,239 (26-49k) | ~~21,130~~ (20-23k)
| April 15, 2020\* | 40,216 (27-79k) | ~~21,130~~ (20-23k)
| April 16, 2020 | 40,444 (27-71k) | ~~21,130~~ (20-23k)
| April 17, 2020 | 43,086 (31-73k) | 26,007 (23-32k)
| April 18, 2020 | 44,609 (31-73k) | 26,007 (23-32k)
| April 19, 2020 | 44,283 (31-72k) | 26,007 (23-32k)
| April 20, 2020 | 44,117 (32-72k) | 26,007 (23-32k)
| April 21, 2020 | 44,683 (32-71k) | 26,600 (24-32k)
| April 22, 2020 | 43,591 (32-66k) | 26,867 (25-33k)
| April 23, 2020 | 43,792 (33-66k) | 26,867 (25-33k)

| Date | Our France proj. death total | IHME France proj. death total
| --- | --- | --- |
| April 9, 2020 | 36,881 (21-58k) | ~~15,058~~ (12-18k)
| April 10, 2020 | 36,621 (21-58k) | ~~15,741~~ (13-21k)
| April 11, 2020 | 37,234 (21-63k) | ~~15,741~~ (13-21k)
| April 12, 2020 | 36,201 (20-63k) | ~~15,741~~ (13-21k)
| April 13, 2020 | 35,063 (21-62k) | ~~17,448~~ (15-23k)
| April 14, 2020 | 35,458 (22-62k) | ~~17,448~~ (15-23k)
| April 15, 2020\* | 42,777 (23-92k) | ~~17,448~~ (15-23k)
| April 16, 2020 | 41,280 (23-90k) | ~~17,448~~ (15-23k)
| April 17, 2020 | 54,095 (31-104k) | 22,555 (19-30k)
| April 18, 2020 | 51,633 (31-99k) | 22,555 (19-30k)
| April 19, 2020 | 44,196 (27-84k) | 22,555 (19-30k)
| April 20, 2020 | 43,242 (27-83k) | 22,555 (19-30k)
| April 21, 2020 | 41,643 (27-81k) | 23,104 (20-29k)
| April 22, 2020 | 40,156 (28-74k) | 23,304 (21-30k)
| April 23, 2020 | 40,752 (26-93k) | 23,304 (21-30k)

[Back to Top](#top)

## Updates

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
