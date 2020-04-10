---
layout: default
title: About
permalink: /about/
---

## About the model

Our COVID-19 prediction model has an underlying simulator that simulates the COVID-19 epidemic in a given region. The parameters/inputs of the simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle some of the world's most difficult problems. We want to show that you do not have to be an expert in epidemiology to be able to make accurate projections. In some cases, starting with a blank state may actually be beneficial by eliminating certain ill-conceived preconceptions.

The only COVID-19 data we use to make these projections is the daily death total provided by [The Covid Tracking Project](https://covidtracking.com/) (for US projections) and [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) (for international projections). The raw files can be found [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/data). Due to the reasonings explained [by Nate Silver](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/), we do not use case-related data in our modeling.

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/tree/master/projections). Because the model factors in new data on a daily basis, it will be more accurate over time as more data becomes available. We are currently in the process of submitting our findings for peer review, but due to the current circumstances we are prioritizing the public release of our research.

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections.

Feel free to reach out to me on Twitter via **[@youyanggu](https://twitter.com/youyanggu)** with any questions/insights/feedback. You can also find me [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

## Assumptions

Similar to other models, our model assumes moderate social distancing through June 2020. If social distancing is relaxed prior to June, the number of infections and deaths may become higher than projected. If social distancing is tightened (e.g. to the level of the Wuhan / Hubei lockdowns in China), the number of infections and deaths may become lower.

While we attempt to predict the _official_ death total, the true death total may be higher due underreporting at various levels.

## Model evaluation

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/).

As of April 9, most models (including our own) now predict somewhere in the range of 50-70k deaths in the US. Nevertheless, the exact trajectory and state-specific projections still differ widely. For example, while both the IHME model and our mdoel predicts a total of roughly 60,000 deaths in the US by August, the timeline differs greatly. The IHME model projects 52,864 deaths through May 1 and 7,781 deaths from May 1 through August 4, while we project 44,776 deaths through May 1 and 17,449 deaths from May 1 through August 4.

Below we compare when the US will surpass the following COVID-19 death milestones compared with the IHME model. This is based on the projections from April 9.

| US deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 20,000 | April 11 | April 11 | -
| 25,000 | April 14 | April 13 | -
| 30,000 | April 17 | April 16 | -
| 35,000 | April 21 | April 18 | -
| 40,000 | April 26 | April 21 | -
| 45,000 | May 2 | April 24 | -
| 50,000 | May 10 | April 28 | -
| 55,000 | May 24 | April 28 | -
| 60,000 | June 20 | April 28 | -
| *Total* | *62,225* | *60,415* | -

Below are the same projections for New York state, Michigan, and Connecticut, some of the worst-hit states in the US:

| NY deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 8,000 | April 11 | April 11 | -
| 10,000 | April 14 | April 14 | -
| 12,000 | April 18 | April 18 | -
| 14,000 | April 25 | (will not reach) | -
| 16,000 | May 9 | (will not reach) | -
| *Total* | *17,371* | *13,307* | -

<br />

| MI deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 1,500 | April 13 | April 13 | -
| 2,000 | April 17 | April 20 | -
| 2,500 | April 22 | (will not reach) | -
| 3,000 | April 28 | (will not reach) | -
| 3,500 | May 7 | (will not reach) | -
| *Total* | *4,733* | *2,103* | -

<br />

| CT deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 500 | April 12 | April 11 | -
| 1,000 | April 21 | April 16 | -
| 1,500 | May 5 | April 20 | -
| 2,000 | June 6 | April 24 | -
| 3,000 | (will not reach) | May 2 | -
| 4,000 | (will not reach) | June 2 | -
| *Total* | *2,252* | *4,003* | -

We also present an international projection comparison below, for the United Kingdom.

| UK deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 10,000 | April 12 | April 9 | -
| 15,000 | April 17 | April 12 | -
| 20,000 | April 25 | April 14 | -
| 25,000 | May 6 | April 16 | -
| 30,000 | June 2 | April 18 | -
| 40,000 | (will not reach) | April 21 | -
| 50,000 | (will not reach) | April 25 | -
| 60,000 | (will not reach) | May 1 | -
| *Total* | *32,173* | *66,314* | -

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
