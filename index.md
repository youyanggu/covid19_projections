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
### Updated Daily - Last Updated: September 3 (3am ET):
<p align="center">
  Current Total: <b>185,717</b> deaths | Projected Total: <b>219,500 deaths by Nov 1, 2020</b> (Range: 206-239k)<br>
  Currently Infected: <b>1.1%</b> (1 in 90) | Total Infected: <b>14.6%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 3, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |          2% |        92% |         99% |        99% |
|              225,000 |         <1% |        <1% |          3% |        19% |
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
|             *[United States](/us)* |          185,717 |                   219,528 |                     662 |                     33,811 |                      102 |                                       18% |                               206,748 |                                238,523 |
|                 [New York](/us-ny) |           32,972 |                    33,389 |                   1,716 |                        417 |                       21 |                                        1% |                                32,986 |                                 35,773 |
|               [California](/us-ca) |           13,317 |                    18,170 |                     460 |                      4,853 |                      123 |                                       36% |                                15,579 |                                 22,595 |
|                    [Texas](/us-tx) |           13,104 |                    17,985 |                     620 |                      4,881 |                      168 |                                       37% |                                15,845 |                                 20,906 |
|               [New Jersey](/us-nj) |           15,964 |                    16,143 |                   1,818 |                        179 |                       20 |                                        1% |                                15,977 |                                 16,770 |
|                  [Florida](/us-fl) |           11,501 |                    14,518 |                     676 |                      3,017 |                      140 |                                       26% |                                12,931 |                                 16,542 |
|            [Massachusetts](/us-ma) |            9,060 |                     9,552 |                   1,375 |                        492 |                       71 |                                        5% |                                 9,090 |                                 10,583 |
|                 [Illinois](/us-il) |            8,300 |                     9,299 |                     734 |                        999 |                       79 |                                       12% |                                 8,414 |                                 10,688 |
|             [Pennsylvania](/us-pa) |            7,705 |                     8,384 |                     655 |                        679 |                       53 |                                        9% |                                 7,738 |                                  9,770 |
|                  [Georgia](/us-ga) |            5,795 |                     8,002 |                     754 |                      2,207 |                      208 |                                       38% |                                 6,932 |                                  9,610 |
|                 [Michigan](/us-mi) |            6,781 |                     7,282 |                     729 |                        501 |                       50 |                                        7% |                                 6,823 |                                  8,130 |
|                  [Arizona](/us-az) |            5,065 |                     5,903 |                     811 |                        838 |                      115 |                                       17% |                                 5,417 |                                  6,621 |
|                [Louisiana](/us-la) |            5,004 |                     5,873 |                   1,263 |                        869 |                      187 |                                       17% |                                 5,368 |                                  6,680 |
|                     [Ohio](/us-oh) |            4,176 |                     4,943 |                     423 |                        767 |                       66 |                                       18% |                                 4,365 |                                  5,895 |
|              [Connecticut](/us-ct) |            4,467 |                     4,553 |                   1,277 |                         86 |                       24 |                                        2% |                                 4,477 |                                  4,815 |
|                 [Maryland](/us-md) |            3,766 |                     4,145 |                     686 |                        379 |                       63 |                                       10% |                                 3,802 |                                  4,865 |
|           [North Carolina](/us-nc) |            2,779 |                     3,908 |                     373 |                      1,129 |                      108 |                                       41% |                                 3,303 |                                  4,933 |
|                  [Indiana](/us-in) |            3,325 |                     3,797 |                     564 |                        472 |                       70 |                                       14% |                                 3,353 |                                  4,739 |
|           [South Carolina](/us-sc) |            2,794 |                     3,765 |                     731 |                        971 |                      189 |                                       35% |                                 3,287 |                                  4,495 |
|              [Mississippi](/us-ms) |            2,526 |                     3,256 |                   1,094 |                        730 |                      245 |                                       29% |                                 2,857 |                                  3,831 |
|                 [Virginia](/us-va) |            2,641 |                     3,235 |                     379 |                        594 |                       70 |                                       22% |                                 2,682 |                                  4,091 |
|                  [Alabama](/us-al) |            2,217 |                     2,877 |                     587 |                        660 |                      135 |                                       30% |                                 2,529 |                                  3,426 |
|                [Tennessee](/us-tn) |            1,797 |                     2,756 |                     403 |                        959 |                      140 |                                       53% |                                 2,298 |                                  3,488 |
|               [Washington](/us-wa) |            1,935 |                     2,358 |                     310 |                        423 |                       56 |                                       22% |                                 2,028 |                                  2,917 |
|                [Minnesota](/us-mn) |            1,882 |                     2,281 |                     404 |                        399 |                       71 |                                       21% |                                 1,950 |                                  2,841 |
|                 [Missouri](/us-mo) |            1,578 |                     2,187 |                     356 |                        609 |                       99 |                                       39% |                                 1,832 |                                  2,792 |
|                 [Colorado](/us-co) |            1,952 |                     2,132 |                     370 |                        180 |                       31 |                                        9% |                                 1,963 |                                  2,632 |
|                   [Nevada](/us-nv) |            1,336 |                     1,866 |                     606 |                        530 |                      172 |                                       40% |                                 1,607 |                                  2,230 |
|                     [Iowa](/us-ia) |            1,133 |                     1,729 |                     548 |                        596 |                      189 |                                       53% |                                 1,324 |                                  2,604 |
|                [Wisconsin](/us-wi) |            1,142 |                     1,542 |                     265 |                        400 |                       69 |                                       35% |                                 1,303 |                                  1,949 |
|                 [Kentucky](/us-ky) |              966 |                     1,393 |                     312 |                        427 |                       96 |                                       44% |                                 1,135 |                                  1,801 |
|                 [Arkansas](/us-ar) |              841 |                     1,387 |                     459 |                        546 |                      181 |                                       65% |                                 1,115 |                                  1,796 |
|                 [Oklahoma](/us-ok) |              821 |                     1,269 |                     321 |                        448 |                      113 |                                       55% |                                 1,023 |                                  1,670 |
|             [Rhode Island](/us-ri) |            1,051 |                     1,127 |                   1,064 |                         76 |                       72 |                                        7% |                                 1,060 |                                  1,288 |
|               [New Mexico](/us-nm) |              790 |                       958 |                     457 |                        168 |                       80 |                                       21% |                                   851 |                                  1,123 |
|              [Puerto Rico](/us-pr) |              443 |                       797 |                     250 |                        354 |                      111 |                                       80% |                                   612 |                                  1,089 |
|                   [Oregon](/us-or) |              468 |                       736 |                     175 |                        268 |                       64 |                                       57% |                                   581 |                                    987 |
|                 [Delaware](/us-de) |              606 |                       652 |                     670 |                         46 |                       47 |                                        8% |                                   611 |                                    743 |
|                   [Kansas](/us-ks) |              461 |                       651 |                     224 |                        190 |                       65 |                                       41% |                                   539 |                                    852 |
|     [District of Columbia](/us-dc) |              608 |                       637 |                     902 |                         29 |                       41 |                                        5% |                                   612 |                                    694 |
|                    [Idaho](/us-id) |              372 |                       615 |                     344 |                        243 |                      136 |                                       65% |                                   495 |                                    797 |
|                     [Utah](/us-ut) |              410 |                       575 |                     179 |                        165 |                       51 |                                       40% |                                   483 |                                    719 |
|                 [Nebraska](/us-ne) |              399 |                       524 |                     271 |                        125 |                       64 |                                       31% |                                   433 |                                    671 |
|            [West Virginia](/us-wv) |              233 |                       461 |                     257 |                        228 |                      127 |                                       98% |                                   341 |                                    662 |
|            [New Hampshire](/us-nh) |              432 |                       461 |                     339 |                         29 |                       21 |                                        7% |                                   434 |                                    529 |
|                   [Hawaii](/us-hi) |               75 |                       273 |                     193 |                        198 |                      140 |                                      264% |                                   157 |                                    488 |
|             [South Dakota](/us-sd) |              169 |                       264 |                     298 |                         95 |                      107 |                                       56% |                                   181 |                                    482 |
|             [North Dakota](/us-nd) |              148 |                       252 |                     331 |                        104 |                      137 |                                       71% |                                   189 |                                    364 |
|                  [Montana](/us-mt) |              109 |                       203 |                     190 |                         94 |                       88 |                                       86% |                                   151 |                                    290 |
|                    [Maine](/us-me) |              133 |                       150 |                     112 |                         17 |                       13 |                                       13% |                                   137 |                                    175 |
|                   [Alaska](/us-ak) |               39 |                        75 |                     102 |                         36 |                       49 |                                       91% |                                    55 |                                    111 |
|                  [Wyoming](/us-wy) |               41 |                        72 |                     124 |                         31 |                       53 |                                       75% |                                    55 |                                    105 |
|                  [Vermont](/us-vt) |               58 |                        67 |                     107 |                          9 |                       14 |                                       15% |                                    60 |                                     81 |
|                     [Guam](/us-gu) |               13 |                        59 |                     357 |                         46 |                      278 |                                      355% |                                    34 |                                    110 |
|           [Virgin Islands](/us-vi) |               15 |                        38 |                     361 |                         23 |                      218 |                                      152% |                                    26 |                                     57 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      52 |                          1 |                       16 |                                       44% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,477 |                   204,052 |                     344 |                     14,575 |                      840 |                                        8% |                               192,656 |                                239,341 |
| [United Kingdom](/united-kingdom) |           41,602 |                    42,104 |                     623 |                        502 |                        7 |                                        1% |                                41,612 |                                 44,285 |
|                   [Italy](/italy) |           35,497 |                    36,121 |                     598 |                        624 |                       10 |                                        2% |                                35,513 |                                 38,885 |
|                 [France](/france) |           30,692 |                    32,190 |                     480 |                      1,498 |                       22 |                                        5% |                                30,725 |                                 40,140 |
|                   [Spain](/spain) |           29,194 |                    31,721 |                     676 |                      2,527 |                       54 |                                        9% |                                29,227 |                                 41,206 |
|               [Belgium](/belgium) |            9,898 |                    10,075 |                     879 |                        177 |                       15 |                                        2% |                                 9,917 |                                 10,738 |
|               [Germany](/germany) |            9,322 |                     9,740 |                     117 |                        418 |                        5 |                                        4% |                                 9,340 |                                 11,101 |
|       [Netherlands](/netherlands) |            6,267 |                     6,476 |                     375 |                        209 |                       12 |                                        3% |                                 6,282 |                                  7,232 |
|               [Romania](/romania) |            3,721 |                     6,044 |                     311 |                      2,323 |                      120 |                                       62% |                                 4,682 |                                  8,197 |
|                 [Sweden](/sweden) |            5,820 |                     5,864 |                     573 |                         44 |                        4 |                                        1% |                                 5,824 |                                  6,010 |
|               [Ukraine](/ukraine) |            2,705 |                     5,607 |                     127 |                      2,902 |                       66 |                                      107% |                                 3,735 |                                  8,671 |
|                 [Poland](/poland) |            2,078 |                     2,862 |                      75 |                        784 |                       21 |                                       38% |                                 2,316 |                                  3,886 |
|       [Switzerland](/switzerland) |            2,011 |                     2,084 |                     243 |                         73 |                        8 |                                        4% |                                 2,024 |                                  2,289 |
|             [Portugal](/portugal) |            1,827 |                     1,982 |                     193 |                        155 |                       15 |                                        8% |                                 1,833 |                                  2,377 |
|               [Ireland](/ireland) |            1,777 |                     1,820 |                     371 |                         43 |                        9 |                                        2% |                                 1,784 |                                  1,948 |
|               [Moldova](/moldova) |            1,024 |                     1,457 |                     360 |                        433 |                      107 |                                       42% |                                 1,178 |                                  1,939 |
|             [Bulgaria](/bulgaria) |              648 |                     1,277 |                     182 |                        629 |                       90 |                                       97% |                                   893 |                                  1,910 |
|               [Belarus](/belarus) |              691 |                       991 |                     105 |                        300 |                       32 |                                       43% |                                   782 |                                  1,444 |
|                 [Serbia](/serbia) |              716 |                       887 |                     127 |                        171 |                       25 |                                       24% |                                   783 |                                  1,049 |
|               [Austria](/austria) |              734 |                       784 |                      89 |                         50 |                        6 |                                        7% |                                   743 |                                    911 |
|               [Hungary](/hungary) |              619 |                       670 |                      69 |                         51 |                        5 |                                        8% |                                   623 |                                    811 |
|               [Denmark](/denmark) |              626 |                       667 |                     115 |                         41 |                        7 |                                        6% |                                   634 |                                    778 |
|               [Czechia](/czechia) |              425 |                       525 |                      49 |                        100 |                        9 |                                       24% |                                   447 |                                    685 |
|                 [Greece](/greece) |              273 |                       507 |                      47 |                        234 |                       22 |                                       86% |                                   359 |                                    791 |
|               [Finland](/finland) |              336 |                       355 |                      64 |                         19 |                        4 |                                        6% |                                   339 |                                    412 |
|               [Croatia](/croatia) |              191 |                       319 |                      78 |                        128 |                       31 |                                       67% |                                   241 |                                    481 |
|                 [Norway](/norway) |              264 |                       288 |                      54 |                         24 |                        4 |                                        9% |                                   269 |                                    351 |
|             [Slovenia](/slovenia) |              134 |                       155 |                      75 |                         21 |                       10 |                                       16% |                                   137 |                                    194 |
|         [Luxembourg](/luxembourg) |              124 |                       146 |                     239 |                         22 |                       37 |                                       18% |                                   131 |                                    178 |
|           [Lithuania](/lithuania) |               86 |                       102 |                      36 |                         16 |                        6 |                                       18% |                                    89 |                                    127 |
|               [Estonia](/estonia) |               64 |                        71 |                      53 |                          7 |                        5 |                                       10% |                                    67 |                                     81 |
|             [Slovakia](/slovakia) |               33 |                        42 |                       8 |                          9 |                        2 |                                       27% |                                    35 |                                     59 |
|                 [Latvia](/latvia) |               34 |                        41 |                      21 |                          7 |                        3 |                                       20% |                                    35 |                                     50 |
|                   [Malta](/malta) |               13 |                        38 |                      78 |                         25 |                       51 |                                      195% |                                    23 |                                     69 |
|                 [Cyprus](/cyprus) |               21 |                        30 |                      34 |                          9 |                       10 |                                       42% |                                    24 |                                     41 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        6 |                                       20% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          457,862 |                   649,748 |                     125 |                    191,886 |                    2,358 |                                       42% |                               538,644 |                                857,064 |
|                             [Brazil](/brazil) |          123,780 |                   164,774 |                     781 |                     40,994 |                      194 |                                       33% |                               144,789 |                                199,424 |
|                               [India](/india) |           67,376 |                   124,664 |                      91 |                     57,288 |                       42 |                                       85% |                                91,389 |                                188,736 |
|                             [Mexico](/mexico) |           65,816 |                    88,367 |                     693 |                     22,551 |                      177 |                                       34% |                                77,645 |                                107,214 |
|                                 [Peru](/peru) |           29,068 |                    34,618 |                   1,065 |                      5,550 |                      171 |                                       19% |                                30,571 |                                 41,228 |
|                         [Colombia](/colombia) |           20,345 |                    31,882 |                     633 |                     11,537 |                      229 |                                       57% |                                25,524 |                                 41,413 |
|                                 [Iran](/iran) |           21,797 |                    27,024 |                     326 |                      5,227 |                       63 |                                       24% |                                23,384 |                                 33,043 |
|                             [Russia](/russia) |           17,365 |                    21,647 |                     148 |                      4,282 |                       29 |                                       25% |                                18,285 |                                 30,096 |
|                 [South Africa](/south-africa) |           14,389 |                    20,037 |                     342 |                      5,648 |                       96 |                                       39% |                                16,755 |                                 27,888 |
|                       [Argentina](/argentina) |            9,118 |                    18,875 |                     422 |                      9,757 |                      218 |                                      107% |                                13,217 |                                 26,492 |
|                               [Chile](/chile) |           11,344 |                    14,414 |                     761 |                      3,070 |                      162 |                                       27% |                                11,817 |                                 21,403 |
|                       [Indonesia](/indonesia) |            7,616 |                    12,519 |                      46 |                      4,903 |                       18 |                                       64% |                                 9,483 |                                 19,476 |
|                             [Canada](/canada) |            9,182 |                     9,455 |                     253 |                        273 |                        7 |                                        3% |                                 9,213 |                                 10,148 |
|                           [Bolivia](/bolivia) |            5,203 |                     7,970 |                     692 |                      2,767 |                      240 |                                       53% |                                 6,327 |                                 10,329 |
|                             [Turkey](/turkey) |            6,462 |                     7,943 |                      95 |                      1,481 |                       18 |                                       23% |                                 6,560 |                                 10,626 |
|                           [Ecuador](/ecuador) |            6,619 |                     7,674 |                     442 |                      1,055 |                       61 |                                       16% |                                 6,710 |                                  9,986 |
|                   [Philippines](/philippines) |            3,623 |                     7,134 |                      66 |                      3,511 |                       32 |                                       97% |                                 4,761 |                                 11,298 |
|                         [Pakistan](/pakistan) |            6,328 |                     6,725 |                      31 |                        397 |                        2 |                                        6% |                                 6,356 |                                  7,639 |
|                     [Bangladesh](/bangladesh) |            4,351 |                     6,231 |                      38 |                      1,880 |                       12 |                                       43% |                                 4,967 |                                  8,543 |
|                               [Egypt](/egypt) |            5,461 |                     6,129 |                      61 |                        668 |                        7 |                                       12% |                                 5,508 |                                  8,527 |
|                 [Saudi Arabia](/saudi-arabia) |            3,956 |                     5,219 |                     152 |                      1,263 |                       37 |                                       32% |                                 4,348 |                                  6,710 |
|                               [China](/china) |            4,727 |                     4,803 |                       3 |                         76 |                        0 |                                        2% |                                 4,727 |                                  5,410 |
|                           [Morocco](/morocco) |            1,216 |                     3,334 |                      91 |                      2,118 |                       58 |                                      174% |                                 1,908 |                                  5,442 |
|                         [Honduras](/honduras) |            1,924 |                     2,827 |                     290 |                        903 |                       93 |                                       47% |                                 2,254 |                                  3,843 |
|     [Dominican Republic](/dominican-republic) |            1,765 |                     2,742 |                     255 |                        977 |                       91 |                                       55% |                                 2,111 |                                  3,801 |
|                             [Panama](/panama) |            2,030 |                     2,531 |                     596 |                        501 |                      118 |                                       25% |                                 2,245 |                                  3,115 |
|                           [Algeria](/algeria) |            1,523 |                     2,113 |                      49 |                        590 |                       14 |                                       39% |                                 1,633 |                                  3,148 |
|                               [Japan](/japan) |            1,327 |                     2,097 |                      17 |                        770 |                        6 |                                       58% |                                 1,512 |                                  3,555 |
|                             [Israel](/israel) |              969 |                     1,839 |                     216 |                        870 |                      102 |                                       90% |                                 1,232 |                                  2,970 |
|                           [Nigeria](/nigeria) |            1,027 |                     1,224 |                       6 |                        197 |                        1 |                                       19% |                                 1,045 |                                  1,515 |
|                       [Australia](/australia) |              678 |                     1,103 |                      44 |                        425 |                       17 |                                       63% |                                   849 |                                  1,441 |
|                             [Kuwait](/kuwait) |              535 |                       660 |                     157 |                        125 |                       30 |                                       23% |                                   556 |                                    911 |
| [United Arab Emirates](/united-arab-emirates) |              387 |                       458 |                      47 |                         71 |                        7 |                                       18% |                                   391 |                                    638 |
|                   [South Korea](/south-korea) |              329 |                       430 |                       8 |                        101 |                        2 |                                       31% |                                   332 |                                    670 |
|                                 [Cuba](/cuba) |               98 |                       145 |                      13 |                         47 |                        4 |                                       48% |                                   109 |                                    232 |
|                         [Malaysia](/malaysia) |              128 |                       140 |                       4 |                         12 |                        0 |                                       10% |                                   131 |                                    154 |
