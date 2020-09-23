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
### Updated Daily - Last Updated: September 23 (4am ET):
<p align="center">
  Current Total: <b>200,783</b> deaths | Projected Total: <b>223,400 deaths by Nov 1, 2020</b> (Range: 214-238k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.8%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 22, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |         <1% |        28% |
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
|             *[United States](/us)* |          200,783 |                   223,429 |                     673 |                     22,646 |                       68 |                                       11% |                               214,077 |                                237,463 |
|                 [New York](/us-ny) |           33,090 |                    33,530 |                   1,724 |                        440 |                       23 |                                        1% |                                33,105 |                                 35,536 |
|                    [Texas](/us-tx) |           15,229 |                    17,931 |                     618 |                      2,702 |                       93 |                                       18% |                                16,514 |                                 20,021 |
|               [California](/us-ca) |           15,189 |                    17,900 |                     453 |                      2,711 |                       69 |                                       18% |                                16,102 |                                 20,844 |
|               [New Jersey](/us-nj) |           16,076 |                    16,295 |                   1,835 |                        219 |                       25 |                                        1% |                                16,085 |                                 16,985 |
|                  [Florida](/us-fl) |           13,416 |                    15,865 |                     739 |                      2,449 |                      114 |                                       18% |                                14,514 |                                 17,798 |
|            [Massachusetts](/us-ma) |            9,328 |                     9,657 |                   1,390 |                        329 |                       47 |                                        4% |                                 9,350 |                                 10,290 |
|                 [Illinois](/us-il) |            8,722 |                     9,396 |                     742 |                        674 |                       53 |                                        8% |                                 8,798 |                                 10,289 |
|             [Pennsylvania](/us-pa) |            8,002 |                     8,520 |                     666 |                        518 |                       40 |                                        6% |                                 8,031 |                                  9,484 |
|                  [Georgia](/us-ga) |            6,673 |                     7,808 |                     735 |                      1,135 |                      107 |                                       17% |                                 7,110 |                                  8,973 |
|                 [Michigan](/us-mi) |            6,997 |                     7,360 |                     737 |                        363 |                       36 |                                        5% |                                 7,041 |                                  7,913 |
|                  [Arizona](/us-az) |            5,498 |                     5,936 |                     816 |                        438 |                       60 |                                        8% |                                 5,596 |                                  6,574 |
|                [Louisiana](/us-la) |            5,388 |                     5,927 |                   1,275 |                        539 |                      116 |                                       10% |                                 5,601 |                                  6,479 |
|                     [Ohio](/us-oh) |            4,635 |                     5,426 |                     464 |                        791 |                       68 |                                       17% |                                 4,831 |                                  6,447 |
|              [Connecticut](/us-ct) |            4,496 |                     4,593 |                   1,288 |                         97 |                       27 |                                        2% |                                 4,505 |                                  4,867 |
|           [North Carolina](/us-nc) |            3,286 |                     4,116 |                     392 |                        830 |                       79 |                                       25% |                                 3,667 |                                  4,836 |
|                 [Maryland](/us-md) |            3,895 |                     4,115 |                     681 |                        220 |                       36 |                                        6% |                                 3,912 |                                  4,515 |
|           [South Carolina](/us-sc) |            3,243 |                     3,921 |                     762 |                        678 |                      132 |                                       21% |                                 3,551 |                                  4,499 |
|                  [Indiana](/us-in) |            3,520 |                     3,883 |                     577 |                        363 |                       54 |                                       10% |                                 3,547 |                                  4,518 |
|                 [Virginia](/us-va) |            3,058 |                     3,759 |                     440 |                        701 |                       82 |                                       23% |                                 3,258 |                                  4,520 |
|              [Mississippi](/us-ms) |            2,846 |                     3,295 |                   1,107 |                        449 |                      151 |                                       16% |                                 3,034 |                                  3,713 |
|                [Tennessee](/us-tn) |            2,261 |                     2,929 |                     429 |                        668 |                       98 |                                       30% |                                 2,590 |                                  3,452 |
|                  [Alabama](/us-al) |            2,457 |                     2,832 |                     578 |                        375 |                       76 |                                       15% |                                 2,606 |                                  3,190 |
|               [Washington](/us-wa) |            2,070 |                     2,367 |                     311 |                        297 |                       39 |                                       14% |                                 2,119 |                                  2,836 |
|                 [Missouri](/us-mo) |            1,867 |                     2,362 |                     385 |                        495 |                       81 |                                       27% |                                 2,069 |                                  2,781 |
|                [Minnesota](/us-mn) |            2,031 |                     2,308 |                     409 |                        277 |                       49 |                                       14% |                                 2,078 |                                  2,680 |
|                 [Colorado](/us-co) |            2,025 |                     2,200 |                     382 |                        175 |                       30 |                                        9% |                                 2,036 |                                  2,536 |
|                   [Nevada](/us-nv) |            1,546 |                     1,808 |                     587 |                        262 |                       85 |                                       17% |                                 1,637 |                                  2,105 |
|                [Wisconsin](/us-wi) |            1,251 |                     1,590 |                     273 |                        339 |                       58 |                                       27% |                                 1,379 |                                  1,946 |
|                     [Iowa](/us-ia) |            1,293 |                     1,587 |                     503 |                        294 |                       93 |                                       23% |                                 1,403 |                                  1,874 |
|                 [Arkansas](/us-ar) |            1,209 |                     1,542 |                     511 |                        333 |                      110 |                                       28% |                                 1,379 |                                  1,784 |
|                 [Kentucky](/us-ky) |            1,119 |                     1,423 |                     319 |                        304 |                       68 |                                       27% |                                 1,236 |                                  1,699 |
|                 [Oklahoma](/us-ok) |              962 |                     1,222 |                     309 |                        260 |                       66 |                                       27% |                                 1,087 |                                  1,445 |
|             [Rhode Island](/us-ri) |            1,099 |                     1,172 |                   1,107 |                         73 |                       69 |                                        7% |                                 1,106 |                                  1,326 |
|               [New Mexico](/us-nm) |              854 |                       985 |                     470 |                        131 |                       62 |                                       15% |                                   890 |                                  1,142 |
|              [Puerto Rico](/us-pr) |              613 |                       908 |                     284 |                        295 |                       93 |                                       48% |                                   762 |                                  1,157 |
|                   [Kansas](/us-ks) |              614 |                       838 |                     288 |                        224 |                       77 |                                       37% |                                   709 |                                  1,035 |
|                   [Oregon](/us-or) |              532 |                       680 |                     161 |                        148 |                       35 |                                       28% |                                   592 |                                    832 |
|                 [Delaware](/us-de) |              628 |                       662 |                     679 |                         34 |                       35 |                                        5% |                                   632 |                                    724 |
|     [District of Columbia](/us-dc) |              621 |                       639 |                     905 |                         18 |                       26 |                                        3% |                                   624 |                                    673 |
|                    [Idaho](/us-id) |              451 |                       578 |                     323 |                        127 |                       71 |                                       28% |                                   515 |                                    666 |
|                 [Nebraska](/us-ne) |              461 |                       566 |                     293 |                        105 |                       54 |                                       23% |                                   488 |                                    686 |
|                     [Utah](/us-ut) |              443 |                       532 |                     166 |                         89 |                       28 |                                       20% |                                   478 |                                    603 |
|            [West Virginia](/us-wv) |              320 |                       503 |                     281 |                        183 |                      102 |                                       57% |                                   411 |                                    646 |
|            [New Hampshire](/us-nh) |              438 |                       460 |                     338 |                         22 |                       16 |                                        5% |                                   439 |                                    521 |
|             [North Dakota](/us-nd) |              196 |                       291 |                     382 |                         95 |                      125 |                                       49% |                                   241 |                                    372 |
|             [South Dakota](/us-sd) |              202 |                       282 |                     319 |                         80 |                       90 |                                       40% |                                   219 |                                    394 |
|                  [Montana](/us-mt) |              163 |                       266 |                     249 |                        103 |                       97 |                                       63% |                                   219 |                                    348 |
|                   [Hawaii](/us-hi) |              120 |                       211 |                     149 |                         91 |                       64 |                                       76% |                                   159 |                                    315 |
|                    [Maine](/us-me) |              140 |                       157 |                     116 |                         17 |                       12 |                                       12% |                                   143 |                                    183 |
|                     [Guam](/us-gu) |               37 |                        80 |                     481 |                         43 |                      258 |                                      115% |                                    58 |                                    115 |
|                  [Wyoming](/us-wy) |               49 |                        64 |                     110 |                         15 |                       26 |                                       30% |                                    56 |                                     77 |
|                  [Vermont](/us-vt) |               58 |                        61 |                      98 |                          3 |                        6 |                                        6% |                                    59 |                                     69 |
|                   [Alaska](/us-ak) |               45 |                        61 |                      84 |                         16 |                       22 |                                       36% |                                    53 |                                     74 |
|           [Virgin Islands](/us-vi) |               19 |                        26 |                     246 |                          7 |                       65 |                                       36% |                                    22 |                                     32 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       10 |                                       29% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          195,787 |                   219,825 |                     371 |                     24,038 |                       41 |                                       12% |                               201,410 |                                274,495 |
| [United Kingdom](/united-kingdom) |           41,914 |                    43,811 |                     649 |                      1,897 |                       28 |                                        5% |                                41,956 |                                 50,807 |
|                   [Spain](/spain) |           30,904 |                    40,200 |                     856 |                      9,296 |                      198 |                                       30% |                                33,510 |                                 56,716 |
|                   [Italy](/italy) |           35,738 |                    36,782 |                     609 |                      1,044 |                       17 |                                        3% |                                35,755 |                                 40,711 |
|                 [France](/france) |           31,426 |                    34,966 |                     522 |                      3,540 |                       53 |                                       11% |                                31,487 |                                 51,354 |
|               [Belgium](/belgium) |            9,955 |                    10,237 |                     894 |                        282 |                       25 |                                        3% |                                 9,986 |                                 11,056 |
|               [Germany](/germany) |            9,405 |                     9,686 |                     117 |                        281 |                        3 |                                        3% |                                 9,416 |                                 10,785 |
|       [Netherlands](/netherlands) |            6,338 |                     6,648 |                     385 |                        310 |                       18 |                                        5% |                                 6,351 |                                  7,466 |
|               [Ukraine](/ukraine) |            3,716 |                     6,062 |                     138 |                      2,346 |                       53 |                                       63% |                                 4,778 |                                  8,008 |
|                 [Sweden](/sweden) |            5,870 |                     5,959 |                     583 |                         89 |                        9 |                                        2% |                                 5,876 |                                  6,207 |
|               [Romania](/romania) |            4,503 |                     5,941 |                     306 |                      1,438 |                       74 |                                       32% |                                 5,118 |                                  7,251 |
|                 [Poland](/poland) |            2,316 |                     2,961 |                      78 |                        645 |                       17 |                                       28% |                                 2,500 |                                  3,884 |
|             [Portugal](/portugal) |            1,925 |                     2,230 |                     217 |                        305 |                       30 |                                       16% |                                 1,950 |                                  2,715 |
|       [Switzerland](/switzerland) |            2,054 |                     2,224 |                     259 |                        170 |                       20 |                                        8% |                                 2,090 |                                  2,530 |
|               [Ireland](/ireland) |            1,792 |                     1,855 |                     378 |                         63 |                       13 |                                        4% |                                 1,796 |                                  2,042 |
|               [Moldova](/moldova) |            1,230 |                     1,636 |                     405 |                        406 |                      100 |                                       33% |                                 1,388 |                                  2,013 |
|               [Belarus](/belarus) |              791 |                     1,007 |                     107 |                        216 |                       23 |                                       27% |                                   863 |                                  1,302 |
|               [Hungary](/hungary) |              694 |                       996 |                     102 |                        302 |                       31 |                                       44% |                                   825 |                                  1,278 |
|             [Bulgaria](/bulgaria) |              767 |                       979 |                     140 |                        212 |                       30 |                                       28% |                                   868 |                                  1,166 |
|               [Czechia](/czechia) |              531 |                       970 |                      91 |                        439 |                       41 |                                       83% |                                   756 |                                  1,347 |
|               [Austria](/austria) |              771 |                       891 |                     101 |                        120 |                       14 |                                       16% |                                   787 |                                  1,104 |
|                 [Serbia](/serbia) |              743 |                       806 |                     116 |                         63 |                        9 |                                        9% |                                   758 |                                    906 |
|               [Denmark](/denmark) |              641 |                       706 |                     122 |                         65 |                       11 |                                       10% |                                   649 |                                    844 |
|                 [Greece](/greece) |              352 |                       621 |                      58 |                        269 |                       25 |                                       76% |                                   462 |                                    939 |
|               [Finland](/finland) |              341 |                       357 |                      65 |                         16 |                        3 |                                        5% |                                   343 |                                    414 |
|               [Croatia](/croatia) |              255 |                       356 |                      87 |                        101 |                       25 |                                       40% |                                   291 |                                    512 |
|                 [Norway](/norway) |              267 |                       283 |                      53 |                         16 |                        3 |                                        6% |                                   270 |                                    317 |
|             [Slovenia](/slovenia) |              142 |                       164 |                      79 |                         22 |                       11 |                                       16% |                                   146 |                                    208 |
|         [Luxembourg](/luxembourg) |              124 |                       137 |                     224 |                         13 |                       22 |                                       11% |                                   128 |                                    158 |
|           [Lithuania](/lithuania) |               87 |                        94 |                      34 |                          7 |                        2 |                                        8% |                                    88 |                                    104 |
|               [Estonia](/estonia) |               64 |                        68 |                      52 |                          4 |                        3 |                                        7% |                                    66 |                                     74 |
|                   [Malta](/malta) |               23 |                        58 |                     117 |                         35 |                       71 |                                      152% |                                    39 |                                    101 |
|             [Slovakia](/slovakia) |               40 |                        54 |                      10 |                         14 |                        3 |                                       36% |                                    44 |                                     82 |
|                 [Latvia](/latvia) |               36 |                        42 |                      22 |                          6 |                        3 |                                       16% |                                    37 |                                     50 |
|                 [Cyprus](/cyprus) |               22 |                        26 |                      29 |                          4 |                        4 |                                       17% |                                    23 |                                     30 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       12% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          537,454 |                   674,595 |                     130 |                    137,141 |                       26 |                                       26% |                               596,533 |                                789,280 |
|                             [Brazil](/brazil) |          138,105 |                   159,728 |                     757 |                     21,623 |                      102 |                                       16% |                               148,070 |                                177,140 |
|                               [India](/india) |           88,935 |                   135,096 |                      99 |                     46,161 |                       34 |                                       52% |                               107,205 |                                161,995 |
|                             [Mexico](/mexico) |           74,348 |                    88,764 |                     696 |                     14,416 |                      113 |                                       19% |                                82,631 |                                 97,200 |
|                                 [Peru](/peru) |           31,369 |                    33,715 |                   1,037 |                      2,346 |                       72 |                                        7% |                                31,854 |                                 36,939 |
|                                 [Iran](/iran) |           24,656 |                    30,472 |                     368 |                      5,816 |                       70 |                                       24% |                                27,338 |                                 35,037 |
|                         [Colombia](/colombia) |           24,397 |                    29,409 |                     584 |                      5,012 |                      100 |                                       21% |                                26,961 |                                 33,960 |
|                       [Argentina](/argentina) |           13,952 |                    25,670 |                     573 |                     11,718 |                      262 |                                       84% |                                21,170 |                                 35,148 |
|                             [Russia](/russia) |           19,575 |                    24,503 |                     168 |                      4,928 |                       34 |                                       25% |                                20,423 |                                 32,017 |
|                 [South Africa](/south-africa) |           16,118 |                    18,254 |                     312 |                      2,136 |                       36 |                                       13% |                                16,982 |                                 20,535 |
|                       [Indonesia](/indonesia) |            9,837 |                    14,844 |                      55 |                      5,007 |                       19 |                                       51% |                                12,803 |                                 20,107 |
|                               [Chile](/chile) |           12,321 |                    14,379 |                     759 |                      2,058 |                      109 |                                       17% |                                12,549 |                                 18,960 |
|                           [Ecuador](/ecuador) |           11,126 |                    12,308 |                     708 |                      1,182 |                       68 |                                       11% |                                11,208 |                                 14,271 |
|                             [Turkey](/turkey) |            7,639 |                    10,333 |                     124 |                      2,694 |                       32 |                                       35% |                                 8,072 |                                 14,462 |
|                             [Canada](/canada) |            9,286 |                     9,772 |                     261 |                        486 |                       13 |                                        5% |                                 9,323 |                                 11,292 |
|                           [Bolivia](/bolivia) |            7,693 |                     8,758 |                     761 |                      1,065 |                       92 |                                       14% |                                 8,156 |                                  9,435 |
|                   [Philippines](/philippines) |            5,049 |                     7,631 |                      71 |                      2,582 |                       24 |                                       51% |                                 6,118 |                                  9,881 |
|                         [Pakistan](/pakistan) |            6,432 |                     6,752 |                      31 |                        320 |                        1 |                                        5% |                                 6,486 |                                  7,272 |
|                               [Egypt](/egypt) |            5,806 |                     6,536 |                      65 |                        730 |                        7 |                                       13% |                                 5,892 |                                  8,125 |
|                     [Bangladesh](/bangladesh) |            5,007 |                     5,974 |                      37 |                        967 |                        6 |                                       19% |                                 5,383 |                                  7,076 |
|                 [Saudi Arabia](/saudi-arabia) |            4,542 |                     5,266 |                     154 |                        724 |                       21 |                                       16% |                                 4,795 |                                  6,052 |
|                               [China](/china) |            4,737 |                     4,789 |                       3 |                         52 |                        0 |                                        1% |                                 4,737 |                                  5,214 |
|                           [Morocco](/morocco) |            1,889 |                     3,386 |                      93 |                      1,497 |                       41 |                                       79% |                                 2,499 |                                  4,723 |
|                             [Panama](/panama) |            2,285 |                     2,876 |                     677 |                        591 |                      139 |                                       26% |                                 2,686 |                                  3,249 |
|                         [Honduras](/honduras) |            2,206 |                     2,709 |                     278 |                        503 |                       52 |                                       23% |                                 2,358 |                                  3,264 |
|     [Dominican Republic](/dominican-republic) |            2,064 |                     2,613 |                     243 |                        549 |                       51 |                                       27% |                                 2,269 |                                  3,202 |
|                             [Israel](/israel) |            1,285 |                     2,057 |                     242 |                        772 |                       91 |                                       60% |                                 1,515 |                                  3,016 |
|                           [Algeria](/algeria) |            1,689 |                     1,939 |                      45 |                        250 |                        6 |                                       15% |                                 1,742 |                                  2,292 |
|                               [Japan](/japan) |            1,519 |                     1,812 |                      14 |                        293 |                        2 |                                       19% |                                 1,600 |                                  2,167 |
|                           [Nigeria](/nigeria) |            1,100 |                     1,222 |                       6 |                        122 |                        1 |                                       11% |                                 1,130 |                                  1,403 |
|                       [Australia](/australia) |              859 |                       979 |                      39 |                        120 |                        5 |                                       14% |                                   898 |                                  1,104 |
|                             [Kuwait](/kuwait) |              588 |                       745 |                     177 |                        157 |                       37 |                                       27% |                                   609 |                                    952 |
| [United Arab Emirates](/united-arab-emirates) |              405 |                       510 |                      52 |                        105 |                       11 |                                       26% |                                   410 |                                    716 |
|                   [South Korea](/south-korea) |              388 |                       500 |                      10 |                        112 |                        2 |                                       29% |                                   402 |                                    710 |
|                                 [Cuba](/cuba) |              117 |                       156 |                      14 |                         39 |                        3 |                                       33% |                                   127 |                                    217 |
|                         [Malaysia](/malaysia) |              130 |                       138 |                       4 |                          8 |                        0 |                                        6% |                                   132 |                                    147 |
