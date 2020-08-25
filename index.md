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

* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 24 (7pm ET):
<p align="center">
  Current Total: <b>176,799</b> deaths | Projected Total: <b>221,000 deaths by Nov 1, 2020</b> (Range: 203-247k)<br>
  Currently Infected: <b>1.3%</b> (1 in 76) | Total Infected: <b>13.7%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 24, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 25, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          8% |        75% |         97% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          7% |        26% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         2% |
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
|             *[United States](/us)* |          176,799 |                   220,947 |                     666 |                     44,148 |                                       25% |                               203,649 |                                246,241 |
|                 [New York](/us-ny) |           32,883 |                    33,227 |                   1,708 |                        344 |                                        1% |                                32,897 |                                 34,925 |
|                    [Texas](/us-tx) |           11,699 |                    18,858 |                     650 |                      7,159 |                                       61% |                                15,480 |                                 23,353 |
|               [California](/us-ca) |           12,153 |                    18,551 |                     469 |                      6,398 |                                       53% |                                14,947 |                                 24,478 |
|               [New Jersey](/us-nj) |           15,946 |                    16,190 |                   1,823 |                        244 |                                        2% |                                15,967 |                                 16,859 |
|                  [Florida](/us-fl) |           10,325 |                    14,357 |                     668 |                      4,032 |                                       39% |                                12,322 |                                 16,979 |
|            [Massachusetts](/us-ma) |            8,921 |                     9,660 |                   1,390 |                        739 |                                        8% |                                 8,966 |                                 11,178 |
|                 [Illinois](/us-il) |            8,089 |                     9,358 |                     738 |                      1,269 |                                       16% |                                 8,252 |                                 11,577 |
|             [Pennsylvania](/us-pa) |            7,557 |                     8,515 |                     665 |                        958 |                                       13% |                                 7,627 |                                 10,478 |
|                  [Georgia](/us-ga) |            5,132 |                     7,533 |                     709 |                      2,401 |                                       47% |                                 6,302 |                                  9,592 |
|                 [Michigan](/us-mi) |            6,659 |                     7,271 |                     728 |                        612 |                                        9% |                                 6,718 |                                  8,413 |
|                  [Arizona](/us-az) |            4,771 |                     5,966 |                     820 |                      1,195 |                                       25% |                                 5,296 |                                  6,968 |
|                [Louisiana](/us-la) |            4,746 |                     5,854 |                   1,259 |                      1,108 |                                       23% |                                 5,215 |                                  6,925 |
|                     [Ohio](/us-oh) |            3,978 |                     5,422 |                     464 |                      1,444 |                                       36% |                                 4,344 |                                  7,394 |
|              [Connecticut](/us-ct) |            4,460 |                     4,547 |                   1,275 |                         87 |                                        2% |                                 4,473 |                                  4,782 |
|                 [Maryland](/us-md) |            3,691 |                     4,187 |                     693 |                        496 |                                       13% |                                 3,740 |                                  5,165 |
|                  [Indiana](/us-in) |            3,220 |                     4,159 |                     618 |                        939 |                                       29% |                                 3,339 |                                  5,580 |
|           [North Carolina](/us-nc) |            2,531 |                     3,876 |                     370 |                      1,345 |                                       53% |                                 3,108 |                                  5,264 |
|           [South Carolina](/us-sc) |            2,504 |                     3,823 |                     743 |                      1,319 |                                       53% |                                 3,155 |                                  4,835 |
|                 [Virginia](/us-va) |            2,467 |                     3,141 |                     368 |                        674 |                                       27% |                                 2,520 |                                  4,265 |
|              [Mississippi](/us-ms) |            2,240 |                     3,103 |                   1,043 |                        863 |                                       39% |                                 2,637 |                                  3,760 |
|                [Tennessee](/us-tn) |            1,567 |                     2,792 |                     409 |                      1,225 |                                       78% |                                 2,138 |                                  3,839 |
|                  [Alabama](/us-al) |            2,013 |                     2,768 |                     564 |                        755 |                                       37% |                                 2,371 |                                  3,461 |
|               [Washington](/us-wa) |            1,863 |                     2,666 |                     350 |                        803 |                                       43% |                                 2,083 |                                  3,725 |
|                [Minnesota](/us-mn) |            1,813 |                     2,334 |                     414 |                        521 |                                       29% |                                 1,899 |                                  3,101 |
|                 [Colorado](/us-co) |            1,918 |                     2,187 |                     380 |                        269 |                                       14% |                                 1,935 |                                  2,814 |
|                 [Missouri](/us-mo) |            1,453 |                     2,074 |                     338 |                        621 |                                       43% |                                 1,695 |                                  2,760 |
|                   [Nevada](/us-nv) |            1,197 |                     1,924 |                     625 |                        727 |                                       61% |                                 1,557 |                                  2,487 |
|                [Wisconsin](/us-wi) |            1,081 |                     1,571 |                     270 |                        490 |                                       45% |                                 1,248 |                                  2,168 |
|                     [Iowa](/us-ia) |            1,037 |                     1,527 |                     484 |                        490 |                                       47% |                                 1,194 |                                  2,143 |
|                 [Kentucky](/us-ky) |              872 |                     1,340 |                     300 |                        468 |                                       54% |                                 1,041 |                                  1,876 |
|                 [Oklahoma](/us-ok) |              726 |                     1,262 |                     319 |                        536 |                                       74% |                                   941 |                                  1,832 |
|                 [Arkansas](/us-ar) |              687 |                     1,208 |                     400 |                        521 |                                       76% |                                   926 |                                  1,660 |
|             [Rhode Island](/us-ri) |            1,030 |                     1,110 |                   1,048 |                         80 |                                        8% |                                 1,041 |                                  1,265 |
|               [New Mexico](/us-nm) |              745 |                     1,038 |                     495 |                        293 |                                       39% |                                   850 |                                  1,388 |
|              [Puerto Rico](/us-pr) |              390 |                       958 |                     300 |                        568 |                                      146% |                                   647 |                                  1,512 |
|                   [Oregon](/us-or) |              417 |                       741 |                     176 |                        324 |                                       78% |                                   541 |                                  1,126 |
|                 [Delaware](/us-de) |              600 |                       679 |                     697 |                         79 |                                       13% |                                   609 |                                    823 |
|     [District of Columbia](/us-dc) |              604 |                       653 |                     925 |                         49 |                                        8% |                                   613 |                                    737 |
|                   [Kansas](/us-ks) |              426 |                       651 |                     223 |                        225 |                                       53% |                                   510 |                                    934 |
|                     [Utah](/us-ut) |              385 |                       621 |                     194 |                        236 |                                       61% |                                   483 |                                    868 |
|                    [Idaho](/us-id) |              307 |                       599 |                     335 |                        292 |                                       95% |                                   443 |                                    847 |
|                 [Nebraska](/us-ne) |              378 |                       527 |                     272 |                        149 |                                       39% |                                   436 |                                    720 |
|            [New Hampshire](/us-nh) |              429 |                       495 |                     364 |                         66 |                                       15% |                                   433 |                                    656 |
|            [West Virginia](/us-wv) |              179 |                       391 |                     218 |                        212 |                                      118% |                                   261 |                                    641 |
|             [North Dakota](/us-nd) |              136 |                       246 |                     323 |                        110 |                                       81% |                                   179 |                                    374 |
|             [South Dakota](/us-sd) |              161 |                       237 |                     268 |                         76 |                                       47% |                                   188 |                                    331 |
|                  [Montana](/us-mt) |               90 |                       191 |                     179 |                        101 |                                      113% |                                   131 |                                    300 |
|                    [Maine](/us-me) |              131 |                       160 |                     119 |                         29 |                                       22% |                                   136 |                                    206 |
|                   [Hawaii](/us-hi) |               47 |                       146 |                     103 |                         99 |                                      210% |                                    81 |                                    270 |
|                  [Wyoming](/us-wy) |               37 |                        76 |                     132 |                         39 |                                      106% |                                    55 |                                    119 |
|                  [Vermont](/us-vt) |               58 |                        73 |                     117 |                         15 |                                       26% |                                    61 |                                    103 |
|                   [Alaska](/us-ak) |               32 |                        65 |                      89 |                         33 |                                      103% |                                    45 |                                    105 |
|           [Virgin Islands](/us-vi) |               10 |                        19 |                     182 |                          9 |                                       91% |                                    13 |                                     30 |
|                     [Guam](/us-gu) |                6 |                        19 |                     113 |                         13 |                                      212% |                                     8 |                                     57 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       53% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,447 |                   203,014 |                     342 |                     15,567 |                                        8% |                               190,790 |                                238,482 |
| [United Kingdom](/united-kingdom) |           41,515 |                    42,310 |                     627 |                        795 |                                        2% |                                41,540 |                                 45,240 |
|                   [Italy](/italy) |           35,437 |                    36,279 |                     601 |                        842 |                                        2% |                                35,472 |                                 39,546 |
|                 [France](/france) |           30,518 |                    31,768 |                     474 |                      1,250 |                                        4% |                                30,571 |                                 36,427 |
|                   [Spain](/spain) |           28,838 |                    30,412 |                     648 |                      1,574 |                                        5% |                                28,877 |                                 35,491 |
|               [Belgium](/belgium) |            9,992 |                    10,520 |                     918 |                        528 |                                        5% |                                10,032 |                                 12,571 |
|               [Germany](/germany) |            9,275 |                     9,998 |                     120 |                        723 |                                        8% |                                 9,323 |                                 12,269 |
|       [Netherlands](/netherlands) |            6,225 |                     6,603 |                     382 |                        378 |                                        6% |                                 6,250 |                                  8,118 |
|               [Romania](/romania) |            3,272 |                     6,166 |                     318 |                      2,894 |                                       88% |                                 4,366 |                                  9,628 |
|                 [Sweden](/sweden) |            5,810 |                     5,947 |                     581 |                        137 |                                        2% |                                 5,832 |                                  6,045 |
|               [Ukraine](/ukraine) |            2,313 |                     5,047 |                     115 |                      2,734 |                                      118% |                                 3,212 |                                  9,098 |
|                 [Poland](/poland) |            1,955 |                     2,934 |                      77 |                        979 |                                       50% |                                 2,236 |                                  4,377 |
|       [Switzerland](/switzerland) |            2,001 |                     2,131 |                     248 |                        130 |                                        7% |                                 2,020 |                                  2,490 |
|             [Portugal](/portugal) |            1,796 |                     2,033 |                     198 |                        237 |                                       13% |                                 1,805 |                                  2,593 |
|               [Ireland](/ireland) |            1,777 |                     1,853 |                     378 |                         76 |                                        4% |                                 1,787 |                                  2,086 |
|               [Moldova](/moldova) |              940 |                     1,327 |                     328 |                        387 |                                       41% |                                 1,083 |                                  1,878 |
|             [Bulgaria](/bulgaria) |              545 |                       959 |                     137 |                        414 |                                       76% |                                   705 |                                  1,514 |
|                 [Serbia](/serbia) |              698 |                       952 |                     137 |                        254 |                                       36% |                                   794 |                                  1,189 |
|               [Belarus](/belarus) |              642 |                       845 |                      89 |                        203 |                                       32% |                                   751 |                                  1,033 |
|               [Austria](/austria) |              732 |                       831 |                      94 |                         99 |                                       14% |                                   749 |                                  1,070 |
|               [Denmark](/denmark) |              622 |                       703 |                     121 |                         81 |                                       13% |                                   638 |                                    894 |
|               [Hungary](/hungary) |              613 |                       694 |                      71 |                         81 |                                       13% |                                   620 |                                    891 |
|               [Czechia](/czechia) |              412 |                       596 |                      56 |                        184 |                                       45% |                                   450 |                                    913 |
|                 [Greece](/greece) |              242 |                       474 |                      44 |                        232 |                                       96% |                                   312 |                                    842 |
|               [Finland](/finland) |              334 |                       371 |                      67 |                         37 |                                       11% |                                   340 |                                    480 |
|                 [Norway](/norway) |              264 |                       316 |                      59 |                         52 |                                       20% |                                   276 |                                    432 |
|               [Croatia](/croatia) |              171 |                       265 |                      65 |                         94 |                                       55% |                                   200 |                                    407 |
|             [Slovenia](/slovenia) |              131 |                       166 |                      80 |                         35 |                                       27% |                                   136 |                                    229 |
|         [Luxembourg](/luxembourg) |              124 |                       163 |                     265 |                         39 |                                       31% |                                   136 |                                    214 |
|           [Lithuania](/lithuania) |               84 |                       113 |                      40 |                         29 |                                       34% |                                    90 |                                    164 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     80 |
|             [Slovakia](/slovakia) |               33 |                        60 |                      11 |                         27 |                                       82% |                                    38 |                                    120 |
|                 [Latvia](/latvia) |               33 |                        42 |                      22 |                          9 |                                       28% |                                    35 |                                     57 |
|                 [Cyprus](/cyprus) |               20 |                        28 |                      32 |                          8 |                                       40% |                                    23 |                                     37 |
|                   [Malta](/malta) |               10 |                        23 |                      46 |                         13 |                                      126% |                                    14 |                                     41 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       29% |                                    10 |                                     18 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          417,351 |                   650,158 |                     125 |                    232,807 |                                       56% |                               501,077 |                                899,430 |
|                             [Brazil](/brazil) |          114,744 |                   170,939 |                     810 |                     56,195 |                                       49% |                               131,832 |                                231,359 |
|                               [India](/india) |           57,542 |                   117,488 |                      86 |                     59,946 |                                      104% |                                80,807 |                                170,346 |
|                             [Mexico](/mexico) |           60,480 |                    89,956 |                     705 |                     29,476 |                                       49% |                                75,243 |                                116,212 |
|                                 [Peru](/peru) |           27,453 |                    35,897 |                   1,104 |                      8,444 |                                       31% |                                30,255 |                                 45,590 |
|                         [Colombia](/colombia) |           17,316 |                    31,275 |                     621 |                     13,959 |                                       81% |                                23,354 |                                 44,175 |
|                                 [Iran](/iran) |           20,643 |                    27,733 |                     334 |                      7,090 |                                       34% |                                22,899 |                                 36,162 |
|                             [Russia](/russia) |           16,341 |                    21,939 |                     150 |                      5,598 |                                       34% |                                17,989 |                                 30,463 |
|                 [South Africa](/south-africa) |           13,059 |                    21,608 |                     369 |                      8,549 |                                       65% |                                15,959 |                                 30,928 |
|                       [Argentina](/argentina) |            6,985 |                    17,648 |                     394 |                     10,663 |                                      153% |                                11,076 |                                 26,889 |
|                               [Chile](/chile) |           10,852 |                    13,686 |                     722 |                      2,834 |                                       26% |                                11,307 |                                 19,846 |
|                       [Indonesia](/indonesia) |            6,680 |                    11,529 |                      43 |                      4,849 |                                       73% |                                 8,383 |                                 17,855 |
|                             [Canada](/canada) |            9,119 |                     9,536 |                     255 |                        417 |                                        5% |                                 9,165 |                                 10,488 |
|                           [Ecuador](/ecuador) |            6,310 |                     7,588 |                     437 |                      1,278 |                                       20% |                                 6,449 |                                 10,322 |
|                             [Turkey](/turkey) |            6,121 |                     7,537 |                      90 |                      1,416 |                                       23% |                                 6,249 |                                 11,377 |
|                           [Bolivia](/bolivia) |            4,509 |                     7,529 |                     654 |                      3,020 |                                       67% |                                 5,706 |                                 10,411 |
|                         [Pakistan](/pakistan) |            6,244 |                     6,957 |                      32 |                        713 |                                       11% |                                 6,339 |                                  8,036 |
|                   [Philippines](/philippines) |            2,998 |                     6,839 |                      63 |                      3,841 |                                      128% |                                 4,023 |                                 12,827 |
|                     [Bangladesh](/bangladesh) |            3,941 |                     5,899 |                      36 |                      1,958 |                                       50% |                                 4,539 |                                  8,349 |
|                               [Egypt](/egypt) |            5,262 |                     5,852 |                      58 |                        590 |                                       11% |                                 5,343 |                                  6,942 |
|                 [Saudi Arabia](/saudi-arabia) |            3,649 |                     5,373 |                     157 |                      1,724 |                                       47% |                                 4,152 |                                  7,431 |
|                               [China](/china) |            4,711 |                     4,815 |                       3 |                        104 |                                        2% |                                 4,711 |                                  5,613 |
|                           [Morocco](/morocco) |              888 |                     3,884 |                     106 |                      2,996 |                                      337% |                                 1,810 |                                  8,033 |
|                             [Panama](/panama) |            1,892 |                     2,701 |                     636 |                        809 |                                       43% |                                 2,218 |                                  3,724 |
|     [Dominican Republic](/dominican-republic) |            1,567 |                     2,603 |                     242 |                      1,036 |                                       66% |                                 1,921 |                                  3,934 |
|                         [Honduras](/honduras) |            1,654 |                     2,461 |                     253 |                        807 |                                       49% |                                 1,932 |                                  3,322 |
|                           [Algeria](/algeria) |            1,435 |                     2,210 |                      51 |                        775 |                                       54% |                                 1,555 |                                  3,811 |
|                             [Israel](/israel) |              834 |                     2,120 |                     249 |                      1,286 |                                      154% |                                 1,209 |                                  3,735 |
|                               [Japan](/japan) |            1,188 |                     2,031 |                      16 |                        843 |                                       71% |                                 1,318 |                                  3,931 |
|                       [Australia](/australia) |              517 |                     1,428 |                      57 |                        911 |                                      176% |                                   817 |                                  2,616 |
|                           [Nigeria](/nigeria) |            1,002 |                     1,275 |                       6 |                        273 |                                       27% |                                 1,054 |                                  1,862 |
|                             [Kuwait](/kuwait) |              515 |                       701 |                     167 |                        186 |                                       36% |                                   543 |                                  1,118 |
| [United Arab Emirates](/united-arab-emirates) |              375 |                       470 |                      48 |                         95 |                                       25% |                                   380 |                                    721 |
|                   [South Korea](/south-korea) |              309 |                       375 |                       7 |                         66 |                                       21% |                                   309 |                                    613 |
|                         [Malaysia](/malaysia) |              125 |                       139 |                       4 |                         14 |                                       11% |                                   129 |                                    154 |
|                                 [Cuba](/cuba) |               91 |                       138 |                      12 |                         47 |                                       52% |                                   102 |                                    235 |
