We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 60 countries.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 18:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

* **May 13:** If you add `-noreopen` to the end of any projections page URL, you can see our projections with the assumption that there are no reopenings. E.g. [covid19-projections.com/us](/us) --> [covid19-projections.com/us-noreopen](/us-noreopen). Some caveats [here](https://twitter.com/youyanggu/status/1260678502107344896).

* **May 12:** We added 23 additional countries. The countries our projections cover encompass 6.3 billion people and account for over 99% of all global COVID-19 deaths. View our global projections [here](#global-projections).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 19 (1am ET):
<p align="center">
  Current Total: <b>90,344</b> deaths | Projected Total: <b>195,077</b> deaths by Aug 4, 2020 (Range: 120-337k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>3.5%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 45% chance that the US surpasses 125,000 deaths by June 15, with June 16 being the most likely date.

Last updated: May 19, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 26, 2020 |
|              125,000 |        Jun 16, 2020 |
|              150,000 |         Jul 5, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |        97% |         99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         45% |        82% |         91% |        95% |
|              150,000 |        <1% |          2% |        37% |         61% |        76% |
|              175,000 |        <1% |         <1% |        11% |         34% |        54% |
|              200,000 |        <1% |         <1% |         2% |         17% |        36% |
|              250,000 |        <1% |         <1% |        <1% |          3% |        14% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |         6% |
|              350,000 |        <1% |         <1% |        <1% |         <1% |         1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 63 countries (including all 27 European Union countries).

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

### Global Projections

| Europe |  |  |
| --- | --- | --- |
| [Austria](/austria) | [Hungary](/hungary) | [Portugal](/portugal) |
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
| [Greece](/greece) | [Poland](/poland) |

<br />

| Rest of World |  |  |
| --- | --- | --- |
| [Algeria](/algeria) | [Egypt](/egypt) | [Pakistan](/pakistan) |
| [Argentina](/argentina) | [India](/india) | [Panama](/panama) |
| [Bangladesh](/bangladesh) | [Indonesia](/indonesia) | [Peru](/peru) |
| [Brazil](/brazil) | [Iran](/iran) | [Philippines](/philippines) |
| [Canada](/canada) | [Israel](/israel) | [Russia](/russia) |
| [Chile](/chile) | [Japan](/japan) | [Saudi Arabia](/saudi-arabia) |
| [China](/china) | [Malaysia](/malaysia) | [South Africa](/south-africa) |
| [Colombia](/colombia) | [Mexico](/mexico) | [South Korea](/south-korea) |
| [Dominican Republic](/dominican-republic) | [Morocco](/morocco) | [Turkey](/turkey) |
| [Ecuador](/ecuador) | [Nigeria](/nigeria) |

[Back to Top](#top)

### US Summary

States are ordered by descending projected deaths (by August 4).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|         *[United States](/us)* |           90,344 |                   195,077 |                     588 |                    104,733 |                                      116% |                               120,563 |                                336,328 |
|             [New York](/us-ny) |           28,339 |                    33,450 |                   1,719 |                      5,111 |                                       18% |                                30,134 |                                 41,393 |
|             [Illinois](/us-il) |            4,234 |                    17,817 |                   1,406 |                     13,583 |                                      321% |                                 9,263 |                                 28,941 |
|           [New Jersey](/us-nj) |           10,439 |                    16,495 |                   1,857 |                      6,056 |                                       58% |                                12,180 |                                 23,863 |
|         [Pennsylvania](/us-pa) |            4,515 |                    12,066 |                     943 |                      7,551 |                                      167% |                                 6,620 |                                 20,414 |
|        [Massachusetts](/us-ma) |            5,862 |                    10,548 |                   1,518 |                      4,686 |                                       80% |                                 7,215 |                                 17,563 |
|           [California](/us-ca) |            3,279 |                     9,732 |                     246 |                      6,453 |                                      197% |                                 4,392 |                                 22,852 |
|                [Texas](/us-tx) |            1,350 |                     6,927 |                     239 |                      5,577 |                                      413% |                                 2,858 |                                 14,967 |
|             [Michigan](/us-mi) |            4,915 |                     6,687 |                     670 |                      1,772 |                                       36% |                                 5,548 |                                  9,182 |
|                 [Ohio](/us-oh) |            1,657 |                     6,682 |                     572 |                      5,025 |                                      303% |                                 2,882 |                                 14,275 |
|              [Indiana](/us-in) |            1,765 |                     6,584 |                     978 |                      4,819 |                                      273% |                                 2,908 |                                 13,761 |
|             [Maryland](/us-md) |            2,023 |                     5,561 |                     920 |                      3,538 |                                      175% |                                 2,756 |                                 10,896 |
|              [Florida](/us-fl) |            1,997 |                     5,424 |                     253 |                      3,427 |                                      172% |                                 2,625 |                                 11,444 |
|          [Connecticut](/us-ct) |            3,450 |                     5,373 |                   1,507 |                      1,923 |                                       56% |                                 4,036 |                                  8,181 |
|              [Arizona](/us-az) |              687 |                     4,625 |                     635 |                      3,938 |                                      573% |                                 2,065 |                                  8,832 |
|              [Georgia](/us-ga) |            1,649 |                     4,096 |                     386 |                      2,447 |                                      148% |                                 2,208 |                                  7,784 |
|            [Louisiana](/us-la) |            2,563 |                     3,913 |                     842 |                      1,350 |                                       53% |                                 3,048 |                                  5,739 |
|             [Colorado](/us-co) |            1,224 |                     3,769 |                     654 |                      2,545 |                                      208% |                                 1,930 |                                  7,307 |
|             [Virginia](/us-va) |            1,015 |                     3,458 |                     405 |                      2,443 |                                      241% |                                 1,441 |                                  8,587 |
|            [Minnesota](/us-mn) |              740 |                     3,374 |                     598 |                      2,634 |                                      356% |                                 1,237 |                                  7,530 |
|          [Mississippi](/us-ms) |              527 |                     2,772 |                     931 |                      2,245 |                                      426% |                                 1,219 |                                  5,246 |
|                 [Iowa](/us-ia) |              355 |                     2,705 |                     857 |                      2,350 |                                      662% |                                 1,343 |                                  4,700 |
|              [Alabama](/us-al) |              489 |                     2,555 |                     521 |                      2,066 |                                      422% |                                 1,230 |                                  4,738 |
|             [Missouri](/us-mo) |              611 |                     2,495 |                     407 |                      1,884 |                                      308% |                                 1,152 |                                  4,837 |
|       [North Carolina](/us-nc) |              693 |                     2,185 |                     208 |                      1,492 |                                      215% |                                 1,077 |                                  4,652 |
|       [South Carolina](/us-sc) |              391 |                     1,741 |                     338 |                      1,350 |                                      345% |                                   704 |                                  3,852 |
|           [New Mexico](/us-nm) |              270 |                     1,491 |                     711 |                      1,221 |                                      452% |                                   658 |                                  2,923 |
|           [Washington](/us-wa) |            1,002 |                     1,419 |                     186 |                        417 |                                       42% |                                 1,128 |                                  2,150 |
|             [Delaware](/us-de) |              297 |                     1,343 |                   1,379 |                      1,046 |                                      352% |                                   688 |                                  2,395 |
|         [Rhode Island](/us-ri) |              506 |                     1,281 |                   1,209 |                        775 |                                      153% |                                   773 |                                  2,295 |
|        [New Hampshire](/us-nh) |              172 |                     1,123 |                     826 |                        951 |                                      553% |                                   544 |                                  2,042 |
| [District of Columbia](/us-dc) |              392 |                       957 |                   1,356 |                        565 |                                      144% |                                   563 |                                  1,579 |
|            [Wisconsin](/us-wi) |              459 |                       907 |                     156 |                        448 |                                       98% |                                   628 |                                  1,535 |
|               [Nevada](/us-nv) |              358 |                       823 |                     267 |                        465 |                                      130% |                                   514 |                                  1,421 |
|            [Tennessee](/us-tn) |              301 |                       675 |                      99 |                        374 |                                      124% |                                   446 |                                  1,231 |
|             [Kentucky](/us-ky) |              346 |                       671 |                     150 |                        325 |                                       94% |                                   441 |                                  1,147 |
|             [Nebraska](/us-ne) |              123 |                       602 |                     311 |                        479 |                                      389% |                                   285 |                                  1,257 |
|             [Oklahoma](/us-ok) |              288 |                       480 |                     121 |                        192 |                                       67% |                                   361 |                                    742 |
|               [Kansas](/us-ks) |              198 |                       369 |                     127 |                        171 |                                       86% |                                   231 |                                    782 |
|                 [Utah](/us-ut) |               80 |                       306 |                      95 |                        226 |                                      282% |                                   137 |                                    665 |
|         [South Dakota](/us-sd) |               44 |                       233 |                     263 |                        189 |                                      430% |                                    98 |                                    497 |
|               [Oregon](/us-or) |              138 |                       217 |                      51 |                         79 |                                       57% |                                   164 |                                    337 |
|         [North Dakota](/us-nd) |               44 |                       215 |                     282 |                        171 |                                      389% |                                    94 |                                    453 |
|             [Arkansas](/us-ar) |              100 |                       209 |                      69 |                        109 |                                      109% |                                   156 |                                    336 |
|          [Puerto Rico](/us-pr) |              124 |                       194 |                      61 |                         70 |                                       56% |                                   155 |                                    280 |
|        [West Virginia](/us-wv) |               68 |                       137 |                      76 |                         69 |                                      101% |                                    95 |                                    252 |
|                [Maine](/us-me) |               71 |                       114 |                      85 |                         43 |                                       61% |                                    92 |                                    152 |
|                [Idaho](/us-id) |               74 |                        99 |                      55 |                         25 |                                       34% |                                    85 |                                    115 |
|              [Vermont](/us-vt) |               54 |                        71 |                     114 |                         17 |                                       31% |                                    64 |                                     77 |
|               [Hawaii](/us-hi) |               17 |                        27 |                      19 |                         10 |                                       59% |                                    21 |                                     31 |
|              [Montana](/us-mt) |               16 |                        22 |                      21 |                          6 |                                       38% |                                    20 |                                     27 |
|              [Wyoming](/us-wy) |               10 |                        18 |                      31 |                          8 |                                       80% |                                    16 |                                     21 |
|               [Alaska](/us-ak) |               10 |                        14 |                      19 |                          4 |                                       40% |                                    13 |                                     16 |
|                 [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     8 |                                     14 |
|       [Virgin Islands](/us-vi) |                6 |                        10 |                      95 |                          4 |                                       67% |                                     9 |                                     12 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          160,284 |                   217,562 |                     372 |                     57,278 |                                       36% |                               178,232 |                                305,340 |
| [United Kingdom](/united-kingdom) |           34,876 |                    50,070 |                     741 |                     15,194 |                                       44% |                                38,809 |                                 72,712 |
|                   [Italy](/italy) |           32,007 |                    38,877 |                     644 |                      6,870 |                                       21% |                                34,576 |                                 47,955 |
|                 [France](/france) |           28,242 |                    34,801 |                     519 |                      6,559 |                                       23% |                                30,335 |                                 49,938 |
|                   [Spain](/spain) |           27,709 |                    31,841 |                     678 |                      4,132 |                                       15% |                                29,039 |                                 38,314 |
|               [Germany](/germany) |            8,003 |                    10,836 |                     131 |                      2,833 |                                       35% |                                 8,672 |                                 16,547 |
|               [Belgium](/belgium) |            9,080 |                    10,388 |                     907 |                      1,308 |                                       14% |                                 9,380 |                                 12,747 |
|               [Ukraine](/ukraine) |              535 |                     7,842 |                     178 |                      7,307 |                                     1366% |                                 2,530 |                                 16,810 |
|       [Netherlands](/netherlands) |            5,713 |                     7,543 |                     436 |                      1,830 |                                       32% |                                 6,218 |                                 10,245 |
|                 [Sweden](/sweden) |            3,698 |                     7,331 |                     717 |                      3,633 |                                       98% |                                 5,702 |                                 10,518 |
|               [Romania](/romania) |            1,120 |                     2,939 |                     151 |                      1,819 |                                      162% |                                 1,890 |                                  5,065 |
|                 [Poland](/poland) |              936 |                     2,475 |                      65 |                      1,539 |                                      164% |                                 1,298 |                                  5,076 |
|       [Switzerland](/switzerland) |            1,886 |                     2,211 |                     257 |                        325 |                                       17% |                                 1,981 |                                  2,800 |
|               [Ireland](/ireland) |            1,547 |                     1,950 |                     398 |                        403 |                                       26% |                                 1,652 |                                  2,848 |
|             [Portugal](/portugal) |            1,231 |                     1,844 |                     179 |                        613 |                                       50% |                                 1,483 |                                  2,652 |
|               [Moldova](/moldova) |              217 |                     1,367 |                     338 |                      1,150 |                                      530% |                                   532 |                                  3,365 |
|               [Hungary](/hungary) |              462 |                       802 |                      82 |                        340 |                                       74% |                                   539 |                                  1,547 |
|               [Austria](/austria) |              629 |                       770 |                      87 |                        141 |                                       22% |                                   684 |                                    943 |
|               [Denmark](/denmark) |              548 |                       738 |                     127 |                        190 |                                       35% |                                   630 |                                    971 |
|               [Finland](/finland) |              300 |                       546 |                      99 |                        246 |                                       82% |                                   361 |                                  1,001 |
|               [Czechia](/czechia) |              297 |                       396 |                      37 |                         99 |                                       33% |                                   355 |                                    447 |
|                 [Serbia](/serbia) |              231 |                       389 |                      44 |                        158 |                                       68% |                                   304 |                                    636 |
|             [Bulgaria](/bulgaria) |              110 |                       370 |                      53 |                        260 |                                      236% |                                   207 |                                    672 |
|                 [Norway](/norway) |              233 |                       280 |                      52 |                         47 |                                       20% |                                   250 |                                    326 |
|                 [Greece](/greece) |              165 |                       217 |                      20 |                         52 |                                       32% |                                   191 |                                    260 |
|               [Croatia](/croatia) |               95 |                       179 |                      44 |                         84 |                                       88% |                                   122 |                                    291 |
|         [Luxembourg](/luxembourg) |              107 |                       133 |                     217 |                         26 |                                       24% |                                   120 |                                    151 |
|             [Slovenia](/slovenia) |              104 |                       130 |                      62 |                         26 |                                       25% |                                   113 |                                    162 |
|               [Estonia](/estonia) |               64 |                        92 |                      69 |                         28 |                                       44% |                                    82 |                                    103 |
|           [Lithuania](/lithuania) |               59 |                        86 |                      31 |                         27 |                                       46% |                                    74 |                                    102 |
|             [Slovakia](/slovakia) |               28 |                        38 |                       7 |                         10 |                                       36% |                                    31 |                                     47 |
|                 [Latvia](/latvia) |               19 |                        35 |                      18 |                         16 |                                       84% |                                    30 |                                     39 |
|                 [Cyprus](/cyprus) |               17 |                        24 |                      27 |                          7 |                                       41% |                                    22 |                                     26 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    12 |                                     14 |
|                   [Malta](/malta) |                6 |                         9 |                      18 |                          3 |                                       50% |                                     8 |                                     10 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           64,506 |                   363,784 |                      71 |                    299,278 |                                      464% |                               116,246 |                                924,423 |
|                         [Brazil](/brazil) |           16,853 |                   136,958 |                     649 |                    120,105 |                                      713% |                                40,209 |                                347,593 |
|                         [Mexico](/mexico) |            5,332 |                    67,887 |                     532 |                     62,555 |                                     1173% |                                13,280 |                                161,029 |
|                           [India](/india) |            3,156 |                    42,361 |                      31 |                     39,205 |                                     1242% |                                 7,721 |                                159,131 |
|                         [Russia](/russia) |            2,722 |                    16,758 |                     115 |                     14,036 |                                      516% |                                 4,663 |                                 56,396 |
|                         [Canada](/canada) |            5,960 |                    14,588 |                     390 |                      8,628 |                                      145% |                                 8,607 |                                 27,180 |
|                             [Iran](/iran) |            7,057 |                    13,296 |                     160 |                      6,239 |                                       88% |                                 8,113 |                                 24,147 |
|                             [Peru](/peru) |            2,789 |                    10,408 |                     320 |                      7,619 |                                      273% |                                 4,025 |                                 17,954 |
|                       [Ecuador](/ecuador) |            2,799 |                     7,516 |                     433 |                      4,717 |                                      169% |                                 3,755 |                                 15,672 |
|             [South Africa](/south-africa) |              286 |                     6,806 |                     116 |                      6,520 |                                     2280% |                                 1,960 |                                 16,475 |
|                         [Turkey](/turkey) |            4,171 |                     5,603 |                      67 |                      1,432 |                                       34% |                                 4,694 |                                  8,169 |
|                           [Chile](/chile) |              478 |                     5,083 |                     268 |                      4,605 |                                      963% |                                 1,814 |                                 10,005 |
|                     [Colombia](/colombia) |              592 |                     5,050 |                     100 |                      4,458 |                                      753% |                                 1,594 |                                 11,784 |
|                     [Pakistan](/pakistan) |              903 |                     4,667 |                      22 |                      3,764 |                                      417% |                                 1,348 |                                 12,497 |
|                           [China](/china) |            4,638 |                     4,642 |                       3 |                          4 |                                        0% |                                 4,638 |                                  4,665 |
|                           [Egypt](/egypt) |              645 |                     3,559 |                      35 |                      2,914 |                                      452% |                                 1,097 |                                 10,964 |
|                 [Bangladesh](/bangladesh) |              349 |                     3,370 |                      21 |                      3,021 |                                      866% |                                   907 |                                  8,422 |
|             [Saudi Arabia](/saudi-arabia) |              320 |                     2,592 |                      76 |                      2,272 |                                      710% |                                   927 |                                  6,449 |
|                   [Indonesia](/indonesia) |            1,191 |                     2,572 |                      10 |                      1,381 |                                      116% |                                 1,521 |                                  4,971 |
|                   [Argentina](/argentina) |              382 |                     2,297 |                      51 |                      1,915 |                                      501% |                                   754 |                                  6,558 |
|               [Philippines](/philippines) |              831 |                     2,010 |                      19 |                      1,179 |                                      142% |                                 1,018 |                                  3,864 |
|                           [Japan](/japan) |              749 |                     1,804 |                      14 |                      1,055 |                                      141% |                                   890 |                                  3,283 |
|                         [Panama](/panama) |              279 |                       783 |                     184 |                        504 |                                      181% |                                   377 |                                  1,876 |
| [Dominican Republic](/dominican-republic) |              434 |                       771 |                      72 |                        337 |                                       78% |                                   527 |                                  1,374 |
|                       [Nigeria](/nigeria) |              191 |                       681 |                       3 |                        490 |                                      257% |                                   291 |                                  1,775 |
|                       [Algeria](/algeria) |              555 |                       665 |                      15 |                        110 |                                       20% |                                   585 |                                    888 |
|                         [Israel](/israel) |              276 |                       363 |                      43 |                         87 |                                       32% |                                   312 |                                    476 |
|               [South Korea](/south-korea) |              263 |                       324 |                       6 |                         61 |                                       23% |                                   284 |                                    411 |
|                       [Morocco](/morocco) |              192 |                       224 |                       6 |                         32 |                                       17% |                                   207 |                                    251 |
|                     [Malaysia](/malaysia) |              113 |                       146 |                       5 |                         33 |                                       29% |                                   128 |                                    164 |
