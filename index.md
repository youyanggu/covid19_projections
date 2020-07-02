We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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

* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 180k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: July 2 (3am ET):
<p align="center">
  Current Total: <b>127,414</b> deaths | Projected Total: <b>184,870 deaths by Oct 1, 2020</b> (Range: 153-236k)<br>
  Currently Infected: <b>0.7%</b> | Total Infected: <b>5.5%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 1, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 6, 2020 |
|              140,000 |        Jul 23, 2020 |
|              150,000 |         Aug 8, 2020 |
|              175,000 |        Sep 13, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        14% |         63% |        94% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        21% |         39% |        51% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          9% |        19% |
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
|             *[United States](/us)* |          128,059 |                   186,115 |                     561 |                     58,056 |                                       45% |                               155,910 |                                235,132 |
|                 [New York](/us-ny) |           32,043 |                    33,248 |                   1,709 |                      1,205 |                                        4% |                                32,099 |                                 37,683 |
|               [New Jersey](/us-nj) |           15,078 |                    16,321 |                   1,837 |                      1,243 |                                        8% |                                15,239 |                                 17,857 |
|               [California](/us-ca) |            6,169 |                    13,030 |                     330 |                      6,861 |                                      111% |                                 8,575 |                                 20,972 |
|                 [Illinois](/us-il) |            6,951 |                     9,776 |                     771 |                      2,825 |                                       41% |                                 7,638 |                                 13,847 |
|            [Massachusetts](/us-ma) |            8,053 |                     9,224 |                   1,327 |                      1,171 |                                       15% |                                 8,246 |                                 11,430 |
|             [Pennsylvania](/us-pa) |            6,684 |                     8,703 |                     680 |                      2,019 |                                       30% |                                 6,951 |                                 13,096 |
|                  [Florida](/us-fl) |            3,550 |                     8,607 |                     401 |                      5,057 |                                      142% |                                 4,926 |                                 16,077 |
|                    [Texas](/us-tx) |            2,503 |                     7,612 |                     263 |                      5,109 |                                      204% |                                 3,745 |                                 15,949 |
|                 [Michigan](/us-mi) |            6,198 |                     7,384 |                     739 |                      1,186 |                                       19% |                                 6,287 |                                 10,517 |
|                  [Georgia](/us-ga) |            2,827 |                     6,263 |                     590 |                      3,436 |                                      122% |                                 3,656 |                                 10,875 |
|                  [Arizona](/us-az) |            1,725 |                     5,585 |                     767 |                      3,860 |                                      224% |                                 3,601 |                                  8,541 |
|                     [Ohio](/us-oh) |            2,876 |                     4,810 |                     411 |                      1,934 |                                       67% |                                 3,185 |                                  8,634 |
|                [Louisiana](/us-la) |            3,238 |                     4,738 |                   1,019 |                      1,500 |                                       46% |                                 3,450 |                                  6,665 |
|              [Connecticut](/us-ct) |            4,324 |                     4,724 |                   1,325 |                        400 |                                        9% |                                 4,381 |                                  5,469 |
|                 [Maryland](/us-md) |            3,205 |                     4,474 |                     740 |                      1,269 |                                       40% |                                 3,442 |                                  6,657 |
|                  [Indiana](/us-in) |            2,650 |                     3,756 |                     558 |                      1,106 |                                       42% |                                 2,777 |                                  6,732 |
|           [North Carolina](/us-nc) |            1,398 |                     3,091 |                     295 |                      1,693 |                                      121% |                                 1,775 |                                  6,489 |
|                 [Virginia](/us-va) |            1,786 |                     2,921 |                     342 |                      1,135 |                                       64% |                                 1,923 |                                  5,385 |
|                  [Alabama](/us-al) |              972 |                     2,894 |                     590 |                      1,922 |                                      198% |                                 1,431 |                                  4,837 |
|           [South Carolina](/us-sc) |              766 |                     2,470 |                     480 |                      1,704 |                                      222% |                                 1,308 |                                  4,447 |
|                [Minnesota](/us-mn) |            1,482 |                     2,464 |                     437 |                        982 |                                       66% |                                 1,647 |                                  4,308 |
|                 [Colorado](/us-co) |            1,697 |                     2,367 |                     411 |                        670 |                                       39% |                                 1,761 |                                  4,242 |
|              [Mississippi](/us-ms) |            1,082 |                     2,259 |                     759 |                      1,177 |                                      109% |                                 1,337 |                                  3,732 |
|               [Washington](/us-wa) |            1,339 |                     2,091 |                     275 |                        752 |                                       56% |                                 1,486 |                                  3,506 |
|                [Tennessee](/us-tn) |              609 |                     1,992 |                     292 |                      1,383 |                                      227% |                                   978 |                                  3,736 |
|                 [Missouri](/us-mo) |            1,018 |                     1,566 |                     255 |                        548 |                                       54% |                                 1,090 |                                  2,905 |
|                [Wisconsin](/us-wi) |              786 |                     1,460 |                     251 |                        674 |                                       86% |                                   920 |                                  2,908 |
|             [Rhode Island](/us-ri) |              956 |                     1,336 |                   1,261 |                        380 |                                       40% |                                 1,041 |                                  1,858 |
|                   [Nevada](/us-nv) |              511 |                     1,225 |                     398 |                        714 |                                      140% |                                   653 |                                  2,144 |
|                 [Kentucky](/us-ky) |              572 |                     1,077 |                     241 |                        505 |                                       88% |                                   645 |                                  2,194 |
|                 [Arkansas](/us-ar) |              277 |                     1,003 |                     332 |                        726 |                                      262% |                                   428 |                                  2,033 |
|                     [Iowa](/us-ia) |              717 |                       946 |                     300 |                        229 |                                       32% |                                   752 |                                  1,519 |
|               [New Mexico](/us-nm) |              500 |                       863 |                     412 |                        363 |                                       73% |                                   564 |                                  1,618 |
|     [District of Columbia](/us-dc) |              553 |                       689 |                     976 |                        136 |                                       25% |                                   578 |                                    976 |
|                 [Oklahoma](/us-ok) |              389 |                       668 |                     169 |                        279 |                                       72% |                                   421 |                                  1,603 |
|                 [Delaware](/us-de) |              509 |                       665 |                     683 |                        156 |                                       31% |                                   531 |                                  1,073 |
|            [New Hampshire](/us-nh) |              373 |                       640 |                     471 |                        267 |                                       72% |                                   416 |                                  1,170 |
|                   [Oregon](/us-or) |              208 |                       545 |                     129 |                        337 |                                      162% |                                   257 |                                  1,145 |
|                 [Nebraska](/us-ne) |              276 |                       514 |                     266 |                        238 |                                       86% |                                   338 |                                    825 |
|                     [Utah](/us-ut) |              173 |                       490 |                     153 |                        317 |                                      183% |                                   222 |                                  1,336 |
|                   [Kansas](/us-ks) |              277 |                       426 |                     146 |                        149 |                                       54% |                                   293 |                                    909 |
|              [Puerto Rico](/us-pr) |              153 |                       213 |                      67 |                         60 |                                       39% |                                   161 |                                    395 |
|                    [Idaho](/us-id) |               92 |                       194 |                     109 |                        102 |                                      111% |                                   109 |                                    344 |
|             [South Dakota](/us-sd) |               93 |                       176 |                     199 |                         83 |                                       89% |                                   110 |                                    301 |
|                    [Maine](/us-me) |              105 |                       148 |                     110 |                         43 |                                       41% |                                   113 |                                    259 |
|            [West Virginia](/us-wv) |               93 |                       120 |                      67 |                         27 |                                       29% |                                    98 |                                    178 |
|             [North Dakota](/us-nd) |               80 |                       110 |                     144 |                         30 |                                       38% |                                    89 |                                    156 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    58 |                                    118 |
|                  [Montana](/us-mt) |               22 |                        48 |                      45 |                         26 |                                      118% |                                    24 |                                    106 |
|                   [Alaska](/us-ak) |               14 |                        34 |                      46 |                         20 |                                      143% |                                    15 |                                     94 |
|                  [Wyoming](/us-wy) |               20 |                        31 |                      54 |                         11 |                                       55% |                                    24 |                                     49 |
|                   [Hawaii](/us-hi) |               18 |                        25 |                      18 |                          7 |                                       39% |                                    19 |                                     38 |
|           [Virgin Islands](/us-vi) |                6 |                        11 |                     105 |                          5 |                                       83% |                                     6 |                                     18 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      7 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          181,921 |                   201,575 |                     340 |                     19,654 |                                       11% |                               186,225 |                                230,402 |
| [United Kingdom](/united-kingdom) |           43,991 |                    48,549 |                     719 |                      4,558 |                                       10% |                                44,900 |                                 52,169 |
|                   [Italy](/italy) |           34,788 |                    36,475 |                     604 |                      1,687 |                                        5% |                                35,041 |                                 40,278 |
|                 [France](/france) |           29,864 |                    30,877 |                     461 |                      1,013 |                                        3% |                                29,896 |                                 35,489 |
|                   [Spain](/spain) |           28,364 |                    29,215 |                     622 |                        851 |                                        3% |                                28,414 |                                 31,196 |
|               [Germany](/germany) |            8,995 |                    10,454 |                     126 |                      1,459 |                                       16% |                                 9,073 |                                 13,538 |
|               [Belgium](/belgium) |            9,754 |                    10,026 |                     875 |                        272 |                                        3% |                                 9,778 |                                 10,765 |
|       [Netherlands](/netherlands) |            6,132 |                     6,464 |                     374 |                        332 |                                        5% |                                 6,170 |                                  7,097 |
|                 [Sweden](/sweden) |            5,370 |                     6,323 |                     618 |                        953 |                                       18% |                                 5,778 |                                  7,601 |
|               [Romania](/romania) |            1,667 |                     3,668 |                     189 |                      2,001 |                                      120% |                                 2,246 |                                  4,806 |
|               [Ukraine](/ukraine) |            1,188 |                     3,107 |                      71 |                      1,919 |                                      162% |                                 1,825 |                                  4,946 |
|                 [Poland](/poland) |            1,477 |                     3,011 |                      79 |                      1,534 |                                      104% |                                 1,868 |                                  4,454 |
|       [Switzerland](/switzerland) |            1,965 |                     2,054 |                     239 |                         89 |                                        5% |                                 1,977 |                                  2,388 |
|             [Portugal](/portugal) |            1,579 |                     1,923 |                     187 |                        344 |                                       22% |                                 1,648 |                                  2,542 |
|               [Ireland](/ireland) |            1,738 |                     1,824 |                     372 |                         86 |                                        5% |                                 1,746 |                                  2,205 |
|               [Moldova](/moldova) |              549 |                     1,348 |                     333 |                        799 |                                      146% |                                   945 |                                  2,003 |
|               [Belarus](/belarus) |              398 |                       852 |                      90 |                        454 |                                      114% |                                   545 |                                  1,628 |
|               [Austria](/austria) |              705 |                       810 |                      91 |                        105 |                                       15% |                                   720 |                                    976 |
|               [Hungary](/hungary) |              586 |                       776 |                      79 |                        190 |                                       32% |                                   612 |                                  1,114 |
|               [Denmark](/denmark) |              606 |                       674 |                     116 |                         68 |                                       11% |                                   621 |                                    832 |
|             [Bulgaria](/bulgaria) |              232 |                       649 |                      93 |                        417 |                                      180% |                                   357 |                                  1,000 |
|                 [Serbia](/serbia) |              281 |                       453 |                      65 |                        172 |                                       61% |                                   310 |                                    712 |
|               [Czechia](/czechia) |              349 |                       447 |                      42 |                         98 |                                       28% |                                   357 |                                    579 |
|               [Finland](/finland) |              328 |                       366 |                      66 |                         38 |                                       12% |                                   334 |                                    474 |
|                 [Norway](/norway) |              251 |                       273 |                      51 |                         22 |                                        9% |                                   258 |                                    312 |
|                 [Greece](/greece) |              192 |                       223 |                      21 |                         31 |                                       16% |                                   203 |                                    271 |
|               [Croatia](/croatia) |              108 |                       156 |                      38 |                         48 |                                       44% |                                   116 |                                    216 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   113 |                                    151 |
|         [Luxembourg](/luxembourg) |              110 |                       118 |                     192 |                          8 |                                        7% |                                   112 |                                    137 |
|           [Lithuania](/lithuania) |               78 |                       111 |                      40 |                         33 |                                       42% |                                    86 |                                    156 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    75 |                                    149 |
|                 [Latvia](/latvia) |               30 |                        47 |                      24 |                         17 |                                       57% |                                    32 |                                     79 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    28 |                                     59 |
|                 [Cyprus](/cyprus) |               19 |                        30 |                      34 |                         11 |                                       58% |                                    20 |                                     46 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          196,456 |                   542,708 |                     105 |                    346,252 |                                      176% |                               345,779 |                                865,165 |
|                             [Brazil](/brazil) |           60,632 |                   131,211 |                     622 |                     70,579 |                                      116% |                               103,092 |                                196,637 |
|                               [India](/india) |           17,834 |                    96,494 |                      71 |                     78,660 |                                      441% |                                39,872 |                                200,605 |
|                             [Mexico](/mexico) |           28,510 |                    91,787 |                     719 |                     63,277 |                                      222% |                                60,359 |                                126,517 |
|                                 [Peru](/peru) |            9,860 |                    22,509 |                     692 |                     12,649 |                                      128% |                                15,780 |                                 32,499 |
|                                 [Iran](/iran) |           10,958 |                    20,236 |                     244 |                      9,278 |                                       85% |                                16,387 |                                 26,073 |
|                             [Russia](/russia) |            9,521 |                    19,881 |                     136 |                     10,360 |                                      109% |                                13,566 |                                 31,902 |
|                         [Colombia](/colombia) |            3,488 |                    19,676 |                     391 |                     16,188 |                                      464% |                                11,711 |                                 27,951 |
|                         [Pakistan](/pakistan) |            4,473 |                    16,087 |                      74 |                     11,614 |                                      260% |                                 8,805 |                                 28,654 |
|                 [South Africa](/south-africa) |            2,749 |                    14,343 |                     245 |                     11,594 |                                      422% |                                 7,273 |                                 20,689 |
|                               [Egypt](/egypt) |            3,034 |                    13,139 |                     131 |                     10,105 |                                      333% |                                 7,604 |                                 20,823 |
|                               [Chile](/chile) |            5,753 |                    12,967 |                     684 |                      7,214 |                                      125% |                                 7,784 |                                 19,096 |
|                             [Canada](/canada) |            8,678 |                    10,197 |                     273 |                      1,519 |                                       18% |                                 8,927 |                                 13,068 |
|                       [Indonesia](/indonesia) |            2,934 |                     8,863 |                      33 |                      5,929 |                                      202% |                                 4,455 |                                 14,606 |
|                     [Bangladesh](/bangladesh) |            1,888 |                     8,598 |                      53 |                      6,710 |                                      355% |                                 4,454 |                                 14,456 |
|                             [Turkey](/turkey) |            5,150 |                     7,777 |                      93 |                      2,627 |                                       51% |                                 5,470 |                                 12,832 |
|                       [Argentina](/argentina) |            1,351 |                     6,986 |                     156 |                      5,635 |                                      417% |                                 3,472 |                                 12,540 |
|                           [Bolivia](/bolivia) |            1,201 |                     6,776 |                     589 |                      5,575 |                                      464% |                                 3,240 |                                 10,448 |
|                           [Ecuador](/ecuador) |            4,576 |                     6,388 |                     368 |                      1,812 |                                       40% |                                 4,885 |                                 10,824 |
|                 [Saudi Arabia](/saudi-arabia) |            1,698 |                     5,183 |                     151 |                      3,485 |                                      205% |                                 3,120 |                                  7,169 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,680 |
|                         [Honduras](/honduras) |              542 |                     3,068 |                     315 |                      2,526 |                                      466% |                                 2,018 |                                  4,545 |
|     [Dominican Republic](/dominican-republic) |              754 |                     2,899 |                     270 |                      2,145 |                                      284% |                                 1,064 |                                  5,608 |
|                   [Philippines](/philippines) |            1,270 |                     2,720 |                      25 |                      1,450 |                                      114% |                                 1,427 |                                  5,111 |
|                             [Panama](/panama) |              645 |                     2,443 |                     575 |                      1,798 |                                      279% |                                 1,327 |                                  3,479 |
|                           [Algeria](/algeria) |              920 |                     2,111 |                      49 |                      1,191 |                                      129% |                                 1,270 |                                  4,244 |
|                           [Nigeria](/nigeria) |              603 |                     1,921 |                      10 |                      1,318 |                                      219% |                                   866 |                                  4,154 |
|                               [Japan](/japan) |              976 |                     1,215 |                      10 |                        239 |                                       24% |                                   980 |                                  1,768 |
|                             [Kuwait](/kuwait) |              358 |                       601 |                     143 |                        243 |                                       68% |                                   409 |                                  1,013 |
|                             [Israel](/israel) |              322 |                       433 |                      51 |                        111 |                                       34% |                                   336 |                                    691 |
| [United Arab Emirates](/united-arab-emirates) |              316 |                       432 |                      44 |                        116 |                                       37% |                                   337 |                                    751 |
|                   [South Korea](/south-korea) |              282 |                       357 |                       7 |                         75 |                                       27% |                                   283 |                                    570 |
|                         [Malaysia](/malaysia) |              121 |                       274 |                       9 |                        153 |                                      126% |                                   136 |                                    472 |
|                           [Morocco](/morocco) |              228 |                       270 |                       7 |                         42 |                                       18% |                                   235 |                                    399 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    153 |
|                                 [Cuba](/cuba) |               86 |                       103 |                       9 |                         17 |                                       20% |                                    90 |                                    138 |
