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

* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 25 (11am ET):
<p align="center">
  Current Total: <b>177,249</b> deaths | Projected Total: <b>219,400 deaths by Nov 1, 2020</b> (Range: 202-244k)<br>
  Currently Infected: <b>1.3%</b> (1 in 76) | Total Infected: <b>13.8%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 25, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 26, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          7% |        73% |         96% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          6% |        22% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         1% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          177,249 |                   219,379 |                     661 |                     42,130 |                                       24% |                               202,869 |                                243,947 |
|                 [New York](/us-ny) |           32,887 |                    33,213 |                   1,707 |                        326 |                                        1% |                                32,900 |                                 34,839 |
|               [California](/us-ca) |           12,235 |                    18,600 |                     471 |                      6,365 |                                       52% |                                15,078 |                                 24,601 |
|                    [Texas](/us-tx) |           11,749 |                    18,501 |                     638 |                      6,752 |                                       57% |                                15,317 |                                 22,942 |
|               [New Jersey](/us-nj) |           15,946 |                    16,176 |                   1,821 |                        230 |                                        1% |                                15,966 |                                 16,804 |
|                  [Florida](/us-fl) |           10,397 |                    14,222 |                     662 |                      3,825 |                                       37% |                                12,290 |                                 16,765 |
|            [Massachusetts](/us-ma) |            8,949 |                     9,678 |                   1,393 |                        729 |                                        8% |                                 9,006 |                                 11,161 |
|                 [Illinois](/us-il) |            8,097 |                     9,303 |                     734 |                      1,206 |                                       15% |                                 8,250 |                                 11,486 |
|             [Pennsylvania](/us-pa) |            7,557 |                     8,456 |                     661 |                        899 |                                       12% |                                 7,612 |                                 10,336 |
|                  [Georgia](/us-ga) |            5,156 |                     7,417 |                     699 |                      2,261 |                                       44% |                                 6,262 |                                  9,370 |
|                 [Michigan](/us-mi) |            6,663 |                     7,243 |                     725 |                        580 |                                        9% |                                 6,718 |                                  8,343 |
|                  [Arizona](/us-az) |            4,771 |                     5,907 |                     812 |                      1,136 |                                       24% |                                 5,262 |                                  6,867 |
|                [Louisiana](/us-la) |            4,764 |                     5,821 |                   1,252 |                      1,057 |                                       22% |                                 5,210 |                                  6,839 |
|                     [Ohio](/us-oh) |            3,986 |                     5,357 |                     458 |                      1,371 |                                       34% |                                 4,336 |                                  7,220 |
|              [Connecticut](/us-ct) |            4,460 |                     4,543 |                   1,274 |                         83 |                                        2% |                                 4,472 |                                  4,770 |
|                 [Maryland](/us-md) |            3,694 |                     4,164 |                     689 |                        470 |                                       13% |                                 3,740 |                                  5,102 |
|                  [Indiana](/us-in) |            3,225 |                     4,120 |                     612 |                        895 |                                       28% |                                 3,340 |                                  5,482 |
|           [North Carolina](/us-nc) |            2,535 |                     3,803 |                     363 |                      1,268 |                                       50% |                                 3,081 |                                  5,138 |
|           [South Carolina](/us-sc) |            2,511 |                     3,758 |                     730 |                      1,247 |                                       50% |                                 3,126 |                                  4,733 |
|                 [Virginia](/us-va) |            2,471 |                     3,107 |                     364 |                        636 |                                       26% |                                 2,520 |                                  4,192 |
|              [Mississippi](/us-ms) |            2,248 |                     3,074 |                   1,033 |                        826 |                                       37% |                                 2,627 |                                  3,721 |
|                  [Alabama](/us-al) |            2,024 |                     2,744 |                     560 |                        720 |                                       36% |                                 2,373 |                                  3,406 |
|                [Tennessee](/us-tn) |            1,588 |                     2,725 |                     399 |                      1,137 |                                       72% |                                 2,140 |                                  3,701 |
|               [Washington](/us-wa) |            1,867 |                     2,632 |                     346 |                        765 |                                       41% |                                 2,072 |                                  3,652 |
|                [Minnesota](/us-mn) |            1,817 |                     2,312 |                     410 |                        495 |                                       27% |                                 1,899 |                                  3,047 |
|                 [Colorado](/us-co) |            1,919 |                     2,172 |                     377 |                        253 |                                       13% |                                 1,935 |                                  2,775 |
|                 [Missouri](/us-mo) |            1,453 |                     2,040 |                     332 |                        587 |                                       40% |                                 1,683 |                                  2,689 |
|                   [Nevada](/us-nv) |            1,200 |                     1,898 |                     616 |                        698 |                                       58% |                                 1,546 |                                  2,447 |
|                [Wisconsin](/us-wi) |            1,081 |                     1,552 |                     267 |                        471 |                                       44% |                                 1,243 |                                  2,131 |
|                     [Iowa](/us-ia) |            1,047 |                     1,518 |                     481 |                        471 |                                       45% |                                 1,200 |                                  2,116 |
|                 [Kentucky](/us-ky) |              884 |                     1,338 |                     300 |                        454 |                                       51% |                                 1,051 |                                  1,853 |
|                 [Oklahoma](/us-ok) |              730 |                     1,234 |                     312 |                        504 |                                       69% |                                   934 |                                  1,778 |
|                 [Arkansas](/us-ar) |              696 |                     1,188 |                     394 |                        492 |                                       71% |                                   922 |                                  1,624 |
|             [Rhode Island](/us-ri) |            1,035 |                     1,110 |                   1,048 |                         75 |                                        7% |                                 1,046 |                                  1,256 |
|               [New Mexico](/us-nm) |              749 |                     1,028 |                     490 |                        279 |                                       37% |                                   849 |                                  1,361 |
|              [Puerto Rico](/us-pr) |              390 |                       918 |                     287 |                        528 |                                      135% |                                   630 |                                  1,447 |
|                   [Oregon](/us-or) |              420 |                       725 |                     172 |                        305 |                                       73% |                                   538 |                                  1,087 |
|                 [Delaware](/us-de) |              604 |                       681 |                     699 |                         77 |                                       13% |                                   612 |                                    820 |
|     [District of Columbia](/us-dc) |              604 |                       651 |                     922 |                         47 |                                        8% |                                   613 |                                    731 |
|                   [Kansas](/us-ks) |              429 |                       643 |                     221 |                        214 |                                       50% |                                   509 |                                    918 |
|                     [Utah](/us-ut) |              390 |                       615 |                     192 |                        225 |                                       58% |                                   484 |                                    854 |
|                    [Idaho](/us-id) |              314 |                       592 |                     331 |                        278 |                                       88% |                                   444 |                                    831 |
|                 [Nebraska](/us-ne) |              383 |                       528 |                     273 |                        145 |                                       38% |                                   439 |                                    719 |
|            [New Hampshire](/us-nh) |              429 |                       492 |                     361 |                         63 |                                       15% |                                   433 |                                    646 |
|            [West Virginia](/us-wv) |              179 |                       370 |                     207 |                        191 |                                      107% |                                   254 |                                    596 |
|             [North Dakota](/us-nd) |              137 |                       240 |                     315 |                        103 |                                       75% |                                   177 |                                    364 |
|             [South Dakota](/us-sd) |              161 |                       233 |                     264 |                         72 |                                       45% |                                   186 |                                    323 |
|                  [Montana](/us-mt) |               91 |                       187 |                     175 |                         96 |                                      105% |                                   129 |                                    291 |
|                    [Maine](/us-me) |              131 |                       159 |                     118 |                         28 |                                       21% |                                   135 |                                    202 |
|                   [Hawaii](/us-hi) |               49 |                       142 |                     100 |                         93 |                                      189% |                                    81 |                                    260 |
|                  [Wyoming](/us-wy) |               37 |                        73 |                     125 |                         36 |                                       96% |                                    53 |                                    112 |
|                  [Vermont](/us-vt) |               58 |                        72 |                     116 |                         14 |                                       25% |                                    61 |                                    100 |
|                   [Alaska](/us-ak) |               32 |                        62 |                      85 |                         30 |                                       95% |                                    44 |                                     99 |
|                     [Guam](/us-gu) |                7 |                        21 |                     130 |                         14 |                                      207% |                                     9 |                                     59 |
|           [Virgin Islands](/us-vi) |               11 |                        20 |                     190 |                          9 |                                       82% |                                    14 |                                     31 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      55 |                          1 |                                       51% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,625 |                   202,092 |                     341 |                     14,467 |                                        8% |                               190,749 |                                235,359 |
| [United Kingdom](/united-kingdom) |           41,519 |                    42,261 |                     626 |                        742 |                                        2% |                                41,543 |                                 45,000 |
|                   [Italy](/italy) |           35,441 |                    36,235 |                     600 |                        794 |                                        2% |                                35,474 |                                 39,318 |
|                 [France](/france) |           30,533 |                    31,721 |                     473 |                      1,188 |                                        4% |                                30,583 |                                 36,124 |
|                   [Spain](/spain) |           28,872 |                    30,361 |                     647 |                      1,489 |                                        5% |                                28,909 |                                 35,211 |
|               [Belgium](/belgium) |            9,996 |                    10,487 |                     915 |                        491 |                                        5% |                                10,034 |                                 12,409 |
|               [Germany](/germany) |            9,276 |                     9,941 |                     120 |                        665 |                                        7% |                                 9,320 |                                 12,056 |
|       [Netherlands](/netherlands) |            6,227 |                     6,580 |                     381 |                        353 |                                        6% |                                 6,250 |                                  8,037 |
|               [Romania](/romania) |            3,309 |                     5,983 |                     308 |                      2,674 |                                       81% |                                 4,332 |                                  9,166 |
|                 [Sweden](/sweden) |            5,813 |                     5,943 |                     581 |                        130 |                                        2% |                                 5,834 |                                  6,039 |
|               [Ukraine](/ukraine) |            2,335 |                     4,712 |                     107 |                      2,377 |                                      102% |                                 3,155 |                                  8,205 |
|                 [Poland](/poland) |            1,960 |                     2,847 |                      75 |                        887 |                                       45% |                                 2,213 |                                  4,156 |
|       [Switzerland](/switzerland) |            2,001 |                     2,122 |                     247 |                        121 |                                        6% |                                 2,018 |                                  2,452 |
|             [Portugal](/portugal) |            1,801 |                     2,033 |                     198 |                        232 |                                       13% |                                 1,810 |                                  2,601 |
|               [Ireland](/ireland) |            1,777 |                     1,848 |                     377 |                         71 |                                        4% |                                 1,786 |                                  2,072 |
|               [Moldova](/moldova) |              945 |                     1,308 |                     323 |                        363 |                                       38% |                                 1,079 |                                  1,813 |
|             [Bulgaria](/bulgaria) |              563 |                     1,059 |                     151 |                        496 |                                       88% |                                   737 |                                  1,814 |
|                 [Serbia](/serbia) |              701 |                       941 |                     135 |                        240 |                                       34% |                                   792 |                                  1,172 |
|               [Belarus](/belarus) |              646 |                       841 |                      89 |                        195 |                                       30% |                                   750 |                                  1,025 |
|               [Austria](/austria) |              733 |                       826 |                      93 |                         93 |                                       13% |                                   749 |                                  1,053 |
|               [Denmark](/denmark) |              623 |                       701 |                     121 |                         78 |                                       12% |                                   639 |                                    890 |
|               [Hungary](/hungary) |              613 |                       687 |                      70 |                         74 |                                       12% |                                   619 |                                    863 |
|               [Czechia](/czechia) |              415 |                       594 |                      56 |                        179 |                                       43% |                                   452 |                                    896 |
|                 [Greece](/greece) |              242 |                       438 |                      41 |                        196 |                                       81% |                                   301 |                                    754 |
|               [Finland](/finland) |              335 |                       371 |                      67 |                         36 |                                       11% |                                   341 |                                    472 |
|                 [Norway](/norway) |              264 |                       311 |                      58 |                         47 |                                       18% |                                   275 |                                    413 |
|               [Croatia](/croatia) |              173 |                       267 |                      66 |                         94 |                                       55% |                                   202 |                                    408 |
|             [Slovenia](/slovenia) |              133 |                       169 |                      81 |                         36 |                                       27% |                                   138 |                                    231 |
|         [Luxembourg](/luxembourg) |              124 |                       160 |                     261 |                         36 |                                       29% |                                   136 |                                    208 |
|           [Lithuania](/lithuania) |               85 |                       114 |                      41 |                         29 |                                       34% |                                    92 |                                    163 |
|               [Estonia](/estonia) |               64 |                        73 |                      55 |                          9 |                                       13% |                                    68 |                                     86 |
|             [Slovakia](/slovakia) |               33 |                        56 |                      10 |                         23 |                                       71% |                                    37 |                                    107 |
|                 [Latvia](/latvia) |               33 |                        41 |                      22 |                          8 |                                       25% |                                    35 |                                     55 |
|                 [Cyprus](/cyprus) |               20 |                        28 |                      31 |                          8 |                                       38% |                                    23 |                                     36 |
|                   [Malta](/malta) |               10 |                        21 |                      42 |                         11 |                                      107% |                                    13 |                                     36 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                                       27% |                                    10 |                                     18 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          420,768 |                   646,204 |                     125 |                    225,436 |                                       54% |                               502,697 |                                889,954 |
|                             [Brazil](/brazil) |          115,309 |                   169,111 |                     801 |                     53,802 |                                       47% |                               131,178 |                                229,047 |
|                               [India](/india) |           58,390 |                   116,512 |                      85 |                     58,122 |                                      100% |                                81,101 |                                167,547 |
|                             [Mexico](/mexico) |           60,800 |                    88,225 |                     692 |                     27,425 |                                       45% |                                74,722 |                                113,061 |
|                                 [Peru](/peru) |           27,663 |                    35,835 |                   1,102 |                      8,172 |                                       30% |                                30,398 |                                 45,251 |
|                         [Colombia](/colombia) |           17,612 |                    31,198 |                     620 |                     13,586 |                                       77% |                                23,480 |                                 43,761 |
|                                 [Iran](/iran) |           20,776 |                    27,591 |                     333 |                      6,815 |                                       33% |                                22,975 |                                 36,015 |
|                             [Russia](/russia) |           16,406 |                    21,649 |                     148 |                      5,243 |                                       32% |                                17,921 |                                 29,563 |
|                 [South Africa](/south-africa) |           13,159 |                    21,348 |                     365 |                      8,189 |                                       62% |                                15,925 |                                 30,444 |
|                       [Argentina](/argentina) |            7,366 |                    19,846 |                     443 |                     12,480 |                                      169% |                                13,107 |                                 30,901 |
|                               [Chile](/chile) |           10,916 |                    13,734 |                     725 |                      2,818 |                                       26% |                                11,357 |                                 19,849 |
|                       [Indonesia](/indonesia) |            6,759 |                    11,563 |                      43 |                      4,804 |                                       71% |                                 8,478 |                                 17,890 |
|                             [Canada](/canada) |            9,129 |                     9,519 |                     254 |                        390 |                                        4% |                                 9,172 |                                 10,466 |
|                           [Bolivia](/bolivia) |            4,578 |                     7,563 |                     657 |                      2,985 |                                       65% |                                 5,750 |                                 10,410 |
|                           [Ecuador](/ecuador) |            6,322 |                     7,551 |                     435 |                      1,229 |                                       19% |                                 6,452 |                                 10,225 |
|                             [Turkey](/turkey) |            6,139 |                     7,473 |                      90 |                      1,334 |                                       22% |                                 6,264 |                                 11,083 |
|                         [Pakistan](/pakistan) |            6,244 |                     6,915 |                      32 |                        671 |                                       11% |                                 6,332 |                                  7,952 |
|                   [Philippines](/philippines) |            3,010 |                     6,562 |                      61 |                      3,552 |                                      118% |                                 3,968 |                                 11,929 |
|                     [Bangladesh](/bangladesh) |            3,983 |                     5,852 |                      36 |                      1,869 |                                       47% |                                 4,557 |                                  8,243 |
|                               [Egypt](/egypt) |            5,280 |                     5,843 |                      58 |                        563 |                                       11% |                                 5,357 |                                  6,894 |
|                 [Saudi Arabia](/saudi-arabia) |            3,691 |                     5,354 |                     156 |                      1,663 |                                       45% |                                 4,173 |                                  7,374 |
|                               [China](/china) |            4,711 |                     4,807 |                       3 |                         96 |                                        2% |                                 4,711 |                                  5,565 |
|                           [Morocco](/morocco) |              920 |                     3,704 |                     102 |                      2,784 |                                      303% |                                 1,799 |                                  7,483 |
|                             [Panama](/panama) |            1,906 |                     2,688 |                     633 |                        782 |                                       41% |                                 2,218 |                                  3,691 |
|     [Dominican Republic](/dominican-republic) |            1,573 |                     2,556 |                     238 |                        983 |                                       62% |                                 1,910 |                                  3,816 |
|                         [Honduras](/honduras) |            1,683 |                     2,505 |                     257 |                        822 |                                       49% |                                 1,965 |                                  3,368 |
|                           [Algeria](/algeria) |            1,446 |                     2,189 |                      51 |                        743 |                                       51% |                                 1,568 |                                  3,707 |
|                             [Israel](/israel) |              847 |                     2,041 |                     240 |                      1,194 |                                      141% |                                 1,203 |                                  3,566 |
|                               [Japan](/japan) |            1,201 |                     2,002 |                      16 |                        801 |                                       67% |                                 1,330 |                                  3,734 |
|                       [Australia](/australia) |              525 |                     1,387 |                      55 |                        862 |                                      164% |                                   806 |                                  2,501 |
|                           [Nigeria](/nigeria) |            1,004 |                     1,273 |                       6 |                        269 |                                       27% |                                 1,055 |                                  1,849 |
|                             [Kuwait](/kuwait) |              518 |                       695 |                     165 |                        177 |                                       34% |                                   545 |                                  1,085 |
| [United Arab Emirates](/united-arab-emirates) |              376 |                       466 |                      48 |                         90 |                                       24% |                                   381 |                                    702 |
|                   [South Korea](/south-korea) |              310 |                       373 |                       7 |                         63 |                                       20% |                                   310 |                                    597 |
|                         [Malaysia](/malaysia) |              125 |                       139 |                       4 |                         14 |                                       11% |                                   128 |                                    153 |
|                                 [Cuba](/cuba) |               91 |                       137 |                      12 |                         46 |                                       51% |                                   101 |                                    232 |
