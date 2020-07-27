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
### Updated Daily - Last Updated: July 27 (5pm ET):
<p align="center">
  Current Total: <b>146,932</b> deaths | Projected Total: <b>221,600 deaths by Nov 1, 2020</b> (Range: 189-269k)<br>
  Currently Infected: <b>1.9%</b> | Total Infected: <b>10.6%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 27, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 30, 2020 |
|              175,000 |        Aug 27, 2020 |
|              200,000 |         Oct 2, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          3% |        73% |         98% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         3% |         22% |        50% |         67% |        80% |
|              225,000 |        <1% |         <1% |        <1% |          1% |         9% |         19% |        33% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          3% |         9% |
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
|             *[United States](/us)* |          146,932 |                   221,612 |                     668 |                     74,680 |                                       51% |                               189,108 |                                268,512 |
|                 [New York](/us-ny) |           32,630 |                    33,754 |                   1,735 |                      1,124 |                                        3% |                                32,679 |                                 38,547 |
|               [California](/us-ca) |            8,448 |                    17,687 |                     448 |                      9,239 |                                      109% |                                11,558 |                                 26,748 |
|               [New Jersey](/us-nj) |           15,787 |                    16,636 |                   1,873 |                        849 |                                        5% |                                15,890 |                                 18,099 |
|                    [Texas](/us-tx) |            5,076 |                    16,208 |                     559 |                     11,132 |                                      219% |                                10,261 |                                 23,351 |
|                  [Florida](/us-fl) |            5,854 |                    14,186 |                     661 |                      8,332 |                                      142% |                                 9,566 |                                 20,066 |
|            [Massachusetts](/us-ma) |            8,529 |                     9,461 |                   1,361 |                        932 |                                       11% |                                 8,611 |                                 11,329 |
|                 [Illinois](/us-il) |            7,590 |                     9,307 |                     734 |                      1,717 |                                       23% |                                 7,868 |                                 11,881 |
|             [Pennsylvania](/us-pa) |            7,127 |                     9,157 |                     715 |                      2,030 |                                       28% |                                 7,286 |                                 13,565 |
|                  [Arizona](/us-az) |            3,305 |                     7,164 |                     984 |                      3,859 |                                      117% |                                 5,196 |                                  9,482 |
|                  [Georgia](/us-ga) |            3,498 |                     7,110 |                     670 |                      3,612 |                                      103% |                                 4,566 |                                 11,711 |
|                 [Michigan](/us-mi) |            6,400 |                     6,891 |                     690 |                        491 |                                        8% |                                 6,447 |                                  8,082 |
|                [Louisiana](/us-la) |            3,763 |                     5,554 |                   1,195 |                      1,791 |                                       48% |                                 4,229 |                                  7,788 |
|                     [Ohio](/us-oh) |            3,307 |                     5,358 |                     458 |                      2,051 |                                       62% |                                 3,695 |                                  8,421 |
|                 [Maryland](/us-md) |            3,440 |                     4,974 |                     823 |                      1,534 |                                       45% |                                 3,689 |                                  8,009 |
|              [Connecticut](/us-ct) |            4,413 |                     4,651 |                   1,305 |                        238 |                                        5% |                                 4,448 |                                  5,140 |
|                  [Indiana](/us-in) |            2,903 |                     4,515 |                     671 |                      1,612 |                                       56% |                                 3,162 |                                  7,559 |
|           [South Carolina](/us-sc) |            1,491 |                     4,490 |                     872 |                      2,999 |                                      201% |                                 2,899 |                                  6,548 |
|           [North Carolina](/us-nc) |            1,817 |                     3,912 |                     373 |                      2,095 |                                      115% |                                 2,473 |                                  6,218 |
|                  [Alabama](/us-al) |            1,473 |                     3,604 |                     735 |                      2,131 |                                      145% |                                 2,427 |                                  5,275 |
|                 [Virginia](/us-va) |            2,078 |                     3,207 |                     376 |                      1,129 |                                       54% |                                 2,218 |                                  5,557 |
|              [Mississippi](/us-ms) |            1,493 |                     3,002 |                   1,009 |                      1,509 |                                      101% |                                 1,956 |                                  4,481 |
|                 [Colorado](/us-co) |            1,794 |                     2,580 |                     448 |                        786 |                                       44% |                                 1,948 |                                  4,095 |
|                 [Missouri](/us-mo) |            1,209 |                     2,516 |                     410 |                      1,307 |                                      108% |                                 1,434 |                                  4,861 |
|                [Tennessee](/us-tn) |              967 |                     2,495 |                     365 |                      1,528 |                                      158% |                                 1,588 |                                  3,729 |
|                [Minnesota](/us-mn) |            1,614 |                     2,282 |                     405 |                        668 |                                       41% |                                 1,728 |                                  3,507 |
|               [Washington](/us-wa) |            1,501 |                     2,069 |                     272 |                        568 |                                       38% |                                 1,576 |                                  3,093 |
|                   [Nevada](/us-nv) |              734 |                     1,974 |                     641 |                      1,240 |                                      169% |                                 1,243 |                                  3,154 |
|                [Wisconsin](/us-wi) |              892 |                     1,871 |                     321 |                        979 |                                      110% |                                 1,086 |                                  3,798 |
|                 [Kentucky](/us-ky) |              700 |                     1,666 |                     373 |                        966 |                                      138% |                                   885 |                                  3,422 |
|                     [Iowa](/us-ia) |              829 |                     1,465 |                     464 |                        636 |                                       77% |                                   974 |                                  2,507 |
|             [Rhode Island](/us-ri) |            1,002 |                     1,172 |                   1,106 |                        170 |                                       17% |                                 1,031 |                                  1,395 |
|               [New Mexico](/us-nm) |              614 |                     1,084 |                     517 |                        470 |                                       76% |                                   735 |                                  1,708 |
|                 [Oklahoma](/us-ok) |              496 |                     1,065 |                     269 |                        569 |                                      115% |                                   654 |                                  1,780 |
|                 [Arkansas](/us-ar) |              401 |                       991 |                     328 |                        590 |                                      147% |                                   608 |                                  1,577 |
|                   [Oregon](/us-or) |              289 |                       919 |                     218 |                        630 |                                      218% |                                   469 |                                  1,727 |
|                     [Utah](/us-ut) |              274 |                       845 |                     263 |                        571 |                                      208% |                                   461 |                                  1,451 |
|              [Puerto Rico](/us-pr) |              201 |                       807 |                     253 |                        606 |                                      301% |                                   339 |                                  1,788 |
|                 [Delaware](/us-de) |              579 |                       676 |                     694 |                         97 |                                       17% |                                   593 |                                    844 |
|                   [Kansas](/us-ks) |              331 |                       652 |                     224 |                        321 |                                       97% |                                   412 |                                  1,093 |
|     [District of Columbia](/us-dc) |              581 |                       646 |                     915 |                         65 |                                       11% |                                   593 |                                    759 |
|                    [Idaho](/us-id) |              146 |                       630 |                     353 |                        484 |                                      332% |                                   314 |                                  1,130 |
|            [New Hampshire](/us-nh) |              409 |                       541 |                     398 |                        132 |                                       32% |                                   424 |                                    775 |
|                 [Nebraska](/us-ne) |              316 |                       508 |                     262 |                        192 |                                       61% |                                   350 |                                    815 |
|             [North Dakota](/us-nd) |               99 |                       227 |                     297 |                        128 |                                      129% |                                   130 |                                    418 |
|                  [Montana](/us-mt) |               46 |                       224 |                     210 |                        178 |                                      388% |                                    99 |                                    436 |
|             [South Dakota](/us-sd) |              123 |                       214 |                     242 |                         91 |                                       74% |                                   138 |                                    355 |
|            [West Virginia](/us-wv) |              103 |                       175 |                      97 |                         72 |                                       70% |                                   114 |                                    342 |
|                    [Maine](/us-me) |              119 |                       171 |                     127 |                         52 |                                       44% |                                   129 |                                    259 |
|                   [Hawaii](/us-hi) |               26 |                        95 |                      67 |                         69 |                                      265% |                                    34 |                                    258 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     121 |                         20 |                                       35% |                                    61 |                                    101 |
|                   [Alaska](/us-ak) |               20 |                        73 |                      99 |                         53 |                                      263% |                                    33 |                                    150 |
|                  [Wyoming](/us-wy) |               25 |                        42 |                      73 |                         17 |                                       70% |                                    30 |                                     74 |
|           [Virgin Islands](/us-vi) |                7 |                        23 |                     217 |                         16 |                                      225% |                                     9 |                                     59 |
|                     [Guam](/us-gu) |                5 |                        10 |                      62 |                          5 |                                      104% |                                     6 |                                     21 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      101% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,144 |                   202,507 |                     341 |                     15,363 |                                        8% |                               190,015 |                                237,630 |
| [United Kingdom](/united-kingdom) |           45,837 |                    49,353 |                     731 |                      3,516 |                                        8% |                                46,024 |                                 57,784 |
|                   [Italy](/italy) |           35,107 |                    35,702 |                     591 |                        595 |                                        2% |                                35,130 |                                 37,593 |
|                 [France](/france) |           30,195 |                    30,851 |                     460 |                        656 |                                        2% |                                30,222 |                                 34,338 |
|                   [Spain](/spain) |           28,432 |                    28,930 |                     616 |                        498 |                                        2% |                                28,454 |                                 31,334 |
|               [Belgium](/belgium) |            9,821 |                     9,973 |                     871 |                        152 |                                        2% |                                 9,841 |                                 10,624 |
|               [Germany](/germany) |            9,124 |                     9,407 |                     113 |                        283 |                                        3% |                                 9,136 |                                 10,760 |
|       [Netherlands](/netherlands) |            6,159 |                     6,230 |                     360 |                         71 |                                        1% |                                 6,168 |                                  6,471 |
|                 [Sweden](/sweden) |            5,697 |                     6,115 |                     598 |                        418 |                                        7% |                                 5,794 |                                  6,825 |
|               [Romania](/romania) |            2,187 |                     4,551 |                     234 |                      2,364 |                                      108% |                                 2,962 |                                  8,512 |
|               [Ukraine](/ukraine) |            1,625 |                     3,335 |                      76 |                      1,710 |                                      105% |                                 2,116 |                                  6,338 |
|             [Portugal](/portugal) |            1,717 |                     2,228 |                     217 |                        511 |                                       30% |                                 1,768 |                                  3,273 |
|                 [Poland](/poland) |            1,671 |                     2,222 |                      59 |                        551 |                                       33% |                                 1,739 |                                  3,481 |
|       [Switzerland](/switzerland) |            1,977 |                     2,060 |                     240 |                         83 |                                        4% |                                 1,988 |                                  2,288 |
|               [Ireland](/ireland) |            1,764 |                     1,856 |                     378 |                         92 |                                        5% |                                 1,776 |                                  2,186 |
|                 [Serbia](/serbia) |              534 |                     1,600 |                     230 |                      1,066 |                                      200% |                                   868 |                                  3,193 |
|               [Moldova](/moldova) |              735 |                     1,436 |                     355 |                        701 |                                       95% |                                   923 |                                  2,373 |
|               [Belarus](/belarus) |              534 |                       980 |                     104 |                        446 |                                       84% |                                   696 |                                  1,445 |
|             [Bulgaria](/bulgaria) |              340 |                       970 |                     139 |                        630 |                                      185% |                                   499 |                                  2,122 |
|               [Austria](/austria) |              712 |                       789 |                      89 |                         77 |                                       11% |                                   728 |                                    947 |
|               [Hungary](/hungary) |              596 |                       700 |                      72 |                        104 |                                       17% |                                   609 |                                    937 |
|               [Denmark](/denmark) |              613 |                       696 |                     120 |                         83 |                                       13% |                                   630 |                                    857 |
|               [Czechia](/czechia) |              371 |                       591 |                      55 |                        220 |                                       59% |                                   409 |                                  1,051 |
|               [Croatia](/croatia) |              136 |                       387 |                      95 |                        251 |                                      185% |                                   209 |                                    806 |
|               [Finland](/finland) |              329 |                       383 |                      69 |                         54 |                                       16% |                                   341 |                                    516 |
|                 [Norway](/norway) |              255 |                       283 |                      53 |                         28 |                                       11% |                                   262 |                                    333 |
|                 [Greece](/greece) |              202 |                       249 |                      23 |                         47 |                                       24% |                                   212 |                                    327 |
|         [Luxembourg](/luxembourg) |              112 |                       161 |                     263 |                         49 |                                       44% |                                   126 |                                    243 |
|             [Slovenia](/slovenia) |              116 |                       140 |                      67 |                         24 |                                       21% |                                   120 |                                    187 |
|           [Lithuania](/lithuania) |               80 |                       106 |                      38 |                         26 |                                       33% |                                    84 |                                    154 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    76 |                                    123 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       31% |                                    33 |                                     61 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    29 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       52% |                                    22 |                                     49 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       63% |                                    11 |                                     18 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       38% |                                    10 |                                     24 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          296,150 |                   686,987 |                     132 |                    390,837 |                                      132% |                               424,613 |                              1,154,851 |
|                             [Brazil](/brazil) |           87,004 |                   185,834 |                     881 |                     98,830 |                                      114% |                               118,951 |                                311,826 |
|                               [India](/india) |           32,771 |                   140,388 |                     103 |                    107,617 |                                      328% |                                63,929 |                                248,111 |
|                             [Mexico](/mexico) |           43,680 |                    97,558 |                     765 |                     53,878 |                                      123% |                                72,009 |                                157,351 |
|                                 [Iran](/iran) |           15,700 |                    30,420 |                     367 |                     14,720 |                                       94% |                                20,784 |                                 46,801 |
|                         [Colombia](/colombia) |            8,269 |                    26,971 |                     536 |                     18,702 |                                      226% |                                16,116 |                                 45,346 |
|                                 [Peru](/peru) |           17,843 |                    26,893 |                     827 |                      9,050 |                                       51% |                                19,545 |                                 44,012 |
|                             [Russia](/russia) |           13,249 |                    22,823 |                     156 |                      9,574 |                                       72% |                                15,040 |                                 40,517 |
|                 [South Africa](/south-africa) |            6,769 |                    22,009 |                     376 |                     15,240 |                                      225% |                                11,671 |                                 30,887 |
|                       [Indonesia](/indonesia) |            4,781 |                    17,240 |                      64 |                     12,459 |                                      261% |                                 8,118 |                                 36,786 |
|                       [Argentina](/argentina) |            2,939 |                    15,325 |                     342 |                     12,386 |                                      421% |                                 7,227 |                                 26,237 |
|                               [Chile](/chile) |            9,112 |                    15,252 |                     805 |                      6,140 |                                       67% |                                 9,933 |                                 26,699 |
|                             [Canada](/canada) |            8,934 |                     9,323 |                     249 |                        389 |                                        4% |                                 8,965 |                                 10,169 |
|                           [Ecuador](/ecuador) |            5,515 |                     7,920 |                     456 |                      2,405 |                                       44% |                                 5,720 |                                 12,130 |
|                         [Pakistan](/pakistan) |            5,822 |                     7,591 |                      35 |                      1,769 |                                       30% |                                 6,263 |                                  9,502 |
|                             [Turkey](/turkey) |            5,613 |                     6,716 |                      80 |                      1,103 |                                       20% |                                 5,731 |                                  9,085 |
|                           [Bolivia](/bolivia) |            2,583 |                     6,639 |                     577 |                      4,056 |                                      157% |                                 3,937 |                                 11,512 |
|                               [Egypt](/egypt) |            4,606 |                     6,050 |                      60 |                      1,444 |                                       31% |                                 4,876 |                                  7,491 |
|                     [Bangladesh](/bangladesh) |            2,928 |                     5,782 |                      35 |                      2,854 |                                       97% |                                 3,396 |                                 10,591 |
|                   [Philippines](/philippines) |            1,932 |                     5,334 |                      49 |                      3,402 |                                      176% |                                 2,292 |                                 12,817 |
|                 [Saudi Arabia](/saudi-arabia) |            2,733 |                     5,137 |                     150 |                      2,404 |                                       88% |                                 3,531 |                                  8,916 |
|                               [China](/china) |            4,652 |                     4,708 |                       3 |                         56 |                                        1% |                                 4,652 |                                  5,155 |
|                         [Honduras](/honduras) |            1,116 |                     3,880 |                     398 |                      2,764 |                                      248% |                                 2,026 |                                  7,365 |
|                             [Panama](/panama) |            1,294 |                     3,388 |                     798 |                      2,094 |                                      162% |                                 2,110 |                                  5,840 |
|                           [Algeria](/algeria) |            1,155 |                     2,400 |                      56 |                      1,245 |                                      108% |                                 1,348 |                                  5,494 |
|     [Dominican Republic](/dominican-republic) |            1,063 |                     2,234 |                     208 |                      1,171 |                                      110% |                                 1,367 |                                  4,062 |
|                           [Nigeria](/nigeria) |              858 |                     1,629 |                       8 |                        771 |                                       90% |                                   949 |                                  3,850 |
|                             [Israel](/israel) |              470 |                     1,595 |                     187 |                      1,125 |                                      239% |                                   782 |                                  3,302 |
|                       [Australia](/australia) |              161 |                     1,535 |                      61 |                      1,374 |                                      854% |                                   503 |                                  3,685 |
|                               [Japan](/japan) |              998 |                     1,487 |                      12 |                        489 |                                       49% |                                 1,006 |                                  3,487 |
|                           [Morocco](/morocco) |              313 |                     1,016 |                      28 |                        703 |                                      225% |                                   480 |                                  2,320 |
|                             [Kuwait](/kuwait) |              433 |                       772 |                     183 |                        339 |                                       78% |                                   476 |                                  1,587 |
| [United Arab Emirates](/united-arab-emirates) |              344 |                       474 |                      49 |                        130 |                                       38% |                                   353 |                                    840 |
|                   [South Korea](/south-korea) |              299 |                       398 |                       8 |                         99 |                                       33% |                                   301 |                                    757 |
|                         [Malaysia](/malaysia) |              124 |                       160 |                       5 |                         36 |                                       29% |                                   136 |                                    181 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       23% |                                    90 |                                    140 |
