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

* *August 12:* We are giving a virtual talk about our model on Thursday, August 13 at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). Join us on the YouTube live stream.
* **August 10:** See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 10:* View our [updated historical performance](/about/#historical-performance).
* **August 5:** We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 12 (12pm ET):
<p align="center">
  Current Total: <b>164,534</b> deaths | Projected Total: <b>227,500 deaths by Nov 1, 2020</b> (Range: 202-262k)<br>
  Currently Infected: <b>1.8%</b> (1 in 57) | Total Infected: <b>13.1%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 12, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |        <1% |         31% |        80% |         95% |        99% |
|              225,000 |         <1% |        <1% |         <1% |         7% |         23% |        45% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          1% |         8% |
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
|             *[United States](/us)* |          164,534 |                   227,497 |                     686 |                     62,963 |                                       38% |                               202,638 |                                261,837 |
|                 [New York](/us-ny) |           32,787 |                    33,250 |                   1,709 |                        463 |                                        1% |                                32,805 |                                 35,483 |
|               [California](/us-ca) |           10,523 |                    19,087 |                     483 |                      8,564 |                                       81% |                                14,086 |                                 26,045 |
|                    [Texas](/us-tx) |            9,222 |                    18,748 |                     647 |                      9,526 |                                      103% |                                14,065 |                                 24,026 |
|                  [Florida](/us-fl) |            8,553 |                    16,495 |                     768 |                      7,942 |                                       93% |                                12,459 |                                 21,498 |
|               [New Jersey](/us-nj) |           15,890 |                    16,285 |                   1,833 |                        395 |                                        2% |                                15,928 |                                 17,350 |
|            [Massachusetts](/us-ma) |            8,751 |                     9,848 |                   1,417 |                      1,097 |                                       13% |                                 8,850 |                                 12,208 |
|                 [Illinois](/us-il) |            7,866 |                     9,650 |                     762 |                      1,784 |                                       23% |                                 8,205 |                                 12,658 |
|             [Pennsylvania](/us-pa) |            7,343 |                     8,464 |                     661 |                      1,121 |                                       15% |                                 7,443 |                                 10,555 |
|                  [Georgia](/us-ga) |            4,351 |                     7,503 |                     707 |                      3,152 |                                       72% |                                 5,692 |                                 10,446 |
|                 [Michigan](/us-mi) |            6,533 |                     7,302 |                     731 |                        769 |                                       12% |                                 6,604 |                                  8,801 |
|                  [Arizona](/us-az) |            4,199 |                     6,642 |                     913 |                      2,443 |                                       58% |                                 5,386 |                                  8,285 |
|                [Louisiana](/us-la) |            4,313 |                     5,729 |                   1,232 |                      1,416 |                                       33% |                                 4,901 |                                  6,948 |
|                     [Ohio](/us-oh) |            3,708 |                     5,484 |                     469 |                      1,776 |                                       48% |                                 4,229 |                                  7,609 |
|                 [Maryland](/us-md) |            3,604 |                     4,652 |                     769 |                      1,048 |                                       29% |                                 3,720 |                                  6,739 |
|              [Connecticut](/us-ct) |            4,444 |                     4,574 |                   1,283 |                        130 |                                        3% |                                 4,465 |                                  4,867 |
|                  [Indiana](/us-in) |            3,069 |                     4,220 |                     627 |                      1,151 |                                       38% |                                 3,204 |                                  6,222 |
|           [North Carolina](/us-nc) |            2,248 |                     4,037 |                     385 |                      1,789 |                                       80% |                                 2,935 |                                  5,830 |
|           [South Carolina](/us-sc) |            2,098 |                     4,015 |                     780 |                      1,917 |                                       91% |                                 3,046 |                                  5,253 |
|                 [Virginia](/us-va) |            2,344 |                     3,916 |                     459 |                      1,572 |                                       67% |                                 2,661 |                                  6,346 |
|              [Mississippi](/us-ms) |            1,944 |                     3,211 |                   1,079 |                      1,267 |                                       65% |                                 2,510 |                                  4,120 |
|                  [Alabama](/us-al) |            1,847 |                     3,100 |                     632 |                      1,253 |                                       68% |                                 2,408 |                                  4,020 |
|               [Washington](/us-wa) |            1,716 |                     2,897 |                     380 |                      1,181 |                                       69% |                                 2,029 |                                  4,479 |
|                [Tennessee](/us-tn) |            1,271 |                     2,563 |                     375 |                      1,292 |                                      102% |                                 1,817 |                                  3,646 |
|                 [Colorado](/us-co) |            1,874 |                     2,378 |                     413 |                        504 |                                       27% |                                 1,922 |                                  3,357 |
|                [Minnesota](/us-mn) |            1,707 |                     2,286 |                     405 |                        579 |                                       34% |                                 1,796 |                                  3,316 |
|                 [Missouri](/us-mo) |            1,346 |                     2,156 |                     351 |                        810 |                                       60% |                                 1,589 |                                  3,135 |
|                   [Nevada](/us-nv) |              981 |                     1,879 |                     610 |                        898 |                                       92% |                                 1,368 |                                  2,534 |
|                [Wisconsin](/us-wi) |            1,006 |                     1,692 |                     291 |                        686 |                                       68% |                                 1,193 |                                  2,607 |
|                     [Iowa](/us-ia) |              946 |                     1,472 |                     467 |                        526 |                                       56% |                                 1,094 |                                  2,111 |
|                 [Kentucky](/us-ky) |              783 |                     1,274 |                     285 |                        491 |                                       63% |                                   923 |                                  1,893 |
|                 [Oklahoma](/us-ok) |              618 |                     1,225 |                     310 |                        607 |                                       98% |                                   839 |                                  1,801 |
|                 [Arkansas](/us-ar) |              566 |                     1,208 |                     400 |                        642 |                                      113% |                                   848 |                                  1,707 |
|             [Rhode Island](/us-ri) |            1,016 |                     1,121 |                   1,058 |                        105 |                                       10% |                                 1,035 |                                  1,289 |
|               [New Mexico](/us-nm) |              693 |                     1,071 |                     511 |                        378 |                                       55% |                                   825 |                                  1,533 |
|              [Puerto Rico](/us-pr) |              287 |                       998 |                     312 |                        711 |                                      248% |                                   545 |                                  1,870 |
|                   [Oregon](/us-or) |              368 |                       843 |                     200 |                        475 |                                      129% |                                   531 |                                  1,332 |
|                     [Utah](/us-ut) |              349 |                       719 |                     224 |                        370 |                                      106% |                                   483 |                                  1,082 |
|                   [Kansas](/us-ks) |              393 |                       712 |                     244 |                        319 |                                       81% |                                   496 |                                  1,095 |
|                    [Idaho](/us-id) |              246 |                       678 |                     379 |                        432 |                                      176% |                                   445 |                                    981 |
|                 [Delaware](/us-de) |              591 |                       676 |                     694 |                         85 |                                       14% |                                   605 |                                    813 |
|     [District of Columbia](/us-dc) |              593 |                       652 |                     925 |                         59 |                                       10% |                                   604 |                                    754 |
|                 [Nebraska](/us-ne) |              351 |                       526 |                     272 |                        175 |                                       50% |                                   418 |                                    781 |
|            [New Hampshire](/us-nh) |              419 |                       518 |                     381 |                         99 |                                       24% |                                   429 |                                    767 |
|            [West Virginia](/us-wv) |              147 |                       465 |                     259 |                        318 |                                      216% |                                   259 |                                    848 |
|                  [Montana](/us-mt) |               77 |                       252 |                     236 |                        175 |                                      228% |                                   143 |                                    421 |
|             [North Dakota](/us-nd) |              118 |                       236 |                     309 |                        118 |                                      100% |                                   159 |                                    377 |
|             [South Dakota](/us-sd) |              146 |                       231 |                     261 |                         85 |                                       58% |                                   176 |                                    337 |
|                   [Hawaii](/us-hi) |               34 |                       178 |                     125 |                        144 |                                      422% |                                    67 |                                    469 |
|                    [Maine](/us-me) |              126 |                       155 |                     115 |                         29 |                                       23% |                                   131 |                                    200 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     119 |                         16 |                                       28% |                                    61 |                                    104 |
|                   [Alaska](/us-ak) |               26 |                        65 |                      88 |                         39 |                                      149% |                                    39 |                                    111 |
|                  [Wyoming](/us-wy) |               29 |                        49 |                      85 |                         20 |                                       70% |                                    36 |                                     74 |
|           [Virgin Islands](/us-vi) |                9 |                        21 |                     204 |                         12 |                                      138% |                                    13 |                                     36 |
|                     [Guam](/us-gu) |                5 |                         8 |                      51 |                          3 |                                       68% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       57% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,219 |                   210,867 |                     356 |                     20,648 |                                       11% |                               193,991 |                                259,299 |
| [United Kingdom](/united-kingdom) |           46,611 |                    50,756 |                     752 |                      4,145 |                                        9% |                                46,854 |                                 61,797 |
|                   [Italy](/italy) |           35,215 |                    35,976 |                     596 |                        761 |                                        2% |                                35,245 |                                 38,613 |
|                 [France](/france) |           30,328 |                    31,262 |                     467 |                        934 |                                        3% |                                30,364 |                                 36,042 |
|                   [Spain](/spain) |           28,581 |                    30,080 |                     641 |                      1,499 |                                        5% |                                28,622 |                                 36,372 |
|               [Belgium](/belgium) |            9,885 |                    10,386 |                     907 |                        501 |                                        5% |                                 9,922 |                                 12,371 |
|               [Germany](/germany) |            9,208 |                    10,293 |                     124 |                      1,085 |                                       12% |                                 9,309 |                                 13,488 |
|       [Netherlands](/netherlands) |            6,161 |                     6,524 |                     377 |                        363 |                                        6% |                                 6,187 |                                  7,966 |
|               [Romania](/romania) |            2,764 |                     6,281 |                     324 |                      3,517 |                                      127% |                                 3,899 |                                 10,874 |
|                 [Sweden](/sweden) |            5,770 |                     5,956 |                     582 |                        186 |                                        3% |                                 5,806 |                                  6,074 |
|               [Ukraine](/ukraine) |            1,979 |                     5,086 |                     116 |                      3,107 |                                      157% |                                 2,838 |                                  9,713 |
|                 [Poland](/poland) |            1,821 |                     2,892 |                      76 |                      1,071 |                                       59% |                                 2,062 |                                  4,596 |
|       [Switzerland](/switzerland) |            1,990 |                     2,088 |                     243 |                         98 |                                        5% |                                 2,003 |                                  2,487 |
|             [Portugal](/portugal) |            1,761 |                     2,050 |                     199 |                        289 |                                       16% |                                 1,773 |                                  2,688 |
|               [Ireland](/ireland) |            1,773 |                     1,865 |                     380 |                         92 |                                        5% |                                 1,785 |                                  2,141 |
|               [Moldova](/moldova) |              857 |                     1,331 |                     329 |                        474 |                                       55% |                                 1,039 |                                  1,925 |
|             [Bulgaria](/bulgaria) |              471 |                     1,256 |                     179 |                        785 |                                      167% |                                   723 |                                  2,308 |
|                 [Serbia](/serbia) |              652 |                     1,124 |                     161 |                        472 |                                       72% |                                   822 |                                  1,694 |
|               [Austria](/austria) |              723 |                       819 |                      92 |                         96 |                                       13% |                                   737 |                                  1,066 |
|               [Belarus](/belarus) |              592 |                       800 |                      85 |                        208 |                                       35% |                                   715 |                                    997 |
|               [Denmark](/denmark) |              621 |                       737 |                     127 |                        116 |                                       19% |                                   642 |                                  1,060 |
|               [Hungary](/hungary) |              605 |                       699 |                      72 |                         94 |                                       16% |                                   614 |                                    928 |
|               [Czechia](/czechia) |              391 |                       545 |                      51 |                        154 |                                       39% |                                   419 |                                    861 |
|               [Finland](/finland) |              333 |                       378 |                      68 |                         45 |                                       13% |                                   341 |                                    495 |
|                 [Greece](/greece) |              214 |                       337 |                      31 |                        123 |                                       57% |                                   241 |                                    581 |
|               [Croatia](/croatia) |              160 |                       316 |                      78 |                        156 |                                       98% |                                   206 |                                    579 |
|                 [Norway](/norway) |              256 |                       294 |                      55 |                         38 |                                       15% |                                   264 |                                    401 |
|         [Luxembourg](/luxembourg) |              122 |                       205 |                     334 |                         83 |                                       68% |                                   144 |                                    357 |
|             [Slovenia](/slovenia) |              129 |                       201 |                      96 |                         72 |                                       56% |                                   147 |                                    343 |
|           [Lithuania](/lithuania) |               81 |                        98 |                      35 |                         17 |                                       21% |                                    85 |                                    133 |
|               [Estonia](/estonia) |               63 |                        72 |                      54 |                          9 |                                       14% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        51 |                       9 |                         20 |                                       63% |                                    34 |                                     97 |
|                 [Cyprus](/cyprus) |               20 |                        43 |                      49 |                         23 |                                      114% |                                    27 |                                     81 |
|                 [Latvia](/latvia) |               32 |                        40 |                      21 |                          8 |                                       26% |                                    34 |                                     56 |
|               [Iceland](/iceland) |               10 |                        13 |                      39 |                          3 |                                       32% |                                    10 |                                     20 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       34% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          362,430 |                   662,423 |                     128 |                    299,993 |                                       83% |                               477,016 |                                974,552 |
|                             [Brazil](/brazil) |          101,752 |                   169,984 |                     805 |                     68,232 |                                       67% |                               121,109 |                                245,443 |
|                               [India](/india) |           46,091 |                   123,345 |                      90 |                     77,254 |                                      168% |                                77,489 |                                176,950 |
|                             [Mexico](/mexico) |           53,929 |                   101,250 |                     794 |                     47,321 |                                       88% |                                82,710 |                                142,298 |
|                         [Colombia](/colombia) |           13,475 |                    31,099 |                     618 |                     17,624 |                                      131% |                                21,133 |                                 48,077 |
|                                 [Peru](/peru) |           21,276 |                    30,607 |                     941 |                      9,331 |                                       44% |                                24,608 |                                 42,490 |
|                                 [Iran](/iran) |           18,800 |                    27,886 |                     336 |                      9,086 |                                       48% |                                22,114 |                                 38,420 |
|                 [South Africa](/south-africa) |           10,751 |                    24,144 |                     412 |                     13,393 |                                      125% |                                15,793 |                                 35,793 |
|                             [Russia](/russia) |           15,103 |                    21,835 |                     150 |                      6,732 |                                       45% |                                17,254 |                                 31,964 |
|                       [Argentina](/argentina) |            5,004 |                    19,069 |                     426 |                     14,065 |                                      281% |                                 9,687 |                                 33,960 |
|                               [Chile](/chile) |           10,178 |                    15,177 |                     801 |                      4,999 |                                       49% |                                10,922 |                                 26,166 |
|                       [Indonesia](/indonesia) |            5,824 |                    11,197 |                      41 |                      5,373 |                                       92% |                                 7,645 |                                 19,221 |
|                             [Canada](/canada) |            9,038 |                     9,461 |                     253 |                        423 |                                        5% |                                 9,075 |                                 10,489 |
|                           [Ecuador](/ecuador) |            5,951 |                     7,473 |                     430 |                      1,522 |                                       26% |                                 6,123 |                                 10,794 |
|                           [Bolivia](/bolivia) |            3,761 |                     7,441 |                     646 |                      3,680 |                                       98% |                                 5,057 |                                 12,046 |
|                             [Turkey](/turkey) |            5,873 |                     7,411 |                      89 |                      1,538 |                                       26% |                                 5,924 |                                 11,550 |
|                         [Pakistan](/pakistan) |            6,112 |                     7,106 |                      33 |                        994 |                                       16% |                                 6,279 |                                  8,402 |
|                               [Egypt](/egypt) |            5,059 |                     5,914 |                      59 |                        855 |                                       17% |                                 5,221 |                                  7,213 |
|                     [Bangladesh](/bangladesh) |            3,471 |                     5,534 |                      34 |                      2,063 |                                       59% |                                 3,993 |                                  9,052 |
|                   [Philippines](/philippines) |            2,312 |                     5,082 |                      47 |                      2,770 |                                      120% |                                 2,916 |                                 10,320 |
|                 [Saudi Arabia](/saudi-arabia) |            3,233 |                     4,915 |                     143 |                      1,682 |                                       52% |                                 3,785 |                                  7,425 |
|                               [China](/china) |            4,691 |                     4,905 |                       3 |                        214 |                                        5% |                                 4,691 |                                  6,376 |
|                           [Morocco](/morocco) |              533 |                     2,948 |                      81 |                      2,415 |                                      453% |                                 1,059 |                                  7,041 |
|                             [Panama](/panama) |            1,680 |                     2,935 |                     691 |                      1,255 |                                       75% |                                 2,121 |                                  4,403 |
|                         [Honduras](/honduras) |            1,515 |                     2,859 |                     293 |                      1,344 |                                       89% |                                 1,911 |                                  4,591 |
|     [Dominican Republic](/dominican-republic) |            1,346 |                     2,585 |                     241 |                      1,239 |                                       92% |                                 1,744 |                                  4,378 |
|                           [Algeria](/algeria) |            1,322 |                     2,255 |                      52 |                        933 |                                       71% |                                 1,524 |                                  3,953 |
|                               [Japan](/japan) |            1,058 |                     1,676 |                      13 |                        618 |                                       58% |                                 1,097 |                                  3,931 |
|                       [Australia](/australia) |              352 |                     1,628 |                      65 |                      1,276 |                                      362% |                                   721 |                                  3,631 |
|                             [Israel](/israel) |              622 |                     1,452 |                     170 |                        830 |                                      133% |                                   848 |                                  2,800 |
|                           [Nigeria](/nigeria) |              956 |                     1,374 |                       7 |                        418 |                                       44% |                                 1,041 |                                  2,219 |
|                             [Kuwait](/kuwait) |              486 |                       776 |                     184 |                        290 |                                       60% |                                   528 |                                  1,446 |
| [United Arab Emirates](/united-arab-emirates) |              358 |                       452 |                      46 |                         94 |                                       26% |                                   364 |                                    710 |
|                   [South Korea](/south-korea) |              305 |                       377 |                       7 |                         72 |                                       24% |                                   305 |                                    614 |
|                         [Malaysia](/malaysia) |              125 |                       142 |                       4 |                         17 |                                       13% |                                   129 |                                    159 |
|                                 [Cuba](/cuba) |               88 |                       130 |                      12 |                         42 |                                       48% |                                    96 |                                    227 |
