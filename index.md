We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by half.

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

For regular updates and insights, follow us on Twitter:<br>
<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

* **August 31:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 7 (3am ET):
<p align="center">
  Current Total: <b>189,205</b> deaths | Projected Total: <b>219,000 deaths by Nov 1, 2020</b> (Range: 207-237k)<br>
  Currently Infected: <b>1.1%</b> (1 in 90) | Total Infected: <b>15.1%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 8, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        96% |         99% |        99% |
|              225,000 |         <1% |        <1% |          2% |        16% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |

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

States are ordered by descending projected deaths (by November 1).

|                                    |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          189,205 |                   219,034 |                     660 |                     29,829 |                       90 |                                       16% |                               207,500 |                                236,183 |
|                 [New York](/us-ny) |           33,002 |                    33,374 |                   1,716 |                        372 |                       19 |                                        1% |                                33,014 |                                 35,529 |
|               [California](/us-ca) |           13,758 |                    18,041 |                     457 |                      4,283 |                      108 |                                       31% |                                15,667 |                                 21,968 |
|                    [Texas](/us-tx) |           13,697 |                    17,900 |                     617 |                      4,203 |                      145 |                                       31% |                                15,995 |                                 20,491 |
|               [New Jersey](/us-nj) |           15,991 |                    16,162 |                   1,820 |                        171 |                       19 |                                        1% |                                16,003 |                                 16,750 |
|                  [Florida](/us-fl) |           11,871 |                    14,407 |                     671 |                      2,536 |                      118 |                                       21% |                                13,032 |                                 16,186 |
|            [Massachusetts](/us-ma) |            9,133 |                     9,532 |                   1,372 |                        399 |                       57 |                                        4% |                                 9,159 |                                 10,470 |
|                 [Illinois](/us-il) |            8,398 |                     9,310 |                     735 |                        912 |                       72 |                                       11% |                                 8,497 |                                 10,564 |
|             [Pennsylvania](/us-pa) |            7,771 |                     8,387 |                     655 |                        616 |                       48 |                                        8% |                                 7,799 |                                  9,645 |
|                  [Georgia](/us-ga) |            6,044 |                     8,076 |                     761 |                      2,032 |                      191 |                                       34% |                                 7,021 |                                  9,745 |
|                 [Michigan](/us-mi) |            6,810 |                     7,238 |                     725 |                        428 |                       43 |                                        6% |                                 6,845 |                                  7,990 |
|                  [Arizona](/us-az) |            5,219 |                     5,935 |                     815 |                        716 |                       98 |                                       14% |                                 5,496 |                                  6,588 |
|                [Louisiana](/us-la) |            5,105 |                     5,825 |                   1,253 |                        720 |                      155 |                                       14% |                                 5,392 |                                  6,520 |
|                     [Ohio](/us-oh) |            4,276 |                     4,987 |                     427 |                        711 |                       61 |                                       17% |                                 4,447 |                                  5,865 |
|              [Connecticut](/us-ct) |            4,468 |                     4,542 |                   1,274 |                         74 |                       21 |                                        2% |                                 4,477 |                                  4,771 |
|                 [Maryland](/us-md) |            3,804 |                     4,148 |                     686 |                        344 |                       57 |                                        9% |                                 3,834 |                                  4,807 |
|           [North Carolina](/us-nc) |            2,897 |                     3,976 |                     379 |                      1,079 |                      103 |                                       37% |                                 3,393 |                                  4,950 |
|                  [Indiana](/us-in) |            3,368 |                     3,793 |                     563 |                        425 |                       63 |                                       13% |                                 3,392 |                                  4,659 |
|           [South Carolina](/us-sc) |            2,907 |                     3,745 |                     727 |                        838 |                      163 |                                       29% |                                 3,333 |                                  4,379 |
|                 [Virginia](/us-va) |            2,684 |                     3,320 |                     389 |                        636 |                       75 |                                       24% |                                 2,754 |                                  4,237 |
|              [Mississippi](/us-ms) |            2,585 |                     3,182 |                   1,069 |                        597 |                      201 |                                       23% |                                 2,844 |                                  3,669 |
|                  [Alabama](/us-al) |            2,276 |                     2,860 |                     583 |                        584 |                      119 |                                       26% |                                 2,539 |                                  3,361 |
|                [Tennessee](/us-tn) |            1,869 |                     2,679 |                     392 |                        810 |                      119 |                                       43% |                                 2,283 |                                  3,309 |
|                 [Missouri](/us-mo) |            1,687 |                     2,339 |                     381 |                        652 |                      106 |                                       39% |                                 1,968 |                                  2,947 |
|               [Washington](/us-wa) |            1,953 |                     2,304 |                     303 |                        351 |                       46 |                                       18% |                                 2,030 |                                  2,773 |
|                [Minnesota](/us-mn) |            1,912 |                     2,264 |                     401 |                        352 |                       62 |                                       18% |                                 1,968 |                                  2,764 |
|                 [Colorado](/us-co) |            1,973 |                     2,140 |                     372 |                        167 |                       29 |                                        8% |                                 1,984 |                                  2,609 |
|                   [Nevada](/us-nv) |            1,393 |                     1,852 |                     601 |                        459 |                      149 |                                       33% |                                 1,629 |                                  2,170 |
|                     [Iowa](/us-ia) |            1,170 |                     1,681 |                     533 |                        511 |                      162 |                                       44% |                                 1,340 |                                  2,368 |
|                [Wisconsin](/us-wi) |            1,168 |                     1,529 |                     263 |                        361 |                       62 |                                       31% |                                 1,310 |                                  1,898 |
|                 [Arkansas](/us-ar) |              908 |                     1,421 |                     471 |                        513 |                      170 |                                       57% |                                 1,168 |                                  1,791 |
|                 [Kentucky](/us-ky) |              996 |                     1,388 |                     311 |                        392 |                       88 |                                       39% |                                 1,153 |                                  1,755 |
|                 [Oklahoma](/us-ok) |              853 |                     1,248 |                     315 |                        395 |                      100 |                                       46% |                                 1,032 |                                  1,610 |
|             [Rhode Island](/us-ri) |            1,055 |                     1,121 |                   1,058 |                         66 |                       62 |                                        6% |                                 1,063 |                                  1,263 |
|               [New Mexico](/us-nm) |              807 |                       958 |                     457 |                        151 |                       72 |                                       19% |                                   861 |                                  1,111 |
|              [Puerto Rico](/us-pr) |              477 |                       797 |                     250 |                        320 |                      100 |                                       67% |                                   628 |                                  1,066 |
|                   [Kansas](/us-ks) |              483 |                       670 |                     230 |                        187 |                       64 |                                       39% |                                   559 |                                    862 |
|                 [Delaware](/us-de) |              609 |                       650 |                     667 |                         41 |                       42 |                                        7% |                                   613 |                                    729 |
|                   [Oregon](/us-or) |              482 |                       647 |                     153 |                        165 |                       39 |                                       34% |                                   551 |                                    807 |
|     [District of Columbia](/us-dc) |              611 |                       637 |                     902 |                         26 |                       36 |                                        4% |                                   615 |                                    687 |
|                    [Idaho](/us-id) |              385 |                       579 |                     324 |                        194 |                      109 |                                       50% |                                   481 |                                    726 |
|                     [Utah](/us-ut) |              423 |                       568 |                     177 |                        145 |                       45 |                                       34% |                                   485 |                                    700 |
|                 [Nebraska](/us-ne) |              404 |                       513 |                     265 |                        109 |                       56 |                                       27% |                                   432 |                                    647 |
|            [West Virginia](/us-wv) |              248 |                       459 |                     256 |                        211 |                      117 |                                       85% |                                   347 |                                    645 |
|            [New Hampshire](/us-nh) |              433 |                       457 |                     336 |                         24 |                       18 |                                        6% |                                   435 |                                    517 |
|             [South Dakota](/us-sd) |              173 |                       254 |                     287 |                         81 |                       91 |                                       47% |                                   182 |                                    426 |
|             [North Dakota](/us-nd) |              156 |                       250 |                     328 |                         94 |                      123 |                                       60% |                                   195 |                                    341 |
|                   [Hawaii](/us-hi) |               86 |                       237 |                     167 |                        151 |                      107 |                                      176% |                                   155 |                                    374 |
|                  [Montana](/us-mt) |              118 |                       208 |                     195 |                         90 |                       85 |                                       77% |                                   158 |                                    290 |
|                    [Maine](/us-me) |              134 |                       150 |                     111 |                         16 |                       12 |                                       12% |                                   137 |                                    172 |
|                   [Alaska](/us-ak) |               42 |                        76 |                     105 |                         34 |                       47 |                                       82% |                                    58 |                                    111 |
|                  [Wyoming](/us-wy) |               42 |                        69 |                     120 |                         27 |                       47 |                                       65% |                                    55 |                                     97 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     105 |                          8 |                       12 |                                       13% |                                    59 |                                     78 |
|                     [Guam](/us-gu) |               14 |                        40 |                     243 |                         26 |                      159 |                                      188% |                                    26 |                                     64 |
|           [Virgin Islands](/us-vi) |               17 |                        38 |                     359 |                         21 |                      197 |                                      121% |                                    27 |                                     55 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      51 |                          1 |                       14 |                                       40% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,658 |                   203,903 |                     344 |                     13,245 |                       22 |                                        7% |                               193,614 |                                236,814 |
| [United Kingdom](/united-kingdom) |           41,643 |                    42,213 |                     625 |                        570 |                        8 |                                        1% |                                41,656 |                                 45,333 |
|                   [Italy](/italy) |           35,553 |                    36,143 |                     599 |                        590 |                       10 |                                        2% |                                35,567 |                                 38,775 |
|                 [France](/france) |           30,732 |                    32,029 |                     478 |                      1,297 |                       19 |                                        4% |                                30,760 |                                 38,896 |
|                   [Spain](/spain) |           29,516 |                    31,759 |                     677 |                      2,243 |                       48 |                                        8% |                                29,544 |                                 40,351 |
|               [Belgium](/belgium) |            9,909 |                    10,067 |                     879 |                        158 |                       14 |                                        2% |                                 9,926 |                                 10,649 |
|               [Germany](/germany) |            9,331 |                     9,681 |                     117 |                        350 |                        4 |                                        4% |                                 9,346 |                                 10,908 |
|       [Netherlands](/netherlands) |            6,278 |                     6,455 |                     374 |                        177 |                       10 |                                        3% |                                 6,291 |                                  7,088 |
|               [Romania](/romania) |            3,926 |                     5,982 |                     308 |                      2,056 |                      106 |                                       52% |                                 4,773 |                                  7,935 |
|                 [Sweden](/sweden) |            5,837 |                     5,879 |                     575 |                         42 |                        4 |                                        1% |                                 5,841 |                                  6,022 |
|               [Ukraine](/ukraine) |            2,930 |                     5,696 |                     129 |                      2,766 |                       63 |                                       94% |                                 3,980 |                                  8,613 |
|                 [Poland](/poland) |            2,124 |                     2,787 |                      73 |                        663 |                       17 |                                       31% |                                 2,316 |                                  3,668 |
|       [Switzerland](/switzerland) |            2,014 |                     2,090 |                     243 |                         76 |                        9 |                                        4% |                                 2,026 |                                  2,268 |
|             [Portugal](/portugal) |            1,843 |                     1,991 |                     194 |                        148 |                       14 |                                        8% |                                 1,849 |                                  2,364 |
|               [Ireland](/ireland) |            1,777 |                     1,816 |                     370 |                         39 |                        8 |                                        2% |                                 1,784 |                                  1,934 |
|               [Moldova](/moldova) |            1,074 |                     1,513 |                     374 |                        439 |                      109 |                                       41% |                                 1,245 |                                  1,958 |
|             [Bulgaria](/bulgaria) |              677 |                     1,110 |                     159 |                        433 |                       62 |                                       64% |                                   850 |                                  1,551 |
|               [Belarus](/belarus) |              716 |                       996 |                     105 |                        280 |                       30 |                                       39% |                                   803 |                                  1,387 |
|                 [Serbia](/serbia) |              725 |                       877 |                     126 |                        152 |                       22 |                                       21% |                                   781 |                                  1,033 |
|               [Austria](/austria) |              746 |                       801 |                      90 |                         55 |                        6 |                                        7% |                                   755 |                                    951 |
|               [Hungary](/hungary) |              625 |                       694 |                      71 |                         69 |                        7 |                                       11% |                                   633 |                                    853 |
|               [Denmark](/denmark) |              628 |                       666 |                     115 |                         38 |                        6 |                                        6% |                                   636 |                                    769 |
|               [Czechia](/czechia) |              437 |                       548 |                      51 |                        111 |                       10 |                                       25% |                                   462 |                                    720 |
|                 [Greece](/greece) |              289 |                       500 |                      47 |                        211 |                       20 |                                       73% |                                   373 |                                    748 |
|               [Finland](/finland) |              336 |                       354 |                      64 |                         18 |                        3 |                                        5% |                                   339 |                                    405 |
|               [Croatia](/croatia) |              201 |                       326 |                      80 |                        125 |                       31 |                                       62% |                                   248 |                                    473 |
|                 [Norway](/norway) |              264 |                       284 |                      53 |                         20 |                        4 |                                        8% |                                   268 |                                    334 |
|             [Slovenia](/slovenia) |              135 |                       155 |                      74 |                         20 |                       10 |                                       15% |                                   138 |                                    192 |
|         [Luxembourg](/luxembourg) |              124 |                       143 |                     232 |                         19 |                       30 |                                       15% |                                   130 |                                    170 |
|           [Lithuania](/lithuania) |               86 |                        97 |                      35 |                         11 |                        4 |                                       13% |                                    88 |                                    117 |
|               [Estonia](/estonia) |               64 |                        70 |                      53 |                          6 |                        4 |                                        9% |                                    67 |                                     77 |
|             [Slovakia](/slovakia) |               37 |                        62 |                      11 |                         25 |                        5 |                                       67% |                                    44 |                                    100 |
|                 [Latvia](/latvia) |               35 |                        43 |                      23 |                          8 |                        4 |                                       24% |                                    37 |                                     56 |
|                   [Malta](/malta) |               14 |                        35 |                      70 |                         21 |                       42 |                                      147% |                                    22 |                                     58 |
|                 [Cyprus](/cyprus) |               22 |                        31 |                      36 |                          9 |                       11 |                                       42% |                                    26 |                                     43 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        5 |                                       18% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          481,284 |                   657,167 |                     127 |                    175,883 |                       34 |                                       37% |                               550,082 |                                835,200 |
|                             [Brazil](/brazil) |          126,960 |                   162,236 |                     769 |                     35,276 |                      167 |                                       28% |                               140,216 |                                194,291 |
|                               [India](/india) |           72,775 |                   128,430 |                      94 |                     55,655 |                       41 |                                       76% |                                95,682 |                                185,542 |
|                             [Mexico](/mexico) |           67,781 |                    89,868 |                     704 |                     22,087 |                      173 |                                       33% |                                80,982 |                                103,203 |
|                                 [Peru](/peru) |           29,838 |                    34,556 |                   1,063 |                      4,718 |                      145 |                                       16% |                                31,128 |                                 40,364 |
|                         [Colombia](/colombia) |           21,412 |                    30,559 |                     607 |                      9,147 |                      182 |                                       43% |                                25,298 |                                 38,595 |
|                                 [Iran](/iran) |           22,410 |                    27,136 |                     327 |                      4,726 |                       57 |                                       21% |                                23,782 |                                 32,718 |
|                             [Russia](/russia) |           17,818 |                    22,190 |                     152 |                      4,372 |                       30 |                                       25% |                                18,566 |                                 28,518 |
|                 [South Africa](/south-africa) |           15,004 |                    19,027 |                     325 |                      4,023 |                       69 |                                       27% |                                15,654 |                                 21,523 |
|                       [Argentina](/argentina) |           10,129 |                    18,965 |                     424 |                      8,836 |                      197 |                                       87% |                                13,840 |                                 26,006 |
|                               [Chile](/chile) |           11,652 |                    14,584 |                     770 |                      2,932 |                      155 |                                       25% |                                12,067 |                                 21,292 |
|                       [Indonesia](/indonesia) |            8,130 |                    12,818 |                      47 |                      4,688 |                       17 |                                       58% |                                10,028 |                                 19,171 |
|                           [Ecuador](/ecuador) |           10,576 |                    11,527 |                     663 |                        951 |                       55 |                                        9% |                                10,652 |                                 13,658 |
|                           [Bolivia](/bolivia) |            7,054 |                     9,558 |                     830 |                      2,504 |                      217 |                                       35% |                                 8,094 |                                 11,692 |
|                             [Canada](/canada) |            9,196 |                     9,526 |                     255 |                        330 |                        9 |                                        4% |                                 9,222 |                                 10,505 |
|                             [Turkey](/turkey) |            6,730 |                     8,315 |                     100 |                      1,585 |                       19 |                                       24% |                                 6,855 |                                 11,412 |
|                   [Philippines](/philippines) |            3,890 |                     6,894 |                      64 |                      3,004 |                       28 |                                       77% |                                 4,896 |                                  9,948 |
|                         [Pakistan](/pakistan) |            6,350 |                     6,682 |                      31 |                        332 |                        2 |                                        5% |                                 6,370 |                                  7,488 |
|                     [Bangladesh](/bangladesh) |            4,516 |                     6,207 |                      38 |                      1,691 |                       10 |                                       37% |                                 5,053 |                                  8,299 |
|                               [Egypt](/egypt) |            5,541 |                     6,133 |                      61 |                        592 |                        6 |                                       11% |                                 5,576 |                                  8,265 |
|                 [Saudi Arabia](/saudi-arabia) |            4,107 |                     5,298 |                     155 |                      1,191 |                       35 |                                       29% |                                 4,478 |                                  6,679 |
|                               [China](/china) |            4,732 |                     4,804 |                       3 |                         72 |                        0 |                                        2% |                                 4,732 |                                  5,373 |
|                           [Morocco](/morocco) |            1,394 |                     3,451 |                      95 |                      2,057 |                       56 |                                      148% |                                 2,087 |                                  5,425 |
|                         [Honduras](/honduras) |            2,023 |                     2,845 |                     292 |                        822 |                       84 |                                       41% |                                 2,304 |                                  3,745 |
|     [Dominican Republic](/dominican-republic) |            1,864 |                     2,789 |                     260 |                        925 |                       86 |                                       50% |                                 2,176 |                                  3,760 |
|                             [Panama](/panama) |            2,099 |                     2,539 |                     598 |                        440 |                      104 |                                       21% |                                 2,281 |                                  3,064 |
|                           [Algeria](/algeria) |            1,562 |                     2,101 |                      49 |                        539 |                       13 |                                       34% |                                 1,654 |                                  3,047 |
|                               [Japan](/japan) |            1,377 |                     2,046 |                      16 |                        669 |                        5 |                                       49% |                                 1,545 |                                  3,249 |
|                             [Israel](/israel) |            1,026 |                     1,762 |                     207 |                        736 |                       86 |                                       72% |                                 1,255 |                                  2,692 |
|                           [Nigeria](/nigeria) |            1,061 |                     1,261 |                       6 |                        200 |                        1 |                                       19% |                                 1,112 |                                  1,547 |
|                       [Australia](/australia) |              770 |                     1,209 |                      48 |                        439 |                       17 |                                       57% |                                   947 |                                  1,551 |
|                             [Kuwait](/kuwait) |              546 |                       660 |                     157 |                        114 |                       27 |                                       21% |                                   564 |                                    890 |
| [United Arab Emirates](/united-arab-emirates) |              390 |                       462 |                      47 |                         72 |                        7 |                                       19% |                                   395 |                                    648 |
|                   [South Korea](/south-korea) |              341 |                       445 |                       9 |                        104 |                        2 |                                       30% |                                   346 |                                    672 |
|                                 [Cuba](/cuba) |              102 |                       146 |                      13 |                         44 |                        4 |                                       43% |                                   114 |                                    218 |
|                         [Malaysia](/malaysia) |              128 |                       139 |                       4 |                         11 |                        0 |                                        8% |                                   131 |                                    150 |
