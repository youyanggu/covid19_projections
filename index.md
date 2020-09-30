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

* **September 28:** We will no longer be extending our projections past November 1. Our last forecast update will be on Monday, October 5. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later).
* *September 22:* [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1308498742451015680).
* *September 20:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 30 (3am ET):
<p align="center">
  Current Total: <b>205,983</b> deaths | Projected Total: <b>230,000 deaths by Nov 1, 2020</b> (Range: 219-248k)<br>
  Currently Infected: <b>1.2%</b> (1 in 80) | Total Infected: <b>16.3%</b> (1 in 6) {% include iframe.html %}
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
|              225,000 |        <1% |          1% |        66% |
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
|             *[United States](/us)* |          205,983 |                   230,019 |                     693 |                     24,036 |                       72 |                                       12% |                               219,404 |                                247,222 |
|                 [New York](/us-ny) |           33,144 |                    33,541 |                   1,724 |                        397 |                       20 |                                        1% |                                33,154 |                                 35,646 |
|                    [Texas](/us-tx) |           15,902 |                    18,659 |                     643 |                      2,757 |                       95 |                                       17% |                                17,007 |                                 21,311 |
|               [California](/us-ca) |           15,782 |                    18,462 |                     467 |                      2,680 |                       68 |                                       17% |                                16,746 |                                 21,836 |
|                  [Florida](/us-fl) |           14,143 |                    17,006 |                     792 |                      2,863 |                      133 |                                       20% |                                15,197 |                                 20,124 |
|               [New Jersey](/us-nj) |           16,117 |                    16,371 |                   1,843 |                        254 |                       29 |                                        2% |                                16,125 |                                 17,222 |
|            [Massachusetts](/us-ma) |            9,423 |                     9,787 |                   1,408 |                        364 |                       52 |                                        4% |                                 9,456 |                                 10,459 |
|                 [Illinois](/us-il) |            8,881 |                     9,600 |                     758 |                        719 |                       57 |                                        8% |                                 9,015 |                                 10,857 |
|             [Pennsylvania](/us-pa) |            8,101 |                     8,786 |                     686 |                        685 |                       53 |                                        8% |                                 8,176 |                                  9,910 |
|                  [Georgia](/us-ga) |            6,994 |                     8,313 |                     783 |                      1,319 |                      124 |                                       19% |                                 7,499 |                                  9,743 |
|                 [Michigan](/us-mi) |            7,072 |                     7,441 |                     745 |                        369 |                       37 |                                        5% |                                 7,115 |                                  8,188 |
|                  [Arizona](/us-az) |            5,632 |                     6,239 |                     857 |                        607 |                       83 |                                       11% |                                 5,792 |                                  7,152 |
|                [Louisiana](/us-la) |            5,490 |                     5,964 |                   1,283 |                        474 |                      102 |                                        9% |                                 5,633 |                                  6,617 |
|                     [Ohio](/us-oh) |            4,783 |                     5,573 |                     477 |                        790 |                       68 |                                       17% |                                 4,975 |                                  6,767 |
|              [Connecticut](/us-ct) |            4,505 |                     4,607 |                   1,292 |                        102 |                       29 |                                        2% |                                 4,512 |                                  4,902 |
|           [North Carolina](/us-nc) |            3,494 |                     4,459 |                     425 |                        965 |                       92 |                                       28% |                                 3,895 |                                  5,452 |
|                 [Maryland](/us-md) |            3,946 |                     4,216 |                     697 |                        270 |                       45 |                                        7% |                                 3,976 |                                  4,728 |
|                  [Indiana](/us-in) |            3,612 |                     4,058 |                     603 |                        446 |                       66 |                                       12% |                                 3,646 |                                  4,879 |
|           [South Carolina](/us-sc) |            3,359 |                     3,900 |                     757 |                        541 |                      105 |                                       16% |                                 3,596 |                                  4,371 |
|                 [Virginia](/us-va) |            3,185 |                     3,857 |                     452 |                        672 |                       79 |                                       21% |                                 3,360 |                                  4,761 |
|              [Mississippi](/us-ms) |            2,957 |                     3,369 |                   1,132 |                        412 |                      138 |                                       14% |                                 3,094 |                                  3,903 |
|                [Tennessee](/us-tn) |            2,420 |                     3,066 |                     449 |                        646 |                       94 |                                       27% |                                 2,685 |                                  3,730 |
|                  [Alabama](/us-al) |            2,517 |                     2,846 |                     580 |                        329 |                       67 |                                       13% |                                 2,627 |                                  3,241 |
|                 [Missouri](/us-mo) |            2,066 |                     2,763 |                     450 |                        697 |                      114 |                                       34% |                                 2,353 |                                  3,387 |
|               [Washington](/us-wa) |            2,124 |                     2,493 |                     327 |                        369 |                       48 |                                       17% |                                 2,175 |                                  3,129 |
|                [Minnesota](/us-mn) |            2,072 |                     2,382 |                     422 |                        310 |                       55 |                                       15% |                                 2,125 |                                  2,826 |
|                 [Colorado](/us-co) |            2,046 |                     2,221 |                     386 |                        175 |                       30 |                                        9% |                                 2,058 |                                  2,584 |
|                 [Arkansas](/us-ar) |            1,350 |                     1,801 |                     597 |                        451 |                      149 |                                       33% |                                 1,556 |                                  2,228 |
|                   [Nevada](/us-nv) |            1,593 |                     1,799 |                     584 |                        206 |                       67 |                                       13% |                                 1,659 |                                  2,056 |
|                     [Iowa](/us-ia) |            1,341 |                     1,616 |                     512 |                        275 |                       87 |                                       20% |                                 1,430 |                                  1,966 |
|                [Wisconsin](/us-wi) |            1,300 |                     1,609 |                     276 |                        309 |                       53 |                                       24% |                                 1,412 |                                  1,928 |
|                 [Kentucky](/us-ky) |            1,170 |                     1,466 |                     328 |                        296 |                       66 |                                       25% |                                 1,269 |                                  1,810 |
|                 [Oklahoma](/us-ok) |            1,018 |                     1,308 |                     331 |                        290 |                       73 |                                       28% |                                 1,149 |                                  1,584 |
|             [Rhode Island](/us-ri) |            1,113 |                     1,199 |                   1,132 |                         86 |                       81 |                                        8% |                                 1,121 |                                  1,369 |
|               [New Mexico](/us-nm) |              875 |                     1,020 |                     486 |                        145 |                       69 |                                       17% |                                   917 |                                  1,227 |
|              [Puerto Rico](/us-pr) |              654 |                       892 |                     279 |                        238 |                       75 |                                       36% |                                   760 |                                  1,117 |
|                   [Kansas](/us-ks) |              651 |                       867 |                     297 |                        216 |                       74 |                                       33% |                                   726 |                                  1,104 |
|                   [Oregon](/us-or) |              555 |                       713 |                     169 |                        158 |                       37 |                                       28% |                                   610 |                                    883 |
|                 [Delaware](/us-de) |              635 |                       679 |                     697 |                         44 |                       45 |                                        7% |                                   641 |                                    766 |
|     [District of Columbia](/us-dc) |              626 |                       644 |                     913 |                         18 |                       26 |                                        3% |                                   629 |                                    682 |
|                 [Nebraska](/us-ne) |              478 |                       596 |                     308 |                        118 |                       61 |                                       25% |                                   516 |                                    734 |
|                    [Idaho](/us-id) |              464 |                       563 |                     315 |                         99 |                       55 |                                       21% |                                   508 |                                    655 |
|                     [Utah](/us-ut) |              457 |                       555 |                     173 |                         98 |                       31 |                                       22% |                                   492 |                                    650 |
|            [West Virginia](/us-wv) |              350 |                       522 |                     291 |                        172 |                       96 |                                       49% |                                   422 |                                    714 |
|             [North Dakota](/us-nd) |              239 |                       453 |                     595 |                        214 |                      281 |                                       90% |                                   343 |                                    634 |
|            [New Hampshire](/us-nh) |              439 |                       449 |                     330 |                         10 |                        7 |                                        2% |                                   440 |                                    488 |
|             [South Dakota](/us-sd) |              223 |                       322 |                     364 |                         99 |                      111 |                                       44% |                                   251 |                                    442 |
|                  [Montana](/us-mt) |              177 |                       292 |                     273 |                        115 |                      107 |                                       65% |                                   232 |                                    387 |
|                   [Hawaii](/us-hi) |              134 |                       200 |                     141 |                         66 |                       47 |                                       49% |                                   163 |                                    272 |
|                    [Maine](/us-me) |              141 |                       153 |                     114 |                         12 |                        9 |                                        9% |                                   143 |                                    176 |
|                   [Alaska](/us-ak) |               56 |                        91 |                     124 |                         35 |                       47 |                                       62% |                                    73 |                                    126 |
|                     [Guam](/us-gu) |               47 |                        84 |                     508 |                         37 |                      224 |                                       79% |                                    66 |                                    115 |
|                  [Wyoming](/us-wy) |               50 |                        63 |                     110 |                         13 |                       23 |                                       27% |                                    55 |                                     76 |
|                  [Vermont](/us-vt) |               58 |                        59 |                      95 |                          1 |                        2 |                                        3% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               20 |                        24 |                     227 |                          4 |                       36 |                                       19% |                                    21 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       10 |                                       28% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          198,835 |                   221,665 |                     374 |                     22,830 |                       38 |                                       11% |                               202,291 |                                284,996 |
| [United Kingdom](/united-kingdom) |           42,162 |                    45,243 |                     670 |                      3,081 |                       46 |                                        7% |                                42,252 |                                 56,958 |
|                   [Italy](/italy) |           35,875 |                    36,837 |                     610 |                        962 |                       16 |                                        3% |                                35,896 |                                 40,085 |
|                 [France](/france) |           31,908 |                    36,142 |                     539 |                      4,234 |                       63 |                                       13% |                                31,958 |                                 56,562 |
|                   [Spain](/spain) |           31,411 |                    35,845 |                     764 |                      4,434 |                       94 |                                       14% |                                31,485 |                                 48,283 |
|               [Belgium](/belgium) |           10,001 |                    10,499 |                     917 |                        498 |                       43 |                                        5% |                                10,026 |                                 12,450 |
|               [Germany](/germany) |            9,483 |                    10,004 |                     121 |                        521 |                        6 |                                        5% |                                 9,495 |                                 11,960 |
|       [Netherlands](/netherlands) |            6,443 |                     7,342 |                     425 |                        899 |                       52 |                                       14% |                                 6,496 |                                  9,678 |
|               [Ukraine](/ukraine) |            4,154 |                     6,456 |                     147 |                      2,302 |                       52 |                                       55% |                                 5,214 |                                  8,094 |
|               [Romania](/romania) |            4,792 |                     6,177 |                     318 |                      1,385 |                       71 |                                       29% |                                 5,384 |                                  7,566 |
|                 [Sweden](/sweden) |            5,890 |                     6,017 |                     588 |                        127 |                       12 |                                        2% |                                 5,898 |                                  6,455 |
|                 [Poland](/poland) |            2,483 |                     3,511 |                      92 |                      1,028 |                       27 |                                       41% |                                 2,767 |                                  4,960 |
|             [Portugal](/portugal) |            1,963 |                     2,247 |                     219 |                        284 |                       28 |                                       14% |                                 2,031 |                                  2,597 |
|       [Switzerland](/switzerland) |            2,069 |                     2,206 |                     257 |                        137 |                       16 |                                        7% |                                 2,099 |                                  2,448 |
|               [Ireland](/ireland) |            1,803 |                     1,905 |                     388 |                        102 |                       21 |                                        6% |                                 1,811 |                                  2,312 |
|               [Moldova](/moldova) |            1,310 |                     1,672 |                     414 |                        362 |                       90 |                                       28% |                                 1,451 |                                  2,019 |
|               [Czechia](/czechia) |              636 |                     1,442 |                     135 |                        806 |                       76 |                                      127% |                                   958 |                                  2,344 |
|               [Hungary](/hungary) |              757 |                     1,128 |                     115 |                        371 |                       38 |                                       49% |                                   936 |                                  1,420 |
|               [Belarus](/belarus) |              828 |                     1,049 |                     111 |                        221 |                       23 |                                       27% |                                   893 |                                  1,366 |
|             [Bulgaria](/bulgaria) |              813 |                     1,007 |                     144 |                        194 |                       28 |                                       24% |                                   905 |                                  1,179 |
|               [Austria](/austria) |              796 |                       956 |                     108 |                        160 |                       18 |                                       20% |                                   829 |                                  1,207 |
|                 [Serbia](/serbia) |              749 |                       770 |                     111 |                         21 |                        3 |                                        3% |                                   753 |                                    825 |
|               [Denmark](/denmark) |              650 |                       753 |                     130 |                        103 |                       18 |                                       16% |                                   666 |                                  1,005 |
|                 [Greece](/greece) |              388 |                       639 |                      60 |                        251 |                       23 |                                       65% |                                   488 |                                    965 |
|               [Finland](/finland) |              345 |                       379 |                      69 |                         34 |                        6 |                                       10% |                                   356 |                                    427 |
|               [Croatia](/croatia) |              275 |                       361 |                      89 |                         86 |                       21 |                                       31% |                                   305 |                                    488 |
|                 [Norway](/norway) |              274 |                       313 |                      58 |                         39 |                        7 |                                       14% |                                   287 |                                    354 |
|             [Slovenia](/slovenia) |              149 |                       190 |                      92 |                         41 |                       20 |                                       28% |                                   166 |                                    233 |
|         [Luxembourg](/luxembourg) |              124 |                       136 |                     222 |                         12 |                       20 |                                       10% |                                   126 |                                    158 |
|           [Lithuania](/lithuania) |               92 |                       117 |                      42 |                         25 |                        9 |                                       27% |                                   102 |                                    141 |
|                   [Malta](/malta) |               34 |                        86 |                     175 |                         52 |                      106 |                                      154% |                                    56 |                                    162 |
|               [Estonia](/estonia) |               64 |                        77 |                      58 |                         13 |                       10 |                                       21% |                                    70 |                                     89 |
|             [Slovakia](/slovakia) |               45 |                        74 |                      14 |                         29 |                        5 |                                       64% |                                    58 |                                    105 |
|                 [Latvia](/latvia) |               37 |                        47 |                      24 |                         10 |                        5 |                                       26% |                                    41 |                                     56 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      28 |                          3 |                        3 |                                       13% |                                    23 |                                     29 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                        7 |                                       25% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          564,210 |                   679,386 |                     131 |                    115,176 |                       22 |                                       20% |                               614,503 |                                777,826 |
|                             [Brazil](/brazil) |          142,921 |                   160,560 |                     761 |                     17,639 |                       84 |                                       12% |                               151,502 |                                174,442 |
|                               [India](/india) |           96,318 |                   133,194 |                      97 |                     36,876 |                       27 |                                       38% |                               112,444 |                                154,581 |
|                             [Mexico](/mexico) |           77,163 |                    88,771 |                     696 |                     11,608 |                       91 |                                       15% |                                84,635 |                                 95,917 |
|                                 [Peru](/peru) |           32,324 |                    35,352 |                   1,087 |                      3,028 |                       93 |                                        9% |                                32,957 |                                 39,020 |
|                                 [Iran](/iran) |           25,986 |                    31,887 |                     385 |                      5,901 |                       71 |                                       23% |                                29,184 |                                 36,288 |
|                         [Colombia](/colombia) |           25,828 |                    29,990 |                     596 |                      4,162 |                       83 |                                       16% |                                27,530 |                                 33,943 |
|                       [Argentina](/argentina) |           16,519 |                    27,395 |                     612 |                     10,876 |                      243 |                                       66% |                                21,382 |                                 37,430 |
|                             [Russia](/russia) |           20,456 |                    24,768 |                     170 |                      4,312 |                       30 |                                       21% |                                21,200 |                                 31,100 |
|                 [South Africa](/south-africa) |           16,667 |                    18,161 |                     310 |                      1,494 |                       26 |                                        9% |                                17,098 |                                 20,317 |
|                       [Indonesia](/indonesia) |           10,601 |                    14,700 |                      54 |                      4,099 |                       15 |                                       39% |                                13,163 |                                 18,739 |
|                               [Chile](/chile) |           12,725 |                    14,460 |                     763 |                      1,735 |                       92 |                                       14% |                                12,898 |                                 18,491 |
|                           [Ecuador](/ecuador) |           11,312 |                    12,231 |                     704 |                        919 |                       53 |                                        8% |                                11,378 |                                 13,837 |
|                             [Turkey](/turkey) |            8,130 |                    10,598 |                     127 |                      2,468 |                       30 |                                       30% |                                 8,542 |                                 13,989 |
|                             [Canada](/canada) |            9,340 |                    10,069 |                     269 |                        729 |                       19 |                                        8% |                                 9,423 |                                 11,932 |
|                           [Bolivia](/bolivia) |            7,931 |                     8,768 |                     762 |                        837 |                       73 |                                       11% |                                 8,266 |                                  9,314 |
|                   [Philippines](/philippines) |            5,448 |                     7,488 |                      69 |                      2,040 |                       19 |                                       37% |                                 6,301 |                                  9,305 |
|                         [Pakistan](/pakistan) |            6,479 |                     6,735 |                      31 |                        256 |                        1 |                                        4% |                                 6,522 |                                  7,169 |
|                               [Egypt](/egypt) |            5,914 |                     6,520 |                      65 |                        606 |                        6 |                                       10% |                                 5,996 |                                  7,787 |
|                     [Bangladesh](/bangladesh) |            5,219 |                     6,148 |                      38 |                        929 |                        6 |                                       18% |                                 5,625 |                                  7,329 |
|                 [Saudi Arabia](/saudi-arabia) |            4,739 |                     5,568 |                     162 |                        829 |                       24 |                                       17% |                                 4,961 |                                  6,468 |
|                               [China](/china) |            4,739 |                     4,758 |                       3 |                         19 |                        0 |                                        0% |                                 4,739 |                                  4,913 |
|                           [Morocco](/morocco) |            2,152 |                     3,493 |                      96 |                      1,341 |                       37 |                                       62% |                                 2,710 |                                  4,596 |
|                         [Honduras](/honduras) |            2,323 |                     2,766 |                     284 |                        443 |                       45 |                                       19% |                                 2,450 |                                  3,256 |
|                             [Panama](/panama) |            2,364 |                     2,646 |                     623 |                        282 |                       66 |                                       12% |                                 2,481 |                                  2,945 |
|                             [Israel](/israel) |            1,528 |                     2,308 |                     271 |                        780 |                       92 |                                       51% |                                 1,802 |                                  3,326 |
|     [Dominican Republic](/dominican-republic) |            2,101 |                     2,281 |                     212 |                        180 |                       17 |                                        9% |                                 2,161 |                                  2,474 |
|                           [Algeria](/algeria) |            1,726 |                     1,841 |                      43 |                        115 |                        3 |                                        7% |                                 1,752 |                                  2,007 |
|                               [Japan](/japan) |            1,568 |                     1,761 |                      14 |                        193 |                        2 |                                       12% |                                 1,627 |                                  1,967 |
|                           [Nigeria](/nigeria) |            1,111 |                     1,193 |                       6 |                         82 |                        0 |                                        7% |                                 1,123 |                                  1,381 |
|                       [Australia](/australia) |              886 |                       965 |                      38 |                         79 |                        3 |                                        9% |                                   909 |                                  1,049 |
|                             [Kuwait](/kuwait) |              607 |                       694 |                     165 |                         87 |                       21 |                                       14% |                                   622 |                                    836 |
| [United Arab Emirates](/united-arab-emirates) |              416 |                       507 |                      52 |                         91 |                        9 |                                       22% |                                   421 |                                    673 |
|                   [South Korea](/south-korea) |              413 |                       504 |                      10 |                         91 |                        2 |                                       22% |                                   430 |                                    630 |
|                         [Malaysia](/malaysia) |              134 |                       154 |                       5 |                         20 |                        1 |                                       15% |                                   140 |                                    181 |
|                                 [Cuba](/cuba) |              122 |                       152 |                      13 |                         30 |                        3 |                                       25% |                                   129 |                                    194 |
