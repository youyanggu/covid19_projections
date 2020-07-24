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
* **July 23:** We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* **July 21:** View our [updated historical performance](/about/#historical-performance).
* **July 8:** We have extended our projections through November 1, 2020. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 24 (3am ET):
<p align="center">
  Current Total: <b>144,301</b> deaths | Projected Total: <b>218,600 deaths by Nov 1, 2020</b> (Range: 186-269k)<br>
  Currently Infected: <b>2.0%</b> | Total Infected: <b>10.6%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 24, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 30, 2020 |
|              175,000 |        Aug 27, 2020 |
|              200,000 |         Oct 5, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          8% |        72% |         96% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         6% |         24% |        46% |         61% |        73% |
|              225,000 |        <1% |         <1% |        <1% |          2% |        10% |         17% |        27% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         1% |          4% |         8% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          144,301 |                   218,627 |                     659 |                     74,326 |                                       52% |                               186,743 |                                268,170 |
|                 [New York](/us-ny) |           32,594 |                    33,483 |                   1,721 |                        889 |                                        3% |                                32,636 |                                 37,233 |
|               [California](/us-ca) |            8,201 |                    16,953 |                     429 |                      8,752 |                                      107% |                                11,712 |                                 25,697 |
|               [New Jersey](/us-nj) |           15,730 |                    16,237 |                   1,828 |                        507 |                                        3% |                                15,797 |                                 17,038 |
|                    [Texas](/us-tx) |            4,622 |                    15,664 |                     540 |                     11,042 |                                      239% |                                 9,834 |                                 24,130 |
|                  [Florida](/us-fl) |            5,518 |                    14,397 |                     670 |                      8,879 |                                      161% |                                 9,569 |                                 21,945 |
|             [Pennsylvania](/us-pa) |            7,093 |                     9,563 |                     747 |                      2,470 |                                       35% |                                 7,427 |                                 14,200 |
|            [Massachusetts](/us-ma) |            8,484 |                     9,097 |                   1,309 |                        613 |                                        7% |                                 8,567 |                                 10,149 |
|                 [Illinois](/us-il) |            7,560 |                     8,862 |                     699 |                      1,302 |                                       17% |                                 7,767 |                                 10,700 |
|                 [Michigan](/us-mi) |            6,395 |                     7,310 |                     732 |                        915 |                                       14% |                                 6,518 |                                  9,397 |
|                  [Georgia](/us-ga) |            3,361 |                     7,001 |                     659 |                      3,640 |                                      108% |                                 4,330 |                                 12,182 |
|                  [Arizona](/us-az) |            3,063 |                     6,759 |                     929 |                      3,696 |                                      121% |                                 4,940 |                                  9,336 |
|                     [Ohio](/us-oh) |            3,256 |                     5,957 |                     510 |                      2,701 |                                       83% |                                 3,904 |                                 10,512 |
|                [Louisiana](/us-la) |            3,574 |                     5,511 |                   1,186 |                      1,937 |                                       54% |                                 4,034 |                                  8,278 |
|              [Connecticut](/us-ct) |            4,410 |                     4,645 |                   1,303 |                        235 |                                        5% |                                 4,449 |                                  5,101 |
|                  [Indiana](/us-in) |            2,880 |                     4,464 |                     663 |                      1,584 |                                       55% |                                 3,119 |                                  7,723 |
|                 [Maryland](/us-md) |            3,409 |                     4,081 |                     675 |                        672 |                                       20% |                                 3,519 |                                  5,326 |
|           [South Carolina](/us-sc) |            1,334 |                     3,789 |                     736 |                      2,455 |                                      184% |                                 2,527 |                                  5,595 |
|           [North Carolina](/us-nc) |            1,756 |                     3,726 |                     355 |                      1,970 |                                      112% |                                 2,408 |                                  6,096 |
|                 [Virginia](/us-va) |            2,054 |                     3,681 |                     431 |                      1,627 |                                       79% |                                 2,306 |                                  7,139 |
|                  [Alabama](/us-al) |            1,397 |                     3,576 |                     729 |                      2,179 |                                      156% |                                 2,377 |                                  5,487 |
|                 [Colorado](/us-co) |            1,786 |                     2,876 |                     499 |                      1,090 |                                       61% |                                 2,018 |                                  5,093 |
|              [Mississippi](/us-ms) |            1,436 |                     2,685 |                     902 |                      1,249 |                                       87% |                                 1,958 |                                  3,907 |
|                [Minnesota](/us-mn) |            1,601 |                     2,417 |                     428 |                        816 |                                       51% |                                 1,788 |                                  3,919 |
|                [Tennessee](/us-tn) |              925 |                     2,400 |                     351 |                      1,475 |                                      159% |                                 1,594 |                                  3,706 |
|                 [Missouri](/us-mo) |            1,189 |                     2,325 |                     379 |                      1,136 |                                       96% |                                 1,422 |                                  4,387 |
|                   [Nevada](/us-nv) |              709 |                     2,239 |                     727 |                      1,530 |                                      216% |                                 1,336 |                                  3,777 |
|               [Washington](/us-wa) |            1,482 |                     2,046 |                     269 |                        564 |                                       38% |                                 1,560 |                                  3,066 |
|                [Wisconsin](/us-wi) |              878 |                     1,879 |                     323 |                      1,001 |                                      114% |                                 1,076 |                                  3,924 |
|                 [Kentucky](/us-ky) |              684 |                     1,735 |                     388 |                      1,051 |                                      154% |                                   910 |                                  3,668 |
|                     [Iowa](/us-ia) |              820 |                     1,534 |                     486 |                        714 |                                       87% |                                 1,000 |                                  2,744 |
|             [Rhode Island](/us-ri) |            1,001 |                     1,178 |                   1,112 |                        177 |                                       18% |                                 1,033 |                                  1,406 |
|               [New Mexico](/us-nm) |              596 |                     1,080 |                     515 |                        484 |                                       81% |                                   676 |                                  1,890 |
|                 [Oklahoma](/us-ok) |              477 |                       960 |                     243 |                        483 |                                      101% |                                   613 |                                  1,624 |
|                 [Arkansas](/us-ar) |              386 |                       957 |                     317 |                        571 |                                      148% |                                   608 |                                  1,550 |
|                     [Utah](/us-ut) |              267 |                       867 |                     270 |                        600 |                                      225% |                                   492 |                                  1,518 |
|                   [Oregon](/us-or) |              273 |                       866 |                     205 |                        593 |                                      217% |                                   443 |                                  1,791 |
|                    [Idaho](/us-id) |              138 |                       859 |                     480 |                        721 |                                      522% |                                   395 |                                  1,617 |
|              [Puerto Rico](/us-pr) |              188 |                       662 |                     207 |                        474 |                                      252% |                                   253 |                                  1,681 |
|     [District of Columbia](/us-dc) |              581 |                       646 |                     916 |                         65 |                                       11% |                                   594 |                                    758 |
|                 [Delaware](/us-de) |              529 |                       627 |                     644 |                         98 |                                       18% |                                   544 |                                    797 |
|                   [Kansas](/us-ks) |              322 |                       615 |                     211 |                        293 |                                       91% |                                   401 |                                  1,057 |
|            [New Hampshire](/us-nh) |              405 |                       540 |                     397 |                        135 |                                       33% |                                   420 |                                    779 |
|                 [Nebraska](/us-ne) |              316 |                       527 |                     273 |                        211 |                                       67% |                                   355 |                                    862 |
|             [South Dakota](/us-sd) |              121 |                       228 |                     258 |                        107 |                                       89% |                                   155 |                                    375 |
|             [North Dakota](/us-nd) |               97 |                       222 |                     291 |                        125 |                                      128% |                                   127 |                                    419 |
|                  [Montana](/us-mt) |               43 |                       217 |                     203 |                        174 |                                      405% |                                   102 |                                    441 |
|            [West Virginia](/us-wv) |              102 |                       189 |                     105 |                         87 |                                       85% |                                   123 |                                    376 |
|                    [Maine](/us-me) |              118 |                       173 |                     129 |                         55 |                                       47% |                                   129 |                                    259 |
|                   [Hawaii](/us-hi) |               26 |                        93 |                      65 |                         67 |                                      256% |                                    37 |                                    236 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     121 |                         20 |                                       35% |                                    62 |                                    101 |
|                   [Alaska](/us-ak) |               19 |                        65 |                      88 |                         46 |                                      240% |                                    30 |                                    142 |
|                  [Wyoming](/us-wy) |               25 |                        54 |                      93 |                         29 |                                      116% |                                    37 |                                     95 |
|           [Virgin Islands](/us-vi) |                7 |                        24 |                     228 |                         17 |                                      242% |                                    11 |                                     56 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                       99% |                                     6 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      102% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,635 |                   201,026 |                     339 |                     14,391 |                                        8% |                               190,305 |                                228,000 |
| [United Kingdom](/united-kingdom) |           45,639 |                    48,178 |                     713 |                      2,539 |                                        6% |                                45,799 |                                 54,001 |
|                   [Italy](/italy) |           35,092 |                    35,709 |                     592 |                        617 |                                        2% |                                35,116 |                                 37,345 |
|                 [France](/france) |           30,185 |                    30,868 |                     461 |                        683 |                                        2% |                                30,215 |                                 34,342 |
|                   [Spain](/spain) |           28,429 |                    28,924 |                     616 |                        495 |                                        2% |                                28,452 |                                 31,159 |
|               [Belgium](/belgium) |            9,812 |                     9,893 |                     864 |                         81 |                                        1% |                                 9,828 |                                 10,189 |
|               [Germany](/germany) |            9,110 |                     9,387 |                     113 |                        277 |                                        3% |                                 9,123 |                                 10,551 |
|       [Netherlands](/netherlands) |            6,158 |                     6,232 |                     361 |                         74 |                                        1% |                                 6,168 |                                  6,466 |
|                 [Sweden](/sweden) |            5,676 |                     6,139 |                     600 |                        463 |                                        8% |                                 5,787 |                                  6,906 |
|               [Romania](/romania) |            2,126 |                     4,603 |                     237 |                      2,477 |                                      117% |                                 3,215 |                                  7,407 |
|               [Ukraine](/ukraine) |            1,570 |                     3,168 |                      72 |                      1,598 |                                      102% |                                 2,235 |                                  4,956 |
|                 [Poland](/poland) |            1,651 |                     2,202 |                      58 |                        551 |                                       33% |                                 1,725 |                                  3,212 |
|             [Portugal](/portugal) |            1,705 |                     2,188 |                     213 |                        483 |                                       28% |                                 1,760 |                                  2,976 |
|       [Switzerland](/switzerland) |            1,975 |                     2,053 |                     239 |                         78 |                                        4% |                                 1,987 |                                  2,250 |
|               [Ireland](/ireland) |            1,763 |                     1,853 |                     378 |                         90 |                                        5% |                                 1,775 |                                  2,163 |
|                 [Serbia](/serbia) |              508 |                     1,635 |                     235 |                      1,127 |                                      222% |                                 1,003 |                                  2,734 |
|               [Moldova](/moldova) |              719 |                     1,484 |                     367 |                        765 |                                      106% |                                   983 |                                  2,195 |
|               [Belarus](/belarus) |              519 |                       983 |                     104 |                        464 |                                       89% |                                   690 |                                  1,461 |
|             [Bulgaria](/bulgaria) |              329 |                       956 |                     137 |                        627 |                                      190% |                                   555 |                                  1,659 |
|               [Austria](/austria) |              711 |                       783 |                      88 |                         72 |                                       10% |                                   728 |                                    909 |
|               [Hungary](/hungary) |              596 |                       699 |                      72 |                        103 |                                       17% |                                   610 |                                    916 |
|               [Denmark](/denmark) |              612 |                       690 |                     119 |                         78 |                                       13% |                                   629 |                                    816 |
|               [Czechia](/czechia) |              365 |                       551 |                      52 |                        186 |                                       51% |                                   404 |                                    866 |
|               [Finland](/finland) |              328 |                       380 |                      69 |                         52 |                                       16% |                                   340 |                                    481 |
|               [Croatia](/croatia) |              128 |                       311 |                      76 |                        183 |                                      143% |                                   191 |                                    541 |
|                 [Norway](/norway) |              255 |                       284 |                      53 |                         29 |                                       11% |                                   263 |                                    331 |
|                 [Greece](/greece) |              201 |                       247 |                      23 |                         46 |                                       23% |                                   211 |                                    306 |
|         [Luxembourg](/luxembourg) |              112 |                       159 |                     259 |                         47 |                                       42% |                                   128 |                                    221 |
|             [Slovenia](/slovenia) |              115 |                       137 |                      66 |                         22 |                                       19% |                                   119 |                                    175 |
|           [Lithuania](/lithuania) |               80 |                       106 |                      38 |                         26 |                                       32% |                                    84 |                                    144 |
|               [Estonia](/estonia) |               69 |                        90 |                      68 |                         21 |                                       30% |                                    77 |                                    124 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       33% |                                    33 |                                     61 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    29 |                                     53 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       52% |                                    22 |                                     43 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       63% |                                    11 |                                     20 |
|               [Iceland](/iceland) |               10 |                        14 |                      40 |                          4 |                                       37% |                                    10 |                                     21 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          284,935 |                   665,284 |                     128 |                    380,349 |                                      133% |                               418,539 |                              1,077,002 |
|                             [Brazil](/brazil) |           84,082 |                   170,403 |                     807 |                     86,321 |                                      103% |                               118,225 |                                264,758 |
|                               [India](/india) |           30,601 |                   138,705 |                     102 |                    108,104 |                                      353% |                                64,700 |                                229,033 |
|                             [Mexico](/mexico) |           41,908 |                    90,554 |                     710 |                     48,646 |                                      116% |                                62,195 |                                158,694 |
|                                 [Peru](/peru) |           17,654 |                    29,559 |                     909 |                     11,905 |                                       67% |                                20,092 |                                 46,086 |
|                         [Colombia](/colombia) |            7,688 |                    28,154 |                     559 |                     20,466 |                                      266% |                                18,204 |                                 41,296 |
|                                 [Iran](/iran) |           15,074 |                    27,550 |                     332 |                     12,476 |                                       83% |                                21,022 |                                 37,531 |
|                 [South Africa](/south-africa) |            6,093 |                    25,057 |                     428 |                     18,964 |                                      311% |                                12,147 |                                 41,779 |
|                             [Russia](/russia) |           12,873 |                    23,060 |                     158 |                     10,187 |                                       79% |                                14,827 |                                 39,868 |
|                       [Indonesia](/indonesia) |            4,576 |                    19,678 |                      73 |                     15,102 |                                      330% |                                10,011 |                                 38,086 |
|                               [Chile](/chile) |            8,838 |                    15,093 |                     796 |                      6,255 |                                       71% |                                 9,757 |                                 26,585 |
|                       [Argentina](/argentina) |            2,702 |                    10,664 |                     238 |                      7,962 |                                      295% |                                 5,867 |                                 16,648 |
|                             [Canada](/canada) |            8,919 |                     9,436 |                     252 |                        517 |                                        6% |                                 8,948 |                                 10,539 |
|                         [Pakistan](/pakistan) |            5,763 |                     8,243 |                      38 |                      2,480 |                                       43% |                                 6,489 |                                 11,862 |
|                           [Ecuador](/ecuador) |            5,439 |                     7,942 |                     457 |                      2,503 |                                       46% |                                 5,676 |                                 11,607 |
|                               [Egypt](/egypt) |            4,480 |                     7,912 |                      79 |                      3,432 |                                       77% |                                 5,212 |                                 13,428 |
|                             [Turkey](/turkey) |            5,563 |                     6,694 |                      80 |                      1,131 |                                       20% |                                 5,697 |                                  8,803 |
|                           [Bolivia](/bolivia) |            2,407 |                     6,409 |                     557 |                      4,002 |                                      166% |                                 4,172 |                                  9,677 |
|                     [Bangladesh](/bangladesh) |            2,801 |                     5,649 |                      35 |                      2,848 |                                      102% |                                 3,285 |                                 10,139 |
|                   [Philippines](/philippines) |            1,871 |                     5,368 |                      50 |                      3,497 |                                      187% |                                 2,258 |                                 11,967 |
|                 [Saudi Arabia](/saudi-arabia) |            2,635 |                     5,212 |                     152 |                      2,577 |                                       98% |                                 3,592 |                                  8,146 |
|                               [China](/china) |            4,649 |                     4,695 |                       3 |                         46 |                                        1% |                                 4,649 |                                  5,035 |
|                             [Panama](/panama) |            1,209 |                     3,389 |                     798 |                      2,180 |                                      180% |                                 2,278 |                                  5,102 |
|                         [Honduras](/honduras) |            1,011 |                     3,324 |                     341 |                      2,313 |                                      229% |                                 1,820 |                                  5,841 |
|                           [Algeria](/algeria) |            1,124 |                     2,335 |                      54 |                      1,211 |                                      108% |                                 1,316 |                                  4,810 |
|     [Dominican Republic](/dominican-republic) |            1,006 |                     1,945 |                     181 |                        939 |                                       93% |                                 1,303 |                                  3,216 |
|                           [Nigeria](/nigeria) |              833 |                     1,684 |                       8 |                        851 |                                      102% |                                   930 |                                  3,873 |
|                             [Israel](/israel) |              442 |                     1,599 |                     188 |                      1,157 |                                      262% |                                   829 |                                  2,749 |
|                               [Japan](/japan) |              992 |                     1,344 |                      11 |                        352 |                                       35% |                                 1,000 |                                  2,634 |
|                       [Australia](/australia) |              139 |                       998 |                      40 |                        859 |                                      618% |                                   301 |                                  2,520 |
|                           [Morocco](/morocco) |              292 |                       852 |                      23 |                        560 |                                      192% |                                   412 |                                  1,756 |
|                             [Kuwait](/kuwait) |              421 |                       650 |                     155 |                        229 |                                       54% |                                   447 |                                  1,186 |
| [United Arab Emirates](/united-arab-emirates) |              342 |                       471 |                      48 |                        129 |                                       38% |                                   352 |                                    802 |
|                   [South Korea](/south-korea) |              298 |                       385 |                       8 |                         87 |                                       29% |                                   300 |                                    625 |
|                         [Malaysia](/malaysia) |              123 |                       160 |                       5 |                         37 |                                       30% |                                   136 |                                    182 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       24% |                                    90 |                                    139 |
