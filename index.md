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
### Updated Daily - Last Updated: October 4 (6am ET):
<p align="center">
  Current Total: <b>209,379</b> deaths | Projected Total: <b>231,600 deaths by Nov 1, 2020</b> (Range: 221-248k)<br>
  Currently Infected: <b>1.2%</b> (1 in 85) | Total Infected: <b>16.1%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: October 4, 2020

|   US deaths surpass: |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|
|              225,000 |         <1% |        80% |
|              250,000 |         <1% |         2% |
|              275,000 |         <1% |        <1% |
|              300,000 |         <1% |        <1% |

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
|             *[United States](/us)* |          209,379 |                   231,558 |                     698 |                     22,179 |                       67 |                                       11% |                               221,680 |                                247,338 |
|                 [New York](/us-ny) |           33,197 |                    33,569 |                   1,726 |                        372 |                       19 |                                        1% |                                33,207 |                                 35,454 |
|                    [Texas](/us-tx) |           16,295 |                    18,806 |                     649 |                      2,511 |                       87 |                                       15% |                                17,361 |                                 21,248 |
|               [California](/us-ca) |           16,115 |                    18,216 |                     461 |                      2,101 |                       53 |                                       13% |                                16,610 |                                 21,846 |
|                  [Florida](/us-fl) |           14,628 |                    17,371 |                     809 |                      2,743 |                      128 |                                       19% |                                15,639 |                                 20,221 |
|               [New Jersey](/us-nj) |           16,135 |                    16,363 |                   1,842 |                        228 |                       26 |                                        1% |                                16,142 |                                 17,103 |
|            [Massachusetts](/us-ma) |            9,507 |                     9,997 |                   1,439 |                        490 |                       71 |                                        5% |                                 9,533 |                                 10,767 |
|                 [Illinois](/us-il) |            9,023 |                     9,751 |                     770 |                        728 |                       57 |                                        8% |                                 9,161 |                                 10,876 |
|             [Pennsylvania](/us-pa) |            8,180 |                     8,824 |                     689 |                        644 |                       50 |                                        8% |                                 8,251 |                                  9,852 |
|                  [Georgia](/us-ga) |            7,133 |                     8,105 |                     763 |                        972 |                       92 |                                       14% |                                 7,420 |                                  9,318 |
|                 [Michigan](/us-mi) |            7,124 |                     7,462 |                     747 |                        338 |                       34 |                                        5% |                                 7,170 |                                  8,001 |
|                  [Arizona](/us-az) |            5,705 |                     6,243 |                     858 |                        538 |                       74 |                                        9% |                                 5,841 |                                  7,060 |
|                [Louisiana](/us-la) |            5,545 |                     5,953 |                   1,280 |                        408 |                       88 |                                        7% |                                 5,671 |                                  6,477 |
|                     [Ohio](/us-oh) |            4,925 |                     5,730 |                     490 |                        805 |                       69 |                                       16% |                                 5,134 |                                  6,753 |
|              [Connecticut](/us-ct) |            4,513 |                     4,602 |                   1,291 |                         89 |                       25 |                                        2% |                                 4,518 |                                  4,876 |
|           [North Carolina](/us-nc) |            3,629 |                     4,569 |                     436 |                        940 |                       90 |                                       26% |                                 4,019 |                                  5,493 |
|                 [Maryland](/us-md) |            3,957 |                     4,182 |                     692 |                        225 |                       37 |                                        6% |                                 3,983 |                                  4,583 |
|                  [Indiana](/us-in) |            3,669 |                     4,094 |                     608 |                        425 |                       63 |                                       12% |                                 3,702 |                                  4,866 |
|           [South Carolina](/us-sc) |            3,442 |                     3,943 |                     766 |                        501 |                       97 |                                       15% |                                 3,661 |                                  4,364 |
|                 [Virginia](/us-va) |            3,267 |                     3,846 |                     451 |                        579 |                       68 |                                       18% |                                 3,413 |                                  4,594 |
|              [Mississippi](/us-ms) |            3,011 |                     3,364 |                   1,130 |                        353 |                      119 |                                       12% |                                 3,134 |                                  3,783 |
|                [Tennessee](/us-tn) |            2,560 |                     3,188 |                     467 |                        628 |                       92 |                                       25% |                                 2,841 |                                  3,734 |
|                 [Missouri](/us-mo) |            2,177 |                     2,906 |                     474 |                        729 |                      119 |                                       33% |                                 2,489 |                                  3,542 |
|                  [Alabama](/us-al) |            2,558 |                     2,840 |                     579 |                        282 |                       58 |                                       11% |                                 2,655 |                                  3,154 |
|               [Washington](/us-wa) |            2,142 |                     2,473 |                     325 |                        331 |                       43 |                                       15% |                                 2,188 |                                  3,043 |
|                [Minnesota](/us-mn) |            2,126 |                     2,441 |                     433 |                        315 |                       56 |                                       15% |                                 2,179 |                                  2,879 |
|                 [Colorado](/us-co) |            2,060 |                     2,218 |                     385 |                        158 |                       27 |                                        8% |                                 2,071 |                                  2,520 |
|                 [Arkansas](/us-ar) |            1,407 |                     1,828 |                     606 |                        421 |                      139 |                                       30% |                                 1,606 |                                  2,224 |
|                   [Nevada](/us-nv) |            1,620 |                     1,803 |                     585 |                        183 |                       59 |                                       11% |                                 1,678 |                                  2,040 |
|                [Wisconsin](/us-wi) |            1,372 |                     1,771 |                     304 |                        399 |                       68 |                                       29% |                                 1,534 |                                  2,118 |
|                     [Iowa](/us-ia) |            1,381 |                     1,652 |                     524 |                        271 |                       86 |                                       20% |                                 1,468 |                                  1,953 |
|                 [Kentucky](/us-ky) |            1,205 |                     1,474 |                     330 |                        269 |                       60 |                                       22% |                                 1,309 |                                  1,731 |
|                 [Oklahoma](/us-ok) |            1,051 |                     1,318 |                     333 |                        267 |                       67 |                                       25% |                                 1,172 |                                  1,554 |
|             [Rhode Island](/us-ri) |            1,118 |                     1,190 |                   1,124 |                         72 |                       68 |                                        6% |                                 1,125 |                                  1,321 |
|               [New Mexico](/us-nm) |              890 |                     1,019 |                     486 |                        129 |                       62 |                                       15% |                                   931 |                                  1,187 |
|                   [Kansas](/us-ks) |              690 |                       893 |                     307 |                        203 |                       70 |                                       29% |                                   768 |                                  1,088 |
|              [Puerto Rico](/us-pr) |              681 |                       890 |                     279 |                        209 |                       65 |                                       31% |                                   783 |                                  1,046 |
|                   [Oregon](/us-or) |              571 |                       718 |                     170 |                        147 |                       35 |                                       26% |                                   623 |                                    868 |
|                 [Delaware](/us-de) |              645 |                       688 |                     706 |                         43 |                       44 |                                        7% |                                   651 |                                    760 |
|     [District of Columbia](/us-dc) |              627 |                       652 |                     924 |                         25 |                       35 |                                        4% |                                   631 |                                    707 |
|                 [Nebraska](/us-ne) |              497 |                       611 |                     316 |                        114 |                       59 |                                       23% |                                   533 |                                    744 |
|                    [Idaho](/us-id) |              480 |                       581 |                     325 |                        101 |                       57 |                                       21% |                                   527 |                                    664 |
|                     [Utah](/us-ut) |              476 |                       574 |                     179 |                         98 |                       31 |                                       21% |                                   509 |                                    670 |
|            [West Virginia](/us-wv) |              363 |                       502 |                     280 |                        139 |                       78 |                                       38% |                                   429 |                                    612 |
|             [North Dakota](/us-nd) |              271 |                       480 |                     630 |                        209 |                      274 |                                       77% |                                   390 |                                    617 |
|            [New Hampshire](/us-nh) |              442 |                       452 |                     333 |                         10 |                        8 |                                        2% |                                   443 |                                    493 |
|             [South Dakota](/us-sd) |              248 |                       379 |                     429 |                        131 |                      148 |                                       53% |                                   301 |                                    512 |
|                  [Montana](/us-mt) |              186 |                       298 |                     279 |                        112 |                      105 |                                       60% |                                   244 |                                    366 |
|                   [Hawaii](/us-hi) |              153 |                       220 |                     156 |                         67 |                       47 |                                       44% |                                   183 |                                    293 |
|                    [Maine](/us-me) |              142 |                       155 |                     115 |                         13 |                        9 |                                        9% |                                   144 |                                    181 |
|                   [Alaska](/us-ak) |               58 |                        88 |                     120 |                         30 |                       41 |                                       52% |                                    73 |                                    116 |
|                     [Guam](/us-gu) |               49 |                        76 |                     460 |                         27 |                      164 |                                       55% |                                    62 |                                    101 |
|                  [Wyoming](/us-wy) |               53 |                        68 |                     117 |                         15 |                       26 |                                       28% |                                    59 |                                     83 |
|                  [Vermont](/us-vt) |               58 |                        59 |                      95 |                          1 |                        2 |                                        2% |                                    58 |                                     64 |
|           [Virgin Islands](/us-vi) |               20 |                        23 |                     220 |                          3 |                       29 |                                       15% |                                    21 |                                     26 |
| [Northern Mariana Islands](/us-mp) |                2 |                         2 |                      45 |                          0 |                        9 |                                       25% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          201,193 |                   220,946 |                     373 |                     19,753 |                       33 |                                       10% |                               204,629 |                                272,842 |
| [United Kingdom](/united-kingdom) |           42,407 |                    44,380 |                     657 |                      1,973 |                       29 |                                        5% |                                42,460 |                                 51,149 |
|                   [Italy](/italy) |           35,968 |                    36,815 |                     610 |                        847 |                       14 |                                        2% |                                35,987 |                                 39,550 |
|                   [Spain](/spain) |           32,086 |                    36,231 |                     772 |                      4,145 |                       88 |                                       13% |                                32,277 |                                 47,419 |
|                 [France](/france) |           32,171 |                    35,429 |                     529 |                      3,258 |                       49 |                                       10% |                                32,211 |                                 52,236 |
|               [Belgium](/belgium) |           10,044 |                    10,466 |                     914 |                        422 |                       37 |                                        4% |                                10,067 |                                 12,084 |
|               [Germany](/germany) |            9,531 |                    10,058 |                     121 |                        527 |                        6 |                                        6% |                                 9,544 |                                 11,999 |
|       [Netherlands](/netherlands) |            6,503 |                     7,255 |                     420 |                        752 |                       43 |                                       12% |                                 6,526 |                                  9,460 |
|               [Ukraine](/ukraine) |            4,451 |                     6,730 |                     153 |                      2,279 |                       52 |                                       51% |                                 5,416 |                                  8,413 |
|               [Romania](/romania) |            4,947 |                     6,160 |                     317 |                      1,213 |                       62 |                                       25% |                                 5,487 |                                  7,354 |
|                 [Sweden](/sweden) |            5,895 |                     6,004 |                     587 |                        109 |                       11 |                                        2% |                                 5,901 |                                  6,395 |
|                 [Poland](/poland) |            2,604 |                     3,747 |                      99 |                      1,143 |                       30 |                                       44% |                                 2,972 |                                  5,489 |
|             [Portugal](/portugal) |            1,995 |                     2,266 |                     220 |                        271 |                       26 |                                       14% |                                 2,063 |                                  2,587 |
|       [Switzerland](/switzerland) |            2,076 |                     2,192 |                     255 |                        116 |                       14 |                                        6% |                                 2,102 |                                  2,401 |
|               [Ireland](/ireland) |            1,810 |                     1,896 |                     387 |                         86 |                       18 |                                        5% |                                 1,817 |                                  2,246 |
|               [Moldova](/moldova) |            1,353 |                     1,665 |                     412 |                        312 |                       77 |                                       23% |                                 1,477 |                                  1,974 |
|               [Czechia](/czechia) |              711 |                     1,429 |                     134 |                        718 |                       67 |                                      101% |                                 1,041 |                                  2,113 |
|               [Hungary](/hungary) |              812 |                     1,248 |                     128 |                        436 |                       45 |                                       54% |                                 1,046 |                                  1,564 |
|               [Belarus](/belarus) |              851 |                     1,050 |                     111 |                        199 |                       21 |                                       23% |                                   912 |                                  1,330 |
|             [Bulgaria](/bulgaria) |              841 |                     1,029 |                     147 |                        188 |                       27 |                                       22% |                                   928 |                                  1,182 |
|               [Austria](/austria) |              809 |                       950 |                     107 |                        141 |                       16 |                                       17% |                                   840 |                                  1,148 |
|                 [Serbia](/serbia) |              753 |                       771 |                     111 |                         18 |                        3 |                                        2% |                                   756 |                                    823 |
|               [Denmark](/denmark) |              654 |                       719 |                     124 |                         65 |                       11 |                                       10% |                                   664 |                                    862 |
|                 [Greece](/greece) |              405 |                       582 |                      54 |                        177 |                       16 |                                       44% |                                   478 |                                    764 |
|               [Croatia](/croatia) |              293 |                       384 |                      94 |                         91 |                       22 |                                       31% |                                   324 |                                    515 |
|               [Finland](/finland) |              345 |                       373 |                      68 |                         28 |                        5 |                                        8% |                                   354 |                                    409 |
|                 [Norway](/norway) |              275 |                       306 |                      57 |                         31 |                        6 |                                       11% |                                   285 |                                    339 |
|             [Slovenia](/slovenia) |              155 |                       200 |                      96 |                         45 |                       21 |                                       29% |                                   175 |                                    241 |
|         [Luxembourg](/luxembourg) |              125 |                       136 |                     221 |                         11 |                       18 |                                        9% |                                   127 |                                    155 |
|           [Lithuania](/lithuania) |               94 |                       117 |                      42 |                         23 |                        8 |                                       25% |                                   104 |                                    139 |
|             [Slovakia](/slovakia) |               54 |                       108 |                      20 |                         54 |                       10 |                                      100% |                                    83 |                                    154 |
|                   [Malta](/malta) |               38 |                        83 |                     169 |                         45 |                       92 |                                      120% |                                    57 |                                    151 |
|               [Estonia](/estonia) |               67 |                        83 |                      62 |                         16 |                       12 |                                       23% |                                    74 |                                     98 |
|                 [Latvia](/latvia) |               38 |                        48 |                      25 |                         10 |                        5 |                                       26% |                                    42 |                                     57 |
|                 [Cyprus](/cyprus) |               22 |                        24 |                      28 |                          2 |                        3 |                                       11% |                                    22 |                                     27 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        6 |                                       21% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          583,096 |                   682,509 |                     132 |                     99,413 |                       19 |                                       17% |                               629,448 |                                768,638 |
|                             [Brazil](/brazil) |          145,987 |                   161,917 |                     767 |                     15,930 |                       75 |                                       11% |                               154,172 |                                174,951 |
|                               [India](/india) |          100,842 |                   129,847 |                      95 |                     29,005 |                       21 |                                       29% |                               114,724 |                                145,186 |
|                             [Mexico](/mexico) |           78,880 |                    88,898 |                     697 |                     10,018 |                       79 |                                       13% |                                85,344 |                                 95,168 |
|                                 [Peru](/peru) |           32,609 |                    35,002 |                   1,077 |                      2,393 |                       74 |                                        7% |                                33,105 |                                 38,025 |
|                                 [Iran](/iran) |           26,746 |                    31,955 |                     385 |                      5,209 |                       63 |                                       19% |                                29,231 |                                 36,014 |
|                       [Argentina](/argentina) |           20,795 |                    30,505 |                     681 |                      9,710 |                      217 |                                       47% |                                25,030 |                                 39,057 |
|                         [Colombia](/colombia) |           26,556 |                    30,298 |                     602 |                      3,742 |                       74 |                                       14% |                                28,469 |                                 33,688 |
|                             [Russia](/russia) |           21,153 |                    25,784 |                     177 |                      4,631 |                       32 |                                       22% |                                23,694 |                                 33,583 |
|                 [South Africa](/south-africa) |           16,938 |                    18,297 |                     312 |                      1,359 |                       23 |                                        8% |                                17,296 |                                 20,369 |
|                       [Indonesia](/indonesia) |           11,055 |                    14,660 |                      54 |                      3,605 |                       13 |                                       33% |                                13,360 |                                 17,887 |
|                               [Chile](/chile) |           12,919 |                    14,429 |                     761 |                      1,510 |                       80 |                                       12% |                                13,060 |                                 17,964 |
|                           [Ecuador](/ecuador) |           11,597 |                    12,616 |                     726 |                      1,019 |                       59 |                                        9% |                                11,673 |                                 14,247 |
|                             [Turkey](/turkey) |            8,384 |                    10,592 |                     127 |                      2,208 |                       26 |                                       26% |                                 8,745 |                                 13,461 |
|                             [Canada](/canada) |            9,488 |                    10,243 |                     274 |                        755 |                       20 |                                        8% |                                 9,565 |                                 11,959 |
|                           [Bolivia](/bolivia) |            8,073 |                     8,833 |                     767 |                        760 |                       66 |                                        9% |                                 8,362 |                                  9,572 |
|                   [Philippines](/philippines) |            5,678 |                     7,466 |                      69 |                      1,788 |                       17 |                                       31% |                                 6,387 |                                  9,056 |
|                         [Pakistan](/pakistan) |            6,513 |                     6,740 |                      31 |                        227 |                        1 |                                        3% |                                 6,552 |                                  7,126 |
|                               [Egypt](/egypt) |            5,970 |                     6,503 |                      65 |                        533 |                        5 |                                        9% |                                 6,039 |                                  7,580 |
|                     [Bangladesh](/bangladesh) |            5,325 |                     6,128 |                      38 |                        803 |                        5 |                                       15% |                                 5,690 |                                  7,129 |
|                 [Saudi Arabia](/saudi-arabia) |            4,850 |                     5,595 |                     163 |                        745 |                       22 |                                       15% |                                 5,043 |                                  6,401 |
|                               [China](/china) |            4,739 |                     4,756 |                       3 |                         17 |                        0 |                                        0% |                                 4,739 |                                  4,898 |
|                           [Morocco](/morocco) |            2,293 |                     3,473 |                      95 |                      1,180 |                       32 |                                       51% |                                 2,816 |                                  4,430 |
|                         [Honduras](/honduras) |            2,399 |                     2,830 |                     290 |                        431 |                       44 |                                       18% |                                 2,522 |                                  3,360 |
|                             [Panama](/panama) |            2,414 |                     2,644 |                     623 |                        230 |                       54 |                                       10% |                                 2,489 |                                  2,922 |
|                             [Israel](/israel) |            1,682 |                     2,456 |                     288 |                        774 |                       91 |                                       46% |                                 1,951 |                                  3,394 |
|     [Dominican Republic](/dominican-republic) |            2,128 |                     2,273 |                     212 |                        145 |                       13 |                                        7% |                                 2,167 |                                  2,428 |
|                           [Algeria](/algeria) |            1,756 |                     1,857 |                      43 |                        101 |                        2 |                                        6% |                                 1,778 |                                  2,006 |
|                               [Japan](/japan) |            1,594 |                     1,761 |                      14 |                        167 |                        1 |                                       10% |                                 1,642 |                                  1,944 |
|                           [Nigeria](/nigeria) |            1,113 |                     1,181 |                       6 |                         68 |                        0 |                                        6% |                                 1,122 |                                  1,341 |
|                       [Australia](/australia) |              894 |                       954 |                      38 |                         60 |                        2 |                                        7% |                                   911 |                                  1,021 |
|                             [Kuwait](/kuwait) |              620 |                       701 |                     167 |                         81 |                       19 |                                       13% |                                   634 |                                    836 |
| [United Arab Emirates](/united-arab-emirates) |              426 |                       515 |                      53 |                         89 |                        9 |                                       21% |                                   430 |                                    665 |
|                   [South Korea](/south-korea) |              421 |                       498 |                      10 |                         77 |                        2 |                                       18% |                                   436 |                                    608 |
|                         [Malaysia](/malaysia) |              137 |                       156 |                       5 |                         19 |                        1 |                                       14% |                                   142 |                                    182 |
|                                 [Cuba](/cuba) |              122 |                       146 |                      13 |                         24 |                        2 |                                       20% |                                   128 |                                    180 |
