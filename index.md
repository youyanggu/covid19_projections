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
### Updated Daily - Last Updated: June 28 (4pm ET):
<p align="center">
  Current Total: <b>125,536</b> deaths | Projected Total: <b>190,324 deaths by Oct 1, 2020</b> (Range: 160-230k)<br>
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
|              130,000 |         Jul 5, 2020 |
|              140,000 |        Jul 21, 2020 |
|              150,000 |         Aug 4, 2020 |
|              175,000 |         Sep 6, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        <1% |         <1% |        35% |         83% |        99% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |          2% |        36% |         53% |        66% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         12% |        28% |
|              225,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         5% |
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
|             *[United States](/us)* |          125,536 |                   190,324 |                     574 |                     64,788 |                                       52% |                               160,021 |                                229,253 |
|                 [New York](/us-ny) |           31,368 |                    33,417 |                   1,718 |                      2,049 |                                        7% |                                31,486 |                                 39,261 |
|               [New Jersey](/us-nj) |           14,948 |                    16,571 |                   1,866 |                      1,623 |                                       11% |                                15,202 |                                 17,998 |
|               [California](/us-ca) |            5,899 |                    14,517 |                     367 |                      8,618 |                                      146% |                                 9,062 |                                 21,829 |
|                 [Illinois](/us-il) |            6,873 |                    10,419 |                     822 |                      3,546 |                                       52% |                                 7,998 |                                 12,840 |
|            [Massachusetts](/us-ma) |            8,040 |                     9,847 |                   1,417 |                      1,807 |                                       22% |                                 8,424 |                                 12,094 |
|             [Pennsylvania](/us-pa) |            6,603 |                     9,453 |                     738 |                      2,850 |                                       43% |                                 7,029 |                                 14,338 |
|                  [Florida](/us-fl) |            3,390 |                     8,406 |                     391 |                      5,016 |                                      148% |                                 5,265 |                                 12,802 |
|                    [Texas](/us-tx) |            2,388 |                     7,279 |                     251 |                      4,891 |                                      205% |                                 4,158 |                                 10,961 |
|                 [Michigan](/us-mi) |            6,153 |                     7,263 |                     727 |                      1,110 |                                       18% |                                 6,270 |                                  9,329 |
|                  [Georgia](/us-ga) |            2,776 |                     6,025 |                     567 |                      3,249 |                                      117% |                                 3,416 |                                  9,576 |
|                  [Arizona](/us-az) |            1,580 |                     5,390 |                     741 |                      3,810 |                                      241% |                                 3,558 |                                  7,382 |
|                     [Ohio](/us-oh) |            2,804 |                     5,291 |                     453 |                      2,487 |                                       89% |                                 3,252 |                                  8,559 |
|              [Connecticut](/us-ct) |            4,311 |                     4,881 |                   1,369 |                        570 |                                       13% |                                 4,417 |                                  5,653 |
|                 [Maryland](/us-md) |            3,157 |                     4,699 |                     777 |                      1,542 |                                       49% |                                 3,479 |                                  6,192 |
|                [Louisiana](/us-la) |            3,190 |                     4,298 |                     925 |                      1,108 |                                       35% |                                 3,385 |                                  5,893 |
|                  [Indiana](/us-in) |            2,616 |                     4,280 |                     636 |                      1,664 |                                       64% |                                 2,847 |                                  7,257 |
|           [North Carolina](/us-nc) |            1,353 |                     3,192 |                     304 |                      1,839 |                                      136% |                                 1,776 |                                  5,391 |
|                [Minnesota](/us-mn) |            1,452 |                     2,885 |                     512 |                      1,433 |                                       99% |                                 1,787 |                                  4,354 |
|                 [Virginia](/us-va) |            1,724 |                     2,823 |                     331 |                      1,099 |                                       64% |                                 1,876 |                                  4,234 |
|                 [Colorado](/us-co) |            1,674 |                     2,569 |                     446 |                        895 |                                       53% |                                 1,763 |                                  4,245 |
|                  [Alabama](/us-al) |              919 |                     2,524 |                     515 |                      1,605 |                                      175% |                                 1,378 |                                  3,770 |
|               [Washington](/us-wa) |            1,310 |                     2,349 |                     308 |                      1,039 |                                       79% |                                 1,487 |                                  4,548 |
|              [Mississippi](/us-ms) |            1,035 |                     2,148 |                     722 |                      1,113 |                                      108% |                                 1,245 |                                  3,440 |
|           [South Carolina](/us-sc) |              711 |                     1,972 |                     383 |                      1,261 |                                      177% |                                 1,080 |                                  2,930 |
|                 [Missouri](/us-mo) |            1,004 |                     1,789 |                     291 |                        785 |                                       78% |                                 1,122 |                                  3,147 |
|                [Tennessee](/us-tn) |              584 |                     1,729 |                     253 |                      1,145 |                                      196% |                                   830 |                                  2,545 |
|                [Wisconsin](/us-wi) |              777 |                     1,644 |                     282 |                        867 |                                      112% |                                   991 |                                  2,576 |
|             [Rhode Island](/us-ri) |              927 |                     1,410 |                   1,331 |                        483 |                                       52% |                                 1,055 |                                  1,820 |
|                 [Kentucky](/us-ky) |              554 |                     1,128 |                     252 |                        574 |                                      104% |                                   659 |                                  1,836 |
|                     [Iowa](/us-ia) |              704 |                     1,042 |                     330 |                        338 |                                       48% |                                   759 |                                  1,875 |
|                 [Arkansas](/us-ar) |              259 |                       963 |                     319 |                        704 |                                      272% |                                   536 |                                  1,447 |
|               [New Mexico](/us-nm) |              491 |                       955 |                     455 |                        464 |                                       95% |                                   582 |                                  1,551 |
|                   [Nevada](/us-nv) |              500 |                       919 |                     298 |                        419 |                                       84% |                                   573 |                                  1,595 |
|            [New Hampshire](/us-nh) |              367 |                       765 |                     563 |                        398 |                                      108% |                                   439 |                                  1,232 |
|                 [Delaware](/us-de) |              507 |                       730 |                     750 |                        223 |                                       44% |                                   543 |                                  1,144 |
|     [District of Columbia](/us-dc) |              548 |                       727 |                   1,030 |                        179 |                                       33% |                                   586 |                                    962 |
|                 [Oklahoma](/us-ok) |              384 |                       701 |                     177 |                        317 |                                       83% |                                   436 |                                  1,244 |
|                 [Nebraska](/us-ne) |              267 |                       652 |                     337 |                        385 |                                      144% |                                   372 |                                  1,112 |
|                     [Utah](/us-ut) |              167 |                       488 |                     152 |                        321 |                                      192% |                                   254 |                                    768 |
|                   [Oregon](/us-or) |              202 |                       486 |                     115 |                        284 |                                      141% |                                   252 |                                    801 |
|                   [Kansas](/us-ks) |              268 |                       466 |                     160 |                        198 |                                       74% |                                   293 |                                    942 |
|              [Puerto Rico](/us-pr) |              152 |                       216 |                      68 |                         64 |                                       42% |                                   164 |                                    339 |
|             [South Dakota](/us-sd) |               91 |                       210 |                     237 |                        119 |                                      131% |                                   115 |                                    373 |
|                    [Idaho](/us-id) |               91 |                       162 |                      91 |                         71 |                                       78% |                                    98 |                                    250 |
|                    [Maine](/us-me) |              104 |                       152 |                     113 |                         48 |                                       46% |                                   115 |                                    236 |
|            [West Virginia](/us-wv) |               93 |                       137 |                      76 |                         44 |                                       47% |                                   103 |                                    237 |
|             [North Dakota](/us-nd) |               78 |                       116 |                     152 |                         38 |                                       49% |                                    91 |                                    174 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     122 |                         20 |                                       36% |                                    59 |                                    103 |
|                  [Montana](/us-mt) |               22 |                        46 |                      43 |                         24 |                                      109% |                                    23 |                                     90 |
|                   [Alaska](/us-ak) |               14 |                        36 |                      49 |                         22 |                                      157% |                                    15 |                                     70 |
|                  [Wyoming](/us-wy) |               20 |                        35 |                      60 |                         15 |                                       75% |                                    25 |                                     59 |
|                   [Hawaii](/us-hi) |               18 |                        24 |                      17 |                          6 |                                       33% |                                    18 |                                     38 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     14 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     2 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          180,891 |                   201,212 |                     339 |                     20,321 |                                       11% |                               185,326 |                                231,223 |
| [United Kingdom](/united-kingdom) |           43,598 |                    47,809 |                     708 |                      4,211 |                                       10% |                                44,915 |                                 50,333 |
|                   [Italy](/italy) |           34,716 |                    37,273 |                     618 |                      2,557 |                                        7% |                                35,051 |                                 41,568 |
|                 [France](/france) |           29,781 |                    30,913 |                     461 |                      1,132 |                                        4% |                                29,822 |                                 35,642 |
|                   [Spain](/spain) |           28,341 |                    29,316 |                     625 |                        975 |                                        3% |                                28,395 |                                 31,677 |
|               [Germany](/germany) |            8,968 |                    10,571 |                     127 |                      1,603 |                                       18% |                                 9,081 |                                 13,858 |
|               [Belgium](/belgium) |            9,732 |                    10,027 |                     875 |                        295 |                                        3% |                                 9,758 |                                 10,894 |
|       [Netherlands](/netherlands) |            6,124 |                     6,598 |                     382 |                        474 |                                        8% |                                 6,174 |                                  7,513 |
|                 [Sweden](/sweden) |            5,280 |                     6,365 |                     622 |                      1,085 |                                       21% |                                 5,537 |                                  7,907 |
|               [Ukraine](/ukraine) |            1,121 |                     3,243 |                      74 |                      2,122 |                                      189% |                                 1,755 |                                  5,208 |
|                 [Poland](/poland) |            1,435 |                     3,091 |                      81 |                      1,656 |                                      115% |                                 1,870 |                                  4,591 |
|               [Romania](/romania) |            1,589 |                     2,691 |                     139 |                      1,102 |                                       69% |                                 1,810 |                                  3,977 |
|       [Switzerland](/switzerland) |            1,962 |                     2,055 |                     239 |                         93 |                                        5% |                                 1,974 |                                  2,387 |
|             [Portugal](/portugal) |            1,561 |                     1,897 |                     185 |                        336 |                                       22% |                                 1,632 |                                  2,494 |
|               [Ireland](/ireland) |            1,734 |                     1,832 |                     374 |                         98 |                                        6% |                                 1,744 |                                  2,241 |
|               [Moldova](/moldova) |              521 |                     1,498 |                     370 |                        977 |                                      188% |                                   984 |                                  2,204 |
|               [Belarus](/belarus) |              377 |                       853 |                      90 |                        476 |                                      126% |                                   522 |                                  1,735 |
|               [Austria](/austria) |              700 |                       776 |                      88 |                         76 |                                       11% |                                   713 |                                    958 |
|               [Hungary](/hungary) |              578 |                       760 |                      78 |                        182 |                                       31% |                                   599 |                                  1,117 |
|               [Denmark](/denmark) |              604 |                       674 |                     116 |                         70 |                                       12% |                                   622 |                                    827 |
|             [Bulgaria](/bulgaria) |              216 |                       599 |                      86 |                        383 |                                      177% |                                   335 |                                    923 |
|               [Czechia](/czechia) |              349 |                       451 |                      42 |                        102 |                                       29% |                                   359 |                                    573 |
|               [Finland](/finland) |              328 |                       367 |                      67 |                         39 |                                       12% |                                   333 |                                    477 |
|                 [Serbia](/serbia) |              267 |                       351 |                      50 |                         84 |                                       31% |                                   283 |                                    548 |
|                 [Norway](/norway) |              249 |                       272 |                      51 |                         23 |                                        9% |                                   255 |                                    313 |
|                 [Greece](/greece) |              191 |                       222 |                      21 |                         31 |                                       16% |                                   203 |                                    272 |
|               [Croatia](/croatia) |              107 |                       129 |                      32 |                         22 |                                       21% |                                   113 |                                    163 |
|         [Luxembourg](/luxembourg) |              110 |                       119 |                     194 |                          9 |                                        8% |                                   112 |                                    139 |
|             [Slovenia](/slovenia) |              109 |                       118 |                      57 |                          9 |                                        8% |                                   110 |                                    141 |
|           [Lithuania](/lithuania) |               78 |                       113 |                      40 |                         35 |                                       45% |                                    87 |                                    167 |
|               [Estonia](/estonia) |               69 |                        92 |                      69 |                         23 |                                       33% |                                    76 |                                    158 |
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
|                               *Rest of World* |          183,592 |                   571,344 |                     110 |                    387,752 |                                      211% |                               345,206 |                                950,955 |
|                             [Brazil](/brazil) |           57,070 |                   135,645 |                     643 |                     78,575 |                                      138% |                               103,220 |                                213,386 |
|                               [India](/india) |           16,095 |                   103,185 |                      76 |                     87,090 |                                      541% |                                37,787 |                                236,638 |
|                             [Mexico](/mexico) |           26,381 |                   101,515 |                     796 |                     75,134 |                                      285% |                                65,232 |                                135,589 |
|                                 [Peru](/peru) |            9,135 |                    22,682 |                     698 |                     13,547 |                                      148% |                                15,473 |                                 33,378 |
|                         [Colombia](/colombia) |            2,946 |                    22,373 |                     444 |                     19,427 |                                      659% |                                13,064 |                                 29,851 |
|                         [Pakistan](/pakistan) |            4,118 |                    22,115 |                     102 |                     17,997 |                                      437% |                                 9,378 |                                 45,306 |
|                                 [Iran](/iran) |           10,364 |                    19,623 |                     237 |                      9,259 |                                       89% |                                14,811 |                                 24,876 |
|                             [Russia](/russia) |            8,958 |                    19,487 |                     134 |                     10,529 |                                      118% |                                12,114 |                                 32,380 |
|                 [South Africa](/south-africa) |            2,413 |                    17,204 |                     294 |                     14,791 |                                      613% |                                 7,951 |                                 25,498 |
|                               [Chile](/chile) |            5,347 |                    14,345 |                     757 |                      8,998 |                                      168% |                                 8,471 |                                 20,015 |
|                               [Egypt](/egypt) |            2,708 |                    13,009 |                     130 |                     10,301 |                                      380% |                                 7,417 |                                 20,859 |
|                             [Canada](/canada) |            8,576 |                    11,125 |                     297 |                      2,549 |                                       30% |                                 9,044 |                                 17,214 |
|                     [Bangladesh](/bangladesh) |            1,695 |                     8,654 |                      53 |                      6,959 |                                      411% |                                 4,277 |                                 14,971 |
|                       [Indonesia](/indonesia) |            2,720 |                     8,285 |                      31 |                      5,565 |                                      205% |                                 4,181 |                                 13,857 |
|                             [Turkey](/turkey) |            5,082 |                     7,811 |                      94 |                      2,729 |                                       54% |                                 5,429 |                                 13,115 |
|                       [Argentina](/argentina) |            1,207 |                     6,544 |                     146 |                      5,337 |                                      442% |                                 2,851 |                                 12,389 |
|                           [Ecuador](/ecuador) |            4,424 |                     6,172 |                     355 |                      1,748 |                                       40% |                                 4,779 |                                 10,663 |
|                           [Bolivia](/bolivia) |              970 |                     5,766 |                     501 |                      4,796 |                                      494% |                                 2,947 |                                  9,471 |
|                 [Saudi Arabia](/saudi-arabia) |            1,511 |                     5,021 |                     147 |                      3,510 |                                      232% |                                 2,944 |                                  7,143 |
|                               [China](/china) |            4,641 |                     4,649 |                       3 |                          8 |                                        0% |                                 4,641 |                                  4,693 |
|                   [Philippines](/philippines) |            1,236 |                     2,451 |                      23 |                      1,215 |                                       98% |                                 1,336 |                                  4,355 |
|                         [Honduras](/honduras) |              479 |                     2,195 |                     225 |                      1,716 |                                      358% |                                 1,074 |                                  3,665 |
|                           [Algeria](/algeria) |              892 |                     2,146 |                      50 |                      1,254 |                                      141% |                                 1,255 |                                  4,357 |
|                           [Nigeria](/nigeria) |              558 |                     1,974 |                      10 |                      1,416 |                                      254% |                                   812 |                                  4,366 |
|                             [Panama](/panama) |              592 |                     1,855 |                     437 |                      1,263 |                                      213% |                                   936 |                                  3,035 |
|     [Dominican Republic](/dominican-republic) |              718 |                     1,717 |                     160 |                        999 |                                      139% |                                   896 |                                  4,108 |
|                               [Japan](/japan) |              971 |                     1,253 |                      10 |                        282 |                                       29% |                                   976 |                                  1,769 |
|                             [Kuwait](/kuwait) |              344 |                       585 |                     139 |                        241 |                                       70% |                                   404 |                                    904 |
| [United Arab Emirates](/united-arab-emirates) |              311 |                       428 |                      44 |                        117 |                                       38% |                                   334 |                                    751 |
|                             [Israel](/israel) |              317 |                       422 |                      50 |                        105 |                                       33% |                                   330 |                                    667 |
|                   [South Korea](/south-korea) |              282 |                       350 |                       7 |                         68 |                                       24% |                                   284 |                                    533 |
|                         [Malaysia](/malaysia) |              121 |                       280 |                       9 |                        159 |                                      131% |                                   137 |                                    478 |
|                           [Morocco](/morocco) |              220 |                       258 |                       7 |                         38 |                                       17% |                                   227 |                                    377 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    155 |
|                                 [Cuba](/cuba) |               86 |                       104 |                       9 |                         18 |                                       21% |                                    90 |                                    143 |
