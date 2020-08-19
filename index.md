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

* **August 17:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 19 (2pm ET):
<p align="center">
  Current Total: <b>171,818</b> deaths | Projected Total: <b>224,800 deaths by Nov 1, 2020</b> (Range: 204-254k)<br>
  Currently Infected: <b>1.6%</b> (1 in 64) | Total Infected: <b>13.5%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 19, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              175,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |        <1% |         19% |        82% |         97% |        99% |
|              225,000 |        <1% |         <1% |         2% |         15% |        39% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         5% |
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
|             *[United States](/us)* |          171,818 |                   224,820 |                     678 |                     53,002 |                                       31% |                               204,300 |                                253,550 |
|                 [New York](/us-ny) |           32,857 |                    33,338 |                   1,714 |                        481 |                                        1% |                                32,873 |                                 35,610 |
|               [California](/us-ca) |           11,504 |                    18,683 |                     473 |                      7,179 |                                       62% |                                14,577 |                                 24,759 |
|                    [Texas](/us-tx) |           10,678 |                    18,443 |                     636 |                      7,765 |                                       73% |                                14,732 |                                 22,918 |
|                  [Florida](/us-fl) |            9,758 |                    16,801 |                     782 |                      7,043 |                                       72% |                                13,290 |                                 21,107 |
|               [New Jersey](/us-nj) |           15,925 |                    16,124 |                   1,815 |                        199 |                                        1% |                                15,943 |                                 16,696 |
|            [Massachusetts](/us-ma) |            8,848 |                     9,760 |                   1,404 |                        912 |                                       10% |                                 8,925 |                                 11,643 |
|                 [Illinois](/us-il) |            7,994 |                     9,402 |                     742 |                      1,408 |                                       18% |                                 8,175 |                                 12,076 |
|             [Pennsylvania](/us-pa) |            7,474 |                     8,641 |                     675 |                      1,167 |                                       16% |                                 7,575 |                                 10,976 |
|                  [Georgia](/us-ga) |            4,794 |                     7,574 |                     713 |                      2,780 |                                       58% |                                 6,096 |                                  9,794 |
|                 [Michigan](/us-mi) |            6,608 |                     7,301 |                     731 |                        693 |                                       10% |                                 6,670 |                                  8,548 |
|                  [Arizona](/us-az) |            4,529 |                     6,501 |                     893 |                      1,972 |                                       44% |                                 5,483 |                                  7,916 |
|                [Louisiana](/us-la) |            4,554 |                     5,774 |                   1,242 |                      1,220 |                                       27% |                                 5,069 |                                  6,772 |
|                     [Ohio](/us-oh) |            3,866 |                     5,450 |                     466 |                      1,584 |                                       41% |                                 4,376 |                                  7,215 |
|              [Connecticut](/us-ct) |            4,456 |                     4,552 |                   1,277 |                         96 |                                        2% |                                 4,470 |                                  4,798 |
|                 [Maryland](/us-md) |            3,650 |                     4,401 |                     728 |                        751 |                                       21% |                                 3,711 |                                  5,861 |
|                  [Indiana](/us-in) |            3,165 |                     4,204 |                     624 |                      1,039 |                                       33% |                                 3,285 |                                  5,817 |
|           [South Carolina](/us-sc) |            2,343 |                     3,927 |                     763 |                      1,584 |                                       68% |                                 3,103 |                                  5,011 |
|           [North Carolina](/us-nc) |            2,396 |                     3,863 |                     368 |                      1,467 |                                       61% |                                 2,986 |                                  5,279 |
|                 [Virginia](/us-va) |            2,396 |                     3,397 |                     398 |                      1,001 |                                       42% |                                 2,554 |                                  5,032 |
|              [Mississippi](/us-ms) |            2,127 |                     3,176 |                   1,067 |                      1,049 |                                       49% |                                 2,611 |                                  3,909 |
|                  [Alabama](/us-al) |            1,936 |                     2,887 |                     589 |                        951 |                                       49% |                                 2,361 |                                  3,617 |
|               [Washington](/us-wa) |            1,808 |                     2,847 |                     374 |                      1,039 |                                       57% |                                 2,126 |                                  4,144 |
|                [Tennessee](/us-tn) |            1,424 |                     2,632 |                     385 |                      1,208 |                                       85% |                                 1,964 |                                  3,606 |
|                 [Colorado](/us-co) |            1,899 |                     2,321 |                     403 |                        422 |                                       22% |                                 1,939 |                                  3,092 |
|                [Minnesota](/us-mn) |            1,767 |                     2,306 |                     409 |                        539 |                                       31% |                                 1,856 |                                  3,179 |
|                 [Missouri](/us-mo) |            1,425 |                     2,139 |                     348 |                        714 |                                       50% |                                 1,676 |                                  2,899 |
|                   [Nevada](/us-nv) |            1,102 |                     1,899 |                     616 |                        797 |                                       72% |                                 1,478 |                                  2,429 |
|                [Wisconsin](/us-wi) |            1,039 |                     1,549 |                     266 |                        510 |                                       49% |                                 1,208 |                                  2,186 |
|                     [Iowa](/us-ia) |            1,002 |                     1,481 |                     469 |                        479 |                                       48% |                                 1,153 |                                  2,008 |
|                 [Kentucky](/us-ky) |              830 |                     1,292 |                     289 |                        462 |                                       56% |                                   984 |                                  1,808 |
|                 [Oklahoma](/us-ok) |              679 |                     1,241 |                     314 |                        562 |                                       83% |                                   898 |                                  1,776 |
|                 [Arkansas](/us-ar) |              619 |                     1,139 |                     377 |                        520 |                                       84% |                                   843 |                                  1,561 |
|             [Rhode Island](/us-ri) |            1,024 |                     1,108 |                   1,045 |                         84 |                                        8% |                                 1,036 |                                  1,262 |
|               [New Mexico](/us-nm) |              723 |                     1,032 |                     492 |                        309 |                                       43% |                                   832 |                                  1,392 |
|              [Puerto Rico](/us-pr) |              346 |                       973 |                     305 |                        627 |                                      181% |                                   600 |                                  1,556 |
|                   [Oregon](/us-or) |              397 |                       777 |                     184 |                        380 |                                       96% |                                   531 |                                  1,168 |
|                 [Delaware](/us-de) |              593 |                       678 |                     696 |                         85 |                                       14% |                                   602 |                                    834 |
|                   [Kansas](/us-ks) |              411 |                       672 |                     231 |                        261 |                                       64% |                                   503 |                                    978 |
|     [District of Columbia](/us-dc) |              599 |                       652 |                     924 |                         53 |                                        9% |                                   609 |                                    743 |
|                     [Utah](/us-ut) |              369 |                       645 |                     201 |                        276 |                                       75% |                                   473 |                                    939 |
|                    [Idaho](/us-id) |              282 |                       619 |                     346 |                        337 |                                      120% |                                   437 |                                    870 |
|                 [Nebraska](/us-ne) |              369 |                       530 |                     274 |                        161 |                                       44% |                                   431 |                                    743 |
|            [New Hampshire](/us-nh) |              424 |                       491 |                     361 |                         67 |                                       16% |                                   428 |                                    647 |
|            [West Virginia](/us-wv) |              162 |                       406 |                     227 |                        244 |                                      151% |                                   253 |                                    666 |
|             [North Dakota](/us-nd) |              128 |                       234 |                     307 |                        106 |                                       83% |                                   168 |                                    345 |
|             [South Dakota](/us-sd) |              154 |                       230 |                     260 |                         76 |                                       49% |                                   182 |                                    322 |
|                  [Montana](/us-mt) |               84 |                       214 |                     200 |                        130 |                                      155% |                                   134 |                                    342 |
|                    [Maine](/us-me) |              127 |                       154 |                     115 |                         27 |                                       21% |                                   132 |                                    196 |
|                   [Hawaii](/us-hi) |               41 |                       149 |                     105 |                        108 |                                      263% |                                    75 |                                    291 |
|                  [Vermont](/us-vt) |               58 |                        73 |                     117 |                         15 |                                       26% |                                    61 |                                    101 |
|                   [Alaska](/us-ak) |               29 |                        64 |                      88 |                         35 |                                      121% |                                    42 |                                    105 |
|                  [Wyoming](/us-wy) |               30 |                        47 |                      81 |                         17 |                                       57% |                                    36 |                                     62 |
|           [Virgin Islands](/us-vi) |                9 |                        17 |                     163 |                          8 |                                       90% |                                    12 |                                     26 |
|                     [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     5 |                                     14 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       54% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,414 |                   201,781 |                     340 |                     15,367 |                                        8% |                               189,800 |                                236,964 |
| [United Kingdom](/united-kingdom) |           41,466 |                    42,505 |                     629 |                      1,039 |                                        3% |                                41,499 |                                 46,417 |
|                   [Italy](/italy) |           35,405 |                    36,057 |                     597 |                        652 |                                        2% |                                35,430 |                                 38,474 |
|                 [France](/france) |           30,434 |                    31,455 |                     469 |                      1,021 |                                        3% |                                30,478 |                                 35,871 |
|                   [Spain](/spain) |           28,670 |                    29,893 |                     637 |                      1,223 |                                        4% |                                28,705 |                                 34,387 |
|               [Belgium](/belgium) |            9,959 |                    10,552 |                     921 |                        593 |                                        6% |                                10,003 |                                 12,866 |
|               [Germany](/germany) |            9,241 |                     9,966 |                     120 |                        725 |                                        8% |                                 9,291 |                                 12,282 |
|       [Netherlands](/netherlands) |            6,197 |                     6,553 |                     379 |                        356 |                                        6% |                                 6,222 |                                  7,948 |
|               [Romania](/romania) |            3,074 |                     6,293 |                     324 |                      3,219 |                                      105% |                                 4,256 |                                  9,896 |
|                 [Sweden](/sweden) |            5,790 |                     5,943 |                     581 |                        153 |                                        3% |                                 5,816 |                                  6,044 |
|               [Ukraine](/ukraine) |            2,152 |                     4,621 |                     105 |                      2,469 |                                      115% |                                 2,946 |                                  8,288 |
|                 [Poland](/poland) |            1,896 |                     2,864 |                      75 |                        968 |                                       51% |                                 2,165 |                                  4,359 |
|       [Switzerland](/switzerland) |            1,992 |                     2,123 |                     247 |                        131 |                                        7% |                                 2,011 |                                  2,497 |
|             [Portugal](/portugal) |            1,784 |                     2,047 |                     199 |                        263 |                                       15% |                                 1,794 |                                  2,634 |
|               [Ireland](/ireland) |            1,775 |                     1,854 |                     378 |                         79 |                                        4% |                                 1,785 |                                  2,086 |
|               [Moldova](/moldova) |              908 |                     1,326 |                     328 |                        418 |                                       46% |                                 1,070 |                                  1,889 |
|             [Bulgaria](/bulgaria) |              519 |                     1,097 |                     157 |                        578 |                                      111% |                                   718 |                                  2,028 |
|                 [Serbia](/serbia) |              681 |                       980 |                     141 |                        299 |                                       44% |                                   802 |                                  1,261 |
|               [Austria](/austria) |              729 |                       820 |                      93 |                         91 |                                       13% |                                   742 |                                  1,056 |
|               [Belarus](/belarus) |              617 |                       809 |                      86 |                        192 |                                       31% |                                   730 |                                    986 |
|               [Denmark](/denmark) |              621 |                       708 |                     122 |                         87 |                                       14% |                                   639 |                                    928 |
|               [Hungary](/hungary) |              609 |                       690 |                      71 |                         81 |                                       13% |                                   616 |                                    890 |
|               [Czechia](/czechia) |              401 |                       557 |                      52 |                        156 |                                       39% |                                   431 |                                    852 |
|                 [Greece](/greece) |              232 |                       471 |                      44 |                        239 |                                      103% |                                   302 |                                    826 |
|               [Finland](/finland) |              334 |                       373 |                      68 |                         39 |                                       12% |                                   341 |                                    481 |
|                 [Norway](/norway) |              262 |                       315 |                      58 |                         53 |                                       20% |                                   275 |                                    434 |
|               [Croatia](/croatia) |              166 |                       267 |                      65 |                        101 |                                       61% |                                   198 |                                    405 |
|         [Luxembourg](/luxembourg) |              124 |                       173 |                     281 |                         49 |                                       39% |                                   139 |                                    245 |
|             [Slovenia](/slovenia) |              129 |                       163 |                      78 |                         34 |                                       26% |                                   134 |                                    223 |
|           [Lithuania](/lithuania) |               81 |                        94 |                      34 |                         13 |                                       16% |                                    84 |                                    120 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     79 |
|                 [Latvia](/latvia) |               33 |                        45 |                      23 |                         12 |                                       37% |                                    35 |                                     66 |
|             [Slovakia](/slovakia) |               31 |                        43 |                       8 |                         12 |                                       40% |                                    33 |                                     70 |
|                 [Cyprus](/cyprus) |               20 |                        29 |                      34 |                          9 |                                       47% |                                    23 |                                     43 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                                       27% |                                    10 |                                     18 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       29% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          396,612 |                   657,643 |                     127 |                    261,031 |                                       66% |                               496,308 |                                939,447 |
|                             [Brazil](/brazil) |          109,888 |                   172,045 |                     815 |                     62,157 |                                       57% |                               129,100 |                                239,110 |
|                               [India](/india) |           52,888 |                   120,997 |                      89 |                     68,109 |                                      129% |                                78,872 |                                179,031 |
|                             [Mexico](/mexico) |           57,774 |                    96,523 |                     757 |                     38,749 |                                       67% |                                82,005 |                                129,451 |
|                                 [Peru](/peru) |           26,481 |                    36,369 |                   1,119 |                      9,888 |                                       37% |                                29,572 |                                 47,987 |
|                         [Colombia](/colombia) |           15,619 |                    30,297 |                     602 |                     14,678 |                                       94% |                                21,987 |                                 45,601 |
|                                 [Iran](/iran) |           19,972 |                    27,820 |                     336 |                      7,848 |                                       39% |                                22,759 |                                 37,301 |
|                 [South Africa](/south-africa) |           12,264 |                    22,266 |                     380 |                     10,002 |                                       82% |                                15,911 |                                 32,147 |
|                             [Russia](/russia) |           15,836 |                    21,772 |                     149 |                      5,936 |                                       37% |                                17,684 |                                 30,540 |
|                       [Argentina](/argentina) |            6,048 |                    16,227 |                     362 |                     10,179 |                                      168% |                                 9,798 |                                 27,031 |
|                               [Chile](/chile) |           10,546 |                    14,296 |                     754 |                      3,750 |                                       36% |                                11,173 |                                 22,529 |
|                       [Indonesia](/indonesia) |            6,277 |                    10,730 |                      40 |                      4,453 |                                       71% |                                 7,882 |                                 17,503 |
|                             [Canada](/canada) |            9,090 |                     9,507 |                     254 |                        417 |                                        5% |                                 9,125 |                                 10,503 |
|                             [Turkey](/turkey) |            6,016 |                     7,442 |                      89 |                      1,426 |                                       24% |                                 6,125 |                                 11,132 |
|                           [Ecuador](/ecuador) |            6,105 |                     7,369 |                     424 |                      1,264 |                                       21% |                                 6,246 |                                 10,167 |
|                           [Bolivia](/bolivia) |            4,172 |                     7,053 |                     613 |                      2,881 |                                       69% |                                 5,263 |                                 10,586 |
|                         [Pakistan](/pakistan) |            6,190 |                     6,992 |                      32 |                        802 |                                       13% |                                 6,311 |                                  8,114 |
|                   [Philippines](/philippines) |            2,687 |                     6,220 |                      58 |                      3,533 |                                      131% |                                 3,666 |                                 11,946 |
|                               [Egypt](/egypt) |            5,184 |                     5,866 |                      58 |                        682 |                                       13% |                                 5,292 |                                  6,979 |
|                     [Bangladesh](/bangladesh) |            3,740 |                     5,720 |                      35 |                      1,980 |                                       53% |                                 4,224 |                                  8,847 |
|                 [Saudi Arabia](/saudi-arabia) |            3,470 |                     5,161 |                     151 |                      1,691 |                                       49% |                                 4,004 |                                  7,123 |
|                               [China](/china) |            4,705 |                     4,904 |                       3 |                        199 |                                        4% |                                 4,705 |                                  6,290 |
|                           [Morocco](/morocco) |              714 |                     3,378 |                      93 |                      2,664 |                                      373% |                                 1,524 |                                  7,261 |
|                             [Panama](/panama) |            1,809 |                     2,800 |                     659 |                        991 |                                       55% |                                 2,183 |                                  3,928 |
|     [Dominican Republic](/dominican-republic) |            1,489 |                     2,677 |                     249 |                      1,188 |                                       80% |                                 1,882 |                                  4,318 |
|                         [Honduras](/honduras) |            1,593 |                     2,599 |                     267 |                      1,006 |                                       63% |                                 1,954 |                                  3,835 |
|                               [Japan](/japan) |            1,135 |                     2,248 |                      18 |                      1,113 |                                       98% |                                 1,240 |                                  5,763 |
|                           [Algeria](/algeria) |            1,391 |                     2,170 |                      50 |                        779 |                                       56% |                                 1,566 |                                  3,551 |
|                             [Israel](/israel) |              708 |                     1,567 |                     184 |                        859 |                                      121% |                                   983 |                                  2,890 |
|                       [Australia](/australia) |              450 |                     1,508 |                      60 |                      1,058 |                                      235% |                                   785 |                                  3,103 |
|                           [Nigeria](/nigeria) |              981 |                     1,297 |                       6 |                        316 |                                       32% |                                 1,043 |                                  2,009 |
|                             [Kuwait](/kuwait) |              505 |                       748 |                     178 |                        243 |                                       48% |                                   542 |                                  1,297 |
| [United Arab Emirates](/united-arab-emirates) |              366 |                       455 |                      47 |                         89 |                                       24% |                                   372 |                                    686 |
|                   [South Korea](/south-korea) |              306 |                       356 |                       7 |                         50 |                                       16% |                                   306 |                                    522 |
|                         [Malaysia](/malaysia) |              125 |                       140 |                       4 |                         15 |                                       12% |                                   129 |                                    156 |
|                                 [Cuba](/cuba) |               88 |                       126 |                      11 |                         38 |                                       43% |                                    95 |                                    210 |
