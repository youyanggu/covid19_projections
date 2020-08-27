We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject.

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

* **August 25:** In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 27 (1pm ET):
<p align="center">
  Current Total: <b>179,700</b> deaths | Projected Total: <b>219,200 deaths by Nov 1, 2020</b> (Range: 204-241k)<br>
  Currently Infected: <b>1.3%</b> (1 in 79) | Total Infected: <b>14.0%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 27, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          7% |        81% |         98% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          5% |        21% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          179,705 |                   219,159 |                     660 |                     39,454 |                      119 |                                       22% |                               204,318 |                                240,217 |
|                 [New York](/us-ny) |           32,921 |                    33,131 |                   1,703 |                        210 |                       11 |                                        1% |                                32,931 |                                 34,157 |
|               [California](/us-ca) |           12,532 |                    18,488 |                     468 |                      5,956 |                      151 |                                       48% |                                15,305 |                                 23,601 |
|                    [Texas](/us-tx) |           12,140 |                    18,400 |                     635 |                      6,260 |                      216 |                                       52% |                                15,551 |                                 22,099 |
|               [New Jersey](/us-nj) |           15,914 |                    16,053 |                   1,807 |                        139 |                       16 |                                        1% |                                15,929 |                                 16,477 |
|                  [Florida](/us-fl) |           10,733 |                    14,329 |                     667 |                      3,596 |                      167 |                                       34% |                                12,561 |                                 16,601 |
|            [Massachusetts](/us-ma) |            8,987 |                     9,678 |                   1,393 |                        691 |                       99 |                                        8% |                                 9,058 |                                 11,037 |
|                 [Illinois](/us-il) |            8,163 |                     9,327 |                     736 |                      1,164 |                       92 |                                       14% |                                 8,299 |                                 11,165 |
|             [Pennsylvania](/us-pa) |            7,613 |                     8,460 |                     661 |                        847 |                       66 |                                       11% |                                 7,662 |                                 10,145 |
|                  [Georgia](/us-ga) |            5,311 |                     7,493 |                     706 |                      2,182 |                      205 |                                       41% |                                 6,400 |                                  9,187 |
|                 [Michigan](/us-mi) |            6,690 |                     7,220 |                     723 |                        530 |                       53 |                                        8% |                                 6,742 |                                  8,164 |
|                  [Arizona](/us-az) |            4,896 |                     5,983 |                     822 |                      1,087 |                      149 |                                       22% |                                 5,358 |                                  6,879 |
|                [Louisiana](/us-la) |            4,851 |                     5,921 |                   1,274 |                      1,070 |                      230 |                                       22% |                                 5,305 |                                  6,899 |
|                     [Ohio](/us-oh) |            4,044 |                     4,915 |                     420 |                        871 |                       74 |                                       22% |                                 4,261 |                                  6,020 |
|              [Connecticut](/us-ct) |            4,463 |                     4,534 |                   1,272 |                         71 |                       20 |                                        2% |                                 4,475 |                                  4,741 |
|                 [Maryland](/us-md) |            3,717 |                     4,164 |                     689 |                        447 |                       74 |                                       12% |                                 3,761 |                                  5,023 |
|                  [Indiana](/us-in) |            3,259 |                     4,098 |                     609 |                        839 |                      125 |                                       26% |                                 3,362 |                                  5,313 |
|           [North Carolina](/us-nc) |            2,606 |                     3,864 |                     368 |                      1,258 |                      120 |                                       48% |                                 3,170 |                                  5,048 |
|           [South Carolina](/us-sc) |            2,573 |                     3,697 |                     718 |                      1,124 |                      218 |                                       44% |                                 3,143 |                                  4,560 |
|              [Mississippi](/us-ms) |            2,373 |                     3,216 |                   1,081 |                        843 |                      283 |                                       36% |                                 2,779 |                                  3,880 |
|                 [Virginia](/us-va) |            2,515 |                     3,142 |                     368 |                        627 |                       73 |                                       25% |                                 2,562 |                                  4,120 |
|                [Tennessee](/us-tn) |            1,648 |                     2,762 |                     404 |                      1,114 |                      163 |                                       68% |                                 2,202 |                                  3,593 |
|                  [Alabama](/us-al) |            2,045 |                     2,702 |                     551 |                        657 |                      134 |                                       32% |                                 2,367 |                                  3,271 |
|               [Washington](/us-wa) |            1,880 |                     2,575 |                     338 |                        695 |                       91 |                                       37% |                                 2,042 |                                  3,426 |
|                [Minnesota](/us-mn) |            1,840 |                     2,306 |                     409 |                        466 |                       83 |                                       25% |                                 1,919 |                                  2,976 |
|                 [Colorado](/us-co) |            1,927 |                     2,139 |                     371 |                        212 |                       37 |                                       11% |                                 1,942 |                                  2,724 |
|                 [Missouri](/us-mo) |            1,481 |                     2,041 |                     333 |                        560 |                       91 |                                       38% |                                 1,711 |                                  2,628 |
|                   [Nevada](/us-nv) |            1,250 |                     1,915 |                     622 |                        665 |                      216 |                                       53% |                                 1,583 |                                  2,382 |
|                [Wisconsin](/us-wi) |            1,100 |                     1,545 |                     265 |                        445 |                       76 |                                       40% |                                 1,272 |                                  2,027 |
|                     [Iowa](/us-ia) |            1,071 |                     1,535 |                     487 |                        464 |                      147 |                                       43% |                                 1,216 |                                  2,064 |
|                 [Kentucky](/us-ky) |              902 |                     1,344 |                     301 |                        442 |                       99 |                                       49% |                                 1,073 |                                  1,790 |
|                 [Oklahoma](/us-ok) |              763 |                     1,283 |                     324 |                        520 |                      131 |                                       68% |                                   993 |                                  1,771 |
|                 [Arkansas](/us-ar) |              732 |                     1,253 |                     415 |                        521 |                      173 |                                       71% |                                   983 |                                  1,650 |
|             [Rhode Island](/us-ri) |            1,041 |                     1,112 |                   1,049 |                         71 |                       67 |                                        7% |                                 1,051 |                                  1,249 |
|               [New Mexico](/us-nm) |              755 |                     1,018 |                     486 |                        263 |                      126 |                                       35% |                                   852 |                                  1,306 |
|              [Puerto Rico](/us-pr) |              404 |                       860 |                     269 |                        456 |                      143 |                                      113% |                                   617 |                                  1,268 |
|                   [Oregon](/us-or) |              433 |                       726 |                     172 |                        293 |                       69 |                                       68% |                                   552 |                                  1,029 |
|                 [Delaware](/us-de) |              604 |                       675 |                     693 |                         71 |                       73 |                                       12% |                                   612 |                                    804 |
|                   [Kansas](/us-ks) |              442 |                       658 |                     226 |                        216 |                       74 |                                       49% |                                   527 |                                    895 |
|     [District of Columbia](/us-dc) |              605 |                       648 |                     918 |                         43 |                       61 |                                        7% |                                   613 |                                    721 |
|                    [Idaho](/us-id) |              337 |                       639 |                     358 |                        302 |                      169 |                                       90% |                                   488 |                                    870 |
|                     [Utah](/us-ut) |              401 |                       619 |                     193 |                        218 |                       68 |                                       54% |                                   495 |                                    831 |
|                 [Nebraska](/us-ne) |              386 |                       524 |                     271 |                        138 |                       71 |                                       36% |                                   425 |                                    696 |
|            [New Hampshire](/us-nh) |              429 |                       469 |                     345 |                         40 |                       29 |                                        9% |                                   432 |                                    552 |
|            [West Virginia](/us-wv) |              190 |                       390 |                     218 |                        200 |                      112 |                                      105% |                                   273 |                                    597 |
|             [North Dakota](/us-nd) |              138 |                       252 |                     331 |                        114 |                      150 |                                       83% |                                   180 |                                    385 |
|             [South Dakota](/us-sd) |              162 |                       236 |                     267 |                         74 |                       84 |                                       46% |                                   180 |                                    320 |
|                  [Montana](/us-mt) |               98 |                       204 |                     191 |                        106 |                       99 |                                      108% |                                   143 |                                    311 |
|                    [Maine](/us-me) |              132 |                       152 |                     113 |                         20 |                       15 |                                       15% |                                   136 |                                    179 |
|                   [Hawaii](/us-hi) |               51 |                       135 |                      95 |                         84 |                       59 |                                      164% |                                    83 |                                    219 |
|                   [Alaska](/us-ak) |               37 |                        84 |                     115 |                         47 |                       64 |                                      127% |                                    59 |                                    130 |
|                  [Vermont](/us-vt) |               58 |                        71 |                     113 |                         13 |                       20 |                                       22% |                                    61 |                                     97 |
|                  [Wyoming](/us-wy) |               37 |                        66 |                     114 |                         29 |                       50 |                                       78% |                                    49 |                                     98 |
|           [Virgin Islands](/us-vi) |               14 |                        54 |                     511 |                         40 |                      377 |                                      283% |                                    33 |                                     87 |
|                     [Guam](/us-gu) |                9 |                        51 |                     310 |                         42 |                      256 |                                      471% |                                    21 |                                     97 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                       17 |                                       48% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,992 |                   202,289 |                     341 |                     14,297 |                      878 |                                        8% |                               191,358 |                                232,037 |
| [United Kingdom](/united-kingdom) |           41,552 |                    42,266 |                     626 |                        714 |                       11 |                                        2% |                                41,575 |                                 44,840 |
|                   [Italy](/italy) |           35,458 |                    36,184 |                     599 |                        726 |                       12 |                                        2% |                                35,489 |                                 39,046 |
|                 [France](/france) |           30,549 |                    31,613 |                     472 |                      1,064 |                       16 |                                        3% |                                30,598 |                                 35,448 |
|                   [Spain](/spain) |           28,971 |                    30,407 |                     648 |                      1,436 |                       31 |                                        5% |                                29,008 |                                 34,933 |
|               [Belgium](/belgium) |            9,879 |                    10,259 |                     896 |                        380 |                       33 |                                        4% |                                 9,911 |                                 11,778 |
|               [Germany](/germany) |            9,285 |                     9,877 |                     119 |                        592 |                        7 |                                        6% |                                 9,326 |                                 11,712 |
|       [Netherlands](/netherlands) |            6,241 |                     6,583 |                     381 |                        342 |                       20 |                                        5% |                                 6,265 |                                  7,896 |
|               [Romania](/romania) |            3,421 |                     6,316 |                     325 |                      2,895 |                      149 |                                       85% |                                 4,589 |                                  9,156 |
|                 [Sweden](/sweden) |            5,817 |                     5,937 |                     580 |                        120 |                       12 |                                        2% |                                 5,836 |                                  6,017 |
|               [Ukraine](/ukraine) |            2,399 |                     4,737 |                     108 |                      2,338 |                       53 |                                       97% |                                 3,227 |                                  7,651 |
|                 [Poland](/poland) |            1,994 |                     2,918 |                      77 |                        924 |                       24 |                                       46% |                                 2,271 |                                  4,133 |
|       [Switzerland](/switzerland) |            2,003 |                     2,114 |                     246 |                        111 |                       13 |                                        6% |                                 2,020 |                                  2,409 |
|             [Portugal](/portugal) |            1,807 |                     2,023 |                     197 |                        216 |                       21 |                                       12% |                                 1,816 |                                  2,514 |
|               [Ireland](/ireland) |            1,777 |                     1,843 |                     376 |                         66 |                       13 |                                        4% |                                 1,786 |                                  2,032 |
|               [Moldova](/moldova) |              967 |                     1,370 |                     339 |                        403 |                      100 |                                       42% |                                 1,124 |                                  1,862 |
|             [Bulgaria](/bulgaria) |              586 |                     1,251 |                     179 |                        665 |                       95 |                                      114% |                                   817 |                                  2,111 |
|                 [Serbia](/serbia) |              707 |                       924 |                     133 |                        217 |                       31 |                                       31% |                                   793 |                                  1,103 |
|               [Belarus](/belarus) |              657 |                       854 |                      90 |                        197 |                       21 |                                       30% |                                   761 |                                    998 |
|               [Austria](/austria) |              733 |                       816 |                      92 |                         83 |                        9 |                                       11% |                                   749 |                                  1,005 |
|               [Denmark](/denmark) |              623 |                       693 |                     119 |                         70 |                       12 |                                       11% |                                   638 |                                    850 |
|               [Hungary](/hungary) |              614 |                       682 |                      70 |                         68 |                        7 |                                       11% |                                   620 |                                    834 |
|               [Czechia](/czechia) |              418 |                       581 |                      55 |                        163 |                       15 |                                       39% |                                   456 |                                    837 |
|                 [Greece](/greece) |              248 |                       453 |                      42 |                        205 |                       19 |                                       83% |                                   314 |                                    779 |
|               [Finland](/finland) |              335 |                       369 |                      67 |                         34 |                        6 |                                       10% |                                   341 |                                    463 |
|                 [Norway](/norway) |              264 |                       306 |                      57 |                         42 |                        8 |                                       16% |                                   275 |                                    392 |
|               [Croatia](/croatia) |              175 |                       263 |                      64 |                         88 |                       21 |                                       50% |                                   205 |                                    375 |
|             [Slovenia](/slovenia) |              133 |                       167 |                      80 |                         34 |                       16 |                                       25% |                                   138 |                                    222 |
|         [Luxembourg](/luxembourg) |              124 |                       156 |                     255 |                         32 |                       53 |                                       26% |                                   135 |                                    196 |
|           [Lithuania](/lithuania) |               85 |                       111 |                      40 |                         26 |                        9 |                                       31% |                                    92 |                                    153 |
|               [Estonia](/estonia) |               64 |                        72 |                      55 |                          8 |                        6 |                                       13% |                                    68 |                                     88 |
|             [Slovakia](/slovakia) |               33 |                        48 |                       9 |                         15 |                        3 |                                       46% |                                    36 |                                     78 |
|                 [Latvia](/latvia) |               33 |                        40 |                      21 |                          7 |                        4 |                                       21% |                                    34 |                                     50 |
|                 [Cyprus](/cyprus) |               20 |                        27 |                      31 |                          7 |                        8 |                                       34% |                                    23 |                                     34 |
|                   [Malta](/malta) |               10 |                        16 |                      33 |                          6 |                       13 |                                       62% |                                    12 |                                     25 |
|               [Iceland](/iceland) |               10 |                        12 |                      37 |                          2 |                        7 |                                       24% |                                    10 |                                     17 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          429,919 |                   644,491 |                     124 |                    214,572 |                    2,776 |                                       50% |                               513,451 |                                862,637 |
|                             [Brazil](/brazil) |          117,665 |                   171,066 |                     811 |                     53,401 |                      253 |                                       45% |                               138,126 |                                225,838 |
|                               [India](/india) |           60,472 |                   113,073 |                      83 |                     52,601 |                       38 |                                       87% |                                81,640 |                                154,790 |
|                             [Mexico](/mexico) |           62,076 |                    88,152 |                     691 |                     26,076 |                      204 |                                       42% |                                75,862 |                                110,239 |
|                                 [Peru](/peru) |           28,001 |                    35,319 |                   1,086 |                      7,318 |                      225 |                                       26% |                                30,273 |                                 43,613 |
|                         [Colombia](/colombia) |           18,184 |                    30,982 |                     615 |                     12,798 |                      254 |                                       70% |                                23,750 |                                 42,540 |
|                                 [Iran](/iran) |           21,020 |                    27,310 |                     329 |                      6,290 |                       76 |                                       30% |                                23,006 |                                 34,528 |
|                             [Russia](/russia) |           16,638 |                    21,778 |                     149 |                      5,140 |                       35 |                                       31% |                                18,174 |                                 28,855 |
|                 [South Africa](/south-africa) |           13,502 |                    21,040 |                     359 |                      7,538 |                      129 |                                       56% |                                16,045 |                                 29,324 |
|                       [Argentina](/argentina) |            7,839 |                    20,274 |                     453 |                     12,435 |                      278 |                                      159% |                                13,252 |                                 31,343 |
|                               [Chile](/chile) |           10,990 |                    13,712 |                     724 |                      2,722 |                      144 |                                       25% |                                11,437 |                                 19,724 |
|                       [Indonesia](/indonesia) |            6,944 |                    11,787 |                      44 |                      4,843 |                       18 |                                       70% |                                 8,694 |                                 17,777 |
|                             [Canada](/canada) |            9,141 |                     9,518 |                     254 |                        377 |                       10 |                                        4% |                                 9,183 |                                 10,356 |
|                           [Bolivia](/bolivia) |            4,726 |                     7,750 |                     673 |                      3,024 |                      263 |                                       64% |                                 5,929 |                                 10,460 |
|                           [Ecuador](/ecuador) |            6,410 |                     7,642 |                     440 |                      1,232 |                       71 |                                       19% |                                 6,543 |                                 10,269 |
|                             [Turkey](/turkey) |            6,183 |                     7,452 |                      89 |                      1,269 |                       15 |                                       21% |                                 6,302 |                                 10,437 |
|                         [Pakistan](/pakistan) |            6,267 |                     6,891 |                      32 |                        624 |                        3 |                                       10% |                                 6,346 |                                  7,826 |
|                   [Philippines](/philippines) |            3,137 |                     6,566 |                      61 |                      3,429 |                       32 |                                      109% |                                 4,095 |                                 11,182 |
|                     [Bangladesh](/bangladesh) |            4,082 |                     5,966 |                      37 |                      1,884 |                       12 |                                       46% |                                 4,827 |                                  8,618 |
|                               [Egypt](/egypt) |            5,317 |                     5,861 |                      58 |                        544 |                        5 |                                       10% |                                 5,389 |                                  6,819 |
|                 [Saudi Arabia](/saudi-arabia) |            3,755 |                     5,374 |                     157 |                      1,619 |                       47 |                                       43% |                                 4,230 |                                  7,013 |
|                               [China](/china) |            4,713 |                     4,805 |                       3 |                         92 |                        0 |                                        2% |                                 4,713 |                                  5,489 |
|                           [Morocco](/morocco) |              984 |                     3,537 |                      97 |                      2,553 |                       70 |                                      259% |                                 1,850 |                                  6,802 |
|                             [Panama](/panama) |            1,932 |                     2,643 |                     622 |                        711 |                      168 |                                       37% |                                 2,218 |                                  3,502 |
|                         [Honduras](/honduras) |            1,747 |                     2,629 |                     270 |                        882 |                       90 |                                       50% |                                 2,037 |                                  3,635 |
|     [Dominican Republic](/dominican-republic) |            1,613 |                     2,565 |                     239 |                        952 |                       89 |                                       59% |                                 1,947 |                                  3,775 |
|                           [Algeria](/algeria) |            1,465 |                     2,164 |                      50 |                        699 |                       16 |                                       48% |                                 1,581 |                                  3,497 |
|                               [Japan](/japan) |            1,230 |                     2,051 |                      16 |                        821 |                        6 |                                       67% |                                 1,375 |                                  3,699 |
|                             [Israel](/israel) |              875 |                     2,009 |                     236 |                      1,134 |                      133 |                                      130% |                                 1,217 |                                  3,368 |
|                       [Australia](/australia) |              572 |                     1,519 |                      60 |                        947 |                       38 |                                      166% |                                   878 |                                  2,840 |
|                           [Nigeria](/nigeria) |            1,010 |                     1,260 |                       6 |                        250 |                        1 |                                       25% |                                 1,058 |                                  1,803 |
|                             [Kuwait](/kuwait) |              521 |                       682 |                     162 |                        161 |                       38 |                                       31% |                                   547 |                                  1,029 |
| [United Arab Emirates](/united-arab-emirates) |              378 |                       463 |                      47 |                         85 |                        9 |                                       23% |                                   383 |                                    674 |
|                   [South Korea](/south-korea) |              313 |                       377 |                       7 |                         64 |                        1 |                                       21% |                                   313 |                                    590 |
|                         [Malaysia](/malaysia) |              125 |                       138 |                       4 |                         13 |                        0 |                                       11% |                                   128 |                                    152 |
|                                 [Cuba](/cuba) |               92 |                       138 |                      12 |                         46 |                        4 |                                       50% |                                   103 |                                    231 |
