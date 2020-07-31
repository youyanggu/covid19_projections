---
layout: default
title: Estimating True Infections
permalink: /estimating-true-infections/
---

# Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate

By: [Youyang Gu](https://twitter.com/youyanggu)
<br>*Last Updated*: July 31, 2020

## Table of Contents
* [Introduction](#introduction)
* [Data](#data)
* [Prevalence Ratio](#prevalence-ratio)
* [Using Confirmed Deaths](#using-confirmed-deaths)
* [Putting it Together](#putting-it-together)
* [Implied Infection Fatality Rate (IIFR)](#implied-infection-fatality-rate-iifr)
* [Discussion](#discussion)
* [Conclusion](#conclusion)

## Introduction

Knowing the true number of people who are infected with COVID-19 in the US is an essential step towards understanding the disease. But estimating this number is not a simple task. The true number of infections is many times greater than the reported number of cases in the US because the majority of infected individuals do not get tested due to several reasons: 1) they are asymptomatic, 2) they are only mildly symptomatic, 3) they do not have easy access to testing, or 4) they simply do not want to.

On this page, we will introduce a simple square root function to estimate the true prevalence of COVID-19 in a region based on only the confirmed cases and test positivity ratio. We will also introduce the *implied infection fatality rate (IIFR)*, which is a metric derived by taking a region's reported deaths and dividing it by the true infections estimate (after accounting for lag).

Using this method, we estimate that the true number of new infections peaked at around 500,000 new infections per day in July, compared to 300,000 new infections per day in March. This means that the peak of infections after reopening is over 60% higher than the initial peak in March. In total, by the end of July 2020, we estimate over 35 million (1 in 10) Americans have been infected at some point by the SARS-CoV-2 virus.

Below, you can see a plot of our infection estimates for the US. We compare the results to [covid19-projections.com](https://covid19-projections.com), which uses only past reported deaths to estimate the number of true infections.

![True Infections Plot 3](/assets/images/estimate_true_infections_3.png)

Once we have a reasonable estimate of the true number of newly infected individuals per day, we can use the reported deaths to compute the implied infection fatality rate (IFFR). The IIFR for the US was above 1% in March, stabilized at around 0.6% in April-May before decreasing to ~0.25% in July. This is further explained [below](implied-infection-fatality-rate-iifr).

While we developed this method independently, this is not a novel approach. See prior work by [Peter Ellis](http://freerangestats.info/blog/2020/05/09/covid-population-incidence), [David Blake](https://medium.com/@dblake.mcg/making-the-o-zone-plots-2a83708f7d6a), and [Campbell et al](https://arxiv.org/pdf/2005.08459.pdf).

[Back to Top](#top)

## Data

*Input*: We use reported cases and deaths data from [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)) and testing data from [The COVID Tracking Project](https://covidtracking.com/).

*Output*: We have uploaded the infections estimates and implied IFR calculations to [our GitHub](https://github.com/youyanggu/covid19_projections/tree/master/implied_ifr). We aim to update those files daily. Currently, we only have IIFR estimates for the US. We are working to expand this concept to other countries.

[Back to Top](#top)

## Prevalence Ratio

The core idea behind this method is that we can use the positivity rate to roughly determine the ratio of true infections to reported cases. The hypothesis is that as positivity rate increases, the higher the true prevalence in a region relative to the reported cases. This also makes sense intuitively: if you test everyone, then the positvity rate will be very low, and you will catch every case. But if testing is not widely available, then you will catch only the severe cases, resulting in a higher positivity rate. This phenomenon is sometimes referred to as *preferential testing*.

We believe that the relationship between positivity rate and ratio of true prevalence is monotonically increasing. Of course, the exact relationship varies from state to state and across time. But if one were to take the average across *all* of the data, one can generate a theoretical curve. We believe this relationship can be approximated by a root function of the following form:

`prevalence-ratio = a * (positivity-rate)^(b) + c`

where `a`, `b`, `c` are unknown constants.

Through some basic curve fitting and trial & error, we found that the following square root approximation function works well:

`prevalence-ratio = 16 * (positivity-rate)^(0.5) + 2.5`

![Root relationship](/assets/images/estimate_true_infections_root.png)

To see if this relationship passes the "common sense test", we can take a look at the US positivity rate over time (below). In March/April, the US positivity is around 20%, which corresponds to a prevalence ratio of roughly 10x the number of reported cases when using the function above. This seems to be a reasonable estimate, and matches estimates provided [by the CDC](https://www.washingtonpost.com/health/2020/06/25/coronavirus-cases-10-times-larger/). In June, when US positivity is around 5%, the function estimates a prevalence of roughly 6x the number of reported cases, which seems reasoanble. We use a y-intercept of 2.5 to indicate minimum prevalence ratio of 2.5x to account for asymptomatic individuals.

![US positivity rate](/assets/images/estimate_true_infections_us_prevalence_ratio.png)

The next step is to map all reported cases to true new infections based on the true prevalence ratio. We can compute the true prevalence ratio simply by inserting the positivity rate into the function above. For all computation purposes, we use the 7-day average of confirmed cases and positivity rates.

As an example, let's say that the US reported 67,000 new cases with a 8.5% positivity rate on July 22. This would result in a true prevalence ratio of `16*sqrt(0.085)+2.5 = 7.16`. We can then multiply this ratio by the confirmed cases to get the true new infections. In this example, we estimate there to be 7.16 * 67,000 = ~480,000 true new infections. Because reported cases lag infections by roughly 2 weeks, we must shift the result back by two weeks. So the 480,000 true infections actually took place approximately 14 days before July 22, on July 8.

[Back to Top](#top)

### Using US Nationwide Cases + Positivity Rates

For US nationwide data, we can compute the true prevalence ratio by passing in the daily positivity rate to our approximation function above. We then multiply the true prevalence ratio by the number of confirmed cases each day to get the number of true new infections. Note that all daily numbers used are 7-day moving averages. Finally, we shift the true new infections back by 14 days to account for reporting delays. We can now plot the results as a function of the date:

![True Infections Plot 1](/assets/images/estimate_true_infections_1.png)

### Using State-by-state Cases + Positivity Rate

Rather than using the US nationwide cases and positivity rates, we can use the state-by-state cases and positivity rates to compute the true new infections for each state using the same method described above. Below is a plot of the estimated true daily new infections for a selection of states. Using this approach, you can see that Florida and Texas are nearing the maximum daily new infections set by New York back in March.

![True Infections States](/assets/images/estimate_true_infections_states.png)

We then take the sum of the infections estimates for all 50 states and territories to get the nationwide daily new infections (orange line). Note that it closely aligns with the graph generated using the US nationwide data.

![True Infections Plot 2](/assets/images/estimate_true_infections_2.png)

[Back to Top](#top)

## Using Confirmed Deaths

We can compare the previous approach to a method used by [covid19-projections.com](https://covid19-projections.com). It uses only past reported deaths to predict future reported deaths. You can read more about our model [here](https://covid19-projections.com/about).

One of the outputs generated by our model is the number of true infections in each region and country. We simply take that output from our model to get our estimate of true infections in the US.

![C19Pro model infections](/assets/images/estimate_true_infections_model.png)

[Back to Top](#top)

## Putting it Together

We can now plot the two methods together and see how they compare. Note that they follow roughly the same shape and magnitude. We try to explain some of the differences below.

![True Infections Plot 3](/assets/images/estimate_true_infections_3.png)

- On average, cases were detected later in March/April compared to June/July. As a result, compared to estimates generated by only deaths data, the plot of infections based on reported cases lag in March/April and lead in June/July.
- Using state-by-state estimates of positivity rates and cases leads to a slight overestimate in the number of true infections in June/July. We suspect this is partly because of some states (such as FL, AZ, GA) undercounting the number of negative results, which artificially inflates the positivity rate and thereby the prevalence ratio. If that factor is adjusted, it is likely that the peak will line up at slightly over 400,000 new infections per day.

[Back to Top](#top)

## Implied Infection Fatality Rate (IIFR)

We can use these estimates of true infections to compute the *implied infection fatality rate (IIFR)* for the US by taking the reported deaths from 28 days into the future (7-day moving average) and dividing it by the true infections (7-day moving average).

![IFR Estimate - US](/assets/images/estimate_true_infections_ifr_us.png)

We can also do this on a state-by-state basis. See below for IIFR plots for select states.

![IFR Estimate - States](/assets/images/estimate_true_infections_ifr_states.png)

[Back to Top](#top)

## Discussion

### Relationship between Positivity Rate and Prevalence Ratio

We developed the constants for the prevalence function (`prevalence-ratio = a * (positivity-rate)^(b) + c`) through a combination of trial & error and curve fitting. We don't believe this function is perfect. There can be other constants `a`, `b`, and `c` that may be a closer approximation of the true relationship. Because there is no "truth" value to fit the function against, we decided it is not worth trying to perfectly fit this function. As a result, we settled on a simple square root function to describe the relationship.

The exact relationship between positivity rate and prevalence ratio may be different from state to state and across time. Here is a partial list of possible factors that can cause these differences:

- Differences and changes in reporting guidelines
  - Counting multiple positive results
  - Counting multiple negative results
  - Only reporting positive results
  - Only reporting negative results
  - Only reporting Electronic Laboratory Reporting (ELR) results
- Availability of testing - the greater the number of tests (as percentage of the population), the less important the role of positivity rate
- Backlog of test results - positive tests receive priority for processing, which may skew the positivity rate upwards
- Delay/lag in test results - if tests take 1-2 weeks to be reported, then it may no longer be an accurate representation of how new infections are changing

For example, [here](https://www.tampabay.com/news/health/2020/07/28/what-is-the-positivity-rate-in-coronavirus-data-and-why-is-it-important/) is a story from the Tampa Bay Times that explores how positivity rate is reported in Florida. Meanwhile, [Georgia](https://www.covid-georgia.com/2020/07/14/georgia-elr-test-data/) has a different set of standards for test reporting. These guidelines are specific on a per-state level and may differ significantly between states, making comparison more difficult.

[Back to Top](#top)

### Higher Infections in July

There are many explanations as to why there are more infections in June/July than in March/April. One reason is based on simple math regarding exponential growth. We started from 0 infections in February with an R0 of ~2.5. There was only a limited period of exponential growth before people began social distancing in March, which quickly brought the Rt value under 1. The stay-at-home orders in most parts of the US were timely and effective in containing the spread and preventing further uncontained spread.

In contrast, when states reopened in May/June, there were already ~100k new infections per day. With an Rt of ~1.2 and limited intervention to mitigate the spread, new infections were able to climb to 400k+ per day in a period of two months. In layman terms, we started from a much higher point in May and had a longer period of time to reach the peak.

[Back to Top](#top)

### Lower IIFR Over Time

The IIFR in the US decreased from over 1% in March to 0.25% in July. Below, we present a few explanations to why the IIFR in the US has decreased significantly since March/April.

- Improved treatment (new drugs, better allocation of resources, more experience among staff, etc)
- Better protection of vulnerable populations ([nearly half of COVID-19 deaths](https://www.wsj.com/articles/coronavirus-deaths-in-u-s-nursing-long-term-care-facilities-top-50-000-11592306919) in March/April were in care homes)
- Lower median age of infection
- Earlier detection

The above are explanations that would explain a *true* decrease in IFR. Below are some reasons that could skew the IIFR lower, but not change the true IFR:

- More comprehensive reporting of confirmed cases
- Changes in the distribution of age groups tested (e.g. more younger people getting tested would skew IIFR down)
- Inflation of the test positivity rate (e.g. double-counting positives, not reporting negatives, etc)
- Longer lag in death reporting
- Underreporting of deaths

[Back to Top](#top)

## Conclusion

To conclude, we presented a simple heuristic that estimates the true prevalence of COVID-19 infections in a region. We also introduced the *implied infection fatality rate (IIFR)* that estimates the fatality rate as implied by the reported deaths and true prevalence.

Using this methodology, we found that the prevalence is higher in the US during June/July (peak of ~500,000 infections/day) than in March/April (peak of ~300,000 new infections/day). However, the implied fatality rate is much lower in June/July (~0.25% IIFR) than in March/April (~1% IIFR).

The data and results used on this page can be found [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/implied_ifr).
