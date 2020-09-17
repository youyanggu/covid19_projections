---
layout: default
title: Historical Performance
permalink: /historical-performance/
---

# Historical Performance

On this page, we present a weekly evaluation of our model's historical performance along with other models in the [COVID-19 Forecast Hub](https://github.com/reichlab/covid19-forecast-hub). The forecasts from these models are sent to the CDC weekly and presented on the [CDC COVID-19 Forecasting page](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html).

We have open-sourced the code and output used to generate these evaluations [here](https://github.com/youyanggu/covid19-forecast-hub-evaluation/#methods). We believe in a fully transparent evaluation methodology, and publicly releasing all of our code and data is the best way to do so.

[Click here](/model-comparison-ihme) to see some sample plots of our past projections.

The charts below represent past state-by-state and US projections evaluated on cumulative deaths on the specified evaluation date (June 20, June 13, etc). As the charts may be outdated, please consult our [evaluation page](https://github.com/youyanggu/covid19-forecast-hub-evaluation) for the latest data.

* [4 Week Ahead](#4-week-ahead)
* [September 12](#september-12)
* [September 5](#september-5)
* [August 29](#august-29)
* [August 22](#august-22)
* [August 15](#august-15)
* [August 8](#august-8)
* [August 1](#august-1)
* [July 25](#july-25)
* [July 18](#july-18)
* [July 11](#july-11)
* [July 4](#july-4)
* [June 27](#june-27)
* [June 20](#june-20)
* [June 13](#june-13)
* [June 6](#june-6)
* [May 30](#may-30)
* [May 23](#may-23)
* [May 16](#may-16)
* [May 9](#may-9)
* [May 2](#may-2)

[Back to Top](#top)

### Observations

* A baseline model that simply uses the previous week's average deaths to make future projections outperforms many models for short-term forecasts.
* Because US country-wide projections only contains a single forecast per week, there is much higher variance week-to-week compared to state-by-state projections, where there are 51 forecasts each week. As a result, we believe state-by-state evaluations is a better indicator of model performance. This same concept is why we play 7-game series for NBA/NHL/MLB playoffs.
* A handful of models consistently outperform the remainder of the models. The top 3 best-performing models every week for state-by-state projections almost always comes from one of these 5 models: covid19-projections.com, UCLA, Los Alamos (LANL), UMass Amherst, COVIDhub Ensemble.
* The [COVIDhub ensemble model](https://github.com/reichlab/covid19-forecast-hub/#ensemble-model) is created by taking a combination of all eligible models that submit projections to the CDC. Our projections are included in this ensemble.
* For state-by-state projections, we evaluate all models that have 4+ week projections for more than 40 states. For models with missing state projections, we use the mean projection for that state (among all the models).
* While past performance is not necessarily indicative of future performance, we believe it's important to consider a model's historical accuracy and not just a model's future forecasts and/or the creator's name recognition. It is also important to make sure that a model can perform better than the baseline.
* We welcome and encourage independent model evaluations. See [here](https://twitter.com/FelixHoenikker_/status/1262517002507182080) for an evaluation from a PhD data scientist at NASA Ames.

### Errata

* Prior to September 12, our 2+ week target calculations for models with only incident deaths forecasts were incorrect. This included the following models: CMU, LNQ, STH. This has since been retroactively corrected on the GitHub repository, but are not reflected in the charts dated before September 12.
* Prior to June 20, the YYG model was the top row by default. Other than that, the ordering follows the mean weekly ranks.

[Back to Top](#top)

## 4 Week Ahead

### State-by-state projections

![States comparison](/assets/images/4_week_ahead_states.png)

### US projections

![US comparison](/assets/images/4_week_ahead_us.png)

## September 12

### State-by-state projections

![States comparison](/assets/images/2020-09-12_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-09-12_comparison_us.png)

## September 5

### State-by-state projections

![States comparison](/assets/images/2020-09-05_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-09-05_comparison_us.png)

## August 29

### State-by-state projections

![States comparison](/assets/images/2020-08-29_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-08-29_comparison_us.png)

## August 22

### State-by-state projections

![States comparison](/assets/images/2020-08-22_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-08-22_comparison_us.png)

## August 15

### State-by-state projections

![States comparison](/assets/images/2020-08-15_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-08-15_comparison_us.png)

## August 8

### State-by-state projections

![States comparison](/assets/images/2020-08-08_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-08-08_comparison_us.png)

## August 1

### State-by-state projections

![States comparison](/assets/images/2020-08-01_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-08-01_comparison_us.png)

## July 25

### State-by-state projections

![States comparison](/assets/images/2020-07-25_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-07-25_comparison_us.png)

## July 18

### State-by-state projections

![States comparison](/assets/images/2020-07-18_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-07-18_comparison_us.png)

## July 11

### State-by-state projections

![States comparison](/assets/images/2020-07-11_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-07-11_comparison_us.png)

## July 4

### State-by-state projections

![States comparison](/assets/images/2020-07-04_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-07-04_comparison_us.png)

## June 27

### State-by-state projections

![States comparison](/assets/images/2020-06-27_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-06-27_comparison_us.png)

## June 20

### State-by-state projections

![States comparison](/assets/images/2020-06-20_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-06-20_comparison_us.png)

## June 13

### State-by-state projections

![States comparison](/assets/images/2020-06-13_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-06-13_comparison_us.png)

## June 6

### State-by-state projections

![States comparison](/assets/images/2020-06-06_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-06-06_comparison_us.png)

## May 30

### State-by-state projections

![States comparison](/assets/images/2020-05-30_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-05-30_comparison_us.png)

## May 23

### State-by-state projections

![States comparison](/assets/images/2020-05-23_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-05-23_comparison_us.png)

## May 16

### State-by-state projections

![States comparison](/assets/images/2020-05-16_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-05-16_comparison_us.png)

![US comparison](/assets/images/2020-05-16_comparison_us_perc.png)

## May 9

### State-by-state projections

![States comparison](/assets/images/2020-05-09_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-05-09_comparison_us.png)

## May 2

### State-by-state projections

![States comparison](/assets/images/2020-05-02_comparison_states.png)

### US projections

![US comparison](/assets/images/2020-05-02_comparison_us.png)
