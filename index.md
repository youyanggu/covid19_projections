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

* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 10:* View our [updated historical performance](/about/#historical-performance).
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 15 (2am ET):
<p align="center">
  Current Total: <b>168,443</b> deaths | Projected Total: <b>229,200 deaths by Nov 1, 2020</b> (Range: 206-261k)<br>
  Currently Infected: <b>1.8%</b> (1 in 57) | Total Infected: <b>13.5%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 15, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 18, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |        <1% |         36% |        90% |         99% |        99% |
|              225,000 |         <1% |        <1% |         <1% |         7% |         25% |        50% |
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
|             *[United States](/us)* |          168,443 |                   229,215 |                     691 |                     60,772 |                                       36% |                               206,494 |                                260,700 |
|                 [New York](/us-ny) |           32,827 |                    33,260 |                   1,710 |                        433 |                                        1% |                                32,844 |                                 35,339 |
|               [California](/us-ca) |           11,148 |                    20,847 |                     528 |                      9,699 |                                       87% |                                16,372 |                                 27,545 |
|                    [Texas](/us-tx) |           10,078 |                    19,024 |                     656 |                      8,946 |                                       89% |                                14,628 |                                 24,112 |
|                  [Florida](/us-fl) |            9,141 |                    16,719 |                     778 |                      7,578 |                                       83% |                                13,162 |                                 21,317 |
|               [New Jersey](/us-nj) |           15,903 |                    16,267 |                   1,831 |                        364 |                                        2% |                                15,938 |                                 17,273 |
|            [Massachusetts](/us-ma) |            8,804 |                     9,865 |                   1,420 |                      1,061 |                                       12% |                                 8,899 |                                 12,013 |
|                 [Illinois](/us-il) |            7,932 |                     9,654 |                     762 |                      1,722 |                                       22% |                                 8,259 |                                 12,479 |
|             [Pennsylvania](/us-pa) |            7,434 |                     8,622 |                     673 |                      1,188 |                                       16% |                                 7,536 |                                 10,651 |
|                  [Georgia](/us-ga) |            4,573 |                     7,524 |                     709 |                      2,951 |                                       65% |                                 5,953 |                                  9,896 |
|                 [Michigan](/us-mi) |            6,566 |                     7,296 |                     731 |                        730 |                                       11% |                                 6,633 |                                  8,628 |
|                  [Arizona](/us-az) |            4,423 |                     6,704 |                     921 |                      2,281 |                                       52% |                                 5,548 |                                  8,230 |
|                [Louisiana](/us-la) |            4,430 |                     5,759 |                   1,239 |                      1,329 |                                       30% |                                 4,999 |                                  6,865 |
|                     [Ohio](/us-oh) |            3,784 |                     5,467 |                     468 |                      1,683 |                                       44% |                                 4,318 |                                  7,388 |
|                 [Maryland](/us-md) |            3,631 |                     4,594 |                     760 |                        963 |                                       27% |                                 3,740 |                                  6,471 |
|              [Connecticut](/us-ct) |            4,453 |                     4,579 |                   1,284 |                        126 |                                        3% |                                 4,473 |                                  4,861 |
|                  [Indiana](/us-in) |            3,113 |                     4,211 |                     625 |                      1,098 |                                       35% |                                 3,244 |                                  5,994 |
|           [South Carolina](/us-sc) |            2,204 |                     3,937 |                     765 |                      1,733 |                                       79% |                                 3,047 |                                  5,073 |
|           [North Carolina](/us-nc) |            2,313 |                     3,931 |                     375 |                      1,618 |                                       70% |                                 2,958 |                                  5,494 |
|                 [Virginia](/us-va) |            2,370 |                     3,706 |                     434 |                      1,336 |                                       56% |                                 2,662 |                                  5,770 |
|              [Mississippi](/us-ms) |            2,043 |                     3,230 |                   1,085 |                      1,187 |                                       58% |                                 2,596 |                                  4,041 |
|                  [Alabama](/us-al) |            1,893 |                     2,988 |                     609 |                      1,095 |                                       58% |                                 2,394 |                                  3,798 |
|               [Washington](/us-wa) |            1,755 |                     2,852 |                     375 |                      1,097 |                                       63% |                                 2,078 |                                  4,268 |
|                [Tennessee](/us-tn) |            1,326 |                     2,524 |                     369 |                      1,198 |                                       90% |                                 1,848 |                                  3,550 |
|                 [Colorado](/us-co) |            1,888 |                     2,352 |                     408 |                        464 |                                       25% |                                 1,933 |                                  3,214 |
|                [Minnesota](/us-mn) |            1,739 |                     2,310 |                     410 |                        571 |                                       33% |                                 1,833 |                                  3,268 |
|                 [Missouri](/us-mo) |            1,365 |                     2,093 |                     341 |                        728 |                                       53% |                                 1,594 |                                  2,968 |
|                   [Nevada](/us-nv) |            1,045 |                     1,935 |                     628 |                        890 |                                       85% |                                 1,464 |                                  2,539 |
|                [Wisconsin](/us-wi) |            1,025 |                     1,611 |                     277 |                        586 |                                       57% |                                 1,214 |                                  2,380 |
|                     [Iowa](/us-ia) |              970 |                     1,469 |                     466 |                        499 |                                       51% |                                 1,120 |                                  2,038 |
|                 [Kentucky](/us-ky) |              804 |                     1,277 |                     286 |                        473 |                                       59% |                                   952 |                                  1,831 |
|                 [Oklahoma](/us-ok) |              644 |                     1,219 |                     308 |                        575 |                                       89% |                                   864 |                                  1,752 |
|                 [Arkansas](/us-ar) |              587 |                     1,154 |                     382 |                        567 |                                       97% |                                   841 |                                  1,610 |
|             [Rhode Island](/us-ri) |            1,021 |                     1,122 |                   1,059 |                        101 |                                       10% |                                 1,039 |                                  1,284 |
|              [Puerto Rico](/us-pr) |              317 |                     1,067 |                     334 |                        750 |                                      237% |                                   614 |                                  1,901 |
|               [New Mexico](/us-nm) |              703 |                     1,041 |                     496 |                        338 |                                       48% |                                   827 |                                  1,439 |
|                   [Oregon](/us-or) |              385 |                       830 |                     197 |                        445 |                                      116% |                                   549 |                                  1,278 |
|                   [Kansas](/us-ks) |              404 |                       698 |                     240 |                        294 |                                       73% |                                   505 |                                  1,040 |
|                     [Utah](/us-ut) |              360 |                       688 |                     215 |                        328 |                                       91% |                                   483 |                                  1,021 |
|                 [Delaware](/us-de) |              593 |                       674 |                     692 |                         81 |                                       14% |                                   606 |                                    806 |
|                    [Idaho](/us-id) |              265 |                       660 |                     369 |                        395 |                                      149% |                                   451 |                                    933 |
|     [District of Columbia](/us-dc) |              594 |                       650 |                     921 |                         56 |                                        9% |                                   605 |                                    745 |
|                 [Nebraska](/us-ne) |              361 |                       533 |                     276 |                        172 |                                       48% |                                   427 |                                    770 |
|            [New Hampshire](/us-nh) |              423 |                       517 |                     380 |                         94 |                                       22% |                                   432 |                                    755 |
|            [West Virginia](/us-wv) |              157 |                       467 |                     261 |                        310 |                                      198% |                                   273 |                                    806 |
|                   [Hawaii](/us-hi) |               40 |                       234 |                     165 |                        194 |                                      484% |                                    92 |                                    544 |
|                  [Montana](/us-mt) |               81 |                       231 |                     216 |                        150 |                                      185% |                                   140 |                                    379 |
|             [South Dakota](/us-sd) |              150 |                       231 |                     261 |                         81 |                                       54% |                                   179 |                                    329 |
|             [North Dakota](/us-nd) |              121 |                       224 |                     294 |                        103 |                                       85% |                                   159 |                                    338 |
|                    [Maine](/us-me) |              126 |                       154 |                     115 |                         28 |                                       22% |                                   131 |                                    197 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     118 |                         16 |                                       27% |                                    61 |                                    103 |
|                   [Alaska](/us-ak) |               27 |                        61 |                      84 |                         34 |                                      127% |                                    39 |                                    102 |
|                  [Wyoming](/us-wy) |               30 |                        51 |                      88 |                         21 |                                       69% |                                    39 |                                     75 |
|           [Virgin Islands](/us-vi) |                9 |                        18 |                     173 |                          9 |                                      102% |                                    12 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      49 |                          3 |                                       64% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       55% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,987 |                   209,413 |                     353 |                     18,426 |                                       10% |                               194,628 |                                251,561 |
| [United Kingdom](/united-kingdom) |           46,791 |                    49,685 |                     736 |                      2,894 |                                        6% |                                46,928 |                                 57,814 |
|                   [Italy](/italy) |           35,234 |                    35,947 |                     596 |                        713 |                                        2% |                                35,262 |                                 38,482 |
|                 [France](/france) |           30,410 |                    31,324 |                     467 |                        914 |                                        3% |                                30,446 |                                 35,902 |
|                   [Spain](/spain) |           28,617 |                    29,962 |                     638 |                      1,345 |                                        5% |                                28,656 |                                 34,909 |
|               [Belgium](/belgium) |            9,924 |                    10,435 |                     911 |                        511 |                                        5% |                                 9,961 |                                 12,415 |
|               [Germany](/germany) |            9,230 |                    10,229 |                     123 |                        999 |                                       11% |                                 9,323 |                                 13,054 |
|       [Netherlands](/netherlands) |            6,189 |                     6,565 |                     380 |                        376 |                                        6% |                                 6,215 |                                  8,027 |
|               [Romania](/romania) |            2,904 |                     6,496 |                     335 |                      3,592 |                                      124% |                                 4,165 |                                 10,716 |
|                 [Sweden](/sweden) |            5,783 |                     5,952 |                     582 |                        169 |                                        3% |                                 5,815 |                                  6,062 |
|               [Ukraine](/ukraine) |            2,042 |                     4,614 |                     105 |                      2,572 |                                      126% |                                 2,785 |                                  8,757 |
|                 [Poland](/poland) |            1,858 |                     2,976 |                      78 |                      1,118 |                                       60% |                                 2,144 |                                  4,633 |
|       [Switzerland](/switzerland) |            1,991 |                     2,083 |                     242 |                         92 |                                        5% |                                 2,003 |                                  2,449 |
|             [Portugal](/portugal) |            1,772 |                     2,056 |                     200 |                        284 |                                       16% |                                 1,784 |                                  2,675 |
|               [Ireland](/ireland) |            1,774 |                     1,859 |                     379 |                         85 |                                        5% |                                 1,785 |                                  2,107 |
|               [Moldova](/moldova) |              884 |                     1,370 |                     339 |                        486 |                                       55% |                                 1,069 |                                  1,953 |
|             [Bulgaria](/bulgaria) |              492 |                     1,163 |                     166 |                        671 |                                      136% |                                   713 |                                  2,214 |
|                 [Serbia](/serbia) |              665 |                     1,048 |                     150 |                        383 |                                       58% |                                   811 |                                  1,509 |
|               [Austria](/austria) |              725 |                       818 |                      92 |                         93 |                                       13% |                                   738 |                                  1,057 |
|               [Belarus](/belarus) |              603 |                       802 |                      85 |                        199 |                                       33% |                                   720 |                                    989 |
|               [Denmark](/denmark) |              621 |                       721 |                     124 |                        100 |                                       16% |                                   641 |                                    984 |
|               [Hungary](/hungary) |              607 |                       696 |                      71 |                         89 |                                       15% |                                   615 |                                    912 |
|               [Czechia](/czechia) |              394 |                       538 |                      51 |                        144 |                                       37% |                                   421 |                                    834 |
|                 [Greece](/greece) |              223 |                       419 |                      39 |                        196 |                                       88% |                                   274 |                                    703 |
|               [Finland](/finland) |              333 |                       374 |                      68 |                         41 |                                       12% |                                   340 |                                    487 |
|                 [Norway](/norway) |              261 |                       308 |                      57 |                         47 |                                       18% |                                   269 |                                    422 |
|               [Croatia](/croatia) |              163 |                       296 |                      73 |                        133 |                                       82% |                                   203 |                                    504 |
|             [Slovenia](/slovenia) |              129 |                       187 |                      90 |                         58 |                                       45% |                                   142 |                                    287 |
|         [Luxembourg](/luxembourg) |              122 |                       178 |                     290 |                         56 |                                       46% |                                   138 |                                    269 |
|           [Lithuania](/lithuania) |               81 |                        96 |                      34 |                         15 |                                       18% |                                    84 |                                    126 |
|               [Estonia](/estonia) |               63 |                        72 |                      54 |                          9 |                                       14% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        47 |                       9 |                         16 |                                       53% |                                    33 |                                     87 |
|                 [Latvia](/latvia) |               32 |                        39 |                      20 |                          7 |                                       23% |                                    33 |                                     52 |
|                 [Cyprus](/cyprus) |               20 |                        34 |                      38 |                         14 |                                       68% |                                    24 |                                     56 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       29% |                                    10 |                                     19 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       31% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          380,465 |                   667,242 |                     129 |                    286,777 |                                       75% |                               493,087 |                                966,371 |
|                             [Brazil](/brazil) |          105,490 |                   167,872 |                     795 |                     62,382 |                                       59% |                               123,264 |                                242,568 |
|                               [India](/india) |           49,036 |                   124,033 |                      91 |                     74,997 |                                      153% |                                81,753 |                                176,498 |
|                             [Mexico](/mexico) |           55,908 |                   100,099 |                     785 |                     44,191 |                                       79% |                                82,988 |                                138,305 |
|                                 [Peru](/peru) |           25,856 |                    38,083 |                   1,171 |                     12,227 |                                       47% |                                30,700 |                                 50,990 |
|                         [Colombia](/colombia) |           14,492 |                    31,741 |                     631 |                     17,249 |                                      119% |                                21,787 |                                 47,718 |
|                                 [Iran](/iran) |           19,331 |                    27,893 |                     336 |                      8,562 |                                       44% |                                22,469 |                                 38,035 |
|                 [South Africa](/south-africa) |           11,556 |                    22,936 |                     392 |                     11,380 |                                       98% |                                15,872 |                                 33,146 |
|                             [Russia](/russia) |           15,467 |                    22,056 |                     151 |                      6,589 |                                       43% |                                17,580 |                                 31,506 |
|                       [Argentina](/argentina) |            5,527 |                    19,319 |                     431 |                     13,792 |                                      250% |                                10,168 |                                 32,132 |
|                               [Chile](/chile) |           10,340 |                    15,222 |                     803 |                      4,882 |                                       47% |                                11,035 |                                 25,940 |
|                       [Indonesia](/indonesia) |            6,021 |                    10,892 |                      40 |                      4,871 |                                       81% |                                 7,719 |                                 18,125 |
|                             [Canada](/canada) |            9,068 |                     9,499 |                     254 |                        431 |                                        5% |                                 9,104 |                                 10,525 |
|                           [Ecuador](/ecuador) |            6,030 |                     7,440 |                     428 |                      1,410 |                                       23% |                                 6,184 |                                 10,509 |
|                             [Turkey](/turkey) |            5,934 |                     7,413 |                      89 |                      1,479 |                                       25% |                                 5,981 |                                 11,244 |
|                           [Bolivia](/bolivia) |            3,939 |                     7,200 |                     625 |                      3,261 |                                       83% |                                 5,121 |                                 11,208 |
|                         [Pakistan](/pakistan) |            6,153 |                     7,064 |                      33 |                        911 |                                       15% |                                 6,302 |                                  8,285 |
|                               [Egypt](/egypt) |            5,124 |                     5,910 |                      59 |                        786 |                                       15% |                                 5,260 |                                  7,118 |
|                     [Bangladesh](/bangladesh) |            3,591 |                     5,639 |                      35 |                      2,048 |                                       57% |                                 4,107 |                                  9,011 |
|                   [Philippines](/philippines) |            2,442 |                     5,380 |                      50 |                      2,938 |                                      120% |                                 3,106 |                                 10,607 |
|                 [Saudi Arabia](/saudi-arabia) |            3,338 |                     4,938 |                     144 |                      1,600 |                                       48% |                                 3,895 |                                  7,136 |
|                               [China](/china) |            4,701 |                     4,912 |                       3 |                        211 |                                        4% |                                 4,701 |                                  6,365 |
|                           [Morocco](/morocco) |              611 |                     3,359 |                      92 |                      2,748 |                                      450% |                                 1,348 |                                  7,409 |
|                             [Panama](/panama) |            1,734 |                     2,838 |                     668 |                      1,104 |                                       64% |                                 2,122 |                                  4,126 |
|                         [Honduras](/honduras) |            1,548 |                     2,680 |                     275 |                      1,132 |                                       73% |                                 1,900 |                                  4,315 |
|     [Dominican Republic](/dominican-republic) |            1,409 |                     2,652 |                     247 |                      1,243 |                                       88% |                                 1,814 |                                  4,376 |
|                           [Algeria](/algeria) |            1,351 |                     2,228 |                      52 |                        877 |                                       65% |                                 1,549 |                                  3,804 |
|                               [Japan](/japan) |            1,080 |                     1,770 |                      14 |                        690 |                                       64% |                                 1,128 |                                  4,222 |
|                             [Israel](/israel) |              665 |                     1,565 |                     184 |                        900 |                                      135% |                                   950 |                                  2,968 |
|                       [Australia](/australia) |              379 |                     1,402 |                      56 |                      1,023 |                                      270% |                                   701 |                                  3,005 |
|                           [Nigeria](/nigeria) |              973 |                     1,358 |                       7 |                        385 |                                       40% |                                 1,051 |                                  2,141 |
|                             [Kuwait](/kuwait) |              494 |                       762 |                     181 |                        268 |                                       54% |                                   534 |                                  1,364 |
| [United Arab Emirates](/united-arab-emirates) |              359 |                       446 |                      46 |                         87 |                                       24% |                                   365 |                                    683 |
|                   [South Korea](/south-korea) |              305 |                       373 |                       7 |                         68 |                                       22% |                                   305 |                                    608 |
|                         [Malaysia](/malaysia) |              125 |                       141 |                       4 |                         16 |                                       13% |                                   129 |                                    158 |
|                                 [Cuba](/cuba) |               88 |                       129 |                      11 |                         41 |                                       46% |                                    95 |                                    221 |
