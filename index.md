We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >97% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5-8x higher than the reported cases.

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
* **July 23:** We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* **July 21:** View our [updated historical performance](/about/#historical-performance).
* **July 8:** We have extended our projections through November 1, 2020. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 26 (6am ET):
<p align="center">
  Current Total: <b>146,457</b> deaths | Projected Total: <b>222,000 deaths by Nov 1, 2020</b> (Range: 190-272k)<br>
  Currently Infected: <b>2.0%</b> | Total Infected: <b>10.8%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 26, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 29, 2020 |
|              175,000 |        Aug 25, 2020 |
|              200,000 |        Sep 29, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          8% |        82% |         99% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         7% |         28% |        53% |         69% |        81% |
|              225,000 |        <1% |         <1% |        <1% |          3% |        11% |         20% |        32% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         1% |          5% |         9% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          146,457 |                   222,047 |                     669 |                     75,590 |                                       52% |                               190,111 |                                271,556 |
|                 [New York](/us-ny) |           32,608 |                    33,696 |                   1,732 |                      1,088 |                                        3% |                                32,660 |                                 38,298 |
|               [New Jersey](/us-nj) |           15,776 |                    16,638 |                   1,873 |                        862 |                                        5% |                                15,882 |                                 18,112 |
|               [California](/us-ca) |            8,408 |                    16,631 |                     421 |                      8,223 |                                       98% |                                11,564 |                                 24,712 |
|                    [Texas](/us-tx) |            4,990 |                    16,360 |                     564 |                     11,370 |                                      228% |                                10,603 |                                 24,272 |
|                  [Florida](/us-fl) |            5,777 |                    14,106 |                     657 |                      8,329 |                                      144% |                                 9,691 |                                 21,005 |
|             [Pennsylvania](/us-pa) |            7,124 |                     9,474 |                     740 |                      2,350 |                                       33% |                                 7,443 |                                 13,824 |
|                 [Illinois](/us-il) |            7,589 |                     9,259 |                     731 |                      1,670 |                                       22% |                                 7,905 |                                 11,668 |
|            [Massachusetts](/us-ma) |            8,510 |                     9,112 |                   1,311 |                        602 |                                        7% |                                 8,589 |                                 10,158 |
|                  [Georgia](/us-ga) |            3,494 |                     7,741 |                     729 |                      4,247 |                                      122% |                                 4,810 |                                 13,119 |
|                 [Michigan](/us-mi) |            6,400 |                     7,273 |                     728 |                        873 |                                       14% |                                 6,519 |                                  9,297 |
|                  [Arizona](/us-az) |            3,286 |                     7,055 |                     969 |                      3,769 |                                      115% |                                 5,231 |                                  9,717 |
|                     [Ohio](/us-oh) |            3,297 |                     5,928 |                     507 |                      2,631 |                                       80% |                                 3,954 |                                 10,318 |
|                [Louisiana](/us-la) |            3,715 |                     5,564 |                   1,197 |                      1,849 |                                       50% |                                 4,175 |                                  8,192 |
|                 [Maryland](/us-md) |            3,433 |                     4,895 |                     810 |                      1,462 |                                       43% |                                 3,686 |                                  7,838 |
|              [Connecticut](/us-ct) |            4,413 |                     4,641 |                   1,302 |                        228 |                                        5% |                                 4,451 |                                  5,092 |
|                  [Indiana](/us-in) |            2,895 |                     4,436 |                     659 |                      1,541 |                                       53% |                                 3,130 |                                  7,613 |
|           [South Carolina](/us-sc) |            1,465 |                     4,413 |                     857 |                      2,948 |                                      201% |                                 2,912 |                                  6,571 |
|           [North Carolina](/us-nc) |            1,811 |                     3,820 |                     364 |                      2,009 |                                      111% |                                 2,503 |                                  6,103 |
|                 [Virginia](/us-va) |            2,075 |                     3,704 |                     434 |                      1,629 |                                       78% |                                 2,324 |                                  7,121 |
|                  [Alabama](/us-al) |            1,456 |                     3,549 |                     724 |                      2,093 |                                      144% |                                 2,431 |                                  5,332 |
|                 [Colorado](/us-co) |            1,794 |                     2,840 |                     493 |                      1,046 |                                       58% |                                 2,021 |                                  4,938 |
|              [Mississippi](/us-ms) |            1,478 |                     2,691 |                     904 |                      1,213 |                                       82% |                                 2,001 |                                  3,841 |
|                [Minnesota](/us-mn) |            1,611 |                     2,418 |                     429 |                        807 |                                       50% |                                 1,793 |                                  3,901 |
|                [Tennessee](/us-tn) |              964 |                     2,415 |                     353 |                      1,451 |                                      151% |                                 1,639 |                                  3,657 |
|                 [Missouri](/us-mo) |            1,200 |                     2,270 |                     370 |                      1,070 |                                       89% |                                 1,433 |                                  4,128 |
|                   [Nevada](/us-nv) |              732 |                     2,160 |                     701 |                      1,428 |                                      195% |                                 1,323 |                                  3,605 |
|               [Washington](/us-wa) |            1,494 |                     2,060 |                     270 |                        566 |                                       38% |                                 1,570 |                                  3,073 |
|                [Wisconsin](/us-wi) |              891 |                     1,860 |                     320 |                        969 |                                      109% |                                 1,090 |                                  3,792 |
|                 [Kentucky](/us-ky) |              696 |                     1,704 |                     381 |                      1,008 |                                      145% |                                   925 |                                  3,507 |
|                     [Iowa](/us-ia) |              826 |                     1,471 |                     466 |                        645 |                                       78% |                                   998 |                                  2,539 |
|             [Rhode Island](/us-ri) |            1,002 |                     1,174 |                   1,108 |                        172 |                                       17% |                                 1,032 |                                  1,399 |
|               [New Mexico](/us-nm) |              607 |                     1,102 |                     526 |                        495 |                                       82% |                                   689 |                                  1,897 |
|                 [Oklahoma](/us-ok) |              496 |                     1,035 |                     262 |                        539 |                                      109% |                                   665 |                                  1,740 |
|                 [Arkansas](/us-ar) |              399 |                       950 |                     315 |                        551 |                                      138% |                                   617 |                                  1,523 |
|              [Puerto Rico](/us-pr) |              201 |                       915 |                     286 |                        714 |                                      355% |                                   357 |                                  2,087 |
|                   [Oregon](/us-or) |              282 |                       855 |                     203 |                        573 |                                      203% |                                   459 |                                  1,651 |
|                     [Utah](/us-ut) |              274 |                       800 |                     249 |                        526 |                                      192% |                                   473 |                                  1,361 |
|                    [Idaho](/us-id) |              144 |                       703 |                     393 |                        559 |                                      388% |                                   345 |                                  1,306 |
|                 [Delaware](/us-de) |              579 |                       677 |                     695 |                         98 |                                       17% |                                   594 |                                    845 |
|     [District of Columbia](/us-dc) |              581 |                       644 |                     913 |                         63 |                                       11% |                                   594 |                                    753 |
|                   [Kansas](/us-ks) |              329 |                       618 |                     212 |                        289 |                                       88% |                                   409 |                                  1,034 |
|            [New Hampshire](/us-nh) |              409 |                       543 |                     399 |                        134 |                                       33% |                                   424 |                                    778 |
|                 [Nebraska](/us-ne) |              316 |                       510 |                     264 |                        194 |                                       62% |                                   352 |                                    821 |
|             [North Dakota](/us-nd) |               99 |                       220 |                     289 |                        121 |                                      123% |                                   131 |                                    403 |
|             [South Dakota](/us-sd) |              122 |                       218 |                     246 |                         96 |                                       79% |                                   140 |                                    356 |
|                  [Montana](/us-mt) |               46 |                       212 |                     199 |                        166 |                                      362% |                                   100 |                                    420 |
|            [West Virginia](/us-wv) |              103 |                       186 |                     104 |                         83 |                                       81% |                                   124 |                                    361 |
|                    [Maine](/us-me) |              119 |                       174 |                     130 |                         55 |                                       46% |                                   130 |                                    259 |
|                   [Hawaii](/us-hi) |               26 |                        88 |                      62 |                         62 |                                      239% |                                    36 |                                    224 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     121 |                         20 |                                       35% |                                    62 |                                    101 |
|                   [Alaska](/us-ak) |               20 |                        73 |                     100 |                         53 |                                      265% |                                    35 |                                    155 |
|                  [Wyoming](/us-wy) |               25 |                        51 |                      88 |                         26 |                                      103% |                                    37 |                                     85 |
|           [Virgin Islands](/us-vi) |                7 |                        24 |                     225 |                         17 |                                      237% |                                    10 |                                     55 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                       98% |                                     6 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      102% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,049 |                   201,995 |                     341 |                     14,946 |                                        8% |                               190,725 |                                229,836 |
| [United Kingdom](/united-kingdom) |           45,823 |                    49,364 |                     731 |                      3,541 |                                        8% |                                46,017 |                                 56,961 |
|                   [Italy](/italy) |           35,102 |                    35,691 |                     591 |                        589 |                                        2% |                                35,125 |                                 37,293 |
|                 [France](/france) |           30,195 |                    30,843 |                     460 |                        648 |                                        2% |                                30,223 |                                 34,164 |
|                   [Spain](/spain) |           28,432 |                    28,918 |                     616 |                        486 |                                        2% |                                28,454 |                                 31,123 |
|               [Belgium](/belgium) |            9,821 |                     9,903 |                     864 |                         82 |                                        1% |                                 9,837 |                                 10,200 |
|               [Germany](/germany) |            9,124 |                     9,406 |                     113 |                        282 |                                        3% |                                 9,136 |                                 10,571 |
|       [Netherlands](/netherlands) |            6,159 |                     6,231 |                     361 |                         72 |                                        1% |                                 6,168 |                                  6,462 |
|                 [Sweden](/sweden) |            5,697 |                     6,137 |                     600 |                        440 |                                        8% |                                 5,802 |                                  6,872 |
|               [Romania](/romania) |            2,165 |                     4,428 |                     228 |                      2,263 |                                      105% |                                 3,181 |                                  6,845 |
|               [Ukraine](/ukraine) |            1,610 |                     3,282 |                      75 |                      1,672 |                                      104% |                                 2,292 |                                  5,030 |
|                 [Poland](/poland) |            1,664 |                     2,206 |                      58 |                        542 |                                       33% |                                 1,734 |                                  3,194 |
|             [Portugal](/portugal) |            1,716 |                     2,201 |                     214 |                        485 |                                       28% |                                 1,770 |                                  2,977 |
|       [Switzerland](/switzerland) |            1,977 |                     2,054 |                     239 |                         77 |                                        4% |                                 1,989 |                                  2,249 |
|               [Ireland](/ireland) |            1,764 |                     1,851 |                     377 |                         87 |                                        5% |                                 1,776 |                                  2,146 |
|                 [Serbia](/serbia) |              518 |                     1,494 |                     215 |                        976 |                                      188% |                                   954 |                                  2,440 |
|               [Moldova](/moldova) |              732 |                     1,451 |                     359 |                        719 |                                       98% |                                   992 |                                  2,118 |
|               [Belarus](/belarus) |              530 |                     1,005 |                     106 |                        475 |                                       90% |                                   814 |                                  1,463 |
|             [Bulgaria](/bulgaria) |              338 |                       915 |                     131 |                        577 |                                      171% |                                   544 |                                  1,618 |
|               [Austria](/austria) |              712 |                       783 |                      88 |                         71 |                                       10% |                                   728 |                                    908 |
|               [Hungary](/hungary) |              596 |                       695 |                      71 |                         99 |                                       17% |                                   610 |                                    900 |
|               [Denmark](/denmark) |              613 |                       691 |                     119 |                         78 |                                       13% |                                   630 |                                    816 |
|               [Czechia](/czechia) |              369 |                       568 |                      53 |                        199 |                                       54% |                                   411 |                                    917 |
|               [Finland](/finland) |              329 |                       381 |                      69 |                         52 |                                       16% |                                   341 |                                    481 |
|               [Croatia](/croatia) |              133 |                       341 |                      84 |                        208 |                                      156% |                                   211 |                                    598 |
|                 [Norway](/norway) |              255 |                       283 |                      53 |                         28 |                                       11% |                                   262 |                                    330 |
|                 [Greece](/greece) |              201 |                       246 |                      23 |                         45 |                                       22% |                                   211 |                                    304 |
|         [Luxembourg](/luxembourg) |              112 |                       158 |                     258 |                         46 |                                       41% |                                   128 |                                    218 |
|             [Slovenia](/slovenia) |              116 |                       139 |                      67 |                         23 |                                       20% |                                   120 |                                    177 |
|           [Lithuania](/lithuania) |               80 |                       105 |                      38 |                         25 |                                       31% |                                    84 |                                    143 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    76 |                                    123 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       32% |                                    33 |                                     60 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       28% |                                    29 |                                     53 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       51% |                                    22 |                                     43 |
|                   [Malta](/malta) |                9 |                        14 |                      29 |                          5 |                                       60% |                                    11 |                                     18 |
|               [Iceland](/iceland) |               10 |                        14 |                      40 |                          4 |                                       36% |                                    10 |                                     21 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          292,900 |                   660,183 |                     127 |                    367,283 |                                      125% |                               421,690 |                              1,053,058 |
|                             [Brazil](/brazil) |           86,449 |                   171,612 |                     813 |                     85,163 |                                       99% |                               119,321 |                                263,678 |
|                               [India](/india) |           32,060 |                   138,426 |                     101 |                    106,366 |                                      332% |                                64,057 |                                227,400 |
|                             [Mexico](/mexico) |           42,645 |                    84,565 |                     663 |                     41,920 |                                       98% |                                61,610 |                                150,054 |
|                         [Colombia](/colombia) |            8,269 |                    29,126 |                     579 |                     20,857 |                                      252% |                                19,046 |                                 41,710 |
|                                 [Iran](/iran) |           15,484 |                    27,556 |                     332 |                     12,072 |                                       78% |                                21,270 |                                 37,332 |
|                                 [Peru](/peru) |           17,843 |                    27,371 |                     842 |                      9,528 |                                       53% |                                19,911 |                                 42,956 |
|                 [South Africa](/south-africa) |            6,655 |                    27,157 |                     464 |                     20,502 |                                      308% |                                13,993 |                                 38,657 |
|                             [Russia](/russia) |           13,172 |                    23,212 |                     159 |                     10,040 |                                       76% |                                15,047 |                                 39,251 |
|                       [Indonesia](/indonesia) |            4,714 |                    17,132 |                      63 |                     12,418 |                                      263% |                                 8,564 |                                 31,895 |
|                               [Chile](/chile) |            9,020 |                    15,202 |                     802 |                      6,182 |                                       69% |                                 9,871 |                                 26,491 |
|                       [Argentina](/argentina) |            2,893 |                    11,173 |                     250 |                      8,280 |                                      286% |                                 6,231 |                                 17,162 |
|                             [Canada](/canada) |            8,929 |                     9,426 |                     252 |                        497 |                                        6% |                                 8,956 |                                 10,512 |
|                         [Pakistan](/pakistan) |            5,822 |                     8,160 |                      38 |                      2,338 |                                       40% |                                 6,484 |                                 11,627 |
|                           [Ecuador](/ecuador) |            5,507 |                     7,922 |                     456 |                      2,415 |                                       44% |                                 5,725 |                                 11,398 |
|                               [Egypt](/egypt) |            4,558 |                     7,777 |                      77 |                      3,219 |                                       71% |                                 5,240 |                                 13,095 |
|                             [Turkey](/turkey) |            5,596 |                     6,704 |                      80 |                      1,108 |                                       20% |                                 5,719 |                                  8,798 |
|                           [Bolivia](/bolivia) |            2,535 |                     6,472 |                     562 |                      3,937 |                                      155% |                                 4,299 |                                  9,657 |
|                     [Bangladesh](/bangladesh) |            2,874 |                     5,542 |                      34 |                      2,668 |                                       93% |                                 3,336 |                                  9,848 |
|                 [Saudi Arabia](/saudi-arabia) |            2,703 |                     5,157 |                     150 |                      2,454 |                                       91% |                                 3,634 |                                  8,012 |
|                   [Philippines](/philippines) |            1,897 |                     5,080 |                      47 |                      3,183 |                                      168% |                                 2,259 |                                 11,218 |
|                               [China](/china) |            4,652 |                     4,697 |                       3 |                         45 |                                        1% |                                 4,652 |                                  5,032 |
|                         [Honduras](/honduras) |            1,098 |                     3,867 |                     397 |                      2,769 |                                      252% |                                 2,233 |                                  6,282 |
|                             [Panama](/panama) |            1,275 |                     3,402 |                     801 |                      2,127 |                                      167% |                                 2,320 |                                  5,066 |
|                           [Algeria](/algeria) |            1,146 |                     2,313 |                      54 |                      1,167 |                                      102% |                                 1,339 |                                  4,598 |
|     [Dominican Republic](/dominican-republic) |            1,055 |                     2,232 |                     208 |                      1,177 |                                      112% |                                 1,404 |                                  3,655 |
|                           [Nigeria](/nigeria) |              856 |                     1,708 |                       8 |                        852 |                                      100% |                                   954 |                                  3,822 |
|                             [Israel](/israel) |              457 |                     1,555 |                     183 |                      1,098 |                                      240% |                                   839 |                                  2,623 |
|                       [Australia](/australia) |              155 |                     1,482 |                      59 |                      1,327 |                                      856% |                                   556 |                                  3,241 |
|                               [Japan](/japan) |              996 |                     1,452 |                      11 |                        456 |                                       46% |                                 1,005 |                                  3,200 |
|                           [Morocco](/morocco) |              305 |                       922 |                      25 |                        617 |                                      202% |                                   480 |                                  1,852 |
|                             [Kuwait](/kuwait) |              429 |                       667 |                     159 |                        238 |                                       56% |                                   458 |                                  1,215 |
| [United Arab Emirates](/united-arab-emirates) |              343 |                       468 |                      48 |                        125 |                                       36% |                                   352 |                                    788 |
|                   [South Korea](/south-korea) |              298 |                       381 |                       7 |                         83 |                                       28% |                                   300 |                                    614 |
|                         [Malaysia](/malaysia) |              123 |                       160 |                       5 |                         37 |                                       30% |                                   135 |                                    181 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       23% |                                    90 |                                    138 |
