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
### Updated Daily - Last Updated: September 6 (2am ET):
<p align="center">
  Current Total: <b>188,535</b> deaths | Projected Total: <b>220,800 deaths by Nov 1, 2020</b> (Range: 208-239k)<br>
  Currently Infected: <b>1.1%</b> (1 in 90) | Total Infected: <b>15.0%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 6, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        99% |         99% |        99% |
|              225,000 |         <1% |        <1% |          3% |        22% |
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
|             *[United States](/us)* |          188,535 |                   220,811 |                     665 |                     32,276 |                       97 |                                       17% |                               208,550 |                                238,797 |
|                 [New York](/us-ny) |           32,987 |                    33,370 |                   1,715 |                        383 |                       20 |                                        1% |                                33,000 |                                 35,557 |
|               [California](/us-ca) |           13,709 |                    18,367 |                     465 |                      4,658 |                      118 |                                       34% |                                15,819 |                                 22,504 |
|                    [Texas](/us-tx) |           13,576 |                    18,189 |                     627 |                      4,613 |                      159 |                                       34% |                                16,146 |                                 20,892 |
|               [New Jersey](/us-nj) |           15,985 |                    16,156 |                   1,819 |                        171 |                       19 |                                        1% |                                15,997 |                                 16,746 |
|                  [Florida](/us-fl) |           11,811 |                    14,563 |                     678 |                      2,752 |                      128 |                                       23% |                                13,102 |                                 16,432 |
|            [Massachusetts](/us-ma) |            9,116 |                     9,604 |                   1,382 |                        488 |                       70 |                                        5% |                                 9,144 |                                 10,567 |
|                 [Illinois](/us-il) |            8,385 |                     9,379 |                     740 |                        994 |                       78 |                                       12% |                                 8,494 |                                 10,681 |
|             [Pennsylvania](/us-pa) |            7,750 |                     8,391 |                     655 |                        641 |                       50 |                                        8% |                                 7,780 |                                  9,675 |
|                  [Georgia](/us-ga) |            5,977 |                     8,167 |                     769 |                      2,190 |                      206 |                                       37% |                                 7,050 |                                  9,926 |
|                 [Michigan](/us-mi) |            6,806 |                     7,264 |                     727 |                        458 |                       46 |                                        7% |                                 6,844 |                                  8,039 |
|                  [Arizona](/us-az) |            5,207 |                     5,987 |                     823 |                        780 |                      107 |                                       15% |                                 5,518 |                                  6,680 |
|                [Louisiana](/us-la) |            5,035 |                     5,806 |                   1,249 |                        771 |                      166 |                                       15% |                                 5,350 |                                  6,548 |
|                     [Ohio](/us-oh) |            4,256 |                     4,996 |                     427 |                        740 |                       63 |                                       17% |                                 4,437 |                                  5,900 |
|              [Connecticut](/us-ct) |            4,468 |                     4,546 |                   1,275 |                         78 |                       22 |                                        2% |                                 4,478 |                                  4,791 |
|                 [Maryland](/us-md) |            3,796 |                     4,160 |                     688 |                        364 |                       60 |                                       10% |                                 3,829 |                                  4,847 |
|           [North Carolina](/us-nc) |            2,889 |                     4,027 |                     384 |                      1,138 |                      109 |                                       39% |                                 3,425 |                                  5,033 |
|                  [Indiana](/us-in) |            3,362 |                     3,807 |                     565 |                        445 |                       66 |                                       13% |                                 3,388 |                                  4,704 |
|           [South Carolina](/us-sc) |            2,877 |                     3,778 |                     734 |                        901 |                      175 |                                       31% |                                 3,337 |                                  4,449 |
|                 [Virginia](/us-va) |            2,677 |                     3,346 |                     392 |                        669 |                       78 |                                       25% |                                 2,752 |                                  4,303 |
|              [Mississippi](/us-ms) |            2,569 |                     3,224 |                   1,083 |                        655 |                      220 |                                       25% |                                 2,863 |                                  3,740 |
|                  [Alabama](/us-al) |            2,275 |                     2,902 |                     592 |                        627 |                      128 |                                       28% |                                 2,564 |                                  3,426 |
|                [Tennessee](/us-tn) |            1,862 |                     2,761 |                     404 |                        899 |                      132 |                                       48% |                                 2,339 |                                  3,441 |
|               [Washington](/us-wa) |            1,953 |                     2,340 |                     307 |                        387 |                       51 |                                       20% |                                 2,040 |                                  2,849 |
|                 [Missouri](/us-mo) |            1,668 |                     2,337 |                     381 |                        669 |                      109 |                                       40% |                                 1,949 |                                  2,977 |
|                [Minnesota](/us-mn) |            1,903 |                     2,281 |                     405 |                        378 |                       67 |                                       20% |                                 1,965 |                                  2,810 |
|                 [Colorado](/us-co) |            1,971 |                     2,145 |                     373 |                        174 |                       30 |                                        9% |                                 1,982 |                                  2,626 |
|                   [Nevada](/us-nv) |            1,388 |                     1,897 |                     616 |                        509 |                      165 |                                       37% |                                 1,653 |                                  2,241 |
|                     [Iowa](/us-ia) |            1,164 |                     1,724 |                     546 |                        560 |                      178 |                                       48% |                                 1,352 |                                  2,469 |
|                [Wisconsin](/us-wi) |            1,168 |                     1,560 |                     268 |                        392 |                       67 |                                       34% |                                 1,326 |                                  1,958 |
|                 [Kentucky](/us-ky) |              993 |                     1,407 |                     315 |                        414 |                       93 |                                       42% |                                 1,161 |                                  1,788 |
|                 [Arkansas](/us-ar) |              882 |                     1,398 |                     463 |                        516 |                      171 |                                       58% |                                 1,143 |                                  1,772 |
|                 [Oklahoma](/us-ok) |              850 |                     1,279 |                     323 |                        429 |                      108 |                                       50% |                                 1,049 |                                  1,658 |
|             [Rhode Island](/us-ri) |            1,055 |                     1,127 |                   1,063 |                         72 |                       68 |                                        7% |                                 1,063 |                                  1,279 |
|               [New Mexico](/us-nm) |              800 |                       957 |                     456 |                        157 |                       75 |                                       20% |                                   857 |                                  1,113 |
|              [Puerto Rico](/us-pr) |              464 |                       803 |                     252 |                        339 |                      106 |                                       73% |                                   627 |                                  1,083 |
|                   [Oregon](/us-or) |              480 |                       731 |                     173 |                        251 |                       60 |                                       52% |                                   587 |                                    963 |
|                   [Kansas](/us-ks) |              480 |                       676 |                     232 |                        196 |                       67 |                                       41% |                                   559 |                                    878 |
|                 [Delaware](/us-de) |              608 |                       652 |                     669 |                         44 |                       45 |                                        7% |                                   613 |                                    737 |
|     [District of Columbia](/us-dc) |              611 |                       638 |                     905 |                         27 |                       39 |                                        4% |                                   615 |                                    692 |
|                    [Idaho](/us-id) |              384 |                       600 |                     336 |                        216 |                      121 |                                       56% |                                   493 |                                    755 |
|                     [Utah](/us-ut) |              420 |                       578 |                     180 |                        158 |                       49 |                                       38% |                                   489 |                                    720 |
|                 [Nebraska](/us-ne) |              404 |                       522 |                     270 |                        118 |                       61 |                                       29% |                                   435 |                                    662 |
|            [West Virginia](/us-wv) |              246 |                       463 |                     258 |                        217 |                      121 |                                       88% |                                   349 |                                    654 |
|            [New Hampshire](/us-nh) |              432 |                       458 |                     337 |                         26 |                       19 |                                        6% |                                   434 |                                    523 |
|             [South Dakota](/us-sd) |              173 |                       265 |                     299 |                         92 |                      104 |                                       53% |                                   184 |                                    460 |
|             [North Dakota](/us-nd) |              155 |                       262 |                     343 |                        107 |                      140 |                                       69% |                                   199 |                                    375 |
|                   [Hawaii](/us-hi) |               84 |                       256 |                     181 |                        172 |                      122 |                                      205% |                                   163 |                                    415 |
|                  [Montana](/us-mt) |              116 |                       214 |                     200 |                         98 |                       92 |                                       84% |                                   159 |                                    306 |
|                    [Maine](/us-me) |              134 |                       151 |                     112 |                         17 |                       12 |                                       12% |                                   137 |                                    174 |
|                   [Alaska](/us-ak) |               42 |                        80 |                     110 |                         38 |                       53 |                                       92% |                                    60 |                                    117 |
|                  [Wyoming](/us-wy) |               42 |                        70 |                     120 |                         28 |                       48 |                                       66% |                                    55 |                                     98 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     106 |                          8 |                       13 |                                       14% |                                    60 |                                     80 |
|                     [Guam](/us-gu) |               14 |                        45 |                     270 |                         31 |                      186 |                                      220% |                                    29 |                                     72 |
|           [Virgin Islands](/us-vi) |               16 |                        36 |                     345 |                         20 |                      193 |                                      126% |                                    26 |                                     52 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      51 |                          1 |                       15 |                                       42% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,301 |                   204,313 |                     344 |                     14,012 |                       24 |                                        7% |                               193,519 |                                237,427 |
| [United Kingdom](/united-kingdom) |           41,638 |                    42,105 |                     623 |                        467 |                        7 |                                        1% |                                41,647 |                                 44,197 |
|                   [Italy](/italy) |           35,534 |                    36,142 |                     599 |                        608 |                       10 |                                        2% |                                35,549 |                                 38,831 |
|                 [France](/france) |           30,730 |                    32,135 |                     480 |                      1,405 |                       21 |                                        5% |                                30,760 |                                 39,545 |
|                   [Spain](/spain) |           29,418 |                    31,671 |                     675 |                      2,253 |                       48 |                                        8% |                                29,448 |                                 40,411 |
|               [Belgium](/belgium) |            9,906 |                    10,071 |                     879 |                        165 |                       14 |                                        2% |                                 9,923 |                                 10,680 |
|               [Germany](/germany) |            9,329 |                     9,699 |                     117 |                        370 |                        4 |                                        4% |                                 9,345 |                                 10,955 |
|       [Netherlands](/netherlands) |            6,275 |                     6,467 |                     374 |                        192 |                       11 |                                        3% |                                 6,289 |                                  7,149 |
|               [Romania](/romania) |            3,850 |                     6,041 |                     311 |                      2,191 |                      113 |                                       57% |                                 4,763 |                                  8,034 |
|               [Ukraine](/ukraine) |            2,863 |                     5,975 |                     136 |                      3,112 |                       71 |                                      109% |                                 4,030 |                                  9,066 |
|                 [Sweden](/sweden) |            5,835 |                     5,879 |                     575 |                         44 |                        4 |                                        1% |                                 5,839 |                                  6,029 |
|                 [Poland](/poland) |            2,113 |                     2,857 |                      75 |                        744 |                       20 |                                       35% |                                 2,338 |                                  3,796 |
|       [Switzerland](/switzerland) |            2,013 |                     2,079 |                     242 |                         66 |                        8 |                                        3% |                                 2,025 |                                  2,257 |
|             [Portugal](/portugal) |            1,838 |                     1,992 |                     194 |                        154 |                       15 |                                        8% |                                 1,844 |                                  2,376 |
|               [Ireland](/ireland) |            1,777 |                     1,817 |                     371 |                         40 |                        8 |                                        2% |                                 1,784 |                                  1,939 |
|               [Moldova](/moldova) |            1,063 |                     1,555 |                     385 |                        492 |                      122 |                                       46% |                                 1,252 |                                  2,035 |
|             [Bulgaria](/bulgaria) |              671 |                     1,202 |                     172 |                        531 |                       76 |                                       79% |                                   882 |                                  1,716 |
|               [Belarus](/belarus) |              705 |                       988 |                     105 |                        283 |                       30 |                                       40% |                                   789 |                                  1,396 |
|                 [Serbia](/serbia) |              723 |                       883 |                     127 |                        160 |                       23 |                                       22% |                                   784 |                                  1,042 |
|               [Austria](/austria) |              735 |                       782 |                      88 |                         47 |                        5 |                                        6% |                                   743 |                                    897 |
|               [Hungary](/hungary) |              624 |                       679 |                      69 |                         55 |                        6 |                                        9% |                                   628 |                                    827 |
|               [Denmark](/denmark) |              627 |                       665 |                     115 |                         38 |                        7 |                                        6% |                                   635 |                                    770 |
|               [Czechia](/czechia) |              431 |                       535 |                      50 |                        104 |                       10 |                                       24% |                                   453 |                                    698 |
|                 [Greece](/greece) |              280 |                       471 |                      44 |                        191 |                       18 |                                       68% |                                   351 |                                    708 |
|               [Finland](/finland) |              336 |                       354 |                      64 |                         18 |                        3 |                                        5% |                                   339 |                                    409 |
|               [Croatia](/croatia) |              197 |                       325 |                      80 |                        128 |                       31 |                                       65% |                                   246 |                                    479 |
|                 [Norway](/norway) |              264 |                       285 |                      53 |                         21 |                        4 |                                        8% |                                   268 |                                    336 |
|             [Slovenia](/slovenia) |              135 |                       156 |                      75 |                         21 |                       10 |                                       16% |                                   138 |                                    194 |
|         [Luxembourg](/luxembourg) |              124 |                       145 |                     236 |                         21 |                       34 |                                       17% |                                   130 |                                    176 |
|           [Lithuania](/lithuania) |               86 |                        98 |                      35 |                         12 |                        4 |                                       14% |                                    89 |                                    119 |
|               [Estonia](/estonia) |               64 |                        70 |                      53 |                          6 |                        4 |                                        9% |                                    67 |                                     76 |
|             [Slovakia](/slovakia) |               37 |                        67 |                      12 |                         30 |                        5 |                                       80% |                                    46 |                                    109 |
|                 [Latvia](/latvia) |               35 |                        44 |                      23 |                          9 |                        5 |                                       26% |                                    37 |                                     57 |
|                   [Malta](/malta) |               14 |                        39 |                      79 |                         25 |                       51 |                                      179% |                                    24 |                                     68 |
|                 [Cyprus](/cyprus) |               21 |                        28 |                      32 |                          7 |                        8 |                                       33% |                                    24 |                                     35 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        5 |                                       18% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          469,728 |                   654,912 |                     126 |                    185,184 |                       36 |                                       39% |                               544,694 |                                841,662 |
|                             [Brazil](/brazil) |          126,203 |                   165,230 |                     783 |                     39,027 |                      185 |                                       31% |                               142,508 |                                198,694 |
|                               [India](/india) |           70,626 |                   127,727 |                      93 |                     57,101 |                       42 |                                       81% |                                94,136 |                                186,711 |
|                             [Mexico](/mexico) |           67,326 |                    91,018 |                     713 |                     23,692 |                      186 |                                       35% |                                81,696 |                                105,826 |
|                                 [Peru](/peru) |           29,554 |                    34,619 |                   1,065 |                      5,065 |                      156 |                                       17% |                                30,999 |                                 40,734 |
|                         [Colombia](/colombia) |           20,886 |                    30,528 |                     606 |                      9,642 |                      192 |                                       46% |                                24,982 |                                 39,038 |
|                                 [Iran](/iran) |           22,154 |                    27,088 |                     327 |                      4,934 |                       60 |                                       22% |                                23,633 |                                 32,713 |
|                             [Russia](/russia) |           17,707 |                    21,938 |                     150 |                      4,231 |                       29 |                                       24% |                                18,624 |                                 30,253 |
|                 [South Africa](/south-africa) |           14,779 |                    19,011 |                     325 |                      4,232 |                       72 |                                       29% |                                15,501 |                                 21,649 |
|                       [Argentina](/argentina) |            9,739 |                    18,994 |                     424 |                      9,255 |                      207 |                                       95% |                                13,644 |                                 26,183 |
|                               [Chile](/chile) |           11,551 |                    14,582 |                     769 |                      3,031 |                      160 |                                       26% |                                11,994 |                                 21,420 |
|                       [Indonesia](/indonesia) |            7,940 |                    12,807 |                      47 |                      4,867 |                       18 |                                       61% |                                 9,880 |                                 19,409 |
|                             [Canada](/canada) |            9,192 |                     9,442 |                     252 |                        250 |                        7 |                                        3% |                                 9,221 |                                 10,086 |
|                             [Turkey](/turkey) |            6,620 |                     8,110 |                      97 |                      1,490 |                       18 |                                       23% |                                 6,779 |                                 10,836 |
|                           [Bolivia](/bolivia) |            5,398 |                     8,018 |                     696 |                      2,620 |                      228 |                                       49% |                                 6,493 |                                 10,229 |
|                           [Ecuador](/ecuador) |            6,724 |                     7,726 |                     445 |                      1,002 |                       58 |                                       15% |                                 6,807 |                                  9,941 |
|                   [Philippines](/philippines) |            3,790 |                     6,993 |                      65 |                      3,203 |                       30 |                                       85% |                                 4,870 |                                 10,385 |
|                         [Pakistan](/pakistan) |            6,340 |                     6,694 |                      31 |                        354 |                        2 |                                        6% |                                 6,363 |                                  7,541 |
|                     [Bangladesh](/bangladesh) |            4,447 |                     6,188 |                      38 |                      1,741 |                       11 |                                       39% |                                 5,009 |                                  8,347 |
|                               [Egypt](/egypt) |            5,511 |                     6,120 |                      61 |                        609 |                        6 |                                       11% |                                 5,551 |                                  8,308 |
|                 [Saudi Arabia](/saudi-arabia) |            4,049 |                     5,269 |                     154 |                      1,220 |                       36 |                                       30% |                                 4,428 |                                  6,684 |
|                               [China](/china) |            4,728 |                     4,800 |                       3 |                         72 |                        0 |                                        2% |                                 4,728 |                                  5,374 |
|                           [Morocco](/morocco) |            1,329 |                     3,471 |                      95 |                      2,142 |                       59 |                                      161% |                                 2,056 |                                  5,491 |
|                         [Honduras](/honduras) |            2,006 |                     2,917 |                     299 |                        911 |                       93 |                                       45% |                                 2,330 |                                  3,974 |
|     [Dominican Republic](/dominican-republic) |            1,840 |                     2,847 |                     265 |                      1,007 |                       94 |                                       55% |                                 2,194 |                                  3,935 |
|                             [Panama](/panama) |            2,075 |                     2,542 |                     599 |                        467 |                      110 |                                       23% |                                 2,271 |                                  3,082 |
|                           [Algeria](/algeria) |            1,549 |                     2,106 |                      49 |                        557 |                       13 |                                       36% |                                 1,653 |                                  3,054 |
|                               [Japan](/japan) |            1,361 |                     2,079 |                      16 |                        718 |                        6 |                                       53% |                                 1,542 |                                  3,414 |
|                             [Israel](/israel) |            1,007 |                     1,794 |                     211 |                        787 |                       92 |                                       78% |                                 1,250 |                                  2,770 |
|                           [Nigeria](/nigeria) |            1,054 |                     1,268 |                       6 |                        214 |                        1 |                                       20% |                                 1,106 |                                  1,568 |
|                       [Australia](/australia) |              753 |                     1,164 |                      46 |                        411 |                       16 |                                       55% |                                   914 |                                  1,499 |
|                             [Kuwait](/kuwait) |              540 |                       656 |                     156 |                        116 |                       28 |                                       21% |                                   559 |                                    887 |
| [United Arab Emirates](/united-arab-emirates) |              388 |                       451 |                      46 |                         63 |                        6 |                                       16% |                                   392 |                                    609 |
|                   [South Korea](/south-korea) |              334 |                       432 |                       8 |                         98 |                        2 |                                       29% |                                   338 |                                    646 |
|                                 [Cuba](/cuba) |              100 |                       144 |                      13 |                         44 |                        4 |                                       44% |                                   112 |                                    219 |
|                         [Malaysia](/malaysia) |              128 |                       140 |                       4 |                         12 |                        0 |                                        9% |                                   131 |                                    153 |
