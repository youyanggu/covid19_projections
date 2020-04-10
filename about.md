---
layout: default
title: About
permalink: /about/
---

## About the model

Our COVID-19 prediction model has an underlying simulator that simulates the COVID-19 epidemic in each given country/state/region. The parameters/inputs of this simulator are then learned using machine learning techniques that attempts to minimize the error between the projected outputs and the actual results. After some additional validation techniques (to minimize a phenomenon called overfitting), we use the learned parameters to simulate the future and make projections.

The goal of this project is to showcase the strengths of artificial intelligence to tackle one of the world's most difficult problems: predict the track of a pandemic. We want to show that it is not necessary to be an expert in epidemiology to be able to make accurate projections. In some cases, starting with a blank state may actually be beneficial by eliminating certain ill-conceived preconceptions. Here, we use a pure data-driven approach by letting the machine do the learning.

## How our model is different

While most models had been predicting [80-250k+ deaths](https://www.washingtonpost.com/politics/2020/04/02/grim-death-toll-projections-white-house-offered-monday-have-already-been-revised-upward/) in the US, we have consistently projected under 65k deaths since we first started this project on March 30.

Unlike other models that try to create complex mathematical equations to "fit a curve", we try to simulate what is actually happening in the real world. This makes our model easy to interpret and understand.

As an example, one of the most important properties for any infectious disease is the [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number), known as R<sub>0</sub>. Rather than pre-setting this value based on assumptions, our model is able to learn the value that most closely matches the data. For Italy, the R<sub>0</sub> is found to be around 2-2.2, while for New York state, the R<sub>0</sub> is 3.6-3.8. This means that on average, an infected person in New York will infect 3.6 to 3.8 additional people. For most regions, the R<sub>0</sub> is found to be around 2, which matches [the WHO findings](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf) from China.

Another strength of our model is that because it is data-driven, it is quick to run and easy to regenerate. No daily tuning needs to be done - it just needs the raw data. Unlike other models, we update our model on a daily basis, leading to more accurate projections.

## Data

The only COVID-19 data we use to make these projections is the daily death total provided by [The Covid Tracking Project](https://covidtracking.com/) (for US projections) and [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19) (for international projections). The raw files can be found [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/data). Due to the reasonings explained [by Nate Silver](https://fivethirtyeight.com/features/coronavirus-case-counts-are-meaningless/), we do not use case-related data in our modeling.

Every day, raw daily projections for all 50 US states and select international countries will be uploaded [here](https://github.com/youyanggu/covid19_projections/tree/master/projections). Because the model factors in new data on a daily basis, it will be more accurate over time as more data becomes available. We are currently in the process of submitting our findings for peer review, but due to the current circumstances we are prioritizing the public release of our research.

Feel free to reach out to me on Twitter via [@youyanggu](https://twitter.com/youyanggu) with any questions/insights/feedback. You can also find me [on LinkedIn](https://www.linkedin.com/in/youyanggu/).

## Assumptions

Similar to other models, our model assumes moderate social distancing through June 2020. If social distancing is relaxed prior to June, the number of infections and deaths may become higher than projected. If social distancing is tightened (e.g. to the level of the Wuhan / Hubei lockdowns in China), the number of infections and deaths may become lower.

In additional to our most likely estimate, we also provide a 95% confidence interval. So for example, if we predict 62k deaths with a range of 38-105k, it means that there is roughly a 95% chance that the true deaths will be between 38-105k. There are too many real-world variables that can affect the outcome, which results in this large range.

*We want to caution against focusing on one particular number as the outcome of this model. We are in fact projecting a range which includes a most likely outcome. If the true results fall within the range, that is within the expected outcome of this model.*

While we attempt our best to ensure accuracy and precision, no model is perfect, so we urge everyone to use caution when interpreting these projections. This is just one particular model, so we encourage everyone to evaluate and be open to multiple sources. At the end of the day, the decision-making rests in the hands of people, not machines.

Also note that while we attempt to predict the *official* death total, the true death total may be higher due to [underreporting at various levels](https://www.nytimes.com/2020/04/05/us/coronavirus-deaths-undercount.html).

## Model evaluation

In this section we will compare our projections with a popular model developed by the [Institute for Health Metrics and Evaluation (IHME)](https://covid19.healthdata.org/) and commonly referred to by the White House.

As of April 9, most models (including our own) predict somewhere in the range of 50-70k deaths in the US. Nevertheless, the exact trajectory and state-specific projections still differ widely. For example, while both the IHME model and our model predicts a total of roughly 60,000 deaths in the US by August, the timelines differ greatly. The IHME model projects 52,864 deaths through May 1 and 7,781 deaths from May 1 through August 4, while we project 44,776 deaths through May 1 and 17,449 deaths from May 1 through August 4.

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
