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
### Updated Daily - Last Updated: July 7 (7pm ET):
<p align="center">
  Current Total: <b>130,282</b> deaths | Projected Total: <b>200,200 deaths by Nov 1, 2020</b> (Range: 162-268k) | 185,400 deaths by Oct 1, 2020 (Range: 156-234k)<br>
  Currently Infected: <b>0.9%</b> | Total Infected: <b>6.3%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 6, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              130,000 |         Jul 6, 2020 |
|              140,000 |        Jul 25, 2020 |
|              150,000 |         Aug 9, 2020 |
|              175,000 |        Sep 14, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |         9% |         63% |        96% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        19% |         39% |        52% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          9% |        18% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         5% |
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
|             *[United States](/us)* |          130,282 |                   185,379 |                     559 |                     55,097 |                                       42% |                               156,443 |                                233,512 |
|                 [New York](/us-ny) |           32,219 |                    33,401 |                   1,717 |                      1,182 |                                        4% |                                32,266 |                                 37,900 |
|               [New Jersey](/us-nj) |           15,229 |                    16,376 |                   1,844 |                      1,147 |                                        8% |                                15,362 |                                 17,861 |
|               [California](/us-ca) |            6,441 |                    14,055 |                     356 |                      7,614 |                                      118% |                                 8,771 |                                 25,169 |
|                  [Florida](/us-fl) |            3,778 |                     9,788 |                     456 |                      6,010 |                                      159% |                                 5,113 |                                 17,227 |
|            [Massachusetts](/us-ma) |            8,198 |                     8,927 |                   1,285 |                        729 |                                        9% |                                 8,358 |                                 10,327 |
|             [Pennsylvania](/us-pa) |            6,754 |                     8,623 |                     674 |                      1,869 |                                       28% |                                 6,965 |                                 12,832 |
|                 [Illinois](/us-il) |            7,026 |                     8,493 |                     670 |                      1,467 |                                       21% |                                 7,406 |                                  9,734 |
|                    [Texas](/us-tx) |            2,677 |                     7,746 |                     267 |                      5,069 |                                      189% |                                 3,874 |                                 15,711 |
|                 [Michigan](/us-mi) |            6,221 |                     7,315 |                     732 |                      1,094 |                                       18% |                                 6,290 |                                 10,385 |
|                  [Georgia](/us-ga) |            2,878 |                     6,198 |                     584 |                      3,320 |                                      115% |                                 3,642 |                                 10,484 |
|                  [Arizona](/us-az) |            1,829 |                     5,546 |                     762 |                      3,717 |                                      203% |                                 3,596 |                                  8,493 |
|                [Louisiana](/us-la) |            3,296 |                     4,772 |                   1,027 |                      1,476 |                                       45% |                                 3,484 |                                  6,660 |
|                     [Ohio](/us-oh) |            2,927 |                     4,704 |                     402 |                      1,777 |                                       61% |                                 3,196 |                                  8,472 |
|              [Connecticut](/us-ct) |            4,338 |                     4,570 |                   1,282 |                        232 |                                        5% |                                 4,376 |                                  4,908 |
|                 [Maryland](/us-md) |            3,246 |                     4,006 |                     663 |                        760 |                                       23% |                                 3,427 |                                  5,014 |
|                  [Indiana](/us-in) |            2,698 |                     3,767 |                     560 |                      1,069 |                                       40% |                                 2,808 |                                  6,682 |
|                 [Virginia](/us-va) |            1,853 |                     2,981 |                     349 |                      1,128 |                                       61% |                                 1,966 |                                  5,405 |
|                  [Alabama](/us-al) |            1,007 |                     2,757 |                     562 |                      1,750 |                                      174% |                                 1,417 |                                  4,635 |
|           [North Carolina](/us-nc) |            1,432 |                     2,544 |                     243 |                      1,112 |                                       78% |                                 1,653 |                                  5,777 |
|           [South Carolina](/us-sc) |              827 |                     2,514 |                     488 |                      1,687 |                                      204% |                                 1,361 |                                  4,430 |
|                [Minnesota](/us-mn) |            1,511 |                     2,447 |                     434 |                        936 |                                       62% |                                 1,655 |                                  4,271 |
|                 [Colorado](/us-co) |            1,691 |                     2,335 |                     405 |                        644 |                                       38% |                                 1,749 |                                  4,287 |
|              [Mississippi](/us-ms) |            1,114 |                     2,210 |                     743 |                      1,096 |                                       98% |                                 1,346 |                                  3,659 |
|               [Washington](/us-wa) |            1,369 |                     2,081 |                     273 |                        712 |                                       52% |                                 1,521 |                                  3,455 |
|                [Tennessee](/us-tn) |              652 |                     2,040 |                     299 |                      1,388 |                                      213% |                                 1,007 |                                  3,733 |
|                 [Missouri](/us-mo) |            1,051 |                     1,619 |                     264 |                        568 |                                       54% |                                 1,134 |                                  3,055 |
|                [Wisconsin](/us-wi) |              796 |                     1,405 |                     241 |                        609 |                                       77% |                                   916 |                                  2,835 |
|                   [Nevada](/us-nv) |              537 |                     1,290 |                     419 |                        753 |                                      140% |                                   751 |                                  2,197 |
|             [Rhode Island](/us-ri) |              960 |                     1,186 |                   1,120 |                        226 |                                       24% |                                 1,021 |                                  1,433 |
|                 [Kentucky](/us-ky) |              593 |                     1,083 |                     242 |                        490 |                                       83% |                                   668 |                                  2,179 |
|                 [Arkansas](/us-ar) |              292 |                       930 |                     308 |                        638 |                                      218% |                                   422 |                                  1,838 |
|                     [Iowa](/us-ia) |              723 |                       922 |                     292 |                        199 |                                       28% |                                   748 |                                  1,421 |
|               [New Mexico](/us-nm) |              515 |                       862 |                     411 |                        347 |                                       67% |                                   572 |                                  1,600 |
|                 [Oklahoma](/us-ok) |              399 |                       677 |                     171 |                        278 |                                       70% |                                   429 |                                  1,611 |
|     [District of Columbia](/us-dc) |              561 |                       675 |                     956 |                        114 |                                       20% |                                   582 |                                    910 |
|                 [Delaware](/us-de) |              512 |                       656 |                     674 |                        144 |                                       28% |                                   531 |                                    981 |
|            [New Hampshire](/us-nh) |              382 |                       636 |                     468 |                        254 |                                       66% |                                   420 |                                  1,149 |
|                   [Oregon](/us-or) |              215 |                       532 |                     126 |                        317 |                                      147% |                                   262 |                                  1,116 |
|                     [Utah](/us-ut) |              190 |                       531 |                     166 |                        341 |                                      179% |                                   242 |                                  1,359 |
|                 [Nebraska](/us-ne) |              283 |                       497 |                     257 |                        214 |                                       76% |                                   339 |                                    761 |
|                   [Kansas](/us-ks) |              285 |                       433 |                     149 |                        148 |                                       52% |                                   302 |                                    899 |
|              [Puerto Rico](/us-pr) |              155 |                       213 |                      67 |                         58 |                                       37% |                                   162 |                                    395 |
|                    [Idaho](/us-id) |               94 |                       196 |                     110 |                        102 |                                      109% |                                   118 |                                    332 |
|             [South Dakota](/us-sd) |               97 |                       195 |                     220 |                         98 |                                      101% |                                   117 |                                    341 |
|                    [Maine](/us-me) |              109 |                       155 |                     115 |                         46 |                                       42% |                                   117 |                                    270 |
|            [West Virginia](/us-wv) |               95 |                       121 |                      68 |                         26 |                                       27% |                                   100 |                                    179 |
|             [North Dakota](/us-nd) |               80 |                       112 |                     147 |                         32 |                                       40% |                                    90 |                                    163 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    58 |                                    116 |
|                  [Montana](/us-mt) |               23 |                        53 |                      50 |                         30 |                                      130% |                                    26 |                                    110 |
|                   [Alaska](/us-ak) |               16 |                        50 |                      68 |                         34 |                                      212% |                                    17 |                                    110 |
|                  [Wyoming](/us-wy) |               20 |                        29 |                      50 |                          9 |                                       45% |                                    23 |                                     43 |
|                   [Hawaii](/us-hi) |               19 |                        26 |                      18 |                          7 |                                       37% |                                    20 |                                     39 |
|           [Virgin Islands](/us-vi) |                6 |                        11 |                     105 |                          5 |                                       83% |                                     6 |                                     18 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      7 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          182,960 |                   199,204 |                     336 |                     16,244 |                                        9% |                               186,800 |                                222,335 |
| [United Kingdom](/united-kingdom) |           44,321 |                    48,413 |                     717 |                      4,092 |                                        9% |                                44,960 |                                 51,971 |
|                   [Italy](/italy) |           34,869 |                    35,884 |                     595 |                      1,015 |                                        3% |                                34,999 |                                 36,983 |
|                 [France](/france) |           29,923 |                    30,879 |                     461 |                        956 |                                        3% |                                29,949 |                                 35,377 |
|                   [Spain](/spain) |           28,388 |                    29,182 |                     622 |                        794 |                                        3% |                                28,432 |                                 31,108 |
|               [Belgium](/belgium) |            9,774 |                    10,025 |                     875 |                        251 |                                        3% |                                 9,795 |                                 10,723 |
|               [Germany](/germany) |            9,022 |                     9,606 |                     116 |                        584 |                                        6% |                                 9,074 |                                 11,139 |
|       [Netherlands](/netherlands) |            6,147 |                     6,352 |                     368 |                        205 |                                        3% |                                 6,168 |                                  6,643 |
|                 [Sweden](/sweden) |            5,433 |                     6,275 |                     613 |                        842 |                                       15% |                                 5,778 |                                  7,458 |
|               [Romania](/romania) |            1,768 |                     3,746 |                     193 |                      1,978 |                                      112% |                                 2,531 |                                  4,995 |
|                 [Poland](/poland) |            1,521 |                     2,687 |                      71 |                      1,166 |                                       77% |                                 1,854 |                                  4,166 |
|               [Ukraine](/ukraine) |            1,278 |                     2,633 |                      60 |                      1,355 |                                      106% |                                 1,832 |                                  3,806 |
|             [Portugal](/portugal) |            1,620 |                     2,083 |                     203 |                        463 |                                       29% |                                 1,688 |                                  2,859 |
|       [Switzerland](/switzerland) |            1,965 |                     2,050 |                     239 |                         85 |                                        4% |                                 1,976 |                                  2,373 |
|               [Ireland](/ireland) |            1,741 |                     1,822 |                     372 |                         81 |                                        5% |                                 1,748 |                                  2,192 |
|               [Moldova](/moldova) |              592 |                     1,187 |                     294 |                        595 |                                      101% |                                   965 |                                  1,617 |
|               [Belarus](/belarus) |              429 |                       890 |                      94 |                        461 |                                      107% |                                   566 |                                  1,625 |
|               [Austria](/austria) |              706 |                       802 |                      91 |                         96 |                                       14% |                                   720 |                                    952 |
|             [Bulgaria](/bulgaria) |              250 |                       716 |                     102 |                        466 |                                      186% |                                   414 |                                  1,026 |
|               [Hungary](/hungary) |              589 |                       707 |                      72 |                        118 |                                       20% |                                   605 |                                    999 |
|               [Denmark](/denmark) |              607 |                       670 |                     115 |                         63 |                                       10% |                                   621 |                                    822 |
|                 [Serbia](/serbia) |              317 |                       543 |                      78 |                        226 |                                       71% |                                   364 |                                    825 |
|               [Czechia](/czechia) |              350 |                       444 |                      42 |                         94 |                                       27% |                                   357 |                                    575 |
|               [Finland](/finland) |              329 |                       367 |                      67 |                         38 |                                       12% |                                   335 |                                    477 |
|                 [Norway](/norway) |              251 |                       271 |                      50 |                         20 |                                        8% |                                   257 |                                    308 |
|                 [Greece](/greece) |              192 |                       219 |                      20 |                         27 |                                       14% |                                   202 |                                    264 |
|               [Croatia](/croatia) |              113 |                       186 |                      46 |                         73 |                                       65% |                                   125 |                                    258 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   112 |                                    150 |
|         [Luxembourg](/luxembourg) |              110 |                       118 |                     192 |                          8 |                                        7% |                                   112 |                                    136 |
|           [Lithuania](/lithuania) |               79 |                       111 |                      40 |                         32 |                                       41% |                                    86 |                                    156 |
|               [Estonia](/estonia) |               69 |                        87 |                      66 |                         18 |                                       26% |                                    74 |                                    147 |
|                 [Latvia](/latvia) |               30 |                        38 |                      20 |                          8 |                                       27% |                                    32 |                                     67 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       6 |                          7 |                                       25% |                                    28 |                                     58 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     46 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    10 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          213,612 |                   518,688 |                     100 |                    305,076 |                                      143% |                               352,883 |                                789,064 |
|                             [Brazil](/brazil) |           65,487 |                   129,994 |                     616 |                     64,507 |                                       99% |                               104,256 |                                191,439 |
|                               [India](/india) |           20,159 |                    92,438 |                      68 |                     72,279 |                                      359% |                                41,996 |                                182,059 |
|                             [Mexico](/mexico) |           31,119 |                    76,341 |                     598 |                     45,222 |                                      145% |                                58,901 |                                 90,862 |
|                                 [Peru](/peru) |           10,772 |                    22,354 |                     688 |                     11,582 |                                      108% |                                16,211 |                                 31,069 |
|                                 [Iran](/iran) |           11,731 |                    21,905 |                     264 |                     10,174 |                                       87% |                                18,314 |                                 27,011 |
|                             [Russia](/russia) |           10,280 |                    20,749 |                     142 |                     10,469 |                                      102% |                                13,233 |                                 36,925 |
|                         [Colombia](/colombia) |            4,305 |                    17,410 |                     346 |                     13,105 |                                      304% |                                10,923 |                                 24,708 |
|                 [South Africa](/south-africa) |            3,310 |                    14,930 |                     255 |                     11,620 |                                      351% |                                 8,278 |                                 20,984 |
|                               [Egypt](/egypt) |            3,422 |                    12,164 |                     121 |                      8,742 |                                      255% |                                 7,744 |                                 16,401 |
|                         [Pakistan](/pakistan) |            4,839 |                    11,940 |                      55 |                      7,101 |                                      147% |                                 7,992 |                                 17,102 |
|                               [Chile](/chile) |            6,384 |                    11,270 |                     595 |                      4,886 |                                       77% |                                 7,527 |                                 15,027 |
|                             [Canada](/canada) |            8,748 |                    10,101 |                     270 |                      1,353 |                                       15% |                                 8,962 |                                 12,850 |
|                       [Indonesia](/indonesia) |            3,241 |                     9,851 |                      36 |                      6,610 |                                      204% |                                 5,609 |                                 15,640 |
|                           [Ecuador](/ecuador) |            4,821 |                     8,420 |                     485 |                      3,599 |                                       75% |                                 5,287 |                                 13,055 |
|                       [Argentina](/argentina) |            1,582 |                     7,892 |                     176 |                      6,310 |                                      399% |                                 3,740 |                                 12,796 |
|                 [Saudi Arabia](/saudi-arabia) |            1,968 |                     7,251 |                     212 |                      5,283 |                                      268% |                                 4,410 |                                  9,708 |
|                             [Turkey](/turkey) |            5,241 |                     6,709 |                      80 |                      1,468 |                                       28% |                                 5,320 |                                 11,321 |
|                     [Bangladesh](/bangladesh) |            2,096 |                     6,627 |                      41 |                      4,531 |                                      216% |                                 4,300 |                                 12,037 |
|                           [Bolivia](/bolivia) |            1,476 |                     5,958 |                     517 |                      4,482 |                                      304% |                                 3,154 |                                  9,711 |
|                               [China](/china) |            4,641 |                     4,646 |                       3 |                          5 |                                        0% |                                 4,641 |                                  4,675 |
|                         [Honduras](/honduras) |              656 |                     3,313 |                     340 |                      2,657 |                                      405% |                                 2,233 |                                  4,960 |
|     [Dominican Republic](/dominican-republic) |              804 |                     2,889 |                     269 |                      2,085 |                                      259% |                                 1,099 |                                  5,499 |
|                             [Panama](/panama) |              770 |                     2,784 |                     656 |                      2,014 |                                      262% |                                 2,098 |                                  3,955 |
|                   [Philippines](/philippines) |            1,303 |                     2,651 |                      25 |                      1,348 |                                      103% |                                 1,447 |                                  4,910 |
|                           [Algeria](/algeria) |              959 |                     2,119 |                      49 |                      1,160 |                                      121% |                                 1,297 |                                  4,167 |
|                           [Nigeria](/nigeria) |              654 |                     1,816 |                       9 |                      1,162 |                                      178% |                                   900 |                                  3,740 |
|                               [Japan](/japan) |              978 |                     1,346 |                      11 |                        368 |                                       38% |                                   983 |                                  1,894 |
|                             [Kuwait](/kuwait) |              373 |                       622 |                     148 |                        249 |                                       67% |                                   419 |                                  1,049 |
|                             [Israel](/israel) |              334 |                       616 |                      72 |                        282 |                                       84% |                                   389 |                                    910 |
| [United Arab Emirates](/united-arab-emirates) |              324 |                       438 |                      45 |                        114 |                                       35% |                                   343 |                                    748 |
|                           [Morocco](/morocco) |              237 |                       390 |                      11 |                        153 |                                       65% |                                   261 |                                    620 |
|                   [South Korea](/south-korea) |              285 |                       326 |                       6 |                         41 |                                       14% |                                   286 |                                    426 |
|                       [Australia](/australia) |              106 |                       172 |                       7 |                         66 |                                       62% |                                   106 |                                    490 |
|                         [Malaysia](/malaysia) |              121 |                       154 |                       5 |                         33 |                                       27% |                                   134 |                                    179 |
|                                 [Cuba](/cuba) |               86 |                       102 |                       9 |                         16 |                                       19% |                                    90 |                                    137 |
