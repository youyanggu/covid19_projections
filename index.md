We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for over 99% of all global COVID-19 deaths.

Note that our infections estimate includes all infected individuals, not just those that took a COVID-19 test kit and tested positive. The vast majority of infected individuals do not get tested, and thus do not get reported as a positive case. As of mid-May, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 29:** We ran a simulation on what would happen if just 20% of infected individuals reduced their own transmission by 25% (such as by self-quarantining immediately after showing symptoms). US deaths would be 30% lower by May 29, and up to 50% lower by September. See the results [here](/us-self-quarantine).

* **May 27:** We added [7 new countries](/#global-projections) (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), [2 Canadian provinces](/#global-projections) (Alberta and British Columbia), and [20 US counties](/#us-counties). We now have projections for 71 countries (>99% of all global COVID-19 deaths), 4 Canadian provinces (99% of Canadian COVID-19 deaths), 56 US states and territories, and 34 US counties (including the top 30 most populous counties).

* **May 26:** We have extended our projections to September 1, 2020.

* **May 25:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 22:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729), [widespread reopenings](https://www.wsj.com/articles/coronavirus-latest-news-05-20-2020-11589963481), [unreported care home deaths](https://www.economist.com/europe/2020/05/09/many-covid-deaths-in-care-homes-are-unrecorded), [increased efforts for contact tracing](https://www.npr.org/sections/health-shots/2020/04/28/846736937/we-asked-all-50-states-about-their-contact-tracing-capacity-heres-what-we-learne), and [conflated testing numbers](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 31 (1am ET):
<p align="center">
  Current Total: <b>103,773</b> deaths | Projected Total: <b>200,443 deaths by Sep 1, 2020</b> (Range: 127-336k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 23 being the most likely date.

Last updated: May 31, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              110,000 |         Jun 6, 2020 |
|              120,000 |        Jun 17, 2020 |
|              125,000 |        Jun 23, 2020 |
|              130,000 |        Jun 28, 2020 |
|              140,000 |         Jul 8, 2020 |
|              150,000 |        Jul 18, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |          9% |        76% |         92% |        97% |         98% |        99% |
|              150,000 |         <1% |         8% |         39% |        63% |         72% |        78% |
|              175,000 |         <1% |        <1% |          9% |        34% |         49% |        57% |
|              200,000 |         <1% |        <1% |         <1% |        16% |         31% |        42% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         10% |        21% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         8% |
|              350,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 63 countries (including all 27 European Union countries).

### US

| [United States](us) |  |  |
| --- | --- | --- |
| [Alabama](us-al) | [Kentucky](us-ky) | [Ohio](us-oh) |
| [Alaska](us-ak) | [Louisiana](us-la) | [Oklahoma](us-ok) |
| [Arizona](us-az) | [Maine](us-me) | [Oregon](us-or) |
| [Arkansas](us-ar) | [Maryland](us-md) | [Pennsylvania](us-pa) |
| [California](us-ca) | [Massachusetts](us-ma) | [Puerto Rico](us-pr) |
| [Colorado](us-co) | [Michigan](us-mi) | [Rhode Island](us-ri) |
| [Connecticut](us-ct) | [Minnesota](us-mn) | [South Carolina](us-sc) |
| [Delaware](us-de) | [Mississippi](us-ms) | [South Dakota](us-sd) |
| [District Of Columbia](us-dc) | [Missouri](us-mo) | [Tennessee](us-tn) |
| [Florida](us-fl) | [Montana](us-mt) | [Texas](us-tx) |
| [Georgia](us-ga) | [Nebraska](us-ne) | [Utah](us-ut) |
| [Guam](us-gu) | [Nevada](us-nv) | [Vermont](us-vt) |
| [Hawaii](us-hi) | [New Hampshire](us-nh) | [Virgin Islands](us-vi) |
| [Idaho](us-id) | [New Jersey](us-nj) | [Virginia](us-va) |
| [Illinois](us-il) | [New Mexico](us-nm) | [Washington](us-wa) |
| [Indiana](us-in) | [New York](us-ny) | [West Virginia](us-wv) |
| [Iowa](us-ia) | [North Carolina](us-nc) | [Wisconsin](us-wi) |
| [Kansas](us-ks) | [North Dakota](us-nd) | [Wyoming](us-wy) |

### US Counties

| US Counties |  |  |
| --- | --- | --- |
| [AZ - Maricopa](/us-az-maricopa) | [FL - Orange](/us-fl-orange) | [NY - Nassau](/us-ny-nassau) |
| [CA - Alameda](/us-ca-alameda) | [FL - Palm Beach](/us-fl-palm-beach) | [NY - New York City](/us-ny-new-york-city) |
| [CA - Los Angeles](/us-ca-los-angeles) | [IL - Cook](/us-il-cook) | [NY - Suffolk](/us-ny-suffolk) |
| [CA - Orange](/us-ca-orange) | [LA - Orleans](/us-la-orleans) | [NY - Westchester](/us-ny-westchester) |
| [CA - Riverside](/us-ca-riverside) | [MA - Middlesex](/us-ma-middlesex) | [PA - Philadelphia](/us-pa-philadelphia) |
| [CA - Sacramento](/us-ca-sacramento) | [MA - Suffolk](/us-ma-suffolk) | [TX - Bexar](/us-tx-bexar) |
| [CA - San Bernardino](/us-ca-san-bernardino) | [MI - Wayne](/us-mi-wayne) | [TX - Dallas](/us-tx-dallas) |
| [CA - San Diego](/us-ca-san-diego) | [NJ - Bergen](/us-nj-bergen) | [TX - Harris](/us-tx-harris) |
| [CA - Santa Clara](/us-ca-santa-clara) | [NJ - Essex](/us-nj-essex) | [TX - Tarrant](/us-tx-tarrant) |
| [FL - Broward](/us-fl-broward) | [NJ - Hudson](/us-nj-hudson) | [WA - King](/us-wa-king) |
| [FL - Hillsborough](/us-fl-hillsborough) | [NV - Clark](/us-nv-clark) |
| [FL - Miami-Dade](/us-fl-miami-dade) | [NV - Washoe](/us-nv-washoe) |

[Back to Top](#top)

### Global Projections

| [Canada](/canada) |  |
| --- | --- |
| [Alberta](/canada-alberta) | [Ontario](/canada-ontario) |
| [British Columbia](/canada-british-columbia) | [Quebec](/canada-quebec) |

<br />

| Europe |  |  |
| --- | --- | --- |
| [Austria](/austria) | [Greece](/greece) | [Poland](/poland) |
| [Belarus](/belarus) | [Hungary](/hungary) | [Portugal](/portugal) |
| [Belgium](/belgium) | [Iceland](/iceland) | [Romania](/romania) |
| [Bulgaria](/bulgaria) | [Ireland](/ireland) | [Serbia](/serbia) |
| [Croatia](/croatia) | [Italy](/italy) | [Slovakia](/slovakia) |
| [Cyprus](/cyprus) | [Latvia](/latvia) | [Slovenia](/slovenia) |
| [Czechia](/czechia) | [Lithuania](/lithuania) | [Spain](/spain) |
| [Denmark](/denmark) | [Luxembourg](/luxembourg) | [Sweden](/sweden) |
| [Estonia](/estonia) | [Malta](/malta) | [Switzerland](/switzerland) |
| [Finland](/finland) | [Moldova](/moldova) | [Ukraine](/ukraine) |
| [France](/france) | [Netherlands](/netherlands) | [United Kingdom](/united-kingdom) |
| [Germany](/germany) | [Norway](/norway) |

<br />

| Rest of World |  |  |
| --- | --- | --- |
| [Algeria](/algeria) | [Ecuador](/ecuador) | [Nigeria](/nigeria) |
| [Argentina](/argentina) | [Egypt](/egypt) | [Pakistan](/pakistan) |
| [Australia](/australia) | [Honduras](/honduras) | [Panama](/panama) |
| [Bangladesh](/bangladesh) | [India](/india) | [Peru](/peru) |
| [Bolivia](/bolivia) | [Indonesia](/indonesia) | [Philippines](/philippines) |
| [Brazil](/brazil) | [Iran](/iran) | [Russia](/russia) |
| [Canada](/canada) | [Israel](/israel) | [Saudi Arabia](/saudi-arabia) |
| [Chile](/chile) | [Japan](/japan) | [South Africa](/south-africa) |
| [China](/china) | [Kuwait](/kuwait) | [South Korea](/south-korea) |
| [Colombia](/colombia) | [Malaysia](/malaysia) | [Turkey](/turkey) |
| [Cuba](/cuba) | [Mexico](/mexico) | [United Arab Emirates](/united-arab-emirates) |
| [Dominican Republic](/dominican-republic) | [Morocco](/morocco) |

[Back to Top](#top)

### US Summary

States are ordered by descending projected deaths (by September 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          103,773 |                   200,443 |                     604 |                     96,670 |                                       93% |                               127,736 |                                335,902 |
|                 [New York](/us-ny) |           29,710 |                    32,945 |                   1,694 |                      3,235 |                                       11% |                                30,337 |                                 39,329 |
|               [New Jersey](/us-nj) |           11,634 |                    14,988 |                   1,687 |                      3,354 |                                       29% |                                12,677 |                                 18,192 |
|                 [Illinois](/us-il) |            5,330 |                    13,541 |                   1,069 |                      8,211 |                                      154% |                                 8,218 |                                 19,705 |
|               [California](/us-ca) |            4,144 |                    12,982 |                     329 |                      8,838 |                                      213% |                                 5,659 |                                 29,302 |
|            [Massachusetts](/us-ma) |            6,768 |                    10,119 |                   1,456 |                      3,351 |                                       50% |                                 7,651 |                                 15,530 |
|             [Pennsylvania](/us-pa) |            5,537 |                     9,681 |                     756 |                      4,144 |                                       75% |                                 6,550 |                                 14,872 |
|                     [Ohio](/us-oh) |            2,149 |                     7,759 |                     664 |                      5,610 |                                      261% |                                 3,669 |                                 15,664 |
|                  [Florida](/us-fl) |            2,447 |                     7,652 |                     356 |                      5,205 |                                      213% |                                 3,406 |                                 17,159 |
|                 [Michigan](/us-mi) |            5,464 |                     6,985 |                     699 |                      1,521 |                                       28% |                                 5,899 |                                  9,865 |
|                 [Maryland](/us-md) |            2,509 |                     6,193 |                   1,024 |                      3,684 |                                      147% |                                 3,278 |                                 11,389 |
|                  [Indiana](/us-in) |            2,125 |                     5,752 |                     854 |                      3,627 |                                      171% |                                 2,953 |                                 10,666 |
|                  [Georgia](/us-ga) |            2,004 |                     5,591 |                     527 |                      3,587 |                                      179% |                                 2,794 |                                 11,011 |
|              [Connecticut](/us-ct) |            3,912 |                     5,282 |                   1,482 |                      1,370 |                                       35% |                                 4,353 |                                  7,153 |
|                    [Texas](/us-tx) |            1,652 |                     5,253 |                     181 |                      3,601 |                                      218% |                                 2,542 |                                 11,602 |
|                 [Virginia](/us-va) |            1,370 |                     4,841 |                     567 |                      3,471 |                                      253% |                                 1,999 |                                  9,995 |
|                [Minnesota](/us-mn) |            1,036 |                     4,621 |                     819 |                      3,585 |                                      346% |                                 1,889 |                                  8,506 |
|                  [Arizona](/us-az) |              904 |                     4,396 |                     604 |                      3,492 |                                      386% |                                 1,797 |                                  7,982 |
|                [Louisiana](/us-la) |            2,786 |                     4,073 |                     876 |                      1,287 |                                       46% |                                 3,111 |                                  5,977 |
|                 [Colorado](/us-co) |            1,443 |                     3,959 |                     687 |                      2,516 |                                      174% |                                 2,028 |                                  7,626 |
|           [North Carolina](/us-nc) |              929 |                     3,953 |                     377 |                      3,024 |                                      326% |                                 1,729 |                                  8,334 |
|                 [Missouri](/us-mo) |              774 |                     3,133 |                     510 |                      2,359 |                                      305% |                                 1,369 |                                  5,875 |
|              [Mississippi](/us-ms) |              723 |                     3,080 |                   1,035 |                      2,357 |                                      326% |                                 1,374 |                                  5,223 |
|                  [Alabama](/us-al) |              618 |                     2,326 |                     474 |                      1,708 |                                      276% |                                 1,050 |                                  4,540 |
|                     [Iowa](/us-ia) |              531 |                     2,192 |                     695 |                      1,661 |                                      313% |                                   919 |                                  3,873 |
|           [South Carolina](/us-sc) |              487 |                     1,950 |                     379 |                      1,463 |                                      300% |                                   822 |                                  4,125 |
|             [Rhode Island](/us-ri) |              711 |                     1,861 |                   1,757 |                      1,150 |                                      162% |                                 1,192 |                                  2,692 |
|                [Wisconsin](/us-wi) |              588 |                     1,759 |                     302 |                      1,171 |                                      199% |                                   895 |                                  3,783 |
|               [Washington](/us-wa) |            1,118 |                     1,697 |                     223 |                        579 |                                       52% |                                 1,231 |                                  3,068 |
|               [New Mexico](/us-nm) |              351 |                     1,333 |                     636 |                        982 |                                      280% |                                   622 |                                  2,703 |
|            [New Hampshire](/us-nh) |              238 |                     1,160 |                     853 |                        922 |                                      387% |                                   529 |                                  2,011 |
|                 [Kentucky](/us-ky) |              431 |                     1,150 |                     257 |                        719 |                                      167% |                                   599 |                                  2,517 |
|                [Tennessee](/us-tn) |              364 |                     1,030 |                     151 |                        666 |                                      183% |                                   505 |                                  2,285 |
|                   [Nevada](/us-nv) |              417 |                     1,018 |                     331 |                        601 |                                      144% |                                   548 |                                  1,987 |
|                 [Delaware](/us-de) |              361 |                       936 |                     961 |                        575 |                                      159% |                                   539 |                                  1,601 |
|                 [Nebraska](/us-ne) |              170 |                       892 |                     461 |                        722 |                                      425% |                                   355 |                                  1,695 |
|     [District of Columbia](/us-dc) |              462 |                       776 |                   1,100 |                        314 |                                       68% |                                   540 |                                  1,341 |
|                 [Oklahoma](/us-ok) |              334 |                       604 |                     153 |                        270 |                                       81% |                                   415 |                                  1,106 |
|                     [Utah](/us-ut) |              112 |                       532 |                     166 |                        420 |                                      375% |                                   209 |                                  1,081 |
|                 [Arkansas](/us-ar) |              133 |                       520 |                     172 |                        387 |                                      291% |                                   235 |                                  1,080 |
|                   [Kansas](/us-ks) |              215 |                       370 |                     127 |                        155 |                                       72% |                                   251 |                                    697 |
|             [South Dakota](/us-sd) |               62 |                       315 |                     356 |                        253 |                                      408% |                                   108 |                                    747 |
|             [North Dakota](/us-nd) |               60 |                       238 |                     312 |                        178 |                                      297% |                                   104 |                                    497 |
|                   [Oregon](/us-or) |              153 |                       229 |                      54 |                         76 |                                       50% |                                   172 |                                    393 |
|              [Puerto Rico](/us-pr) |              133 |                       187 |                      59 |                         54 |                                       41% |                                   152 |                                    277 |
|                    [Maine](/us-me) |               89 |                       146 |                     109 |                         57 |                                       64% |                                   114 |                                    229 |
|            [West Virginia](/us-wv) |               75 |                       130 |                      73 |                         55 |                                       73% |                                    93 |                                    216 |
|                    [Idaho](/us-id) |               82 |                       105 |                      59 |                         23 |                                       28% |                                    91 |                                    131 |
|                  [Wyoming](/us-wy) |               16 |                        69 |                     119 |                         53 |                                      331% |                                    38 |                                    112 |
|                  [Vermont](/us-vt) |               55 |                        65 |                     104 |                         10 |                                       18% |                                    60 |                                     72 |
|                   [Hawaii](/us-hi) |               17 |                        22 |                      16 |                          5 |                                       29% |                                    20 |                                     24 |
|                  [Montana](/us-mt) |               17 |                        21 |                      20 |                          4 |                                       24% |                                    19 |                                     26 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     14 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          169,910 |                   209,609 |                     353 |                     39,699 |                                       23% |                               179,419 |                                284,149 |
| [United Kingdom](/united-kingdom) |           38,458 |                    49,024 |                     726 |                     10,566 |                                       27% |                                42,432 |                                 65,882 |
|                   [Italy](/italy) |           33,340 |                    39,334 |                     652 |                      5,994 |                                       18% |                                35,265 |                                 47,301 |
|                 [France](/france) |           28,774 |                    32,009 |                     478 |                      3,235 |                                       11% |                                29,051 |                                 42,181 |
|                   [Spain](/spain) |           28,752 |                    30,122 |                     642 |                      1,370 |                                        5% |                                27,590 |                                 37,334 |
|               [Germany](/germany) |            8,530 |                    11,285 |                     136 |                      2,755 |                                       32% |                                 8,989 |                                 19,173 |
|               [Belgium](/belgium) |            9,453 |                    10,459 |                     913 |                      1,006 |                                       11% |                                 9,652 |                                 12,529 |
|       [Netherlands](/netherlands) |            5,970 |                     7,551 |                     437 |                      1,581 |                                       26% |                                 6,308 |                                 10,035 |
|                 [Sweden](/sweden) |            4,395 |                     6,766 |                     661 |                      2,371 |                                       54% |                                 5,166 |                                  9,582 |
|               [Ukraine](/ukraine) |              696 |                     3,760 |                      85 |                      3,064 |                                      440% |                                 1,390 |                                  7,449 |
|               [Romania](/romania) |            1,259 |                     2,665 |                     137 |                      1,406 |                                      112% |                                 1,704 |                                  4,827 |
|                 [Poland](/poland) |            1,061 |                     2,561 |                      67 |                      1,500 |                                      141% |                                 1,322 |                                  5,291 |
|       [Switzerland](/switzerland) |            1,919 |                     2,176 |                     253 |                        257 |                                       13% |                                 1,969 |                                  2,884 |
|             [Portugal](/portugal) |            1,396 |                     2,106 |                     205 |                        710 |                                       51% |                                 1,598 |                                  3,084 |
|               [Ireland](/ireland) |            1,651 |                     1,970 |                     402 |                        319 |                                       19% |                                 1,709 |                                  2,934 |
|               [Moldova](/moldova) |              291 |                     1,552 |                     384 |                      1,261 |                                      433% |                                   668 |                                  2,788 |
|               [Hungary](/hungary) |              524 |                       972 |                      99 |                        448 |                                       85% |                                   605 |                                  2,211 |
|               [Austria](/austria) |              668 |                       775 |                      87 |                        107 |                                       16% |                                   699 |                                    981 |
|               [Denmark](/denmark) |              571 |                       725 |                     125 |                        154 |                                       27% |                                   622 |                                    944 |
|               [Belarus](/belarus) |              229 |                       706 |                      75 |                        477 |                                      208% |                                   379 |                                  1,914 |
|             [Bulgaria](/bulgaria) |              139 |                       637 |                      91 |                        498 |                                      358% |                                   254 |                                  1,337 |
|               [Finland](/finland) |              316 |                       469 |                      85 |                        153 |                                       48% |                                   347 |                                    824 |
|               [Czechia](/czechia) |              319 |                       383 |                      36 |                         64 |                                       20% |                                   351 |                                    437 |
|                 [Serbia](/serbia) |              242 |                       359 |                      52 |                        117 |                                       48% |                                   283 |                                    539 |
|                 [Norway](/norway) |              236 |                       271 |                      50 |                         35 |                                       15% |                                   247 |                                    314 |
|                 [Greece](/greece) |              175 |                       221 |                      21 |                         46 |                                       26% |                                   194 |                                    310 |
|               [Croatia](/croatia) |              103 |                       182 |                      45 |                         79 |                                       77% |                                   124 |                                    358 |
|             [Slovenia](/slovenia) |              108 |                       130 |                      62 |                         22 |                                       20% |                                   114 |                                    186 |
|         [Luxembourg](/luxembourg) |              110 |                       128 |                     209 |                         18 |                                       16% |                                   115 |                                    150 |
|           [Lithuania](/lithuania) |               70 |                       111 |                      40 |                         41 |                                       59% |                                    87 |                                    148 |
|               [Estonia](/estonia) |               67 |                        85 |                      64 |                         18 |                                       27% |                                    79 |                                     94 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    30 |                                     43 |
|                 [Latvia](/latvia) |               24 |                        34 |                      18 |                         10 |                                       42% |                                    32 |                                     36 |
|                 [Cyprus](/cyprus) |               17 |                        21 |                      24 |                          4 |                                       24% |                                    20 |                                     23 |
|                   [Malta](/malta) |                9 |                        14 |                      28 |                          5 |                                       56% |                                    13 |                                     14 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           93,762 |                   537,323 |                     104 |                    443,561 |                                      473% |                               213,332 |                                890,181 |
|                             [Brazil](/brazil) |           28,834 |                   163,909 |                     777 |                    135,075 |                                      468% |                                66,501 |                                263,707 |
|                             [Mexico](/mexico) |            9,779 |                   115,293 |                     904 |                    105,514 |                                     1079% |                                41,742 |                                158,368 |
|                               [India](/india) |            5,185 |                    69,344 |                      51 |                     64,159 |                                     1237% |                                15,493 |                                127,369 |
|                                 [Peru](/peru) |            4,371 |                    28,472 |                     876 |                     24,101 |                                      551% |                                 9,771 |                                 43,913 |
|                             [Russia](/russia) |            4,555 |                    28,194 |                     193 |                     23,639 |                                      519% |                                 9,809 |                                 57,181 |
|                 [South Africa](/south-africa) |              643 |                    18,514 |                     316 |                     17,871 |                                     2779% |                                 8,903 |                                 29,596 |
|                             [Canada](/canada) |            7,159 |                    13,982 |                     374 |                      6,823 |                                       95% |                                 8,527 |                                 28,944 |
|                                 [Iran](/iran) |            7,734 |                    12,388 |                     149 |                      4,654 |                                       60% |                                 8,632 |                                 21,265 |
|                               [Chile](/chile) |              997 |                    11,345 |                     599 |                     10,348 |                                     1038% |                                 6,501 |                                 15,352 |
|                         [Pakistan](/pakistan) |            1,395 |                    10,159 |                      47 |                      8,764 |                                      628% |                                 2,671 |                                 22,420 |
|                         [Colombia](/colombia) |              891 |                     7,864 |                     156 |                      6,973 |                                      783% |                                 3,650 |                                 13,015 |
|                     [Bangladesh](/bangladesh) |              610 |                     7,380 |                      45 |                      6,770 |                                     1110% |                                 2,380 |                                 13,061 |
|                           [Ecuador](/ecuador) |            3,334 |                     6,973 |                     401 |                      3,639 |                                      109% |                                 4,026 |                                 16,615 |
|                       [Indonesia](/indonesia) |            1,573 |                     6,106 |                      23 |                      4,533 |                                      288% |                                 2,595 |                                 12,968 |
|                               [Egypt](/egypt) |              913 |                     5,901 |                      59 |                      4,988 |                                      546% |                                 1,938 |                                 12,252 |
|                             [Turkey](/turkey) |            4,515 |                     5,592 |                      67 |                      1,077 |                                       24% |                                 4,750 |                                  8,054 |
|                               [China](/china) |            4,638 |                     4,651 |                       3 |                         13 |                                        0% |                                 4,638 |                                  4,738 |
|                 [Saudi Arabia](/saudi-arabia) |              480 |                     4,245 |                     124 |                      3,765 |                                      784% |                                 1,801 |                                  7,448 |
|                       [Argentina](/argentina) |              528 |                     2,748 |                      61 |                      2,220 |                                      420% |                                 1,232 |                                  5,900 |
|                           [Bolivia](/bolivia) |              310 |                     2,230 |                     194 |                      1,920 |                                      619% |                                   940 |                                  4,004 |
|                   [Philippines](/philippines) |              950 |                     1,773 |                      16 |                        823 |                                       87% |                                 1,112 |                                  3,615 |
|                             [Kuwait](/kuwait) |              205 |                     1,604 |                     381 |                      1,399 |                                      682% |                                   697 |                                  2,835 |
|                           [Nigeria](/nigeria) |              273 |                     1,601 |                       8 |                      1,328 |                                      486% |                                   463 |                                  4,539 |
|                               [Japan](/japan) |              894 |                     1,449 |                      11 |                        555 |                                       62% |                                   926 |                                  2,143 |
|                           [Algeria](/algeria) |              646 |                     1,017 |                      24 |                        371 |                                       57% |                                   745 |                                  1,986 |
|                         [Honduras](/honduras) |              201 |                       978 |                     100 |                        777 |                                      387% |                                   403 |                                  2,340 |
|                             [Panama](/panama) |              330 |                       942 |                     222 |                        612 |                                      185% |                                   435 |                                  2,330 |
|     [Dominican Republic](/dominican-republic) |              498 |                       849 |                      79 |                        351 |                                       70% |                                   595 |                                  1,384 |
| [United Arab Emirates](/united-arab-emirates) |              262 |                       549 |                      56 |                        287 |                                      110% |                                   330 |                                  1,208 |
|                             [Israel](/israel) |              284 |                       347 |                      41 |                         63 |                                       22% |                                   307 |                                    463 |
|                   [South Korea](/south-korea) |              270 |                       321 |                       6 |                         51 |                                       19% |                                   276 |                                    433 |
|                           [Morocco](/morocco) |              204 |                       239 |                       7 |                         35 |                                       17% |                                   219 |                                    290 |
|                         [Malaysia](/malaysia) |              115 |                       145 |                       5 |                         30 |                                       26% |                                   128 |                                    171 |
|                       [Australia](/australia) |              103 |                       112 |                       4 |                          9 |                                        9% |                                   104 |                                    136 |
|                                 [Cuba](/cuba) |               83 |                       107 |                       9 |                         24 |                                       29% |                                    92 |                                    138 |
