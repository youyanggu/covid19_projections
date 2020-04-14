---
layout: default
title: About
permalink: /about/
---

## About the model

Our COVID-19 prediction model has an underlying simulator based on [an SEIS model](http://leonidzhukov.net/hse/2014/socialnetworks/papers/2000SiamRev.pdf) to simulate the COVID-19 epidemic in each given country/state/region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. Here, we use a pure data-driven approach by letting the machine do the learning.

## How our model is different

Unlike many models that try to create complex mathematical equations to "fit a curve" without an intuitive explanation as to why it works, we try to simulate what is happening in the real world. This makes our model easy to interpret and understand.

As an example, one of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2-2.2, while for New York state, the R<sub>0</sub> is 3.6-3.8. This means that on average, an infected person in New York will infect 3.6 to 3.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf) from China.

We can learn more from the model than just the R<sub>0</sub>. For example, our model determined that the true mortality rate for COVID-19 in Italy is around 2%, while the true mortality rate in New York (and most other regions) is roughly 1%. This is again consistent with the widely published reports. The model can also determine when people in a region started social-distancing. For New York, this inflection point is determined to be on March 13-14, which closely matches the [NYC subway ridership data](https://twitter.com/youyanggu/status/1248844841733128192).

Another strength of our model is that because it is purely data-driven, it is quick to run and easy to regenerate. No daily tuning needs to be done - it just needs the raw data. Unlike other models that can only be updated once every few days, our entire model takes 10 minutes to generate and is updated on a daily basis, leading to more accurate projections.

## Concerns with the IHME model

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House and media.

The IHME model is a good model and provides a good starting point for making projections. We greatly applaud their efforts, especially for making a fairly accurate projection in March (80-100k US deaths) when many other models were projecting 100-250k+.

With that said, because their model is based on fitting a mathethetical curve rather than a real world simulation, some of their region-specific projections do not pass what we call the "common sense test". Here are a few examples:

### Italy: under-projection

As of April 11, 2020, IHME is projecting 19,691 - 21,377 deaths for Italy. However, Italy is already at over 19,000 deaths and they have been reporting 500+ deaths for the past 3 weeks. The IHME confidence interval is unrealistic. Our projections from April 11 are much higher: 24,646 - 48,764. See our Tweet [here](https://twitter.com/youyanggu/status/1249243436881829888) for a graphical explanation.

### New York: under-projection

New York reached 799 deaths on Thursday April 9, which we hope is the peak. As of April 11, the IHME model is projecting 42-196 deaths for NY on April 24, 15 days later. However, 15 days after Italy reached its peak deaths at 917, they still reported 619 deaths. So assuming that New York deaths will drop 90% in 15 days when Italy dropped only 30% would be an optimistic viewpoint. We think NY will report 206 - 514 deaths on April 24.

As of April 11, IHME is projecting 13,463 (9,382 - 24,236) total deaths for New York. Due to the reason above, we believe this is an underestimate. Our model projects 21,703 (15,848 - 30,280) deaths.

### Connecticut: over-projection

As of April 11, Connecticut currently has 448 deaths, and yet the IHME is projecting 4,614 deaths, a 10x increase. Their range is also 1,143-13,559, an extremely large range. Our projections from April 11 show a range of 1,337 - 3,850.

### US June-August: under-projection

As of April 11, IHME projects 225 (0 - 1,180) deaths in the US from June 1 to August 4. While we hope the US only has 225 total deaths from June to August (an average of 3 deaths per day), we believe this is an underestimate. The upper range of 1,180 (18 deaths per day) also appears to be an under-projection *for an upper range*. Meanwhile, our model is projecting 8,373 (944 - 29,315) deaths in US from June 1 to August 4.

### Update time

New data is extremely important when making projections such as these. That's why we update our model daily based on the new data we receive. Projections using today's data is much more valuable than projections from 2-3 days ago. However, due to certain constraints, IHME is only able to update their model [3 times a week](http://www.healthdata.org/covid/updates): *"Our ambition to produce daily updates has proven to be unrealistic given the relative size of our team and the effort required to fully process, review, and vet large amounts of data alongside implementing model updates."* 

We believe that a successful model must be able to quickly determine what is realistic and what is not, and the above examples highlights our main concerns with the IHME model.

## Data

The only COVID-19 data our model uses to make projections is the daily death total provided by [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports), what is considered by experts to be the "gold standard" reference data. We do not use case-related data in our modeling due to reasonings described [here](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/).

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/tree/master/projections). Because the model factors in new data on a daily basis, it will be more accurate over time as more data becomes available. We are currently in the process of submitting our findings for peer review, but due to the current circumstances we are prioritizing the public release of our research.

## Contact

We enourage questions/insights/feedback! Please reach out to Youyang Gu on Twitter via [@youyanggu](https://twitter.com/youyanggu) or [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

## Assumptions

Similar to other models, our model assumes moderate social distancing through June 2020. If social distancing is relaxed prior to June, the number of infections and deaths may become higher than projected. If social distancing is tightened (e.g. to the level of the Wuhan / Hubei lockdowns in China), the number of infections and deaths may become lower.

In additional to our most likely estimate, we also provide a 95% confidence interval. So for example, if we predict 62k deaths with a range of 38-105k, it means that there is roughly a 95% chance that the true deaths will be between 38-105k. There are too many real-world variables that can affect the outcome, which results in this large range.

*We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a most likely outcome. If the true results fall within the range, that is within the expected outcome of this model. We highly recommend that you include our range when using our projections (i.e. 21,342 (15-34k) deaths).*

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

Also note that while we attempt to predict the *official* death total, the true death total may be higher due to [underreporting at various levels](https://www.nytimes.com/2020/04/05/us/coronavirus-deaths-undercount.html).

## Model comparison

We will compare our daily projections with the IHME projections for several heavily-impacted regions where our estimates widely differ: US, New York, Michigan, Connecticut, Italy, and France. Note that while we update our projections daily, IHME only updates their projections three times a week.

| Date | Our US proj. death total | IHME US proj. death total
| --- | --- | --- |
| April 9, 2020 | 62,225 (37-106k) | 60,415 (31-127k)
| April 10, 2020 | 70,699 (41-125k) | 61,545 (26-156k)
| April 11, 2020 | 75,870 (43-137k) | 61,545 (26-156k)
| April 12, 2020 | 71,959 (43-125k) | 61,545 (26-156k)
| April 13, 2020 | 71,731 (45-121k) | 68,841 (30-176k)

| Date | Our US Jun-Aug proj. death total | IHME US Jun-Aug proj. death total
| --- | --- | --- |
| April 9, 2020 | 5,125 (0.8-17k) | 51 (0-0.2k)
| April 10, 2020 | 5,782 (0.8-20k) | 225 (0-1.2k)
| April 11, 2020 | 8,373 (0.9-30k) | 225 (0-1.2k)
| April 12, 2020 | 7,637 (0.7-27k) | 225 (0-1.2k)
| April 13, 2020 | 8,081 (1.0-28k) | 620 (3-2.9k)

| Date | Our NY proj. death total | IHME NY proj. death total
| --- | --- | --- |
| April 9, 2020 | 17,371 (13-24k) | 13,306 (9-22k)
| April 10, 2020 | 21,342 (14-35k) | 13,463 (9-25k)
| April 11, 2020 | 21,703 (15-31k) | 13,463 (9-25k)
| April 12, 2020 | 21,479 (15-29k) | 13,463 (9-25k)
| April 13, 2020 | 20,738 (16-27k) | 14,542 (11-23k)

| Date | Our MI proj. death total | IHME MI proj. death total
| --- | --- | --- |
| April 9, 2020 | 4,733 (2.7-8.8k) | 2,103 (1.3-3.7k)
| April 10, 2020 | 6,747 (3.9-12k) | 1,977 (1.3-3.6k)
| April 11, 2020 | 6,421 (3.7-11k) | 1,977 (1.3-3.6k)
| April 12, 2020 | 6,138 (3.6-10k) | 1,977 (1.3-3.6k)
| April 13, 2020 | 6,268 (3.9-9.9k) | 2,373 (1.7-4.1k)

| Date | Our CT proj. death total | IHME CT proj. death total
| --- | --- | --- |
| April 9, 2020 | 2,252 (1.2-3.9k) | 4,003 (1.3-10.1k)
| April 10, 2020 | 2,002 (1.0-3.4k) | 4,614 (1.1-13.6k)
| April 11, 2020 | 2,326 (1.3-3.9k) | 4,614 (1.1-13.6k)
| April 12, 2020 | 2,241 (1.2-3.8k) | 4,614 (1.1-13.6k)
| April 13, 2020 | 2,276 (1.3-3.9k) | 5,426 (1.3-15.4k)

| Date | Our Italy proj. death total | IHME Italy proj. death total
| --- | --- | --- |
| April 9, 2020 | 29,402 (22-40k) | 20,300 (19-22k)
| April 10, 2020 | 29,908 (23-39k) | 20,333 (19-22k)
| April 11, 2020 | 33,829 (24-49k) | 20,333 (19-22k)
| April 12, 2020 | 32,909 (24-47k) | 20,333 (19-22k)
| April 13, 2020 | 33,596 (25-47k) | 21,130 (20-23k)

| Date | Our France proj. death total | IHME France proj. death total
| --- | --- | --- |
| April 9, 2020 | 36,881 (21-58k) | 15,058 (12-18k)
| April 10, 2020 | 36,621 (21-58k) | 15,741 (13-21k)
| April 11, 2020 | 37,234 (21-63k) | 15,741 (13-21k)
| April 12, 2020 | 36,201 (20-63k) | 15,741 (13-21k)
| April 13, 2020 | 35,063 (21-62k) | 17,448 (15-23k)

## Updates

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
