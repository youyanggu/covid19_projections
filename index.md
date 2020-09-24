We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 22:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1308498742451015680).
* **September 20:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 24 (4am ET):
<p align="center">
  Current Total: <b>201,881</b> deaths | Projected Total: <b>224,800 deaths by Nov 1, 2020</b> (Range: 215-239k)<br>
  Currently Infected: <b>1.0%</b> (1 in 100) | Total Infected: <b>15.9%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 23, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |         <1% |        36% |
|              250,000 |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          201,881 |                   224,766 |                     677 |                     22,885 |                       69 |                                       11% |                               215,351 |                                238,672 |
|                 [New York](/us-ny) |           33,090 |                    33,505 |                   1,722 |                        415 |                       21 |                                        1% |                                33,104 |                                 35,423 |
|                    [Texas](/us-tx) |           15,372 |                    18,048 |                     622 |                      2,676 |                       92 |                                       17% |                                16,649 |                                 20,122 |
|               [California](/us-ca) |           15,291 |                    17,948 |                     454 |                      2,657 |                       67 |                                       17% |                                16,183 |                                 20,830 |
|               [New Jersey](/us-nj) |           16,082 |                    16,294 |                   1,834 |                        212 |                       24 |                                        1% |                                16,090 |                                 16,959 |
|                  [Florida](/us-fl) |           13,618 |                    16,102 |                     750 |                      2,484 |                      116 |                                       18% |                                14,724 |                                 18,055 |
|            [Massachusetts](/us-ma) |            9,347 |                     9,676 |                   1,392 |                        329 |                       47 |                                        4% |                                 9,370 |                                 10,296 |
|                 [Illinois](/us-il) |            8,744 |                     9,400 |                     742 |                        656 |                       52 |                                        8% |                                 8,819 |                                 10,265 |
|             [Pennsylvania](/us-pa) |            8,038 |                     8,938 |                     698 |                        900 |                       70 |                                       11% |                                 8,087 |                                 10,244 |
|                  [Georgia](/us-ga) |            6,769 |                     8,005 |                     754 |                      1,236 |                      116 |                                       18% |                                 7,332 |                                  8,972 |
|                 [Michigan](/us-mi) |            7,013 |                     7,373 |                     738 |                        360 |                       36 |                                        5% |                                 7,059 |                                  7,914 |
|                  [Arizona](/us-az) |            5,525 |                     5,957 |                     818 |                        432 |                       59 |                                        8% |                                 5,619 |                                  6,588 |
|                [Louisiana](/us-la) |            5,407 |                     5,926 |                   1,275 |                        519 |                      112 |                                       10% |                                 5,611 |                                  6,462 |
|                     [Ohio](/us-oh) |            4,687 |                     5,484 |                     469 |                        797 |                       68 |                                       17% |                                 4,894 |                                  6,499 |
|              [Connecticut](/us-ct) |            4,497 |                     4,590 |                   1,287 |                         93 |                       26 |                                        2% |                                 4,505 |                                  4,853 |
|           [North Carolina](/us-nc) |            3,316 |                     4,135 |                     394 |                        819 |                       78 |                                       25% |                                 3,690 |                                  4,830 |
|                 [Maryland](/us-md) |            3,902 |                     4,117 |                     681 |                        215 |                       36 |                                        6% |                                 3,919 |                                  4,507 |
|           [South Carolina](/us-sc) |            3,262 |                     3,914 |                     760 |                        652 |                      127 |                                       20% |                                 3,560 |                                  4,465 |
|                  [Indiana](/us-in) |            3,530 |                     3,882 |                     577 |                        352 |                       52 |                                       10% |                                 3,557 |                                  4,494 |
|                 [Virginia](/us-va) |            3,087 |                     3,785 |                     443 |                        698 |                       82 |                                       23% |                                 3,293 |                                  4,542 |
|              [Mississippi](/us-ms) |            2,870 |                     3,313 |                   1,113 |                        443 |                      149 |                                       15% |                                 3,053 |                                  3,721 |
|                [Tennessee](/us-tn) |            2,277 |                     2,919 |                     427 |                        642 |                       94 |                                       28% |                                 2,593 |                                  3,426 |
|                  [Alabama](/us-al) |            2,488 |                     2,870 |                     585 |                        382 |                       78 |                                       15% |                                 2,635 |                                  3,239 |
|                 [Missouri](/us-mo) |            1,938 |                     2,503 |                     408 |                        565 |                       92 |                                       29% |                                 2,172 |                                  2,993 |
|               [Washington](/us-wa) |            2,081 |                     2,375 |                     312 |                        294 |                       39 |                                       14% |                                 2,128 |                                  2,835 |
|                [Minnesota](/us-mn) |            2,037 |                     2,306 |                     409 |                        269 |                       48 |                                       13% |                                 2,083 |                                  2,666 |
|                 [Colorado](/us-co) |            2,030 |                     2,201 |                     382 |                        171 |                       30 |                                        8% |                                 2,041 |                                  2,526 |
|                   [Nevada](/us-nv) |            1,556 |                     1,810 |                     588 |                        254 |                       82 |                                       16% |                                 1,643 |                                  2,101 |
|                [Wisconsin](/us-wi) |            1,259 |                     1,593 |                     274 |                        334 |                       57 |                                       26% |                                 1,385 |                                  1,936 |
|                     [Iowa](/us-ia) |            1,298 |                     1,580 |                     501 |                        282 |                       90 |                                       22% |                                 1,404 |                                  1,856 |
|                 [Arkansas](/us-ar) |            1,229 |                     1,562 |                     518 |                        333 |                      110 |                                       27% |                                 1,396 |                                  1,804 |
|                 [Kentucky](/us-ky) |            1,124 |                     1,414 |                     317 |                        290 |                       65 |                                       26% |                                 1,235 |                                  1,678 |
|                 [Oklahoma](/us-ok) |              970 |                     1,224 |                     309 |                        254 |                       64 |                                       26% |                                 1,092 |                                  1,441 |
|             [Rhode Island](/us-ri) |            1,102 |                     1,173 |                   1,108 |                         71 |                       67 |                                        6% |                                 1,109 |                                  1,323 |
|               [New Mexico](/us-nm) |              857 |                     1,003 |                     479 |                        146 |                       70 |                                       17% |                                   905 |                                  1,172 |
|              [Puerto Rico](/us-pr) |              617 |                       884 |                     277 |                        267 |                       84 |                                       43% |                                   751 |                                  1,099 |
|                   [Kansas](/us-ks) |              620 |                       839 |                     288 |                        219 |                       75 |                                       35% |                                   712 |                                  1,029 |
|                   [Oregon](/us-or) |              538 |                       687 |                     163 |                        149 |                       35 |                                       28% |                                   598 |                                    835 |
|                 [Delaware](/us-de) |              629 |                       662 |                     680 |                         33 |                       34 |                                        5% |                                   633 |                                    722 |
|     [District of Columbia](/us-dc) |              621 |                       638 |                     904 |                         17 |                       24 |                                        3% |                                   624 |                                    671 |
|                    [Idaho](/us-id) |              454 |                       576 |                     322 |                        122 |                       68 |                                       27% |                                   516 |                                    661 |
|                 [Nebraska](/us-ne) |              462 |                       564 |                     292 |                        102 |                       53 |                                       22% |                                   489 |                                    682 |
|                     [Utah](/us-ut) |              444 |                       530 |                     165 |                         86 |                       27 |                                       19% |                                   477 |                                    598 |
|            [West Virginia](/us-wv) |              322 |                       496 |                     277 |                        174 |                       97 |                                       54% |                                   409 |                                    636 |
|            [New Hampshire](/us-nh) |              438 |                       459 |                     338 |                         21 |                       15 |                                        5% |                                   439 |                                    519 |
|             [North Dakota](/us-nd) |              203 |                       314 |                     412 |                        111 |                      145 |                                       55% |                                   257 |                                    400 |
|             [South Dakota](/us-sd) |              202 |                       275 |                     311 |                         73 |                       82 |                                       36% |                                   217 |                                    374 |
|                  [Montana](/us-mt) |              165 |                       267 |                     250 |                        102 |                       96 |                                       62% |                                   220 |                                    346 |
|                   [Hawaii](/us-hi) |              122 |                       203 |                     144 |                         81 |                       57 |                                       67% |                                   158 |                                    290 |
|                    [Maine](/us-me) |              140 |                       156 |                     116 |                         16 |                       12 |                                       11% |                                   143 |                                    181 |
|                     [Guam](/us-gu) |               37 |                        75 |                     452 |                         38 |                      229 |                                      102% |                                    55 |                                    107 |
|                  [Wyoming](/us-wy) |               50 |                        65 |                     113 |                         15 |                       26 |                                       31% |                                    57 |                                     79 |
|                  [Vermont](/us-vt) |               58 |                        61 |                      98 |                          3 |                        5 |                                        6% |                                    58 |                                     69 |
|                   [Alaska](/us-ak) |               45 |                        60 |                      82 |                         15 |                       21 |                                       34% |                                    52 |                                     72 |
|           [Virgin Islands](/us-vi) |               19 |                        25 |                     240 |                          6 |                       59 |                                       33% |                                    21 |                                     31 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      46 |                          1 |                       10 |                                       27% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          196,268 |                   220,648 |                     372 |                     24,380 |                       41 |                                       12% |                               202,387 |                                273,057 |
| [United Kingdom](/united-kingdom) |           41,951 |                    43,833 |                     649 |                      1,882 |                       28 |                                        4% |                                41,992 |                                 50,712 |
|                   [Spain](/spain) |           31,034 |                    40,539 |                     864 |                      9,505 |                      203 |                                       31% |                                33,971 |                                 56,482 |
|                   [Italy](/italy) |           35,758 |                    36,772 |                     609 |                      1,014 |                       17 |                                        3% |                                35,774 |                                 40,593 |
|                 [France](/france) |           31,447 |                    34,839 |                     520 |                      3,392 |                       51 |                                       11% |                                31,504 |                                 49,839 |
|               [Belgium](/belgium) |            9,959 |                    10,233 |                     893 |                        274 |                       24 |                                        3% |                                 9,989 |                                 11,032 |
|               [Germany](/germany) |            9,423 |                     9,719 |                     117 |                        296 |                        4 |                                        3% |                                 9,435 |                                 10,856 |
|       [Netherlands](/netherlands) |            6,344 |                     6,647 |                     385 |                        303 |                       18 |                                        5% |                                 6,356 |                                  7,439 |
|               [Ukraine](/ukraine) |            3,784 |                     6,214 |                     141 |                      2,430 |                       55 |                                       64% |                                 4,866 |                                  8,095 |
|               [Romania](/romania) |            4,550 |                     6,022 |                     310 |                      1,472 |                       76 |                                       32% |                                 5,227 |                                  7,293 |
|                 [Sweden](/sweden) |            5,876 |                     5,966 |                     583 |                         90 |                        9 |                                        2% |                                 5,882 |                                  6,215 |
|                 [Poland](/poland) |            2,344 |                     3,068 |                      81 |                        724 |                       19 |                                       31% |                                 2,553 |                                  4,051 |
|       [Switzerland](/switzerland) |            2,060 |                     2,234 |                     260 |                        174 |                       20 |                                        8% |                                 2,096 |                                  2,536 |
|             [Portugal](/portugal) |            1,928 |                     2,214 |                     215 |                        286 |                       28 |                                       15% |                                 1,952 |                                  2,677 |
|               [Ireland](/ireland) |            1,794 |                     1,856 |                     378 |                         62 |                       13 |                                        3% |                                 1,798 |                                  2,038 |
|               [Moldova](/moldova) |            1,244 |                     1,660 |                     411 |                        416 |                      103 |                                       33% |                                 1,405 |                                  2,030 |
|               [Czechia](/czechia) |              555 |                     1,102 |                     103 |                        547 |                       51 |                                       99% |                                   831 |                                  1,524 |
|               [Hungary](/hungary) |              702 |                     1,019 |                     104 |                        317 |                       32 |                                       45% |                                   843 |                                  1,300 |
|               [Belarus](/belarus) |              796 |                     1,007 |                     107 |                        211 |                       22 |                                       27% |                                   865 |                                  1,293 |
|             [Bulgaria](/bulgaria) |              779 |                       998 |                     143 |                        219 |                       31 |                                       28% |                                   884 |                                  1,187 |
|               [Austria](/austria) |              777 |                       911 |                     103 |                        134 |                       15 |                                       17% |                                   793 |                                  1,137 |
|                 [Serbia](/serbia) |              744 |                       804 |                     115 |                         60 |                        9 |                                        8% |                                   759 |                                    892 |
|               [Denmark](/denmark) |              643 |                       710 |                     122 |                         67 |                       12 |                                       10% |                                   652 |                                    848 |
|                 [Greece](/greece) |              357 |                       621 |                      58 |                        264 |                       25 |                                       74% |                                   467 |                                    913 |
|               [Finland](/finland) |              343 |                       360 |                      65 |                         17 |                        3 |                                        5% |                                   345 |                                    420 |
|               [Croatia](/croatia) |              257 |                       355 |                      87 |                         98 |                       24 |                                       38% |                                   291 |                                    504 |
|                 [Norway](/norway) |              267 |                       282 |                      52 |                         15 |                        3 |                                        6% |                                   270 |                                    315 |
|             [Slovenia](/slovenia) |              143 |                       166 |                      80 |                         23 |                       11 |                                       16% |                                   147 |                                    210 |
|         [Luxembourg](/luxembourg) |              124 |                       137 |                     223 |                         13 |                       21 |                                       10% |                                   128 |                                    157 |
|           [Lithuania](/lithuania) |               87 |                        93 |                      33 |                          6 |                        2 |                                        7% |                                    88 |                                    103 |
|               [Estonia](/estonia) |               64 |                        68 |                      51 |                          4 |                        3 |                                        7% |                                    66 |                                     74 |
|                   [Malta](/malta) |               25 |                        63 |                     128 |                         38 |                       78 |                                      153% |                                    42 |                                    112 |
|             [Slovakia](/slovakia) |               41 |                        58 |                      11 |                         17 |                        3 |                                       41% |                                    46 |                                     88 |
|                 [Latvia](/latvia) |               36 |                        41 |                      21 |                          5 |                        3 |                                       14% |                                    37 |                                     48 |
|                 [Cyprus](/cyprus) |               22 |                        26 |                      29 |                          4 |                        4 |                                       16% |                                    23 |                                     30 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        3 |                                       12% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          541,116 |                   675,074 |                     130 |                    133,958 |                       26 |                                       25% |                               601,950 |                                786,564 |
|                             [Brazil](/brazil) |          138,105 |                   159,431 |                     755 |                     21,326 |                      101 |                                       15% |                               149,106 |                                176,161 |
|                               [India](/india) |           90,020 |                   134,753 |                      99 |                     44,733 |                       33 |                                       50% |                               108,353 |                                160,433 |
|                             [Mexico](/mexico) |           74,949 |                    89,242 |                     700 |                     14,293 |                      112 |                                       19% |                                84,406 |                                 97,393 |
|                                 [Peru](/peru) |           31,568 |                    33,899 |                   1,043 |                      2,331 |                       72 |                                        7% |                                32,067 |                                 37,115 |
|                                 [Iran](/iran) |           24,840 |                    30,576 |                     369 |                      5,736 |                       69 |                                       23% |                                27,517 |                                 35,101 |
|                         [Colombia](/colombia) |           24,746 |                    29,746 |                     591 |                      5,000 |                       99 |                                       20% |                                27,524 |                                 34,123 |
|                       [Argentina](/argentina) |           14,376 |                    25,597 |                     572 |                     11,221 |                      251 |                                       78% |                                21,143 |                                 34,631 |
|                             [Russia](/russia) |           19,720 |                    24,759 |                     170 |                      5,039 |                       35 |                                       26% |                                20,634 |                                 32,663 |
|                 [South Africa](/south-africa) |           16,206 |                    18,033 |                     308 |                      1,827 |                       31 |                                       11% |                                16,788 |                                 20,481 |
|                       [Indonesia](/indonesia) |            9,977 |                    14,970 |                      55 |                      4,993 |                       18 |                                       50% |                                12,946 |                                 20,098 |
|                               [Chile](/chile) |           12,345 |                    14,291 |                     754 |                      1,946 |                      103 |                                       16% |                                12,559 |                                 18,761 |
|                           [Ecuador](/ecuador) |           11,171 |                    12,334 |                     710 |                      1,163 |                       67 |                                       10% |                                11,269 |                                 14,264 |
|                             [Turkey](/turkey) |            7,711 |                    10,373 |                     124 |                      2,662 |                       32 |                                       35% |                                 8,153 |                                 14,300 |
|                             [Canada](/canada) |            9,294 |                     9,769 |                     261 |                        475 |                       13 |                                        5% |                                 9,330 |                                 11,257 |
|                           [Bolivia](/bolivia) |            7,731 |                     8,770 |                     762 |                      1,039 |                       90 |                                       13% |                                 8,173 |                                  9,424 |
|                   [Philippines](/philippines) |            5,091 |                     7,510 |                      69 |                      2,419 |                       22 |                                       48% |                                 6,109 |                                  9,665 |
|                         [Pakistan](/pakistan) |            6,437 |                     6,749 |                      31 |                        312 |                        1 |                                        5% |                                 6,488 |                                  7,255 |
|                               [Egypt](/egypt) |            5,822 |                     6,532 |                      65 |                        710 |                        7 |                                       12% |                                 5,905 |                                  8,070 |
|                     [Bangladesh](/bangladesh) |            5,044 |                     5,996 |                      37 |                        952 |                        6 |                                       19% |                                 5,412 |                                  7,073 |
|                 [Saudi Arabia](/saudi-arabia) |            4,569 |                     5,277 |                     154 |                        708 |                       21 |                                       16% |                                 4,814 |                                  6,055 |
|                               [China](/china) |            4,738 |                     4,789 |                       3 |                         51 |                        0 |                                        1% |                                 4,738 |                                  5,205 |
|                           [Morocco](/morocco) |            1,918 |                     3,359 |                      92 |                      1,441 |                       40 |                                       75% |                                 2,518 |                                  4,643 |
|                             [Panama](/panama) |            2,291 |                     2,854 |                     672 |                        563 |                      133 |                                       25% |                                 2,675 |                                  3,209 |
|                         [Honduras](/honduras) |            2,222 |                     2,721 |                     279 |                        499 |                       51 |                                       22% |                                 2,368 |                                  3,275 |
|     [Dominican Republic](/dominican-republic) |            2,074 |                     2,594 |                     242 |                        520 |                       48 |                                       25% |                                 2,275 |                                  3,159 |
|                             [Israel](/israel) |            1,325 |                     2,157 |                     253 |                        832 |                       98 |                                       63% |                                 1,608 |                                  3,106 |
|                           [Algeria](/algeria) |            1,698 |                     1,943 |                      45 |                        245 |                        6 |                                       14% |                                 1,750 |                                  2,289 |
|                               [Japan](/japan) |            1,525 |                     1,805 |                      14 |                        280 |                        2 |                                       18% |                                 1,601 |                                  2,145 |
|                           [Nigeria](/nigeria) |            1,102 |                     1,219 |                       6 |                        117 |                        1 |                                       11% |                                 1,131 |                                  1,395 |
|                       [Australia](/australia) |              861 |                       972 |                      39 |                        111 |                        4 |                                       13% |                                   897 |                                  1,088 |
|                             [Kuwait](/kuwait) |              590 |                       740 |                     176 |                        150 |                       36 |                                       25% |                                   610 |                                    938 |
|                   [South Korea](/south-korea) |              393 |                       509 |                      10 |                        116 |                        2 |                                       29% |                                   409 |                                    720 |
| [United Arab Emirates](/united-arab-emirates) |              406 |                       508 |                      52 |                        102 |                       10 |                                       25% |                                   411 |                                    703 |
|                                 [Cuba](/cuba) |              118 |                       157 |                      14 |                         39 |                        3 |                                       33% |                                   128 |                                    216 |
|                         [Malaysia](/malaysia) |              133 |                       141 |                       4 |                          8 |                        0 |                                        6% |                                   135 |                                    150 |
