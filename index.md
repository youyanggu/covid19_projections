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

* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 180k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: July 3 (2pm ET):
<p align="center">
  Current Total: <b>128,059</b> deaths | Projected Total: <b>186,115 deaths by Oct 1, 2020</b> (Range: 155-236k)<br>
  Currently Infected: <b>0.8%</b> | Total Infected: <b>6.0%</b> {% include iframe.html %}
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
|              140,000 |        Jul 23, 2020 |
|              150,000 |         Aug 8, 2020 |
|              175,000 |        Sep 12, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        15% |         65% |        95% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        22% |         40% |        52% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |         10% |        19% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         6% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          128,737 |                   186,647 |                     563 |                     57,910 |                                       45% |                               156,431 |                                235,815 |
|                 [New York](/us-ny) |           32,064 |                    33,245 |                   1,709 |                      1,181 |                                        4% |                                32,115 |                                 37,656 |
|               [New Jersey](/us-nj) |           15,107 |                    16,328 |                   1,838 |                      1,221 |                                        8% |                                15,264 |                                 17,850 |
|               [California](/us-ca) |            6,265 |                    13,141 |                     333 |                      6,876 |                                      110% |                                 8,667 |                                 21,052 |
|                 [Illinois](/us-il) |            6,951 |                     9,693 |                     765 |                      2,742 |                                       39% |                                 7,488 |                                 13,766 |
|            [Massachusetts](/us-ma) |            8,132 |                     9,423 |                   1,356 |                      1,291 |                                       16% |                                 8,369 |                                 11,578 |
|                  [Florida](/us-fl) |            3,617 |                     8,787 |                     409 |                      5,170 |                                      143% |                                 4,984 |                                 16,559 |
|             [Pennsylvania](/us-pa) |            6,712 |                     8,723 |                     681 |                      2,011 |                                       30% |                                 6,974 |                                 13,110 |
|                    [Texas](/us-tx) |            2,542 |                     7,595 |                     262 |                      5,053 |                                      199% |                                 3,769 |                                 15,880 |
|                 [Michigan](/us-mi) |            6,212 |                     7,402 |                     741 |                      1,190 |                                       19% |                                 6,299 |                                 10,524 |
|                  [Georgia](/us-ga) |            2,849 |                     6,253 |                     589 |                      3,404 |                                      119% |                                 3,664 |                                 10,850 |
|                  [Arizona](/us-az) |            1,764 |                     5,586 |                     767 |                      3,822 |                                      217% |                                 3,594 |                                  8,476 |
|                [Louisiana](/us-la) |            3,255 |                     4,754 |                   1,023 |                      1,499 |                                       46% |                                 3,463 |                                  6,671 |
|                     [Ohio](/us-oh) |            2,876 |                     4,734 |                     405 |                      1,858 |                                       65% |                                 3,169 |                                  8,556 |
|              [Connecticut](/us-ct) |            4,326 |                     4,718 |                   1,323 |                        392 |                                        9% |                                 4,380 |                                  5,457 |
|                 [Maryland](/us-md) |            3,212 |                     4,460 |                     738 |                      1,248 |                                       39% |                                 3,440 |                                  6,635 |
|                  [Indiana](/us-in) |            2,662 |                     3,769 |                     560 |                      1,107 |                                       42% |                                 2,788 |                                  6,726 |
|           [North Carolina](/us-nc) |            1,409 |                     3,049 |                     291 |                      1,640 |                                      116% |                                 1,778 |                                  6,435 |
|                 [Virginia](/us-va) |            1,816 |                     2,951 |                     346 |                      1,135 |                                       62% |                                 1,940 |                                  5,407 |
|                  [Alabama](/us-al) |              985 |                     2,867 |                     585 |                      1,882 |                                      191% |                                 1,432 |                                  4,821 |
|                [Minnesota](/us-mn) |            1,495 |                     2,479 |                     440 |                        984 |                                       66% |                                 1,661 |                                  4,316 |
|           [South Carolina](/us-sc) |              784 |                     2,475 |                     481 |                      1,691 |                                      216% |                                 1,323 |                                  4,450 |
|                 [Colorado](/us-co) |            1,701 |                     2,366 |                     411 |                        665 |                                       39% |                                 1,767 |                                  4,229 |
|              [Mississippi](/us-ms) |            1,092 |                     2,251 |                     756 |                      1,159 |                                      106% |                                 1,344 |                                  3,710 |
|               [Washington](/us-wa) |            1,342 |                     2,074 |                     272 |                        732 |                                       55% |                                 1,481 |                                  3,484 |
|                [Tennessee](/us-tn) |              620 |                     2,048 |                     300 |                      1,428 |                                      230% |                                   992 |                                  3,752 |
|                 [Missouri](/us-mo) |            1,044 |                     1,656 |                     270 |                        612 |                                       59% |                                 1,139 |                                  3,252 |
|                [Wisconsin](/us-wi) |              793 |                     1,474 |                     253 |                        681 |                                       86% |                                   925 |                                  2,918 |
|             [Rhode Island](/us-ri) |              959 |                     1,332 |                   1,257 |                        373 |                                       39% |                                 1,040 |                                  1,849 |
|                   [Nevada](/us-nv) |              525 |                     1,265 |                     411 |                        740 |                                      141% |                                   678 |                                  2,189 |
|                 [Kentucky](/us-ky) |              581 |                     1,094 |                     245 |                        513 |                                       88% |                                   655 |                                  2,211 |
|                 [Arkansas](/us-ar) |              279 |                       986 |                     327 |                        707 |                                      253% |                                   424 |                                  2,002 |
|                     [Iowa](/us-ia) |              719 |                       945 |                     300 |                        226 |                                       31% |                                   752 |                                  1,512 |
|               [New Mexico](/us-nm) |              503 |                       862 |                     411 |                        359 |                                       71% |                                   566 |                                  1,613 |
|                 [Oklahoma](/us-ok) |              395 |                       693 |                     175 |                        298 |                                       75% |                                   427 |                                  1,624 |
|     [District of Columbia](/us-dc) |              554 |                       687 |                     973 |                        133 |                                       24% |                                   578 |                                    972 |
|                 [Delaware](/us-de) |              510 |                       665 |                     683 |                        155 |                                       30% |                                   531 |                                  1,070 |
|            [New Hampshire](/us-nh) |              375 |                       638 |                     469 |                        263 |                                       70% |                                   417 |                                  1,165 |
|                   [Oregon](/us-or) |              209 |                       535 |                     127 |                        326 |                                      156% |                                   258 |                                  1,125 |
|                 [Nebraska](/us-ne) |              282 |                       527 |                     272 |                        245 |                                       87% |                                   347 |                                    860 |
|                     [Utah](/us-ut) |              176 |                       494 |                     154 |                        318 |                                      181% |                                   225 |                                  1,337 |
|                   [Kansas](/us-ks) |              280 |                       428 |                     147 |                        148 |                                       53% |                                   296 |                                    909 |
|              [Puerto Rico](/us-pr) |              153 |                       212 |                      66 |                         59 |                                       39% |                                   161 |                                    393 |
|                    [Idaho](/us-id) |               92 |                       193 |                     108 |                        101 |                                      110% |                                   109 |                                    343 |
|             [South Dakota](/us-sd) |               97 |                       182 |                     206 |                         85 |                                       88% |                                   114 |                                    307 |
|                    [Maine](/us-me) |              105 |                       147 |                     109 |                         42 |                                       40% |                                   113 |                                    258 |
|            [West Virginia](/us-wv) |               93 |                       119 |                      66 |                         26 |                                       28% |                                    98 |                                    178 |
|             [North Dakota](/us-nd) |               80 |                       109 |                     143 |                         29 |                                       36% |                                    89 |                                    153 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    58 |                                    118 |
|                  [Montana](/us-mt) |               22 |                        48 |                      45 |                         26 |                                      118% |                                    24 |                                    106 |
|                   [Alaska](/us-ak) |               14 |                        34 |                      46 |                         20 |                                      143% |                                    15 |                                     94 |
|                  [Wyoming](/us-wy) |               20 |                        31 |                      54 |                         11 |                                       55% |                                    24 |                                     46 |
|                   [Hawaii](/us-hi) |               18 |                        25 |                      18 |                          7 |                                       39% |                                    19 |                                     38 |
|           [Virgin Islands](/us-vi) |                6 |                        11 |                     105 |                          5 |                                       83% |                                     6 |                                     18 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      7 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          182,203 |                   201,664 |                     340 |                     19,461 |                                       11% |                               186,423 |                                230,247 |
| [United Kingdom](/united-kingdom) |           44,080 |                    48,561 |                     719 |                      4,481 |                                       10% |                                44,880 |                                 52,146 |
|                   [Italy](/italy) |           34,818 |                    36,478 |                     604 |                      1,660 |                                        5% |                                35,063 |                                 40,248 |
|                 [France](/france) |           29,878 |                    30,877 |                     461 |                        999 |                                        3% |                                29,909 |                                 35,459 |
|                   [Spain](/spain) |           28,368 |                    29,207 |                     622 |                        839 |                                        3% |                                28,417 |                                 31,194 |
|               [Germany](/germany) |            9,006 |                    10,444 |                     126 |                      1,438 |                                       16% |                                 9,081 |                                 13,511 |
|               [Belgium](/belgium) |            9,761 |                    10,030 |                     876 |                        269 |                                        3% |                                 9,784 |                                 10,763 |
|       [Netherlands](/netherlands) |            6,132 |                     6,460 |                     374 |                        328 |                                        5% |                                 6,169 |                                  7,088 |
|                 [Sweden](/sweden) |            5,411 |                     6,361 |                     622 |                        950 |                                       18% |                                 5,806 |                                  7,604 |
|               [Romania](/romania) |            1,687 |                     3,752 |                     193 |                      2,065 |                                      122% |                                 2,369 |                                  4,915 |
|                 [Poland](/poland) |            1,492 |                     3,043 |                      80 |                      1,551 |                                      104% |                                 1,887 |                                  4,484 |
|               [Ukraine](/ukraine) |            1,200 |                     2,976 |                      68 |                      1,776 |                                      148% |                                 1,777 |                                  4,748 |
|       [Switzerland](/switzerland) |            1,965 |                     2,053 |                     239 |                         88 |                                        4% |                                 1,977 |                                  2,384 |
|             [Portugal](/portugal) |            1,587 |                     1,946 |                     189 |                        359 |                                       23% |                                 1,655 |                                  2,561 |
|               [Ireland](/ireland) |            1,738 |                     1,822 |                     372 |                         84 |                                        5% |                                 1,746 |                                  2,198 |
|               [Moldova](/moldova) |              560 |                     1,377 |                     341 |                        817 |                                      146% |                                   963 |                                  2,033 |
|               [Belarus](/belarus) |              405 |                       861 |                      91 |                        456 |                                      113% |                                   550 |                                  1,629 |
|               [Austria](/austria) |              705 |                       808 |                      91 |                        103 |                                       15% |                                   720 |                                    969 |
|               [Hungary](/hungary) |              587 |                       773 |                      79 |                        186 |                                       32% |                                   612 |                                  1,107 |
|               [Denmark](/denmark) |              606 |                       672 |                     116 |                         66 |                                       11% |                                   621 |                                    826 |
|             [Bulgaria](/bulgaria) |              232 |                       617 |                      88 |                        385 |                                      166% |                                   345 |                                    957 |
|                 [Serbia](/serbia) |              287 |                       481 |                      69 |                        194 |                                       68% |                                   327 |                                    742 |
|               [Czechia](/czechia) |              353 |                       462 |                      43 |                        109 |                                       31% |                                   363 |                                    598 |
|               [Finland](/finland) |              328 |                       366 |                      66 |                         38 |                                       12% |                                   334 |                                    471 |
|                 [Norway](/norway) |              251 |                       272 |                      51 |                         21 |                                        8% |                                   257 |                                    311 |
|                 [Greece](/greece) |              192 |                       222 |                      21 |                         30 |                                       16% |                                   203 |                                    270 |
|               [Croatia](/croatia) |              110 |                       169 |                      41 |                         59 |                                       54% |                                   121 |                                    224 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   113 |                                    151 |
|         [Luxembourg](/luxembourg) |              110 |                       118 |                     192 |                          8 |                                        7% |                                   112 |                                    137 |
|           [Lithuania](/lithuania) |               78 |                       110 |                      39 |                         32 |                                       41% |                                    86 |                                    152 |
|               [Estonia](/estonia) |               69 |                        88 |                      66 |                         19 |                                       28% |                                    75 |                                    149 |
|                 [Latvia](/latvia) |               30 |                        46 |                      24 |                         16 |                                       53% |                                    32 |                                     79 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    28 |                                     59 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     46 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          200,298 |                   535,791 |                     103 |                    335,493 |                                      167% |                               347,276 |                                854,770 |
|                             [Brazil](/brazil) |           61,884 |                   132,131 |                     626 |                     70,247 |                                      114% |                               103,791 |                                196,987 |
|                               [India](/india) |           18,213 |                    93,022 |                      68 |                     74,809 |                                      411% |                                38,788 |                                190,814 |
|                             [Mexico](/mexico) |           29,189 |                    86,316 |                     677 |                     57,127 |                                      196% |                                60,552 |                                125,730 |
|                                 [Peru](/peru) |           10,045 |                    22,458 |                     691 |                     12,413 |                                      124% |                                15,864 |                                 32,130 |
|                         [Colombia](/colombia) |            3,650 |                    20,953 |                     416 |                     17,303 |                                      474% |                                12,503 |                                 28,378 |
|                                 [Iran](/iran) |           11,106 |                    20,334 |                     245 |                      9,228 |                                       83% |                                16,518 |                                 26,127 |
|                             [Russia](/russia) |            9,668 |                    19,137 |                     131 |                      9,469 |                                       98% |                                12,762 |                                 31,163 |
|                         [Pakistan](/pakistan) |            4,551 |                    15,633 |                      72 |                     11,082 |                                      244% |                                 8,666 |                                 28,489 |
|                 [South Africa](/south-africa) |            2,844 |                    14,383 |                     246 |                     11,539 |                                      406% |                                 7,397 |                                 20,613 |
|                               [Egypt](/egypt) |            3,120 |                    13,225 |                     132 |                     10,105 |                                      324% |                                 7,693 |                                 20,849 |
|                               [Chile](/chile) |            5,920 |                    13,014 |                     687 |                      7,094 |                                      120% |                                 7,952 |                                 18,946 |
|                             [Canada](/canada) |            8,700 |                    10,195 |                     273 |                      1,495 |                                       17% |                                 8,942 |                                 13,046 |
|                       [Indonesia](/indonesia) |            2,987 |                     9,043 |                      33 |                      6,056 |                                      203% |                                 4,878 |                                 14,839 |
|                     [Bangladesh](/bangladesh) |            1,926 |                     8,438 |                      52 |                      6,512 |                                      338% |                                 4,419 |                                 14,249 |
|                             [Turkey](/turkey) |            5,167 |                     7,764 |                      93 |                      2,597 |                                       50% |                                 5,482 |                                 12,758 |
|                           [Bolivia](/bolivia) |            1,271 |                     7,014 |                     609 |                      5,743 |                                      452% |                                 3,387 |                                 10,779 |
|                       [Argentina](/argentina) |            1,385 |                     6,937 |                     155 |                      5,552 |                                      401% |                                 3,517 |                                 12,451 |
|                           [Ecuador](/ecuador) |            4,639 |                     6,522 |                     375 |                      1,883 |                                       41% |                                 4,938 |                                 10,941 |
|                 [Saudi Arabia](/saudi-arabia) |            1,752 |                     5,218 |                     152 |                      3,466 |                                      198% |                                 3,192 |                                  7,179 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,679 |
|                         [Honduras](/honduras) |              591 |                     3,373 |                     346 |                      2,782 |                                      471% |                                 2,257 |                                  5,098 |
|     [Dominican Republic](/dominican-republic) |              765 |                     2,916 |                     272 |                      2,151 |                                      281% |                                 1,075 |                                  5,606 |
|                   [Philippines](/philippines) |            1,274 |                     2,691 |                      25 |                      1,417 |                                      111% |                                 1,426 |                                  5,044 |
|                             [Panama](/panama) |              667 |                     2,570 |                     605 |                      1,903 |                                      285% |                                 1,563 |                                  3,540 |
|                           [Algeria](/algeria) |              928 |                     2,113 |                      49 |                      1,185 |                                      128% |                                 1,278 |                                  4,208 |
|                           [Nigeria](/nigeria) |              616 |                     1,954 |                      10 |                      1,338 |                                      217% |                                   886 |                                  4,189 |
|                               [Japan](/japan) |              977 |                     1,214 |                      10 |                        237 |                                       24% |                                   981 |                                  1,762 |
|                             [Kuwait](/kuwait) |              359 |                       589 |                     140 |                        230 |                                       64% |                                   405 |                                    998 |
|                             [Israel](/israel) |              324 |                       438 |                      51 |                        114 |                                       35% |                                   338 |                                    694 |
| [United Arab Emirates](/united-arab-emirates) |              317 |                       431 |                      44 |                        114 |                                       36% |                                   337 |                                    745 |
|                   [South Korea](/south-korea) |              282 |                       356 |                       7 |                         74 |                                       26% |                                   283 |                                    568 |
|                           [Morocco](/morocco) |              229 |                       272 |                       7 |                         43 |                                       19% |                                   236 |                                    409 |
|                         [Malaysia](/malaysia) |              121 |                       271 |                       8 |                        150 |                                      124% |                                   135 |                                    470 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    154 |
|                                 [Cuba](/cuba) |               86 |                       103 |                       9 |                         17 |                                       20% |                                    90 |                                    138 |
