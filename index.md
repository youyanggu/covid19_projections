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
### Updated Daily - Last Updated: September 11 (1pm ET):
<p align="center">
  Current Total: <b>191,763</b> deaths | Projected Total: <b>220,100 deaths by Nov 1, 2020</b> (Range: 209-236k)<br>
  Currently Infected: <b>1.0%</b> (1 in 100) | Total Infected: <b>15.4%</b> (1 in 6) {% include iframe.html %}
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
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        99% |         99% |       >99% |
|              225,000 |         <1% |        <1% |          1% |        18% |
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
|             *[United States](/us)* |          191,763 |                   220,117 |                     663 |                     28,354 |                       85 |                                       15% |                               209,629 |                                235,701 |
|                 [New York](/us-ny) |           33,019 |                    33,348 |                   1,714 |                        329 |                       17 |                                        1% |                                33,030 |                                 35,255 |
|               [California](/us-ca) |           14,077 |                    17,967 |                     455 |                      3,890 |                       98 |                                       28% |                                15,813 |                                 21,523 |
|                    [Texas](/us-tx) |           13,930 |                    17,717 |                     611 |                      3,787 |                      131 |                                       27% |                                16,020 |                                 20,083 |
|               [New Jersey](/us-nj) |           16,014 |                    16,172 |                   1,821 |                        158 |                       18 |                                        1% |                                16,025 |                                 16,714 |
|                  [Florida](/us-fl) |           12,326 |                    15,535 |                     723 |                      3,209 |                      149 |                                       26% |                                14,406 |                                 17,131 |
|            [Massachusetts](/us-ma) |            9,166 |                     9,528 |                   1,371 |                        362 |                       52 |                                        4% |                                 9,190 |                                 10,367 |
|                 [Illinois](/us-il) |            8,461 |                     9,306 |                     734 |                        845 |                       67 |                                       10% |                                 8,553 |                                 10,460 |
|             [Pennsylvania](/us-pa) |            7,807 |                     8,364 |                     653 |                        557 |                       44 |                                        7% |                                 7,832 |                                  9,489 |
|                  [Georgia](/us-ga) |            6,204 |                     7,865 |                     741 |                      1,661 |                      156 |                                       27% |                                 7,006 |                                  9,077 |
|                 [Michigan](/us-mi) |            6,894 |                     7,374 |                     738 |                        480 |                       48 |                                        7% |                                 6,931 |                                  8,155 |
|                  [Arizona](/us-az) |            5,273 |                     5,902 |                     811 |                        629 |                       86 |                                       12% |                                 5,509 |                                  6,498 |
|                [Louisiana](/us-la) |            5,161 |                     5,811 |                   1,250 |                        650 |                      140 |                                       13% |                                 5,418 |                                  6,462 |
|                     [Ohio](/us-oh) |            4,354 |                     5,038 |                     431 |                        684 |                       59 |                                       16% |                                 4,513 |                                  5,871 |
|              [Connecticut](/us-ct) |            4,478 |                     4,550 |                   1,276 |                         72 |                       20 |                                        2% |                                 4,487 |                                  4,771 |
|                 [Maryland](/us-md) |            3,824 |                     4,144 |                     685 |                        320 |                       53 |                                        8% |                                 3,851 |                                  4,754 |
|           [North Carolina](/us-nc) |            2,990 |                     4,036 |                     385 |                      1,046 |                      100 |                                       35% |                                 3,479 |                                  4,953 |
|                  [Indiana](/us-in) |            3,410 |                     3,814 |                     567 |                        404 |                       60 |                                       12% |                                 3,433 |                                  4,645 |
|           [South Carolina](/us-sc) |            2,975 |                     3,727 |                     724 |                        752 |                      146 |                                       25% |                                 3,358 |                                  4,278 |
|                 [Virginia](/us-va) |            2,708 |                     3,286 |                     385 |                        578 |                       68 |                                       21% |                                 2,770 |                                  4,120 |
|              [Mississippi](/us-ms) |            2,656 |                     3,214 |                   1,080 |                        558 |                      187 |                                       21% |                                 2,895 |                                  3,675 |
|                [Tennessee](/us-tn) |            1,988 |                     2,849 |                     417 |                        861 |                      126 |                                       43% |                                 2,432 |                                  3,524 |
|                  [Alabama](/us-al) |            2,301 |                     2,810 |                     573 |                        509 |                      104 |                                       22% |                                 2,525 |                                  3,262 |
|                 [Missouri](/us-mo) |            1,713 |                     2,316 |                     377 |                        603 |                       98 |                                       35% |                                 1,974 |                                  2,865 |
|               [Washington](/us-wa) |            1,985 |                     2,314 |                     304 |                        329 |                       43 |                                       17% |                                 2,058 |                                  2,754 |
|                [Minnesota](/us-mn) |            1,936 |                     2,275 |                     403 |                        339 |                       60 |                                       18% |                                 1,991 |                                  2,755 |
|                 [Colorado](/us-co) |            1,979 |                     2,130 |                     370 |                        151 |                       26 |                                        8% |                                 1,989 |                                  2,561 |
|                   [Nevada](/us-nv) |            1,429 |                     1,844 |                     599 |                        415 |                      135 |                                       29% |                                 1,640 |                                  2,133 |
|                     [Iowa](/us-ia) |            1,207 |                     1,697 |                     538 |                        490 |                      155 |                                       41% |                                 1,379 |                                  2,289 |
|                [Wisconsin](/us-wi) |            1,193 |                     1,547 |                     266 |                        354 |                       61 |                                       30% |                                 1,334 |                                  1,911 |
|                 [Kentucky](/us-ky) |            1,035 |                     1,428 |                     320 |                        393 |                       88 |                                       38% |                                 1,194 |                                  1,782 |
|                 [Arkansas](/us-ar) |              940 |                     1,395 |                     462 |                        455 |                      151 |                                       48% |                                 1,176 |                                  1,711 |
|                 [Oklahoma](/us-ok) |              876 |                     1,233 |                     312 |                        357 |                       90 |                                       41% |                                 1,039 |                                  1,561 |
|             [Rhode Island](/us-ri) |            1,067 |                     1,133 |                   1,069 |                         66 |                       62 |                                        6% |                                 1,074 |                                  1,275 |
|               [New Mexico](/us-nm) |              816 |                       954 |                     455 |                        138 |                       66 |                                       17% |                                   864 |                                  1,097 |
|              [Puerto Rico](/us-pr) |              512 |                       862 |                     270 |                        350 |                      110 |                                       68% |                                   680 |                                  1,136 |
|                   [Kansas](/us-ks) |              503 |                       693 |                     238 |                        190 |                       65 |                                       38% |                                   577 |                                    882 |
|                   [Oregon](/us-or) |              497 |                       656 |                     156 |                        159 |                       38 |                                       32% |                                   564 |                                    804 |
|                 [Delaware](/us-de) |              613 |                       653 |                     670 |                         40 |                       41 |                                        6% |                                   617 |                                    731 |
|     [District of Columbia](/us-dc) |              616 |                       642 |                     909 |                         26 |                       36 |                                        4% |                                   620 |                                    691 |
|                    [Idaho](/us-id) |              407 |                       597 |                     334 |                        190 |                      106 |                                       47% |                                   504 |                                    737 |
|                     [Utah](/us-ut) |              430 |                       566 |                     177 |                        136 |                       43 |                                       32% |                                   489 |                                    686 |
|                 [Nebraska](/us-ne) |              430 |                       557 |                     288 |                        127 |                       66 |                                       30% |                                   466 |                                    700 |
|            [New Hampshire](/us-nh) |              434 |                       457 |                     336 |                         23 |                       17 |                                        5% |                                   436 |                                    514 |
|            [West Virginia](/us-wv) |              258 |                       446 |                     249 |                        188 |                      105 |                                       73% |                                   345 |                                    619 |
|             [South Dakota](/us-sd) |              177 |                       256 |                     289 |                         79 |                       89 |                                       45% |                                   186 |                                    417 |
|             [North Dakota](/us-nd) |              160 |                       243 |                     320 |                         83 |                      110 |                                       52% |                                   197 |                                    320 |
|                   [Hawaii](/us-hi) |               94 |                       213 |                     150 |                        119 |                       84 |                                      126% |                                   152 |                                    311 |
|                  [Montana](/us-mt) |              123 |                       208 |                     194 |                         85 |                       79 |                                       69% |                                   161 |                                    281 |
|                    [Maine](/us-me) |              134 |                       148 |                     110 |                         14 |                       11 |                                       11% |                                   137 |                                    169 |
|                   [Alaska](/us-ak) |               42 |                        69 |                      95 |                         27 |                       38 |                                       65% |                                    55 |                                     95 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     105 |                          7 |                       12 |                                       13% |                                    59 |                                     77 |
|                  [Wyoming](/us-wy) |               42 |                        62 |                     108 |                         20 |                       35 |                                       48% |                                    51 |                                     84 |
|                     [Guam](/us-gu) |               21 |                        62 |                     374 |                         41 |                      248 |                                      195% |                                    43 |                                     95 |
|           [Virgin Islands](/us-vi) |               18 |                        36 |                     345 |                         18 |                      173 |                                      101% |                                    27 |                                     50 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      50 |                          1 |                       13 |                                       37% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          191,510 |                   204,216 |                     344 |                     12,706 |                       21 |                                        7% |                               194,520 |                                234,474 |
| [United Kingdom](/united-kingdom) |           41,697 |                    42,231 |                     625 |                        534 |                        8 |                                        1% |                                41,709 |                                 45,183 |
|                   [Italy](/italy) |           35,587 |                    36,143 |                     599 |                        556 |                        9 |                                        2% |                                35,601 |                                 38,674 |
|                 [France](/france) |           30,819 |                    32,031 |                     478 |                      1,212 |                       18 |                                        4% |                                30,846 |                                 38,424 |
|                   [Spain](/spain) |           29,699 |                    31,841 |                     678 |                      2,142 |                       46 |                                        7% |                                29,726 |                                 39,464 |
|               [Belgium](/belgium) |            9,917 |                    10,064 |                     878 |                        147 |                       13 |                                        1% |                                 9,933 |                                 10,589 |
|               [Germany](/germany) |            9,345 |                     9,661 |                     116 |                        316 |                        4 |                                        3% |                                 9,359 |                                 10,815 |
|       [Netherlands](/netherlands) |            6,285 |                     6,444 |                     373 |                        159 |                        9 |                                        3% |                                 6,297 |                                  7,019 |
|               [Romania](/romania) |            4,065 |                     6,112 |                     315 |                      2,047 |                      105 |                                       50% |                                 4,947 |                                  7,927 |
|                 [Sweden](/sweden) |            5,843 |                     5,881 |                     575 |                         38 |                        4 |                                        1% |                                 5,847 |                                  6,014 |
|               [Ukraine](/ukraine) |            3,079 |                     5,781 |                     131 |                      2,702 |                       61 |                                       88% |                                 4,159 |                                  8,451 |
|                 [Poland](/poland) |            2,159 |                     2,776 |                      73 |                        617 |                       16 |                                       29% |                                 2,348 |                                  3,552 |
|       [Switzerland](/switzerland) |            2,020 |                     2,093 |                     244 |                         73 |                        9 |                                        4% |                                 2,032 |                                  2,266 |
|             [Portugal](/portugal) |            1,852 |                     1,992 |                     194 |                        140 |                       14 |                                        8% |                                 1,858 |                                  2,344 |
|               [Ireland](/ireland) |            1,781 |                     1,818 |                     371 |                         37 |                        8 |                                        2% |                                 1,787 |                                  1,932 |
|               [Moldova](/moldova) |            1,106 |                     1,547 |                     383 |                        441 |                      109 |                                       40% |                                 1,286 |                                  1,974 |
|             [Bulgaria](/bulgaria) |              706 |                     1,110 |                     159 |                        404 |                       58 |                                       57% |                                   876 |                                  1,492 |
|               [Belarus](/belarus) |              732 |                     1,003 |                     106 |                        271 |                       29 |                                       37% |                                   822 |                                  1,363 |
|                 [Serbia](/serbia) |              729 |                       866 |                     124 |                        137 |                       20 |                                       19% |                                   780 |                                  1,014 |
|               [Austria](/austria) |              748 |                       803 |                      91 |                         55 |                        6 |                                        7% |                                   756 |                                    947 |
|               [Hungary](/hungary) |              630 |                       699 |                      72 |                         69 |                        7 |                                       11% |                                   638 |                                    850 |
|               [Denmark](/denmark) |              629 |                       663 |                     114 |                         34 |                        6 |                                        5% |                                   636 |                                    757 |
|               [Czechia](/czechia) |              448 |                       580 |                      54 |                        132 |                       12 |                                       29% |                                   484 |                                    761 |
|                 [Greece](/greece) |              297 |                       485 |                      45 |                        188 |                       17 |                                       63% |                                   373 |                                    701 |
|               [Finland](/finland) |              337 |                       354 |                      64 |                         17 |                        3 |                                        5% |                                   340 |                                    404 |
|               [Croatia](/croatia) |              208 |                       338 |                      83 |                        130 |                       32 |                                       63% |                                   260 |                                    478 |
|                 [Norway](/norway) |              265 |                       284 |                      53 |                         19 |                        4 |                                        7% |                                   269 |                                    329 |
|             [Slovenia](/slovenia) |              135 |                       152 |                      73 |                         17 |                        8 |                                       13% |                                   138 |                                    187 |
|         [Luxembourg](/luxembourg) |              124 |                       141 |                     229 |                         17 |                       27 |                                       14% |                                   129 |                                    166 |
|           [Lithuania](/lithuania) |               86 |                        95 |                      34 |                          9 |                        3 |                                       11% |                                    88 |                                    110 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        8% |                                    66 |                                     75 |
|             [Slovakia](/slovakia) |               37 |                        51 |                       9 |                         14 |                        3 |                                       38% |                                    41 |                                     71 |
|                 [Latvia](/latvia) |               35 |                        41 |                      22 |                          6 |                        3 |                                       18% |                                    36 |                                     50 |
|                 [Cyprus](/cyprus) |               22 |                        30 |                      35 |                          8 |                       10 |                                       38% |                                    25 |                                     40 |
|                   [Malta](/malta) |               14 |                        25 |                      52 |                         11 |                       23 |                                       82% |                                    18 |                                     37 |
|               [Iceland](/iceland) |               10 |                        12 |                      34 |                          2 |                        5 |                                       16% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          494,086 |                   664,230 |                     128 |                    170,144 |                       33 |                                       34% |                               562,058 |                                826,210 |
|                             [Brazil](/brazil) |          129,522 |                   162,221 |                     769 |                     32,699 |                      155 |                                       25% |                               142,909 |                                191,476 |
|                               [India](/india) |           76,271 |                   132,751 |                      97 |                     56,480 |                       41 |                                       74% |                                98,935 |                                183,250 |
|                             [Mexico](/mexico) |           69,649 |                    90,312 |                     708 |                     20,663 |                      162 |                                       30% |                                82,014 |                                102,477 |
|                                 [Peru](/peru) |           30,236 |                    34,399 |                   1,058 |                      4,163 |                      128 |                                       14% |                                31,286 |                                 39,632 |
|                         [Colombia](/colombia) |           22,275 |                    30,777 |                     611 |                      8,502 |                      169 |                                       38% |                                25,976 |                                 37,540 |
|                                 [Iran](/iran) |           22,798 |                    27,289 |                     329 |                      4,491 |                       54 |                                       20% |                                24,056 |                                 32,612 |
|                             [Russia](/russia) |           18,207 |                    22,798 |                     156 |                      4,591 |                       31 |                                       25% |                                19,467 |                                 29,136 |
|                       [Argentina](/argentina) |           10,907 |                    20,090 |                     449 |                      9,183 |                      205 |                                       84% |                                15,114 |                                 26,650 |
|                 [South Africa](/south-africa) |           15,265 |                    18,903 |                     323 |                      3,638 |                       62 |                                       24% |                                15,812 |                                 21,273 |
|                               [Chile](/chile) |           11,781 |                    14,538 |                     767 |                      2,757 |                      145 |                                       23% |                                12,159 |                                 20,897 |
|                       [Indonesia](/indonesia) |            8,456 |                    13,033 |                      48 |                      4,577 |                       17 |                                       54% |                                10,314 |                                 18,889 |
|                           [Ecuador](/ecuador) |           10,749 |                    11,708 |                     674 |                        959 |                       55 |                                        9% |                                10,816 |                                 13,836 |
|                             [Canada](/canada) |            9,213 |                     9,522 |                     255 |                        309 |                        8 |                                        3% |                                 9,237 |                                 10,433 |
|                           [Bolivia](/bolivia) |            7,193 |                     9,403 |                     817 |                      2,210 |                      192 |                                       31% |                                 8,124 |                                 11,412 |
|                             [Turkey](/turkey) |            6,895 |                     8,580 |                     103 |                      1,685 |                       20 |                                       24% |                                 7,055 |                                 11,601 |
|                   [Philippines](/philippines) |            4,066 |                     6,892 |                      64 |                      2,826 |                       26 |                                       69% |                                 5,132 |                                  9,538 |
|                         [Pakistan](/pakistan) |            6,370 |                     6,669 |                      31 |                        299 |                        1 |                                        5% |                                 6,386 |                                  7,415 |
|                     [Bangladesh](/bangladesh) |            4,634 |                     6,312 |                      39 |                      1,678 |                       10 |                                       36% |                                 5,166 |                                  8,286 |
|                               [Egypt](/egypt) |            5,590 |                     6,138 |                      61 |                        548 |                        5 |                                       10% |                                 5,619 |                                  8,117 |
|                 [Saudi Arabia](/saudi-arabia) |            4,189 |                     5,332 |                     156 |                      1,143 |                       33 |                                       27% |                                 4,536 |                                  6,604 |
|                               [China](/china) |            4,733 |                     4,799 |                       3 |                         66 |                        0 |                                        1% |                                 4,733 |                                  5,321 |
|                           [Morocco](/morocco) |            1,491 |                     3,404 |                      93 |                      1,913 |                       52 |                                      128% |                                 2,155 |                                  5,233 |
|     [Dominican Republic](/dominican-republic) |            1,926 |                     2,802 |                     261 |                        876 |                       82 |                                       45% |                                 2,241 |                                  3,711 |
|                         [Honduras](/honduras) |            2,049 |                     2,770 |                     284 |                        721 |                       74 |                                       35% |                                 2,293 |                                  3,603 |
|                             [Panama](/panama) |            2,127 |                     2,513 |                     592 |                        386 |                       91 |                                       18% |                                 2,284 |                                  2,986 |
|                           [Algeria](/algeria) |            1,591 |                     2,109 |                      49 |                        518 |                       12 |                                       33% |                                 1,683 |                                  2,965 |
|                               [Japan](/japan) |            1,416 |                     2,047 |                      16 |                        631 |                        5 |                                       45% |                                 1,579 |                                  3,040 |
|                             [Israel](/israel) |            1,077 |                     1,804 |                     212 |                        727 |                       85 |                                       68% |                                 1,324 |                                  2,654 |
|                           [Nigeria](/nigeria) |            1,075 |                     1,263 |                       6 |                        188 |                        1 |                                       17% |                                 1,125 |                                  1,524 |
|                       [Australia](/australia) |              797 |                     1,161 |                      46 |                        364 |                       14 |                                       46% |                                   946 |                                  1,468 |
|                             [Kuwait](/kuwait) |              556 |                       668 |                     159 |                        112 |                       27 |                                       20% |                                   573 |                                    888 |
| [United Arab Emirates](/united-arab-emirates) |              398 |                       474 |                      49 |                         76 |                        8 |                                       19% |                                   403 |                                    660 |
|                   [South Korea](/south-korea) |              350 |                       461 |                       9 |                        111 |                        2 |                                       32% |                                   358 |                                    705 |
|                                 [Cuba](/cuba) |              106 |                       151 |                      13 |                         45 |                        4 |                                       42% |                                   118 |                                    229 |
|                         [Malaysia](/malaysia) |              128 |                       138 |                       4 |                         10 |                        0 |                                        8% |                                   130 |                                    149 |
