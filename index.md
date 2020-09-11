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
### Updated Daily - Last Updated: September 10 (8pm ET):
<p align="center">
  Current Total: <b>190,856</b> deaths | Projected Total: <b>219,000 deaths by Nov 1, 2020</b> (Range: 208-236k)<br>
  Currently Infected: <b>1.0%</b> (1 in 100) | Total Infected: <b>15.2%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 10, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        98% |         99% |        99% |
|              225,000 |         <1% |        <1% |          1% |        15% |
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
|             *[United States](/us)* |          190,856 |                   219,011 |                     660 |                     28,155 |                       85 |                                       15% |                               208,131 |                                235,270 |
|                 [New York](/us-ny) |           33,019 |                    33,365 |                   1,715 |                        346 |                       18 |                                        1% |                                33,031 |                                 35,358 |
|               [California](/us-ca) |           13,983 |                    17,988 |                     455 |                      4,005 |                      101 |                                       29% |                                15,770 |                                 21,685 |
|                    [Texas](/us-tx) |           13,923 |                    17,797 |                     614 |                      3,874 |                      134 |                                       28% |                                16,047 |                                 20,238 |
|               [New Jersey](/us-nj) |           16,008 |                    16,170 |                   1,820 |                        162 |                       18 |                                        1% |                                16,020 |                                 16,728 |
|                  [Florida](/us-fl) |           12,110 |                    14,501 |                     675 |                      2,391 |                      111 |                                       20% |                                13,196 |                                 16,202 |
|            [Massachusetts](/us-ma) |            9,146 |                     9,510 |                   1,368 |                        364 |                       52 |                                        4% |                                 9,170 |                                 10,388 |
|                 [Illinois](/us-il) |            8,433 |                     9,290 |                     733 |                        857 |                       68 |                                       10% |                                 8,526 |                                 10,478 |
|             [Pennsylvania](/us-pa) |            7,794 |                     8,374 |                     654 |                        580 |                       45 |                                        7% |                                 7,820 |                                  9,564 |
|                  [Georgia](/us-ga) |            6,128 |                     7,984 |                     752 |                      1,856 |                      175 |                                       30% |                                 7,042 |                                  9,509 |
|                 [Michigan](/us-mi) |            6,886 |                     7,375 |                     738 |                        489 |                       49 |                                        7% |                                 6,923 |                                  8,212 |
|                  [Arizona](/us-az) |            5,251 |                     5,903 |                     811 |                        652 |                       90 |                                       12% |                                 5,496 |                                  6,513 |
|                [Louisiana](/us-la) |            5,140 |                     5,807 |                   1,249 |                        667 |                      143 |                                       13% |                                 5,404 |                                  6,468 |
|                     [Ohio](/us-oh) |            4,324 |                     5,021 |                     430 |                        697 |                       60 |                                       16% |                                 4,488 |                                  5,868 |
|              [Connecticut](/us-ct) |            4,474 |                     4,544 |                   1,275 |                         70 |                       20 |                                        2% |                                 4,483 |                                  4,763 |
|                 [Maryland](/us-md) |            3,816 |                     4,141 |                     685 |                        325 |                       54 |                                        9% |                                 3,844 |                                  4,763 |
|           [North Carolina](/us-nc) |            2,958 |                     4,019 |                     383 |                      1,061 |                      101 |                                       36% |                                 3,458 |                                  4,958 |
|                  [Indiana](/us-in) |            3,397 |                     3,815 |                     567 |                        418 |                       62 |                                       12% |                                 3,421 |                                  4,664 |
|           [South Carolina](/us-sc) |            2,942 |                     3,708 |                     720 |                        766 |                      149 |                                       26% |                                 3,332 |                                  4,276 |
|                 [Virginia](/us-va) |            2,697 |                     3,283 |                     385 |                        586 |                       69 |                                       22% |                                 2,760 |                                  4,135 |
|              [Mississippi](/us-ms) |            2,623 |                     3,179 |                   1,068 |                        556 |                      187 |                                       21% |                                 2,861 |                                  3,643 |
|                  [Alabama](/us-al) |            2,285 |                     2,803 |                     572 |                        518 |                      106 |                                       23% |                                 2,511 |                                  3,262 |
|                [Tennessee](/us-tn) |            1,931 |                     2,736 |                     400 |                        805 |                      118 |                                       42% |                                 2,349 |                                  3,374 |
|                 [Missouri](/us-mo) |            1,702 |                     2,321 |                     378 |                        619 |                      101 |                                       36% |                                 1,968 |                                  2,888 |
|               [Washington](/us-wa) |            1,978 |                     2,313 |                     304 |                        335 |                       44 |                                       17% |                                 2,053 |                                  2,766 |
|                [Minnesota](/us-mn) |            1,921 |                     2,253 |                     400 |                        332 |                       59 |                                       17% |                                 1,974 |                                  2,731 |
|                 [Colorado](/us-co) |            1,977 |                     2,134 |                     370 |                        157 |                       27 |                                        8% |                                 1,987 |                                  2,579 |
|                   [Nevada](/us-nv) |            1,412 |                     1,834 |                     595 |                        422 |                      137 |                                       30% |                                 1,625 |                                  2,134 |
|                     [Iowa](/us-ia) |            1,204 |                     1,725 |                     547 |                        521 |                      165 |                                       43% |                                 1,384 |                                  2,389 |
|                [Wisconsin](/us-wi) |            1,183 |                     1,535 |                     264 |                        352 |                       60 |                                       30% |                                 1,323 |                                  1,893 |
|                 [Arkansas](/us-ar) |              928 |                     1,401 |                     464 |                        473 |                      157 |                                       51% |                                 1,170 |                                  1,732 |
|                 [Kentucky](/us-ky) |            1,013 |                     1,390 |                     311 |                        377 |                       84 |                                       37% |                                 1,163 |                                  1,737 |
|                 [Oklahoma](/us-ok) |              863 |                     1,219 |                     308 |                        356 |                       90 |                                       41% |                                 1,022 |                                  1,550 |
|             [Rhode Island](/us-ri) |            1,062 |                     1,128 |                   1,064 |                         66 |                       62 |                                        6% |                                 1,069 |                                  1,269 |
|               [New Mexico](/us-nm) |              813 |                       956 |                     456 |                        143 |                       68 |                                       18% |                                   863 |                                  1,102 |
|              [Puerto Rico](/us-pr) |              500 |                       843 |                     264 |                        343 |                      107 |                                       69% |                                   659 |                                  1,114 |
|                   [Kansas](/us-ks) |              499 |                       694 |                     238 |                        195 |                       67 |                                       39% |                                   576 |                                    888 |
|                   [Oregon](/us-or) |              494 |                       658 |                     156 |                        164 |                       39 |                                       33% |                                   562 |                                    817 |
|                 [Delaware](/us-de) |              609 |                       647 |                     665 |                         38 |                       39 |                                        6% |                                   613 |                                    723 |
|     [District of Columbia](/us-dc) |              615 |                       641 |                     909 |                         26 |                       37 |                                        4% |                                   619 |                                    693 |
|                    [Idaho](/us-id) |              420 |                       625 |                     350 |                        205 |                      115 |                                       49% |                                   523 |                                    778 |
|                     [Utah](/us-ut) |              427 |                       565 |                     176 |                        138 |                       43 |                                       32% |                                   486 |                                    688 |
|                 [Nebraska](/us-ne) |              421 |                       547 |                     283 |                        126 |                       65 |                                       30% |                                   455 |                                    693 |
|            [New Hampshire](/us-nh) |              433 |                       456 |                     335 |                         23 |                       17 |                                        5% |                                   435 |                                    514 |
|            [West Virginia](/us-wv) |              255 |                       449 |                     251 |                        194 |                      108 |                                       76% |                                   345 |                                    624 |
|             [South Dakota](/us-sd) |              173 |                       244 |                     276 |                         71 |                       80 |                                       41% |                                   182 |                                    388 |
|             [North Dakota](/us-nd) |              157 |                       240 |                     315 |                         83 |                      109 |                                       53% |                                   192 |                                    317 |
|                   [Hawaii](/us-hi) |               91 |                       217 |                     154 |                        126 |                       89 |                                      139% |                                   152 |                                    322 |
|                  [Montana](/us-mt) |              122 |                       211 |                     197 |                         89 |                       83 |                                       73% |                                   161 |                                    289 |
|                    [Maine](/us-me) |              134 |                       149 |                     111 |                         15 |                       11 |                                       11% |                                   137 |                                    170 |
|                   [Alaska](/us-ak) |               42 |                        72 |                      99 |                         30 |                       41 |                                       72% |                                    56 |                                    104 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     105 |                          7 |                       12 |                                       13% |                                    59 |                                     78 |
|                  [Wyoming](/us-wy) |               42 |                        65 |                     112 |                         23 |                       39 |                                       54% |                                    52 |                                     89 |
|                     [Guam](/us-gu) |               20 |                        62 |                     373 |                         42 |                      252 |                                      209% |                                    41 |                                     98 |
|           [Virgin Islands](/us-vi) |               18 |                        38 |                     365 |                         20 |                      193 |                                      113% |                                    28 |                                     54 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      50 |                          1 |                       14 |                                       38% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          191,249 |                   204,178 |                     344 |                     12,929 |                       22 |                                        7% |                               194,304 |                                235,008 |
| [United Kingdom](/united-kingdom) |           41,683 |                    42,227 |                     625 |                        544 |                        8 |                                        1% |                                41,695 |                                 45,229 |
|                   [Italy](/italy) |           35,577 |                    36,147 |                     599 |                        570 |                        9 |                                        2% |                                35,591 |                                 38,722 |
|                 [France](/france) |           30,805 |                    32,051 |                     478 |                      1,246 |                       19 |                                        4% |                                30,833 |                                 38,575 |
|                   [Spain](/spain) |           29,628 |                    31,771 |                     677 |                      2,143 |                       46 |                                        7% |                                29,656 |                                 39,500 |
|               [Belgium](/belgium) |            9,917 |                    10,069 |                     879 |                        152 |                       13 |                                        2% |                                 9,933 |                                 10,617 |
|               [Germany](/germany) |            9,342 |                     9,668 |                     116 |                        326 |                        4 |                                        3% |                                 9,356 |                                 10,842 |
|       [Netherlands](/netherlands) |            6,281 |                     6,443 |                     373 |                        162 |                        9 |                                        3% |                                 6,293 |                                  7,029 |
|               [Romania](/romania) |            4,018 |                     6,051 |                     312 |                      2,033 |                      105 |                                       51% |                                 4,902 |                                  7,907 |
|                 [Sweden](/sweden) |            5,842 |                     5,882 |                     575 |                         40 |                        4 |                                        1% |                                 5,846 |                                  6,018 |
|               [Ukraine](/ukraine) |            3,034 |                     5,814 |                     132 |                      2,780 |                       63 |                                       92% |                                 4,134 |                                  8,521 |
|                 [Poland](/poland) |            2,147 |                     2,767 |                      73 |                        620 |                       16 |                                       29% |                                 2,329 |                                  3,555 |
|       [Switzerland](/switzerland) |            2,019 |                     2,095 |                     244 |                         76 |                        9 |                                        4% |                                 2,031 |                                  2,270 |
|             [Portugal](/portugal) |            1,849 |                     1,991 |                     194 |                        142 |                       14 |                                        8% |                                 1,855 |                                  2,349 |
|               [Ireland](/ireland) |            1,781 |                     1,819 |                     371 |                         38 |                        8 |                                        2% |                                 1,787 |                                  1,935 |
|               [Moldova](/moldova) |            1,096 |                     1,542 |                     381 |                        446 |                      110 |                                       41% |                                 1,279 |                                  1,976 |
|             [Bulgaria](/bulgaria) |              702 |                     1,161 |                     166 |                        459 |                       66 |                                       65% |                                   893 |                                  1,578 |
|               [Belarus](/belarus) |              726 |                       999 |                     106 |                        273 |                       29 |                                       38% |                                   817 |                                  1,365 |
|                 [Serbia](/serbia) |              728 |                       870 |                     125 |                        142 |                       20 |                                       19% |                                   781 |                                  1,021 |
|               [Austria](/austria) |              747 |                       803 |                      91 |                         56 |                        6 |                                        8% |                                   756 |                                    952 |
|               [Hungary](/hungary) |              628 |                       697 |                      71 |                         69 |                        7 |                                       11% |                                   636 |                                    850 |
|               [Denmark](/denmark) |              628 |                       662 |                     114 |                         34 |                        6 |                                        5% |                                   635 |                                    755 |
|               [Czechia](/czechia) |              444 |                       570 |                      54 |                        126 |                       12 |                                       28% |                                   476 |                                    752 |
|                 [Greece](/greece) |              293 |                       478 |                      45 |                        185 |                       17 |                                       63% |                                   366 |                                    699 |
|               [Finland](/finland) |              337 |                       354 |                      64 |                         17 |                        3 |                                        5% |                                   340 |                                    406 |
|               [Croatia](/croatia) |              206 |                       340 |                      83 |                        134 |                       33 |                                       65% |                                   260 |                                    486 |
|                 [Norway](/norway) |              264 |                       283 |                      53 |                         19 |                        3 |                                        7% |                                   268 |                                    327 |
|             [Slovenia](/slovenia) |              135 |                       153 |                      74 |                         18 |                        9 |                                       14% |                                   138 |                                    189 |
|         [Luxembourg](/luxembourg) |              124 |                       141 |                     230 |                         17 |                       28 |                                       14% |                                   129 |                                    166 |
|           [Lithuania](/lithuania) |               86 |                        96 |                      34 |                         10 |                        3 |                                       11% |                                    88 |                                    112 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        9% |                                    67 |                                     75 |
|             [Slovakia](/slovakia) |               37 |                        54 |                      10 |                         17 |                        3 |                                       45% |                                    42 |                                     78 |
|                 [Latvia](/latvia) |               35 |                        42 |                      22 |                          7 |                        4 |                                       20% |                                    36 |                                     51 |
|                 [Cyprus](/cyprus) |               22 |                        31 |                      36 |                          9 |                       11 |                                       42% |                                    26 |                                     42 |
|                   [Malta](/malta) |               14 |                        28 |                      57 |                         14 |                       29 |                                      102% |                                    20 |                                     45 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        5 |                                       17% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          489,701 |                   661,144 |                     127 |                    171,443 |                       33 |                                       35% |                               557,307 |                                826,455 |
|                             [Brazil](/brazil) |          128,539 |                   161,686 |                     766 |                     33,147 |                      157 |                                       26% |                               141,462 |                                191,786 |
|                               [India](/india) |           75,062 |                   131,273 |                      96 |                     56,211 |                       41 |                                       75% |                                97,705 |                                183,005 |
|                             [Mexico](/mexico) |           69,049 |                    90,081 |                     706 |                     21,032 |                      165 |                                       30% |                                81,667 |                                102,437 |
|                                 [Peru](/peru) |           30,123 |                    34,516 |                   1,062 |                      4,393 |                      135 |                                       15% |                                31,302 |                                 39,958 |
|                         [Colombia](/colombia) |           22,053 |                    30,893 |                     614 |                      8,840 |                      176 |                                       40% |                                25,954 |                                 37,862 |
|                                 [Iran](/iran) |           22,669 |                    27,274 |                     329 |                      4,605 |                       56 |                                       20% |                                23,977 |                                 32,672 |
|                             [Russia](/russia) |           18,080 |                    22,410 |                     154 |                      4,330 |                       30 |                                       24% |                                18,736 |                                 28,452 |
|                       [Argentina](/argentina) |           10,658 |                    19,867 |                     444 |                      9,209 |                      206 |                                       86% |                                14,925 |                                 26,547 |
|                 [South Africa](/south-africa) |           15,168 |                    18,923 |                     323 |                      3,755 |                       64 |                                       25% |                                15,746 |                                 21,343 |
|                               [Chile](/chile) |           11,702 |                    14,450 |                     762 |                      2,748 |                      145 |                                       23% |                                12,076 |                                 20,847 |
|                       [Indonesia](/indonesia) |            8,336 |                    12,913 |                      48 |                      4,577 |                       17 |                                       55% |                                10,219 |                                 18,855 |
|                           [Ecuador](/ecuador) |           10,701 |                    11,675 |                     672 |                        974 |                       56 |                                        9% |                                10,770 |                                 13,827 |
|                             [Canada](/canada) |            9,204 |                     9,516 |                     254 |                        312 |                        8 |                                        3% |                                 9,229 |                                 10,445 |
|                           [Bolivia](/bolivia) |            7,146 |                     9,443 |                     820 |                      2,297 |                      199 |                                       32% |                                 8,105 |                                 11,496 |
|                             [Turkey](/turkey) |            6,837 |                     8,489 |                     102 |                      1,652 |                       20 |                                       24% |                                 6,993 |                                 11,551 |
|                   [Philippines](/philippines) |            3,986 |                     6,770 |                      63 |                      2,784 |                       26 |                                       70% |                                 4,949 |                                  9,414 |
|                         [Pakistan](/pakistan) |            6,365 |                     6,676 |                      31 |                        311 |                        1 |                                        5% |                                 6,382 |                                  7,441 |
|                     [Bangladesh](/bangladesh) |            4,593 |                     6,266 |                      38 |                      1,673 |                       10 |                                       36% |                                 5,124 |                                  8,272 |
|                               [Egypt](/egypt) |            5,577 |                     6,141 |                      61 |                        564 |                        6 |                                       10% |                                 5,608 |                                  8,170 |
|                 [Saudi Arabia](/saudi-arabia) |            4,165 |                     5,326 |                     155 |                      1,161 |                       34 |                                       28% |                                 4,519 |                                  6,652 |
|                               [China](/china) |            4,733 |                     4,801 |                       3 |                         68 |                        0 |                                        1% |                                 4,733 |                                  5,342 |
|                           [Morocco](/morocco) |            1,453 |                     3,365 |                      92 |                      1,912 |                       52 |                                      132% |                                 2,114 |                                  5,224 |
|     [Dominican Republic](/dominican-republic) |            1,914 |                     2,832 |                     264 |                        918 |                       85 |                                       48% |                                 2,254 |                                  3,755 |
|                         [Honduras](/honduras) |            2,044 |                     2,787 |                     286 |                        743 |                       76 |                                       36% |                                 2,299 |                                  3,644 |
|                             [Panama](/panama) |            2,116 |                     2,517 |                     593 |                        401 |                       94 |                                       19% |                                 2,280 |                                  3,005 |
|                           [Algeria](/algeria) |            1,581 |                     2,109 |                      49 |                        528 |                       12 |                                       33% |                                 1,675 |                                  3,008 |
|                               [Japan](/japan) |            1,412 |                     2,092 |                      16 |                        680 |                        5 |                                       48% |                                 1,587 |                                  3,242 |
|                             [Israel](/israel) |            1,054 |                     1,754 |                     206 |                        700 |                       82 |                                       66% |                                 1,287 |                                  2,607 |
|                           [Nigeria](/nigeria) |            1,070 |                     1,263 |                       6 |                        193 |                        1 |                                       18% |                                 1,122 |                                  1,529 |
|                       [Australia](/australia) |              788 |                     1,172 |                      46 |                        384 |                       15 |                                       49% |                                   943 |                                  1,487 |
|                             [Kuwait](/kuwait) |              552 |                       663 |                     158 |                        111 |                       26 |                                       20% |                                   569 |                                    884 |
| [United Arab Emirates](/united-arab-emirates) |              393 |                       464 |                      47 |                         71 |                        7 |                                       18% |                                   398 |                                    642 |
|                   [South Korea](/south-korea) |              346 |                       454 |                       9 |                        108 |                        2 |                                       31% |                                   352 |                                    686 |
|                                 [Cuba](/cuba) |              104 |                       148 |                      13 |                         44 |                        4 |                                       42% |                                   116 |                                    219 |
|                         [Malaysia](/malaysia) |              128 |                       138 |                       4 |                         10 |                        0 |                                        8% |                                   130 |                                    149 |
