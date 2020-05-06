# R Value Estimates

Our data-driven model allows us to provide an estimate for the initial [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R0) and post-mitigation R in each US state and 40 countries.

For each date, we provide our best estimate of the initial R0 and post-mitigation R *from data generated on that date*. For example, file `2020-04-24_r_values_us.csv` simply means that our estimates were generated on April 24, not that these are the R values on April 24. We are not providing day-by-day R estimates at this time.

View our [Infections Tracker](https://covid19-projections.com/infections-tracker/) page to see histograms of our latest R estimates.

While we only include a single value for each region in this directory, our model actually uses a weighted range of R values to make its projections. We also include an inflection date, which roughly represents the midpoint of the transition between the initial R0 and the post-mitigation R.

The initial R0 is the R value before the inflection date, while the post-mitigation R is the R value following the inflection date. The inflection date is roughly correlated to when regions implemented stay-at-home/lockdown orders, but it may not be exact. For example, New York enacted a stay-at-home order on March 22, but the inflection date our model estimated was more than a week earlier, around March 14. This agrees with various mobility reports and [our analysis](https://twitter.com/youyanggu/status/1248844841733128192) of New York City subway ridership.

## Notes

* Please note that this is merely an estimate based on the data. The true R values can vary widely, even day-to-day.
* For example, California has a lower-than-expected R0 partly because there is a significant time lag in their deaths reporting. While this does not significantly affect our projections (assuming the lag is consistent), it will result in a lower R estimate than the true value.
* Our post-mitigation R estimates may not accurately reflect the true situation for regions where no mitigation was applied, such as in Sweden and Brazil.
