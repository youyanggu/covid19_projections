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
* **July 13:** View our [updated historical performance](/about/#historical-performance) (commentary [on Twitter](https://twitter.com/youyanggu/status/1283102532236181504)).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 15 (4am ET):
<p align="center">
  Current Total: <b>136,463</b> deaths | Projected Total: <b>226,700 deaths by Nov 1, 2020</b> (Range: 179-308k) | 206,600 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.3%</b> | Total Infected: <b>7.5%</b> {% include iframe.html %}
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
|              150,000 |         Aug 2, 2020 |
|              175,000 |        Aug 31, 2020 |
|              200,000 |         Oct 8, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        48% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |         <1% |        <1% |          5% |        54% |         78% |        92% |         98% |        99% |
|              200,000 |         <1% |        <1% |         <1% |         8% |         27% |        45% |         56% |        68% |
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
|             *[United States](/us)* |          136,463 |                   226,723 |                     683 |                     90,260 |                                       66% |                               179,647 |                                307,413 |
|                 [New York](/us-ny) |           32,408 |                    33,674 |                   1,731 |                      1,266 |                                        4% |                                32,444 |                                 39,084 |
|               [California](/us-ca) |            7,250 |                    21,379 |                     541 |                     14,129 |                                      195% |                                 9,249 |                                 44,829 |
|                  [Florida](/us-fl) |            4,409 |                    16,886 |                     786 |                     12,477 |                                      283% |                                 7,946 |                                 30,592 |
|               [New Jersey](/us-nj) |           15,582 |                    16,845 |                   1,896 |                      1,263 |                                        8% |                                15,658 |                                 19,078 |
|                    [Texas](/us-tx) |            3,362 |                    14,986 |                     517 |                     11,624 |                                      346% |                                 9,055 |                                 30,167 |
|            [Massachusetts](/us-ma) |            8,340 |                     9,053 |                   1,303 |                        713 |                                        9% |                                 8,460 |                                 10,580 |
|             [Pennsylvania](/us-pa) |            6,931 |                     9,043 |                     706 |                      2,112 |                                       30% |                                 7,124 |                                 14,166 |
|                 [Illinois](/us-il) |            7,419 |                     8,618 |                     680 |                      1,199 |                                       16% |                                 7,625 |                                 10,093 |
|                 [Michigan](/us-mi) |            6,326 |                     7,951 |                     796 |                      1,625 |                                       26% |                                 6,438 |                                 12,391 |
|                  [Georgia](/us-ga) |            3,054 |                     7,189 |                     677 |                      4,135 |                                      135% |                                 3,902 |                                 14,056 |
|                  [Arizona](/us-az) |            2,337 |                     6,472 |                     889 |                      4,135 |                                      177% |                                 4,643 |                                 10,397 |
|                     [Ohio](/us-oh) |            3,069 |                     6,159 |                     527 |                      3,090 |                                      101% |                                 3,304 |                                 13,762 |
|                [Louisiana](/us-la) |            3,445 |                     5,832 |                   1,255 |                      2,387 |                                       69% |                                 3,740 |                                  8,292 |
|                 [Virginia](/us-va) |            1,977 |                     4,583 |                     537 |                      2,606 |                                      132% |                                 2,154 |                                  9,652 |
|              [Connecticut](/us-ct) |            4,372 |                     4,505 |                   1,264 |                        133 |                                        3% |                                 4,395 |                                  4,664 |
|                 [Maryland](/us-md) |            3,334 |                     4,156 |                     687 |                        822 |                                       25% |                                 3,489 |                                  5,492 |
|                  [Alabama](/us-al) |            1,164 |                     4,115 |                     839 |                      2,951 |                                      254% |                                 2,119 |                                  6,818 |
|                  [Indiana](/us-in) |            2,775 |                     4,058 |                     603 |                      1,283 |                                       46% |                                 2,875 |                                  7,715 |
|           [North Carolina](/us-nc) |            1,571 |                     3,875 |                     369 |                      2,304 |                                      147% |                                 1,874 |                                  9,373 |
|           [South Carolina](/us-sc) |              993 |                     3,849 |                     748 |                      2,856 |                                      288% |                                 2,374 |                                  6,330 |
|                [Tennessee](/us-tn) |              767 |                     3,197 |                     468 |                      2,430 |                                      317% |                                 1,786 |                                  6,277 |
|              [Mississippi](/us-ms) |            1,272 |                     2,942 |                     989 |                      1,670 |                                      131% |                                 1,724 |                                  4,678 |
|                 [Colorado](/us-co) |            1,738 |                     2,523 |                     438 |                        785 |                                       45% |                                 1,796 |                                  4,996 |
|                 [Missouri](/us-mo) |            1,114 |                     2,301 |                     375 |                      1,187 |                                      107% |                                 1,247 |                                  5,201 |
|               [Washington](/us-wa) |            1,404 |                     2,244 |                     295 |                        840 |                                       60% |                                 1,478 |                                  4,691 |
|                   [Nevada](/us-nv) |              612 |                     2,224 |                     722 |                      1,612 |                                      263% |                                 1,225 |                                  3,804 |
|                [Minnesota](/us-mn) |            1,548 |                     2,194 |                     389 |                        646 |                                       42% |                                 1,655 |                                  3,417 |
|                 [Kentucky](/us-ky) |              635 |                     1,838 |                     411 |                      1,203 |                                      189% |                                   856 |                                  3,939 |
|                [Wisconsin](/us-wi) |              826 |                     1,655 |                     284 |                        829 |                                      100% |                                   956 |                                  4,467 |
|                     [Iowa](/us-ia) |              757 |                     1,216 |                     385 |                        459 |                                       61% |                                   795 |                                  2,486 |
|             [Rhode Island](/us-ri) |              985 |                     1,135 |                   1,071 |                        150 |                                       15% |                                 1,008 |                                  1,306 |
|                 [Arkansas](/us-ar) |              331 |                     1,099 |                     364 |                        768 |                                      232% |                                   660 |                                  2,112 |
|                     [Utah](/us-ut) |              226 |                     1,081 |                     337 |                        855 |                                      378% |                                   389 |                                  2,415 |
|                   [Oregon](/us-or) |              244 |                     1,068 |                     253 |                        824 |                                      338% |                                   370 |                                  2,564 |
|               [New Mexico](/us-nm) |              551 |                     1,053 |                     502 |                        502 |                                       91% |                                   607 |                                  2,152 |
|                 [Oklahoma](/us-ok) |              428 |                       835 |                     211 |                        407 |                                       95% |                                   501 |                                  1,687 |
|                   [Kansas](/us-ks) |              299 |                       706 |                     242 |                        407 |                                      136% |                                   333 |                                  1,749 |
|     [District of Columbia](/us-dc) |              568 |                       696 |                     986 |                        128 |                                       23% |                                   585 |                                  1,031 |
|                 [Delaware](/us-de) |              518 |                       669 |                     687 |                        151 |                                       29% |                                   535 |                                  1,016 |
|                 [Nebraska](/us-ne) |              286 |                       470 |                     243 |                        184 |                                       64% |                                   356 |                                    652 |
|            [New Hampshire](/us-nh) |              392 |                       451 |                     332 |                         59 |                                       15% |                                   398 |                                    517 |
|                    [Idaho](/us-id) |              103 |                       411 |                     230 |                        308 |                                      299% |                                   138 |                                  1,009 |
|              [Puerto Rico](/us-pr) |              169 |                       289 |                      90 |                        120 |                                       71% |                                   180 |                                    657 |
|                  [Montana](/us-mt) |               34 |                       210 |                     196 |                        176 |                                      518% |                                    85 |                                    468 |
|             [South Dakota](/us-sd) |              109 |                       206 |                     233 |                         97 |                                       89% |                                   135 |                                    316 |
|                    [Maine](/us-me) |              114 |                       192 |                     143 |                         78 |                                       68% |                                   124 |                                    425 |
|             [North Dakota](/us-nd) |               88 |                       184 |                     241 |                         96 |                                      109% |                                   100 |                                    422 |
|            [West Virginia](/us-wv) |               97 |                       153 |                      85 |                         56 |                                       58% |                                   105 |                                    299 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    157 |
|                   [Hawaii](/us-hi) |               22 |                        52 |                      37 |                         30 |                                      136% |                                    24 |                                    126 |
|                   [Alaska](/us-ak) |               17 |                        52 |                      71 |                         35 |                                      206% |                                    19 |                                    146 |
|                  [Wyoming](/us-wy) |               22 |                        42 |                      73 |                         20 |                                       91% |                                    28 |                                     72 |
|           [Virgin Islands](/us-vi) |                6 |                        14 |                     133 |                          8 |                                      133% |                                     6 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          184,833 |                   203,588 |                     343 |                     18,755 |                                       10% |                               188,910 |                                229,556 |
| [United Kingdom](/united-kingdom) |           45,053 |                    49,373 |                     731 |                      4,320 |                                       10% |                                45,600 |                                 53,538 |
|                   [Italy](/italy) |           34,984 |                    35,615 |                     590 |                        631 |                                        2% |                                35,050 |                                 36,202 |
|                 [France](/france) |           30,032 |                    30,714 |                     458 |                        682 |                                        2% |                                30,053 |                                 33,891 |
|                   [Spain](/spain) |           28,409 |                    28,785 |                     613 |                        376 |                                        1% |                                28,440 |                                 29,747 |
|               [Belgium](/belgium) |            9,787 |                     9,975 |                     871 |                        188 |                                        2% |                                 9,804 |                                 10,491 |
|               [Germany](/germany) |            9,078 |                     9,443 |                     114 |                        365 |                                        4% |                                 9,111 |                                 10,246 |
|       [Netherlands](/netherlands) |            6,154 |                     6,264 |                     362 |                        110 |                                        2% |                                 6,173 |                                  6,380 |
|                 [Sweden](/sweden) |            5,545 |                     5,990 |                     586 |                        445 |                                        8% |                                 5,690 |                                  6,177 |
|               [Romania](/romania) |            1,931 |                     4,135 |                     213 |                      2,204 |                                      114% |                                 2,756 |                                  5,871 |
|                 [Serbia](/serbia) |              418 |                     3,992 |                     573 |                      3,574 |                                      855% |                                   992 |                                  9,029 |
|               [Ukraine](/ukraine) |            1,429 |                     2,891 |                      66 |                      1,462 |                                      102% |                                 1,998 |                                  4,406 |
|                 [Poland](/poland) |            1,588 |                     2,466 |                      65 |                        878 |                                       55% |                                 1,858 |                                  3,829 |
|             [Portugal](/portugal) |            1,668 |                     2,257 |                     220 |                        589 |                                       35% |                                 1,758 |                                  3,289 |
|       [Switzerland](/switzerland) |            1,968 |                     2,071 |                     241 |                        103 |                                        5% |                                 1,981 |                                  2,484 |
|               [Ireland](/ireland) |            1,746 |                     1,836 |                     374 |                         90 |                                        5% |                                 1,754 |                                  2,266 |
|               [Moldova](/moldova) |              655 |                     1,214 |                     300 |                        559 |                                       85% |                                   993 |                                  1,635 |
|               [Belarus](/belarus) |              474 |                     1,135 |                     120 |                        661 |                                      139% |                                   628 |                                  2,354 |
|             [Bulgaria](/bulgaria) |              283 |                       966 |                     138 |                        683 |                                      241% |                                   510 |                                  1,619 |
|               [Austria](/austria) |              709 |                       840 |                      95 |                        131 |                                       18% |                                   725 |                                  1,086 |
|               [Hungary](/hungary) |              595 |                       715 |                      73 |                        120 |                                       20% |                                   609 |                                  1,077 |
|               [Denmark](/denmark) |              610 |                       657 |                     113 |                         47 |                                        8% |                                   624 |                                    743 |
|               [Czechia](/czechia) |              355 |                       501 |                      47 |                        146 |                                       41% |                                   365 |                                    744 |
|               [Finland](/finland) |              329 |                       373 |                      68 |                         44 |                                       13% |                                   335 |                                    504 |
|                 [Norway](/norway) |              253 |                       276 |                      51 |                         23 |                                        9% |                                   259 |                                    321 |
|               [Croatia](/croatia) |              120 |                       266 |                      65 |                        146 |                                      122% |                                   145 |                                    396 |
|                 [Greece](/greece) |              193 |                       225 |                      21 |                         32 |                                       17% |                                   204 |                                    288 |
|         [Luxembourg](/luxembourg) |              111 |                       148 |                     241 |                         37 |                                       33% |                                   118 |                                    191 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    160 |
|           [Lithuania](/lithuania) |               79 |                       113 |                      40 |                         34 |                                       43% |                                    86 |                                    183 |
|               [Estonia](/estonia) |               69 |                        87 |                      66 |                         18 |                                       26% |                                    75 |                                    114 |
|                 [Latvia](/latvia) |               31 |                        42 |                      22 |                         11 |                                       35% |                                    33 |                                     95 |
|             [Slovakia](/slovakia) |               28 |                        41 |                       8 |                         13 |                                       46% |                                    28 |                                     87 |
|                 [Cyprus](/cyprus) |               19 |                        31 |                      35 |                         12 |                                       63% |                                    21 |                                     70 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     29 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          243,700 |                   600,501 |                     116 |                    356,801 |                                      146% |                               392,854 |                                985,025 |
|                             [Brazil](/brazil) |           74,133 |                   147,626 |                     699 |                     73,493 |                                       99% |                               114,506 |                                221,322 |
|                               [India](/india) |           24,309 |                   115,117 |                      84 |                     90,808 |                                      374% |                                50,591 |                                241,740 |
|                             [Mexico](/mexico) |           36,327 |                    86,094 |                     675 |                     49,767 |                                      137% |                                65,342 |                                109,752 |
|                                 [Iran](/iran) |           13,211 |                    30,561 |                     369 |                     17,350 |                                      131% |                                21,706 |                                 45,307 |
|                                 [Peru](/peru) |           12,229 |                    23,260 |                     715 |                     11,031 |                                       90% |                                17,320 |                                 31,816 |
|                 [South Africa](/south-africa) |            4,346 |                    23,136 |                     395 |                     18,790 |                                      432% |                                13,367 |                                 39,013 |
|                             [Russia](/russia) |           11,597 |                    22,461 |                     154 |                     10,864 |                                       94% |                                14,464 |                                 38,930 |
|                         [Colombia](/colombia) |            5,787 |                    21,714 |                     431 |                     15,927 |                                      275% |                                14,682 |                                 32,630 |
|                       [Indonesia](/indonesia) |            3,710 |                    13,990 |                      52 |                     10,280 |                                      277% |                                 6,000 |                                 27,929 |
|                               [Chile](/chile) |            7,069 |                    10,920 |                     576 |                      3,851 |                                       54% |                                 7,949 |                                 13,574 |
|                         [Pakistan](/pakistan) |            5,386 |                    10,911 |                      50 |                      5,525 |                                      103% |                                 7,060 |                                 17,326 |
|                               [Egypt](/egypt) |            4,008 |                    10,079 |                     100 |                      6,071 |                                      151% |                                 5,942 |                                 17,239 |
|                             [Canada](/canada) |            8,845 |                     9,793 |                     262 |                        948 |                                       11% |                                 8,940 |                                 11,134 |
|                       [Argentina](/argentina) |            1,968 |                     9,120 |                     204 |                      7,152 |                                      363% |                                 3,975 |                                 17,665 |
|                           [Ecuador](/ecuador) |            5,130 |                     8,265 |                     476 |                      3,135 |                                       61% |                                 5,466 |                                 13,777 |
|                             [Turkey](/turkey) |            5,402 |                     7,027 |                      84 |                      1,625 |                                       30% |                                 5,500 |                                 11,987 |
|                           [Bolivia](/bolivia) |            1,898 |                     6,722 |                     584 |                      4,824 |                                      254% |                                 3,696 |                                 11,798 |
|                     [Bangladesh](/bangladesh) |            2,424 |                     6,325 |                      39 |                      3,901 |                                      161% |                                 3,831 |                                 11,248 |
|                 [Saudi Arabia](/saudi-arabia) |            2,283 |                     6,029 |                     176 |                      3,746 |                                      164% |                                 3,783 |                                  9,366 |
|                               [China](/china) |            4,642 |                     4,647 |                       3 |                          5 |                                        0% |                                 4,642 |                                  4,675 |
|                   [Philippines](/philippines) |            1,603 |                     4,174 |                      39 |                      2,571 |                                      160% |                                 2,105 |                                  9,058 |
|     [Dominican Republic](/dominican-republic) |              910 |                     3,928 |                     366 |                      3,018 |                                      332% |                                 1,444 |                                  8,168 |
|                         [Honduras](/honduras) |              789 |                     3,792 |                     389 |                      3,003 |                                      381% |                                 2,361 |                                  6,591 |
|                             [Panama](/panama) |              960 |                     3,464 |                     816 |                      2,504 |                                      261% |                                 2,483 |                                  5,480 |
|                           [Algeria](/algeria) |            1,028 |                     2,974 |                      69 |                      1,946 |                                      189% |                                 1,405 |                                  7,344 |
|                           [Nigeria](/nigeria) |              754 |                     2,196 |                      11 |                      1,442 |                                      191% |                                 1,044 |                                  5,169 |
|                             [Israel](/israel) |              371 |                     1,930 |                     227 |                      1,559 |                                      420% |                                   541 |                                  6,624 |
|                               [Japan](/japan) |              984 |                     1,601 |                      13 |                        617 |                                       63% |                                   991 |                                  2,919 |
|                             [Kuwait](/kuwait) |              396 |                       718 |                     171 |                        322 |                                       81% |                                   439 |                                  1,356 |
|                           [Morocco](/morocco) |              257 |                       523 |                      14 |                        266 |                                      104% |                                   298 |                                  1,039 |
| [United Arab Emirates](/united-arab-emirates) |              335 |                       489 |                      50 |                        154 |                                       46% |                                   352 |                                    927 |
|                   [South Korea](/south-korea) |              289 |                       342 |                       7 |                         53 |                                       18% |                                   290 |                                    492 |
|                       [Australia](/australia) |              111 |                       311 |                      12 |                        200 |                                      180% |                                   111 |                                  1,299 |
|                         [Malaysia](/malaysia) |              122 |                       156 |                       5 |                         34 |                                       28% |                                   137 |                                    186 |
|                                 [Cuba](/cuba) |               87 |                       106 |                       9 |                         19 |                                       22% |                                    91 |                                    145 |
