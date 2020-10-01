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

* **September 28 - MAJOR ANNOUNCEMENT:** We will no longer be extending our projections past November 1. Our last forecast update will be on Monday, October 5. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later). Thank you for your support over the past six months.
* **September 30:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1311384211983675397).
* *September 29:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: October 1 (3am ET):
<p align="center">
  Current Total: <b>206,929</b> deaths | Projected Total: <b>230,600 deaths by Nov 1, 2020</b> (Range: 220-248k)<br>
  Currently Infected: <b>1.2%</b> (1 in 90) | Total Infected: <b>16.0%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: October 1, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |          1% |        70% |
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
|             *[United States](/us)* |          206,929 |                   230,648 |                     695 |                     23,719 |                       71 |                                       11% |                               220,101 |                                247,770 |
|                 [New York](/us-ny) |           33,153 |                    33,555 |                   1,725 |                        402 |                       21 |                                        1% |                                33,164 |                                 35,605 |
|                    [Texas](/us-tx) |           16,016 |                    18,764 |                     647 |                      2,748 |                       95 |                                       17% |                                17,141 |                                 21,421 |
|               [California](/us-ca) |           15,885 |                    18,338 |                     464 |                      2,453 |                       62 |                                       15% |                                16,486 |                                 22,426 |
|                  [Florida](/us-fl) |           14,317 |                    17,284 |                     805 |                      2,967 |                      138 |                                       21% |                                15,437 |                                 20,365 |
|               [New Jersey](/us-nj) |           16,122 |                    16,378 |                   1,844 |                        256 |                       29 |                                        2% |                                16,130 |                                 17,203 |
|            [Massachusetts](/us-ma) |            9,456 |                     9,811 |                   1,412 |                        355 |                       51 |                                        4% |                                 9,469 |                                 10,709 |
|                 [Illinois](/us-il) |            8,916 |                     9,634 |                     760 |                        718 |                       57 |                                        8% |                                 9,061 |                                 10,737 |
|             [Pennsylvania](/us-pa) |            8,130 |                     8,832 |                     690 |                        702 |                       55 |                                        9% |                                 8,209 |                                  9,952 |
|                  [Georgia](/us-ga) |            7,021 |                     8,118 |                     765 |                      1,097 |                      103 |                                       16% |                                 7,410 |                                  9,531 |
|                 [Michigan](/us-mi) |            7,083 |                     7,441 |                     745 |                        358 |                       36 |                                        5% |                                 7,132 |                                  8,014 |
|                  [Arizona](/us-az) |            5,650 |                     6,250 |                     859 |                        600 |                       82 |                                       11% |                                 5,809 |                                  7,133 |
|                [Louisiana](/us-la) |            5,511 |                     5,974 |                   1,285 |                        463 |                      100 |                                        8% |                                 5,661 |                                  6,551 |
|                     [Ohio](/us-oh) |            4,804 |                     5,572 |                     477 |                        768 |                       66 |                                       16% |                                 5,008 |                                  6,593 |
|              [Connecticut](/us-ct) |            4,508 |                     4,605 |                   1,292 |                         97 |                       27 |                                        2% |                                 4,513 |                                  4,903 |
|           [North Carolina](/us-nc) |            3,532 |                     4,521 |                     431 |                        989 |                       94 |                                       28% |                                 3,953 |                                  5,515 |
|                 [Maryland](/us-md) |            3,949 |                     4,209 |                     696 |                        260 |                       43 |                                        7% |                                 3,979 |                                  4,667 |
|                  [Indiana](/us-in) |            3,632 |                     4,094 |                     608 |                        462 |                       69 |                                       13% |                                 3,667 |                                  4,930 |
|           [South Carolina](/us-sc) |            3,378 |                     3,914 |                     760 |                        536 |                      104 |                                       16% |                                 3,613 |                                  4,363 |
|                 [Virginia](/us-va) |            3,205 |                     3,857 |                     452 |                        652 |                       76 |                                       20% |                                 3,394 |                                  4,624 |
|              [Mississippi](/us-ms) |            2,969 |                     3,364 |                   1,130 |                        395 |                      133 |                                       13% |                                 3,114 |                                  3,821 |
|                [Tennessee](/us-tn) |            2,454 |                     3,086 |                     452 |                        632 |                       92 |                                       26% |                                 2,737 |                                  3,651 |
|                  [Alabama](/us-al) |            2,540 |                     2,867 |                     585 |                        327 |                       67 |                                       13% |                                 2,658 |                                  3,214 |
|                 [Missouri](/us-mo) |            2,069 |                     2,756 |                     449 |                        687 |                      112 |                                       33% |                                 2,356 |                                  3,363 |
|               [Washington](/us-wa) |            2,126 |                     2,493 |                     327 |                        367 |                       48 |                                       17% |                                 2,178 |                                  3,127 |
|                [Minnesota](/us-mn) |            2,089 |                     2,414 |                     428 |                        325 |                       58 |                                       16% |                                 2,145 |                                  2,872 |
|                 [Colorado](/us-co) |            2,051 |                     2,225 |                     386 |                        174 |                       30 |                                        8% |                                 2,064 |                                  2,553 |
|                 [Arkansas](/us-ar) |            1,369 |                     1,841 |                     610 |                        472 |                      156 |                                       34% |                                 1,591 |                                  2,285 |
|                   [Nevada](/us-nv) |            1,600 |                     1,803 |                     585 |                        203 |                       66 |                                       13% |                                 1,666 |                                  2,062 |
|                [Wisconsin](/us-wi) |            1,327 |                     1,722 |                     296 |                        395 |                       68 |                                       30% |                                 1,478 |                                  2,079 |
|                     [Iowa](/us-ia) |            1,358 |                     1,656 |                     525 |                        298 |                       94 |                                       22% |                                 1,455 |                                  1,987 |
|                 [Kentucky](/us-ky) |            1,174 |                     1,454 |                     325 |                        280 |                       63 |                                       24% |                                 1,276 |                                  1,720 |
|                 [Oklahoma](/us-ok) |            1,031 |                     1,328 |                     336 |                        297 |                       75 |                                       29% |                                 1,166 |                                  1,603 |
|             [Rhode Island](/us-ri) |            1,114 |                     1,197 |                   1,130 |                         83 |                       78 |                                        7% |                                 1,122 |                                  1,346 |
|               [New Mexico](/us-nm) |              877 |                     1,017 |                     485 |                        140 |                       67 |                                       16% |                                   922 |                                  1,196 |
|              [Puerto Rico](/us-pr) |              661 |                       890 |                     279 |                        229 |                       72 |                                       35% |                                   771 |                                  1,065 |
|                   [Kansas](/us-ks) |              669 |                       887 |                     304 |                        218 |                       75 |                                       33% |                                   755 |                                  1,095 |
|                   [Oregon](/us-or) |              559 |                       714 |                     169 |                        155 |                       37 |                                       28% |                                   615 |                                    876 |
|                 [Delaware](/us-de) |              636 |                       679 |                     697 |                         43 |                       44 |                                        7% |                                   642 |                                    753 |
|     [District of Columbia](/us-dc) |              627 |                       655 |                     929 |                         28 |                       40 |                                        5% |                                   631 |                                    717 |
|                 [Nebraska](/us-ne) |              478 |                       589 |                     305 |                        111 |                       58 |                                       23% |                                   513 |                                    721 |
|                    [Idaho](/us-id) |              469 |                       578 |                     323 |                        109 |                       61 |                                       23% |                                   520 |                                    669 |
|                     [Utah](/us-ut) |              459 |                       555 |                     173 |                         96 |                       30 |                                       21% |                                   493 |                                    646 |
|            [West Virginia](/us-wv) |              355 |                       520 |                     290 |                        165 |                       92 |                                       46% |                                   431 |                                    672 |
|            [New Hampshire](/us-nh) |              439 |                       449 |                     330 |                         10 |                        7 |                                        2% |                                   440 |                                    490 |
|             [North Dakota](/us-nd) |              246 |                       443 |                     582 |                        197 |                      259 |                                       80% |                                   353 |                                    590 |
|             [South Dakota](/us-sd) |              223 |                       328 |                     371 |                        105 |                      119 |                                       47% |                                   250 |                                    445 |
|                  [Montana](/us-mt) |              180 |                       312 |                     292 |                        132 |                      124 |                                       74% |                                   248 |                                    407 |
|                   [Hawaii](/us-hi) |              136 |                       201 |                     142 |                         65 |                       46 |                                       48% |                                   165 |                                    267 |
|                    [Maine](/us-me) |              141 |                       154 |                     115 |                         13 |                       10 |                                        9% |                                   144 |                                    181 |
|                   [Alaska](/us-ak) |               56 |                        90 |                     123 |                         34 |                       46 |                                       60% |                                    72 |                                    123 |
|                     [Guam](/us-gu) |               49 |                        84 |                     509 |                         35 |                      213 |                                       72% |                                    67 |                                    113 |
|                  [Wyoming](/us-wy) |               50 |                        62 |                     108 |                         12 |                       21 |                                       25% |                                    55 |                                     73 |
|                  [Vermont](/us-vt) |               58 |                        60 |                      95 |                          2 |                        2 |                                        3% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               20 |                        24 |                     226 |                          4 |                       35 |                                       18% |                                    21 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      46 |                          1 |                       10 |                                       27% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          199,640 |                   221,914 |                     374 |                     22,274 |                       38 |                                       11% |                               203,071 |                                283,030 |
| [United Kingdom](/united-kingdom) |           42,233 |                    45,379 |                     672 |                      3,146 |                       47 |                                        7% |                                42,320 |                                 56,918 |
|                   [Italy](/italy) |           35,894 |                    36,815 |                     610 |                        921 |                       15 |                                        3% |                                35,914 |                                 39,861 |
|                   [Spain](/spain) |           31,791 |                    36,028 |                     768 |                      4,237 |                       90 |                                       13% |                                31,870 |                                 47,788 |
|                 [France](/france) |           31,986 |                    36,026 |                     538 |                      4,040 |                       60 |                                       13% |                                32,034 |                                 55,876 |
|               [Belgium](/belgium) |           10,016 |                    10,497 |                     916 |                        481 |                       42 |                                        5% |                                10,041 |                                 12,403 |
|               [Germany](/germany) |            9,495 |                     9,994 |                     120 |                        499 |                        6 |                                        5% |                                 9,506 |                                 11,855 |
|       [Netherlands](/netherlands) |            6,457 |                     7,321 |                     424 |                        864 |                       50 |                                       13% |                                 6,513 |                                  9,444 |
|               [Ukraine](/ukraine) |            4,221 |                     6,513 |                     148 |                      2,292 |                       52 |                                       54% |                                 5,265 |                                  8,082 |
|               [Romania](/romania) |            4,825 |                     6,129 |                     316 |                      1,304 |                       67 |                                       27% |                                 5,388 |                                  7,460 |
|                 [Sweden](/sweden) |            5,893 |                     6,017 |                     588 |                        124 |                       12 |                                        2% |                                 5,901 |                                  6,452 |
|                 [Poland](/poland) |            2,513 |                     3,592 |                      95 |                      1,079 |                       28 |                                       43% |                                 2,818 |                                  5,234 |
|             [Portugal](/portugal) |            1,971 |                     2,252 |                     219 |                        281 |                       27 |                                       14% |                                 2,040 |                                  2,589 |
|       [Switzerland](/switzerland) |            2,074 |                     2,211 |                     257 |                        137 |                       16 |                                        7% |                                 2,104 |                                  2,449 |
|               [Ireland](/ireland) |            1,804 |                     1,898 |                     387 |                         94 |                       19 |                                        5% |                                 1,811 |                                  2,276 |
|               [Moldova](/moldova) |            1,320 |                     1,667 |                     412 |                        347 |                       86 |                                       26% |                                 1,457 |                                  1,997 |
|               [Czechia](/czechia) |              655 |                     1,462 |                     137 |                        807 |                       76 |                                      123% |                                   990 |                                  2,299 |
|               [Hungary](/hungary) |              765 |                     1,135 |                     116 |                        370 |                       38 |                                       48% |                                   944 |                                  1,415 |
|               [Belarus](/belarus) |              833 |                     1,046 |                     111 |                        213 |                       23 |                                       26% |                                   897 |                                  1,354 |
|             [Bulgaria](/bulgaria) |              825 |                     1,045 |                     149 |                        220 |                       31 |                                       27% |                                   921 |                                  1,224 |
|               [Austria](/austria) |              799 |                       953 |                     108 |                        154 |                       17 |                                       19% |                                   832 |                                  1,184 |
|                 [Serbia](/serbia) |              749 |                       768 |                     110 |                         19 |                        3 |                                        3% |                                   752 |                                    821 |
|               [Denmark](/denmark) |              650 |                       738 |                     127 |                         88 |                       15 |                                       13% |                                   665 |                                    942 |
|                 [Greece](/greece) |              391 |                       597 |                      56 |                        206 |                       19 |                                       53% |                                   473 |                                    845 |
|               [Finland](/finland) |              344 |                       375 |                      68 |                         31 |                        6 |                                        9% |                                   354 |                                    414 |
|               [Croatia](/croatia) |              280 |                       370 |                      91 |                         90 |                       22 |                                       32% |                                   311 |                                    506 |
|                 [Norway](/norway) |              274 |                       311 |                      58 |                         37 |                        7 |                                       13% |                                   286 |                                    350 |
|             [Slovenia](/slovenia) |              150 |                       191 |                      92 |                         41 |                       20 |                                       27% |                                   167 |                                    233 |
|         [Luxembourg](/luxembourg) |              124 |                       136 |                     221 |                         12 |                       19 |                                        9% |                                   126 |                                    156 |
|           [Lithuania](/lithuania) |               92 |                       115 |                      41 |                         23 |                        8 |                                       25% |                                   101 |                                    135 |
|             [Slovakia](/slovakia) |               48 |                        91 |                      17 |                         43 |                        8 |                                       89% |                                    71 |                                    126 |
|                   [Malta](/malta) |               35 |                        85 |                     173 |                         50 |                      102 |                                      144% |                                    56 |                                    157 |
|               [Estonia](/estonia) |               64 |                        77 |                      58 |                         13 |                       10 |                                       20% |                                    70 |                                     88 |
|                 [Latvia](/latvia) |               37 |                        46 |                      24 |                          9 |                        5 |                                       24% |                                    40 |                                     53 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      28 |                          3 |                        3 |                                       12% |                                    23 |                                     29 |
|               [Iceland](/iceland) |               10 |                        12 |                      37 |                          2 |                        7 |                                       24% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          568,583 |                   678,944 |                     131 |                    110,361 |                       21 |                                       19% |                               621,375 |                                772,480 |
|                             [Brazil](/brazil) |          143,952 |                   162,014 |                     768 |                     18,062 |                       86 |                                       13% |                               154,757 |                                176,392 |
|                               [India](/india) |           97,497 |                   129,904 |                      95 |                     32,407 |                       24 |                                       33% |                               112,804 |                                146,364 |
|                             [Mexico](/mexico) |           77,646 |                    88,881 |                     697 |                     11,235 |                       88 |                                       14% |                                84,985 |                                 95,804 |
|                                 [Peru](/peru) |           32,396 |                    35,250 |                   1,084 |                      2,854 |                       88 |                                        9% |                                32,993 |                                 38,707 |
|                                 [Iran](/iran) |           26,169 |                    31,807 |                     384 |                      5,638 |                       68 |                                       22% |                                28,924 |                                 36,180 |
|                         [Colombia](/colombia) |           25,998 |                    30,011 |                     596 |                      4,013 |                       80 |                                       15% |                                27,549 |                                 33,847 |
|                       [Argentina](/argentina) |           16,937 |                    28,002 |                     625 |                     11,065 |                      247 |                                       65% |                                21,848 |                                 37,397 |
|                             [Russia](/russia) |           20,630 |                    25,440 |                     174 |                      4,810 |                       33 |                                       23% |                                23,351 |                                 33,328 |
|                 [South Africa](/south-africa) |           16,734 |                    18,173 |                     310 |                      1,439 |                       25 |                                        9% |                                17,142 |                                 20,262 |
|                       [Indonesia](/indonesia) |           10,740 |                    14,758 |                      55 |                      4,018 |                       15 |                                       37% |                                13,270 |                                 18,516 |
|                               [Chile](/chile) |           12,741 |                    14,364 |                     758 |                      1,623 |                       86 |                                       13% |                                12,901 |                                 18,239 |
|                           [Ecuador](/ecuador) |           11,355 |                    12,264 |                     706 |                        909 |                       52 |                                        8% |                                11,421 |                                 13,827 |
|                             [Turkey](/turkey) |            8,195 |                    10,609 |                     127 |                      2,414 |                       29 |                                       29% |                                 8,593 |                                 13,807 |
|                             [Canada](/canada) |            9,346 |                    10,039 |                     268 |                        693 |                       19 |                                        7% |                                 9,424 |                                 11,776 |
|                           [Bolivia](/bolivia) |            7,965 |                     8,810 |                     765 |                        845 |                       73 |                                       11% |                                 8,298 |                                  9,621 |
|                   [Philippines](/philippines) |            5,504 |                     7,477 |                      69 |                      1,973 |                       18 |                                       36% |                                 6,333 |                                  9,238 |
|                         [Pakistan](/pakistan) |            6,484 |                     6,730 |                      31 |                        246 |                        1 |                                        4% |                                 6,525 |                                  7,148 |
|                               [Egypt](/egypt) |            5,930 |                     6,524 |                      65 |                        594 |                        6 |                                       10% |                                 6,008 |                                  7,746 |
|                     [Bangladesh](/bangladesh) |            5,251 |                     6,154 |                      38 |                        903 |                        6 |                                       17% |                                 5,649 |                                  7,287 |
|                 [Saudi Arabia](/saudi-arabia) |            4,768 |                     5,577 |                     163 |                        809 |                       24 |                                       17% |                                 4,983 |                                  6,456 |
|                               [China](/china) |            4,739 |                     4,758 |                       3 |                         19 |                        0 |                                        0% |                                 4,739 |                                  4,910 |
|                           [Morocco](/morocco) |            2,194 |                     3,526 |                      97 |                      1,332 |                       37 |                                       61% |                                 2,750 |                                  4,597 |
|                         [Honduras](/honduras) |            2,353 |                     2,829 |                     290 |                        476 |                       49 |                                       20% |                                 2,481 |                                  3,408 |
|                             [Panama](/panama) |            2,372 |                     2,617 |                     616 |                        245 |                       58 |                                       10% |                                 2,455 |                                  2,899 |
|                             [Israel](/israel) |            1,569 |                     2,382 |                     280 |                        813 |                       95 |                                       52% |                                 1,863 |                                  3,396 |
|     [Dominican Republic](/dominican-republic) |            2,105 |                     2,266 |                     211 |                        161 |                       15 |                                        8% |                                 2,151 |                                  2,437 |
|                           [Algeria](/algeria) |            1,736 |                     1,849 |                      43 |                        113 |                        3 |                                        7% |                                 1,762 |                                  2,012 |
|                               [Japan](/japan) |            1,575 |                     1,762 |                      14 |                        187 |                        1 |                                       12% |                                 1,630 |                                  1,963 |
|                           [Nigeria](/nigeria) |            1,112 |                     1,190 |                       6 |                         78 |                        0 |                                        7% |                                 1,123 |                                  1,370 |
|                       [Australia](/australia) |              888 |                       962 |                      38 |                         74 |                        3 |                                        8% |                                   910 |                                  1,041 |
|                             [Kuwait](/kuwait) |              610 |                       695 |                     165 |                         85 |                       20 |                                       14% |                                   625 |                                    835 |
| [United Arab Emirates](/united-arab-emirates) |              419 |                       511 |                      52 |                         92 |                        9 |                                       22% |                                   424 |                                    670 |
|                   [South Korea](/south-korea) |              415 |                       503 |                      10 |                         88 |                        2 |                                       21% |                                   433 |                                    624 |
|                         [Malaysia](/malaysia) |              136 |                       157 |                       5 |                         21 |                        1 |                                       15% |                                   142 |                                    186 |
|                                 [Cuba](/cuba) |              122 |                       150 |                      13 |                         28 |                        2 |                                       23% |                                   129 |                                    190 |
