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
* **July 31:** We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* **July 28:** View our [updated historical performance](/about/#historical-performance).
* **July 23:** We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: August 2 (1pm ET):
<p align="center">
  Current Total: <b>154,444</b> deaths | Projected Total: <b>229,400 deaths by Nov 1, 2020</b> (Range: 199-272k)<br>
  Currently Infected: <b>2.0%</b> (1 in 50) | Total Infected: <b>12.0%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 2, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |          5% |        99% |         99% |        99% |         99% |       >99% |
|              200,000 |         <1% |         5% |         37% |        74% |         89% |        96% |
|              225,000 |         <1% |        <1% |          2% |        13% |         30% |        48% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          5% |        12% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          154,444 |                   229,377 |                     691 |                     74,933 |                                       49% |                               199,077 |                                271,903 |
|                 [New York](/us-ny) |           32,694 |                    33,644 |                   1,729 |                        950 |                                        3% |                                32,740 |                                 37,877 |
|               [California](/us-ca) |            9,345 |                    18,751 |                     475 |                      9,406 |                                      101% |                                12,944 |                                 26,554 |
|                    [Texas](/us-tx) |            6,865 |                    18,749 |                     647 |                     11,884 |                                      173% |                                12,723 |                                 25,500 |
|               [New Jersey](/us-nj) |           15,830 |                    16,540 |                   1,862 |                        710 |                                        4% |                                15,923 |                                 17,949 |
|                  [Florida](/us-fl) |            7,022 |                    16,530 |                     770 |                      9,508 |                                      135% |                                11,842 |                                 23,278 |
|            [Massachusetts](/us-ma) |            8,626 |                     9,536 |                   1,372 |                        910 |                                       11% |                                 8,695 |                                 11,384 |
|                 [Illinois](/us-il) |            7,700 |                     9,325 |                     736 |                      1,625 |                                       21% |                                 7,956 |                                 11,859 |
|             [Pennsylvania](/us-pa) |            7,219 |                     9,082 |                     709 |                      1,863 |                                       26% |                                 7,358 |                                 13,044 |
|                  [Georgia](/us-ga) |            3,825 |                     7,313 |                     689 |                      3,488 |                                       91% |                                 5,284 |                                 10,392 |
|                  [Arizona](/us-az) |            3,747 |                     7,204 |                     990 |                      3,457 |                                       92% |                                 5,517 |                                  9,293 |
|                 [Michigan](/us-mi) |            6,457 |                     6,937 |                     695 |                        480 |                                        7% |                                 6,500 |                                  7,926 |
|                [Louisiana](/us-la) |            3,949 |                     5,659 |                   1,217 |                      1,710 |                                       43% |                                 4,506 |                                  7,556 |
|                     [Ohio](/us-oh) |            3,515 |                     5,655 |                     484 |                      2,140 |                                       61% |                                 4,079 |                                  8,418 |
|                 [Maryland](/us-md) |            3,506 |                     4,842 |                     801 |                      1,336 |                                       38% |                                 3,727 |                                  7,547 |
|              [Connecticut](/us-ct) |            4,432 |                     4,658 |                   1,306 |                        226 |                                        5% |                                 4,464 |                                  5,110 |
|           [South Carolina](/us-sc) |            1,751 |                     4,557 |                     885 |                      2,806 |                                      160% |                                 3,163 |                                  6,308 |
|                  [Indiana](/us-in) |            2,971 |                     4,442 |                     660 |                      1,471 |                                       50% |                                 3,237 |                                  6,955 |
|           [North Carolina](/us-nc) |            1,979 |                     4,186 |                     399 |                      2,207 |                                      112% |                                 2,764 |                                  6,444 |
|                 [Virginia](/us-va) |            2,215 |                     3,446 |                     404 |                      1,231 |                                       56% |                                 2,397 |                                  5,539 |
|                  [Alabama](/us-al) |            1,603 |                     3,286 |                     670 |                      1,683 |                                      105% |                                 2,347 |                                  4,669 |
|              [Mississippi](/us-ms) |            1,693 |                     3,243 |                   1,090 |                      1,550 |                                       92% |                                 2,295 |                                  4,617 |
|                 [Missouri](/us-mo) |            1,276 |                     2,674 |                     436 |                      1,398 |                                      110% |                                 1,606 |                                  4,609 |
|                 [Colorado](/us-co) |            1,844 |                     2,468 |                     429 |                        624 |                                       34% |                                 1,932 |                                  3,700 |
|                [Tennessee](/us-tn) |            1,067 |                     2,408 |                     352 |                      1,341 |                                      126% |                                 1,613 |                                  3,460 |
|                [Minnesota](/us-mn) |            1,646 |                     2,274 |                     403 |                        628 |                                       38% |                                 1,748 |                                  3,440 |
|               [Washington](/us-wa) |            1,592 |                     2,231 |                     293 |                        639 |                                       40% |                                 1,662 |                                  3,320 |
|                [Wisconsin](/us-wi) |              947 |                     1,969 |                     338 |                      1,022 |                                      108% |                                 1,153 |                                  3,550 |
|                   [Nevada](/us-nv) |              832 |                     1,848 |                     600 |                      1,016 |                                      122% |                                 1,282 |                                  2,677 |
|                 [Kentucky](/us-ky) |              740 |                     1,630 |                     365 |                        890 |                                      120% |                                   928 |                                  3,077 |
|                     [Iowa](/us-ia) |              874 |                     1,491 |                     472 |                        617 |                                       71% |                                 1,021 |                                  2,417 |
|                 [Oklahoma](/us-ok) |              549 |                     1,360 |                     344 |                        811 |                                      148% |                                   836 |                                  2,202 |
|             [Rhode Island](/us-ri) |            1,007 |                     1,170 |                   1,104 |                        163 |                                       16% |                                 1,033 |                                  1,401 |
|               [New Mexico](/us-nm) |              651 |                     1,128 |                     538 |                        477 |                                       73% |                                   784 |                                  1,713 |
|                 [Arkansas](/us-ar) |              458 |                     1,086 |                     360 |                        628 |                                      137% |                                   705 |                                  1,616 |
|                   [Oregon](/us-or) |              325 |                       984 |                     233 |                        659 |                                      203% |                                   537 |                                  1,716 |
|              [Puerto Rico](/us-pr) |              225 |                       897 |                     281 |                        672 |                                      298% |                                   406 |                                  1,794 |
|                     [Utah](/us-ut) |              310 |                       853 |                     266 |                        543 |                                      175% |                                   509 |                                  1,349 |
|                    [Idaho](/us-id) |              197 |                       800 |                     448 |                        603 |                                      306% |                                   446 |                                  1,289 |
|                   [Kansas](/us-ks) |              358 |                       706 |                     242 |                        348 |                                       97% |                                   461 |                                  1,115 |
|                 [Delaware](/us-de) |              585 |                       675 |                     694 |                         90 |                                       15% |                                   600 |                                    826 |
|     [District of Columbia](/us-dc) |              584 |                       644 |                     913 |                         60 |                                       10% |                                   596 |                                    747 |
|            [New Hampshire](/us-nh) |              416 |                       533 |                     392 |                        117 |                                       28% |                                   427 |                                    742 |
|                 [Nebraska](/us-ne) |              332 |                       492 |                     254 |                        160 |                                       48% |                                   365 |                                    719 |
|                  [Montana](/us-mt) |               61 |                       282 |                     264 |                        221 |                                      362% |                                   143 |                                    495 |
|            [West Virginia](/us-wv) |              116 |                       239 |                     133 |                        123 |                                      106% |                                   145 |                                    466 |
|             [South Dakota](/us-sd) |              134 |                       231 |                     262 |                         97 |                                       73% |                                   167 |                                    356 |
|             [North Dakota](/us-nd) |              103 |                       201 |                     263 |                         98 |                                       95% |                                   131 |                                    348 |
|                    [Maine](/us-me) |              123 |                       176 |                     131 |                         53 |                                       43% |                                   133 |                                    251 |
|                   [Alaska](/us-ak) |               24 |                       121 |                     166 |                         97 |                                      405% |                                    53 |                                    262 |
|                  [Vermont](/us-vt) |               57 |                        78 |                     126 |                         21 |                                       38% |                                    64 |                                    110 |
|                   [Hawaii](/us-hi) |               26 |                        67 |                      47 |                         41 |                                      157% |                                    31 |                                    165 |
|                  [Wyoming](/us-wy) |               26 |                        41 |                      70 |                         15 |                                       56% |                                    31 |                                     66 |
|           [Virgin Islands](/us-vi) |                8 |                        23 |                     215 |                         15 |                                      182% |                                    11 |                                     43 |
|                     [Guam](/us-gu) |                5 |                         9 |                      53 |                          4 |                                       76% |                                     5 |                                     17 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       58% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,409 |                   204,826 |                     345 |                     16,417 |                                        9% |                               191,874 |                                237,089 |
| [United Kingdom](/united-kingdom) |           46,278 |                    50,801 |                     752 |                      4,523 |                                       10% |                                46,677 |                                 60,446 |
|                   [Italy](/italy) |           35,146 |                    35,659 |                     591 |                        513 |                                        1% |                                35,170 |                                 37,501 |
|                 [France](/france) |           30,268 |                    30,847 |                     460 |                        579 |                                        2% |                                30,293 |                                 33,268 |
|                   [Spain](/spain) |           28,445 |                    28,844 |                     615 |                        399 |                                        1% |                                28,464 |                                 30,787 |
|               [Belgium](/belgium) |            9,845 |                     9,951 |                     869 |                        106 |                                        1% |                                 9,863 |                                 10,213 |
|               [Germany](/germany) |            9,154 |                     9,431 |                     114 |                        277 |                                        3% |                                 9,166 |                                 10,578 |
|       [Netherlands](/netherlands) |            6,167 |                     6,234 |                     361 |                         67 |                                        1% |                                 6,176 |                                  6,470 |
|                 [Sweden](/sweden) |            5,743 |                     6,112 |                     597 |                        369 |                                        6% |                                 5,821 |                                  6,680 |
|               [Romania](/romania) |            2,379 |                     5,549 |                     286 |                      3,170 |                                      133% |                                 3,472 |                                  9,364 |
|               [Ukraine](/ukraine) |            1,733 |                     3,382 |                      77 |                      1,649 |                                       95% |                                 2,216 |                                  5,440 |
|                 [Poland](/poland) |            1,721 |                     2,366 |                      62 |                        645 |                                       37% |                                 1,874 |                                  3,666 |
|             [Portugal](/portugal) |            1,737 |                     2,165 |                     211 |                        428 |                                       25% |                                 1,780 |                                  2,984 |
|       [Switzerland](/switzerland) |            1,981 |                     2,044 |                     238 |                         63 |                                        3% |                                 1,992 |                                  2,270 |
|               [Ireland](/ireland) |            1,763 |                     1,834 |                     374 |                         71 |                                        4% |                                 1,776 |                                  2,036 |
|               [Moldova](/moldova) |              788 |                     1,464 |                     362 |                        676 |                                       86% |                                 1,030 |                                  2,362 |
|                 [Serbia](/serbia) |              582 |                     1,351 |                     194 |                        769 |                                      132% |                                   829 |                                  2,725 |
|             [Bulgaria](/bulgaria) |              385 |                     1,147 |                     164 |                        762 |                                      198% |                                   598 |                                  2,339 |
|               [Belarus](/belarus) |              563 |                       831 |                      88 |                        268 |                                       48% |                                   720 |                                  1,033 |
|               [Austria](/austria) |              718 |                       790 |                      89 |                         72 |                                       10% |                                   734 |                                    940 |
|               [Hungary](/hungary) |              597 |                       698 |                      71 |                        101 |                                       17% |                                   610 |                                    942 |
|               [Czechia](/czechia) |              383 |                       689 |                      65 |                        306 |                                       80% |                                   431 |                                  1,364 |
|               [Denmark](/denmark) |              615 |                       681 |                     117 |                         66 |                                       11% |                                   630 |                                    814 |
|               [Finland](/finland) |              329 |                       384 |                      70 |                         55 |                                       17% |                                   343 |                                    494 |
|               [Croatia](/croatia) |              145 |                       378 |                      93 |                        233 |                                      161% |                                   204 |                                    732 |
|                 [Norway](/norway) |              255 |                       280 |                      52 |                         25 |                                       10% |                                   262 |                                    328 |
|                 [Greece](/greece) |              206 |                       251 |                      23 |                         45 |                                       22% |                                   215 |                                    317 |
|         [Luxembourg](/luxembourg) |              116 |                       191 |                     312 |                         75 |                                       65% |                                   135 |                                    328 |
|             [Slovenia](/slovenia) |              119 |                       153 |                      74 |                         34 |                                       29% |                                   127 |                                    221 |
|           [Lithuania](/lithuania) |               80 |                       100 |                      36 |                         20 |                                       25% |                                    85 |                                    134 |
|               [Estonia](/estonia) |               69 |                        85 |                      64 |                         16 |                                       23% |                                    76 |                                    114 |
|                 [Latvia](/latvia) |               32 |                        43 |                      22 |                         11 |                                       34% |                                    34 |                                     58 |
|             [Slovakia](/slovakia) |               29 |                        38 |                       7 |                          9 |                                       30% |                                    30 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       46% |                                    22 |                                     43 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       34% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       45% |                                     9 |                                     20 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          321,763 |                   651,059 |                     125 |                    329,296 |                                      102% |                               434,138 |                              1,010,603 |
|                             [Brazil](/brazil) |           93,563 |                   174,038 |                     825 |                     80,475 |                                       86% |                               117,317 |                                271,214 |
|                               [India](/india) |           37,364 |                   122,983 |                      90 |                     85,619 |                                      229% |                                68,173 |                                183,398 |
|                             [Mexico](/mexico) |           47,472 |                    87,767 |                     688 |                     40,295 |                                       85% |                                71,744 |                                129,623 |
|                         [Colombia](/colombia) |           10,330 |                    31,872 |                     633 |                     21,542 |                                      209% |                                18,019 |                                 50,414 |
|                                 [Iran](/iran) |           16,982 |                    31,222 |                     377 |                     14,240 |                                       84% |                                20,527 |                                 44,592 |
|                                 [Peru](/peru) |           19,021 |                    26,619 |                     819 |                      7,598 |                                       40% |                                20,551 |                                 40,328 |
|                 [South Africa](/south-africa) |            8,153 |                    22,918 |                     391 |                     14,765 |                                      181% |                                12,514 |                                 33,785 |
|                             [Russia](/russia) |           14,034 |                    22,358 |                     153 |                      8,324 |                                       59% |                                15,600 |                                 39,131 |
|                       [Argentina](/argentina) |            3,596 |                    16,595 |                     371 |                     12,999 |                                      361% |                                 8,293 |                                 27,064 |
|                       [Indonesia](/indonesia) |            5,193 |                    13,743 |                      51 |                      8,550 |                                      165% |                                 7,541 |                                 25,372 |
|                               [Chile](/chile) |            9,533 |                    13,549 |                     715 |                      4,016 |                                       42% |                                10,141 |                                 23,224 |
|                             [Canada](/canada) |            8,986 |                     9,360 |                     250 |                        374 |                                        4% |                                 9,023 |                                 10,286 |
|                           [Bolivia](/bolivia) |            3,064 |                     7,634 |                     663 |                      4,570 |                                      149% |                                 4,540 |                                 12,708 |
|                           [Ecuador](/ecuador) |            5,736 |                     7,554 |                     435 |                      1,818 |                                       32% |                                 5,992 |                                 10,706 |
|                         [Pakistan](/pakistan) |            5,951 |                     7,231 |                      33 |                      1,280 |                                       22% |                                 6,323 |                                  8,775 |
|                             [Turkey](/turkey) |            5,710 |                     6,680 |                      80 |                        970 |                                       17% |                                 5,804 |                                  8,670 |
|                               [Egypt](/egypt) |            4,834 |                     6,162 |                      61 |                      1,328 |                                       27% |                                 5,084 |                                  7,462 |
|                     [Bangladesh](/bangladesh) |            3,132 |                     5,422 |                      33 |                      2,290 |                                       73% |                                 3,868 |                                  9,332 |
|                   [Philippines](/philippines) |            2,039 |                     5,209 |                      48 |                      3,170 |                                      155% |                                 2,295 |                                 14,428 |
|                 [Saudi Arabia](/saudi-arabia) |            2,887 |                     5,037 |                     147 |                      2,150 |                                       74% |                                 3,514 |                                  8,165 |
|                               [China](/china) |            4,667 |                     4,818 |                       3 |                        151 |                                        3% |                                 4,667 |                                  5,796 |
|                         [Honduras](/honduras) |            1,368 |                     4,558 |                     468 |                      3,190 |                                      233% |                                 2,361 |                                  8,961 |
|                             [Panama](/panama) |            1,449 |                     3,140 |                     739 |                      1,691 |                                      117% |                                 2,095 |                                  5,402 |
|     [Dominican Republic](/dominican-republic) |            1,170 |                     2,567 |                     239 |                      1,397 |                                      119% |                                 1,552 |                                  4,724 |
|                           [Algeria](/algeria) |            1,223 |                     2,378 |                      55 |                      1,155 |                                       94% |                                 1,417 |                                  4,935 |
|                           [Morocco](/morocco) |              367 |                     2,196 |                      60 |                      1,829 |                                      498% |                                   656 |                                  6,594 |
|                             [Israel](/israel) |              526 |                     1,578 |                     185 |                      1,052 |                                      200% |                                   780 |                                  3,241 |
|                               [Japan](/japan) |            1,012 |                     1,397 |                      11 |                        385 |                                       38% |                                 1,020 |                                  3,293 |
|                           [Nigeria](/nigeria) |              883 |                     1,341 |                       7 |                        458 |                                       52% |                                   953 |                                  2,384 |
|                       [Australia](/australia) |              201 |                     1,170 |                      46 |                        969 |                                      482% |                                   380 |                                  3,151 |
|                             [Kuwait](/kuwait) |              453 |                       854 |                     203 |                        401 |                                       89% |                                   503 |                                  1,755 |
| [United Arab Emirates](/united-arab-emirates) |              351 |                       457 |                      47 |                        106 |                                       30% |                                   360 |                                    759 |
|                   [South Korea](/south-korea) |              301 |                       383 |                       7 |                         82 |                                       27% |                                   303 |                                    614 |
|                         [Malaysia](/malaysia) |              125 |                       154 |                       5 |                         29 |                                       23% |                                   136 |                                    173 |
|                                 [Cuba](/cuba) |               87 |                       109 |                      10 |                         22 |                                       25% |                                    92 |                                    144 |
