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

* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: June 29 (3am ET):
<p align="center">
  Current Total: <b>125,800</b> deaths | Projected Total: <b>189,095 deaths by Oct 1, 2020</b> (Range: 159-227k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>5.2%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: Jun 28, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 6, 2020 |
|              140,000 |        Jul 22, 2020 |
|              150,000 |         Aug 5, 2020 |
|              175,000 |         Sep 8, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        <1% |         <1% |        28% |         80% |        99% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        33% |         51% |        65% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         10% |        26% |
|              225,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         3% |
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
|             *[United States](/us)* |          125,800 |                   189,095 |                     570 |                     63,295 |                                       50% |                               159,821 |                                226,544 |
|                 [New York](/us-ny) |           31,397 |                    33,439 |                   1,719 |                      2,042 |                                        7% |                                31,508 |                                 39,248 |
|               [New Jersey](/us-nj) |           14,975 |                    16,572 |                   1,866 |                      1,597 |                                       11% |                                15,220 |                                 17,987 |
|               [California](/us-ca) |            5,932 |                    14,430 |                     365 |                      8,498 |                                      143% |                                 9,021 |                                 21,726 |
|                 [Illinois](/us-il) |            6,888 |                    10,368 |                     818 |                      3,480 |                                       51% |                                 7,960 |                                 12,790 |
|            [Massachusetts](/us-ma) |            8,059 |                     9,803 |                   1,411 |                      1,744 |                                       22% |                                 8,428 |                                 11,988 |
|             [Pennsylvania](/us-pa) |            6,606 |                     9,343 |                     730 |                      2,737 |                                       41% |                                 6,994 |                                 14,143 |
|                  [Florida](/us-fl) |            3,419 |                     8,359 |                     389 |                      4,940 |                                      144% |                                 5,256 |                                 12,742 |
|                 [Michigan](/us-mi) |            6,157 |                     7,254 |                     726 |                      1,097 |                                       18% |                                 6,268 |                                  9,309 |
|                    [Texas](/us-tx) |            2,402 |                     7,006 |                     242 |                      4,604 |                                      192% |                                 4,098 |                                 10,698 |
|                  [Georgia](/us-ga) |            2,778 |                     5,941 |                     560 |                      3,163 |                                      114% |                                 3,395 |                                  9,453 |
|                  [Arizona](/us-az) |            1,594 |                     5,276 |                     725 |                      3,682 |                                      231% |                                 3,387 |                                  7,267 |
|                     [Ohio](/us-oh) |            2,807 |                     5,038 |                     431 |                      2,231 |                                       79% |                                 3,227 |                                  7,580 |
|              [Connecticut](/us-ct) |            4,316 |                     4,876 |                   1,368 |                        560 |                                       13% |                                 4,418 |                                  5,642 |
|                 [Maryland](/us-md) |            3,168 |                     4,691 |                     776 |                      1,523 |                                       48% |                                 3,484 |                                  6,176 |
|                [Louisiana](/us-la) |            3,199 |                     4,303 |                     926 |                      1,104 |                                       35% |                                 3,387 |                                  5,884 |
|                  [Indiana](/us-in) |            2,619 |                     4,013 |                     596 |                      1,394 |                                       53% |                                 2,817 |                                  6,170 |
|           [North Carolina](/us-nc) |            1,352 |                     3,413 |                     325 |                      2,061 |                                      152% |                                 1,948 |                                  5,349 |
|                 [Virginia](/us-va) |            1,732 |                     2,821 |                     331 |                      1,089 |                                       63% |                                 1,883 |                                  4,219 |
|                  [Alabama](/us-al) |              919 |                     2,656 |                     542 |                      1,737 |                                      189% |                                 1,569 |                                  3,762 |
|                [Minnesota](/us-mn) |            1,460 |                     2,607 |                     462 |                      1,147 |                                       79% |                                 1,687 |                                  3,783 |
|                 [Colorado](/us-co) |            1,676 |                     2,444 |                     424 |                        768 |                                       46% |                                 1,751 |                                  3,857 |
|              [Mississippi](/us-ms) |            1,039 |                     2,438 |                     819 |                      1,399 |                                      135% |                                 1,425 |                                  3,513 |
|               [Washington](/us-wa) |            1,310 |                     2,328 |                     306 |                      1,018 |                                       78% |                                 1,482 |                                  4,511 |
|           [South Carolina](/us-sc) |              716 |                     1,979 |                     384 |                      1,263 |                                      176% |                                 1,038 |                                  3,018 |
|                 [Missouri](/us-mo) |            1,004 |                     1,759 |                     287 |                        755 |                                       75% |                                 1,117 |                                  3,096 |
|                [Tennessee](/us-tn) |              584 |                     1,716 |                     251 |                      1,132 |                                      194% |                                   911 |                                  2,499 |
|                [Wisconsin](/us-wi) |              777 |                     1,600 |                     275 |                        823 |                                      106% |                                   974 |                                  2,518 |
|             [Rhode Island](/us-ri) |              927 |                     1,399 |                   1,321 |                        472 |                                       51% |                                 1,049 |                                  1,807 |
|                 [Kentucky](/us-ky) |              558 |                     1,126 |                     252 |                        568 |                                      102% |                                   661 |                                  1,833 |
|                   [Nevada](/us-nv) |              500 |                     1,060 |                     344 |                        560 |                                      112% |                                   615 |                                  1,656 |
|                     [Iowa](/us-ia) |              706 |                     1,039 |                     329 |                        333 |                                       47% |                                   758 |                                  1,883 |
|                 [Arkansas](/us-ar) |              264 |                       954 |                     316 |                        690 |                                      261% |                                   532 |                                  1,428 |
|               [New Mexico](/us-nm) |              492 |                       948 |                     452 |                        456 |                                       93% |                                   581 |                                  1,539 |
|     [District of Columbia](/us-dc) |              550 |                       727 |                   1,030 |                        177 |                                       32% |                                   588 |                                    961 |
|                 [Delaware](/us-de) |              507 |                       726 |                     746 |                        219 |                                       43% |                                   542 |                                  1,133 |
|                 [Oklahoma](/us-ok) |              385 |                       692 |                     175 |                        307 |                                       80% |                                   431 |                                  1,236 |
|            [New Hampshire](/us-nh) |              367 |                       685 |                     504 |                        318 |                                       87% |                                   425 |                                  1,059 |
|                 [Nebraska](/us-ne) |              267 |                       629 |                     325 |                        362 |                                      136% |                                   363 |                                  1,079 |
|                     [Utah](/us-ut) |              167 |                       481 |                     150 |                        314 |                                      188% |                                   251 |                                    760 |
|                   [Oregon](/us-or) |              202 |                       472 |                     112 |                        270 |                                      134% |                                   249 |                                    786 |
|                   [Kansas](/us-ks) |              269 |                       462 |                     159 |                        193 |                                       72% |                                   292 |                                    932 |
|              [Puerto Rico](/us-pr) |              153 |                       218 |                      68 |                         65 |                                       42% |                                   165 |                                    340 |
|             [South Dakota](/us-sd) |               91 |                       205 |                     232 |                        114 |                                      125% |                                   113 |                                    369 |
|                    [Idaho](/us-id) |               91 |                       161 |                      90 |                         70 |                                       77% |                                    98 |                                    249 |
|                    [Maine](/us-me) |              104 |                       151 |                     112 |                         47 |                                       45% |                                   115 |                                    234 |
|            [West Virginia](/us-wv) |               93 |                       134 |                      75 |                         41 |                                       44% |                                   103 |                                    226 |
|             [North Dakota](/us-nd) |               79 |                       116 |                     152 |                         37 |                                       47% |                                    92 |                                    174 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     122 |                         20 |                                       36% |                                    59 |                                    103 |
|                  [Montana](/us-mt) |               22 |                        46 |                      43 |                         24 |                                      109% |                                    23 |                                     90 |
|                   [Alaska](/us-ak) |               14 |                        35 |                      48 |                         21 |                                      150% |                                    15 |                                     70 |
|                  [Wyoming](/us-wy) |               20 |                        34 |                      59 |                         14 |                                       70% |                                    25 |                                     58 |
|                   [Hawaii](/us-hi) |               18 |                        24 |                      17 |                          6 |                                       33% |                                    18 |                                     38 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     14 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     2 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          181,029 |                   202,265 |                     341 |                     21,236 |                                       12% |                               185,246 |                                233,790 |
| [United Kingdom](/united-kingdom) |           43,634 |                    48,877 |                     724 |                      5,243 |                                       12% |                                44,575 |                                 53,303 |
|                   [Italy](/italy) |           34,738 |                    36,860 |                     611 |                      2,122 |                                        6% |                                35,039 |                                 41,210 |
|                 [France](/france) |           29,781 |                    30,894 |                     461 |                      1,113 |                                        4% |                                29,820 |                                 35,549 |
|                   [Spain](/spain) |           28,343 |                    29,313 |                     625 |                        970 |                                        3% |                                28,398 |                                 31,661 |
|               [Germany](/germany) |            8,968 |                    10,535 |                     127 |                      1,567 |                                       17% |                                 9,075 |                                 13,809 |
|               [Belgium](/belgium) |            9,732 |                    10,022 |                     875 |                        290 |                                        3% |                                 9,757 |                                 10,880 |
|       [Netherlands](/netherlands) |            6,124 |                     6,502 |                     376 |                        378 |                                        6% |                                 6,165 |                                  7,212 |
|                 [Sweden](/sweden) |            5,280 |                     6,325 |                     618 |                      1,045 |                                       20% |                                 5,526 |                                  7,850 |
|               [Ukraine](/ukraine) |            1,142 |                     3,309 |                      75 |                      2,167 |                                      190% |                                 1,791 |                                  5,300 |
|               [Romania](/romania) |            1,612 |                     3,267 |                     168 |                      1,655 |                                      103% |                                 2,065 |                                  4,481 |
|                 [Poland](/poland) |            1,438 |                     3,017 |                      79 |                      1,579 |                                      110% |                                 1,853 |                                  4,474 |
|       [Switzerland](/switzerland) |            1,962 |                     2,054 |                     239 |                         92 |                                        5% |                                 1,974 |                                  2,379 |
|             [Portugal](/portugal) |            1,564 |                     1,896 |                     184 |                        332 |                                       21% |                                 1,633 |                                  2,489 |
|               [Ireland](/ireland) |            1,735 |                     1,831 |                     373 |                         96 |                                        6% |                                 1,745 |                                  2,236 |
|               [Moldova](/moldova) |              530 |                     1,502 |                     371 |                        972 |                                      183% |                                   987 |                                  2,201 |
|               [Belarus](/belarus) |              383 |                       860 |                      91 |                        477 |                                      125% |                                   528 |                                  1,734 |
|               [Austria](/austria) |              702 |                       779 |                      88 |                         77 |                                       11% |                                   715 |                                    959 |
|               [Hungary](/hungary) |              581 |                       772 |                      79 |                        191 |                                       33% |                                   605 |                                  1,130 |
|               [Denmark](/denmark) |              604 |                       673 |                     116 |                         69 |                                       11% |                                   621 |                                    826 |
|             [Bulgaria](/bulgaria) |              219 |                       599 |                      86 |                        380 |                                      174% |                                   336 |                                    922 |
|               [Czechia](/czechia) |              348 |                       447 |                      42 |                         99 |                                       28% |                                   358 |                                    571 |
|               [Finland](/finland) |              328 |                       367 |                      67 |                         39 |                                       12% |                                   333 |                                    478 |
|                 [Serbia](/serbia) |              270 |                       364 |                      52 |                         94 |                                       35% |                                   287 |                                    571 |
|                 [Norway](/norway) |              249 |                       271 |                      50 |                         22 |                                        9% |                                   255 |                                    311 |
|                 [Greece](/greece) |              191 |                       221 |                      21 |                         30 |                                       16% |                                   203 |                                    271 |
|               [Croatia](/croatia) |              107 |                       129 |                      32 |                         22 |                                       21% |                                   113 |                                    162 |
|             [Slovenia](/slovenia) |              111 |                       121 |                      58 |                         10 |                                        9% |                                   113 |                                    146 |
|         [Luxembourg](/luxembourg) |              110 |                       119 |                     194 |                          9 |                                        8% |                                   112 |                                    139 |
|           [Lithuania](/lithuania) |               78 |                       111 |                      40 |                         33 |                                       42% |                                    86 |                                    160 |
|               [Estonia](/estonia) |               69 |                        91 |                      69 |                         22 |                                       32% |                                    76 |                                    158 |
|                 [Latvia](/latvia) |               30 |                        50 |                      26 |                         20 |                                       67% |                                    33 |                                     84 |
|             [Slovakia](/slovakia) |               28 |                        34 |                       6 |                          6 |                                       21% |                                    28 |                                     56 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     45 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    10 |                                     18 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          186,125 |                   567,330 |                     109 |                    381,205 |                                      205% |                               354,205 |                                925,222 |
|                             [Brazil](/brazil) |           57,622 |                   133,726 |                     634 |                     76,104 |                                      132% |                               102,369 |                                208,797 |
|                               [India](/india) |           16,475 |                   100,789 |                      74 |                     84,314 |                                      512% |                                37,503 |                                223,060 |
|                             [Mexico](/mexico) |           26,648 |                    98,421 |                     771 |                     71,773 |                                      269% |                                61,721 |                                134,077 |
|                         [Colombia](/colombia) |            3,256 |                    29,820 |                     592 |                     26,564 |                                      816% |                                26,051 |                                 37,674 |
|                                 [Peru](/peru) |            9,317 |                    22,643 |                     696 |                     13,326 |                                      143% |                                15,532 |                                 33,199 |
|                                 [Iran](/iran) |           10,508 |                    19,750 |                     238 |                      9,242 |                                       88% |                                15,068 |                                 24,972 |
|                             [Russia](/russia) |            9,060 |                    19,092 |                     131 |                     10,032 |                                      111% |                                12,118 |                                 31,893 |
|                         [Pakistan](/pakistan) |            4,167 |                    17,409 |                      80 |                     13,242 |                                      318% |                                 8,980 |                                 32,095 |
|                 [South Africa](/south-africa) |            2,456 |                    16,700 |                     285 |                     14,244 |                                      580% |                                 7,553 |                                 25,165 |
|                               [Chile](/chile) |            5,509 |                    13,868 |                     732 |                      8,359 |                                      152% |                                 8,142 |                                 19,766 |
|                               [Egypt](/egypt) |            2,789 |                    13,031 |                     130 |                     10,242 |                                      367% |                                 7,455 |                                 20,845 |
|                             [Canada](/canada) |            8,582 |                    10,537 |                     282 |                      1,955 |                                       23% |                                 8,930 |                                 14,782 |
|                     [Bangladesh](/bangladesh) |            1,738 |                     8,633 |                      53 |                      6,895 |                                      397% |                                 4,307 |                                 14,917 |
|                       [Indonesia](/indonesia) |            2,754 |                     8,233 |                      30 |                      5,479 |                                      199% |                                 4,186 |                                 13,766 |
|                             [Turkey](/turkey) |            5,097 |                     7,811 |                      94 |                      2,714 |                                       53% |                                 5,433 |                                 13,073 |
|                       [Argentina](/argentina) |            1,232 |                     6,450 |                     144 |                      5,218 |                                      424% |                                 3,004 |                                 12,313 |
|                           [Ecuador](/ecuador) |            4,429 |                     6,115 |                     352 |                      1,686 |                                       38% |                                 4,760 |                                 10,542 |
|                           [Bolivia](/bolivia) |            1,014 |                     5,982 |                     520 |                      4,968 |                                      490% |                                 2,989 |                                  9,599 |
|                 [Saudi Arabia](/saudi-arabia) |            1,551 |                     5,042 |                     147 |                      3,491 |                                      225% |                                 2,977 |                                  7,142 |
|                               [China](/china) |            4,641 |                     4,649 |                       3 |                          8 |                                        0% |                                 4,641 |                                  4,692 |
|                         [Honduras](/honduras) |              479 |                     2,989 |                     307 |                      2,510 |                                      524% |                                 1,894 |                                  4,462 |
|     [Dominican Republic](/dominican-republic) |              726 |                     2,978 |                     277 |                      2,252 |                                      310% |                                 1,039 |                                  6,066 |
|                   [Philippines](/philippines) |            1,244 |                     2,451 |                      23 |                      1,207 |                                       97% |                                 1,341 |                                  4,345 |
|                             [Panama](/panama) |              604 |                     2,376 |                     560 |                      1,772 |                                      293% |                                 1,251 |                                  3,442 |
|                           [Algeria](/algeria) |              897 |                     2,137 |                      50 |                      1,240 |                                      138% |                                 1,255 |                                  4,338 |
|                           [Nigeria](/nigeria) |              565 |                     1,867 |                       9 |                      1,302 |                                      230% |                                   815 |                                  4,245 |
|                               [Japan](/japan) |              972 |                     1,250 |                      10 |                        278 |                                       29% |                                   977 |                                  1,759 |
|                             [Kuwait](/kuwait) |              348 |                       621 |                     148 |                        273 |                                       78% |                                   406 |                                  1,095 |
| [United Arab Emirates](/united-arab-emirates) |              313 |                       431 |                      44 |                        118 |                                       38% |                                   335 |                                    756 |
|                             [Israel](/israel) |              318 |                       422 |                      50 |                        104 |                                       33% |                                   331 |                                    666 |
|                   [South Korea](/south-korea) |              282 |                       349 |                       7 |                         67 |                                       24% |                                   284 |                                    531 |
|                         [Malaysia](/malaysia) |              121 |                       279 |                       9 |                        158 |                                      131% |                                   137 |                                    477 |
|                           [Morocco](/morocco) |              221 |                       259 |                       7 |                         38 |                                       17% |                                   227 |                                    377 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    155 |
|                                 [Cuba](/cuba) |               86 |                       104 |                       9 |                         18 |                                       21% |                                    90 |                                    139 |
