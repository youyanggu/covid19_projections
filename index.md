We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 22:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1308498742451015680).
* **September 20:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 25 (4am ET):
<p align="center">
  Current Total: <b>202,795</b> deaths | Projected Total: <b>226,800 deaths by Nov 1, 2020</b> (Range: 217-242k)<br>
  Currently Infected: <b>1.0%</b> (1 in 100) | Total Infected: <b>15.7%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 23, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |          1% |        49% |
|              250,000 |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries).

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
|             *[United States](/us)* |          202,795 |                   226,833 |                     684 |                     24,038 |                       72 |                                       12% |                               217,326 |                                241,325 |
|                 [New York](/us-ny) |           33,095 |                    33,503 |                   1,722 |                        408 |                       21 |                                        1% |                                33,109 |                                 35,390 |
|                    [Texas](/us-tx) |           15,510 |                    18,283 |                     631 |                      2,773 |                       96 |                                       18% |                                16,747 |                                 20,597 |
|               [California](/us-ca) |           15,393 |                    18,037 |                     457 |                      2,644 |                       67 |                                       17% |                                16,270 |                                 20,933 |
|                  [Florida](/us-fl) |           13,795 |                    17,213 |                     801 |                      3,418 |                      159 |                                       25% |                                16,025 |                                 19,595 |
|               [New Jersey](/us-nj) |           16,091 |                    16,303 |                   1,835 |                        212 |                       24 |                                        1% |                                16,099 |                                 16,966 |
|            [Massachusetts](/us-ma) |            9,362 |                     9,690 |                   1,394 |                        328 |                       47 |                                        3% |                                 9,385 |                                 10,305 |
|                 [Illinois](/us-il) |            8,774 |                     9,487 |                     749 |                        713 |                       56 |                                        8% |                                 8,906 |                                 10,504 |
|             [Pennsylvania](/us-pa) |            8,054 |                     8,944 |                     699 |                        890 |                       69 |                                       11% |                                 8,101 |                                 10,225 |
|                  [Georgia](/us-ga) |            6,816 |                     8,194 |                     772 |                      1,378 |                      130 |                                       20% |                                 7,419 |                                  9,419 |
|                 [Michigan](/us-mi) |            7,019 |                     7,370 |                     738 |                        351 |                       35 |                                        5% |                                 7,064 |                                  7,907 |
|                  [Arizona](/us-az) |            5,559 |                     5,994 |                     823 |                        435 |                       60 |                                        8% |                                 5,651 |                                  6,642 |
|                [Louisiana](/us-la) |            5,423 |                     5,928 |                   1,275 |                        505 |                      109 |                                        9% |                                 5,620 |                                  6,458 |
|                     [Ohio](/us-oh) |            4,715 |                     5,520 |                     472 |                        805 |                       69 |                                       17% |                                 4,918 |                                  6,536 |
|              [Connecticut](/us-ct) |            4,499 |                     4,591 |                   1,288 |                         92 |                       26 |                                        2% |                                 4,507 |                                  4,853 |
|           [North Carolina](/us-nc) |            3,356 |                     4,190 |                     399 |                        834 |                       79 |                                       25% |                                 3,731 |                                  4,893 |
|                 [Maryland](/us-md) |            3,909 |                     4,121 |                     682 |                        212 |                       35 |                                        5% |                                 3,925 |                                  4,510 |
|           [South Carolina](/us-sc) |            3,279 |                     3,916 |                     761 |                        637 |                      124 |                                       19% |                                 3,567 |                                  4,464 |
|                  [Indiana](/us-in) |            3,548 |                     3,902 |                     580 |                        354 |                       53 |                                       10% |                                 3,575 |                                  4,522 |
|                 [Virginia](/us-va) |            3,111 |                     3,802 |                     445 |                        691 |                       81 |                                       22% |                                 3,314 |                                  4,560 |
|              [Mississippi](/us-ms) |            2,874 |                     3,298 |                   1,108 |                        424 |                      142 |                                       15% |                                 3,048 |                                  3,699 |
|                [Tennessee](/us-tn) |            2,312 |                     2,960 |                     433 |                        648 |                       95 |                                       28% |                                 2,627 |                                  3,460 |
|                  [Alabama](/us-al) |            2,506 |                     2,888 |                     589 |                        382 |                       78 |                                       15% |                                 2,651 |                                  3,258 |
|                 [Missouri](/us-mo) |            1,951 |                     2,515 |                     410 |                        564 |                       92 |                                       29% |                                 2,188 |                                  2,994 |
|               [Washington](/us-wa) |            2,080 |                     2,365 |                     311 |                        285 |                       37 |                                       14% |                                 2,126 |                                  2,814 |
|                [Minnesota](/us-mn) |            2,040 |                     2,302 |                     408 |                        262 |                       46 |                                       13% |                                 2,085 |                                  2,657 |
|                 [Colorado](/us-co) |            2,033 |                     2,202 |                     382 |                        169 |                       29 |                                        8% |                                 2,044 |                                  2,524 |
|                   [Nevada](/us-nv) |            1,564 |                     1,814 |                     589 |                        250 |                       81 |                                       16% |                                 1,648 |                                  2,103 |
|                [Wisconsin](/us-wi) |            1,265 |                     1,598 |                     275 |                        333 |                       57 |                                       26% |                                 1,390 |                                  1,941 |
|                 [Arkansas](/us-ar) |            1,246 |                     1,581 |                     524 |                        335 |                      111 |                                       27% |                                 1,414 |                                  1,822 |
|                     [Iowa](/us-ia) |            1,303 |                     1,579 |                     501 |                        276 |                       88 |                                       21% |                                 1,406 |                                  1,852 |
|                 [Kentucky](/us-ky) |            1,137 |                     1,433 |                     321 |                        296 |                       66 |                                       26% |                                 1,250 |                                  1,701 |
|                 [Oklahoma](/us-ok) |              981 |                     1,237 |                     313 |                        256 |                       65 |                                       26% |                                 1,103 |                                  1,455 |
|             [Rhode Island](/us-ri) |            1,106 |                     1,177 |                   1,111 |                         71 |                       67 |                                        6% |                                 1,113 |                                  1,325 |
|               [New Mexico](/us-nm) |              859 |                     1,002 |                     478 |                        143 |                       68 |                                       17% |                                   906 |                                  1,169 |
|              [Puerto Rico](/us-pr) |              627 |                       897 |                     281 |                        270 |                       85 |                                       43% |                                   765 |                                  1,114 |
|                   [Kansas](/us-ks) |              621 |                       826 |                     283 |                        205 |                       70 |                                       33% |                                   706 |                                  1,007 |
|                   [Oregon](/us-or) |              539 |                       683 |                     162 |                        144 |                       34 |                                       27% |                                   596 |                                    827 |
|                 [Delaware](/us-de) |              630 |                       663 |                     681 |                         33 |                       34 |                                        5% |                                   634 |                                    722 |
|     [District of Columbia](/us-dc) |              621 |                       638 |                     904 |                         17 |                       24 |                                        3% |                                   624 |                                    669 |
|                    [Idaho](/us-id) |              457 |                       574 |                     321 |                        117 |                       66 |                                       26% |                                   516 |                                    653 |
|                 [Nebraska](/us-ne) |              462 |                       560 |                     289 |                         98 |                       51 |                                       21% |                                   487 |                                    673 |
|                     [Utah](/us-ut) |              444 |                       548 |                     171 |                        104 |                       32 |                                       23% |                                   482 |                                    640 |
|            [West Virginia](/us-wv) |              328 |                       503 |                     281 |                        175 |                       98 |                                       53% |                                   415 |                                    642 |
|            [New Hampshire](/us-nh) |              438 |                       459 |                     337 |                         21 |                       15 |                                        5% |                                   439 |                                    518 |
|             [North Dakota](/us-nd) |              211 |                       339 |                     445 |                        128 |                      168 |                                       61% |                                   278 |                                    437 |
|             [South Dakota](/us-sd) |              210 |                       297 |                     336 |                         87 |                       99 |                                       42% |                                   230 |                                    417 |
|                  [Montana](/us-mt) |              165 |                       262 |                     245 |                         97 |                       91 |                                       59% |                                   218 |                                    336 |
|                   [Hawaii](/us-hi) |              124 |                       203 |                     143 |                         79 |                       55 |                                       63% |                                   159 |                                    287 |
|                    [Maine](/us-me) |              140 |                       155 |                     116 |                         15 |                       12 |                                       11% |                                   143 |                                    180 |
|                     [Guam](/us-gu) |               38 |                        74 |                     447 |                         36 |                      217 |                                       95% |                                    55 |                                    105 |
|                  [Wyoming](/us-wy) |               50 |                        64 |                     111 |                         14 |                       25 |                                       29% |                                    56 |                                     77 |
|                   [Alaska](/us-ak) |               46 |                        62 |                      84 |                         16 |                       22 |                                       34% |                                    54 |                                     74 |
|                  [Vermont](/us-vt) |               58 |                        61 |                      98 |                          3 |                        5 |                                        6% |                                    58 |                                     69 |
|           [Virgin Islands](/us-vi) |               19 |                        25 |                     237 |                          6 |                       56 |                                       31% |                                    21 |                                     30 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      46 |                          1 |                       10 |                                       27% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          196,727 |                   218,243 |                     368 |                     21,516 |                       36 |                                       11% |                               201,179 |                                268,268 |
| [United Kingdom](/united-kingdom) |           41,991 |                    43,882 |                     650 |                      1,891 |                       28 |                                        5% |                                42,032 |                                 50,789 |
|                   [Spain](/spain) |           31,118 |                    37,710 |                     803 |                      6,592 |                      140 |                                       21% |                                32,379 |                                 51,394 |
|                   [Italy](/italy) |           35,781 |                    36,795 |                     610 |                      1,014 |                       17 |                                        3% |                                35,797 |                                 40,584 |
|                 [France](/france) |           31,524 |                    34,912 |                     521 |                      3,388 |                       51 |                                       11% |                                31,581 |                                 49,803 |
|               [Belgium](/belgium) |            9,965 |                    10,238 |                     894 |                        273 |                       24 |                                        3% |                                 9,995 |                                 11,032 |
|               [Germany](/germany) |            9,436 |                     9,735 |                     117 |                        299 |                        4 |                                        3% |                                 9,448 |                                 10,873 |
|       [Netherlands](/netherlands) |            6,361 |                     6,682 |                     387 |                        321 |                       19 |                                        5% |                                 6,373 |                                  7,503 |
|               [Ukraine](/ukraine) |            3,838 |                     6,242 |                     142 |                      2,404 |                       55 |                                       63% |                                 4,908 |                                  8,053 |
|               [Romania](/romania) |            4,591 |                     6,043 |                     311 |                      1,452 |                       75 |                                       32% |                                 5,258 |                                  7,290 |
|                 [Sweden](/sweden) |            5,878 |                     5,965 |                     583 |                         87 |                        9 |                                        1% |                                 5,884 |                                  6,207 |
|                 [Poland](/poland) |            2,369 |                     3,139 |                      83 |                        770 |                       20 |                                       33% |                                 2,591 |                                  4,155 |
|       [Switzerland](/switzerland) |            2,061 |                     2,225 |                     259 |                        164 |                       19 |                                        8% |                                 2,096 |                                  2,514 |
|             [Portugal](/portugal) |            1,931 |                     2,198 |                     214 |                        267 |                       26 |                                       14% |                                 1,952 |                                  2,648 |
|               [Ireland](/ireland) |            1,797 |                     1,860 |                     379 |                         63 |                       13 |                                        3% |                                 1,801 |                                  2,045 |
|               [Moldova](/moldova) |            1,252 |                     1,650 |                     408 |                        398 |                       98 |                                       32% |                                 1,407 |                                  2,005 |
|               [Czechia](/czechia) |              567 |                     1,125 |                     106 |                        558 |                       52 |                                       98% |                                   852 |                                  1,534 |
|               [Hungary](/hungary) |              709 |                     1,028 |                     105 |                        319 |                       33 |                                       45% |                                   853 |                                  1,313 |
|               [Belarus](/belarus) |              802 |                     1,016 |                     107 |                        214 |                       23 |                                       27% |                                   871 |                                  1,302 |
|             [Bulgaria](/bulgaria) |              785 |                     1,004 |                     143 |                        219 |                       31 |                                       28% |                                   889 |                                  1,191 |
|               [Austria](/austria) |              783 |                       933 |                     105 |                        150 |                       17 |                                       19% |                                   800 |                                  1,174 |
|                 [Serbia](/serbia) |              745 |                       803 |                     115 |                         58 |                        8 |                                        8% |                                   759 |                                    892 |
|               [Denmark](/denmark) |              645 |                       715 |                     123 |                         70 |                       12 |                                       11% |                                   653 |                                    855 |
|                 [Greece](/greece) |              366 |                       657 |                      61 |                        291 |                       27 |                                       80% |                                   492 |                                    984 |
|               [Finland](/finland) |              343 |                       360 |                      65 |                         17 |                        3 |                                        5% |                                   345 |                                    417 |
|               [Croatia](/croatia) |              261 |                       359 |                      88 |                         98 |                       24 |                                       38% |                                   295 |                                    510 |
|                 [Norway](/norway) |              270 |                       288 |                      54 |                         18 |                        3 |                                        7% |                                   273 |                                    328 |
|             [Slovenia](/slovenia) |              145 |                       171 |                      82 |                         26 |                       13 |                                       18% |                                   150 |                                    228 |
|         [Luxembourg](/luxembourg) |              124 |                       136 |                     222 |                         12 |                       20 |                                       10% |                                   128 |                                    155 |
|           [Lithuania](/lithuania) |               89 |                       100 |                      36 |                         11 |                        4 |                                       13% |                                    91 |                                    121 |
|               [Estonia](/estonia) |               64 |                        68 |                      51 |                          4 |                        3 |                                        6% |                                    66 |                                     74 |
|                   [Malta](/malta) |               27 |                        67 |                     136 |                         40 |                       81 |                                      149% |                                    45 |                                    120 |
|             [Slovakia](/slovakia) |               41 |                        56 |                      10 |                         15 |                        3 |                                       37% |                                    45 |                                     84 |
|                 [Latvia](/latvia) |               36 |                        41 |                      21 |                          5 |                        2 |                                       13% |                                    37 |                                     48 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      29 |                          3 |                        4 |                                       16% |                                    23 |                                     30 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        3 |                                       11% |                                    10 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          546,207 |                   686,741 |                     132 |                    140,534 |                       27 |                                       26% |                               616,371 |                                799,260 |
|                             [Brazil](/brazil) |          139,808 |                   168,500 |                     798 |                     28,692 |                      136 |                                       21% |                               159,953 |                                187,533 |
|                               [India](/india) |           91,149 |                   134,853 |                      99 |                     43,704 |                       32 |                                       48% |                               109,472 |                                159,409 |
|                             [Mexico](/mexico) |           75,439 |                    89,155 |                     699 |                     13,716 |                      108 |                                       18% |                                84,178 |                                 97,182 |
|                                 [Peru](/peru) |           31,870 |                    35,606 |                   1,095 |                      3,736 |                      115 |                                       12% |                                33,868 |                                 38,993 |
|                                 [Iran](/iran) |           25,015 |                    30,698 |                     370 |                      5,683 |                       69 |                                       23% |                                27,568 |                                 35,212 |
|                         [Colombia](/colombia) |           24,746 |                    29,343 |                     583 |                      4,597 |                       91 |                                       19% |                                27,206 |                                 33,478 |
|                       [Argentina](/argentina) |           14,766 |                    25,616 |                     572 |                     10,850 |                      242 |                                       73% |                                20,857 |                                 34,309 |
|                             [Russia](/russia) |           19,867 |                    25,441 |                     174 |                      5,574 |                       38 |                                       28% |                                21,451 |                                 34,404 |
|                 [South Africa](/south-africa) |           16,283 |                    18,074 |                     309 |                      1,791 |                       31 |                                       11% |                                16,842 |                                 20,535 |
|                       [Indonesia](/indonesia) |           10,105 |                    15,005 |                      55 |                      4,900 |                       18 |                                       48% |                                13,043 |                                 19,972 |
|                               [Chile](/chile) |           12,469 |                    14,479 |                     764 |                      2,010 |                      106 |                                       16% |                                12,684 |                                 18,945 |
|                           [Ecuador](/ecuador) |           11,213 |                    12,358 |                     711 |                      1,145 |                       66 |                                       10% |                                11,310 |                                 14,258 |
|                             [Turkey](/turkey) |            7,785 |                    10,444 |                     125 |                      2,659 |                       32 |                                       34% |                                 8,265 |                                 14,262 |
|                             [Canada](/canada) |            9,297 |                     9,757 |                     261 |                        460 |                       12 |                                        5% |                                 9,332 |                                 11,230 |
|                           [Bolivia](/bolivia) |            7,765 |                     8,768 |                     762 |                      1,003 |                       87 |                                       13% |                                 8,188 |                                  9,404 |
|                   [Philippines](/philippines) |            5,127 |                     7,409 |                      69 |                      2,282 |                       21 |                                       45% |                                 6,073 |                                  9,480 |
|                         [Pakistan](/pakistan) |            6,444 |                     6,748 |                      31 |                        304 |                        1 |                                        5% |                                 6,497 |                                  7,240 |
|                               [Egypt](/egypt) |            5,835 |                     6,523 |                      65 |                        688 |                        7 |                                       12% |                                 5,914 |                                  8,010 |
|                     [Bangladesh](/bangladesh) |            5,072 |                     5,999 |                      37 |                        927 |                        6 |                                       18% |                                 5,425 |                                  7,058 |
|                 [Saudi Arabia](/saudi-arabia) |            4,599 |                     5,294 |                     154 |                        695 |                       20 |                                       15% |                                 4,837 |                                  6,067 |
|                               [China](/china) |            4,738 |                     4,789 |                       3 |                         51 |                        0 |                                        1% |                                 4,738 |                                  5,204 |
|                           [Morocco](/morocco) |            1,956 |                     3,382 |                      93 |                      1,426 |                       39 |                                       73% |                                 2,552 |                                  4,634 |
|                             [Panama](/panama) |            2,297 |                     2,835 |                     668 |                        538 |                      127 |                                       23% |                                 2,664 |                                  3,167 |
|                         [Honduras](/honduras) |            2,249 |                     2,762 |                     283 |                        513 |                       53 |                                       23% |                                 2,400 |                                  3,310 |
|     [Dominican Republic](/dominican-republic) |            2,076 |                     2,582 |                     240 |                        506 |                       47 |                                       24% |                                 2,270 |                                  3,140 |
|                             [Israel](/israel) |            1,378 |                     2,332 |                     274 |                        954 |                      112 |                                       69% |                                 1,690 |                                  3,237 |
|                           [Algeria](/algeria) |            1,703 |                     1,938 |                      45 |                        235 |                        5 |                                       14% |                                 1,753 |                                  2,275 |
|                               [Japan](/japan) |            1,540 |                     1,815 |                      14 |                        275 |                        2 |                                       18% |                                 1,614 |                                  2,146 |
|                           [Nigeria](/nigeria) |            1,102 |                     1,214 |                       6 |                        112 |                        1 |                                       10% |                                 1,129 |                                  1,383 |
|                       [Australia](/australia) |              869 |                       977 |                      39 |                        108 |                        4 |                                       12% |                                   904 |                                  1,090 |
|                             [Kuwait](/kuwait) |              592 |                       738 |                     175 |                        146 |                       35 |                                       25% |                                   610 |                                    931 |
|                   [South Korea](/south-korea) |              395 |                       506 |                      10 |                        111 |                        2 |                                       28% |                                   410 |                                    706 |
| [United Arab Emirates](/united-arab-emirates) |              407 |                       506 |                      52 |                         99 |                       10 |                                       24% |                                   412 |                                    695 |
|                                 [Cuba](/cuba) |              118 |                       155 |                      14 |                         37 |                        3 |                                       31% |                                   127 |                                    211 |
|                         [Malaysia](/malaysia) |              133 |                       141 |                       4 |                          8 |                        0 |                                        6% |                                   135 |                                    150 |
