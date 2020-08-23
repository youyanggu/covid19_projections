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
### Updated Daily - Last Updated: August 23 (2am ET):
<p align="center">
  Current Total: <b>176,350</b> deaths | Projected Total: <b>227,000 deaths by Nov 1, 2020</b> (Range: 207-254k)<br>
  Currently Infected: <b>1.5%</b> (1 in 65) | Total Infected: <b>14.0%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 23, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |         23% |        93% |         99% |        99% |
|              225,000 |        <1% |         <1% |         2% |         17% |        47% |
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
|             *[United States](/us)* |          176,350 |                   227,023 |                     684 |                     50,673 |                                       29% |                               207,777 |                                253,511 |
|                 [New York](/us-ny) |           32,871 |                    33,378 |                   1,716 |                        507 |                                        2% |                                32,889 |                                 35,926 |
|                    [Texas](/us-tx) |           11,581 |                    19,416 |                     670 |                      7,835 |                                       68% |                                15,736 |                                 23,468 |
|               [California](/us-ca) |           12,131 |                    19,168 |                     485 |                      7,037 |                                       58% |                                15,247 |                                 24,768 |
|                  [Florida](/us-fl) |           10,274 |                    16,358 |                     762 |                      6,084 |                                       59% |                                13,320 |                                 20,210 |
|               [New Jersey](/us-nj) |           15,943 |                    16,181 |                   1,822 |                        238 |                                        1% |                                15,964 |                                 16,809 |
|            [Massachusetts](/us-ma) |            8,921 |                     9,829 |                   1,414 |                        908 |                                       10% |                                 9,002 |                                 11,557 |
|                 [Illinois](/us-il) |            8,083 |                     9,401 |                     742 |                      1,318 |                                       16% |                                 8,249 |                                 11,675 |
|             [Pennsylvania](/us-pa) |            7,555 |                     8,669 |                     677 |                      1,114 |                                       15% |                                 7,668 |                                 10,795 |
|                  [Georgia](/us-ga) |            5,092 |                     7,745 |                     729 |                      2,653 |                                       52% |                                 6,369 |                                  9,739 |
|                 [Michigan](/us-mi) |            6,655 |                     7,302 |                     731 |                        647 |                                       10% |                                 6,714 |                                  8,472 |
|                  [Arizona](/us-az) |            4,756 |                     6,540 |                     898 |                      1,784 |                                       38% |                                 5,613 |                                  7,841 |
|                [Louisiana](/us-la) |            4,687 |                     5,780 |                   1,243 |                      1,093 |                                       23% |                                 5,147 |                                  6,703 |
|                     [Ohio](/us-oh) |            3,975 |                     5,519 |                     472 |                      1,544 |                                       39% |                                 4,509 |                                  7,131 |
|              [Connecticut](/us-ct) |            4,460 |                     4,544 |                   1,275 |                         84 |                                        2% |                                 4,473 |                                  4,764 |
|                 [Maryland](/us-md) |            3,685 |                     4,364 |                     722 |                        679 |                                       18% |                                 3,740 |                                  5,665 |
|                  [Indiana](/us-in) |            3,218 |                     4,199 |                     624 |                        981 |                                       30% |                                 3,339 |                                  5,651 |
|           [South Carolina](/us-sc) |            2,493 |                     3,976 |                     772 |                      1,483 |                                       59% |                                 3,195 |                                  4,983 |
|           [North Carolina](/us-nc) |            2,521 |                     3,969 |                     378 |                      1,448 |                                       57% |                                 3,125 |                                  5,320 |
|                 [Virginia](/us-va) |            2,443 |                     3,355 |                     393 |                        912 |                                       37% |                                 2,586 |                                  4,782 |
|              [Mississippi](/us-ms) |            2,237 |                     3,198 |                   1,075 |                        961 |                                       43% |                                 2,682 |                                  3,836 |
|                [Tennessee](/us-tn) |            1,563 |                     2,884 |                     422 |                      1,321 |                                       85% |                                 2,202 |                                  3,800 |
|                  [Alabama](/us-al) |            2,011 |                     2,873 |                     586 |                        862 |                                       43% |                                 2,395 |                                  3,554 |
|               [Washington](/us-wa) |            1,857 |                     2,812 |                     369 |                        955 |                                       51% |                                 2,163 |                                  3,977 |
|                [Minnesota](/us-mn) |            1,807 |                     2,335 |                     414 |                        528 |                                       29% |                                 1,893 |                                  3,126 |
|                 [Colorado](/us-co) |            1,918 |                     2,309 |                     401 |                        391 |                                       20% |                                 1,955 |                                  2,995 |
|                 [Missouri](/us-mo) |            1,451 |                     2,112 |                     344 |                        661 |                                       46% |                                 1,697 |                                  2,798 |
|                   [Nevada](/us-nv) |            1,197 |                     2,005 |                     651 |                        808 |                                       67% |                                 1,602 |                                  2,523 |
|                [Wisconsin](/us-wi) |            1,081 |                     1,599 |                     275 |                        518 |                                       48% |                                 1,263 |                                  2,223 |
|                     [Iowa](/us-ia) |            1,033 |                     1,487 |                     471 |                        454 |                                       44% |                                 1,185 |                                  1,966 |
|                 [Kentucky](/us-ky) |              872 |                     1,355 |                     303 |                        483 |                                       55% |                                 1,040 |                                  1,853 |
|                 [Oklahoma](/us-ok) |              725 |                     1,305 |                     330 |                        580 |                                       80% |                                   958 |                                  1,818 |
|                 [Arkansas](/us-ar) |              674 |                     1,226 |                     406 |                        552 |                                       82% |                                   921 |                                  1,627 |
|             [Rhode Island](/us-ri) |            1,030 |                     1,107 |                   1,045 |                         77 |                                        8% |                                 1,041 |                                  1,255 |
|               [New Mexico](/us-nm) |              743 |                     1,038 |                     495 |                        295 |                                       40% |                                   849 |                                  1,371 |
|              [Puerto Rico](/us-pr) |              381 |                       978 |                     306 |                        597 |                                      157% |                                   652 |                                  1,480 |
|                   [Oregon](/us-or) |              417 |                       776 |                     184 |                        359 |                                       86% |                                   551 |                                  1,128 |
|                 [Delaware](/us-de) |              600 |                       681 |                     699 |                         81 |                                       13% |                                   609 |                                    829 |
|                   [Kansas](/us-ks) |              426 |                       667 |                     229 |                        241 |                                       57% |                                   512 |                                    944 |
|     [District of Columbia](/us-dc) |              604 |                       654 |                     927 |                         50 |                                        8% |                                   613 |                                    740 |
|                     [Utah](/us-ut) |              385 |                       635 |                     198 |                        250 |                                       65% |                                   481 |                                    902 |
|                    [Idaho](/us-id) |              306 |                       626 |                     350 |                        320 |                                      105% |                                   456 |                                    860 |
|                 [Nebraska](/us-ne) |              376 |                       523 |                     271 |                        147 |                                       39% |                                   434 |                                    713 |
|            [New Hampshire](/us-nh) |              429 |                       493 |                     363 |                         64 |                                       15% |                                   433 |                                    642 |
|            [West Virginia](/us-wv) |              177 |                       411 |                     229 |                        234 |                                      132% |                                   268 |                                    646 |
|             [North Dakota](/us-nd) |              135 |                       241 |                     316 |                        106 |                                       78% |                                   178 |                                    345 |
|             [South Dakota](/us-sd) |              160 |                       232 |                     262 |                         72 |                                       45% |                                   186 |                                    318 |
|                  [Montana](/us-mt) |               90 |                       204 |                     191 |                        114 |                                      127% |                                   135 |                                    315 |
|                    [Maine](/us-me) |              130 |                       158 |                     117 |                         28 |                                       21% |                                   135 |                                    199 |
|                   [Hawaii](/us-hi) |               47 |                       154 |                     109 |                        107 |                                      228% |                                    84 |                                    275 |
|                  [Wyoming](/us-wy) |               37 |                        76 |                     131 |                         39 |                                      105% |                                    54 |                                    116 |
|                  [Vermont](/us-vt) |               58 |                        73 |                     116 |                         15 |                                       25% |                                    61 |                                     99 |
|                   [Alaska](/us-ak) |               31 |                        66 |                      91 |                         35 |                                      114% |                                    44 |                                    106 |
|           [Virgin Islands](/us-vi) |               10 |                        20 |                     188 |                         10 |                                       97% |                                    13 |                                     31 |
|                     [Guam](/us-gu) |                6 |                        14 |                      86 |                          8 |                                      138% |                                     7 |                                     31 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      55 |                          1 |                                       51% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,328 |                   201,942 |                     340 |                     14,614 |                                        8% |                               190,679 |                                234,449 |
| [United Kingdom](/united-kingdom) |           41,509 |                    42,438 |                     628 |                        929 |                                        2% |                                41,537 |                                 46,027 |
|                   [Italy](/italy) |           35,430 |                    36,015 |                     597 |                        585 |                                        2% |                                35,452 |                                 38,305 |
|                 [France](/france) |           30,517 |                    31,500 |                     470 |                        983 |                                        3% |                                30,559 |                                 35,709 |
|                   [Spain](/spain) |           28,838 |                    30,074 |                     641 |                      1,236 |                                        4% |                                28,875 |                                 34,349 |
|               [Belgium](/belgium) |            9,988 |                    10,509 |                     917 |                        521 |                                        5% |                                10,028 |                                 12,533 |
|               [Germany](/germany) |            9,272 |                     9,959 |                     120 |                        687 |                                        7% |                                 9,318 |                                 12,079 |
|       [Netherlands](/netherlands) |            6,225 |                     6,590 |                     381 |                        365 |                                        6% |                                 6,250 |                                  7,999 |
|               [Romania](/romania) |            3,233 |                     6,034 |                     311 |                      2,801 |                                       87% |                                 4,333 |                                  9,107 |
|                 [Sweden](/sweden) |            5,810 |                     5,950 |                     582 |                        140 |                                        2% |                                 5,833 |                                  6,043 |
|               [Ukraine](/ukraine) |            2,286 |                     5,004 |                     114 |                      2,718 |                                      119% |                                 3,192 |                                  8,756 |
|                 [Poland](/poland) |            1,951 |                     2,967 |                      78 |                      1,016 |                                       52% |                                 2,248 |                                  4,341 |
|       [Switzerland](/switzerland) |            2,000 |                     2,125 |                     247 |                        125 |                                        6% |                                 2,018 |                                  2,458 |
|             [Portugal](/portugal) |            1,794 |                     2,026 |                     197 |                        232 |                                       13% |                                 1,803 |                                  2,575 |
|               [Ireland](/ireland) |            1,777 |                     1,849 |                     377 |                         72 |                                        4% |                                 1,787 |                                  2,063 |
|               [Moldova](/moldova) |              935 |                     1,317 |                     326 |                        382 |                                       41% |                                 1,085 |                                  1,820 |
|                 [Serbia](/serbia) |              695 |                       951 |                     137 |                        256 |                                       37% |                                   797 |                                  1,176 |
|             [Bulgaria](/bulgaria) |              539 |                       935 |                     134 |                        396 |                                       74% |                                   697 |                                  1,449 |
|               [Belarus](/belarus) |              637 |                       832 |                      88 |                        195 |                                       31% |                                   745 |                                  1,001 |
|               [Austria](/austria) |              732 |                       816 |                      92 |                         84 |                                       11% |                                   744 |                                  1,034 |
|               [Denmark](/denmark) |              622 |                       699 |                     120 |                         77 |                                       12% |                                   638 |                                    881 |
|               [Hungary](/hungary) |              611 |                       686 |                      70 |                         75 |                                       12% |                                   617 |                                    870 |
|               [Czechia](/czechia) |              411 |                       591 |                      56 |                        180 |                                       44% |                                   450 |                                    884 |
|                 [Greece](/greece) |              240 |                       460 |                      43 |                        220 |                                       91% |                                   309 |                                    787 |
|               [Finland](/finland) |              334 |                       370 |                      67 |                         36 |                                       11% |                                   340 |                                    469 |
|                 [Norway](/norway) |              264 |                       315 |                      58 |                         51 |                                       19% |                                   276 |                                    423 |
|               [Croatia](/croatia) |              170 |                       260 |                      64 |                         90 |                                       53% |                                   199 |                                    385 |
|             [Slovenia](/slovenia) |              131 |                       165 |                      79 |                         34 |                                       26% |                                   136 |                                    223 |
|         [Luxembourg](/luxembourg) |              124 |                       161 |                     263 |                         37 |                                       30% |                                   136 |                                    208 |
|           [Lithuania](/lithuania) |               84 |                       113 |                      40 |                         29 |                                       34% |                                    91 |                                    159 |
|               [Estonia](/estonia) |               63 |                        71 |                      53 |                          8 |                                       12% |                                    67 |                                     78 |
|             [Slovakia](/slovakia) |               33 |                        55 |                      10 |                         22 |                                       67% |                                    37 |                                    105 |
|                 [Latvia](/latvia) |               33 |                        42 |                      22 |                          9 |                                       27% |                                    35 |                                     57 |
|                 [Cyprus](/cyprus) |               20 |                        28 |                      32 |                          8 |                                       39% |                                    23 |                                     37 |
|                   [Malta](/malta) |               10 |                        23 |                      47 |                         13 |                                      130% |                                    14 |                                     42 |
|               [Iceland](/iceland) |               10 |                        12 |                      37 |                          2 |                                       25% |                                    10 |                                     17 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          413,891 |                   657,329 |                     127 |                    243,438 |                                       59% |                               511,164 |                                912,846 |
|                             [Brazil](/brazil) |          114,250 |                   174,602 |                     827 |                     60,352 |                                       53% |                               136,955 |                                235,019 |
|                               [India](/india) |           56,706 |                   118,567 |                      87 |                     61,861 |                                      109% |                                80,797 |                                171,735 |
|                             [Mexico](/mexico) |           60,254 |                    95,759 |                     751 |                     35,505 |                                       59% |                                82,830 |                                124,439 |
|                                 [Peru](/peru) |           27,245 |                    35,669 |                   1,097 |                      8,424 |                                       31% |                                29,942 |                                 45,637 |
|                         [Colombia](/colombia) |           16,568 |                    28,252 |                     561 |                     11,684 |                                       71% |                                21,753 |                                 41,545 |
|                                 [Iran](/iran) |           20,502 |                    27,513 |                     332 |                      7,011 |                                       34% |                                22,819 |                                 35,523 |
|                 [South Africa](/south-africa) |           12,987 |                    21,843 |                     373 |                      8,856 |                                       68% |                                16,161 |                                 31,551 |
|                             [Russia](/russia) |           16,268 |                    21,803 |                     149 |                      5,535 |                                       34% |                                17,972 |                                 29,683 |
|                       [Argentina](/argentina) |            6,848 |                    17,787 |                     397 |                     10,939 |                                      160% |                                11,038 |                                 27,488 |
|                               [Chile](/chile) |           10,792 |                    14,429 |                     761 |                      3,637 |                                       34% |                                11,315 |                                 22,445 |
|                       [Indonesia](/indonesia) |            6,594 |                    10,899 |                      40 |                      4,305 |                                       65% |                                 8,147 |                                 17,367 |
|                             [Canada](/canada) |            9,117 |                     9,523 |                     255 |                        406 |                                        4% |                                 9,151 |                                 10,489 |
|                           [Ecuador](/ecuador) |            6,277 |                     7,562 |                     435 |                      1,285 |                                       20% |                                 6,422 |                                 10,330 |
|                             [Turkey](/turkey) |            6,102 |                     7,465 |                      89 |                      1,363 |                                       22% |                                 6,223 |                                 10,940 |
|                           [Bolivia](/bolivia) |            4,442 |                     7,217 |                     627 |                      2,775 |                                       62% |                                 5,458 |                                 10,372 |
|                   [Philippines](/philippines) |            2,966 |                     6,978 |                      65 |                      4,012 |                                      135% |                                 4,036 |                                 13,037 |
|                         [Pakistan](/pakistan) |            6,231 |                     6,943 |                      32 |                        712 |                                       11% |                                 6,329 |                                  7,977 |
|                     [Bangladesh](/bangladesh) |            3,907 |                     5,878 |                      36 |                      1,971 |                                       50% |                                 4,395 |                                  9,032 |
|                               [Egypt](/egypt) |            5,243 |                     5,840 |                      58 |                        597 |                                       11% |                                 5,327 |                                  6,855 |
|                 [Saudi Arabia](/saudi-arabia) |            3,619 |                     5,301 |                     155 |                      1,682 |                                       46% |                                 4,127 |                                  7,124 |
|                               [China](/china) |            4,711 |                     4,895 |                       3 |                        184 |                                        4% |                                 4,711 |                                  6,207 |
|                           [Morocco](/morocco) |              858 |                     3,755 |                     103 |                      2,897 |                                      338% |                                 1,778 |                                  7,435 |
|                             [Panama](/panama) |            1,878 |                     2,769 |                     652 |                        891 |                                       47% |                                 2,210 |                                  3,807 |
|     [Dominican Republic](/dominican-republic) |            1,554 |                     2,626 |                     245 |                      1,072 |                                       69% |                                 1,916 |                                  4,003 |
|                         [Honduras](/honduras) |            1,643 |                     2,510 |                     258 |                        867 |                                       53% |                                 1,958 |                                  3,616 |
|                               [Japan](/japan) |            1,179 |                     2,295 |                      18 |                      1,116 |                                       95% |                                 1,307 |                                  5,109 |
|                           [Algeria](/algeria) |            1,424 |                     2,132 |                      50 |                        708 |                                       50% |                                 1,585 |                                  3,353 |
|                             [Israel](/israel) |              819 |                     2,018 |                     237 |                      1,199 |                                      146% |                                 1,191 |                                  3,477 |
|                       [Australia](/australia) |              502 |                     1,424 |                      56 |                        922 |                                      184% |                                   806 |                                  2,651 |
|                           [Nigeria](/nigeria) |              997 |                     1,275 |                       6 |                        278 |                                       28% |                                 1,050 |                                  1,871 |
|                             [Kuwait](/kuwait) |              513 |                       717 |                     170 |                        204 |                                       40% |                                   545 |                                  1,160 |
| [United Arab Emirates](/united-arab-emirates) |              372 |                       460 |                      47 |                         88 |                                       24% |                                   377 |                                    689 |
|                   [South Korea](/south-korea) |              309 |                       360 |                       7 |                         51 |                                       17% |                                   309 |                                    527 |
|                         [Malaysia](/malaysia) |              125 |                       139 |                       4 |                         14 |                                       11% |                                   129 |                                    154 |
|                                 [Cuba](/cuba) |               89 |                       124 |                      11 |                         35 |                                       40% |                                    95 |                                    199 |
