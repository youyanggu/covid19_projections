We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#current-us-projections)
* [US and Global Dashboard](#covid-19-dashboard)
* [View US state-by-state projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: July 6 (3am ET):
<p align="center">
  Current Total: <b>129,944</b> deaths | Projected Total: <b>185,800 deaths by Oct 1, 2020</b> (Range: 156q-235k)<br>
  Currently Infected: <b>0.9%</b> | Total Infected: <b>6.2%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 6, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 6, 2020 |
|              140,000 |        Jul 24, 2020 |
|              150,000 |         Aug 9, 2020 |
|              175,000 |        Sep 13, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        10% |         65% |        96% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        20% |         39% |        53% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          9% |        18% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         6% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 63 countries (including all 27 European Union countries).

[Back to Top](#top)

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

[Back to Top](#top)

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

[Back to Top](#top)

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

[Back to Top](#top)

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

States are ordered by descending projected deaths (by October 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          129,944 |                   185,810 |                     560 |                     55,866 |                                       43% |                               156,513 |                                234,238 |
|                 [New York](/us-ny) |           32,206 |                    33,411 |                   1,717 |                      1,205 |                                        4% |                                32,255 |                                 37,937 |
|               [New Jersey](/us-nj) |           15,211 |                    16,377 |                   1,844 |                      1,166 |                                        8% |                                15,349 |                                 17,869 |
|               [California](/us-ca) |            6,373 |                    14,078 |                     356 |                      7,705 |                                      121% |                                 8,718 |                                 25,286 |
|                  [Florida](/us-fl) |            3,731 |                     9,735 |                     453 |                      6,004 |                                      161% |                                 5,063 |                                 17,245 |
|            [Massachusetts](/us-ma) |            8,183 |                     8,930 |                   1,285 |                        747 |                                        9% |                                 8,350 |                                 10,342 |
|             [Pennsylvania](/us-pa) |            6,753 |                     8,698 |                     679 |                      1,945 |                                       29% |                                 6,980 |                                 12,995 |
|                 [Illinois](/us-il) |            7,020 |                     8,521 |                     672 |                      1,501 |                                       21% |                                 7,421 |                                  9,773 |
|                    [Texas](/us-tx) |            2,628 |                     7,529 |                     260 |                      4,901 |                                      186% |                                 3,814 |                                 15,314 |
|                 [Michigan](/us-mi) |            6,218 |                     7,338 |                     735 |                      1,120 |                                       18% |                                 6,291 |                                 10,432 |
|                  [Georgia](/us-ga) |            2,860 |                     6,334 |                     597 |                      3,474 |                                      121% |                                 3,644 |                                 10,588 |
|                  [Arizona](/us-az) |            1,825 |                     5,638 |                     775 |                      3,813 |                                      209% |                                 3,629 |                                  8,592 |
|                [Louisiana](/us-la) |            3,288 |                     4,782 |                   1,029 |                      1,494 |                                       45% |                                 3,483 |                                  6,682 |
|                     [Ohio](/us-oh) |            2,911 |                     4,714 |                     403 |                      1,803 |                                       62% |                                 3,185 |                                  8,519 |
|              [Connecticut](/us-ct) |            4,335 |                     4,575 |                   1,283 |                        240 |                                        6% |                                 4,375 |                                  4,914 |
|                 [Maryland](/us-md) |            3,243 |                     4,026 |                     666 |                        783 |                                       24% |                                 3,433 |                                  5,042 |
|                  [Indiana](/us-in) |            2,693 |                     3,779 |                     561 |                      1,086 |                                       40% |                                 2,808 |                                  6,713 |
|                 [Virginia](/us-va) |            1,853 |                     2,985 |                     350 |                      1,132 |                                       61% |                                 1,972 |                                  5,417 |
|                  [Alabama](/us-al) |            1,007 |                     2,800 |                     571 |                      1,793 |                                      178% |                                 1,428 |                                  4,703 |
|           [North Carolina](/us-nc) |            1,423 |                     2,587 |                     247 |                      1,164 |                                       82% |                                 1,650 |                                  5,945 |
|           [South Carolina](/us-sc) |              820 |                     2,508 |                     487 |                      1,688 |                                      206% |                                 1,358 |                                  4,444 |
|                [Minnesota](/us-mn) |            1,508 |                     2,459 |                     436 |                        951 |                                       63% |                                 1,658 |                                  4,288 |
|                 [Colorado](/us-co) |            1,701 |                     2,369 |                     411 |                        668 |                                       39% |                                 1,765 |                                  4,338 |
|              [Mississippi](/us-ms) |            1,111 |                     2,240 |                     753 |                      1,129 |                                      102% |                                 1,352 |                                  3,706 |
|               [Washington](/us-wa) |            1,359 |                     2,073 |                     272 |                        714 |                                       53% |                                 1,507 |                                  3,453 |
|                [Tennessee](/us-tn) |              645 |                     2,051 |                     300 |                      1,406 |                                      218% |                                 1,006 |                                  3,740 |
|                 [Missouri](/us-mo) |            1,051 |                     1,639 |                     267 |                        588 |                                       56% |                                 1,138 |                                  3,189 |
|                [Wisconsin](/us-wi) |              796 |                     1,431 |                     246 |                        635 |                                       80% |                                   919 |                                  2,869 |
|                   [Nevada](/us-nv) |              534 |                     1,293 |                     420 |                        759 |                                      142% |                                   749 |                                  2,206 |
|             [Rhode Island](/us-ri) |              960 |                     1,193 |                   1,126 |                        233 |                                       24% |                                 1,024 |                                  1,440 |
|                 [Kentucky](/us-ky) |              585 |                     1,073 |                     240 |                        488 |                                       83% |                                   656 |                                  2,174 |
|                 [Arkansas](/us-ar) |              287 |                       948 |                     314 |                        661 |                                      230% |                                   421 |                                  1,880 |
|                     [Iowa](/us-ia) |              721 |                       924 |                     293 |                        203 |                                       28% |                                   747 |                                  1,431 |
|               [New Mexico](/us-nm) |              513 |                       866 |                     413 |                        353 |                                       69% |                                   572 |                                  1,610 |
|                 [Oklahoma](/us-ok) |              398 |                       688 |                     174 |                        290 |                                       73% |                                   429 |                                  1,643 |
|     [District of Columbia](/us-dc) |              559 |                       674 |                     955 |                        115 |                                       21% |                                   580 |                                    909 |
|                 [Delaware](/us-de) |              512 |                       661 |                     679 |                        149 |                                       29% |                                   532 |                                    994 |
|            [New Hampshire](/us-nh) |              381 |                       640 |                     471 |                        259 |                                       68% |                                   420 |                                  1,159 |
|                   [Oregon](/us-or) |              215 |                       540 |                     128 |                        325 |                                      151% |                                   263 |                                  1,122 |
|                     [Utah](/us-ut) |              184 |                       511 |                     159 |                        327 |                                      178% |                                   234 |                                  1,346 |
|                 [Nebraska](/us-ne) |              284 |                       509 |                     263 |                        225 |                                       79% |                                   343 |                                    790 |
|                   [Kansas](/us-ks) |              284 |                       434 |                     149 |                        150 |                                       53% |                                   301 |                                    907 |
|              [Puerto Rico](/us-pr) |              155 |                       214 |                      67 |                         59 |                                       38% |                                   162 |                                    395 |
|             [South Dakota](/us-sd) |               97 |                       202 |                     228 |                        105 |                                      108% |                                   118 |                                    368 |
|                    [Idaho](/us-id) |               93 |                       194 |                     109 |                        101 |                                      109% |                                   117 |                                    331 |
|                    [Maine](/us-me) |              109 |                       156 |                     116 |                         47 |                                       43% |                                   117 |                                    274 |
|            [West Virginia](/us-wv) |               94 |                       120 |                      67 |                         26 |                                       28% |                                    99 |                                    173 |
|             [North Dakota](/us-nd) |               80 |                       113 |                     148 |                         33 |                                       41% |                                    90 |                                    166 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    58 |                                    116 |
|                  [Montana](/us-mt) |               23 |                        50 |                      47 |                         27 |                                      117% |                                    25 |                                    106 |
|                   [Alaska](/us-ak) |               16 |                        49 |                      67 |                         33 |                                      206% |                                    17 |                                    102 |
|                  [Wyoming](/us-wy) |               20 |                        30 |                      52 |                         10 |                                       50% |                                    23 |                                     43 |
|                   [Hawaii](/us-hi) |               19 |                        26 |                      18 |                          7 |                                       37% |                                    20 |                                     39 |
|           [Virgin Islands](/us-vi) |                6 |                        11 |                     105 |                          5 |                                       83% |                                     6 |                                     18 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      7 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          182,704 |                   201,975 |                     341 |                     19,271 |                                       11% |                               186,954 |                                230,069 |
| [United Kingdom](/united-kingdom) |           44,283 |                    48,625 |                     720 |                      4,342 |                                       10% |                                45,004 |                                 52,140 |
|                   [Italy](/italy) |           34,854 |                    36,449 |                     604 |                      1,595 |                                        5% |                                35,082 |                                 40,149 |
|                 [France](/france) |           29,896 |                    30,864 |                     461 |                        968 |                                        3% |                                29,925 |                                 35,374 |
|                   [Spain](/spain) |           28,385 |                    29,201 |                     622 |                        816 |                                        3% |                                28,431 |                                 31,146 |
|               [Germany](/germany) |            9,020 |                    10,393 |                     125 |                      1,373 |                                       15% |                                 9,089 |                                 13,428 |
|               [Belgium](/belgium) |            9,771 |                    10,031 |                     876 |                        260 |                                        3% |                                 9,793 |                                 10,746 |
|       [Netherlands](/netherlands) |            6,132 |                     6,451 |                     373 |                        319 |                                        5% |                                 6,167 |                                  7,069 |
|                 [Sweden](/sweden) |            5,420 |                     6,314 |                     617 |                        894 |                                       16% |                                 5,789 |                                  7,523 |
|               [Romania](/romania) |            1,731 |                     3,922 |                     202 |                      2,191 |                                      127% |                                 2,499 |                                  5,006 |
|               [Ukraine](/ukraine) |            1,243 |                     3,082 |                      70 |                      1,839 |                                      148% |                                 1,920 |                                  4,849 |
|                 [Poland](/poland) |            1,512 |                     2,986 |                      79 |                      1,474 |                                       97% |                                 1,885 |                                  4,373 |
|       [Switzerland](/switzerland) |            1,965 |                     2,051 |                     239 |                         86 |                                        4% |                                 1,976 |                                  2,377 |
|             [Portugal](/portugal) |            1,605 |                     2,003 |                     195 |                        398 |                                       25% |                                 1,671 |                                  2,622 |
|               [Ireland](/ireland) |            1,741 |                     1,824 |                     372 |                         83 |                                        5% |                                 1,748 |                                  2,199 |
|               [Moldova](/moldova) |              580 |                     1,412 |                     349 |                        832 |                                      143% |                                   983 |                                  2,041 |
|               [Belarus](/belarus) |              418 |                       873 |                      92 |                        455 |                                      109% |                                   559 |                                  1,629 |
|               [Austria](/austria) |              705 |                       803 |                      91 |                         98 |                                       14% |                                   719 |                                    954 |
|               [Hungary](/hungary) |              589 |                       769 |                      79 |                        180 |                                       31% |                                   612 |                                  1,098 |
|               [Denmark](/denmark) |              606 |                       669 |                     115 |                         63 |                                       10% |                                   620 |                                    821 |
|             [Bulgaria](/bulgaria) |              241 |                       648 |                      93 |                        407 |                                      169% |                                   361 |                                    994 |
|                 [Serbia](/serbia) |              306 |                       531 |                      76 |                        225 |                                       74% |                                   352 |                                    818 |
|               [Czechia](/czechia) |              351 |                       451 |                      42 |                        100 |                                       28% |                                   359 |                                    591 |
|               [Finland](/finland) |              329 |                       367 |                      67 |                         38 |                                       12% |                                   335 |                                    475 |
|                 [Norway](/norway) |              251 |                       272 |                      51 |                         21 |                                        8% |                                   257 |                                    310 |
|                 [Greece](/greece) |              192 |                       220 |                      21 |                         28 |                                       15% |                                   203 |                                    265 |
|               [Croatia](/croatia) |              113 |                       190 |                      47 |                         77 |                                       68% |                                   126 |                                    260 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   113 |                                    151 |
|         [Luxembourg](/luxembourg) |              110 |                       118 |                     192 |                          8 |                                        7% |                                   112 |                                    136 |
|           [Lithuania](/lithuania) |               79 |                       113 |                      40 |                         34 |                                       43% |                                    88 |                                    162 |
|               [Estonia](/estonia) |               69 |                        87 |                      66 |                         18 |                                       26% |                                    75 |                                    148 |
|                 [Latvia](/latvia) |               30 |                        45 |                      23 |                         15 |                                       50% |                                    32 |                                     77 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    28 |                                     58 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     46 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    10 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          207,823 |                   531,661 |                     102 |                    323,838 |                                      156% |                               354,780 |                                813,330 |
|                             [Brazil](/brazil) |           64,265 |                   133,424 |                     632 |                     69,159 |                                      108% |                               104,938 |                                197,127 |
|                               [India](/india) |           19,268 |                    95,888 |                      70 |                     76,620 |                                      398% |                                43,317 |                                192,026 |
|                             [Mexico](/mexico) |           30,366 |                    79,504 |                     623 |                     49,138 |                                      162% |                                59,935 |                                 92,875 |
|                                 [Peru](/peru) |           10,412 |                    22,416 |                     690 |                     12,004 |                                      115% |                                16,070 |                                 31,565 |
|                         [Colombia](/colombia) |            4,001 |                    21,555 |                     428 |                     17,554 |                                      439% |                                13,162 |                                 28,621 |
|                                 [Iran](/iran) |           11,408 |                    20,556 |                     248 |                      9,148 |                                       80% |                                16,928 |                                 26,237 |
|                             [Russia](/russia) |           10,011 |                    19,450 |                     133 |                      9,439 |                                       94% |                                13,100 |                                 31,168 |
|                 [South Africa](/south-africa) |            3,026 |                    14,293 |                     244 |                     11,267 |                                      372% |                                 7,843 |                                 20,244 |
|                               [Egypt](/egypt) |            3,280 |                    13,270 |                     132 |                      9,990 |                                      305% |                                 7,784 |                                 20,774 |
|                               [Chile](/chile) |            6,192 |                    12,955 |                     684 |                      6,763 |                                      109% |                                 8,108 |                                 18,795 |
|                         [Pakistan](/pakistan) |            4,619 |                    12,228 |                      56 |                      7,609 |                                      165% |                                 7,753 |                                 19,726 |
|                             [Canada](/canada) |            8,732 |                    10,158 |                     272 |                      1,426 |                                       16% |                                 8,961 |                                 12,964 |
|                       [Indonesia](/indonesia) |            3,089 |                     9,278 |                      34 |                      6,189 |                                      200% |                                 5,143 |                                 15,204 |
|                     [Bangladesh](/bangladesh) |            1,997 |                     7,972 |                      49 |                      5,975 |                                      299% |                                 4,246 |                                 13,670 |
|                             [Turkey](/turkey) |            5,206 |                     7,734 |                      93 |                      2,528 |                                       49% |                                 5,509 |                                 12,582 |
|                       [Argentina](/argentina) |            1,481 |                     7,668 |                     171 |                      6,187 |                                      418% |                                 3,691 |                                 12,730 |
|                           [Bolivia](/bolivia) |            1,378 |                     7,168 |                     623 |                      5,790 |                                      420% |                                 3,559 |                                 10,749 |
|                           [Ecuador](/ecuador) |            4,769 |                     6,734 |                     388 |                      1,965 |                                       41% |                                 5,051 |                                 11,100 |
|                 [Saudi Arabia](/saudi-arabia) |            1,858 |                     5,296 |                     155 |                      3,438 |                                      185% |                                 3,317 |                                  7,199 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,677 |
|                         [Honduras](/honduras) |              629 |                     3,393 |                     348 |                      2,764 |                                      439% |                                 2,274 |                                  5,082 |
|     [Dominican Republic](/dominican-republic) |              786 |                     2,927 |                     273 |                      2,141 |                                      272% |                                 1,087 |                                  5,604 |
|                             [Panama](/panama) |              720 |                     2,714 |                     639 |                      1,994 |                                      277% |                                 1,821 |                                  3,725 |
|                   [Philippines](/philippines) |            1,290 |                     2,672 |                      25 |                      1,382 |                                      107% |                                 1,436 |                                  4,974 |
|                           [Algeria](/algeria) |              946 |                     2,123 |                      49 |                      1,177 |                                      124% |                                 1,290 |                                  4,205 |
|                           [Nigeria](/nigeria) |              634 |                     1,835 |                       9 |                      1,201 |                                      189% |                                   891 |                                  3,779 |
|                               [Japan](/japan) |              977 |                     1,209 |                      10 |                        232 |                                       24% |                                   981 |                                  1,749 |
|                             [Kuwait](/kuwait) |              365 |                       588 |                     140 |                        223 |                                       61% |                                   408 |                                    987 |
|                             [Israel](/israel) |              330 |                       454 |                      53 |                        124 |                                       38% |                                   344 |                                    714 |
| [United Arab Emirates](/united-arab-emirates) |              321 |                       436 |                      45 |                        115 |                                       36% |                                   340 |                                    748 |
|                   [South Korea](/south-korea) |              283 |                       355 |                       7 |                         72 |                                       25% |                                   284 |                                    564 |
|                           [Morocco](/morocco) |              232 |                       276 |                       8 |                         44 |                                       19% |                                   239 |                                    417 |
|                         [Malaysia](/malaysia) |              121 |                       267 |                       8 |                        146 |                                      121% |                                   135 |                                    458 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    154 |
|                                 [Cuba](/cuba) |               86 |                       102 |                       9 |                         16 |                                       19% |                                    90 |                                    137 |
