We present an intuitive COVID-19 model that adds machine learning techniques on top of a classic infectious disease model to make projections for infections and deaths for the US and 70 other countries. The countries our projections cover encompass 6.4 billion people and account for more than 95% of all global reported COVID-19 deaths.

Our infections estimates include all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 28 - MAJOR ANNOUNCEMENT:** We will no longer be extending our projections past November 1. Our last forecast update will be on Monday, October 5. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later). Thank you for your support over the past six months.
* **September 30:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1311384211983675397).
* *September 29:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: October 3 (4am ET):
<p align="center">
  Current Total: <b>208,692</b> deaths | Projected Total: <b>231,600 deaths by Nov 1, 2020</b> (Range: 221-248k)<br>
  Currently Infected: <b>1.2%</b> (1 in 85) | Total Infected: <b>16.0%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: October 3, 2020

|   US deaths surpass: |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|
|              225,000 |          1% |        79% |
|              250,000 |         <1% |         2% |
|              275,000 |         <1% |        <1% |
|              300,000 |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries).

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
|             *[United States](/us)* |          208,692 |                   231,613 |                     698 |                     22,921 |                       69 |                                       11% |                               221,386 |                                247,980 |
|                 [New York](/us-ny) |           33,199 |                    33,594 |                   1,727 |                        395 |                       20 |                                        1% |                                33,209 |                                 35,636 |
|                    [Texas](/us-tx) |           16,224 |                    18,861 |                     650 |                      2,637 |                       91 |                                       16% |                                17,359 |                                 21,363 |
|               [California](/us-ca) |           16,054 |                    18,266 |                     462 |                      2,212 |                       56 |                                       14% |                                16,583 |                                 22,089 |
|                  [Florida](/us-fl) |           14,554 |                    17,422 |                     811 |                      2,868 |                      134 |                                       20% |                                15,612 |                                 20,375 |
|               [New Jersey](/us-nj) |           16,131 |                    16,369 |                   1,843 |                        238 |                       27 |                                        1% |                                16,138 |                                 17,136 |
|            [Massachusetts](/us-ma) |            9,490 |                     9,990 |                   1,438 |                        500 |                       72 |                                        5% |                                 9,517 |                                 10,784 |
|                 [Illinois](/us-il) |            8,992 |                     9,729 |                     768 |                        737 |                       58 |                                        8% |                                 9,131 |                                 10,892 |
|             [Pennsylvania](/us-pa) |            8,162 |                     8,822 |                     689 |                        660 |                       52 |                                        8% |                                 8,235 |                                  9,877 |
|                  [Georgia](/us-ga) |            7,106 |                     8,130 |                     766 |                      1,024 |                       96 |                                       14% |                                 7,413 |                                  9,389 |
|                 [Michigan](/us-mi) |            7,110 |                     7,454 |                     746 |                        344 |                       34 |                                        5% |                                 7,157 |                                  8,004 |
|                  [Arizona](/us-az) |            5,693 |                     6,256 |                     859 |                        563 |                       77 |                                       10% |                                 5,840 |                                  7,099 |
|                [Louisiana](/us-la) |            5,545 |                     5,979 |                   1,286 |                        434 |                       93 |                                        8% |                                 5,681 |                                  6,529 |
|                     [Ohio](/us-oh) |            4,905 |                     5,734 |                     491 |                        829 |                       71 |                                       17% |                                 5,116 |                                  6,806 |
|              [Connecticut](/us-ct) |            4,513 |                     4,606 |                   1,292 |                         93 |                       26 |                                        2% |                                 4,518 |                                  4,892 |
|           [North Carolina](/us-nc) |            3,608 |                     4,589 |                     437 |                        981 |                       93 |                                       27% |                                 4,016 |                                  5,557 |
|                 [Maryland](/us-md) |            3,950 |                     4,184 |                     692 |                        234 |                       39 |                                        6% |                                 3,977 |                                  4,598 |
|                  [Indiana](/us-in) |            3,656 |                     4,094 |                     608 |                        438 |                       65 |                                       12% |                                 3,690 |                                  4,894 |
|           [South Carolina](/us-sc) |            3,409 |                     3,907 |                     759 |                        498 |                       97 |                                       15% |                                 3,627 |                                  4,326 |
|                 [Virginia](/us-va) |            3,247 |                     3,843 |                     450 |                        596 |                       70 |                                       18% |                                 3,395 |                                  4,610 |
|              [Mississippi](/us-ms) |            2,999 |                     3,366 |                   1,131 |                        367 |                      123 |                                       12% |                                 3,130 |                                  3,800 |
|                [Tennessee](/us-tn) |            2,515 |                     3,133 |                     459 |                        618 |                       90 |                                       25% |                                 2,792 |                                  3,675 |
|                 [Missouri](/us-mo) |            2,146 |                     2,874 |                     468 |                        728 |                      119 |                                       34% |                                 2,458 |                                  3,503 |
|                  [Alabama](/us-al) |            2,550 |                     2,845 |                     580 |                        295 |                       60 |                                       12% |                                 2,654 |                                  3,169 |
|               [Washington](/us-wa) |            2,143 |                     2,493 |                     327 |                        350 |                       46 |                                       16% |                                 2,192 |                                  3,097 |
|                [Minnesota](/us-mn) |            2,112 |                     2,430 |                     431 |                        318 |                       56 |                                       15% |                                 2,166 |                                  2,872 |
|                 [Colorado](/us-co) |            2,057 |                     2,220 |                     386 |                        163 |                       28 |                                        8% |                                 2,069 |                                  2,532 |
|                 [Arkansas](/us-ar) |            1,391 |                     1,823 |                     604 |                        432 |                      143 |                                       31% |                                 1,593 |                                  2,229 |
|                   [Nevada](/us-nv) |            1,609 |                     1,793 |                     582 |                        184 |                       60 |                                       11% |                                 1,667 |                                  2,033 |
|                [Wisconsin](/us-wi) |            1,353 |                     1,745 |                     300 |                        392 |                       67 |                                       29% |                                 1,504 |                                  2,089 |
|                     [Iowa](/us-ia) |            1,377 |                     1,662 |                     527 |                        285 |                       90 |                                       21% |                                 1,469 |                                  1,981 |
|                 [Kentucky](/us-ky) |            1,197 |                     1,474 |                     330 |                        277 |                       62 |                                       23% |                                 1,302 |                                  1,740 |
|                 [Oklahoma](/us-ok) |            1,044 |                     1,320 |                     334 |                        276 |                       70 |                                       26% |                                 1,169 |                                  1,569 |
|             [Rhode Island](/us-ri) |            1,118 |                     1,195 |                   1,128 |                         77 |                       72 |                                        7% |                                 1,126 |                                  1,332 |
|               [New Mexico](/us-nm) |              887 |                     1,021 |                     487 |                        134 |                       64 |                                       15% |                                   930 |                                  1,194 |
|                   [Kansas](/us-ks) |              688 |                       903 |                     310 |                        215 |                       74 |                                       31% |                                   771 |                                  1,104 |
|              [Puerto Rico](/us-pr) |              673 |                       886 |                     277 |                        213 |                       67 |                                       32% |                                   777 |                                  1,044 |
|                   [Oregon](/us-or) |              563 |                       705 |                     167 |                        142 |                       34 |                                       25% |                                   614 |                                    853 |
|                 [Delaware](/us-de) |              642 |                       685 |                     703 |                         43 |                       44 |                                        7% |                                   648 |                                    758 |
|     [District of Columbia](/us-dc) |              627 |                       653 |                     925 |                         26 |                       37 |                                        4% |                                   631 |                                    710 |
|                 [Nebraska](/us-ne) |              493 |                       610 |                     315 |                        117 |                       61 |                                       24% |                                   530 |                                    747 |
|                    [Idaho](/us-id) |              474 |                       575 |                     322 |                        101 |                       57 |                                       21% |                                   521 |                                    656 |
|                     [Utah](/us-ut) |              474 |                       575 |                     179 |                        101 |                       31 |                                       21% |                                   508 |                                    675 |
|            [West Virginia](/us-wv) |              361 |                       510 |                     285 |                        149 |                       83 |                                       41% |                                   431 |                                    637 |
|             [North Dakota](/us-nd) |              264 |                       478 |                     628 |                        214 |                      281 |                                       81% |                                   384 |                                    621 |
|            [New Hampshire](/us-nh) |              442 |                       453 |                     333 |                         11 |                        8 |                                        2% |                                   443 |                                    495 |
|             [South Dakota](/us-sd) |              237 |                       365 |                     412 |                        128 |                      144 |                                       54% |                                   282 |                                    492 |
|                  [Montana](/us-mt) |              186 |                       313 |                     293 |                        127 |                      119 |                                       68% |                                   252 |                                    402 |
|                   [Hawaii](/us-hi) |              142 |                       207 |                     146 |                         65 |                       46 |                                       46% |                                   171 |                                    275 |
|                    [Maine](/us-me) |              141 |                       153 |                     114 |                         12 |                        9 |                                        9% |                                   143 |                                    178 |
|                   [Alaska](/us-ak) |               57 |                        87 |                     119 |                         30 |                       42 |                                       53% |                                    72 |                                    116 |
|                     [Guam](/us-gu) |               49 |                        79 |                     474 |                         30 |                      178 |                                       60% |                                    63 |                                    104 |
|                  [Wyoming](/us-wy) |               53 |                        69 |                     119 |                         16 |                       28 |                                       30% |                                    59 |                                     85 |
|                  [Vermont](/us-vt) |               58 |                        59 |                      95 |                          1 |                        2 |                                        2% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               20 |                        23 |                     222 |                          3 |                       31 |                                       16% |                                    21 |                                     27 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      46 |                          1 |                        9 |                                       26% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          200,826 |                   221,998 |                     374 |                     21,172 |                       36 |                                       11% |                               204,942 |                                275,172 |
| [United Kingdom](/united-kingdom) |           42,358 |                    44,494 |                     659 |                      2,136 |                       32 |                                        5% |                                42,413 |                                 51,769 |
|                   [Spain](/spain) |           32,086 |                    37,095 |                     790 |                      5,009 |                      107 |                                       16% |                                32,871 |                                 48,162 |
|                   [Italy](/italy) |           35,941 |                    36,803 |                     610 |                        862 |                       14 |                                        2% |                                35,960 |                                 39,618 |
|                 [France](/france) |           32,171 |                    35,578 |                     531 |                      3,407 |                       51 |                                       11% |                                32,213 |                                 52,926 |
|               [Belgium](/belgium) |           10,037 |                    10,487 |                     915 |                        450 |                       39 |                                        4% |                                10,061 |                                 12,229 |
|               [Germany](/germany) |            9,518 |                    10,043 |                     121 |                        525 |                        6 |                                        6% |                                 9,531 |                                 12,008 |
|       [Netherlands](/netherlands) |            6,482 |                     7,246 |                     419 |                        764 |                       44 |                                       12% |                                 6,506 |                                  9,633 |
|               [Ukraine](/ukraine) |            4,357 |                     6,604 |                     150 |                      2,247 |                       51 |                                       52% |                                 5,357 |                                  8,054 |
|               [Romania](/romania) |            4,915 |                     6,226 |                     321 |                      1,311 |                       68 |                                       27% |                                 5,493 |                                  7,518 |
|                 [Sweden](/sweden) |            5,895 |                     6,009 |                     587 |                        114 |                       11 |                                        2% |                                 5,902 |                                  6,416 |
|                 [Poland](/poland) |            2,570 |                     3,677 |                      97 |                      1,107 |                       29 |                                       43% |                                 2,893 |                                  5,344 |
|             [Portugal](/portugal) |            1,983 |                     2,246 |                     219 |                        263 |                       26 |                                       13% |                                 2,049 |                                  2,559 |
|       [Switzerland](/switzerland) |            2,075 |                     2,197 |                     256 |                        122 |                       14 |                                        6% |                                 2,102 |                                  2,414 |
|               [Ireland](/ireland) |            1,801 |                     1,881 |                     384 |                         80 |                       16 |                                        4% |                                 1,808 |                                  2,192 |
|               [Moldova](/moldova) |            1,344 |                     1,678 |                     415 |                        334 |                       83 |                                       25% |                                 1,482 |                                  1,990 |
|               [Czechia](/czechia) |              699 |                     1,539 |                     144 |                        840 |                       79 |                                      120% |                                 1,063 |                                  2,357 |
|               [Hungary](/hungary) |              798 |                     1,227 |                     126 |                        429 |                       44 |                                       54% |                                 1,022 |                                  1,545 |
|             [Bulgaria](/bulgaria) |              838 |                     1,047 |                     150 |                        209 |                       30 |                                       25% |                                   938 |                                  1,214 |
|               [Belarus](/belarus) |              844 |                     1,047 |                     111 |                        203 |                       21 |                                       24% |                                   905 |                                  1,334 |
|               [Austria](/austria) |              803 |                       936 |                     106 |                        133 |                       15 |                                       17% |                                   832 |                                  1,135 |
|                 [Serbia](/serbia) |              751 |                       769 |                     110 |                         18 |                        3 |                                        2% |                                   754 |                                    820 |
|               [Denmark](/denmark) |              652 |                       717 |                     124 |                         65 |                       11 |                                       10% |                                   662 |                                    867 |
|                 [Greece](/greece) |              398 |                       564 |                      53 |                        166 |                       15 |                                       42% |                                   466 |                                    735 |
|               [Croatia](/croatia) |              291 |                       387 |                      95 |                         96 |                       24 |                                       33% |                                   323 |                                    528 |
|               [Finland](/finland) |              345 |                       375 |                      68 |                         30 |                        5 |                                        9% |                                   355 |                                    412 |
|                 [Norway](/norway) |              275 |                       309 |                      57 |                         34 |                        6 |                                       12% |                                   287 |                                    346 |
|             [Slovenia](/slovenia) |              154 |                       200 |                      96 |                         46 |                       22 |                                       30% |                                   174 |                                    242 |
|         [Luxembourg](/luxembourg) |              125 |                       137 |                     222 |                         12 |                       19 |                                        9% |                                   127 |                                    156 |
|             [Slovakia](/slovakia) |               54 |                       116 |                      21 |                         62 |                       11 |                                      115% |                                    86 |                                    167 |
|           [Lithuania](/lithuania) |               93 |                       115 |                      41 |                         22 |                        8 |                                       24% |                                   102 |                                    134 |
|                   [Malta](/malta) |               37 |                        84 |                     170 |                         47 |                       95 |                                      127% |                                    57 |                                    153 |
|               [Estonia](/estonia) |               66 |                        80 |                      60 |                         14 |                       11 |                                       21% |                                    72 |                                     93 |
|                 [Latvia](/latvia) |               38 |                        49 |                      26 |                         11 |                        6 |                                       29% |                                    43 |                                     59 |
|                 [Cyprus](/cyprus) |               22 |                        24 |                      28 |                          2 |                        3 |                                       11% |                                    23 |                                     28 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        7 |                                       22% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          578,916 |                   683,440 |                     132 |                    104,524 |                       20 |                                       18% |                               629,585 |                                771,765 |
|                             [Brazil](/brazil) |          144,680 |                   161,202 |                     764 |                     16,522 |                       78 |                                       11% |                               153,344 |                                174,674 |
|                               [India](/india) |           99,773 |                   130,189 |                      95 |                     30,416 |                       22 |                                       30% |                               115,069 |                                145,809 |
|                             [Mexico](/mexico) |           78,492 |                    88,912 |                     697 |                     10,420 |                       82 |                                       13% |                                85,247 |                                 95,394 |
|                                 [Peru](/peru) |           32,535 |                    35,077 |                   1,079 |                      2,542 |                       78 |                                        8% |                                33,063 |                                 38,241 |
|                                 [Iran](/iran) |           26,567 |                    32,003 |                     386 |                      5,436 |                       66 |                                       20% |                                29,358 |                                 36,128 |
|                       [Argentina](/argentina) |           20,599 |                    31,718 |                     708 |                     11,119 |                      248 |                                       54% |                                26,052 |                                 40,229 |
|                         [Colombia](/colombia) |           26,397 |                    30,336 |                     603 |                      3,939 |                       78 |                                       15% |                                28,521 |                                 33,905 |
|                             [Russia](/russia) |           20,981 |                    25,687 |                     176 |                      4,706 |                       32 |                                       22% |                                23,610 |                                 33,536 |
|                 [South Africa](/south-africa) |           16,909 |                    18,376 |                     314 |                      1,467 |                       25 |                                        9% |                                17,302 |                                 20,567 |
|                       [Indonesia](/indonesia) |           10,972 |                    14,758 |                      55 |                      3,786 |                       14 |                                       35% |                                13,370 |                                 18,205 |
|                               [Chile](/chile) |           12,867 |                    14,434 |                     762 |                      1,567 |                       83 |                                       12% |                                13,016 |                                 18,093 |
|                           [Ecuador](/ecuador) |           11,495 |                    12,455 |                     717 |                        960 |                       55 |                                        8% |                                11,564 |                                 14,042 |
|                             [Turkey](/turkey) |            8,325 |                    10,606 |                     127 |                      2,281 |                       27 |                                       27% |                                 8,695 |                                 13,594 |
|                             [Canada](/canada) |            9,466 |                    10,208 |                     273 |                        742 |                       20 |                                        8% |                                 9,544 |                                 11,951 |
|                           [Bolivia](/bolivia) |            8,045 |                     8,843 |                     768 |                        798 |                       69 |                                       10% |                                 8,352 |                                  9,613 |
|                   [Philippines](/philippines) |            5,616 |                     7,460 |                      69 |                      1,844 |                       17 |                                       33% |                                 6,366 |                                  9,077 |
|                         [Pakistan](/pakistan) |            6,507 |                     6,744 |                      31 |                        237 |                        1 |                                        4% |                                 6,548 |                                  7,146 |
|                               [Egypt](/egypt) |            5,956 |                     6,507 |                      65 |                        551 |                        5 |                                        9% |                                 6,028 |                                  7,640 |
|                     [Bangladesh](/bangladesh) |            5,305 |                     6,148 |                      38 |                        843 |                        5 |                                       16% |                                 5,690 |                                  7,200 |
|                 [Saudi Arabia](/saudi-arabia) |            4,823 |                     5,589 |                     163 |                        766 |                       22 |                                       16% |                                 5,017 |                                  6,419 |
|                               [China](/china) |            4,739 |                     4,757 |                       3 |                         18 |                        0 |                                        0% |                                 4,739 |                                  4,902 |
|                           [Morocco](/morocco) |            2,263 |                     3,506 |                      96 |                      1,243 |                       34 |                                       55% |                                 2,810 |                                  4,504 |
|                         [Honduras](/honduras) |            2,386 |                     2,835 |                     291 |                        449 |                       46 |                                       19% |                                 2,517 |                                  3,380 |
|                             [Panama](/panama) |            2,406 |                     2,647 |                     623 |                        241 |                       57 |                                       10% |                                 2,484 |                                  2,938 |
|                             [Israel](/israel) |            1,633 |                     2,398 |                     282 |                        765 |                       90 |                                       47% |                                 1,911 |                                  3,329 |
|     [Dominican Republic](/dominican-republic) |            2,117 |                     2,264 |                     211 |                        147 |                       14 |                                        7% |                                 2,158 |                                  2,422 |
|                           [Algeria](/algeria) |            1,749 |                     1,855 |                      43 |                        106 |                        2 |                                        6% |                                 1,772 |                                  2,007 |
|                               [Japan](/japan) |            1,591 |                     1,768 |                      14 |                        177 |                        1 |                                       11% |                                 1,642 |                                  1,959 |
|                           [Nigeria](/nigeria) |            1,112 |                     1,185 |                       6 |                         73 |                        0 |                                        7% |                                 1,122 |                                  1,356 |
|                       [Australia](/australia) |              893 |                       959 |                      38 |                         66 |                        3 |                                        7% |                                   912 |                                  1,029 |
|                             [Kuwait](/kuwait) |              615 |                       695 |                     165 |                         80 |                       19 |                                       13% |                                   629 |                                    828 |
| [United Arab Emirates](/united-arab-emirates) |              424 |                       515 |                      53 |                         91 |                        9 |                                       21% |                                   428 |                                    667 |
|                   [South Korea](/south-korea) |              420 |                       502 |                      10 |                         82 |                        2 |                                       19% |                                   436 |                                    616 |
|                         [Malaysia](/malaysia) |              136 |                       154 |                       5 |                         18 |                        1 |                                       13% |                                   141 |                                    181 |
|                                 [Cuba](/cuba) |              122 |                       148 |                      13 |                         26 |                        2 |                                       21% |                                   128 |                                    184 |
