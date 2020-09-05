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
### Updated Daily - Last Updated: September 5 (2am ET):
<p align="center">
  Current Total: <b>187,752</b> deaths | Projected Total: <b>220,900 deaths by Nov 1, 2020</b> (Range: 208-240k)<br>
  Currently Infected: <b>1.1%</b> (1 in 90) | Total Infected: <b>14.9%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 5, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |          2% |        98% |         99% |        99% |
|              225,000 |         <1% |        <1% |          4% |        22% |
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
|             *[United States](/us)* |          187,752 |                   220,853 |                     666 |                     33,101 |                      100 |                                       18% |                               208,268 |                                239,374 |
|                 [New York](/us-ny) |           32,982 |                    33,374 |                   1,716 |                        392 |                       20 |                                        1% |                                32,995 |                                 35,613 |
|               [California](/us-ca) |           13,638 |                    18,517 |                     469 |                      4,879 |                      123 |                                       36% |                                15,881 |                                 22,878 |
|                    [Texas](/us-tx) |           13,426 |                    18,137 |                     626 |                      4,711 |                      162 |                                       35% |                                16,030 |                                 20,916 |
|               [New Jersey](/us-nj) |           15,978 |                    16,152 |                   1,818 |                        174 |                       20 |                                        1% |                                15,990 |                                 16,753 |
|                  [Florida](/us-fl) |           11,750 |                    14,623 |                     681 |                      2,873 |                      134 |                                       24% |                                13,107 |                                 16,581 |
|            [Massachusetts](/us-ma) |            9,100 |                     9,595 |                   1,381 |                        495 |                       71 |                                        5% |                                 9,129 |                                 10,580 |
|                 [Illinois](/us-il) |            8,362 |                     9,370 |                     739 |                      1,008 |                       80 |                                       12% |                                 8,474 |                                 10,720 |
|             [Pennsylvania](/us-pa) |            7,735 |                     8,390 |                     655 |                        655 |                       51 |                                        8% |                                 7,766 |                                  9,703 |
|                  [Georgia](/us-ga) |            5,931 |                     8,199 |                     772 |                      2,268 |                      214 |                                       38% |                                 7,032 |                                 10,023 |
|                 [Michigan](/us-mi) |            6,798 |                     7,271 |                     728 |                        473 |                       47 |                                        7% |                                 6,838 |                                  8,073 |
|                  [Arizona](/us-az) |            5,171 |                     5,975 |                     821 |                        804 |                      110 |                                       16% |                                 5,499 |                                  6,671 |
|                [Louisiana](/us-la) |            5,035 |                     5,844 |                   1,257 |                        809 |                      174 |                                       16% |                                 5,369 |                                  6,604 |
|                     [Ohio](/us-oh) |            4,248 |                     5,009 |                     428 |                        761 |                       65 |                                       18% |                                 4,433 |                                  5,937 |
|              [Connecticut](/us-ct) |            4,468 |                     4,549 |                   1,276 |                         81 |                       23 |                                        2% |                                 4,478 |                                  4,799 |
|                 [Maryland](/us-md) |            3,789 |                     4,160 |                     688 |                        371 |                       61 |                                       10% |                                 3,823 |                                  4,860 |
|           [North Carolina](/us-nc) |            2,839 |                     3,953 |                     377 |                      1,114 |                      106 |                                       39% |                                 3,362 |                                  4,965 |
|                  [Indiana](/us-in) |            3,350 |                     3,805 |                     565 |                        455 |                       68 |                                       14% |                                 3,376 |                                  4,718 |
|           [South Carolina](/us-sc) |            2,846 |                     3,760 |                     730 |                        914 |                      178 |                                       32% |                                 3,306 |                                  4,446 |
|                 [Virginia](/us-va) |            2,662 |                     3,339 |                     391 |                        677 |                       79 |                                       25% |                                 2,738 |                                  4,318 |
|              [Mississippi](/us-ms) |            2,558 |                     3,238 |                   1,088 |                        680 |                      229 |                                       27% |                                 2,868 |                                  3,764 |
|                  [Alabama](/us-al) |            2,266 |                     2,920 |                     595 |                        654 |                      133 |                                       29% |                                 2,568 |                                  3,468 |
|                [Tennessee](/us-tn) |            1,837 |                     2,747 |                     402 |                        910 |                      133 |                                       50% |                                 2,313 |                                  3,440 |
|               [Washington](/us-wa) |            1,953 |                     2,356 |                     309 |                        403 |                       53 |                                       21% |                                 2,044 |                                  2,887 |
|                [Minnesota](/us-mn) |            1,899 |                     2,289 |                     406 |                        390 |                       69 |                                       21% |                                 1,964 |                                  2,829 |
|                 [Missouri](/us-mo) |            1,607 |                     2,208 |                     360 |                        601 |                       98 |                                       37% |                                 1,862 |                                  2,803 |
|                 [Colorado](/us-co) |            1,955 |                     2,126 |                     369 |                        171 |                       30 |                                        9% |                                 1,966 |                                  2,605 |
|                   [Nevada](/us-nv) |            1,375 |                     1,898 |                     616 |                        523 |                      170 |                                       38% |                                 1,648 |                                  2,255 |
|                     [Iowa](/us-ia) |            1,158 |                     1,743 |                     552 |                        585 |                      185 |                                       50% |                                 1,356 |                                  2,541 |
|                [Wisconsin](/us-wi) |            1,153 |                     1,538 |                     264 |                        385 |                       66 |                                       33% |                                 1,307 |                                  1,927 |
|                 [Arkansas](/us-ar) |              873 |                     1,411 |                     467 |                        538 |                      178 |                                       62% |                                 1,146 |                                  1,804 |
|                 [Kentucky](/us-ky) |              987 |                     1,410 |                     316 |                        423 |                       95 |                                       43% |                                 1,158 |                                  1,804 |
|                 [Oklahoma](/us-ok) |              846 |                     1,294 |                     327 |                        448 |                      113 |                                       53% |                                 1,053 |                                  1,688 |
|             [Rhode Island](/us-ri) |            1,055 |                     1,128 |                   1,065 |                         73 |                       69 |                                        7% |                                 1,063 |                                  1,283 |
|               [New Mexico](/us-nm) |              794 |                       952 |                     454 |                        158 |                       75 |                                       20% |                                   852 |                                  1,111 |
|              [Puerto Rico](/us-pr) |              455 |                       792 |                     248 |                        337 |                      106 |                                       74% |                                   617 |                                  1,074 |
|                   [Oregon](/us-or) |              475 |                       729 |                     173 |                        254 |                       60 |                                       54% |                                   584 |                                    964 |
|                   [Kansas](/us-ks) |              478 |                       679 |                     233 |                        201 |                       69 |                                       42% |                                   559 |                                    884 |
|                 [Delaware](/us-de) |              606 |                       650 |                     667 |                         44 |                       45 |                                        7% |                                   611 |                                    737 |
|     [District of Columbia](/us-dc) |              611 |                       639 |                     906 |                         28 |                       40 |                                        5% |                                   615 |                                    694 |
|                    [Idaho](/us-id) |              382 |                       612 |                     343 |                        230 |                      129 |                                       60% |                                   499 |                                    785 |
|                     [Utah](/us-ut) |              419 |                       582 |                     182 |                        163 |                       51 |                                       39% |                                   491 |                                    731 |
|                 [Nebraska](/us-ne) |              404 |                       526 |                     272 |                        122 |                       63 |                                       30% |                                   437 |                                    669 |
|            [West Virginia](/us-wv) |              245 |                       472 |                     264 |                        227 |                      127 |                                       93% |                                   353 |                                    672 |
|            [New Hampshire](/us-nh) |              432 |                       459 |                     338 |                         27 |                       20 |                                        6% |                                   434 |                                    525 |
|                   [Hawaii](/us-hi) |               81 |                       261 |                     184 |                        180 |                      127 |                                      222% |                                   161 |                                    438 |
|             [South Dakota](/us-sd) |              170 |                       256 |                     289 |                         86 |                       97 |                                       50% |                                   181 |                                    441 |
|             [North Dakota](/us-nd) |              150 |                       244 |                     320 |                         94 |                      123 |                                       63% |                                   188 |                                    334 |
|                  [Montana](/us-mt) |              114 |                       213 |                     199 |                         99 |                       92 |                                       87% |                                   157 |                                    306 |
|                    [Maine](/us-me) |              134 |                       151 |                     112 |                         17 |                       13 |                                       13% |                                   137 |                                    175 |
|                   [Alaska](/us-ak) |               40 |                        74 |                     101 |                         34 |                       47 |                                       85% |                                    56 |                                    109 |
|                  [Wyoming](/us-wy) |               42 |                        72 |                     124 |                         30 |                       52 |                                       71% |                                    56 |                                    104 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     106 |                          8 |                       13 |                                       14% |                                    60 |                                     80 |
|                     [Guam](/us-gu) |               14 |                        52 |                     315 |                         38 |                      231 |                                      273% |                                    32 |                                     89 |
|           [Virgin Islands](/us-vi) |               16 |                        39 |                     370 |                         23 |                      217 |                                      142% |                                    27 |                                     57 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      52 |                          1 |                       15 |                                       42% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,116 |                   204,491 |                     345 |                     14,375 |                       24 |                                        8% |                               193,356 |                                238,534 |
| [United Kingdom](/united-kingdom) |           41,626 |                    42,101 |                     623 |                        475 |                        7 |                                        1% |                                41,635 |                                 44,221 |
|                   [Italy](/italy) |           35,518 |                    36,124 |                     598 |                        606 |                       10 |                                        2% |                                35,533 |                                 38,822 |
|                 [France](/france) |           30,730 |                    32,186 |                     480 |                      1,456 |                       22 |                                        5% |                                30,761 |                                 39,865 |
|                   [Spain](/spain) |           29,418 |                    31,829 |                     678 |                      2,411 |                       51 |                                        8% |                                29,449 |                                 40,888 |
|               [Belgium](/belgium) |            9,901 |                    10,069 |                     879 |                        168 |                       15 |                                        2% |                                 9,919 |                                 10,681 |
|               [Germany](/germany) |            9,327 |                     9,713 |                     117 |                        386 |                        5 |                                        4% |                                 9,343 |                                 11,012 |
|       [Netherlands](/netherlands) |            6,270 |                     6,462 |                     374 |                        192 |                       11 |                                        3% |                                 6,284 |                                  7,150 |
|               [Romania](/romania) |            3,812 |                     6,103 |                     314 |                      2,291 |                      118 |                                       60% |                                 4,759 |                                  8,136 |
|               [Ukraine](/ukraine) |            2,812 |                     5,889 |                     134 |                      3,077 |                       70 |                                      109% |                                 3,945 |                                  9,022 |
|                 [Sweden](/sweden) |            5,835 |                     5,881 |                     575 |                         46 |                        4 |                                        1% |                                 5,839 |                                  6,034 |
|                 [Poland](/poland) |            2,100 |                     2,848 |                      75 |                        748 |                       20 |                                       36% |                                 2,325 |                                  3,811 |
|       [Switzerland](/switzerland) |            2,013 |                     2,083 |                     242 |                         70 |                        8 |                                        3% |                                 2,025 |                                  2,276 |
|             [Portugal](/portugal) |            1,833 |                     1,984 |                     193 |                        151 |                       15 |                                        8% |                                 1,839 |                                  2,367 |
|               [Ireland](/ireland) |            1,777 |                     1,818 |                     371 |                         41 |                        8 |                                        2% |                                 1,784 |                                  1,942 |
|               [Moldova](/moldova) |            1,047 |                     1,505 |                     372 |                        458 |                      113 |                                       44% |                                 1,214 |                                  1,987 |
|             [Bulgaria](/bulgaria) |              665 |                     1,249 |                     178 |                        584 |                       83 |                                       88% |                                   897 |                                  1,831 |
|               [Belarus](/belarus) |              701 |                       991 |                     105 |                        290 |                       31 |                                       41% |                                   790 |                                  1,410 |
|                 [Serbia](/serbia) |              721 |                       886 |                     127 |                        165 |                       24 |                                       23% |                                   784 |                                  1,044 |
|               [Austria](/austria) |              735 |                       783 |                      88 |                         48 |                        5 |                                        7% |                                   744 |                                    902 |
|               [Hungary](/hungary) |              621 |                       672 |                      69 |                         51 |                        5 |                                        8% |                                   625 |                                    815 |
|               [Denmark](/denmark) |              627 |                       666 |                     115 |                         39 |                        7 |                                        6% |                                   635 |                                    774 |
|               [Czechia](/czechia) |              429 |                       532 |                      50 |                        103 |                       10 |                                       24% |                                   451 |                                    697 |
|                 [Greece](/greece) |              279 |                       496 |                      46 |                        217 |                       20 |                                       78% |                                   362 |                                    765 |
|               [Finland](/finland) |              336 |                       355 |                      64 |                         19 |                        3 |                                        6% |                                   339 |                                    410 |
|               [Croatia](/croatia) |              195 |                       323 |                      79 |                        128 |                       31 |                                       66% |                                   244 |                                    480 |
|                 [Norway](/norway) |              264 |                       286 |                      53 |                         22 |                        4 |                                        8% |                                   269 |                                    340 |
|             [Slovenia](/slovenia) |              134 |                       154 |                      74 |                         20 |                       10 |                                       15% |                                   137 |                                    192 |
|         [Luxembourg](/luxembourg) |              124 |                       146 |                     237 |                         22 |                       35 |                                       17% |                                   131 |                                    176 |
|           [Lithuania](/lithuania) |               86 |                       100 |                      36 |                         14 |                        5 |                                       16% |                                    89 |                                    121 |
|               [Estonia](/estonia) |               64 |                        70 |                      53 |                          6 |                        5 |                                       10% |                                    67 |                                     77 |
|             [Slovakia](/slovakia) |               37 |                        69 |                      13 |                         32 |                        6 |                                       86% |                                    46 |                                    121 |
|                 [Latvia](/latvia) |               35 |                        45 |                      23 |                         10 |                        5 |                                       27% |                                    37 |                                     58 |
|                   [Malta](/malta) |               13 |                        33 |                      66 |                         20 |                       40 |                                      152% |                                    21 |                                     56 |
|                 [Cyprus](/cyprus) |               21 |                        28 |                      32 |                          7 |                        8 |                                       35% |                                    24 |                                     36 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        6 |                                       19% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          466,012 |                   655,975 |                     126 |                    189,963 |                       37 |                                       41% |                               544,160 |                                846,880 |
|                             [Brazil](/brazil) |          125,502 |                   166,269 |                     788 |                     40,767 |                      193 |                                       32% |                               143,064 |                                200,882 |
|                               [India](/india) |           69,561 |                   127,161 |                      93 |                     57,600 |                       42 |                                       83% |                                93,138 |                                187,505 |
|                             [Mexico](/mexico) |           66,851 |                    91,175 |                     715 |                     24,324 |                      191 |                                       36% |                                81,652 |                                106,317 |
|                                 [Peru](/peru) |           29,405 |                    34,656 |                   1,066 |                      5,251 |                      162 |                                       18% |                                30,929 |                                 40,905 |
|                         [Colombia](/colombia) |           20,618 |                    30,506 |                     606 |                      9,888 |                      196 |                                       48% |                                24,881 |                                 39,111 |
|                                 [Iran](/iran) |           22,044 |                    27,119 |                     327 |                      5,075 |                       61 |                                       23% |                                23,584 |                                 32,887 |
|                             [Russia](/russia) |           17,598 |                    21,844 |                     150 |                      4,246 |                       29 |                                       24% |                                18,534 |                                 30,269 |
|                       [Argentina](/argentina) |            9,623 |                    19,723 |                     440 |                     10,100 |                      226 |                                      105% |                                14,198 |                                 27,013 |
|                 [South Africa](/south-africa) |           14,678 |                    19,051 |                     325 |                      4,373 |                       75 |                                       30% |                                15,861 |                                 21,731 |
|                               [Chile](/chile) |           11,494 |                    14,545 |                     767 |                      3,051 |                      161 |                                       27% |                                11,963 |                                 21,455 |
|                       [Indonesia](/indonesia) |            7,832 |                    12,706 |                      47 |                      4,874 |                       18 |                                       62% |                                 9,684 |                                 19,417 |
|                             [Canada](/canada) |            9,190 |                     9,449 |                     253 |                        259 |                        7 |                                        3% |                                 9,220 |                                 10,112 |
|                             [Turkey](/turkey) |            6,564 |                     8,051 |                      96 |                      1,487 |                       18 |                                       23% |                                 6,721 |                                 10,768 |
|                           [Bolivia](/bolivia) |            5,343 |                     8,041 |                     698 |                      2,698 |                      234 |                                       50% |                                 6,453 |                                 10,304 |
|                           [Ecuador](/ecuador) |            6,674 |                     7,666 |                     441 |                        992 |                       57 |                                       15% |                                 6,757 |                                  9,874 |
|                   [Philippines](/philippines) |            3,737 |                     7,041 |                      65 |                      3,304 |                       31 |                                       88% |                                 4,839 |                                 10,544 |
|                         [Pakistan](/pakistan) |            6,340 |                     6,709 |                      31 |                        369 |                        2 |                                        6% |                                 6,364 |                                  7,578 |
|                     [Bangladesh](/bangladesh) |            4,412 |                     6,189 |                      38 |                      1,777 |                       11 |                                       40% |                                 4,988 |                                  8,388 |
|                               [Egypt](/egypt) |            5,495 |                     6,127 |                      61 |                        632 |                        6 |                                       12% |                                 5,537 |                                  8,407 |
|                 [Saudi Arabia](/saudi-arabia) |            4,015 |                     5,246 |                     153 |                      1,231 |                       36 |                                       31% |                                 4,401 |                                  6,683 |
|                               [China](/china) |            4,728 |                     4,803 |                       3 |                         75 |                        0 |                                        2% |                                 4,728 |                                  5,394 |
|                           [Morocco](/morocco) |            1,292 |                     3,439 |                      94 |                      2,147 |                       59 |                                      166% |                                 2,007 |                                  5,498 |
|                         [Honduras](/honduras) |            1,984 |                     2,899 |                     297 |                        915 |                       94 |                                       46% |                                 2,298 |                                  3,971 |
|     [Dominican Republic](/dominican-republic) |            1,801 |                     2,742 |                     255 |                        941 |                       88 |                                       52% |                                 2,132 |                                  3,765 |
|                             [Panama](/panama) |            2,063 |                     2,548 |                     600 |                        485 |                      114 |                                       24% |                                 2,267 |                                  3,116 |
|                           [Algeria](/algeria) |            1,539 |                     2,101 |                      49 |                        562 |                       13 |                                       37% |                                 1,635 |                                  3,080 |
|                               [Japan](/japan) |            1,352 |                     2,101 |                      17 |                        749 |                        6 |                                       55% |                                 1,540 |                                  3,484 |
|                             [Israel](/israel) |              993 |                     1,791 |                     210 |                        798 |                       94 |                                       80% |                                 1,241 |                                  2,786 |
|                           [Nigeria](/nigeria) |            1,051 |                     1,270 |                       6 |                        219 |                        1 |                                       21% |                                 1,099 |                                  1,577 |
|                       [Australia](/australia) |              748 |                     1,184 |                      47 |                        436 |                       17 |                                       58% |                                   918 |                                  1,522 |
|                             [Kuwait](/kuwait) |              537 |                       652 |                     155 |                        115 |                       27 |                                       21% |                                   556 |                                    884 |
| [United Arab Emirates](/united-arab-emirates) |              387 |                       451 |                      46 |                         64 |                        7 |                                       17% |                                   391 |                                    612 |
|                   [South Korea](/south-korea) |              333 |                       433 |                       8 |                        100 |                        2 |                                       30% |                                   337 |                                    658 |
|                                 [Cuba](/cuba) |              100 |                       146 |                      13 |                         46 |                        4 |                                       46% |                                   112 |                                    230 |
|                         [Malaysia](/malaysia) |              128 |                       140 |                       4 |                         12 |                        0 |                                        9% |                                   131 |                                    153 |
