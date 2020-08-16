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
### Updated Daily - Last Updated: August 16 (11am ET):
<p align="center">
  Current Total: <b>169,478</b> deaths | Projected Total: <b>227,700 deaths by Nov 1, 2020</b> (Range: 205-259k)<br>
  Currently Infected: <b>1.7%</b> (1 in 60) | Total Infected: <b>13.4%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 16, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 19, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              175,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |        <1% |         32% |        87% |         99% |        99% |
|              225,000 |        <1% |         <1% |         5% |         22% |        47% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         7% |
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
|             *[United States](/us)* |          169,478 |                   227,675 |                     686 |                     58,197 |                                       34% |                               205,543 |                                258,104 |
|                 [New York](/us-ny) |           32,833 |                    33,255 |                   1,709 |                        422 |                                        1% |                                32,850 |                                 35,285 |
|               [California](/us-ca) |           11,218 |                    19,145 |                     485 |                      7,927 |                                       71% |                                14,615 |                                 25,471 |
|                    [Texas](/us-tx) |           10,268 |                    19,105 |                     659 |                      8,837 |                                       86% |                                15,020 |                                 23,822 |
|                  [Florida](/us-fl) |            9,345 |                    16,882 |                     786 |                      7,537 |                                       81% |                                13,374 |                                 21,353 |
|               [New Jersey](/us-nj) |           15,910 |                    16,265 |                   1,831 |                        355 |                                        2% |                                15,944 |                                 17,256 |
|            [Massachusetts](/us-ma) |            8,826 |                     9,890 |                   1,423 |                      1,064 |                                       12% |                                 8,920 |                                 12,008 |
|                 [Illinois](/us-il) |            7,937 |                     9,554 |                     754 |                      1,617 |                                       20% |                                 8,249 |                                 12,315 |
|             [Pennsylvania](/us-pa) |            7,451 |                     8,623 |                     674 |                      1,172 |                                       16% |                                 7,551 |                                 10,616 |
|                  [Georgia](/us-ga) |            4,669 |                     7,678 |                     723 |                      3,009 |                                       64% |                                 6,106 |                                 10,041 |
|                 [Michigan](/us-mi) |            6,586 |                     7,349 |                     736 |                        763 |                                       12% |                                 6,653 |                                  8,720 |
|                  [Arizona](/us-az) |            4,492 |                     6,747 |                     927 |                      2,255 |                                       50% |                                 5,598 |                                  8,239 |
|                [Louisiana](/us-la) |            4,430 |                     5,694 |                   1,225 |                      1,264 |                                       29% |                                 4,974 |                                  6,764 |
|                     [Ohio](/us-oh) |            3,824 |                     5,525 |                     473 |                      1,701 |                                       44% |                                 4,370 |                                  7,435 |
|              [Connecticut](/us-ct) |            4,453 |                     4,576 |                   1,283 |                        123 |                                        3% |                                 4,472 |                                  4,854 |
|                 [Maryland](/us-md) |            3,636 |                     4,564 |                     755 |                        928 |                                       26% |                                 3,742 |                                  6,369 |
|                  [Indiana](/us-in) |            3,128 |                     4,211 |                     625 |                      1,083 |                                       35% |                                 3,255 |                                  5,952 |
|           [South Carolina](/us-sc) |            2,260 |                     4,026 |                     782 |                      1,766 |                                       78% |                                 3,122 |                                  5,141 |
|           [North Carolina](/us-nc) |            2,343 |                     3,951 |                     377 |                      1,608 |                                       69% |                                 2,986 |                                  5,488 |
|                 [Virginia](/us-va) |            2,381 |                     3,463 |                     406 |                      1,082 |                                       45% |                                 2,551 |                                  5,241 |
|              [Mississippi](/us-ms) |            2,080 |                     3,258 |                   1,095 |                      1,178 |                                       57% |                                 2,628 |                                  4,058 |
|                  [Alabama](/us-al) |            1,896 |                     2,929 |                     597 |                      1,033 |                                       54% |                                 2,363 |                                  3,707 |
|               [Washington](/us-wa) |            1,766 |                     2,835 |                     372 |                      1,069 |                                       61% |                                 2,083 |                                  4,197 |
|                [Tennessee](/us-tn) |            1,345 |                     2,523 |                     369 |                      1,178 |                                       88% |                                 1,861 |                                  3,536 |
|                 [Colorado](/us-co) |            1,896 |                     2,355 |                     409 |                        459 |                                       24% |                                 1,940 |                                  3,203 |
|                [Minnesota](/us-mn) |            1,705 |                     2,204 |                     391 |                        499 |                                       29% |                                 1,782 |                                  3,058 |
|                 [Missouri](/us-mo) |            1,378 |                     2,111 |                     344 |                        733 |                                       53% |                                 1,612 |                                  2,982 |
|                   [Nevada](/us-nv) |            1,069 |                     1,971 |                     640 |                        902 |                                       84% |                                 1,503 |                                  2,561 |
|                [Wisconsin](/us-wi) |            1,038 |                     1,640 |                     282 |                        602 |                                       58% |                                 1,235 |                                  2,423 |
|                     [Iowa](/us-ia) |              975 |                     1,462 |                     463 |                        487 |                                       50% |                                 1,123 |                                  2,017 |
|                 [Kentucky](/us-ky) |              810 |                     1,278 |                     286 |                        468 |                                       58% |                                   959 |                                  1,819 |
|                 [Oklahoma](/us-ok) |              657 |                     1,251 |                     316 |                        594 |                                       90% |                                   884 |                                  1,791 |
|                 [Arkansas](/us-ar) |              600 |                     1,174 |                     389 |                        574 |                                       96% |                                   855 |                                  1,629 |
|              [Puerto Rico](/us-pr) |              329 |                     1,123 |                     352 |                        794 |                                      241% |                                   654 |                                  1,974 |
|             [Rhode Island](/us-ri) |            1,021 |                     1,120 |                   1,057 |                         99 |                                       10% |                                 1,038 |                                  1,281 |
|               [New Mexico](/us-nm) |              711 |                     1,053 |                     502 |                        342 |                                       48% |                                   839 |                                  1,450 |
|                   [Oregon](/us-or) |              386 |                       802 |                     190 |                        416 |                                      108% |                                   538 |                                  1,224 |
|                   [Kansas](/us-ks) |              406 |                       689 |                     236 |                        283 |                                       70% |                                   504 |                                  1,021 |
|                     [Utah](/us-ut) |              363 |                       681 |                     212 |                        318 |                                       88% |                                   482 |                                  1,007 |
|                 [Delaware](/us-de) |              593 |                       672 |                     690 |                         79 |                                       13% |                                   605 |                                    803 |
|     [District of Columbia](/us-dc) |              597 |                       653 |                     925 |                         56 |                                        9% |                                   608 |                                    747 |
|                    [Idaho](/us-id) |              269 |                       650 |                     364 |                        381 |                                      142% |                                   446 |                                    924 |
|                 [Nebraska](/us-ne) |              361 |                       526 |                     272 |                        165 |                                       46% |                                   425 |                                    748 |
|            [New Hampshire](/us-nh) |              423 |                       514 |                     378 |                         91 |                                       22% |                                   432 |                                    749 |
|            [West Virginia](/us-wv) |              160 |                       464 |                     259 |                        304 |                                      190% |                                   274 |                                    797 |
|             [South Dakota](/us-sd) |              152 |                       233 |                     263 |                         81 |                                       53% |                                   182 |                                    330 |
|                  [Montana](/us-mt) |               82 |                       225 |                     211 |                        143 |                                      174% |                                   138 |                                    366 |
|             [North Dakota](/us-nd) |              121 |                       216 |                     283 |                         95 |                                       78% |                                   156 |                                    319 |
|                   [Hawaii](/us-hi) |               40 |                       188 |                     133 |                        148 |                                      371% |                                    82 |                                    419 |
|                    [Maine](/us-me) |              127 |                       155 |                     115 |                         28 |                                       22% |                                   132 |                                    198 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     118 |                         16 |                                       27% |                                    61 |                                    103 |
|                   [Alaska](/us-ak) |               28 |                        65 |                      89 |                         37 |                                      133% |                                    42 |                                    108 |
|                  [Wyoming](/us-wy) |               30 |                        50 |                      86 |                         20 |                                       65% |                                    39 |                                     72 |
|           [Virgin Islands](/us-vi) |                9 |                        18 |                     168 |                          9 |                                       96% |                                    12 |                                     28 |
|                     [Guam](/us-gu) |                5 |                         8 |                      49 |                          3 |                                       63% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       55% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          191,290 |                   209,636 |                     353 |                     18,346 |                                       10% |                               195,050 |                                251,418 |
| [United Kingdom](/united-kingdom) |           46,791 |                    49,526 |                     733 |                      2,735 |                                        6% |                                46,918 |                                 57,473 |
|                   [Italy](/italy) |           35,392 |                    36,198 |                     600 |                        806 |                                        2% |                                35,417 |                                 38,885 |
|                 [France](/france) |           30,410 |                    31,299 |                     467 |                        889 |                                        3% |                                30,445 |                                 35,773 |
|                   [Spain](/spain) |           28,617 |                    29,925 |                     638 |                      1,308 |                                        5% |                                28,655 |                                 34,750 |
|               [Belgium](/belgium) |            9,935 |                    10,448 |                     912 |                        513 |                                        5% |                                 9,972 |                                 12,420 |
|               [Germany](/germany) |            9,235 |                    10,209 |                     123 |                        974 |                                       11% |                                 9,325 |                                 12,931 |
|               [Romania](/romania) |            2,954 |                     6,636 |                     342 |                      3,682 |                                      125% |                                 4,287 |                                 11,060 |
|       [Netherlands](/netherlands) |            6,191 |                     6,564 |                     380 |                        373 |                                        6% |                                 6,217 |                                  8,013 |
|                 [Sweden](/sweden) |            5,783 |                     5,947 |                     581 |                        164 |                                        3% |                                 5,814 |                                  6,054 |
|               [Ukraine](/ukraine) |            2,076 |                     4,795 |                     109 |                      2,719 |                                      131% |                                 2,916 |                                  8,883 |
|                 [Poland](/poland) |            1,869 |                     2,958 |                      78 |                      1,089 |                                       58% |                                 2,150 |                                  4,593 |
|       [Switzerland](/switzerland) |            1,991 |                     2,080 |                     242 |                         89 |                                        4% |                                 2,003 |                                  2,419 |
|             [Portugal](/portugal) |            1,775 |                     2,054 |                     200 |                        279 |                                       16% |                                 1,786 |                                  2,668 |
|               [Ireland](/ireland) |            1,774 |                     1,857 |                     379 |                         83 |                                        5% |                                 1,785 |                                  2,099 |
|               [Moldova](/moldova) |              895 |                     1,409 |                     349 |                        514 |                                       57% |                                 1,090 |                                  2,065 |
|             [Bulgaria](/bulgaria) |              495 |                     1,046 |                     149 |                        551 |                                      111% |                                   690 |                                  1,976 |
|                 [Serbia](/serbia) |              670 |                     1,037 |                     149 |                        367 |                                       55% |                                   811 |                                  1,478 |
|               [Austria](/austria) |              728 |                       826 |                      93 |                         98 |                                       13% |                                   742 |                                  1,072 |
|               [Belarus](/belarus) |              603 |                       794 |                      84 |                        191 |                                       32% |                                   716 |                                    978 |
|               [Denmark](/denmark) |              621 |                       717 |                     124 |                         96 |                                       16% |                                   640 |                                    969 |
|               [Hungary](/hungary) |              607 |                       692 |                      71 |                         85 |                                       14% |                                   615 |                                    902 |
|               [Czechia](/czechia) |              395 |                       533 |                      50 |                        138 |                                       35% |                                   421 |                                    800 |
|                 [Greece](/greece) |              226 |                       432 |                      40 |                        206 |                                       91% |                                   279 |                                    768 |
|               [Finland](/finland) |              333 |                       373 |                      68 |                         40 |                                       12% |                                   340 |                                    484 |
|                 [Norway](/norway) |              261 |                       306 |                      57 |                         45 |                                       17% |                                   269 |                                    417 |
|               [Croatia](/croatia) |              165 |                       300 |                      74 |                        135 |                                       82% |                                   206 |                                    508 |
|             [Slovenia](/slovenia) |              129 |                       184 |                      88 |                         55 |                                       42% |                                   140 |                                    280 |
|         [Luxembourg](/luxembourg) |              123 |                       181 |                     294 |                         58 |                                       47% |                                   139 |                                    273 |
|           [Lithuania](/lithuania) |               81 |                        95 |                      34 |                         14 |                                       18% |                                    84 |                                    126 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        46 |                       8 |                         15 |                                       48% |                                    33 |                                     82 |
|                 [Latvia](/latvia) |               32 |                        39 |                      20 |                          7 |                                       22% |                                    33 |                                     52 |
|                 [Cyprus](/cyprus) |               20 |                        32 |                      37 |                         12 |                                       62% |                                    24 |                                     53 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       29% |                                    10 |                                     19 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       30% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          385,230 |                   670,361 |                     129 |                    285,131 |                                       74% |                               496,246 |                                962,013 |
|                             [Brazil](/brazil) |          107,232 |                   174,390 |                     826 |                     67,158 |                                       63% |                               127,376 |                                243,773 |
|                               [India](/india) |           49,980 |                   123,499 |                      90 |                     73,519 |                                      147% |                                81,786 |                                175,644 |
|                             [Mexico](/mexico) |           56,543 |                    99,798 |                     782 |                     43,255 |                                       76% |                                83,091 |                                137,566 |
|                                 [Peru](/peru) |           25,856 |                    35,886 |                   1,104 |                     10,030 |                                       39% |                                28,671 |                                 48,277 |
|                         [Colombia](/colombia) |           14,810 |                    31,590 |                     628 |                     16,780 |                                      113% |                                21,909 |                                 47,249 |
|                                 [Iran](/iran) |           19,492 |                    27,856 |                     336 |                      8,364 |                                       43% |                                22,577 |                                 37,846 |
|                 [South Africa](/south-africa) |           11,677 |                    22,525 |                     385 |                     10,848 |                                       93% |                                15,634 |                                 32,771 |
|                             [Russia](/russia) |           15,585 |                    22,149 |                     152 |                      6,564 |                                       42% |                                17,668 |                                 31,465 |
|                       [Argentina](/argentina) |            5,637 |                    17,679 |                     395 |                     12,042 |                                      214% |                                 9,836 |                                 29,135 |
|                               [Chile](/chile) |           10,395 |                    15,227 |                     803 |                      4,832 |                                       46% |                                11,073 |                                 25,882 |
|                       [Indonesia](/indonesia) |            6,071 |                    10,732 |                      40 |                      4,661 |                                       77% |                                 7,717 |                                 17,718 |
|                             [Canada](/canada) |            9,072 |                     9,498 |                     254 |                        426 |                                        5% |                                 9,108 |                                 10,515 |
|                           [Ecuador](/ecuador) |            6,065 |                     7,464 |                     430 |                      1,399 |                                       23% |                                 6,222 |                                 10,502 |
|                             [Turkey](/turkey) |            5,955 |                     7,425 |                      89 |                      1,470 |                                       25% |                                 6,027 |                                 11,221 |
|                   [Philippines](/philippines) |            2,600 |                     7,358 |                      68 |                      4,758 |                                      183% |                                 3,932 |                                 14,780 |
|                           [Bolivia](/bolivia) |            4,003 |                     7,186 |                     624 |                      3,183 |                                       80% |                                 5,168 |                                 11,034 |
|                         [Pakistan](/pakistan) |            6,162 |                     7,043 |                      33 |                        881 |                                       14% |                                 6,306 |                                  8,237 |
|                               [Egypt](/egypt) |            5,141 |                     5,905 |                      59 |                        764 |                                       15% |                                 5,271 |                                  7,095 |
|                     [Bangladesh](/bangladesh) |            3,625 |                     5,639 |                      35 |                      2,014 |                                       56% |                                 4,132 |                                  8,868 |
|                 [Saudi Arabia](/saudi-arabia) |            3,369 |                     4,938 |                     144 |                      1,569 |                                       47% |                                 3,919 |                                  7,094 |
|                               [China](/china) |            4,703 |                     4,912 |                       3 |                        209 |                                        4% |                                 4,703 |                                  6,354 |
|                           [Morocco](/morocco) |              632 |                     3,267 |                      90 |                      2,635 |                                      417% |                                 1,366 |                                  7,242 |
|                             [Panama](/panama) |            1,746 |                     2,793 |                     658 |                      1,047 |                                       60% |                                 2,110 |                                  4,024 |
|     [Dominican Republic](/dominican-republic) |            1,438 |                     2,722 |                     253 |                      1,284 |                                       89% |                                 1,857 |                                  4,422 |
|                         [Honduras](/honduras) |            1,567 |                     2,663 |                     273 |                      1,096 |                                       70% |                                 1,920 |                                  4,221 |
|                           [Algeria](/algeria) |            1,360 |                     2,211 |                      51 |                        851 |                                       63% |                                 1,560 |                                  3,740 |
|                               [Japan](/japan) |            1,093 |                     1,832 |                      14 |                        739 |                                       68% |                                 1,145 |                                  4,329 |
|                             [Israel](/israel) |              674 |                     1,551 |                     182 |                        877 |                                      130% |                                   954 |                                  2,898 |
|                       [Australia](/australia) |              396 |                     1,434 |                      57 |                      1,038 |                                      262% |                                   724 |                                  2,999 |
|                           [Nigeria](/nigeria) |              974 |                     1,334 |                       7 |                        360 |                                       37% |                                 1,047 |                                  2,087 |
|                             [Kuwait](/kuwait) |              498 |                       768 |                     182 |                        270 |                                       54% |                                   541 |                                  1,359 |
| [United Arab Emirates](/united-arab-emirates) |              361 |                       449 |                      46 |                         88 |                                       24% |                                   367 |                                    688 |
|                   [South Korea](/south-korea) |              305 |                       371 |                       7 |                         66 |                                       22% |                                   305 |                                    601 |
|                         [Malaysia](/malaysia) |              125 |                       141 |                       4 |                         16 |                                       13% |                                   129 |                                    157 |
|                                 [Cuba](/cuba) |               88 |                       128 |                      11 |                         40 |                                       46% |                                    95 |                                    220 |
