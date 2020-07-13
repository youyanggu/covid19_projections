We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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
* **July 13:** View our [updated historical performance](/about/#historical-performance).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 13 (6am ET):
<p align="center">
  Current Total: <b>135,202</b> deaths | Projected Total: <b>224,000 deaths by Nov 1, 2020</b> (Range: 178-301k) | 204,400 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.2%</b> | Total Infected: <b>7.2%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 13, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 20, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |        Aug 28, 2020 |
|              200,000 |        Sep 26, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        46% |         99% |        99% |         99% |       >99% |        >99% |       >99% |
|              175,000 |         <1% |        <1% |          5% |        51% |         75% |        89% |         96% |        99% |
|              200,000 |         <1% |        <1% |         <1% |         7% |         25% |        42% |         53% |        65% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |          6% |        15% |         24% |        34% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         5% |         10% |        15% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         3% |

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
|             *[United States](/us)* |          135,202 |                   224,039 |                     675 |                     88,837 |                                       66% |                               178,150 |                                300,746 |
|                 [New York](/us-ny) |           32,350 |                    33,639 |                   1,729 |                      1,289 |                                        4% |                                32,388 |                                 39,076 |
|               [California](/us-ca) |            7,051 |                    20,671 |                     523 |                     13,620 |                                      193% |                                 9,251 |                                 42,451 |
|               [New Jersey](/us-nj) |           15,525 |                    16,823 |                   1,894 |                      1,298 |                                        8% |                                15,608 |                                 19,056 |
|                  [Florida](/us-fl) |            4,242 |                    15,018 |                     699 |                     10,776 |                                      254% |                                 7,483 |                                 26,138 |
|                    [Texas](/us-tx) |            3,216 |                    14,099 |                     486 |                     10,883 |                                      338% |                                 8,262 |                                 25,750 |
|             [Pennsylvania](/us-pa) |            6,904 |                     9,196 |                     718 |                      2,292 |                                       33% |                                 7,115 |                                 14,653 |
|            [Massachusetts](/us-ma) |            8,325 |                     9,078 |                   1,306 |                        753 |                                        9% |                                 8,458 |                                 10,647 |
|                 [Illinois](/us-il) |            7,388 |                     8,616 |                     680 |                      1,228 |                                       17% |                                 7,609 |                                 10,110 |
|                 [Michigan](/us-mi) |            6,314 |                     8,025 |                     804 |                      1,711 |                                       27% |                                 6,433 |                                 12,613 |
|                  [Georgia](/us-ga) |            3,003 |                     7,186 |                     677 |                      4,183 |                                      139% |                                 3,862 |                                 14,343 |
|                  [Arizona](/us-az) |            2,237 |                     6,545 |                     899 |                      4,308 |                                      193% |                                 4,489 |                                  9,988 |
|                     [Ohio](/us-oh) |            3,058 |                     6,478 |                     554 |                      3,420 |                                      112% |                                 3,320 |                                 14,037 |
|                [Louisiana](/us-la) |            3,416 |                     5,826 |                   1,253 |                      2,410 |                                       71% |                                 3,719 |                                  8,324 |
|                 [Virginia](/us-va) |            1,966 |                     4,616 |                     541 |                      2,650 |                                      135% |                                 2,148 |                                  9,687 |
|              [Connecticut](/us-ct) |            4,348 |                     4,479 |                   1,256 |                        131 |                                        3% |                                 4,370 |                                  4,636 |
|                 [Maryland](/us-md) |            3,319 |                     4,166 |                     689 |                        847 |                                       26% |                                 3,483 |                                  5,527 |
|                  [Indiana](/us-in) |            2,760 |                     4,080 |                     606 |                      1,320 |                                       48% |                                 2,858 |                                  7,812 |
|                  [Alabama](/us-al) |            1,121 |                     3,984 |                     813 |                      2,863 |                                      255% |                                 2,057 |                                  6,730 |
|           [South Carolina](/us-sc) |              961 |                     3,933 |                     764 |                      2,972 |                                      309% |                                 2,397 |                                  6,413 |
|           [North Carolina](/us-nc) |            1,522 |                     3,463 |                     330 |                      1,941 |                                      128% |                                 1,807 |                                  8,925 |
|                [Tennessee](/us-tn) |              741 |                     3,318 |                     486 |                      2,577 |                                      348% |                                 1,819 |                                  6,640 |
|               [Washington](/us-wa) |            1,438 |                     2,947 |                     387 |                      1,509 |                                      105% |                                 1,640 |                                  6,101 |
|              [Mississippi](/us-ms) |            1,249 |                     2,884 |                     969 |                      1,635 |                                      131% |                                 1,685 |                                  4,711 |
|                 [Colorado](/us-co) |            1,725 |                     2,507 |                     435 |                        782 |                                       45% |                                 1,785 |                                  5,004 |
|                 [Missouri](/us-mo) |            1,092 |                     2,209 |                     360 |                      1,117 |                                      102% |                                 1,221 |                                  5,096 |
|                [Minnesota](/us-mn) |            1,540 |                     2,206 |                     391 |                        666 |                                       43% |                                 1,653 |                                  3,452 |
|                   [Nevada](/us-nv) |              593 |                     2,164 |                     703 |                      1,571 |                                      265% |                                 1,156 |                                  3,776 |
|                 [Kentucky](/us-ky) |              625 |                     1,840 |                     412 |                      1,215 |                                      194% |                                   844 |                                  3,956 |
|                [Wisconsin](/us-wi) |              820 |                     1,703 |                     292 |                        883 |                                      108% |                                   955 |                                  4,670 |
|                 [Arkansas](/us-ar) |              321 |                     1,299 |                     430 |                        978 |                                      305% |                                   505 |                                  2,836 |
|                     [Iowa](/us-ia) |              752 |                     1,234 |                     391 |                        482 |                                       64% |                                   793 |                                  2,553 |
|             [Rhode Island](/us-ri) |              976 |                     1,127 |                   1,064 |                        151 |                                       15% |                                 1,000 |                                  1,299 |
|               [New Mexico](/us-nm) |              545 |                     1,063 |                     507 |                        518 |                                       95% |                                   605 |                                  2,181 |
|                     [Utah](/us-ut) |              215 |                     1,004 |                     313 |                        789 |                                      367% |                                   341 |                                  2,374 |
|                   [Oregon](/us-or) |              234 |                       971 |                     230 |                        737 |                                      315% |                                   304 |                                  2,437 |
|                 [Oklahoma](/us-ok) |              422 |                       846 |                     214 |                        424 |                                      100% |                                   495 |                                  1,764 |
|     [District of Columbia](/us-dc) |              568 |                       701 |                     993 |                        133 |                                       23% |                                   587 |                                  1,041 |
|                 [Delaware](/us-de) |              517 |                       675 |                     693 |                        158 |                                       31% |                                   535 |                                  1,033 |
|                   [Kansas](/us-ks) |              297 |                       608 |                     209 |                        311 |                                      105% |                                   332 |                                  1,464 |
|            [New Hampshire](/us-nh) |              391 |                       454 |                     334 |                         63 |                                       16% |                                   398 |                                    523 |
|                 [Nebraska](/us-ne) |              285 |                       454 |                     235 |                        169 |                                       59% |                                   345 |                                    628 |
|                    [Idaho](/us-id) |              102 |                       422 |                     236 |                        320 |                                      314% |                                   137 |                                  1,027 |
|              [Puerto Rico](/us-pr) |              167 |                       284 |                      89 |                        117 |                                       70% |                                   177 |                                    648 |
|             [South Dakota](/us-sd) |              109 |                       217 |                     245 |                        108 |                                       99% |                                   138 |                                    349 |
|                  [Montana](/us-mt) |               29 |                       196 |                     183 |                        167 |                                      576% |                                    83 |                                    483 |
|                    [Maine](/us-me) |              114 |                       194 |                     144 |                         80 |                                       70% |                                   124 |                                    434 |
|             [North Dakota](/us-nd) |               87 |                       189 |                     248 |                        102 |                                      117% |                                   103 |                                    445 |
|            [West Virginia](/us-wv) |               96 |                       153 |                      85 |                         57 |                                       59% |                                   104 |                                    302 |
|                  [Vermont](/us-vt) |               56 |                        81 |                     130 |                         25 |                                       45% |                                    58 |                                    157 |
|                   [Alaska](/us-ak) |               17 |                        52 |                      71 |                         35 |                                      206% |                                    19 |                                    181 |
|                  [Wyoming](/us-wy) |               21 |                        47 |                      81 |                         26 |                                      124% |                                    27 |                                     96 |
|                   [Hawaii](/us-hi) |               19 |                        42 |                      30 |                         23 |                                      121% |                                    21 |                                    112 |
|           [Virgin Islands](/us-vi) |                6 |                        15 |                     143 |                          9 |                                      150% |                                     6 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          184,422 |                   203,868 |                     344 |                     19,446 |                                       11% |                               188,644 |                                232,041 |
| [United Kingdom](/united-kingdom) |           44,904 |                    49,245 |                     729 |                      4,341 |                                       10% |                                45,480 |                                 53,606 |
|                   [Italy](/italy) |           34,954 |                    35,700 |                     591 |                        746 |                                        2% |                                35,032 |                                 36,459 |
|                 [France](/france) |           30,007 |                    30,714 |                     458 |                        707 |                                        2% |                                30,029 |                                 33,989 |
|                   [Spain](/spain) |           28,403 |                    28,987 |                     618 |                        584 |                                        2% |                                28,436 |                                 30,804 |
|               [Belgium](/belgium) |            9,782 |                     9,976 |                     871 |                        194 |                                        2% |                                 9,800 |                                 10,502 |
|               [Germany](/germany) |            9,071 |                     9,481 |                     114 |                        410 |                                        5% |                                 9,112 |                                 10,489 |
|       [Netherlands](/netherlands) |            6,156 |                     6,309 |                     365 |                        153 |                                        2% |                                 6,177 |                                  6,508 |
|                 [Sweden](/sweden) |            5,526 |                     5,994 |                     586 |                        468 |                                        8% |                                 5,682 |                                  6,192 |
|               [Romania](/romania) |            1,884 |                     4,045 |                     208 |                      2,161 |                                      115% |                                 2,707 |                                  5,846 |
|                 [Serbia](/serbia) |              393 |                     3,827 |                     550 |                      3,434 |                                      874% |                                   941 |                                  8,926 |
|               [Ukraine](/ukraine) |            1,400 |                     3,060 |                      70 |                      1,660 |                                      119% |                                 2,067 |                                  4,728 |
|                 [Poland](/poland) |            1,571 |                     2,513 |                      66 |                        942 |                                       60% |                                 1,865 |                                  3,959 |
|             [Portugal](/portugal) |            1,660 |                     2,321 |                     226 |                        661 |                                       40% |                                 1,757 |                                  3,403 |
|       [Switzerland](/switzerland) |            1,968 |                     2,074 |                     241 |                        106 |                                        5% |                                 1,981 |                                  2,506 |
|               [Ireland](/ireland) |            1,746 |                     1,840 |                     375 |                         94 |                                        5% |                                 1,754 |                                  2,278 |
|               [Moldova](/moldova) |              642 |                     1,282 |                     317 |                        640 |                                      100% |                                 1,013 |                                  1,851 |
|               [Belarus](/belarus) |              464 |                     1,160 |                     123 |                        696 |                                      150% |                                   622 |                                  2,414 |
|             [Bulgaria](/bulgaria) |              268 |                       868 |                     124 |                        600 |                                      224% |                                   431 |                                  1,436 |
|               [Austria](/austria) |              708 |                       840 |                      95 |                        132 |                                       19% |                                   724 |                                  1,089 |
|               [Hungary](/hungary) |              595 |                       731 |                      75 |                        136 |                                       23% |                                   611 |                                  1,137 |
|               [Denmark](/denmark) |              609 |                       657 |                     113 |                         48 |                                        8% |                                   623 |                                    744 |
|               [Czechia](/czechia) |              352 |                       487 |                      46 |                        135 |                                       38% |                                   361 |                                    728 |
|               [Finland](/finland) |              329 |                       375 |                      68 |                         46 |                                       14% |                                   335 |                                    527 |
|                 [Norway](/norway) |              252 |                       275 |                      51 |                         23 |                                        9% |                                   259 |                                    320 |
|               [Croatia](/croatia) |              119 |                       268 |                      66 |                        149 |                                      125% |                                   145 |                                    397 |
|                 [Greece](/greece) |              193 |                       227 |                      21 |                         34 |                                       18% |                                   205 |                                    295 |
|         [Luxembourg](/luxembourg) |              111 |                       148 |                     241 |                         37 |                                       33% |                                   118 |                                    190 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    162 |
|           [Lithuania](/lithuania) |               79 |                       114 |                      41 |                         35 |                                       44% |                                    87 |                                    184 |
|               [Estonia](/estonia) |               69 |                        87 |                      66 |                         18 |                                       26% |                                    75 |                                    115 |
|             [Slovakia](/slovakia) |               28 |                        41 |                       8 |                         13 |                                       46% |                                    28 |                                     87 |
|                 [Latvia](/latvia) |               30 |                        39 |                      20 |                          9 |                                       30% |                                    32 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        32 |                      37 |                         13 |                                       68% |                                    21 |                                     70 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     29 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          236,407 |                   596,888 |                     115 |                    360,481 |                                      152% |                               385,550 |                                991,196 |
|                             [Brazil](/brazil) |           72,100 |                   145,102 |                     688 |                     73,002 |                                      101% |                               111,937 |                                221,221 |
|                               [India](/india) |           23,174 |                   114,278 |                      84 |                     91,104 |                                      393% |                                47,861 |                                243,845 |
|                             [Mexico](/mexico) |           35,006 |                    84,858 |                     665 |                     49,852 |                                      142% |                                64,350 |                                108,339 |
|                                 [Iran](/iran) |           12,829 |                    30,180 |                     364 |                     17,351 |                                      135% |                                21,359 |                                 45,068 |
|                                 [Peru](/peru) |           11,870 |                    23,320 |                     717 |                     11,450 |                                       96% |                                17,116 |                                 32,281 |
|                             [Russia](/russia) |           11,318 |                    22,951 |                     157 |                     11,633 |                                      103% |                                14,373 |                                 41,246 |
|                 [South Africa](/south-africa) |            4,079 |                    22,936 |                     392 |                     18,857 |                                      462% |                                12,858 |                                 39,082 |
|                         [Colombia](/colombia) |            5,426 |                    21,796 |                     433 |                     16,370 |                                      302% |                                15,483 |                                 32,837 |
|                       [Indonesia](/indonesia) |            3,606 |                    14,295 |                      53 |                     10,689 |                                      296% |                                 5,965 |                                 28,537 |
|                         [Pakistan](/pakistan) |            5,266 |                    11,114 |                      51 |                      5,848 |                                      111% |                                 7,051 |                                 17,632 |
|                               [Chile](/chile) |            6,979 |                    11,025 |                     582 |                      4,046 |                                       58% |                                 7,875 |                                 13,728 |
|                               [Egypt](/egypt) |            3,858 |                    10,113 |                     101 |                      6,255 |                                      162% |                                 5,860 |                                 17,411 |
|                             [Canada](/canada) |            8,829 |                     9,816 |                     262 |                        987 |                                       11% |                                 8,931 |                                 11,178 |
|                       [Argentina](/argentina) |            1,845 |                     8,325 |                     186 |                      6,480 |                                      351% |                                 3,778 |                                 17,293 |
|                           [Ecuador](/ecuador) |            5,047 |                     8,267 |                     476 |                      3,220 |                                       64% |                                 5,423 |                                 13,898 |
|                             [Turkey](/turkey) |            5,363 |                     7,040 |                      84 |                      1,677 |                                       31% |                                 5,469 |                                 12,135 |
|                           [Bolivia](/bolivia) |            1,807 |                     6,932 |                     602 |                      5,125 |                                      284% |                                 3,694 |                                 12,066 |
|                     [Bangladesh](/bangladesh) |            2,352 |                     6,623 |                      41 |                      4,271 |                                      182% |                                 3,831 |                                 11,996 |
|                 [Saudi Arabia](/saudi-arabia) |            2,223 |                     6,256 |                     183 |                      4,033 |                                      181% |                                 3,767 |                                  9,620 |
|                               [China](/china) |            4,641 |                     4,646 |                       3 |                          5 |                                        0% |                                 4,641 |                                  4,674 |
|     [Dominican Republic](/dominican-republic) |              897 |                     4,420 |                     412 |                      3,523 |                                      393% |                                 1,469 |                                  9,016 |
|                         [Honduras](/honduras) |              774 |                     4,072 |                     418 |                      3,298 |                                      426% |                                 2,603 |                                  7,055 |
|                   [Philippines](/philippines) |            1,534 |                     3,731 |                      35 |                      2,197 |                                      143% |                                 1,724 |                                  8,260 |
|                             [Panama](/panama) |              909 |                     3,433 |                     808 |                      2,524 |                                      278% |                                 2,442 |                                  5,470 |
|                           [Algeria](/algeria) |            1,011 |                     2,947 |                      68 |                      1,936 |                                      191% |                                 1,391 |                                  7,378 |
|                           [Nigeria](/nigeria) |              740 |                     2,413 |                      12 |                      1,673 |                                      226% |                                 1,099 |                                  5,303 |
|                             [Israel](/israel) |              362 |                     1,769 |                     208 |                      1,407 |                                      389% |                                   513 |                                  6,266 |
|                               [Japan](/japan) |              983 |                     1,608 |                      13 |                        625 |                                       64% |                                   990 |                                  2,934 |
|                             [Kuwait](/kuwait) |              390 |                       721 |                     171 |                        331 |                                       85% |                                   435 |                                  1,376 |
|                           [Morocco](/morocco) |              250 |                       501 |                      14 |                        251 |                                      100% |                                   283 |                                    989 |
| [United Arab Emirates](/united-arab-emirates) |              333 |                       487 |                      50 |                        154 |                                       46% |                                   351 |                                    930 |
|                   [South Korea](/south-korea) |              289 |                       345 |                       7 |                         56 |                                       19% |                                   291 |                                    499 |
|                       [Australia](/australia) |              108 |                       305 |                      12 |                        197 |                                      182% |                                   108 |                                  1,300 |
|                         [Malaysia](/malaysia) |              122 |                       157 |                       5 |                         35 |                                       29% |                                   137 |                                    187 |
|                                 [Cuba](/cuba) |               87 |                       106 |                       9 |                         19 |                                       22% |                                    92 |                                    146 |
