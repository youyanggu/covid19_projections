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

* *August 31:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 12 (3am ET):
<p align="center">
  Current Total: <b>192,976</b> deaths | Projected Total: <b>221,700 deaths by Nov 1, 2020</b> (Range: 211-237k)<br>
  Currently Infected: <b>1.1%</b> (1 in 95) | Total Infected: <b>15.8%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 11, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        99% |         99% |       >99% |
|              225,000 |         <1% |        <1% |          2% |        22% |
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
|             *[United States](/us)* |          192,976 |                   221,717 |                     668 |                     28,741 |                       87 |                                       15% |                               211,532 |                                236,581 |
|                 [New York](/us-ny) |           33,019 |                    33,332 |                   1,713 |                        313 |                       16 |                                        1% |                                33,030 |                                 35,152 |
|                    [Texas](/us-tx) |           14,227 |                    18,711 |                     645 |                      4,484 |                      155 |                                       32% |                                17,262 |                                 20,409 |
|               [California](/us-ca) |           14,230 |                    18,109 |                     458 |                      3,879 |                       98 |                                       27% |                                15,934 |                                 21,595 |
|               [New Jersey](/us-nj) |           16,023 |                    16,177 |                   1,821 |                        154 |                       17 |                                        1% |                                16,034 |                                 16,708 |
|                  [Florida](/us-fl) |           12,502 |                    15,616 |                     727 |                      3,114 |                      145 |                                       25% |                                14,520 |                                 17,200 |
|            [Massachusetts](/us-ma) |            9,180 |                     9,534 |                   1,372 |                        354 |                       51 |                                        4% |                                 9,203 |                                 10,355 |
|                 [Illinois](/us-il) |            8,505 |                     9,379 |                     740 |                        874 |                       69 |                                       10% |                                 8,597 |                                 10,521 |
|             [Pennsylvania](/us-pa) |            7,829 |                     8,384 |                     655 |                        555 |                       43 |                                        7% |                                 7,853 |                                  9,488 |
|                  [Georgia](/us-ga) |            6,246 |                     7,848 |                     739 |                      1,602 |                      151 |                                       26% |                                 7,022 |                                  9,024 |
|                 [Michigan](/us-mi) |            6,900 |                     7,369 |                     738 |                        469 |                       47 |                                        7% |                                 6,937 |                                  8,112 |
|                  [Arizona](/us-az) |            5,288 |                     5,889 |                     809 |                        601 |                       83 |                                       11% |                                 5,516 |                                  6,466 |
|                [Louisiana](/us-la) |            5,202 |                     5,846 |                   1,257 |                        644 |                      138 |                                       12% |                                 5,458 |                                  6,485 |
|                     [Ohio](/us-oh) |            4,403 |                     5,089 |                     435 |                        686 |                       59 |                                       16% |                                 4,558 |                                  5,931 |
|              [Connecticut](/us-ct) |            4,480 |                     4,551 |                   1,276 |                         71 |                       20 |                                        2% |                                 4,489 |                                  4,767 |
|                 [Maryland](/us-md) |            3,828 |                     4,136 |                     684 |                        308 |                       51 |                                        8% |                                 3,854 |                                  4,728 |
|           [North Carolina](/us-nc) |            3,023 |                     4,064 |                     387 |                      1,041 |                       99 |                                       34% |                                 3,512 |                                  4,965 |
|                  [Indiana](/us-in) |            3,420 |                     3,816 |                     567 |                        396 |                       59 |                                       12% |                                 3,443 |                                  4,628 |
|           [South Carolina](/us-sc) |            3,028 |                     3,809 |                     740 |                        781 |                      152 |                                       26% |                                 3,420 |                                  4,379 |
|                 [Virginia](/us-va) |            2,711 |                     3,263 |                     382 |                        552 |                       65 |                                       20% |                                 2,769 |                                  4,064 |
|              [Mississippi](/us-ms) |            2,670 |                     3,206 |                   1,077 |                        536 |                      180 |                                       20% |                                 2,898 |                                  3,652 |
|                [Tennessee](/us-tn) |            2,025 |                     2,900 |                     424 |                        875 |                      128 |                                       43% |                                 2,474 |                                  3,576 |
|                  [Alabama](/us-al) |            2,333 |                     2,843 |                     580 |                        510 |                      104 |                                       22% |                                 2,554 |                                  3,290 |
|               [Washington](/us-wa) |            1,991 |                     2,312 |                     304 |                        321 |                       42 |                                       16% |                                 2,063 |                                  2,739 |
|                 [Missouri](/us-mo) |            1,720 |                     2,305 |                     376 |                        585 |                       95 |                                       34% |                                 1,974 |                                  2,838 |
|                [Minnesota](/us-mn) |            1,949 |                     2,290 |                     406 |                        341 |                       60 |                                       18% |                                 2,003 |                                  2,766 |
|                 [Colorado](/us-co) |            1,985 |                     2,135 |                     371 |                        150 |                       26 |                                        8% |                                 1,995 |                                  2,559 |
|                   [Nevada](/us-nv) |            1,439 |                     1,839 |                     597 |                        400 |                      130 |                                       28% |                                 1,645 |                                  2,118 |
|                     [Iowa](/us-ia) |            1,216 |                     1,692 |                     536 |                        476 |                      151 |                                       39% |                                 1,385 |                                  2,255 |
|                [Wisconsin](/us-wi) |            1,197 |                     1,542 |                     265 |                        345 |                       59 |                                       29% |                                 1,334 |                                  1,889 |
|                 [Kentucky](/us-ky) |            1,044 |                     1,433 |                     321 |                        389 |                       87 |                                       37% |                                 1,204 |                                  1,779 |
|                 [Arkansas](/us-ar) |              953 |                     1,398 |                     463 |                        445 |                      147 |                                       47% |                                 1,186 |                                  1,706 |
|                 [Oklahoma](/us-ok) |              888 |                     1,245 |                     315 |                        357 |                       90 |                                       40% |                                 1,052 |                                  1,569 |
|             [Rhode Island](/us-ri) |            1,071 |                     1,136 |                   1,072 |                         65 |                       61 |                                        6% |                                 1,078 |                                  1,276 |
|               [New Mexico](/us-nm) |              818 |                       951 |                     454 |                        133 |                       64 |                                       16% |                                   864 |                                  1,090 |
|              [Puerto Rico](/us-pr) |              523 |                       881 |                     276 |                        358 |                      112 |                                       69% |                                   698 |                                  1,165 |
|                   [Kansas](/us-ks) |              516 |                       718 |                     247 |                        202 |                       69 |                                       39% |                                   597 |                                    917 |
|                   [Oregon](/us-or) |              499 |                       652 |                     155 |                        153 |                       36 |                                       31% |                                   563 |                                    795 |
|                 [Delaware](/us-de) |              613 |                       651 |                     669 |                         38 |                       39 |                                        6% |                                   617 |                                    727 |
|     [District of Columbia](/us-dc) |              616 |                       641 |                     908 |                         25 |                       35 |                                        4% |                                   620 |                                    689 |
|                    [Idaho](/us-id) |              412 |                       596 |                     334 |                        184 |                      103 |                                       45% |                                   506 |                                    732 |
|                 [Nebraska](/us-ne) |              437 |                       572 |                     295 |                        135 |                       70 |                                       31% |                                   480 |                                    717 |
|                     [Utah](/us-ut) |              431 |                       561 |                     175 |                        130 |                       41 |                                       30% |                                   487 |                                    674 |
|            [New Hampshire](/us-nh) |              434 |                       456 |                     335 |                         22 |                       16 |                                        5% |                                   436 |                                    512 |
|            [West Virginia](/us-wv) |              264 |                       451 |                     252 |                        187 |                      104 |                                       71% |                                   352 |                                    621 |
|             [North Dakota](/us-nd) |              164 |                       252 |                     331 |                         88 |                      116 |                                       54% |                                   203 |                                    330 |
|             [South Dakota](/us-sd) |              177 |                       246 |                     278 |                         69 |                       78 |                                       39% |                                   185 |                                    376 |
|                  [Montana](/us-mt) |              131 |                       237 |                     222 |                        106 |                       99 |                                       81% |                                   184 |                                    325 |
|                   [Hawaii](/us-hi) |               96 |                       206 |                     145 |                        110 |                       78 |                                      114% |                                   150 |                                    294 |
|                    [Maine](/us-me) |              134 |                       148 |                     110 |                         14 |                       10 |                                       10% |                                   137 |                                    168 |
|                   [Alaska](/us-ak) |               43 |                        70 |                      96 |                         27 |                       37 |                                       64% |                                    56 |                                     96 |
|                     [Guam](/us-gu) |               23 |                        69 |                     415 |                         46 |                      276 |                                      199% |                                    49 |                                    106 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     77 |
|                  [Wyoming](/us-wy) |               42 |                        60 |                     104 |                         18 |                       31 |                                       43% |                                    50 |                                     79 |
|           [Virgin Islands](/us-vi) |               18 |                        34 |                     329 |                         16 |                      157 |                                       92% |                                    26 |                                     47 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      49 |                          1 |                       13 |                                       36% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          191,804 |                   204,289 |                     344 |                     12,485 |                       21 |                                        7% |                               194,790 |                                234,136 |
| [United Kingdom](/united-kingdom) |           41,703 |                    42,216 |                     625 |                        513 |                        8 |                                        1% |                                41,714 |                                 45,065 |
|                   [Italy](/italy) |           35,597 |                    36,139 |                     599 |                        542 |                        9 |                                        2% |                                35,610 |                                 38,617 |
|                 [France](/france) |           30,901 |                    32,164 |                     480 |                      1,263 |                       19 |                                        4% |                                30,928 |                                 38,745 |
|                   [Spain](/spain) |           29,747 |                    31,800 |                     678 |                      2,053 |                       44 |                                        7% |                                29,773 |                                 39,231 |
|               [Belgium](/belgium) |            9,919 |                    10,063 |                     878 |                        144 |                       13 |                                        1% |                                 9,934 |                                 10,575 |
|               [Germany](/germany) |            9,348 |                     9,654 |                     116 |                        306 |                        4 |                                        3% |                                 9,362 |                                 10,780 |
|       [Netherlands](/netherlands) |            6,290 |                     6,447 |                     373 |                        157 |                        9 |                                        2% |                                 6,302 |                                  7,014 |
|               [Romania](/romania) |            4,100 |                     6,034 |                     311 |                      1,934 |                      100 |                                       47% |                                 4,949 |                                  7,800 |
|                 [Sweden](/sweden) |            5,846 |                     5,883 |                     575 |                         37 |                        4 |                                        1% |                                 5,850 |                                  6,013 |
|               [Ukraine](/ukraine) |            3,132 |                     5,874 |                     134 |                      2,742 |                       62 |                                       88% |                                 4,237 |                                  8,472 |
|                 [Poland](/poland) |            2,169 |                     2,767 |                      73 |                        598 |                       16 |                                       28% |                                 2,352 |                                  3,514 |
|       [Switzerland](/switzerland) |            2,020 |                     2,090 |                     243 |                         70 |                        8 |                                        3% |                                 2,031 |                                  2,256 |
|             [Portugal](/portugal) |            1,855 |                     1,993 |                     194 |                        138 |                       13 |                                        7% |                                 1,860 |                                  2,339 |
|               [Ireland](/ireland) |            1,781 |                     1,817 |                     371 |                         36 |                        7 |                                        2% |                                 1,787 |                                  1,930 |
|               [Moldova](/moldova) |            1,114 |                     1,537 |                     380 |                        423 |                      105 |                                       38% |                                 1,288 |                                  1,958 |
|             [Bulgaria](/bulgaria) |              713 |                     1,102 |                     157 |                        389 |                       56 |                                       55% |                                   879 |                                  1,470 |
|               [Belarus](/belarus) |              738 |                     1,010 |                     107 |                        272 |                       29 |                                       37% |                                   830 |                                  1,363 |
|                 [Serbia](/serbia) |              730 |                       863 |                     124 |                        133 |                       19 |                                       18% |                                   779 |                                  1,009 |
|               [Austria](/austria) |              750 |                       806 |                      91 |                         56 |                        6 |                                        7% |                                   758 |                                    951 |
|               [Hungary](/hungary) |              631 |                       699 |                      72 |                         68 |                        7 |                                       11% |                                   639 |                                    848 |
|               [Denmark](/denmark) |              629 |                       662 |                     114 |                         33 |                        6 |                                        5% |                                   636 |                                    753 |
|               [Czechia](/czechia) |              450 |                       580 |                      54 |                        130 |                       12 |                                       29% |                                   486 |                                    757 |
|                 [Greece](/greece) |              300 |                       483 |                      45 |                        183 |                       17 |                                       61% |                                   376 |                                    688 |
|               [Finland](/finland) |              337 |                       353 |                      64 |                         16 |                        3 |                                        5% |                                   340 |                                    403 |
|               [Croatia](/croatia) |              211 |                       349 |                      86 |                        138 |                       34 |                                       65% |                                   267 |                                    501 |
|                 [Norway](/norway) |              265 |                       284 |                      53 |                         19 |                        3 |                                        7% |                                   269 |                                    327 |
|             [Slovenia](/slovenia) |              135 |                       152 |                      73 |                         17 |                        8 |                                       12% |                                   138 |                                    186 |
|         [Luxembourg](/luxembourg) |              124 |                       140 |                     229 |                         16 |                       27 |                                       13% |                                   129 |                                    165 |
|           [Lithuania](/lithuania) |               86 |                        95 |                      34 |                          9 |                        3 |                                       10% |                                    88 |                                    108 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        8% |                                    66 |                                     74 |
|             [Slovakia](/slovakia) |               37 |                        49 |                       9 |                         12 |                        2 |                                       34% |                                    40 |                                     69 |
|                 [Latvia](/latvia) |               35 |                        41 |                      21 |                          6 |                        3 |                                       17% |                                    36 |                                     49 |
|                   [Malta](/malta) |               15 |                        33 |                      67 |                         18 |                       37 |                                      121% |                                    22 |                                     54 |
|                 [Cyprus](/cyprus) |               22 |                        30 |                      34 |                          8 |                        9 |                                       34% |                                    25 |                                     38 |
|               [Iceland](/iceland) |               10 |                        12 |                      34 |                          2 |                        5 |                                       16% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          498,211 |                   667,256 |                     129 |                    169,045 |                       33 |                                       34% |                               566,176 |                                820,851 |
|                             [Brazil](/brazil) |          130,396 |                   162,991 |                     772 |                     32,595 |                      154 |                                       25% |                               145,933 |                                191,494 |
|                               [India](/india) |           77,472 |                   134,805 |                      99 |                     57,333 |                       42 |                                       74% |                                98,742 |                                179,897 |
|                             [Mexico](/mexico) |           70,183 |                    90,402 |                     709 |                     20,219 |                      158 |                                       29% |                                82,228 |                                102,456 |
|                                 [Peru](/peru) |           30,344 |                    34,309 |                   1,055 |                      3,965 |                      122 |                                       13% |                                31,326 |                                 39,269 |
|                         [Colombia](/colombia) |           22,518 |                    30,798 |                     612 |                      8,280 |                      164 |                                       37% |                                26,390 |                                 37,319 |
|                                 [Iran](/iran) |           22,913 |                    27,293 |                     329 |                      4,380 |                       53 |                                       19% |                                24,114 |                                 32,543 |
|                             [Russia](/russia) |           18,309 |                    22,677 |                     155 |                      4,368 |                       30 |                                       24% |                                19,275 |                                 28,617 |
|                       [Argentina](/argentina) |           11,148 |                    20,311 |                     454 |                      9,163 |                      205 |                                       82% |                                15,314 |                                 26,688 |
|                 [South Africa](/south-africa) |           15,378 |                    18,916 |                     323 |                      3,538 |                       60 |                                       23% |                                15,895 |                                 21,222 |
|                               [Chile](/chile) |           11,850 |                    14,603 |                     770 |                      2,753 |                      145 |                                       23% |                                12,220 |                                 20,887 |
|                       [Indonesia](/indonesia) |            8,544 |                    13,012 |                      48 |                      4,468 |                       17 |                                       52% |                                10,352 |                                 18,687 |
|                           [Ecuador](/ecuador) |           10,836 |                    11,809 |                     680 |                        973 |                       56 |                                        9% |                                10,918 |                                 13,908 |
|                             [Canada](/canada) |            9,214 |                     9,509 |                     254 |                        295 |                        8 |                                        3% |                                 9,237 |                                 10,392 |
|                           [Bolivia](/bolivia) |            7,250 |                     9,407 |                     817 |                      2,157 |                      187 |                                       30% |                                 8,155 |                                 11,368 |
|                             [Turkey](/turkey) |            6,951 |                     8,636 |                     104 |                      1,685 |                       20 |                                       24% |                                 7,115 |                                 11,617 |
|                   [Philippines](/philippines) |            4,108 |                     6,832 |                      63 |                      2,724 |                       25 |                                       66% |                                 5,158 |                                  9,371 |
|                         [Pakistan](/pakistan) |            6,373 |                     6,661 |                      31 |                        288 |                        1 |                                        5% |                                 6,388 |                                  7,387 |
|                     [Bangladesh](/bangladesh) |            4,668 |                     6,317 |                      39 |                      1,649 |                       10 |                                       35% |                                 5,186 |                                  8,255 |
|                               [Egypt](/egypt) |            5,607 |                     6,139 |                      61 |                        532 |                        5 |                                        9% |                                 5,634 |                                  8,068 |
|                 [Saudi Arabia](/saudi-arabia) |            4,213 |                     5,331 |                     156 |                      1,118 |                       33 |                                       27% |                                 4,564 |                                  6,578 |
|                               [China](/china) |            4,733 |                     4,798 |                       3 |                         65 |                        0 |                                        1% |                                 4,733 |                                  5,312 |
|                           [Morocco](/morocco) |            1,524 |                     3,395 |                      93 |                      1,871 |                       51 |                                      123% |                                 2,180 |                                  5,152 |
|     [Dominican Republic](/dominican-republic) |            1,941 |                     2,787 |                     260 |                        846 |                       79 |                                       44% |                                 2,256 |                                  3,682 |
|                         [Honduras](/honduras) |            2,058 |                     2,755 |                     283 |                        697 |                       72 |                                       34% |                                 2,295 |                                  3,555 |
|                             [Panama](/panama) |            2,140 |                     2,516 |                     592 |                        376 |                       88 |                                       18% |                                 2,292 |                                  2,979 |
|                           [Algeria](/algeria) |            1,599 |                     2,105 |                      49 |                        506 |                       12 |                                       32% |                                 1,684 |                                  2,952 |
|                               [Japan](/japan) |            1,428 |                     2,050 |                      16 |                        622 |                        5 |                                       44% |                                 1,591 |                                  2,996 |
|                             [Israel](/israel) |            1,090 |                     1,806 |                     212 |                        716 |                       84 |                                       66% |                                 1,351 |                                  2,638 |
|                           [Nigeria](/nigeria) |            1,076 |                     1,254 |                       6 |                        178 |                        1 |                                       17% |                                 1,123 |                                  1,506 |
|                       [Australia](/australia) |              803 |                     1,141 |                      45 |                        338 |                       13 |                                       42% |                                   941 |                                  1,436 |
|                             [Kuwait](/kuwait) |              557 |                       664 |                     158 |                        107 |                       26 |                                       19% |                                   573 |                                    876 |
| [United Arab Emirates](/united-arab-emirates) |              398 |                       471 |                      48 |                         73 |                        7 |                                       18% |                                   403 |                                    652 |
|                   [South Korea](/south-korea) |              355 |                       469 |                       9 |                        114 |                        2 |                                       32% |                                   363 |                                    722 |
|                                 [Cuba](/cuba) |              106 |                       149 |                      13 |                         43 |                        4 |                                       40% |                                   117 |                                    221 |
|                         [Malaysia](/malaysia) |              128 |                       138 |                       4 |                         10 |                        0 |                                        8% |                                   130 |                                    149 |
