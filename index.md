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

* **August 25:** In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 26 (2pm ET):
<p align="center">
  Current Total: <b>178,483</b> deaths | Projected Total: <b>218,300 deaths by Nov 1, 2020</b> (Range: 203-240k)<br>
  Currently Infected: <b>1.3%</b> (1 in 79) | Total Infected: <b>13.8%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 26, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 25, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          6% |        74% |         97% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          4% |        19% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
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
|             *[United States](/us)* |          178,483 |                   218,334 |                     658 |                     39,851 |                      120 |                                       22% |                               203,190 |                                239,979 |
|                 [New York](/us-ny) |           32,918 |                    33,133 |                   1,703 |                        215 |                       11 |                                        1% |                                32,928 |                                 34,187 |
|               [California](/us-ca) |           12,382 |                    18,449 |                     467 |                      6,067 |                      154 |                                       49% |                                15,171 |                                 23,704 |
|                    [Texas](/us-tx) |           11,935 |                    18,276 |                     630 |                      6,341 |                      219 |                                       53% |                                15,365 |                                 22,192 |
|               [New Jersey](/us-nj) |           15,953 |                    16,106 |                   1,813 |                        153 |                       17 |                                        1% |                                15,970 |                                 16,551 |
|                  [Florida](/us-fl) |           10,580 |                    14,261 |                     664 |                      3,681 |                      171 |                                       35% |                                12,429 |                                 16,611 |
|            [Massachusetts](/us-ma) |            8,961 |                     9,646 |                   1,388 |                        685 |                       98 |                                        8% |                                 9,019 |                                 11,035 |
|                 [Illinois](/us-il) |            8,126 |                     9,261 |                     731 |                      1,135 |                       90 |                                       14% |                                 8,260 |                                 11,153 |
|             [Pennsylvania](/us-pa) |            7,582 |                     8,417 |                     657 |                        835 |                       65 |                                       11% |                                 7,630 |                                 10,135 |
|                  [Georgia](/us-ga) |            5,262 |                     7,502 |                     707 |                      2,240 |                      211 |                                       43% |                                 6,379 |                                  9,269 |
|                 [Michigan](/us-mi) |            6,684 |                     7,237 |                     725 |                        553 |                       55 |                                        8% |                                 6,737 |                                  8,236 |
|                [Louisiana](/us-la) |            4,797 |                     5,881 |                   1,265 |                      1,084 |                      233 |                                       23% |                                 5,256 |                                  6,883 |
|                  [Arizona](/us-az) |            4,792 |                     5,866 |                     806 |                      1,074 |                      148 |                                       22% |                                 5,262 |                                  6,738 |
|                     [Ohio](/us-oh) |            3,996 |                     4,859 |                     416 |                        863 |                       74 |                                       22% |                                 4,209 |                                  5,985 |
|              [Connecticut](/us-ct) |            4,463 |                     4,537 |                   1,273 |                         74 |                       21 |                                        2% |                                 4,475 |                                  4,750 |
|                 [Maryland](/us-md) |            3,707 |                     4,163 |                     689 |                        456 |                       75 |                                       12% |                                 3,753 |                                  5,040 |
|                  [Indiana](/us-in) |            3,241 |                     4,092 |                     608 |                        851 |                      126 |                                       26% |                                 3,344 |                                  5,352 |
|           [North Carolina](/us-nc) |            2,570 |                     3,831 |                     365 |                      1,261 |                      120 |                                       49% |                                 3,133 |                                  5,035 |
|           [South Carolina](/us-sc) |            2,529 |                     3,680 |                     715 |                      1,151 |                      224 |                                       46% |                                 3,111 |                                  4,567 |
|              [Mississippi](/us-ms) |            2,315 |                     3,140 |                   1,055 |                        825 |                      277 |                                       36% |                                 2,704 |                                  3,739 |
|                 [Virginia](/us-va) |            2,494 |                     3,121 |                     366 |                        627 |                       73 |                                       25% |                                 2,541 |                                  4,116 |
|                [Tennessee](/us-tn) |            1,628 |                     2,748 |                     402 |                      1,120 |                      164 |                                       69% |                                 2,185 |                                  3,595 |
|                  [Alabama](/us-al) |            2,037 |                     2,723 |                     555 |                        686 |                      140 |                                       34% |                                 2,377 |                                  3,315 |
|               [Washington](/us-wa) |            1,876 |                     2,602 |                     342 |                        726 |                       95 |                                       39% |                                 2,056 |                                  3,501 |
|                [Minnesota](/us-mn) |            1,825 |                     2,292 |                     406 |                        467 |                       83 |                                       26% |                                 1,904 |                                  2,983 |
|                 [Colorado](/us-co) |            1,926 |                     2,144 |                     372 |                        218 |                       38 |                                       11% |                                 1,941 |                                  2,745 |
|                 [Missouri](/us-mo) |            1,470 |                     2,037 |                     332 |                        567 |                       92 |                                       39% |                                 1,698 |                                  2,634 |
|                   [Nevada](/us-nv) |            1,230 |                     1,902 |                     618 |                        672 |                      218 |                                       55% |                                 1,560 |                                  2,391 |
|                [Wisconsin](/us-wi) |            1,094 |                     1,551 |                     266 |                        457 |                       78 |                                       42% |                                 1,273 |                                  2,048 |
|                     [Iowa](/us-ia) |            1,059 |                     1,523 |                     483 |                        464 |                      147 |                                       44% |                                 1,198 |                                  2,070 |
|                 [Kentucky](/us-ky) |              895 |                     1,344 |                     301 |                        449 |                      100 |                                       50% |                                 1,068 |                                  1,806 |
|                 [Oklahoma](/us-ok) |              744 |                     1,240 |                     313 |                        496 |                      125 |                                       67% |                                   962 |                                  1,732 |
|                 [Arkansas](/us-ar) |              711 |                     1,203 |                     399 |                        492 |                      163 |                                       69% |                                   943 |                                  1,600 |
|             [Rhode Island](/us-ri) |            1,039 |                     1,111 |                   1,049 |                         72 |                       68 |                                        7% |                                 1,049 |                                  1,250 |
|               [New Mexico](/us-nm) |              752 |                     1,023 |                     488 |                        271 |                      129 |                                       36% |                                   850 |                                  1,323 |
|              [Puerto Rico](/us-pr) |              395 |                       866 |                     271 |                        471 |                      147 |                                      119% |                                   611 |                                  1,289 |
|                   [Oregon](/us-or) |              428 |                       725 |                     172 |                        297 |                       70 |                                       69% |                                   548 |                                  1,041 |
|                 [Delaware](/us-de) |              603 |                       675 |                     693 |                         72 |                       74 |                                       12% |                                   611 |                                    806 |
|     [District of Columbia](/us-dc) |              604 |                       648 |                     918 |                         44 |                       62 |                                        7% |                                   612 |                                    722 |
|                   [Kansas](/us-ks) |              430 |                       633 |                     217 |                        203 |                       70 |                                       47% |                                   506 |                                    863 |
|                     [Utah](/us-ut) |              397 |                       620 |                     193 |                        223 |                       69 |                                       56% |                                   493 |                                    834 |
|                    [Idaho](/us-id) |              326 |                       614 |                     344 |                        288 |                      161 |                                       88% |                                   468 |                                    840 |
|                 [Nebraska](/us-ne) |              383 |                       522 |                     270 |                        139 |                       72 |                                       36% |                                   423 |                                    699 |
|            [New Hampshire](/us-nh) |              429 |                       470 |                     346 |                         41 |                       30 |                                       10% |                                   432 |                                    555 |
|            [West Virginia](/us-wv) |              187 |                       389 |                     217 |                        202 |                      113 |                                      108% |                                   270 |                                    602 |
|             [North Dakota](/us-nd) |              138 |                       271 |                     356 |                        133 |                      174 |                                       96% |                                   184 |                                    466 |
|             [South Dakota](/us-sd) |              161 |                       238 |                     269 |                         77 |                       87 |                                       48% |                                   180 |                                    324 |
|                  [Montana](/us-mt) |               97 |                       209 |                     196 |                        112 |                      105 |                                      115% |                                   144 |                                    324 |
|                    [Maine](/us-me) |              131 |                       151 |                     112 |                         20 |                       15 |                                       15% |                                   135 |                                    178 |
|                   [Hawaii](/us-hi) |               49 |                       128 |                      91 |                         79 |                       56 |                                      162% |                                    79 |                                    212 |
|                   [Alaska](/us-ak) |               36 |                        80 |                     109 |                         44 |                       60 |                                      121% |                                    55 |                                    125 |
|                  [Vermont](/us-vt) |               58 |                        71 |                     114 |                         13 |                       21 |                                       22% |                                    61 |                                     97 |
|                  [Wyoming](/us-wy) |               37 |                        68 |                     118 |                         31 |                       54 |                                       84% |                                    50 |                                    104 |
|                     [Guam](/us-gu) |                7 |                        26 |                     160 |                         19 |                      118 |                                      278% |                                    10 |                                     66 |
|           [Virgin Islands](/us-vi) |               12 |                        26 |                     245 |                         14 |                      131 |                                      115% |                                    18 |                                     39 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                       18 |                                       49% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,871 |                   202,119 |                     341 |                     14,248 |                      879 |                                        8% |                               191,121 |                                232,587 |
| [United Kingdom](/united-kingdom) |           41,535 |                    42,258 |                     626 |                        723 |                       11 |                                        2% |                                41,558 |                                 44,863 |
|                   [Italy](/italy) |           35,445 |                    36,194 |                     600 |                        749 |                       12 |                                        2% |                                35,477 |                                 39,097 |
|                 [France](/france) |           30,549 |                    31,664 |                     473 |                      1,115 |                       17 |                                        4% |                                30,599 |                                 35,688 |
|                   [Spain](/spain) |           28,924 |                    30,381 |                     647 |                      1,457 |                       31 |                                        5% |                                28,961 |                                 35,031 |
|               [Belgium](/belgium) |            9,996 |                    10,445 |                     912 |                        449 |                       39 |                                        4% |                                10,033 |                                 12,097 |
|               [Germany](/germany) |            9,281 |                     9,899 |                     119 |                        618 |                        7 |                                        7% |                                 9,324 |                                 11,813 |
|       [Netherlands](/netherlands) |            6,233 |                     6,574 |                     380 |                        341 |                       20 |                                        5% |                                 6,257 |                                  7,894 |
|               [Romania](/romania) |            3,367 |                     6,183 |                     318 |                      2,816 |                      145 |                                       84% |                                 4,483 |                                  9,107 |
|                 [Sweden](/sweden) |            5,814 |                     5,938 |                     580 |                        124 |                       12 |                                        2% |                                 5,834 |                                  6,020 |
|               [Ukraine](/ukraine) |            2,362 |                     4,647 |                     106 |                      2,285 |                       52 |                                       97% |                                 3,172 |                                  7,642 |
|                 [Poland](/poland) |            1,977 |                     2,859 |                      75 |                        882 |                       23 |                                       45% |                                 2,241 |                                  4,066 |
|       [Switzerland](/switzerland) |            2,002 |                     2,117 |                     246 |                        115 |                       13 |                                        6% |                                 2,019 |                                  2,422 |
|             [Portugal](/portugal) |            1,805 |                     2,032 |                     198 |                        227 |                       22 |                                       13% |                                 1,814 |                                  2,551 |
|               [Ireland](/ireland) |            1,777 |                     1,845 |                     376 |                         68 |                       14 |                                        4% |                                 1,786 |                                  2,037 |
|               [Moldova](/moldova) |              960 |                     1,375 |                     340 |                        415 |                      103 |                                       43% |                                 1,118 |                                  1,885 |
|             [Bulgaria](/bulgaria) |              572 |                     1,121 |                     160 |                        549 |                       78 |                                       96% |                                   764 |                                  1,858 |
|                 [Serbia](/serbia) |              705 |                       935 |                     134 |                        230 |                       33 |                                       33% |                                   795 |                                  1,133 |
|               [Belarus](/belarus) |              652 |                       848 |                      90 |                        196 |                       21 |                                       30% |                                   758 |                                    998 |
|               [Austria](/austria) |              733 |                       821 |                      93 |                         88 |                       10 |                                       12% |                                   750 |                                  1,022 |
|               [Denmark](/denmark) |              623 |                       695 |                     120 |                         72 |                       12 |                                       12% |                                   639 |                                    858 |
|               [Hungary](/hungary) |              614 |                       686 |                      70 |                         72 |                        7 |                                       12% |                                   620 |                                    854 |
|               [Czechia](/czechia) |              416 |                       580 |                      54 |                        164 |                       15 |                                       39% |                                   452 |                                    841 |
|                 [Greece](/greece) |              243 |                       409 |                      38 |                        166 |                       16 |                                       69% |                                   293 |                                    658 |
|               [Finland](/finland) |              335 |                       369 |                      67 |                         34 |                        6 |                                       10% |                                   341 |                                    465 |
|                 [Norway](/norway) |              264 |                       307 |                      57 |                         43 |                        8 |                                       16% |                                   275 |                                    394 |
|               [Croatia](/croatia) |              175 |                       275 |                      68 |                        100 |                       25 |                                       57% |                                   209 |                                    404 |
|             [Slovenia](/slovenia) |              133 |                       168 |                      81 |                         35 |                       17 |                                       26% |                                   138 |                                    225 |
|         [Luxembourg](/luxembourg) |              124 |                       157 |                     256 |                         33 |                       54 |                                       27% |                                   135 |                                    199 |
|           [Lithuania](/lithuania) |               85 |                       113 |                      40 |                         28 |                       10 |                                       33% |                                    92 |                                    156 |
|               [Estonia](/estonia) |               64 |                        73 |                      55 |                          9 |                        6 |                                       13% |                                    68 |                                     89 |
|             [Slovakia](/slovakia) |               33 |                        51 |                       9 |                         18 |                        3 |                                       56% |                                    36 |                                     87 |
|                 [Latvia](/latvia) |               33 |                        41 |                      21 |                          8 |                        4 |                                       23% |                                    34 |                                     53 |
|                 [Cyprus](/cyprus) |               20 |                        27 |                      31 |                          7 |                        8 |                                       36% |                                    23 |                                     35 |
|                   [Malta](/malta) |               10 |                        18 |                      36 |                          8 |                       15 |                                       76% |                                    13 |                                     28 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                        7 |                                       25% |                                    10 |                                     17 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          425,261 |                   640,254 |                     123 |                    214,993 |                    2,799 |                                       51% |                               507,829 |                                864,375 |
|                             [Brazil](/brazil) |          116,580 |                   170,453 |                     808 |                     53,873 |                      255 |                                       46% |                               136,253 |                                227,588 |
|                               [India](/india) |           59,357 |                   111,015 |                      81 |                     51,658 |                       38 |                                       87% |                                80,474 |                                154,702 |
|                             [Mexico](/mexico) |           61,450 |                    87,936 |                     689 |                     26,486 |                      208 |                                       43% |                                75,488 |                                110,575 |
|                                 [Peru](/peru) |           27,813 |                    35,392 |                   1,089 |                      7,579 |                      233 |                                       27% |                                30,050 |                                 44,437 |
|                         [Colombia](/colombia) |           17,889 |                    31,032 |                     616 |                     13,143 |                      261 |                                       73% |                                23,628 |                                 42,963 |
|                                 [Iran](/iran) |           20,901 |                    27,430 |                     331 |                      6,529 |                       79 |                                       31% |                                22,985 |                                 34,891 |
|                             [Russia](/russia) |           16,524 |                    21,650 |                     148 |                      5,126 |                       35 |                                       31% |                                18,059 |                                 28,860 |
|                 [South Africa](/south-africa) |           13,308 |                    21,073 |                     360 |                      7,765 |                      133 |                                       58% |                                15,946 |                                 29,754 |
|                       [Argentina](/argentina) |            7,563 |                    19,517 |                     436 |                     11,954 |                      267 |                                      158% |                                12,344 |                                 29,951 |
|                               [Chile](/chile) |           10,958 |                    13,752 |                     726 |                      2,794 |                      147 |                                       25% |                                11,425 |                                 19,842 |
|                       [Indonesia](/indonesia) |            6,858 |                    11,693 |                      43 |                      4,835 |                       18 |                                       70% |                                 8,595 |                                 17,810 |
|                             [Canada](/canada) |            9,136 |                     9,518 |                     254 |                        382 |                       10 |                                        4% |                                 9,179 |                                 10,370 |
|                           [Bolivia](/bolivia) |            4,664 |                     7,730 |                     671 |                      3,066 |                      266 |                                       66% |                                 5,876 |                                 10,501 |
|                           [Ecuador](/ecuador) |            6,368 |                     7,610 |                     438 |                      1,242 |                       72 |                                       20% |                                 6,507 |                                 10,271 |
|                             [Turkey](/turkey) |            6,163 |                     7,455 |                      89 |                      1,292 |                       15 |                                       21% |                                 6,287 |                                 10,612 |
|                         [Pakistan](/pakistan) |            6,255 |                     6,900 |                      32 |                        645 |                        3 |                                       10% |                                 6,338 |                                  7,856 |
|                   [Philippines](/philippines) |            3,038 |                     6,133 |                      57 |                      3,095 |                       29 |                                      102% |                                 3,923 |                                 10,089 |
|                     [Bangladesh](/bangladesh) |            4,028 |                     5,887 |                      36 |                      1,859 |                       11 |                                       46% |                                 4,721 |                                  8,336 |
|                               [Egypt](/egypt) |            5,298 |                     5,849 |                      58 |                        551 |                        5 |                                       10% |                                 5,371 |                                  6,828 |
|                 [Saudi Arabia](/saudi-arabia) |            3,722 |                     5,356 |                     156 |                      1,634 |                       48 |                                       44% |                                 4,206 |                                  7,027 |
|                               [China](/china) |            4,712 |                     4,805 |                       3 |                         93 |                        0 |                                        2% |                                 4,712 |                                  5,499 |
|                           [Morocco](/morocco) |              955 |                     3,638 |                     100 |                      2,683 |                       74 |                                      281% |                                 1,844 |                                  7,065 |
|                             [Panama](/panama) |            1,919 |                     2,658 |                     626 |                        739 |                      174 |                                       39% |                                 2,217 |                                  3,546 |
|                         [Honduras](/honduras) |            1,703 |                     2,522 |                     259 |                        819 |                       84 |                                       48% |                                 1,982 |                                  3,376 |
|     [Dominican Republic](/dominican-republic) |            1,585 |                     2,516 |                     234 |                        931 |                       87 |                                       59% |                                 1,908 |                                  3,744 |
|                           [Algeria](/algeria) |            1,456 |                     2,178 |                      51 |                        722 |                       17 |                                       50% |                                 1,578 |                                  3,630 |
|                               [Japan](/japan) |            1,219 |                     2,045 |                      16 |                        826 |                        7 |                                       68% |                                 1,359 |                                  3,767 |
|                             [Israel](/israel) |              859 |                     1,999 |                     235 |                      1,140 |                      134 |                                      133% |                                 1,206 |                                  3,390 |
|                       [Australia](/australia) |              549 |                     1,450 |                      58 |                        901 |                       36 |                                      164% |                                   844 |                                  2,582 |
|                           [Nigeria](/nigeria) |            1,007 |                     1,265 |                       6 |                        258 |                        1 |                                       26% |                                 1,056 |                                  1,817 |
|                             [Kuwait](/kuwait) |              519 |                       684 |                     163 |                        165 |                       39 |                                       32% |                                   545 |                                  1,048 |
| [United Arab Emirates](/united-arab-emirates) |              377 |                       463 |                      47 |                         86 |                        9 |                                       23% |                                   382 |                                    678 |
|                   [South Korea](/south-korea) |              312 |                       376 |                       7 |                         64 |                        1 |                                       21% |                                   312 |                                    590 |
|                         [Malaysia](/malaysia) |              125 |                       139 |                       4 |                         14 |                        0 |                                       11% |                                   128 |                                    153 |
|                                 [Cuba](/cuba) |               91 |                       136 |                      12 |                         45 |                        4 |                                       49% |                                   101 |                                    227 |
