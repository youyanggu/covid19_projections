We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#current-us-projections)
* [US and Global Dashboard **(New June 6)**](#covid-19-dashboard)
* [View US state-by-state projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **June 12:** We changed how we display our R_t values. Previously, we displayed the R value before factoring in recovered/immune individuals. Now we are displaying the R values after factoring in immunity, which is what our model uses internally. This R value is lower than our previous displayed values. Note that this is merely a cosmetic change, and that our underlying model has not changed.
* **June 11:** We have extended our projections to October 1, 2020.
* **June 10:** We launched the C19Pro Score for both cases and deaths to show where weekly cases and deaths are changing the most. They are shown in the first two maps on our new [Maps](/maps) page.
* **June 8:** We added a map that shows how cases are changing in each state/country. Scroll down below to see it, or click [here](#covid-19-dashboard)

## Current US Projections
### Updated Daily - Last Updated: June 14 (3am ET):
<p align="center">
  Current Total: <b>115,433</b> deaths | Projected Total: <b>179,172 deaths by Sep 1 | 198,860 deaths by Oct 1, 2020</b> (Range: 147-286k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.4%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 88% chance that the US surpasses 125,000 deaths by July 1, with June 27 being the most likely date.

Last updated: Jun 14, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 20, 2020 |
|              125,000 |        Jun 27, 2020 |
|              130,000 |         Jul 4, 2020 |
|              140,000 |        Jul 17, 2020 |
|              150,000 |        Jul 29, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        88% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |         <1% |        <1% |          7% |        53% |         73% |        87% |         92% |        95% |
|              175,000 |         <1% |        <1% |         <1% |         6% |         27% |        48% |         55% |        61% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          5% |        21% |         31% |        38% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |          6% |        12% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |

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

States are ordered by descending projected deaths (by October 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          115,433 |                   198,860 |                     599 |                     83,427 |                                       72% |                               147,256 |                                285,843 |
|                 [New York](/us-ny) |           30,795 |                    33,589 |                   1,727 |                      2,794 |                                        9% |                                31,180 |                                 38,677 |
|               [California](/us-ca) |            5,076 |                    17,345 |                     439 |                     12,269 |                                      242% |                                 7,537 |                                 32,587 |
|               [New Jersey](/us-nj) |           12,621 |                    15,309 |                   1,724 |                      2,688 |                                       21% |                                13,323 |                                 17,923 |
|                 [Illinois](/us-il) |            6,289 |                    12,154 |                     959 |                      5,865 |                                       93% |                                 7,969 |                                 18,243 |
|             [Pennsylvania](/us-pa) |            6,211 |                     9,809 |                     766 |                      3,598 |                                       58% |                                 6,880 |                                 16,674 |
|            [Massachusetts](/us-ma) |            7,576 |                     9,796 |                   1,410 |                      2,220 |                                       29% |                                 8,203 |                                 13,346 |
|                  [Florida](/us-fl) |            2,925 |                     9,022 |                     420 |                      6,097 |                                      208% |                                 4,125 |                                 17,142 |
|                 [Michigan](/us-mi) |            6,013 |                     7,334 |                     734 |                      1,321 |                                       22% |                                 6,332 |                                 10,285 |
|                     [Ohio](/us-oh) |            2,556 |                     6,360 |                     544 |                      3,804 |                                      149% |                                 3,251 |                                 12,021 |
|                  [Georgia](/us-ga) |            2,447 |                     6,250 |                     589 |                      3,803 |                                      155% |                                 3,412 |                                 11,820 |
|                 [Maryland](/us-md) |            2,926 |                     5,513 |                     912 |                      2,587 |                                       88% |                                 3,486 |                                  8,545 |
|              [Connecticut](/us-ct) |            4,186 |                     5,296 |                   1,485 |                      1,110 |                                       27% |                                 4,484 |                                  7,044 |
|                  [Indiana](/us-in) |            2,413 |                     4,568 |                     679 |                      2,155 |                                       89% |                                 2,758 |                                  9,376 |
|                    [Texas](/us-tx) |            1,971 |                     4,537 |                     156 |                      2,566 |                                      130% |                                 2,640 |                                 10,257 |
|                  [Arizona](/us-az) |            1,189 |                     4,531 |                     622 |                      3,342 |                                      281% |                                 1,793 |                                  8,278 |
|                [Louisiana](/us-la) |            3,004 |                     4,287 |                     922 |                      1,283 |                                       43% |                                 3,314 |                                  6,557 |
|           [North Carolina](/us-nc) |            1,127 |                     4,026 |                     384 |                      2,899 |                                      257% |                                 1,816 |                                  7,760 |
|                 [Virginia](/us-va) |            1,541 |                     3,789 |                     444 |                      2,248 |                                      146% |                                 1,912 |                                  7,770 |
|                [Minnesota](/us-mn) |            1,314 |                     3,323 |                     589 |                      2,009 |                                      153% |                                 1,994 |                                  5,095 |
|                 [Colorado](/us-co) |            1,597 |                     2,966 |                     515 |                      1,369 |                                       86% |                                 1,789 |                                  6,174 |
|                 [Missouri](/us-mo) |              885 |                     2,716 |                     443 |                      1,831 |                                      207% |                                 1,273 |                                  5,388 |
|                  [Alabama](/us-al) |              773 |                     2,596 |                     529 |                      1,823 |                                      236% |                                 1,258 |                                  4,798 |
|               [Washington](/us-wa) |            1,213 |                     2,505 |                     329 |                      1,292 |                                      107% |                                 1,358 |                                  5,805 |
|              [Mississippi](/us-ms) |              889 |                     2,249 |                     756 |                      1,360 |                                      153% |                                 1,126 |                                  4,417 |
|           [South Carolina](/us-sc) |              599 |                     2,113 |                     410 |                      1,514 |                                      253% |                                   913 |                                  4,090 |
|                [Wisconsin](/us-wi) |              691 |                     1,918 |                     329 |                      1,227 |                                      178% |                                   967 |                                  3,970 |
|             [Rhode Island](/us-ri) |              833 |                     1,556 |                   1,469 |                        723 |                                       87% |                                 1,043 |                                  2,360 |
|                     [Iowa](/us-ia) |              650 |                     1,551 |                     492 |                        901 |                                      139% |                                 1,027 |                                  2,497 |
|                 [Kentucky](/us-ky) |              499 |                     1,365 |                     306 |                        866 |                                      174% |                                   664 |                                  2,866 |
|                [Tennessee](/us-tn) |              472 |                     1,230 |                     180 |                        758 |                                      161% |                                   671 |                                  2,404 |
|               [New Mexico](/us-nm) |              431 |                     1,191 |                     568 |                        760 |                                      176% |                                   561 |                                  2,361 |
|                   [Nevada](/us-nv) |              462 |                     1,046 |                     340 |                        584 |                                      126% |                                   571 |                                  2,104 |
|            [New Hampshire](/us-nh) |              318 |                       997 |                     733 |                        679 |                                      214% |                                   435 |                                  1,942 |
|                 [Arkansas](/us-ar) |              177 |                       805 |                     267 |                        628 |                                      355% |                                   316 |                                  1,531 |
|                 [Delaware](/us-de) |              419 |                       784 |                     805 |                        365 |                                       87% |                                   490 |                                  1,438 |
|     [District of Columbia](/us-dc) |              511 |                       778 |                   1,102 |                        267 |                                       52% |                                   571 |                                  1,191 |
|                     [Utah](/us-ut) |              139 |                       634 |                     198 |                        495 |                                      356% |                                   248 |                                  1,276 |
|                 [Nebraska](/us-ne) |              215 |                       617 |                     319 |                        402 |                                      187% |                                   368 |                                  1,012 |
|                 [Oklahoma](/us-ok) |              359 |                       506 |                     128 |                        147 |                                       41% |                                   411 |                                    784 |
|                   [Kansas](/us-ks) |              245 |                       411 |                     141 |                        166 |                                       68% |                                   277 |                                    840 |
|                   [Oregon](/us-or) |              173 |                       323 |                      77 |                        150 |                                       87% |                                   200 |                                    689 |
|              [Puerto Rico](/us-pr) |              146 |                       215 |                      67 |                         69 |                                       47% |                                   166 |                                    352 |
|             [South Dakota](/us-sd) |               75 |                       214 |                     242 |                        139 |                                      185% |                                   112 |                                    408 |
|                    [Maine](/us-me) |              100 |                       164 |                     122 |                         64 |                                       64% |                                   121 |                                    288 |
|             [North Dakota](/us-nd) |               74 |                       150 |                     197 |                         76 |                                      103% |                                   106 |                                    231 |
|            [West Virginia](/us-wv) |               88 |                       140 |                      78 |                         52 |                                       59% |                                   103 |                                    231 |
|                    [Idaho](/us-id) |               87 |                       109 |                      61 |                         22 |                                       25% |                                    96 |                                    139 |
|                  [Vermont](/us-vt) |               55 |                        67 |                     107 |                         12 |                                       22% |                                    60 |                                     85 |
|                  [Wyoming](/us-wy) |               18 |                        28 |                      48 |                         10 |                                       56% |                                    24 |                                     35 |
|                  [Montana](/us-mt) |               18 |                        22 |                      21 |                          4 |                                       22% |                                    19 |                                     29 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     24 |
|                   [Alaska](/us-ak) |               12 |                        15 |                      21 |                          3 |                                       25% |                                    13 |                                     17 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          175,254 |                   206,178 |                     348 |                     30,924 |                                       18% |                               183,379 |                                252,465 |
| [United Kingdom](/united-kingdom) |           41,747 |                    51,199 |                     758 |                      9,452 |                                       23% |                                45,058 |                                 59,537 |
|                   [Italy](/italy) |           34,301 |                    36,035 |                     597 |                      1,734 |                                        5% |                                34,613 |                                 37,001 |
|                 [France](/france) |           29,401 |                    31,191 |                     465 |                      1,790 |                                        6% |                                29,513 |                                 37,673 |
|                   [Spain](/spain) |           27,136 |                    28,498 |                     607 |                      1,362 |                                        5% |                                27,227 |                                 33,584 |
|               [Germany](/germany) |            8,793 |                    10,663 |                     128 |                      1,870 |                                       21% |                                 9,052 |                                 14,971 |
|               [Belgium](/belgium) |            9,650 |                    10,213 |                     892 |                        563 |                                        6% |                                 9,743 |                                 11,606 |
|                 [Sweden](/sweden) |            4,874 |                     7,225 |                     706 |                      2,351 |                                       48% |                                 5,709 |                                  9,330 |
|       [Netherlands](/netherlands) |            6,076 |                     6,976 |                     404 |                        900 |                                       15% |                                 6,218 |                                  9,168 |
|               [Ukraine](/ukraine) |              890 |                     4,126 |                      94 |                      3,236 |                                      364% |                                 1,681 |                                  7,455 |
|                 [Poland](/poland) |            1,237 |                     3,312 |                      87 |                      2,075 |                                      168% |                                 1,626 |                                  6,621 |
|               [Romania](/romania) |            1,394 |                     2,228 |                     115 |                        834 |                                       60% |                                 1,658 |                                  3,760 |
|               [Moldova](/moldova) |              398 |                     2,226 |                     551 |                      1,828 |                                      459% |                                 1,158 |                                  3,435 |
|             [Portugal](/portugal) |            1,512 |                     2,096 |                     204 |                        584 |                                       39% |                                 1,681 |                                  3,370 |
|       [Switzerland](/switzerland) |            1,938 |                     2,078 |                     242 |                        140 |                                        7% |                                 1,963 |                                  2,359 |
|               [Ireland](/ireland) |            1,705 |                     1,865 |                     380 |                        160 |                                        9% |                                 1,727 |                                  2,500 |
|               [Belarus](/belarus) |              303 |                       918 |                      97 |                        615 |                                      203% |                                   461 |                                  2,488 |
|               [Hungary](/hungary) |              559 |                       885 |                      91 |                        326 |                                       58% |                                   619 |                                  1,666 |
|               [Austria](/austria) |              677 |                       749 |                      85 |                         72 |                                       11% |                                   701 |                                    888 |
|               [Denmark](/denmark) |              597 |                       708 |                     122 |                        111 |                                       19% |                                   633 |                                    875 |
|             [Bulgaria](/bulgaria) |              172 |                       700 |                     100 |                        528 |                                      307% |                                   292 |                                  1,264 |
|               [Finland](/finland) |              325 |                       387 |                      70 |                         62 |                                       19% |                                   338 |                                    531 |
|               [Czechia](/czechia) |              328 |                       365 |                      34 |                         37 |                                       11% |                                   347 |                                    405 |
|                 [Serbia](/serbia) |              253 |                       323 |                      46 |                         70 |                                       28% |                                   284 |                                    428 |
|                 [Norway](/norway) |              242 |                       273 |                      51 |                         31 |                                       13% |                                   254 |                                    319 |
|                 [Greece](/greece) |              183 |                       225 |                      21 |                         42 |                                       23% |                                   203 |                                    275 |
|               [Croatia](/croatia) |              107 |                       146 |                      36 |                         39 |                                       36% |                                   119 |                                    225 |
|           [Lithuania](/lithuania) |               75 |                       128 |                      46 |                         53 |                                       71% |                                    92 |                                    225 |
|         [Luxembourg](/luxembourg) |              110 |                       124 |                     202 |                         14 |                                       13% |                                   114 |                                    146 |
|             [Slovenia](/slovenia) |              109 |                       123 |                      59 |                         14 |                                       13% |                                   113 |                                    148 |
|               [Estonia](/estonia) |               69 |                        82 |                      62 |                         13 |                                       19% |                                    79 |                                     88 |
|                 [Latvia](/latvia) |               28 |                        35 |                      18 |                          7 |                                       25% |                                    32 |                                     40 |
|             [Slovakia](/slovakia) |               28 |                        32 |                       6 |                          4 |                                       14% |                                    29 |                                     35 |
|                 [Cyprus](/cyprus) |               18 |                        21 |                      24 |                          3 |                                       17% |                                    20 |                                     23 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    11 |                                     14 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          134,040 |                   688,515 |                     133 |                    554,475 |                                      414% |                               347,326 |                              1,117,178 |
|                             [Brazil](/brazil) |           42,720 |                   160,599 |                     761 |                    117,879 |                                      276% |                                82,403 |                                267,748 |
|                               [India](/india) |            9,204 |                   149,757 |                     110 |                    140,553 |                                     1527% |                                50,723 |                                275,319 |
|                             [Mexico](/mexico) |           16,872 |                   107,255 |                     841 |                     90,383 |                                      536% |                                68,049 |                                127,940 |
|                 [South Africa](/south-africa) |            1,423 |                    33,141 |                     566 |                     31,718 |                                     2229% |                                16,558 |                                 48,590 |
|                                 [Peru](/peru) |            6,308 |                    27,406 |                     843 |                     21,098 |                                      334% |                                12,686 |                                 40,271 |
|                         [Pakistan](/pakistan) |            2,551 |                    26,320 |                     122 |                     23,769 |                                      932% |                                 8,817 |                                 53,686 |
|                               [Chile](/chile) |            3,101 |                    24,949 |                   1,316 |                     21,848 |                                      705% |                                17,340 |                                 37,044 |
|                             [Russia](/russia) |            6,819 |                    24,003 |                     165 |                     17,184 |                                      252% |                                11,555 |                                 45,103 |
|                         [Colombia](/colombia) |            1,623 |                    20,520 |                     408 |                     18,897 |                                     1164% |                                11,853 |                                 26,645 |
|                                 [Iran](/iran) |            8,730 |                    15,128 |                     182 |                      6,398 |                                       73% |                                10,278 |                                 25,305 |
|                             [Canada](/canada) |            8,183 |                    14,250 |                     381 |                      6,067 |                                       74% |                                 9,261 |                                 27,042 |
|                               [Egypt](/egypt) |            1,484 |                    10,492 |                     105 |                      9,008 |                                      607% |                                 4,344 |                                 16,817 |
|                     [Bangladesh](/bangladesh) |            1,139 |                    10,477 |                      64 |                      9,338 |                                      820% |                                 5,684 |                                 15,033 |
|                       [Indonesia](/indonesia) |            2,091 |                    10,448 |                      39 |                      8,357 |                                      400% |                                 4,257 |                                 20,193 |
|                 [Saudi Arabia](/saudi-arabia) |              932 |                     7,950 |                     232 |                      7,018 |                                      753% |                                 5,018 |                                 11,576 |
|                       [Argentina](/argentina) |              815 |                     7,660 |                     171 |                      6,845 |                                      840% |                                 3,035 |                                 13,941 |
|                           [Ecuador](/ecuador) |            3,874 |                     6,723 |                     387 |                      2,849 |                                       74% |                                 4,406 |                                 13,726 |
|                           [Bolivia](/bolivia) |              585 |                     6,627 |                     576 |                      6,042 |                                     1033% |                                 3,677 |                                  9,544 |
|                             [Turkey](/turkey) |            4,792 |                     5,681 |                      68 |                        889 |                                       19% |                                 4,936 |                                  8,167 |
|                               [China](/china) |            4,638 |                     4,647 |                       3 |                          9 |                                        0% |                                 4,638 |                                  4,703 |
|                           [Nigeria](/nigeria) |              407 |                     2,480 |                      12 |                      2,073 |                                      509% |                                   732 |                                  5,242 |
|                   [Philippines](/philippines) |            1,074 |                     2,228 |                      21 |                      1,154 |                                      107% |                                 1,259 |                                  4,836 |
|                         [Honduras](/honduras) |              310 |                     1,833 |                     188 |                      1,523 |                                      491% |                                   766 |                                  3,337 |
|                           [Algeria](/algeria) |              760 |                     1,617 |                      38 |                        857 |                                      113% |                                   874 |                                  4,622 |
|                             [Panama](/panama) |              429 |                     1,446 |                     341 |                      1,017 |                                      237% |                                   618 |                                  2,831 |
|                               [Japan](/japan) |              927 |                     1,206 |                      10 |                        279 |                                       30% |                                   938 |                                  1,627 |
|     [Dominican Republic](/dominican-republic) |              577 |                     1,068 |                      99 |                        491 |                                       85% |                                   689 |                                  2,127 |
|                             [Kuwait](/kuwait) |              289 |                       852 |                     203 |                        563 |                                      195% |                                   449 |                                  1,552 |
| [United Arab Emirates](/united-arab-emirates) |              288 |                       470 |                      48 |                        182 |                                       63% |                                   326 |                                  1,003 |
|                             [Israel](/israel) |              300 |                       370 |                      43 |                         70 |                                       23% |                                   325 |                                    505 |
|                   [South Korea](/south-korea) |              277 |                       322 |                       6 |                         45 |                                       16% |                                   281 |                                    437 |
|                           [Morocco](/morocco) |              212 |                       238 |                       7 |                         26 |                                       12% |                                   223 |                                    270 |
|                         [Malaysia](/malaysia) |              120 |                       147 |                       5 |                         27 |                                       22% |                                   136 |                                    163 |
|                       [Australia](/australia) |              102 |                       106 |                       4 |                          4 |                                        4% |                                   102 |                                    122 |
|                                 [Cuba](/cuba) |               84 |                        99 |                       9 |                         15 |                                       18% |                                    90 |                                    111 |
