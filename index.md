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
### Updated Daily - Last Updated: July 29 (10am ET):
<p align="center">
  Current Total: <b>149,253</b> deaths | Projected Total: <b>221,400 deaths by Nov 1, 2020</b> (Range: 190-267k)<br>
  Currently Infected: <b>1.8%</b> | Total Infected: <b>10.8%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 29, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 29, 2020 |
|              175,000 |        Aug 27, 2020 |
|              200,000 |         Oct 1, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |       >99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          2% |        77% |         99% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         2% |         21% |        50% |         68% |        82% |
|              225,000 |        <1% |         <1% |        <1% |         <1% |         8% |         18% |        33% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          2% |         9% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |
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
|             *[United States](/us)* |          149,253 |                   221,474 |                     667 |                     72,221 |                                       48% |                               190,437 |                                266,147 |
|                 [New York](/us-ny) |           32,653 |                    33,748 |                   1,735 |                      1,095 |                                        3% |                                32,707 |                                 38,435 |
|               [California](/us-ca) |            8,679 |                    17,686 |                     448 |                      9,007 |                                      104% |                                11,771 |                                 26,179 |
|               [New Jersey](/us-nj) |           15,825 |                    16,651 |                   1,875 |                        826 |                                        5% |                                15,922 |                                 18,090 |
|                    [Texas](/us-tx) |            5,913 |                    16,479 |                     568 |                     10,566 |                                      179% |                                10,863 |                                 23,718 |
|                  [Florida](/us-fl) |            6,117 |                    14,245 |                     663 |                      8,128 |                                      133% |                                 9,878 |                                 20,183 |
|            [Massachusetts](/us-ma) |            8,551 |                     9,472 |                   1,363 |                        921 |                                       11% |                                 8,629 |                                 11,319 |
|                 [Illinois](/us-il) |            7,638 |                     9,373 |                     740 |                      1,735 |                                       23% |                                 7,906 |                                 11,910 |
|             [Pennsylvania](/us-pa) |            7,154 |                     9,111 |                     712 |                      1,957 |                                       27% |                                 7,305 |                                 13,407 |
|                  [Arizona](/us-az) |            3,408 |                     6,986 |                     960 |                      3,578 |                                      105% |                                 5,160 |                                  9,193 |
|                 [Michigan](/us-mi) |            6,421 |                     6,920 |                     693 |                        499 |                                        8% |                                 6,468 |                                  8,112 |
|                  [Georgia](/us-ga) |            3,509 |                     6,704 |                     631 |                      3,195 |                                       91% |                                 4,604 |                                  9,864 |
|                [Louisiana](/us-la) |            3,812 |                     5,555 |                   1,195 |                      1,743 |                                       46% |                                 4,286 |                                  7,673 |
|                     [Ohio](/us-oh) |            3,382 |                     5,486 |                     469 |                      2,104 |                                       62% |                                 3,781 |                                  8,463 |
|                 [Maryland](/us-md) |            3,458 |                     4,960 |                     820 |                      1,502 |                                       43% |                                 3,700 |                                  7,890 |
|              [Connecticut](/us-ct) |            4,423 |                     4,659 |                   1,307 |                        236 |                                        5% |                                 4,457 |                                  5,143 |
|                  [Indiana](/us-in) |            2,924 |                     4,486 |                     666 |                      1,562 |                                       53% |                                 3,175 |                                  7,378 |
|           [South Carolina](/us-sc) |            1,565 |                     4,408 |                     856 |                      2,843 |                                      182% |                                 2,916 |                                  6,277 |
|           [North Carolina](/us-nc) |            1,860 |                     3,848 |                     367 |                      1,988 |                                      107% |                                 2,497 |                                  5,969 |
|                  [Alabama](/us-al) |            1,491 |                     3,320 |                     677 |                      1,829 |                                      123% |                                 2,317 |                                  4,743 |
|                 [Virginia](/us-va) |            2,095 |                     3,225 |                     378 |                      1,130 |                                       54% |                                 2,255 |                                  5,541 |
|              [Mississippi](/us-ms) |            1,540 |                     3,066 |                   1,030 |                      1,526 |                                       99% |                                 2,027 |                                  4,493 |
|                 [Missouri](/us-mo) |            1,232 |                     2,681 |                     437 |                      1,449 |                                      118% |                                 1,510 |                                  5,047 |
|                [Tennessee](/us-tn) |              999 |                     2,464 |                     361 |                      1,465 |                                      147% |                                 1,598 |                                  3,660 |
|                 [Colorado](/us-co) |            1,807 |                     2,453 |                     426 |                        646 |                                       36% |                                 1,898 |                                  3,730 |
|                [Minnesota](/us-mn) |            1,620 |                     2,274 |                     403 |                        654 |                                       40% |                                 1,731 |                                  3,486 |
|               [Washington](/us-wa) |            1,548 |                     2,155 |                     283 |                        607 |                                       39% |                                 1,620 |                                  3,223 |
|                [Wisconsin](/us-wi) |              906 |                     1,854 |                     318 |                        948 |                                      105% |                                 1,102 |                                  3,657 |
|                 [Kentucky](/us-ky) |              719 |                     1,737 |                     389 |                      1,018 |                                      142% |                                   910 |                                  3,452 |
|                   [Nevada](/us-nv) |              759 |                     1,685 |                     547 |                        926 |                                      122% |                                 1,138 |                                  2,440 |
|                     [Iowa](/us-ia) |              839 |                     1,438 |                     456 |                        599 |                                       71% |                                   982 |                                  2,393 |
|                 [Oklahoma](/us-ok) |              509 |                     1,224 |                     309 |                        715 |                                      141% |                                   720 |                                  2,106 |
|             [Rhode Island](/us-ri) |            1,005 |                     1,169 |                   1,104 |                        164 |                                       16% |                                 1,033 |                                  1,391 |
|                 [Arkansas](/us-ar) |              428 |                     1,093 |                     362 |                        665 |                                      155% |                                   672 |                                  1,699 |
|               [New Mexico](/us-nm) |              626 |                     1,091 |                     520 |                        465 |                                       74% |                                   747 |                                  1,684 |
|                   [Oregon](/us-or) |              303 |                       972 |                     230 |                        669 |                                      221% |                                   497 |                                  1,768 |
|              [Puerto Rico](/us-pr) |              209 |                       847 |                     265 |                        638 |                                      305% |                                   365 |                                  1,814 |
|                     [Utah](/us-ut) |              286 |                       837 |                     261 |                        551 |                                      193% |                                   469 |                                  1,395 |
|                    [Idaho](/us-id) |              160 |                       683 |                     382 |                        523 |                                      327% |                                   355 |                                  1,150 |
|                 [Delaware](/us-de) |              580 |                       674 |                     693 |                         94 |                                       16% |                                   594 |                                    839 |
|                   [Kansas](/us-ks) |              340 |                       669 |                     230 |                        329 |                                       97% |                                   426 |                                  1,099 |
|     [District of Columbia](/us-dc) |              583 |                       646 |                     916 |                         63 |                                       11% |                                   595 |                                    758 |
|            [New Hampshire](/us-nh) |              409 |                       537 |                     395 |                        128 |                                       31% |                                   423 |                                    766 |
|                 [Nebraska](/us-ne) |              321 |                       511 |                     264 |                        190 |                                       59% |                                   354 |                                    810 |
|                  [Montana](/us-mt) |               51 |                       250 |                     234 |                        199 |                                      389% |                                   114 |                                    461 |
|             [North Dakota](/us-nd) |              100 |                       214 |                     281 |                        114 |                                      114% |                                   128 |                                    388 |
|             [South Dakota](/us-sd) |              123 |                       206 |                     233 |                         83 |                                       67% |                                   137 |                                    339 |
|            [West Virginia](/us-wv) |              108 |                       201 |                     112 |                         93 |                                       87% |                                   121 |                                    404 |
|                    [Maine](/us-me) |              121 |                       175 |                     130 |                         54 |                                       44% |                                   131 |                                    265 |
|                   [Alaska](/us-ak) |               22 |                        96 |                     132 |                         74 |                                      339% |                                    43 |                                    202 |
|                   [Hawaii](/us-hi) |               26 |                        86 |                      61 |                         60 |                                      230% |                                    34 |                                    230 |
|                  [Vermont](/us-vt) |               56 |                        75 |                     121 |                         19 |                                       35% |                                    61 |                                    101 |
|                  [Wyoming](/us-wy) |               26 |                        50 |                      87 |                         24 |                                       94% |                                    31 |                                     83 |
|           [Virgin Islands](/us-vi) |                7 |                        22 |                     212 |                         15 |                                      218% |                                     9 |                                     58 |
|                     [Guam](/us-gu) |                5 |                        10 |                      61 |                          5 |                                      104% |                                     6 |                                     21 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      100% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,514 |                   202,367 |                     341 |                     14,853 |                                        8% |                               190,311 |                                236,271 |
| [United Kingdom](/united-kingdom) |           45,963 |                    49,417 |                     732 |                      3,454 |                                        8% |                                46,140 |                                 57,671 |
|                   [Italy](/italy) |           35,123 |                    35,705 |                     592 |                        582 |                                        2% |                                35,145 |                                 37,569 |
|                 [France](/france) |           30,226 |                    30,874 |                     461 |                        648 |                                        2% |                                30,252 |                                 34,315 |
|                   [Spain](/spain) |           28,436 |                    28,922 |                     616 |                        486 |                                        2% |                                28,457 |                                 31,271 |
|               [Belgium](/belgium) |            9,833 |                     9,987 |                     872 |                        154 |                                        2% |                                 9,853 |                                 10,651 |
|               [Germany](/germany) |            9,131 |                     9,407 |                     113 |                        276 |                                        3% |                                 9,143 |                                 10,742 |
|       [Netherlands](/netherlands) |            6,164 |                     6,234 |                     361 |                         70 |                                        1% |                                 6,173 |                                  6,473 |
|                 [Sweden](/sweden) |            5,702 |                     6,087 |                     595 |                        385 |                                        7% |                                 5,789 |                                  6,762 |
|               [Romania](/romania) |            2,239 |                     4,559 |                     235 |                      2,320 |                                      104% |                                 2,994 |                                  8,355 |
|               [Ukraine](/ukraine) |            1,650 |                     3,192 |                      73 |                      1,542 |                                       93% |                                 2,110 |                                  5,800 |
|                 [Poland](/poland) |            1,682 |                     2,217 |                      58 |                        535 |                                       32% |                                 1,747 |                                  3,426 |
|             [Portugal](/portugal) |            1,722 |                     2,204 |                     214 |                        482 |                                       28% |                                 1,771 |                                  3,209 |
|       [Switzerland](/switzerland) |            1,978 |                     2,060 |                     240 |                         82 |                                        4% |                                 1,989 |                                  2,285 |
|               [Ireland](/ireland) |            1,764 |                     1,853 |                     378 |                         89 |                                        5% |                                 1,775 |                                  2,172 |
|                 [Serbia](/serbia) |              551 |                     1,514 |                     217 |                        963 |                                      175% |                                   856 |                                  2,980 |
|               [Moldova](/moldova) |              753 |                     1,456 |                     360 |                        703 |                                       93% |                                   974 |                                  2,349 |
|             [Bulgaria](/bulgaria) |              355 |                       996 |                     142 |                        641 |                                      181% |                                   520 |                                  2,141 |
|               [Belarus](/belarus) |              543 |                       962 |                     102 |                        419 |                                       77% |                                   699 |                                  1,412 |
|               [Austria](/austria) |              713 |                       789 |                      89 |                         76 |                                       11% |                                   729 |                                    946 |
|               [Hungary](/hungary) |              596 |                       697 |                      71 |                        101 |                                       17% |                                   609 |                                    927 |
|               [Denmark](/denmark) |              613 |                       694 |                     119 |                         81 |                                       13% |                                   629 |                                    851 |
|               [Czechia](/czechia) |              374 |                       598 |                      56 |                        224 |                                       60% |                                   414 |                                  1,052 |
|               [Croatia](/croatia) |              140 |                       395 |                      97 |                        255 |                                      182% |                                   215 |                                    819 |
|               [Finland](/finland) |              329 |                       382 |                      69 |                         53 |                                       16% |                                   340 |                                    514 |
|                 [Norway](/norway) |              255 |                       283 |                      53 |                         28 |                                       11% |                                   262 |                                    332 |
|                 [Greece](/greece) |              203 |                       250 |                      23 |                         47 |                                       23% |                                   213 |                                    327 |
|         [Luxembourg](/luxembourg) |              113 |                       164 |                     268 |                         51 |                                       46% |                                   127 |                                    248 |
|             [Slovenia](/slovenia) |              117 |                       141 |                      68 |                         24 |                                       21% |                                   121 |                                    189 |
|           [Lithuania](/lithuania) |               80 |                       106 |                      38 |                         26 |                                       32% |                                    84 |                                    154 |
|               [Estonia](/estonia) |               69 |                        88 |                      67 |                         19 |                                       28% |                                    76 |                                    123 |
|                 [Latvia](/latvia) |               31 |                        40 |                      21 |                          9 |                                       30% |                                    33 |                                     61 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       28% |                                    29 |                                     55 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       50% |                                    22 |                                     48 |
|                   [Malta](/malta) |                9 |                        14 |                      29 |                          5 |                                       59% |                                    11 |                                     18 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       37% |                                    10 |                                     24 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          303,390 |                   682,427 |                     131 |                    379,037 |                                      125% |                               430,160 |                              1,132,935 |
|                             [Brazil](/brazil) |           88,539 |                   181,933 |                     862 |                     93,394 |                                      105% |                               118,690 |                                306,482 |
|                               [India](/india) |           33,425 |                   137,159 |                     100 |                    103,734 |                                      310% |                                64,041 |                                238,183 |
|                             [Mexico](/mexico) |           44,876 |                    96,289 |                     755 |                     51,413 |                                      115% |                                72,076 |                                154,517 |
|                                 [Iran](/iran) |           16,147 |                    30,365 |                     366 |                     14,218 |                                       88% |                                21,079 |                                 46,065 |
|                         [Colombia](/colombia) |            9,074 |                    30,119 |                     598 |                     21,045 |                                      232% |                                18,234 |                                 49,002 |
|                                 [Peru](/peru) |           18,418 |                    28,319 |                     871 |                      9,901 |                                       54% |                                20,350 |                                 44,534 |
|                 [South Africa](/south-africa) |            7,257 |                    23,035 |                     393 |                     15,778 |                                      217% |                                12,766 |                                 31,890 |
|                             [Russia](/russia) |           13,483 |                    22,456 |                     154 |                      8,973 |                                       67% |                                15,167 |                                 39,227 |
|                       [Argentina](/argentina) |            3,179 |                    16,147 |                     361 |                     12,968 |                                      408% |                                 7,926 |                                 27,006 |
|                               [Chile](/chile) |            9,240 |                    15,283 |                     806 |                      6,043 |                                       65% |                                10,016 |                                 26,541 |
|                       [Indonesia](/indonesia) |            4,901 |                    14,957 |                      55 |                     10,056 |                                      205% |                                 7,756 |                                 30,781 |
|                             [Canada](/canada) |            8,957 |                     9,347 |                     250 |                        390 |                                        4% |                                 8,987 |                                 10,195 |
|                           [Ecuador](/ecuador) |            5,584 |                     7,923 |                     456 |                      2,339 |                                       42% |                                 5,773 |                                 12,035 |
|                         [Pakistan](/pakistan) |            5,865 |                     7,518 |                      35 |                      1,653 |                                       28% |                                 6,253 |                                  9,382 |
|                           [Bolivia](/bolivia) |            2,720 |                     6,733 |                     585 |                      4,013 |                                      148% |                                 4,059 |                                 11,487 |
|                             [Turkey](/turkey) |            5,645 |                     6,727 |                      81 |                      1,082 |                                       19% |                                 5,756 |                                  9,031 |
|                               [Egypt](/egypt) |            4,691 |                     6,085 |                      61 |                      1,394 |                                       30% |                                 4,947 |                                  7,464 |
|                     [Bangladesh](/bangladesh) |            3,000 |                     5,716 |                      35 |                      2,716 |                                       91% |                                 3,447 |                                 10,367 |
|                 [Saudi Arabia](/saudi-arabia) |            2,789 |                     5,083 |                     148 |                      2,294 |                                       82% |                                 3,559 |                                  8,772 |
|                   [Philippines](/philippines) |            1,947 |                     4,984 |                      46 |                      3,037 |                                      156% |                                 2,275 |                                 12,086 |
|                               [China](/china) |            4,657 |                     4,712 |                       3 |                         55 |                                        1% |                                 4,657 |                                  5,153 |
|                         [Honduras](/honduras) |            1,214 |                     4,331 |                     444 |                      3,117 |                                      257% |                                 2,212 |                                  8,245 |
|                             [Panama](/panama) |            1,349 |                     3,288 |                     774 |                      1,939 |                                      144% |                                 2,099 |                                  5,623 |
|     [Dominican Republic](/dominican-republic) |            1,101 |                     2,336 |                     218 |                      1,235 |                                      112% |                                 1,436 |                                  4,102 |
|                           [Algeria](/algeria) |            1,174 |                     2,304 |                      54 |                      1,130 |                                       96% |                                 1,369 |                                  4,705 |
|                       [Australia](/australia) |              176 |                     1,716 |                      68 |                      1,540 |                                      875% |                                   606 |                                  4,161 |
|                             [Israel](/israel) |              486 |                     1,558 |                     183 |                      1,072 |                                      220% |                                   787 |                                  3,078 |
|                           [Nigeria](/nigeria) |              868 |                     1,526 |                       8 |                        658 |                                       76% |                                   951 |                                  3,366 |
|                               [Japan](/japan) |            1,001 |                     1,483 |                      12 |                        482 |                                       48% |                                 1,009 |                                  3,434 |
|                           [Morocco](/morocco) |              327 |                     1,057 |                      29 |                        730 |                                      223% |                                   507 |                                  2,454 |
|                             [Kuwait](/kuwait) |              442 |                       797 |                     189 |                        355 |                                       80% |                                   486 |                                  1,658 |
| [United Arab Emirates](/united-arab-emirates) |              347 |                       480 |                      49 |                        133 |                                       38% |                                   356 |                                    848 |
|                   [South Korea](/south-korea) |              300 |                       396 |                       8 |                         96 |                                       32% |                                   302 |                                    742 |
|                         [Malaysia](/malaysia) |              124 |                       159 |                       5 |                         35 |                                       28% |                                   136 |                                    180 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       23% |                                    90 |                                    139 |
