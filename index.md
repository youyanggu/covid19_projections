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

* **September 28 - MAJOR ANNOUNCEMENT:** We will no longer be extending our projections past November 1. Our last forecast update will be on Monday, October 5. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later). Thank you for your support over the past six months.
* **September 30:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1311384211983675397).
* *September 29:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: October 2 (5am ET):
<p align="center">
  Current Total: <b>207,786</b> deaths | Projected Total: <b>231,300 deaths by Nov 1, 2020</b> (Range: 220-249k)<br>
  Currently Infected: <b>1.2%</b> (1 in 90) | Total Infected: <b>15.9%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: October 2, 2020

|   US deaths surpass: |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|
|              225,000 |          1% |        75% |
|              250,000 |         <1% |         2% |
|              275,000 |         <1% |        <1% |
|              300,000 |         <1% |        <1% |

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
|             *[United States](/us)* |          207,786 |                   231,256 |                     697 |                     23,470 |                       71 |                                       11% |                               220,838 |                                248,001 |
|                 [New York](/us-ny) |           33,159 |                    33,548 |                   1,725 |                        389 |                       20 |                                        1% |                                33,169 |                                 35,536 |
|                    [Texas](/us-tx) |           16,130 |                    18,840 |                     650 |                      2,710 |                       93 |                                       17% |                                17,254 |                                 21,431 |
|               [California](/us-ca) |           15,973 |                    18,354 |                     465 |                      2,381 |                       60 |                                       15% |                                16,550 |                                 22,344 |
|                  [Florida](/us-fl) |           14,444 |                    17,376 |                     809 |                      2,932 |                      137 |                                       20% |                                15,543 |                                 20,412 |
|               [New Jersey](/us-nj) |           16,140 |                    16,400 |                   1,846 |                        260 |                       29 |                                        2% |                                16,148 |                                 17,231 |
|            [Massachusetts](/us-ma) |            9,480 |                    10,004 |                   1,440 |                        524 |                       75 |                                        6% |                                 9,508 |                                 10,849 |
|                 [Illinois](/us-il) |            8,940 |                     9,641 |                     761 |                        701 |                       55 |                                        8% |                                 9,082 |                                 10,712 |
|             [Pennsylvania](/us-pa) |            8,144 |                     8,819 |                     689 |                        675 |                       53 |                                        8% |                                 8,219 |                                  9,899 |
|                  [Georgia](/us-ga) |            7,063 |                     8,121 |                     765 |                      1,058 |                      100 |                                       15% |                                 7,436 |                                  9,501 |
|                 [Michigan](/us-mi) |            7,102 |                     7,462 |                     747 |                        360 |                       36 |                                        5% |                                 7,151 |                                  8,040 |
|                  [Arizona](/us-az) |            5,674 |                     6,258 |                     860 |                        584 |                       80 |                                       10% |                                 5,826 |                                  7,123 |
|                [Louisiana](/us-la) |            5,519 |                     5,961 |                   1,282 |                        442 |                       95 |                                        8% |                                 5,661 |                                  6,520 |
|                     [Ohio](/us-oh) |            4,817 |                     5,580 |                     477 |                        763 |                       65 |                                       16% |                                 5,030 |                                  6,587 |
|              [Connecticut](/us-ct) |            4,511 |                     4,607 |                   1,292 |                         96 |                       27 |                                        2% |                                 4,516 |                                  4,900 |
|           [North Carolina](/us-nc) |            3,579 |                     4,584 |                     437 |                      1,005 |                       96 |                                       28% |                                 4,001 |                                  5,580 |
|                 [Maryland](/us-md) |            3,949 |                     4,195 |                     694 |                        246 |                       41 |                                        6% |                                 3,977 |                                  4,631 |
|                  [Indiana](/us-in) |            3,645 |                     4,096 |                     608 |                        451 |                       67 |                                       12% |                                 3,679 |                                  4,918 |
|           [South Carolina](/us-sc) |            3,400 |                     3,924 |                     762 |                        524 |                      102 |                                       15% |                                 3,629 |                                  4,362 |
|                 [Virginia](/us-va) |            3,225 |                     3,859 |                     452 |                        634 |                       74 |                                       20% |                                 3,410 |                                  4,606 |
|              [Mississippi](/us-ms) |            2,979 |                     3,356 |                   1,127 |                        377 |                      127 |                                       13% |                                 3,115 |                                  3,798 |
|                [Tennessee](/us-tn) |            2,501 |                     3,148 |                     461 |                        647 |                       95 |                                       26% |                                 2,788 |                                  3,714 |
|                  [Alabama](/us-al) |            2,548 |                     2,862 |                     584 |                        314 |                       64 |                                       12% |                                 2,661 |                                  3,199 |
|                 [Missouri](/us-mo) |            2,074 |                     2,718 |                     443 |                        644 |                      105 |                                       31% |                                 2,341 |                                  3,291 |
|               [Washington](/us-wa) |            2,132 |                     2,488 |                     327 |                        356 |                       47 |                                       17% |                                 2,182 |                                  3,103 |
|                [Minnesota](/us-mn) |            2,102 |                     2,425 |                     430 |                        323 |                       57 |                                       15% |                                 2,157 |                                  2,876 |
|                 [Colorado](/us-co) |            2,054 |                     2,223 |                     386 |                        169 |                       29 |                                        8% |                                 2,066 |                                  2,542 |
|                 [Arkansas](/us-ar) |            1,384 |                     1,842 |                     610 |                        458 |                      152 |                                       33% |                                 1,602 |                                  2,276 |
|                   [Nevada](/us-nv) |            1,603 |                     1,795 |                     583 |                        192 |                       62 |                                       12% |                                 1,665 |                                  2,045 |
|                [Wisconsin](/us-wi) |            1,348 |                     1,756 |                     302 |                        408 |                       70 |                                       30% |                                 1,508 |                                  2,115 |
|                     [Iowa](/us-ia) |            1,366 |                     1,655 |                     525 |                        289 |                       92 |                                       21% |                                 1,460 |                                  1,976 |
|                 [Kentucky](/us-ky) |            1,191 |                     1,478 |                     331 |                        287 |                       64 |                                       24% |                                 1,298 |                                  1,761 |
|                 [Oklahoma](/us-ok) |            1,035 |                     1,317 |                     333 |                        282 |                       71 |                                       27% |                                 1,164 |                                  1,576 |
|             [Rhode Island](/us-ri) |            1,117 |                     1,197 |                   1,130 |                         80 |                       76 |                                        7% |                                 1,125 |                                  1,343 |
|               [New Mexico](/us-nm) |              882 |                     1,019 |                     486 |                        137 |                       65 |                                       16% |                                   926 |                                  1,195 |
|              [Puerto Rico](/us-pr) |              665 |                       881 |                     276 |                        216 |                       68 |                                       33% |                                   771 |                                  1,045 |
|                   [Kansas](/us-ks) |              672 |                       881 |                     302 |                        209 |                       72 |                                       31% |                                   754 |                                  1,079 |
|                   [Oregon](/us-or) |              560 |                       707 |                     168 |                        147 |                       35 |                                       26% |                                   612 |                                    859 |
|                 [Delaware](/us-de) |              636 |                       677 |                     695 |                         41 |                       42 |                                        6% |                                   642 |                                    748 |
|     [District of Columbia](/us-dc) |              627 |                       654 |                     927 |                         27 |                       39 |                                        4% |                                   631 |                                    714 |
|                 [Nebraska](/us-ne) |              493 |                       617 |                     319 |                        124 |                       64 |                                       25% |                                   532 |                                    759 |
|                    [Idaho](/us-id) |              472 |                       578 |                     323 |                        106 |                       59 |                                       22% |                                   521 |                                    665 |
|                     [Utah](/us-ut) |              459 |                       549 |                     171 |                         90 |                       28 |                                       20% |                                   491 |                                    633 |
|            [West Virginia](/us-wv) |              359 |                       518 |                     289 |                        159 |                       89 |                                       44% |                                   432 |                                    664 |
|             [North Dakota](/us-nd) |              256 |                       469 |                     616 |                        213 |                      280 |                                       83% |                                   373 |                                    617 |
|            [New Hampshire](/us-nh) |              441 |                       452 |                     332 |                         11 |                        8 |                                        2% |                                   442 |                                    494 |
|             [South Dakota](/us-sd) |              236 |                       376 |                     425 |                        140 |                      158 |                                       59% |                                   289 |                                    519 |
|                  [Montana](/us-mt) |              181 |                       301 |                     282 |                        120 |                      113 |                                       67% |                                   243 |                                    378 |
|                   [Hawaii](/us-hi) |              139 |                       204 |                     144 |                         65 |                       46 |                                       47% |                                   168 |                                    272 |
|                    [Maine](/us-me) |              141 |                       154 |                     114 |                         13 |                       10 |                                        9% |                                   143 |                                    180 |
|                   [Alaska](/us-ak) |               57 |                        90 |                     124 |                         33 |                       46 |                                       59% |                                    74 |                                    123 |
|                     [Guam](/us-gu) |               49 |                        82 |                     492 |                         33 |                      197 |                                       66% |                                    65 |                                    109 |
|                  [Wyoming](/us-wy) |               53 |                        70 |                     121 |                         17 |                       30 |                                       32% |                                    60 |                                     87 |
|                  [Vermont](/us-vt) |               58 |                        59 |                      95 |                          1 |                        2 |                                        3% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               20 |                        23 |                     224 |                          3 |                       33 |                                       17% |                                    21 |                                     27 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      46 |                          1 |                       10 |                                       27% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          200,205 |                   222,402 |                     375 |                     22,197 |                       37 |                                       11% |                               203,954 |                                280,640 |
| [United Kingdom](/united-kingdom) |           42,292 |                    45,391 |                     672 |                      3,099 |                       46 |                                        7% |                                42,378 |                                 56,805 |
|                   [Italy](/italy) |           35,918 |                    36,809 |                     610 |                        891 |                       15 |                                        2% |                                35,938 |                                 39,743 |
|                   [Spain](/spain) |           31,973 |                    36,533 |                     778 |                      4,560 |                       97 |                                       14% |                                32,402 |                                 47,352 |
|                 [France](/france) |           32,034 |                    35,830 |                     535 |                      3,796 |                       57 |                                       12% |                                32,080 |                                 54,269 |
|               [Belgium](/belgium) |           10,023 |                    10,477 |                     915 |                        454 |                       40 |                                        5% |                                10,047 |                                 12,260 |
|               [Germany](/germany) |            9,509 |                    10,068 |                     121 |                        559 |                        7 |                                        6% |                                 9,523 |                                 12,100 |
|       [Netherlands](/netherlands) |            6,470 |                     7,292 |                     422 |                        822 |                       48 |                                       13% |                                 6,523 |                                  9,248 |
|               [Ukraine](/ukraine) |            4,288 |                     6,558 |                     149 |                      2,270 |                       52 |                                       53% |                                 5,312 |                                  8,069 |
|               [Romania](/romania) |            4,862 |                     6,118 |                     315 |                      1,256 |                       65 |                                       26% |                                 5,401 |                                  7,384 |
|                 [Sweden](/sweden) |            5,893 |                     6,011 |                     588 |                        118 |                       12 |                                        2% |                                 5,900 |                                  6,429 |
|                 [Poland](/poland) |            2,543 |                     3,653 |                      96 |                      1,110 |                       29 |                                       44% |                                 2,855 |                                  5,376 |
|             [Portugal](/portugal) |            1,977 |                     2,250 |                     219 |                        273 |                       27 |                                       14% |                                 2,045 |                                  2,578 |
|       [Switzerland](/switzerland) |            2,074 |                     2,202 |                     256 |                        128 |                       15 |                                        6% |                                 2,102 |                                  2,432 |
|               [Ireland](/ireland) |            1,806 |                     1,897 |                     387 |                         91 |                       19 |                                        5% |                                 1,813 |                                  2,268 |
|               [Moldova](/moldova) |            1,336 |                     1,696 |                     420 |                        360 |                       89 |                                       27% |                                 1,483 |                                  2,026 |
|               [Czechia](/czechia) |              678 |                     1,531 |                     144 |                        853 |                       80 |                                      126% |                                 1,035 |                                  2,408 |
|               [Hungary](/hungary) |              781 |                     1,183 |                     121 |                        402 |                       41 |                                       52% |                                   974 |                                  1,464 |
|               [Belarus](/belarus) |              839 |                     1,049 |                     111 |                        210 |                       22 |                                       25% |                                   902 |                                  1,349 |
|             [Bulgaria](/bulgaria) |              825 |                     1,010 |                     144 |                        185 |                       26 |                                       22% |                                   912 |                                  1,174 |
|               [Austria](/austria) |              802 |                       950 |                     107 |                        148 |                       17 |                                       18% |                                   833 |                                  1,173 |
|                 [Serbia](/serbia) |              750 |                       769 |                     110 |                         19 |                        3 |                                        2% |                                   753 |                                    820 |
|               [Denmark](/denmark) |              651 |                       734 |                     126 |                         83 |                       14 |                                       13% |                                   665 |                                    928 |
|                 [Greece](/greece) |              393 |                       563 |                      52 |                        170 |                       16 |                                       43% |                                   460 |                                    738 |
|               [Finland](/finland) |              344 |                       374 |                      68 |                         30 |                        5 |                                        9% |                                   354 |                                    412 |
|               [Croatia](/croatia) |              284 |                       373 |                      91 |                         89 |                       22 |                                       31% |                                   316 |                                    507 |
|                 [Norway](/norway) |              274 |                       308 |                      57 |                         34 |                        6 |                                       13% |                                   285 |                                    346 |
|             [Slovenia](/slovenia) |              152 |                       195 |                      94 |                         43 |                       21 |                                       28% |                                   171 |                                    238 |
|         [Luxembourg](/luxembourg) |              125 |                       138 |                     224 |                         13 |                       20 |                                       10% |                                   127 |                                    161 |
|           [Lithuania](/lithuania) |               92 |                       112 |                      40 |                         20 |                        7 |                                       22% |                                   100 |                                    130 |
|             [Slovakia](/slovakia) |               48 |                        85 |                      16 |                         37 |                        7 |                                       77% |                                    67 |                                    117 |
|                   [Malta](/malta) |               35 |                        82 |                     166 |                         47 |                       95 |                                      134% |                                    54 |                                    152 |
|               [Estonia](/estonia) |               65 |                        78 |                      59 |                         13 |                       10 |                                       20% |                                    71 |                                     89 |
|                 [Latvia](/latvia) |               37 |                        45 |                      23 |                          8 |                        4 |                                       22% |                                    40 |                                     52 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      28 |                          3 |                        3 |                                       12% |                                    23 |                                     28 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        7 |                                       23% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          575,735 |                   684,984 |                     132 |                    109,249 |                       21 |                                       19% |                               630,311 |                                776,698 |
|                             [Brazil](/brazil) |          144,680 |                   162,076 |                     768 |                     17,396 |                       82 |                                       12% |                               155,096 |                                175,934 |
|                               [India](/india) |           98,678 |                   130,100 |                      95 |                     31,422 |                       23 |                                       32% |                               114,267 |                                146,023 |
|                             [Mexico](/mexico) |           78,078 |                    88,899 |                     697 |                     10,821 |                       85 |                                       14% |                                85,123 |                                 95,682 |
|                                 [Peru](/peru) |           32,463 |                    35,155 |                   1,081 |                      2,692 |                       83 |                                        8% |                                33,026 |                                 38,462 |
|                       [Argentina](/argentina) |           20,288 |                    32,878 |                     734 |                     12,590 |                      281 |                                       62% |                                26,825 |                                 42,797 |
|                                 [Iran](/iran) |           26,380 |                    32,043 |                     386 |                      5,663 |                       68 |                                       21% |                                29,399 |                                 36,260 |
|                         [Colombia](/colombia) |           26,196 |                    30,199 |                     600 |                      4,003 |                       80 |                                       15% |                                28,328 |                                 33,833 |
|                             [Russia](/russia) |           20,796 |                    25,508 |                     175 |                      4,712 |                       32 |                                       23% |                                23,436 |                                 33,240 |
|                 [South Africa](/south-africa) |           16,866 |                    18,304 |                     313 |                      1,438 |                       25 |                                        9% |                                17,266 |                                 20,433 |
|                       [Indonesia](/indonesia) |           10,856 |                    14,749 |                      55 |                      3,893 |                       14 |                                       36% |                                13,320 |                                 18,386 |
|                               [Chile](/chile) |           12,822 |                    14,459 |                     763 |                      1,637 |                       86 |                                       13% |                                12,982 |                                 18,239 |
|                           [Ecuador](/ecuador) |           11,433 |                    12,371 |                     712 |                        938 |                       54 |                                        8% |                                11,501 |                                 13,948 |
|                             [Turkey](/turkey) |            8,262 |                    10,615 |                     127 |                      2,353 |                       28 |                                       28% |                                 8,644 |                                 13,717 |
|                             [Canada](/canada) |            9,368 |                    10,078 |                     269 |                        710 |                       19 |                                        8% |                                 9,445 |                                 11,810 |
|                           [Bolivia](/bolivia) |            8,001 |                     8,818 |                     766 |                        817 |                       71 |                                       10% |                                 8,320 |                                  9,611 |
|                   [Philippines](/philippines) |            5,562 |                     7,478 |                      69 |                      1,916 |                       18 |                                       34% |                                 6,358 |                                  9,176 |
|                         [Pakistan](/pakistan) |            6,499 |                     6,743 |                      31 |                        244 |                        1 |                                        4% |                                 6,541 |                                  7,159 |
|                               [Egypt](/egypt) |            5,946 |                     6,521 |                      65 |                        575 |                        6 |                                       10% |                                 6,022 |                                  7,700 |
|                     [Bangladesh](/bangladesh) |            5,272 |                     6,136 |                      38 |                        864 |                        5 |                                       16% |                                 5,647 |                                  7,224 |
|                 [Saudi Arabia](/saudi-arabia) |            4,794 |                     5,579 |                     163 |                        785 |                       23 |                                       16% |                                 4,997 |                                  6,436 |
|                               [China](/china) |            4,739 |                     4,757 |                       3 |                         18 |                        0 |                                        0% |                                 4,739 |                                  4,906 |
|                           [Morocco](/morocco) |            2,229 |                     3,520 |                      96 |                      1,291 |                       35 |                                       58% |                                 2,782 |                                  4,556 |
|                         [Honduras](/honduras) |            2,380 |                     2,858 |                     293 |                        478 |                       49 |                                       20% |                                 2,517 |                                  3,431 |
|                             [Panama](/panama) |            2,387 |                     2,626 |                     618 |                        239 |                       56 |                                       10% |                                 2,466 |                                  2,908 |
|                             [Israel](/israel) |            1,622 |                     2,490 |                     292 |                        868 |                      102 |                                       53% |                                 1,930 |                                  3,563 |
|     [Dominican Republic](/dominican-republic) |            2,108 |                     2,261 |                     211 |                        153 |                       14 |                                        7% |                                 2,151 |                                  2,426 |
|                           [Algeria](/algeria) |            1,741 |                     1,850 |                      43 |                        109 |                        3 |                                        6% |                                 1,764 |                                  2,006 |
|                               [Japan](/japan) |            1,580 |                     1,758 |                      14 |                        178 |                        1 |                                       11% |                                 1,632 |                                  1,950 |
|                           [Nigeria](/nigeria) |            1,112 |                     1,189 |                       6 |                         77 |                        0 |                                        7% |                                 1,123 |                                  1,365 |
|                       [Australia](/australia) |              890 |                       959 |                      38 |                         69 |                        3 |                                        8% |                                   910 |                                  1,034 |
|                             [Kuwait](/kuwait) |              612 |                       693 |                     165 |                         81 |                       19 |                                       13% |                                   626 |                                    829 |
| [United Arab Emirates](/united-arab-emirates) |              421 |                       512 |                      52 |                         91 |                        9 |                                       22% |                                   425 |                                    668 |
|                   [South Korea](/south-korea) |              416 |                       498 |                      10 |                         82 |                        2 |                                       20% |                                   432 |                                    616 |
|                         [Malaysia](/malaysia) |              136 |                       156 |                       5 |                         20 |                        1 |                                       15% |                                   142 |                                    184 |
|                                 [Cuba](/cuba) |              122 |                       149 |                      13 |                         27 |                        2 |                                       22% |                                   129 |                                    186 |
