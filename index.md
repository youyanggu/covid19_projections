We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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

* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: July 4 (2pm ET):
<p align="center">
  Current Total: <b>129,431</b> deaths | Projected Total: <b>187,300 deaths by Oct 1, 2020</b> (Range: 157-237k)<br>
  Currently Infected: <b>0.8%</b> | Total Infected: <b>6.1%</b> {% include iframe.html %}
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
|              140,000 |        Jul 22, 2020 |
|              150,000 |         Aug 7, 2020 |
|              175,000 |        Sep 12, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        16% |         68% |        97% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        22% |         41% |        53% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |         10% |        20% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         7% |
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
|             *[United States](/us)* |          129,431 |                   187,318 |                     565 |                     57,887 |                                       45% |                               157,126 |                                236,513 |
|                 [New York](/us-ny) |           32,137 |                    33,356 |                   1,715 |                      1,219 |                                        4% |                                32,189 |                                 37,912 |
|               [New Jersey](/us-nj) |           15,164 |                    16,374 |                   1,843 |                      1,210 |                                        8% |                                15,313 |                                 17,877 |
|               [California](/us-ca) |            6,315 |                    13,132 |                     332 |                      6,817 |                                      108% |                                 8,696 |                                 20,905 |
|                 [Illinois](/us-il) |            7,005 |                     9,779 |                     772 |                      2,774 |                                       40% |                                 7,685 |                                 13,802 |
|            [Massachusetts](/us-ma) |            8,149 |                     9,406 |                   1,353 |                      1,257 |                                       15% |                                 8,374 |                                 11,536 |
|                  [Florida](/us-fl) |            3,684 |                     8,949 |                     417 |                      5,265 |                                      143% |                                 5,040 |                                 16,935 |
|             [Pennsylvania](/us-pa) |            6,746 |                     8,806 |                     688 |                      2,060 |                                       31% |                                 6,997 |                                 13,253 |
|                    [Texas](/us-tx) |            2,592 |                     7,721 |                     266 |                      5,129 |                                      198% |                                 3,815 |                                 16,017 |
|                 [Michigan](/us-mi) |            6,215 |                     7,379 |                     739 |                      1,164 |                                       19% |                                 6,297 |                                 10,497 |
|                  [Georgia](/us-ga) |            2,857 |                     6,201 |                     584 |                      3,344 |                                      117% |                                 3,658 |                                 10,765 |
|                  [Arizona](/us-az) |            1,798 |                     5,589 |                     768 |                      3,791 |                                      211% |                                 3,608 |                                  8,454 |
|                [Louisiana](/us-la) |            3,278 |                     4,791 |                   1,031 |                      1,513 |                                       46% |                                 3,484 |                                  6,696 |
|                     [Ohio](/us-oh) |            2,903 |                     4,774 |                     408 |                      1,871 |                                       64% |                                 3,194 |                                  8,585 |
|              [Connecticut](/us-ct) |            4,335 |                     4,722 |                   1,324 |                        387 |                                        9% |                                 4,385 |                                  5,457 |
|                 [Maryland](/us-md) |            3,223 |                     4,458 |                     737 |                      1,235 |                                       38% |                                 3,445 |                                  6,621 |
|                  [Indiana](/us-in) |            2,681 |                     3,785 |                     562 |                      1,104 |                                       41% |                                 2,805 |                                  6,738 |
|           [North Carolina](/us-nc) |            1,419 |                     3,018 |                     288 |                      1,599 |                                      113% |                                 1,780 |                                  6,381 |
|                 [Virginia](/us-va) |            1,845 |                     2,983 |                     349 |                      1,138 |                                       62% |                                 1,966 |                                  5,429 |
|                  [Alabama](/us-al) |            1,006 |                     2,900 |                     591 |                      1,894 |                                      188% |                                 1,452 |                                  4,839 |
|                [Minnesota](/us-mn) |            1,503 |                     2,481 |                     440 |                        978 |                                       65% |                                 1,665 |                                  4,312 |
|           [South Carolina](/us-sc) |              793 |                     2,461 |                     478 |                      1,668 |                                      210% |                                 1,320 |                                  4,438 |
|                 [Colorado](/us-co) |            1,701 |                     2,356 |                     409 |                        655 |                                       39% |                                 1,765 |                                  4,206 |
|              [Mississippi](/us-ms) |            1,103 |                     2,247 |                     755 |                      1,144 |                                      104% |                                 1,349 |                                  3,696 |
|               [Washington](/us-wa) |            1,352 |                     2,088 |                     274 |                        736 |                                       54% |                                 1,500 |                                  3,489 |
|                [Tennessee](/us-tn) |              633 |                     2,079 |                     304 |                      1,446 |                                      228% |                                 1,005 |                                  3,775 |
|                 [Missouri](/us-mo) |            1,047 |                     1,648 |                     269 |                        601 |                                       57% |                                 1,138 |                                  3,229 |
|                [Wisconsin](/us-wi) |              796 |                     1,468 |                     252 |                        672 |                                       84% |                                   925 |                                  2,923 |
|             [Rhode Island](/us-ri) |              960 |                     1,324 |                   1,250 |                        364 |                                       38% |                                 1,037 |                                  1,837 |
|                   [Nevada](/us-nv) |              528 |                     1,275 |                     414 |                        747 |                                      141% |                                   697 |                                  2,191 |
|                 [Kentucky](/us-ky) |              585 |                     1,097 |                     246 |                        512 |                                       88% |                                   662 |                                  2,208 |
|                 [Arkansas](/us-ar) |              281 |                       972 |                     322 |                        691 |                                      246% |                                   421 |                                  1,955 |
|                     [Iowa](/us-ia) |              721 |                       942 |                     299 |                        221 |                                       31% |                                   754 |                                  1,500 |
|               [New Mexico](/us-nm) |              511 |                       875 |                     417 |                        364 |                                       71% |                                   575 |                                  1,625 |
|                 [Oklahoma](/us-ok) |              398 |                       696 |                     176 |                        298 |                                       75% |                                   430 |                                  1,625 |
|     [District of Columbia](/us-dc) |              555 |                       685 |                     971 |                        130 |                                       23% |                                   578 |                                    968 |
|                 [Delaware](/us-de) |              512 |                       667 |                     685 |                        155 |                                       30% |                                   533 |                                  1,077 |
|            [New Hampshire](/us-nh) |              376 |                       635 |                     467 |                        259 |                                       69% |                                   416 |                                  1,157 |
|                   [Oregon](/us-or) |              209 |                       528 |                     125 |                        319 |                                      153% |                                   256 |                                  1,118 |
|                 [Nebraska](/us-ne) |              284 |                       525 |                     271 |                        241 |                                       85% |                                   347 |                                    854 |
|                     [Utah](/us-ut) |              181 |                       506 |                     158 |                        325 |                                      180% |                                   231 |                                  1,352 |
|                   [Kansas](/us-ks) |              282 |                       433 |                     149 |                        151 |                                       54% |                                   299 |                                    909 |
|              [Puerto Rico](/us-pr) |              154 |                       213 |                      67 |                         59 |                                       38% |                                   162 |                                    396 |
|                    [Idaho](/us-id) |               93 |                       196 |                     110 |                        103 |                                      111% |                                   111 |                                    344 |
|             [South Dakota](/us-sd) |               97 |                       181 |                     205 |                         84 |                                       87% |                                   114 |                                    305 |
|                    [Maine](/us-me) |              105 |                       147 |                     109 |                         42 |                                       40% |                                   112 |                                    257 |
|            [West Virginia](/us-wv) |               93 |                       119 |                      66 |                         26 |                                       28% |                                    98 |                                    177 |
|             [North Dakota](/us-nd) |               80 |                       108 |                     142 |                         28 |                                       35% |                                    89 |                                    151 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    58 |                                    118 |
|                  [Montana](/us-mt) |               23 |                        51 |                      48 |                         28 |                                      122% |                                    25 |                                    111 |
|                   [Alaska](/us-ak) |               15 |                        37 |                      51 |                         22 |                                      147% |                                    16 |                                    103 |
|                  [Wyoming](/us-wy) |               20 |                        30 |                      52 |                         10 |                                       50% |                                    23 |                                     44 |
|                   [Hawaii](/us-hi) |               19 |                        26 |                      18 |                          7 |                                       37% |                                    20 |                                     39 |
|           [Virgin Islands](/us-vi) |                6 |                        11 |                     105 |                          5 |                                       83% |                                     6 |                                     18 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      7 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          182,524 |                   202,284 |                     341 |                     19,760 |                                       11% |                               187,126 |                                230,627 |
| [United Kingdom](/united-kingdom) |           44,216 |                    48,721 |                     721 |                      4,505 |                                       10% |                                45,219 |                                 52,196 |
|                   [Italy](/italy) |           34,833 |                    36,458 |                     604 |                      1,625 |                                        5% |                                35,069 |                                 40,193 |
|                 [France](/france) |           29,896 |                    30,883 |                     461 |                        987 |                                        3% |                                29,926 |                                 35,454 |
|                   [Spain](/spain) |           28,385 |                    29,213 |                     622 |                        828 |                                        3% |                                28,433 |                                 31,181 |
|               [Germany](/germany) |            9,010 |                    10,404 |                     125 |                      1,394 |                                       15% |                                 9,082 |                                 13,454 |
|               [Belgium](/belgium) |            9,765 |                    10,029 |                     875 |                        264 |                                        3% |                                 9,788 |                                 10,754 |
|       [Netherlands](/netherlands) |            6,132 |                     6,455 |                     374 |                        323 |                                        5% |                                 6,168 |                                  7,078 |
|                 [Sweden](/sweden) |            5,420 |                     6,343 |                     620 |                        923 |                                       17% |                                 5,802 |                                  7,570 |
|               [Romania](/romania) |            1,708 |                     3,846 |                     198 |                      2,138 |                                      125% |                                 2,445 |                                  4,970 |
|               [Ukraine](/ukraine) |            1,227 |                     3,185 |                      72 |                      1,958 |                                      160% |                                 1,933 |                                  4,974 |
|                 [Poland](/poland) |            1,507 |                     3,068 |                      81 |                      1,561 |                                      104% |                                 1,901 |                                  4,502 |
|       [Switzerland](/switzerland) |            1,965 |                     2,052 |                     239 |                         87 |                                        4% |                                 1,976 |                                  2,381 |
|             [Portugal](/portugal) |            1,598 |                     1,990 |                     194 |                        392 |                                       25% |                                 1,666 |                                  2,609 |
|               [Ireland](/ireland) |            1,740 |                     1,823 |                     372 |                         83 |                                        5% |                                 1,747 |                                  2,198 |
|               [Moldova](/moldova) |              572 |                     1,447 |                     358 |                        875 |                                      153% |                                   983 |                                  2,072 |
|               [Belarus](/belarus) |              412 |                       870 |                      92 |                        458 |                                      111% |                                   555 |                                  1,631 |
|               [Austria](/austria) |              705 |                       805 |                      91 |                        100 |                                       14% |                                   720 |                                    957 |
|               [Hungary](/hungary) |              588 |                       771 |                      79 |                        183 |                                       31% |                                   612 |                                  1,103 |
|               [Denmark](/denmark) |              606 |                       670 |                     115 |                         64 |                                       11% |                                   620 |                                    824 |
|             [Bulgaria](/bulgaria) |              239 |                       655 |                      94 |                        416 |                                      174% |                                   365 |                                    999 |
|                 [Serbia](/serbia) |              298 |                       516 |                      74 |                        218 |                                       73% |                                   344 |                                    802 |
|               [Czechia](/czechia) |              353 |                       461 |                      43 |                        108 |                                       31% |                                   363 |                                    597 |
|               [Finland](/finland) |              329 |                       368 |                      67 |                         39 |                                       12% |                                   335 |                                    479 |
|                 [Norway](/norway) |              251 |                       272 |                      51 |                         21 |                                        8% |                                   257 |                                    311 |
|                 [Greece](/greece) |              192 |                       221 |                      21 |                         29 |                                       15% |                                   203 |                                    267 |
|               [Croatia](/croatia) |              112 |                       180 |                      44 |                         68 |                                       61% |                                   125 |                                    245 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   113 |                                    151 |
|         [Luxembourg](/luxembourg) |              110 |                       118 |                     192 |                          8 |                                        7% |                                   112 |                                    136 |
|           [Lithuania](/lithuania) |               79 |                       114 |                      41 |                         35 |                                       44% |                                    88 |                                    174 |
|               [Estonia](/estonia) |               69 |                        88 |                      66 |                         19 |                                       28% |                                    75 |                                    149 |
|                 [Latvia](/latvia) |               30 |                        46 |                      24 |                         16 |                                       53% |                                    32 |                                     78 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    28 |                                     58 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     46 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          202,858 |                   527,551 |                     102 |                    324,693 |                                      160% |                               348,534 |                                811,551 |
|                             [Brazil](/brazil) |           61,884 |                   132,372 |                     627 |                     70,488 |                                      114% |                               103,204 |                                198,751 |
|                               [India](/india) |           18,655 |                    91,820 |                      67 |                     73,165 |                                      392% |                                39,431 |                                186,508 |
|                             [Mexico](/mexico) |           29,843 |                    80,613 |                     632 |                     50,770 |                                      170% |                                60,274 |                                 93,645 |
|                                 [Peru](/peru) |           10,226 |                    22,413 |                     689 |                     12,187 |                                      119% |                                15,972 |                                 31,714 |
|                         [Colombia](/colombia) |            3,851 |                    21,458 |                     426 |                     17,607 |                                      457% |                                13,076 |                                 28,618 |
|                                 [Iran](/iran) |           11,260 |                    20,459 |                     247 |                      9,199 |                                       82% |                                16,741 |                                 26,208 |
|                             [Russia](/russia) |            9,844 |                    19,406 |                     133 |                      9,562 |                                       97% |                                13,048 |                                 31,292 |
|                 [South Africa](/south-africa) |            2,952 |                    14,537 |                     248 |                     11,585 |                                      392% |                                 7,836 |                                 20,651 |
|                               [Egypt](/egypt) |            3,201 |                    13,254 |                     132 |                     10,053 |                                      314% |                                 7,751 |                                 20,820 |
|                               [Chile](/chile) |            6,051 |                    12,942 |                     683 |                      6,891 |                                      114% |                                 8,012 |                                 18,856 |
|                         [Pakistan](/pakistan) |            4,551 |                    12,447 |                      57 |                      7,896 |                                      174% |                                 7,812 |                                 20,075 |
|                             [Canada](/canada) |            8,722 |                    10,192 |                     272 |                      1,470 |                                       17% |                                 8,961 |                                 13,021 |
|                       [Indonesia](/indonesia) |            3,036 |                     9,123 |                      34 |                      6,087 |                                      200% |                                 4,956 |                                 14,906 |
|                     [Bangladesh](/bangladesh) |            1,968 |                     8,263 |                      51 |                      6,295 |                                      320% |                                 4,414 |                                 13,942 |
|                             [Turkey](/turkey) |            5,186 |                     7,754 |                      93 |                      2,568 |                                       50% |                                 5,497 |                                 12,709 |
|                       [Argentina](/argentina) |            1,437 |                     7,466 |                     167 |                      6,029 |                                      420% |                                 3,630 |                                 12,699 |
|                           [Bolivia](/bolivia) |            1,320 |                     7,038 |                     611 |                      5,718 |                                      433% |                                 3,448 |                                 10,727 |
|                           [Ecuador](/ecuador) |            4,700 |                     6,617 |                     381 |                      1,917 |                                       41% |                                 4,991 |                                 11,030 |
|                 [Saudi Arabia](/saudi-arabia) |            1,802 |                     5,257 |                     153 |                      3,455 |                                      192% |                                 3,241 |                                  7,187 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,678 |
|                         [Honduras](/honduras) |              605 |                     3,356 |                     344 |                      2,751 |                                      455% |                                 2,253 |                                  5,072 |
|     [Dominican Republic](/dominican-republic) |              775 |                     2,911 |                     271 |                      2,136 |                                      276% |                                 1,080 |                                  5,587 |
|                   [Philippines](/philippines) |            1,280 |                     2,672 |                      25 |                      1,392 |                                      109% |                                 1,427 |                                  4,994 |
|                             [Panama](/panama) |              698 |                     2,666 |                     628 |                      1,968 |                                      282% |                                 1,741 |                                  3,664 |
|                           [Algeria](/algeria) |              937 |                     2,118 |                      49 |                      1,181 |                                      126% |                                 1,284 |                                  4,206 |
|                           [Nigeria](/nigeria) |              628 |                     1,965 |                      10 |                      1,337 |                                      213% |                                   902 |                                  4,075 |
|                               [Japan](/japan) |              977 |                     1,212 |                      10 |                        235 |                                       24% |                                   981 |                                  1,756 |
|                             [Kuwait](/kuwait) |              360 |                       582 |                     138 |                        222 |                                       62% |                                   403 |                                    984 |
|                             [Israel](/israel) |              326 |                       443 |                      52 |                        117 |                                       36% |                                   340 |                                    701 |
| [United Arab Emirates](/united-arab-emirates) |              318 |                       430 |                      44 |                        112 |                                       35% |                                   337 |                                    740 |
|                   [South Korea](/south-korea) |              283 |                       356 |                       7 |                         73 |                                       26% |                                   284 |                                    567 |
|                           [Morocco](/morocco) |              230 |                       273 |                       7 |                         43 |                                       19% |                                   237 |                                    411 |
|                         [Malaysia](/malaysia) |              121 |                       270 |                       8 |                        149 |                                      123% |                                   135 |                                    466 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    154 |
|                                 [Cuba](/cuba) |               86 |                       103 |                       9 |                         17 |                                       20% |                                    90 |                                    137 |
