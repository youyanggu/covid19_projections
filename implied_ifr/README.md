# Implied IFR

**New July 29**: This is still a work in progress - stay tuned for updates.

Here we introduce the concept of implied infection fatality rate (IIFR), and present the raw data used to compute the IIFR. IIFR is a metric computed by taking a region’s reported deaths and dividing it by the true infections estimate (after accounting for the lag). Knowing the true number of people who are infected with COVID-19 in the US is an essential step towards understanding the disease.

Read more about how we compute the implied IFR [here](https://covid19-projections.com/estimating-true-infections/).

Note: Currently, we only support the computation of IIFR for the US on a state and national level. For all other regions, we only include the implied case fatality rate, which is computed by taking the 7-day moving average of daily confirmed deaths two weeks in the future and dividing by the 7-day moving average of daily confirmed cases.

## Data Source

- Cases and deaths: [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
- Tests: [The COVID Tracking Project](https://covidtracking.com/)
