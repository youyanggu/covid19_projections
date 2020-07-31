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
### Updated Daily - Last Updated: July 31 (1pm ET):
<p align="center">
  Current Total: <b>152,052</b> deaths | Projected Total: <b>228,900 deaths by Nov 1, 2020</b> (Range: 197-275k)<br>
  Currently Infected: <b>2.0%</b> | Total Infected: <b>11.7%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 31, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |        <1% |          7% |        98% |         99% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         7% |         36% |        70% |         86% |        95% |
|              225,000 |        <1% |         <1% |        <1% |          3% |        14% |         29% |        45% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         1% |          6% |        13% |
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
|             *[United States](/us)* |          152,052 |                   227,732 |                     686 |                     75,680 |                                       50% |                               197,198 |                                271,552 |
|                 [New York](/us-ny) |           32,683 |                    33,630 |                   1,729 |                        947 |                                        3% |                                32,731 |                                 37,761 |
|                    [Texas](/us-tx) |            6,442 |                    18,594 |                     641 |                     12,152 |                                      189% |                                12,287 |                                 26,116 |
|               [California](/us-ca) |            9,026 |                    18,540 |                     469 |                      9,514 |                                      105% |                                12,999 |                                 26,342 |
|               [New Jersey](/us-nj) |           15,809 |                    16,546 |                   1,863 |                        737 |                                        5% |                                15,908 |                                 17,984 |
|                  [Florida](/us-fl) |            6,586 |                    16,214 |                     755 |                      9,628 |                                      146% |                                11,782 |                                 22,988 |
|            [Massachusetts](/us-ma) |            8,580 |                     9,494 |                   1,366 |                        914 |                                       11% |                                 8,654 |                                 11,350 |
|                 [Illinois](/us-il) |            7,670 |                     9,329 |                     736 |                      1,659 |                                       22% |                                 7,934 |                                 11,928 |
|             [Pennsylvania](/us-pa) |            7,194 |                     9,125 |                     713 |                      1,931 |                                       27% |                                 7,342 |                                 13,230 |
|                  [Arizona](/us-az) |            3,626 |                     7,314 |                   1,005 |                      3,688 |                                      102% |                                 5,494 |                                  9,529 |
|                 [Michigan](/us-mi) |            6,443 |                     6,944 |                     695 |                        501 |                                        8% |                                 6,490 |                                  7,971 |
|                  [Georgia](/us-ga) |            3,671 |                     6,852 |                     645 |                      3,181 |                                       87% |                                 4,832 |                                  9,908 |
|                [Louisiana](/us-la) |            3,925 |                     5,751 |                   1,237 |                      1,826 |                                       47% |                                 4,507 |                                  7,795 |
|                     [Ohio](/us-oh) |            3,442 |                     5,488 |                     470 |                      2,046 |                                       59% |                                 3,935 |                                  8,299 |
|                 [Maryland](/us-md) |            3,488 |                     4,858 |                     804 |                      1,370 |                                       39% |                                 3,718 |                                  7,693 |
|              [Connecticut](/us-ct) |            4,431 |                     4,669 |                   1,309 |                        238 |                                        5% |                                 4,466 |                                  5,138 |
|           [South Carolina](/us-sc) |            1,667 |                     4,614 |                     896 |                      2,947 |                                      177% |                                 3,139 |                                  6,508 |
|                  [Indiana](/us-in) |            2,946 |                     4,443 |                     660 |                      1,497 |                                       51% |                                 3,219 |                                  7,076 |
|           [North Carolina](/us-nc) |            1,922 |                     4,058 |                     387 |                      2,136 |                                      111% |                                 2,659 |                                  6,318 |
|                  [Alabama](/us-al) |            1,565 |                     3,366 |                     687 |                      1,801 |                                      115% |                                 2,353 |                                  4,874 |
|                 [Virginia](/us-va) |            2,141 |                     3,281 |                     384 |                      1,140 |                                       53% |                                 2,316 |                                  5,340 |
|              [Mississippi](/us-ms) |            1,611 |                     3,122 |                   1,049 |                      1,511 |                                       94% |                                 2,177 |                                  4,552 |
|                 [Missouri](/us-mo) |            1,255 |                     2,691 |                     439 |                      1,436 |                                      114% |                                 1,572 |                                  4,774 |
|                 [Colorado](/us-co) |            1,822 |                     2,438 |                     423 |                        616 |                                       34% |                                 1,912 |                                  3,693 |
|                [Tennessee](/us-tn) |            1,033 |                     2,419 |                     354 |                      1,386 |                                      134% |                                 1,596 |                                  3,498 |
|                [Minnesota](/us-mn) |            1,634 |                     2,270 |                     402 |                        636 |                                       39% |                                 1,740 |                                  3,471 |
|               [Washington](/us-wa) |            1,564 |                     2,172 |                     285 |                        608 |                                       39% |                                 1,634 |                                  3,275 |
|                   [Nevada](/us-nv) |              801 |                     1,823 |                     592 |                      1,022 |                                      128% |                                 1,250 |                                  2,706 |
|                [Wisconsin](/us-wi) |              919 |                     1,767 |                     304 |                        848 |                                       92% |                                 1,105 |                                  3,304 |
|                 [Kentucky](/us-ky) |              731 |                     1,708 |                     382 |                        977 |                                      134% |                                   925 |                                  3,248 |
|                     [Iowa](/us-ia) |              865 |                     1,516 |                     480 |                        651 |                                       75% |                                 1,016 |                                  2,512 |
|                 [Oklahoma](/us-ok) |              536 |                     1,387 |                     350 |                        851 |                                      159% |                                   825 |                                  2,298 |
|             [Rhode Island](/us-ri) |            1,007 |                     1,175 |                   1,110 |                        168 |                                       17% |                                 1,035 |                                  1,413 |
|                 [Arkansas](/us-ar) |              442 |                     1,080 |                     358 |                        638 |                                      144% |                                   691 |                                  1,635 |
|               [New Mexico](/us-nm) |              635 |                     1,080 |                     515 |                        445 |                                       70% |                                   754 |                                  1,665 |
|                   [Oregon](/us-or) |              316 |                     1,005 |                     238 |                        689 |                                      218% |                                   535 |                                  1,804 |
|                     [Utah](/us-ut) |              300 |                       862 |                     269 |                        562 |                                      187% |                                   500 |                                  1,385 |
|              [Puerto Rico](/us-pr) |              214 |                       820 |                     257 |                        606 |                                      283% |                                   365 |                                  1,697 |
|                   [Kansas](/us-ks) |              357 |                       760 |                     261 |                        403 |                                      113% |                                   475 |                                  1,248 |
|                    [Idaho](/us-id) |              177 |                       731 |                     409 |                        554 |                                      313% |                                   398 |                                  1,218 |
|                 [Delaware](/us-de) |              581 |                       671 |                     689 |                         90 |                                       15% |                                   596 |                                    825 |
|     [District of Columbia](/us-dc) |              584 |                       647 |                     916 |                         63 |                                       11% |                                   597 |                                    752 |
|            [New Hampshire](/us-nh) |              415 |                       535 |                     394 |                        120 |                                       29% |                                   427 |                                    750 |
|                 [Nebraska](/us-ne) |              328 |                       490 |                     253 |                        162 |                                       49% |                                   362 |                                    728 |
|                  [Montana](/us-mt) |               55 |                       249 |                     233 |                        194 |                                      353% |                                   122 |                                    458 |
|             [South Dakota](/us-sd) |              129 |                       224 |                     253 |                         95 |                                       73% |                                   160 |                                    352 |
|             [North Dakota](/us-nd) |              103 |                       223 |                     292 |                        120 |                                      116% |                                   135 |                                    393 |
|            [West Virginia](/us-wv) |              112 |                       221 |                     123 |                        109 |                                       97% |                                   135 |                                    434 |
|                    [Maine](/us-me) |              122 |                       174 |                     130 |                         52 |                                       43% |                                   132 |                                    252 |
|                   [Alaska](/us-ak) |               23 |                       126 |                     172 |                        103 |                                      447% |                                    52 |                                    276 |
|                  [Vermont](/us-vt) |               57 |                        79 |                     127 |                         22 |                                       39% |                                    64 |                                    112 |
|                   [Hawaii](/us-hi) |               26 |                        76 |                      54 |                         50 |                                      193% |                                    32 |                                    194 |
|                  [Wyoming](/us-wy) |               26 |                        44 |                      76 |                         18 |                                       69% |                                    31 |                                     71 |
|           [Virgin Islands](/us-vi) |                8 |                        24 |                     226 |                         16 |                                      196% |                                    12 |                                     44 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       79% |                                     5 |                                     17 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      58 |                          1 |                                       60% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,948 |                   203,028 |                     342 |                     15,080 |                                        8% |                               191,187 |                                233,378 |
| [United Kingdom](/united-kingdom) |           46,084 |                    49,369 |                     731 |                      3,285 |                                        7% |                                46,426 |                                 56,476 |
|                   [Italy](/italy) |           35,132 |                    35,684 |                     591 |                        552 |                                        2% |                                35,159 |                                 37,544 |
|                 [France](/france) |           30,241 |                    30,820 |                     460 |                        579 |                                        2% |                                30,266 |                                 33,186 |
|                   [Spain](/spain) |           28,443 |                    28,847 |                     615 |                        404 |                                        1% |                                28,463 |                                 30,753 |
|               [Belgium](/belgium) |            9,840 |                     9,955 |                     869 |                        115 |                                        1% |                                 9,859 |                                 10,254 |
|               [Germany](/germany) |            9,144 |                     9,435 |                     114 |                        291 |                                        3% |                                 9,158 |                                 10,595 |
|       [Netherlands](/netherlands) |            6,166 |                     6,240 |                     361 |                         74 |                                        1% |                                 6,175 |                                  6,492 |
|                 [Sweden](/sweden) |            5,739 |                     6,135 |                     600 |                        396 |                                        7% |                                 5,825 |                                  6,715 |
|               [Romania](/romania) |            2,304 |                     5,047 |                     260 |                      2,743 |                                      119% |                                 3,181 |                                  8,803 |
|               [Ukraine](/ukraine) |            1,697 |                     3,371 |                      77 |                      1,674 |                                       99% |                                 2,171 |                                  5,692 |
|                 [Poland](/poland) |            1,709 |                     2,367 |                      62 |                        658 |                                       38% |                                 1,864 |                                  3,720 |
|             [Portugal](/portugal) |            1,727 |                     2,146 |                     209 |                        419 |                                       24% |                                 1,769 |                                  2,946 |
|       [Switzerland](/switzerland) |            1,980 |                     2,048 |                     238 |                         68 |                                        3% |                                 1,991 |                                  2,282 |
|               [Ireland](/ireland) |            1,763 |                     1,836 |                     374 |                         73 |                                        4% |                                 1,777 |                                  2,043 |
|               [Moldova](/moldova) |              771 |                     1,435 |                     355 |                        664 |                                       86% |                                 1,001 |                                  2,340 |
|                 [Serbia](/serbia) |              565 |                     1,360 |                     195 |                        795 |                                      141% |                                   819 |                                  2,776 |
|             [Bulgaria](/bulgaria) |              374 |                     1,234 |                     176 |                        860 |                                      230% |                                   612 |                                  2,550 |
|               [Belarus](/belarus) |              553 |                       825 |                      87 |                        272 |                                       49% |                                   713 |                                  1,036 |
|               [Austria](/austria) |              718 |                       791 |                      89 |                         73 |                                       10% |                                   734 |                                    946 |
|               [Hungary](/hungary) |              596 |                       698 |                      71 |                        102 |                                       17% |                                   609 |                                    949 |
|               [Denmark](/denmark) |              615 |                       685 |                     118 |                         70 |                                       11% |                                   630 |                                    836 |
|               [Czechia](/czechia) |              379 |                       682 |                      64 |                        303 |                                       80% |                                   422 |                                  1,379 |
|               [Croatia](/croatia) |              144 |                       467 |                     115 |                        323 |                                      224% |                                   226 |                                    972 |
|               [Finland](/finland) |              329 |                       385 |                      70 |                         56 |                                       17% |                                   343 |                                    501 |
|                 [Norway](/norway) |              255 |                       281 |                      52 |                         26 |                                       10% |                                   262 |                                    330 |
|                 [Greece](/greece) |              203 |                       246 |                      23 |                         43 |                                       21% |                                   212 |                                    316 |
|         [Luxembourg](/luxembourg) |              114 |                       178 |                     289 |                         64 |                                       56% |                                   132 |                                    285 |
|             [Slovenia](/slovenia) |              117 |                       149 |                      72 |                         32 |                                       28% |                                   124 |                                    219 |
|           [Lithuania](/lithuania) |               80 |                       100 |                      36 |                         20 |                                       26% |                                    85 |                                    135 |
|               [Estonia](/estonia) |               69 |                        85 |                      64 |                         16 |                                       23% |                                    76 |                                    114 |
|                 [Latvia](/latvia) |               31 |                        39 |                      20 |                          8 |                                       27% |                                    33 |                                     53 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       26% |                                    29 |                                     53 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    22 |                                     44 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       35% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        13 |                      27 |                          4 |                                       48% |                                     9 |                                     21 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          313,371 |                   649,101 |                     125 |                    335,730 |                                      107% |                               427,778 |                              1,020,988 |
|                             [Brazil](/brazil) |           91,263 |                   170,838 |                     809 |                     79,575 |                                       87% |                               114,415 |                                269,209 |
|                               [India](/india) |           35,718 |                   120,363 |                      88 |                     84,645 |                                      237% |                                63,749 |                                185,307 |
|                             [Mexico](/mexico) |           46,000 |                    85,503 |                     670 |                     39,503 |                                       86% |                                70,474 |                                127,745 |
|                         [Colombia](/colombia) |            9,808 |                    33,521 |                     666 |                     23,713 |                                      242% |                                18,075 |                                 51,427 |
|                                 [Iran](/iran) |           16,569 |                    31,266 |                     377 |                     14,697 |                                       89% |                                20,246 |                                 45,010 |
|                                 [Peru](/peru) |           18,816 |                    27,627 |                     850 |                      8,811 |                                       47% |                                20,581 |                                 42,075 |
|                 [South Africa](/south-africa) |            7,812 |                    24,313 |                     415 |                     16,501 |                                      211% |                                15,143 |                                 34,160 |
|                             [Russia](/russia) |           13,778 |                    22,326 |                     153 |                      8,548 |                                       62% |                                15,420 |                                 39,632 |
|                       [Argentina](/argentina) |            3,441 |                    17,306 |                     386 |                     13,865 |                                      403% |                                 8,686 |                                 27,899 |
|                       [Indonesia](/indonesia) |            5,058 |                    14,720 |                      54 |                      9,662 |                                      191% |                                 7,638 |                                 30,476 |
|                               [Chile](/chile) |            9,377 |                    13,434 |                     709 |                      4,057 |                                       43% |                                10,014 |                                 23,413 |
|                             [Canada](/canada) |            8,974 |                     9,373 |                     251 |                        399 |                                        4% |                                 9,013 |                                 10,335 |
|                           [Ecuador](/ecuador) |            5,657 |                     7,452 |                     429 |                      1,795 |                                       32% |                                 5,913 |                                 10,648 |
|                         [Pakistan](/pakistan) |            5,924 |                     7,310 |                      34 |                      1,386 |                                       23% |                                 6,363 |                                  8,890 |
|                           [Bolivia](/bolivia) |            2,894 |                     7,305 |                     635 |                      4,411 |                                      152% |                                 4,336 |                                 12,532 |
|                             [Turkey](/turkey) |            5,674 |                     6,650 |                      80 |                        976 |                                       17% |                                 5,772 |                                  8,594 |
|                               [Egypt](/egypt) |            4,774 |                     6,172 |                      61 |                      1,398 |                                       29% |                                 5,033 |                                  7,497 |
|                     [Bangladesh](/bangladesh) |            3,083 |                     5,724 |                      35 |                      2,641 |                                       86% |                                 3,952 |                                  9,616 |
|                 [Saudi Arabia](/saudi-arabia) |            2,842 |                     5,215 |                     152 |                      2,373 |                                       83% |                                 3,533 |                                  8,720 |
|                   [Philippines](/philippines) |            1,962 |                     4,963 |                      46 |                      3,001 |                                      153% |                                 2,218 |                                 13,551 |
|                         [Honduras](/honduras) |            1,312 |                     4,899 |                     503 |                      3,587 |                                      273% |                                 2,436 |                                  9,490 |
|                               [China](/china) |            4,659 |                     4,804 |                       3 |                        145 |                                        3% |                                 4,659 |                                  5,779 |
|                             [Panama](/panama) |            1,397 |                     3,219 |                     758 |                      1,822 |                                      130% |                                 2,074 |                                  5,608 |
|     [Dominican Republic](/dominican-republic) |            1,146 |                     2,637 |                     246 |                      1,491 |                                      130% |                                 1,544 |                                  4,914 |
|                           [Algeria](/algeria) |            1,200 |                     2,383 |                      55 |                      1,183 |                                       99% |                                 1,396 |                                  5,095 |
|                           [Morocco](/morocco) |              346 |                     2,017 |                      55 |                      1,671 |                                      483% |                                   562 |                                  6,344 |
|                       [Australia](/australia) |              196 |                     1,529 |                      61 |                      1,333 |                                      680% |                                   446 |                                  4,190 |
|                             [Israel](/israel) |              500 |                     1,443 |                     169 |                        943 |                                      189% |                                   726 |                                  3,083 |
|                               [Japan](/japan) |            1,007 |                     1,422 |                      11 |                        415 |                                       41% |                                 1,015 |                                  3,385 |
|                           [Nigeria](/nigeria) |              878 |                     1,417 |                       7 |                        539 |                                       61% |                                   961 |                                  2,859 |
|                             [Kuwait](/kuwait) |              445 |                       841 |                     200 |                        396 |                                       89% |                                   496 |                                  1,751 |
| [United Arab Emirates](/united-arab-emirates) |              349 |                       456 |                      47 |                        107 |                                       31% |                                   358 |                                    768 |
|                   [South Korea](/south-korea) |              301 |                       390 |                       8 |                         89 |                                       29% |                                   304 |                                    668 |
|                         [Malaysia](/malaysia) |              124 |                       153 |                       5 |                         29 |                                       23% |                                   135 |                                    173 |
|                                 [Cuba](/cuba) |               87 |                       110 |                      10 |                         23 |                                       26% |                                    92 |                                    145 |
