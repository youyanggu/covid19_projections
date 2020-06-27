---
layout: default
title: COVID-19 Maps
permalink: /maps/
---

## Maps

* US maps (this page)
* [View Global maps](/maps-global)
* [View Europe maps](/maps-europe)

Here we display a variety of US maps generated based on current data and our projections. All maps are updated daily.

Note that our future projections have a high degree of uncertainty which is not reflected in these maps. Please refer to our [detailed projections](/#view-projections) to view our confidence intervals. Learn more about our assumptions and limitations [here](/about/#assumptions).

*Mobile users: We recommend using landscape mode for optimized viewing of this page.*

[Back to Top](#top)

### C19Pro Score

We created the *C19Pro Score* for both cases and deaths to show where weekly cases and deaths are changing the most. They are shown in the first two maps below.

You can download historical C19Pro Scores [here](https://github.com/youyanggu/covid19_projections/tree/master/c19pro_score).

We created this score to try to encapsulate three important factors into a single number: absolute new daily cases (sheer number of cases), rate of change in cases (how fast cases are changing), cases per capita (prevalence relative to population).

#### Formula

```C19Pro_Score = scaled(-avg_daily_cases_per_1mil * mean(Δcases * |cases_%_change|, Δcases_per_1_mil))```

- where `Δcases` is the change in cases (7-day moving average) from 7 days ago and `scaled()` is a function that maps all values to -100 to 100. A negative value means that cases are increasing.
- For our US C19Pro Scores for cases, we also incorporating changes in testing. If a state report increasing cases, we increase (improve) their C19Pro Score if they also report increasing tests. Conversely, if states report decreasing cases, we decrease their C19Pro Score if they report decreasing tests.
- We apply the same formula for deaths to show where deaths are changing the most.

#### Data Source

- Cases and deaths: [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
- Tests (US only): [The COVID Tracking Project](https://covidtracking.com/)

[Back to Top](#top)

### Definitions
- *Infections:* Number of all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimate do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.
- *Currently infected:* Percentage of the population that are actively carrying the virus on the given date. We assume an average recovery time of 15 days.
- *Total infected:* Percentage of the population that are currently infected or have been infected at some point, by a given date.
- *Total deaths:* Total deaths per 1 million people by a given date.
- *Additional deaths:* Additional deaths per 1 million people from today until the projected date.

[Back to Top](#top)
{% include iframe_us_maps.html %}[Back to Top](#top)

## Global Maps

[Click here](/maps-global) to view our Global maps.

## Europe Maps

[Click here](/maps-europe) to view our Europe maps.
