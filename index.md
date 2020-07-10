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

* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

For more updates, following Youyang Gu on Twitter: <a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow @youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 10 (11am ET):
<p align="center">
  Current Total: <b>133,287</b> deaths | Projected Total: <b>208,100 deaths by Nov 1, 2020</b> (Range: 170-272k) | 191,700 deaths by Oct 1, 2020<br>
  Currently Infected: <b>0.9%</b> | Total Infected: <b>6.5%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 9, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 22, 2020 |
|              150,000 |         Aug 6, 2020 |
|              175,000 |         Sep 9, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        15% |         82% |        99% |         99% |        99% |         99% |        99% |
|              175,000 |         <1% |        <1% |         <1% |        25% |         46% |        64% |         73% |        83% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          9% |        21% |         30% |        40% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         6% |         11% |        16% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |          3% |         7% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          132,297 |                   204,896 |                     618 |                     72,599 |                                       55% |                               167,646 |                                268,317 |
|                 [New York](/us-ny) |           32,251 |                    33,628 |                   1,729 |                      1,377 |                                        4% |                                32,299 |                                 39,050 |
|               [California](/us-ca) |            6,718 |                    18,956 |                     480 |                     12,238 |                                      182% |                                10,038 |                                 36,618 |
|               [New Jersey](/us-nj) |           15,332 |                    16,756 |                   1,886 |                      1,424 |                                        9% |                                15,461 |                                 19,016 |
|                  [Florida](/us-fl) |            3,889 |                    11,706 |                     545 |                      7,817 |                                      201% |                                 6,266 |                                 21,024 |
|                    [Texas](/us-tx) |            2,875 |                    10,545 |                     364 |                      7,670 |                                      267% |                                 5,966 |                                 19,316 |
|                 [Illinois](/us-il) |            7,309 |                     9,150 |                     722 |                      1,841 |                                       25% |                                 7,710 |                                 11,272 |
|            [Massachusetts](/us-ma) |            8,243 |                     9,051 |                   1,302 |                        808 |                                       10% |                                 8,408 |                                 10,669 |
|             [Pennsylvania](/us-pa) |            6,812 |                     8,858 |                     692 |                      2,046 |                                       30% |                                 7,020 |                                 13,852 |
|                 [Michigan](/us-mi) |            6,262 |                     7,735 |                     775 |                      1,473 |                                       24% |                                 6,335 |                                 11,909 |
|                  [Georgia](/us-ga) |            2,922 |                     6,700 |                     631 |                      3,778 |                                      129% |                                 3,765 |                                 12,932 |
|                  [Arizona](/us-az) |            1,963 |                     5,627 |                     773 |                      3,664 |                                      187% |                                 3,978 |                                  8,036 |
|                     [Ohio](/us-oh) |            2,991 |                     5,383 |                     461 |                      2,392 |                                       80% |                                 3,276 |                                 11,307 |
|                [Louisiana](/us-la) |            3,339 |                     5,380 |                   1,157 |                      2,041 |                                       61% |                                 3,650 |                                  7,692 |
|              [Connecticut](/us-ct) |            4,343 |                     4,594 |                   1,289 |                        251 |                                        6% |                                 4,382 |                                  5,044 |
|                 [Maryland](/us-md) |            3,275 |                     4,167 |                     689 |                        892 |                                       27% |                                 3,460 |                                  5,554 |
|                  [Indiana](/us-in) |            2,732 |                     4,054 |                     602 |                      1,322 |                                       48% |                                 2,847 |                                  7,682 |
|                 [Virginia](/us-va) |            1,905 |                     3,505 |                     411 |                      1,600 |                                       84% |                                 2,054 |                                  7,094 |
|           [South Carolina](/us-sc) |              884 |                     3,245 |                     630 |                      2,361 |                                      267% |                                 1,893 |                                  5,188 |
|                  [Alabama](/us-al) |            1,058 |                     3,207 |                     654 |                      2,149 |                                      203% |                                 1,605 |                                  5,459 |
|           [North Carolina](/us-nc) |            1,462 |                     2,719 |                     259 |                      1,257 |                                       86% |                                 1,703 |                                  6,128 |
|                [Tennessee](/us-tn) |              685 |                     2,713 |                     397 |                      2,028 |                                      296% |                                 1,503 |                                  5,338 |
|              [Mississippi](/us-ms) |            1,188 |                     2,652 |                     891 |                      1,464 |                                      123% |                                 1,565 |                                  4,257 |
|               [Washington](/us-wa) |            1,394 |                     2,496 |                     328 |                      1,102 |                                       79% |                                 1,577 |                                  5,158 |
|                 [Colorado](/us-co) |            1,704 |                     2,460 |                     427 |                        756 |                                       44% |                                 1,765 |                                  4,900 |
|                [Minnesota](/us-mn) |            1,523 |                     2,229 |                     395 |                        706 |                                       46% |                                 1,658 |                                  3,502 |
|                 [Missouri](/us-mo) |            1,069 |                     1,791 |                     292 |                        722 |                                       68% |                                 1,160 |                                  3,571 |
|                   [Nevada](/us-nv) |              553 |                     1,674 |                     543 |                      1,121 |                                      203% |                                   879 |                                  3,058 |
|                [Wisconsin](/us-wi) |              807 |                     1,561 |                     268 |                        754 |                                       93% |                                   931 |                                  3,993 |
|                 [Kentucky](/us-ky) |              608 |                     1,333 |                     298 |                        725 |                                      119% |                                   703 |                                  3,100 |
|             [Rhode Island](/us-ri) |              971 |                     1,216 |                   1,148 |                        245 |                                       25% |                                 1,033 |                                  1,514 |
|                 [Arkansas](/us-ar) |              305 |                     1,120 |                     371 |                        815 |                                      267% |                                   456 |                                  2,303 |
|               [New Mexico](/us-nm) |              527 |                       998 |                     476 |                        471 |                                       89% |                                   590 |                                  2,033 |
|                     [Iowa](/us-ia) |              736 |                       981 |                     311 |                        245 |                                       33% |                                   761 |                                  1,649 |
|                     [Utah](/us-ut) |              201 |                       836 |                     261 |                        635 |                                      316% |                                   316 |                                  1,906 |
|                   [Oregon](/us-or) |              224 |                       783 |                     186 |                        559 |                                      250% |                                   286 |                                  1,864 |
|                 [Oklahoma](/us-ok) |              407 |                       721 |                     182 |                        314 |                                       77% |                                   444 |                                  1,658 |
|     [District of Columbia](/us-dc) |              564 |                       704 |                     998 |                        140 |                                       25% |                                   586 |                                  1,042 |
|                 [Delaware](/us-de) |              515 |                       673 |                     691 |                        158 |                                       31% |                                   535 |                                  1,039 |
|            [New Hampshire](/us-nh) |              386 |                       585 |                     430 |                        199 |                                       52% |                                   418 |                                    938 |
|                   [Kansas](/us-ks) |              289 |                       471 |                     162 |                        182 |                                       63% |                                   308 |                                    998 |
|                 [Nebraska](/us-ne) |              282 |                       457 |                     236 |                        175 |                                       62% |                                   338 |                                    654 |
|                    [Idaho](/us-id) |               98 |                       309 |                     173 |                        211 |                                      215% |                                   115 |                                    727 |
|              [Puerto Rico](/us-pr) |              159 |                       248 |                      78 |                         89 |                                       56% |                                   168 |                                    551 |
|             [South Dakota](/us-sd) |               98 |                       183 |                     207 |                         85 |                                       87% |                                   120 |                                    289 |
|                    [Maine](/us-me) |              110 |                       177 |                     132 |                         67 |                                       61% |                                   119 |                                    374 |
|             [North Dakota](/us-nd) |               85 |                       128 |                     168 |                         43 |                                       51% |                                   100 |                                    190 |
|            [West Virginia](/us-wv) |               95 |                       126 |                      70 |                         31 |                                       33% |                                   101 |                                    202 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    150 |
|                   [Alaska](/us-ak) |               17 |                        66 |                      90 |                         49 |                                      288% |                                    19 |                                    198 |
|                  [Montana](/us-mt) |               23 |                        60 |                      56 |                         37 |                                      161% |                                    25 |                                    148 |
|                  [Wyoming](/us-wy) |               21 |                        43 |                      74 |                         22 |                                      105% |                                    27 |                                     76 |
|                   [Hawaii](/us-hi) |               19 |                        31 |                      22 |                         12 |                                       63% |                                    21 |                                     64 |
|           [Virgin Islands](/us-vi) |                6 |                        14 |                     133 |                          8 |                                      133% |                                     6 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     5 |                                     24 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          183,587 |                   201,646 |                     340 |                     18,059 |                                       10% |                               187,737 |                                227,077 |
| [United Kingdom](/united-kingdom) |           44,602 |                    49,223 |                     729 |                      4,621 |                                       10% |                                45,259 |                                 53,710 |
|                   [Italy](/italy) |           34,914 |                    35,745 |                     592 |                        831 |                                        2% |                                35,027 |                                 36,602 |
|                 [France](/france) |           29,936 |                    30,673 |                     458 |                        737 |                                        2% |                                29,962 |                                 34,121 |
|                   [Spain](/spain) |           28,396 |                    29,023 |                     618 |                        627 |                                        2% |                                28,433 |                                 30,933 |
|               [Belgium](/belgium) |            9,776 |                    10,050 |                     877 |                        274 |                                        3% |                                 9,799 |                                 10,863 |
|               [Germany](/germany) |            9,046 |                     9,480 |                     114 |                        434 |                                        5% |                                 9,093 |                                 10,513 |
|       [Netherlands](/netherlands) |            6,154 |                     6,314 |                     365 |                        160 |                                        3% |                                 6,176 |                                  6,510 |
|                 [Sweden](/sweden) |            5,482 |                     5,996 |                     586 |                        514 |                                        9% |                                 5,660 |                                  6,213 |
|               [Romania](/romania) |            1,817 |                     4,352 |                     224 |                      2,535 |                                      140% |                                 2,751 |                                  6,060 |
|               [Ukraine](/ukraine) |            1,323 |                     3,157 |                      72 |                      1,834 |                                      139% |                                 1,989 |                                  4,877 |
|                 [Poland](/poland) |            1,542 |                     2,943 |                      78 |                      1,401 |                                       91% |                                 1,885 |                                  5,312 |
|             [Portugal](/portugal) |            1,631 |                     2,229 |                     217 |                        598 |                                       37% |                                 1,702 |                                  3,323 |
|       [Switzerland](/switzerland) |            1,966 |                     2,071 |                     241 |                        105 |                                        5% |                                 1,980 |                                  2,489 |
|               [Ireland](/ireland) |            1,738 |                     1,830 |                     373 |                         92 |                                        5% |                                 1,746 |                                  2,252 |
|               [Moldova](/moldova) |              614 |                     1,353 |                     335 |                        739 |                                      120% |                                 1,039 |                                  1,971 |
|               [Belarus](/belarus) |              443 |                     1,164 |                     123 |                        721 |                                      163% |                                   610 |                                  2,408 |
|             [Bulgaria](/bulgaria) |              259 |                       918 |                     131 |                        659 |                                      254% |                                   469 |                                  1,539 |
|               [Austria](/austria) |              706 |                       836 |                      94 |                        130 |                                       18% |                                   722 |                                  1,076 |
|               [Hungary](/hungary) |              589 |                       718 |                      73 |                        129 |                                       22% |                                   605 |                                  1,099 |
|                 [Serbia](/serbia) |              341 |                       701 |                     101 |                        360 |                                      106% |                                   428 |                                  1,197 |
|               [Denmark](/denmark) |              609 |                       689 |                     119 |                         80 |                                       13% |                                   625 |                                    902 |
|               [Czechia](/czechia) |              351 |                       489 |                      46 |                        138 |                                       39% |                                   360 |                                    722 |
|               [Finland](/finland) |              329 |                       376 |                      68 |                         47 |                                       14% |                                   335 |                                    532 |
|                 [Norway](/norway) |              251 |                       274 |                      51 |                         23 |                                        9% |                                   258 |                                    319 |
|                 [Greece](/greece) |              193 |                       228 |                      21 |                         35 |                                       18% |                                   205 |                                    295 |
|               [Croatia](/croatia) |              114 |                       225 |                      55 |                        111 |                                       97% |                                   129 |                                    363 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    163 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    147 |
|           [Lithuania](/lithuania) |               79 |                       117 |                      42 |                         38 |                                       48% |                                    87 |                                    187 |
|               [Estonia](/estonia) |               69 |                        90 |                      68 |                         21 |                                       30% |                                    76 |                                    132 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        39 |                      20 |                          9 |                                       30% |                                    32 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        32 |                      37 |                         13 |                                       68% |                                    21 |                                     68 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     27 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          221,744 |                   604,906 |                     117 |                    383,162 |                                      173% |                               379,194 |                              1,027,634 |
|                             [Brazil](/brazil) |           67,964 |                   145,166 |                     688 |                     77,202 |                                      114% |                               110,667 |                                224,738 |
|                               [India](/india) |           21,129 |                   117,364 |                      86 |                     96,235 |                                      455% |                                46,557 |                                271,746 |
|                             [Mexico](/mexico) |           32,796 |                    87,163 |                     683 |                     54,367 |                                      166% |                                64,288 |                                110,094 |
|                                 [Iran](/iran) |           12,084 |                    25,549 |                     308 |                     13,465 |                                      111% |                                19,331 |                                 39,900 |
|                                 [Peru](/peru) |           11,133 |                    23,302 |                     717 |                     12,169 |                                      109% |                                16,655 |                                 32,919 |
|                             [Russia](/russia) |           10,650 |                    22,889 |                     157 |                     12,239 |                                      115% |                                13,934 |                                 44,514 |
|                         [Colombia](/colombia) |            4,606 |                    20,331 |                     404 |                     15,725 |                                      341% |                                12,506 |                                 32,043 |
|                 [South Africa](/south-africa) |            3,602 |                    18,566 |                     317 |                     14,964 |                                      415% |                                 9,650 |                                 29,960 |
|                               [Egypt](/egypt) |            3,564 |                    14,798 |                     147 |                     11,234 |                                      315% |                                 8,554 |                                 22,799 |
|                       [Indonesia](/indonesia) |            3,359 |                    13,402 |                      50 |                     10,043 |                                      299% |                                 6,101 |                                 25,657 |
|                         [Pakistan](/pakistan) |            4,983 |                    13,150 |                      61 |                      8,167 |                                      164% |                                 8,014 |                                 20,992 |
|                               [Chile](/chile) |            6,573 |                    12,292 |                     649 |                      5,719 |                                       87% |                                 7,728 |                                 16,925 |
|                       [Argentina](/argentina) |            1,694 |                    11,978 |                     267 |                     10,284 |                                      607% |                                 4,467 |                                 20,268 |
|                             [Canada](/canada) |            8,786 |                    10,318 |                     276 |                      1,532 |                                       17% |                                 9,002 |                                 13,704 |
|                           [Ecuador](/ecuador) |            4,873 |                     8,854 |                     510 |                      3,981 |                                       82% |                                 5,307 |                                 14,576 |
|                 [Saudi Arabia](/saudi-arabia) |            2,059 |                     8,782 |                     256 |                      6,723 |                                      327% |                                 5,121 |                                 12,628 |
|                     [Bangladesh](/bangladesh) |            2,197 |                     8,061 |                      49 |                      5,864 |                                      267% |                                 4,830 |                                 15,221 |
|                             [Turkey](/turkey) |            5,282 |                     6,972 |                      84 |                      1,690 |                                       32% |                                 5,399 |                                 12,283 |
|                           [Bolivia](/bolivia) |            1,577 |                     6,759 |                     587 |                      5,182 |                                      329% |                                 3,410 |                                 12,094 |
|                               [China](/china) |            4,641 |                     4,647 |                       3 |                          6 |                                        0% |                                 4,641 |                                  4,678 |
|                         [Honduras](/honduras) |              694 |                     4,076 |                     418 |                      3,382 |                                      487% |                                 2,577 |                                  7,158 |
|     [Dominican Republic](/dominican-republic) |              829 |                     3,873 |                     361 |                      3,044 |                                      367% |                                 1,172 |                                  8,463 |
|                             [Panama](/panama) |              819 |                     3,391 |                     799 |                      2,572 |                                      314% |                                 2,397 |                                  5,464 |
|                   [Philippines](/philippines) |            1,314 |                     3,124 |                      29 |                      1,810 |                                      138% |                                 1,476 |                                  6,841 |
|                           [Algeria](/algeria) |              978 |                     2,962 |                      69 |                      1,984 |                                      203% |                                 1,370 |                                  7,555 |
|                           [Nigeria](/nigeria) |              684 |                     2,299 |                      11 |                      1,615 |                                      236% |                                   972 |                                  5,381 |
|                               [Japan](/japan) |              982 |                     1,566 |                      12 |                        584 |                                       59% |                                   989 |                                  2,769 |
|                             [Israel](/israel) |              344 |                       783 |                      92 |                        439 |                                      128% |                                   410 |                                  1,291 |
|                             [Kuwait](/kuwait) |              379 |                       722 |                     172 |                        343 |                                       91% |                                   427 |                                  1,394 |
|                           [Morocco](/morocco) |              242 |                       485 |                      13 |                        243 |                                      100% |                                   273 |                                    966 |
| [United Arab Emirates](/united-arab-emirates) |              327 |                       477 |                      49 |                        150 |                                       46% |                                   347 |                                    909 |
|                   [South Korea](/south-korea) |              287 |                       341 |                       7 |                         54 |                                       19% |                                   288 |                                    487 |
|                       [Australia](/australia) |              106 |                       201 |                       8 |                         95 |                                       90% |                                   106 |                                    882 |
|                         [Malaysia](/malaysia) |              121 |                       157 |                       5 |                         36 |                                       30% |                                   137 |                                    189 |
|                                 [Cuba](/cuba) |               86 |                       106 |                       9 |                         20 |                                       23% |                                    91 |                                    146 |
