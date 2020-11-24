---
layout: default
title: Estimating True Infections - Revisited
permalink: /estimating-true-infections-revisited/
---

# Estimating True Infections Revisited: A Simple Heuristic to Estimate True Infections

By: [Youyang Gu](https://twitter.com/youyanggu)
<br>November 24, 2020

## Table of Contents
* [Main Conclusions](#main-conclusions)
* [Introduction](#introduction)
* [Disclaimers](#disclaimers)
* [Data](#data)
* [Prevalence Ratio](#prevalence-ratio)
* [Discussion](#discussion)
* [Conclusion](#conclusion)

In July 2020, we released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)*. We described a simple heuristic that can be used to estimate true infections for every state in the US based on the confirmed cases and test positivity rate. Now, in November 2020, we are posting a revision of the methods based on new data that have come to light over the course of the past four months.

## Introduction

Knowing the true number of people who are infected with COVID-19 in the US is an essential step towards understanding the disease. But estimating this number is not a simple task. The true number of infections is many times greater than the reported number of cases in the US because the majority of infected individuals do not get tested due to several reasons: 1) they are asymptomatic, 2) they are only mildly symptomatic, 3) they do not have easy access to testing, or 4) they simply do not want to get tested.

On this page, we introduce a simple square root function to estimate the true prevalence of COVID-19 in a region based on only the confirmed cases and test positivity rate: `true-new-daily-infections = daily-confirmed-cases * (1500 / (day_idx + 50) * (positivity-rate)^(0.5) + 2)`, where `day_idx` is the number of days since February 12, 2020 (2 weeks before the first confirmed community transmission in the US). We will also introduce the *implied infection fatality rate (IIFR)*, which is a metric derived by taking a region's reported deaths and dividing it by the true infections estimate (after accounting for lag).

Using this method, we estimate that the true number of new infections peaked at close to 300,000 new infections per day in both the March-April and June-August waves. The similarity in the peak matches the hospitalization data, which also shows a similar peak for the two waves. In contrast, we estimate that the October-December wave reached over 500,000 new infectious per day, about twice as high as the first two waves. In total, by mid-November 2020, we estimate around 50 million (1 in 7) Americans have been infected at some point by the SARS-CoV-2 virus.

Below, you can see a plot of our infection estimates for the US.

Once we have a reasonable estimate of the true number of newly infected individuals per day, we can use the reported deaths to compute the implied infection fatality rate (IFFR). The IIFR for the US was above 1% in March, stabilized at around 0.6% in April-May before decreasing to ~0.4% in July-August. Note that our IIFR estimate does not take into account excess/unreported COVID-19 deaths, so it is likely a lower bound for the true IFR. This is further explained [below](#implied-infection-fatality-rate-iifr).

## Disclaimers

- All of the work presented on this page has not been peer-reviewed, and so we encourage reading this with a healthy dose of skepticism. We hope that the reader can make their own conclusions based on the evidence we present. This is just one possible take on the situation, and the results are subject to change based on new data/evidence.

- The outputs from this analysis are only as good as the provided input data. If states, for example, underreport/misrreport COVID-19 cases, then that could skew the outcome of this analysis. Hence, we call on all states to follow national guidelines and report data in a honest, comprehensive, and consistent manner.

- This approach was optimized on US data. It is not necessarily applicable to countries outside the United States, where testing guidelines/procedures may be drastically different. One may need to refit the prevalence curve to suit each country.

- While all the methods on this page were developed independently, we want to note that this is not a novel approach. See prior work by [Peter Ellis](http://freerangestats.info/blog/2020/05/09/covid-population-incidence), [David Blake](https://medium.com/@dblake.mcg/making-the-o-zone-plots-2a83708f7d6a), and [Campbell et al](https://arxiv.org/pdf/2005.08459.pdf).

- Note that our use of the term *infection fatality rate (IFR)* refers to true deaths divided by true infections. It is not age-adjusted. As a result, if there is an increasing prevalence of the disease in a younger population, then the IFR will decrease, despite the deadliness of the virus remaining unchanged among a particular age group. It is likely that the fatality rate for a given age group have not changed significantly.

- To compute our estimates of the *implied infection fatality rate (IIFR)*, we use only reported deaths in the numerator. If a state is significantly undercounting COVID-19 deaths, then our estimates will likely underestimate the true IFR. Since most states are [undercounting](https://www.nytimes.com/interactive/2020/05/05/us/coronavirus-death-toll-us.html) COVID-19 deaths, our IIFR estimate is closer to a lower bound for the true infection fatality rate. For example, if true deaths is 50% higher than reported deaths, then the true IFR will be roughly 50% higher than the IIFR. To get a better understanding of the true deaths caused by COVID-19, we recommend looking into [excess deaths](https://www.cdc.gov/nchs/nvss/vsrr/covid19/excess_deaths.htm), something we do not do in this analysis.

[Back to Top](#top)

## Data

*Input*: We use reported cases and testing data from [The COVID Tracking Project](https://covidtracking.com/data/download/). For county infection estimates, we use county case data from [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series).

*Output*: We have uploaded the infections estimates to [our GitHub](https://github.com/youyanggu/covid19_projections/tree/master/infection_estimates).

[Back to Top](#top)

## Prevalence Ratio

The core idea behind this method is that we can use the positivity rate to roughly determine the ratio of true infections to reported cases. The hypothesis is that as positivity rate increases, the higher the true prevalence in a region relative to the reported cases. This also makes sense intuitively: if you test everyone, then the positvity rate will be very low, and you will catch every case. But if testing is not widely available, then you will catch only the severe cases, resulting in a higher positivity rate. This phenomenon is sometimes referred to as *preferential testing*.

But as time goes on and testing becomes more accessible, the positivity rate matters less and less in the determination of the true prevalence ratio. Intuitively, this makes sense as well: if everyone who wants a test can get a test, then the prevalence ratio will be constant regardless of what percentage of the tests result in a positive result. The only reason the prevalence ratio would increase is if the number of undetected cases increase in proportion with the detected cases.

We believe that the relationship between positivity rate and ratio of true prevalence is monotonically increasing. Of course, the exact relationship varies from state to state and across time. But if one were to take the average across *all* of the data, one can generate a theoretical curve. We believe this relationship can be approximated by a root function of the following form:

`prevalence-ratio = a * (positivity-rate)^(b) + c`

where `a`, `b`, `c` are unknown constants.

Through curve fitting on historical test positivity and serological surveys, as well as trial & error, we found that the following square root approximation function works well:

`prevalence-ratio = (1500 / (day_idx + 50) * (positivity-rate)^(0.5) + 2`,

where `day_idx` is the number of days since February 12, 2020 (2 weeks before the first confirmed community transmission in the US).

To see if this relationship passes the "common sense test", we can take a look at the US positivity rate over time (below). In March/April, the US positivity is around 20%, which corresponds to a prevalence ratio of roughly 10x the number of reported cases when using the function above. This seems to be a reasonable estimate, and matches estimates provided [by the CDC](https://www.washingtonpost.com/health/2020/06/25/coronavirus-cases-10-times-larger/). In New York and New Jersey during this period, test positivity was around 40-50%, which corresponds to a roughly 12-15x prevalence (later substantiated by [serology surveys](https://www.nytimes.com/2020/04/23/nyregion/coronavirus-antibodies-test-ny.html)). In June, when test is more widely available and the US positivity rate is ~5%, the function estimates a prevalence of roughly 4x the number of reported cases. We use a y-intercept of 2 to indicate minimum prevalence ratio of 2x to account for asymptomatic individuals (~40% according to [the CDC](https://www.cdc.gov/coronavirus/2019-ncov/hcp/planning-scenarios.html)).

The next step is to map all reported cases to true new infections based on the true prevalence ratio. We can compute the true prevalence ratio simply by inserting the positivity rate into the function above. We then multiple the ratio by the daily confirmed cases to get the true daily infections:

`true-new-daily-infections = daily-confirmed-cases * prevalence-ratio`

For all computation purposes, we use the 7-day average of confirmed cases and positivity rates. Combining the two functions from above, we get:

`true-new-daily-infections = daily-confirmed-cases * (1500 / (day_idx + 50) * (positivity-rate)^(0.5) + 2)`

As an example, let's say that the US reported 67,000 new cases with a 8.5% positivity rate on July 22. This would result in a true prevalence ratio of `(1500 / (160 + 50) * s qrt(0.085) + 2 = 4.1`. We can then multiply this ratio by the confirmed cases to get the true new infections. In this example, we estimate there to be 4.1 * 67,000 = ~275,000 true new infections. Because reported cases lag infections by roughly 2 weeks, we must shift the result back by two weeks. So the 275,000 true infections actually took place approximately 14 days before July 22, on July 8.

[Back to Top](#top)

### Using US Nationwide Cases + Positivity Rates

For US nationwide data, we can compute the true prevalence ratio by passing in the daily positivity rate to our approximation function above. We then multiply the true prevalence ratio by the number of confirmed cases each day to get the number of true new infections. Note that all daily numbers used are 7-day moving averages. Finally, we shift the true new infections back by 14 days to account for reporting delays. We can now plot the results as a function of the date:

### Using State-by-state Cases + Positivity Rate

Rather than using the US nationwide cases and positivity rates, we can use the state-by-state cases and positivity rates to compute the true new infections for each state using the same method described above. Below is a plot of the estimated true daily new infections for a selection of states.

We then take the sum of the infections estimates for all 50 states and territories to get the nationwide daily new infections (orange line). Note that it closely aligns with the graph generated using the US nationwide data.

[Back to Top](#top)

## Discussion

## Conclusion

To conclude, we presented a simple heuristic that estimates the true prevalence of COVID-19 infections in a region.

Using this methodology, we found that the prevalence is roughly equal in the US during June/July and during in March/April (peak of ~300,000 new infections/day). However, the implied fatality rate is lower in June/July (~0.4% IIFR) than in March/April (~1% IIFR).

While this is by no means a comprehensive study, we hope this work can help other scientists and researchers better understand the changing dynamics of this disease over time.

The data and results used on this page can be found [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/infection_estimates).
