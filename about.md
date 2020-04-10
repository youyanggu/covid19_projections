---
layout: default
title: About
permalink: /about/
---

## About the model

Our COVID-19 prediction model has an underlying simulator that simulates the COVID-19 epidemic in a given region. The parameters of the simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle some of the world's most difficult problems. We want to show that you do not have to be an expert in epidemiology to be able to make accurate projections. In some cases, starting with a blank state may actually be beneficial by eliminating certain ill-conceived preconceptions.

The only COVID-19 data we use to make these projections is the daily death total provided by [The Covid Tracking Project](https://covidtracking.com/) (for US projections) and [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) (for international projections). The raw files can be found [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/data).

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/tree/master/projections). Because the model factors in new data on a daily basis, it will be more accurate over time.

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections.

Feel free to reach out to me on Twitter via **[@youyanggu](https://twitter.com/youyanggu)** with any questions/insights/feedback. You can also find me [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

_Note_: While we attempt to predict the _official_ death total, the true death total may be higher due underreporting at various levels.

## Assumptions

Similar to other models, our model assumes full social distancing through June 2020. If social distancing is relaxed prior to June, the true number of infections and deaths may increase.

## Model evaluation

While other models have predicted 100-250k+ deaths as late as early April, we have consistently projected under 60k deaths in the US since we launched our first projections on Apr 1.

As of April 9, most models (including our own) now predict somewhere in the range of 50-70k deaths in the US. Nevertheless, the exact trajectory and state-specific projections still differ widely.

In this section we will compare our projections of when the US will hit the following COVID-19 death milestones with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/). This is based on the projections taken from *April 9, 2020*.

| US deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 20,000 | April 11 | April 11 | -
| 25,000 | April 14 | April 13 | -
| 30,000 | April 18 | April 16 | -
| 35,000 | April 22 | April 18 | -
| 40,000 | April 27 | April 21 | -
| 45,000 | May 6 | April 24 | -
| 50,000 | May 22 | April 28 | -
| *Total* | *55,001* | *60,415* | -

Below are the same projections for New York state, Michigan, and Connecticut, some of the worst-hit states in the US:

| NY deaths | Our 4/9 projection | 4/9 IHME projection | Actual
| --- | --- | --- | --- |
| 8,000 | April 11 | April 11 | -
| 10,000 | April 14 | April 14 | -
| 12,000 | April 18 | April 18 | -
| 14,000 | April 26 | (will not reach) | -
| 16,000 | May 16 | (will not reach) | -
| *Total* | *16,713* | *13,307* | -

| MI deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 1,500 | April 13 | April 13 | -
| 2,000 | April 17 | April 20 | -
| 2,500 | April 23 | (will not reach) | -
| 3,000 | May 1 | (will not reach) | -
| 3,500 | May 16 | (will not reach) | -
| *Total* | *4,112* | *2,103* | -

| CT deaths | Our 4/9 projection | IHME 4/9 projection | Actual
| --- | --- | --- | --- |
| 500 | April 12 | April 11 | -
| 1,000 | April 22 | April 16 | -
| 2,000 | (will not reach) | April 24 | -
| 3,000 | (will not reach) | May 2 | -
| 4,000 | (will not reach) | June 2 | -
| *Total* | *1,906* | *4,003* | -

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
