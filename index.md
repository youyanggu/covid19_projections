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
### Updated Daily - Last Updated: August 22 (2am ET):
<p align="center">
  Current Total: <b>175,360</b> deaths | Projected Total: <b>227,000 deaths by Nov 1, 2020</b> (Range: 207-255k)<br>
  Currently Infected: <b>1.6%</b> (1 in 64) | Total Infected: <b>13.9%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 22, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |         24% |        92% |         99% |        99% |
|              225,000 |        <1% |         <1% |         2% |         17% |        46% |
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
|             *[United States](/us)* |          175,360 |                   226,990 |                     684 |                     51,630 |                                       29% |                               207,439 |                                254,041 |
|                 [New York](/us-ny) |           32,864 |                    33,381 |                   1,716 |                        517 |                                        2% |                                32,882 |                                 35,987 |
|                    [Texas](/us-tx) |           11,418 |                    19,474 |                     672 |                      8,056 |                                       71% |                                15,835 |                                 23,671 |
|               [California](/us-ca) |           11,946 |                    18,898 |                     478 |                      6,952 |                                       58% |                                14,956 |                                 24,588 |
|                  [Florida](/us-fl) |           10,168 |                    16,537 |                     770 |                      6,369 |                                       63% |                                13,350 |                                 20,473 |
|               [New Jersey](/us-nj) |           15,941 |                    16,186 |                   1,822 |                        245 |                                        2% |                                15,963 |                                 16,825 |
|            [Massachusetts](/us-ma) |            8,901 |                     9,813 |                   1,412 |                        912 |                                       10% |                                 8,971 |                                 11,593 |
|                 [Illinois](/us-il) |            8,066 |                     9,428 |                     744 |                      1,362 |                                       17% |                                 8,236 |                                 11,793 |
|             [Pennsylvania](/us-pa) |            7,537 |                     8,670 |                     677 |                      1,133 |                                       15% |                                 7,651 |                                 10,840 |
|                  [Georgia](/us-ga) |            4,998 |                     7,626 |                     718 |                      2,628 |                                       53% |                                 6,273 |                                  9,604 |
|                 [Michigan](/us-mi) |            6,634 |                     7,255 |                     726 |                        621 |                                        9% |                                 6,692 |                                  8,417 |
|                  [Arizona](/us-az) |            4,688 |                     6,496 |                     893 |                      1,808 |                                       39% |                                 5,566 |                                  7,830 |
|                [Louisiana](/us-la) |            4,687 |                     5,832 |                   1,255 |                      1,145 |                                       24% |                                 5,172 |                                  6,784 |
|                     [Ohio](/us-oh) |            3,955 |                     5,522 |                     472 |                      1,567 |                                       40% |                                 4,495 |                                  7,192 |
|              [Connecticut](/us-ct) |            4,460 |                     4,546 |                   1,275 |                         86 |                                        2% |                                 4,473 |                                  4,771 |
|                 [Maryland](/us-md) |            3,674 |                     4,361 |                     721 |                        687 |                                       19% |                                 3,730 |                                  5,694 |
|                  [Indiana](/us-in) |            3,208 |                     4,210 |                     625 |                      1,002 |                                       31% |                                 3,329 |                                  5,692 |
|           [South Carolina](/us-sc) |            2,459 |                     3,980 |                     773 |                      1,521 |                                       62% |                                 3,181 |                                  5,005 |
|           [North Carolina](/us-nc) |            2,494 |                     3,961 |                     378 |                      1,467 |                                       59% |                                 3,105 |                                  5,334 |
|                 [Virginia](/us-va) |            2,436 |                     3,373 |                     395 |                        937 |                                       38% |                                 2,583 |                                  4,854 |
|              [Mississippi](/us-ms) |            2,214 |                     3,200 |                   1,075 |                        986 |                                       45% |                                 2,672 |                                  3,862 |
|                [Tennessee](/us-tn) |            1,549 |                     2,911 |                     426 |                      1,362 |                                       88% |                                 2,221 |                                  3,838 |
|                  [Alabama](/us-al) |            1,996 |                     2,883 |                     588 |                        887 |                                       44% |                                 2,393 |                                  3,573 |
|               [Washington](/us-wa) |            1,850 |                     2,842 |                     373 |                        992 |                                       54% |                                 2,165 |                                  4,045 |
|                [Minnesota](/us-mn) |            1,799 |                     2,334 |                     414 |                        535 |                                       30% |                                 1,886 |                                  3,146 |
|                 [Colorado](/us-co) |            1,903 |                     2,286 |                     397 |                        383 |                                       20% |                                 1,940 |                                  2,959 |
|                 [Missouri](/us-mo) |            1,445 |                     2,123 |                     346 |                        678 |                                       47% |                                 1,696 |                                  2,829 |
|                   [Nevada](/us-nv) |            1,185 |                     2,023 |                     657 |                        838 |                                       71% |                                 1,607 |                                  2,544 |
|                [Wisconsin](/us-wi) |            1,068 |                     1,574 |                     270 |                        506 |                                       47% |                                 1,243 |                                  2,187 |
|                     [Iowa](/us-ia) |            1,029 |                     1,497 |                     475 |                        468 |                                       46% |                                 1,184 |                                  1,988 |
|                 [Kentucky](/us-ky) |              864 |                     1,351 |                     302 |                        487 |                                       56% |                                 1,033 |                                  1,854 |
|                 [Oklahoma](/us-ok) |              715 |                     1,298 |                     328 |                        583 |                                       82% |                                   950 |                                  1,817 |
|                 [Arkansas](/us-ar) |              663 |                     1,217 |                     403 |                        554 |                                       83% |                                   911 |                                  1,621 |
|             [Rhode Island](/us-ri) |            1,030 |                     1,109 |                   1,047 |                         79 |                                        8% |                                 1,041 |                                  1,259 |
|               [New Mexico](/us-nm) |              739 |                     1,040 |                     496 |                        301 |                                       41% |                                   847 |                                  1,380 |
|              [Puerto Rico](/us-pr) |              374 |                       995 |                     311 |                        621 |                                      166% |                                   652 |                                  1,518 |
|                   [Oregon](/us-or) |              414 |                       785 |                     186 |                        371 |                                       90% |                                   553 |                                  1,149 |
|                 [Delaware](/us-de) |              600 |                       683 |                     701 |                         83 |                                       14% |                                   609 |                                    833 |
|                   [Kansas](/us-ks) |              426 |                       680 |                     233 |                        254 |                                       60% |                                   517 |                                    968 |
|                    [Idaho](/us-id) |              305 |                       656 |                     367 |                        351 |                                      115% |                                   474 |                                    897 |
|     [District of Columbia](/us-dc) |              602 |                       653 |                     925 |                         51 |                                        8% |                                   611 |                                    739 |
|                     [Utah](/us-ut) |              383 |                       647 |                     202 |                        264 |                                       69% |                                   482 |                                    932 |
|                 [Nebraska](/us-ne) |              376 |                       529 |                     273 |                        153 |                                       41% |                                   436 |                                    725 |
|            [New Hampshire](/us-nh) |              428 |                       493 |                     362 |                         65 |                                       15% |                                   432 |                                    644 |
|            [West Virginia](/us-wv) |              171 |                       390 |                     217 |                        219 |                                      128% |                                   256 |                                    611 |
|             [North Dakota](/us-nd) |              132 |                       233 |                     305 |                        101 |                                       76% |                                   171 |                                    334 |
|             [South Dakota](/us-sd) |              159 |                       232 |                     263 |                         73 |                                       46% |                                   185 |                                    320 |
|                  [Montana](/us-mt) |               89 |                       208 |                     195 |                        119 |                                      134% |                                   136 |                                    327 |
|                   [Hawaii](/us-hi) |               46 |                       159 |                     113 |                        113 |                                      246% |                                    84 |                                    297 |
|                    [Maine](/us-me) |              129 |                       156 |                     116 |                         27 |                                       21% |                                   134 |                                    198 |
|                  [Wyoming](/us-wy) |               37 |                        78 |                     135 |                         41 |                                      111% |                                    56 |                                    119 |
|                  [Vermont](/us-vt) |               58 |                        73 |                     117 |                         15 |                                       25% |                                    61 |                                    100 |
|                   [Alaska](/us-ak) |               30 |                        63 |                      86 |                         33 |                                      109% |                                    43 |                                    100 |
|           [Virgin Islands](/us-vi) |               10 |                        20 |                     194 |                         10 |                                      104% |                                    14 |                                     32 |
|                     [Guam](/us-gu) |                6 |                        15 |                      91 |                          9 |                                      150% |                                     7 |                                     33 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      55 |                          1 |                                       52% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,170 |                   202,149 |                     341 |                     14,979 |                                        8% |                               190,570 |                                235,719 |
| [United Kingdom](/united-kingdom) |           41,491 |                    42,436 |                     628 |                        945 |                                        2% |                                41,515 |                                 46,087 |
|                   [Italy](/italy) |           35,427 |                    36,028 |                     597 |                        601 |                                        2% |                                35,449 |                                 38,351 |
|                 [France](/france) |           30,508 |                    31,518 |                     470 |                      1,010 |                                        3% |                                30,551 |                                 35,816 |
|                   [Spain](/spain) |           28,838 |                    30,146 |                     642 |                      1,308 |                                        5% |                                28,876 |                                 34,655 |
|               [Belgium](/belgium) |            9,985 |                    10,530 |                     919 |                        545 |                                        5% |                                10,026 |                                 12,663 |
|               [Germany](/germany) |            9,266 |                     9,959 |                     120 |                        693 |                                        7% |                                 9,314 |                                 12,119 |
|       [Netherlands](/netherlands) |            6,219 |                     6,586 |                     381 |                        367 |                                        6% |                                 6,244 |                                  7,989 |
|               [Romania](/romania) |            3,196 |                     6,140 |                     316 |                      2,944 |                                       92% |                                 4,341 |                                  9,378 |
|                 [Sweden](/sweden) |            5,810 |                     5,956 |                     582 |                        146 |                                        3% |                                 5,834 |                                  6,053 |
|               [Ukraine](/ukraine) |            2,248 |                     4,840 |                     110 |                      2,592 |                                      115% |                                 3,111 |                                  8,583 |
|                 [Poland](/poland) |            1,938 |                     2,957 |                      78 |                      1,019 |                                       53% |                                 2,237 |                                  4,356 |
|       [Switzerland](/switzerland) |            2,000 |                     2,131 |                     248 |                        131 |                                        7% |                                 2,019 |                                  2,483 |
|             [Portugal](/portugal) |            1,792 |                     2,032 |                     198 |                        240 |                                       13% |                                 1,802 |                                  2,588 |
|               [Ireland](/ireland) |            1,776 |                     1,850 |                     377 |                         74 |                                        4% |                                 1,786 |                                  2,065 |
|               [Moldova](/moldova) |              929 |                     1,323 |                     327 |                        394 |                                       42% |                                 1,083 |                                  1,833 |
|             [Bulgaria](/bulgaria) |              539 |                     1,044 |                     149 |                        505 |                                       94% |                                   722 |                                  1,754 |
|                 [Serbia](/serbia) |              692 |                       958 |                     138 |                        266 |                                       38% |                                   798 |                                  1,187 |
|               [Belarus](/belarus) |              632 |                       826 |                      87 |                        194 |                                       31% |                                   741 |                                    997 |
|               [Austria](/austria) |              730 |                       813 |                      92 |                         83 |                                       11% |                                   742 |                                  1,028 |
|               [Denmark](/denmark) |              621 |                       698 |                     120 |                         77 |                                       12% |                                   637 |                                    879 |
|               [Hungary](/hungary) |              611 |                       688 |                      70 |                         77 |                                       13% |                                   618 |                                    880 |
|               [Czechia](/czechia) |              411 |                       612 |                      57 |                        201 |                                       49% |                                   454 |                                    947 |
|                 [Greece](/greece) |              238 |                       462 |                      43 |                        224 |                                       94% |                                   308 |                                    802 |
|               [Finland](/finland) |              334 |                       371 |                      67 |                         37 |                                       11% |                                   341 |                                    475 |
|                 [Norway](/norway) |              264 |                       317 |                      59 |                         53 |                                       20% |                                   276 |                                    436 |
|               [Croatia](/croatia) |              169 |                       261 |                      64 |                         92 |                                       55% |                                   199 |                                    388 |
|         [Luxembourg](/luxembourg) |              124 |                       163 |                     265 |                         39 |                                       31% |                                   137 |                                    211 |
|             [Slovenia](/slovenia) |              130 |                       161 |                      78 |                         31 |                                       24% |                                   135 |                                    217 |
|           [Lithuania](/lithuania) |               83 |                       106 |                      38 |                         23 |                                       27% |                                    87 |                                    147 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     79 |
|             [Slovakia](/slovakia) |               33 |                        57 |                      10 |                         24 |                                       73% |                                    37 |                                    110 |
|                 [Latvia](/latvia) |               33 |                        43 |                      22 |                         10 |                                       30% |                                    35 |                                     60 |
|                 [Cyprus](/cyprus) |               20 |                        28 |                      32 |                          8 |                                       40% |                                    23 |                                     38 |
|                   [Malta](/malta) |               10 |                        25 |                      51 |                         15 |                                      153% |                                    15 |                                     48 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                                       25% |                                    10 |                                     17 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          410,156 |                   662,872 |                     128 |                    252,716 |                                       62% |                               511,392 |                                925,023 |
|                             [Brazil](/brazil) |          113,358 |                   175,871 |                     833 |                     62,513 |                                       55% |                               137,559 |                                237,468 |
|                               [India](/india) |           55,794 |                   119,601 |                      88 |                     63,807 |                                      114% |                                80,388 |                                173,543 |
|                             [Mexico](/mexico) |           59,610 |                    95,747 |                     751 |                     36,137 |                                       61% |                                82,557 |                                125,854 |
|                                 [Peru](/peru) |           27,034 |                    35,633 |                   1,096 |                      8,599 |                                       32% |                                29,691 |                                 45,933 |
|                         [Colombia](/colombia) |           16,568 |                    30,119 |                     598 |                     13,551 |                                       82% |                                22,500 |                                 43,557 |
|                                 [Iran](/iran) |           20,376 |                    27,621 |                     333 |                      7,245 |                                       36% |                                22,796 |                                 36,237 |
|                 [South Africa](/south-africa) |           12,843 |                    22,165 |                     379 |                      9,322 |                                       73% |                                16,408 |                                 31,784 |
|                             [Russia](/russia) |           16,148 |                    21,700 |                     149 |                      5,552 |                                       34% |                                17,851 |                                 29,790 |
|                       [Argentina](/argentina) |            6,730 |                    18,874 |                     421 |                     12,144 |                                      180% |                                11,190 |                                 29,036 |
|                               [Chile](/chile) |           10,723 |                    14,377 |                     759 |                      3,654 |                                       34% |                                11,254 |                                 22,435 |
|                       [Indonesia](/indonesia) |            6,500 |                    10,718 |                      40 |                      4,218 |                                       65% |                                 8,033 |                                 17,208 |
|                             [Canada](/canada) |            9,110 |                     9,519 |                     254 |                        409 |                                        4% |                                 9,144 |                                 10,492 |
|                           [Ecuador](/ecuador) |            6,248 |                     7,552 |                     435 |                      1,304 |                                       21% |                                 6,395 |                                 10,360 |
|                             [Turkey](/turkey) |            6,080 |                     7,458 |                      89 |                      1,378 |                                       23% |                                 6,209 |                                 10,985 |
|                   [Philippines](/philippines) |            2,940 |                     7,386 |                      68 |                      4,446 |                                      151% |                                 4,100 |                                 14,056 |
|                           [Bolivia](/bolivia) |            4,366 |                     7,115 |                     618 |                      2,749 |                                       63% |                                 5,392 |                                 10,262 |
|                         [Pakistan](/pakistan) |            6,219 |                     6,950 |                      32 |                        731 |                                       12% |                                 6,322 |                                  8,004 |
|                               [Egypt](/egypt) |            5,231 |                     5,852 |                      58 |                        621 |                                       12% |                                 5,320 |                                  6,891 |
|                     [Bangladesh](/bangladesh) |            3,861 |                     5,817 |                      36 |                      1,956 |                                       51% |                                 4,337 |                                  8,924 |
|                 [Saudi Arabia](/saudi-arabia) |            3,580 |                     5,257 |                     153 |                      1,677 |                                       47% |                                 4,096 |                                  7,117 |
|                               [China](/china) |            4,709 |                     4,897 |                       3 |                        188 |                                        4% |                                 4,709 |                                  6,228 |
|                           [Morocco](/morocco) |              817 |                     3,631 |                     100 |                      2,814 |                                      344% |                                 1,712 |                                  7,392 |
|                             [Panama](/panama) |            1,859 |                     2,767 |                     651 |                        908 |                                       49% |                                 2,197 |                                  3,813 |
|     [Dominican Republic](/dominican-republic) |            1,533 |                     2,608 |                     243 |                      1,075 |                                       70% |                                 1,897 |                                  4,009 |
|                         [Honduras](/honduras) |            1,632 |                     2,525 |                     259 |                        893 |                                       55% |                                 1,959 |                                  3,639 |
|                               [Japan](/japan) |            1,175 |                     2,425 |                      19 |                      1,250 |                                      106% |                                 1,309 |                                  5,793 |
|                           [Algeria](/algeria) |            1,418 |                     2,145 |                      50 |                        727 |                                       51% |                                 1,585 |                                  3,386 |
|                             [Israel](/israel) |              809 |                     2,045 |                     240 |                      1,236 |                                      153% |                                 1,194 |                                  3,537 |
|                       [Australia](/australia) |              485 |                     1,405 |                      56 |                        920 |                                      190% |                                   784 |                                  2,640 |
|                           [Nigeria](/nigeria) |              996 |                     1,285 |                       6 |                        289 |                                       29% |                                 1,051 |                                  1,896 |
|                             [Kuwait](/kuwait) |              511 |                       722 |                     172 |                        211 |                                       41% |                                   544 |                                  1,183 |
| [United Arab Emirates](/united-arab-emirates) |              370 |                       458 |                      47 |                         88 |                                       24% |                                   375 |                                    684 |
|                   [South Korea](/south-korea) |              309 |                       361 |                       7 |                         52 |                                       17% |                                   309 |                                    529 |
|                         [Malaysia](/malaysia) |              125 |                       139 |                       4 |                         14 |                                       12% |                                   129 |                                    155 |
|                                 [Cuba](/cuba) |               89 |                       125 |                      11 |                         36 |                                       41% |                                    96 |                                    203 |
