---
layout: default
title: About
permalink: /about/
---

## About the model

Our COVID-19 prediction model has an underlying simulator based on an SEIS model to simulate the COVID-19 epidemic in each given country/state/region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. We want to show that it is not necessary to be an expert in epidemiology to be able to make accurate projections. In some cases, starting with a blank state may actually be beneficial by eliminating certain ill-conceived preconceptions. Here, we use a pure data-driven approach by letting the machine do the learning.

## How our model is different

Unlike other models that try to create complex mathematical equations to "fit a curve", we try to simulate what is actually happening in the real world. This makes our model easy to interpret and understand.

As an example, one of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2-2.2, while for New York state, the R<sub>0</sub> is 3.6-3.8. This means that on average, an infected person in New York will infect 3.6 to 3.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf) from China.

We can learn more from the model than just the R<sub>0</sub>. For example, our model determined that the true mortality rate for COVID-19 in Italy is around 2%, while the true mortality rate in New York (and most other regions) is roughly 1%. This is again consistent with the widely published reports. The model can also determine when people in a region started social-distancing. For New York, this inflection point is determined to be on March 13-14, which closely matches the [NYC subway ridership data](https://twitter.com/youyanggu/status/1248838172986896384).

Another strength of our model is that because it is data-driven, it is quick to run and easy to regenerate. No daily tuning needs to be done - it just needs the raw data. Unlike other models that can only be updated once every few days, our model takes under 10 minutes to generate and is updated on a daily basis, leading to more accurate projections.

## Data

The only COVID-19 data we use to make these projections is the daily death total provided by [The Covid Tracking Project](https://covidtracking.com/) (for US projections) and [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) (for international projections). The raw files can be found [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/data). Due to the reasonings explained [by Nate Silver](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/), we do not use case-related data in our modeling.

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/tree/master/projections). Because the model factors in new data on a daily basis, it will be more accurate over time as more data becomes available. We are currently in the process of submitting our findings for peer review, but due to the current circumstances we are prioritizing the public release of our research.

## Contact

We enourage questions/insights/feedback! Please reach out to Youyang Gu on Twitter via [@youyanggu](https://twitter.com/youyanggu) or [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

## Assumptions

Similar to other models, our model assumes moderate social distancing through June 2020. If social distancing is relaxed prior to June, the number of infections and deaths may become higher than projected. If social distancing is tightened (e.g. to the level of the Wuhan / Hubei lockdowns in China), the number of infections and deaths may become lower.

In additional to our most likely estimate, we also provide a 95% confidence interval. So for example, if we predict 62k deaths with a range of 38-105k, it means that there is roughly a 95% chance that the true deaths will be between 38-105k. There are too many real-world variables that can affect the outcome, which results in this large range.

*We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a most likely outcome. If the true results fall within the range, that is within the expected outcome of this model.*

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

Also note that while we attempt to predict the *official* death total, the true death total may be higher due to [underreporting at various levels](https://www.nytimes.com/2020/04/05/us/coronavirus-deaths-undercount.html).

## Model comparison

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House and the media.

As of April 9, most models (including our own) predict somewhere in the range of 50-70k deaths in the US. Nevertheless, the exact trajectory and state-specific projections still differ widely. For example, while both the IHME model and our model predicts a total of roughly 60,000 deaths in the US by August, the timelines differ greatly. The IHME model projects 52,864 deaths through May 1 and 7,781 deaths from May 1 through August 4, while we project 44,776 deaths through May 1 and 17,449 deaths from May 1 through August 4.

Below is a comparison of our models in predicting daily US deaths. To make a fair comparison, we start on April 9, the day when both our model and the IHME model projected ~60k deaths. Note that because deaths are [not evenly reported by day](https://twitter.com/NateSilver538/status/1245105892028223490), the projections may be significantly higher than reported on weekends and lower than reported on the weekdays.

| Date | Actual US deaths | Our projection | IHME projection | 
| --- | --- | --- | --- |
| Apr 9, 2020 | 1,904 | 1,878 | 2,037
| Apr 10, 2020 | 1,932 | 1,855 | 2,104
| Apr 11, 2020 | TBA | 	1,996 | 1,907

Below we compare our daily projections with the IHME projections for several selected regions: US, New York, Michigan, Connecticut, Italy, and the UK. While we update our projections daily, IHME only updates their projections three time a week: *"Our ambition to produce daily updates has proven to be unrealistic given the relative size of our team and the effort required to fully process, review, and vet large amounts of data alongside implementing model updates."*

| Date | Our US proj. death total | IHME US proj. death total
| --- | --- | --- |
| April 9, 2020 | 62,225 | 60,415
| April 10, 2020 | 70,699 | 61,545

| Date | Our NY proj. death total | IHME NY proj. death total
| --- | --- | --- |
| April 9, 2020 | 17,371 | 13,306
| April 10, 2020 | 21,342 | 13,463

| Date | Our MI proj. death total | IHME MI proj. death total
| --- | --- | --- |
| April 9, 2020 | 4,733 | 2,103
| April 10, 2020 | 6,747 | 1,977

| Date | Our CT proj. death total | IHME CT proj. death total
| --- | --- | --- |
| April 9, 2020 | 2,252 | 4,003
| April 10, 2020 | 2,002 | 4,614

| Date | Our Italy proj. death total | IHME Italy proj. death total
| --- | --- | --- |
| April 9, 2020 | 29,402 | 20,300
| April 10, 2020 | 29,908 | 20,333

| Date | Our UK proj. death total | IHME UK proj. death total
| --- | --- | --- |
| April 9, 2020 | 32,173 | 66,314
| April 10, 2020 | 33,106 | 37,494

## Updates

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
