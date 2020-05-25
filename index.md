We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 60 countries. The countries our projections cover encompass 6.3 billion people and account for over 99% of all global COVID-19 deaths.

Note that our infections estimate includes all infected individuals, not just those that took a COVID-19 test kit and tested positive. The vast majority of infected individuals do not get tested, and thus do not get reported as a positive case. As of mid-May, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 22:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729), [widespread reopenings](https://www.wsj.com/articles/coronavirus-latest-news-05-20-2020-11589963481), [unreported care home deaths](https://www.economist.com/europe/2020/05/09/many-covid-deaths-in-care-homes-are-unrecorded), [increased efforts for contact tracing](https://www.npr.org/sections/health-shots/2020/04/28/846736937/we-asked-all-50-states-about-their-contact-tracing-capacity-heres-what-we-learne), and [conflated testing numbers](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/).

* **May 20:** We added county-level projections for 14 US counties heavily impacted by COVID-19. This includes cities such as [New York City](/us-ny-new-york-city) (5 boroughs), [Los Angeles](/us-ca-los-angeles), and [Chicago](/us-il-cook). See all 14 counties [here](#us-counties). We also added the 2 Canadian provinces accounting for ~85% of cases in Canada: [Ontario](/canada-ontario) and [Quebec](/canada-quebec).

* **May 18:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 25 (1am ET):
<p align="center">
  Current Total: <b>98,874</b> deaths | Projected Total: <b>180,707</b> deaths by Aug 4, 2020 (Range: 122-292k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 51% chance that the US surpasses 150,000 deaths by July 15, with July 12 being the most likely date.

Last updated: May 25, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 27, 2020 |
|              125,000 |        Jun 19, 2020 |
|              150,000 |        Jul 12, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         28% |        80% |         91% |        95% |
|              150,000 |        <1% |         <1% |        21% |         51% |        68% |
|              175,000 |        <1% |         <1% |         2% |         20% |        43% |
|              200,000 |        <1% |         <1% |        <1% |          7% |        26% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         8% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |

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
| [CA - Los Angeles](/us-ca-los-angeles) | [MI - Wayne](/us-mi-wayne) | [NY - New York City](/us-ny-new-york-city) |
| [CA - Santa Clara](/us-ca-santa-clara) | [NJ - Bergen](/us-nj-bergen) | [NY - Suffolk](/us-ny-suffolk) |
| [FL - Miami-Dade](/us-fl-miami-dade) | [NJ - Essex](/us-nj-essex) | [NY - Westchester](/us-ny-westchester) |
| [IL - Cook](/us-il-cook) | [NV - Washoe](/us-nv-washoe) | [PA - Philadelphia](/us-pa-philadelphia) |
| [MA - Middlesex](/us-ma-middlesex) | [NY - Nassau](/us-ny-nassau) |

[Back to Top](#top)

### Global Projections

| [Canada](/canada) |  |  |
| --- | --- | --- |
| [Ontario](/canada-ontario) | [Quebec](/canada-quebec) |

<br />

| Europe |  |  |
| --- | --- | --- |
| [Austria](/austria) | [Hungary](/hungary) | [Portugal](/portugal) |
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
| [Greece](/greece) | [Poland](/poland) |

<br />

| Rest of World |  |  |
| --- | --- | --- |
| [Algeria](/algeria) | [Egypt](/egypt) | [Pakistan](/pakistan) |
| [Argentina](/argentina) | [India](/india) | [Panama](/panama) |
| [Bangladesh](/bangladesh) | [Indonesia](/indonesia) | [Peru](/peru) |
| [Brazil](/brazil) | [Iran](/iran) | [Philippines](/philippines) |
| [Canada](/canada) | [Israel](/israel) | [Russia](/russia) |
| [Chile](/chile) | [Japan](/japan) | [Saudi Arabia](/saudi-arabia) |
| [China](/china) | [Malaysia](/malaysia) | [South Africa](/south-africa) |
| [Colombia](/colombia) | [Mexico](/mexico) | [South Korea](/south-korea) |
| [Dominican Republic](/dominican-republic) | [Morocco](/morocco) | [Turkey](/turkey) |
| [Ecuador](/ecuador) | [Nigeria](/nigeria) |

[Back to Top](#top)

### US Summary

States are ordered by descending projected deaths (by August 4).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|         *[United States](/us)* |           97,717 |                   180,707 |                     545 |                     82,990 |                                       85% |                               122,460 |                                291,472 |
|             [New York](/us-ny) |           29,141 |                    32,738 |                   1,683 |                      3,597 |                                       12% |                                30,297 |                                 38,822 |
|           [New Jersey](/us-nj) |           11,138 |                    15,083 |                   1,698 |                      3,945 |                                       35% |                                12,486 |                                 19,524 |
|             [Illinois](/us-il) |            4,856 |                    14,245 |                   1,124 |                      9,389 |                                      193% |                                 8,737 |                                 20,684 |
|         [Pennsylvania](/us-pa) |            5,136 |                    11,998 |                     937 |                      6,862 |                                      134% |                                 7,081 |                                 21,352 |
|           [California](/us-ca) |            3,754 |                     9,719 |                     246 |                      5,965 |                                      159% |                                 4,914 |                                 19,738 |
|        [Massachusetts](/us-ma) |            6,372 |                     9,465 |                   1,362 |                      3,093 |                                       49% |                                 7,290 |                                 13,902 |
|                 [Ohio](/us-oh) |            1,969 |                     7,092 |                     607 |                      5,123 |                                      260% |                                 3,502 |                                 13,511 |
|             [Michigan](/us-mi) |            5,228 |                     6,619 |                     663 |                      1,391 |                                       27% |                                 5,746 |                                  8,446 |
|              [Florida](/us-fl) |            2,237 |                     5,828 |                     271 |                      3,591 |                                      161% |                                 2,988 |                                 13,487 |
|              [Indiana](/us-in) |            1,976 |                     5,715 |                     849 |                      3,739 |                                      189% |                                 2,823 |                                 11,517 |
|                [Texas](/us-tx) |            1,528 |                     5,431 |                     187 |                      3,903 |                                      255% |                                 2,618 |                                 10,371 |
|          [Connecticut](/us-ct) |            3,693 |                     5,078 |                   1,424 |                      1,385 |                                       38% |                                 4,166 |                                  6,753 |
|             [Maryland](/us-md) |            2,277 |                     4,974 |                     823 |                      2,697 |                                      118% |                                 2,895 |                                  9,046 |
|              [Georgia](/us-ga) |            1,827 |                     4,392 |                     414 |                      2,565 |                                      140% |                                 2,448 |                                  8,890 |
|            [Louisiana](/us-la) |            2,691 |                     3,792 |                     816 |                      1,101 |                                       41% |                                 3,083 |                                  5,018 |
|              [Arizona](/us-az) |              801 |                     3,764 |                     517 |                      2,963 |                                      370% |                                 1,746 |                                  6,762 |
|             [Colorado](/us-co) |            1,332 |                     3,517 |                     611 |                      2,185 |                                      164% |                                 1,903 |                                  6,425 |
|            [Minnesota](/us-mn) |              878 |                     3,108 |                     551 |                      2,230 |                                      254% |                                 1,383 |                                  6,121 |
|             [Virginia](/us-va) |            1,171 |                     2,766 |                     324 |                      1,595 |                                      136% |                                 1,511 |                                  6,295 |
|          [Mississippi](/us-ms) |              625 |                     2,701 |                     908 |                      2,076 |                                      332% |                                 1,342 |                                  4,644 |
|             [Missouri](/us-mo) |              686 |                     2,349 |                     383 |                      1,663 |                                      242% |                                 1,109 |                                  4,497 |
|                 [Iowa](/us-ia) |              456 |                     2,171 |                     688 |                      1,715 |                                      376% |                                 1,100 |                                  3,368 |
|       [North Carolina](/us-nc) |              784 |                     1,931 |                     184 |                      1,147 |                                      146% |                                 1,114 |                                  3,825 |
|              [Alabama](/us-al) |              551 |                     1,793 |                     366 |                      1,242 |                                      225% |                                   929 |                                  3,355 |
|         [Rhode Island](/us-ri) |              608 |                     1,531 |                   1,445 |                        923 |                                      152% |                                   968 |                                  2,694 |
|           [Washington](/us-wa) |            1,061 |                     1,410 |                     185 |                        349 |                                       33% |                                 1,164 |                                  2,108 |
|       [South Carolina](/us-sc) |              435 |                     1,352 |                     263 |                        917 |                                      211% |                                   640 |                                  3,059 |
|           [New Mexico](/us-nm) |              317 |                     1,171 |                     558 |                        854 |                                      269% |                                   605 |                                  2,035 |
|        [New Hampshire](/us-nh) |              209 |                       976 |                     718 |                        767 |                                      367% |                                   502 |                                  1,617 |
|            [Wisconsin](/us-wi) |              510 |                       915 |                     157 |                        405 |                                       79% |                                   670 |                                  1,384 |
|             [Delaware](/us-de) |              326 |                       858 |                     881 |                        532 |                                      163% |                                   504 |                                  1,567 |
|             [Kentucky](/us-ky) |              391 |                       793 |                     177 |                        402 |                                      103% |                                   528 |                                  1,366 |
| [District of Columbia](/us-dc) |              432 |                       769 |                   1,090 |                        337 |                                       78% |                                   545 |                                  1,114 |
|               [Nevada](/us-nv) |              380 |                       713 |                     231 |                        333 |                                       88% |                                   486 |                                  1,270 |
|            [Tennessee](/us-tn) |              336 |                       632 |                      92 |                        296 |                                       88% |                                   467 |                                  1,073 |
|             [Nebraska](/us-ne) |              147 |                       610 |                     315 |                        463 |                                      315% |                                   299 |                                  1,162 |
|             [Oklahoma](/us-ok) |              311 |                       460 |                     116 |                        149 |                                       48% |                                   370 |                                    699 |
|                 [Utah](/us-ut) |               97 |                       400 |                     125 |                        303 |                                      312% |                                   167 |                                    913 |
|               [Kansas](/us-ks) |              205 |                       306 |                     105 |                        101 |                                       49% |                                   227 |                                    524 |
|         [South Dakota](/us-sd) |               50 |                       241 |                     272 |                        191 |                                      382% |                                   100 |                                    562 |
|             [Arkansas](/us-ar) |              116 |                       232 |                      77 |                        116 |                                      100% |                                   171 |                                    393 |
|               [Oregon](/us-or) |              148 |                       209 |                      50 |                         61 |                                       41% |                                   169 |                                    293 |
|         [North Dakota](/us-nd) |               53 |                       205 |                     269 |                        152 |                                      287% |                                   101 |                                    461 |
|          [Puerto Rico](/us-pr) |              127 |                       166 |                      52 |                         39 |                                       31% |                                   145 |                                    215 |
|        [West Virginia](/us-wv) |               72 |                       112 |                      62 |                         40 |                                       56% |                                    87 |                                    167 |
|                [Maine](/us-me) |               78 |                       111 |                      83 |                         33 |                                       42% |                                    95 |                                    138 |
|                [Idaho](/us-id) |               79 |                        99 |                      55 |                         20 |                                       25% |                                    92 |                                    110 |
|              [Vermont](/us-vt) |               54 |                        65 |                     104 |                         11 |                                       20% |                                    61 |                                     69 |
|              [Wyoming](/us-wy) |               12 |                        27 |                      47 |                         15 |                                      125% |                                    18 |                                     40 |
|               [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    20 |                                     26 |
|              [Montana](/us-mt) |               16 |                        20 |                      19 |                          4 |                                       25% |                                    18 |                                     23 |
|               [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     13 |
|                 [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     7 |                                      9 |
|       [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     8 |                                      9 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          165,672 |                   208,864 |                     358 |                     43,192 |                                       26% |                               176,876 |                                282,955 |
| [United Kingdom](/united-kingdom) |           36,875 |                    49,971 |                     740 |                     13,096 |                                       36% |                                40,395 |                                 67,917 |
|                   [Italy](/italy) |           32,785 |                    39,439 |                     653 |                      6,654 |                                       20% |                                34,867 |                                 49,177 |
|                   [Spain](/spain) |           28,752 |                    32,528 |                     693 |                      3,776 |                                       13% |                                29,694 |                                 39,810 |
|                 [France](/france) |           28,370 |                    32,169 |                     480 |                      3,799 |                                       13% |                                28,834 |                                 43,457 |
|               [Germany](/germany) |            8,283 |                    10,855 |                     131 |                      2,572 |                                       31% |                                 8,774 |                                 17,957 |
|               [Belgium](/belgium) |            9,280 |                    10,431 |                     911 |                      1,151 |                                       12% |                                 9,546 |                                 12,740 |
|       [Netherlands](/netherlands) |            5,841 |                     7,493 |                     434 |                      1,652 |                                       28% |                                 6,243 |                                 10,054 |
|                 [Sweden](/sweden) |            3,998 |                     5,639 |                     551 |                      1,641 |                                       41% |                                 4,626 |                                  7,249 |
|               [Ukraine](/ukraine) |              617 |                     2,881 |                      65 |                      2,264 |                                      367% |                                 1,246 |                                  5,332 |
|               [Romania](/romania) |            1,185 |                     2,553 |                     131 |                      1,368 |                                      115% |                                 1,633 |                                  4,554 |
|                 [Poland](/poland) |              996 |                     2,453 |                      65 |                      1,457 |                                      146% |                                 1,234 |                                  5,933 |
|       [Switzerland](/switzerland) |            1,906 |                     2,171 |                     253 |                        265 |                                       14% |                                 1,971 |                                  2,792 |
|             [Portugal](/portugal) |            1,316 |                     1,945 |                     189 |                        629 |                                       48% |                                 1,531 |                                  2,911 |
|               [Ireland](/ireland) |            1,608 |                     1,924 |                     392 |                        316 |                                       20% |                                 1,677 |                                  2,820 |
|               [Moldova](/moldova) |              250 |                     1,109 |                     274 |                        859 |                                      344% |                                   502 |                                  2,093 |
|               [Hungary](/hungary) |              486 |                       804 |                      82 |                        318 |                                       65% |                                   551 |                                  1,475 |
|               [Austria](/austria) |              640 |                       749 |                      85 |                        109 |                                       17% |                                   676 |                                    908 |
|               [Denmark](/denmark) |              562 |                       728 |                     125 |                        166 |                                       30% |                                   623 |                                    935 |
|             [Bulgaria](/bulgaria) |              130 |                       624 |                      89 |                        494 |                                      380% |                                   234 |                                  1,504 |
|               [Finland](/finland) |              307 |                       472 |                      86 |                        165 |                                       54% |                                   337 |                                    905 |
|               [Czechia](/czechia) |              315 |                       397 |                      37 |                         82 |                                       26% |                                   361 |                                    454 |
|                 [Serbia](/serbia) |              238 |                       337 |                      48 |                         99 |                                       42% |                                   281 |                                    457 |
|                 [Norway](/norway) |              235 |                       271 |                      50 |                         36 |                                       15% |                                   247 |                                    314 |
|                 [Greece](/greece) |              171 |                       217 |                      20 |                         46 |                                       27% |                                   192 |                                    259 |
|               [Croatia](/croatia) |               99 |                       169 |                      41 |                         70 |                                       71% |                                   118 |                                    316 |
|         [Luxembourg](/luxembourg) |              110 |                       131 |                     213 |                         21 |                                       19% |                                   119 |                                    156 |
|             [Slovenia](/slovenia) |              107 |                       127 |                      61 |                         20 |                                       19% |                                   113 |                                    160 |
|           [Lithuania](/lithuania) |               63 |                        87 |                      31 |                         24 |                                       38% |                                    77 |                                    103 |
|               [Estonia](/estonia) |               64 |                        83 |                      63 |                         19 |                                       30% |                                    76 |                                     92 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    30 |                                     42 |
|                 [Latvia](/latvia) |               22 |                        32 |                      17 |                         10 |                                       45% |                                    30 |                                     34 |
|                 [Cyprus](/cyprus) |               17 |                        21 |                      24 |                          4 |                                       24% |                                    20 |                                     24 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |
|                   [Malta](/malta) |                6 |                         8 |                      16 |                          2 |                                       33% |                                     7 |                                      9 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           77,721 |                   377,313 |                      74 |                    299,592 |                                      385% |                               142,758 |                                745,306 |
|                         [Brazil](/brazil) |           22,666 |                   135,187 |                     641 |                    112,521 |                                      496% |                                45,906 |                                265,755 |
|                         [Mexico](/mexico) |            7,394 |                    82,398 |                     646 |                     75,004 |                                     1014% |                                24,700 |                                138,900 |
|                           [India](/india) |            4,024 |                    34,451 |                      25 |                     30,427 |                                      756% |                                 8,140 |                                 93,659 |
|                         [Russia](/russia) |            3,541 |                    19,699 |                     135 |                     16,158 |                                      456% |                                 5,986 |                                 51,924 |
|                             [Peru](/peru) |            3,456 |                    15,875 |                     488 |                     12,419 |                                      359% |                                 6,184 |                                 28,477 |
|                             [Iran](/iran) |            7,417 |                    14,254 |                     172 |                      6,837 |                                       92% |                                 8,657 |                                 27,603 |
|                         [Canada](/canada) |            6,534 |                    11,184 |                     299 |                      4,650 |                                       71% |                                 7,721 |                                 19,381 |
|             [South Africa](/south-africa) |              429 |                     7,161 |                     122 |                      6,732 |                                     1569% |                                 3,250 |                                 11,930 |
|                     [Pakistan](/pakistan) |            1,133 |                     6,851 |                      32 |                      5,718 |                                      505% |                                 1,971 |                                 16,250 |
|                           [Chile](/chile) |              718 |                     6,761 |                     357 |                      6,043 |                                      842% |                                 3,692 |                                 10,514 |
|                       [Ecuador](/ecuador) |            3,108 |                     6,593 |                     379 |                      3,485 |                                      112% |                                 3,908 |                                 15,373 |
|                 [Bangladesh](/bangladesh) |              480 |                     5,387 |                      33 |                      4,907 |                                     1022% |                                 1,662 |                                 11,936 |
|                         [Turkey](/turkey) |            4,340 |                     5,293 |                      63 |                        953 |                                       22% |                                 4,692 |                                  6,873 |
|                           [China](/china) |            4,638 |                     4,643 |                       3 |                          5 |                                        0% |                                 4,638 |                                  4,674 |
|                     [Colombia](/colombia) |              727 |                     4,373 |                      87 |                      3,646 |                                      502% |                                 1,918 |                                  8,803 |
|                   [Indonesia](/indonesia) |            1,372 |                     3,320 |                      12 |                      1,948 |                                      142% |                                 1,933 |                                  6,304 |
|                           [Egypt](/egypt) |              764 |                     3,162 |                      31 |                      2,398 |                                      314% |                                 1,248 |                                  7,205 |
|             [Saudi Arabia](/saudi-arabia) |              390 |                     2,543 |                      74 |                      2,153 |                                      552% |                                 1,054 |                                  5,334 |
|                   [Argentina](/argentina) |              452 |                     1,781 |                      40 |                      1,329 |                                      294% |                                   829 |                                  3,306 |
|               [Philippines](/philippines) |              868 |                     1,337 |                      12 |                        469 |                                       54% |                                   986 |                                  1,941 |
|                           [Japan](/japan) |              820 |                     1,029 |                       8 |                        209 |                                       25% |                                   835 |                                  1,424 |
|                       [Nigeria](/nigeria) |              226 |                       973 |                       5 |                        747 |                                      331% |                                   364 |                                  3,105 |
|                       [Algeria](/algeria) |              600 |                       718 |                      17 |                        118 |                                       20% |                                   627 |                                    965 |
| [Dominican Republic](/dominican-republic) |              458 |                       693 |                      65 |                        235 |                                       51% |                                   544 |                                  1,073 |
|                         [Panama](/panama) |              306 |                       640 |                     151 |                        334 |                                      109% |                                   385 |                                  1,433 |
|                         [Israel](/israel) |              279 |                       332 |                      39 |                         53 |                                       19% |                                   302 |                                    396 |
|               [South Korea](/south-korea) |              267 |                       311 |                       6 |                         44 |                                       16% |                                   282 |                                    367 |
|                       [Morocco](/morocco) |              199 |                       225 |                       6 |                         26 |                                       13% |                                   211 |                                    251 |
|                     [Malaysia](/malaysia) |              115 |                       139 |                       4 |                         24 |                                       21% |                                   133 |                                    150 |
