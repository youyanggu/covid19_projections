We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >97% of all global COVID-19 deaths.

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
* **July 13:** View our [updated historical performance](/about/#historical-performance) (commentary [on Twitter](https://twitter.com/youyanggu/status/1283102532236181504)).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 19 (2am ET):
<p align="center">
  Current Total: <b>140,116</b> deaths | Projected Total: <b>214,200 deaths by Nov 1, 2020</b> (Range: 180-276k)<br>
  Currently Infected: <b>1.5%</b> | Total Infected: <b>8.4%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 19, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 18, 2020 |
|              150,000 |        Jul 31, 2020 |
|              175,000 |         Sep 2, 2020 |
|              200,000 |        Oct 24, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        68% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          7% |        49% |         76% |        93% |         99% |        99% |
|              200,000 |        <1% |         <1% |         6% |         17% |        32% |         44% |        56% |
|              225,000 |        <1% |         <1% |        <1% |          4% |         9% |         14% |        21% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         2% |          5% |         8% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          1% |         3% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          140,116 |                   214,217 |                     646 |                     74,101 |                                       53% |                               180,437 |                                275,384 |
|                 [New York](/us-ny) |           32,478 |                    33,744 |                   1,735 |                      1,266 |                                        4% |                                32,522 |                                 38,344 |
|               [New Jersey](/us-nj) |           15,699 |                    16,882 |                   1,901 |                      1,183 |                                        8% |                                15,751 |                                 18,812 |
|               [California](/us-ca) |            7,702 |                    16,272 |                     412 |                      8,570 |                                      111% |                                 9,982 |                                 25,141 |
|                  [Florida](/us-fl) |            4,895 |                    14,977 |                     697 |                     10,082 |                                      206% |                                 9,284 |                                 27,845 |
|                    [Texas](/us-tx) |            3,939 |                    13,652 |                     471 |                      9,713 |                                      247% |                                 9,801 |                                 26,647 |
|            [Massachusetts](/us-ma) |            8,419 |                     9,126 |                   1,313 |                        707 |                                        8% |                                 8,532 |                                 10,534 |
|             [Pennsylvania](/us-pa) |            7,015 |                     8,860 |                     692 |                      1,845 |                                       26% |                                 7,187 |                                 12,901 |
|                 [Illinois](/us-il) |            7,483 |                     8,605 |                     679 |                      1,122 |                                       15% |                                 7,652 |                                  9,926 |
|                 [Michigan](/us-mi) |            6,364 |                     7,799 |                     781 |                      1,435 |                                       23% |                                 6,460 |                                 11,517 |
|                  [Arizona](/us-az) |            2,730 |                     6,746 |                     927 |                      4,016 |                                      147% |                                 5,204 |                                 10,061 |
|                  [Georgia](/us-ga) |            3,169 |                     6,170 |                     581 |                      3,001 |                                       95% |                                 3,913 |                                 10,207 |
|                [Louisiana](/us-la) |            3,509 |                     5,899 |                   1,269 |                      2,390 |                                       68% |                                 3,928 |                                  8,538 |
|                     [Ohio](/us-oh) |            3,132 |                     5,898 |                     505 |                      2,766 |                                       88% |                                 3,385 |                                 14,452 |
|              [Connecticut](/us-ct) |            4,396 |                     4,522 |                   1,268 |                        126 |                                        3% |                                 4,415 |                                  4,685 |
|                 [Maryland](/us-md) |            3,368 |                     4,098 |                     678 |                        730 |                                       22% |                                 3,498 |                                  5,277 |
|                  [Indiana](/us-in) |            2,820 |                     3,990 |                     593 |                      1,170 |                                       41% |                                 2,945 |                                  7,089 |
|                  [Alabama](/us-al) |            1,286 |                     3,976 |                     811 |                      2,690 |                                      209% |                                 2,555 |                                  5,978 |
|                 [Virginia](/us-va) |            2,025 |                     3,474 |                     407 |                      1,449 |                                       72% |                                 2,157 |                                  6,355 |
|           [North Carolina](/us-nc) |            1,648 |                     3,460 |                     330 |                      1,812 |                                      110% |                                 2,237 |                                  6,282 |
|           [South Carolina](/us-sc) |            1,135 |                     3,357 |                     652 |                      2,222 |                                      196% |                                 2,216 |                                  5,194 |
|                [Tennessee](/us-tn) |              838 |                     2,932 |                     429 |                      2,094 |                                      250% |                                 1,845 |                                  5,258 |
|              [Mississippi](/us-ms) |            1,346 |                     2,782 |                     935 |                      1,436 |                                      107% |                                 1,769 |                                  4,749 |
|                [Minnesota](/us-mn) |            1,578 |                     2,643 |                     469 |                      1,065 |                                       67% |                                 1,689 |                                  5,274 |
|                 [Colorado](/us-co) |            1,752 |                     2,545 |                     442 |                        793 |                                       45% |                                 1,854 |                                  4,623 |
|               [Washington](/us-wa) |            1,444 |                     2,242 |                     294 |                        798 |                                       55% |                                 1,526 |                                  4,271 |
|                 [Missouri](/us-mo) |            1,136 |                     2,069 |                     337 |                        933 |                                       82% |                                 1,257 |                                  4,299 |
|                   [Nevada](/us-nv) |              646 |                     1,949 |                     633 |                      1,303 |                                      202% |                                 1,150 |                                  3,062 |
|                 [Kentucky](/us-ky) |              667 |                     1,880 |                     421 |                      1,213 |                                      182% |                                   889 |                                  3,943 |
|                [Wisconsin](/us-wi) |              843 |                     1,693 |                     291 |                        850 |                                      101% |                                   996 |                                  4,114 |
|                     [Iowa](/us-ia) |              789 |                     1,223 |                     388 |                        434 |                                       55% |                                   822 |                                  2,198 |
|             [Rhode Island](/us-ri) |              990 |                     1,122 |                   1,059 |                        132 |                                       13% |                                 1,010 |                                  1,280 |
|               [New Mexico](/us-nm) |              569 |                     1,031 |                     492 |                        462 |                                       81% |                                   633 |                                  1,971 |
|                     [Utah](/us-ut) |              243 |                     1,022 |                     319 |                        779 |                                      321% |                                   494 |                                  2,629 |
|                   [Oregon](/us-or) |              257 |                       987 |                     234 |                        730 |                                      284% |                                   380 |                                  2,518 |
|                 [Arkansas](/us-ar) |              357 |                       955 |                     316 |                        598 |                                      168% |                                   644 |                                  1,559 |
|                 [Oklahoma](/us-ok) |              451 |                       836 |                     211 |                        385 |                                       85% |                                   561 |                                  1,337 |
|     [District of Columbia](/us-dc) |              578 |                       700 |                     992 |                        122 |                                       21% |                                   595 |                                  1,001 |
|                 [Delaware](/us-de) |              523 |                       660 |                     678 |                        137 |                                       26% |                                   539 |                                    954 |
|                   [Kansas](/us-ks) |              308 |                       600 |                     206 |                        292 |                                       95% |                                   342 |                                  1,344 |
|                    [Idaho](/us-id) |              119 |                       471 |                     264 |                        352 |                                      296% |                                   241 |                                    902 |
|                 [Nebraska](/us-ne) |              301 |                       457 |                     236 |                        156 |                                       52% |                                   356 |                                    605 |
|            [New Hampshire](/us-nh) |              396 |                       448 |                     329 |                         52 |                                       13% |                                   401 |                                    507 |
|              [Puerto Rico](/us-pr) |              178 |                       309 |                      97 |                        131 |                                       74% |                                   189 |                                    776 |
|             [South Dakota](/us-sd) |              116 |                       201 |                     227 |                         85 |                                       73% |                                   139 |                                    293 |
|                    [Maine](/us-me) |              117 |                       188 |                     140 |                         71 |                                       61% |                                   127 |                                    368 |
|                  [Montana](/us-mt) |               37 |                       183 |                     171 |                        146 |                                      395% |                                    76 |                                    391 |
|            [West Virginia](/us-wv) |              100 |                       155 |                      86 |                         55 |                                       55% |                                   108 |                                    275 |
|             [North Dakota](/us-nd) |               90 |                       153 |                     201 |                         63 |                                       70% |                                   100 |                                    283 |
|                  [Vermont](/us-vt) |               56 |                        79 |                     127 |                         23 |                                       41% |                                    58 |                                    178 |
|                   [Hawaii](/us-hi) |               24 |                        69 |                      49 |                         45 |                                      188% |                                    27 |                                    184 |
|                  [Wyoming](/us-wy) |               24 |                        52 |                      90 |                         28 |                                      117% |                                    31 |                                    103 |
|                   [Alaska](/us-ak) |               18 |                        41 |                      56 |                         23 |                                      128% |                                    20 |                                     90 |
|           [Virgin Islands](/us-vi) |                6 |                        16 |                     153 |                         10 |                                      167% |                                     6 |                                     48 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     5 |                                     42 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                     10 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          185,745 |                   201,178 |                     339 |                     15,433 |                                        8% |                               189,310 |                                223,520 |
| [United Kingdom](/united-kingdom) |           45,358 |                    49,232 |                     729 |                      3,874 |                                        9% |                                45,828 |                                 53,170 |
|                   [Italy](/italy) |           35,042 |                    35,609 |                     590 |                        567 |                                        2% |                                35,099 |                                 36,150 |
|                 [France](/france) |           30,155 |                    30,799 |                     460 |                        644 |                                        2% |                                30,173 |                                 33,794 |
|                   [Spain](/spain) |           28,420 |                    28,758 |                     613 |                        338 |                                        1% |                                28,448 |                                 29,636 |
|               [Belgium](/belgium) |            9,800 |                     9,967 |                     870 |                        167 |                                        2% |                                 9,815 |                                 10,432 |
|               [Germany](/germany) |            9,091 |                     9,405 |                     113 |                        314 |                                        3% |                                 9,121 |                                 10,116 |
|       [Netherlands](/netherlands) |            6,155 |                     6,250 |                     362 |                         95 |                                        2% |                                 6,172 |                                  6,358 |
|                 [Sweden](/sweden) |            5,619 |                     6,015 |                     588 |                        396 |                                        7% |                                 5,743 |                                  6,181 |
|               [Romania](/romania) |            2,009 |                     3,753 |                     193 |                      1,744 |                                       87% |                                 2,727 |                                  5,106 |
|                 [Serbia](/serbia) |              461 |                     2,916 |                     419 |                      2,455 |                                      533% |                                   954 |                                  7,331 |
|               [Ukraine](/ukraine) |            1,496 |                     2,683 |                      61 |                      1,187 |                                       79% |                                 2,022 |                                  3,872 |
|                 [Poland](/poland) |            1,618 |                     2,330 |                      61 |                        712 |                                       44% |                                 1,846 |                                  3,365 |
|             [Portugal](/portugal) |            1,684 |                     2,127 |                     207 |                        443 |                                       26% |                                 1,761 |                                  2,917 |
|       [Switzerland](/switzerland) |            1,969 |                     2,058 |                     240 |                         89 |                                        5% |                                 1,981 |                                  2,411 |
|               [Ireland](/ireland) |            1,753 |                     1,838 |                     375 |                         85 |                                        5% |                                 1,760 |                                  2,242 |
|               [Moldova](/moldova) |              680 |                     1,135 |                     281 |                        455 |                                       67% |                                   967 |                                  1,439 |
|               [Belarus](/belarus) |              495 |                     1,099 |                     116 |                        604 |                                      122% |                                   642 |                                  1,956 |
|             [Bulgaria](/bulgaria) |              299 |                       870 |                     124 |                        571 |                                      191% |                                   500 |                                  1,419 |
|               [Austria](/austria) |              711 |                       827 |                      93 |                        116 |                                       16% |                                   725 |                                  1,028 |
|               [Hungary](/hungary) |              596 |                       691 |                      71 |                         95 |                                       16% |                                   607 |                                    941 |
|               [Denmark](/denmark) |              611 |                       653 |                     112 |                         42 |                                        7% |                                   624 |                                    730 |
|               [Czechia](/czechia) |              358 |                       492 |                      46 |                        134 |                                       37% |                                   368 |                                    698 |
|               [Finland](/finland) |              328 |                       362 |                      66 |                         34 |                                       10% |                                   332 |                                    452 |
|                 [Norway](/norway) |              255 |                       276 |                      51 |                         21 |                                        8% |                                   262 |                                    318 |
|                 [Greece](/greece) |              194 |                       223 |                      21 |                         29 |                                       15% |                                   204 |                                    280 |
|               [Croatia](/croatia) |              120 |                       216 |                      53 |                         96 |                                       80% |                                   138 |                                    337 |
|         [Luxembourg](/luxembourg) |              111 |                       144 |                     235 |                         33 |                                       30% |                                   117 |                                    180 |
|             [Slovenia](/slovenia) |              111 |                       121 |                      58 |                         10 |                                        9% |                                   112 |                                    148 |
|           [Lithuania](/lithuania) |               80 |                       111 |                      40 |                         31 |                                       39% |                                    86 |                                    171 |
|               [Estonia](/estonia) |               69 |                        84 |                      63 |                         15 |                                       22% |                                    75 |                                    110 |
|                 [Latvia](/latvia) |               31 |                        40 |                      21 |                          9 |                                       29% |                                    33 |                                     69 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     71 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     56 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     23 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    10 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          260,651 |                   587,156 |                     113 |                    326,505 |                                      125% |                               398,409 |                                956,826 |
|                             [Brazil](/brazil) |           78,772 |                   154,235 |                     731 |                     75,463 |                                       96% |                               117,275 |                                233,254 |
|                               [India](/india) |           26,816 |                   106,338 |                      78 |                     79,522 |                                      297% |                                54,848 |                                221,354 |
|                             [Mexico](/mexico) |           38,888 |                    79,737 |                     625 |                     40,849 |                                      105% |                                56,230 |                                113,707 |
|                                 [Iran](/iran) |           13,979 |                    31,099 |                     375 |                     17,120 |                                      122% |                                22,569 |                                 45,448 |
|                                 [Peru](/peru) |           12,998 |                    23,114 |                     711 |                     10,116 |                                       78% |                                18,660 |                                 31,072 |
|                             [Russia](/russia) |           12,228 |                    22,303 |                     153 |                     10,075 |                                       82% |                                15,193 |                                 37,520 |
|                 [South Africa](/south-africa) |            4,948 |                    21,501 |                     367 |                     16,553 |                                      335% |                                13,318 |                                 32,073 |
|                         [Colombia](/colombia) |            6,516 |                    20,518 |                     408 |                     14,002 |                                      215% |                                15,467 |                                 28,995 |
|                       [Indonesia](/indonesia) |            4,016 |                    14,282 |                      53 |                     10,266 |                                      256% |                                 7,204 |                                 27,033 |
|                               [Chile](/chile) |            8,445 |                    12,156 |                     641 |                      3,711 |                                       44% |                                 9,470 |                                 14,503 |
|                         [Pakistan](/pakistan) |            5,568 |                    10,225 |                      47 |                      4,657 |                                       84% |                                 6,991 |                                 16,145 |
|                             [Canada](/canada) |            8,892 |                     9,795 |                     262 |                        903 |                                       10% |                                 8,983 |                                 11,032 |
|                               [Egypt](/egypt) |            4,251 |                     9,756 |                      97 |                      5,505 |                                      129% |                                 6,059 |                                 16,771 |
|                       [Argentina](/argentina) |            2,220 |                     9,015 |                     201 |                      6,795 |                                      306% |                                 4,224 |                                 16,907 |
|                           [Ecuador](/ecuador) |            5,282 |                     8,108 |                     467 |                      2,826 |                                       54% |                                 5,631 |                                 12,779 |
|                             [Turkey](/turkey) |            5,475 |                     6,848 |                      82 |                      1,373 |                                       25% |                                 5,558 |                                 11,257 |
|                           [Bolivia](/bolivia) |            2,106 |                     6,223 |                     541 |                      4,117 |                                      195% |                                 3,700 |                                 10,821 |
|                     [Bangladesh](/bangladesh) |            2,581 |                     5,869 |                      36 |                      3,288 |                                      127% |                                 3,813 |                                 10,124 |
|                 [Saudi Arabia](/saudi-arabia) |            2,447 |                     5,785 |                     169 |                      3,338 |                                      136% |                                 3,968 |                                  8,341 |
|                               [China](/china) |            4,644 |                     4,647 |                       3 |                          3 |                                        0% |                                 4,644 |                                  4,668 |
|                   [Philippines](/philippines) |            1,773 |                     4,297 |                      40 |                      2,524 |                                      142% |                                 2,435 |                                  8,751 |
|     [Dominican Republic](/dominican-republic) |              971 |                     3,841 |                     358 |                      2,870 |                                      296% |                                 1,483 |                                  8,397 |
|                         [Honduras](/honduras) |              891 |                     3,613 |                     371 |                      2,722 |                                      305% |                                 2,413 |                                  6,431 |
|                             [Panama](/panama) |            1,071 |                     3,319 |                     782 |                      2,248 |                                      210% |                                 2,468 |                                  5,253 |
|                           [Algeria](/algeria) |            1,068 |                     3,056 |                      71 |                      1,988 |                                      186% |                                 1,448 |                                  8,184 |
|                             [Israel](/israel) |              401 |                     1,740 |                     204 |                      1,339 |                                      334% |                                   637 |                                  5,108 |
|                           [Nigeria](/nigeria) |              778 |                     1,697 |                       8 |                        919 |                                      118% |                                   976 |                                  3,619 |
|                               [Japan](/japan) |              986 |                     1,503 |                      12 |                        517 |                                       52% |                                   992 |                                  2,555 |
|                             [Kuwait](/kuwait) |              407 |                       665 |                     158 |                        258 |                                       63% |                                   441 |                                  1,216 |
|                           [Morocco](/morocco) |              269 |                       511 |                      14 |                        242 |                                       90% |                                   316 |                                    964 |
| [United Arab Emirates](/united-arab-emirates) |              338 |                       473 |                      48 |                        135 |                                       40% |                                   351 |                                    868 |
|                   [South Korea](/south-korea) |              295 |                       341 |                       7 |                         46 |                                       16% |                                   297 |                                    460 |
|                       [Australia](/australia) |              122 |                       279 |                      11 |                        157 |                                      129% |                                   123 |                                    840 |
|                         [Malaysia](/malaysia) |              122 |                       150 |                       5 |                         28 |                                       23% |                                   133 |                                    179 |
|                                 [Cuba](/cuba) |               87 |                       117 |                      10 |                         30 |                                       34% |                                    91 |                                    197 |
