# R Value Estimates

Our data-driven model allows us to provide an estimate for the R values in each US region and country.

View our [Infections Tracker](https://covid19-projections.com/infections-tracker/) page to see histograms of our latest R estimates.

The [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R) estimates in this directory are what our model has learned for each state/region. While we only include a single value for each region in this directory, our model actually uses a weighted range of R values to make its projections. We also include an inflection date, which roughly represents the midpoint of the transition between the initial R0 and the post-mitigation R.

The initial R0 is the R value before the inflection date, while the post-mitigation R is the R value following the inflection date. The inflection date is roughly correlated to when regions implemented stay-at-home/lockdown orders, but it may not be exact. For example, New York enacted a stay-at-home order on March 22, but the inflection date our model estimated was more than a week earlier, around March 14. This agrees with various mobility reports and [our analysis](https://twitter.com/youyanggu/status/1248844841733128192) of New York City subway ridership.

Please note that this is merely an estimate based on the data. The true R values can vary widely, even day-to-day. For example, California has a lower-than-expected R0 partly because there is a significant time lag in their deaths reporting. While this does not significantly affect our projections (assuming the lag is consistent), it will result in a lower R estimate than the true value. Lastly, our post-mitigation R estimates may not accurately reflect the true situation for regions where no mitigation was applied, such as in Sweden and Brazil.
