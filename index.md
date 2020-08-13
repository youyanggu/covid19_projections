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

* **August 13:** Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). Join us on the [YouTube live stream](https://www.youtube.com/channel/UCe9KREYNZuvgnDe0lQWi6Vw) at 2pm ET.
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 10:* View our [updated historical performance](/about/#historical-performance).
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 13 (2am ET):
<p align="center">
  Current Total: <b>166,023</b> deaths | Projected Total: <b>227,700 deaths by Nov 1, 2020</b> (Range: 203-261k)<br>
  Currently Infected: <b>1.7%</b> (1 in 57) | Total Infected: <b>13.1%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 13, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |        <1% |         32% |        82% |         96% |        99% |
|              225,000 |         <1% |        <1% |         <1% |         7% |         23% |        46% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         8% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          166,023 |                   227,699 |                     686 |                     61,676 |                                       37% |                               203,657 |                                260,943 |
|                 [New York](/us-ny) |           32,797 |                    33,244 |                   1,709 |                        447 |                                        1% |                                32,815 |                                 35,414 |
|               [California](/us-ca) |           10,753 |                    19,021 |                     481 |                      8,268 |                                       77% |                                14,228 |                                 25,810 |
|                    [Texas](/us-tx) |            9,527 |                    18,446 |                     636 |                      8,919 |                                       94% |                                14,020 |                                 23,649 |
|                  [Florida](/us-fl) |            8,765 |                    16,667 |                     776 |                      7,902 |                                       90% |                                12,811 |                                 21,498 |
|               [New Jersey](/us-nj) |           15,885 |                    16,264 |                   1,831 |                        379 |                                        2% |                                15,921 |                                 17,299 |
|            [Massachusetts](/us-ma) |            8,751 |                     9,755 |                   1,404 |                      1,004 |                                       11% |                                 8,841 |                                 11,933 |
|                 [Illinois](/us-il) |            7,881 |                     9,600 |                     758 |                      1,719 |                                       22% |                                 8,211 |                                 12,543 |
|             [Pennsylvania](/us-pa) |            7,380 |                     8,536 |                     667 |                      1,156 |                                       16% |                                 7,479 |                                 10,596 |
|                  [Georgia](/us-ga) |            4,456 |                     7,724 |                     727 |                      3,268 |                                       73% |                                 5,908 |                                 10,567 |
|                 [Michigan](/us-mi) |            6,539 |                     7,263 |                     727 |                        724 |                                       11% |                                 6,607 |                                  8,659 |
|                  [Arizona](/us-az) |            4,347 |                     6,875 |                     945 |                      2,528 |                                       58% |                                 5,582 |                                  8,443 |
|                [Louisiana](/us-la) |            4,356 |                     5,759 |                   1,239 |                      1,403 |                                       32% |                                 4,952 |                                  6,934 |
|                     [Ohio](/us-oh) |            3,734 |                     5,483 |                     469 |                      1,749 |                                       47% |                                 4,257 |                                  7,539 |
|                 [Maryland](/us-md) |            3,612 |                     4,626 |                     765 |                      1,014 |                                       28% |                                 3,725 |                                  6,633 |
|              [Connecticut](/us-ct) |            4,450 |                     4,580 |                   1,285 |                        130 |                                        3% |                                 4,470 |                                  4,869 |
|                  [Indiana](/us-in) |            3,086 |                     4,216 |                     626 |                      1,130 |                                       37% |                                 3,219 |                                  6,137 |
|           [North Carolina](/us-nc) |            2,290 |                     4,124 |                     393 |                      1,834 |                                       80% |                                 3,017 |                                  5,901 |
|           [South Carolina](/us-sc) |            2,144 |                     4,037 |                     784 |                      1,893 |                                       88% |                                 3,095 |                                  5,250 |
|                 [Virginia](/us-va) |            2,352 |                     3,818 |                     447 |                      1,466 |                                       62% |                                 2,656 |                                  6,086 |
|              [Mississippi](/us-ms) |            1,989 |                     3,261 |                   1,096 |                      1,272 |                                       64% |                                 2,572 |                                  4,137 |
|                  [Alabama](/us-al) |            1,882 |                     3,139 |                     640 |                      1,257 |                                       67% |                                 2,454 |                                  4,035 |
|               [Washington](/us-wa) |            1,724 |                     2,864 |                     376 |                      1,140 |                                       66% |                                 2,034 |                                  4,393 |
|                [Tennessee](/us-tn) |            1,289 |                     2,563 |                     375 |                      1,274 |                                       99% |                                 1,833 |                                  3,624 |
|                 [Colorado](/us-co) |            1,875 |                     2,355 |                     409 |                        480 |                                       26% |                                 1,921 |                                  3,276 |
|                [Minnesota](/us-mn) |            1,724 |                     2,319 |                     411 |                        595 |                                       35% |                                 1,818 |                                  3,353 |
|                 [Missouri](/us-mo) |            1,354 |                     2,145 |                     349 |                        791 |                                       58% |                                 1,595 |                                  3,105 |
|                   [Nevada](/us-nv) |              996 |                     1,877 |                     609 |                        881 |                                       88% |                                 1,387 |                                  2,497 |
|                [Wisconsin](/us-wi) |            1,011 |                     1,655 |                     284 |                        644 |                                       64% |                                 1,188 |                                  2,517 |
|                     [Iowa](/us-ia) |              953 |                     1,468 |                     465 |                        515 |                                       54% |                                 1,100 |                                  2,077 |
|                 [Kentucky](/us-ky) |              790 |                     1,275 |                     285 |                        485 |                                       61% |                                   933 |                                  1,866 |
|                 [Oklahoma](/us-ok) |              627 |                     1,228 |                     310 |                        601 |                                       96% |                                   850 |                                  1,783 |
|                 [Arkansas](/us-ar) |              572 |                     1,193 |                     395 |                        621 |                                      109% |                                   845 |                                  1,676 |
|             [Rhode Island](/us-ri) |            1,018 |                     1,122 |                   1,059 |                        104 |                                       10% |                                 1,037 |                                  1,288 |
|               [New Mexico](/us-nm) |              695 |                     1,052 |                     502 |                        357 |                                       51% |                                   821 |                                  1,488 |
|              [Puerto Rico](/us-pr) |              295 |                       982 |                     308 |                        687 |                                      233% |                                   552 |                                  1,770 |
|                   [Oregon](/us-or) |              375 |                       853 |                     202 |                        478 |                                      128% |                                   545 |                                  1,328 |
|                   [Kansas](/us-ks) |              397 |                       709 |                     243 |                        312 |                                       79% |                                   500 |                                  1,069 |
|                     [Utah](/us-ut) |              351 |                       699 |                     218 |                        348 |                                       99% |                                   476 |                                  1,054 |
|                 [Delaware](/us-de) |              592 |                       675 |                     694 |                         83 |                                       14% |                                   605 |                                    811 |
|     [District of Columbia](/us-dc) |              593 |                       651 |                     923 |                         58 |                                       10% |                                   604 |                                    750 |
|                    [Idaho](/us-id) |              246 |                       629 |                     352 |                        383 |                                      156% |                                   418 |                                    916 |
|                 [Nebraska](/us-ne) |              356 |                       534 |                     276 |                        178 |                                       50% |                                   424 |                                    788 |
|            [New Hampshire](/us-nh) |              420 |                       516 |                     379 |                         96 |                                       23% |                                   429 |                                    760 |
|            [West Virginia](/us-wv) |              153 |                       506 |                     283 |                        353 |                                      231% |                                   281 |                                    895 |
|                   [Hawaii](/us-hi) |               38 |                       286 |                     202 |                        248 |                                      652% |                                   100 |                                    661 |
|                  [Montana](/us-mt) |               80 |                       262 |                     245 |                        182 |                                      227% |                                   148 |                                    428 |
|             [North Dakota](/us-nd) |              120 |                       238 |                     313 |                        118 |                                       99% |                                   162 |                                    375 |
|             [South Dakota](/us-sd) |              147 |                       230 |                     260 |                         83 |                                       56% |                                   176 |                                    330 |
|                    [Maine](/us-me) |              126 |                       155 |                     115 |                         29 |                                       23% |                                   131 |                                    199 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     119 |                         16 |                                       28% |                                    61 |                                    103 |
|                   [Alaska](/us-ak) |               27 |                        68 |                      93 |                         41 |                                      151% |                                    41 |                                    114 |
|                  [Wyoming](/us-wy) |               29 |                        48 |                      83 |                         19 |                                       65% |                                    35 |                                     70 |
|           [Virgin Islands](/us-vi) |                9 |                        20 |                     188 |                         11 |                                      119% |                                    13 |                                     32 |
|                     [Guam](/us-gu) |                5 |                         8 |                      50 |                          3 |                                       67% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       56% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,605 |                   210,856 |                     356 |                     20,251 |                                       11% |                               194,346 |                                257,299 |
| [United Kingdom](/united-kingdom) |           46,791 |                    51,026 |                     756 |                      4,235 |                                        9% |                                47,039 |                                 61,847 |
|                   [Italy](/italy) |           35,225 |                    35,970 |                     596 |                        745 |                                        2% |                                35,254 |                                 38,572 |
|                 [France](/france) |           30,375 |                    31,309 |                     467 |                        934 |                                        3% |                                30,411 |                                 36,067 |
|                   [Spain](/spain) |           28,579 |                    29,997 |                     639 |                      1,418 |                                        5% |                                28,619 |                                 35,482 |
|               [Belgium](/belgium) |            9,900 |                    10,410 |                     909 |                        510 |                                        5% |                                 9,937 |                                 12,409 |
|               [Germany](/germany) |            9,213 |                    10,260 |                     124 |                      1,047 |                                       11% |                                 9,309 |                                 13,295 |
|       [Netherlands](/netherlands) |            6,182 |                     6,561 |                     380 |                        379 |                                        6% |                                 6,208 |                                  8,033 |
|               [Romania](/romania) |            2,807 |                     6,283 |                     324 |                      3,476 |                                      124% |                                 3,983 |                                 10,626 |
|                 [Sweden](/sweden) |            5,774 |                     5,954 |                     582 |                        180 |                                        3% |                                 5,809 |                                  6,069 |
|               [Ukraine](/ukraine) |            1,999 |                     4,883 |                     111 |                      2,884 |                                      144% |                                 2,805 |                                  9,257 |
|                 [Poland](/poland) |            1,830 |                     2,867 |                      76 |                      1,037 |                                       57% |                                 2,065 |                                  4,545 |
|       [Switzerland](/switzerland) |            1,991 |                     2,088 |                     243 |                         97 |                                        5% |                                 2,004 |                                  2,484 |
|             [Portugal](/portugal) |            1,764 |                     2,050 |                     200 |                        286 |                                       16% |                                 1,776 |                                  2,680 |
|               [Ireland](/ireland) |            1,774 |                     1,865 |                     380 |                         91 |                                        5% |                                 1,786 |                                  2,137 |
|               [Moldova](/moldova) |              863 |                     1,314 |                     325 |                        451 |                                       52% |                                 1,039 |                                  1,861 |
|             [Bulgaria](/bulgaria) |              482 |                     1,310 |                     187 |                        828 |                                      172% |                                   752 |                                  2,350 |
|                 [Serbia](/serbia) |              658 |                     1,108 |                     159 |                        450 |                                       68% |                                   823 |                                  1,660 |
|               [Austria](/austria) |              724 |                       820 |                      93 |                         96 |                                       13% |                                   738 |                                  1,066 |
|               [Belarus](/belarus) |              595 |                       798 |                      84 |                        203 |                                       34% |                                   716 |                                    991 |
|               [Denmark](/denmark) |              621 |                       730 |                     126 |                        109 |                                       18% |                                   642 |                                  1,030 |
|               [Hungary](/hungary) |              605 |                       695 |                      71 |                         90 |                                       15% |                                   613 |                                    916 |
|               [Czechia](/czechia) |              391 |                       529 |                      50 |                        138 |                                       35% |                                   416 |                                    811 |
|               [Finland](/finland) |              333 |                       376 |                      68 |                         43 |                                       13% |                                   340 |                                    490 |
|                 [Greece](/greece) |              216 |                       358 |                      33 |                        142 |                                       66% |                                   248 |                                    614 |
|               [Croatia](/croatia) |              160 |                       293 |                      72 |                        133 |                                       83% |                                   199 |                                    508 |
|                 [Norway](/norway) |              256 |                       293 |                      54 |                         37 |                                       14% |                                   263 |                                    391 |
|             [Slovenia](/slovenia) |              129 |                       197 |                      95 |                         68 |                                       53% |                                   146 |                                    330 |
|         [Luxembourg](/luxembourg) |              122 |                       192 |                     313 |                         70 |                                       58% |                                   142 |                                    320 |
|           [Lithuania](/lithuania) |               81 |                        97 |                      35 |                         16 |                                       19% |                                    84 |                                    130 |
|               [Estonia](/estonia) |               63 |                        72 |                      54 |                          9 |                                       14% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        49 |                       9 |                         18 |                                       59% |                                    34 |                                     93 |
|                 [Latvia](/latvia) |               32 |                        40 |                      21 |                          8 |                                       25% |                                    33 |                                     54 |
|                 [Cyprus](/cyprus) |               20 |                        38 |                      44 |                         18 |                                       91% |                                    25 |                                     67 |
|               [Iceland](/iceland) |               10 |                        13 |                      39 |                          3 |                                       31% |                                    10 |                                     19 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          368,522 |                   669,700 |                     129 |                    301,178 |                                       82% |                               484,574 |                                974,291 |
|                             [Brazil](/brazil) |          104,201 |                   175,154 |                     830 |                     70,953 |                                       68% |                               125,122 |                                247,107 |
|                               [India](/india) |           47,033 |                   123,206 |                      90 |                     76,173 |                                      162% |                                78,434 |                                176,382 |
|                             [Mexico](/mexico) |           54,666 |                   101,339 |                     794 |                     46,673 |                                       85% |                                83,093 |                                141,707 |
|                         [Colombia](/colombia) |           13,837 |                    31,757 |                     631 |                     17,920 |                                      130% |                                21,497 |                                 48,312 |
|                                 [Peru](/peru) |           21,501 |                    30,726 |                     945 |                      9,225 |                                       43% |                                24,836 |                                 42,105 |
|                                 [Iran](/iran) |           18,988 |                    27,896 |                     336 |                      8,908 |                                       47% |                                22,305 |                                 38,237 |
|                 [South Africa](/south-africa) |           11,010 |                    23,979 |                     409 |                     12,969 |                                      118% |                                16,093 |                                 35,029 |
|                             [Russia](/russia) |           15,231 |                    21,943 |                     150 |                      6,712 |                                       44% |                                17,397 |                                 31,746 |
|                       [Argentina](/argentina) |            5,213 |                    19,734 |                     441 |                     14,521 |                                      279% |                                 9,949 |                                 34,270 |
|                               [Chile](/chile) |           10,205 |                    15,150 |                     799 |                      4,945 |                                       48% |                                10,918 |                                 26,006 |
|                       [Indonesia](/indonesia) |            5,903 |                    11,181 |                      41 |                      5,278 |                                       89% |                                 7,700 |                                 19,008 |
|                             [Canada](/canada) |            9,052 |                     9,484 |                     254 |                        432 |                                        5% |                                 9,089 |                                 10,519 |
|                           [Ecuador](/ecuador) |            5,984 |                     7,476 |                     430 |                      1,492 |                                       25% |                                 6,154 |                                 10,686 |
|                             [Turkey](/turkey) |            5,891 |                     7,403 |                      89 |                      1,512 |                                       26% |                                 5,946 |                                 11,446 |
|                           [Bolivia](/bolivia) |            3,827 |                     7,385 |                     641 |                      3,558 |                                       93% |                                 5,100 |                                 11,842 |
|                         [Pakistan](/pakistan) |            6,129 |                     7,095 |                      33 |                        966 |                                       16% |                                 6,286 |                                  8,363 |
|                               [Egypt](/egypt) |            5,085 |                     5,917 |                      59 |                        832 |                                       16% |                                 5,239 |                                  7,176 |
|                   [Philippines](/philippines) |            2,404 |                     5,791 |                      54 |                      3,387 |                                      141% |                                 3,149 |                                 11,734 |
|                     [Bangladesh](/bangladesh) |            3,513 |                     5,569 |                      34 |                      2,056 |                                       59% |                                 4,046 |                                  8,981 |
|                 [Saudi Arabia](/saudi-arabia) |            3,269 |                     4,928 |                     144 |                      1,659 |                                       51% |                                 3,830 |                                  7,318 |
|                               [China](/china) |            4,697 |                     4,909 |                       3 |                        212 |                                        5% |                                 4,697 |                                  6,370 |
|                           [Morocco](/morocco) |              556 |                     3,057 |                      84 |                      2,501 |                                      450% |                                 1,131 |                                  7,079 |
|                             [Panama](/panama) |            1,703 |                     2,912 |                     686 |                      1,209 |                                       71% |                                 2,138 |                                  4,320 |
|                         [Honduras](/honduras) |            1,533 |                     2,800 |                     287 |                      1,267 |                                       83% |                                 1,911 |                                  4,447 |
|     [Dominican Republic](/dominican-republic) |            1,371 |                     2,649 |                     247 |                      1,278 |                                       93% |                                 1,788 |                                  4,406 |
|                           [Algeria](/algeria) |            1,333 |                     2,249 |                      52 |                        916 |                                       69% |                                 1,540 |                                  3,904 |
|                               [Japan](/japan) |            1,066 |                     1,716 |                      14 |                        650 |                                       61% |                                 1,105 |                                  4,105 |
|                       [Australia](/australia) |              361 |                     1,565 |                      62 |                      1,204 |                                      334% |                                   724 |                                  3,530 |
|                             [Israel](/israel) |              639 |                     1,515 |                     178 |                        876 |                                      137% |                                   896 |                                  2,893 |
|                           [Nigeria](/nigeria) |              956 |                     1,343 |                       7 |                        387 |                                       40% |                                 1,036 |                                  2,143 |
|                             [Kuwait](/kuwait) |              489 |                       775 |                     184 |                        286 |                                       58% |                                   531 |                                  1,423 |
| [United Arab Emirates](/united-arab-emirates) |              358 |                       449 |                      46 |                         91 |                                       26% |                                   364 |                                    699 |
|                   [South Korea](/south-korea) |              305 |                       375 |                       7 |                         70 |                                       23% |                                   305 |                                    613 |
|                         [Malaysia](/malaysia) |              125 |                       142 |                       4 |                         17 |                                       13% |                                   129 |                                    159 |
|                                 [Cuba](/cuba) |               88 |                       130 |                      11 |                         42 |                                       48% |                                    96 |                                    226 |
