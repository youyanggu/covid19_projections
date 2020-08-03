We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >97% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5-8x higher than the reported cases.

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
* **August 3:** View our [updated historical performance](/about/#historical-performance).
* **July 31:** We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* **July 23:** We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: August 3 (5pm ET):
<p align="center">
  Current Total: <b>154,857</b> deaths | Projected Total: <b>228,300 deaths by Nov 1, 2020</b> (Range: 198-271k)<br>
  Currently Infected: <b>2.0%</b> (1 in 50) | Total Infected: <b>12.0%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 3, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 23, 2020 |
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |          2% |        98% |         99% |        99% |         99% |       >99% |
|              200,000 |         <1% |         3% |         33% |        71% |         87% |        96% |
|              225,000 |         <1% |        <1% |          1% |        11% |         27% |        46% |
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
|                          *Europe* |          188,509 |                   208,338 |                     351 |                     19,829 |                                       11% |                               191,976 |                                255,414 |
| [United Kingdom](/united-kingdom) |           46,286 |                    50,597 |                     749 |                      4,311 |                                        9% |                                46,660 |                                 59,803 |
|                   [Italy](/italy) |           35,154 |                    35,661 |                     591 |                        507 |                                        1% |                                35,178 |                                 37,492 |
|                 [France](/france) |           30,268 |                    31,237 |                     466 |                        969 |                                        3% |                                30,290 |                                 36,336 |
|                   [Spain](/spain) |           28,445 |                    30,512 |                     650 |                      2,067 |                                        7% |                                28,520 |                                 39,207 |
|               [Belgium](/belgium) |            9,845 |                    10,086 |                     880 |                        241 |                                        2% |                                 9,876 |                                 10,779 |
|               [Germany](/germany) |            9,154 |                     9,988 |                     120 |                        834 |                                        9% |                                 9,186 |                                 12,607 |
|       [Netherlands](/netherlands) |            6,169 |                     6,373 |                     369 |                        204 |                                        3% |                                 6,184 |                                  7,129 |
|                 [Sweden](/sweden) |            5,743 |                     6,102 |                     596 |                        359 |                                        6% |                                 5,818 |                                  6,658 |
|               [Romania](/romania) |            2,413 |                     5,718 |                     295 |                      3,305 |                                      137% |                                 3,453 |                                 10,326 |
|               [Ukraine](/ukraine) |            1,749 |                     3,437 |                      78 |                      1,688 |                                       97% |                                 2,245 |                                  5,945 |
|                 [Poland](/poland) |            1,731 |                     2,860 |                      75 |                      1,129 |                                       65% |                                 1,903 |                                  5,735 |
|             [Portugal](/portugal) |            1,738 |                     2,129 |                     207 |                        391 |                                       23% |                                 1,754 |                                  3,038 |
|       [Switzerland](/switzerland) |            1,981 |                     2,062 |                     240 |                         81 |                                        4% |                                 1,994 |                                  2,347 |
|               [Ireland](/ireland) |            1,763 |                     1,833 |                     374 |                         70 |                                        4% |                                 1,776 |                                  2,031 |
|               [Moldova](/moldova) |              791 |                     1,409 |                     349 |                        618 |                                       78% |                                 1,002 |                                  2,160 |
|                 [Serbia](/serbia) |              590 |                     1,339 |                     192 |                        749 |                                      127% |                                   831 |                                  2,700 |
|             [Bulgaria](/bulgaria) |              388 |                     1,109 |                     158 |                        721 |                                      186% |                                   593 |                                  2,266 |
|               [Austria](/austria) |              718 |                       847 |                      96 |                        129 |                                       18% |                                   739 |                                  1,147 |
|               [Belarus](/belarus) |              567 |                       832 |                      88 |                        265 |                                       47% |                                   721 |                                  1,032 |
|               [Denmark](/denmark) |              615 |                       713 |                     123 |                         98 |                                       16% |                                   630 |                                    935 |
|               [Hungary](/hungary) |              597 |                       682 |                      70 |                         85 |                                       14% |                                   604 |                                    904 |
|               [Czechia](/czechia) |              384 |                       675 |                      63 |                        291 |                                       76% |                                   428 |                                  1,345 |
|               [Croatia](/croatia) |              149 |                       454 |                     111 |                        305 |                                      204% |                                   230 |                                    963 |
|               [Finland](/finland) |              329 |                       371 |                      67 |                         42 |                                       13% |                                   339 |                                    459 |
|                 [Greece](/greece) |              208 |                       325 |                      30 |                        117 |                                       56% |                                   234 |                                    546 |
|                 [Norway](/norway) |              255 |                       293 |                      54 |                         38 |                                       15% |                                   262 |                                    388 |
|         [Luxembourg](/luxembourg) |              117 |                       214 |                     348 |                         97 |                                       83% |                                   137 |                                    429 |
|             [Slovenia](/slovenia) |              120 |                       167 |                      80 |                         47 |                                       39% |                                   129 |                                    267 |
|           [Lithuania](/lithuania) |               80 |                       100 |                      36 |                         20 |                                       25% |                                    85 |                                    134 |
|               [Estonia](/estonia) |               63 |                        74 |                      56 |                         11 |                                       18% |                                    69 |                                     92 |
|                 [Latvia](/latvia) |               32 |                        43 |                      22 |                         11 |                                       34% |                                    34 |                                     58 |
|             [Slovakia](/slovakia) |               29 |                        41 |                       8 |                         12 |                                       42% |                                    30 |                                     71 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       46% |                                    22 |                                     43 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       39% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       45% |                                    10 |                                     20 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          325,253 |                   653,464 |                     126 |                    328,211 |                                      101% |                               436,140 |                              1,015,884 |
|                             [Brazil](/brazil) |           94,104 |                   173,297 |                     821 |                     79,193 |                                       84% |                               115,095 |                                265,027 |
|                               [India](/india) |           38,135 |                   122,313 |                      90 |                     84,178 |                                      221% |                                67,162 |                                182,931 |
|                             [Mexico](/mexico) |           47,746 |                    88,126 |                     691 |                     40,380 |                                       85% |                                70,754 |                                128,445 |
|                         [Colombia](/colombia) |           10,650 |                    33,778 |                     671 |                     23,128 |                                      217% |                                19,638 |                                 55,308 |
|                                 [Peru](/peru) |           19,614 |                    32,083 |                     987 |                     12,469 |                                       64% |                                24,950 |                                 47,147 |
|                                 [Iran](/iran) |           17,190 |                    29,127 |                     351 |                     11,937 |                                       69% |                                21,710 |                                 41,001 |
|                 [South Africa](/south-africa) |            8,366 |                    23,223 |                     397 |                     14,857 |                                      178% |                                12,873 |                                 33,743 |
|                             [Russia](/russia) |           14,104 |                    22,118 |                     152 |                      8,014 |                                       57% |                                15,597 |                                 38,749 |
|                               [Chile](/chile) |            9,608 |                    14,027 |                     740 |                      4,419 |                                       46% |                                10,446 |                                 25,059 |
|                       [Indonesia](/indonesia) |            5,236 |                    13,497 |                      50 |                      8,261 |                                      158% |                                 7,426 |                                 26,517 |
|                       [Argentina](/argentina) |            3,648 |                    12,766 |                     285 |                      9,118 |                                      250% |                                 6,854 |                                 23,164 |
|                             [Canada](/canada) |            8,990 |                     9,407 |                     251 |                        417 |                                        5% |                                 9,026 |                                 10,532 |
|                           [Bolivia](/bolivia) |            3,153 |                     8,267 |                     718 |                      5,114 |                                      162% |                                 4,849 |                                 14,069 |
|                           [Ecuador](/ecuador) |            5,736 |                     7,472 |                     430 |                      1,736 |                                       30% |                                 5,951 |                                 10,543 |
|                         [Pakistan](/pakistan) |            5,976 |                     7,180 |                      33 |                      1,204 |                                       20% |                                 6,262 |                                  8,784 |
|                             [Turkey](/turkey) |            5,728 |                     7,129 |                      85 |                      1,401 |                                       24% |                                 5,785 |                                 10,832 |
|                               [Egypt](/egypt) |            4,865 |                     6,766 |                      67 |                      1,901 |                                       39% |                                 5,134 |                                  9,295 |
|                     [Bangladesh](/bangladesh) |            3,154 |                     5,438 |                      33 |                      2,284 |                                       72% |                                 3,571 |                                  9,120 |
|                               [China](/china) |            4,669 |                     5,137 |                       4 |                        468 |                                       10% |                                 4,669 |                                  7,475 |
|                   [Philippines](/philippines) |            2,059 |                     5,130 |                      47 |                      3,071 |                                      149% |                                 2,308 |                                 13,706 |
|                 [Saudi Arabia](/saudi-arabia) |            2,917 |                     4,798 |                     140 |                      1,881 |                                       64% |                                 3,438 |                                  6,998 |
|                         [Honduras](/honduras) |            1,377 |                     4,283 |                     440 |                      2,906 |                                      211% |                                 2,288 |                                  8,459 |
|                             [Panama](/panama) |            1,471 |                     3,512 |                     827 |                      2,041 |                                      139% |                                 2,157 |                                  6,300 |
|     [Dominican Republic](/dominican-republic) |            1,178 |                     2,500 |                     233 |                      1,322 |                                      112% |                                 1,543 |                                  4,577 |
|                           [Algeria](/algeria) |            1,231 |                     2,347 |                      55 |                      1,116 |                                       91% |                                 1,417 |                                  4,839 |
|                           [Morocco](/morocco) |              382 |                     2,314 |                      63 |                      1,932 |                                      506% |                                   679 |                                  6,785 |
|                               [Japan](/japan) |            1,013 |                     1,692 |                      13 |                        679 |                                       67% |                                 1,032 |                                  5,298 |
|                             [Israel](/israel) |              536 |                     1,554 |                     182 |                      1,018 |                                      190% |                                   785 |                                  3,168 |
|                           [Nigeria](/nigeria) |              888 |                     1,341 |                       7 |                        453 |                                       51% |                                   957 |                                  2,368 |
|                       [Australia](/australia) |              208 |                       881 |                      35 |                        673 |                                      324% |                                   387 |                                  2,152 |
|                             [Kuwait](/kuwait) |              457 |                       863 |                     205 |                        406 |                                       89% |                                   508 |                                  1,779 |
| [United Arab Emirates](/united-arab-emirates) |              351 |                       454 |                      46 |                        103 |                                       29% |                                   360 |                                    751 |
|                   [South Korea](/south-korea) |              301 |                       377 |                       7 |                         76 |                                       25% |                                   301 |                                    626 |
|                         [Malaysia](/malaysia) |              125 |                       153 |                       5 |                         28 |                                       23% |                                   135 |                                    172 |
|                                 [Cuba](/cuba) |               87 |                       115 |                      10 |                         28 |                                       32% |                                    93 |                                    165 |
