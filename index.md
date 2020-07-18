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
* **July 13:** View our [updated historical performance](/about/#historical-performance) (commentary [on Twitter](https://twitter.com/youyanggu/status/1283102532236181504)).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 18 (2pm ET):
<p align="center">
  Current Total: <b>139,263</b> deaths | Projected Total: <b>213,200 deaths by Nov 1, 2020</b> (Range: 178-276k)<br>
  Currently Infected: <b>1.4%</b> | Total Infected: <b>8.2%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 18, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 19, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |         Sep 3, 2020 |
|              200,000 |        Oct 27, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        61% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          6% |        47% |         73% |        91% |         98% |        99% |
|              200,000 |        <1% |         <1% |         6% |         17% |        31% |         43% |        53% |
|              225,000 |        <1% |         <1% |        <1% |          4% |         9% |         13% |        20% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         2% |          5% |         8% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          1% |         3% |
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
|             *[United States](/us)* |          139,263 |                   213,158 |                     642 |                     73,895 |                                       53% |                               178,858 |                                275,311 |
|                 [New York](/us-ny) |           32,463 |                    33,756 |                   1,735 |                      1,293 |                                        4% |                                32,512 |                                 38,386 |
|               [New Jersey](/us-nj) |           15,684 |                    16,854 |                   1,898 |                      1,170 |                                        7% |                                15,740 |                                 18,802 |
|               [California](/us-ca) |            7,603 |                    16,327 |                     413 |                      8,724 |                                      115% |                                 9,863 |                                 25,508 |
|                  [Florida](/us-fl) |            4,805 |                    15,204 |                     708 |                     10,399 |                                      216% |                                 9,235 |                                 28,594 |
|                    [Texas](/us-tx) |            3,820 |                    13,390 |                     462 |                      9,570 |                                      251% |                                 9,459 |                                 26,425 |
|            [Massachusetts](/us-ma) |            8,402 |                     9,117 |                   1,312 |                        715 |                                        9% |                                 8,520 |                                 10,536 |
|             [Pennsylvania](/us-pa) |            7,004 |                     8,955 |                     700 |                      1,951 |                                       28% |                                 7,186 |                                 13,244 |
|                 [Illinois](/us-il) |            7,465 |                     8,594 |                     678 |                      1,129 |                                       15% |                                 7,638 |                                  9,928 |
|                 [Michigan](/us-mi) |            6,355 |                     7,805 |                     782 |                      1,450 |                                       23% |                                 6,453 |                                 11,575 |
|                  [Arizona](/us-az) |            2,583 |                     6,177 |                     849 |                      3,594 |                                      139% |                                 4,629 |                                  9,461 |
|                [Louisiana](/us-la) |            3,509 |                     6,073 |                   1,306 |                      2,564 |                                       73% |                                 3,949 |                                  8,627 |
|                  [Georgia](/us-ga) |            3,132 |                     6,072 |                     572 |                      2,940 |                                       94% |                                 3,868 |                                 10,161 |
|                     [Ohio](/us-oh) |            3,112 |                     5,872 |                     502 |                      2,760 |                                       89% |                                 3,339 |                                 14,608 |
|              [Connecticut](/us-ct) |            4,396 |                     4,523 |                   1,269 |                        127 |                                        3% |                                 4,415 |                                  4,688 |
|                 [Maryland](/us-md) |            3,359 |                     4,091 |                     677 |                        732 |                                       22% |                                 3,493 |                                  5,279 |
|                  [Alabama](/us-al) |            1,265 |                     4,000 |                     816 |                      2,735 |                                      216% |                                 2,555 |                                  6,031 |
|                  [Indiana](/us-in) |            2,803 |                     3,954 |                     587 |                      1,151 |                                       41% |                                 2,925 |                                  7,049 |
|                 [Virginia](/us-va) |            2,013 |                     3,460 |                     405 |                      1,447 |                                       72% |                                 2,146 |                                  6,350 |
|           [North Carolina](/us-nc) |            1,623 |                     3,397 |                     324 |                      1,774 |                                      109% |                                 2,204 |                                  6,264 |
|           [South Carolina](/us-sc) |            1,096 |                     3,148 |                     611 |                      2,052 |                                      187% |                                 2,104 |                                  5,023 |
|              [Mississippi](/us-ms) |            1,332 |                     2,838 |                     954 |                      1,506 |                                      113% |                                 1,763 |                                  4,831 |
|                [Tennessee](/us-tn) |              815 |                     2,729 |                     399 |                      1,914 |                                      235% |                                 1,748 |                                  5,056 |
|                [Minnesota](/us-mn) |            1,573 |                     2,648 |                     470 |                      1,075 |                                       68% |                                 1,687 |                                  5,290 |
|                 [Colorado](/us-co) |            1,751 |                     2,571 |                     446 |                        820 |                                       47% |                                 1,856 |                                  4,705 |
|               [Washington](/us-wa) |            1,434 |                     2,212 |                     290 |                        778 |                                       54% |                                 1,509 |                                  4,247 |
|                 [Missouri](/us-mo) |            1,125 |                     2,027 |                     330 |                        902 |                                       80% |                                 1,245 |                                  4,252 |
|                   [Nevada](/us-nv) |              637 |                     1,956 |                     635 |                      1,319 |                                      207% |                                 1,146 |                                  3,080 |
|                 [Kentucky](/us-ky) |              658 |                     1,836 |                     411 |                      1,178 |                                      179% |                                   876 |                                  3,923 |
|                [Wisconsin](/us-wi) |              833 |                     1,631 |                     280 |                        798 |                                       96% |                                   938 |                                  3,946 |
|                     [Iowa](/us-ia) |              785 |                     1,224 |                     388 |                        439 |                                       56% |                                   819 |                                  2,233 |
|             [Rhode Island](/us-ri) |              990 |                     1,126 |                   1,063 |                        136 |                                       14% |                                 1,010 |                                  1,286 |
|               [New Mexico](/us-nm) |              565 |                     1,030 |                     491 |                        465 |                                       82% |                                   628 |                                  1,976 |
|                 [Arkansas](/us-ar) |              353 |                     1,009 |                     334 |                        656 |                                      186% |                                   649 |                                  1,695 |
|                   [Oregon](/us-or) |              254 |                       989 |                     234 |                        735 |                                      289% |                                   371 |                                  2,532 |
|                     [Utah](/us-ut) |              235 |                       921 |                     287 |                        686 |                                      292% |                                   434 |                                  2,488 |
|                 [Oklahoma](/us-ok) |              445 |                       814 |                     206 |                        369 |                                       83% |                                   551 |                                  1,311 |
|     [District of Columbia](/us-dc) |              577 |                       700 |                     992 |                        123 |                                       21% |                                   594 |                                  1,002 |
|                 [Delaware](/us-de) |              521 |                       658 |                     676 |                        137 |                                       26% |                                   537 |                                    955 |
|                   [Kansas](/us-ks) |              306 |                       610 |                     209 |                        304 |                                       99% |                                   339 |                                  1,400 |
|                    [Idaho](/us-id) |              118 |                       492 |                     275 |                        374 |                                      317% |                                   270 |                                    967 |
|                 [Nebraska](/us-ne) |              301 |                       463 |                     239 |                        162 |                                       54% |                                   358 |                                    612 |
|            [New Hampshire](/us-nh) |              395 |                       447 |                     329 |                         52 |                                       13% |                                   401 |                                    508 |
|              [Puerto Rico](/us-pr) |              177 |                       305 |                      96 |                        128 |                                       72% |                                   188 |                                    758 |
|             [South Dakota](/us-sd) |              116 |                       204 |                     231 |                         88 |                                       76% |                                   141 |                                    304 |
|                  [Montana](/us-mt) |               37 |                       187 |                     175 |                        150 |                                      405% |                                    79 |                                    396 |
|                    [Maine](/us-me) |              115 |                       180 |                     134 |                         65 |                                       57% |                                   123 |                                    347 |
|             [North Dakota](/us-nd) |               90 |                       164 |                     215 |                         74 |                                       82% |                                   101 |                                    321 |
|            [West Virginia](/us-wv) |              100 |                       157 |                      88 |                         57 |                                       57% |                                   109 |                                    286 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    180 |
|                   [Hawaii](/us-hi) |               23 |                        62 |                      44 |                         39 |                                      170% |                                    25 |                                    175 |
|                  [Wyoming](/us-wy) |               24 |                        54 |                      93 |                         30 |                                      125% |                                    31 |                                    104 |
|                   [Alaska](/us-ak) |               17 |                        33 |                      45 |                         16 |                                       94% |                                    18 |                                     73 |
|           [Virgin Islands](/us-vi) |                6 |                        16 |                     153 |                         10 |                                      167% |                                     6 |                                     48 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     5 |                                     42 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     10 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          185,615 |                   201,487 |                     340 |                     15,872 |                                        9% |                               189,238 |                                224,275 |
| [United Kingdom](/united-kingdom) |           45,318 |                    49,306 |                     730 |                      3,988 |                                        9% |                                45,808 |                                 53,236 |
|                   [Italy](/italy) |           35,028 |                    35,609 |                     590 |                        581 |                                        2% |                                35,087 |                                 36,155 |
|                 [France](/france) |           30,155 |                    30,817 |                     460 |                        662 |                                        2% |                                30,174 |                                 33,900 |
|                   [Spain](/spain) |           28,420 |                    28,766 |                     613 |                        346 |                                        1% |                                28,449 |                                 29,660 |
|               [Belgium](/belgium) |            9,800 |                     9,971 |                     870 |                        171 |                                        2% |                                 9,816 |                                 10,441 |
|               [Germany](/germany) |            9,088 |                     9,410 |                     113 |                        322 |                                        4% |                                 9,116 |                                 10,130 |
|       [Netherlands](/netherlands) |            6,157 |                     6,255 |                     362 |                         98 |                                        2% |                                 6,174 |                                  6,363 |
|                 [Sweden](/sweden) |            5,619 |                     6,027 |                     589 |                        408 |                                        7% |                                 5,747 |                                  6,197 |
|               [Romania](/romania) |            1,988 |                     3,761 |                     194 |                      1,773 |                                       89% |                                 2,720 |                                  5,130 |
|                 [Serbia](/serbia) |              452 |                     2,926 |                     420 |                      2,474 |                                      547% |                                   946 |                                  7,318 |
|               [Ukraine](/ukraine) |            1,473 |                     2,697 |                      61 |                      1,224 |                                       83% |                                 1,966 |                                  3,946 |
|                 [Poland](/poland) |            1,612 |                     2,361 |                      62 |                        749 |                                       46% |                                 1,852 |                                  3,425 |
|             [Portugal](/portugal) |            1,682 |                     2,166 |                     211 |                        484 |                                       29% |                                 1,762 |                                  2,973 |
|       [Switzerland](/switzerland) |            1,969 |                     2,060 |                     240 |                         91 |                                        5% |                                 1,981 |                                  2,422 |
|               [Ireland](/ireland) |            1,752 |                     1,838 |                     375 |                         86 |                                        5% |                                 1,759 |                                  2,247 |
|               [Moldova](/moldova) |              675 |                     1,154 |                     285 |                        479 |                                       71% |                                   983 |                                  1,493 |
|               [Belarus](/belarus) |              491 |                     1,117 |                     118 |                        626 |                                      127% |                                   641 |                                  2,111 |
|             [Bulgaria](/bulgaria) |              297 |                       895 |                     128 |                        598 |                                      201% |                                   505 |                                  1,442 |
|               [Austria](/austria) |              711 |                       829 |                      94 |                        118 |                                       17% |                                   725 |                                  1,039 |
|               [Hungary](/hungary) |              595 |                       690 |                      71 |                         95 |                                       16% |                                   607 |                                    936 |
|               [Denmark](/denmark) |              611 |                       654 |                     113 |                         43 |                                        7% |                                   624 |                                    732 |
|               [Czechia](/czechia) |              358 |                       497 |                      47 |                        139 |                                       39% |                                   368 |                                    710 |
|               [Finland](/finland) |              328 |                       362 |                      66 |                         34 |                                       10% |                                   332 |                                    455 |
|                 [Norway](/norway) |              255 |                       277 |                      51 |                         22 |                                        9% |                                   262 |                                    320 |
|               [Croatia](/croatia) |              120 |                       228 |                      56 |                        108 |                                       90% |                                   139 |                                    354 |
|                 [Greece](/greece) |              194 |                       223 |                      21 |                         29 |                                       15% |                                   205 |                                    281 |
|         [Luxembourg](/luxembourg) |              111 |                       144 |                     235 |                         33 |                                       30% |                                   117 |                                    181 |
|             [Slovenia](/slovenia) |              111 |                       121 |                      58 |                         10 |                                        9% |                                   112 |                                    148 |
|           [Lithuania](/lithuania) |               79 |                       107 |                      38 |                         28 |                                       35% |                                    85 |                                    168 |
|               [Estonia](/estonia) |               69 |                        85 |                      64 |                         16 |                                       23% |                                    75 |                                    111 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     71 |
|                 [Latvia](/latvia) |               31 |                        40 |                      21 |                          9 |                                       29% |                                    33 |                                     86 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     57 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     24 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    10 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          256,982 |                   590,739 |                     114 |                    333,757 |                                      130% |                               404,224 |                                967,360 |
|                             [Brazil](/brazil) |           77,851 |                   155,622 |                     737 |                     77,771 |                                      100% |                               117,251 |                                237,503 |
|                               [India](/india) |           26,273 |                   107,904 |                      79 |                     81,631 |                                      311% |                                59,771 |                                226,318 |
|                             [Mexico](/mexico) |           38,310 |                    80,392 |                     630 |                     42,082 |                                      110% |                                57,838 |                                114,685 |
|                                 [Iran](/iran) |           13,791 |                    31,029 |                     374 |                     17,238 |                                      125% |                                22,475 |                                 45,479 |
|                                 [Peru](/peru) |           12,799 |                    23,022 |                     708 |                     10,223 |                                       80% |                                18,458 |                                 31,120 |
|                             [Russia](/russia) |           12,106 |                    22,721 |                     156 |                     10,615 |                                       88% |                                15,354 |                                 38,326 |
|                 [South Africa](/south-africa) |            4,804 |                    21,453 |                     366 |                     16,649 |                                      347% |                                13,187 |                                 32,149 |
|                         [Colombia](/colombia) |            6,288 |                    20,564 |                     409 |                     14,276 |                                      227% |                                15,856 |                                 28,976 |
|                       [Indonesia](/indonesia) |            3,957 |                    14,407 |                      53 |                     10,450 |                                      264% |                                 7,291 |                                 27,125 |
|                               [Chile](/chile) |            8,347 |                    12,084 |                     638 |                      3,737 |                                       45% |                                 9,199 |                                 14,512 |
|                         [Pakistan](/pakistan) |            5,522 |                    10,367 |                      48 |                      4,845 |                                       88% |                                 7,038 |                                 16,458 |
|                               [Egypt](/egypt) |            4,188 |                     9,816 |                      98 |                      5,628 |                                      134% |                                 6,036 |                                 16,913 |
|                             [Canada](/canada) |            8,884 |                     9,806 |                     262 |                        922 |                                       10% |                                 8,979 |                                 11,052 |
|                       [Argentina](/argentina) |            2,178 |                     9,320 |                     208 |                      7,142 |                                      328% |                                 4,275 |                                 17,004 |
|                           [Ecuador](/ecuador) |            5,250 |                     8,151 |                     469 |                      2,901 |                                       55% |                                 5,614 |                                 12,893 |
|                             [Turkey](/turkey) |            5,458 |                     6,865 |                      82 |                      1,407 |                                       26% |                                 5,545 |                                 11,378 |
|                           [Bolivia](/bolivia) |            2,049 |                     6,196 |                     538 |                      4,147 |                                      202% |                                 3,657 |                                 10,845 |
|                     [Bangladesh](/bangladesh) |            2,547 |                     5,997 |                      37 |                      3,450 |                                      135% |                                 3,811 |                                 10,298 |
|                 [Saudi Arabia](/saudi-arabia) |            2,407 |                     5,810 |                     170 |                      3,403 |                                      141% |                                 3,930 |                                  8,380 |
|                               [China](/china) |            4,644 |                     4,647 |                       3 |                          3 |                                        0% |                                 4,644 |                                  4,669 |
|                   [Philippines](/philippines) |            1,660 |                     4,000 |                      37 |                      2,340 |                                      141% |                                 2,145 |                                  8,464 |
|                         [Honduras](/honduras) |              857 |                     3,502 |                     359 |                      2,645 |                                      309% |                                 2,289 |                                  6,194 |
|     [Dominican Republic](/dominican-republic) |              942 |                     3,397 |                     316 |                      2,455 |                                      261% |                                 1,416 |                                  7,511 |
|                             [Panama](/panama) |            1,038 |                     3,276 |                     771 |                      2,238 |                                      216% |                                 2,411 |                                  5,222 |
|                           [Algeria](/algeria) |            1,057 |                     3,025 |                      70 |                      1,968 |                                      186% |                                 1,441 |                                  8,171 |
|                           [Nigeria](/nigeria) |              772 |                     1,765 |                       9 |                        993 |                                      129% |                                   976 |                                  3,776 |
|                             [Israel](/israel) |              392 |                     1,609 |                     189 |                      1,217 |                                      310% |                                   619 |                                  4,752 |
|                               [Japan](/japan) |              985 |                     1,505 |                      12 |                        520 |                                       53% |                                   991 |                                  2,563 |
|                             [Kuwait](/kuwait) |              404 |                       660 |                     157 |                        256 |                                       63% |                                   438 |                                  1,202 |
|                           [Morocco](/morocco) |              264 |                       487 |                      13 |                        223 |                                       84% |                                   300 |                                    885 |
| [United Arab Emirates](/united-arab-emirates) |              337 |                       473 |                      48 |                        136 |                                       40% |                                   351 |                                    866 |
|                   [South Korea](/south-korea) |              294 |                       340 |                       7 |                         46 |                                       16% |                                   296 |                                    460 |
|                       [Australia](/australia) |              118 |                       260 |                      10 |                        142 |                                      120% |                                   118 |                                    834 |
|                         [Malaysia](/malaysia) |              122 |                       150 |                       5 |                         28 |                                       23% |                                   133 |                                    179 |
|                                 [Cuba](/cuba) |               87 |                       117 |                      10 |                         30 |                                       34% |                                    91 |                                    198 |
