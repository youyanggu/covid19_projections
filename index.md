We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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

* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 180k new infections per day in the US, 4-5x higher than the number of reported cases.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: July 1 (5am ET):
<p align="center">
  Current Total: <b>127,414</b> deaths | Projected Total: <b>184,870 deaths by Oct 1, 2020</b> (Range: 153-236k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>5.4%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 1, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 6, 2020 |
|              140,000 |        Jul 24, 2020 |
|              150,000 |         Aug 9, 2020 |
|              175,000 |        Sep 15, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        <1% |         <1% |        14% |         58% |        89% |         98% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        20% |         36% |        47% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          9% |        18% |
|              225,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         6% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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

States are ordered by descending projected deaths (by October 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          127,414 |                   184,870 |                     557 |                     57,456 |                                       45% |                               153,759 |                                235,341 |
|                 [New York](/us-ny) |           32,032 |                    33,511 |                   1,723 |                      1,479 |                                        5% |                                32,101 |                                 38,743 |
|               [New Jersey](/us-nj) |           15,035 |                    16,392 |                   1,845 |                      1,357 |                                        9% |                                15,220 |                                 17,983 |
|               [California](/us-ca) |            6,082 |                    13,884 |                     351 |                      7,802 |                                      128% |                                 8,464 |                                 24,519 |
|                 [Illinois](/us-il) |            6,923 |                     9,799 |                     773 |                      2,876 |                                       42% |                                 7,529 |                                 13,930 |
|            [Massachusetts](/us-ma) |            8,053 |                     9,342 |                   1,344 |                      1,289 |                                       16% |                                 8,229 |                                 11,738 |
|             [Pennsylvania](/us-pa) |            6,649 |                     8,591 |                     671 |                      1,942 |                                       29% |                                 6,867 |                                 13,100 |
|                  [Florida](/us-fl) |            3,505 |                     8,409 |                     392 |                      4,904 |                                      140% |                                 4,855 |                                 16,323 |
|                 [Michigan](/us-mi) |            6,193 |                     7,421 |                     743 |                      1,228 |                                       20% |                                 6,274 |                                 10,534 |
|                    [Texas](/us-tx) |            2,455 |                     6,949 |                     240 |                      4,494 |                                      183% |                                 3,574 |                                 14,194 |
|                  [Georgia](/us-ga) |            2,805 |                     6,285 |                     592 |                      3,480 |                                      124% |                                 3,650 |                                 10,748 |
|                  [Arizona](/us-az) |            1,645 |                     5,005 |                     688 |                      3,360 |                                      204% |                                 2,800 |                                  8,207 |
|                     [Ohio](/us-oh) |            2,863 |                     4,786 |                     409 |                      1,923 |                                       67% |                                 3,168 |                                  8,430 |
|              [Connecticut](/us-ct) |            4,322 |                     4,732 |                   1,327 |                        410 |                                        9% |                                 4,395 |                                  5,579 |
|                [Louisiana](/us-la) |            3,221 |                     4,509 |                     970 |                      1,288 |                                       40% |                                 3,437 |                                  6,541 |
|                 [Maryland](/us-md) |            3,190 |                     4,464 |                     738 |                      1,274 |                                       40% |                                 3,421 |                                  6,701 |
|                  [Indiana](/us-in) |            2,640 |                     3,786 |                     562 |                      1,146 |                                       43% |                                 2,777 |                                  6,739 |
|           [North Carolina](/us-nc) |            1,380 |                     3,158 |                     301 |                      1,778 |                                      129% |                                 1,767 |                                  6,448 |
|                 [Virginia](/us-va) |            1,763 |                     2,836 |                     332 |                      1,073 |                                       61% |                                 1,886 |                                  5,236 |
|                  [Alabama](/us-al) |              950 |                     2,679 |                     546 |                      1,729 |                                      182% |                                 1,388 |                                  4,465 |
|                [Minnesota](/us-mn) |            1,476 |                     2,463 |                     437 |                        987 |                                       67% |                                 1,646 |                                  4,341 |
|                 [Colorado](/us-co) |            1,690 |                     2,335 |                     405 |                        645 |                                       38% |                                 1,742 |                                  4,186 |
|              [Mississippi](/us-ms) |            1,073 |                     2,253 |                     757 |                      1,180 |                                      110% |                                 1,334 |                                  3,714 |
|           [South Carolina](/us-sc) |              739 |                     2,248 |                     437 |                      1,509 |                                      204% |                                 1,088 |                                  4,214 |
|               [Washington](/us-wa) |            1,332 |                     2,081 |                     273 |                        749 |                                       56% |                                 1,465 |                                  3,480 |
|                [Tennessee](/us-tn) |              604 |                     1,875 |                     274 |                      1,271 |                                      210% |                                   836 |                                  3,613 |
|                 [Missouri](/us-mo) |            1,005 |                     1,513 |                     247 |                        508 |                                       51% |                                 1,073 |                                  2,784 |
|                [Wisconsin](/us-wi) |              784 |                     1,475 |                     253 |                        691 |                                       88% |                                   924 |                                  2,917 |
|             [Rhode Island](/us-ri) |              950 |                     1,344 |                   1,269 |                        394 |                                       41% |                                 1,041 |                                  1,888 |
|                   [Nevada](/us-nv) |              507 |                     1,189 |                     386 |                        682 |                                      135% |                                   647 |                                  2,051 |
|                 [Kentucky](/us-ky) |              565 |                     1,040 |                     233 |                        475 |                                       84% |                                   635 |                                  2,111 |
|                     [Iowa](/us-ia) |              716 |                       945 |                     300 |                        229 |                                       32% |                                   753 |                                  1,489 |
|                 [Arkansas](/us-ar) |              270 |                       930 |                     308 |                        660 |                                      244% |                                   401 |                                  1,784 |
|               [New Mexico](/us-nm) |              497 |                       861 |                     411 |                        364 |                                       73% |                                   560 |                                  1,607 |
|     [District of Columbia](/us-dc) |              551 |                       692 |                     981 |                        141 |                                       26% |                                   578 |                                    995 |
|                 [Delaware](/us-de) |              509 |                       669 |                     687 |                        160 |                                       31% |                                   532 |                                  1,090 |
|                 [Oklahoma](/us-ok) |              387 |                       645 |                     163 |                        258 |                                       67% |                                   418 |                                  1,544 |
|            [New Hampshire](/us-nh) |              371 |                       635 |                     467 |                        264 |                                       71% |                                   416 |                                  1,151 |
|                   [Oregon](/us-or) |              207 |                       520 |                     123 |                        313 |                                      151% |                                   250 |                                  1,116 |
|                 [Nebraska](/us-ne) |              274 |                       511 |                     264 |                        237 |                                       86% |                                   337 |                                    825 |
|                     [Utah](/us-ut) |              172 |                       510 |                     159 |                        338 |                                      197% |                                   221 |                                  1,344 |
|                   [Kansas](/us-ks) |              273 |                       413 |                     142 |                        140 |                                       51% |                                   288 |                                    876 |
|              [Puerto Rico](/us-pr) |              153 |                       209 |                      65 |                         56 |                                       37% |                                   161 |                                    373 |
|                    [Idaho](/us-id) |               92 |                       190 |                     106 |                         98 |                                      107% |                                   109 |                                    341 |
|             [South Dakota](/us-sd) |               91 |                       169 |                     191 |                         78 |                                       86% |                                   107 |                                    301 |
|                    [Maine](/us-me) |              105 |                       145 |                     108 |                         40 |                                       38% |                                   113 |                                    239 |
|            [West Virginia](/us-wv) |               93 |                       120 |                      67 |                         27 |                                       29% |                                    98 |                                    177 |
|             [North Dakota](/us-nd) |               79 |                       108 |                     142 |                         29 |                                       37% |                                    88 |                                    152 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     122 |                         20 |                                       36% |                                    58 |                                    111 |
|                  [Montana](/us-mt) |               22 |                        49 |                      46 |                         27 |                                      123% |                                    24 |                                    114 |
|                   [Alaska](/us-ak) |               14 |                        37 |                      51 |                         23 |                                      164% |                                    14 |                                    103 |
|                  [Wyoming](/us-wy) |               20 |                        34 |                      59 |                         14 |                                       70% |                                    24 |                                     64 |
|                   [Hawaii](/us-hi) |               18 |                        25 |                      18 |                          7 |                                       39% |                                    19 |                                     38 |
|           [Virgin Islands](/us-vi) |                6 |                        10 |                      95 |                          4 |                                       67% |                                     6 |                                     17 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          181,576 |                   202,446 |                     341 |                     20,870 |                                       11% |                               185,686 |                                233,179 |
| [United Kingdom](/united-kingdom) |           43,815 |                    48,849 |                     723 |                      5,034 |                                       11% |                                44,697 |                                 53,179 |
|                   [Italy](/italy) |           34,767 |                    36,784 |                     609 |                      2,017 |                                        6% |                                35,042 |                                 41,008 |
|                 [France](/france) |           29,846 |                    30,942 |                     462 |                      1,096 |                                        4% |                                29,882 |                                 35,523 |
|                   [Spain](/spain) |           28,355 |                    29,317 |                     625 |                        962 |                                        3% |                                28,409 |                                 31,629 |
|               [Germany](/germany) |            8,990 |                    10,506 |                     127 |                      1,516 |                                       17% |                                 9,089 |                                 13,722 |
|               [Belgium](/belgium) |            9,747 |                    10,028 |                     875 |                        281 |                                        3% |                                 9,771 |                                 10,866 |
|       [Netherlands](/netherlands) |            6,132 |                     6,506 |                     376 |                        374 |                                        6% |                                 6,172 |                                  7,200 |
|                 [Sweden](/sweden) |            5,333 |                     6,337 |                     619 |                      1,004 |                                       19% |                                 5,557 |                                  7,805 |
|               [Romania](/romania) |            1,651 |                     3,504 |                     180 |                      1,853 |                                      112% |                                 2,126 |                                  4,599 |
|               [Ukraine](/ukraine) |            1,173 |                     3,247 |                      74 |                      2,074 |                                      177% |                                 1,828 |                                  5,005 |
|                 [Poland](/poland) |            1,463 |                     2,996 |                      79 |                      1,533 |                                      105% |                                 1,863 |                                  4,390 |
|       [Switzerland](/switzerland) |            1,963 |                     2,053 |                     239 |                         90 |                                        5% |                                 1,975 |                                  2,374 |
|             [Portugal](/portugal) |            1,576 |                     1,917 |                     187 |                        341 |                                       22% |                                 1,642 |                                  2,533 |
|               [Ireland](/ireland) |            1,736 |                     1,829 |                     373 |                         93 |                                        5% |                                 1,745 |                                  2,223 |
|               [Moldova](/moldova) |              545 |                     1,434 |                     355 |                        889 |                                      163% |                                   983 |                                  2,121 |
|               [Belarus](/belarus) |              392 |                       847 |                      90 |                        455 |                                      116% |                                   535 |                                  1,720 |
|               [Austria](/austria) |              705 |                       784 |                      88 |                         79 |                                       11% |                                   718 |                                    967 |
|               [Hungary](/hungary) |              585 |                       779 |                      80 |                        194 |                                       33% |                                   608 |                                  1,133 |
|             [Bulgaria](/bulgaria) |              230 |                       687 |                      98 |                        457 |                                      199% |                                   372 |                                  1,062 |
|               [Denmark](/denmark) |              605 |                       673 |                     116 |                         68 |                                       11% |                                   622 |                                    826 |
|               [Czechia](/czechia) |              349 |                       447 |                      42 |                         98 |                                       28% |                                   358 |                                    571 |
|                 [Serbia](/serbia) |              277 |                       414 |                      59 |                        137 |                                       49% |                                   300 |                                    685 |
|               [Finland](/finland) |              328 |                       366 |                      66 |                         38 |                                       12% |                                   333 |                                    477 |
|                 [Norway](/norway) |              250 |                       273 |                      51 |                         23 |                                        9% |                                   256 |                                    313 |
|                 [Greece](/greece) |              192 |                       222 |                      21 |                         30 |                                       16% |                                   203 |                                    273 |
|               [Croatia](/croatia) |              107 |                       128 |                      31 |                         21 |                                       20% |                                   113 |                                    159 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   112 |                                    146 |
|         [Luxembourg](/luxembourg) |              110 |                       119 |                     194 |                          9 |                                        8% |                                   112 |                                    138 |
|           [Lithuania](/lithuania) |               78 |                       109 |                      39 |                         31 |                                       40% |                                    86 |                                    155 |
|               [Estonia](/estonia) |               69 |                        90 |                      68 |                         21 |                                       30% |                                    75 |                                    156 |
|                 [Latvia](/latvia) |               30 |                        48 |                      25 |                         18 |                                       60% |                                    33 |                                     82 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    28 |                                     58 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     47 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    10 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          192,808 |                   548,693 |                     106 |                    355,885 |                                      185% |                               344,178 |                                885,842 |
|                             [Brazil](/brazil) |           59,594 |                   131,695 |                     624 |                     72,101 |                                      121% |                               102,696 |                                199,236 |
|                               [India](/india) |           17,400 |                    99,501 |                      73 |                     82,101 |                                      472% |                                39,785 |                                210,823 |
|                             [Mexico](/mexico) |           27,769 |                    92,443 |                     725 |                     64,674 |                                      233% |                                59,862 |                                128,222 |
|                                 [Peru](/peru) |            9,677 |                    22,571 |                     694 |                     12,894 |                                      133% |                                15,683 |                                 32,786 |
|                                 [Iran](/iran) |           10,817 |                    20,119 |                     243 |                      9,302 |                                       86% |                                16,414 |                                 25,404 |
|                         [Colombia](/colombia) |            3,376 |                    19,585 |                     389 |                     16,209 |                                      480% |                                11,604 |                                 27,991 |
|                             [Russia](/russia) |            9,306 |                    18,673 |                     128 |                      9,367 |                                      101% |                                12,191 |                                 31,134 |
|                         [Pakistan](/pakistan) |            4,395 |                    17,032 |                      79 |                     12,637 |                                      288% |                                 9,108 |                                 31,150 |
|                 [South Africa](/south-africa) |            2,657 |                    17,026 |                     291 |                     14,369 |                                      541% |                                 8,573 |                                 24,893 |
|                               [Chile](/chile) |            5,688 |                    13,266 |                     700 |                      7,578 |                                      133% |                                 7,907 |                                 19,409 |
|                               [Egypt](/egypt) |            2,953 |                    13,111 |                     131 |                     10,158 |                                      344% |                                 7,563 |                                 20,835 |
|                             [Canada](/canada) |            8,650 |                    10,536 |                     282 |                      1,886 |                                       22% |                                 8,978 |                                 14,713 |
|                     [Bangladesh](/bangladesh) |            1,847 |                     8,795 |                      54 |                      6,948 |                                      376% |                                 4,455 |                                 14,935 |
|                       [Indonesia](/indonesia) |            2,876 |                     8,671 |                      32 |                      5,795 |                                      201% |                                 4,352 |                                 14,255 |
|                             [Turkey](/turkey) |            5,131 |                     7,792 |                      93 |                      2,661 |                                       52% |                                 5,448 |                                 12,920 |
|                       [Argentina](/argentina) |            1,307 |                     6,634 |                     148 |                      5,327 |                                      408% |                                 3,314 |                                 12,309 |
|                           [Bolivia](/bolivia) |            1,123 |                     6,575 |                     571 |                      5,452 |                                      485% |                                 3,149 |                                  9,898 |
|                           [Ecuador](/ecuador) |            4,527 |                     6,325 |                     364 |                      1,798 |                                       40% |                                 4,844 |                                 10,774 |
|                 [Saudi Arabia](/saudi-arabia) |            1,649 |                     5,132 |                     150 |                      3,483 |                                      211% |                                 3,072 |                                  7,160 |
|                               [China](/china) |            4,641 |                     4,648 |                       3 |                          7 |                                        0% |                                 4,641 |                                  4,686 |
|     [Dominican Republic](/dominican-republic) |              747 |                     2,973 |                     277 |                      2,226 |                                      298% |                                 1,063 |                                  5,840 |
|                         [Honduras](/honduras) |              497 |                     2,850 |                     292 |                      2,353 |                                      473% |                                 1,820 |                                  4,297 |
|                   [Philippines](/philippines) |            1,266 |                     2,479 |                      23 |                      1,213 |                                       96% |                                 1,359 |                                  4,345 |
|                             [Panama](/panama) |              631 |                     2,413 |                     568 |                      1,782 |                                      282% |                                 1,277 |                                  3,469 |
|                           [Algeria](/algeria) |              912 |                     2,120 |                      49 |                      1,208 |                                      132% |                                 1,266 |                                  4,298 |
|                           [Nigeria](/nigeria) |              590 |                     1,910 |                      10 |                      1,320 |                                      224% |                                   853 |                                  4,147 |
|                               [Japan](/japan) |              972 |                     1,234 |                      10 |                        262 |                                       27% |                                   976 |                                  1,715 |
|                             [Kuwait](/kuwait) |              354 |                       602 |                     143 |                        248 |                                       70% |                                   406 |                                  1,031 |
| [United Arab Emirates](/united-arab-emirates) |              315 |                       432 |                      44 |                        117 |                                       37% |                                   336 |                                    754 |
|                             [Israel](/israel) |              320 |                       429 |                      50 |                        109 |                                       34% |                                   334 |                                    686 |
|                   [South Korea](/south-korea) |              282 |                       355 |                       7 |                         73 |                                       26% |                                   284 |                                    559 |
|                         [Malaysia](/malaysia) |              121 |                       277 |                       9 |                        156 |                                      129% |                                   136 |                                    474 |
|                           [Morocco](/morocco) |              228 |                       270 |                       7 |                         42 |                                       18% |                                   235 |                                    401 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    154 |
|                                 [Cuba](/cuba) |               86 |                       103 |                       9 |                         17 |                                       20% |                                    90 |                                    139 |
