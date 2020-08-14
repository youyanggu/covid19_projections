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

* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 10:* View our [updated historical performance](/about/#historical-performance).
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 14 (2am ET):
<p align="center">
  Current Total: <b>167,107</b> deaths | Projected Total: <b>228,000 deaths by Nov 1, 2020</b> (Range: 204-261k)<br>
  Currently Infected: <b>1.7%</b> (1 in 58) | Total Infected: <b>13.3%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 14, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |        <1% |         32% |        84% |         97% |        99% |
|              225,000 |         <1% |        <1% |         <1% |         6% |         24% |        47% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         8% |
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
|             *[United States](/us)* |          167,107 |                   227,952 |                     687 |                     60,845 |                                       36% |                               204,217 |                                260,524 |
|                 [New York](/us-ny) |           32,805 |                    33,241 |                   1,709 |                        436 |                                        1% |                                32,823 |                                 35,361 |
|               [California](/us-ca) |           10,870 |                    18,928 |                     479 |                      8,058 |                                       74% |                                14,267 |                                 25,592 |
|                    [Texas](/us-tx) |            9,771 |                    18,803 |                     648 |                      9,032 |                                       92% |                                14,246 |                                 23,960 |
|                  [Florida](/us-fl) |            8,913 |                    16,559 |                     771 |                      7,646 |                                       86% |                                12,833 |                                 21,205 |
|               [New Jersey](/us-nj) |           15,893 |                    16,263 |                   1,831 |                        370 |                                        2% |                                15,929 |                                 17,283 |
|            [Massachusetts](/us-ma) |            8,790 |                     9,883 |                   1,422 |                      1,093 |                                       12% |                                 8,888 |                                 12,129 |
|                 [Illinois](/us-il) |            7,905 |                     9,629 |                     760 |                      1,724 |                                       22% |                                 8,233 |                                 12,531 |
|             [Pennsylvania](/us-pa) |            7,395 |                     8,538 |                     667 |                      1,143 |                                       15% |                                 7,495 |                                 10,565 |
|                  [Georgia](/us-ga) |            4,538 |                     7,822 |                     737 |                      3,284 |                                       72% |                                 5,994 |                                 10,618 |
|                 [Michigan](/us-mi) |            6,555 |                     7,300 |                     731 |                        745 |                                       11% |                                 6,623 |                                  8,688 |
|                  [Arizona](/us-az) |            4,383 |                     6,808 |                     935 |                      2,425 |                                       55% |                                 5,569 |                                  8,354 |
|                [Louisiana](/us-la) |            4,402 |                     5,797 |                   1,247 |                      1,395 |                                       32% |                                 4,994 |                                  6,942 |
|                     [Ohio](/us-oh) |            3,755 |                     5,483 |                     469 |                      1,728 |                                       46% |                                 4,289 |                                  7,500 |
|                 [Maryland](/us-md) |            3,620 |                     4,609 |                     762 |                        989 |                                       27% |                                 3,730 |                                  6,556 |
|              [Connecticut](/us-ct) |            4,450 |                     4,577 |                   1,284 |                        127 |                                        3% |                                 4,470 |                                  4,862 |
|                  [Indiana](/us-in) |            3,105 |                     4,242 |                     630 |                      1,137 |                                       37% |                                 3,238 |                                  6,127 |
|           [South Carolina](/us-sc) |            2,184 |                     4,051 |                     787 |                      1,867 |                                       85% |                                 3,103 |                                  5,240 |
|           [North Carolina](/us-nc) |            2,287 |                     3,961 |                     378 |                      1,674 |                                       73% |                                 2,943 |                                  5,596 |
|                 [Virginia](/us-va) |            2,363 |                     3,782 |                     443 |                      1,419 |                                       60% |                                 2,662 |                                  5,968 |
|              [Mississippi](/us-ms) |            2,011 |                     3,240 |                   1,089 |                      1,229 |                                       61% |                                 2,574 |                                  4,083 |
|                  [Alabama](/us-al) |            1,890 |                     3,086 |                     629 |                      1,196 |                                       63% |                                 2,434 |                                  3,948 |
|               [Washington](/us-wa) |            1,736 |                     2,849 |                     374 |                      1,113 |                                       64% |                                 2,044 |                                  4,309 |
|                [Tennessee](/us-tn) |            1,313 |                     2,590 |                     379 |                      1,277 |                                       97% |                                 1,868 |                                  3,632 |
|                 [Colorado](/us-co) |            1,882 |                     2,357 |                     409 |                        475 |                                       25% |                                 1,928 |                                  3,251 |
|                [Minnesota](/us-mn) |            1,731 |                     2,317 |                     411 |                        586 |                                       34% |                                 1,826 |                                  3,321 |
|                 [Missouri](/us-mo) |            1,356 |                     2,111 |                     344 |                        755 |                                       56% |                                 1,585 |                                  3,036 |
|                   [Nevada](/us-nv) |            1,030 |                     1,966 |                     638 |                        936 |                                       91% |                                 1,462 |                                  2,594 |
|                [Wisconsin](/us-wi) |            1,018 |                     1,650 |                     283 |                        632 |                                       62% |                                 1,195 |                                  2,497 |
|                     [Iowa](/us-ia) |              960 |                     1,467 |                     465 |                        507 |                                       53% |                                 1,108 |                                  2,057 |
|                 [Kentucky](/us-ky) |              796 |                     1,274 |                     285 |                        478 |                                       60% |                                   937 |                                  1,855 |
|                 [Oklahoma](/us-ok) |              638 |                     1,247 |                     315 |                        609 |                                       95% |                                   866 |                                  1,797 |
|                 [Arkansas](/us-ar) |              582 |                     1,195 |                     396 |                        613 |                                      105% |                                   850 |                                  1,670 |
|             [Rhode Island](/us-ri) |            1,019 |                     1,121 |                   1,058 |                        102 |                                       10% |                                 1,037 |                                  1,285 |
|               [New Mexico](/us-nm) |              697 |                     1,039 |                     495 |                        342 |                                       49% |                                   819 |                                  1,455 |
|              [Puerto Rico](/us-pr) |              306 |                     1,039 |                     325 |                        733 |                                      239% |                                   577 |                                  1,866 |
|                   [Oregon](/us-or) |              383 |                       868 |                     206 |                        485 |                                      127% |                                   557 |                                  1,343 |
|                   [Kansas](/us-ks) |              403 |                       722 |                     248 |                        319 |                                       79% |                                   508 |                                  1,088 |
|                     [Utah](/us-ut) |              353 |                       684 |                     213 |                        331 |                                       94% |                                   471 |                                  1,019 |
|                 [Delaware](/us-de) |              593 |                       675 |                     693 |                         82 |                                       14% |                                   606 |                                    809 |
|     [District of Columbia](/us-dc) |              594 |                       651 |                     923 |                         57 |                                       10% |                                   605 |                                    749 |
|                    [Idaho](/us-id) |              251 |                       625 |                     350 |                        374 |                                      149% |                                   419 |                                    904 |
|                 [Nebraska](/us-ne) |              360 |                       540 |                     279 |                        180 |                                       50% |                                   428 |                                    796 |
|            [New Hampshire](/us-nh) |              422 |                       517 |                     380 |                         95 |                                       23% |                                   431 |                                    759 |
|            [West Virginia](/us-wv) |              153 |                       470 |                     262 |                        317 |                                      207% |                                   269 |                                    823 |
|                   [Hawaii](/us-hi) |               40 |                       292 |                     206 |                        252 |                                      631% |                                   107 |                                    659 |
|                  [Montana](/us-mt) |               81 |                       252 |                     236 |                        171 |                                      211% |                                   145 |                                    411 |
|             [North Dakota](/us-nd) |              120 |                       229 |                     300 |                        109 |                                       91% |                                   159 |                                    354 |
|             [South Dakota](/us-sd) |              148 |                       229 |                     259 |                         81 |                                       55% |                                   177 |                                    327 |
|                    [Maine](/us-me) |              126 |                       154 |                     115 |                         28 |                                       23% |                                   131 |                                    198 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     119 |                         16 |                                       28% |                                    61 |                                    103 |
|                   [Alaska](/us-ak) |               27 |                        65 |                      89 |                         38 |                                      140% |                                    40 |                                    109 |
|                  [Wyoming](/us-wy) |               30 |                        52 |                      90 |                         22 |                                       74% |                                    40 |                                     80 |
|           [Virgin Islands](/us-vi) |                9 |                        19 |                     181 |                         10 |                                      111% |                                    12 |                                     31 |
|                     [Guam](/us-gu) |                5 |                         8 |                      50 |                          3 |                                       66% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       56% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,810 |                   209,888 |                     354 |                     19,078 |                                       10% |                               194,557 |                                253,493 |
| [United Kingdom](/united-kingdom) |           46,791 |                    49,900 |                     739 |                      3,109 |                                        7% |                                46,944 |                                 58,297 |
|                   [Italy](/italy) |           35,231 |                    35,961 |                     596 |                        730 |                                        2% |                                35,260 |                                 38,529 |
|                 [France](/france) |           30,392 |                    31,311 |                     467 |                        919 |                                        3% |                                30,428 |                                 35,934 |
|                   [Spain](/spain) |           28,605 |                    30,010 |                     639 |                      1,405 |                                        5% |                                28,644 |                                 35,378 |
|               [Belgium](/belgium) |            9,916 |                    10,435 |                     911 |                        519 |                                        5% |                                 9,954 |                                 12,446 |
|               [Germany](/germany) |            9,217 |                    10,222 |                     123 |                      1,005 |                                       11% |                                 9,311 |                                 13,123 |
|       [Netherlands](/netherlands) |            6,187 |                     6,567 |                     380 |                        380 |                                        6% |                                 6,213 |                                  8,040 |
|               [Romania](/romania) |            2,860 |                     6,561 |                     338 |                      3,701 |                                      129% |                                 4,139 |                                 11,086 |
|                 [Sweden](/sweden) |            5,776 |                     5,950 |                     582 |                        174 |                                        3% |                                 5,809 |                                  6,063 |
|               [Ukraine](/ukraine) |            2,023 |                     4,792 |                     109 |                      2,769 |                                      137% |                                 2,820 |                                  9,037 |
|                 [Poland](/poland) |            1,844 |                     2,932 |                      77 |                      1,088 |                                       59% |                                 2,125 |                                  4,606 |
|       [Switzerland](/switzerland) |            1,991 |                     2,085 |                     243 |                         94 |                                        5% |                                 2,004 |                                  2,470 |
|             [Portugal](/portugal) |            1,770 |                     2,065 |                     201 |                        295 |                                       17% |                                 1,782 |                                  2,717 |
|               [Ireland](/ireland) |            1,774 |                     1,863 |                     380 |                         89 |                                        5% |                                 1,785 |                                  2,128 |
|               [Moldova](/moldova) |              878 |                     1,387 |                     343 |                        509 |                                       58% |                                 1,073 |                                  2,015 |
|             [Bulgaria](/bulgaria) |              482 |                     1,146 |                     164 |                        664 |                                      138% |                                   704 |                                  2,209 |
|                 [Serbia](/serbia) |              661 |                     1,070 |                     154 |                        409 |                                       62% |                                   814 |                                  1,553 |
|               [Austria](/austria) |              725 |                       821 |                      93 |                         96 |                                       13% |                                   739 |                                  1,066 |
|               [Belarus](/belarus) |              599 |                       801 |                      85 |                        202 |                                       34% |                                   718 |                                    990 |
|               [Denmark](/denmark) |              621 |                       727 |                     125 |                        106 |                                       17% |                                   641 |                                  1,012 |
|               [Hungary](/hungary) |              607 |                       700 |                      72 |                         93 |                                       15% |                                   616 |                                    928 |
|               [Czechia](/czechia) |              391 |                       518 |                      49 |                        127 |                                       32% |                                   415 |                                    757 |
|                 [Greece](/greece) |              221 |                       414 |                      39 |                        193 |                                       88% |                                   272 |                                    703 |
|               [Finland](/finland) |              333 |                       375 |                      68 |                         42 |                                       13% |                                   340 |                                    488 |
|                 [Norway](/norway) |              257 |                       295 |                      55 |                         38 |                                       15% |                                   264 |                                    401 |
|               [Croatia](/croatia) |              161 |                       286 |                      70 |                        125 |                                       78% |                                   197 |                                    481 |
|             [Slovenia](/slovenia) |              129 |                       193 |                      93 |                         64 |                                       49% |                                   144 |                                    306 |
|         [Luxembourg](/luxembourg) |              122 |                       184 |                     299 |                         62 |                                       51% |                                   139 |                                    282 |
|           [Lithuania](/lithuania) |               81 |                        96 |                      34 |                         15 |                                       19% |                                    84 |                                    127 |
|               [Estonia](/estonia) |               63 |                        72 |                      54 |                          9 |                                       14% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        49 |                       9 |                         18 |                                       57% |                                    33 |                                     91 |
|                 [Latvia](/latvia) |               32 |                        40 |                      21 |                          8 |                                       24% |                                    33 |                                     54 |
|                 [Cyprus](/cyprus) |               20 |                        36 |                      41 |                         16 |                                       80% |                                    25 |                                     62 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     19 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       32% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          373,182 |                   672,980 |                     130 |                    299,798 |                                       80% |                               496,201 |                                969,164 |
|                             [Brazil](/brazil) |          105,463 |                   179,258 |                     849 |                     73,795 |                                       70% |                               133,195 |                                248,038 |
|                               [India](/india) |           48,040 |                   123,782 |                      91 |                     75,742 |                                      158% |                                80,388 |                                176,361 |
|                             [Mexico](/mexico) |           55,293 |                   100,651 |                     789 |                     45,358 |                                       82% |                                83,087 |                                139,706 |
|                         [Colombia](/colombia) |           14,145 |                    31,407 |                     624 |                     17,262 |                                      122% |                                21,592 |                                 47,774 |
|                                 [Peru](/peru) |           21,713 |                    30,802 |                     947 |                      9,089 |                                       42% |                                25,259 |                                 41,713 |
|                                 [Iran](/iran) |           19,162 |                    27,978 |                     337 |                      8,816 |                                       46% |                                22,518 |                                 38,204 |
|                 [South Africa](/south-africa) |           11,270 |                    23,918 |                     408 |                     12,648 |                                      112% |                                16,431 |                                 34,737 |
|                             [Russia](/russia) |           15,353 |                    22,075 |                     151 |                      6,722 |                                       44% |                                17,493 |                                 31,735 |
|                       [Argentina](/argentina) |            5,362 |                    19,206 |                     429 |                     13,844 |                                      258% |                                 9,926 |                                 33,144 |
|                               [Chile](/chile) |           10,299 |                    15,271 |                     806 |                      4,972 |                                       48% |                                11,024 |                                 26,055 |
|                       [Indonesia](/indonesia) |            5,968 |                    11,087 |                      41 |                      5,119 |                                       86% |                                 7,720 |                                 18,713 |
|                             [Canada](/canada) |            9,063 |                     9,498 |                     254 |                        435 |                                        5% |                                 9,099 |                                 10,533 |
|                           [Ecuador](/ecuador) |            6,010 |                     7,461 |                     429 |                      1,451 |                                       24% |                                 6,174 |                                 10,618 |
|                             [Turkey](/turkey) |            5,912 |                     7,410 |                      89 |                      1,498 |                                       25% |                                 5,988 |                                 11,295 |
|                           [Bolivia](/bolivia) |            3,884 |                     7,287 |                     633 |                      3,403 |                                       88% |                                 5,112 |                                 11,431 |
|                         [Pakistan](/pakistan) |            6,139 |                     7,078 |                      33 |                        939 |                                       15% |                                 6,290 |                                  8,324 |
|                               [Egypt](/egypt) |            5,107 |                     5,921 |                      59 |                        814 |                                       16% |                                 5,252 |                                  7,157 |
|                     [Bangladesh](/bangladesh) |            3,557 |                     5,635 |                      35 |                      2,078 |                                       58% |                                 4,084 |                                  9,133 |
|                   [Philippines](/philippines) |            2,426 |                     5,623 |                      52 |                      3,197 |                                      132% |                                 3,131 |                                 11,161 |
|                 [Saudi Arabia](/saudi-arabia) |            3,303 |                     4,927 |                     144 |                      1,624 |                                       49% |                                 3,853 |                                  7,192 |
|                               [China](/china) |            4,700 |                     4,913 |                       3 |                        213 |                                        5% |                                 4,700 |                                  6,377 |
|                           [Morocco](/morocco) |              584 |                     3,255 |                      89 |                      2,671 |                                      457% |                                 1,249 |                                  7,312 |
|                             [Panama](/panama) |            1,722 |                     2,879 |                     678 |                      1,157 |                                       67% |                                 2,141 |                                  4,197 |
|                         [Honduras](/honduras) |            1,542 |                     2,741 |                     281 |                      1,199 |                                       78% |                                 1,915 |                                  4,401 |
|     [Dominican Republic](/dominican-republic) |            1,393 |                     2,673 |                     249 |                      1,280 |                                       92% |                                 1,808 |                                  4,407 |
|                           [Algeria](/algeria) |            1,341 |                     2,234 |                      52 |                        893 |                                       67% |                                 1,542 |                                  3,838 |
|                               [Japan](/japan) |            1,073 |                     1,740 |                      14 |                        667 |                                       62% |                                 1,119 |                                  4,111 |
|                       [Australia](/australia) |              375 |                     1,550 |                      61 |                      1,175 |                                      313% |                                   736 |                                  3,445 |
|                             [Israel](/israel) |              651 |                     1,521 |                     178 |                        870 |                                      134% |                                   908 |                                  2,866 |
|                           [Nigeria](/nigeria) |              966 |                     1,354 |                       7 |                        388 |                                       40% |                                 1,044 |                                  2,146 |
|                             [Kuwait](/kuwait) |              489 |                       751 |                     179 |                        262 |                                       54% |                                   528 |                                  1,360 |
| [United Arab Emirates](/united-arab-emirates) |              358 |                       446 |                      46 |                         88 |                                       25% |                                   364 |                                    686 |
|                   [South Korea](/south-korea) |              305 |                       374 |                       7 |                         69 |                                       23% |                                   305 |                                    610 |
|                         [Malaysia](/malaysia) |              125 |                       141 |                       4 |                         16 |                                       13% |                                   129 |                                    158 |
|                                 [Cuba](/cuba) |               89 |                       132 |                      12 |                         43 |                                       48% |                                    97 |                                    226 |
