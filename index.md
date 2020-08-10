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

* **August 10:** See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19.
* **August 5:** We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *August 3:* View our [updated historical performance](/about/#historical-performance).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 9 (3am ET):
<p align="center">
  Current Total: <b>162,420</b> deaths | Projected Total: <b>231,300 deaths by Nov 1, 2020</b> (Range: 204-270k)<br>
  Currently Infected: <b>1.9%</b> (1 in 53) | Total Infected: <b>12.7%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 9, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 18, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |         2% |         42% |        85% |         97% |        99% |
|              225,000 |         <1% |        <1% |         <1% |        11% |         32% |        54% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          3% |        12% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |
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
|             *[United States](/us)* |          162,420 |                   231,291 |                     697 |                     68,871 |                                       42% |                               204,134 |                                269,269 |
|                 [New York](/us-ny) |           32,768 |                    33,356 |                   1,715 |                        588 |                                        2% |                                32,799 |                                 35,926 |
|                    [Texas](/us-tx) |            9,058 |                    19,549 |                     674 |                     10,491 |                                      116% |                                14,479 |                                 25,662 |
|               [California](/us-ca) |           10,307 |                    19,374 |                     490 |                      9,067 |                                       88% |                                14,057 |                                 26,546 |
|                  [Florida](/us-fl) |            8,109 |                    16,809 |                     783 |                      8,700 |                                      107% |                                12,433 |                                 22,300 |
|               [New Jersey](/us-nj) |           15,869 |                    16,685 |                   1,878 |                        816 |                                        5% |                                15,933 |                                 19,096 |
|            [Massachusetts](/us-ma) |            8,721 |                     9,925 |                   1,428 |                      1,204 |                                       14% |                                 8,834 |                                 12,485 |
|                 [Illinois](/us-il) |            7,840 |                     9,858 |                     778 |                      2,018 |                                       26% |                                 8,215 |                                 13,033 |
|             [Pennsylvania](/us-pa) |            7,310 |                     8,497 |                     664 |                      1,187 |                                       16% |                                 7,420 |                                 10,643 |
|                 [Michigan](/us-mi) |            6,520 |                     7,375 |                     738 |                        855 |                                       13% |                                 6,597 |                                  9,029 |
|                  [Georgia](/us-ga) |            4,186 |                     7,254 |                     683 |                      3,068 |                                       73% |                                 5,524 |                                  9,843 |
|                  [Arizona](/us-az) |            4,137 |                     6,930 |                     952 |                      2,793 |                                       68% |                                 5,511 |                                  8,685 |
|                [Louisiana](/us-la) |            4,207 |                     5,646 |                   1,215 |                      1,439 |                                       34% |                                 4,782 |                                  6,950 |
|                     [Ohio](/us-oh) |            3,668 |                     5,564 |                     476 |                      1,896 |                                       52% |                                 4,217 |                                  7,819 |
|                 [Maryland](/us-md) |            3,577 |                     4,849 |                     802 |                      1,272 |                                       36% |                                 3,776 |                                  7,408 |
|              [Connecticut](/us-ct) |            4,441 |                     4,578 |                   1,284 |                        137 |                                        3% |                                 4,463 |                                  4,880 |
|                  [Indiana](/us-in) |            3,036 |                     4,225 |                     628 |                      1,189 |                                       39% |                                 3,178 |                                  6,354 |
|           [South Carolina](/us-sc) |            2,007 |                     4,210 |                     818 |                      2,203 |                                      110% |                                 3,105 |                                  5,559 |
|                 [Virginia](/us-va) |            2,322 |                     4,168 |                     488 |                      1,846 |                                       80% |                                 2,642 |                                  7,424 |
|           [North Carolina](/us-nc) |            2,184 |                     4,067 |                     388 |                      1,883 |                                       86% |                                 2,921 |                                  5,798 |
|              [Mississippi](/us-ms) |            1,874 |                     3,334 |                   1,120 |                      1,460 |                                       78% |                                 2,521 |                                  4,449 |
|                  [Alabama](/us-al) |            1,755 |                     3,030 |                     618 |                      1,275 |                                       73% |                                 2,332 |                                  3,991 |
|               [Washington](/us-wa) |            1,688 |                     2,981 |                     392 |                      1,293 |                                       77% |                                 2,021 |                                  4,752 |
|                [Tennessee](/us-tn) |            1,215 |                     2,550 |                     373 |                      1,335 |                                      110% |                                 1,800 |                                  3,572 |
|                 [Colorado](/us-co) |            1,857 |                     2,514 |                     436 |                        657 |                                       35% |                                 1,979 |                                  3,738 |
|                [Minnesota](/us-mn) |            1,689 |                     2,295 |                     407 |                        606 |                                       36% |                                 1,784 |                                  3,380 |
|                 [Missouri](/us-mo) |            1,327 |                     2,286 |                     372 |                        959 |                                       72% |                                 1,603 |                                  3,443 |
|                   [Nevada](/us-nv) |              949 |                     1,898 |                     616 |                        949 |                                      100% |                                 1,385 |                                  2,562 |
|                [Wisconsin](/us-wi) |              996 |                     1,819 |                     312 |                        823 |                                       83% |                                 1,213 |                                  2,943 |
|                     [Iowa](/us-ia) |              927 |                     1,486 |                     471 |                        559 |                                       60% |                                 1,083 |                                  2,193 |
|                 [Kentucky](/us-ky) |              772 |                     1,331 |                     298 |                        559 |                                       72% |                                   942 |                                  2,092 |
|                 [Oklahoma](/us-ok) |              603 |                     1,274 |                     322 |                        671 |                                      111% |                                   847 |                                  1,917 |
|                 [Arkansas](/us-ar) |              535 |                     1,193 |                     395 |                        658 |                                      123% |                                   813 |                                  1,705 |
|             [Rhode Island](/us-ri) |            1,014 |                     1,123 |                   1,060 |                        109 |                                       11% |                                 1,034 |                                  1,295 |
|               [New Mexico](/us-nm) |              681 |                     1,105 |                     527 |                        424 |                                       62% |                                   811 |                                  1,601 |
|              [Puerto Rico](/us-pr) |              274 |                       963 |                     302 |                        689 |                                      252% |                                   526 |                                  1,714 |
|                   [Oregon](/us-or) |              355 |                       865 |                     205 |                        510 |                                      144% |                                   532 |                                  1,381 |
|                     [Utah](/us-ut) |              335 |                       738 |                     230 |                        403 |                                      120% |                                   479 |                                  1,130 |
|                    [Idaho](/us-id) |              235 |                       737 |                     412 |                        502 |                                      213% |                                   464 |                                  1,085 |
|                   [Kansas](/us-ks) |              380 |                       702 |                     241 |                        322 |                                       85% |                                   483 |                                  1,107 |
|                 [Delaware](/us-de) |              590 |                       672 |                     690 |                         82 |                                       14% |                                   604 |                                    808 |
|     [District of Columbia](/us-dc) |              590 |                       651 |                     923 |                         61 |                                       10% |                                   602 |                                    756 |
|            [New Hampshire](/us-nh) |              419 |                       565 |                     416 |                        146 |                                       35% |                                   436 |                                    848 |
|                 [Nebraska](/us-ne) |              345 |                       530 |                     274 |                        185 |                                       54% |                                   415 |                                    812 |
|            [West Virginia](/us-wv) |              131 |                       381 |                     213 |                        250 |                                      191% |                                   204 |                                    735 |
|                  [Montana](/us-mt) |               75 |                       305 |                     285 |                        230 |                                      306% |                                   162 |                                    506 |
|             [South Dakota](/us-sd) |              146 |                       242 |                     274 |                         96 |                                       66% |                                   180 |                                    362 |
|             [North Dakota](/us-nd) |              112 |                       217 |                     285 |                        105 |                                       94% |                                   146 |                                    348 |
|                    [Maine](/us-me) |              125 |                       197 |                     146 |                         72 |                                       57% |                                   143 |                                    324 |
|                   [Hawaii](/us-hi) |               31 |                       151 |                     107 |                        120 |                                      388% |                                    53 |                                    418 |
|                  [Vermont](/us-vt) |               58 |                        78 |                     125 |                         20 |                                       35% |                                    62 |                                    114 |
|                   [Alaska](/us-ak) |               26 |                        74 |                     102 |                         48 |                                      186% |                                    42 |                                    131 |
|                  [Wyoming](/us-wy) |               28 |                        47 |                      81 |                         19 |                                       67% |                                    34 |                                     70 |
|           [Virgin Islands](/us-vi) |                9 |                        24 |                     233 |                         15 |                                      171% |                                    14 |                                     42 |
|                     [Guam](/us-gu) |                5 |                         8 |                      51 |                          3 |                                       70% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       58% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,847 |                   209,605 |                     353 |                     19,758 |                                       10% |                               193,789 |                                252,818 |
| [United Kingdom](/united-kingdom) |           46,651 |                    50,883 |                     753 |                      4,232 |                                        9% |                                46,967 |                                 60,693 |
|                   [Italy](/italy) |           35,203 |                    35,644 |                     591 |                        441 |                                        1% |                                35,230 |                                 37,084 |
|                 [France](/france) |           30,327 |                    31,080 |                     464 |                        753 |                                        2% |                                30,352 |                                 35,139 |
|                   [Spain](/spain) |           28,503 |                    30,045 |                     640 |                      1,542 |                                        5% |                                28,548 |                                 36,694 |
|               [Belgium](/belgium) |            9,870 |                    10,240 |                     894 |                        370 |                                        4% |                                 9,901 |                                 11,886 |
|               [Germany](/germany) |            9,201 |                    10,020 |                     121 |                        819 |                                        9% |                                 9,241 |                                 12,547 |
|               [Romania](/romania) |            2,659 |                     6,441 |                     332 |                      3,782 |                                      142% |                                 3,963 |                                 11,127 |
|       [Netherlands](/netherlands) |            6,178 |                     6,389 |                     370 |                        211 |                                        3% |                                 6,193 |                                  7,203 |
|                 [Sweden](/sweden) |            5,763 |                     6,049 |                     591 |                        286 |                                        5% |                                 5,824 |                                  6,336 |
|               [Ukraine](/ukraine) |            1,906 |                     4,306 |                      98 |                      2,400 |                                      126% |                                 2,648 |                                  7,379 |
|                 [Poland](/poland) |            1,800 |                     3,126 |                      82 |                      1,326 |                                       74% |                                 2,101 |                                  5,199 |
|       [Switzerland](/switzerland) |            1,986 |                     2,084 |                     243 |                         98 |                                        5% |                                 1,999 |                                  2,487 |
|             [Portugal](/portugal) |            1,750 |                     2,037 |                     198 |                        287 |                                       16% |                                 1,763 |                                  2,687 |
|               [Ireland](/ireland) |            1,772 |                     1,848 |                     377 |                         76 |                                        4% |                                 1,784 |                                  2,052 |
|               [Moldova](/moldova) |              841 |                     1,400 |                     346 |                        559 |                                       66% |                                 1,050 |                                  2,066 |
|             [Bulgaria](/bulgaria) |              445 |                     1,212 |                     173 |                        767 |                                      172% |                                   696 |                                  2,366 |
|                 [Serbia](/serbia) |              632 |                     1,147 |                     165 |                        515 |                                       81% |                                   814 |                                  1,774 |
|               [Austria](/austria) |              721 |                       841 |                      95 |                        120 |                                       17% |                                   741 |                                  1,165 |
|               [Belarus](/belarus) |              585 |                       810 |                      86 |                        225 |                                       38% |                                   718 |                                  1,013 |
|               [Denmark](/denmark) |              617 |                       697 |                     120 |                         80 |                                       13% |                                   631 |                                    897 |
|               [Hungary](/hungary) |              602 |                       696 |                      71 |                         94 |                                       16% |                                   611 |                                    925 |
|               [Czechia](/czechia) |              389 |                       568 |                      53 |                        179 |                                       46% |                                   421 |                                    938 |
|               [Finland](/finland) |              331 |                       369 |                      67 |                         38 |                                       12% |                                   340 |                                    444 |
|               [Croatia](/croatia) |              157 |                       347 |                      85 |                        190 |                                      121% |                                   211 |                                    650 |
|                 [Greece](/greece) |              211 |                       316 |                      29 |                        105 |                                       50% |                                   232 |                                    517 |
|                 [Norway](/norway) |              256 |                       289 |                      54 |                         33 |                                       13% |                                   262 |                                    378 |
|         [Luxembourg](/luxembourg) |              120 |                       211 |                     343 |                         91 |                                       76% |                                   143 |                                    395 |
|             [Slovenia](/slovenia) |              126 |                       195 |                      94 |                         69 |                                       55% |                                   142 |                                    341 |
|           [Lithuania](/lithuania) |               81 |                        99 |                      35 |                         18 |                                       22% |                                    86 |                                    126 |
|               [Estonia](/estonia) |               63 |                        73 |                      55 |                         10 |                                       16% |                                    69 |                                     86 |
|             [Slovakia](/slovakia) |               31 |                        51 |                       9 |                         20 |                                       64% |                                    34 |                                     99 |
|                 [Latvia](/latvia) |               32 |                        41 |                      21 |                          9 |                                       27% |                                    34 |                                     55 |
|                 [Cyprus](/cyprus) |               19 |                        26 |                      29 |                          7 |                                       35% |                                    21 |                                     34 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       34% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        11 |                      23 |                          2 |                                       27% |                                     9 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          351,712 |                   661,805 |                     128 |                    310,093 |                                       88% |                               463,496 |                                972,166 |
|                             [Brazil](/brazil) |          100,477 |                   179,066 |                     848 |                     78,589 |                                       78% |                               122,555 |                                254,738 |
|                               [India](/india) |           43,379 |                   123,856 |                      91 |                     80,477 |                                      186% |                                75,257 |                                178,584 |
|                             [Mexico](/mexico) |           52,006 |                    92,809 |                     727 |                     40,803 |                                       78% |                                73,826 |                                130,341 |
|                         [Colombia](/colombia) |           12,540 |                    32,160 |                     639 |                     19,620 |                                      156% |                                20,893 |                                 50,544 |
|                                 [Peru](/peru) |           20,649 |                    29,073 |                     894 |                      8,424 |                                       41% |                                22,504 |                                 40,131 |
|                                 [Iran](/iran) |           18,264 |                    28,006 |                     338 |                      9,742 |                                       53% |                                21,754 |                                 39,008 |
|                 [South Africa](/south-africa) |           10,210 |                    25,711 |                     439 |                     15,501 |                                      152% |                                16,971 |                                 37,383 |
|                             [Russia](/russia) |           14,827 |                    22,153 |                     152 |                      7,326 |                                       49% |                                17,076 |                                 33,271 |
|                       [Argentina](/argentina) |            4,523 |                    15,605 |                     348 |                     11,082 |                                      245% |                                 8,609 |                                 25,230 |
|                               [Chile](/chile) |           10,011 |                    14,073 |                     743 |                      4,062 |                                       41% |                                10,688 |                                 24,430 |
|                       [Indonesia](/indonesia) |            5,658 |                    11,809 |                      44 |                      6,151 |                                      109% |                                 7,692 |                                 20,901 |
|                             [Canada](/canada) |            9,024 |                     9,460 |                     253 |                        436 |                                        5% |                                 9,063 |                                 10,511 |
|                           [Bolivia](/bolivia) |            3,587 |                     7,820 |                     679 |                      4,233 |                                      118% |                                 5,081 |                                 12,840 |
|                           [Ecuador](/ecuador) |            5,916 |                     7,358 |                     424 |                      1,442 |                                       24% |                                 6,123 |                                 10,168 |
|                         [Pakistan](/pakistan) |            6,068 |                     7,145 |                      33 |                      1,077 |                                       18% |                                 6,252 |                                  8,538 |
|                             [Turkey](/turkey) |            5,829 |                     7,144 |                      86 |                      1,315 |                                       23% |                                 5,932 |                                 10,396 |
|                               [Egypt](/egypt) |            4,992 |                     6,495 |                      65 |                      1,503 |                                       30% |                                 5,152 |                                  8,820 |
|                     [Bangladesh](/bangladesh) |            3,365 |                     5,457 |                      33 |                      2,092 |                                       62% |                                 4,111 |                                  8,774 |
|                               [China](/china) |            4,681 |                     5,075 |                       4 |                        394 |                                        8% |                                 4,681 |                                  7,707 |
|                   [Philippines](/philippines) |            2,209 |                     4,982 |                      46 |                      2,773 |                                      126% |                                 2,518 |                                 10,985 |
|                 [Saudi Arabia](/saudi-arabia) |            3,130 |                     4,941 |                     144 |                      1,811 |                                       58% |                                 3,684 |                                  7,115 |
|                         [Honduras](/honduras) |            1,476 |                     3,050 |                     313 |                      1,574 |                                      107% |                                 1,953 |                                  5,420 |
|                             [Panama](/panama) |            1,609 |                     2,979 |                     702 |                      1,370 |                                       85% |                                 2,079 |                                  4,601 |
|                           [Morocco](/morocco) |              480 |                     2,974 |                      82 |                      2,494 |                                      520% |                                   974 |                                  7,387 |
|     [Dominican Republic](/dominican-republic) |            1,289 |                     2,545 |                     237 |                      1,256 |                                       97% |                                 1,677 |                                  4,420 |
|                           [Algeria](/algeria) |            1,293 |                     2,300 |                      53 |                      1,007 |                                       78% |                                 1,475 |                                  4,178 |
|                               [Japan](/japan) |            1,042 |                     1,729 |                      14 |                        687 |                                       66% |                                 1,059 |                                  4,443 |
|                             [Israel](/israel) |              593 |                     1,461 |                     172 |                        868 |                                      146% |                                   831 |                                  2,958 |
|                           [Nigeria](/nigeria) |              942 |                     1,398 |                       7 |                        456 |                                       48% |                                 1,054 |                                  2,361 |
|                       [Australia](/australia) |              295 |                     1,256 |                      50 |                        961 |                                      326% |                                   557 |                                  2,645 |
|                             [Kuwait](/kuwait) |              474 |                       814 |                     194 |                        340 |                                       72% |                                   519 |                                  1,638 |
| [United Arab Emirates](/united-arab-emirates) |              356 |                       455 |                      47 |                         99 |                                       28% |                                   363 |                                    738 |
|                   [South Korea](/south-korea) |              305 |                       382 |                       7 |                         77 |                                       25% |                                   305 |                                    627 |
|                         [Malaysia](/malaysia) |              125 |                       149 |                       5 |                         24 |                                       19% |                                   134 |                                    168 |
|                                 [Cuba](/cuba) |               88 |                       116 |                      10 |                         28 |                                       32% |                                    94 |                                    167 |
