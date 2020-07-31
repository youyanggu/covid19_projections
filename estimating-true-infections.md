---
layout: default
title: Estimating True Infections
permalink: /estimating-true-infections/
---

Youyang Gu
<br>*Last Updated*: July 31, 2020

## Table of Contents
* [Estimating True Infections](#estimating-true-infections)
* [Data](#data)
* [Method #1: Using Confirmed Cases + Positivity Rates](#method-1-using-confirmed-cases--positivity-rates)
* [Method #2: Using Confirmed Deaths](#method-2-using-confirmed-deaths)
* [Putting it Together](#putting-it-together)
* [Implied Infection Fatality Rate (IIFR)](#implied-infection-fatality-rate-iifr)
* [Discussion](#discussion)

## Estimating True Infections

Knowing the true number of people who are infected with COVID-19 in the US is an essential step towards understanding the disease. But estimating this number is not a simple task. The true number of infections is many times larger than the reported number of cases in the US, because the majority of people do not get tested due to several reasons: 1) they are asymptomatic, 2) they are only mildly symptomatic or 3) they do not have easy access to testing.

On this page, We will introduce the *implied infection fatality rate (IIFR)*, which is a metric computed by taking a region's reported deaths and dividing it by the true infections estimate (after accounting for the lag). To estimate the number of true COVID-19 infections in a region, we will use two different, independent methods: 

1. Based on confirmed cases ([Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)) and test positivity rate ([COVID Tracking Project](https://covidtracking.com/))
2. Based on confirmed deaths ([Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series))

Both methods yield a similar result: the true number of new infections peaked at around 400-500k new infections per day in July, compared to 300k new infections per day in March. In total, as of July 2020, we estimate over 30 million Americans have been infected at some point by the SARS-CoV-2 virus.

![True Infections Plot 3](/assets/images/estimate_true_infections_3.png)

Once we have a reasonable estimate of the true number of newly infected individuals per day, we can take the reported deaths and imply the infection fatality rate. This is explained [below](implied-infection-fatality-rate-iifr).

## Data

*Input*: We use reported cases and deaths data from [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)) and testing data from [The COVID Tracking Project](https://covidtracking.com/).

*Output*: We have uploaded the infections estimates and implied IFR calculations to [our GitHub](https://github.com/youyanggu/covid19_projections/tree/master/implied_ifr). We aim to update those files daily.

[Back to Top](#top)

## Method #1: Using Confirmed Cases + Positivity Rates

The core idea behind this method is that we can use the positivity rate to roughly determine the ratio of true infections to reported cases. The hypothesis is that as positivity rate increases, the higher the true prevalence in a region relative to the reported cases. This also makes sense intuitively: if you test everyone, then the positvity rate will be very low, and you will catch every case. But if testing is not widely available, then you will catch only the severe cases, resulting in a high positivity rate.

We believe that the relationship between positivity rate and ratio of true prevalence is monotonically increasing. Of course, the exact relationship varies from state to state and across time. But if one were to take the average across *all* of the data, one can generate a theoretical curve. We believe this relationship can be approximated by a root function, namely the square root function. We present our approximation function below.

`prevalence-ratio = 16 * sqrt(positivity-rate) + 2.5`

![Root relationship](/assets/images/estimate_true_infections_root.png)

To see if this relationship passes the "common sense test", we can take a look at the US positivity rate over time (below). In March/April, the US positivity is around 20%, which corresponds to a prevalence ratio of roughly 10x the number of reported cases when using the function above. This seems to be a reasonable estimate, and matches estimates provided [by the CDC](https://www.washingtonpost.com/health/2020/06/25/coronavirus-cases-10-times-larger/). In June, when US positivity is around 5%, the function estimates a prevalence of roughly 6x the number of reported cases, which seems reasoanble. We use a y-intercept of 2.5 to indicate minimum prevalence ratio of 2.5x to account for asymptomatic individuals.

![US positivity rate](/assets/images/estimate_true_infections_us_prevalence_ratio.png)

The next step is to map all reported cases to true new infections based on the true prevalence ratio. We can compute the true prevalence ratio simply by inserting the positivity rate into the function above. For all computation purposes, we use the 7-day average of confirmed cases and positivity rates.

As an example, let's say that the US reported 67,000 new cases with a 8.5% positivity rate on July 22. This would result in a true prevalence ratio of `16*sqrt(0.085)+2.5 = 7.16`. We can then multiply this ratio by the confirmed cases to get the true new infections. In this example, we estimate there to be 7.16 * 67,000 = ~480,000 true new infections. Because reported cases lag infections by roughly 2 weeks, we must shift the result back by two weeks. So the 480,000 true infections actually took place approximately 14 days before July 22, on July 8.

[Back to Top](#top)

### Using US Nationwide Cases + Positivity Rates

For US nationwide data, we can compute the true prevalence ratio by passing in the daily positivity rate to our approximation function above. We then multiple the true prevalence ratio by the number of confirmed cases each day to get the number of true new infections. Note that all daily numbers used are 7-day moving averages rather than the raw numbers. Finally, we shift the true new infections back by 14 days to account for reporting delays. We can now plot the results as a function of the date:

![True Infections Plot 1](/assets/images/estimate_true_infections_1.png)

### Using State-by-state Cases + Positivity Rate

Rather than using the US nationwide cases and positivity rates, we can use the state-by-state cases and positivity rates to compute the true new infections for each state using the same method described above. Below is a plot of the estimated true daily new infections for a selection of states. Using this approach, you can see that Florida and Texas are nearing the maximum daily new infections set by New York back in March.

![True Infections States](/assets/images/estimate_true_infections_states.png)

We then take the sum of all 50 states and territories to get the true US nationwide daily new infections:

![True Infections Plot 2](/assets/images/estimate_true_infections_2.png)

[Back to Top](#top)

## Method #2: Using Confirmed Deaths

The second method is the method used by *covid19-projections.com*. It uses only past reported deaths to predict future reported deaths. You can read more about our model on our [About](/about) page.

One of the outputs generated by our model is the number of true infections in each region and country. We simply take that output from our model to get our estimate of true infections in the US.

![C19Pro model infections](/assets/images/estimate_true_infections_model.png)

[Back to Top](#top)

## Putting it Together

We can now plot the two methods together and see how they compare. Note that they follow roughly the same shape and magnitude. We try to explain some of the differences below.

![True Infections Plot 3](/assets/images/estimate_true_infections_3.png)

- On average, cases were detected later in March/April compared to June/July. As a result, compared to estimates generated by only deaths data, the plot of infections based on cases lag in March/April and lead in June/July.
- Using state-by-state estimates of positivity rates and cases leads to a slight overestimate in the number of true infections in June/July. We suspect this is because of some states only reporting positive results for a subset of their tests, which artificially inflates the positivity rate and therby the prevalence ratio.

## Implied Infection Fatality Rate (IIFR)

We can use these estimates of true infections to compute the *implied infection fatality rate (IIFR)* for the US by taking the reported deaths from 28 days into the future (7-day moving average) and dividing it by the true infections (7-day moving average).

![IFR Estimate - US](/assets/images/estimate_true_infections_ifr_us.png)

We can also do this on a state-by-state basis. See below for IIFR plots for select states.

![IFR Estimate - States](/assets/images/estimate_true_infections_ifr_states.png)

[Back to Top](#top)

## Discussion

There are many explanations as to why there are more infections in June/July than in March/April. One reason is based on simple math regarding exponential growth. We started from 0 infections in February with an R0 of ~2.5. There was only a limited period of exponential growth before people began social distancing in March, which brought the Rt value under 1. The stay-at-home orders in most parts of the US were timely and effective in containing the spread and preventing further uncontained spread.

In contrast, when states reopened in May/June, there were already ~100k new infections per day. With an Rt of ~1.2 and limited intervention to mitigate the spread, new infections were able to climb to 400k+ per day in a period of 2 months.

[Back to Top](#top)

### Lower Infection Fatality Rate (IFR)

Below are a few reasons why we think the infection fatality rate (IFR) has gone down since March/April.

- Improved treatment (new drugs, better allocation of resources, more experience among staff, etc)
- Better protection of vulnerable populations ([nearly half of COVID-19 deaths](https://www.wsj.com/articles/coronavirus-deaths-in-u-s-nursing-long-term-care-facilities-top-50-000-11592306919) in March/April were in care homes)
- Lower median age of infection
- Earlier detection
