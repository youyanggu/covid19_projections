# Implied Infection Fatality Rate (IIFR)

**New July 29**: This is the accompanying dataset for our write-up, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](https://covid19-projections.com/estimating-true-infections/)*. We aim to update this daily as new data becomes available.

Here we introduce the concept of *implied infection fatality rate* (IIFR), and present the raw data used to compute the IIFR. IIFR is a metric computed by taking a region’s reported deaths and dividing it by the true infections estimate (after accounting for the lag). Knowing the true number of people who are infected with COVID-19 in the US is an essential step towards understanding the disease.

Read more about how we compute the implied IFR in write-up, [Estimating True Infections](https://covid19-projections.com/estimating-true-infections/).

Note: Currently, we only support the computation of IIFR for the US on a state and national level. For all other regions, we only include the implied case fatality rate, which is computed by taking the 7-day moving average of daily confirmed deaths two weeks in the future and dividing by the 7-day moving average of daily confirmed cases.

## Description of Columns
* `Confirmed` - Total reported cases
* `Deaths` - Total reported deaths
* `daily_deaths`, `daily_deaths_7day_ma` - Daily reported deaths and 7-day moving average
* `daily_confirmed`, `daily_confirmed_7day_ma` - Daily reported cases and 7-day moving average
* `daily_tests`, `daily_tests_7day_ma` - Daily reported tests and 7-day moving average
* `net_hosp`, `net_hosp_7day_ma` - Daily reported net hospitalizations and 7-day moving average (positive number means more admissions, negative number means more discharges)
* `pos_rate_7day_ma` - `daily_confirmed_7day_ma / daily_tests_7day_ma`
* `rt_estimate` - Rough estimate of the effective reproduction number, taken by taking the `pos_rate_7day_ma` and dividing it by the `pos_rate_7day_ma` from 5 days ago (the serial interval). Formula: `rt_estimate(n) = pos_rate_7day_ma(n) / pos_rate_7day_ma(n-5)`.
* `prevalence_ratio_7day_ma` - Estimate of the ratio of true infections to confirmed cases. Formula explained [here](https://covid19-projections.com/estimating-true-infections/#prevalence-ratio).
* `true_inf_est_7day_ma` - Estimate of the true number of newly infected individuals on that day, after accounting for a 14-day lag. Formula: `true_inf_est_7day_ma(n) = daily_confirmed_7day_ma(n+14) * prevalence_ratio_7day_ma(n+14)`.
* `implied_ifr_7day_ma` - Implied infection fatality rate, after accounting for a 28-day lag. Formula: `implied_ifr_7day_ma(n) = daily_deaths_7day_ma(n+28) / true_inf_est_7day_ma(n)`.

For the summary files ([example](https://github.com/youyanggu/covid19_projections/blob/master/implied_ifr/0_IIFR_Summary.csv)), we have a few additional columns:

* `cur_implied_cfr` - Current impleid CFR, calculating by taking deaths and dividing by true cases from 14 days ago: `cur_implied_ifr(n) = daily_deaths_7day_ma(n) / daily_confirmed_7day_ma(n-14)`
* `total_implied_cfr` - `Deaths / Confirmed` (total deaths / total cases)
* `cur_implied_ifr` - Current implied IFR, calculated by taking deaths and dividing by true infections from 28 days ago: `cur_implied_ifr(n) = daily_deaths_7day_ma(n) / true_inf_est_7day_ma(n-28)`
* `total_infections` - `sum(true_inf_est_7day_ma)` (Sum of new daily infections)
* `total_implied_ifr` - `Deaths / total_infections` (total deaths / total infections)
* `perc_infected` - `total_infections / population`

## Data Source

- Cases and deaths: [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
- Tests and hospitalizations: [The COVID Tracking Project](https://covidtracking.com/)
