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

* **August 31:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 7 (3am ET):
<p align="center">
  Current Total: <b>188,938</b> deaths | Projected Total: <b>220,000 deaths by Nov 1, 2020</b> (Range: 208-238k)<br>
  Currently Infected: <b>1.1%</b> (1 in 90) | Total Infected: <b>15.0%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 7, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        98% |         99% |        99% |
|              225,000 |         <1% |        <1% |          2% |        19% |
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
|             *[United States](/us)* |          188,938 |                   220,006 |                     663 |                     31,068 |                       94 |                                       16% |                               208,133 |                                237,530 |
|                 [New York](/us-ny) |           32,987 |                    33,362 |                   1,715 |                        375 |                       19 |                                        1% |                                33,000 |                                 35,508 |
|               [California](/us-ca) |           13,731 |                    18,191 |                     460 |                      4,460 |                      113 |                                       32% |                                15,747 |                                 22,206 |
|                    [Texas](/us-tx) |           13,654 |                    18,061 |                     623 |                      4,407 |                      152 |                                       32% |                                16,100 |                                 20,695 |
|               [New Jersey](/us-nj) |           15,989 |                    16,164 |                   1,820 |                        175 |                       20 |                                        1% |                                16,001 |                                 16,764 |
|                  [Florida](/us-fl) |           11,849 |                    14,529 |                     676 |                      2,680 |                      125 |                                       23% |                                13,094 |                                 16,370 |
|            [Massachusetts](/us-ma) |            9,125 |                     9,539 |                   1,373 |                        414 |                       60 |                                        5% |                                 9,152 |                                 10,498 |
|                 [Illinois](/us-il) |            8,390 |                     9,337 |                     737 |                        947 |                       75 |                                       11% |                                 8,495 |                                 10,611 |
|             [Pennsylvania](/us-pa) |            7,750 |                     8,361 |                     653 |                        611 |                       48 |                                        8% |                                 7,778 |                                  9,605 |
|                  [Georgia](/us-ga) |            6,037 |                     8,178 |                     770 |                      2,141 |                      202 |                                       35% |                                 7,078 |                                  9,900 |
|                 [Michigan](/us-mi) |            6,806 |                     7,250 |                     726 |                        444 |                       44 |                                        7% |                                 6,843 |                                  8,017 |
|                  [Arizona](/us-az) |            5,221 |                     5,984 |                     822 |                        763 |                      105 |                                       15% |                                 5,523 |                                  6,664 |
|                [Louisiana](/us-la) |            5,093 |                     5,842 |                   1,257 |                        749 |                      161 |                                       15% |                                 5,395 |                                  6,557 |
|                     [Ohio](/us-oh) |            4,259 |                     4,986 |                     427 |                        727 |                       62 |                                       17% |                                 4,437 |                                  5,880 |
|              [Connecticut](/us-ct) |            4,468 |                     4,542 |                   1,274 |                         74 |                       21 |                                        2% |                                 4,477 |                                  4,775 |
|                 [Maryland](/us-md) |            3,799 |                     4,152 |                     687 |                        353 |                       58 |                                        9% |                                 3,830 |                                  4,823 |
|           [North Carolina](/us-nc) |            2,890 |                     4,019 |                     383 |                      1,129 |                      108 |                                       39% |                                 3,412 |                                  5,024 |
|                  [Indiana](/us-in) |            3,364 |                     3,803 |                     565 |                        439 |                       65 |                                       13% |                                 3,389 |                                  4,689 |
|           [South Carolina](/us-sc) |            2,887 |                     3,754 |                     729 |                        867 |                      168 |                                       30% |                                 3,328 |                                  4,401 |
|                 [Virginia](/us-va) |            2,678 |                     3,335 |                     391 |                        657 |                       77 |                                       25% |                                 2,751 |                                  4,278 |
|              [Mississippi](/us-ms) |            2,584 |                     3,214 |                   1,080 |                        630 |                      212 |                                       24% |                                 2,863 |                                  3,715 |
|                  [Alabama](/us-al) |            2,276 |                     2,891 |                     590 |                        615 |                      126 |                                       27% |                                 2,558 |                                  3,411 |
|                [Tennessee](/us-tn) |            1,865 |                     2,709 |                     396 |                        844 |                      123 |                                       45% |                                 2,300 |                                  3,358 |
|                 [Missouri](/us-mo) |            1,685 |                     2,355 |                     384 |                        670 |                      109 |                                       40% |                                 1,974 |                                  2,974 |
|               [Washington](/us-wa) |            1,953 |                     2,314 |                     304 |                        361 |                       47 |                                       18% |                                 2,032 |                                  2,792 |
|                [Minnesota](/us-mn) |            1,909 |                     2,272 |                     403 |                        363 |                       64 |                                       19% |                                 1,968 |                                  2,783 |
|                 [Colorado](/us-co) |            1,972 |                     2,146 |                     373 |                        174 |                       30 |                                        9% |                                 1,983 |                                  2,627 |
|                   [Nevada](/us-nv) |            1,389 |                     1,868 |                     606 |                        479 |                      155 |                                       34% |                                 1,638 |                                  2,196 |
|                     [Iowa](/us-ia) |            1,167 |                     1,694 |                     537 |                        527 |                      167 |                                       45% |                                 1,342 |                                  2,404 |
|                [Wisconsin](/us-wi) |            1,168 |                     1,543 |                     265 |                        375 |                       64 |                                       32% |                                 1,316 |                                  1,924 |
|                 [Arkansas](/us-ar) |              894 |                     1,418 |                     470 |                        524 |                      174 |                                       59% |                                 1,162 |                                  1,794 |
|                 [Kentucky](/us-ky) |              996 |                     1,404 |                     314 |                        408 |                       91 |                                       41% |                                 1,161 |                                  1,780 |
|                 [Oklahoma](/us-ok) |              853 |                     1,264 |                     319 |                        411 |                      104 |                                       48% |                                 1,042 |                                  1,633 |
|             [Rhode Island](/us-ri) |            1,055 |                     1,123 |                   1,060 |                         68 |                       64 |                                        6% |                                 1,063 |                                  1,269 |
|               [New Mexico](/us-nm) |              803 |                       957 |                     457 |                        154 |                       74 |                                       19% |                                   859 |                                  1,112 |
|              [Puerto Rico](/us-pr) |              477 |                       816 |                     256 |                        339 |                      106 |                                       71% |                                   638 |                                  1,093 |
|                   [Kansas](/us-ks) |              481 |                       674 |                     231 |                        193 |                       66 |                                       40% |                                   559 |                                    869 |
|                   [Oregon](/us-or) |              481 |                       652 |                     155 |                        171 |                       40 |                                       36% |                                   554 |                                    816 |
|                 [Delaware](/us-de) |              609 |                       651 |                     668 |                         42 |                       43 |                                        7% |                                   613 |                                    733 |
|     [District of Columbia](/us-dc) |              611 |                       638 |                     904 |                         27 |                       38 |                                        4% |                                   615 |                                    690 |
|                    [Idaho](/us-id) |              385 |                       588 |                     329 |                        203 |                      113 |                                       53% |                                   486 |                                    738 |
|                     [Utah](/us-ut) |              422 |                       571 |                     178 |                        149 |                       46 |                                       35% |                                   486 |                                    705 |
|                 [Nebraska](/us-ne) |              404 |                       516 |                     266 |                        112 |                       58 |                                       28% |                                   433 |                                    651 |
|            [West Virginia](/us-wv) |              249 |                       469 |                     262 |                        220 |                      123 |                                       88% |                                   354 |                                    662 |
|            [New Hampshire](/us-nh) |              433 |                       458 |                     337 |                         25 |                       18 |                                        6% |                                   435 |                                    519 |
|             [South Dakota](/us-sd) |              173 |                       257 |                     291 |                         84 |                       95 |                                       49% |                                   183 |                                    435 |
|             [North Dakota](/us-nd) |              156 |                       257 |                     337 |                        101 |                      132 |                                       65% |                                   198 |                                    357 |
|                   [Hawaii](/us-hi) |               85 |                       243 |                     172 |                        158 |                      112 |                                      186% |                                   158 |                                    388 |
|                  [Montana](/us-mt) |              117 |                       211 |                     197 |                         94 |                       88 |                                       80% |                                   159 |                                    294 |
|                    [Maine](/us-me) |              134 |                       150 |                     112 |                         16 |                       12 |                                       12% |                                   137 |                                    173 |
|                   [Alaska](/us-ak) |               42 |                        78 |                     107 |                         36 |                       50 |                                       87% |                                    59 |                                    115 |
|                  [Wyoming](/us-wy) |               42 |                        70 |                     121 |                         28 |                       48 |                                       66% |                                    55 |                                     99 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     106 |                          8 |                       13 |                                       14% |                                    60 |                                     79 |
|                     [Guam](/us-gu) |               14 |                        42 |                     252 |                         28 |                      167 |                                      198% |                                    27 |                                     66 |
|           [Virgin Islands](/us-vi) |               17 |                        39 |                     371 |                         22 |                      209 |                                      129% |                                    28 |                                     57 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      51 |                          1 |                       15 |                                       40% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,424 |                   203,979 |                     344 |                     13,555 |                       23 |                                        7% |                               193,530 |                                236,766 |
| [United Kingdom](/united-kingdom) |           41,640 |                    42,225 |                     625 |                        585 |                        9 |                                        1% |                                41,653 |                                 45,393 |
|                   [Italy](/italy) |           35,541 |                    36,137 |                     599 |                        596 |                       10 |                                        2% |                                35,556 |                                 38,789 |
|                 [France](/france) |           30,730 |                    32,066 |                     479 |                      1,336 |                       20 |                                        4% |                                30,759 |                                 39,117 |
|                   [Spain](/spain) |           29,418 |                    31,517 |                     671 |                      2,099 |                       45 |                                        7% |                                29,446 |                                 39,533 |
|               [Belgium](/belgium) |            9,907 |                    10,068 |                     879 |                        161 |                       14 |                                        2% |                                 9,924 |                                 10,663 |
|               [Germany](/germany) |            9,330 |                     9,691 |                     117 |                        361 |                        4 |                                        4% |                                 9,346 |                                 10,928 |
|       [Netherlands](/netherlands) |            6,277 |                     6,461 |                     374 |                        184 |                       11 |                                        3% |                                 6,290 |                                  7,112 |
|               [Romania](/romania) |            3,893 |                     6,049 |                     312 |                      2,156 |                      111 |                                       55% |                                 4,783 |                                  8,012 |
|                 [Sweden](/sweden) |            5,835 |                     5,878 |                     575 |                         43 |                        4 |                                        1% |                                 5,839 |                                  6,024 |
|               [Ukraine](/ukraine) |            2,898 |                     5,847 |                     133 |                      2,949 |                       67 |                                      102% |                                 4,016 |                                  8,878 |
|                 [Poland](/poland) |            2,120 |                     2,824 |                      74 |                        704 |                       19 |                                       33% |                                 2,330 |                                  3,735 |
|       [Switzerland](/switzerland) |            2,013 |                     2,090 |                     243 |                         77 |                        9 |                                        4% |                                 2,025 |                                  2,271 |
|             [Portugal](/portugal) |            1,840 |                     1,989 |                     194 |                        149 |                       15 |                                        8% |                                 1,846 |                                  2,367 |
|               [Ireland](/ireland) |            1,777 |                     1,816 |                     370 |                         39 |                        8 |                                        2% |                                 1,784 |                                  1,937 |
|               [Moldova](/moldova) |            1,063 |                     1,500 |                     371 |                        437 |                      108 |                                       41% |                                 1,233 |                                  1,942 |
|             [Bulgaria](/bulgaria) |              676 |                     1,165 |                     166 |                        489 |                       70 |                                       72% |                                   874 |                                  1,626 |
|               [Belarus](/belarus) |              711 |                       995 |                     105 |                        284 |                       30 |                                       40% |                                   798 |                                  1,400 |
|                 [Serbia](/serbia) |              724 |                       879 |                     126 |                        155 |                       22 |                                       21% |                                   782 |                                  1,037 |
|               [Austria](/austria) |              736 |                       782 |                      88 |                         46 |                        5 |                                        6% |                                   744 |                                    898 |
|               [Hungary](/hungary) |              624 |                       694 |                      71 |                         70 |                        7 |                                       11% |                                   632 |                                    853 |
|               [Denmark](/denmark) |              627 |                       664 |                     114 |                         37 |                        6 |                                        6% |                                   635 |                                    767 |
|               [Czechia](/czechia) |              436 |                       549 |                      52 |                        113 |                       11 |                                       26% |                                   461 |                                    724 |
|                 [Greece](/greece) |              284 |                       484 |                      45 |                        200 |                       19 |                                       70% |                                   359 |                                    722 |
|               [Finland](/finland) |              336 |                       354 |                      64 |                         18 |                        3 |                                        5% |                                   339 |                                    408 |
|               [Croatia](/croatia) |              198 |                       318 |                      78 |                        120 |                       30 |                                       61% |                                   245 |                                    463 |
|                 [Norway](/norway) |              264 |                       285 |                      53 |                         21 |                        4 |                                        8% |                                   268 |                                    335 |
|             [Slovenia](/slovenia) |              135 |                       156 |                      75 |                         21 |                       10 |                                       15% |                                   138 |                                    193 |
|         [Luxembourg](/luxembourg) |              124 |                       143 |                     233 |                         19 |                       31 |                                       15% |                                   130 |                                    171 |
|           [Lithuania](/lithuania) |               86 |                        98 |                      35 |                         12 |                        4 |                                       14% |                                    89 |                                    118 |
|               [Estonia](/estonia) |               64 |                        70 |                      53 |                          6 |                        4 |                                        9% |                                    67 |                                     76 |
|             [Slovakia](/slovakia) |               37 |                        64 |                      12 |                         27 |                        5 |                                       74% |                                    45 |                                    106 |
|                 [Latvia](/latvia) |               35 |                        44 |                      23 |                          9 |                        5 |                                       25% |                                    37 |                                     57 |
|                   [Malta](/malta) |               14 |                        36 |                      73 |                         22 |                       45 |                                      159% |                                    23 |                                     61 |
|                 [Cyprus](/cyprus) |               21 |                        28 |                      32 |                          7 |                        8 |                                       32% |                                    24 |                                     35 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        5 |                                       18% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          472,960 |                   653,414 |                     126 |                    180,454 |                       35 |                                       38% |                               544,399 |                                835,437 |
|                             [Brazil](/brazil) |          126,650 |                   163,710 |                     776 |                     37,060 |                      176 |                                       29% |                               140,686 |                                196,640 |
|                               [India](/india) |           71,642 |                   127,461 |                      93 |                     55,819 |                       41 |                                       78% |                                94,611 |                                185,819 |
|                             [Mexico](/mexico) |           67,558 |                    90,455 |                     709 |                     22,897 |                      179 |                                       34% |                                81,347 |                                104,605 |
|                                 [Peru](/peru) |           29,687 |                    34,525 |                   1,062 |                      4,838 |                      149 |                                       16% |                                30,991 |                                 40,311 |
|                         [Colombia](/colombia) |           21,412 |                    31,568 |                     627 |                     10,156 |                      202 |                                       47% |                                26,222 |                                 39,393 |
|                                 [Iran](/iran) |           22,293 |                    27,132 |                     327 |                      4,839 |                       58 |                                       22% |                                23,725 |                                 32,719 |
|                             [Russia](/russia) |           17,768 |                    22,307 |                     153 |                      4,539 |                       31 |                                       26% |                                18,585 |                                 28,769 |
|                 [South Africa](/south-africa) |           14,889 |                    19,028 |                     325 |                      4,139 |                       71 |                                       28% |                                15,570 |                                 21,583 |
|                       [Argentina](/argentina) |            9,859 |                    18,537 |                     414 |                      8,678 |                      194 |                                       88% |                                13,505 |                                 25,789 |
|                               [Chile](/chile) |           11,592 |                    14,559 |                     768 |                      2,967 |                      157 |                                       26% |                                12,019 |                                 21,317 |
|                       [Indonesia](/indonesia) |            8,025 |                    12,755 |                      47 |                      4,730 |                       17 |                                       59% |                                 9,954 |                                 19,130 |
|                             [Canada](/canada) |            9,194 |                     9,533 |                     255 |                        339 |                        9 |                                        4% |                                 9,220 |                                 10,530 |
|                             [Turkey](/turkey) |            6,673 |                     8,244 |                      99 |                      1,571 |                       19 |                                       24% |                                 6,803 |                                 11,345 |
|                           [Bolivia](/bolivia) |            5,398 |                     7,789 |                     677 |                      2,391 |                      208 |                                       44% |                                 6,369 |                                 10,003 |
|                           [Ecuador](/ecuador) |            6,724 |                     7,666 |                     441 |                        942 |                       54 |                                       14% |                                 6,801 |                                  9,793 |
|                   [Philippines](/philippines) |            3,875 |                     7,133 |                      66 |                      3,258 |                       30 |                                       84% |                                 4,982 |                                 10,539 |
|                         [Pakistan](/pakistan) |            6,345 |                     6,689 |                      31 |                        344 |                        2 |                                        5% |                                 6,366 |                                  7,515 |
|                     [Bangladesh](/bangladesh) |            4,479 |                     6,181 |                      38 |                      1,702 |                       10 |                                       38% |                                 5,025 |                                  8,311 |
|                               [Egypt](/egypt) |            5,530 |                     6,141 |                      61 |                        611 |                        6 |                                       11% |                                 5,567 |                                  8,322 |
|                 [Saudi Arabia](/saudi-arabia) |            4,081 |                     5,286 |                     154 |                      1,205 |                       35 |                                       30% |                                 4,456 |                                  6,680 |
|                               [China](/china) |            4,730 |                     4,802 |                       3 |                         72 |                        0 |                                        2% |                                 4,730 |                                  5,375 |
|                           [Morocco](/morocco) |            1,361 |                     3,459 |                      95 |                      2,098 |                       58 |                                      154% |                                 2,072 |                                  5,456 |
|                         [Honduras](/honduras) |            2,007 |                     2,856 |                     293 |                        849 |                       87 |                                       42% |                                 2,304 |                                  3,808 |
|     [Dominican Republic](/dominican-republic) |            1,845 |                     2,784 |                     259 |                        939 |                       87 |                                       51% |                                 2,161 |                                  3,772 |
|                             [Panama](/panama) |            2,086 |                     2,541 |                     598 |                        455 |                      107 |                                       22% |                                 2,274 |                                  3,082 |
|                           [Algeria](/algeria) |            1,556 |                     2,103 |                      49 |                        547 |                       13 |                                       35% |                                 1,651 |                                  3,072 |
|                               [Japan](/japan) |            1,366 |                     2,053 |                      16 |                        687 |                        5 |                                       50% |                                 1,541 |                                  3,332 |
|                             [Israel](/israel) |            1,019 |                     1,787 |                     210 |                        768 |                       90 |                                       75% |                                 1,259 |                                  2,736 |
|                           [Nigeria](/nigeria) |            1,057 |                     1,264 |                       6 |                        207 |                        1 |                                       20% |                                 1,110 |                                  1,558 |
|                       [Australia](/australia) |              762 |                     1,226 |                      49 |                        464 |                       18 |                                       61% |                                   953 |                                  1,575 |
|                             [Kuwait](/kuwait) |              544 |                       660 |                     157 |                        116 |                       28 |                                       21% |                                   562 |                                    893 |
| [United Arab Emirates](/united-arab-emirates) |              388 |                       460 |                      47 |                         72 |                        7 |                                       19% |                                   393 |                                    647 |
|                   [South Korea](/south-korea) |              336 |                       434 |                       8 |                         98 |                        2 |                                       29% |                                   341 |                                    645 |
|                                 [Cuba](/cuba) |              101 |                       145 |                      13 |                         44 |                        4 |                                       44% |                                   113 |                                    221 |
|                         [Malaysia](/malaysia) |              128 |                       140 |                       4 |                         12 |                        0 |                                        9% |                                   131 |                                    152 |
