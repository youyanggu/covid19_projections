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
* **July 28:** View our [updated historical performance](/about/#historical-performance).
* **July 23:** We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* **July 8:** We have extended our projections through November 1, 2020. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 30 (2am ET):
<p align="center">
  Current Total: <b>150,710</b> deaths | Projected Total: <b>227,000 deaths by Nov 1, 2020</b> (Range: 196-271k)<br>
  Currently Infected: <b>2.0%</b> | Total Infected: <b>11.3%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 30, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 23, 2020 |
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |        <1% |          4% |        95% |         99% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         4% |         31% |        66% |         83% |        92% |
|              225,000 |        <1% |         <1% |        <1% |          2% |        11% |         25% |        42% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          5% |        11% |
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
|             *[United States](/us)* |          150,710 |                   227,011 |                     684 |                     76,301 |                                       51% |                               196,221 |                                270,806 |
|                 [New York](/us-ny) |           32,658 |                    33,731 |                   1,734 |                      1,073 |                                        3% |                                32,711 |                                 38,354 |
|               [California](/us-ca) |            8,908 |                    19,982 |                     506 |                     11,074 |                                      124% |                                14,275 |                                 27,971 |
|                    [Texas](/us-tx) |            6,193 |                    17,888 |                     617 |                     11,695 |                                      189% |                                11,947 |                                 25,321 |
|               [New Jersey](/us-nj) |           15,798 |                    16,591 |                   1,868 |                        793 |                                        5% |                                15,892 |                                 18,019 |
|                  [Florida](/us-fl) |            6,333 |                    15,174 |                     706 |                      8,841 |                                      140% |                                10,905 |                                 21,074 |
|            [Massachusetts](/us-ma) |            8,580 |                     9,533 |                   1,372 |                        953 |                                       11% |                                 8,657 |                                 11,399 |
|                 [Illinois](/us-il) |            7,654 |                     9,378 |                     740 |                      1,724 |                                       23% |                                 7,917 |                                 11,898 |
|             [Pennsylvania](/us-pa) |            7,171 |                     9,102 |                     711 |                      1,931 |                                       27% |                                 7,321 |                                 13,285 |
|                  [Georgia](/us-ga) |            3,642 |                     6,937 |                     653 |                      3,295 |                                       90% |                                 4,792 |                                 10,113 |
|                 [Michigan](/us-mi) |            6,422 |                     6,903 |                     691 |                        481 |                                        7% |                                 6,468 |                                  8,059 |
|                  [Arizona](/us-az) |            3,454 |                     6,852 |                     941 |                      3,398 |                                       98% |                                 5,101 |                                  9,048 |
|                [Louisiana](/us-la) |            3,883 |                     5,721 |                   1,231 |                      1,838 |                                       47% |                                 4,446 |                                  7,772 |
|                     [Ohio](/us-oh) |            3,422 |                     5,591 |                     478 |                      2,169 |                                       63% |                                 3,840 |                                  8,507 |
|                 [Maryland](/us-md) |            3,478 |                     4,995 |                     826 |                      1,517 |                                       44% |                                 3,721 |                                  7,890 |
|              [Connecticut](/us-ct) |            4,425 |                     4,658 |                   1,306 |                        233 |                                        5% |                                 4,458 |                                  5,140 |
|           [South Carolina](/us-sc) |            1,615 |                     4,486 |                     871 |                      2,871 |                                      178% |                                 3,039 |                                  6,273 |
|                  [Indiana](/us-in) |            2,932 |                     4,439 |                     659 |                      1,507 |                                       51% |                                 3,180 |                                  7,211 |
|           [North Carolina](/us-nc) |            1,888 |                     3,889 |                     371 |                      2,001 |                                      106% |                                 2,549 |                                  5,937 |
|                  [Alabama](/us-al) |            1,538 |                     3,396 |                     693 |                      1,858 |                                      121% |                                 2,387 |                                  4,807 |
|                 [Virginia](/us-va) |            2,125 |                     3,300 |                     387 |                      1,175 |                                       55% |                                 2,285 |                                  5,618 |
|              [Mississippi](/us-ms) |            1,563 |                     3,097 |                   1,041 |                      1,534 |                                       98% |                                 2,107 |                                  4,482 |
|                 [Missouri](/us-mo) |            1,239 |                     2,639 |                     430 |                      1,400 |                                      113% |                                 1,525 |                                  4,866 |
|                [Tennessee](/us-tn) |            1,020 |                     2,485 |                     364 |                      1,465 |                                      144% |                                 1,632 |                                  3,653 |
|                 [Colorado](/us-co) |            1,822 |                     2,479 |                     431 |                        657 |                                       36% |                                 1,916 |                                  3,739 |
|                [Minnesota](/us-mn) |            1,629 |                     2,284 |                     405 |                        655 |                                       40% |                                 1,741 |                                  3,485 |
|               [Washington](/us-wa) |            1,555 |                     2,167 |                     285 |                        612 |                                       39% |                                 1,626 |                                  3,215 |
|                [Wisconsin](/us-wi) |              911 |                     1,793 |                     308 |                        882 |                                       97% |                                 1,105 |                                  3,378 |
|                   [Nevada](/us-nv) |              780 |                     1,734 |                     563 |                        954 |                                      122% |                                 1,175 |                                  2,483 |
|                 [Kentucky](/us-ky) |              724 |                     1,679 |                     376 |                        955 |                                      132% |                                   913 |                                  3,215 |
|                     [Iowa](/us-ia) |              854 |                     1,480 |                     469 |                        626 |                                       73% |                                 1,008 |                                  2,423 |
|                 [Oklahoma](/us-ok) |              523 |                     1,305 |                     330 |                        782 |                                      150% |                                   775 |                                  2,212 |
|             [Rhode Island](/us-ri) |            1,007 |                     1,170 |                   1,104 |                        163 |                                       16% |                                 1,034 |                                  1,389 |
|               [New Mexico](/us-nm) |              632 |                     1,094 |                     522 |                        462 |                                       73% |                                   757 |                                  1,657 |
|                 [Arkansas](/us-ar) |              434 |                     1,068 |                     354 |                        634 |                                      146% |                                   671 |                                  1,643 |
|                   [Oregon](/us-or) |              311 |                     1,022 |                     242 |                        711 |                                      228% |                                   527 |                                  1,820 |
|                     [Utah](/us-ut) |              292 |                       841 |                     262 |                        549 |                                      188% |                                   483 |                                  1,373 |
|              [Puerto Rico](/us-pr) |              211 |                       826 |                     259 |                        615 |                                      292% |                                   372 |                                  1,748 |
|                    [Idaho](/us-id) |              173 |                       774 |                     433 |                        601 |                                      348% |                                   412 |                                  1,264 |
|                   [Kansas](/us-ks) |              349 |                       714 |                     245 |                        365 |                                      105% |                                   450 |                                  1,164 |
|                 [Delaware](/us-de) |              581 |                       674 |                     692 |                         93 |                                       16% |                                   594 |                                    837 |
|     [District of Columbia](/us-dc) |              584 |                       647 |                     916 |                         63 |                                       11% |                                   596 |                                    758 |
|            [New Hampshire](/us-nh) |              411 |                       538 |                     395 |                        127 |                                       31% |                                   428 |                                    764 |
|                 [Nebraska](/us-ne) |              324 |                       510 |                     264 |                        186 |                                       57% |                                   357 |                                    794 |
|                  [Montana](/us-mt) |               54 |                       263 |                     246 |                        209 |                                      386% |                                   128 |                                    472 |
|             [South Dakota](/us-sd) |              129 |                       226 |                     255 |                         97 |                                       75% |                                   159 |                                    361 |
|            [West Virginia](/us-wv) |              111 |                       220 |                     123 |                        109 |                                       98% |                                   134 |                                    438 |
|             [North Dakota](/us-nd) |              102 |                       216 |                     283 |                        114 |                                      112% |                                   132 |                                    381 |
|                    [Maine](/us-me) |              121 |                       174 |                     129 |                         53 |                                       44% |                                   130 |                                    263 |
|                   [Alaska](/us-ak) |               22 |                       109 |                     149 |                         87 |                                      395% |                                    45 |                                    233 |
|                   [Hawaii](/us-hi) |               26 |                        79 |                      55 |                         53 |                                      202% |                                    32 |                                    206 |
|                  [Vermont](/us-vt) |               56 |                        75 |                     121 |                         19 |                                       34% |                                    61 |                                    101 |
|                  [Wyoming](/us-wy) |               26 |                        46 |                      79 |                         20 |                                       76% |                                    31 |                                     75 |
|           [Virgin Islands](/us-vi) |                8 |                        26 |                     250 |                         18 |                                      228% |                                    10 |                                     62 |
|                     [Guam](/us-gu) |                5 |                        10 |                      61 |                          5 |                                      103% |                                     6 |                                     21 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,751 |                   202,633 |                     342 |                     14,882 |                                        8% |                               190,555 |                                236,031 |
| [United Kingdom](/united-kingdom) |           46,046 |                    49,489 |                     733 |                      3,443 |                                        7% |                                46,219 |                                 57,653 |
|                   [Italy](/italy) |           35,129 |                    35,699 |                     591 |                        570 |                                        2% |                                35,150 |                                 37,546 |
|                 [France](/france) |           30,226 |                    30,856 |                     460 |                        630 |                                        2% |                                30,252 |                                 34,202 |
|                   [Spain](/spain) |           28,441 |                    28,921 |                     616 |                        480 |                                        2% |                                28,462 |                                 31,242 |
|               [Belgium](/belgium) |            9,836 |                     9,989 |                     872 |                        153 |                                        2% |                                 9,856 |                                 10,651 |
|               [Germany](/germany) |            9,135 |                     9,408 |                     113 |                        273 |                                        3% |                                 9,146 |                                 10,732 |
|       [Netherlands](/netherlands) |            6,166 |                     6,236 |                     361 |                         70 |                                        1% |                                 6,175 |                                  6,475 |
|                 [Sweden](/sweden) |            5,730 |                     6,117 |                     598 |                        387 |                                        7% |                                 5,817 |                                  6,792 |
|               [Romania](/romania) |            2,269 |                     4,625 |                     238 |                      2,356 |                                      104% |                                 3,034 |                                  8,410 |
|               [Ukraine](/ukraine) |            1,673 |                     3,271 |                      74 |                      1,598 |                                       96% |                                 2,144 |                                  5,783 |
|                 [Poland](/poland) |            1,694 |                     2,260 |                      60 |                        566 |                                       33% |                                 1,759 |                                  3,516 |
|             [Portugal](/portugal) |            1,725 |                     2,191 |                     213 |                        466 |                                       27% |                                 1,772 |                                  3,168 |
|       [Switzerland](/switzerland) |            1,979 |                     2,060 |                     240 |                         81 |                                        4% |                                 1,990 |                                  2,285 |
|               [Ireland](/ireland) |            1,764 |                     1,852 |                     378 |                         88 |                                        5% |                                 1,775 |                                  2,160 |
|                 [Serbia](/serbia) |              558 |                     1,455 |                     209 |                        897 |                                      161% |                                   853 |                                  2,758 |
|               [Moldova](/moldova) |              759 |                     1,436 |                     355 |                        677 |                                       89% |                                   974 |                                  2,312 |
|             [Bulgaria](/bulgaria) |              368 |                     1,104 |                     158 |                        736 |                                      200% |                                   549 |                                  2,325 |
|               [Belarus](/belarus) |              548 |                       961 |                     102 |                        413 |                                       75% |                                   702 |                                  1,410 |
|               [Austria](/austria) |              716 |                       795 |                      90 |                         79 |                                       11% |                                   732 |                                    956 |
|               [Denmark](/denmark) |              614 |                       696 |                     120 |                         82 |                                       13% |                                   630 |                                    854 |
|               [Hungary](/hungary) |              596 |                       695 |                      71 |                         99 |                                       17% |                                   609 |                                    917 |
|               [Czechia](/czechia) |              374 |                       587 |                      55 |                        213 |                                       57% |                                   412 |                                  1,001 |
|               [Croatia](/croatia) |              141 |                       384 |                      94 |                        243 |                                      172% |                                   213 |                                    790 |
|               [Finland](/finland) |              329 |                       382 |                      69 |                         53 |                                       16% |                                   340 |                                    513 |
|                 [Norway](/norway) |              255 |                       282 |                      52 |                         27 |                                       11% |                                   262 |                                    331 |
|                 [Greece](/greece) |              203 |                       250 |                      23 |                         47 |                                       23% |                                   213 |                                    327 |
|         [Luxembourg](/luxembourg) |              114 |                       167 |                     273 |                         53 |                                       47% |                                   129 |                                    253 |
|             [Slovenia](/slovenia) |              117 |                       141 |                      68 |                         24 |                                       20% |                                   121 |                                    189 |
|           [Lithuania](/lithuania) |               80 |                       106 |                      38 |                         26 |                                       32% |                                    84 |                                    153 |
|               [Estonia](/estonia) |               69 |                        88 |                      66 |                         19 |                                       27% |                                    76 |                                    123 |
|                 [Latvia](/latvia) |               31 |                        40 |                      21 |                          9 |                                       29% |                                    33 |                                     61 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       28% |                                    29 |                                     54 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       49% |                                    22 |                                     48 |
|                   [Malta](/malta) |                9 |                        14 |                      29 |                          5 |                                       58% |                                    11 |                                     17 |
|               [Iceland](/iceland) |               10 |                        14 |                      40 |                          4 |                                       37% |                                    10 |                                     24 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          309,026 |                   691,745 |                     133 |                    382,719 |                                      124% |                               437,968 |                              1,129,409 |
|                             [Brazil](/brazil) |           90,134 |                   185,607 |                     879 |                     95,473 |                                      106% |                               120,082 |                                307,358 |
|                               [India](/india) |           34,955 |                   141,455 |                     104 |                    106,500 |                                      305% |                                66,664 |                                237,382 |
|                             [Mexico](/mexico) |           45,361 |                    94,764 |                     743 |                     49,403 |                                      109% |                                71,912 |                                152,698 |
|                                 [Peru](/peru) |           18,816 |                    30,707 |                     945 |                     11,891 |                                       63% |                                22,206 |                                 47,017 |
|                         [Colombia](/colombia) |            9,454 |                    30,699 |                     610 |                     21,245 |                                      225% |                                19,190 |                                 49,164 |
|                                 [Iran](/iran) |           16,343 |                    30,113 |                     363 |                     13,770 |                                       84% |                                21,121 |                                 45,360 |
|                 [South Africa](/south-africa) |            7,497 |                    23,373 |                     399 |                     15,876 |                                      212% |                                12,892 |                                 32,387 |
|                             [Russia](/russia) |           13,650 |                    22,586 |                     155 |                      8,936 |                                       65% |                                15,312 |                                 39,027 |
|                       [Argentina](/argentina) |            3,288 |                    16,417 |                     367 |                     13,129 |                                      399% |                                 8,201 |                                 27,103 |
|                               [Chile](/chile) |            9,278 |                    15,175 |                     801 |                      5,897 |                                       64% |                                10,007 |                                 26,347 |
|                       [Indonesia](/indonesia) |            4,975 |                    14,201 |                      52 |                      9,226 |                                      185% |                                 7,697 |                                 27,670 |
|                             [Canada](/canada) |            8,962 |                     9,346 |                     250 |                        384 |                                        4% |                                 8,992 |                                 10,183 |
|                           [Ecuador](/ecuador) |            5,623 |                     7,936 |                     457 |                      2,313 |                                       41% |                                 5,818 |                                 11,982 |
|                         [Pakistan](/pakistan) |            5,892 |                     7,489 |                      35 |                      1,597 |                                       27% |                                 6,254 |                                  9,330 |
|                           [Bolivia](/bolivia) |            2,808 |                     6,984 |                     607 |                      4,176 |                                      149% |                                 4,168 |                                 11,726 |
|                             [Turkey](/turkey) |            5,659 |                     6,729 |                      81 |                      1,070 |                                       19% |                                 5,772 |                                  9,055 |
|                               [Egypt](/egypt) |            4,728 |                     6,095 |                      61 |                      1,367 |                                       29% |                                 4,970 |                                  7,440 |
|                     [Bangladesh](/bangladesh) |            3,035 |                     5,668 |                      35 |                      2,633 |                                       87% |                                 3,481 |                                 10,203 |
|                 [Saudi Arabia](/saudi-arabia) |            2,816 |                     5,038 |                     147 |                      2,222 |                                       79% |                                 3,566 |                                  8,658 |
|                   [Philippines](/philippines) |            1,962 |                     4,855 |                      45 |                      2,893 |                                      147% |                                 2,285 |                                 11,717 |
|                               [China](/china) |            4,658 |                     4,713 |                       3 |                         55 |                                        1% |                                 4,658 |                                  5,151 |
|                         [Honduras](/honduras) |            1,259 |                     4,460 |                     458 |                      3,201 |                                      254% |                                 2,352 |                                  8,380 |
|                             [Panama](/panama) |            1,374 |                     3,216 |                     757 |                      1,842 |                                      134% |                                 2,085 |                                  5,533 |
|     [Dominican Republic](/dominican-republic) |            1,123 |                     2,425 |                     226 |                      1,302 |                                      116% |                                 1,512 |                                  4,181 |
|                           [Algeria](/algeria) |            1,186 |                     2,287 |                      53 |                      1,101 |                                       93% |                                 1,385 |                                  4,453 |
|                       [Australia](/australia) |              189 |                     1,946 |                      77 |                      1,757 |                                      930% |                                   759 |                                  4,482 |
|                             [Israel](/israel) |              491 |                     1,515 |                     178 |                      1,024 |                                      209% |                                   782 |                                  2,981 |
|                           [Nigeria](/nigeria) |              873 |                     1,486 |                       7 |                        613 |                                       70% |                                   950 |                                  3,197 |
|                               [Japan](/japan) |            1,001 |                     1,471 |                      12 |                        470 |                                       47% |                                 1,009 |                                  3,349 |
|                           [Morocco](/morocco) |              334 |                     1,061 |                      29 |                        727 |                                      218% |                                   515 |                                  2,377 |
|                             [Kuwait](/kuwait) |              444 |                       795 |                     189 |                        351 |                                       79% |                                   488 |                                  1,635 |
| [United Arab Emirates](/united-arab-emirates) |              347 |                       476 |                      49 |                        129 |                                       37% |                                   355 |                                    833 |
|                   [South Korea](/south-korea) |              300 |                       394 |                       8 |                         94 |                                       31% |                                   302 |                                    732 |
|                         [Malaysia](/malaysia) |              124 |                       159 |                       5 |                         35 |                                       28% |                                   136 |                                    179 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       23% |                                    90 |                                    139 |
