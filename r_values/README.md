# Reproduction Number (R) Estimates

**May 15 Update:** For a time series of the effective reproduction number (R_t) over time for every region, use our [`projections`](/projections) directory. This data available starting on May 15 projections.

Our data-driven model allows us to provide an estimate for the initial [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R0) and post-mitigation R in each US state and 40 countries.

For each date, we provide our best estimate of the initial R0 and post-mitigation R *from data generated on that date*. For example, file `2020-04-24_r_values_us.csv` simply means that our estimates were generated on April 24, not that these were the R values on April 24.

View our [Infections Tracker](https://covid19-projections.com/infections-tracker/) page to see histograms of our latest R estimates. See our [Model Details](https://covid19-projections.com/model-details/) page to learn more about how our model generates these estimates.

While we only include a single value for each region in this directory, our model actually uses a weighted range of R values to make its projections. We also include an inflection date, which roughly represents the midpoint of the transition between the initial R0 and the post-mitigation R.

The initial R0 is the R value before the inflection date, while the post-mitigation R is the R value following the inflection date. The inflection date is roughly correlated to when regions implemented stay-at-home/lockdown orders, but it may not be exact. For example, New York enacted a stay-at-home order on March 22, but the inflection date our model estimated was more than a week earlier, around March 14. This agrees with various mobility reports and [our analysis](https://twitter.com/youyanggu/status/1248844841733128192) of New York City subway ridership.

## Notes

* Please note that this is merely an estimate based on the data. The true R values can vary widely, even day-to-day.
* Our initial R0 estimate is calculated based on all transmissions up to the inflection date. So if there is a gradual decline in transmission in the days/weeks leading up to the inflection date, it will result in a lower estimated R0 value. The mirror effect applies to the post-mitigation R.
* Because these estimates are generated from daily death reports, they are highly sensitive to how deaths are being reported by each state/country. For example, California has a lower-than-expected R0 partly because there is a significant time lag in their deaths reporting. While this does not significantly affect our projections (assuming the lag is consistent), it will result in a lower R estimate than the true value.
* Our post-mitigation R estimates may not accurately reflect the true situation for regions where no mitigation was applied, such as in Sweden and Brazil.
* Starting on May 19, 2020, we are also including R0 and post-mitigation R estimates for select US counties and global regions.
