We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](https://covid19-projections.com/estimating-true-infections), for a more detailed look into this subject.

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
* *August 3:* View our [updated historical performance](/about/#historical-performance).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

For regular updates and insights, follow our Twitter:<br>
<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: August 4 (2am ET):
<p align="center">
  Current Total: <b>155,399</b> deaths | Projected Total: <b>227,703 deaths by Nov 1, 2020</b> (Range: 198-270k)<br>
  Currently Infected: <b>1.9%</b> (1 in 50) | Total Infected: <b>12.0%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 4, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 23, 2020 |
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        98% |         99% |        99% |         99% |       >99% |
|              200,000 |         <1% |         2% |         31% |        69% |         86% |        96% |
|              225,000 |         <1% |        <1% |         <1% |        10% |         26% |        45% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          4% |        11% |
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
|             *[United States](/us)* |          154,857 |                   228,268 |                     688 |                     73,411 |                                       47% |                               198,600 |                                270,152 |
|                 [New York](/us-ny) |           32,710 |                    33,367 |                   1,715 |                        657 |                                        2% |                                32,745 |                                 36,399 |
|               [California](/us-ca) |            9,396 |                    18,689 |                     473 |                      9,293 |                                       99% |                                13,054 |                                 25,956 |
|                    [Texas](/us-tx) |            6,878 |                    18,031 |                     622 |                     11,153 |                                      162% |                                12,458 |                                 24,401 |
|               [New Jersey](/us-nj) |           15,836 |                    16,817 |                   1,893 |                        981 |                                        6% |                                15,910 |                                 19,139 |
|                  [Florida](/us-fl) |            7,084 |                    16,277 |                     758 |                      9,193 |                                      130% |                                11,639 |                                 22,516 |
|            [Massachusetts](/us-ma) |            8,638 |                    10,014 |                   1,441 |                      1,376 |                                       16% |                                 8,751 |                                 12,844 |
|                 [Illinois](/us-il) |            7,714 |                     9,746 |                     769 |                      2,032 |                                       26% |                                 8,127 |                                 12,999 |
|             [Pennsylvania](/us-pa) |            7,223 |                     8,442 |                     659 |                      1,219 |                                       17% |                                 7,346 |                                 10,689 |
|                 [Michigan](/us-mi) |            6,457 |                     7,362 |                     737 |                        905 |                                       14% |                                 6,532 |                                  9,428 |
|                  [Arizona](/us-az) |            3,765 |                     7,080 |                     973 |                      3,315 |                                       88% |                                 5,433 |                                  9,135 |
|                  [Georgia](/us-ga) |            3,840 |                     6,755 |                     636 |                      2,915 |                                       76% |                                 5,005 |                                  9,407 |
|                [Louisiana](/us-la) |            4,007 |                     5,642 |                   1,214 |                      1,635 |                                       41% |                                 4,595 |                                  7,282 |
|                     [Ohio](/us-oh) |            3,529 |                     5,592 |                     478 |                      2,063 |                                       58% |                                 4,111 |                                  8,225 |
|                 [Maryland](/us-md) |            3,515 |                     4,835 |                     800 |                      1,320 |                                       38% |                                 3,732 |                                  7,517 |
|              [Connecticut](/us-ct) |            4,432 |                     4,655 |                   1,306 |                        223 |                                        5% |                                 4,464 |                                  5,104 |
|           [South Carolina](/us-sc) |            1,777 |                     4,309 |                     837 |                      2,532 |                                      142% |                                 3,009 |                                  5,778 |
|                  [Indiana](/us-in) |            2,975 |                     4,292 |                     638 |                      1,317 |                                       44% |                                 3,135 |                                  6,715 |
|                 [Virginia](/us-va) |            2,218 |                     4,067 |                     476 |                      1,849 |                                       83% |                                 2,527 |                                  7,223 |
|           [North Carolina](/us-nc) |            1,983 |                     3,802 |                     362 |                      1,819 |                                       92% |                                 2,628 |                                  5,596 |
|              [Mississippi](/us-ms) |            1,703 |                     3,474 |                   1,167 |                      1,771 |                                      104% |                                 2,434 |                                  5,101 |
|                  [Alabama](/us-al) |            1,627 |                     3,116 |                     635 |                      1,489 |                                       92% |                                 2,277 |                                  4,271 |
|               [Washington](/us-wa) |            1,596 |                     2,817 |                     370 |                      1,221 |                                       76% |                                 1,815 |                                  4,942 |
|                 [Colorado](/us-co) |            1,844 |                     2,640 |                     458 |                        796 |                                       43% |                                 1,985 |                                  4,195 |
|                 [Missouri](/us-mo) |            1,276 |                     2,557 |                     417 |                      1,281 |                                      100% |                                 1,631 |                                  4,315 |
|                [Tennessee](/us-tn) |            1,073 |                     2,373 |                     347 |                      1,300 |                                      121% |                                 1,599 |                                  3,413 |
|                [Minnesota](/us-mn) |            1,654 |                     2,293 |                     407 |                        639 |                                       39% |                                 1,757 |                                  3,477 |
|                [Wisconsin](/us-wi) |              948 |                     1,805 |                     310 |                        857 |                                       90% |                                 1,129 |                                  3,208 |
|                   [Nevada](/us-nv) |              832 |                     1,752 |                     569 |                        920 |                                      111% |                                 1,242 |                                  2,461 |
|                 [Kentucky](/us-ky) |              742 |                     1,459 |                     327 |                        717 |                                       97% |                                   921 |                                  2,515 |
|                     [Iowa](/us-ia) |              878 |                     1,447 |                     459 |                        569 |                                       65% |                                 1,021 |                                  2,304 |
|                 [Oklahoma](/us-ok) |              550 |                     1,238 |                     313 |                        688 |                                      125% |                                   777 |                                  1,953 |
|               [New Mexico](/us-nm) |              654 |                     1,169 |                     557 |                        515 |                                       79% |                                   792 |                                  1,807 |
|             [Rhode Island](/us-ri) |            1,007 |                     1,122 |                   1,059 |                        115 |                                       11% |                                 1,030 |                                  1,300 |
|                 [Arkansas](/us-ar) |              464 |                     1,058 |                     350 |                        594 |                                      128% |                                   702 |                                  1,587 |
|                   [Oregon](/us-or) |              326 |                       974 |                     231 |                        648 |                                      199% |                                   537 |                                  1,725 |
|                    [Idaho](/us-id) |              197 |                       846 |                     473 |                        649 |                                      330% |                                   462 |                                  1,439 |
|                     [Utah](/us-ut) |              311 |                       825 |                     257 |                        514 |                                      165% |                                   491 |                                  1,309 |
|              [Puerto Rico](/us-pr) |              230 |                       783 |                     245 |                        553 |                                      241% |                                   400 |                                  1,536 |
|                   [Kansas](/us-ks) |              361 |                       766 |                     263 |                        405 |                                      112% |                                   478 |                                  1,293 |
|                 [Delaware](/us-de) |              585 |                       674 |                     692 |                         89 |                                       15% |                                   600 |                                    823 |
|     [District of Columbia](/us-dc) |              584 |                       649 |                     919 |                         65 |                                       11% |                                   597 |                                    757 |
|            [New Hampshire](/us-nh) |              417 |                       590 |                     434 |                        173 |                                       42% |                                   438 |                                    921 |
|                 [Nebraska](/us-ne) |              332 |                       556 |                     287 |                        224 |                                       67% |                                   406 |                                    919 |
|            [West Virginia](/us-wv) |              117 |                       277 |                     154 |                        160 |                                      137% |                                   152 |                                    548 |
|                  [Montana](/us-mt) |               61 |                       273 |                     255 |                        212 |                                      347% |                                   135 |                                    486 |
|             [South Dakota](/us-sd) |              135 |                       231 |                     261 |                         96 |                                       71% |                                   168 |                                    351 |
|             [North Dakota](/us-nd) |              105 |                       205 |                     269 |                        100 |                                       95% |                                   133 |                                    352 |
|                    [Maine](/us-me) |              123 |                       201 |                     149 |                         78 |                                       63% |                                   142 |                                    339 |
|                   [Alaska](/us-ak) |               24 |                       110 |                     150 |                         86 |                                      357% |                                    49 |                                    237 |
|                  [Vermont](/us-vt) |               57 |                        77 |                     123 |                         20 |                                       35% |                                    61 |                                    107 |
|                   [Hawaii](/us-hi) |               26 |                        65 |                      46 |                         39 |                                      151% |                                    31 |                                    158 |
|                  [Wyoming](/us-wy) |               26 |                        41 |                      72 |                         15 |                                       60% |                                    32 |                                     57 |
|           [Virgin Islands](/us-vi) |                8 |                        20 |                     192 |                         12 |                                      152% |                                    12 |                                     37 |
|                     [Guam](/us-gu) |                5 |                         9 |                      53 |                          4 |                                       76% |                                     5 |                                     17 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       58% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,645 |                   208,008 |                     351 |                     19,363 |                                       10% |                               191,986 |                                254,383 |
| [United Kingdom](/united-kingdom) |           46,295 |                    50,527 |                     748 |                      4,232 |                                        9% |                                46,646 |                                 59,774 |
|                   [Italy](/italy) |           35,166 |                    35,670 |                     591 |                        504 |                                        1% |                                35,190 |                                 37,495 |
|                 [France](/france) |           30,268 |                    31,217 |                     466 |                        949 |                                        3% |                                30,289 |                                 36,218 |
|                   [Spain](/spain) |           28,472 |                    30,548 |                     651 |                      2,076 |                                        7% |                                28,546 |                                 39,195 |
|               [Belgium](/belgium) |            9,850 |                    10,092 |                     881 |                        242 |                                        2% |                                 9,881 |                                 10,786 |
|               [Germany](/germany) |            9,154 |                     9,976 |                     120 |                        822 |                                        9% |                                 9,185 |                                 12,581 |
|       [Netherlands](/netherlands) |            6,169 |                     6,371 |                     369 |                        202 |                                        3% |                                 6,184 |                                  7,124 |
|                 [Sweden](/sweden) |            5,744 |                     6,093 |                     596 |                        349 |                                        6% |                                 5,816 |                                  6,638 |
|               [Romania](/romania) |            2,432 |                     5,504 |                     283 |                      3,072 |                                      126% |                                 3,364 |                                 10,040 |
|               [Ukraine](/ukraine) |            1,762 |                     3,357 |                      76 |                      1,595 |                                       91% |                                 2,236 |                                  5,777 |
|                 [Poland](/poland) |            1,732 |                     2,730 |                      72 |                        998 |                                       58% |                                 1,896 |                                  5,205 |
|             [Portugal](/portugal) |            1,738 |                     2,112 |                     205 |                        374 |                                       22% |                                 1,753 |                                  3,006 |
|       [Switzerland](/switzerland) |            1,981 |                     2,061 |                     240 |                         80 |                                        4% |                                 1,994 |                                  2,341 |
|               [Ireland](/ireland) |            1,763 |                     1,833 |                     374 |                         70 |                                        4% |                                 1,776 |                                  2,029 |
|               [Moldova](/moldova) |              800 |                     1,419 |                     351 |                        619 |                                       77% |                                 1,013 |                                  2,165 |
|                 [Serbia](/serbia) |              598 |                     1,333 |                     191 |                        735 |                                      123% |                                   834 |                                  2,670 |
|             [Bulgaria](/bulgaria) |              404 |                     1,234 |                     176 |                        830 |                                      205% |                                   647 |                                  2,462 |
|               [Austria](/austria) |              718 |                       845 |                      95 |                        127 |                                       18% |                                   739 |                                  1,143 |
|               [Belarus](/belarus) |              571 |                       831 |                      88 |                        260 |                                       45% |                                   722 |                                  1,028 |
|               [Denmark](/denmark) |              616 |                       715 |                     123 |                         99 |                                       16% |                                   631 |                                    935 |
|               [Hungary](/hungary) |              597 |                       681 |                      70 |                         84 |                                       14% |                                   604 |                                    899 |
|               [Czechia](/czechia) |              386 |                       676 |                      63 |                        290 |                                       75% |                                   431 |                                  1,338 |
|               [Croatia](/croatia) |              153 |                       486 |                     119 |                        333 |                                      218% |                                   241 |                                    997 |
|               [Finland](/finland) |              329 |                       371 |                      67 |                         42 |                                       13% |                                   339 |                                    458 |
|                 [Greece](/greece) |              209 |                       327 |                      31 |                        118 |                                       57% |                                   236 |                                    547 |
|                 [Norway](/norway) |              256 |                       294 |                      55 |                         38 |                                       15% |                                   263 |                                    389 |
|         [Luxembourg](/luxembourg) |              118 |                       220 |                     359 |                        102 |                                       87% |                                   139 |                                    435 |
|             [Slovenia](/slovenia) |              122 |                       174 |                      84 |                         52 |                                       43% |                                   131 |                                    275 |
|           [Lithuania](/lithuania) |               80 |                        99 |                      36 |                         19 |                                       24% |                                    85 |                                    133 |
|               [Estonia](/estonia) |               63 |                        74 |                      56 |                         11 |                                       17% |                                    69 |                                     87 |
|                 [Latvia](/latvia) |               32 |                        43 |                      22 |                         11 |                                       33% |                                    34 |                                     58 |
|             [Slovakia](/slovakia) |               29 |                        41 |                       7 |                         12 |                                       40% |                                    30 |                                     70 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      31 |                          9 |                                       45% |                                    22 |                                     43 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       38% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    10 |                                     20 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          328,646 |                   649,846 |                     125 |                    321,200 |                                       98% |                               436,735 |                              1,008,310 |
|                             [Brazil](/brazil) |           94,665 |                   171,418 |                     812 |                     76,753 |                                       81% |                               114,897 |                                262,320 |
|                               [India](/india) |           38,938 |                   122,326 |                      90 |                     83,388 |                                      214% |                                67,915 |                                182,884 |
|                             [Mexico](/mexico) |           48,012 |                    86,769 |                     680 |                     38,757 |                                       81% |                                70,348 |                                125,997 |
|                         [Colombia](/colombia) |           11,017 |                    34,306 |                     681 |                     23,289 |                                      211% |                                20,027 |                                 55,227 |
|                                 [Peru](/peru) |           19,811 |                    30,750 |                     946 |                     10,939 |                                       55% |                                24,000 |                                 45,999 |
|                                 [Iran](/iran) |           17,405 |                    29,202 |                     352 |                     11,797 |                                       68% |                                21,850 |                                 41,065 |
|                 [South Africa](/south-africa) |            8,539 |                    23,066 |                     394 |                     14,527 |                                      170% |                                12,818 |                                 33,574 |
|                             [Russia](/russia) |           14,183 |                    21,939 |                     150 |                      7,756 |                                       55% |                                15,611 |                                 38,386 |
|                               [Chile](/chile) |            9,707 |                    14,114 |                     745 |                      4,407 |                                       45% |                                10,526 |                                 25,145 |
|                       [Argentina](/argentina) |            3,813 |                    13,497 |                     301 |                      9,684 |                                      254% |                                 7,372 |                                 23,503 |
|                       [Indonesia](/indonesia) |            5,302 |                    13,338 |                      49 |                      8,036 |                                      152% |                                 7,437 |                                 26,188 |
|                             [Canada](/canada) |            8,995 |                     9,407 |                     251 |                        412 |                                        5% |                                 9,030 |                                 10,527 |
|                           [Bolivia](/bolivia) |            3,228 |                     8,252 |                     717 |                      5,024 |                                      156% |                                 4,889 |                                 13,956 |
|                           [Ecuador](/ecuador) |            5,767 |                     7,475 |                     430 |                      1,708 |                                       30% |                                 6,000 |                                 10,461 |
|                         [Pakistan](/pakistan) |            5,999 |                     7,177 |                      33 |                      1,178 |                                       20% |                                 6,269 |                                  8,757 |
|                             [Turkey](/turkey) |            5,747 |                     7,144 |                      86 |                      1,397 |                                       24% |                                 5,802 |                                 10,810 |
|                               [Egypt](/egypt) |            4,888 |                     6,729 |                      67 |                      1,841 |                                       38% |                                 5,133 |                                  9,193 |
|                     [Bangladesh](/bangladesh) |            3,184 |                     5,392 |                      33 |                      2,208 |                                       69% |                                 3,583 |                                  9,034 |
|                   [Philippines](/philippines) |            2,104 |                     5,252 |                      49 |                      3,148 |                                      150% |                                 2,398 |                                 13,922 |
|                               [China](/china) |            4,672 |                     5,138 |                       4 |                        466 |                                       10% |                                 4,672 |                                  7,465 |
|                 [Saudi Arabia](/saudi-arabia) |            2,949 |                     4,810 |                     140 |                      1,861 |                                       63% |                                 3,484 |                                  6,989 |
|                         [Honduras](/honduras) |            1,384 |                     4,004 |                     411 |                      2,620 |                                      189% |                                 2,187 |                                  7,916 |
|                             [Panama](/panama) |            1,497 |                     3,473 |                     818 |                      1,976 |                                      132% |                                 2,163 |                                  6,076 |
|                           [Morocco](/morocco) |              401 |                     2,520 |                      69 |                      2,119 |                                      528% |                                   731 |                                  6,986 |
|     [Dominican Republic](/dominican-republic) |            1,183 |                     2,409 |                     224 |                      1,226 |                                      104% |                                 1,531 |                                  4,383 |
|                           [Algeria](/algeria) |            1,239 |                     2,330 |                      54 |                      1,091 |                                       88% |                                 1,420 |                                  4,788 |
|                               [Japan](/japan) |            1,018 |                     1,699 |                      13 |                        681 |                                       67% |                                 1,037 |                                  5,302 |
|                             [Israel](/israel) |              546 |                     1,547 |                     182 |                      1,001 |                                      183% |                                   792 |                                  3,118 |
|                           [Nigeria](/nigeria) |              896 |                     1,350 |                       7 |                        454 |                                       51% |                                   963 |                                  2,373 |
|                       [Australia](/australia) |              232 |                     1,054 |                      42 |                        822 |                                      354% |                                   451 |                                  2,492 |
|                             [Kuwait](/kuwait) |              461 |                       866 |                     206 |                        405 |                                       88% |                                   511 |                                  1,779 |
| [United Arab Emirates](/united-arab-emirates) |              351 |                       452 |                      46 |                        101 |                                       29% |                                   359 |                                    743 |
|                   [South Korea](/south-korea) |              301 |                       375 |                       7 |                         74 |                                       25% |                                   301 |                                    617 |
|                         [Malaysia](/malaysia) |              125 |                       153 |                       5 |                         28 |                                       23% |                                   135 |                                    171 |
|                                 [Cuba](/cuba) |               87 |                       114 |                      10 |                         27 |                                       32% |                                    93 |                                    164 |
