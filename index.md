We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by half.

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

* **August 31:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 4 (2am ET):
<p align="center">
  Current Total: <b>186,787</b> deaths | Projected Total: <b>220,300 deaths by Nov 1, 2020</b> (Range: 207-239k)<br>
  Currently Infected: <b>1.1%</b> (1 in 90) | Total Infected: <b>14.8%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 4, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |          2% |        97% |         99% |        99% |
|              225,000 |         <1% |        <1% |          4% |        21% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |

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

|                                    |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          186,787 |                   220,341 |                     664 |                     33,554 |                      101 |                                       18% |                               207,779 |                                238,963 |
|                 [New York](/us-ny) |           32,976 |                    33,382 |                   1,716 |                        406 |                       21 |                                        1% |                                32,989 |                                 35,708 |
|               [California](/us-ca) |           13,493 |                    18,536 |                     469 |                      5,043 |                      128 |                                       37% |                                16,021 |                                 22,916 |
|                    [Texas](/us-tx) |           13,296 |                    18,173 |                     627 |                      4,877 |                      168 |                                       37% |                                15,992 |                                 21,068 |
|               [New Jersey](/us-nj) |           15,971 |                    16,148 |                   1,818 |                        177 |                       20 |                                        1% |                                15,984 |                                 16,762 |
|                  [Florida](/us-fl) |           11,650 |                    14,616 |                     681 |                      2,966 |                      138 |                                       25% |                                13,072 |                                 16,628 |
|            [Massachusetts](/us-ma) |            9,077 |                     9,568 |                   1,377 |                        491 |                       71 |                                        5% |                                 9,106 |                                 10,568 |
|                 [Illinois](/us-il) |            8,324 |                     9,313 |                     735 |                        989 |                       78 |                                       12% |                                 8,436 |                                 10,673 |
|             [Pennsylvania](/us-pa) |            7,724 |                     8,400 |                     656 |                        676 |                       53 |                                        9% |                                 7,756 |                                  9,757 |
|                  [Georgia](/us-ga) |            5,868 |                     8,032 |                     756 |                      2,164 |                      204 |                                       37% |                                 6,974 |                                  9,602 |
|                 [Michigan](/us-mi) |            6,791 |                     7,281 |                     729 |                        490 |                       49 |                                        7% |                                 6,833 |                                  8,109 |
|                  [Arizona](/us-az) |            5,130 |                     5,959 |                     819 |                        829 |                      114 |                                       16% |                                 5,474 |                                  6,667 |
|                [Louisiana](/us-la) |            5,021 |                     5,860 |                   1,261 |                        839 |                      181 |                                       17% |                                 5,371 |                                  6,642 |
|                     [Ohio](/us-oh) |            4,226 |                     4,998 |                     428 |                        772 |                       66 |                                       18% |                                 4,413 |                                  5,950 |
|              [Connecticut](/us-ct) |            4,468 |                     4,552 |                   1,277 |                         84 |                       23 |                                        2% |                                 4,478 |                                  4,809 |
|                 [Maryland](/us-md) |            3,778 |                     4,154 |                     687 |                        376 |                       62 |                                       10% |                                 3,813 |                                  4,863 |
|           [North Carolina](/us-nc) |            2,803 |                     3,913 |                     373 |                      1,110 |                      106 |                                       40% |                                 3,321 |                                  4,920 |
|                  [Indiana](/us-in) |            3,332 |                     3,794 |                     563 |                        462 |                       69 |                                       14% |                                 3,359 |                                  4,719 |
|           [South Carolina](/us-sc) |            2,807 |                     3,727 |                     724 |                        920 |                      179 |                                       33% |                                 3,270 |                                  4,407 |
|                 [Virginia](/us-va) |            2,652 |                     3,239 |                     379 |                        587 |                       69 |                                       22% |                                 2,692 |                                  4,077 |
|              [Mississippi](/us-ms) |            2,536 |                     3,233 |                   1,086 |                        697 |                      234 |                                       27% |                                 2,856 |                                  3,774 |
|                  [Alabama](/us-al) |            2,233 |                     2,877 |                     587 |                        644 |                      131 |                                       29% |                                 2,535 |                                  3,414 |
|                [Tennessee](/us-tn) |            1,815 |                     2,744 |                     402 |                        929 |                      136 |                                       51% |                                 2,301 |                                  3,450 |
|               [Washington](/us-wa) |            1,945 |                     2,358 |                     310 |                        413 |                       54 |                                       21% |                                 2,037 |                                  2,903 |
|                [Minnesota](/us-mn) |            1,889 |                     2,282 |                     405 |                        393 |                       70 |                                       21% |                                 1,955 |                                  2,833 |
|                 [Missouri](/us-mo) |            1,586 |                     2,180 |                     355 |                        594 |                       97 |                                       37% |                                 1,834 |                                  2,769 |
|                 [Colorado](/us-co) |            1,955 |                     2,132 |                     370 |                        177 |                       31 |                                        9% |                                 1,966 |                                  2,624 |
|                   [Nevada](/us-nv) |            1,363 |                     1,902 |                     618 |                        539 |                      175 |                                       40% |                                 1,642 |                                  2,271 |
|                     [Iowa](/us-ia) |            1,136 |                     1,702 |                     539 |                        566 |                      179 |                                       50% |                                 1,317 |                                  2,490 |
|                [Wisconsin](/us-wi) |            1,146 |                     1,537 |                     264 |                        391 |                       67 |                                       34% |                                 1,303 |                                  1,936 |
|                 [Arkansas](/us-ar) |              861 |                     1,413 |                     468 |                        552 |                      183 |                                       64% |                                 1,139 |                                  1,820 |
|                 [Kentucky](/us-ky) |              976 |                     1,400 |                     313 |                        424 |                       95 |                                       43% |                                 1,147 |                                  1,801 |
|                 [Oklahoma](/us-ok) |              835 |                     1,287 |                     325 |                        452 |                      114 |                                       54% |                                 1,044 |                                  1,686 |
|             [Rhode Island](/us-ri) |            1,055 |                     1,130 |                   1,067 |                         75 |                       71 |                                        7% |                                 1,064 |                                  1,288 |
|               [New Mexico](/us-nm) |              791 |                       953 |                     454 |                        162 |                       77 |                                       20% |                                   850 |                                  1,115 |
|              [Puerto Rico](/us-pr) |              448 |                       791 |                     248 |                        343 |                      107 |                                       76% |                                   612 |                                  1,075 |
|                   [Oregon](/us-or) |              470 |                       727 |                     172 |                        257 |                       61 |                                       55% |                                   580 |                                    965 |
|                   [Kansas](/us-ks) |              471 |                       669 |                     230 |                        198 |                       68 |                                       42% |                                   551 |                                    872 |
|                 [Delaware](/us-de) |              606 |                       651 |                     669 |                         45 |                       46 |                                        7% |                                   611 |                                    740 |
|     [District of Columbia](/us-dc) |              609 |                       637 |                     903 |                         28 |                       40 |                                        5% |                                   613 |                                    693 |
|                    [Idaho](/us-id) |              372 |                       594 |                     333 |                        222 |                      124 |                                       60% |                                   486 |                                    755 |
|                     [Utah](/us-ut) |              414 |                       578 |                     180 |                        164 |                       51 |                                       40% |                                   486 |                                    725 |
|                 [Nebraska](/us-ne) |              404 |                       531 |                     274 |                        127 |                       66 |                                       31% |                                   438 |                                    680 |
|            [West Virginia](/us-wv) |              240 |                       470 |                     262 |                        230 |                      128 |                                       96% |                                   349 |                                    671 |
|            [New Hampshire](/us-nh) |              432 |                       460 |                     338 |                         28 |                       20 |                                        6% |                                   434 |                                    527 |
|                   [Hawaii](/us-hi) |               79 |                       285 |                     201 |                        206 |                      145 |                                      260% |                                   166 |                                    497 |
|             [South Dakota](/us-sd) |              169 |                       257 |                     290 |                         88 |                       99 |                                       52% |                                   180 |                                    454 |
|             [North Dakota](/us-nd) |              150 |                       254 |                     333 |                        104 |                      137 |                                       69% |                                   192 |                                    362 |
|                  [Montana](/us-mt) |              111 |                       205 |                     192 |                         94 |                       88 |                                       85% |                                   153 |                                    290 |
|                    [Maine](/us-me) |              133 |                       150 |                     111 |                         17 |                       12 |                                       13% |                                   136 |                                    174 |
|                   [Alaska](/us-ak) |               40 |                        77 |                     105 |                         37 |                       50 |                                       92% |                                    57 |                                    113 |
|                  [Wyoming](/us-wy) |               41 |                        69 |                     120 |                         28 |                       49 |                                       69% |                                    55 |                                     99 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     107 |                          8 |                       14 |                                       15% |                                    60 |                                     80 |
|                     [Guam](/us-gu) |               13 |                        49 |                     296 |                         36 |                      217 |                                      277% |                                    29 |                                     85 |
|           [Virgin Islands](/us-vi) |               16 |                        41 |                     395 |                         25 |                      243 |                                      159% |                                    29 |                                     63 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      52 |                          1 |                       16 |                                       43% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,735 |                   204,323 |                     344 |                     14,588 |                       25 |                                        8% |                               192,965 |                                239,157 |
| [United Kingdom](/united-kingdom) |           41,616 |                    42,105 |                     623 |                        489 |                        7 |                                        1% |                                41,625 |                                 44,261 |
|                   [Italy](/italy) |           35,507 |                    36,121 |                     598 |                        614 |                       10 |                                        2% |                                35,522 |                                 38,849 |
|                 [France](/france) |           30,712 |                    32,193 |                     480 |                      1,481 |                       22 |                                        5% |                                30,744 |                                 40,015 |
|                   [Spain](/spain) |           29,234 |                    31,714 |                     676 |                      2,480 |                       53 |                                        8% |                                29,266 |                                 41,067 |
|               [Belgium](/belgium) |            9,899 |                    10,071 |                     879 |                        172 |                       15 |                                        2% |                                 9,917 |                                 10,715 |
|               [Germany](/germany) |            9,322 |                     9,719 |                     117 |                        397 |                        5 |                                        4% |                                 9,339 |                                 11,037 |
|       [Netherlands](/netherlands) |            6,268 |                     6,469 |                     374 |                        201 |                       12 |                                        3% |                                 6,282 |                                  7,192 |
|               [Romania](/romania) |            3,765 |                     6,055 |                     312 |                      2,290 |                      118 |                                       61% |                                 4,708 |                                  8,121 |
|                 [Sweden](/sweden) |            5,832 |                     5,879 |                     575 |                         47 |                        5 |                                        1% |                                 5,837 |                                  6,035 |
|               [Ukraine](/ukraine) |            2,759 |                     5,767 |                     131 |                      3,008 |                       68 |                                      109% |                                 3,828 |                                  8,896 |
|                 [Poland](/poland) |            2,092 |                     2,878 |                      76 |                        786 |                       21 |                                       38% |                                 2,331 |                                  3,885 |
|       [Switzerland](/switzerland) |            2,013 |                     2,086 |                     243 |                         73 |                        9 |                                        4% |                                 2,025 |                                  2,294 |
|             [Portugal](/portugal) |            1,829 |                     1,979 |                     193 |                        150 |                       15 |                                        8% |                                 1,835 |                                  2,367 |
|               [Ireland](/ireland) |            1,777 |                     1,819 |                     371 |                         42 |                        9 |                                        2% |                                 1,784 |                                  1,945 |
|               [Moldova](/moldova) |            1,036 |                     1,488 |                     368 |                        452 |                      112 |                                       44% |                                 1,197 |                                  1,973 |
|             [Bulgaria](/bulgaria) |              658 |                     1,292 |                     185 |                        634 |                       91 |                                       96% |                                   912 |                                  1,912 |
|               [Belarus](/belarus) |              696 |                       989 |                     105 |                        293 |                       31 |                                       42% |                                   787 |                                  1,416 |
|                 [Serbia](/serbia) |              718 |                       885 |                     127 |                        167 |                       24 |                                       23% |                                   782 |                                  1,046 |
|               [Austria](/austria) |              735 |                       785 |                      89 |                         50 |                        6 |                                        7% |                                   744 |                                    911 |
|               [Hungary](/hungary) |              620 |                       671 |                      69 |                         51 |                        5 |                                        8% |                                   624 |                                    811 |
|               [Denmark](/denmark) |              626 |                       665 |                     115 |                         39 |                        7 |                                        6% |                                   634 |                                    773 |
|                 [Greece](/greece) |              278 |                       529 |                      49 |                        251 |                       23 |                                       90% |                                   375 |                                    819 |
|               [Czechia](/czechia) |              426 |                       522 |                      49 |                         96 |                        9 |                                       23% |                                   447 |                                    672 |
|               [Finland](/finland) |              336 |                       355 |                      64 |                         19 |                        3 |                                        6% |                                   339 |                                    411 |
|               [Croatia](/croatia) |              194 |                       333 |                      82 |                        139 |                       34 |                                       72% |                                   246 |                                    505 |
|                 [Norway](/norway) |              264 |                       287 |                      53 |                         23 |                        4 |                                        9% |                                   269 |                                    344 |
|             [Slovenia](/slovenia) |              134 |                       155 |                      74 |                         21 |                       10 |                                       15% |                                   137 |                                    193 |
|         [Luxembourg](/luxembourg) |              124 |                       146 |                     238 |                         22 |                       36 |                                       18% |                                   131 |                                    177 |
|           [Lithuania](/lithuania) |               86 |                       101 |                      36 |                         15 |                        5 |                                       17% |                                    89 |                                    122 |
|             [Slovakia](/slovakia) |               37 |                        81 |                      15 |                         44 |                        8 |                                      119% |                                    51 |                                    152 |
|               [Estonia](/estonia) |               64 |                        70 |                      53 |                          6 |                        5 |                                       10% |                                    67 |                                     78 |
|                 [Latvia](/latvia) |               34 |                        40 |                      21 |                          6 |                        3 |                                       18% |                                    35 |                                     49 |
|                   [Malta](/malta) |               13 |                        35 |                      72 |                         22 |                       45 |                                      172% |                                    22 |                                     61 |
|                 [Cyprus](/cyprus) |               21 |                        29 |                      33 |                          8 |                        9 |                                       37% |                                    24 |                                     38 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        6 |                                       20% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          462,002 |                   657,224 |                     127 |                    195,222 |                       38 |                                       42% |                               543,858 |                                858,914 |
|                             [Brazil](/brazil) |          124,614 |                   166,689 |                     790 |                     42,075 |                      199 |                                       34% |                               143,398 |                                202,296 |
|                               [India](/india) |           68,472 |                   126,115 |                      92 |                     57,643 |                       42 |                                       84% |                                92,479 |                                188,288 |
|                             [Mexico](/mexico) |           66,329 |                    91,247 |                     715 |                     24,918 |                      195 |                                       38% |                                81,563 |                                106,759 |
|                                 [Peru](/peru) |           29,068 |                    34,645 |                   1,066 |                      5,577 |                      172 |                                       19% |                                30,824 |                                 41,131 |
|                         [Colombia](/colombia) |           20,618 |                    31,713 |                     630 |                     11,095 |                      220 |                                       54% |                                25,481 |                                 40,766 |
|                                 [Iran](/iran) |           21,926 |                    27,159 |                     328 |                      5,233 |                       63 |                                       24% |                                23,481 |                                 33,224 |
|                             [Russia](/russia) |           17,479 |                    21,766 |                     149 |                      4,287 |                       29 |                                       25% |                                18,424 |                                 30,212 |
|                 [South Africa](/south-africa) |           14,563 |                    20,063 |                     343 |                      5,500 |                       94 |                                       38% |                                16,830 |                                 27,784 |
|                       [Argentina](/argentina) |            9,361 |                    19,266 |                     430 |                      9,905 |                      221 |                                      106% |                                13,521 |                                 26,609 |
|                               [Chile](/chile) |           11,422 |                    14,479 |                     764 |                      3,057 |                      161 |                                       27% |                                11,887 |                                 21,437 |
|                       [Indonesia](/indonesia) |            7,750 |                    12,746 |                      47 |                      4,996 |                       18 |                                       64% |                                 9,648 |                                 19,743 |
|                             [Canada](/canada) |            9,189 |                     9,459 |                     253 |                        270 |                        7 |                                        3% |                                 9,220 |                                 10,142 |
|                           [Bolivia](/bolivia) |            5,288 |                     8,079 |                     702 |                      2,791 |                      242 |                                       53% |                                 6,397 |                                 10,393 |
|                             [Turkey](/turkey) |            6,511 |                     7,983 |                      96 |                      1,472 |                       18 |                                       23% |                                 6,630 |                                 10,655 |
|                           [Ecuador](/ecuador) |            6,648 |                     7,668 |                     441 |                      1,020 |                       59 |                                       15% |                                 6,737 |                                  9,934 |
|                   [Philippines](/philippines) |            3,688 |                     7,150 |                      66 |                      3,462 |                       32 |                                       94% |                                 4,828 |                                 11,156 |
|                         [Pakistan](/pakistan) |            6,335 |                     6,718 |                      31 |                        383 |                        2 |                                        6% |                                 6,361 |                                  7,611 |
|                     [Bangladesh](/bangladesh) |            4,383 |                     6,213 |                      38 |                      1,830 |                       11 |                                       42% |                                 4,981 |                                  8,473 |
|                               [Egypt](/egypt) |            5,479 |                     6,136 |                      61 |                        657 |                        7 |                                       12% |                                 5,524 |                                  8,489 |
|                 [Saudi Arabia](/saudi-arabia) |            3,982 |                     5,219 |                     152 |                      1,237 |                       36 |                                       31% |                                 4,363 |                                  6,686 |
|                               [China](/china) |            4,728 |                     4,804 |                       3 |                         76 |                        0 |                                        2% |                                 4,728 |                                  5,403 |
|                           [Morocco](/morocco) |            1,253 |                     3,378 |                      93 |                      2,125 |                       58 |                                      170% |                                 1,949 |                                  5,463 |
|                         [Honduras](/honduras) |            1,954 |                     2,861 |                     294 |                        907 |                       93 |                                       46% |                                 2,275 |                                  3,876 |
|     [Dominican Republic](/dominican-republic) |            1,801 |                     2,841 |                     265 |                      1,040 |                       97 |                                       58% |                                 2,181 |                                  4,031 |
|                             [Panama](/panama) |            2,046 |                     2,540 |                     598 |                        494 |                      116 |                                       24% |                                 2,254 |                                  3,128 |
|                           [Algeria](/algeria) |            1,529 |                     2,103 |                      49 |                        574 |                       13 |                                       38% |                                 1,629 |                                  3,117 |
|                               [Japan](/japan) |            1,334 |                     2,060 |                      16 |                        726 |                        6 |                                       54% |                                 1,514 |                                  3,446 |
|                             [Israel](/israel) |              985 |                     1,857 |                     218 |                        872 |                      102 |                                       88% |                                 1,246 |                                  2,964 |
|                           [Nigeria](/nigeria) |            1,048 |                     1,272 |                       6 |                        224 |                        1 |                                       21% |                                 1,072 |                                  1,590 |
|                       [Australia](/australia) |              737 |                     1,168 |                      46 |                        431 |                       17 |                                       58% |                                   908 |                                  1,544 |
|                             [Kuwait](/kuwait) |              536 |                       656 |                     156 |                        120 |                       28 |                                       22% |                                   556 |                                    893 |
| [United Arab Emirates](/united-arab-emirates) |              387 |                       454 |                      46 |                         67 |                        7 |                                       17% |                                   391 |                                    623 |
|                   [South Korea](/south-korea) |              331 |                       432 |                       8 |                        101 |                        2 |                                       30% |                                   335 |                                    659 |
|                                 [Cuba](/cuba) |              100 |                       147 |                      13 |                         47 |                        4 |                                       47% |                                   112 |                                    235 |
|                         [Malaysia](/malaysia) |              128 |                       140 |                       4 |                         12 |                        0 |                                       10% |                                   131 |                                    154 |
