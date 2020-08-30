We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are infectious, we recommend dividing the "currently infected" number by half.

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

* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* **August 25:** In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 30 (2am ET):
<p align="center">
  Current Total: <b>182,758</b> deaths | Projected Total: <b>220,200 deaths by Nov 1, 2020</b> (Range: 206-240k)<br>
  Currently Infected: <b>1.2%</b> (1 in 81) | Total Infected: <b>14.3%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 28, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          6% |        90% |         99% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          4% |        23% |
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

|                                    |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          182,758 |                   220,154 |                     663 |                     37,396 |                      113 |                                       20% |                               206,139 |                                239,924 |
|                 [New York](/us-ny) |           32,938 |                    33,132 |                   1,703 |                        194 |                       10 |                                        1% |                                32,948 |                                 34,086 |
|               [California](/us-ca) |           12,894 |                    18,484 |                     468 |                      5,590 |                      141 |                                       43% |                                15,506 |                                 23,288 |
|                    [Texas](/us-tx) |           12,607 |                    18,357 |                     633 |                      5,750 |                      198 |                                       46% |                                15,739 |                                 21,741 |
|               [New Jersey](/us-nj) |           15,933 |                    16,064 |                   1,809 |                        131 |                       15 |                                        1% |                                15,948 |                                 16,471 |
|                  [Florida](/us-fl) |           11,105 |                    14,424 |                     672 |                      3,319 |                      155 |                                       30% |                                12,776 |                                 16,527 |
|            [Massachusetts](/us-ma) |            9,036 |                     9,683 |                   1,393 |                        647 |                       93 |                                        7% |                                 9,102 |                                 10,931 |
|                 [Illinois](/us-il) |            8,217 |                     9,286 |                     733 |                      1,069 |                       84 |                                       13% |                                 8,341 |                                 10,903 |
|             [Pennsylvania](/us-pa) |            7,656 |                     8,439 |                     659 |                        783 |                       61 |                                       10% |                                 7,700 |                                 10,021 |
|                  [Georgia](/us-ga) |            5,576 |                     7,750 |                     730 |                      2,174 |                      205 |                                       39% |                                 6,650 |                                  9,422 |
|                 [Michigan](/us-mi) |            6,712 |                     7,195 |                     720 |                        483 |                       48 |                                        7% |                                 6,760 |                                  8,065 |
|                  [Arizona](/us-az) |            5,007 |                     5,995 |                     824 |                        988 |                      136 |                                       20% |                                 5,434 |                                  6,821 |
|                [Louisiana](/us-la) |            4,904 |                     5,851 |                   1,259 |                        947 |                      204 |                                       19% |                                 5,299 |                                  6,739 |
|                     [Ohio](/us-oh) |            4,252 |                     5,092 |                     436 |                        840 |                       72 |                                       20% |                                 4,455 |                                  6,141 |
|              [Connecticut](/us-ct) |            4,465 |                     4,531 |                   1,271 |                         66 |                       19 |                                        1% |                                 4,476 |                                  4,725 |
|                 [Maryland](/us-md) |            3,746 |                     4,173 |                     690 |                        427 |                       71 |                                       11% |                                 3,786 |                                  4,987 |
|                  [Indiana](/us-in) |            3,285 |                     4,059 |                     603 |                        774 |                      115 |                                       24% |                                 3,383 |                                  5,175 |
|           [North Carolina](/us-nc) |            2,683 |                     3,886 |                     370 |                      1,203 |                      115 |                                       45% |                                 3,225 |                                  5,019 |
|           [South Carolina](/us-sc) |            2,698 |                     3,816 |                     741 |                      1,118 |                      217 |                                       41% |                                 3,260 |                                  4,646 |
|              [Mississippi](/us-ms) |            2,427 |                     3,224 |                   1,083 |                        797 |                      268 |                                       33% |                                 2,797 |                                  3,845 |
|                 [Virginia](/us-va) |            2,568 |                     3,187 |                     373 |                        619 |                       73 |                                       24% |                                 2,613 |                                  4,117 |
|                  [Alabama](/us-al) |            2,152 |                     2,851 |                     581 |                        699 |                      143 |                                       32% |                                 2,479 |                                  3,456 |
|                [Tennessee](/us-tn) |            1,725 |                     2,810 |                     411 |                      1,085 |                      159 |                                       63% |                                 2,264 |                                  3,610 |
|               [Washington](/us-wa) |            1,905 |                     2,558 |                     336 |                        653 |                       86 |                                       34% |                                 2,053 |                                  3,344 |
|                [Minnesota](/us-mn) |            1,863 |                     2,305 |                     409 |                        442 |                       78 |                                       24% |                                 1,937 |                                  2,927 |
|                 [Colorado](/us-co) |            1,942 |                     2,146 |                     373 |                        204 |                       35 |                                       10% |                                 1,956 |                                  2,706 |
|                 [Missouri](/us-mo) |            1,528 |                     2,097 |                     342 |                        569 |                       93 |                                       37% |                                 1,763 |                                  2,671 |
|                   [Nevada](/us-nv) |            1,302 |                     1,932 |                     627 |                        630 |                      204 |                                       48% |                                 1,620 |                                  2,364 |
|                     [Iowa](/us-ia) |            1,100 |                     1,599 |                     507 |                        499 |                      158 |                                       45% |                                 1,272 |                                  2,121 |
|                [Wisconsin](/us-wi) |            1,119 |                     1,544 |                     265 |                        425 |                       73 |                                       38% |                                 1,287 |                                  1,997 |
|                 [Kentucky](/us-ky) |              921 |                     1,338 |                     299 |                        417 |                       93 |                                       45% |                                 1,083 |                                  1,751 |
|                 [Oklahoma](/us-ok) |              797 |                     1,314 |                     332 |                        517 |                      131 |                                       65% |                                 1,024 |                                  1,787 |
|                 [Arkansas](/us-ar) |              772 |                     1,287 |                     426 |                        515 |                      171 |                                       67% |                                 1,019 |                                  1,661 |
|             [Rhode Island](/us-ri) |            1,046 |                     1,113 |                   1,051 |                         67 |                       63 |                                        6% |                                 1,056 |                                  1,242 |
|               [New Mexico](/us-nm) |              769 |                     1,022 |                     488 |                        253 |                      121 |                                       33% |                                   861 |                                  1,295 |
|              [Puerto Rico](/us-pr) |              428 |                       866 |                     271 |                        438 |                      137 |                                      102% |                                   641 |                                  1,254 |
|                   [Oregon](/us-or) |              454 |                       757 |                     179 |                        303 |                       72 |                                       67% |                                   578 |                                  1,057 |
|                 [Delaware](/us-de) |              604 |                       668 |                     686 |                         64 |                       66 |                                       11% |                                   611 |                                    789 |
|                    [Idaho](/us-id) |              358 |                       654 |                     366 |                        296 |                      166 |                                       83% |                                   507 |                                    879 |
|                   [Kansas](/us-ks) |              449 |                       650 |                     223 |                        201 |                       69 |                                       45% |                                   528 |                                    868 |
|     [District of Columbia](/us-dc) |              605 |                       644 |                     913 |                         39 |                       56 |                                        7% |                                   612 |                                    712 |
|                     [Utah](/us-ut) |              407 |                       601 |                     188 |                        194 |                       61 |                                       48% |                                   492 |                                    787 |
|                 [Nebraska](/us-ne) |              392 |                       524 |                     271 |                        132 |                       68 |                                       34% |                                   429 |                                    686 |
|            [New Hampshire](/us-nh) |              432 |                       470 |                     345 |                         38 |                       28 |                                        9% |                                   435 |                                    549 |
|            [West Virginia](/us-wv) |              215 |                       451 |                     252 |                        236 |                      132 |                                      110% |                                   323 |                                    663 |
|             [North Dakota](/us-nd) |              141 |                       241 |                     316 |                        100 |                      131 |                                       71% |                                   178 |                                    361 |
|             [South Dakota](/us-sd) |              167 |                       240 |                     271 |                         73 |                       83 |                                       44% |                                   185 |                                    320 |
|                  [Montana](/us-mt) |              104 |                       212 |                     198 |                        108 |                      101 |                                      103% |                                   150 |                                    321 |
|                   [Hawaii](/us-hi) |               62 |                       184 |                     130 |                        122 |                       86 |                                      197% |                                   109 |                                    338 |
|                    [Maine](/us-me) |              132 |                       151 |                     112 |                         19 |                       14 |                                       14% |                                   136 |                                    177 |
|                   [Alaska](/us-ak) |               37 |                        75 |                     103 |                         38 |                       52 |                                      103% |                                    54 |                                    115 |
|                  [Vermont](/us-vt) |               58 |                        70 |                     112 |                         12 |                       20 |                                       21% |                                    60 |                                     96 |
|                  [Wyoming](/us-wy) |               37 |                        60 |                     104 |                         23 |                       40 |                                       63% |                                    46 |                                     88 |
|                     [Guam](/us-gu) |               10 |                        48 |                     289 |                         38 |                      228 |                                      378% |                                    22 |                                     89 |
|           [Virgin Islands](/us-vi) |               14 |                        43 |                     409 |                         29 |                      275 |                                      206% |                                    27 |                                     70 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      53 |                          1 |                       17 |                                       46% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,568 |                   203,347 |                     343 |                     14,779 |                      837 |                                        8% |                               191,880 |                                235,101 |
| [United Kingdom](/united-kingdom) |           41,585 |                    42,258 |                     626 |                        673 |                       10 |                                        2% |                                41,606 |                                 44,721 |
|                   [Italy](/italy) |           35,473 |                    36,118 |                     598 |                        645 |                       11 |                                        2% |                                35,500 |                                 38,635 |
|                 [France](/france) |           30,601 |                    32,014 |                     478 |                      1,413 |                       21 |                                        5% |                                30,646 |                                 37,624 |
|                   [Spain](/spain) |           29,011 |                    31,013 |                     661 |                      2,002 |                       43 |                                        7% |                                29,059 |                                 37,142 |
|               [Belgium](/belgium) |            9,891 |                    10,210 |                     891 |                        319 |                       28 |                                        3% |                                 9,923 |                                 11,319 |
|               [Germany](/germany) |            9,299 |                     9,842 |                     119 |                        543 |                        7 |                                        6% |                                 9,338 |                                 11,582 |
|       [Netherlands](/netherlands) |            6,252 |                     6,569 |                     380 |                        317 |                       18 |                                        5% |                                 6,275 |                                  7,787 |
|               [Romania](/romania) |            3,539 |                     6,074 |                     313 |                      2,535 |                      131 |                                       72% |                                 4,603 |                                  8,654 |
|                 [Sweden](/sweden) |            5,821 |                     5,907 |                     577 |                         86 |                        8 |                                        1% |                                 5,832 |                                  5,997 |
|               [Ukraine](/ukraine) |            2,540 |                     5,336 |                     121 |                      2,796 |                       64 |                                      110% |                                 3,491 |                                  8,691 |
|                 [Poland](/poland) |            2,032 |                     2,931 |                      77 |                        899 |                       24 |                                       44% |                                 2,301 |                                  4,070 |
|       [Switzerland](/switzerland) |            2,005 |                     2,107 |                     245 |                        102 |                       12 |                                        5% |                                 2,021 |                                  2,382 |
|             [Portugal](/portugal) |            1,818 |                     2,029 |                     197 |                        211 |                       21 |                                       12% |                                 1,826 |                                  2,504 |
|               [Ireland](/ireland) |            1,777 |                     1,839 |                     375 |                         62 |                       13 |                                        3% |                                 1,786 |                                  2,017 |
|               [Moldova](/moldova) |              990 |                     1,384 |                     342 |                        394 |                       97 |                                       40% |                                 1,143 |                                  1,844 |
|             [Bulgaria](/bulgaria) |              605 |                     1,123 |                     160 |                        518 |                       74 |                                       86% |                                   793 |                                  1,752 |
|                 [Serbia](/serbia) |              710 |                       901 |                     129 |                        191 |                       27 |                                       27% |                                   784 |                                  1,066 |
|               [Belarus](/belarus) |              671 |                       864 |                      91 |                        193 |                       20 |                                       29% |                                   770 |                                  1,000 |
|               [Austria](/austria) |              733 |                       808 |                      91 |                         75 |                        8 |                                       10% |                                   749 |                                    986 |
|               [Denmark](/denmark) |              624 |                       675 |                     116 |                         51 |                        9 |                                        8% |                                   635 |                                    802 |
|               [Hungary](/hungary) |              614 |                       674 |                      69 |                         60 |                        6 |                                       10% |                                   620 |                                    815 |
|               [Czechia](/czechia) |              421 |                       559 |                      52 |                        138 |                       13 |                                       33% |                                   452 |                                    767 |
|                 [Greece](/greece) |              260 |                       500 |                      47 |                        240 |                       22 |                                       92% |                                   343 |                                    843 |
|               [Finland](/finland) |              335 |                       361 |                      65 |                         26 |                        5 |                                        8% |                                   339 |                                    436 |
|               [Croatia](/croatia) |              183 |                       308 |                      76 |                        125 |                       31 |                                       69% |                                   224 |                                    462 |
|                 [Norway](/norway) |              264 |                       301 |                      56 |                         37 |                        7 |                                       14% |                                   274 |                                    371 |
|             [Slovenia](/slovenia) |              133 |                       162 |                      78 |                         29 |                       14 |                                       22% |                                   137 |                                    210 |
|         [Luxembourg](/luxembourg) |              124 |                       154 |                     251 |                         30 |                       49 |                                       24% |                                   134 |                                    191 |
|           [Lithuania](/lithuania) |               86 |                       112 |                      40 |                         26 |                        9 |                                       31% |                                    93 |                                    151 |
|               [Estonia](/estonia) |               64 |                        72 |                      54 |                          8 |                        6 |                                       12% |                                    68 |                                     82 |
|             [Slovakia](/slovakia) |               33 |                        45 |                       8 |                         12 |                        2 |                                       38% |                                    35 |                                     69 |
|                 [Latvia](/latvia) |               34 |                        44 |                      23 |                         10 |                        5 |                                       31% |                                    36 |                                     62 |
|                 [Cyprus](/cyprus) |               20 |                        26 |                      30 |                          6 |                        7 |                                       31% |                                    22 |                                     32 |
|                   [Malta](/malta) |               10 |                        14 |                      29 |                          4 |                        9 |                                       43% |                                    12 |                                     19 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        7 |                                       23% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          442,306 |                   639,069 |                     123 |                    196,763 |                    2,546 |                                       44% |                               519,280 |                                827,621 |
|                             [Brazil](/brazil) |          120,262 |                   163,634 |                     775 |                     43,372 |                      206 |                                       36% |                               138,214 |                                201,001 |
|                               [India](/india) |           63,498 |                   114,977 |                      84 |                     51,479 |                       38 |                                       81% |                                83,572 |                                153,081 |
|                             [Mexico](/mexico) |           63,819 |                    88,757 |                     696 |                     24,938 |                      195 |                                       39% |                                76,802 |                                109,708 |
|                                 [Peru](/peru) |           28,471 |                    34,851 |                   1,072 |                      6,380 |                      196 |                                       22% |                                30,307 |                                 42,365 |
|                         [Colombia](/colombia) |           19,063 |                    30,965 |                     615 |                     11,902 |                      236 |                                       62% |                                24,212 |                                 41,708 |
|                                 [Iran](/iran) |           21,359 |                    27,157 |                     328 |                      5,798 |                       70 |                                       27% |                                23,125 |                                 33,961 |
|                             [Russia](/russia) |           16,977 |                    21,952 |                     150 |                      4,975 |                       34 |                                       29% |                                18,426 |                                 28,651 |
|                 [South Africa](/south-africa) |           13,981 |                    20,913 |                     357 |                      6,932 |                      118 |                                       50% |                                16,776 |                                 28,232 |
|                       [Argentina](/argentina) |            8,353 |                    18,918 |                     422 |                     10,565 |                      236 |                                      126% |                                12,462 |                                 27,844 |
|                               [Chile](/chile) |           11,181 |                    13,861 |                     731 |                      2,680 |                      141 |                                       24% |                                11,649 |                                 19,722 |
|                       [Indonesia](/indonesia) |            7,261 |                    12,285 |                      45 |                      5,024 |                       19 |                                       69% |                                 9,061 |                                 18,032 |
|                             [Canada](/canada) |            9,161 |                     9,524 |                     255 |                        363 |                       10 |                                        4% |                                 9,201 |                                 10,333 |
|                           [Bolivia](/bolivia) |            4,938 |                     7,888 |                     685 |                      2,950 |                      256 |                                       60% |                                 6,111 |                                 10,429 |
|                           [Ecuador](/ecuador) |            6,537 |                     7,740 |                     445 |                      1,203 |                       69 |                                       18% |                                 6,665 |                                 10,259 |
|                             [Turkey](/turkey) |            6,284 |                     7,589 |                      91 |                      1,305 |                       16 |                                       21% |                                 6,396 |                                 10,708 |
|                   [Philippines](/philippines) |            3,419 |                     7,466 |                      69 |                      4,047 |                       37 |                                      118% |                                 4,659 |                                 12,869 |
|                         [Pakistan](/pakistan) |            6,284 |                     6,847 |                      32 |                        563 |                        3 |                                        9% |                                 6,351 |                                  7,723 |
|                     [Bangladesh](/bangladesh) |            4,206 |                     6,050 |                      37 |                      1,844 |                       11 |                                       44% |                                 4,988 |                                  8,659 |
|                               [Egypt](/egypt) |            5,376 |                     5,891 |                      59 |                        515 |                        5 |                                       10% |                                 5,440 |                                  6,805 |
|                 [Saudi Arabia](/saudi-arabia) |            3,840 |                     5,381 |                     157 |                      1,541 |                       45 |                                       40% |                                 4,288 |                                  6,927 |
|                               [China](/china) |            4,721 |                     4,812 |                       3 |                         91 |                        0 |                                        2% |                                 4,721 |                                  5,489 |
|                           [Morocco](/morocco) |            1,078 |                     3,387 |                      93 |                      2,309 |                       63 |                                      214% |                                 1,881 |                                  6,224 |
|                         [Honduras](/honduras) |            1,842 |                     2,782 |                     285 |                        940 |                       96 |                                       51% |                                 2,145 |                                  3,934 |
|                             [Panama](/panama) |            1,983 |                     2,641 |                     622 |                        658 |                      155 |                                       33% |                                 2,250 |                                  3,393 |
|     [Dominican Republic](/dominican-republic) |            1,673 |                     2,617 |                     244 |                        944 |                       88 |                                       56% |                                 2,003 |                                  3,779 |
|                           [Algeria](/algeria) |            1,491 |                     2,145 |                      50 |                        654 |                       15 |                                       44% |                                 1,614 |                                  3,328 |
|                               [Japan](/japan) |            1,271 |                     2,101 |                      17 |                        830 |                        7 |                                       65% |                                 1,432 |                                  3,678 |
|                             [Israel](/israel) |              906 |                     1,874 |                     220 |                        968 |                      114 |                                      107% |                                 1,206 |                                  3,061 |
|                           [Nigeria](/nigeria) |            1,011 |                     1,235 |                       6 |                        224 |                        1 |                                       22% |                                 1,053 |                                  1,706 |
|                       [Australia](/australia) |              611 |                     1,025 |                      41 |                        414 |                       16 |                                       68% |                                   780 |                                  1,389 |
|                             [Kuwait](/kuwait) |              528 |                       677 |                     161 |                        149 |                       35 |                                       28% |                                   551 |                                    983 |
| [United Arab Emirates](/united-arab-emirates) |              379 |                       455 |                      47 |                         76 |                        8 |                                       20% |                                   383 |                                    644 |
|                   [South Korea](/south-korea) |              323 |                       397 |                       8 |                         74 |                        1 |                                       23% |                                   323 |                                    619 |
|                                 [Cuba](/cuba) |               94 |                       139 |                      12 |                         45 |                        4 |                                       47% |                                   105 |                                    226 |
|                         [Malaysia](/malaysia) |              125 |                       138 |                       4 |                         13 |                        0 |                                       10% |                                   128 |                                    151 |
