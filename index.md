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
### Updated Daily - Last Updated: June 24 (2am ET):
<p align="center">
  Current Total: <b>121,225</b> deaths | Projected Total: <b>184,162 deaths by Oct 1, 2020</b> (Range: 154-222k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.9%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 72% chance that the US surpasses 125,000 deaths by July 1, with June 30 being the most likely date.

Last updated: Jun 24, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 22, 2020 |
|              125,000 |        Jun 30, 2020 |
|              130,000 |         Jul 9, 2020 |
|              140,000 |        Jul 26, 2020 |
|              150,000 |        Aug 10, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        80% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        12% |         64% |        89% |         98% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        20% |         44% |        59% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          5% |        20% |
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
|             *[United States](/us)* |          121,225 |                   184,162 |                     555 |                     62,937 |                                       52% |                               154,563 |                                221,428 |
|                 [New York](/us-ny) |           31,232 |                    32,198 |                   1,655 |                        966 |                                        3% |                                31,300 |                                 34,231 |
|               [California](/us-ca) |            5,626 |                    14,675 |                     371 |                      9,049 |                                      161% |                                 7,461 |                                 23,784 |
|               [New Jersey](/us-nj) |           13,025 |                    14,056 |                   1,582 |                      1,031 |                                        8% |                                13,195 |                                 14,759 |
|                 [Illinois](/us-il) |            6,707 |                    10,348 |                     817 |                      3,641 |                                       54% |                                 7,895 |                                 12,787 |
|            [Massachusetts](/us-ma) |            7,889 |                     9,205 |                   1,325 |                      1,316 |                                       17% |                                 8,234 |                                 10,955 |
|                  [Florida](/us-fl) |            3,238 |                     9,074 |                     422 |                      5,836 |                                      180% |                                 5,283 |                                 13,752 |
|             [Pennsylvania](/us-pa) |            6,464 |                     8,408 |                     657 |                      1,944 |                                       30% |                                 6,779 |                                 11,883 |
|                    [Texas](/us-tx) |            2,236 |                     7,068 |                     244 |                      4,832 |                                      216% |                                 4,179 |                                 10,904 |
|                 [Michigan](/us-mi) |            6,109 |                     6,748 |                     676 |                        639 |                                       10% |                                 6,208 |                                  7,927 |
|                  [Georgia](/us-ga) |            2,695 |                     5,877 |                     554 |                      3,182 |                                      118% |                                 3,373 |                                  9,086 |
|                     [Ohio](/us-oh) |            2,735 |                     5,340 |                     457 |                      2,605 |                                       95% |                                 3,214 |                                  8,439 |
|              [Connecticut](/us-ct) |            4,277 |                     4,796 |                   1,345 |                        519 |                                       12% |                                 4,389 |                                  5,295 |
|                 [Maryland](/us-md) |            3,092 |                     4,687 |                     775 |                      1,595 |                                       52% |                                 3,444 |                                  6,157 |
|                  [Arizona](/us-az) |            1,396 |                     4,619 |                     635 |                      3,223 |                                      231% |                                 2,590 |                                  6,544 |
|                  [Indiana](/us-in) |            2,569 |                     4,367 |                     649 |                      1,798 |                                       70% |                                 2,822 |                                  7,283 |
|                [Louisiana](/us-la) |            3,134 |                     4,298 |                     925 |                      1,164 |                                       37% |                                 3,323 |                                  5,815 |
|           [North Carolina](/us-nc) |            1,296 |                     3,343 |                     319 |                      2,047 |                                      158% |                                 1,749 |                                  5,569 |
|                [Minnesota](/us-mn) |            1,425 |                     2,988 |                     530 |                      1,563 |                                      110% |                                 1,815 |                                  4,366 |
|                 [Virginia](/us-va) |            1,645 |                     2,745 |                     322 |                      1,100 |                                       67% |                                 1,797 |                                  4,400 |
|                 [Colorado](/us-co) |            1,665 |                     2,640 |                     458 |                        975 |                                       59% |                                 1,765 |                                  4,324 |
|               [Washington](/us-wa) |            1,284 |                     2,479 |                     326 |                      1,195 |                                       93% |                                 1,480 |                                  5,025 |
|                  [Alabama](/us-al) |              864 |                     2,440 |                     498 |                      1,576 |                                      182% |                                 1,243 |                                  3,818 |
|              [Mississippi](/us-ms) |              989 |                     2,100 |                     706 |                      1,111 |                                      112% |                                 1,202 |                                  3,348 |
|           [South Carolina](/us-sc) |              673 |                     2,048 |                     398 |                      1,375 |                                      204% |                                 1,050 |                                  3,135 |
|                 [Missouri](/us-mo) |              976 |                     1,755 |                     286 |                        779 |                                       80% |                                 1,097 |                                  3,093 |
|                [Wisconsin](/us-wi) |              750 |                     1,655 |                     284 |                        905 |                                      121% |                                   930 |                                  2,653 |
|                [Tennessee](/us-tn) |              542 |                     1,601 |                     234 |                      1,059 |                                      195% |                                   763 |                                  2,662 |
|             [Rhode Island](/us-ri) |              906 |                     1,402 |                   1,323 |                        496 |                                       55% |                                 1,045 |                                  1,798 |
|                 [Kentucky](/us-ky) |              537 |                     1,117 |                     250 |                        580 |                                      108% |                                   645 |                                  1,834 |
|                     [Iowa](/us-ia) |              689 |                     1,086 |                     344 |                        397 |                                       58% |                                   756 |                                  2,059 |
|                 [Arkansas](/us-ar) |              237 |                       960 |                     318 |                        723 |                                      305% |                                   525 |                                  1,436 |
|               [New Mexico](/us-nm) |              476 |                       956 |                     456 |                        480 |                                      101% |                                   570 |                                  1,547 |
|                   [Nevada](/us-nv) |              489 |                       932 |                     303 |                        443 |                                       91% |                                   570 |                                  1,578 |
|                 [Delaware](/us-de) |              504 |                       722 |                     741 |                        218 |                                       43% |                                   544 |                                  1,073 |
|                 [Nebraska](/us-ne) |              256 |                       713 |                     369 |                        457 |                                      179% |                                   391 |                                  1,195 |
|            [New Hampshire](/us-nh) |              343 |                       704 |                     518 |                        361 |                                      105% |                                   403 |                                  1,155 |
|     [District of Columbia](/us-dc) |              537 |                       696 |                     986 |                        159 |                                       30% |                                   569 |                                    896 |
|                 [Oklahoma](/us-ok) |              371 |                       625 |                     158 |                        254 |                                       68% |                                   425 |                                  1,120 |
|                     [Utah](/us-ut) |              163 |                       574 |                     179 |                        411 |                                      252% |                                   284 |                                    902 |
|                   [Kansas](/us-ks) |              260 |                       458 |                     157 |                        198 |                                       76% |                                   286 |                                    914 |
|                   [Oregon](/us-or) |              192 |                       432 |                     102 |                        240 |                                      125% |                                   235 |                                    738 |
|              [Puerto Rico](/us-pr) |              149 |                       202 |                      63 |                         53 |                                       36% |                                   161 |                                    306 |
|             [South Dakota](/us-sd) |               83 |                       198 |                     224 |                        115 |                                      139% |                                   101 |                                    394 |
|                    [Idaho](/us-id) |               89 |                       152 |                      85 |                         63 |                                       71% |                                    95 |                                    230 |
|                    [Maine](/us-me) |              102 |                       146 |                     109 |                         44 |                                       43% |                                   114 |                                    224 |
|            [West Virginia](/us-wv) |               92 |                       144 |                      80 |                         52 |                                       57% |                                   103 |                                    280 |
|             [North Dakota](/us-nd) |               78 |                       142 |                     186 |                         64 |                                       82% |                                    95 |                                    292 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    59 |                                    104 |
|                  [Wyoming](/us-wy) |               20 |                        54 |                      93 |                         34 |                                      170% |                                    25 |                                    121 |
|                  [Montana](/us-mt) |               21 |                        43 |                      40 |                         22 |                                      105% |                                    22 |                                     78 |
|                   [Alaska](/us-ak) |               12 |                        24 |                      33 |                         12 |                                      100% |                                    13 |                                     65 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    18 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     17 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     3 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          179,670 |                   200,522 |                     338 |                     20,852 |                                       12% |                               183,913 |                                229,684 |
| [United Kingdom](/united-kingdom) |           43,011 |                    47,507 |                     703 |                      4,496 |                                       10% |                                43,972 |                                 50,779 |
|                   [Italy](/italy) |           34,675 |                    36,979 |                     613 |                      2,304 |                                        7% |                                35,003 |                                 39,197 |
|                 [France](/france) |           29,723 |                    30,764 |                     459 |                      1,041 |                                        4% |                                29,762 |                                 34,958 |
|                   [Spain](/spain) |           28,325 |                    29,413 |                     627 |                      1,088 |                                        4% |                                28,384 |                                 32,023 |
|               [Germany](/germany) |            8,914 |                    10,589 |                     128 |                      1,675 |                                       19% |                                 9,043 |                                 14,184 |
|               [Belgium](/belgium) |            9,713 |                     9,962 |                     870 |                        249 |                                        3% |                                 9,737 |                                 10,551 |
|       [Netherlands](/netherlands) |            6,114 |                     6,633 |                     384 |                        519 |                                        8% |                                 6,171 |                                  7,639 |
|                 [Sweden](/sweden) |            5,161 |                     6,389 |                     625 |                      1,228 |                                       24% |                                 5,477 |                                  8,088 |
|               [Ukraine](/ukraine) |            1,045 |                     3,193 |                      73 |                      2,148 |                                      206% |                                 1,685 |                                  5,284 |
|                 [Poland](/poland) |            1,375 |                     3,055 |                      80 |                      1,680 |                                      122% |                                 1,799 |                                  4,651 |
|               [Romania](/romania) |            1,539 |                     2,607 |                     134 |                      1,068 |                                       69% |                                 1,784 |                                  3,994 |
|       [Switzerland](/switzerland) |            1,956 |                     2,053 |                     239 |                         97 |                                        5% |                                 1,970 |                                  2,327 |
|             [Portugal](/portugal) |            1,540 |                     1,881 |                     183 |                        341 |                                       22% |                                 1,619 |                                  2,491 |
|               [Ireland](/ireland) |            1,720 |                     1,816 |                     370 |                         96 |                                        6% |                                 1,731 |                                  2,187 |
|               [Moldova](/moldova) |              490 |                     1,635 |                     404 |                      1,145 |                                      234% |                                 1,002 |                                  2,372 |
|               [Belarus](/belarus) |              357 |                       813 |                      86 |                        456 |                                      128% |                                   475 |                                  1,806 |
|               [Hungary](/hungary) |              573 |                       776 |                      79 |                        203 |                                       35% |                                   599 |                                  1,168 |
|               [Austria](/austria) |              693 |                       747 |                      84 |                         54 |                                        8% |                                   707 |                                    896 |
|             [Bulgaria](/bulgaria) |              208 |                       682 |                      97 |                        474 |                                      228% |                                   349 |                                  1,117 |
|               [Denmark](/denmark) |              603 |                       680 |                     117 |                         77 |                                       13% |                                   623 |                                    851 |
|               [Czechia](/czechia) |              339 |                       428 |                      40 |                         89 |                                       26% |                                   349 |                                    556 |
|               [Finland](/finland) |              327 |                       368 |                      67 |                         41 |                                       13% |                                   332 |                                    470 |
|                 [Serbia](/serbia) |              263 |                       334 |                      48 |                         71 |                                       27% |                                   281 |                                    467 |
|                 [Norway](/norway) |              248 |                       272 |                      51 |                         24 |                                       10% |                                   255 |                                    315 |
|                 [Greece](/greece) |              190 |                       224 |                      21 |                         34 |                                       18% |                                   203 |                                    282 |
|               [Croatia](/croatia) |              107 |                       131 |                      32 |                         24 |                                       22% |                                   114 |                                    170 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    141 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   111 |                                    144 |
|           [Lithuania](/lithuania) |               77 |                       114 |                      41 |                         37 |                                       48% |                                    87 |                                    171 |
|               [Estonia](/estonia) |               69 |                        94 |                      71 |                         25 |                                       36% |                                    76 |                                    166 |
|                 [Latvia](/latvia) |               30 |                        55 |                      29 |                         25 |                                       83% |                                    33 |                                     90 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    28 |                                     70 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     45 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          169,054 |                   594,749 |                     115 |                    425,695 |                                      252% |                               340,246 |                              1,014,538 |
|                             [Brazil](/brazil) |           52,645 |                   138,129 |                     654 |                     85,484 |                                      162% |                               102,129 |                                221,509 |
|                               [India](/india) |           14,476 |                   113,612 |                      83 |                     99,136 |                                      685% |                                36,658 |                                249,461 |
|                             [Mexico](/mexico) |           23,377 |                   101,188 |                     793 |                     77,811 |                                      333% |                                62,459 |                                137,080 |
|                         [Pakistan](/pakistan) |            3,755 |                    27,569 |                     127 |                     23,814 |                                      634% |                                10,573 |                                 62,728 |
|                                 [Peru](/peru) |            8,404 |                    23,202 |                     714 |                     14,798 |                                      176% |                                15,183 |                                 35,297 |
|                         [Colombia](/colombia) |            2,524 |                    21,123 |                     420 |                     18,599 |                                      737% |                                11,127 |                                 29,758 |
|                             [Russia](/russia) |            8,349 |                    20,499 |                     141 |                     12,150 |                                      146% |                                11,947 |                                 36,945 |
|                                 [Iran](/iran) |            9,863 |                    18,809 |                     227 |                      8,946 |                                       91% |                                12,070 |                                 27,267 |
|                 [South Africa](/south-africa) |            2,102 |                    18,159 |                     310 |                     16,057 |                                      764% |                                 8,236 |                                 26,945 |
|                               [Chile](/chile) |            4,505 |                    17,159 |                     905 |                     12,654 |                                      281% |                                12,008 |                                 27,974 |
|                               [Egypt](/egypt) |            2,365 |                    12,458 |                     124 |                     10,093 |                                      427% |                                 6,808 |                                 20,343 |
|                             [Canada](/canada) |            8,512 |                    11,487 |                     307 |                      2,975 |                                       35% |                                 9,060 |                                 18,198 |
|                     [Bangladesh](/bangladesh) |            1,545 |                     9,705 |                      60 |                      8,160 |                                      528% |                                 4,560 |                                 17,600 |
|                 [Saudi Arabia](/saudi-arabia) |            1,346 |                     8,985 |                     262 |                      7,639 |                                      568% |                                 5,084 |                                 12,293 |
|                       [Indonesia](/indonesia) |            2,535 |                     7,955 |                      29 |                      5,420 |                                      214% |                                 3,981 |                                 13,841 |
|                             [Turkey](/turkey) |            5,001 |                     6,131 |                      73 |                      1,130 |                                       23% |                                 5,054 |                                  9,911 |
|                       [Argentina](/argentina) |            1,078 |                     6,118 |                     137 |                      5,040 |                                      468% |                                 2,348 |                                 12,337 |
|                           [Ecuador](/ecuador) |            4,274 |                     6,058 |                     349 |                      1,784 |                                       42% |                                 4,665 |                                 10,671 |
|                           [Bolivia](/bolivia) |              846 |                     5,874 |                     510 |                      5,028 |                                      594% |                                 2,765 |                                  9,716 |
|                               [China](/china) |            4,640 |                     4,650 |                       3 |                         10 |                                        0% |                                 4,640 |                                  4,705 |
|                           [Nigeria](/nigeria) |              533 |                     2,535 |                      13 |                      2,002 |                                      376% |                                   912 |                                  5,330 |
|                   [Philippines](/philippines) |            1,186 |                     2,375 |                      22 |                      1,189 |                                      100% |                                 1,281 |                                  4,337 |
|                           [Algeria](/algeria) |              861 |                     2,189 |                      51 |                      1,328 |                                      154% |                                 1,245 |                                  4,548 |
|                         [Honduras](/honduras) |              405 |                     1,867 |                     192 |                      1,462 |                                      361% |                                   931 |                                  3,149 |
|                             [Panama](/panama) |              536 |                     1,596 |                     376 |                      1,060 |                                      198% |                                   816 |                                  2,828 |
|     [Dominican Republic](/dominican-republic) |              675 |                     1,535 |                     143 |                        860 |                                      127% |                                   836 |                                  3,880 |
|                               [Japan](/japan) |              965 |                     1,291 |                      10 |                        326 |                                       34% |                                   971 |                                  1,868 |
|                             [Kuwait](/kuwait) |              334 |                       620 |                     147 |                        286 |                                       86% |                                   406 |                                  1,040 |
| [United Arab Emirates](/united-arab-emirates) |              305 |                       431 |                      44 |                        126 |                                       41% |                                   333 |                                    757 |
|                             [Israel](/israel) |              308 |                       390 |                      46 |                         82 |                                       27% |                                   324 |                                    617 |
|                   [South Korea](/south-korea) |              281 |                       340 |                       7 |                         59 |                                       21% |                                   284 |                                    536 |
|                         [Malaysia](/malaysia) |              121 |                       251 |                       8 |                        130 |                                      107% |                                   137 |                                    475 |
|                           [Morocco](/morocco) |              214 |                       244 |                       7 |                         30 |                                       14% |                                   222 |                                    313 |
|                       [Australia](/australia) |              103 |                       112 |                       4 |                          9 |                                        9% |                                   103 |                                    150 |
|                                 [Cuba](/cuba) |               85 |                       103 |                       9 |                         18 |                                       21% |                                    90 |                                    131 |
