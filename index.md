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

* **June 25:** Our analysis shows that having *no* model [is better](/about/#baseline-comparison-c19pro-vs-ihme) than having IHME's model for US state-by-state projections.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: June 27 (2am ET):
<p align="center">
  Current Total: <b>125,636</b> deaths | Projected Total: <b>192,360 deaths by Oct 1, 2020</b> (Range: 160-234k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>5.0%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: Jun 26, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 5, 2020 |
|              140,000 |        Jul 20, 2020 |
|              150,000 |         Aug 3, 2020 |
|              175,000 |         Sep 4, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        <1% |         <1% |        39% |         84% |        99% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |          4% |        40% |         57% |        69% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |         1% |         15% |        32% |
|              225,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         7% |
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
|             *[United States](/us)* |          125,036 |                   192,360 |                     580 |                     67,324 |                                       54% |                               160,631 |                                233,068 |
|                 [New York](/us-ny) |           31,342 |                    33,414 |                   1,718 |                      2,072 |                                        7% |                                31,467 |                                 39,293 |
|               [New Jersey](/us-nj) |           14,914 |                    16,557 |                   1,864 |                      1,643 |                                       11% |                                15,170 |                                 17,997 |
|               [California](/us-ca) |            5,868 |                    15,353 |                     389 |                      9,485 |                                      162% |                                 8,639 |                                 23,683 |
|                 [Illinois](/us-il) |            6,847 |                    10,459 |                     825 |                      3,612 |                                       53% |                                 8,003 |                                 12,877 |
|            [Massachusetts](/us-ma) |            8,012 |                     9,657 |                   1,390 |                      1,645 |                                       21% |                                 8,379 |                                 12,120 |
|             [Pennsylvania](/us-pa) |            6,579 |                     9,274 |                     724 |                      2,695 |                                       41% |                                 7,024 |                                 13,912 |
|                  [Florida](/us-fl) |            3,366 |                     9,064 |                     422 |                      5,698 |                                      169% |                                 5,487 |                                 13,883 |
|                    [Texas](/us-tx) |            2,354 |                     7,422 |                     256 |                      5,068 |                                      215% |                                 4,301 |                                 11,461 |
|                 [Michigan](/us-mi) |            6,134 |                     7,173 |                     718 |                      1,039 |                                       17% |                                 6,259 |                                  8,949 |
|                  [Georgia](/us-ga) |            2,770 |                     6,254 |                     589 |                      3,484 |                                      126% |                                 3,463 |                                  9,714 |
|                     [Ohio](/us-oh) |            2,788 |                     5,323 |                     455 |                      2,535 |                                       91% |                                 3,246 |                                  8,589 |
|                  [Arizona](/us-az) |            1,536 |                     5,313 |                     730 |                      3,777 |                                      246% |                                 3,384 |                                  7,336 |
|              [Connecticut](/us-ct) |            4,307 |                     4,814 |                   1,350 |                        507 |                                       12% |                                 4,409 |                                  5,326 |
|                 [Maryland](/us-md) |            3,142 |                     4,699 |                     777 |                      1,557 |                                       50% |                                 3,471 |                                  6,201 |
|                [Louisiana](/us-la) |            3,190 |                     4,261 |                     917 |                      1,071 |                                       34% |                                 3,372 |                                  5,890 |
|                  [Indiana](/us-in) |            2,595 |                     4,251 |                     631 |                      1,656 |                                       64% |                                 2,824 |                                  7,266 |
|           [North Carolina](/us-nc) |            1,348 |                     3,479 |                     332 |                      2,131 |                                      158% |                                 1,811 |                                  5,869 |
|                [Minnesota](/us-mn) |            1,446 |                     2,910 |                     516 |                      1,464 |                                      101% |                                 1,798 |                                  4,377 |
|                 [Virginia](/us-va) |            1,700 |                     2,834 |                     332 |                      1,134 |                                       67% |                                 1,858 |                                  4,487 |
|                  [Alabama](/us-al) |              907 |                     2,631 |                     537 |                      1,724 |                                      190% |                                 1,376 |                                  4,057 |
|                 [Colorado](/us-co) |            1,673 |                     2,585 |                     449 |                        912 |                                       55% |                                 1,766 |                                  4,265 |
|               [Washington](/us-wa) |            1,304 |                     2,361 |                     310 |                      1,057 |                                       81% |                                 1,483 |                                  4,576 |
|              [Mississippi](/us-ms) |            1,022 |                     2,137 |                     718 |                      1,115 |                                      109% |                                 1,234 |                                  3,443 |
|           [South Carolina](/us-sc) |              694 |                     2,002 |                     389 |                      1,308 |                                      188% |                                 1,038 |                                  3,180 |
|                [Tennessee](/us-tn) |              577 |                     1,889 |                     276 |                      1,312 |                                      227% |                                 1,059 |                                  2,937 |
|                 [Missouri](/us-mo) |              997 |                     1,785 |                     291 |                        788 |                                       79% |                                 1,116 |                                  3,155 |
|                [Wisconsin](/us-wi) |              766 |                     1,640 |                     282 |                        874 |                                      114% |                                   932 |                                  2,631 |
|             [Rhode Island](/us-ri) |              927 |                     1,427 |                   1,347 |                        500 |                                       54% |                                 1,062 |                                  1,837 |
|                 [Kentucky](/us-ky) |              553 |                     1,149 |                     257 |                        596 |                                      108% |                                   661 |                                  1,884 |
|                     [Iowa](/us-ia) |              704 |                     1,066 |                     338 |                        362 |                                       51% |                                   766 |                                  1,977 |
|                 [Arkansas](/us-ar) |              249 |                       991 |                     328 |                        742 |                                      298% |                                   522 |                                  1,515 |
|               [New Mexico](/us-nm) |              489 |                       965 |                     460 |                        476 |                                       97% |                                   583 |                                  1,573 |
|                   [Nevada](/us-nv) |              498 |                       928 |                     301 |                        430 |                                       86% |                                   573 |                                  1,604 |
|            [New Hampshire](/us-nh) |              365 |                       769 |                     566 |                        404 |                                      111% |                                   438 |                                  1,243 |
|                 [Delaware](/us-de) |              507 |                       736 |                     756 |                        229 |                                       45% |                                   544 |                                  1,155 |
|     [District of Columbia](/us-dc) |              546 |                       726 |                   1,029 |                        180 |                                       33% |                                   582 |                                    964 |
|                 [Nebraska](/us-ne) |              266 |                       693 |                     358 |                        427 |                                      161% |                                   387 |                                  1,215 |
|                 [Oklahoma](/us-ok) |              377 |                       673 |                     170 |                        296 |                                       79% |                                   421 |                                  1,228 |
|                     [Utah](/us-ut) |              166 |                       533 |                     166 |                        367 |                                      221% |                                   269 |                                    853 |
|                   [Oregon](/us-or) |              202 |                       495 |                     117 |                        293 |                                      145% |                                   260 |                                    853 |
|                   [Kansas](/us-ks) |              265 |                       456 |                     157 |                        191 |                                       72% |                                   289 |                                    930 |
|              [Puerto Rico](/us-pr) |              151 |                       204 |                      64 |                         53 |                                       35% |                                   163 |                                    314 |
|             [South Dakota](/us-sd) |               88 |                       203 |                     229 |                        115 |                                      131% |                                   111 |                                    404 |
|                    [Idaho](/us-id) |               90 |                       157 |                      88 |                         67 |                                       74% |                                    96 |                                    240 |
|                    [Maine](/us-me) |              103 |                       145 |                     108 |                         42 |                                       41% |                                   114 |                                    226 |
|            [West Virginia](/us-wv) |               92 |                       133 |                      74 |                         41 |                                       45% |                                   102 |                                    226 |
|             [North Dakota](/us-nd) |               78 |                       123 |                     161 |                         45 |                                       58% |                                    91 |                                    200 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     122 |                         20 |                                       36% |                                    59 |                                    103 |
|                  [Montana](/us-mt) |               22 |                        50 |                      47 |                         28 |                                      127% |                                    23 |                                     93 |
|                   [Alaska](/us-ak) |               14 |                        37 |                      51 |                         23 |                                      164% |                                    15 |                                     87 |
|                  [Wyoming](/us-wy) |               20 |                        35 |                      60 |                         15 |                                       75% |                                    25 |                                     72 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    17 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     17 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     3 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          180,709 |                   201,075 |                     339 |                     20,366 |                                       11% |                               186,764 |                                227,258 |
| [United Kingdom](/united-kingdom) |           43,498 |                    48,389 |                     717 |                      4,891 |                                       11% |                                46,457 |                                 50,532 |
|                   [Italy](/italy) |           34,708 |                    36,722 |                     608 |                      2,014 |                                        6% |                                34,986 |                                 38,726 |
|                 [France](/france) |           29,781 |                    30,691 |                     458 |                        910 |                                        3% |                                29,813 |                                 34,537 |
|                   [Spain](/spain) |           28,338 |                    29,329 |                     625 |                        991 |                                        3% |                                28,393 |                                 31,713 |
|               [Germany](/germany) |            8,965 |                    10,602 |                     128 |                      1,637 |                                       18% |                                 9,083 |                                 13,924 |
|               [Belgium](/belgium) |            9,731 |                     9,961 |                     870 |                        230 |                                        2% |                                 9,752 |                                 10,507 |
|       [Netherlands](/netherlands) |            6,122 |                     6,602 |                     382 |                        480 |                                        8% |                                 6,173 |                                  7,523 |
|                 [Sweden](/sweden) |            5,280 |                     6,421 |                     628 |                      1,141 |                                       22% |                                 5,554 |                                  7,971 |
|               [Ukraine](/ukraine) |            1,097 |                     3,163 |                      72 |                      2,066 |                                      188% |                                 1,737 |                                  4,999 |
|                 [Poland](/poland) |            1,429 |                     3,157 |                      83 |                      1,728 |                                      121% |                                 1,878 |                                  4,716 |
|               [Romania](/romania) |            1,579 |                     2,682 |                     138 |                      1,103 |                                       70% |                                 1,806 |                                  3,983 |
|       [Switzerland](/switzerland) |            1,962 |                     2,056 |                     239 |                         94 |                                        5% |                                 1,974 |                                  2,388 |
|             [Portugal](/portugal) |            1,555 |                     1,888 |                     184 |                        333 |                                       21% |                                 1,627 |                                  2,477 |
|               [Ireland](/ireland) |            1,730 |                     1,827 |                     373 |                         97 |                                        6% |                                 1,740 |                                  2,233 |
|               [Moldova](/moldova) |              515 |                     1,565 |                     387 |                      1,050 |                                      204% |                                   996 |                                  2,254 |
|               [Belarus](/belarus) |              373 |                       811 |                      86 |                        438 |                                      117% |                                   487 |                                  1,761 |
|               [Austria](/austria) |              698 |                       773 |                      87 |                         75 |                                       11% |                                   711 |                                    950 |
|               [Hungary](/hungary) |              578 |                       770 |                      79 |                        192 |                                       33% |                                   602 |                                  1,131 |
|               [Denmark](/denmark) |              604 |                       675 |                     116 |                         71 |                                       12% |                                   622 |                                    831 |
|             [Bulgaria](/bulgaria) |              215 |                       626 |                      89 |                        411 |                                      191% |                                   342 |                                    994 |
|               [Czechia](/czechia) |              349 |                       454 |                      43 |                        105 |                                       30% |                                   359 |                                    578 |
|               [Finland](/finland) |              328 |                       368 |                      67 |                         40 |                                       12% |                                   333 |                                    478 |
|                 [Serbia](/serbia) |              265 |                       334 |                      48 |                         69 |                                       26% |                                   282 |                                    461 |
|                 [Norway](/norway) |              249 |                       272 |                      51 |                         23 |                                        9% |                                   255 |                                    315 |
|                 [Greece](/greece) |              191 |                       223 |                      21 |                         32 |                                       17% |                                   203 |                                    275 |
|               [Croatia](/croatia) |              107 |                       130 |                      32 |                         23 |                                       21% |                                   113 |                                    164 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   110 |                                    142 |
|         [Luxembourg](/luxembourg) |              110 |                       119 |                     194 |                          9 |                                        8% |                                   112 |                                    139 |
|           [Lithuania](/lithuania) |               78 |                       114 |                      41 |                         36 |                                       46% |                                    87 |                                    168 |
|               [Estonia](/estonia) |               69 |                        92 |                      69 |                         23 |                                       33% |                                    76 |                                    158 |
|                 [Latvia](/latvia) |               30 |                        52 |                      27 |                         22 |                                       73% |                                    33 |                                     86 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    28 |                                     67 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     44 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          180,008 |                   579,313 |                     112 |                    399,305 |                                      222% |                               346,959 |                                970,130 |
|                             [Brazil](/brazil) |           55,961 |                   135,923 |                     644 |                     79,962 |                                      143% |                               102,765 |                                214,975 |
|                               [India](/india) |           15,685 |                   105,559 |                      77 |                     89,874 |                                      573% |                                37,277 |                                240,992 |
|                             [Mexico](/mexico) |           25,779 |                   104,583 |                     820 |                     78,804 |                                      306% |                                67,006 |                                137,535 |
|                         [Pakistan](/pakistan) |            4,035 |                    23,395 |                     108 |                     19,360 |                                      480% |                                 9,699 |                                 48,793 |
|                                 [Peru](/peru) |            8,939 |                    22,656 |                     697 |                     13,717 |                                      153% |                                15,316 |                                 33,642 |
|                         [Colombia](/colombia) |            2,786 |                    22,417 |                     445 |                     19,631 |                                      705% |                                14,036 |                                 31,258 |
|                             [Russia](/russia) |            8,770 |                    19,707 |                     135 |                     10,937 |                                      125% |                                12,177 |                                 34,670 |
|                                 [Iran](/iran) |           10,239 |                    19,560 |                     236 |                      9,321 |                                       91% |                                14,604 |                                 24,903 |
|                 [South Africa](/south-africa) |            2,340 |                    17,368 |                     297 |                     15,028 |                                      642% |                                 7,914 |                                 25,906 |
|                               [Chile](/chile) |            5,068 |                    13,243 |                     699 |                      8,175 |                                      161% |                                 7,549 |                                 19,700 |
|                               [Egypt](/egypt) |            2,620 |                    12,882 |                     128 |                     10,262 |                                      392% |                                 7,273 |                                 20,791 |
|                             [Canada](/canada) |            8,571 |                    11,186 |                     299 |                      2,615 |                                       31% |                                 9,057 |                                 17,314 |
|                     [Bangladesh](/bangladesh) |            1,661 |                     8,882 |                      54 |                      7,221 |                                      435% |                                 4,379 |                                 15,436 |
|                       [Indonesia](/indonesia) |            2,683 |                     8,357 |                      31 |                      5,674 |                                      211% |                                 4,174 |                                 14,014 |
|                             [Turkey](/turkey) |            5,065 |                     7,721 |                      93 |                      2,656 |                                       52% |                                 5,471 |                                 13,695 |
|                       [Argentina](/argentina) |            1,184 |                     6,838 |                     153 |                      5,654 |                                      478% |                                 3,117 |                                 12,640 |
|                 [Saudi Arabia](/saudi-arabia) |            1,474 |                     6,326 |                     185 |                      4,852 |                                      329% |                                 3,679 |                                  9,038 |
|                           [Ecuador](/ecuador) |            4,406 |                     6,203 |                     357 |                      1,797 |                                       41% |                                 4,778 |                                 10,750 |
|                           [Bolivia](/bolivia) |              934 |                     5,661 |                     492 |                      4,727 |                                      506% |                                 2,897 |                                  9,418 |
|                               [China](/china) |            4,641 |                     4,649 |                       3 |                          8 |                                        0% |                                 4,641 |                                  4,694 |
|                   [Philippines](/philippines) |            1,224 |                     2,429 |                      22 |                      1,205 |                                       98% |                                 1,321 |                                  4,351 |
|                         [Honduras](/honduras) |              471 |                     2,231 |                     229 |                      1,760 |                                      374% |                                 1,083 |                                  3,746 |
|                           [Nigeria](/nigeria) |              554 |                     2,157 |                      11 |                      1,603 |                                      289% |                                   843 |                                  4,631 |
|                           [Algeria](/algeria) |              885 |                     2,154 |                      50 |                      1,269 |                                      143% |                                 1,254 |                                  4,376 |
|                             [Panama](/panama) |              575 |                     1,785 |                     420 |                      1,210 |                                      210% |                                   887 |                                  2,969 |
|     [Dominican Republic](/dominican-republic) |              712 |                     1,731 |                     161 |                      1,019 |                                      143% |                                   889 |                                  4,172 |
|                               [Japan](/japan) |              971 |                     1,257 |                      10 |                        286 |                                       29% |                                   976 |                                  1,778 |
|                             [Kuwait](/kuwait) |              341 |                       572 |                     136 |                        231 |                                       68% |                                   391 |                                    971 |
| [United Arab Emirates](/united-arab-emirates) |              310 |                       434 |                      44 |                        124 |                                       40% |                                   336 |                                    762 |
|                             [Israel](/israel) |              314 |                       398 |                      47 |                         84 |                                       27% |                                   330 |                                    621 |
|                   [South Korea](/south-korea) |              282 |                       335 |                       7 |                         53 |                                       19% |                                   284 |                                    510 |
|                           [Morocco](/morocco) |              218 |                       250 |                       7 |                         32 |                                       15% |                                   226 |                                    325 |
|                         [Malaysia](/malaysia) |              121 |                       249 |                       8 |                        128 |                                      106% |                                   137 |                                    474 |
|                       [Australia](/australia) |              104 |                       113 |                       4 |                          9 |                                        9% |                                   104 |                                    150 |
|                                 [Cuba](/cuba) |               85 |                       102 |                       9 |                         17 |                                       20% |                                    89 |                                    130 |
