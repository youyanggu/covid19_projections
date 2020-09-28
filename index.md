We present an intuitive COVID-19 model that adds machine learning techniques on top of a classic infectious disease model to make projections for infections and deaths for the US and 70 other countries. The countries our projections cover encompass 6.4 billion people and account for more than 95% of all global reported COVID-19 deaths.

Our infections estimates include all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 22:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1308498742451015680).
* **September 20:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 28 (7pm ET):
<p align="center">
  Current Total: <b>204,753</b> deaths | Projected Total: <b>230,100 deaths by Nov 1, 2020</b> (Range: 219-248k)<br>
  Currently Infected: <b>1.2%</b> (1 in 80) | Total Infected: <b>16.2%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 28, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |          2% |        66% |
|              250,000 |        <1% |         <1% |         2% |
|              275,000 |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries).

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

|                                    |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          204,753 |                   230,144 |                     694 |                     25,391 |                       77 |                                       12% |                               219,125 |                                247,930 |
|                 [New York](/us-ny) |           33,131 |                    33,551 |                   1,725 |                        420 |                       22 |                                        1% |                                33,142 |                                 35,774 |
|                    [Texas](/us-tx) |           15,745 |                    18,719 |                     646 |                      2,974 |                      103 |                                       19% |                                16,947 |                                 21,551 |
|               [California](/us-ca) |           15,606 |                    18,458 |                     467 |                      2,852 |                       72 |                                       18% |                                16,659 |                                 21,967 |
|                  [Florida](/us-fl) |           14,032 |                    16,827 |                     783 |                      2,795 |                      130 |                                       20% |                                15,196 |                                 19,523 |
|               [New Jersey](/us-nj) |           16,106 |                    16,377 |                   1,844 |                        271 |                       30 |                                        2% |                                16,114 |                                 17,271 |
|            [Massachusetts](/us-ma) |            9,404 |                     9,801 |                   1,410 |                        397 |                       57 |                                        4% |                                 9,440 |                                 10,517 |
|                 [Illinois](/us-il) |            8,845 |                     9,622 |                     759 |                        777 |                       61 |                                        9% |                                 8,987 |                                 11,003 |
|             [Pennsylvania](/us-pa) |            8,086 |                     8,852 |                     691 |                        766 |                       60 |                                        9% |                                 8,171 |                                 10,056 |
|                  [Georgia](/us-ga) |            6,946 |                     8,385 |                     790 |                      1,439 |                      136 |                                       21% |                                 7,519 |                                  9,895 |
|                 [Michigan](/us-mi) |            7,044 |                     7,421 |                     743 |                        377 |                       38 |                                        5% |                                 7,089 |                                  8,190 |
|                  [Arizona](/us-az) |            5,623 |                     6,293 |                     865 |                        670 |                       92 |                                       12% |                                 5,806 |                                  7,295 |
|                [Louisiana](/us-la) |            5,465 |                     5,976 |                   1,285 |                        511 |                      110 |                                        9% |                                 5,624 |                                  6,663 |
|                     [Ohio](/us-oh) |            4,741 |                     5,572 |                     477 |                        831 |                       71 |                                       18% |                                 4,945 |                                  6,838 |
|              [Connecticut](/us-ct) |            4,501 |                     4,608 |                   1,292 |                        107 |                       30 |                                        2% |                                 4,509 |                                  4,918 |
|           [North Carolina](/us-nc) |            3,441 |                     4,476 |                     427 |                      1,035 |                       99 |                                       30% |                                 3,872 |                                  5,531 |
|                 [Maryland](/us-md) |            3,935 |                     4,221 |                     698 |                        286 |                       47 |                                        7% |                                 3,968 |                                  4,762 |
|                  [Indiana](/us-in) |            3,580 |                     4,036 |                     600 |                        456 |                       68 |                                       13% |                                 3,615 |                                  4,875 |
|           [South Carolina](/us-sc) |            3,326 |                     3,907 |                     759 |                        581 |                      113 |                                       17% |                                 3,586 |                                  4,414 |
|                 [Virginia](/us-va) |            3,157 |                     3,879 |                     454 |                        722 |                       85 |                                       23% |                                 3,346 |                                  4,832 |
|              [Mississippi](/us-ms) |            2,919 |                     3,350 |                   1,126 |                        431 |                      145 |                                       15% |                                 3,070 |                                  3,904 |
|                [Tennessee](/us-tn) |            2,377 |                     3,055 |                     447 |                        678 |                       99 |                                       29% |                                 2,664 |                                  3,750 |
|                  [Alabama](/us-al) |            2,501 |                     2,859 |                     583 |                        358 |                       73 |                                       14% |                                 2,623 |                                  3,281 |
|                 [Missouri](/us-mo) |            2,053 |                     2,806 |                     457 |                        753 |                      123 |                                       37% |                                 2,370 |                                  3,482 |
|               [Washington](/us-wa) |            2,100 |                     2,479 |                     326 |                        379 |                       50 |                                       18% |                                 2,153 |                                  3,130 |
|                [Minnesota](/us-mn) |            2,060 |                     2,388 |                     423 |                        328 |                       58 |                                       16% |                                 2,116 |                                  2,854 |
|                 [Colorado](/us-co) |            2,041 |                     2,228 |                     387 |                        187 |                       32 |                                        9% |                                 2,054 |                                  2,611 |
|                   [Nevada](/us-nv) |            1,585 |                     1,812 |                     588 |                        227 |                       74 |                                       14% |                                 1,659 |                                  2,085 |
|                 [Arkansas](/us-ar) |            1,308 |                     1,757 |                     582 |                        449 |                      149 |                                       34% |                                 1,517 |                                  2,179 |
|                     [Iowa](/us-ia) |            1,316 |                     1,597 |                     506 |                        281 |                       89 |                                       21% |                                 1,408 |                                  1,956 |
|                [Wisconsin](/us-wi) |            1,281 |                     1,594 |                     274 |                        313 |                       54 |                                       24% |                                 1,398 |                                  1,918 |
|                 [Kentucky](/us-ky) |            1,157 |                     1,469 |                     329 |                        312 |                       70 |                                       27% |                                 1,263 |                                  1,830 |
|                 [Oklahoma](/us-ok) |            1,006 |                     1,320 |                     334 |                        314 |                       79 |                                       31% |                                 1,147 |                                  1,619 |
|             [Rhode Island](/us-ri) |            1,107 |                     1,199 |                   1,132 |                         92 |                       87 |                                        8% |                                 1,116 |                                  1,378 |
|               [New Mexico](/us-nm) |              870 |                     1,025 |                     489 |                        155 |                       74 |                                       18% |                                   916 |                                  1,242 |
|              [Puerto Rico](/us-pr) |              644 |                       906 |                     284 |                        262 |                       82 |                                       41% |                                   761 |                                  1,159 |
|                   [Kansas](/us-ks) |              635 |                       858 |                     294 |                        223 |                       76 |                                       35% |                                   717 |                                  1,105 |
|                   [Oregon](/us-or) |              543 |                       697 |                     165 |                        154 |                       37 |                                       28% |                                   598 |                                    865 |
|                 [Delaware](/us-de) |              633 |                       679 |                     698 |                         46 |                       48 |                                        7% |                                   639 |                                    770 |
|     [District of Columbia](/us-dc) |              624 |                       643 |                     911 |                         19 |                       27 |                                        3% |                                   627 |                                    681 |
|                 [Nebraska](/us-ne) |              470 |                       590 |                     305 |                        120 |                       62 |                                       26% |                                   509 |                                    733 |
|                    [Idaho](/us-id) |              460 |                       569 |                     318 |                        109 |                       61 |                                       24% |                                   508 |                                    669 |
|                     [Utah](/us-ut) |              453 |                       554 |                     173 |                        101 |                       32 |                                       22% |                                   489 |                                    650 |
|            [West Virginia](/us-wv) |              339 |                       516 |                     288 |                        177 |                       99 |                                       52% |                                   412 |                                    719 |
|             [North Dakota](/us-nd) |              231 |                       476 |                     624 |                        245 |                      321 |                                      106% |                                   347 |                                    684 |
|            [New Hampshire](/us-nh) |              439 |                       450 |                     331 |                         11 |                        8 |                                        2% |                                   440 |                                    490 |
|             [South Dakota](/us-sd) |              218 |                       322 |                     364 |                        104 |                      118 |                                       48% |                                   246 |                                    454 |
|                  [Montana](/us-mt) |              173 |                       297 |                     278 |                        124 |                      116 |                                       71% |                                   232 |                                    404 |
|                   [Hawaii](/us-hi) |              132 |                       206 |                     145 |                         74 |                       52 |                                       56% |                                   164 |                                    287 |
|                    [Maine](/us-me) |              140 |                       153 |                     114 |                         13 |                        9 |                                        9% |                                   143 |                                    175 |
|                   [Alaska](/us-ak) |               56 |                        92 |                     125 |                         36 |                       49 |                                       64% |                                    73 |                                    130 |
|                     [Guam](/us-gu) |               39 |                        67 |                     406 |                         28 |                      171 |                                       73% |                                    52 |                                     92 |
|                  [Wyoming](/us-wy) |               50 |                        65 |                     113 |                         15 |                       26 |                                       30% |                                    56 |                                     82 |
|                  [Vermont](/us-vt) |               58 |                        60 |                      95 |                          2 |                        3 |                                        3% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               19 |                        23 |                     214 |                          4 |                       33 |                                       18% |                                    20 |                                     26 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       11 |                                       30% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          197,830 |                   223,075 |                     376 |                     25,245 |                       43 |                                       13% |                               201,816 |                                291,895 |
| [United Kingdom](/united-kingdom) |           42,077 |                    45,386 |                     672 |                      3,309 |                       49 |                                        8% |                                42,170 |                                 57,360 |
|                   [Italy](/italy) |           35,835 |                    36,859 |                     611 |                      1,024 |                       17 |                                        3% |                                35,857 |                                 40,445 |
|                   [Spain](/spain) |           31,232 |                    36,800 |                     784 |                      5,568 |                      119 |                                       18% |                                31,746 |                                 50,184 |
|                 [France](/france) |           31,675 |                    36,347 |                     542 |                      4,672 |                       70 |                                       15% |                                31,729 |                                 59,040 |
|               [Belgium](/belgium) |            9,980 |                    10,504 |                     917 |                        524 |                       46 |                                        5% |                                10,005 |                                 12,565 |
|               [Germany](/germany) |            9,464 |                    10,026 |                     121 |                        562 |                        7 |                                        6% |                                 9,477 |                                 12,143 |
|       [Netherlands](/netherlands) |            6,415 |                     7,362 |                     426 |                        947 |                       55 |                                       15% |                                 6,466 |                                  9,967 |
|               [Ukraine](/ukraine) |            4,044 |                     6,505 |                     148 |                      2,461 |                       56 |                                       61% |                                 5,132 |                                  8,474 |
|               [Romania](/romania) |            4,718 |                     6,227 |                     321 |                      1,509 |                       78 |                                       32% |                                 5,359 |                                  7,711 |
|                 [Sweden](/sweden) |            5,880 |                     6,009 |                     587 |                        129 |                       13 |                                        2% |                                 5,889 |                                  6,460 |
|                 [Poland](/poland) |            2,432 |                     3,388 |                      89 |                        956 |                       25 |                                       39% |                                 2,687 |                                  4,835 |
|             [Portugal](/portugal) |            1,953 |                     2,262 |                     220 |                        309 |                       30 |                                       16% |                                 2,027 |                                  2,637 |
|       [Switzerland](/switzerland) |            2,064 |                     2,210 |                     257 |                        146 |                       17 |                                        7% |                                 2,096 |                                  2,467 |
|               [Ireland](/ireland) |            1,802 |                     1,916 |                     391 |                        114 |                       23 |                                        6% |                                 1,810 |                                  2,372 |
|               [Moldova](/moldova) |            1,287 |                     1,667 |                     412 |                        380 |                       94 |                                       30% |                                 1,434 |                                  2,033 |
|               [Czechia](/czechia) |              606 |                     1,489 |                     140 |                        883 |                       83 |                                      146% |                                   945 |                                  2,730 |
|               [Hungary](/hungary) |              736 |                     1,088 |                     111 |                        352 |                       36 |                                       48% |                                   899 |                                  1,394 |
|               [Belarus](/belarus) |              818 |                     1,050 |                     111 |                        232 |                       25 |                                       28% |                                   887 |                                  1,380 |
|             [Bulgaria](/bulgaria) |              796 |                       978 |                     140 |                        182 |                       26 |                                       23% |                                   883 |                                  1,131 |
|               [Austria](/austria) |              787 |                       950 |                     107 |                        163 |                       18 |                                       21% |                                   821 |                                  1,243 |
|               [Denmark](/denmark) |              649 |                       786 |                     135 |                        137 |                       24 |                                       21% |                                   667 |                                  1,162 |
|                 [Serbia](/serbia) |              747 |                       769 |                     110 |                         22 |                        3 |                                        3% |                                   751 |                                    826 |
|                 [Greece](/greece) |              379 |                       688 |                      64 |                        309 |                       29 |                                       82% |                                   496 |                                  1,067 |
|               [Finland](/finland) |              343 |                       377 |                      68 |                         34 |                        6 |                                       10% |                                   354 |                                    423 |
|               [Croatia](/croatia) |              272 |                       368 |                      90 |                         96 |                       24 |                                       35% |                                   305 |                                    515 |
|                 [Norway](/norway) |              270 |                       305 |                      57 |                         35 |                        7 |                                       13% |                                   282 |                                    344 |
|             [Slovenia](/slovenia) |              147 |                       189 |                      91 |                         42 |                       20 |                                       29% |                                   163 |                                    234 |
|         [Luxembourg](/luxembourg) |              124 |                       138 |                     224 |                         14 |                       22 |                                       11% |                                   127 |                                    162 |
|           [Lithuania](/lithuania) |               91 |                       114 |                      41 |                         23 |                        8 |                                       25% |                                   100 |                                    136 |
|                   [Malta](/malta) |               31 |                        85 |                     173 |                         54 |                      110 |                                      175% |                                    53 |                                    164 |
|               [Estonia](/estonia) |               64 |                        78 |                      59 |                         14 |                       10 |                                       22% |                                    70 |                                     89 |
|             [Slovakia](/slovakia) |               44 |                        74 |                      14 |                         30 |                        5 |                                       68% |                                    57 |                                    106 |
|                 [Latvia](/latvia) |               36 |                        44 |                      23 |                          8 |                        4 |                                       21% |                                    39 |                                     51 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      29 |                          3 |                        4 |                                       14% |                                    23 |                                     29 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                        8 |                                       27% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          557,213 |                   679,287 |                     131 |                    122,074 |                       24 |                                       22% |                               609,814 |                                783,810 |
|                             [Brazil](/brazil) |          141,741 |                   160,220 |                     759 |                     18,479 |                       88 |                                       13% |                               150,805 |                                174,991 |
|                               [India](/india) |           94,503 |                   134,524 |                      98 |                     40,021 |                       29 |                                       42% |                               111,520 |                                156,656 |
|                             [Mexico](/mexico) |           76,430 |                    88,726 |                     695 |                     12,296 |                       96 |                                       16% |                                84,253 |                                 96,027 |
|                                 [Peru](/peru) |           32,142 |                    35,507 |                   1,092 |                      3,365 |                      104 |                                       10% |                                32,853 |                                 39,523 |
|                                 [Iran](/iran) |           25,589 |                    31,556 |                     381 |                      5,967 |                       72 |                                       23% |                                28,557 |                                 36,211 |
|                         [Colombia](/colombia) |           25,488 |                    30,045 |                     597 |                      4,557 |                       91 |                                       18% |                                27,789 |                                 34,181 |
|                       [Argentina](/argentina) |           15,749 |                    26,529 |                     592 |                     10,780 |                      241 |                                       68% |                                20,273 |                                 37,502 |
|                             [Russia](/russia) |           20,239 |                    24,869 |                     170 |                      4,630 |                       32 |                                       23% |                                21,057 |                                 32,036 |
|                 [South Africa](/south-africa) |           16,398 |                    17,891 |                     306 |                      1,493 |                       25 |                                        9% |                                16,847 |                                 20,023 |
|                       [Indonesia](/indonesia) |           10,386 |                    14,814 |                      55 |                      4,428 |                       16 |                                       43% |                                13,107 |                                 19,328 |
|                               [Chile](/chile) |           12,641 |                    14,510 |                     766 |                      1,869 |                       99 |                                       15% |                                12,834 |                                 18,754 |
|                           [Ecuador](/ecuador) |           11,279 |                    12,291 |                     707 |                      1,012 |                       58 |                                        9% |                                11,354 |                                 14,012 |
|                             [Turkey](/turkey) |            7,997 |                    10,562 |                     127 |                      2,565 |                       31 |                                       32% |                                 8,439 |                                 14,157 |
|                             [Canada](/canada) |            9,318 |                    10,097 |                     270 |                        779 |                       21 |                                        8% |                                 9,405 |                                 12,086 |
|                           [Bolivia](/bolivia) |            7,858 |                     8,750 |                     760 |                        892 |                       78 |                                       11% |                                 8,219 |                                  9,333 |
|                   [Philippines](/philippines) |            5,344 |                     7,518 |                      70 |                      2,174 |                       20 |                                       41% |                                 6,246 |                                  9,464 |
|                         [Pakistan](/pakistan) |            6,466 |                     6,741 |                      31 |                        275 |                        1 |                                        4% |                                 6,512 |                                  7,194 |
|                               [Egypt](/egypt) |            5,883 |                     6,533 |                      65 |                        650 |                        6 |                                       11% |                                 5,971 |                                  7,890 |
|                     [Bangladesh](/bangladesh) |            5,161 |                     6,152 |                      38 |                        991 |                        6 |                                       19% |                                 5,596 |                                  7,405 |
|                 [Saudi Arabia](/saudi-arabia) |            4,683 |                     5,553 |                     162 |                        870 |                       25 |                                       19% |                                 4,914 |                                  6,498 |
|                               [China](/china) |            4,739 |                     4,759 |                       3 |                         20 |                        0 |                                        0% |                                 4,739 |                                  4,921 |
|                           [Morocco](/morocco) |            2,069 |                     3,434 |                      94 |                      1,365 |                       37 |                                       66% |                                 2,636 |                                  4,607 |
|                         [Honduras](/honduras) |            2,288 |                     2,751 |                     282 |                        463 |                       47 |                                       20% |                                 2,416 |                                  3,254 |
|                             [Panama](/panama) |            2,340 |                     2,636 |                     621 |                        296 |                       70 |                                       13% |                                 2,454 |                                  2,940 |
|     [Dominican Republic](/dominican-republic) |            2,095 |                     2,298 |                     214 |                        203 |                       19 |                                       10% |                                 2,164 |                                  2,508 |
|                             [Israel](/israel) |            1,466 |                     2,267 |                     266 |                        801 |                       94 |                                       55% |                                 1,751 |                                  3,332 |
|                           [Algeria](/algeria) |            1,714 |                     1,839 |                      43 |                        125 |                        3 |                                        7% |                                 1,743 |                                  2,015 |
|                               [Japan](/japan) |            1,549 |                     1,749 |                      14 |                        200 |                        2 |                                       13% |                                 1,609 |                                  1,965 |
|                           [Nigeria](/nigeria) |            1,108 |                     1,197 |                       6 |                         89 |                        0 |                                        8% |                                 1,121 |                                  1,400 |
|                       [Australia](/australia) |              875 |                       959 |                      38 |                         84 |                        3 |                                       10% |                                   901 |                                  1,048 |
|                             [Kuwait](/kuwait) |              601 |                       691 |                     164 |                         90 |                       21 |                                       15% |                                   618 |                                    842 |
| [United Arab Emirates](/united-arab-emirates) |              412 |                       505 |                      52 |                         93 |                       10 |                                       23% |                                   417 |                                    681 |
|                   [South Korea](/south-korea) |              406 |                       499 |                      10 |                         93 |                        2 |                                       23% |                                   423 |                                    633 |
|                                 [Cuba](/cuba) |              122 |                       156 |                      14 |                         34 |                        3 |                                       28% |                                   130 |                                    207 |
|                         [Malaysia](/malaysia) |              134 |                       156 |                       5 |                         22 |                        1 |                                       16% |                                   141 |                                    186 |
