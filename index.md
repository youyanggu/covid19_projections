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

* **September 28:** We will no longer be extending our projections past November 1. Our last forecast update will be on Monday, October 5. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later).
* *September 22:* [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1308498742451015680).
* *September 20:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 29 (2am ET):
<p align="center">
  Current Total: <b>205,069</b> deaths | Projected Total: <b>229,600 deaths by Nov 1, 2020</b> (Range: 218-248k)<br>
  Currently Infected: <b>1.2%</b> (1 in 80) | Total Infected: <b>16.3%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 28, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |          1% |        62% |
|              250,000 |        <1% |         <1% |         2% |
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
|             *[United States](/us)* |          205,069 |                   229,601 |                     692 |                     24,532 |                       74 |                                       12% |                               218,852 |                                247,045 |
|                 [New York](/us-ny) |           33,140 |                    33,556 |                   1,725 |                        416 |                       21 |                                        1% |                                33,151 |                                 35,793 |
|                    [Texas](/us-tx) |           15,807 |                    18,687 |                     644 |                      2,880 |                       99 |                                       18% |                                16,958 |                                 21,467 |
|               [California](/us-ca) |           15,633 |                    18,381 |                     465 |                      2,748 |                       70 |                                       18% |                                16,628 |                                 21,819 |
|                  [Florida](/us-fl) |           14,037 |                    16,705 |                     778 |                      2,668 |                      124 |                                       19% |                                15,121 |                                 19,302 |
|               [New Jersey](/us-nj) |           16,107 |                    16,372 |                   1,843 |                        265 |                       30 |                                        2% |                                16,115 |                                 17,253 |
|            [Massachusetts](/us-ma) |            9,415 |                     9,800 |                   1,410 |                        385 |                       55 |                                        4% |                                 9,450 |                                 10,508 |
|                 [Illinois](/us-il) |            8,858 |                     9,609 |                     758 |                        751 |                       59 |                                        8% |                                 8,995 |                                 10,964 |
|             [Pennsylvania](/us-pa) |            8,088 |                     8,832 |                     690 |                        744 |                       58 |                                        9% |                                 8,169 |                                 10,011 |
|                  [Georgia](/us-ga) |            6,961 |                     8,346 |                     786 |                      1,385 |                      130 |                                       20% |                                 7,501 |                                  9,825 |
|                 [Michigan](/us-mi) |            7,051 |                     7,421 |                     743 |                        370 |                       37 |                                        5% |                                 7,095 |                                  8,186 |
|                  [Arizona](/us-az) |            5,624 |                     6,265 |                     861 |                        641 |                       88 |                                       11% |                                 5,796 |                                  7,242 |
|                [Louisiana](/us-la) |            5,480 |                     5,976 |                   1,286 |                        496 |                      107 |                                        9% |                                 5,631 |                                  6,652 |
|                     [Ohio](/us-oh) |            4,746 |                     5,550 |                     475 |                        804 |                       69 |                                       17% |                                 4,943 |                                  6,788 |
|              [Connecticut](/us-ct) |            4,503 |                     4,609 |                   1,293 |                        106 |                       30 |                                        2% |                                 4,511 |                                  4,919 |
|           [North Carolina](/us-nc) |            3,445 |                     4,419 |                     421 |                        974 |                       93 |                                       28% |                                 3,846 |                                  5,435 |
|                 [Maryland](/us-md) |            3,938 |                     4,215 |                     697 |                        277 |                       46 |                                        7% |                                 3,970 |                                  4,741 |
|                  [Indiana](/us-in) |            3,591 |                     4,037 |                     600 |                        446 |                       66 |                                       12% |                                 3,625 |                                  4,866 |
|           [South Carolina](/us-sc) |            3,337 |                     3,899 |                     757 |                        562 |                      109 |                                       17% |                                 3,585 |                                  4,396 |
|                 [Virginia](/us-va) |            3,170 |                     3,871 |                     454 |                        701 |                       82 |                                       22% |                                 3,355 |                                  4,807 |
|              [Mississippi](/us-ms) |            2,921 |                     3,333 |                   1,120 |                        412 |                      138 |                                       14% |                                 3,062 |                                  3,874 |
|                [Tennessee](/us-tn) |            2,389 |                     3,045 |                     446 |                        656 |                       96 |                                       27% |                                 2,661 |                                  3,726 |
|                  [Alabama](/us-al) |            2,501 |                     2,844 |                     580 |                        343 |                       70 |                                       14% |                                 2,616 |                                  3,255 |
|                 [Missouri](/us-mo) |            2,057 |                     2,783 |                     453 |                        726 |                      118 |                                       35% |                                 2,357 |                                  3,445 |
|               [Washington](/us-wa) |            2,100 |                     2,467 |                     324 |                        367 |                       48 |                                       17% |                                 2,151 |                                  3,104 |
|                [Minnesota](/us-mn) |            2,067 |                     2,389 |                     424 |                        322 |                       57 |                                       16% |                                 2,122 |                                  2,849 |
|                 [Colorado](/us-co) |            2,044 |                     2,226 |                     387 |                        182 |                       32 |                                        9% |                                 2,057 |                                  2,602 |
|                   [Nevada](/us-nv) |            1,585 |                     1,801 |                     585 |                        216 |                       70 |                                       14% |                                 1,654 |                                  2,067 |
|                 [Arkansas](/us-ar) |            1,329 |                     1,776 |                     588 |                        447 |                      148 |                                       34% |                                 1,532 |                                  2,198 |
|                     [Iowa](/us-ia) |            1,324 |                     1,598 |                     506 |                        274 |                       87 |                                       21% |                                 1,413 |                                  1,952 |
|                [Wisconsin](/us-wi) |            1,283 |                     1,587 |                     273 |                        304 |                       52 |                                       24% |                                 1,395 |                                  1,907 |
|                 [Kentucky](/us-ky) |            1,162 |                     1,466 |                     328 |                        304 |                       68 |                                       26% |                                 1,266 |                                  1,823 |
|                 [Oklahoma](/us-ok) |            1,007 |                     1,311 |                     331 |                        304 |                       77 |                                       30% |                                 1,142 |                                  1,603 |
|             [Rhode Island](/us-ri) |            1,110 |                     1,199 |                   1,132 |                         89 |                       84 |                                        8% |                                 1,118 |                                  1,374 |
|               [New Mexico](/us-nm) |              873 |                     1,024 |                     488 |                        151 |                       72 |                                       17% |                                   918 |                                  1,238 |
|              [Puerto Rico](/us-pr) |              648 |                       902 |                     282 |                        254 |                       80 |                                       39% |                                   760 |                                  1,150 |
|                   [Kansas](/us-ks) |              644 |                       865 |                     297 |                        221 |                       76 |                                       34% |                                   723 |                                  1,111 |
|                   [Oregon](/us-or) |              547 |                       699 |                     166 |                        152 |                       36 |                                       28% |                                   600 |                                    865 |
|                 [Delaware](/us-de) |              634 |                       679 |                     697 |                         45 |                       46 |                                        7% |                                   640 |                                    768 |
|     [District of Columbia](/us-dc) |              624 |                       642 |                     910 |                         18 |                       25 |                                        3% |                                   627 |                                    679 |
|                 [Nebraska](/us-ne) |              472 |                       589 |                     305 |                        117 |                       61 |                                       25% |                                   510 |                                    730 |
|                    [Idaho](/us-id) |              460 |                       564 |                     316 |                        104 |                       58 |                                       23% |                                   506 |                                    662 |
|                     [Utah](/us-ut) |              453 |                       551 |                     172 |                         98 |                       31 |                                       22% |                                   488 |                                    646 |
|            [West Virginia](/us-wv) |              342 |                       515 |                     287 |                        173 |                       97 |                                       51% |                                   412 |                                    715 |
|             [North Dakota](/us-nd) |              234 |                       473 |                     620 |                        239 |                      313 |                                      102% |                                   346 |                                    677 |
|            [New Hampshire](/us-nh) |              439 |                       449 |                     330 |                         10 |                        8 |                                        2% |                                   440 |                                    489 |
|             [South Dakota](/us-sd) |              218 |                       317 |                     359 |                         99 |                      112 |                                       46% |                                   245 |                                    445 |
|                  [Montana](/us-mt) |              174 |                       294 |                     275 |                        120 |                      112 |                                       69% |                                   231 |                                    399 |
|                   [Hawaii](/us-hi) |              132 |                       203 |                     143 |                         71 |                       50 |                                       53% |                                   162 |                                    283 |
|                    [Maine](/us-me) |              140 |                       152 |                     113 |                         12 |                        9 |                                        9% |                                   142 |                                    174 |
|                   [Alaska](/us-ak) |               56 |                        89 |                     122 |                         33 |                       46 |                                       59% |                                    72 |                                    123 |
|                     [Guam](/us-gu) |               39 |                        66 |                     397 |                         27 |                      162 |                                       69% |                                    51 |                                     90 |
|                  [Wyoming](/us-wy) |               50 |                        65 |                     112 |                         15 |                       26 |                                       30% |                                    56 |                                     81 |
|                  [Vermont](/us-vt) |               58 |                        60 |                      95 |                          2 |                        2 |                                        3% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               20 |                        24 |                     227 |                          4 |                       36 |                                       19% |                                    21 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       11 |                                       29% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          198,278 |                   222,175 |                     375 |                     23,897 |                       40 |                                       12% |                               202,051 |                                288,667 |
| [United Kingdom](/united-kingdom) |           42,090 |                    45,228 |                     670 |                      3,138 |                       46 |                                        7% |                                42,179 |                                 57,085 |
|                   [Italy](/italy) |           35,851 |                    36,845 |                     610 |                        994 |                       16 |                                        3% |                                35,872 |                                 40,309 |
|                   [Spain](/spain) |           31,411 |                    36,584 |                     779 |                      5,173 |                      110 |                                       16% |                                31,851 |                                 49,598 |
|                 [France](/france) |           31,744 |                    36,280 |                     541 |                      4,536 |                       68 |                                       14% |                                31,796 |                                 58,400 |
|               [Belgium](/belgium) |            9,987 |                    10,498 |                     916 |                        511 |                       45 |                                        5% |                                10,012 |                                 12,520 |
|               [Germany](/germany) |            9,468 |                    10,000 |                     120 |                        532 |                        6 |                                        6% |                                 9,480 |                                 12,044 |
|       [Netherlands](/netherlands) |            6,415 |                     7,255 |                     420 |                        840 |                       49 |                                       13% |                                 6,464 |                                  9,644 |
|               [Ukraine](/ukraine) |            4,082 |                     6,350 |                     144 |                      2,268 |                       52 |                                       56% |                                 5,122 |                                  8,062 |
|               [Romania](/romania) |            4,748 |                     6,161 |                     317 |                      1,413 |                       73 |                                       30% |                                 5,348 |                                  7,605 |
|                 [Sweden](/sweden) |            5,880 |                     6,006 |                     587 |                        126 |                       12 |                                        2% |                                 5,888 |                                  6,446 |
|                 [Poland](/poland) |            2,447 |                     3,355 |                      88 |                        908 |                       24 |                                       37% |                                 2,688 |                                  4,669 |
|             [Portugal](/portugal) |            1,957 |                     2,252 |                     219 |                        295 |                       29 |                                       15% |                                 2,026 |                                  2,621 |
|       [Switzerland](/switzerland) |            2,065 |                     2,206 |                     257 |                        141 |                       16 |                                        7% |                                 2,096 |                                  2,457 |
|               [Ireland](/ireland) |            1,802 |                     1,911 |                     390 |                        109 |                       22 |                                        6% |                                 1,810 |                                  2,350 |
|               [Moldova](/moldova) |            1,301 |                     1,681 |                     416 |                        380 |                       94 |                                       29% |                                 1,451 |                                  2,043 |
|               [Czechia](/czechia) |              618 |                     1,426 |                     134 |                        808 |                       76 |                                      131% |                                   938 |                                  2,385 |
|               [Hungary](/hungary) |              749 |                     1,115 |                     114 |                        366 |                       37 |                                       49% |                                   923 |                                  1,421 |
|               [Belarus](/belarus) |              822 |                     1,048 |                     111 |                        226 |                       24 |                                       27% |                                   888 |                                  1,370 |
|             [Bulgaria](/bulgaria) |              807 |                     1,001 |                     143 |                        194 |                       28 |                                       24% |                                   896 |                                  1,179 |
|               [Austria](/austria) |              790 |                       948 |                     107 |                        158 |                       18 |                                       20% |                                   823 |                                  1,215 |
|               [Denmark](/denmark) |              649 |                       773 |                     133 |                        124 |                       21 |                                       19% |                                   665 |                                  1,109 |
|                 [Serbia](/serbia) |              748 |                       769 |                     110 |                         21 |                        3 |                                        3% |                                   752 |                                    825 |
|                 [Greece](/greece) |              383 |                       667 |                      62 |                        284 |                       26 |                                       74% |                                   490 |                                  1,035 |
|               [Finland](/finland) |              345 |                       381 |                      69 |                         36 |                        6 |                                       10% |                                   357 |                                    434 |
|               [Croatia](/croatia) |              272 |                       362 |                      89 |                         90 |                       22 |                                       33% |                                   302 |                                    500 |
|                 [Norway](/norway) |              274 |                       313 |                      58 |                         39 |                        7 |                                       14% |                                   287 |                                    354 |
|             [Slovenia](/slovenia) |              149 |                       193 |                      93 |                         44 |                       21 |                                       30% |                                   167 |                                    240 |
|         [Luxembourg](/luxembourg) |              124 |                       137 |                     224 |                         13 |                       22 |                                       11% |                                   127 |                                    161 |
|           [Lithuania](/lithuania) |               92 |                       117 |                      42 |                         25 |                        9 |                                       27% |                                   102 |                                    141 |
|                   [Malta](/malta) |               32 |                        85 |                     171 |                         53 |                      107 |                                      164% |                                    53 |                                    161 |
|               [Estonia](/estonia) |               64 |                        78 |                      59 |                         14 |                       10 |                                       21% |                                    70 |                                     89 |
|             [Slovakia](/slovakia) |               44 |                        71 |                      13 |                         27 |                        5 |                                       60% |                                    56 |                                    100 |
|                 [Latvia](/latvia) |               36 |                        43 |                      23 |                          7 |                        4 |                                       21% |                                    39 |                                     50 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      29 |                          3 |                        3 |                                       14% |                                    23 |                                     29 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                        8 |                                       27% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          561,121 |                   678,069 |                     131 |                    116,948 |                       23 |                                       21% |                               609,031 |                                780,354 |
|                             [Brazil](/brazil) |          142,058 |                   159,341 |                     755 |                     17,283 |                       82 |                                       12% |                               149,408 |                                173,702 |
|                               [India](/india) |           96,318 |                   134,230 |                      98 |                     37,912 |                       28 |                                       39% |                               111,891 |                                156,703 |
|                             [Mexico](/mexico) |           76,603 |                    88,480 |                     694 |                     11,877 |                       93 |                                       16% |                                84,041 |                                 95,665 |
|                                 [Peru](/peru) |           32,262 |                    35,497 |                   1,092 |                      3,235 |                      100 |                                       10% |                                32,945 |                                 39,401 |
|                                 [Iran](/iran) |           25,779 |                    31,643 |                     382 |                      5,864 |                       71 |                                       23% |                                28,663 |                                 36,243 |
|                         [Colombia](/colombia) |           25,641 |                    29,932 |                     595 |                      4,291 |                       85 |                                       17% |                                27,328 |                                 34,038 |
|                       [Argentina](/argentina) |           16,113 |                    26,739 |                     597 |                     10,626 |                      237 |                                       66% |                                20,294 |                                 37,430 |
|                             [Russia](/russia) |           20,299 |                    24,626 |                     169 |                      4,327 |                       30 |                                       21% |                                20,952 |                                 30,841 |
|                 [South Africa](/south-africa) |           16,586 |                    18,188 |                     311 |                      1,602 |                       27 |                                       10% |                                17,319 |                                 20,366 |
|                       [Indonesia](/indonesia) |           10,473 |                    14,728 |                      54 |                      4,255 |                       16 |                                       41% |                                13,103 |                                 19,077 |
|                               [Chile](/chile) |           12,698 |                    14,531 |                     767 |                      1,833 |                       97 |                                       14% |                                12,882 |                                 18,688 |
|                           [Ecuador](/ecuador) |           11,280 |                    12,238 |                     704 |                        958 |                       55 |                                        8% |                                11,349 |                                 13,893 |
|                             [Turkey](/turkey) |            8,062 |                    10,575 |                     127 |                      2,513 |                       30 |                                       31% |                                 8,488 |                                 14,082 |
|                             [Canada](/canada) |            9,328 |                    10,092 |                     270 |                        764 |                       20 |                                        8% |                                 9,413 |                                 12,046 |
|                           [Bolivia](/bolivia) |            7,900 |                     8,770 |                     762 |                        870 |                       76 |                                       11% |                                 8,250 |                                  9,334 |
|                   [Philippines](/philippines) |            5,381 |                     7,467 |                      69 |                      2,086 |                       19 |                                       39% |                                 6,258 |                                  9,339 |
|                         [Pakistan](/pakistan) |            6,474 |                     6,740 |                      31 |                        266 |                        1 |                                        4% |                                 6,518 |                                  7,188 |
|                               [Egypt](/egypt) |            5,901 |                     6,533 |                      65 |                        632 |                        6 |                                       11% |                                 5,986 |                                  7,858 |
|                     [Bangladesh](/bangladesh) |            5,193 |                     6,156 |                      38 |                        963 |                        6 |                                       19% |                                 5,614 |                                  7,386 |
|                 [Saudi Arabia](/saudi-arabia) |            4,712 |                     5,564 |                     162 |                        852 |                       25 |                                       18% |                                 4,938 |                                  6,488 |
|                               [China](/china) |            4,739 |                     4,759 |                       3 |                         20 |                        0 |                                        0% |                                 4,739 |                                  4,917 |
|                           [Morocco](/morocco) |            2,113 |                     3,470 |                      95 |                      1,357 |                       37 |                                       64% |                                 2,671 |                                  4,619 |
|                         [Honduras](/honduras) |            2,301 |                     2,751 |                     282 |                        450 |                       46 |                                       20% |                                 2,430 |                                  3,245 |
|                             [Panama](/panama) |            2,348 |                     2,630 |                     619 |                        282 |                       66 |                                       12% |                                 2,458 |                                  2,921 |
|                             [Israel](/israel) |            1,507 |                     2,335 |                     274 |                        828 |                       97 |                                       55% |                                 1,800 |                                  3,433 |
|     [Dominican Republic](/dominican-republic) |            2,098 |                     2,289 |                     213 |                        191 |                       18 |                                        9% |                                 2,163 |                                  2,491 |
|                           [Algeria](/algeria) |            1,719 |                     1,838 |                      43 |                        119 |                        3 |                                        7% |                                 1,746 |                                  2,007 |
|                               [Japan](/japan) |            1,561 |                     1,760 |                      14 |                        199 |                        2 |                                       13% |                                 1,622 |                                  1,973 |
|                           [Nigeria](/nigeria) |            1,111 |                     1,198 |                       6 |                         87 |                        0 |                                        8% |                                 1,123 |                                  1,395 |
|                       [Australia](/australia) |              882 |                       965 |                      38 |                         83 |                        3 |                                        9% |                                   907 |                                  1,053 |
|                             [Kuwait](/kuwait) |              605 |                       695 |                     165 |                         90 |                       21 |                                       15% |                                   621 |                                    845 |
| [United Arab Emirates](/united-arab-emirates) |              413 |                       505 |                      52 |                         92 |                        9 |                                       22% |                                   418 |                                    676 |
|                   [South Korea](/south-korea) |              407 |                       495 |                      10 |                         88 |                        2 |                                       22% |                                   423 |                                    625 |
|                         [Malaysia](/malaysia) |              134 |                       156 |                       5 |                         22 |                        1 |                                       16% |                                   140 |                                    185 |
|                                 [Cuba](/cuba) |              122 |                       155 |                      14 |                         33 |                        3 |                                       27% |                                   130 |                                    201 |
