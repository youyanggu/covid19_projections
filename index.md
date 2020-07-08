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

* **July 8:** We have extended our projections to November 1, 2020.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: July 8 (3am ET):
<p align="center">
  Current Total: <b>131,477</b> deaths | Projected Total: <b>203,500 deaths by Nov 1, 2020</b> (Range: 164-270k) | 187,700 deaths by Oct 1, 2020 (Range: 158-235k)<br>
  Currently Infected: <b>0.9%</b> | Total Infected: <b>6.3%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 8, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 23, 2020 |
|              150,000 |         Aug 7, 2020 |
|              175,000 |        Sep 11, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        13% |         74% |        99% |         99% |        99% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        22% |         43% |        58% |         68% |        78% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          9% |        20% |         29% |        38% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         6% |         10% |        16% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |          3% |         7% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          131,477 |                   203,470 |                     613 |                     71,993 |                                       55% |                               164,826 |                                269,611 |
|                 [New York](/us-ny) |           32,243 |                    33,658 |                   1,730 |                      1,415 |                                        4% |                                32,294 |                                 39,178 |
|               [California](/us-ca) |            6,573 |                    17,644 |                     447 |                     11,071 |                                      168% |                                 9,273 |                                 36,060 |
|               [New Jersey](/us-nj) |           15,281 |                    16,722 |                   1,883 |                      1,441 |                                        9% |                                15,422 |                                 18,974 |
|                  [Florida](/us-fl) |            3,841 |                    11,573 |                     539 |                      7,732 |                                      201% |                                 5,528 |                                 20,842 |
|                    [Texas](/us-tx) |            2,778 |                    10,130 |                     349 |                      7,352 |                                      265% |                                 5,326 |                                 19,169 |
|                 [Illinois](/us-il) |            7,273 |                     9,114 |                     719 |                      1,841 |                                       25% |                                 7,679 |                                 11,249 |
|            [Massachusetts](/us-ma) |            8,213 |                     9,013 |                   1,297 |                        800 |                                       10% |                                 8,378 |                                 10,635 |
|             [Pennsylvania](/us-pa) |            6,787 |                     8,932 |                     698 |                      2,145 |                                       32% |                                 7,002 |                                 14,238 |
|                 [Michigan](/us-mi) |            6,251 |                     7,795 |                     781 |                      1,544 |                                       25% |                                 6,326 |                                 12,121 |
|                  [Georgia](/us-ga) |            2,899 |                     6,847 |                     645 |                      3,948 |                                      136% |                                 3,760 |                                 13,062 |
|                  [Arizona](/us-az) |            1,927 |                     6,268 |                     861 |                      4,341 |                                      225% |                                 4,027 |                                  9,970 |
|                     [Ohio](/us-oh) |            2,970 |                     5,415 |                     463 |                      2,445 |                                       82% |                                 3,256 |                                 11,349 |
|                [Louisiana](/us-la) |            3,319 |                     5,102 |                   1,097 |                      1,783 |                                       54% |                                 3,525 |                                  7,419 |
|              [Connecticut](/us-ct) |            4,338 |                     4,598 |                   1,290 |                        260 |                                        6% |                                 4,379 |                                  5,051 |
|                 [Maryland](/us-md) |            3,266 |                     4,180 |                     691 |                        914 |                                       28% |                                 3,459 |                                  5,585 |
|                  [Indiana](/us-in) |            2,717 |                     4,034 |                     599 |                      1,317 |                                       48% |                                 2,835 |                                  7,696 |
|                 [Virginia](/us-va) |            1,881 |                     3,442 |                     403 |                      1,561 |                                       83% |                                 2,025 |                                  7,053 |
|                  [Alabama](/us-al) |            1,033 |                     3,073 |                     627 |                      2,040 |                                      197% |                                 1,529 |                                  5,329 |
|           [South Carolina](/us-sc) |              846 |                     2,910 |                     565 |                      2,064 |                                      244% |                                 1,511 |                                  4,825 |
|                [Minnesota](/us-mn) |            1,514 |                     2,758 |                     489 |                      1,244 |                                       82% |                                 1,662 |                                  5,644 |
|           [North Carolina](/us-nc) |            1,446 |                     2,725 |                     260 |                      1,279 |                                       88% |                                 1,688 |                                  6,250 |
|                [Tennessee](/us-tn) |              665 |                     2,541 |                     372 |                      1,876 |                                      282% |                                 1,164 |                                  5,222 |
|              [Mississippi](/us-ms) |            1,158 |                     2,532 |                     851 |                      1,374 |                                      119% |                                 1,464 |                                  4,199 |
|               [Washington](/us-wa) |            1,384 |                     2,481 |                     326 |                      1,097 |                                       79% |                                 1,563 |                                  5,157 |
|                 [Colorado](/us-co) |            1,696 |                     2,474 |                     430 |                        778 |                                       46% |                                 1,759 |                                  4,964 |
|                 [Missouri](/us-mo) |            1,067 |                     1,834 |                     299 |                        767 |                                       72% |                                 1,162 |                                  3,675 |
|                   [Nevada](/us-nv) |              548 |                     1,654 |                     537 |                      1,106 |                                      202% |                                   864 |                                  3,058 |
|                [Wisconsin](/us-wi) |              805 |                     1,647 |                     283 |                        842 |                                      105% |                                   936 |                                  4,246 |
|                 [Kentucky](/us-ky) |              602 |                     1,314 |                     294 |                        712 |                                      118% |                                   693 |                                  3,093 |
|             [Rhode Island](/us-ri) |              969 |                     1,221 |                   1,153 |                        252 |                                       26% |                                 1,033 |                                  1,521 |
|                 [Arkansas](/us-ar) |              301 |                     1,141 |                     378 |                        840 |                                      279% |                                   455 |                                  2,387 |
|                     [Iowa](/us-ia) |              732 |                       984 |                     312 |                        252 |                                       34% |                                   758 |                                  1,670 |
|               [New Mexico](/us-nm) |              519 |                       972 |                     464 |                        453 |                                       87% |                                   579 |                                  2,011 |
|                   [Oregon](/us-or) |              220 |                       742 |                     176 |                        522 |                                      237% |                                   279 |                                  1,803 |
|                 [Oklahoma](/us-ok) |              404 |                       724 |                     183 |                        320 |                                       79% |                                   440 |                                  1,677 |
|                     [Utah](/us-ut) |              194 |                       713 |                     222 |                        519 |                                      268% |                                   259 |                                  1,704 |
|            [New Hampshire](/us-nh) |              384 |                       706 |                     519 |                        322 |                                       84% |                                   424 |                                  1,417 |
|     [District of Columbia](/us-dc) |              561 |                       700 |                     992 |                        139 |                                       25% |                                   582 |                                  1,038 |
|                 [Delaware](/us-de) |              514 |                       679 |                     697 |                        165 |                                       32% |                                   535 |                                  1,058 |
|                 [Nebraska](/us-ne) |              282 |                       507 |                     262 |                        225 |                                       80% |                                   338 |                                    814 |
|                   [Kansas](/us-ks) |              289 |                       486 |                     167 |                        197 |                                       68% |                                   309 |                                  1,071 |
|                    [Idaho](/us-id) |               94 |                       261 |                     146 |                        167 |                                      178% |                                   120 |                                    557 |
|              [Puerto Rico](/us-pr) |              157 |                       245 |                      77 |                         88 |                                       56% |                                   166 |                                    541 |
|             [South Dakota](/us-sd) |               98 |                       216 |                     244 |                        118 |                                      120% |                                   120 |                                    392 |
|                    [Maine](/us-me) |              110 |                       177 |                     132 |                         67 |                                       61% |                                   120 |                                    376 |
|             [North Dakota](/us-nd) |               84 |                       133 |                     175 |                         49 |                                       58% |                                    99 |                                    221 |
|            [West Virginia](/us-wv) |               95 |                       127 |                      71 |                         32 |                                       34% |                                   101 |                                    204 |
|                  [Vermont](/us-vt) |               56 |                        89 |                     143 |                         33 |                                       59% |                                    58 |                                    162 |
|                   [Alaska](/us-ak) |               17 |                        73 |                     100 |                         56 |                                      329% |                                    20 |                                    206 |
|                  [Montana](/us-mt) |               23 |                        62 |                      58 |                         39 |                                      170% |                                    26 |                                    148 |
|                  [Wyoming](/us-wy) |               21 |                        45 |                      78 |                         24 |                                      114% |                                    27 |                                     88 |
|                   [Hawaii](/us-hi) |               19 |                        32 |                      23 |                         13 |                                       68% |                                    21 |                                     65 |
|           [Virgin Islands](/us-vi) |                6 |                        14 |                     133 |                          8 |                                      133% |                                     6 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     5 |                                     24 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          183,299 |                   201,747 |                     340 |                     18,448 |                                       10% |                               187,649 |                                228,690 |
| [United Kingdom](/united-kingdom) |           44,476 |                    49,110 |                     727 |                      4,634 |                                       10% |                                45,154 |                                 53,676 |
|                   [Italy](/italy) |           34,899 |                    35,750 |                     592 |                        851 |                                        2% |                                35,015 |                                 36,614 |
|                 [France](/france) |           29,936 |                    30,691 |                     458 |                        755 |                                        3% |                                29,963 |                                 34,199 |
|                   [Spain](/spain) |           28,392 |                    29,029 |                     618 |                        637 |                                        2% |                                28,431 |                                 30,959 |
|               [Belgium](/belgium) |            9,774 |                    10,053 |                     878 |                        279 |                                        3% |                                 9,797 |                                 10,875 |
|               [Germany](/germany) |            9,032 |                     9,472 |                     114 |                        440 |                                        5% |                                 9,077 |                                 10,519 |
|                 [Sweden](/sweden) |            5,447 |                     6,339 |                     620 |                        892 |                                       16% |                                 5,799 |                                  7,644 |
|       [Netherlands](/netherlands) |            6,151 |                     6,313 |                     365 |                        162 |                                        3% |                                 6,174 |                                  6,511 |
|               [Romania](/romania) |            1,799 |                     4,378 |                     226 |                      2,579 |                                      143% |                                 2,739 |                                  6,200 |
|               [Ukraine](/ukraine) |            1,299 |                     3,022 |                      69 |                      1,723 |                                      133% |                                 1,974 |                                  4,757 |
|                 [Poland](/poland) |            1,528 |                     2,922 |                      77 |                      1,394 |                                       91% |                                 1,870 |                                  5,295 |
|             [Portugal](/portugal) |            1,629 |                     2,268 |                     221 |                        639 |                                       39% |                                 1,703 |                                  3,350 |
|       [Switzerland](/switzerland) |            1,966 |                     2,073 |                     241 |                        107 |                                        5% |                                 1,980 |                                  2,494 |
|               [Ireland](/ireland) |            1,742 |                     1,839 |                     375 |                         97 |                                        6% |                                 1,750 |                                  2,282 |
|               [Moldova](/moldova) |              603 |                     1,328 |                     328 |                        725 |                                      120% |                                 1,024 |                                  1,947 |
|               [Belarus](/belarus) |              436 |                     1,143 |                     121 |                        707 |                                      162% |                                   601 |                                  2,399 |
|             [Bulgaria](/bulgaria) |              254 |                       905 |                     129 |                        651 |                                      256% |                                   459 |                                  1,520 |
|               [Austria](/austria) |              706 |                       839 |                      95 |                        133 |                                       19% |                                   723 |                                  1,091 |
|               [Hungary](/hungary) |              589 |                       728 |                      74 |                        139 |                                       24% |                                   606 |                                  1,131 |
|               [Denmark](/denmark) |              609 |                       691 |                     119 |                         82 |                                       13% |                                   626 |                                    907 |
|                 [Serbia](/serbia) |              330 |                       676 |                      97 |                        346 |                                      105% |                                   408 |                                  1,154 |
|               [Czechia](/czechia) |              351 |                       491 |                      46 |                        140 |                                       40% |                                   360 |                                    729 |
|               [Finland](/finland) |              329 |                       377 |                      68 |                         48 |                                       15% |                                   335 |                                    534 |
|                 [Norway](/norway) |              251 |                       275 |                      51 |                         24 |                                       10% |                                   258 |                                    322 |
|                 [Greece](/greece) |              193 |                       229 |                      21 |                         36 |                                       19% |                                   205 |                                    296 |
|               [Croatia](/croatia) |              113 |                       211 |                      52 |                         98 |                                       87% |                                   127 |                                    339 |
|             [Slovenia](/slovenia) |              111 |                       125 |                      60 |                         14 |                                       13% |                                   113 |                                    165 |
|         [Luxembourg](/luxembourg) |              110 |                       121 |                     197 |                         11 |                                       10% |                                   112 |                                    147 |
|           [Lithuania](/lithuania) |               79 |                       118 |                      42 |                         39 |                                       49% |                                    88 |                                    189 |
|               [Estonia](/estonia) |               69 |                        92 |                      69 |                         23 |                                       33% |                                    76 |                                    181 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        39 |                      20 |                          9 |                                       30% |                                    32 |                                     72 |
|                 [Cyprus](/cyprus) |               19 |                        33 |                      38 |                         14 |                                       74% |                                    21 |                                     70 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     27 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          217,854 |                   598,856 |                     115 |                    381,002 |                                      175% |                               375,975 |                              1,026,734 |
|                             [Brazil](/brazil) |           66,741 |                   138,779 |                     658 |                     72,038 |                                      108% |                               107,260 |                                212,450 |
|                               [India](/india) |           20,642 |                   118,446 |                      87 |                     97,804 |                                      474% |                                46,032 |                                282,624 |
|                             [Mexico](/mexico) |           32,014 |                    85,305 |                     669 |                     53,291 |                                      166% |                                62,732 |                                105,871 |
|                                 [Iran](/iran) |           11,931 |                    25,677 |                     310 |                     13,746 |                                      115% |                                19,609 |                                 40,254 |
|                                 [Peru](/peru) |           10,952 |                    23,337 |                     718 |                     12,385 |                                      113% |                                16,551 |                                 33,219 |
|                             [Russia](/russia) |           10,478 |                    22,731 |                     156 |                     12,253 |                                      117% |                                13,690 |                                 44,971 |
|                         [Colombia](/colombia) |            4,452 |                    20,180 |                     401 |                     15,728 |                                      353% |                                12,322 |                                 31,415 |
|                 [South Africa](/south-africa) |            3,502 |                    19,653 |                     336 |                     16,151 |                                      461% |                                12,413 |                                 32,300 |
|                               [Egypt](/egypt) |            3,489 |                    14,869 |                     148 |                     11,380 |                                      326% |                                 8,593 |                                 22,906 |
|                         [Pakistan](/pakistan) |            4,922 |                    13,458 |                      62 |                      8,536 |                                      173% |                                 8,179 |                                 21,280 |
|                       [Indonesia](/indonesia) |            3,309 |                    13,212 |                      49 |                      9,903 |                                      299% |                                 6,015 |                                 25,151 |
|                               [Chile](/chile) |            6,434 |                    12,179 |                     643 |                      5,745 |                                       89% |                                 7,608 |                                 16,962 |
|                       [Argentina](/argentina) |            1,644 |                    11,531 |                     257 |                      9,887 |                                      601% |                                 4,382 |                                 20,212 |
|                             [Canada](/canada) |            8,765 |                    10,300 |                     275 |                      1,535 |                                       18% |                                 8,984 |                                 13,710 |
|                           [Ecuador](/ecuador) |            4,873 |                     9,049 |                     521 |                      4,176 |                                       86% |                                 5,344 |                                 14,924 |
|                 [Saudi Arabia](/saudi-arabia) |            2,017 |                     8,818 |                     257 |                      6,801 |                                      337% |                                 5,112 |                                 12,673 |
|                     [Bangladesh](/bangladesh) |            2,151 |                     8,307 |                      51 |                      6,156 |                                      286% |                                 4,809 |                                 16,447 |
|                             [Turkey](/turkey) |            5,260 |                     6,947 |                      83 |                      1,687 |                                       32% |                                 5,346 |                                 12,312 |
|                           [Bolivia](/bolivia) |            1,530 |                     6,797 |                     590 |                      5,267 |                                      344% |                                 3,379 |                                 12,184 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,678 |
|                         [Honduras](/honduras) |              677 |                     4,095 |                     420 |                      3,418 |                                      505% |                                 2,597 |                                  7,149 |
|     [Dominican Republic](/dominican-republic) |              821 |                     3,980 |                     371 |                      3,159 |                                      385% |                                 1,171 |                                  8,677 |
|                             [Panama](/panama) |              799 |                     3,371 |                     794 |                      2,572 |                                      322% |                                 2,377 |                                  5,443 |
|                   [Philippines](/philippines) |            1,309 |                     3,163 |                      29 |                      1,854 |                                      142% |                                 1,471 |                                  6,941 |
|                           [Algeria](/algeria) |              968 |                     2,948 |                      68 |                      1,980 |                                      205% |                                 1,362 |                                  7,545 |
|                           [Nigeria](/nigeria) |              669 |                     2,219 |                      11 |                      1,550 |                                      232% |                                   941 |                                  5,337 |
|                               [Japan](/japan) |              981 |                     1,580 |                      12 |                        599 |                                       61% |                                   988 |                                  2,775 |
|                             [Israel](/israel) |              342 |                       789 |                      93 |                        447 |                                      131% |                                   409 |                                  1,328 |
|                             [Kuwait](/kuwait) |              377 |                       729 |                     173 |                        352 |                                       93% |                                   426 |                                  1,425 |
|                           [Morocco](/morocco) |              240 |                       482 |                      13 |                        242 |                                      101% |                                   266 |                                    964 |
| [United Arab Emirates](/united-arab-emirates) |              326 |                       477 |                      49 |                        151 |                                       46% |                                   346 |                                    912 |
|                   [South Korea](/south-korea) |              285 |                       335 |                       7 |                         50 |                                       18% |                                   286 |                                    476 |
|                       [Australia](/australia) |              106 |                       202 |                       8 |                         96 |                                       91% |                                   106 |                                    883 |
|                         [Malaysia](/malaysia) |              121 |                       158 |                       5 |                         37 |                                       31% |                                   137 |                                    190 |
|                                 [Cuba](/cuba) |               86 |                       106 |                       9 |                         20 |                                       23% |                                    91 |                                    146 |
