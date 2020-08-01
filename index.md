We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >97% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5-8x higher than the reported cases.

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
* **July 31:** We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* **July 28:** View our [updated historical performance](/about/#historical-performance).
* **July 23:** We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: August 1 (2am ET):
<p align="center">
  Current Total: <b>153,311</b> deaths | Projected Total: <b>230,400 deaths by Nov 1, 2020</b> (Range: 199-276k)<br>
  Currently Infected: <b>2.1%</b> | Total Infected: <b>12.0%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 1, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 19, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |        <1% |          7% |        99% |         99% |        99% |         99% |       >99% |
|              200,000 |        <1% |         <1% |         7% |         40% |        74% |         89% |        97% |
|              225,000 |        <1% |         <1% |        <1% |          3% |        16% |         32% |        49% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         1% |          6% |        14% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         3% |
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
|             *[United States](/us)* |          153,311 |                   230,449 |                     695 |                     77,138 |                                       50% |                               199,462 |                                275,014 |
|                 [New York](/us-ny) |           32,689 |                    33,667 |                   1,731 |                        978 |                                        3% |                                32,736 |                                 38,064 |
|               [California](/us-ca) |            9,214 |                    19,277 |                     488 |                     10,063 |                                      109% |                                13,639 |                                 27,039 |
|                    [Texas](/us-tx) |            6,576 |                    17,909 |                     618 |                     11,333 |                                      172% |                                12,092 |                                 24,388 |
|                  [Florida](/us-fl) |            6,843 |                    17,741 |                     826 |                     10,898 |                                      159% |                                12,352 |                                 26,857 |
|               [New Jersey](/us-nj) |           15,819 |                    16,540 |                   1,862 |                        721 |                                        5% |                                15,913 |                                 17,962 |
|            [Massachusetts](/us-ma) |            8,609 |                     9,515 |                   1,369 |                        906 |                                       11% |                                 8,680 |                                 11,376 |
|                 [Illinois](/us-il) |            7,692 |                     9,363 |                     739 |                      1,671 |                                       22% |                                 7,955 |                                 11,924 |
|             [Pennsylvania](/us-pa) |            7,207 |                     9,106 |                     711 |                      1,899 |                                       26% |                                 7,349 |                                 13,130 |
|                  [Arizona](/us-az) |            3,694 |                     7,299 |                   1,003 |                      3,605 |                                       98% |                                 5,537 |                                  9,449 |
|                  [Georgia](/us-ga) |            3,752 |                     7,154 |                     674 |                      3,402 |                                       91% |                                 5,115 |                                 10,242 |
|                 [Michigan](/us-mi) |            6,450 |                     6,933 |                     694 |                        483 |                                        7% |                                 6,494 |                                  7,935 |
|                [Louisiana](/us-la) |            3,949 |                     5,761 |                   1,239 |                      1,812 |                                       46% |                                 4,540 |                                  7,753 |
|                     [Ohio](/us-oh) |            3,489 |                     5,655 |                     484 |                      2,166 |                                       62% |                                 4,039 |                                  8,536 |
|                 [Maryland](/us-md) |            3,493 |                     4,833 |                     799 |                      1,340 |                                       38% |                                 3,715 |                                  7,567 |
|              [Connecticut](/us-ct) |            4,432 |                     4,662 |                   1,308 |                        230 |                                        5% |                                 4,465 |                                  5,120 |
|           [South Carolina](/us-sc) |            1,712 |                     4,625 |                     898 |                      2,913 |                                      170% |                                 3,176 |                                  6,466 |
|                  [Indiana](/us-in) |            2,965 |                     4,487 |                     666 |                      1,522 |                                       51% |                                 3,236 |                                  7,115 |
|           [North Carolina](/us-nc) |            1,942 |                     4,055 |                     387 |                      2,113 |                                      109% |                                 2,677 |                                  6,244 |
|                 [Virginia](/us-va) |            2,174 |                     3,353 |                     393 |                      1,179 |                                       54% |                                 2,357 |                                  5,423 |
|                  [Alabama](/us-al) |            1,580 |                     3,316 |                     676 |                      1,736 |                                      110% |                                 2,347 |                                  4,745 |
|              [Mississippi](/us-ms) |            1,663 |                     3,204 |                   1,076 |                      1,541 |                                       93% |                                 2,252 |                                  4,607 |
|                 [Missouri](/us-mo) |            1,265 |                     2,696 |                     439 |                      1,431 |                                      113% |                                 1,592 |                                  4,743 |
|                [Tennessee](/us-tn) |            1,060 |                     2,508 |                     367 |                      1,448 |                                      137% |                                 1,649 |                                  3,631 |
|                 [Colorado](/us-co) |            1,838 |                     2,469 |                     429 |                        631 |                                       34% |                                 1,928 |                                  3,732 |
|                [Minnesota](/us-mn) |            1,640 |                     2,271 |                     403 |                        631 |                                       38% |                                 1,744 |                                  3,447 |
|               [Washington](/us-wa) |            1,564 |                     2,159 |                     284 |                        595 |                                       38% |                                 1,633 |                                  3,248 |
|                   [Nevada](/us-nv) |              830 |                     1,952 |                     634 |                      1,122 |                                      135% |                                 1,310 |                                  2,867 |
|                [Wisconsin](/us-wi) |              934 |                     1,884 |                     324 |                        950 |                                      102% |                                 1,120 |                                  3,425 |
|                 [Kentucky](/us-ky) |              735 |                     1,675 |                     375 |                        940 |                                      128% |                                   926 |                                  3,177 |
|                     [Iowa](/us-ia) |              872 |                     1,530 |                     485 |                        658 |                                       76% |                                 1,028 |                                  2,517 |
|                 [Oklahoma](/us-ok) |              541 |                     1,363 |                     344 |                        822 |                                      152% |                                   824 |                                  2,229 |
|             [Rhode Island](/us-ri) |            1,007 |                     1,173 |                   1,107 |                        166 |                                       16% |                                 1,034 |                                  1,407 |
|                 [Arkansas](/us-ar) |              453 |                     1,118 |                     370 |                        665 |                                      147% |                                   710 |                                  1,698 |
|               [New Mexico](/us-nm) |              642 |                     1,104 |                     526 |                        462 |                                       72% |                                   766 |                                  1,698 |
|                   [Oregon](/us-or) |              322 |                     1,022 |                     242 |                        700 |                                      217% |                                   547 |                                  1,828 |
|              [Puerto Rico](/us-pr) |              219 |                       856 |                     268 |                        637 |                                      291% |                                   387 |                                  1,735 |
|                     [Utah](/us-ut) |              304 |                       852 |                     266 |                        548 |                                      180% |                                   500 |                                  1,360 |
|                    [Idaho](/us-id) |              188 |                       784 |                     439 |                        596 |                                      317% |                                   430 |                                  1,282 |
|                   [Kansas](/us-ks) |              358 |                       739 |                     254 |                        381 |                                      107% |                                   471 |                                  1,195 |
|                 [Delaware](/us-de) |              585 |                       677 |                     695 |                         92 |                                       16% |                                   601 |                                    829 |
|     [District of Columbia](/us-dc) |              584 |                       645 |                     914 |                         61 |                                       10% |                                   597 |                                    748 |
|            [New Hampshire](/us-nh) |              415 |                       533 |                     392 |                        118 |                                       28% |                                   427 |                                    745 |
|                 [Nebraska](/us-ne) |              332 |                       498 |                     258 |                        166 |                                       50% |                                   367 |                                    738 |
|                  [Montana](/us-mt) |               60 |                       293 |                     274 |                        233 |                                      389% |                                   146 |                                    517 |
|            [West Virginia](/us-wv) |              116 |                       249 |                     139 |                        133 |                                      115% |                                   147 |                                    482 |
|             [South Dakota](/us-sd) |              130 |                       222 |                     251 |                         92 |                                       71% |                                   161 |                                    345 |
|             [North Dakota](/us-nd) |              103 |                       213 |                     279 |                        110 |                                      106% |                                   133 |                                    369 |
|                    [Maine](/us-me) |              123 |                       176 |                     131 |                         53 |                                       43% |                                   133 |                                    253 |
|                   [Alaska](/us-ak) |               23 |                       106 |                     146 |                         83 |                                      363% |                                    47 |                                    237 |
|                  [Vermont](/us-vt) |               57 |                        79 |                     126 |                         22 |                                       38% |                                    64 |                                    110 |
|                   [Hawaii](/us-hi) |               26 |                        71 |                      50 |                         45 |                                      174% |                                    31 |                                    181 |
|                  [Wyoming](/us-wy) |               26 |                        42 |                      73 |                         16 |                                       62% |                                    31 |                                     68 |
|           [Virgin Islands](/us-vi) |                8 |                        23 |                     218 |                         15 |                                      186% |                                    11 |                                     43 |
|                     [Guam](/us-gu) |                5 |                         9 |                      53 |                          4 |                                       77% |                                     5 |                                     17 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       59% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,230 |                   204,840 |                     345 |                     16,610 |                                        9% |                               191,648 |                                237,849 |
| [United Kingdom](/united-kingdom) |           46,204 |                    50,742 |                     751 |                      4,538 |                                       10% |                                46,612 |                                 60,483 |
|                   [Italy](/italy) |           35,141 |                    35,662 |                     591 |                        521 |                                        1% |                                35,166 |                                 37,518 |
|                 [France](/france) |           30,268 |                    30,861 |                     461 |                        593 |                                        2% |                                30,294 |                                 33,347 |
|                   [Spain](/spain) |           28,445 |                    28,849 |                     615 |                        404 |                                        1% |                                28,464 |                                 30,810 |
|               [Belgium](/belgium) |            9,841 |                     9,946 |                     868 |                        105 |                                        1% |                                 9,859 |                                 10,201 |
|               [Germany](/germany) |            9,147 |                     9,426 |                     114 |                        279 |                                        3% |                                 9,159 |                                 10,577 |
|       [Netherlands](/netherlands) |            6,166 |                     6,234 |                     361 |                         68 |                                        1% |                                 6,175 |                                  6,471 |
|                 [Sweden](/sweden) |            5,743 |                     6,128 |                     599 |                        385 |                                        7% |                                 5,825 |                                  6,712 |
|               [Romania](/romania) |            2,343 |                     5,379 |                     277 |                      3,036 |                                      130% |                                 3,308 |                                  9,225 |
|               [Ukraine](/ukraine) |            1,717 |                     3,419 |                      78 |                      1,702 |                                       99% |                                 2,204 |                                  5,728 |
|                 [Poland](/poland) |            1,716 |                     2,375 |                      63 |                        659 |                                       38% |                                 1,871 |                                  3,697 |
|             [Portugal](/portugal) |            1,735 |                     2,179 |                     212 |                        444 |                                       26% |                                 1,780 |                                  3,026 |
|       [Switzerland](/switzerland) |            1,981 |                     2,045 |                     238 |                         64 |                                        3% |                                 1,992 |                                  2,272 |
|               [Ireland](/ireland) |            1,763 |                     1,835 |                     374 |                         72 |                                        4% |                                 1,776 |                                  2,039 |
|               [Moldova](/moldova) |              778 |                     1,426 |                     353 |                        648 |                                       83% |                                 1,007 |                                  2,296 |
|                 [Serbia](/serbia) |              573 |                     1,351 |                     194 |                        778 |                                      136% |                                   825 |                                  2,749 |
|             [Bulgaria](/bulgaria) |              383 |                     1,277 |                     182 |                        894 |                                      233% |                                   645 |                                  2,577 |
|               [Belarus](/belarus) |              559 |                       832 |                      88 |                        273 |                                       49% |                                   718 |                                  1,038 |
|               [Austria](/austria) |              718 |                       790 |                      89 |                         72 |                                       10% |                                   734 |                                    941 |
|               [Czechia](/czechia) |              382 |                       700 |                      66 |                        318 |                                       83% |                                   429 |                                  1,401 |
|               [Hungary](/hungary) |              596 |                       697 |                      71 |                        101 |                                       17% |                                   609 |                                    942 |
|               [Denmark](/denmark) |              615 |                       683 |                     118 |                         68 |                                       11% |                                   630 |                                    822 |
|               [Croatia](/croatia) |              145 |                       437 |                     107 |                        292 |                                      202% |                                   220 |                                    882 |
|               [Finland](/finland) |              329 |                       384 |                      70 |                         55 |                                       17% |                                   343 |                                    495 |
|                 [Norway](/norway) |              255 |                       280 |                      52 |                         25 |                                       10% |                                   262 |                                    328 |
|                 [Greece](/greece) |              206 |                       251 |                      23 |                         45 |                                       22% |                                   216 |                                    317 |
|         [Luxembourg](/luxembourg) |              114 |                       178 |                     290 |                         64 |                                       56% |                                   132 |                                    286 |
|             [Slovenia](/slovenia) |              119 |                       154 |                      74 |                         35 |                                       29% |                                   127 |                                    221 |
|           [Lithuania](/lithuania) |               80 |                       100 |                      36 |                         20 |                                       25% |                                    85 |                                    134 |
|               [Estonia](/estonia) |               69 |                        85 |                      64 |                         16 |                                       23% |                                    76 |                                    114 |
|                 [Latvia](/latvia) |               32 |                        43 |                      23 |                         11 |                                       35% |                                    34 |                                     58 |
|             [Slovakia](/slovakia) |               29 |                        38 |                       7 |                          9 |                                       30% |                                    30 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    22 |                                     43 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       35% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        13 |                      27 |                          4 |                                       47% |                                     9 |                                     20 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          317,739 |                   653,828 |                     126 |                    336,089 |                                      106% |                               432,986 |                              1,016,159 |
|                             [Brazil](/brazil) |           92,475 |                   174,453 |                     827 |                     81,978 |                                       89% |                               116,957 |                                272,194 |
|                               [India](/india) |           36,511 |                   121,654 |                      89 |                     85,143 |                                      233% |                                65,493 |                                182,877 |
|                             [Mexico](/mexico) |           46,688 |                    86,158 |                     675 |                     39,470 |                                       85% |                                70,934 |                                127,923 |
|                         [Colombia](/colombia) |           10,105 |                    33,760 |                     671 |                     23,655 |                                      234% |                                18,301 |                                 51,553 |
|                                 [Iran](/iran) |           16,766 |                    31,081 |                     375 |                     14,315 |                                       85% |                                20,298 |                                 44,764 |
|                                 [Peru](/peru) |           19,021 |                    27,705 |                     852 |                      8,684 |                                       46% |                                20,757 |                                 41,926 |
|                 [South Africa](/south-africa) |            8,005 |                    23,465 |                     401 |                     15,460 |                                      193% |                                14,207 |                                 33,806 |
|                             [Russia](/russia) |           13,939 |                    22,761 |                     156 |                      8,822 |                                       63% |                                15,910 |                                 39,615 |
|                       [Argentina](/argentina) |            3,543 |                    17,622 |                     394 |                     14,079 |                                      397% |                                 8,881 |                                 27,816 |
|                       [Indonesia](/indonesia) |            5,131 |                    14,435 |                      53 |                      9,304 |                                      181% |                                 7,664 |                                 28,505 |
|                               [Chile](/chile) |            9,457 |                    13,455 |                     710 |                      3,998 |                                       42% |                                10,086 |                                 23,180 |
|                             [Canada](/canada) |            8,980 |                     9,359 |                     250 |                        379 |                                        4% |                                 9,018 |                                 10,290 |
|                           [Ecuador](/ecuador) |            5,702 |                     7,537 |                     434 |                      1,835 |                                       32% |                                 5,969 |                                 10,727 |
|                           [Bolivia](/bolivia) |            2,977 |                     7,481 |                     650 |                      4,504 |                                      151% |                                 4,443 |                                 12,607 |
|                         [Pakistan](/pakistan) |            5,951 |                     7,284 |                      34 |                      1,333 |                                       22% |                                 6,350 |                                  8,859 |
|                             [Turkey](/turkey) |            5,691 |                     6,662 |                      80 |                        971 |                                       17% |                                 5,788 |                                  8,673 |
|                               [Egypt](/egypt) |            4,805 |                     6,166 |                      61 |                      1,361 |                                       28% |                                 5,056 |                                  7,476 |
|                     [Bangladesh](/bangladesh) |            3,111 |                     5,569 |                      34 |                      2,458 |                                       79% |                                 3,929 |                                  9,456 |
|                 [Saudi Arabia](/saudi-arabia) |            2,866 |                     5,126 |                     150 |                      2,260 |                                       79% |                                 3,533 |                                  8,491 |
|                               [China](/china) |            4,661 |                     4,813 |                       3 |                        152 |                                        3% |                                 4,661 |                                  5,794 |
|                   [Philippines](/philippines) |            1,962 |                     4,793 |                      44 |                      2,831 |                                      144% |                                 2,212 |                                 12,712 |
|                         [Honduras](/honduras) |            1,337 |                     4,688 |                     481 |                      3,351 |                                      251% |                                 2,384 |                                  9,154 |
|                             [Panama](/panama) |            1,421 |                     3,176 |                     748 |                      1,755 |                                      124% |                                 2,085 |                                  5,482 |
|     [Dominican Republic](/dominican-republic) |            1,160 |                     2,628 |                     245 |                      1,468 |                                      127% |                                 1,555 |                                  4,848 |
|                           [Algeria](/algeria) |            1,210 |                     2,371 |                      55 |                      1,161 |                                       96% |                                 1,405 |                                  4,966 |
|                           [Morocco](/morocco) |              353 |                     1,993 |                      55 |                      1,640 |                                      465% |                                   565 |                                  6,188 |
|                             [Israel](/israel) |              512 |                     1,491 |                     175 |                        979 |                                      191% |                                   752 |                                  3,082 |
|                       [Australia](/australia) |              201 |                     1,442 |                      57 |                      1,241 |                                      617% |                                   435 |                                  3,953 |
|                               [Japan](/japan) |            1,008 |                     1,391 |                      11 |                        383 |                                       38% |                                 1,016 |                                  3,289 |
|                           [Nigeria](/nigeria) |              879 |                     1,371 |                       7 |                        492 |                                       56% |                                   955 |                                  2,544 |
|                             [Kuwait](/kuwait) |              447 |                       828 |                     197 |                        381 |                                       85% |                                   495 |                                  1,709 |
| [United Arab Emirates](/united-arab-emirates) |              351 |                       459 |                      47 |                        108 |                                       31% |                                   361 |                                    766 |
|                   [South Korea](/south-korea) |              301 |                       385 |                       8 |                         84 |                                       28% |                                   303 |                                    616 |
|                         [Malaysia](/malaysia) |              125 |                       155 |                       5 |                         30 |                                       24% |                                   136 |                                    174 |
|                                 [Cuba](/cuba) |               87 |                       109 |                      10 |                         22 |                                       25% |                                    92 |                                    144 |
