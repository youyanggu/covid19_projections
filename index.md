We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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
* **July 13:** View our [updated historical performance](/about/#historical-performance).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 14 (4am ET):
<p align="center">
  Current Total: <b>135,602</b> deaths | Projected Total: <b>225,600 deaths by Nov 1, 2020</b> (Range: 178-309k) | 205,400 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.2%</b> | Total Infected: <b>7.3%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 14, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 20, 2020 |
|              150,000 |         Aug 3, 2020 |
|              175,000 |         Sep 1, 2020 |
|              200,000 |        Oct 10, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        41% |         99% |        99% |         99% |       >99% |        >99% |       >99% |
|              175,000 |         <1% |        <1% |          5% |        50% |         74% |        88% |         95% |        99% |
|              200,000 |         <1% |        <1% |         <1% |         8% |         26% |        43% |         54% |        65% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |          7% |        17% |         25% |        35% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         6% |         11% |        17% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |          1% |         4% |

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
|             *[United States](/us)* |          135,602 |                   225,558 |                     680 |                     89,956 |                                       66% |                               178,090 |                                308,919 |
|                 [New York](/us-ny) |           32,395 |                    33,676 |                   1,731 |                      1,281 |                                        4% |                                32,432 |                                 39,130 |
|               [California](/us-ca) |            7,089 |                    21,842 |                     553 |                     14,753 |                                      208% |                                 9,045 |                                 48,043 |
|               [New Jersey](/us-nj) |           15,560 |                    16,834 |                   1,895 |                      1,274 |                                        8% |                                15,639 |                                 19,073 |
|                  [Florida](/us-fl) |            4,277 |                    15,865 |                     739 |                     11,588 |                                      271% |                                 7,380 |                                 29,962 |
|                    [Texas](/us-tx) |            3,276 |                    14,752 |                     509 |                     11,476 |                                      350% |                                 8,717 |                                 29,971 |
|             [Pennsylvania](/us-pa) |            6,911 |                     9,170 |                     716 |                      2,259 |                                       33% |                                 7,112 |                                 14,612 |
|            [Massachusetts](/us-ma) |            8,330 |                     9,068 |                   1,305 |                        738 |                                        9% |                                 8,458 |                                 10,627 |
|                 [Illinois](/us-il) |            7,394 |                     8,597 |                     678 |                      1,203 |                                       16% |                                 7,605 |                                 10,080 |
|                 [Michigan](/us-mi) |            6,321 |                     7,999 |                     801 |                      1,678 |                                       27% |                                 6,437 |                                 12,552 |
|                  [Georgia](/us-ga) |            3,026 |                     7,212 |                     679 |                      4,186 |                                      138% |                                 3,878 |                                 14,349 |
|                     [Ohio](/us-oh) |            3,064 |                     6,397 |                     547 |                      3,333 |                                      109% |                                 3,314 |                                 13,956 |
|                  [Arizona](/us-az) |            2,246 |                     6,194 |                     851 |                      3,948 |                                      176% |                                 4,471 |                                  8,840 |
|                [Louisiana](/us-la) |            3,423 |                     5,789 |                   1,245 |                      2,366 |                                       69% |                                 3,719 |                                  8,295 |
|                 [Virginia](/us-va) |            1,968 |                     4,608 |                     540 |                      2,640 |                                      134% |                                 2,147 |                                  9,675 |
|              [Connecticut](/us-ct) |            4,371 |                     4,505 |                   1,264 |                        134 |                                        3% |                                 4,394 |                                  4,667 |
|                 [Maryland](/us-md) |            3,325 |                     4,160 |                     688 |                        835 |                                       25% |                                 3,485 |                                  5,511 |
|                  [Indiana](/us-in) |            2,762 |                     4,065 |                     604 |                      1,303 |                                       47% |                                 2,856 |                                  7,776 |
|                  [Alabama](/us-al) |            1,124 |                     3,910 |                     797 |                      2,786 |                                      248% |                                 2,036 |                                  6,688 |
|           [South Carolina](/us-sc) |              972 |                     3,900 |                     757 |                      2,928 |                                      301% |                                 2,365 |                                  6,376 |
|           [North Carolina](/us-nc) |            1,529 |                     3,383 |                     323 |                      1,854 |                                      121% |                                 1,806 |                                  8,747 |
|                [Tennessee](/us-tn) |              749 |                     3,288 |                     481 |                      2,539 |                                      339% |                                 1,789 |                                  6,601 |
|              [Mississippi](/us-ms) |            1,250 |                     2,965 |                     996 |                      1,715 |                                      137% |                                 1,708 |                                  4,700 |
|                 [Colorado](/us-co) |            1,727 |                     2,503 |                     435 |                        776 |                                       45% |                                 1,785 |                                  4,989 |
|               [Washington](/us-wa) |            1,438 |                     2,400 |                     315 |                        962 |                                       67% |                                 1,537 |                                  4,930 |
|                 [Missouri](/us-mo) |            1,105 |                     2,277 |                     371 |                      1,172 |                                      106% |                                 1,238 |                                  5,200 |
|                [Minnesota](/us-mn) |            1,542 |                     2,201 |                     390 |                        659 |                                       43% |                                 1,652 |                                  3,443 |
|                   [Nevada](/us-nv) |              593 |                     2,136 |                     693 |                      1,543 |                                      260% |                                 1,136 |                                  3,756 |
|                 [Kentucky](/us-ky) |              629 |                     1,845 |                     413 |                      1,216 |                                      193% |                                   849 |                                  3,953 |
|                [Wisconsin](/us-wi) |              820 |                     1,693 |                     291 |                        873 |                                      106% |                                   953 |                                  4,649 |
|                     [Iowa](/us-ia) |              755 |                     1,232 |                     390 |                        477 |                                       63% |                                   795 |                                  2,545 |
|                 [Arkansas](/us-ar) |              323 |                     1,157 |                     383 |                        834 |                                      258% |                                   661 |                                  2,372 |
|             [Rhode Island](/us-ri) |              984 |                     1,137 |                   1,073 |                        153 |                                       16% |                                 1,008 |                                  1,310 |
|               [New Mexico](/us-nm) |              548 |                     1,061 |                     506 |                        513 |                                       94% |                                   606 |                                  2,175 |
|                     [Utah](/us-ut) |              216 |                       987 |                     308 |                        771 |                                      357% |                                   310 |                                  2,362 |
|                   [Oregon](/us-or) |              237 |                       982 |                     233 |                        745 |                                      314% |                                   307 |                                  2,441 |
|                 [Oklahoma](/us-ok) |              424 |                       833 |                     211 |                        409 |                                       96% |                                   496 |                                  1,690 |
|                   [Kansas](/us-ks) |              298 |                       744 |                     255 |                        446 |                                      150% |                                   333 |                                  1,837 |
|     [District of Columbia](/us-dc) |              568 |                       699 |                     990 |                        131 |                                       23% |                                   586 |                                  1,036 |
|                 [Delaware](/us-de) |              517 |                       674 |                     692 |                        157 |                                       30% |                                   535 |                                  1,030 |
|                 [Nebraska](/us-ne) |              288 |                       483 |                     250 |                        195 |                                       68% |                                   362 |                                    669 |
|            [New Hampshire](/us-nh) |              391 |                       452 |                     332 |                         61 |                                       16% |                                   398 |                                    519 |
|                    [Idaho](/us-id) |              102 |                       415 |                     232 |                        313 |                                      307% |                                   137 |                                  1,014 |
|              [Puerto Rico](/us-pr) |              167 |                       279 |                      87 |                        112 |                                       67% |                                   177 |                                    638 |
|             [South Dakota](/us-sd) |              109 |                       215 |                     243 |                        106 |                                       97% |                                   137 |                                    346 |
|                    [Maine](/us-me) |              114 |                       194 |                     144 |                         80 |                                       70% |                                   124 |                                    433 |
|                  [Montana](/us-mt) |               32 |                       193 |                     181 |                        161 |                                      503% |                                    80 |                                    478 |
|             [North Dakota](/us-nd) |               87 |                       184 |                     241 |                         97 |                                      111% |                                    99 |                                    430 |
|            [West Virginia](/us-wv) |               97 |                       155 |                      86 |                         58 |                                       60% |                                   105 |                                    307 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    157 |
|                   [Alaska](/us-ak) |               17 |                        52 |                      71 |                         35 |                                      206% |                                    19 |                                    180 |
|                   [Hawaii](/us-hi) |               22 |                        49 |                      35 |                         27 |                                      123% |                                    24 |                                    121 |
|                  [Wyoming](/us-wy) |               21 |                        40 |                      69 |                         19 |                                       90% |                                    27 |                                     70 |
|           [Virgin Islands](/us-vi) |                6 |                        15 |                     143 |                          9 |                                      150% |                                     6 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          184,561 |                   203,240 |                     343 |                     18,679 |                                       10% |                               188,645 |                                230,084 |
| [United Kingdom](/united-kingdom) |           44,915 |                    49,136 |                     728 |                      4,221 |                                        9% |                                45,457 |                                 53,522 |
|                   [Italy](/italy) |           34,967 |                    35,613 |                     590 |                        646 |                                        2% |                                35,035 |                                 36,205 |
|                 [France](/france) |           30,032 |                    30,730 |                     459 |                        698 |                                        2% |                                30,054 |                                 33,963 |
|                   [Spain](/spain) |           28,406 |                    28,791 |                     613 |                        385 |                                        1% |                                28,438 |                                 29,769 |
|               [Belgium](/belgium) |            9,782 |                     9,973 |                     871 |                        191 |                                        2% |                                 9,799 |                                 10,494 |
|               [Germany](/germany) |            9,074 |                     9,450 |                     114 |                        376 |                                        4% |                                 9,109 |                                 10,260 |
|       [Netherlands](/netherlands) |            6,156 |                     6,268 |                     363 |                        112 |                                        2% |                                 6,176 |                                  6,385 |
|                 [Sweden](/sweden) |            5,536 |                     5,992 |                     586 |                        456 |                                        8% |                                 5,689 |                                  6,185 |
|               [Romania](/romania) |            1,901 |                     3,959 |                     204 |                      2,058 |                                      108% |                                 2,684 |                                  5,731 |
|                 [Serbia](/serbia) |              405 |                     3,862 |                     555 |                      3,457 |                                      854% |                                   956 |                                  8,939 |
|               [Ukraine](/ukraine) |            1,415 |                     2,996 |                      68 |                      1,581 |                                      112% |                                 2,037 |                                  4,669 |
|                 [Poland](/poland) |            1,576 |                     2,477 |                      65 |                        901 |                                       57% |                                 1,851 |                                  3,865 |
|             [Portugal](/portugal) |            1,662 |                     2,279 |                     222 |                        617 |                                       37% |                                 1,754 |                                  3,368 |
|       [Switzerland](/switzerland) |            1,968 |                     2,073 |                     241 |                        105 |                                        5% |                                 1,981 |                                  2,503 |
|               [Ireland](/ireland) |            1,746 |                     1,838 |                     375 |                         92 |                                        5% |                                 1,754 |                                  2,274 |
|               [Moldova](/moldova) |              649 |                     1,258 |                     311 |                        609 |                                       94% |                                 1,012 |                                  1,820 |
|               [Belarus](/belarus) |              468 |                     1,151 |                     122 |                        683 |                                      146% |                                   623 |                                  2,400 |
|             [Bulgaria](/bulgaria) |              276 |                       927 |                     132 |                        651 |                                      236% |                                   477 |                                  1,561 |
|               [Austria](/austria) |              708 |                       839 |                      95 |                        131 |                                       19% |                                   724 |                                  1,087 |
|               [Hungary](/hungary) |              595 |                       726 |                      74 |                        131 |                                       22% |                                   610 |                                  1,125 |
|               [Denmark](/denmark) |              610 |                       658 |                     113 |                         48 |                                        8% |                                   625 |                                    745 |
|               [Czechia](/czechia) |              353 |                       491 |                      46 |                        138 |                                       39% |                                   362 |                                    737 |
|               [Finland](/finland) |              329 |                       374 |                      68 |                         45 |                                       14% |                                   335 |                                    525 |
|                 [Norway](/norway) |              253 |                       276 |                      51 |                         23 |                                        9% |                                   260 |                                    322 |
|               [Croatia](/croatia) |              119 |                       263 |                      65 |                        144 |                                      121% |                                   143 |                                    394 |
|                 [Greece](/greece) |              193 |                       226 |                      21 |                         33 |                                       17% |                                   205 |                                    292 |
|         [Luxembourg](/luxembourg) |              111 |                       149 |                     243 |                         38 |                                       34% |                                   118 |                                    191 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    162 |
|           [Lithuania](/lithuania) |               79 |                       114 |                      41 |                         35 |                                       44% |                                    86 |                                    184 |
|               [Estonia](/estonia) |               69 |                        87 |                      66 |                         18 |                                       26% |                                    75 |                                    115 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       32% |                                    33 |                                     92 |
|             [Slovakia](/slovakia) |               28 |                        41 |                       8 |                         13 |                                       46% |                                    28 |                                     87 |
|                 [Cyprus](/cyprus) |               19 |                        31 |                      35 |                         12 |                                       63% |                                    21 |                                     70 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     29 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          239,547 |                   594,723 |                     115 |                    355,176 |                                      148% |                               386,466 |                                985,288 |
|                             [Brazil](/brazil) |           72,833 |                   144,367 |                     684 |                     71,534 |                                       98% |                               111,633 |                                219,441 |
|                               [India](/india) |           23,727 |                   114,562 |                      84 |                     90,835 |                                      383% |                                48,704 |                                243,220 |
|                             [Mexico](/mexico) |           35,491 |                    83,897 |                     658 |                     48,406 |                                      136% |                                64,176 |                                107,868 |
|                                 [Iran](/iran) |           13,032 |                    30,360 |                     366 |                     17,328 |                                      133% |                                21,588 |                                 45,126 |
|                                 [Peru](/peru) |           12,054 |                    23,323 |                     717 |                     11,269 |                                       93% |                                17,203 |                                 32,181 |
|                 [South Africa](/south-africa) |            4,172 |                    22,645 |                     387 |                     18,473 |                                      443% |                                12,775 |                                 38,952 |
|                             [Russia](/russia) |           11,422 |                    22,573 |                     155 |                     11,151 |                                       98% |                                14,324 |                                 39,591 |
|                         [Colombia](/colombia) |            5,634 |                    21,788 |                     433 |                     16,154 |                                      287% |                                15,303 |                                 32,814 |
|                       [Indonesia](/indonesia) |            3,656 |                    14,089 |                      52 |                     10,433 |                                      285% |                                 5,962 |                                 27,975 |
|                         [Pakistan](/pakistan) |            5,320 |                    11,025 |                      51 |                      5,705 |                                      107% |                                 7,052 |                                 17,489 |
|                               [Chile](/chile) |            7,024 |                    11,000 |                     580 |                      3,976 |                                       57% |                                 7,942 |                                 13,650 |
|                               [Egypt](/egypt) |            3,935 |                    10,085 |                     100 |                      6,150 |                                      156% |                                 5,888 |                                 17,307 |
|                             [Canada](/canada) |            8,836 |                     9,804 |                     262 |                        968 |                                       11% |                                 8,935 |                                 11,154 |
|                       [Argentina](/argentina) |            1,903 |                     8,609 |                     192 |                      6,706 |                                      352% |                                 3,889 |                                 17,477 |
|                           [Ecuador](/ecuador) |            5,063 |                     8,170 |                     470 |                      3,107 |                                       61% |                                 5,383 |                                 13,725 |
|                             [Turkey](/turkey) |            5,382 |                     7,035 |                      84 |                      1,653 |                                       31% |                                 5,484 |                                 12,090 |
|                           [Bolivia](/bolivia) |            1,866 |                     6,963 |                     605 |                      5,097 |                                      273% |                                 3,741 |                                 12,070 |
|                     [Bangladesh](/bangladesh) |            2,391 |                     6,561 |                      40 |                      4,170 |                                      174% |                                 3,839 |                                 11,802 |
|                 [Saudi Arabia](/saudi-arabia) |            2,243 |                     6,119 |                     179 |                      3,876 |                                      173% |                                 3,714 |                                  9,495 |
|                               [China](/china) |            4,641 |                     4,646 |                       3 |                          5 |                                        0% |                                 4,641 |                                  4,673 |
|     [Dominican Republic](/dominican-republic) |              903 |                     4,232 |                     394 |                      3,329 |                                      369% |                                 1,460 |                                  8,729 |
|                   [Philippines](/philippines) |            1,599 |                     4,187 |                      39 |                      2,588 |                                      162% |                                 2,114 |                                  9,084 |
|                         [Honduras](/honduras) |              789 |                     4,026 |                     413 |                      3,237 |                                      410% |                                 2,586 |                                  6,905 |
|                             [Panama](/panama) |              932 |                     3,447 |                     812 |                      2,515 |                                      270% |                                 2,463 |                                  5,470 |
|                           [Algeria](/algeria) |            1,018 |                     2,953 |                      69 |                      1,935 |                                      190% |                                 1,398 |                                  7,369 |
|                           [Nigeria](/nigeria) |              744 |                     2,253 |                      11 |                      1,509 |                                      203% |                                 1,054 |                                  5,129 |
|                             [Israel](/israel) |              365 |                     1,779 |                     209 |                      1,414 |                                      387% |                                   517 |                                  6,203 |
|                               [Japan](/japan) |              984 |                     1,606 |                      13 |                        622 |                                       63% |                                   991 |                                  2,929 |
|                             [Kuwait](/kuwait) |              393 |                       717 |                     170 |                        324 |                                       82% |                                   437 |                                  1,362 |
|                           [Morocco](/morocco) |              255 |                       512 |                      14 |                        257 |                                      101% |                                   292 |                                  1,007 |
| [United Arab Emirates](/united-arab-emirates) |              334 |                       488 |                      50 |                        154 |                                       46% |                                   351 |                                    929 |
|                   [South Korea](/south-korea) |              289 |                       343 |                       7 |                         54 |                                       19% |                                   290 |                                    496 |
|                       [Australia](/australia) |              108 |                       296 |                      12 |                        188 |                                      174% |                                   108 |                                  1,245 |
|                         [Malaysia](/malaysia) |              122 |                       157 |                       5 |                         35 |                                       29% |                                   137 |                                    186 |
|                                 [Cuba](/cuba) |               87 |                       106 |                       9 |                         19 |                                       22% |                                    92 |                                    145 |
