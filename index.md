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

* **Jun 1:** We have lowered our US projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), and [slow reopenings](https://twitter.com/youyanggu/status/1267551592837832704).

* **May 29:** We ran a simulation on what would happen if just 20% of infected individuals reduced their own transmission by 25% (such as by self-quarantining immediately after showing symptoms). US deaths would be 30% lower by May 29, and up to 50% lower by September. See the results [here](/us-self-quarantine).

* **May 27:** We added [7 new countries](/#global-projections) (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), [2 Canadian provinces](/#global-projections) (Alberta and British Columbia), and [20 US counties](/#us-counties). We now have projections for 71 countries (>99% of all global COVID-19 deaths), 4 Canadian provinces (99% of Canadian COVID-19 deaths), 56 US states and territories, and 34 US counties (including the top 30 most populous counties).

* **May 26:** We have extended our projections to September 1, 2020.

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: Jun 4 (1am ET):
<p align="center">
  Current Total: <b>107,172</b> deaths | Projected Total: <b>186,959 deaths by Sep 1, 2020</b> (Range: 128-281k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.1%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 26 being the most likely date.

Last updated: Jun 4, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              110,000 |         Jun 7, 2020 |
|              120,000 |        Jun 19, 2020 |
|              125,000 |        Jun 26, 2020 |
|              130,000 |         Jul 2, 2020 |
|              140,000 |        Jul 14, 2020 |
|              150,000 |        Jul 24, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        73% |         92% |        97% |         98% |        99% |
|              150,000 |         <1% |        <1% |         26% |        57% |         68% |        75% |
|              175,000 |         <1% |        <1% |         <1% |        23% |         41% |        52% |
|              200,000 |         <1% |        <1% |         <1% |         5% |         21% |        35% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        11% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          107,172 |                   186,959 |                     563 |                     79,787 |                                       74% |                               128,220 |                                280,973 |
|                 [New York](/us-ny) |           30,019 |                    32,934 |                   1,693 |                      2,915 |                                       10% |                                30,661 |                                 37,542 |
|               [New Jersey](/us-nj) |           11,880 |                    14,625 |                   1,647 |                      2,745 |                                       23% |                                12,836 |                                 18,086 |
|               [California](/us-ca) |            4,374 |                    13,033 |                     330 |                      8,659 |                                      198% |                                 6,076 |                                 23,834 |
|                 [Illinois](/us-il) |            5,621 |                    10,620 |                     838 |                      4,999 |                                       89% |                                 7,432 |                                 14,314 |
|            [Massachusetts](/us-ma) |            7,152 |                     9,594 |                   1,381 |                      2,442 |                                       34% |                                 8,020 |                                 12,513 |
|             [Pennsylvania](/us-pa) |            5,742 |                     9,562 |                     747 |                      3,820 |                                       67% |                                 6,838 |                                 13,919 |
|                  [Florida](/us-fl) |            2,566 |                     7,196 |                     335 |                      4,630 |                                      180% |                                 3,506 |                                 12,251 |
|                 [Michigan](/us-mi) |            5,570 |                     6,957 |                     697 |                      1,387 |                                       25% |                                 6,007 |                                  9,413 |
|                     [Ohio](/us-oh) |            2,300 |                     6,826 |                     584 |                      4,526 |                                      197% |                                 3,663 |                                 10,690 |
|                 [Maryland](/us-md) |            2,641 |                     6,189 |                   1,024 |                      3,548 |                                      134% |                                 3,524 |                                  9,798 |
|              [Connecticut](/us-ct) |            3,989 |                     5,238 |                   1,469 |                      1,249 |                                       31% |                                 4,303 |                                  6,827 |
|                  [Georgia](/us-ga) |            2,123 |                     5,193 |                     489 |                      3,070 |                                      145% |                                 3,016 |                                  9,814 |
|                    [Texas](/us-tx) |            1,744 |                     5,186 |                     179 |                      3,442 |                                      197% |                                 2,710 |                                 10,040 |
|                  [Indiana](/us-in) |            2,207 |                     4,799 |                     713 |                      2,592 |                                      117% |                                 2,842 |                                  8,009 |
|                [Louisiana](/us-la) |            2,870 |                     4,340 |                     934 |                      1,470 |                                       51% |                                 3,269 |                                  7,045 |
|                 [Virginia](/us-va) |            1,428 |                     4,030 |                     472 |                      2,602 |                                      182% |                                 1,937 |                                  7,386 |
|                [Minnesota](/us-mn) |            1,097 |                     3,900 |                     692 |                      2,803 |                                      256% |                                 1,837 |                                  6,252 |
|           [North Carolina](/us-nc) |              999 |                     3,860 |                     368 |                      2,861 |                                      286% |                                 1,819 |                                  6,422 |
|                  [Arizona](/us-az) |              983 |                     3,489 |                     479 |                      2,506 |                                      255% |                                 1,442 |                                  6,174 |
|                 [Colorado](/us-co) |            1,494 |                     3,150 |                     547 |                      1,656 |                                      111% |                                 1,773 |                                  6,185 |
|              [Mississippi](/us-ms) |              782 |                     2,567 |                     863 |                      1,785 |                                      228% |                                 1,145 |                                  4,146 |
|                 [Missouri](/us-mo) |              791 |                     2,504 |                     408 |                      1,713 |                                      217% |                                 1,215 |                                  4,216 |
|                  [Alabama](/us-al) |              653 |                     2,145 |                     437 |                      1,492 |                                      228% |                                 1,084 |                                  3,713 |
|               [Washington](/us-wa) |            1,135 |                     1,974 |                     259 |                        839 |                                       74% |                                 1,273 |                                  3,619 |
|                [Wisconsin](/us-wi) |              616 |                     1,757 |                     302 |                      1,141 |                                      185% |                                   924 |                                  3,150 |
|             [Rhode Island](/us-ri) |              742 |                     1,713 |                   1,617 |                        971 |                                      131% |                                 1,153 |                                  2,317 |
|                     [Iowa](/us-ia) |              574 |                     1,633 |                     518 |                      1,059 |                                      184% |                                 1,085 |                                  2,356 |
|           [South Carolina](/us-sc) |              501 |                     1,601 |                     311 |                      1,100 |                                      220% |                                   736 |                                  2,848 |
|                 [Kentucky](/us-ky) |              450 |                     1,183 |                     265 |                        733 |                                      163% |                                   629 |                                  2,165 |
|               [New Mexico](/us-nm) |              375 |                     1,119 |                     534 |                        744 |                                      198% |                                   598 |                                  1,728 |
|                [Tennessee](/us-tn) |              388 |                     1,061 |                     155 |                        673 |                                      173% |                                   544 |                                  2,020 |
|                   [Nevada](/us-nv) |              431 |                       956 |                     310 |                        525 |                                      122% |                                   567 |                                  1,659 |
|            [New Hampshire](/us-nh) |              265 |                       793 |                     583 |                        528 |                                      199% |                                   365 |                                  1,467 |
|     [District of Columbia](/us-dc) |              473 |                       741 |                   1,050 |                        268 |                                       57% |                                   536 |                                  1,168 |
|                 [Delaware](/us-de) |              375 |                       691 |                     710 |                        316 |                                       84% |                                   445 |                                  1,240 |
|                 [Oklahoma](/us-ok) |              341 |                       561 |                     142 |                        220 |                                       65% |                                   406 |                                    962 |
|                 [Arkansas](/us-ar) |              142 |                       524 |                     174 |                        382 |                                      269% |                                   237 |                                    927 |
|                     [Utah](/us-ut) |              117 |                       473 |                     148 |                        356 |                                      304% |                                   203 |                                    846 |
|                 [Nebraska](/us-ne) |              170 |                       440 |                     227 |                        270 |                                      159% |                                   276 |                                    739 |
|                   [Kansas](/us-ks) |              226 |                       394 |                     135 |                        168 |                                       74% |                                   256 |                                    893 |
|                   [Oregon](/us-or) |              159 |                       248 |                      59 |                         89 |                                       56% |                                   179 |                                    424 |
|              [Puerto Rico](/us-pr) |              140 |                       203 |                      64 |                         63 |                                       45% |                                   162 |                                    292 |
|             [South Dakota](/us-sd) |               62 |                       188 |                     213 |                        126 |                                      203% |                                   100 |                                    396 |
|             [North Dakota](/us-nd) |               66 |                       183 |                     240 |                        117 |                                      177% |                                   116 |                                    333 |
|                    [Maine](/us-me) |               95 |                       159 |                     118 |                         64 |                                       67% |                                   118 |                                    272 |
|            [West Virginia](/us-wv) |               78 |                       127 |                      71 |                         49 |                                       63% |                                    94 |                                    208 |
|                    [Idaho](/us-id) |               83 |                       104 |                      58 |                         21 |                                       25% |                                    92 |                                    129 |
|                  [Vermont](/us-vt) |               55 |                        65 |                     104 |                         10 |                                       18% |                                    60 |                                     71 |
|                  [Wyoming](/us-wy) |               17 |                        42 |                      73 |                         25 |                                      147% |                                    31 |                                     56 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     22 |
| [Northern Mariana Islands](/us-mp) |               16 |                        21 |                     380 |                          5 |                                       31% |                                    19 |                                     23 |
|                  [Montana](/us-mt) |               17 |                        20 |                      19 |                          3 |                                       18% |                                    18 |                                     24 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     13 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          170,751 |                   203,285 |                     343 |                     32,534 |                                       19% |                               182,086 |                                249,181 |
| [United Kingdom](/united-kingdom) |           39,811 |                    49,529 |                     733 |                      9,718 |                                       24% |                                44,609 |                                 55,391 |
|                   [Italy](/italy) |           33,601 |                    38,137 |                     632 |                      4,536 |                                       13% |                                34,767 |                                 43,845 |
|                 [France](/france) |           29,024 |                    31,053 |                     463 |                      2,029 |                                        7% |                                29,223 |                                 37,740 |
|                   [Spain](/spain) |           27,128 |                    28,770 |                     613 |                      1,642 |                                        6% |                                27,310 |                                 34,131 |
|               [Germany](/germany) |            8,602 |                    10,317 |                     124 |                      1,715 |                                       20% |                                 8,920 |                                 15,057 |
|               [Belgium](/belgium) |            9,522 |                    10,188 |                     889 |                        666 |                                        7% |                                 9,669 |                                 11,489 |
|                 [Sweden](/sweden) |            4,542 |                     7,771 |                     760 |                      3,229 |                                       71% |                                 6,416 |                                 12,045 |
|       [Netherlands](/netherlands) |            5,996 |                     6,972 |                     403 |                        976 |                                       16% |                                 6,223 |                                  8,634 |
|               [Ukraine](/ukraine) |              742 |                     3,114 |                      71 |                      2,372 |                                      320% |                                 1,361 |                                  5,188 |
|                 [Poland](/poland) |            1,115 |                     2,323 |                      61 |                      1,208 |                                      108% |                                 1,394 |                                  3,964 |
|             [Portugal](/portugal) |            1,447 |                     2,120 |                     206 |                        673 |                                       47% |                                 1,677 |                                  3,109 |
|       [Switzerland](/switzerland) |            1,921 |                     2,056 |                     239 |                        135 |                                        7% |                                 1,947 |                                  2,311 |
|               [Romania](/romania) |            1,296 |                     2,037 |                     105 |                        741 |                                       57% |                                 1,612 |                                  3,087 |
|               [Ireland](/ireland) |            1,659 |                     1,809 |                     369 |                        150 |                                        9% |                                 1,685 |                                  2,367 |
|               [Moldova](/moldova) |              310 |                     1,310 |                     324 |                      1,000 |                                      323% |                                   673 |                                  2,028 |
|               [Hungary](/hungary) |              534 |                       884 |                      90 |                        350 |                                       66% |                                   610 |                                  1,594 |
|               [Austria](/austria) |              670 |                       741 |                      84 |                         71 |                                       11% |                                   694 |                                    863 |
|               [Belarus](/belarus) |              248 |                       684 |                      72 |                        436 |                                      176% |                                   391 |                                  1,854 |
|               [Denmark](/denmark) |              580 |                       680 |                     117 |                        100 |                                       17% |                                   617 |                                    813 |
|             [Bulgaria](/bulgaria) |              146 |                       520 |                      74 |                        374 |                                      256% |                                   261 |                                    858 |
|               [Finland](/finland) |              321 |                       394 |                      71 |                         73 |                                       23% |                                   339 |                                    534 |
|               [Czechia](/czechia) |              325 |                       371 |                      35 |                         46 |                                       14% |                                   351 |                                    413 |
|                 [Serbia](/serbia) |              245 |                       320 |                      46 |                         75 |                                       31% |                                   277 |                                    418 |
|                 [Norway](/norway) |              237 |                       264 |                      49 |                         27 |                                       11% |                                   247 |                                    302 |
|                 [Greece](/greece) |              179 |                       219 |                      20 |                         40 |                                       22% |                                   198 |                                    255 |
|               [Croatia](/croatia) |              103 |                       136 |                      33 |                         33 |                                       32% |                                   114 |                                    185 |
|           [Lithuania](/lithuania) |               71 |                       130 |                      47 |                         59 |                                       83% |                                    95 |                                    215 |
|         [Luxembourg](/luxembourg) |              110 |                       123 |                     200 |                         13 |                                       12% |                                   114 |                                    142 |
|             [Slovenia](/slovenia) |              109 |                       123 |                      59 |                         14 |                                       13% |                                   113 |                                    145 |
|               [Estonia](/estonia) |               69 |                        82 |                      62 |                         13 |                                       19% |                                    79 |                                     87 |
|             [Slovakia](/slovakia) |               28 |                        32 |                       6 |                          4 |                                       14% |                                    29 |                                     36 |
|                 [Latvia](/latvia) |               24 |                        31 |                      16 |                          7 |                                       29% |                                    30 |                                     32 |
|                 [Cyprus](/cyprus) |               17 |                        20 |                      23 |                          3 |                                       18% |                                    19 |                                     21 |
|                   [Malta](/malta) |                9 |                        14 |                      28 |                          5 |                                       56% |                                    12 |                                     16 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          104,241 |                   459,967 |                      89 |                    355,726 |                                      341% |                               228,594 |                                699,882 |
|                             [Brazil](/brazil) |           32,548 |                   144,149 |                     683 |                    111,601 |                                      343% |                                68,255 |                                247,916 |
|                             [Mexico](/mexico) |           11,729 |                    81,099 |                     636 |                     69,370 |                                      591% |                                40,195 |                                103,999 |
|                               [India](/india) |            6,088 |                    59,698 |                      44 |                     53,610 |                                      881% |                                20,610 |                                 77,589 |
|                             [Russia](/russia) |            5,208 |                    25,985 |                     178 |                     20,777 |                                      399% |                                 9,968 |                                 42,967 |
|                                 [Peru](/peru) |            4,894 |                    25,430 |                     782 |                     20,536 |                                      420% |                                11,048 |                                 40,561 |
|                                 [Iran](/iran) |            8,012 |                    13,417 |                     162 |                      5,405 |                                       67% |                                 9,219 |                                 22,093 |
|                             [Canada](/canada) |            7,579 |                    13,155 |                     352 |                      5,576 |                                       74% |                                 8,595 |                                 22,212 |
|                               [Chile](/chile) |            1,275 |                    11,343 |                     599 |                     10,068 |                                      790% |                                 9,617 |                                 13,491 |
|                         [Colombia](/colombia) |            1,057 |                    10,422 |                     207 |                      9,365 |                                      886% |                                 6,355 |                                 13,304 |
|                 [South Africa](/south-africa) |              792 |                    10,084 |                     172 |                      9,292 |                                     1173% |                                 6,059 |                                 12,777 |
|                         [Pakistan](/pakistan) |            1,688 |                     9,011 |                      42 |                      7,323 |                                      434% |                                 3,792 |                                 15,792 |
|                     [Bangladesh](/bangladesh) |              746 |                     6,740 |                      41 |                      5,994 |                                      803% |                                 3,674 |                                  8,867 |
|                               [Egypt](/egypt) |            1,088 |                     6,207 |                      62 |                      5,119 |                                      470% |                                 2,567 |                                  9,650 |
|                           [Ecuador](/ecuador) |            3,486 |                     6,096 |                     351 |                      2,610 |                                       75% |                                 4,105 |                                 11,646 |
|                       [Indonesia](/indonesia) |            1,698 |                     5,557 |                      21 |                      3,859 |                                      227% |                                 2,865 |                                  9,497 |
|                             [Turkey](/turkey) |            4,609 |                     5,512 |                      66 |                        903 |                                       20% |                                 4,792 |                                  7,450 |
|                               [China](/china) |            4,638 |                     4,644 |                       3 |                          6 |                                        0% |                                 4,638 |                                  4,684 |
|                 [Saudi Arabia](/saudi-arabia) |              579 |                     3,054 |                      89 |                      2,475 |                                      427% |                                 1,944 |                                  4,343 |
|                           [Bolivia](/bolivia) |              400 |                     3,054 |                     265 |                      2,654 |                                      664% |                                 1,704 |                                  4,624 |
|                       [Argentina](/argentina) |              583 |                     2,673 |                      60 |                      2,090 |                                      358% |                                 1,303 |                                  4,098 |
|                   [Philippines](/philippines) |              974 |                     2,175 |                      20 |                      1,201 |                                      123% |                                 1,172 |                                  5,270 |
|                           [Nigeria](/nigeria) |              315 |                     1,721 |                       9 |                      1,406 |                                      446% |                                   556 |                                  3,096 |
|                             [Kuwait](/kuwait) |              230 |                     1,427 |                     339 |                      1,197 |                                      520% |                                   711 |                                  2,079 |
|                               [Japan](/japan) |              905 |                     1,416 |                      11 |                        511 |                                       56% |                                   934 |                                  2,100 |
|                         [Honduras](/honduras) |              234 |                     1,172 |                     120 |                        938 |                                      401% |                                   567 |                                  1,934 |
|                           [Algeria](/algeria) |              673 |                     1,082 |                      25 |                        409 |                                       61% |                                   758 |                                  2,052 |
|                             [Panama](/panama) |              357 |                     1,042 |                     245 |                        685 |                                      192% |                                   517 |                                  1,940 |
|     [Dominican Republic](/dominican-republic) |              516 |                       844 |                      79 |                        328 |                                       64% |                                   611 |                                  1,286 |
| [United Arab Emirates](/united-arab-emirates) |              270 |                       498 |                      51 |                        228 |                                       84% |                                   331 |                                  1,019 |
|                             [Israel](/israel) |              291 |                       357 |                      42 |                         66 |                                       23% |                                   315 |                                    465 |
|                   [South Korea](/south-korea) |              273 |                       323 |                       6 |                         50 |                                       18% |                                   279 |                                    432 |
|                           [Morocco](/morocco) |              206 |                       230 |                       6 |                         24 |                                       12% |                                   216 |                                    259 |
|                         [Malaysia](/malaysia) |              115 |                       144 |                       5 |                         29 |                                       25% |                                   130 |                                    157 |
|                       [Australia](/australia) |              102 |                       108 |                       4 |                          6 |                                        6% |                                   103 |                                    124 |
|                                 [Cuba](/cuba) |               83 |                        98 |                       9 |                         15 |                                       18% |                                    89 |                                    109 |
