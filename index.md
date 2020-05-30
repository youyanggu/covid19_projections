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

## Current Projection for US - Updated Daily - Last Updated: May 30 (2am ET):
<p align="center">
  Current Total: <b>102,806</b> deaths | Projected Total: <b>200,130 deaths by Sep 1, 2020</b> (Range: 127-335k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 23 being the most likely date.

Last updated: May 30, 2020

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
|              125,000 |          9% |        76% |         91% |        96% |         98% |        98% |
|              150,000 |         <1% |         8% |         40% |        63% |         72% |        78% |
|              175,000 |         <1% |        <1% |         10% |        34% |         48% |        57% |
|              200,000 |         <1% |        <1% |         <1% |        16% |         31% |        42% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         10% |        21% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         8% |
|              350,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          102,806 |                   200,130 |                     603 |                     97,324 |                                       95% |                               127,183 |                                334,876 |
|                 [New York](/us-ny) |           29,646 |                    32,962 |                   1,694 |                      3,316 |                                       11% |                                30,472 |                                 39,102 |
|               [New Jersey](/us-nj) |           11,531 |                    14,922 |                   1,680 |                      3,391 |                                       29% |                                12,593 |                                 18,175 |
|                 [Illinois](/us-il) |            5,270 |                    13,660 |                   1,078 |                      8,390 |                                      159% |                                 8,250 |                                 19,799 |
|               [California](/us-ca) |            4,077 |                    12,902 |                     327 |                      8,825 |                                      216% |                                 5,514 |                                 29,480 |
|            [Massachusetts](/us-ma) |            6,718 |                    10,179 |                   1,465 |                      3,461 |                                       52% |                                 7,633 |                                 15,621 |
|             [Pennsylvania](/us-pa) |            5,464 |                     9,657 |                     754 |                      4,193 |                                       77% |                                 6,497 |                                 14,896 |
|                     [Ohio](/us-oh) |            2,131 |                     8,138 |                     696 |                      6,007 |                                      282% |                                 3,784 |                                 15,981 |
|                  [Florida](/us-fl) |            2,413 |                     7,663 |                     357 |                      5,250 |                                      218% |                                 3,377 |                                 17,445 |
|                 [Michigan](/us-mi) |            5,406 |                     6,864 |                     687 |                      1,458 |                                       27% |                                 5,863 |                                  9,709 |
|                 [Maryland](/us-md) |            2,466 |                     6,110 |                   1,011 |                      3,644 |                                      148% |                                 3,220 |                                 11,383 |
|                  [Indiana](/us-in) |            2,110 |                     5,883 |                     874 |                      3,773 |                                      179% |                                 2,974 |                                 10,809 |
|                  [Georgia](/us-ga) |            1,987 |                     5,409 |                     509 |                      3,422 |                                      172% |                                 2,808 |                                 10,202 |
|              [Connecticut](/us-ct) |            3,868 |                     5,230 |                   1,467 |                      1,362 |                                       35% |                                 4,303 |                                  7,133 |
|                    [Texas](/us-tx) |            1,619 |                     5,178 |                     179 |                      3,559 |                                      220% |                                 2,495 |                                 11,584 |
|                 [Virginia](/us-va) |            1,358 |                     5,100 |                     598 |                      3,742 |                                      276% |                                 2,049 |                                 10,128 |
|                [Minnesota](/us-mn) |            1,006 |                     4,490 |                     796 |                      3,484 |                                      346% |                                 1,830 |                                  8,324 |
|                  [Arizona](/us-az) |              886 |                     4,396 |                     604 |                      3,510 |                                      396% |                                 1,787 |                                  8,009 |
|           [North Carolina](/us-nc) |              919 |                     4,213 |                     402 |                      3,294 |                                      358% |                                 1,783 |                                  8,673 |
|                 [Colorado](/us-co) |            1,436 |                     4,095 |                     711 |                      2,659 |                                      185% |                                 2,056 |                                  7,770 |
|                [Louisiana](/us-la) |            2,767 |                     4,062 |                     874 |                      1,295 |                                       47% |                                 3,095 |                                  5,982 |
|              [Mississippi](/us-ms) |              710 |                     3,103 |                   1,043 |                      2,393 |                                      337% |                                 1,367 |                                  5,253 |
|                 [Missouri](/us-mo) |              730 |                     2,414 |                     393 |                      1,684 |                                      231% |                                 1,141 |                                  5,054 |
|                  [Alabama](/us-al) |              610 |                     2,393 |                     488 |                      1,783 |                                      292% |                                 1,059 |                                  4,622 |
|                     [Iowa](/us-ia) |              524 |                     2,264 |                     718 |                      1,740 |                                      332% |                                   923 |                                  3,946 |
|           [South Carolina](/us-sc) |              483 |                     2,085 |                     405 |                      1,602 |                                      332% |                                   848 |                                  4,332 |
|             [Rhode Island](/us-ri) |              693 |                     1,842 |                   1,739 |                      1,149 |                                      166% |                                 1,174 |                                  2,687 |
|               [Washington](/us-wa) |            1,111 |                     1,695 |                     223 |                        584 |                                       53% |                                 1,225 |                                  3,075 |
|                [Wisconsin](/us-wi) |              568 |                     1,532 |                     263 |                        964 |                                      170% |                                   812 |                                  3,117 |
|               [New Mexico](/us-nm) |              344 |                     1,340 |                     639 |                        996 |                                      290% |                                   614 |                                  2,720 |
|            [New Hampshire](/us-nh) |              238 |                     1,216 |                     894 |                        978 |                                      411% |                                   551 |                                  2,065 |
|                [Tennessee](/us-tn) |              361 |                     1,088 |                     159 |                        727 |                                      201% |                                   510 |                                  2,371 |
|                 [Kentucky](/us-ky) |              418 |                     1,025 |                     229 |                        607 |                                      145% |                                   549 |                                  2,255 |
|                   [Nevada](/us-nv) |              406 |                       949 |                     308 |                        543 |                                      134% |                                   525 |                                  1,918 |
|                 [Delaware](/us-de) |              356 |                       943 |                     968 |                        587 |                                      165% |                                   538 |                                  1,607 |
|                 [Nebraska](/us-ne) |              164 |                       815 |                     421 |                        651 |                                      397% |                                   339 |                                  1,566 |
|     [District of Columbia](/us-dc) |              460 |                       808 |                   1,145 |                        348 |                                       76% |                                   546 |                                  1,379 |
|                 [Oklahoma](/us-ok) |              329 |                       593 |                     150 |                        264 |                                       80% |                                   410 |                                  1,094 |
|                 [Arkansas](/us-ar) |              132 |                       555 |                     184 |                        423 |                                      320% |                                   239 |                                  1,158 |
|                     [Utah](/us-ut) |              107 |                       435 |                     136 |                        328 |                                      307% |                                   188 |                                    892 |
|                   [Kansas](/us-ks) |              215 |                       383 |                     131 |                        168 |                                       78% |                                   252 |                                    838 |
|             [South Dakota](/us-sd) |               59 |                       298 |                     337 |                        239 |                                      405% |                                   103 |                                    715 |
|             [North Dakota](/us-nd) |               59 |                       252 |                     331 |                        193 |                                      327% |                                   113 |                                    532 |
|                   [Oregon](/us-or) |              151 |                       225 |                      53 |                         74 |                                       49% |                                   169 |                                    384 |
|              [Puerto Rico](/us-pr) |              132 |                       187 |                      59 |                         55 |                                       42% |                                   151 |                                    277 |
|                    [Maine](/us-me) |               85 |                       137 |                     102 |                         52 |                                       61% |                                   106 |                                    195 |
|            [West Virginia](/us-wv) |               74 |                       129 |                      72 |                         55 |                                       74% |                                    93 |                                    216 |
|                    [Idaho](/us-id) |               82 |                       105 |                      59 |                         23 |                                       28% |                                    92 |                                    133 |
|                  [Vermont](/us-vt) |               55 |                        66 |                     106 |                         11 |                                       20% |                                    61 |                                     73 |
|                  [Wyoming](/us-wy) |               15 |                        65 |                     112 |                         50 |                                      333% |                                    35 |                                    110 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    20 |                                     25 |
|                  [Montana](/us-mt) |               17 |                        21 |                      20 |                          4 |                                       24% |                                    19 |                                     26 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     14 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     8 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          169,331 |                   216,092 |                     364 |                     46,761 |                                       28% |                               180,875 |                                300,818 |
| [United Kingdom](/united-kingdom) |           38,243 |                    55,726 |                     825 |                     17,483 |                                       46% |                                44,327 |                                 82,611 |
|                   [Italy](/italy) |           33,229 |                    39,299 |                     651 |                      6,070 |                                       18% |                                35,184 |                                 47,324 |
|                 [France](/france) |           28,717 |                    32,031 |                     478 |                      3,314 |                                       12% |                                29,011 |                                 42,355 |
|                   [Spain](/spain) |           28,752 |                    30,195 |                     643 |                      1,443 |                                        5% |                                27,610 |                                 37,458 |
|               [Germany](/germany) |            8,504 |                    11,361 |                     137 |                      2,857 |                                       34% |                                 8,991 |                                 19,339 |
|               [Belgium](/belgium) |            9,430 |                    10,466 |                     914 |                      1,036 |                                       11% |                                 9,639 |                                 12,565 |
|       [Netherlands](/netherlands) |            5,950 |                     7,554 |                     437 |                      1,604 |                                       27% |                                 6,298 |                                 10,073 |
|                 [Sweden](/sweden) |            4,350 |                     6,331 |                     619 |                      1,981 |                                       46% |                                 4,947 |                                  8,622 |
|               [Ukraine](/ukraine) |              679 |                     3,703 |                      84 |                      3,024 |                                      445% |                                 1,308 |                                  7,451 |
|               [Romania](/romania) |            1,248 |                     2,689 |                     139 |                      1,441 |                                      115% |                                 1,708 |                                  4,843 |
|                 [Poland](/poland) |            1,051 |                     2,581 |                      68 |                      1,530 |                                      146% |                                 1,318 |                                  5,387 |
|       [Switzerland](/switzerland) |            1,919 |                     2,183 |                     254 |                        264 |                                       14% |                                 1,971 |                                  2,897 |
|             [Portugal](/portugal) |            1,383 |                     2,090 |                     203 |                        707 |                                       51% |                                 1,588 |                                  3,076 |
|               [Ireland](/ireland) |            1,645 |                     1,970 |                     402 |                        325 |                                       20% |                                 1,706 |                                  2,941 |
|               [Moldova](/moldova) |              288 |                     1,644 |                     407 |                      1,356 |                                      471% |                                   680 |                                  3,024 |
|               [Hungary](/hungary) |              517 |                       960 |                      98 |                        443 |                                       86% |                                   597 |                                  2,141 |
|               [Austria](/austria) |              668 |                       780 |                      88 |                        112 |                                       17% |                                   700 |                                    997 |
|               [Denmark](/denmark) |              568 |                       724 |                     125 |                        156 |                                       27% |                                   620 |                                    945 |
|               [Belarus](/belarus) |              224 |                       710 |                      75 |                        486 |                                      217% |                                   374 |                                  1,919 |
|             [Bulgaria](/bulgaria) |              136 |                       628 |                      90 |                        492 |                                      362% |                                   252 |                                  1,324 |
|               [Finland](/finland) |              314 |                       468 |                      85 |                        154 |                                       49% |                                   346 |                                    824 |
|               [Czechia](/czechia) |              319 |                       386 |                      36 |                         67 |                                       21% |                                   353 |                                    439 |
|                 [Serbia](/serbia) |              242 |                       367 |                      53 |                        125 |                                       52% |                                   284 |                                    564 |
|                 [Norway](/norway) |              236 |                       271 |                      50 |                         35 |                                       15% |                                   247 |                                    316 |
|                 [Greece](/greece) |              175 |                       222 |                      21 |                         47 |                                       27% |                                   194 |                                    311 |
|               [Croatia](/croatia) |              103 |                       185 |                      45 |                         82 |                                       80% |                                   124 |                                    360 |
|             [Slovenia](/slovenia) |              108 |                       130 |                      62 |                         22 |                                       20% |                                   114 |                                    187 |
|         [Luxembourg](/luxembourg) |              110 |                       128 |                     209 |                         18 |                                       16% |                                   115 |                                    151 |
|           [Lithuania](/lithuania) |               68 |                       109 |                      39 |                         41 |                                       60% |                                    83 |                                    147 |
|               [Estonia](/estonia) |               67 |                        85 |                      64 |                         18 |                                       27% |                                    80 |                                     95 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    30 |                                     43 |
|                 [Latvia](/latvia) |               24 |                        35 |                      18 |                         11 |                                       46% |                                    32 |                                     39 |
|                 [Cyprus](/cyprus) |               17 |                        21 |                      24 |                          4 |                                       24% |                                    20 |                                     23 |
|                   [Malta](/malta) |                9 |                        14 |                      28 |                          5 |                                       56% |                                    13 |                                     15 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           91,180 |                   544,097 |                     105 |                    452,917 |                                      497% |                               218,451 |                                903,873 |
|                             [Brazil](/brazil) |           27,878 |                   167,819 |                     795 |                    139,941 |                                      502% |                                65,911 |                                266,304 |
|                             [Mexico](/mexico) |            9,415 |                   123,446 |                     968 |                    114,031 |                                     1211% |                                46,897 |                                170,824 |
|                               [India](/india) |            4,980 |                    70,630 |                      52 |                     65,650 |                                     1318% |                                17,394 |                                127,966 |
|                             [Russia](/russia) |            4,374 |                    30,219 |                     207 |                     25,845 |                                      591% |                                11,175 |                                 58,739 |
|                                 [Peru](/peru) |            4,099 |                    22,464 |                     691 |                     18,365 |                                      448% |                                 8,025 |                                 42,300 |
|                 [South Africa](/south-africa) |              611 |                    18,406 |                     314 |                     17,795 |                                     2912% |                                 8,863 |                                 29,587 |
|                             [Canada](/canada) |            7,063 |                    13,899 |                     372 |                      6,836 |                                       97% |                                 8,366 |                                 28,996 |
|                                 [Iran](/iran) |            7,677 |                    12,418 |                     150 |                      4,741 |                                       62% |                                 8,592 |                                 21,424 |
|                               [Chile](/chile) |              944 |                    11,104 |                     586 |                     10,160 |                                     1076% |                                 6,413 |                                 15,123 |
|                         [Pakistan](/pakistan) |            1,317 |                     9,742 |                      45 |                      8,425 |                                      640% |                                 2,698 |                                 20,702 |
|                           [Ecuador](/ecuador) |            3,334 |                     7,284 |                     419 |                      3,950 |                                      118% |                                 4,071 |                                 17,444 |
|                     [Bangladesh](/bangladesh) |              582 |                     7,152 |                      44 |                      6,570 |                                     1129% |                                 2,274 |                                 13,010 |
|                         [Colombia](/colombia) |              855 |                     7,118 |                     141 |                      6,263 |                                      733% |                                 3,544 |                                 12,707 |
|                             [Turkey](/turkey) |            4,489 |                     5,586 |                      67 |                      1,097 |                                       24% |                                 4,736 |                                  8,078 |
|                               [Egypt](/egypt) |              879 |                     5,572 |                      56 |                      4,693 |                                      534% |                                 1,800 |                                 11,691 |
|                       [Indonesia](/indonesia) |            1,520 |                     5,429 |                      20 |                      3,909 |                                      257% |                                 2,358 |                                 12,226 |
|                               [China](/china) |            4,638 |                     4,652 |                       3 |                         14 |                                        0% |                                 4,638 |                                  4,741 |
|                 [Saudi Arabia](/saudi-arabia) |              458 |                     4,019 |                     117 |                      3,561 |                                      778% |                                 1,740 |                                  7,250 |
|                       [Argentina](/argentina) |              520 |                     2,912 |                      65 |                      2,392 |                                      460% |                                 1,256 |                                  6,078 |
|                           [Bolivia](/bolivia) |              300 |                     2,223 |                     193 |                      1,923 |                                      641% |                                   934 |                                  4,010 |
|                   [Philippines](/philippines) |              942 |                     1,798 |                      17 |                        856 |                                       91% |                                 1,107 |                                  3,810 |
|                             [Kuwait](/kuwait) |              194 |                     1,557 |                     370 |                      1,363 |                                      703% |                                   677 |                                  2,791 |
|                           [Nigeria](/nigeria) |              261 |                     1,461 |                       7 |                      1,200 |                                      460% |                                   440 |                                  4,426 |
|                               [Japan](/japan) |              887 |                     1,447 |                      11 |                        560 |                                       63% |                                   920 |                                  2,149 |
|                           [Algeria](/algeria) |              638 |                     1,007 |                      23 |                        369 |                                       58% |                                   739 |                                  1,978 |
|     [Dominican Republic](/dominican-republic) |              488 |                       985 |                      92 |                        497 |                                      102% |                                   601 |                                  1,907 |
|                         [Honduras](/honduras) |              196 |                       957 |                      98 |                        761 |                                      388% |                                   394 |                                  2,387 |
|                             [Panama](/panama) |              326 |                       942 |                     222 |                        616 |                                      189% |                                   432 |                                  2,337 |
| [United Arab Emirates](/united-arab-emirates) |              260 |                       579 |                      59 |                        319 |                                      123% |                                   332 |                                  1,256 |
|                             [Israel](/israel) |              284 |                       349 |                      41 |                         65 |                                       23% |                                   307 |                                    465 |
|                   [South Korea](/south-korea) |              269 |                       320 |                       6 |                         51 |                                       19% |                                   275 |                                    434 |
|                           [Morocco](/morocco) |              202 |                       237 |                       6 |                         35 |                                       17% |                                   217 |                                    287 |
|                         [Malaysia](/malaysia) |              115 |                       146 |                       5 |                         31 |                                       27% |                                   129 |                                    172 |
|                       [Australia](/australia) |              103 |                       112 |                       4 |                          9 |                                        9% |                                   105 |                                    137 |
|                                 [Cuba](/cuba) |               82 |                       106 |                       9 |                         24 |                                       29% |                                    91 |                                    137 |
