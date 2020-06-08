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

Note that our future projections have a high degree of uncertainty which is not reflected in these maps. Please refer to our [detailed projections](/#view-projections) to view our confidence interview. Learn more about our assumptions and limitations [here](/about/#assumptions).

*Mobile users: We recommend using landscape mode for optimized viewing of this page.*

### Definitions
- *Infections:* Number of all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimate do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.
- *Currently infected:* Percentage of the population that are actively carrying the virus on the given date. We assume an average recovery time of 15 days.
- *Total infected:* Percentage of the population that are currently infected or have been infected at some point, by a given date.
- *Total deaths:* Total deaths per 1 million people by a given date.
- *Additional deaths:* Additional deaths per 1 million people from today until the projected date.
- *Cases score:* `mean(scaled(Δcases * |cases_%_change|), scaled(Δcases_per_1_mil * |cases_%_change|))`, where `Δcases` is the change in cases (7-day moving average) from 7 days ago and `scaled()` is a function that maps all values to -100 to 100.

[Back to Top](#top)
{% include iframe_us_maps.html %}

## Global Maps

[Click here](/maps-global) to view our Global maps.

## Europe Maps

[Click here](/maps-europe) to view our Europe maps.
