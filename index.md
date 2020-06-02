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

## Current Projection for US - Updated Daily - Last Updated: Jun 2 (2am ET):
<p align="center">
  Current Total: <b>105,162</b> deaths | Projected Total: <b>190,938 deaths by Sep 1, 2020</b> (Range: 127-285k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.1%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 26 being the most likely date.

Last updated: Jun 2, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              110,000 |         Jun 7, 2020 |
|              120,000 |        Jun 19, 2020 |
|              125,000 |        Jun 26, 2020 |
|              130,000 |         Jul 2, 2020 |
|              140,000 |        Jul 13, 2020 |
|              150,000 |        Jul 23, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        72% |         91% |        97% |         98% |        99% |
|              150,000 |         <1% |        <1% |         31% |        59% |         70% |        77% |
|              175,000 |         <1% |        <1% |         <1% |        28% |         46% |        55% |
|              200,000 |         <1% |        <1% |         <1% |         7% |         25% |        39% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          1% |        14% |
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
|             *[United States](/us)* |          105,162 |                   190,938 |                     575 |                     85,776 |                                       82% |                               127,887 |                                284,294 |
|                 [New York](/us-ny) |           29,917 |                    33,130 |                   1,703 |                      3,213 |                                       11% |                                30,647 |                                 38,334 |
|               [New Jersey](/us-nj) |           11,723 |                    14,390 |                   1,620 |                      2,667 |                                       23% |                                12,637 |                                 16,625 |
|               [California](/us-ca) |            4,217 |                    12,906 |                     327 |                      8,689 |                                      206% |                                 5,785 |                                 24,275 |
|                 [Illinois](/us-il) |            5,412 |                    10,397 |                     820 |                      4,985 |                                       92% |                                 7,213 |                                 14,152 |
|            [Massachusetts](/us-ma) |            7,035 |                     9,557 |                   1,375 |                      2,522 |                                       36% |                                 7,909 |                                 12,577 |
|             [Pennsylvania](/us-pa) |            5,567 |                     9,383 |                     733 |                      3,816 |                                       69% |                                 6,578 |                                 13,907 |
|                  [Florida](/us-fl) |            2,460 |                     6,989 |                     325 |                      4,529 |                                      184% |                                 3,355 |                                 12,190 |
|                 [Michigan](/us-mi) |            5,516 |                     6,943 |                     695 |                      1,427 |                                       26% |                                 5,972 |                                  9,472 |
|                     [Ohio](/us-oh) |            2,207 |                     6,655 |                     569 |                      4,448 |                                      202% |                                 3,509 |                                 10,632 |
|                 [Maryland](/us-md) |            2,552 |                     6,125 |                   1,013 |                      3,573 |                                      140% |                                 3,406 |                                  9,827 |
|                  [Georgia](/us-ga) |            2,094 |                     6,111 |                     576 |                      4,017 |                                      192% |                                 3,101 |                                  9,955 |
|                    [Texas](/us-tx) |            1,683 |                     5,453 |                     188 |                      3,770 |                                      224% |                                 2,606 |                                 10,461 |
|              [Connecticut](/us-ct) |            3,970 |                     5,370 |                   1,506 |                      1,400 |                                       35% |                                 4,372 |                                  6,940 |
|                  [Indiana](/us-in) |            2,143 |                     4,776 |                     709 |                      2,633 |                                      123% |                                 2,724 |                                  8,022 |
|                 [Virginia](/us-va) |            1,392 |                     4,432 |                     519 |                      3,040 |                                      218% |                                 1,974 |                                  7,767 |
|                [Minnesota](/us-mn) |            1,060 |                     4,244 |                     753 |                      3,184 |                                      300% |                                 1,875 |                                  6,590 |
|                [Louisiana](/us-la) |            2,801 |                     4,176 |                     898 |                      1,375 |                                       49% |                                 3,162 |                                  6,839 |
|                  [Arizona](/us-az) |              918 |                     4,078 |                     560 |                      3,160 |                                      344% |                                 1,935 |                                  6,224 |
|                 [Colorado](/us-co) |            1,458 |                     3,932 |                     683 |                      2,474 |                                      170% |                                 2,027 |                                  6,622 |
|           [North Carolina](/us-nc) |              948 |                     3,614 |                     345 |                      2,666 |                                      281% |                                 1,719 |                                  6,254 |
|              [Mississippi](/us-ms) |              739 |                     2,829 |                     951 |                      2,090 |                                      283% |                                 1,408 |                                  4,053 |
|                 [Missouri](/us-mo) |              776 |                     2,694 |                     439 |                      1,918 |                                      247% |                                 1,316 |                                  4,581 |
|                  [Alabama](/us-al) |              646 |                     2,351 |                     479 |                      1,705 |                                      264% |                                 1,188 |                                  3,901 |
|                     [Iowa](/us-ia) |              555 |                     2,242 |                     711 |                      1,687 |                                      304% |                                 1,098 |                                  3,394 |
|           [South Carolina](/us-sc) |              500 |                     1,939 |                     377 |                      1,439 |                                      288% |                                   847 |                                  3,278 |
|             [Rhode Island](/us-ri) |              720 |                     1,733 |                   1,636 |                      1,013 |                                      141% |                                 1,155 |                                  2,333 |
|               [Washington](/us-wa) |            1,123 |                     1,730 |                     227 |                        607 |                                       54% |                                 1,228 |                                  3,009 |
|                [Wisconsin](/us-wi) |              595 |                     1,646 |                     283 |                      1,051 |                                      177% |                                   884 |                                  3,014 |
|                 [Kentucky](/us-ky) |              439 |                     1,123 |                     251 |                        684 |                                      156% |                                   601 |                                  2,161 |
|               [New Mexico](/us-nm) |              362 |                     1,115 |                     532 |                        753 |                                      208% |                                   577 |                                  1,734 |
|            [New Hampshire](/us-nh) |              245 |                     1,057 |                     777 |                        812 |                                      331% |                                   530 |                                  1,569 |
|                [Tennessee](/us-tn) |              364 |                       952 |                     139 |                        588 |                                      162% |                                   513 |                                  1,872 |
|                   [Nevada](/us-nv) |              417 |                       948 |                     308 |                        531 |                                      127% |                                   542 |                                  1,667 |
|                 [Delaware](/us-de) |              368 |                       911 |                     936 |                        543 |                                      148% |                                   537 |                                  1,389 |
|     [District of Columbia](/us-dc) |              468 |                       795 |                   1,126 |                        327 |                                       70% |                                   542 |                                  1,231 |
|                 [Nebraska](/us-ne) |              170 |                       720 |                     372 |                        550 |                                      324% |                                   328 |                                  1,200 |
|                 [Oklahoma](/us-ok) |              350 |                       639 |                     161 |                        289 |                                       83% |                                   430 |                                  1,128 |
|                     [Utah](/us-ut) |              113 |                       497 |                     155 |                        384 |                                      340% |                                   201 |                                    871 |
|                 [Arkansas](/us-ar) |              133 |                       474 |                     157 |                        341 |                                      256% |                                   224 |                                    857 |
|                   [Kansas](/us-ks) |              217 |                       369 |                     127 |                        152 |                                       70% |                                   243 |                                    831 |
|             [South Dakota](/us-sd) |               62 |                       272 |                     307 |                        210 |                                      339% |                                   103 |                                    536 |
|                   [Oregon](/us-or) |              154 |                       237 |                      56 |                         83 |                                       54% |                                   171 |                                    410 |
|             [North Dakota](/us-nd) |               61 |                       236 |                     310 |                        175 |                                      287% |                                   106 |                                    479 |
|              [Puerto Rico](/us-pr) |              136 |                       195 |                      61 |                         59 |                                       43% |                                   158 |                                    286 |
|                    [Maine](/us-me) |               89 |                       136 |                     101 |                         47 |                                       53% |                                   109 |                                    194 |
|            [West Virginia](/us-wv) |               76 |                       120 |                      67 |                         44 |                                       58% |                                    89 |                                    204 |
|                    [Idaho](/us-id) |               82 |                       104 |                      58 |                         22 |                                       27% |                                    91 |                                    132 |
|                  [Wyoming](/us-wy) |               17 |                        75 |                     130 |                         58 |                                      341% |                                    37 |                                    157 |
|                  [Vermont](/us-vt) |               55 |                        65 |                     104 |                         10 |                                       18% |                                    60 |                                     75 |
|                  [Montana](/us-mt) |               17 |                        21 |                      20 |                          4 |                                       24% |                                    19 |                                     25 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     23 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     13 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          169,360 |                   202,150 |                     341 |                     32,790 |                                       19% |                               179,147 |                                250,823 |
| [United Kingdom](/united-kingdom) |           39,127 |                    47,739 |                     707 |                      8,612 |                                       22% |                                41,923 |                                 54,725 |
|                   [Italy](/italy) |           33,475 |                    38,223 |                     633 |                      4,748 |                                       14% |                                34,768 |                                 44,002 |
|                 [France](/france) |           28,836 |                    30,939 |                     462 |                      2,103 |                                        7% |                                29,063 |                                 37,830 |
|                   [Spain](/spain) |           27,127 |                    28,894 |                     616 |                      1,767 |                                        7% |                                27,332 |                                 34,969 |
|               [Germany](/germany) |            8,555 |                    10,384 |                     125 |                      1,829 |                                       21% |                                 8,904 |                                 15,270 |
|               [Belgium](/belgium) |            9,486 |                    10,199 |                     890 |                        713 |                                        8% |                                 9,649 |                                 11,551 |
|                 [Sweden](/sweden) |            4,403 |                     7,851 |                     767 |                      3,448 |                                       78% |                                 6,339 |                                 12,175 |
|       [Netherlands](/netherlands) |            5,981 |                     7,022 |                     406 |                      1,041 |                                       17% |                                 6,231 |                                  8,697 |
|               [Ukraine](/ukraine) |              724 |                     3,407 |                      77 |                      2,683 |                                      371% |                                 1,434 |                                  5,613 |
|                 [Poland](/poland) |            1,074 |                     2,135 |                      56 |                      1,061 |                                       99% |                                 1,320 |                                  3,884 |
|               [Romania](/romania) |            1,276 |                     2,088 |                     108 |                        812 |                                       64% |                                 1,616 |                                  3,189 |
|             [Portugal](/portugal) |            1,424 |                     2,066 |                     201 |                        642 |                                       45% |                                 1,649 |                                  3,053 |
|       [Switzerland](/switzerland) |            1,920 |                     2,064 |                     240 |                        144 |                                        8% |                                 1,948 |                                  2,329 |
|               [Ireland](/ireland) |            1,650 |                     1,809 |                     369 |                        159 |                                       10% |                                 1,676 |                                  2,379 |
|               [Moldova](/moldova) |              305 |                     1,486 |                     368 |                      1,181 |                                      387% |                                   713 |                                  2,256 |
|               [Hungary](/hungary) |              527 |                       891 |                      91 |                        364 |                                       69% |                                   605 |                                  1,637 |
|               [Austria](/austria) |              668 |                       743 |                      84 |                         75 |                                       11% |                                   694 |                                    867 |
|               [Belarus](/belarus) |              240 |                       741 |                      78 |                        501 |                                      209% |                                   389 |                                  1,883 |
|               [Denmark](/denmark) |              576 |                       679 |                     117 |                        103 |                                       18% |                                   615 |                                    815 |
|             [Bulgaria](/bulgaria) |              140 |                       499 |                      71 |                        359 |                                      256% |                                   252 |                                    855 |
|               [Finland](/finland) |              318 |                       392 |                      71 |                         74 |                                       23% |                                   335 |                                    537 |
|               [Czechia](/czechia) |              321 |                       370 |                      35 |                         49 |                                       15% |                                   348 |                                    413 |
|                 [Serbia](/serbia) |              244 |                       325 |                      47 |                         81 |                                       33% |                                   278 |                                    424 |
|                 [Norway](/norway) |              236 |                       264 |                      49 |                         28 |                                       12% |                                   246 |                                    302 |
|                 [Greece](/greece) |              179 |                       221 |                      21 |                         42 |                                       23% |                                   201 |                                    257 |
|               [Croatia](/croatia) |              103 |                       143 |                      35 |                         40 |                                       39% |                                   116 |                                    197 |
|           [Lithuania](/lithuania) |               70 |                       135 |                      48 |                         65 |                                       93% |                                    95 |                                    218 |
|         [Luxembourg](/luxembourg) |              110 |                       124 |                     202 |                         14 |                                       13% |                                   114 |                                    143 |
|             [Slovenia](/slovenia) |              109 |                       124 |                      60 |                         15 |                                       14% |                                   113 |                                    146 |
|               [Estonia](/estonia) |               68 |                        82 |                      62 |                         14 |                                       21% |                                    78 |                                     87 |
|             [Slovakia](/slovakia) |               28 |                        33 |                       6 |                          5 |                                       18% |                                    29 |                                     37 |
|                 [Latvia](/latvia) |               24 |                        32 |                      17 |                          8 |                                       33% |                                    31 |                                     34 |
|                 [Cyprus](/cyprus) |               17 |                        20 |                      23 |                          3 |                                       18% |                                    19 |                                     21 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       67% |                                    13 |                                     16 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           97,532 |                   440,024 |                      85 |                    342,492 |                                      351% |                               206,623 |                                715,384 |
|                             [Brazil](/brazil) |           29,937 |                   132,021 |                     626 |                    102,084 |                                      341% |                                62,819 |                                249,751 |
|                             [Mexico](/mexico) |           10,167 |                    81,526 |                     639 |                     71,359 |                                      702% |                                35,896 |                                124,386 |
|                               [India](/india) |            5,608 |                    56,055 |                      41 |                     50,447 |                                      900% |                                16,228 |                                 76,685 |
|                                 [Peru](/peru) |            4,634 |                    27,438 |                     844 |                     22,804 |                                      492% |                                11,158 |                                 41,695 |
|                             [Russia](/russia) |            4,849 |                    24,602 |                     169 |                     19,753 |                                      407% |                                 9,314 |                                 42,315 |
|                             [Canada](/canada) |            7,404 |                    13,091 |                     350 |                      5,687 |                                       77% |                                 8,409 |                                 22,329 |
|                                 [Iran](/iran) |            7,878 |                    11,994 |                     145 |                      4,116 |                                       52% |                                 8,730 |                                 20,134 |
|                               [Chile](/chile) |            1,113 |                    10,415 |                     550 |                      9,302 |                                      836% |                                 6,944 |                                 12,501 |
|                 [South Africa](/south-africa) |              705 |                     9,700 |                     166 |                      8,995 |                                     1276% |                                 5,901 |                                 12,166 |
|                         [Pakistan](/pakistan) |            1,543 |                     9,596 |                      44 |                      8,053 |                                      522% |                                 3,288 |                                 15,652 |
|                         [Colombia](/colombia) |              963 |                     8,534 |                     170 |                      7,571 |                                      786% |                                 4,057 |                                 12,521 |
|                     [Bangladesh](/bangladesh) |              672 |                     6,382 |                      39 |                      5,710 |                                      850% |                                 3,509 |                                  8,661 |
|                           [Ecuador](/ecuador) |            3,358 |                     6,144 |                     354 |                      2,786 |                                       83% |                                 4,018 |                                 12,130 |
|                               [Egypt](/egypt) |            1,005 |                     5,599 |                      56 |                      4,594 |                                      457% |                                 2,251 |                                  8,978 |
|                       [Indonesia](/indonesia) |            1,641 |                     5,549 |                      21 |                      3,908 |                                      238% |                                 2,820 |                                  9,713 |
|                             [Turkey](/turkey) |            4,563 |                     5,510 |                      66 |                        947 |                                       21% |                                 4,755 |                                  7,531 |
|                               [China](/china) |            4,638 |                     4,645 |                       3 |                          7 |                                        0% |                                 4,638 |                                  4,687 |
|                 [Saudi Arabia](/saudi-arabia) |              525 |                     3,878 |                     113 |                      3,353 |                                      639% |                                 1,968 |                                  5,023 |
|                           [Bolivia](/bolivia) |              343 |                     2,728 |                     237 |                      2,385 |                                      695% |                                 1,536 |                                  4,090 |
|                       [Argentina](/argentina) |              556 |                     2,655 |                      59 |                      2,099 |                                      378% |                                 1,271 |                                  4,117 |
|                   [Philippines](/philippines) |              960 |                     1,855 |                      17 |                        895 |                                       93% |                                 1,153 |                                  3,322 |
|                           [Nigeria](/nigeria) |              299 |                     1,582 |                       8 |                      1,283 |                                      429% |                                   522 |                                  3,059 |
|                             [Kuwait](/kuwait) |              220 |                     1,481 |                     352 |                      1,261 |                                      573% |                                   746 |                                  2,167 |
|                               [Japan](/japan) |              899 |                     1,449 |                      11 |                        550 |                                       61% |                                   938 |                                  2,185 |
|                         [Honduras](/honduras) |              217 |                     1,054 |                     108 |                        837 |                                      386% |                                   484 |                                  1,882 |
|                           [Algeria](/algeria) |              661 |                     1,022 |                      24 |                        361 |                                       55% |                                   760 |                                  1,960 |
|                             [Panama](/panama) |              344 |                       935 |                     220 |                        591 |                                      172% |                                   459 |                                  1,862 |
|     [Dominican Republic](/dominican-republic) |              502 |                       817 |                      76 |                        315 |                                       63% |                                   597 |                                  1,271 |
| [United Arab Emirates](/united-arab-emirates) |              266 |                       515 |                      53 |                        249 |                                       94% |                                   333 |                                  1,057 |
|                             [Israel](/israel) |              285 |                       346 |                      41 |                         61 |                                       21% |                                   306 |                                    454 |
|                   [South Korea](/south-korea) |              272 |                       325 |                       6 |                         53 |                                       19% |                                   279 |                                    437 |
|                           [Morocco](/morocco) |              205 |                       230 |                       6 |                         25 |                                       12% |                                   215 |                                    259 |
|                         [Malaysia](/malaysia) |              115 |                       144 |                       5 |                         29 |                                       25% |                                   128 |                                    169 |
|                       [Australia](/australia) |              102 |                       109 |                       4 |                          7 |                                        7% |                                   103 |                                    125 |
|                                 [Cuba](/cuba) |               83 |                        98 |                       9 |                         15 |                                       18% |                                    90 |                                    110 |
