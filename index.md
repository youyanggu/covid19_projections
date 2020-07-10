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

* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 10 (6pm ET):
<p align="center">
  Current Total: <b>133,287</b> deaths | Projected Total: <b>211,700 deaths by Nov 1, 2020</b> (Range: 171-277k) | 194,800 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.1%</b> | Total Infected: <b>6.9%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 9, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 20, 2020 |
|              150,000 |         Aug 4, 2020 |
|              175,000 |         Sep 3, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        29% |         94% |        99% |         99% |        99% |        >99% |       >99% |
|              175,000 |         <1% |        <1% |         <1% |        37% |         61% |        78% |         87% |        93% |
|              200,000 |         <1% |        <1% |         <1% |         2% |         14% |        29% |         40% |        51% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |          1% |         8% |         14% |        21% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |          5% |         9% |
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
|             *[United States](/us)* |          133,287 |                   211,736 |                     638 |                     78,449 |                                       59% |                               171,852 |                                276,756 |
|                 [New York](/us-ny) |           32,283 |                    33,616 |                   1,728 |                      1,333 |                                        4% |                                32,326 |                                 39,020 |
|               [California](/us-ca) |            6,859 |                    19,483 |                     493 |                     12,624 |                                      184% |                                 9,278 |                                 37,176 |
|               [New Jersey](/us-nj) |           15,448 |                    17,085 |                   1,924 |                      1,637 |                                       11% |                                15,860 |                                 19,188 |
|                  [Florida](/us-fl) |            4,009 |                    13,188 |                     614 |                      9,179 |                                      229% |                                 6,751 |                                 22,511 |
|                    [Texas](/us-tx) |            3,006 |                    12,149 |                     419 |                      9,143 |                                      304% |                                 7,297 |                                 21,678 |
|             [Pennsylvania](/us-pa) |            6,848 |                     9,285 |                     725 |                      2,437 |                                       36% |                                 7,076 |                                 15,065 |
|                 [Illinois](/us-il) |            7,329 |                     9,093 |                     718 |                      1,764 |                                       24% |                                 7,686 |                                 11,170 |
|            [Massachusetts](/us-ma) |            8,268 |                     9,045 |                   1,302 |                        777 |                                        9% |                                 8,412 |                                 10,655 |
|                 [Michigan](/us-mi) |            6,271 |                     7,818 |                     783 |                      1,547 |                                       25% |                                 6,338 |                                 12,132 |
|                  [Georgia](/us-ga) |            2,930 |                     7,041 |                     663 |                      4,111 |                                      140% |                                 3,800 |                                 13,779 |
|                  [Arizona](/us-az) |            2,038 |                     5,806 |                     798 |                      3,768 |                                      185% |                                 4,170 |                                  8,003 |
|                [Louisiana](/us-la) |            3,355 |                     5,512 |                   1,186 |                      2,157 |                                       64% |                                 3,665 |                                  7,734 |
|                     [Ohio](/us-oh) |            3,006 |                     5,505 |                     471 |                      2,499 |                                       83% |                                 3,277 |                                 11,343 |
|              [Connecticut](/us-ct) |            4,348 |                     4,586 |                   1,286 |                        238 |                                        5% |                                 4,383 |                                  5,016 |
|                 [Maryland](/us-md) |            3,288 |                     4,159 |                     688 |                        871 |                                       26% |                                 3,464 |                                  5,537 |
|                  [Indiana](/us-in) |            2,739 |                     4,097 |                     609 |                      1,358 |                                       50% |                                 2,846 |                                  7,725 |
|                 [Virginia](/us-va) |            1,937 |                     3,547 |                     416 |                      1,610 |                                       83% |                                 2,075 |                                  7,092 |
|                  [Alabama](/us-al) |            1,068 |                     3,381 |                     690 |                      2,313 |                                      217% |                                 1,845 |                                  5,656 |
|           [South Carolina](/us-sc) |              905 |                     3,329 |                     647 |                      2,424 |                                      268% |                                 2,148 |                                  5,283 |
|           [North Carolina](/us-nc) |            1,477 |                     2,938 |                     280 |                      1,461 |                                       99% |                                 1,733 |                                  6,548 |
|                [Tennessee](/us-tn) |              710 |                     2,826 |                     414 |                      2,116 |                                      298% |                                 1,678 |                                  5,419 |
|              [Mississippi](/us-ms) |            1,204 |                     2,772 |                     931 |                      1,568 |                                      130% |                                 1,639 |                                  4,364 |
|               [Washington](/us-wa) |            1,409 |                     2,573 |                     338 |                      1,164 |                                       83% |                                 1,602 |                                  5,219 |
|                 [Colorado](/us-co) |            1,706 |                     2,492 |                     433 |                        786 |                                       46% |                                 1,768 |                                  4,955 |
|                [Minnesota](/us-mn) |            1,528 |                     2,221 |                     394 |                        693 |                                       45% |                                 1,651 |                                  3,499 |
|                   [Nevada](/us-nv) |              571 |                     1,897 |                     616 |                      1,326 |                                      232% |                                   933 |                                  3,242 |
|                 [Missouri](/us-mo) |            1,073 |                     1,883 |                     307 |                        810 |                                       75% |                                 1,164 |                                  3,955 |
|                [Wisconsin](/us-wi) |              809 |                     1,608 |                     276 |                        799 |                                       99% |                                   933 |                                  4,126 |
|                 [Kentucky](/us-ky) |              612 |                     1,396 |                     312 |                        784 |                                      128% |                                   705 |                                  3,143 |
|             [Rhode Island](/us-ri) |              974 |                     1,218 |                   1,150 |                        244 |                                       25% |                                 1,032 |                                  1,504 |
|                 [Arkansas](/us-ar) |              309 |                     1,157 |                     383 |                        848 |                                      274% |                                   466 |                                  2,424 |
|               [New Mexico](/us-nm) |              533 |                     1,022 |                     487 |                        489 |                                       92% |                                   594 |                                  2,045 |
|                     [Iowa](/us-ia) |              741 |                       991 |                     314 |                        250 |                                       34% |                                   765 |                                  1,669 |
|                   [Oregon](/us-or) |              230 |                       860 |                     204 |                        630 |                                      274% |                                   295 |                                  2,105 |
|                     [Utah](/us-ut) |              205 |                       853 |                     266 |                        648 |                                      316% |                                   350 |                                  1,912 |
|                 [Oklahoma](/us-ok) |              410 |                       777 |                     196 |                        367 |                                       90% |                                   456 |                                  1,742 |
|     [District of Columbia](/us-dc) |              568 |                       708 |                   1,003 |                        140 |                                       25% |                                   590 |                                  1,040 |
|                 [Delaware](/us-de) |              517 |                       688 |                     707 |                        171 |                                       33% |                                   537 |                                  1,074 |
|            [New Hampshire](/us-nh) |              387 |                       594 |                     437 |                        207 |                                       53% |                                   421 |                                    957 |
|                   [Kansas](/us-ks) |              293 |                       505 |                     173 |                        212 |                                       72% |                                   313 |                                  1,114 |
|                 [Nebraska](/us-ne) |              284 |                       475 |                     246 |                        191 |                                       67% |                                   346 |                                    690 |
|                    [Idaho](/us-id) |              100 |                       342 |                     191 |                        242 |                                      242% |                                   126 |                                    784 |
|              [Puerto Rico](/us-pr) |              159 |                       248 |                      78 |                         89 |                                       56% |                                   168 |                                    552 |
|             [South Dakota](/us-sd) |              101 |                       194 |                     219 |                         93 |                                       92% |                                   125 |                                    310 |
|                    [Maine](/us-me) |              111 |                       181 |                     135 |                         70 |                                       63% |                                   120 |                                    383 |
|            [West Virginia](/us-wv) |               95 |                       129 |                      72 |                         34 |                                       36% |                                   101 |                                    219 |
|             [North Dakota](/us-nd) |               85 |                       128 |                     168 |                         43 |                                       51% |                                   100 |                                    187 |
|                  [Montana](/us-mt) |               25 |                        90 |                      84 |                         65 |                                      260% |                                    30 |                                    199 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    150 |
|                   [Alaska](/us-ak) |               17 |                        65 |                      89 |                         48 |                                      282% |                                    19 |                                    198 |
|                  [Wyoming](/us-wy) |               21 |                        43 |                      74 |                         22 |                                      105% |                                    27 |                                     79 |
|                   [Hawaii](/us-hi) |               19 |                        31 |                      22 |                         12 |                                       63% |                                    21 |                                     64 |
|           [Virgin Islands](/us-vi) |                6 |                        14 |                     133 |                          8 |                                      133% |                                     6 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     5 |                                     24 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          183,868 |                   201,785 |                     340 |                     17,917 |                                       10% |                               187,971 |                                226,912 |
| [United Kingdom](/united-kingdom) |           44,687 |                    49,230 |                     729 |                      4,543 |                                       10% |                                45,321 |                                 53,689 |
|                   [Italy](/italy) |           34,926 |                    35,737 |                     592 |                        811 |                                        2% |                                35,035 |                                 36,588 |
|                 [France](/france) |           29,982 |                    30,717 |                     458 |                        735 |                                        2% |                                30,007 |                                 34,118 |
|                   [Spain](/spain) |           28,401 |                    29,015 |                     618 |                        614 |                                        2% |                                28,437 |                                 30,894 |
|               [Belgium](/belgium) |            9,778 |                    10,047 |                     877 |                        269 |                                        3% |                                 9,800 |                                 10,851 |
|               [Germany](/germany) |            9,057 |                     9,488 |                     114 |                        431 |                                        5% |                                 9,103 |                                 10,507 |
|       [Netherlands](/netherlands) |            6,156 |                     6,313 |                     365 |                        157 |                                        3% |                                 6,178 |                                  6,508 |
|                 [Sweden](/sweden) |            5,500 |                     6,006 |                     587 |                        506 |                                        9% |                                 5,671 |                                  6,212 |
|               [Romania](/romania) |            1,834 |                     4,279 |                     220 |                      2,445 |                                      133% |                                 2,735 |                                  5,998 |
|               [Ukraine](/ukraine) |            1,344 |                     3,199 |                      73 |                      1,855 |                                      138% |                                 2,022 |                                  4,831 |
|                 [Poland](/poland) |            1,551 |                     2,919 |                      77 |                      1,368 |                                       88% |                                 1,885 |                                  5,232 |
|             [Portugal](/portugal) |            1,644 |                     2,330 |                     227 |                        686 |                                       42% |                                 1,747 |                                  3,400 |
|       [Switzerland](/switzerland) |            1,966 |                     2,070 |                     241 |                        104 |                                        5% |                                 1,979 |                                  2,485 |
|               [Ireland](/ireland) |            1,743 |                     1,837 |                     375 |                         94 |                                        5% |                                 1,751 |                                  2,267 |
|               [Moldova](/moldova) |              624 |                     1,367 |                     338 |                        743 |                                      119% |                                 1,046 |                                  1,989 |
|               [Belarus](/belarus) |              449 |                     1,164 |                     123 |                        715 |                                      159% |                                   614 |                                  2,403 |
|             [Bulgaria](/bulgaria) |              262 |                       910 |                     130 |                        648 |                                      247% |                                   466 |                                  1,534 |
|               [Austria](/austria) |              706 |                       834 |                      94 |                        128 |                                       18% |                                   722 |                                  1,072 |
|               [Hungary](/hungary) |              591 |                       723 |                      74 |                        132 |                                       22% |                                   607 |                                  1,111 |
|                 [Serbia](/serbia) |              352 |                       722 |                     104 |                        370 |                                      105% |                                   440 |                                  1,229 |
|               [Denmark](/denmark) |              609 |                       688 |                     118 |                         79 |                                       13% |                                   625 |                                    897 |
|               [Czechia](/czechia) |              352 |                       492 |                      46 |                        140 |                                       40% |                                   361 |                                    725 |
|               [Finland](/finland) |              329 |                       376 |                      68 |                         47 |                                       14% |                                   335 |                                    531 |
|                 [Norway](/norway) |              252 |                       276 |                      51 |                         24 |                                       10% |                                   259 |                                    322 |
|               [Croatia](/croatia) |              115 |                       233 |                      57 |                        118 |                                      103% |                                   130 |                                    369 |
|                 [Greece](/greece) |              193 |                       227 |                      21 |                         34 |                                       18% |                                   205 |                                    293 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    163 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    146 |
|           [Lithuania](/lithuania) |               79 |                       115 |                      41 |                         36 |                                       46% |                                    87 |                                    184 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    76 |                                    117 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        39 |                      20 |                          9 |                                       30% |                                    32 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        32 |                      37 |                         13 |                                       68% |                                    21 |                                     68 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     27 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          225,637 |                   604,932 |                     117 |                    379,295 |                                      168% |                               382,072 |                              1,015,212 |
|                             [Brazil](/brazil) |           69,184 |                   146,578 |                     695 |                     77,394 |                                      112% |                               111,350 |                                226,516 |
|                               [India](/india) |           21,604 |                   115,345 |                      84 |                     93,741 |                                      434% |                                46,644 |                                258,064 |
|                             [Mexico](/mexico) |           33,526 |                    87,731 |                     688 |                     54,205 |                                      162% |                                64,617 |                                110,010 |
|                                 [Iran](/iran) |           12,305 |                    26,187 |                     316 |                     13,882 |                                      113% |                                20,174 |                                 40,891 |
|                                 [Peru](/peru) |           11,314 |                    23,293 |                     716 |                     11,979 |                                      106% |                                16,772 |                                 32,655 |
|                             [Russia](/russia) |           10,826 |                    23,076 |                     158 |                     12,250 |                                      113% |                                14,134 |                                 44,203 |
|                         [Colombia](/colombia) |            4,791 |                    20,659 |                     410 |                     15,868 |                                      331% |                                13,023 |                                 32,134 |
|                 [South Africa](/south-africa) |            3,720 |                    18,773 |                     321 |                     15,053 |                                      405% |                                 9,777 |                                 30,166 |
|                               [Egypt](/egypt) |            3,617 |                    14,541 |                     145 |                     10,924 |                                      302% |                                 8,451 |                                 22,476 |
|                       [Indonesia](/indonesia) |            3,417 |                    13,446 |                      50 |                     10,029 |                                      294% |                                 6,132 |                                 25,685 |
|                         [Pakistan](/pakistan) |            5,058 |                    12,954 |                      60 |                      7,896 |                                      156% |                                 7,953 |                                 20,783 |
|                               [Chile](/chile) |            6,682 |                    12,294 |                     649 |                      5,612 |                                       84% |                                 7,815 |                                 16,857 |
|                       [Argentina](/argentina) |            1,720 |                    11,477 |                     256 |                      9,757 |                                      567% |                                 4,423 |                                 20,176 |
|                             [Canada](/canada) |            8,797 |                    10,295 |                     275 |                      1,498 |                                       17% |                                 9,005 |                                 13,650 |
|                           [Ecuador](/ecuador) |            4,900 |                     8,780 |                     505 |                      3,880 |                                       79% |                                 5,311 |                                 14,271 |
|                 [Saudi Arabia](/saudi-arabia) |            2,100 |                     8,729 |                     255 |                      6,629 |                                      316% |                                 5,106 |                                 12,618 |
|                     [Bangladesh](/bangladesh) |            2,238 |                     7,721 |                      47 |                      5,483 |                                      245% |                                 4,764 |                                 14,218 |
|                             [Turkey](/turkey) |            5,300 |                     7,012 |                      84 |                      1,712 |                                       32% |                                 5,415 |                                 12,256 |
|                           [Bolivia](/bolivia) |            1,638 |                     6,859 |                     596 |                      5,221 |                                      319% |                                 3,529 |                                 12,123 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,677 |
|                         [Honduras](/honduras) |              704 |                     3,980 |                     408 |                      3,276 |                                      465% |                                 2,443 |                                  6,991 |
|     [Dominican Republic](/dominican-republic) |              842 |                     3,898 |                     363 |                      3,056 |                                      363% |                                 1,318 |                                  8,453 |
|                             [Panama](/panama) |              839 |                     3,403 |                     801 |                      2,564 |                                      306% |                                 2,402 |                                  5,473 |
|                   [Philippines](/philippines) |            1,314 |                     3,070 |                      28 |                      1,756 |                                      134% |                                 1,470 |                                  6,783 |
|                           [Algeria](/algeria) |              988 |                     2,980 |                      69 |                      1,992 |                                      202% |                                 1,376 |                                  7,568 |
|                           [Nigeria](/nigeria) |              689 |                     2,112 |                      11 |                      1,423 |                                      207% |                                   949 |                                  4,809 |
|                               [Japan](/japan) |              982 |                     1,562 |                      12 |                        580 |                                       59% |                                   989 |                                  2,762 |
|                             [Israel](/israel) |              348 |                     1,085 |                     127 |                        737 |                                      212% |                                   416 |                                  3,482 |
|                             [Kuwait](/kuwait) |              382 |                       722 |                     172 |                        340 |                                       89% |                                   429 |                                  1,395 |
|                           [Morocco](/morocco) |              242 |                       484 |                      13 |                        242 |                                      100% |                                   273 |                                    963 |
| [United Arab Emirates](/united-arab-emirates) |              328 |                       476 |                      49 |                        148 |                                       45% |                                   347 |                                    905 |
|                   [South Korea](/south-korea) |              288 |                       343 |                       7 |                         55 |                                       19% |                                   290 |                                    488 |
|                       [Australia](/australia) |              106 |                       158 |                       6 |                         52 |                                       49% |                                   106 |                                    378 |
|                         [Malaysia](/malaysia) |              121 |                       157 |                       5 |                         36 |                                       30% |                                   137 |                                    188 |
|                                 [Cuba](/cuba) |               86 |                       105 |                       9 |                         19 |                                       22% |                                    91 |                                    145 |
