We present an intuitive COVID-19 model that adds machine learning techniques on top of a classic infectious disease model to make projections for infections and deaths for the US and 70 other countries. The countries our projections cover encompass 6.4 billion people and account for more than 95% of all global reported COVID-19 deaths.

Our infections estimates include all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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
### Updated Daily - Last Updated: September 26 (2am ET):
<p align="center">
  Current Total: <b>203,747</b> deaths | Projected Total: <b>227,000 deaths by Nov 1, 2020</b> (Range: 217-242k)<br>
  Currently Infected: <b>1.0%</b> (1 in 100) | Total Infected: <b>15.8%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 26, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |          1% |        50% |
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
|             *[United States](/us)* |          203,747 |                   226,987 |                     684 |                     23,240 |                       70 |                                       11% |                               217,521 |                                241,224 |
|                 [New York](/us-ny) |           33,122 |                    33,529 |                   1,724 |                        407 |                       21 |                                        1% |                                33,136 |                                 35,403 |
|                    [Texas](/us-tx) |           15,610 |                    18,317 |                     632 |                      2,707 |                       93 |                                       17% |                                16,812 |                                 20,584 |
|               [California](/us-ca) |           15,516 |                    18,147 |                     459 |                      2,631 |                       67 |                                       17% |                                16,398 |                                 21,020 |
|                  [Florida](/us-fl) |           13,915 |                    16,726 |                     779 |                      2,811 |                      131 |                                       20% |                                15,398 |                                 18,993 |
|               [New Jersey](/us-nj) |           16,097 |                    16,303 |                   1,835 |                        206 |                       23 |                                        1% |                                16,105 |                                 16,948 |
|            [Massachusetts](/us-ma) |            9,373 |                     9,690 |                   1,394 |                        317 |                       46 |                                        3% |                                 9,395 |                                 10,285 |
|                 [Illinois](/us-il) |            8,807 |                     9,522 |                     751 |                        715 |                       56 |                                        8% |                                 8,936 |                                 10,546 |
|             [Pennsylvania](/us-pa) |            8,065 |                     8,918 |                     697 |                        853 |                       67 |                                       11% |                                 8,110 |                                 10,148 |
|                  [Georgia](/us-ga) |            6,874 |                     8,232 |                     775 |                      1,358 |                      128 |                                       20% |                                 7,462 |                                  9,451 |
|                 [Michigan](/us-mi) |            7,027 |                     7,365 |                     737 |                        338 |                       34 |                                        5% |                                 7,070 |                                  7,890 |
|                  [Arizona](/us-az) |            5,587 |                     6,080 |                     835 |                        493 |                       68 |                                        9% |                                 5,727 |                                  6,696 |
|                [Louisiana](/us-la) |            5,444 |                     5,935 |                   1,277 |                        491 |                      106 |                                        9% |                                 5,634 |                                  6,454 |
|                     [Ohio](/us-oh) |            4,734 |                     5,520 |                     472 |                        786 |                       67 |                                       17% |                                 4,932 |                                  6,509 |
|              [Connecticut](/us-ct) |            4,501 |                     4,592 |                   1,288 |                         91 |                       26 |                                        2% |                                 4,509 |                                  4,848 |
|           [North Carolina](/us-nc) |            3,409 |                     4,260 |                     406 |                        851 |                       81 |                                       25% |                                 3,785 |                                  4,979 |
|                 [Maryland](/us-md) |            3,917 |                     4,126 |                     682 |                        209 |                       35 |                                        5% |                                 3,933 |                                  4,505 |
|                  [Indiana](/us-in) |            3,566 |                     3,918 |                     582 |                        352 |                       52 |                                       10% |                                 3,593 |                                  4,532 |
|           [South Carolina](/us-sc) |            3,297 |                     3,914 |                     760 |                        617 |                      120 |                                       19% |                                 3,575 |                                  4,445 |
|                 [Virginia](/us-va) |            3,134 |                     3,806 |                     446 |                        672 |                       79 |                                       21% |                                 3,331 |                                  4,549 |
|              [Mississippi](/us-ms) |            2,894 |                     3,305 |                   1,111 |                        411 |                      138 |                                       14% |                                 3,061 |                                  3,699 |
|                [Tennessee](/us-tn) |            2,352 |                     3,013 |                     441 |                        661 |                       97 |                                       28% |                                 2,669 |                                  3,503 |
|                  [Alabama](/us-al) |            2,491 |                     2,836 |                     578 |                        345 |                       70 |                                       14% |                                 2,623 |                                  3,178 |
|                 [Missouri](/us-mo) |            1,991 |                     2,570 |                     419 |                        579 |                       94 |                                       29% |                                 2,243 |                                  3,048 |
|               [Washington](/us-wa) |            2,100 |                     2,389 |                     314 |                        289 |                       38 |                                       14% |                                 2,145 |                                  2,842 |
|                [Minnesota](/us-mn) |            2,046 |                     2,301 |                     408 |                        255 |                       45 |                                       12% |                                 2,090 |                                  2,647 |
|                 [Colorado](/us-co) |            2,034 |                     2,196 |                     381 |                        162 |                       28 |                                        8% |                                 2,045 |                                  2,506 |
|                   [Nevada](/us-nv) |            1,573 |                     1,816 |                     590 |                        243 |                       79 |                                       15% |                                 1,654 |                                  2,101 |
|                [Wisconsin](/us-wi) |            1,274 |                     1,606 |                     276 |                        332 |                       57 |                                       26% |                                 1,400 |                                  1,945 |
|                 [Arkansas](/us-ar) |            1,266 |                     1,604 |                     532 |                        338 |                      112 |                                       27% |                                 1,436 |                                  1,850 |
|                     [Iowa](/us-ia) |            1,312 |                     1,582 |                     501 |                        270 |                       85 |                                       21% |                                 1,413 |                                  1,849 |
|                 [Kentucky](/us-ky) |            1,149 |                     1,443 |                     323 |                        294 |                       66 |                                       26% |                                 1,261 |                                  1,711 |
|                 [Oklahoma](/us-ok) |              993 |                     1,250 |                     316 |                        257 |                       65 |                                       26% |                                 1,117 |                                  1,464 |
|             [Rhode Island](/us-ri) |            1,107 |                     1,175 |                   1,109 |                         68 |                       64 |                                        6% |                                 1,113 |                                  1,317 |
|               [New Mexico](/us-nm) |              865 |                     1,007 |                     480 |                        142 |                       68 |                                       16% |                                   911 |                                  1,172 |
|              [Puerto Rico](/us-pr) |              635 |                       899 |                     281 |                        264 |                       83 |                                       42% |                                   770 |                                  1,109 |
|                   [Kansas](/us-ks) |              635 |                       848 |                     291 |                        213 |                       73 |                                       34% |                                   723 |                                  1,029 |
|                   [Oregon](/us-or) |              542 |                       682 |                     162 |                        140 |                       33 |                                       26% |                                   597 |                                    823 |
|                 [Delaware](/us-de) |              631 |                       663 |                     681 |                         32 |                       33 |                                        5% |                                   635 |                                    721 |
|     [District of Columbia](/us-dc) |              623 |                       640 |                     907 |                         17 |                       24 |                                        3% |                                   626 |                                    672 |
|                    [Idaho](/us-id) |              458 |                       568 |                     318 |                        110 |                       62 |                                       24% |                                   514 |                                    641 |
|                 [Nebraska](/us-ne) |              468 |                       568 |                     294 |                        100 |                       52 |                                       21% |                                   494 |                                    681 |
|                     [Utah](/us-ut) |              448 |                       552 |                     172 |                        104 |                       32 |                                       23% |                                   486 |                                    643 |
|            [West Virginia](/us-wv) |              335 |                       510 |                     285 |                        175 |                       98 |                                       52% |                                   422 |                                    646 |
|            [New Hampshire](/us-nh) |              438 |                       458 |                     337 |                         20 |                       15 |                                        5% |                                   439 |                                    516 |
|             [North Dakota](/us-nd) |              219 |                       358 |                     470 |                        139 |                      183 |                                       64% |                                   294 |                                    461 |
|             [South Dakota](/us-sd) |              216 |                       313 |                     354 |                         97 |                      110 |                                       45% |                                   244 |                                    440 |
|                  [Montana](/us-mt) |              170 |                       269 |                     252 |                         99 |                       93 |                                       58% |                                   224 |                                    346 |
|                   [Hawaii](/us-hi) |              127 |                       204 |                     144 |                         77 |                       54 |                                       61% |                                   160 |                                    290 |
|                    [Maine](/us-me) |              140 |                       155 |                     115 |                         15 |                       11 |                                       11% |                                   143 |                                    179 |
|                   [Alaska](/us-ak) |               52 |                        79 |                     107 |                         27 |                       36 |                                       51% |                                    66 |                                    103 |
|                     [Guam](/us-gu) |               39 |                        73 |                     443 |                         34 |                      207 |                                       88% |                                    56 |                                    103 |
|                  [Wyoming](/us-wy) |               50 |                        64 |                     110 |                         14 |                       24 |                                       27% |                                    56 |                                     76 |
|                  [Vermont](/us-vt) |               58 |                        61 |                      98 |                          3 |                        5 |                                        6% |                                    58 |                                     69 |
|           [Virgin Islands](/us-vi) |               19 |                        25 |                     234 |                          6 |                       53 |                                       29% |                                    21 |                                     29 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      46 |                          1 |                       10 |                                       26% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          197,288 |                   222,299 |                     375 |                     25,011 |                       42 |                                       13% |                               201,872 |                                285,669 |
| [United Kingdom](/united-kingdom) |           42,025 |                    45,479 |                     673 |                      3,454 |                       51 |                                        8% |                                42,118 |                                 56,963 |
|                   [Spain](/spain) |           31,232 |                    37,392 |                     797 |                      6,160 |                      131 |                                       20% |                                32,256 |                                 50,653 |
|                   [Italy](/italy) |           35,801 |                    36,797 |                     610 |                        996 |                       17 |                                        3% |                                35,822 |                                 40,443 |
|                 [France](/france) |           31,675 |                    35,513 |                     530 |                      3,838 |                       57 |                                       12% |                                31,726 |                                 54,128 |
|               [Belgium](/belgium) |            9,969 |                    10,496 |                     916 |                        527 |                       46 |                                        5% |                                 9,994 |                                 12,638 |
|               [Germany](/germany) |            9,451 |                     9,995 |                     120 |                        544 |                        7 |                                        6% |                                 9,468 |                                 11,867 |
|       [Netherlands](/netherlands) |            6,377 |                     7,229 |                     418 |                        852 |                       49 |                                       13% |                                 6,421 |                                  9,767 |
|               [Ukraine](/ukraine) |            3,910 |                     6,367 |                     145 |                      2,457 |                       56 |                                       63% |                                 4,993 |                                  8,422 |
|               [Romania](/romania) |            4,633 |                     6,082 |                     313 |                      1,449 |                       75 |                                       31% |                                 5,319 |                                  7,345 |
|                 [Sweden](/sweden) |            5,880 |                     6,018 |                     588 |                        138 |                       14 |                                        2% |                                 5,894 |                                  6,377 |
|                 [Poland](/poland) |            2,392 |                     3,208 |                      84 |                        816 |                       21 |                                       34% |                                 2,641 |                                  4,244 |
|             [Portugal](/portugal) |            1,936 |                     2,241 |                     218 |                        305 |                       30 |                                       16% |                                 2,007 |                                  2,623 |
|       [Switzerland](/switzerland) |            2,064 |                     2,226 |                     259 |                        162 |                       19 |                                        8% |                                 2,098 |                                  2,503 |
|               [Ireland](/ireland) |            1,797 |                     1,913 |                     390 |                        116 |                       24 |                                        6% |                                 1,805 |                                  2,375 |
|               [Moldova](/moldova) |            1,264 |                     1,658 |                     410 |                        394 |                       98 |                                       31% |                                 1,419 |                                  2,038 |
|               [Czechia](/czechia) |              581 |                     1,533 |                     144 |                        952 |                       89 |                                      164% |                                   951 |                                  2,591 |
|               [Hungary](/hungary) |              718 |                     1,057 |                     108 |                        339 |                       35 |                                       47% |                                   868 |                                  1,366 |
|               [Belarus](/belarus) |              807 |                     1,047 |                     111 |                        240 |                       25 |                                       30% |                                   879 |                                  1,389 |
|             [Bulgaria](/bulgaria) |              789 |                       993 |                     142 |                        204 |                       29 |                                       26% |                                   888 |                                  1,177 |
|               [Austria](/austria) |              786 |                       984 |                     111 |                        198 |                       22 |                                       25% |                                   825 |                                  1,354 |
|               [Denmark](/denmark) |              647 |                       807 |                     139 |                        160 |                       28 |                                       25% |                                   671 |                                  1,270 |
|                 [Serbia](/serbia) |              746 |                       802 |                     115 |                         56 |                        8 |                                        7% |                                   759 |                                    887 |
|                 [Greece](/greece) |              369 |                       685 |                      64 |                        316 |                       29 |                                       86% |                                   489 |                                  1,026 |
|               [Finland](/finland) |              343 |                       381 |                      69 |                         38 |                        7 |                                       11% |                                   356 |                                    437 |
|               [Croatia](/croatia) |              266 |                       367 |                      90 |                        101 |                       25 |                                       38% |                                   301 |                                    517 |
|                 [Norway](/norway) |              270 |                       307 |                      57 |                         37 |                        7 |                                       14% |                                   282 |                                    349 |
|             [Slovenia](/slovenia) |              145 |                       187 |                      90 |                         42 |                       20 |                                       29% |                                   160 |                                    234 |
|         [Luxembourg](/luxembourg) |              124 |                       136 |                     221 |                         12 |                       19 |                                       10% |                                   127 |                                    155 |
|           [Lithuania](/lithuania) |               89 |                       109 |                      39 |                         20 |                        7 |                                       22% |                                    96 |                                    130 |
|               [Estonia](/estonia) |               64 |                        80 |                      60 |                         16 |                       12 |                                       24% |                                    71 |                                     95 |
|                   [Malta](/malta) |               29 |                        70 |                     142 |                         41 |                       84 |                                      142% |                                    48 |                                    128 |
|             [Slovakia](/slovakia) |               41 |                        59 |                      11 |                         18 |                        3 |                                       45% |                                    48 |                                     80 |
|                 [Latvia](/latvia) |               36 |                        44 |                      23 |                          8 |                        4 |                                       23% |                                    39 |                                     52 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      29 |                          3 |                        4 |                                       15% |                                    23 |                                     30 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                        8 |                                       27% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          550,385 |                   679,695 |                     131 |                    129,310 |                       25 |                                       23% |                               609,712 |                                785,419 |
|                             [Brazil](/brazil) |          140,537 |                   160,751 |                     762 |                     20,214 |                       96 |                                       14% |                               151,181 |                                176,528 |
|                               [India](/india) |           92,290 |                   134,865 |                      99 |                     42,575 |                       31 |                                       46% |                               110,352 |                                158,221 |
|                             [Mexico](/mexico) |           75,844 |                    89,010 |                     698 |                     13,166 |                      103 |                                       17% |                                83,486 |                                 96,858 |
|                                 [Peru](/peru) |           32,037 |                    35,617 |                   1,096 |                      3,580 |                      110 |                                       11% |                                33,967 |                                 38,933 |
|                                 [Iran](/iran) |           25,222 |                    31,026 |                     374 |                      5,804 |                       70 |                                       23% |                                28,250 |                                 35,546 |
|                         [Colombia](/colombia) |           25,103 |                    29,770 |                     591 |                      4,667 |                       93 |                                       19% |                                27,735 |                                 33,901 |
|                       [Argentina](/argentina) |           15,208 |                    26,419 |                     590 |                     11,211 |                      250 |                                       74% |                                21,759 |                                 35,193 |
|                             [Russia](/russia) |           19,973 |                    24,756 |                     170 |                      4,783 |                       33 |                                       24% |                                20,776 |                                 32,070 |
|                 [South Africa](/south-africa) |           16,312 |                    18,007 |                     308 |                      1,695 |                       29 |                                       10% |                                16,836 |                                 20,360 |
|                       [Indonesia](/indonesia) |           10,218 |                    14,987 |                      55 |                      4,769 |                       18 |                                       47% |                                13,092 |                                 19,827 |
|                               [Chile](/chile) |           12,527 |                    14,488 |                     764 |                      1,961 |                      103 |                                       16% |                                12,733 |                                 18,878 |
|                           [Ecuador](/ecuador) |           11,236 |                    12,335 |                     710 |                      1,099 |                       63 |                                       10% |                                11,328 |                                 14,180 |
|                             [Turkey](/turkey) |            7,858 |                    10,492 |                     126 |                      2,634 |                       32 |                                       34% |                                 8,326 |                                 14,216 |
|                             [Canada](/canada) |            9,306 |                     9,760 |                     261 |                        454 |                       12 |                                        5% |                                 9,341 |                                 11,208 |
|                           [Bolivia](/bolivia) |            7,800 |                     8,767 |                     761 |                        967 |                       84 |                                       12% |                                 8,205 |                                  9,388 |
|                   [Philippines](/philippines) |            5,196 |                     7,430 |                      69 |                      2,234 |                       21 |                                       43% |                                 6,129 |                                  9,449 |
|                         [Pakistan](/pakistan) |            6,451 |                     6,745 |                      31 |                        294 |                        1 |                                        5% |                                 6,502 |                                  7,223 |
|                               [Egypt](/egypt) |            5,853 |                     6,532 |                      65 |                        679 |                        7 |                                       12% |                                 5,929 |                                  7,969 |
|                     [Bangladesh](/bangladesh) |            5,093 |                     5,987 |                      37 |                        894 |                        5 |                                       18% |                                 5,430 |                                  7,016 |
|                 [Saudi Arabia](/saudi-arabia) |            4,625 |                     5,306 |                     155 |                        681 |                       20 |                                       15% |                                 4,855 |                                  6,062 |
|                               [China](/china) |            4,739 |                     4,789 |                       3 |                         50 |                        0 |                                        1% |                                 4,739 |                                  5,195 |
|                           [Morocco](/morocco) |            1,998 |                     3,426 |                      94 |                      1,428 |                       39 |                                       71% |                                 2,586 |                                  4,652 |
|                             [Panama](/panama) |            2,311 |                     2,830 |                     666 |                        519 |                      122 |                                       22% |                                 2,667 |                                  3,150 |
|                         [Honduras](/honduras) |            2,271 |                     2,785 |                     286 |                        514 |                       53 |                                       23% |                                 2,417 |                                  3,349 |
|     [Dominican Republic](/dominican-republic) |            2,087 |                     2,577 |                     240 |                        490 |                       46 |                                       23% |                                 2,266 |                                  3,123 |
|                             [Israel](/israel) |            1,412 |                     2,279 |                     268 |                        867 |                      102 |                                       61% |                                 1,725 |                                  3,436 |
|                           [Algeria](/algeria) |            1,707 |                     1,931 |                      45 |                        224 |                        5 |                                       13% |                                 1,754 |                                  2,256 |
|                               [Japan](/japan) |            1,544 |                     1,802 |                      14 |                        258 |                        2 |                                       17% |                                 1,614 |                                  2,114 |
|                           [Nigeria](/nigeria) |            1,103 |                     1,210 |                       6 |                        107 |                        1 |                                       10% |                                 1,129 |                                  1,374 |
|                       [Australia](/australia) |              870 |                       970 |                      38 |                        100 |                        4 |                                       11% |                                   902 |                                  1,074 |
|                             [Kuwait](/kuwait) |              595 |                       737 |                     175 |                        142 |                       34 |                                       24% |                                   613 |                                    923 |
|                   [South Korea](/south-korea) |              399 |                       511 |                      10 |                        112 |                        2 |                                       28% |                                   413 |                                    707 |
| [United Arab Emirates](/united-arab-emirates) |              409 |                       506 |                      52 |                         97 |                       10 |                                       24% |                                   414 |                                    690 |
|                                 [Cuba](/cuba) |              118 |                       152 |                      13 |                         34 |                        3 |                                       29% |                                   126 |                                    201 |
|                         [Malaysia](/malaysia) |              133 |                       141 |                       4 |                          8 |                        0 |                                        6% |                                   135 |                                    149 |
