# Projections Data

Here, you will find all of our projections based on the date the projectoins were generated. Under each date directory, you will find a .csv file for each individual state/region/country. You can also look under our `combined` directory to see all of our daily projections combined in a single file.

# Evaluation

When evaluating our projections, please keep in mind the following notes and update log:

* Our estimates from early April do not incorporate reopenings and probable deaths, two factors that significantly increases the estimates. Furthermore, our early April projections only go through June.

* We send projections to the CDC every Monday using Sunday's data. For example, April 26, May 3, May 10, May 17, etc. As a result, we recommend using those projections for evaluation, since those have the highest impact and were the most carefully vetted.

* We did not submit our first projections to the CDC until April 20. While we welcome an evaluation of every projection we have ever made, we also want to point out that our projections have been constantly evolving/improving, and it wasn't until April 20 that we felt confident enough in our projections to submit to the CDC. With that said, we fully stand behind every projection we have sent to the CDC.

* One way to think of this is to view our projections starting on April 20 as the "release" version, while projections prior to April 20 were "beta" versions.

# Updates

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

2020-04-08
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

2020-03-30
* Begin project
