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
* **August 5:** We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *August 3:* View our [updated historical performance](/about/#historical-performance).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

For regular updates and insights, follow our Twitter:<br>
<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: August 6 (2pm ET):
<p align="center">
  Current Total: <b>158,247</b> deaths | Projected Total: <b>228,000 deaths by Nov 1, 2020</b> (Range: 200-267k)<br>
  Currently Infected: <b>1.9%</b> (1 in 52) | Total Infected: <b>12.4%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 5, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |        99% |        >99% |       >99% |
|              200,000 |         <1% |         2% |         33% |        75% |         90% |        98% |
|              225,000 |         <1% |        <1% |         <1% |        10% |         26% |        46% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          3% |        10% |
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
|             *[United States](/us)* |          158,247 |                   228,074 |                     687 |                     69,827 |                                       44% |                               200,498 |                                266,831 |
|                 [New York](/us-ny) |           32,754 |                    33,332 |                   1,713 |                        578 |                                        2% |                                32,785 |                                 36,005 |
|                    [Texas](/us-tx) |            7,706 |                    18,894 |                     652 |                     11,188 |                                      145% |                                13,526 |                                 25,717 |
|               [California](/us-ca) |            9,808 |                    18,752 |                     475 |                      8,944 |                                       91% |                                13,305 |                                 25,928 |
|               [New Jersey](/us-nj) |           15,842 |                    16,637 |                   1,873 |                        795 |                                        5% |                                15,910 |                                 18,820 |
|                  [Florida](/us-fl) |            7,627 |                    16,144 |                     752 |                      8,517 |                                      112% |                                12,028 |                                 20,988 |
|            [Massachusetts](/us-ma) |            8,659 |                     9,842 |                   1,416 |                      1,183 |                                       14% |                                 8,764 |                                 12,179 |
|                 [Illinois](/us-il) |            7,770 |                     9,723 |                     767 |                      1,953 |                                       25% |                                 8,145 |                                 12,997 |
|             [Pennsylvania](/us-pa) |            7,254 |                     8,423 |                     658 |                      1,169 |                                       16% |                                 7,364 |                                 10,629 |
|                 [Michigan](/us-mi) |            6,478 |                     7,280 |                     729 |                        802 |                                       12% |                                 6,551 |                                  8,975 |
|                  [Arizona](/us-az) |            3,932 |                     6,886 |                     946 |                      2,954 |                                       75% |                                 5,397 |                                  8,679 |
|                  [Georgia](/us-ga) |            3,984 |                     6,840 |                     644 |                      2,856 |                                       72% |                                 5,121 |                                  9,298 |
|                [Louisiana](/us-la) |            4,096 |                     5,590 |                   1,202 |                      1,494 |                                       36% |                                 4,681 |                                  7,050 |
|                     [Ohio](/us-oh) |            3,596 |                     5,564 |                     476 |                      1,968 |                                       55% |                                 4,146 |                                  7,929 |
|                 [Maryland](/us-md) |            3,536 |                     4,828 |                     799 |                      1,292 |                                       37% |                                 3,751 |                                  7,370 |
|              [Connecticut](/us-ct) |            4,437 |                     4,635 |                   1,300 |                        198 |                                        4% |                                 4,468 |                                  5,045 |
|                  [Indiana](/us-in) |            3,007 |                     4,265 |                     633 |                      1,258 |                                       42% |                                 3,161 |                                  6,638 |
|           [South Carolina](/us-sc) |            1,894 |                     4,252 |                     826 |                      2,358 |                                      125% |                                 3,082 |                                  5,658 |
|                 [Virginia](/us-va) |            2,274 |                     4,159 |                     487 |                      1,885 |                                       83% |                                 2,594 |                                  7,509 |
|           [North Carolina](/us-nc) |            2,085 |                     3,935 |                     375 |                      1,850 |                                       89% |                                 2,783 |                                  5,649 |
|              [Mississippi](/us-ms) |            1,804 |                     3,449 |                   1,159 |                      1,645 |                                       91% |                                 2,527 |                                  4,806 |
|                  [Alabama](/us-al) |            1,695 |                     3,079 |                     628 |                      1,384 |                                       82% |                                 2,322 |                                  4,098 |
|               [Washington](/us-wa) |            1,624 |                     2,792 |                     367 |                      1,168 |                                       72% |                                 1,858 |                                  4,558 |
|                 [Colorado](/us-co) |            1,851 |                     2,572 |                     447 |                        721 |                                       39% |                                 1,981 |                                  3,892 |
|                [Tennessee](/us-tn) |            1,144 |                     2,447 |                     358 |                      1,303 |                                      114% |                                 1,693 |                                  3,459 |
|                 [Missouri](/us-mo) |            1,297 |                     2,308 |                     376 |                      1,011 |                                       78% |                                 1,579 |                                  3,600 |
|                [Minnesota](/us-mn) |            1,670 |                     2,287 |                     406 |                        617 |                                       37% |                                 1,769 |                                  3,406 |
|                   [Nevada](/us-nv) |              890 |                     1,836 |                     596 |                        946 |                                      106% |                                 1,319 |                                  2,505 |
|                [Wisconsin](/us-wi) |              970 |                     1,819 |                     312 |                        849 |                                       88% |                                 1,174 |                                  3,085 |
|                     [Iowa](/us-ia) |              900 |                     1,457 |                     462 |                        557 |                                       62% |                                 1,049 |                                  2,206 |
|                 [Kentucky](/us-ky) |              752 |                     1,321 |                     296 |                        569 |                                       76% |                                   919 |                                  2,103 |
|                 [Oklahoma](/us-ok) |              583 |                     1,301 |                     329 |                        718 |                                      123% |                                   843 |                                  1,981 |
|                 [Arkansas](/us-ar) |              508 |                     1,199 |                     397 |                        691 |                                      136% |                                   797 |                                  1,749 |
|             [Rhode Island](/us-ri) |            1,012 |                     1,124 |                   1,061 |                        112 |                                       11% |                                 1,034 |                                  1,301 |
|               [New Mexico](/us-nm) |              667 |                     1,124 |                     536 |                        457 |                                       68% |                                   801 |                                  1,660 |
|                   [Oregon](/us-or) |              338 |                       852 |                     202 |                        514 |                                      152% |                                   509 |                                  1,368 |
|              [Puerto Rico](/us-pr) |              246 |                       820 |                     257 |                        574 |                                      233% |                                   432 |                                  1,484 |
|                     [Utah](/us-ut) |              327 |                       797 |                     249 |                        470 |                                      144% |                                   500 |                                  1,213 |
|                    [Idaho](/us-id) |              217 |                       783 |                     438 |                        566 |                                      261% |                                   470 |                                  1,229 |
|                   [Kansas](/us-ks) |              372 |                       729 |                     250 |                        357 |                                       96% |                                   483 |                                  1,194 |
|                 [Delaware](/us-de) |              587 |                       671 |                     689 |                         84 |                                       14% |                                   601 |                                    808 |
|     [District of Columbia](/us-dc) |              587 |                       650 |                     922 |                         63 |                                       11% |                                   598 |                                    758 |
|            [New Hampshire](/us-nh) |              418 |                       577 |                     424 |                        159 |                                       38% |                                   437 |                                    883 |
|                 [Nebraska](/us-ne) |              340 |                       542 |                     280 |                        202 |                                       59% |                                   412 |                                    855 |
|            [West Virginia](/us-wv) |              124 |                       360 |                     201 |                        236 |                                      190% |                                   187 |                                    723 |
|                  [Montana](/us-mt) |               65 |                       242 |                     226 |                        177 |                                      272% |                                   130 |                                    414 |
|             [South Dakota](/us-sd) |              137 |                       225 |                     254 |                         88 |                                       64% |                                   168 |                                    333 |
|             [North Dakota](/us-nd) |              108 |                       210 |                     276 |                        102 |                                       95% |                                   139 |                                    339 |
|                    [Maine](/us-me) |              124 |                       197 |                     147 |                         73 |                                       59% |                                   142 |                                    325 |
|                   [Hawaii](/us-hi) |               27 |                        93 |                      66 |                         66 |                                      244% |                                    40 |                                    240 |
|                   [Alaska](/us-ak) |               25 |                        80 |                     109 |                         55 |                                      219% |                                    44 |                                    140 |
|                  [Vermont](/us-vt) |               57 |                        77 |                     123 |                         20 |                                       35% |                                    61 |                                    111 |
|                  [Wyoming](/us-wy) |               27 |                        44 |                      75 |                         17 |                                       62% |                                    33 |                                     61 |
|           [Virgin Islands](/us-vi) |                8 |                        18 |                     176 |                         10 |                                      131% |                                    11 |                                     32 |
|                     [Guam](/us-gu) |                5 |                         9 |                      52 |                          4 |                                       71% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       58% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,016 |                   207,881 |                     350 |                     18,865 |                                       10% |                               192,427 |                                249,796 |
| [United Kingdom](/united-kingdom) |           46,295 |                    50,257 |                     744 |                      3,962 |                                        9% |                                46,546 |                                 58,042 |
|                   [Italy](/italy) |           35,181 |                    35,643 |                     591 |                        462 |                                        1% |                                35,203 |                                 36,975 |
|                 [France](/france) |           30,297 |                    31,112 |                     464 |                        815 |                                        3% |                                30,320 |                                 35,580 |
|                   [Spain](/spain) |           28,499 |                    30,253 |                     645 |                      1,754 |                                        6% |                                28,551 |                                 38,016 |
|               [Belgium](/belgium) |            9,859 |                    10,090 |                     881 |                        231 |                                        2% |                                 9,886 |                                 11,070 |
|               [Germany](/germany) |            9,179 |                     9,995 |                     120 |                        816 |                                        9% |                                 9,209 |                                 12,494 |
|       [Netherlands](/netherlands) |            6,173 |                     6,372 |                     369 |                        199 |                                        3% |                                 6,188 |                                  7,240 |
|                 [Sweden](/sweden) |            5,760 |                     6,057 |                     592 |                        297 |                                        5% |                                 5,828 |                                  6,356 |
|               [Romania](/romania) |            2,521 |                     5,851 |                     301 |                      3,330 |                                      132% |                                 3,560 |                                 10,160 |
|               [Ukraine](/ukraine) |            1,813 |                     3,644 |                      83 |                      1,831 |                                      101% |                                 2,356 |                                  6,345 |
|                 [Poland](/poland) |            1,756 |                     2,848 |                      75 |                      1,092 |                                       62% |                                 1,942 |                                  4,992 |
|       [Switzerland](/switzerland) |            1,984 |                     2,072 |                     241 |                         88 |                                        4% |                                 1,997 |                                  2,310 |
|             [Portugal](/portugal) |            1,740 |                     2,040 |                     199 |                        300 |                                       17% |                                 1,753 |                                  2,757 |
|               [Ireland](/ireland) |            1,763 |                     1,829 |                     373 |                         66 |                                        4% |                                 1,775 |                                  2,054 |
|               [Moldova](/moldova) |              823 |                     1,472 |                     364 |                        649 |                                       79% |                                 1,057 |                                  2,232 |
|             [Bulgaria](/bulgaria) |              424 |                     1,312 |                     187 |                        888 |                                      209% |                                   712 |                                  2,539 |
|                 [Serbia](/serbia) |              614 |                     1,247 |                     179 |                        633 |                                      103% |                                   823 |                                  2,152 |
|               [Austria](/austria) |              719 |                       836 |                      94 |                        117 |                                       16% |                                   737 |                                  1,138 |
|               [Belarus](/belarus) |              577 |                       819 |                      87 |                        242 |                                       42% |                                   723 |                                  1,017 |
|               [Denmark](/denmark) |              616 |                       704 |                     121 |                         88 |                                       14% |                                   631 |                                    894 |
|               [Hungary](/hungary) |              599 |                       692 |                      71 |                         93 |                                       15% |                                   606 |                                    918 |
|               [Czechia](/czechia) |              388 |                       634 |                      60 |                        246 |                                       64% |                                   426 |                                  1,188 |
|               [Croatia](/croatia) |              154 |                       400 |                      98 |                        246 |                                      160% |                                   219 |                                    808 |
|               [Finland](/finland) |              331 |                       371 |                      67 |                         40 |                                       12% |                                   341 |                                    446 |
|                 [Greece](/greece) |              210 |                       330 |                      31 |                        120 |                                       57% |                                   235 |                                    542 |
|                 [Norway](/norway) |              256 |                       291 |                      54 |                         35 |                                       14% |                                   263 |                                    382 |
|         [Luxembourg](/luxembourg) |              118 |                       211 |                     343 |                         93 |                                       78% |                                   140 |                                    406 |
|             [Slovenia](/slovenia) |              124 |                       192 |                      92 |                         68 |                                       55% |                                   138 |                                    330 |
|           [Lithuania](/lithuania) |               81 |                       101 |                      36 |                         20 |                                       25% |                                    87 |                                    130 |
|               [Estonia](/estonia) |               63 |                        73 |                      55 |                         10 |                                       16% |                                    69 |                                     85 |
|                 [Latvia](/latvia) |               32 |                        42 |                      22 |                         10 |                                       30% |                                    34 |                                     58 |
|             [Slovakia](/slovakia) |               29 |                        40 |                       7 |                         11 |                                       36% |                                    30 |                                     65 |
|                 [Cyprus](/cyprus) |               19 |                        26 |                      30 |                          7 |                                       38% |                                    22 |                                     37 |
|               [Iceland](/iceland) |               10 |                        14 |                      40 |                          4 |                                       37% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       31% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          338,482 |                   664,566 |                     128 |                    326,084 |                                       96% |                               455,262 |                                992,194 |
|                             [Brazil](/brazil) |           97,256 |                   181,838 |                     862 |                     84,582 |                                       87% |                               120,677 |                                260,483 |
|                               [India](/india) |           40,699 |                   124,098 |                      91 |                     83,399 |                                      205% |                                72,232 |                                184,085 |
|                             [Mexico](/mexico) |           49,698 |                    89,419 |                     701 |                     39,721 |                                       80% |                                72,602 |                                122,706 |
|                         [Colombia](/colombia) |           11,624 |                    33,217 |                     660 |                     21,593 |                                      186% |                                20,774 |                                 52,572 |
|                                 [Peru](/peru) |           20,228 |                    30,469 |                     937 |                     10,241 |                                       51% |                                23,918 |                                 45,023 |
|                                 [Iran](/iran) |           17,802 |                    28,647 |                     345 |                     10,845 |                                       61% |                                21,756 |                                 40,773 |
|                 [South Africa](/south-africa) |            9,298 |                    25,498 |                     435 |                     16,200 |                                      174% |                                16,464 |                                 39,148 |
|                             [Russia](/russia) |           14,465 |                    22,052 |                     151 |                      7,587 |                                       52% |                                15,806 |                                 34,824 |
|                       [Argentina](/argentina) |            4,106 |                    14,985 |                     335 |                     10,879 |                                      265% |                                 8,041 |                                 24,651 |
|                               [Chile](/chile) |            9,792 |                    13,921 |                     735 |                      4,129 |                                       42% |                                10,532 |                                 24,437 |
|                       [Indonesia](/indonesia) |            5,452 |                    12,448 |                      46 |                      6,996 |                                      128% |                                 7,659 |                                 23,296 |
|                             [Canada](/canada) |            9,010 |                     9,459 |                     253 |                        449 |                                        5% |                                 9,047 |                                 10,563 |
|                           [Bolivia](/bolivia) |            3,385 |                     8,174 |                     710 |                      4,789 |                                      141% |                                 4,992 |                                 13,579 |
|                           [Ecuador](/ecuador) |            5,847 |                     7,448 |                     429 |                      1,601 |                                       27% |                                 6,102 |                                 10,314 |
|                         [Pakistan](/pakistan) |            6,014 |                     7,135 |                      33 |                      1,121 |                                       19% |                                 6,241 |                                  8,627 |
|                             [Turkey](/turkey) |            5,784 |                     6,973 |                      84 |                      1,189 |                                       21% |                                 5,833 |                                  9,985 |
|                               [Egypt](/egypt) |            4,930 |                     6,604 |                      66 |                      1,674 |                                       34% |                                 5,132 |                                  8,958 |
|                     [Bangladesh](/bangladesh) |            3,267 |                     5,423 |                      33 |                      2,156 |                                       66% |                                 3,869 |                                  8,921 |
|                   [Philippines](/philippines) |            2,123 |                     4,999 |                      46 |                      2,876 |                                      135% |                                 2,421 |                                 11,538 |
|                               [China](/china) |            4,677 |                     4,959 |                       3 |                        282 |                                        6% |                                 4,677 |                                  6,833 |
|                 [Saudi Arabia](/saudi-arabia) |            3,020 |                     4,813 |                     140 |                      1,793 |                                       59% |                                 3,596 |                                  6,963 |
|                         [Honduras](/honduras) |            1,423 |                     3,389 |                     348 |                      1,966 |                                      138% |                                 2,029 |                                  6,239 |
|                             [Panama](/panama) |            1,553 |                     3,186 |                     750 |                      1,633 |                                      105% |                                 2,135 |                                  5,048 |
|                           [Morocco](/morocco) |              435 |                     2,954 |                      81 |                      2,519 |                                      579% |                                   877 |                                  7,564 |
|     [Dominican Republic](/dominican-republic) |            1,222 |                     2,349 |                     219 |                      1,127 |                                       92% |                                 1,564 |                                  4,194 |
|                           [Algeria](/algeria) |            1,261 |                     2,341 |                      54 |                      1,080 |                                       86% |                                 1,455 |                                  4,486 |
|                               [Japan](/japan) |            1,028 |                     1,718 |                      14 |                        690 |                                       67% |                                 1,048 |                                  4,602 |
|                             [Israel](/israel) |              565 |                     1,504 |                     177 |                        939 |                                      166% |                                   830 |                                  3,004 |
|                           [Nigeria](/nigeria) |              927 |                     1,448 |                       7 |                        521 |                                       56% |                                 1,047 |                                  2,724 |
|                       [Australia](/australia) |              255 |                     1,139 |                      45 |                        884 |                                      347% |                                   497 |                                  2,562 |
|                             [Kuwait](/kuwait) |              468 |                       856 |                     203 |                        388 |                                       83% |                                   517 |                                  1,779 |
| [United Arab Emirates](/united-arab-emirates) |              353 |                       459 |                      47 |                        106 |                                       30% |                                   361 |                                    732 |
|                   [South Korea](/south-korea) |              302 |                       379 |                       7 |                         77 |                                       25% |                                   302 |                                    642 |
|                         [Malaysia](/malaysia) |              125 |                       150 |                       5 |                         25 |                                       20% |                                   135 |                                    170 |
|                                 [Cuba](/cuba) |               88 |                       117 |                      10 |                         29 |                                       32% |                                    94 |                                    169 |
