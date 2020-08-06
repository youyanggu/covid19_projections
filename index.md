We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](https://covid19-projections.com/estimating-true-infections), for a more detailed look into this subject.

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
* **August 5:** We released a report, [Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](https://covid19-projections.com/estimating-true-infections/#higher-infections-in-july) that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *August 3:* View our [updated historical performance](/about/#historical-performance).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

For regular updates and insights, follow our Twitter:<br>
<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: August 5 (2am ET):
<p align="center">
  Current Total: <b>156,798</b> deaths | Projected Total: <b>226,700 deaths by Nov 1, 2020</b> (Range: 198-266k)<br>
  Currently Infected: <b>1.9%</b> (1 in 53) | Total Infected: <b>12.1%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 4, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 23, 2020 |
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |        99% |         99% |       >99% |
|              200,000 |         <1% |         1% |         28% |        69% |         86% |        96% |
|              225,000 |         <1% |        <1% |         <1% |         9% |         24% |        43% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          2% |         9% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |
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
|             *[United States](/us)* |          156,798 |                   226,691 |                     683 |                     69,893 |                                       45% |                               198,635 |                                265,745 |
|                 [New York](/us-ny) |           32,725 |                    33,358 |                   1,715 |                        633 |                                        2% |                                32,759 |                                 36,286 |
|               [California](/us-ca) |            9,684 |                    18,870 |                     478 |                      9,186 |                                       95% |                                13,412 |                                 25,842 |
|                    [Texas](/us-tx) |            7,271 |                    18,089 |                     624 |                     10,818 |                                      149% |                                12,746 |                                 23,903 |
|               [New Jersey](/us-nj) |           15,857 |                    16,809 |                   1,892 |                        952 |                                        6% |                                15,927 |                                 19,097 |
|                  [Florida](/us-fl) |            7,402 |                    15,643 |                     728 |                      8,241 |                                      111% |                                11,464 |                                 20,750 |
|            [Massachusetts](/us-ma) |            8,657 |                     9,968 |                   1,434 |                      1,311 |                                       15% |                                 8,764 |                                 12,674 |
|                 [Illinois](/us-il) |            7,742 |                     9,698 |                     765 |                      1,956 |                                       25% |                                 8,143 |                                 12,852 |
|             [Pennsylvania](/us-pa) |            7,248 |                     8,423 |                     658 |                      1,175 |                                       16% |                                 7,365 |                                 10,595 |
|                 [Michigan](/us-mi) |            6,471 |                     7,335 |                     734 |                        864 |                                       13% |                                 6,544 |                                  9,320 |
|                  [Arizona](/us-az) |            3,845 |                     6,828 |                     938 |                      2,983 |                                       78% |                                 5,289 |                                  8,776 |
|                  [Georgia](/us-ga) |            3,921 |                     6,685 |                     630 |                      2,764 |                                       71% |                                 5,053 |                                  9,062 |
|                [Louisiana](/us-la) |            4,051 |                     5,588 |                   1,202 |                      1,537 |                                       38% |                                 4,610 |                                  7,037 |
|                     [Ohio](/us-oh) |            3,570 |                     5,551 |                     475 |                      1,981 |                                       55% |                                 4,142 |                                  8,003 |
|                 [Maryland](/us-md) |            3,530 |                     4,808 |                     795 |                      1,278 |                                       36% |                                 3,742 |                                  7,401 |
|              [Connecticut](/us-ct) |            4,437 |                     4,654 |                   1,305 |                        217 |                                        5% |                                 4,468 |                                  5,094 |
|                  [Indiana](/us-in) |            2,996 |                     4,273 |                     635 |                      1,277 |                                       43% |                                 3,146 |                                  6,664 |
|           [South Carolina](/us-sc) |            1,847 |                     4,226 |                     821 |                      2,379 |                                      129% |                                 2,996 |                                  5,629 |
|                 [Virginia](/us-va) |            2,244 |                     4,076 |                     478 |                      1,832 |                                       82% |                                 2,555 |                                  7,125 |
|           [North Carolina](/us-nc) |            2,061 |                     3,948 |                     376 |                      1,887 |                                       92% |                                 2,751 |                                  5,738 |
|              [Mississippi](/us-ms) |            1,753 |                     3,342 |                   1,123 |                      1,589 |                                       91% |                                 2,414 |                                  4,826 |
|                  [Alabama](/us-al) |            1,666 |                     3,059 |                     624 |                      1,393 |                                       84% |                                 2,272 |                                  4,131 |
|               [Washington](/us-wa) |            1,619 |                     2,816 |                     370 |                      1,197 |                                       74% |                                 1,839 |                                  4,806 |
|                 [Colorado](/us-co) |            1,849 |                     2,599 |                     451 |                        750 |                                       41% |                                 1,985 |                                  4,004 |
|                 [Missouri](/us-mo) |            1,290 |                     2,439 |                     397 |                      1,149 |                                       89% |                                 1,615 |                                  4,015 |
|                [Tennessee](/us-tn) |            1,117 |                     2,395 |                     350 |                      1,278 |                                      114% |                                 1,638 |                                  3,387 |
|                [Minnesota](/us-mn) |            1,660 |                     2,277 |                     404 |                        617 |                                       37% |                                 1,760 |                                  3,417 |
|                [Wisconsin](/us-wi) |              961 |                     1,768 |                     304 |                        807 |                                       84% |                                 1,140 |                                  3,046 |
|                   [Nevada](/us-nv) |              862 |                     1,750 |                     568 |                        888 |                                      103% |                                 1,266 |                                  2,410 |
|                     [Iowa](/us-ia) |              888 |                     1,428 |                     453 |                        540 |                                       61% |                                 1,029 |                                  2,205 |
|                 [Kentucky](/us-ky) |              751 |                     1,416 |                     317 |                        665 |                                       89% |                                   924 |                                  2,373 |
|                 [Oklahoma](/us-ok) |              566 |                     1,226 |                     310 |                        660 |                                      117% |                                   790 |                                  1,887 |
|             [Rhode Island](/us-ri) |            1,011 |                     1,124 |                   1,061 |                        113 |                                       11% |                                 1,033 |                                  1,299 |
|                 [Arkansas](/us-ar) |              490 |                     1,121 |                     371 |                        631 |                                      129% |                                   745 |                                  1,657 |
|               [New Mexico](/us-nm) |              658 |                     1,117 |                     533 |                        459 |                                       70% |                                   787 |                                  1,682 |
|                   [Oregon](/us-or) |              333 |                       897 |                     213 |                        564 |                                      169% |                                   522 |                                  1,494 |
|                     [Utah](/us-ut) |              321 |                       800 |                     249 |                        479 |                                      149% |                                   491 |                                  1,232 |
|                    [Idaho](/us-id) |              210 |                       798 |                     447 |                        588 |                                      280% |                                   465 |                                  1,304 |
|              [Puerto Rico](/us-pr) |              237 |                       758 |                     237 |                        521 |                                      220% |                                   402 |                                  1,459 |
|                   [Kansas](/us-ks) |              368 |                       743 |                     255 |                        375 |                                      102% |                                   483 |                                  1,198 |
|                 [Delaware](/us-de) |              587 |                       675 |                     693 |                         88 |                                       15% |                                   602 |                                    821 |
|     [District of Columbia](/us-dc) |              587 |                       651 |                     922 |                         64 |                                       11% |                                   599 |                                    758 |
|            [New Hampshire](/us-nh) |              418 |                       585 |                     430 |                        167 |                                       40% |                                   437 |                                    904 |
|                 [Nebraska](/us-ne) |              332 |                       533 |                     276 |                        201 |                                       61% |                                   403 |                                    847 |
|            [West Virginia](/us-wv) |              124 |                       334 |                     186 |                        210 |                                      169% |                                   178 |                                    639 |
|                  [Montana](/us-mt) |               64 |                       252 |                     236 |                        188 |                                      294% |                                   131 |                                    438 |
|             [South Dakota](/us-sd) |              136 |                       226 |                     255 |                         90 |                                       66% |                                   167 |                                    340 |
|             [North Dakota](/us-nd) |              107 |                       217 |                     285 |                        110 |                                      103% |                                   138 |                                    363 |
|                    [Maine](/us-me) |              123 |                       196 |                     146 |                         73 |                                       60% |                                   141 |                                    323 |
|                   [Alaska](/us-ak) |               25 |                        96 |                     131 |                         71 |                                      284% |                                    48 |                                    194 |
|                  [Vermont](/us-vt) |               57 |                        77 |                     123 |                         20 |                                       34% |                                    61 |                                    107 |
|                   [Hawaii](/us-hi) |               27 |                        75 |                      53 |                         48 |                                      179% |                                    34 |                                    182 |
|                  [Wyoming](/us-wy) |               27 |                        44 |                      77 |                         17 |                                       64% |                                    33 |                                     66 |
|           [Virgin Islands](/us-vi) |                8 |                        18 |                     176 |                         10 |                                      131% |                                    11 |                                     33 |
|                     [Guam](/us-gu) |                5 |                         9 |                      53 |                          4 |                                       76% |                                     5 |                                     17 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       57% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,835 |                   208,125 |                     351 |                     19,290 |                                       10% |                               192,330 |                                253,009 |
| [United Kingdom](/united-kingdom) |           46,295 |                    50,323 |                     745 |                      4,028 |                                        9% |                                46,604 |                                 59,135 |
|                   [Italy](/italy) |           35,171 |                    35,666 |                     591 |                        495 |                                        1% |                                35,194 |                                 37,472 |
|                 [France](/france) |           30,297 |                    31,248 |                     466 |                        951 |                                        3% |                                30,318 |                                 36,206 |
|                   [Spain](/spain) |           28,498 |                    30,555 |                     651 |                      2,057 |                                        7% |                                28,572 |                                 39,088 |
|               [Belgium](/belgium) |            9,852 |                    10,093 |                     881 |                        241 |                                        2% |                                 9,882 |                                 10,784 |
|               [Germany](/germany) |            9,163 |                     9,968 |                     120 |                        805 |                                        9% |                                 9,194 |                                 12,552 |
|       [Netherlands](/netherlands) |            6,170 |                     6,371 |                     369 |                        201 |                                        3% |                                 6,185 |                                  7,120 |
|                 [Sweden](/sweden) |            5,747 |                     6,086 |                     595 |                        339 |                                        6% |                                 5,816 |                                  6,621 |
|               [Romania](/romania) |            2,480 |                     5,829 |                     300 |                      3,349 |                                      135% |                                 3,546 |                                 10,349 |
|               [Ukraine](/ukraine) |            1,788 |                     3,539 |                      80 |                      1,751 |                                       98% |                                 2,302 |                                  5,984 |
|                 [Poland](/poland) |            1,738 |                     2,631 |                      69 |                        893 |                                       51% |                                 1,897 |                                  4,623 |
|             [Portugal](/portugal) |            1,739 |                     2,080 |                     202 |                        341 |                                       20% |                                 1,753 |                                  2,882 |
|       [Switzerland](/switzerland) |            1,981 |                     2,060 |                     240 |                         79 |                                        4% |                                 1,994 |                                  2,336 |
|               [Ireland](/ireland) |            1,763 |                     1,832 |                     374 |                         69 |                                        4% |                                 1,776 |                                  2,026 |
|               [Moldova](/moldova) |              810 |                     1,439 |                     356 |                        629 |                                       78% |                                 1,037 |                                  2,182 |
|                 [Serbia](/serbia) |              605 |                     1,304 |                     187 |                        699 |                                      116% |                                   835 |                                  2,597 |
|             [Bulgaria](/bulgaria) |              415 |                     1,300 |                     186 |                        885 |                                      213% |                                   700 |                                  2,539 |
|               [Austria](/austria) |              719 |                       844 |                      95 |                        125 |                                       17% |                                   740 |                                  1,137 |
|               [Belarus](/belarus) |              574 |                       825 |                      87 |                        251 |                                       44% |                                   721 |                                  1,021 |
|               [Denmark](/denmark) |              616 |                       713 |                     123 |                         97 |                                       16% |                                   631 |                                    932 |
|               [Hungary](/hungary) |              598 |                       680 |                      70 |                         82 |                                       14% |                                   605 |                                    892 |
|               [Czechia](/czechia) |              383 |                       585 |                      55 |                        202 |                                       53% |                                   417 |                                  1,034 |
|               [Croatia](/croatia) |              154 |                       459 |                     113 |                        305 |                                      198% |                                   239 |                                    963 |
|               [Finland](/finland) |              331 |                       375 |                      68 |                         44 |                                       13% |                                   341 |                                    467 |
|                 [Greece](/greece) |              209 |                       324 |                      30 |                        115 |                                       55% |                                   236 |                                    535 |
|                 [Norway](/norway) |              256 |                       294 |                      55 |                         38 |                                       15% |                                   263 |                                    389 |
|         [Luxembourg](/luxembourg) |              118 |                       212 |                     345 |                         94 |                                       80% |                                   138 |                                    423 |
|             [Slovenia](/slovenia) |              123 |                       182 |                      87 |                         59 |                                       48% |                                   135 |                                    295 |
|           [Lithuania](/lithuania) |               80 |                        99 |                      35 |                         19 |                                       24% |                                    85 |                                    133 |
|               [Estonia](/estonia) |               63 |                        73 |                      55 |                         10 |                                       16% |                                    69 |                                     85 |
|                 [Latvia](/latvia) |               32 |                        42 |                      22 |                         10 |                                       32% |                                    34 |                                     57 |
|             [Slovakia](/slovakia) |               29 |                        40 |                       7 |                         11 |                                       38% |                                    30 |                                     66 |
|                 [Cyprus](/cyprus) |               19 |                        27 |                      31 |                          8 |                                       43% |                                    22 |                                     43 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       38% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       41% |                                     9 |                                     19 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          333,435 |                   652,470 |                     126 |                    319,035 |                                       96% |                               444,337 |                              1,002,014 |
|                             [Brazil](/brazil) |           95,819 |                   172,210 |                     816 |                     76,391 |                                       80% |                               115,647 |                                261,011 |
|                               [India](/india) |           39,795 |                   123,100 |                      90 |                     83,305 |                                      209% |                                70,588 |                                182,927 |
|                             [Mexico](/mexico) |           48,869 |                    87,113 |                     683 |                     38,244 |                                       78% |                                70,957 |                                125,721 |
|                         [Colombia](/colombia) |           11,315 |                    33,842 |                     672 |                     22,527 |                                      199% |                                20,116 |                                 53,466 |
|                                 [Peru](/peru) |           20,007 |                    30,672 |                     943 |                     10,665 |                                       53% |                                24,024 |                                 45,460 |
|                                 [Iran](/iran) |           17,617 |                    29,219 |                     352 |                     11,602 |                                       66% |                                22,137 |                                 40,881 |
|                 [South Africa](/south-africa) |            8,884 |                    24,116 |                     412 |                     15,232 |                                      171% |                                14,961 |                                 33,753 |
|                             [Russia](/russia) |           14,327 |                    21,809 |                     150 |                      7,482 |                                       52% |                                15,721 |                                 37,788 |
|                               [Chile](/chile) |            9,745 |                    14,063 |                     742 |                      4,318 |                                       44% |                                10,529 |                                 24,972 |
|                       [Argentina](/argentina) |            3,979 |                    13,886 |                     310 |                      9,907 |                                      249% |                                 7,670 |                                 24,064 |
|                       [Indonesia](/indonesia) |            5,388 |                    13,193 |                      49 |                      7,805 |                                      145% |                                 7,480 |                                 25,783 |
|                             [Canada](/canada) |            9,005 |                     9,417 |                     252 |                        412 |                                        5% |                                 9,040 |                                 10,540 |
|                           [Bolivia](/bolivia) |            3,320 |                     8,493 |                     738 |                      5,173 |                                      156% |                                 5,078 |                                 14,023 |
|                           [Ecuador](/ecuador) |            5,808 |                     7,494 |                     431 |                      1,686 |                                       29% |                                 6,045 |                                 10,443 |
|                             [Turkey](/turkey) |            5,765 |                     7,163 |                      86 |                      1,398 |                                       24% |                                 5,825 |                                 10,786 |
|                         [Pakistan](/pakistan) |            5,999 |                     7,126 |                      33 |                      1,127 |                                       19% |                                 6,254 |                                  8,683 |
|                               [Egypt](/egypt) |            4,912 |                     6,676 |                      67 |                      1,764 |                                       36% |                                 5,134 |                                  9,083 |
|                     [Bangladesh](/bangladesh) |            3,234 |                     5,443 |                      33 |                      2,209 |                                       68% |                                 3,680 |                                  9,018 |
|                   [Philippines](/philippines) |            2,115 |                     5,160 |                      48 |                      3,045 |                                      144% |                                 2,399 |                                 13,177 |
|                               [China](/china) |            4,676 |                     5,139 |                       4 |                        463 |                                       10% |                                 4,676 |                                  7,452 |
|                 [Saudi Arabia](/saudi-arabia) |            2,984 |                     4,834 |                     141 |                      1,850 |                                       62% |                                 3,575 |                                  6,969 |
|                         [Honduras](/honduras) |            1,400 |                     3,576 |                     367 |                      2,176 |                                      155% |                                 2,076 |                                  6,982 |
|                             [Panama](/panama) |            1,522 |                     3,352 |                     789 |                      1,830 |                                      120% |                                 2,155 |                                  5,742 |
|                           [Morocco](/morocco) |              417 |                     2,781 |                      76 |                      2,364 |                                      567% |                                   781 |                                  7,316 |
|     [Dominican Republic](/dominican-republic) |            1,213 |                     2,466 |                     230 |                      1,253 |                                      103% |                                 1,572 |                                  4,383 |
|                           [Algeria](/algeria) |            1,248 |                     2,284 |                      53 |                      1,036 |                                       83% |                                 1,425 |                                  4,547 |
|                               [Japan](/japan) |            1,023 |                     1,704 |                      13 |                        681 |                                       67% |                                 1,042 |                                  5,279 |
|                             [Israel](/israel) |              561 |                     1,638 |                     192 |                      1,077 |                                      192% |                                   838 |                                  3,249 |
|                           [Nigeria](/nigeria) |              910 |                     1,391 |                       7 |                        481 |                                       53% |                                 1,019 |                                  2,443 |
|                       [Australia](/australia) |              247 |                     1,149 |                      46 |                        902 |                                      365% |                                   489 |                                  2,610 |
|                             [Kuwait](/kuwait) |              465 |                       869 |                     207 |                        404 |                                       87% |                                   514 |                                  1,777 |
| [United Arab Emirates](/united-arab-emirates) |              351 |                       448 |                      46 |                         97 |                                       28% |                                   359 |                                    731 |
|                   [South Korea](/south-korea) |              302 |                       375 |                       7 |                         73 |                                       24% |                                   302 |                                    617 |
|                         [Malaysia](/malaysia) |              125 |                       153 |                       5 |                         28 |                                       22% |                                   135 |                                    171 |
|                                 [Cuba](/cuba) |               88 |                       116 |                      10 |                         28 |                                       32% |                                    94 |                                    167 |
