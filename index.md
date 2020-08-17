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
### Updated Daily - Last Updated: August 17 (5pm ET):
<p align="center">
  Current Total: <b>170,049</b> deaths | Projected Total: <b>225,900 deaths by Nov 1, 2020</b> (Range: 204-256k)<br>
  Currently Infected: <b>1.6%</b> (1 in 62) | Total Infected: <b>13.4%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 17, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              175,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |        <1% |         25% |        83% |         97% |        99% |
|              225,000 |        <1% |         <1% |         3% |         18% |        42% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         6% |
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
|             *[United States](/us)* |          170,049 |                   225,894 |                     681 |                     55,845 |                                       33% |                               204,357 |                                255,877 |
|                 [New York](/us-ny) |           32,840 |                    33,253 |                   1,709 |                        413 |                                        1% |                                32,857 |                                 35,246 |
|                    [Texas](/us-tx) |           10,396 |                    18,773 |                     647 |                      8,377 |                                       81% |                                14,864 |                                 23,386 |
|               [California](/us-ca) |           11,243 |                    18,770 |                     475 |                      7,527 |                                       67% |                                14,467 |                                 25,027 |
|                  [Florida](/us-fl) |            9,452 |                    16,874 |                     786 |                      7,422 |                                       79% |                                13,189 |                                 21,378 |
|               [New Jersey](/us-nj) |           15,912 |                    16,120 |                   1,815 |                        208 |                                        1% |                                15,931 |                                 16,710 |
|            [Massachusetts](/us-ma) |            8,838 |                     9,873 |                   1,421 |                      1,035 |                                       12% |                                 8,929 |                                 11,955 |
|                 [Illinois](/us-il) |            7,955 |                     9,402 |                     742 |                      1,447 |                                       18% |                                 8,144 |                                 12,222 |
|             [Pennsylvania](/us-pa) |            7,453 |                     8,715 |                     681 |                      1,262 |                                       17% |                                 7,565 |                                 11,179 |
|                  [Georgia](/us-ga) |            4,702 |                     7,696 |                     725 |                      2,994 |                                       64% |                                 6,093 |                                 10,135 |
|                 [Michigan](/us-mi) |            6,592 |                     7,321 |                     733 |                        729 |                                       11% |                                 6,657 |                                  8,634 |
|                  [Arizona](/us-az) |            4,506 |                     6,672 |                     917 |                      2,166 |                                       48% |                                 5,566 |                                  8,144 |
|                [Louisiana](/us-la) |            4,507 |                     5,790 |                   1,246 |                      1,283 |                                       28% |                                 5,057 |                                  6,842 |
|                     [Ohio](/us-oh) |            3,826 |                     5,459 |                     467 |                      1,633 |                                       43% |                                 4,349 |                                  7,302 |
|              [Connecticut](/us-ct) |            4,453 |                     4,553 |                   1,277 |                        100 |                                        2% |                                 4,468 |                                  4,806 |
|                 [Maryland](/us-md) |            3,639 |                     4,433 |                     733 |                        794 |                                       22% |                                 3,704 |                                  5,975 |
|                  [Indiana](/us-in) |            3,133 |                     4,194 |                     623 |                      1,061 |                                       34% |                                 3,257 |                                  5,889 |
|           [South Carolina](/us-sc) |            2,269 |                     3,937 |                     765 |                      1,668 |                                       74% |                                 3,075 |                                  5,044 |
|           [North Carolina](/us-nc) |            2,347 |                     3,897 |                     372 |                      1,550 |                                       66% |                                 2,961 |                                  5,401 |
|                 [Virginia](/us-va) |            2,381 |                     3,434 |                     402 |                      1,053 |                                       44% |                                 2,546 |                                  5,173 |
|              [Mississippi](/us-ms) |            2,084 |                     3,202 |                   1,076 |                      1,118 |                                       54% |                                 2,604 |                                  3,974 |
|                  [Alabama](/us-al) |            1,898 |                     2,903 |                     592 |                      1,005 |                                       53% |                                 2,349 |                                  3,673 |
|               [Washington](/us-wa) |            1,781 |                     2,844 |                     373 |                      1,063 |                                       60% |                                 2,102 |                                  4,192 |
|                [Tennessee](/us-tn) |            1,366 |                     2,533 |                     371 |                      1,167 |                                       85% |                                 1,877 |                                  3,536 |
|                 [Colorado](/us-co) |            1,896 |                     2,342 |                     407 |                        446 |                                       23% |                                 1,938 |                                  3,169 |
|                [Minnesota](/us-mn) |            1,752 |                     2,293 |                     407 |                        541 |                                       31% |                                 1,841 |                                  3,191 |
|                 [Missouri](/us-mo) |            1,383 |                     2,061 |                     336 |                        678 |                                       49% |                                 1,604 |                                  2,828 |
|                   [Nevada](/us-nv) |            1,072 |                     1,914 |                     621 |                        842 |                                       79% |                                 1,467 |                                  2,486 |
|                [Wisconsin](/us-wi) |            1,039 |                     1,611 |                     277 |                        572 |                                       55% |                                 1,226 |                                  2,343 |
|                     [Iowa](/us-ia) |              975 |                     1,450 |                     459 |                        475 |                                       49% |                                 1,118 |                                  1,993 |
|                 [Kentucky](/us-ky) |              810 |                     1,255 |                     281 |                        445 |                                       55% |                                   949 |                                  1,780 |
|                 [Oklahoma](/us-ok) |              661 |                     1,229 |                     311 |                        568 |                                       86% |                                   880 |                                  1,776 |
|                 [Arkansas](/us-ar) |              599 |                     1,143 |                     379 |                        544 |                                       91% |                                   834 |                                  1,577 |
|             [Rhode Island](/us-ri) |            1,021 |                     1,107 |                   1,045 |                         86 |                                        8% |                                 1,034 |                                  1,265 |
|              [Puerto Rico](/us-pr) |              335 |                     1,059 |                     332 |                        724 |                                      216% |                                   629 |                                  1,813 |
|               [New Mexico](/us-nm) |              714 |                     1,032 |                     492 |                        318 |                                       45% |                                   825 |                                  1,407 |
|                   [Oregon](/us-or) |              388 |                       784 |                     186 |                        396 |                                      102% |                                   528 |                                  1,191 |
|                   [Kansas](/us-ks) |              406 |                       682 |                     234 |                        276 |                                       68% |                                   501 |                                  1,007 |
|                 [Delaware](/us-de) |              593 |                       681 |                     700 |                         88 |                                       15% |                                   603 |                                    841 |
|                     [Utah](/us-ut) |              363 |                       659 |                     206 |                        296 |                                       82% |                                   473 |                                    970 |
|     [District of Columbia](/us-dc) |              597 |                       652 |                     923 |                         55 |                                        9% |                                   607 |                                    744 |
|                    [Idaho](/us-id) |              269 |                       613 |                     343 |                        344 |                                      128% |                                   429 |                                    871 |
|                 [Nebraska](/us-ne) |              361 |                       522 |                     270 |                        161 |                                       45% |                                   424 |                                    738 |
|            [New Hampshire](/us-nh) |              423 |                       493 |                     362 |                         70 |                                       16% |                                   428 |                                    651 |
|            [West Virginia](/us-wv) |              160 |                       433 |                     242 |                        273 |                                      171% |                                   264 |                                    722 |
|             [South Dakota](/us-sd) |              153 |                       233 |                     263 |                         80 |                                       52% |                                   182 |                                    329 |
|             [North Dakota](/us-nd) |              125 |                       232 |                     304 |                        107 |                                       85% |                                   164 |                                    346 |
|                  [Montana](/us-mt) |               82 |                       220 |                     206 |                        138 |                                      169% |                                   135 |                                    359 |
|                   [Hawaii](/us-hi) |               40 |                       179 |                     126 |                        139 |                                      346% |                                    79 |                                    401 |
|                    [Maine](/us-me) |              127 |                       155 |                     115 |                         28 |                                       22% |                                   132 |                                    198 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     118 |                         16 |                                       27% |                                    61 |                                    102 |
|                   [Alaska](/us-ak) |               28 |                        63 |                      86 |                         35 |                                      124% |                                    41 |                                    103 |
|                  [Wyoming](/us-wy) |               30 |                        49 |                      85 |                         19 |                                       64% |                                    38 |                                     71 |
|           [Virgin Islands](/us-vi) |                9 |                        18 |                     173 |                          9 |                                      101% |                                    12 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      49 |                          3 |                                       62% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       55% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          191,394 |                   208,212 |                     351 |                     16,818 |                                        9% |                               194,899 |                                247,078 |
| [United Kingdom](/united-kingdom) |           46,791 |                    48,504 |                     718 |                      1,713 |                                        4% |                                46,856 |                                 54,322 |
|                   [Italy](/italy) |           35,396 |                    36,080 |                     598 |                        684 |                                        2% |                                35,422 |                                 38,564 |
|                 [France](/france) |           30,410 |                    31,485 |                     470 |                      1,075 |                                        4% |                                30,456 |                                 36,052 |
|                   [Spain](/spain) |           28,617 |                    29,900 |                     637 |                      1,283 |                                        4% |                                28,654 |                                 34,642 |
|               [Belgium](/belgium) |            9,939 |                    10,552 |                     921 |                        613 |                                        6% |                                 9,984 |                                 12,951 |
|               [Germany](/germany) |            9,235 |                    10,017 |                     121 |                        782 |                                        8% |                                 9,288 |                                 12,479 |
|       [Netherlands](/netherlands) |            6,194 |                     6,567 |                     380 |                        373 |                                        6% |                                 6,219 |                                  8,012 |
|               [Romania](/romania) |            2,991 |                     6,423 |                     331 |                      3,432 |                                      115% |                                 4,223 |                                 10,393 |
|                 [Sweden](/sweden) |            5,783 |                     5,946 |                     581 |                        163 |                                        3% |                                 5,811 |                                  6,052 |
|               [Ukraine](/ukraine) |            2,100 |                     4,714 |                     107 |                      2,614 |                                      124% |                                 2,901 |                                  8,755 |
|                 [Poland](/poland) |            1,877 |                     2,917 |                      77 |                      1,040 |                                       55% |                                 2,147 |                                  4,518 |
|       [Switzerland](/switzerland) |            1,991 |                     2,127 |                     248 |                        136 |                                        7% |                                 2,011 |                                  2,527 |
|             [Portugal](/portugal) |            1,778 |                     2,055 |                     200 |                        277 |                                       16% |                                 1,789 |                                  2,677 |
|               [Ireland](/ireland) |            1,774 |                     1,856 |                     378 |                         82 |                                        5% |                                 1,785 |                                  2,095 |
|               [Moldova](/moldova) |              896 |                     1,374 |                     340 |                        478 |                                       53% |                                 1,073 |                                  1,972 |
|                 [Serbia](/serbia) |              674 |                     1,009 |                     145 |                        335 |                                       50% |                                   810 |                                  1,340 |
|             [Bulgaria](/bulgaria) |              498 |                     1,009 |                     144 |                        511 |                                      103% |                                   678 |                                  1,820 |
|               [Austria](/austria) |              728 |                       823 |                      93 |                         95 |                                       13% |                                   742 |                                  1,064 |
|               [Belarus](/belarus) |              610 |                       805 |                      85 |                        195 |                                       32% |                                   725 |                                    989 |
|               [Denmark](/denmark) |              621 |                       715 |                     123 |                         94 |                                       15% |                                   640 |                                    955 |
|               [Hungary](/hungary) |              608 |                       694 |                      71 |                         86 |                                       14% |                                   616 |                                    904 |
|               [Czechia](/czechia) |              397 |                       542 |                      51 |                        145 |                                       37% |                                   424 |                                    835 |
|                 [Greece](/greece) |              228 |                       466 |                      43 |                        238 |                                      105% |                                   290 |                                    834 |
|               [Finland](/finland) |              333 |                       372 |                      68 |                         39 |                                       12% |                                   340 |                                    482 |
|                 [Norway](/norway) |              261 |                       315 |                      59 |                         54 |                                       21% |                                   274 |                                    439 |
|               [Croatia](/croatia) |              166 |                       298 |                      73 |                        132 |                                       80% |                                   207 |                                    503 |
|         [Luxembourg](/luxembourg) |              123 |                       175 |                     284 |                         52 |                                       42% |                                   138 |                                    251 |
|             [Slovenia](/slovenia) |              129 |                       166 |                      80 |                         37 |                                       29% |                                   135 |                                    233 |
|           [Lithuania](/lithuania) |               81 |                        95 |                      34 |                         14 |                                       18% |                                    84 |                                    125 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     79 |
|             [Slovakia](/slovakia) |               31 |                        45 |                       8 |                         14 |                                       47% |                                    33 |                                     81 |
|                 [Latvia](/latvia) |               32 |                        39 |                      20 |                          7 |                                       22% |                                    33 |                                     51 |
|                 [Cyprus](/cyprus) |               20 |                        32 |                      36 |                         12 |                                       58% |                                    24 |                                     49 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       28% |                                    10 |                                     18 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       30% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          388,472 |                   661,812 |                     128 |                    273,340 |                                       70% |                               490,698 |                                955,247 |
|                             [Brazil](/brazil) |          107,852 |                   171,984 |                     815 |                     64,132 |                                       59% |                               126,088 |                                242,036 |
|                               [India](/india) |           50,921 |                   120,826 |                      88 |                     69,905 |                                      137% |                                77,569 |                                178,880 |
|                             [Mexico](/mexico) |           56,757 |                    98,418 |                     771 |                     41,661 |                                       73% |                                82,196 |                                134,156 |
|                                 [Peru](/peru) |           26,075 |                    36,800 |                   1,132 |                     10,725 |                                       41% |                                29,532 |                                 48,978 |
|                         [Colombia](/colombia) |           15,097 |                    31,099 |                     618 |                     16,002 |                                      106% |                                21,959 |                                 46,697 |
|                                 [Iran](/iran) |           19,639 |                    27,810 |                     335 |                      8,171 |                                       42% |                                22,509 |                                 37,668 |
|                 [South Africa](/south-africa) |           11,839 |                    22,324 |                     381 |                     10,485 |                                       89% |                                15,619 |                                 32,457 |
|                             [Russia](/russia) |           15,653 |                    22,000 |                     151 |                      6,347 |                                       41% |                                17,671 |                                 31,203 |
|                       [Argentina](/argentina) |            5,703 |                    16,274 |                     363 |                     10,571 |                                      185% |                                 9,590 |                                 27,425 |
|                               [Chile](/chile) |           10,452 |                    14,270 |                     753 |                      3,818 |                                       37% |                                11,060 |                                 22,680 |
|                       [Indonesia](/indonesia) |            6,150 |                    10,816 |                      40 |                      4,666 |                                       76% |                                 7,833 |                                 17,854 |
|                             [Canada](/canada) |            9,074 |                     9,492 |                     254 |                        418 |                                        5% |                                 9,109 |                                 10,496 |
|                             [Turkey](/turkey) |            5,974 |                     7,430 |                      89 |                      1,456 |                                       24% |                                 6,068 |                                 11,218 |
|                           [Ecuador](/ecuador) |            6,070 |                     7,410 |                     427 |                      1,340 |                                       22% |                                 6,219 |                                 10,376 |
|                   [Philippines](/philippines) |            2,665 |                     7,208 |                      67 |                      4,543 |                                      170% |                                 3,767 |                                 15,469 |
|                           [Bolivia](/bolivia) |            4,058 |                     7,150 |                     621 |                      3,092 |                                       76% |                                 5,217 |                                 10,922 |
|                         [Pakistan](/pakistan) |            6,175 |                     7,031 |                      32 |                        856 |                                       14% |                                 6,312 |                                  8,196 |
|                               [Egypt](/egypt) |            5,160 |                     5,899 |                      59 |                        739 |                                       14% |                                 5,283 |                                  7,058 |
|                     [Bangladesh](/bangladesh) |            3,657 |                     5,641 |                      35 |                      1,984 |                                       54% |                                 4,154 |                                  8,806 |
|                 [Saudi Arabia](/saudi-arabia) |            3,408 |                     5,148 |                     150 |                      1,740 |                                       51% |                                 3,955 |                                  7,175 |
|                               [China](/china) |            4,703 |                     4,909 |                       3 |                        206 |                                        4% |                                 4,703 |                                  6,337 |
|                           [Morocco](/morocco) |              658 |                     3,314 |                      91 |                      2,656 |                                      404% |                                 1,417 |                                  7,258 |
|                             [Panama](/panama) |            1,767 |                     2,797 |                     659 |                      1,030 |                                       58% |                                 2,120 |                                  4,007 |
|     [Dominican Republic](/dominican-republic) |            1,453 |                     2,700 |                     251 |                      1,247 |                                       86% |                                 1,864 |                                  4,400 |
|                         [Honduras](/honduras) |            1,575 |                     2,671 |                     274 |                      1,096 |                                       70% |                                 1,964 |                                  3,975 |
|                           [Algeria](/algeria) |            1,370 |                     2,175 |                      51 |                        805 |                                       59% |                                 1,533 |                                  3,654 |
|                               [Japan](/japan) |            1,103 |                     1,974 |                      16 |                        871 |                                       79% |                                 1,177 |                                  4,711 |
|                             [Israel](/israel) |              685 |                     1,554 |                     182 |                        869 |                                      127% |                                   962 |                                  2,907 |
|                       [Australia](/australia) |              421 |                     1,525 |                      61 |                      1,104 |                                      262% |                                   765 |                                  3,244 |
|                           [Nigeria](/nigeria) |              975 |                     1,319 |                       7 |                        344 |                                       35% |                                 1,043 |                                  2,057 |
|                             [Kuwait](/kuwait) |              501 |                       766 |                     182 |                        265 |                                       53% |                                   541 |                                  1,349 |
| [United Arab Emirates](/united-arab-emirates) |              364 |                       455 |                      47 |                         91 |                                       25% |                                   370 |                                    699 |
|                   [South Korea](/south-korea) |              305 |                       355 |                       7 |                         50 |                                       17% |                                   305 |                                    523 |
|                         [Malaysia](/malaysia) |              125 |                       141 |                       4 |                         16 |                                       12% |                                   129 |                                    157 |
|                                 [Cuba](/cuba) |               88 |                       128 |                      11 |                         40 |                                       45% |                                    95 |                                    219 |
