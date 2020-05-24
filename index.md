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

## Current Projection for US - Updated Daily - Last Updated: May 24 (3am ET):
<p align="center">
  Current Total: <b>97,084</b> deaths | Projected Total: <b>180,880</b> deaths by Aug 4, 2020 (Range: 122-284k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>3.9%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 52% chance that the US surpasses 150,000 deaths by July 15, with July 11 being the most likely date.

Last updated: May 24, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 27, 2020 |
|              125,000 |        Jun 18, 2020 |
|              150,000 |        Jul 11, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |        99% |        >99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         33% |        81% |         92% |        96% |
|              150,000 |        <1% |         <1% |        22% |         52% |        69% |
|              175,000 |        <1% |         <1% |         2% |         21% |        44% |
|              200,000 |        <1% |         <1% |        <1% |          7% |        26% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         7% |
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
|         *[United States](/us)* |           97,084 |                   180,880 |                     545 |                     83,796 |                                       86% |                               122,578 |                                283,691 |
|             [New York](/us-ny) |           29,031 |                    32,783 |                   1,685 |                      3,752 |                                       13% |                                30,280 |                                 39,078 |
|           [New Jersey](/us-nj) |           11,082 |                    15,195 |                   1,711 |                      4,113 |                                       37% |                                12,505 |                                 19,697 |
|             [Illinois](/us-il) |            4,790 |                    14,414 |                   1,137 |                      9,624 |                                      201% |                                 8,756 |                                 20,803 |
|         [Pennsylvania](/us-pa) |            5,112 |                    10,933 |                     854 |                      5,821 |                                      114% |                                 7,138 |                                 15,870 |
|           [California](/us-ca) |            3,738 |                    10,090 |                     255 |                      6,352 |                                      170% |                                 4,961 |                                 20,249 |
|        [Massachusetts](/us-ma) |            6,304 |                     9,487 |                   1,365 |                      3,183 |                                       50% |                                 7,272 |                                 13,952 |
|                 [Ohio](/us-oh) |            1,956 |                     7,701 |                     659 |                      5,745 |                                      294% |                                 3,606 |                                 13,994 |
|             [Michigan](/us-mi) |            5,223 |                     6,749 |                     676 |                      1,526 |                                       29% |                                 5,777 |                                  8,682 |
|              [Indiana](/us-in) |            1,964 |                     5,825 |                     865 |                      3,861 |                                      197% |                                 2,857 |                                 11,619 |
|              [Florida](/us-fl) |            2,233 |                     5,418 |                     252 |                      3,185 |                                      143% |                                 2,925 |                                  9,936 |
|          [Connecticut](/us-ct) |            3,675 |                     5,156 |                   1,446 |                      1,481 |                                       40% |                                 4,191 |                                  7,007 |
|             [Maryland](/us-md) |            2,243 |                     5,006 |                     828 |                      2,763 |                                      123% |                                 2,907 |                                  9,032 |
|                [Texas](/us-tx) |            1,478 |                     4,967 |                     171 |                      3,489 |                                      236% |                                 2,272 |                                 10,015 |
|              [Georgia](/us-ga) |            1,822 |                     4,629 |                     436 |                      2,807 |                                      154% |                                 2,486 |                                  9,112 |
|              [Arizona](/us-az) |              801 |                     4,106 |                     564 |                      3,305 |                                      413% |                                 1,992 |                                  7,455 |
|            [Louisiana](/us-la) |            2,668 |                     3,767 |                     810 |                      1,099 |                                       41% |                                 3,064 |                                  5,008 |
|             [Colorado](/us-co) |            1,327 |                     3,331 |                     578 |                      2,004 |                                      151% |                                 1,882 |                                  5,920 |
|            [Minnesota](/us-mn) |              861 |                     3,184 |                     565 |                      2,323 |                                      270% |                                 1,392 |                                  6,153 |
|             [Virginia](/us-va) |            1,159 |                     3,071 |                     360 |                      1,912 |                                      165% |                                 1,616 |                                  6,424 |
|          [Mississippi](/us-ms) |              616 |                     2,730 |                     917 |                      2,114 |                                      343% |                                 1,327 |                                  4,683 |
|             [Missouri](/us-mo) |              682 |                     2,241 |                     365 |                      1,559 |                                      229% |                                 1,098 |                                  4,244 |
|                 [Iowa](/us-ia) |              446 |                     2,187 |                     693 |                      1,741 |                                      390% |                                 1,108 |                                  3,406 |
|       [North Carolina](/us-nc) |              778 |                     1,957 |                     187 |                      1,179 |                                      152% |                                 1,122 |                                  3,856 |
|              [Alabama](/us-al) |              549 |                     1,863 |                     380 |                      1,314 |                                      239% |                                   948 |                                  3,397 |
|         [Rhode Island](/us-ri) |              597 |                     1,468 |                   1,386 |                        871 |                                      146% |                                   965 |                                  2,175 |
|           [Washington](/us-wa) |            1,050 |                     1,381 |                     181 |                        331 |                                       32% |                                 1,145 |                                  1,985 |
|       [South Carolina](/us-sc) |              425 |                     1,319 |                     256 |                        894 |                                      210% |                                   630 |                                  2,941 |
|           [New Mexico](/us-nm) |              302 |                     1,051 |                     501 |                        749 |                                      248% |                                   534 |                                  1,977 |
|            [Wisconsin](/us-wi) |              507 |                       951 |                     163 |                        444 |                                       88% |                                   676 |                                  1,424 |
|             [Delaware](/us-de) |              322 |                       859 |                     882 |                        537 |                                      167% |                                   505 |                                  1,574 |
|               [Nevada](/us-nv) |              387 |                       811 |                     263 |                        424 |                                      110% |                                   535 |                                  1,524 |
|             [Kentucky](/us-ky) |              391 |                       799 |                     179 |                        408 |                                      104% |                                   525 |                                  1,453 |
| [District of Columbia](/us-dc) |              427 |                       794 |                   1,125 |                        367 |                                       86% |                                   557 |                                  1,128 |
|        [New Hampshire](/us-nh) |              208 |                       701 |                     516 |                        493 |                                      237% |                                   401 |                                  1,120 |
|            [Tennessee](/us-tn) |              329 |                       640 |                      94 |                        311 |                                       95% |                                   439 |                                  1,114 |
|             [Nebraska](/us-ne) |              147 |                       613 |                     317 |                        466 |                                      317% |                                   305 |                                  1,169 |
|             [Oklahoma](/us-ok) |              311 |                       476 |                     120 |                        165 |                                       53% |                                   378 |                                    712 |
|                 [Utah](/us-ut) |               97 |                       388 |                     121 |                        291 |                                      300% |                                   170 |                                    807 |
|               [Kansas](/us-ks) |              205 |                       311 |                     107 |                        106 |                                       52% |                                   228 |                                    539 |
|             [Arkansas](/us-ar) |              115 |                       244 |                      81 |                        129 |                                      112% |                                   172 |                                    397 |
|               [Oregon](/us-or) |              147 |                       209 |                      50 |                         62 |                                       42% |                                   168 |                                    294 |
|         [North Dakota](/us-nd) |               52 |                       205 |                     269 |                        153 |                                      294% |                                   101 |                                    462 |
|         [South Dakota](/us-sd) |               50 |                       195 |                     220 |                        145 |                                      290% |                                    89 |                                    443 |
|          [Puerto Rico](/us-pr) |              127 |                       169 |                      53 |                         42 |                                       33% |                                   148 |                                    219 |
|        [West Virginia](/us-wv) |               72 |                       119 |                      66 |                         47 |                                       65% |                                    91 |                                    189 |
|                [Maine](/us-me) |               77 |                       113 |                      84 |                         36 |                                       47% |                                    95 |                                    137 |
|                [Idaho](/us-id) |               79 |                       101 |                      57 |                         22 |                                       28% |                                    91 |                                    114 |
|              [Vermont](/us-vt) |               54 |                        66 |                     106 |                         12 |                                       22% |                                    61 |                                     70 |
|              [Wyoming](/us-wy) |               12 |                        28 |                      48 |                         16 |                                      133% |                                    18 |                                     40 |
|               [Hawaii](/us-hi) |               17 |                        24 |                      17 |                          7 |                                       41% |                                    20 |                                     27 |
|              [Montana](/us-mt) |               16 |                        20 |                      19 |                          4 |                                       25% |                                    18 |                                     24 |
|               [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    12 |                                     14 |
|       [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     8 |                                     10 |
|                 [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     7 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          165,131 |                   206,658 |                     353 |                     41,527 |                                       25% |                               176,974 |                                276,980 |
| [United Kingdom](/united-kingdom) |           36,757 |                    50,631 |                     750 |                     13,874 |                                       38% |                                40,823 |                                 76,768 |
|                   [Italy](/italy) |           32,735 |                    38,356 |                     635 |                      5,621 |                                       17% |                                34,791 |                                 45,070 |
|                   [Spain](/spain) |           28,678 |                    31,884 |                     679 |                      3,206 |                                       11% |                                29,603 |                                 36,510 |
|                 [France](/france) |           28,218 |                    31,383 |                     468 |                      3,165 |                                       11% |                                28,539 |                                 40,020 |
|               [Germany](/germany) |            8,261 |                    10,495 |                     126 |                      2,234 |                                       27% |                                 8,794 |                                 14,919 |
|               [Belgium](/belgium) |            9,237 |                    10,283 |                     898 |                      1,046 |                                       11% |                                 9,454 |                                 12,325 |
|       [Netherlands](/netherlands) |            5,830 |                     7,292 |                     422 |                      1,462 |                                       25% |                                 6,214 |                                 10,443 |
|                 [Sweden](/sweden) |            3,992 |                     5,790 |                     566 |                      1,798 |                                       45% |                                 4,665 |                                  7,370 |
|               [Ukraine](/ukraine) |              605 |                     3,973 |                      90 |                      3,368 |                                      557% |                                 1,403 |                                  7,937 |
|               [Romania](/romania) |            1,176 |                     2,445 |                     126 |                      1,269 |                                      108% |                                 1,678 |                                  4,506 |
|       [Switzerland](/switzerland) |            1,905 |                     2,153 |                     251 |                        248 |                                       13% |                                 1,970 |                                  2,610 |
|                 [Poland](/poland) |              993 |                     2,148 |                      57 |                      1,155 |                                      116% |                                 1,245 |                                  4,516 |
|               [Ireland](/ireland) |            1,604 |                     1,904 |                     388 |                        300 |                                       19% |                                 1,675 |                                  2,571 |
|             [Portugal](/portugal) |            1,302 |                     1,848 |                     180 |                        546 |                                       42% |                                 1,523 |                                  2,474 |
|               [Moldova](/moldova) |              242 |                     1,089 |                     269 |                        847 |                                      350% |                                   484 |                                  2,102 |
|               [Austria](/austria) |              639 |                       747 |                      84 |                        108 |                                       17% |                                   678 |                                    882 |
|               [Hungary](/hungary) |              482 |                       734 |                      75 |                        252 |                                       52% |                                   539 |                                  1,193 |
|               [Denmark](/denmark) |              561 |                       709 |                     122 |                        148 |                                       26% |                                   622 |                                    869 |
|               [Finland](/finland) |              306 |                       464 |                      84 |                        158 |                                       52% |                                   350 |                                    751 |
|             [Bulgaria](/bulgaria) |              126 |                       409 |                      58 |                        283 |                                      225% |                                   230 |                                    757 |
|               [Czechia](/czechia) |              314 |                       394 |                      37 |                         80 |                                       25% |                                   361 |                                    448 |
|                 [Serbia](/serbia) |              238 |                       348 |                      40 |                        110 |                                       46% |                                   290 |                                    528 |
|                 [Norway](/norway) |              235 |                       271 |                      50 |                         36 |                                       15% |                                   248 |                                    305 |
|                 [Greece](/greece) |              171 |                       213 |                      20 |                         42 |                                       25% |                                   191 |                                    253 |
|               [Croatia](/croatia) |               99 |                       157 |                      39 |                         58 |                                       59% |                                   118 |                                    235 |
|         [Luxembourg](/luxembourg) |              109 |                       129 |                     210 |                         20 |                                       18% |                                   118 |                                    148 |
|             [Slovenia](/slovenia) |              106 |                       126 |                      61 |                         20 |                                       19% |                                   112 |                                    149 |
|           [Lithuania](/lithuania) |               63 |                        87 |                      31 |                         24 |                                       38% |                                    77 |                                    106 |
|               [Estonia](/estonia) |               64 |                        84 |                      63 |                         20 |                                       31% |                                    76 |                                     92 |
|                 [Latvia](/latvia) |               22 |                        35 |                      18 |                         13 |                                       59% |                                    33 |                                     38 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    30 |                                     40 |
|                 [Cyprus](/cyprus) |               17 |                        22 |                      25 |                          5 |                                       29% |                                    21 |                                     23 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    11 |                                     13 |
|                   [Malta](/malta) |                6 |                         8 |                      16 |                          2 |                                       33% |                                     8 |                                      9 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           76,035 |                   397,083 |                      78 |                    321,048 |                                      422% |                               150,405 |                                746,534 |
|                         [Brazil](/brazil) |           22,013 |                   158,394 |                     751 |                    136,381 |                                      620% |                                54,050 |                                275,570 |
|                         [Mexico](/mexico) |            7,179 |                    85,245 |                     668 |                     78,066 |                                     1087% |                                26,557 |                                144,040 |
|                           [India](/india) |            3,868 |                    33,733 |                      25 |                     29,865 |                                      772% |                                 7,945 |                                 93,554 |
|                         [Russia](/russia) |            3,388 |                    19,078 |                     131 |                     15,690 |                                      463% |                                 5,820 |                                 51,730 |
|                             [Peru](/peru) |            3,373 |                    13,671 |                     421 |                     10,298 |                                      305% |                                 5,806 |                                 20,455 |
|                             [Iran](/iran) |            7,359 |                    12,163 |                     147 |                      4,804 |                                       65% |                                 8,090 |                                 22,416 |
|                         [Canada](/canada) |            6,466 |                    11,638 |                     311 |                      5,172 |                                       80% |                                 7,778 |                                 19,895 |
|                     [Pakistan](/pakistan) |            1,101 |                     7,009 |                      32 |                      5,908 |                                      537% |                                 1,927 |                                 16,693 |
|             [South Africa](/south-africa) |              407 |                     6,926 |                     118 |                      6,519 |                                     1602% |                                 2,915 |                                 11,817 |
|                           [Chile](/chile) |              673 |                     6,516 |                     344 |                      5,843 |                                      868% |                                 3,485 |                                 10,114 |
|                       [Ecuador](/ecuador) |            3,096 |                     6,500 |                     374 |                      3,404 |                                      110% |                                 3,778 |                                 15,720 |
|                         [Turkey](/turkey) |            4,308 |                     5,263 |                      63 |                        955 |                                       22% |                                 4,674 |                                  6,885 |
|                 [Bangladesh](/bangladesh) |              452 |                     5,054 |                      31 |                      4,602 |                                     1018% |                                 1,547 |                                 11,842 |
|                           [China](/china) |            4,638 |                     4,645 |                       3 |                          7 |                                        0% |                                 4,638 |                                  4,672 |
|                     [Colombia](/colombia) |              705 |                     4,476 |                      89 |                      3,771 |                                      535% |                                 1,885 |                                  9,208 |
|                           [Egypt](/egypt) |              735 |                     2,931 |                      29 |                      2,196 |                                      299% |                                 1,152 |                                  7,089 |
|                   [Indonesia](/indonesia) |            1,351 |                     2,923 |                      11 |                      1,572 |                                      116% |                                 1,854 |                                  4,598 |
|             [Saudi Arabia](/saudi-arabia) |              379 |                     2,604 |                      76 |                      2,225 |                                      587% |                                 1,046 |                                  5,401 |
|                   [Argentina](/argentina) |              445 |                     1,994 |                      45 |                      1,549 |                                      348% |                                   869 |                                  3,528 |
|               [Philippines](/philippines) |              863 |                     1,386 |                      13 |                        523 |                                       61% |                                   996 |                                  2,175 |
|                           [Japan](/japan) |              808 |                     1,022 |                       8 |                        214 |                                       26% |                                   823 |                                  1,424 |
|                       [Nigeria](/nigeria) |              221 |                       874 |                       4 |                        653 |                                      295% |                                   326 |                                  3,072 |
|                       [Algeria](/algeria) |              592 |                       698 |                      16 |                        106 |                                       18% |                                   617 |                                    930 |
| [Dominican Republic](/dominican-republic) |              458 |                       691 |                      64 |                        233 |                                       51% |                                   532 |                                  1,087 |
|                         [Panama](/panama) |              299 |                       637 |                     150 |                        338 |                                      113% |                                   373 |                                  1,435 |
|                         [Israel](/israel) |              279 |                       335 |                      39 |                         56 |                                       20% |                                   303 |                                    400 |
|               [South Korea](/south-korea) |              266 |                       312 |                       6 |                         46 |                                       17% |                                   280 |                                    378 |
|                       [Morocco](/morocco) |              198 |                       224 |                       6 |                         26 |                                       13% |                                   210 |                                    251 |
|                     [Malaysia](/malaysia) |              115 |                       141 |                       4 |                         26 |                                       23% |                                   129 |                                    155 |
