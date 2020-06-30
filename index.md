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
### Updated Daily - Last Updated: June 30 (3pm ET):
<p align="center">
  Current Total: <b>126,137</b> deaths | Projected Total: <b>188,703 deaths by Oct 1, 2020</b> (Range: 159-226k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>5.2%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: Jun 30, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 7, 2020 |
|              140,000 |        Jul 23, 2020 |
|              150,000 |         Aug 6, 2020 |
|              175,000 |         Sep 9, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        <1% |         <1% |        24% |         78% |        99% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        32% |         51% |        65% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          9% |        26% |
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
|             *[United States](/us)* |          126,137 |                   188,703 |                     569 |                     62,566 |                                       50% |                               159,641 |                                225,922 |
|                 [New York](/us-ny) |           31,403 |                    33,400 |                   1,717 |                      1,997 |                                        6% |                                31,508 |                                 39,152 |
|               [New Jersey](/us-nj) |           14,992 |                    16,561 |                   1,865 |                      1,569 |                                       10% |                                15,224 |                                 17,963 |
|               [California](/us-ca) |            5,983 |                    14,397 |                     364 |                      8,414 |                                      141% |                                 9,027 |                                 21,636 |
|                 [Illinois](/us-il) |            6,902 |                    10,329 |                     815 |                      3,427 |                                       50% |                                 7,942 |                                 12,739 |
|            [Massachusetts](/us-ma) |            8,094 |                     9,840 |                   1,416 |                      1,746 |                                       22% |                                 8,457 |                                 12,025 |
|             [Pennsylvania](/us-pa) |            6,614 |                     9,300 |                     726 |                      2,686 |                                       41% |                                 6,975 |                                 14,079 |
|                  [Florida](/us-fl) |            3,447 |                     8,320 |                     387 |                      4,873 |                                      141% |                                 5,248 |                                 12,684 |
|                 [Michigan](/us-mi) |            6,161 |                     7,246 |                     726 |                      1,085 |                                       18% |                                 6,268 |                                  9,298 |
|                    [Texas](/us-tx) |            2,416 |                     6,948 |                     240 |                      4,532 |                                      188% |                                 4,078 |                                 10,636 |
|                  [Georgia](/us-ga) |            2,784 |                     5,917 |                     557 |                      3,133 |                                      113% |                                 3,388 |                                  9,414 |
|                  [Arizona](/us-az) |            1,598 |                     5,191 |                     713 |                      3,593 |                                      225% |                                 3,324 |                                  7,170 |
|                     [Ohio](/us-oh) |            2,818 |                     5,021 |                     430 |                      2,203 |                                       78% |                                 3,228 |                                  7,556 |
|              [Connecticut](/us-ct) |            4,320 |                     4,871 |                   1,366 |                        551 |                                       13% |                                 4,422 |                                  5,629 |
|                 [Maryland](/us-md) |            3,175 |                     4,677 |                     774 |                      1,502 |                                       47% |                                 3,482 |                                  6,153 |
|                [Louisiana](/us-la) |            3,199 |                     4,280 |                     921 |                      1,081 |                                       34% |                                 3,377 |                                  5,847 |
|                  [Indiana](/us-in) |            2,624 |                     3,999 |                     594 |                      1,375 |                                       52% |                                 2,815 |                                  6,143 |
|           [North Carolina](/us-nc) |            1,357 |                     3,387 |                     323 |                      2,030 |                                      150% |                                 1,938 |                                  5,316 |
|                 [Virginia](/us-va) |            1,740 |                     2,820 |                     330 |                      1,080 |                                       62% |                                 1,893 |                                  4,209 |
|                  [Alabama](/us-al) |              929 |                     2,685 |                     548 |                      1,756 |                                      189% |                                 1,596 |                                  3,760 |
|                [Minnesota](/us-mn) |            1,470 |                     2,613 |                     463 |                      1,143 |                                       78% |                                 1,697 |                                  3,785 |
|              [Mississippi](/us-ms) |            1,059 |                     2,465 |                     828 |                      1,406 |                                      133% |                                 1,453 |                                  3,532 |
|                 [Colorado](/us-co) |            1,681 |                     2,444 |                     424 |                        763 |                                       45% |                                 1,754 |                                  3,849 |
|               [Washington](/us-wa) |            1,320 |                     2,344 |                     308 |                      1,024 |                                       78% |                                 1,491 |                                  4,515 |
|           [South Carolina](/us-sc) |              720 |                     1,967 |                     382 |                      1,247 |                                      173% |                                 1,034 |                                  3,000 |
|                 [Missouri](/us-mo) |            1,004 |                     1,747 |                     285 |                        743 |                                       74% |                                 1,112 |                                  3,075 |
|                [Tennessee](/us-tn) |              592 |                     1,717 |                     251 |                      1,125 |                                      190% |                                   913 |                                  2,495 |
|                [Wisconsin](/us-wi) |              777 |                     1,600 |                     275 |                        823 |                                      106% |                                   971 |                                  2,518 |
|             [Rhode Island](/us-ri) |              946 |                     1,435 |                   1,355 |                        489 |                                       52% |                                 1,074 |                                  1,836 |
|                 [Kentucky](/us-ky) |              560 |                     1,121 |                     251 |                        561 |                                      100% |                                   660 |                                  1,822 |
|                   [Nevada](/us-nv) |              504 |                     1,065 |                     346 |                        561 |                                      111% |                                   624 |                                  1,663 |
|                     [Iowa](/us-ia) |              711 |                     1,044 |                     331 |                        333 |                                       47% |                                   762 |                                  1,892 |
|               [New Mexico](/us-nm) |              493 |                       943 |                     450 |                        450 |                                       91% |                                   580 |                                  1,529 |
|                 [Arkansas](/us-ar) |              265 |                       934 |                     309 |                        669 |                                      252% |                                   518 |                                  1,400 |
|     [District of Columbia](/us-dc) |              551 |                       725 |                   1,027 |                        174 |                                       32% |                                   588 |                                    958 |
|                 [Delaware](/us-de) |              507 |                       723 |                     742 |                        216 |                                       43% |                                   541 |                                  1,129 |
|                 [Oklahoma](/us-ok) |              385 |                       684 |                     173 |                        299 |                                       78% |                                   429 |                                  1,228 |
|            [New Hampshire](/us-nh) |              367 |                       680 |                     500 |                        313 |                                       85% |                                   423 |                                  1,052 |
|                 [Nebraska](/us-ne) |              269 |                       627 |                     324 |                        358 |                                      133% |                                   363 |                                  1,074 |
|                     [Utah](/us-ut) |              168 |                       476 |                     148 |                        308 |                                      183% |                                   250 |                                    758 |
|                   [Oregon](/us-or) |              204 |                       473 |                     112 |                        269 |                                      132% |                                   251 |                                    786 |
|                   [Kansas](/us-ks) |              273 |                       469 |                     161 |                        196 |                                       72% |                                   297 |                                    947 |
|              [Puerto Rico](/us-pr) |              153 |                       217 |                      68 |                         64 |                                       42% |                                   165 |                                    339 |
|             [South Dakota](/us-sd) |               91 |                       201 |                     227 |                        110 |                                      121% |                                   111 |                                    362 |
|                    [Idaho](/us-id) |               91 |                       161 |                      90 |                         70 |                                       77% |                                    98 |                                    249 |
|                    [Maine](/us-me) |              105 |                       153 |                     114 |                         48 |                                       46% |                                   117 |                                    235 |
|            [West Virginia](/us-wv) |               93 |                       133 |                      74 |                         40 |                                       43% |                                   102 |                                    224 |
|             [North Dakota](/us-nd) |               79 |                       116 |                     152 |                         37 |                                       47% |                                    92 |                                    174 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     122 |                         20 |                                       36% |                                    59 |                                    103 |
|                  [Montana](/us-mt) |               22 |                        45 |                      42 |                         23 |                                      105% |                                    23 |                                     89 |
|                   [Alaska](/us-ak) |               14 |                        35 |                      48 |                         21 |                                      150% |                                    15 |                                     70 |
|                  [Wyoming](/us-wy) |               20 |                        34 |                      59 |                         14 |                                       70% |                                    24 |                                     58 |
|                   [Hawaii](/us-hi) |               18 |                        24 |                      17 |                          6 |                                       33% |                                    18 |                                     38 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     14 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     2 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          181,213 |                   202,202 |                     341 |                     20,989 |                                       12% |                               185,310 |                                233,629 |
| [United Kingdom](/united-kingdom) |           43,659 |                    48,741 |                     722 |                      5,082 |                                       12% |                                44,539 |                                 53,211 |
|                   [Italy](/italy) |           34,744 |                    36,833 |                     610 |                      2,089 |                                        6% |                                35,032 |                                 41,152 |
|                 [France](/france) |           29,816 |                    30,931 |                     462 |                      1,115 |                                        4% |                                29,853 |                                 35,586 |
|                   [Spain](/spain) |           28,346 |                    29,313 |                     625 |                        967 |                                        3% |                                28,400 |                                 31,649 |
|               [Germany](/germany) |            8,976 |                    10,524 |                     127 |                      1,548 |                                       17% |                                 9,079 |                                 13,787 |
|               [Belgium](/belgium) |            9,732 |                    10,017 |                     874 |                        285 |                                        3% |                                 9,756 |                                 10,865 |
|       [Netherlands](/netherlands) |            6,126 |                     6,503 |                     376 |                        377 |                                        6% |                                 6,166 |                                  7,205 |
|                 [Sweden](/sweden) |            5,310 |                     6,337 |                     619 |                      1,027 |                                       19% |                                 5,546 |                                  7,830 |
|               [Romania](/romania) |            1,634 |                     3,359 |                     173 |                      1,725 |                                      106% |                                 2,093 |                                  4,543 |
|               [Ukraine](/ukraine) |            1,161 |                     3,332 |                      76 |                      2,171 |                                      187% |                                 1,808 |                                  5,302 |
|                 [Poland](/poland) |            1,444 |                     2,980 |                      78 |                      1,536 |                                      106% |                                 1,843 |                                  4,427 |
|       [Switzerland](/switzerland) |            1,962 |                     2,053 |                     239 |                         91 |                                        5% |                                 1,974 |                                  2,376 |
|             [Portugal](/portugal) |            1,568 |                     1,894 |                     184 |                        326 |                                       21% |                                 1,634 |                                  2,479 |
|               [Ireland](/ireland) |            1,735 |                     1,830 |                     373 |                         95 |                                        5% |                                 1,745 |                                  2,235 |
|               [Moldova](/moldova) |              536 |                     1,460 |                     361 |                        924 |                                      172% |                                   982 |                                  2,147 |
|               [Belarus](/belarus) |              387 |                       851 |                      90 |                        464 |                                      120% |                                   529 |                                  1,727 |
|               [Hungary](/hungary) |              585 |                       782 |                      80 |                        197 |                                       34% |                                   609 |                                  1,139 |
|               [Austria](/austria) |              703 |                       780 |                      88 |                         77 |                                       11% |                                   716 |                                    960 |
|               [Denmark](/denmark) |              605 |                       675 |                     116 |                         70 |                                       12% |                                   622 |                                    832 |
|             [Bulgaria](/bulgaria) |              223 |                       621 |                      89 |                        398 |                                      178% |                                   343 |                                    984 |
|               [Czechia](/czechia) |              348 |                       446 |                      42 |                         98 |                                       28% |                                   357 |                                    570 |
|                 [Serbia](/serbia) |              274 |                       378 |                      54 |                        104 |                                       38% |                                   292 |                                    585 |
|               [Finland](/finland) |              328 |                       366 |                      66 |                         38 |                                       12% |                                   333 |                                    478 |
|                 [Norway](/norway) |              249 |                       271 |                      50 |                         22 |                                        9% |                                   255 |                                    310 |
|                 [Greece](/greece) |              191 |                       220 |                      21 |                         29 |                                       15% |                                   202 |                                    271 |
|               [Croatia](/croatia) |              107 |                       128 |                      31 |                         21 |                                       20% |                                   113 |                                    161 |
|             [Slovenia](/slovenia) |              111 |                       121 |                      58 |                         10 |                                        9% |                                   113 |                                    146 |
|         [Luxembourg](/luxembourg) |              110 |                       119 |                     194 |                          9 |                                        8% |                                   112 |                                    139 |
|           [Lithuania](/lithuania) |               78 |                       110 |                      39 |                         32 |                                       41% |                                    86 |                                    158 |
|               [Estonia](/estonia) |               69 |                        91 |                      69 |                         22 |                                       32% |                                    76 |                                    157 |
|                 [Latvia](/latvia) |               30 |                        49 |                      26 |                         19 |                                       63% |                                    33 |                                     84 |
|             [Slovakia](/slovakia) |               28 |                        34 |                       6 |                          6 |                                       21% |                                    28 |                                     56 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     45 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    10 |                                     18 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          188,958 |                   553,185 |                     107 |                    364,227 |                                      193% |                               340,686 |                                903,782 |
|                             [Brazil](/brazil) |           58,314 |                   132,872 |                     630 |                     74,558 |                                      128% |                               102,038 |                                207,331 |
|                               [India](/india) |           16,893 |                    99,919 |                      73 |                     83,026 |                                      491% |                                37,720 |                                216,687 |
|                             [Mexico](/mexico) |           27,121 |                    95,271 |                     747 |                     68,150 |                                      251% |                                60,287 |                                131,025 |
|                                 [Peru](/peru) |            9,504 |                    22,638 |                     696 |                     13,134 |                                      138% |                                15,642 |                                 32,966 |
|                         [Colombia](/colombia) |            3,256 |                    20,364 |                     405 |                     17,108 |                                      525% |                                12,309 |                                 27,932 |
|                                 [Iran](/iran) |           10,670 |                    20,046 |                     242 |                      9,376 |                                       88% |                                16,030 |                                 25,431 |
|                             [Russia](/russia) |            9,152 |                    18,786 |                     129 |                      9,634 |                                      105% |                                12,099 |                                 31,472 |
|                         [Pakistan](/pakistan) |            4,304 |                    17,651 |                      82 |                     13,347 |                                      310% |                                 9,386 |                                 32,197 |
|                 [South Africa](/south-africa) |            2,529 |                    16,475 |                     281 |                     13,946 |                                      551% |                                 7,563 |                                 24,741 |
|                               [Chile](/chile) |            5,575 |                    13,360 |                     705 |                      7,785 |                                      140% |                                 7,910 |                                 19,520 |
|                               [Egypt](/egypt) |            2,872 |                    13,061 |                     130 |                     10,189 |                                      355% |                                 7,496 |                                 20,843 |
|                             [Canada](/canada) |            8,628 |                    10,555 |                     282 |                      1,927 |                                       22% |                                 8,969 |                                 14,767 |
|                     [Bangladesh](/bangladesh) |            1,783 |                     8,604 |                      53 |                      6,821 |                                      383% |                                 4,318 |                                 14,802 |
|                       [Indonesia](/indonesia) |            2,805 |                     8,307 |                      31 |                      5,502 |                                      196% |                                 4,222 |                                 13,808 |
|                             [Turkey](/turkey) |            5,115 |                     7,825 |                      94 |                      2,710 |                                       53% |                                 5,443 |                                 13,025 |
|                       [Argentina](/argentina) |            1,280 |                     6,738 |                     150 |                      5,458 |                                      426% |                                 3,236 |                                 12,485 |
|                           [Ecuador](/ecuador) |            4,502 |                     6,325 |                     364 |                      1,823 |                                       40% |                                 4,833 |                                 10,825 |
|                           [Bolivia](/bolivia) |            1,071 |                     6,206 |                     539 |                      5,135 |                                      479% |                                 3,036 |                                  9,762 |
|                 [Saudi Arabia](/saudi-arabia) |            1,599 |                     5,081 |                     148 |                      3,482 |                                      218% |                                 3,029 |                                  7,149 |
|                               [China](/china) |            4,641 |                     4,649 |                       3 |                          8 |                                        0% |                                 4,641 |                                  4,690 |
|                         [Honduras](/honduras) |              485 |                     2,894 |                     297 |                      2,409 |                                      497% |                                 1,843 |                                  4,335 |
|     [Dominican Republic](/dominican-republic) |              733 |                     2,892 |                     269 |                      2,159 |                                      295% |                                 1,040 |                                  5,783 |
|                   [Philippines](/philippines) |            1,255 |                     2,462 |                      23 |                      1,207 |                                       96% |                                 1,351 |                                  4,343 |
|                             [Panama](/panama) |              620 |                     2,419 |                     570 |                      1,799 |                                      290% |                                 1,275 |                                  3,475 |
|                           [Algeria](/algeria) |              905 |                     2,133 |                      50 |                      1,228 |                                      136% |                                 1,259 |                                  4,329 |
|                           [Nigeria](/nigeria) |              573 |                     1,831 |                       9 |                      1,258 |                                      220% |                                   817 |                                  4,125 |
|                               [Japan](/japan) |              972 |                     1,245 |                      10 |                        273 |                                       28% |                                   976 |                                  1,747 |
|                             [Kuwait](/kuwait) |              350 |                       610 |                     145 |                        260 |                                       74% |                                   405 |                                  1,084 |
| [United Arab Emirates](/united-arab-emirates) |              314 |                       433 |                      44 |                        119 |                                       38% |                                   336 |                                    757 |
|                             [Israel](/israel) |              319 |                       423 |                      50 |                        104 |                                       33% |                                   332 |                                    665 |
|                   [South Korea](/south-korea) |              282 |                       348 |                       7 |                         66 |                                       23% |                                   284 |                                    526 |
|                         [Malaysia](/malaysia) |              121 |                       278 |                       9 |                        157 |                                      130% |                                   136 |                                    475 |
|                           [Morocco](/morocco) |              225 |                       265 |                       7 |                         40 |                                       18% |                                   231 |                                    386 |
|                       [Australia](/australia) |              104 |                       116 |                       5 |                         12 |                                       12% |                                   104 |                                    155 |
|                                 [Cuba](/cuba) |               86 |                       103 |                       9 |                         17 |                                       20% |                                    90 |                                    139 |
