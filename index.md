We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject.

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

For regular updates and insights, follow us on Twitter:<br>
<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

* **August 10:** See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 10:* View our [updated historical performance](/about/#historical-performance).
* **August 5:** We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 10 (8pm ET):
<p align="center">
  Current Total: <b>162,935</b> deaths | Projected Total: <b>229,200 deaths by Nov 1, 2020</b> (Range: 202-266k)<br>
  Currently Infected: <b>1.8%</b> (1 in 54) | Total Infected: <b>12.9%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 10, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 19, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |        <1% |         37% |        82% |         95% |        99% |
|              225,000 |         <1% |        <1% |         <1% |         9% |         28% |        49% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          2% |        10% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          162,935 |                   229,152 |                     691 |                     66,217 |                                       41% |                               202,918 |                                265,151 |
|                 [New York](/us-ny) |           32,774 |                    33,261 |                   1,710 |                        487 |                                        1% |                                32,793 |                                 35,602 |
|                    [Texas](/us-tx) |            9,157 |                    19,533 |                     674 |                     10,376 |                                      113% |                                14,467 |                                 25,065 |
|               [California](/us-ca) |           10,377 |                    19,271 |                     488 |                      8,894 |                                       86% |                                14,031 |                                 26,608 |
|                  [Florida](/us-fl) |            8,186 |                    16,535 |                     770 |                      8,349 |                                      102% |                                12,234 |                                 21,918 |
|               [New Jersey](/us-nj) |           15,874 |                    16,288 |                   1,834 |                        414 |                                        3% |                                15,914 |                                 17,390 |
|            [Massachusetts](/us-ma) |            8,735 |                     9,928 |                   1,429 |                      1,193 |                                       14% |                                 8,844 |                                 12,469 |
|                 [Illinois](/us-il) |            7,845 |                     9,767 |                     771 |                      1,922 |                                       24% |                                 8,208 |                                 12,902 |
|             [Pennsylvania](/us-pa) |            7,311 |                     8,460 |                     661 |                      1,149 |                                       16% |                                 7,417 |                                 10,596 |
|                 [Michigan](/us-mi) |            6,519 |                     7,335 |                     734 |                        816 |                                       13% |                                 6,593 |                                  8,934 |
|                  [Georgia](/us-ga) |            4,199 |                     7,059 |                     665 |                      2,860 |                                       68% |                                 5,429 |                                  9,569 |
|                  [Arizona](/us-az) |            4,150 |                     6,841 |                     940 |                      2,691 |                                       65% |                                 5,478 |                                  8,501 |
|                [Louisiana](/us-la) |            4,263 |                     5,765 |                   1,240 |                      1,502 |                                       35% |                                 4,868 |                                  7,082 |
|                     [Ohio](/us-oh) |            3,669 |                     5,533 |                     473 |                      1,864 |                                       51% |                                 4,212 |                                  7,760 |
|                 [Maryland](/us-md) |            3,585 |                     4,675 |                     773 |                      1,090 |                                       30% |                                 3,706 |                                  6,832 |
|              [Connecticut](/us-ct) |            4,441 |                     4,576 |                   1,283 |                        135 |                                        3% |                                 4,463 |                                  4,875 |
|                  [Indiana](/us-in) |            3,041 |                     4,211 |                     625 |                      1,170 |                                       38% |                                 3,180 |                                  6,300 |
|           [South Carolina](/us-sc) |            2,031 |                     4,146 |                     805 |                      2,115 |                                      104% |                                 3,085 |                                  5,494 |
|           [North Carolina](/us-nc) |            2,192 |                     4,078 |                     389 |                      1,886 |                                       86% |                                 2,910 |                                  5,985 |
|                 [Virginia](/us-va) |            2,326 |                     4,035 |                     473 |                      1,709 |                                       73% |                                 2,659 |                                  6,644 |
|              [Mississippi](/us-ms) |            1,896 |                     3,246 |                   1,091 |                      1,350 |                                       71% |                                 2,498 |                                  4,211 |
|                  [Alabama](/us-al) |            1,768 |                     2,991 |                     610 |                      1,223 |                                       69% |                                 2,311 |                                  3,911 |
|               [Washington](/us-wa) |            1,688 |                     2,896 |                     380 |                      1,208 |                                       72% |                                 1,994 |                                  4,577 |
|                [Tennessee](/us-tn) |            1,223 |                     2,551 |                     373 |                      1,328 |                                      109% |                                 1,783 |                                  3,654 |
|                 [Colorado](/us-co) |            1,858 |                     2,369 |                     411 |                        511 |                                       28% |                                 1,906 |                                  3,374 |
|                [Minnesota](/us-mn) |            1,698 |                     2,300 |                     408 |                        602 |                                       35% |                                 1,792 |                                  3,378 |
|                 [Missouri](/us-mo) |            1,334 |                     2,217 |                     361 |                        883 |                                       66% |                                 1,591 |                                  3,247 |
|                   [Nevada](/us-nv) |              957 |                     1,929 |                     626 |                        972 |                                      102% |                                 1,379 |                                  2,626 |
|                [Wisconsin](/us-wi) |              998 |                     1,784 |                     306 |                        786 |                                       79% |                                 1,202 |                                  2,856 |
|                     [Iowa](/us-ia) |              931 |                     1,473 |                     467 |                        542 |                                       58% |                                 1,082 |                                  2,155 |
|                 [Kentucky](/us-ky) |              773 |                     1,288 |                     288 |                        515 |                                       67% |                                   915 |                                  1,961 |
|                 [Oklahoma](/us-ok) |              603 |                     1,253 |                     317 |                        650 |                                      108% |                                   839 |                                  1,869 |
|              [Puerto Rico](/us-pr) |              279 |                     1,211 |                     379 |                        932 |                                      334% |                                   581 |                                  2,482 |
|                 [Arkansas](/us-ar) |              544 |                     1,193 |                     395 |                        649 |                                      119% |                                   829 |                                  1,715 |
|             [Rhode Island](/us-ri) |            1,014 |                     1,122 |                   1,059 |                        108 |                                       11% |                                 1,034 |                                  1,292 |
|               [New Mexico](/us-nm) |              685 |                     1,082 |                     516 |                        397 |                                       58% |                                   819 |                                  1,561 |
|                   [Oregon](/us-or) |              356 |                       832 |                     197 |                        476 |                                      134% |                                   516 |                                  1,330 |
|                    [Idaho](/us-id) |              237 |                       715 |                     400 |                        478 |                                      202% |                                   455 |                                  1,052 |
|                     [Utah](/us-ut) |              336 |                       709 |                     221 |                        373 |                                      111% |                                   468 |                                  1,078 |
|                   [Kansas](/us-ks) |              380 |                       688 |                     236 |                        308 |                                       81% |                                   474 |                                  1,074 |
|                 [Delaware](/us-de) |              591 |                       672 |                     690 |                         81 |                                       14% |                                   604 |                                    808 |
|     [District of Columbia](/us-dc) |              591 |                       652 |                     923 |                         61 |                                       10% |                                   603 |                                    755 |
|                 [Nebraska](/us-ne) |              345 |                       524 |                     271 |                        179 |                                       52% |                                   414 |                                    789 |
|            [New Hampshire](/us-nh) |              419 |                       524 |                     385 |                        105 |                                       25% |                                   429 |                                    780 |
|            [West Virginia](/us-wv) |              139 |                       406 |                     227 |                        267 |                                      192% |                                   223 |                                    770 |
|                  [Montana](/us-mt) |               75 |                       270 |                     253 |                        195 |                                      261% |                                   146 |                                    454 |
|             [South Dakota](/us-sd) |              146 |                       237 |                     268 |                         91 |                                       63% |                                   178 |                                    350 |
|             [North Dakota](/us-nd) |              112 |                       208 |                     273 |                         96 |                                       86% |                                   141 |                                    326 |
|                    [Maine](/us-me) |              125 |                       154 |                     115 |                         29 |                                       23% |                                   130 |                                    199 |
|                   [Hawaii](/us-hi) |               31 |                       135 |                      95 |                        104 |                                      335% |                                    52 |                                    376 |
|                  [Vermont](/us-vt) |               58 |                        75 |                     119 |                         17 |                                       28% |                                    61 |                                    104 |
|                   [Alaska](/us-ak) |               26 |                        71 |                      97 |                         45 |                                      172% |                                    41 |                                    123 |
|                  [Wyoming](/us-wy) |               28 |                        46 |                      79 |                         18 |                                       63% |                                    34 |                                     65 |
|           [Virgin Islands](/us-vi) |                9 |                        24 |                     227 |                         15 |                                      164% |                                    14 |                                     41 |
|                     [Guam](/us-gu) |                5 |                         8 |                      51 |                          3 |                                       69% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       58% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,953 |                   212,527 |                     358 |                     22,574 |                                       12% |                               194,077 |                                264,806 |
| [United Kingdom](/united-kingdom) |           46,659 |                    51,390 |                     761 |                      4,731 |                                       10% |                                46,937 |                                 63,111 |
|                   [Italy](/italy) |           35,205 |                    35,996 |                     596 |                        791 |                                        2% |                                35,236 |                                 38,703 |
|                 [France](/france) |           30,327 |                    31,319 |                     467 |                        992 |                                        3% |                                30,365 |                                 36,438 |
|                   [Spain](/spain) |           28,503 |                    30,019 |                     640 |                      1,516 |                                        5% |                                28,547 |                                 36,557 |
|               [Belgium](/belgium) |            9,872 |                    10,384 |                     906 |                        512 |                                        5% |                                 9,909 |                                 12,418 |
|               [Germany](/germany) |            9,202 |                    10,357 |                     125 |                      1,155 |                                       13% |                                 9,314 |                                 13,765 |
|               [Romania](/romania) |            2,700 |                     7,040 |                     363 |                      4,340 |                                      161% |                                 4,118 |                                 12,789 |
|       [Netherlands](/netherlands) |            6,178 |                     6,568 |                     380 |                        390 |                                        6% |                                 6,205 |                                  8,085 |
|                 [Sweden](/sweden) |            5,763 |                     5,961 |                     583 |                        198 |                                        3% |                                 5,809 |                                  6,084 |
|               [Ukraine](/ukraine) |            1,925 |                     5,151 |                     117 |                      3,226 |                                      168% |                                 2,772 |                                 10,204 |
|                 [Poland](/poland) |            1,807 |                     3,033 |                      80 |                      1,226 |                                       68% |                                 2,074 |                                  4,997 |
|       [Switzerland](/switzerland) |            1,986 |                     2,082 |                     242 |                         96 |                                        5% |                                 1,999 |                                  2,479 |
|             [Portugal](/portugal) |            1,756 |                     2,051 |                     200 |                        295 |                                       17% |                                 1,769 |                                  2,715 |
|               [Ireland](/ireland) |            1,772 |                     1,867 |                     381 |                         95 |                                        5% |                                 1,784 |                                  2,153 |
|               [Moldova](/moldova) |              845 |                     1,363 |                     337 |                        518 |                                       61% |                                 1,041 |                                  2,088 |
|                 [Serbia](/serbia) |              641 |                     1,171 |                     168 |                        530 |                                       83% |                                   824 |                                  1,811 |
|             [Bulgaria](/bulgaria) |              447 |                     1,126 |                     161 |                        679 |                                      152% |                                   663 |                                  2,210 |
|               [Austria](/austria) |              721 |                       817 |                      92 |                         96 |                                       13% |                                   735 |                                  1,067 |
|               [Belarus](/belarus) |              587 |                       806 |                      85 |                        219 |                                       37% |                                   716 |                                  1,007 |
|               [Denmark](/denmark) |              617 |                       726 |                     125 |                        109 |                                       18% |                                   638 |                                  1,031 |
|               [Hungary](/hungary) |              602 |                       694 |                      71 |                         92 |                                       15% |                                   611 |                                    921 |
|               [Czechia](/czechia) |              390 |                       566 |                      53 |                        176 |                                       45% |                                   422 |                                    921 |
|               [Finland](/finland) |              331 |                       374 |                      68 |                         43 |                                       13% |                                   339 |                                    490 |
|                 [Greece](/greece) |              212 |                       334 |                      31 |                        122 |                                       58% |                                   237 |                                    589 |
|               [Croatia](/croatia) |              157 |                       323 |                      79 |                        166 |                                      106% |                                   204 |                                    611 |
|                 [Norway](/norway) |              256 |                       296 |                      55 |                         40 |                                       16% |                                   264 |                                    405 |
|             [Slovenia](/slovenia) |              127 |                       197 |                      94 |                         70 |                                       55% |                                   143 |                                    341 |
|         [Luxembourg](/luxembourg) |              120 |                       196 |                     319 |                         76 |                                       63% |                                   139 |                                    346 |
|           [Lithuania](/lithuania) |               81 |                       100 |                      36 |                         19 |                                       23% |                                    85 |                                    138 |
|               [Estonia](/estonia) |               63 |                        72 |                      54 |                          9 |                                       14% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        54 |                      10 |                         23 |                                       75% |                                    34 |                                    114 |
|                 [Latvia](/latvia) |               32 |                        41 |                      21 |                          9 |                                       29% |                                    34 |                                     58 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       49% |                                    22 |                                     42 |
|               [Iceland](/iceland) |               10 |                        13 |                      39 |                          3 |                                       34% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        12 |                      25 |                          3 |                                       36% |                                    10 |                                     17 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          355,339 |                   667,183 |                     129 |                    311,844 |                                       88% |                               474,345 |                                987,759 |
|                             [Brazil](/brazil) |          101,049 |                   174,644 |                     828 |                     73,595 |                                       73% |                               121,328 |                                250,614 |
|                               [India](/india) |           44,386 |                   124,861 |                      91 |                     80,475 |                                      181% |                                77,662 |                                179,729 |
|                             [Mexico](/mexico) |           52,298 |                    99,326 |                     779 |                     47,028 |                                       90% |                                81,010 |                                140,220 |
|                         [Colombia](/colombia) |           12,842 |                    31,803 |                     632 |                     18,961 |                                      148% |                                20,885 |                                 49,707 |
|                                 [Peru](/peru) |           21,072 |                    30,832 |                     948 |                      9,760 |                                       46% |                                24,571 |                                 43,921 |
|                                 [Iran](/iran) |           18,427 |                    27,926 |                     337 |                      9,499 |                                       52% |                                21,823 |                                 38,797 |
|                 [South Africa](/south-africa) |           10,408 |                    25,286 |                     432 |                     14,878 |                                      143% |                                16,534 |                                 36,943 |
|                             [Russia](/russia) |           14,903 |                    21,960 |                     151 |                      7,057 |                                       47% |                                17,068 |                                 32,740 |
|                       [Argentina](/argentina) |            4,606 |                    16,110 |                     360 |                     11,504 |                                      250% |                                 8,917 |                                 29,954 |
|                               [Chile](/chile) |           10,077 |                    15,239 |                     804 |                      5,162 |                                       51% |                                10,881 |                                 26,359 |
|                       [Indonesia](/indonesia) |            5,723 |                    11,743 |                      43 |                      6,020 |                                      105% |                                 7,707 |                                 20,681 |
|                             [Canada](/canada) |            9,028 |                     9,459 |                     253 |                        431 |                                        5% |                                 9,066 |                                 10,502 |
|                           [Bolivia](/bolivia) |            3,640 |                     7,669 |                     666 |                      4,029 |                                      111% |                                 5,054 |                                 12,609 |
|                           [Ecuador](/ecuador) |            5,922 |                     7,549 |                     434 |                      1,627 |                                       27% |                                 6,119 |                                 11,031 |
|                             [Turkey](/turkey) |            5,844 |                     7,456 |                      89 |                      1,612 |                                       28% |                                 5,953 |                                 11,794 |
|                         [Pakistan](/pakistan) |            6,082 |                     7,137 |                      33 |                      1,055 |                                       17% |                                 6,266 |                                  8,491 |
|                               [Egypt](/egypt) |            5,009 |                     5,913 |                      59 |                        904 |                                       18% |                                 5,190 |                                  7,258 |
|                     [Bangladesh](/bangladesh) |            3,399 |                     5,501 |                      34 |                      2,102 |                                       62% |                                 3,925 |                                  9,262 |
|                   [Philippines](/philippines) |            2,270 |                     5,157 |                      48 |                      2,887 |                                      127% |                                 2,730 |                                 11,160 |
|                               [China](/china) |            4,686 |                     4,907 |                       3 |                        221 |                                        5% |                                 4,686 |                                  6,412 |
|                 [Saudi Arabia](/saudi-arabia) |            3,167 |                     4,899 |                     143 |                      1,732 |                                       55% |                                 3,697 |                                  7,618 |
|                         [Honduras](/honduras) |            1,495 |                     3,050 |                     313 |                      1,555 |                                      104% |                                 1,971 |                                  5,289 |
|                             [Panama](/panama) |            1,639 |                     3,016 |                     710 |                      1,377 |                                       84% |                                 2,121 |                                  4,629 |
|                           [Morocco](/morocco) |              498 |                     3,015 |                      83 |                      2,517 |                                      505% |                                 1,001 |                                  7,373 |
|     [Dominican Republic](/dominican-republic) |            1,309 |                     2,556 |                     238 |                      1,247 |                                       95% |                                 1,707 |                                  4,404 |
|                           [Algeria](/algeria) |            1,302 |                     2,268 |                      53 |                        966 |                                       74% |                                 1,479 |                                  4,035 |
|                               [Japan](/japan) |            1,047 |                     1,733 |                      14 |                        686 |                                       66% |                                 1,064 |                                  4,422 |
|                       [Australia](/australia) |              313 |                     1,465 |                      58 |                      1,152 |                                      368% |                                   650 |                                  3,503 |
|                             [Israel](/israel) |              600 |                     1,434 |                     168 |                        834 |                                      139% |                                   828 |                                  2,824 |
|                           [Nigeria](/nigeria) |              945 |                     1,394 |                       7 |                        449 |                                       48% |                                 1,037 |                                  2,286 |
|                             [Kuwait](/kuwait) |              478 |                       766 |                     182 |                        288 |                                       60% |                                   520 |                                  1,439 |
| [United Arab Emirates](/united-arab-emirates) |              357 |                       456 |                      47 |                         99 |                                       28% |                                   364 |                                    736 |
|                   [South Korea](/south-korea) |              305 |                       381 |                       7 |                         76 |                                       25% |                                   305 |                                    625 |
|                         [Malaysia](/malaysia) |              125 |                       142 |                       4 |                         17 |                                       14% |                                   130 |                                    160 |
|                                 [Cuba](/cuba) |               88 |                       132 |                      12 |                         44 |                                       50% |                                    96 |                                    232 |
