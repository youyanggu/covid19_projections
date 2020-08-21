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

* **August 17:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 21 (12pm ET):
<p align="center">
  Current Total: <b>174,252</b> deaths | Projected Total: <b>226,500 deaths by Nov 1, 2020</b> (Range: 206-255k)<br>
  Currently Infected: <b>1.6%</b> (1 in 64) | Total Infected: <b>13.7%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 21, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              175,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |        <1% |         23% |        89% |         99% |        99% |
|              225,000 |        <1% |         <1% |         2% |         17% |        45% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         5% |
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

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          174,252 |                   226,547 |                     683 |                     52,295 |                                       30% |                               206,591 |                                254,209 |
|                 [New York](/us-ny) |           32,861 |                    33,392 |                   1,716 |                        531 |                                        2% |                                32,880 |                                 36,056 |
|                    [Texas](/us-tx) |           11,174 |                    19,188 |                     662 |                      8,014 |                                       72% |                                15,489 |                                 23,447 |
|               [California](/us-ca) |           11,810 |                    18,859 |                     477 |                      7,049 |                                       60% |                                14,837 |                                 24,663 |
|                  [Florida](/us-fl) |           10,049 |                    16,696 |                     777 |                      6,647 |                                       66% |                                13,386 |                                 20,705 |
|               [New Jersey](/us-nj) |           15,932 |                    16,183 |                   1,822 |                        251 |                                        2% |                                15,954 |                                 16,838 |
|            [Massachusetts](/us-ma) |            8,888 |                     9,828 |                   1,414 |                        940 |                                       11% |                                 8,960 |                                 11,665 |
|                 [Illinois](/us-il) |            8,044 |                     9,427 |                     744 |                      1,383 |                                       17% |                                 8,218 |                                 11,890 |
|             [Pennsylvania](/us-pa) |            7,520 |                     8,674 |                     678 |                      1,154 |                                       15% |                                 7,637 |                                 10,895 |
|                  [Georgia](/us-ga) |            4,904 |                     7,510 |                     707 |                      2,606 |                                       53% |                                 6,158 |                                  9,495 |
|                 [Michigan](/us-mi) |            6,634 |                     7,306 |                     732 |                        672 |                                       10% |                                 6,695 |                                  8,538 |
|                  [Arizona](/us-az) |            4,684 |                     6,592 |                     906 |                      1,908 |                                       41% |                                 5,605 |                                  7,952 |
|                [Louisiana](/us-la) |            4,637 |                     5,792 |                   1,246 |                      1,155 |                                       25% |                                 5,128 |                                  6,758 |
|                     [Ohio](/us-oh) |            3,929 |                     5,509 |                     471 |                      1,580 |                                       40% |                                 4,463 |                                  7,205 |
|              [Connecticut](/us-ct) |            4,458 |                     4,546 |                   1,275 |                         88 |                                        2% |                                 4,472 |                                  4,775 |
|                 [Maryland](/us-md) |            3,669 |                     4,379 |                     724 |                        710 |                                       19% |                                 3,727 |                                  5,751 |
|                  [Indiana](/us-in) |            3,191 |                     4,199 |                     624 |                      1,008 |                                       32% |                                 3,312 |                                  5,713 |
|           [North Carolina](/us-nc) |            2,465 |                     3,944 |                     376 |                      1,479 |                                       60% |                                 3,080 |                                  5,333 |
|           [South Carolina](/us-sc) |            2,401 |                     3,880 |                     754 |                      1,479 |                                       62% |                                 3,113 |                                  4,922 |
|                 [Virginia](/us-va) |            2,427 |                     3,389 |                     397 |                        962 |                                       40% |                                 2,577 |                                  4,919 |
|              [Mississippi](/us-ms) |            2,190 |                     3,203 |                   1,076 |                      1,013 |                                       46% |                                 2,659 |                                  3,889 |
|                  [Alabama](/us-al) |            1,974 |                     2,873 |                     586 |                        899 |                                       46% |                                 2,377 |                                  3,576 |
|               [Washington](/us-wa) |            1,837 |                     2,849 |                     374 |                      1,012 |                                       55% |                                 2,158 |                                  4,079 |
|                [Tennessee](/us-tn) |            1,488 |                     2,741 |                     401 |                      1,253 |                                       84% |                                 2,085 |                                  3,684 |
|                [Minnesota](/us-mn) |            1,791 |                     2,334 |                     414 |                        543 |                                       30% |                                 1,879 |                                  3,166 |
|                 [Colorado](/us-co) |            1,903 |                     2,300 |                     399 |                        397 |                                       21% |                                 1,941 |                                  3,006 |
|                 [Missouri](/us-mo) |            1,442 |                     2,144 |                     349 |                        702 |                                       49% |                                 1,696 |                                  2,870 |
|                   [Nevada](/us-nv) |            1,172 |                     2,031 |                     660 |                        859 |                                       73% |                                 1,605 |                                  2,569 |
|                [Wisconsin](/us-wi) |            1,067 |                     1,599 |                     275 |                        532 |                                       50% |                                 1,250 |                                  2,250 |
|                     [Iowa](/us-ia) |            1,016 |                     1,479 |                     469 |                        463 |                                       46% |                                 1,164 |                                  1,979 |
|                 [Kentucky](/us-ky) |              856 |                     1,345 |                     301 |                        489 |                                       57% |                                 1,027 |                                  1,859 |
|                 [Oklahoma](/us-ok) |              709 |                     1,309 |                     331 |                        600 |                                       85% |                                   950 |                                  1,849 |
|                 [Arkansas](/us-ar) |              641 |                     1,156 |                     383 |                        515 |                                       80% |                                   868 |                                  1,562 |
|             [Rhode Island](/us-ri) |            1,028 |                     1,109 |                   1,047 |                         81 |                                        8% |                                 1,040 |                                  1,260 |
|               [New Mexico](/us-nm) |              734 |                     1,038 |                     495 |                        304 |                                       41% |                                   842 |                                  1,384 |
|              [Puerto Rico](/us-pr) |              367 |                     1,015 |                     318 |                        648 |                                      177% |                                   656 |                                  1,570 |
|                   [Oregon](/us-or) |              412 |                       803 |                     190 |                        391 |                                       95% |                                   559 |                                  1,179 |
|                 [Delaware](/us-de) |              595 |                       677 |                     695 |                         82 |                                       14% |                                   604 |                                    827 |
|                   [Kansas](/us-ks) |              419 |                       667 |                     229 |                        248 |                                       59% |                                   508 |                                    953 |
|                     [Utah](/us-ut) |              381 |                       656 |                     205 |                        275 |                                       72% |                                   483 |                                    946 |
|     [District of Columbia](/us-dc) |              601 |                       652 |                     925 |                         51 |                                        9% |                                   610 |                                    740 |
|                    [Idaho](/us-id) |              296 |                       635 |                     355 |                        339 |                                      114% |                                   455 |                                    875 |
|                 [Nebraska](/us-ne) |              373 |                       527 |                     272 |                        154 |                                       41% |                                   434 |                                    725 |
|            [New Hampshire](/us-nh) |              428 |                       494 |                     363 |                         66 |                                       15% |                                   432 |                                    647 |
|            [West Virginia](/us-wv) |              167 |                       382 |                     213 |                        215 |                                      129% |                                   249 |                                    605 |
|             [South Dakota](/us-sd) |              157 |                       230 |                     261 |                         73 |                                       47% |                                   184 |                                    318 |
|             [North Dakota](/us-nd) |              130 |                       230 |                     302 |                        100 |                                       77% |                                   168 |                                    331 |
|                  [Montana](/us-mt) |               89 |                       218 |                     204 |                        129 |                                      144% |                                   140 |                                    342 |
|                   [Hawaii](/us-hi) |               45 |                       167 |                     118 |                        122 |                                      271% |                                    84 |                                    323 |
|                    [Maine](/us-me) |              128 |                       155 |                     115 |                         27 |                                       21% |                                   133 |                                    196 |
|                  [Vermont](/us-vt) |               58 |                        73 |                     117 |                         15 |                                       26% |                                    61 |                                    100 |
|                  [Wyoming](/us-wy) |               34 |                        64 |                     110 |                         30 |                                       87% |                                    47 |                                    101 |
|                   [Alaska](/us-ak) |               29 |                        59 |                      81 |                         30 |                                      104% |                                    41 |                                     92 |
|           [Virgin Islands](/us-vi) |               10 |                        21 |                     202 |                         11 |                                      112% |                                    14 |                                     33 |
|                     [Guam](/us-gu) |                6 |                        16 |                      95 |                         10 |                                      163% |                                     7 |                                     35 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      55 |                          1 |                                       52% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,917 |                   202,225 |                     341 |                     15,308 |                                        8% |                               190,326 |                                236,513 |
| [United Kingdom](/united-kingdom) |           41,489 |                    42,470 |                     629 |                        981 |                                        2% |                                41,515 |                                 46,229 |
|                   [Italy](/italy) |           35,418 |                    36,031 |                     597 |                        613 |                                        2% |                                35,441 |                                 38,389 |
|                 [France](/france) |           30,434 |                    31,400 |                     469 |                        966 |                                        3% |                                30,476 |                                 35,637 |
|                   [Spain](/spain) |           28,813 |                    30,164 |                     643 |                      1,351 |                                        5% |                                28,852 |                                 34,765 |
|               [Belgium](/belgium) |            9,976 |                    10,534 |                     920 |                        558 |                                        6% |                                10,018 |                                 12,710 |
|               [Germany](/germany) |            9,263 |                     9,985 |                     120 |                        722 |                                        8% |                                 9,312 |                                 12,228 |
|       [Netherlands](/netherlands) |            6,215 |                     6,584 |                     381 |                        369 |                                        6% |                                 6,240 |                                  8,000 |
|               [Romania](/romania) |            3,154 |                     6,167 |                     318 |                      3,013 |                                       96% |                                 4,291 |                                  9,564 |
|                 [Sweden](/sweden) |            5,805 |                     5,954 |                     582 |                        149 |                                        3% |                                 5,830 |                                  6,052 |
|               [Ukraine](/ukraine) |            2,225 |                     5,001 |                     114 |                      2,776 |                                      125% |                                 3,117 |                                  8,896 |
|                 [Poland](/poland) |            1,925 |                     2,941 |                      77 |                      1,016 |                                       53% |                                 2,218 |                                  4,369 |
|       [Switzerland](/switzerland) |            1,998 |                     2,130 |                     248 |                        132 |                                        7% |                                 2,017 |                                  2,501 |
|             [Portugal](/portugal) |            1,788 |                     2,028 |                     197 |                        240 |                                       13% |                                 1,798 |                                  2,589 |
|               [Ireland](/ireland) |            1,776 |                     1,852 |                     378 |                         76 |                                        4% |                                 1,786 |                                  2,075 |
|               [Moldova](/moldova) |              921 |                     1,318 |                     326 |                        397 |                                       43% |                                 1,069 |                                  1,860 |
|             [Bulgaria](/bulgaria) |              532 |                     1,048 |                     150 |                        516 |                                       97% |                                   720 |                                  1,774 |
|                 [Serbia](/serbia) |              689 |                       966 |                     139 |                        277 |                                       40% |                                   799 |                                  1,211 |
|               [Belarus](/belarus) |              627 |                       821 |                      87 |                        194 |                                       31% |                                   738 |                                    995 |
|               [Austria](/austria) |              729 |                       812 |                      92 |                         83 |                                       11% |                                   741 |                                  1,032 |
|               [Denmark](/denmark) |              621 |                       702 |                     121 |                         81 |                                       13% |                                   638 |                                    908 |
|               [Hungary](/hungary) |              609 |                       684 |                      70 |                         75 |                                       12% |                                   616 |                                    870 |
|               [Czechia](/czechia) |              406 |                       580 |                      54 |                        174 |                                       43% |                                   442 |                                    881 |
|                 [Greece](/greece) |              235 |                       451 |                      42 |                        216 |                                       92% |                                   297 |                                    782 |
|               [Finland](/finland) |              334 |                       371 |                      67 |                         37 |                                       11% |                                   341 |                                    476 |
|                 [Norway](/norway) |              264 |                       320 |                      59 |                         56 |                                       21% |                                   277 |                                    444 |
|               [Croatia](/croatia) |              168 |                       262 |                      64 |                         94 |                                       56% |                                   198 |                                    389 |
|         [Luxembourg](/luxembourg) |              124 |                       165 |                     269 |                         41 |                                       33% |                                   137 |                                    216 |
|             [Slovenia](/slovenia) |              129 |                       159 |                      77 |                         30 |                                       24% |                                   134 |                                    214 |
|           [Lithuania](/lithuania) |               82 |                        98 |                      35 |                         16 |                                       19% |                                    85 |                                    130 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     79 |
|             [Slovakia](/slovakia) |               33 |                        59 |                      11 |                         26 |                                       80% |                                    38 |                                    113 |
|                 [Latvia](/latvia) |               33 |                        44 |                      23 |                         11 |                                       32% |                                    35 |                                     64 |
|                 [Cyprus](/cyprus) |               20 |                        28 |                      32 |                          8 |                                       42% |                                    23 |                                     39 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                                       26% |                                    10 |                                     18 |
|                   [Malta](/malta) |                9 |                        11 |                      23 |                          2 |                                       27% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          405,835 |                   663,226 |                     128 |                    257,391 |                                       63% |                               509,445 |                                932,506 |
|                             [Brazil](/brazil) |          112,304 |                   176,357 |                     836 |                     64,053 |                                       57% |                               137,749 |                                239,367 |
|                               [India](/india) |           54,849 |                   120,358 |                      88 |                     65,509 |                                      119% |                                80,006 |                                175,460 |
|                             [Mexico](/mexico) |           59,106 |                    96,184 |                     754 |                     37,078 |                                       63% |                                82,565 |                                127,515 |
|                                 [Peru](/peru) |           26,834 |                    35,561 |                   1,094 |                      8,727 |                                       33% |                                29,255 |                                 46,201 |
|                         [Colombia](/colombia) |           16,183 |                    29,484 |                     586 |                     13,301 |                                       82% |                                22,137 |                                 43,479 |
|                                 [Iran](/iran) |           20,264 |                    27,751 |                     335 |                      7,487 |                                       37% |                                22,866 |                                 36,529 |
|                 [South Africa](/south-africa) |           12,618 |                    22,010 |                     376 |                      9,392 |                                       74% |                                16,043 |                                 31,828 |
|                             [Russia](/russia) |           16,058 |                    21,799 |                     149 |                      5,741 |                                       36% |                                17,876 |                                 30,146 |
|                       [Argentina](/argentina) |            6,517 |                    18,611 |                     416 |                     12,094 |                                      186% |                                11,045 |                                 29,516 |
|                               [Chile](/chile) |           10,671 |                    14,358 |                     758 |                      3,687 |                                       35% |                                11,233 |                                 22,484 |
|                       [Indonesia](/indonesia) |            6,418 |                    10,658 |                      39 |                      4,240 |                                       66% |                                 7,967 |                                 17,207 |
|                             [Canada](/canada) |            9,097 |                     9,499 |                     254 |                        402 |                                        4% |                                 9,130 |                                 10,468 |
|                           [Ecuador](/ecuador) |            6,200 |                     7,498 |                     432 |                      1,298 |                                       21% |                                 6,347 |                                 10,299 |
|                             [Turkey](/turkey) |            6,058 |                     7,452 |                      89 |                      1,394 |                                       23% |                                 6,179 |                                 11,021 |
|                   [Philippines](/philippines) |            2,883 |                     7,425 |                      69 |                      4,542 |                                      158% |                                 4,019 |                                 14,425 |
|                           [Bolivia](/bolivia) |            4,305 |                     7,114 |                     618 |                      2,809 |                                       65% |                                 5,361 |                                 10,452 |
|                         [Pakistan](/pakistan) |            6,209 |                     6,964 |                      32 |                        755 |                                       12% |                                 6,316 |                                  8,039 |
|                               [Egypt](/egypt) |            5,212 |                     5,849 |                      58 |                        637 |                                       12% |                                 5,307 |                                  6,909 |
|                     [Bangladesh](/bangladesh) |            3,822 |                     5,803 |                      36 |                      1,981 |                                       52% |                                 4,309 |                                  9,007 |
|                 [Saudi Arabia](/saudi-arabia) |            3,548 |                     5,248 |                     153 |                      1,700 |                                       48% |                                 4,070 |                                  7,136 |
|                               [China](/china) |            4,709 |                     4,902 |                       3 |                        193 |                                        4% |                                 4,709 |                                  6,257 |
|                           [Morocco](/morocco) |              775 |                     3,427 |                      94 |                      2,652 |                                      342% |                                 1,612 |                                  7,206 |
|                             [Panama](/panama) |            1,844 |                     2,776 |                     654 |                        932 |                                       51% |                                 2,194 |                                  3,830 |
|                         [Honduras](/honduras) |            1,619 |                     2,547 |                     261 |                        928 |                                       57% |                                 1,957 |                                  3,719 |
|     [Dominican Republic](/dominican-republic) |            1,505 |                     2,544 |                     237 |                      1,039 |                                       69% |                                 1,867 |                                  3,914 |
|                               [Japan](/japan) |            1,157 |                     2,312 |                      18 |                      1,155 |                                      100% |                                 1,279 |                                  5,554 |
|                           [Algeria](/algeria) |            1,411 |                     2,156 |                      50 |                        745 |                                       53% |                                 1,583 |                                  3,425 |
|                             [Israel](/israel) |              795 |                     2,057 |                     241 |                      1,262 |                                      159% |                                 1,185 |                                  3,588 |
|                       [Australia](/australia) |              472 |                     1,422 |                      56 |                        950 |                                      201% |                                   779 |                                  2,811 |
|                           [Nigeria](/nigeria) |              992 |                     1,288 |                       6 |                        296 |                                       30% |                                 1,049 |                                  1,921 |
|                             [Kuwait](/kuwait) |              509 |                       729 |                     173 |                        220 |                                       43% |                                   544 |                                  1,212 |
| [United Arab Emirates](/united-arab-emirates) |              369 |                       458 |                      47 |                         89 |                                       24% |                                   374 |                                    692 |
|                   [South Korea](/south-korea) |              309 |                       362 |                       7 |                         53 |                                       17% |                                   309 |                                    531 |
|                         [Malaysia](/malaysia) |              125 |                       140 |                       4 |                         15 |                                       12% |                                   129 |                                    155 |
|                                 [Cuba](/cuba) |               88 |                       124 |                      11 |                         36 |                                       41% |                                    95 |                                    203 |
