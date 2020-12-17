# US Infections Estimate

**December 17, 2020 Update:** If you only need the *latest* estimates and not our *past* estimates, you can download our latest estimates from our [new, slimmed-down repo](https://github.com/youyanggu/covid19-infection-estimates-latest). That repository is much smaller (~500MB) compared to this one (~4GB). If you need the entire history of past estimates, please continue to use this repository.

In this folder you will find the raw estimates of true infections in the US. We use confirmed cases and testing data from [The COVID Tracking Project](https://covidtracking.com/data/download) to generate these estimates.

The raw data files are located in: `latest_all_estimates_states.csv` and `latest_all_estimates_states.csv`. You can find the historical estimates in the [`past_estimates`](past_estimates) directory. You can also find the latest county-by-county estimates in the [`counties`](counties) directory. The column descriptions are below:

## Column Descriptions

* `total_cases` - (Column added Nov 22) Total confirmed cases (cumulative). Corresponds to the `positive` column in The COVID Tracking Project. 
* `total_deaths` - (Column added Nov 24) Total deaths (cumulative). Corresponds to the `death` column in The COVID Tracking Project. 
* `total_tests` - (Column added Nov 22) Total test results (cumulative). Corresponds to the `totalTestResults` column in The COVID Tracking Project. This is the unadjusted test numbers.
* `current_hospitalized` - (Column added Dec 2) Currently hospitalized. Corresponds to the `hospitalizedCurrently` column in The COVID Tracking Project.
* `daily_positive_7day_ma` - Daily confirmed cases (7 day moving average)
* `daily_deaths_7day_ma` - (Column added Nov 24) Daily deaths (7 day moving average)
* `daily_tests_7day_ma` - Daily tests (7 day moving average). This is the adjusted test numbers.
* `positivity_rate_orig_7day_ma` - Unadjusted positivity rate (cases / tests)
* `positivity_rate_7day_ma` - Adjusted positivity rate (cases / tests). It attempts to correct for the [differences](https://covidtracking.com/about-data/total-tests) in test reporting from state to state. Learn more about our adjustments [here](https://covid19-projections.com/estimating-true-infections-revisited/#adjusted-test-positivity).
* `prevalence_ratio_mean`, `prevalence_ratio_lower`, `prevalence_ratio_upper` - Estimates the ratio of the number of true infections compared to confirmed cases. When multiplied with the daily confirmed cases (daily_positive_7day_ma), it provides an estimate of the true infections from ~10 days prior (due to the lag in reporting).
* `rt_mean` - Effective reproduction number (Rt) estimate. This is computed by taking the ratio of the current positivity rate (`positivity_rate_7day_ma`) with the positivity rate from 5 days prior. We use 5 days because that is the approximate serial interval for COVID-19.
* `new_infected_mean`, `new_infected_lower`, `new_infected_upper` - Mean, lower and upper bounds of our estimates for the total number of newly infected individuals on that day. This is based on the date an individual is *first exposed*. Note that these estimates include all infections, not just those who tested positive.
* `current_infected_mean`, `current_infected_lower`, `current_infected_upper` - Mean, lower and upper bounds of our estimates for the total number of individuals that are infected on that day. This is the sum of the past 15 days of newly infected individuals
* `perc_current_infected_mean`, `perc_current_infected_lower`, `perc_current_infected_upper` - current_infected_mean / population
* `total_infected_mean`, `total_infected_lower`, `total_infected_upper` - Mean, lower and upper bounds of our estimates for the total number of individuals that have ever been infected. This is the cumulative sum of the newly infected individuals
* `perc_total_infected_mean`, `perc_total_infected_lower`, `perc_total_infected_upper` - total_infected_mean / population)
