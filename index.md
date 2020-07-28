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
### Updated Daily - Last Updated: July 28 (2pm ET):
<p align="center">
  Current Total: <b>148,008</b> deaths | Projected Total: <b>221,800 deaths by Nov 1, 2020</b> (Range: 189-270k)<br>
  Currently Infected: <b>1.9%</b> | Total Infected: <b>10.7%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 28, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 29, 2020 |
|              175,000 |        Aug 27, 2020 |
|              200,000 |         Oct 2, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          3% |        75% |         98% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         4% |         23% |        50% |         67% |        80% |
|              225,000 |        <1% |         <1% |        <1% |          1% |         9% |         19% |        33% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          4% |         9% |
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
|             *[United States](/us)* |          148,008 |                   221,818 |                     668 |                     73,810 |                                       50% |                               189,513 |                                269,041 |
|                 [New York](/us-ny) |           32,645 |                    33,757 |                   1,735 |                      1,112 |                                        3% |                                32,693 |                                 38,508 |
|               [California](/us-ca) |            8,494 |                    17,595 |                     445 |                      9,101 |                                      107% |                                11,520 |                                 26,624 |
|                    [Texas](/us-tx) |            5,713 |                    16,809 |                     580 |                     11,096 |                                      194% |                                10,826 |                                 24,776 |
|               [New Jersey](/us-nj) |           15,804 |                    16,637 |                   1,873 |                        833 |                                        5% |                                15,903 |                                 18,083 |
|                  [Florida](/us-fl) |            5,931 |                    14,556 |                     678 |                      8,625 |                                      145% |                                 9,807 |                                 21,213 |
|            [Massachusetts](/us-ma) |            8,536 |                     9,458 |                   1,361 |                        922 |                                       11% |                                 8,616 |                                 11,318 |
|                 [Illinois](/us-il) |            7,608 |                     9,324 |                     736 |                      1,716 |                                       23% |                                 7,880 |                                 11,888 |
|             [Pennsylvania](/us-pa) |            7,131 |                     9,140 |                     714 |                      2,009 |                                       28% |                                 7,287 |                                 13,526 |
|                  [Arizona](/us-az) |            3,304 |                     7,038 |                     967 |                      3,734 |                                      113% |                                 5,114 |                                  9,344 |
|                  [Georgia](/us-ga) |            3,509 |                     6,978 |                     657 |                      3,469 |                                       99% |                                 4,471 |                                 11,004 |
|                 [Michigan](/us-mi) |            6,405 |                     6,892 |                     690 |                        487 |                                        8% |                                 6,451 |                                  8,077 |
|                [Louisiana](/us-la) |            3,786 |                     5,561 |                   1,196 |                      1,775 |                                       47% |                                 4,258 |                                  7,764 |
|                     [Ohio](/us-oh) |            3,344 |                     5,418 |                     464 |                      2,074 |                                       62% |                                 3,744 |                                  8,474 |
|                 [Maryland](/us-md) |            3,447 |                     4,974 |                     823 |                      1,527 |                                       44% |                                 3,693 |                                  7,997 |
|              [Connecticut](/us-ct) |            4,418 |                     4,656 |                   1,306 |                        238 |                                        5% |                                 4,452 |                                  5,141 |
|                  [Indiana](/us-in) |            2,906 |                     4,504 |                     669 |                      1,598 |                                       55% |                                 3,161 |                                  7,527 |
|           [South Carolina](/us-sc) |            1,506 |                     4,304 |                     836 |                      2,798 |                                      186% |                                 2,823 |                                  6,252 |
|           [North Carolina](/us-nc) |            1,838 |                     3,918 |                     374 |                      2,080 |                                      113% |                                 2,488 |                                  6,215 |
|                  [Alabama](/us-al) |            1,491 |                     3,575 |                     729 |                      2,084 |                                      140% |                                 2,420 |                                  5,219 |
|                 [Virginia](/us-va) |            2,082 |                     3,204 |                     375 |                      1,122 |                                       54% |                                 2,220 |                                  5,546 |
|              [Mississippi](/us-ms) |            1,498 |                     2,976 |                   1,000 |                      1,478 |                                       99% |                                 1,949 |                                  4,449 |
|                 [Colorado](/us-co) |            1,799 |                     2,582 |                     448 |                        783 |                                       44% |                                 1,953 |                                  4,087 |
|                 [Missouri](/us-mo) |            1,221 |                     2,530 |                     412 |                      1,309 |                                      107% |                                 1,448 |                                  4,866 |
|                [Tennessee](/us-tn) |              978 |                     2,484 |                     363 |                      1,506 |                                      154% |                                 1,585 |                                  3,705 |
|                [Minnesota](/us-mn) |            1,616 |                     2,279 |                     404 |                        663 |                                       41% |                                 1,728 |                                  3,498 |
|               [Washington](/us-wa) |            1,518 |                     2,088 |                     274 |                        570 |                                       38% |                                 1,591 |                                  3,112 |
|                [Wisconsin](/us-wi) |              893 |                     1,860 |                     319 |                        967 |                                      108% |                                 1,086 |                                  3,773 |
|                   [Nevada](/us-nv) |              739 |                     1,717 |                     557 |                        978 |                                      132% |                                 1,131 |                                  2,589 |
|                 [Kentucky](/us-ky) |              709 |                     1,689 |                     378 |                        980 |                                      138% |                                   896 |                                  3,476 |
|                     [Iowa](/us-ia) |              836 |                     1,476 |                     468 |                        640 |                                       77% |                                   982 |                                  2,511 |
|             [Rhode Island](/us-ri) |            1,004 |                     1,171 |                   1,105 |                        167 |                                       17% |                                 1,032 |                                  1,393 |
|               [New Mexico](/us-nm) |              619 |                     1,085 |                     518 |                        466 |                                       75% |                                   740 |                                  1,703 |
|                 [Oklahoma](/us-ok) |              496 |                     1,051 |                     266 |                        555 |                                      112% |                                   649 |                                  1,747 |
|                 [Arkansas](/us-ar) |              408 |                       993 |                     329 |                        585 |                                      143% |                                   611 |                                  1,577 |
|                   [Oregon](/us-or) |              289 |                       887 |                     210 |                        598 |                                      207% |                                   457 |                                  1,680 |
|                     [Utah](/us-ut) |              281 |                       861 |                     269 |                        580 |                                      206% |                                   471 |                                  1,460 |
|              [Puerto Rico](/us-pr) |              201 |                       794 |                     249 |                        593 |                                      295% |                                   330 |                                  1,764 |
|                 [Delaware](/us-de) |              579 |                       675 |                     693 |                         96 |                                       17% |                                   593 |                                    841 |
|                   [Kansas](/us-ks) |              333 |                       651 |                     223 |                        318 |                                       95% |                                   413 |                                  1,089 |
|     [District of Columbia](/us-dc) |              581 |                       645 |                     914 |                         64 |                                       11% |                                   593 |                                    757 |
|                    [Idaho](/us-id) |              152 |                       644 |                     360 |                        492 |                                      323% |                                   320 |                                  1,136 |
|            [New Hampshire](/us-nh) |              409 |                       540 |                     397 |                        131 |                                       32% |                                   423 |                                    772 |
|                 [Nebraska](/us-ne) |              317 |                       507 |                     262 |                        190 |                                       60% |                                   350 |                                    812 |
|             [North Dakota](/us-nd) |               99 |                       225 |                     296 |                        126 |                                      128% |                                   130 |                                    415 |
|                  [Montana](/us-mt) |               47 |                       224 |                     210 |                        177 |                                      377% |                                   100 |                                    435 |
|             [South Dakota](/us-sd) |              123 |                       213 |                     241 |                         90 |                                       73% |                                   137 |                                    353 |
|            [West Virginia](/us-wv) |              104 |                       177 |                      99 |                         73 |                                       70% |                                   115 |                                    344 |
|                    [Maine](/us-me) |              119 |                       171 |                     127 |                         52 |                                       43% |                                   128 |                                    259 |
|                   [Hawaii](/us-hi) |               26 |                        95 |                      67 |                         69 |                                      264% |                                    34 |                                    257 |
|                   [Alaska](/us-ak) |               21 |                        76 |                     104 |                         55 |                                      263% |                                    36 |                                    154 |
|                  [Vermont](/us-vt) |               56 |                        75 |                     121 |                         19 |                                       35% |                                    61 |                                    101 |
|                  [Wyoming](/us-wy) |               25 |                        42 |                      73 |                         17 |                                       69% |                                    30 |                                     74 |
|           [Virgin Islands](/us-vi) |                7 |                        23 |                     217 |                         16 |                                      225% |                                     9 |                                     59 |
|                     [Guam](/us-gu) |                5 |                        10 |                      62 |                          5 |                                      104% |                                     6 |                                     21 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      101% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          187,256 |                   202,288 |                     341 |                     15,032 |                                        8% |                               190,094 |                                236,833 |
| [United Kingdom](/united-kingdom) |           45,844 |                    49,238 |                     729 |                      3,394 |                                        7% |                                46,018 |                                 57,532 |
|                   [Italy](/italy) |           35,112 |                    35,695 |                     591 |                        583 |                                        2% |                                35,134 |                                 37,569 |
|                 [France](/france) |           30,212 |                    30,863 |                     461 |                        651 |                                        2% |                                30,239 |                                 34,318 |
|                   [Spain](/spain) |           28,432 |                    28,924 |                     616 |                        492 |                                        2% |                                28,453 |                                 31,302 |
|               [Belgium](/belgium) |            9,822 |                     9,972 |                     871 |                        150 |                                        2% |                                 9,842 |                                 10,620 |
|               [Germany](/germany) |            9,125 |                     9,402 |                     113 |                        277 |                                        3% |                                 9,137 |                                 10,738 |
|       [Netherlands](/netherlands) |            6,160 |                     6,230 |                     361 |                         70 |                                        1% |                                 6,169 |                                  6,469 |
|                 [Sweden](/sweden) |            5,700 |                     6,101 |                     596 |                        401 |                                        7% |                                 5,792 |                                  6,792 |
|               [Romania](/romania) |            2,206 |                     4,501 |                     232 |                      2,295 |                                      104% |                                 2,958 |                                  8,243 |
|               [Ukraine](/ukraine) |            1,636 |                     3,278 |                      75 |                      1,642 |                                      100% |                                 2,107 |                                  6,214 |
|             [Portugal](/portugal) |            1,719 |                     2,217 |                     216 |                        498 |                                       29% |                                 1,769 |                                  3,255 |
|                 [Poland](/poland) |            1,676 |                     2,215 |                      58 |                        539 |                                       32% |                                 1,742 |                                  3,453 |
|       [Switzerland](/switzerland) |            1,978 |                     2,061 |                     240 |                         83 |                                        4% |                                 1,989 |                                  2,291 |
|               [Ireland](/ireland) |            1,764 |                     1,855 |                     378 |                         91 |                                        5% |                                 1,776 |                                  2,183 |
|                 [Serbia](/serbia) |              543 |                     1,576 |                     226 |                      1,033 |                                      190% |                                   866 |                                  3,146 |
|               [Moldova](/moldova) |              748 |                     1,488 |                     368 |                        740 |                                       99% |                                   977 |                                  2,415 |
|             [Bulgaria](/bulgaria) |              347 |                       988 |                     141 |                        641 |                                      185% |                                   512 |                                  2,186 |
|               [Belarus](/belarus) |              538 |                       968 |                     102 |                        430 |                                       80% |                                   697 |                                  1,420 |
|               [Austria](/austria) |              713 |                       790 |                      89 |                         77 |                                       11% |                                   729 |                                    947 |
|               [Hungary](/hungary) |              596 |                       699 |                      72 |                        103 |                                       17% |                                   609 |                                    934 |
|               [Denmark](/denmark) |              613 |                       695 |                     120 |                         82 |                                       13% |                                   629 |                                    855 |
|               [Czechia](/czechia) |              373 |                       597 |                      56 |                        224 |                                       60% |                                   411 |                                  1,061 |
|               [Croatia](/croatia) |              139 |                       393 |                      96 |                        254 |                                      183% |                                   214 |                                    807 |
|               [Finland](/finland) |              329 |                       383 |                      69 |                         54 |                                       16% |                                   341 |                                    515 |
|                 [Norway](/norway) |              255 |                       283 |                      53 |                         28 |                                       11% |                                   262 |                                    332 |
|                 [Greece](/greece) |              202 |                       249 |                      23 |                         47 |                                       23% |                                   212 |                                    326 |
|         [Luxembourg](/luxembourg) |              112 |                       160 |                     261 |                         48 |                                       43% |                                   125 |                                    237 |
|             [Slovenia](/slovenia) |              116 |                       140 |                      67 |                         24 |                                       21% |                                   120 |                                    187 |
|           [Lithuania](/lithuania) |               80 |                       106 |                      38 |                         26 |                                       33% |                                    84 |                                    154 |
|               [Estonia](/estonia) |               69 |                        88 |                      67 |                         19 |                                       28% |                                    76 |                                    123 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       31% |                                    33 |                                     61 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    29 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       52% |                                    22 |                                     49 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       62% |                                    11 |                                     18 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       38% |                                    10 |                                     24 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          300,057 |                   690,468 |                     133 |                    390,411 |                                      130% |                               433,316 |                              1,151,613 |
|                             [Brazil](/brazil) |           87,618 |                   183,955 |                     872 |                     96,337 |                                      110% |                               118,567 |                                309,577 |
|                               [India](/india) |           33,408 |                   138,390 |                     101 |                    104,982 |                                      314% |                                63,964 |                                243,529 |
|                             [Mexico](/mexico) |           44,022 |                    96,011 |                     753 |                     51,989 |                                      118% |                                71,256 |                                155,284 |
|                                 [Peru](/peru) |           18,418 |                    31,314 |                     963 |                     12,896 |                                       70% |                                22,611 |                                 48,314 |
|                                 [Iran](/iran) |           15,912 |                    30,356 |                     366 |                     14,444 |                                       91% |                                20,903 |                                 46,473 |
|                         [Colombia](/colombia) |            8,777 |                    29,775 |                     591 |                     20,998 |                                      239% |                                17,854 |                                 48,922 |
|                 [South Africa](/south-africa) |            7,067 |                    24,382 |                     416 |                     17,315 |                                      245% |                                16,028 |                                 32,170 |
|                             [Russia](/russia) |           13,334 |                    22,590 |                     155 |                      9,256 |                                       69% |                                15,062 |                                 39,917 |
|                       [Indonesia](/indonesia) |            4,838 |                    16,481 |                      61 |                     11,643 |                                      241% |                                 7,946 |                                 34,821 |
|                       [Argentina](/argentina) |            3,059 |                    15,796 |                     353 |                     12,737 |                                      416% |                                 7,606 |                                 26,759 |
|                               [Chile](/chile) |            9,187 |                    15,290 |                     807 |                      6,103 |                                       66% |                                 9,974 |                                 26,639 |
|                             [Canada](/canada) |            8,945 |                     9,333 |                     249 |                        388 |                                        4% |                                 8,975 |                                 10,176 |
|                           [Ecuador](/ecuador) |            5,532 |                     7,872 |                     453 |                      2,340 |                                       42% |                                 5,726 |                                 12,030 |
|                         [Pakistan](/pakistan) |            5,842 |                     7,562 |                      35 |                      1,720 |                                       29% |                                 6,259 |                                  9,448 |
|                             [Turkey](/turkey) |            5,630 |                     6,723 |                      81 |                      1,093 |                                       19% |                                 5,745 |                                  9,075 |
|                           [Bolivia](/bolivia) |            2,647 |                     6,615 |                     575 |                      3,968 |                                      150% |                                 3,967 |                                 11,441 |
|                               [Egypt](/egypt) |            4,652 |                     6,076 |                      61 |                      1,424 |                                       31% |                                 4,923 |                                  7,488 |
|                     [Bangladesh](/bangladesh) |            2,965 |                     5,749 |                      35 |                      2,784 |                                       94% |                                 3,420 |                                 10,489 |
|                   [Philippines](/philippines) |            1,945 |                     5,234 |                      48 |                      3,289 |                                      169% |                                 2,298 |                                 12,535 |
|                 [Saudi Arabia](/saudi-arabia) |            2,760 |                     5,134 |                     150 |                      2,374 |                                       86% |                                 3,545 |                                  8,858 |
|                               [China](/china) |            4,656 |                     4,711 |                       3 |                         55 |                                        1% |                                 4,656 |                                  5,155 |
|                         [Honduras](/honduras) |            1,166 |                     4,056 |                     416 |                      2,890 |                                      248% |                                 2,093 |                                  7,811 |
|                             [Panama](/panama) |            1,322 |                     3,367 |                     793 |                      2,045 |                                      155% |                                 2,108 |                                  5,795 |
|                           [Algeria](/algeria) |            1,163 |                     2,353 |                      55 |                      1,190 |                                      102% |                                 1,360 |                                  5,092 |
|     [Dominican Republic](/dominican-republic) |            1,083 |                     2,278 |                     212 |                      1,195 |                                      110% |                                 1,397 |                                  4,088 |
|                           [Nigeria](/nigeria) |              860 |                     1,578 |                       8 |                        718 |                                       84% |                                   945 |                                  3,617 |
|                             [Israel](/israel) |              474 |                     1,558 |                     183 |                      1,084 |                                      229% |                                   776 |                                  3,198 |
|                       [Australia](/australia) |              167 |                     1,546 |                      61 |                      1,379 |                                      826% |                                   508 |                                  3,709 |
|                               [Japan](/japan) |              998 |                     1,479 |                      12 |                        481 |                                       48% |                                 1,006 |                                  3,442 |
|                           [Morocco](/morocco) |              316 |                       982 |                      27 |                        666 |                                      211% |                                   475 |                                  2,243 |
|                             [Kuwait](/kuwait) |              438 |                       782 |                     186 |                        344 |                                       78% |                                   481 |                                  1,605 |
| [United Arab Emirates](/united-arab-emirates) |              345 |                       474 |                      49 |                        129 |                                       37% |                                   354 |                                    835 |
|                   [South Korea](/south-korea) |              300 |                       400 |                       8 |                        100 |                                       33% |                                   302 |                                    758 |
|                         [Malaysia](/malaysia) |              124 |                       159 |                       5 |                         35 |                                       28% |                                   136 |                                    180 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       23% |                                    90 |                                    140 |
