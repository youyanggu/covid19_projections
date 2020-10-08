# Projections Data

Here, you will find the raw data for our [covid19-projections.com](https://covid19-projections.com) projections, ordered by the date the projections were generated. Under each date directory, you will find a .csv file for each individual state/region/country. You can also look under our `combined` directory to see all of our daily projections combined in a single file. The directories are further subdivided by global countries and subregions (US counties and Canadian provinces).

# Column Descriptions

* `actual_deaths` - Daily deaths as reported by [Johns Hopkins University CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
* `total_deaths` - Cumulative deaths as reported by Johns Hopkins University CSSE
* `predicted_deaths_mean`, `predicted_deaths_lower`, `predicted_deaths_upper` - Mean, 2.5th, and 97.5th percentile of our daily deaths projections
* `predicted_total_deaths_mean`, `predicted_total_deaths_lower`, `predicted_total_deaths_upper` (Since 2020-04-02) - Mean, 2.5th, and 97.5th percentile of our cumulative deaths projections
* `predicted_new_infected_mean`, `predicted_new_infected_lower`, `predicted_new_infected_upper` (Since 2020-04-08) - Mean, 2.5th, and 97.5th percentile of our estimates for the total number of newly infected individuals on that day. This is based on the date an individual is *first exposed*. Note that these estimates include all infections, not just those who tested positive.
* `predicted_current_infected_mean`, `predicted_current_infected_lower`, `predicted_current_infected_upper` (Since 2020-04-08) - Mean, 2.5th, and 97.5th percentile of our estimates for the total number of individuals that are infected on that day. This is the sum of the past 15 days of newly infected individuals
* `predicted_total_infected_mean`, `predicted_total_infected_lower`, `predicted_total_infected_upper` (Since 2020-04-08) - Mean, 2.5th, and 97.5th percentile of our estimates for the total number of individuals that have ever been infected. This is the cumulative sum of the newly infected individuals
* `r_values_mean` (since 2020-05-15), `r_values_lower` (since 2020-07-30), `r_values_upper` (since 2020-07-30) - Mean, lower and upper bound estimates of the Rt value on that day. Starting on 2020-08-24, we began including Rt estimates for the future as well. Note that our Rt lower and upper bounds tend to be on the narrow side.

# Notes

* Projections in this repository are rounded to the nearest integer, and hence is missing decimal precision. To avoid rounding errors, we recommend using the cumulative deaths to perform computations on incident deaths (e.g. weekly incident deaths).

* Our estimates from early April do not incorporate reopenings and probable deaths, two factors that significantly increases the estimates. Furthermore, our April 1-7 projections only go through June 30. Starting on April 8, our projections were extended to August 4.

* Our first projections on April 1 do not have an upper/lower bound.

* We added estimates of infected individuals starting on April 8.

* We added estimates of the R_t value starting on May 15.

* We send projections to the CDC every Monday using Sunday's data. For example, April 26, May 3, May 10, May 17, etc. As a result, we recommend using those projections for evaluation, since those have the highest impact and were the most carefully vetted. See our [open source evaluation](https://github.com/youyanggu/covid19-forecast-hub-evaluation).

# Updates

2020-10-05
* Final model update (using data from 2020-10-04). For more information, read [Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later). Follow [@youyanggu](https://twitter.com/youyanggu) on Twitter for continued COVID-19 insights. Thank you for your support over the past year.

2020-07-22
* We released a major update that tries to better account for increases in cases and deaths from the reopening. See [Update Notes on Twitter](https://twitter.com/youyanggu/status/1286421296474202115)

2020-07-08
* Extended projection end date from October 1 to November 1

2020-06-23
* We have open-sourced the underlying [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator) behind our model

2020-06-16
* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models’ historical point forecasts in a transparent, rigorous, and non-biased manner

2020-06-15
* Switch main data source from Johns Hopkins [Daily Reports](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports) to Johns Hopkins [Time Series Summary](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)

2020-06-11
* Extended projection end date from September 1 to October 1

2020-05-26
* Add 7 new countries (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), 2 Canadian provinces (Alberta, British Columbia), and 20 US counties

2020-05-25
* Increase projected end date from August 4 to September 1

2020-05-19
* Add subregion projections (14 US counties + Ontario/Quebec)

2020-05-16
* Add estimate for the effective reproduction value (R_t) over time

2020-05-12
* Add projections for 23 additional countries: Algeria, Argentina, Bangladesh, Chile, Colombia, Dominican Republic, Ecuador, Egypt, Iceland, Israel, Japan, Malaysia, Moldova, Morocco, Nigeria, Pakistan, Panama, Peru, Saudi Arabia, Serbia, South Africa, South Korea, Ukraine

2020-04-24
* Forecasts added to the [CDC website](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html)

2020-04-23
* Incorporate probable deaths into projections, following updated [CDC guidelines](https://www.cdc.gov/coronavirus/2019-ncov/cases-updates/cases-in-us.html)

2020-04-20
* First projections submitted to the Centers for Disease Control and Prevention (CDC).

2020-04-15
* Incorporate the relaxing of social distancing in June (see our [Assumptions](/about#assumptions) page)

2020-04-13
* Switch main data source from [COVID Tracking Project](https://covidtracking.com/) to [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports)

2020-04-12
* Add Norway and Russia to projections

2020-04-09
* Increase projected end date from June 30 to August 4
* Add plots for the number of infected individuals

2020-04-07
* Add projections for all European Union countries and 7 additional countries: Brazil, Canada, India, Indonesia, Mexico, Philippines, Turkey

2020-04-05
* Launch [covid19-projections.com](https://covid19-projections.com/)

2020-04-04
* Separate global data from US data

2020-04-03
* Add 9 international countries for projections: Belgium, France, Germany, Iran, Italy, Netherlands, Spain, Switzerland, United Kingdom

2020-04-02
* Add lower and upper bounds to projections; also project date of peak deaths
* Incorporate international data and add projections for Italy

2020-04-01
* Incorporate US states data and add projections for every state

2020-03-31
* Add first projections for New York and California
* Initial projection end date is June 30

2020-03-30
* Begin project
