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
### Updated Daily - Last Updated: July 25 (5am ET):
<p align="center">
  Current Total: <b>145,543</b> deaths | Projected Total: <b>220,600 deaths by Nov 1, 2020</b> (Range: 188-271k)<br>
  Currently Infected: <b>2.0%</b> | Total Infected: <b>10.6%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 25, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 29, 2020 |
|              175,000 |        Aug 25, 2020 |
|              200,000 |         Oct 1, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          9% |        79% |         99% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         7% |         27% |        51% |         66% |        78% |
|              225,000 |        <1% |         <1% |        <1% |          3% |        11% |         19% |        30% |
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
|             *[United States](/us)* |          145,543 |                   220,645 |                     665 |                     75,102 |                                       52% |                               188,679 |                                270,062 |
|                 [New York](/us-ny) |           32,596 |                    33,700 |                   1,732 |                      1,104 |                                        3% |                                32,649 |                                 38,355 |
|               [California](/us-ca) |            8,337 |                    16,927 |                     428 |                      8,590 |                                      103% |                                11,620 |                                 25,502 |
|               [New Jersey](/us-nj) |           15,765 |                    16,266 |                   1,831 |                        501 |                                        3% |                                15,830 |                                 17,059 |
|                    [Texas](/us-tx) |            4,790 |                    15,906 |                     549 |                     11,116 |                                      232% |                                10,164 |                                 24,129 |
|                  [Florida](/us-fl) |            5,653 |                    14,347 |                     668 |                      8,694 |                                      154% |                                 9,660 |                                 21,560 |
|             [Pennsylvania](/us-pa) |            7,116 |                     9,590 |                     749 |                      2,474 |                                       35% |                                 7,451 |                                 14,162 |
|            [Massachusetts](/us-ma) |            8,498 |                     9,107 |                   1,310 |                        609 |                                        7% |                                 8,579 |                                 10,161 |
|                 [Illinois](/us-il) |            7,577 |                     8,872 |                     700 |                      1,295 |                                       17% |                                 7,783 |                                 10,700 |
|                  [Georgia](/us-ga) |            3,443 |                     7,644 |                     720 |                      4,201 |                                      122% |                                 4,705 |                                 13,172 |
|                 [Michigan](/us-mi) |            6,400 |                     7,302 |                     731 |                        902 |                                       14% |                                 6,521 |                                  9,365 |
|                  [Arizona](/us-az) |            3,143 |                     6,778 |                     931 |                      3,635 |                                      116% |                                 4,997 |                                  9,275 |
|                     [Ohio](/us-oh) |            3,297 |                     6,128 |                     524 |                      2,831 |                                       86% |                                 3,973 |                                 10,690 |
|                [Louisiana](/us-la) |            3,715 |                     5,662 |                   1,218 |                      1,947 |                                       52% |                                 4,191 |                                  8,361 |
|              [Connecticut](/us-ct) |            4,413 |                     4,645 |                   1,303 |                        232 |                                        5% |                                 4,451 |                                  5,099 |
|                  [Indiana](/us-in) |            2,884 |                     4,435 |                     659 |                      1,551 |                                       54% |                                 3,119 |                                  7,645 |
|                 [Maryland](/us-md) |            3,422 |                     4,091 |                     677 |                        669 |                                       20% |                                 3,530 |                                  5,328 |
|           [South Carolina](/us-sc) |            1,385 |                     3,918 |                     761 |                      2,533 |                                      183% |                                 2,648 |                                  5,666 |
|           [North Carolina](/us-nc) |            1,789 |                     3,831 |                     365 |                      2,042 |                                      114% |                                 2,489 |                                  6,178 |
|                 [Virginia](/us-va) |            2,067 |                     3,707 |                     434 |                      1,640 |                                       79% |                                 2,318 |                                  7,161 |
|                  [Alabama](/us-al) |            1,438 |                     3,680 |                     751 |                      2,242 |                                      156% |                                 2,488 |                                  5,557 |
|                 [Colorado](/us-co) |            1,790 |                     2,861 |                     497 |                      1,071 |                                       60% |                                 2,019 |                                  5,026 |
|              [Mississippi](/us-ms) |            1,463 |                     2,724 |                     915 |                      1,261 |                                       86% |                                 2,007 |                                  3,915 |
|                [Minnesota](/us-mn) |            1,606 |                     2,420 |                     429 |                        814 |                                       51% |                                 1,791 |                                  3,913 |
|                [Tennessee](/us-tn) |              938 |                     2,354 |                     344 |                      1,416 |                                      151% |                                 1,584 |                                  3,612 |
|                 [Missouri](/us-mo) |            1,195 |                     2,317 |                     377 |                      1,122 |                                       94% |                                 1,432 |                                  4,300 |
|                   [Nevada](/us-nv) |              722 |                     2,217 |                     720 |                      1,495 |                                      207% |                                 1,352 |                                  3,714 |
|               [Washington](/us-wa) |            1,495 |                     2,073 |                     272 |                        578 |                                       39% |                                 1,573 |                                  3,116 |
|                [Wisconsin](/us-wi) |              878 |                     1,782 |                     306 |                        904 |                                      103% |                                 1,071 |                                  3,652 |
|                 [Kentucky](/us-ky) |              691 |                     1,739 |                     389 |                      1,048 |                                      152% |                                   924 |                                  3,618 |
|                     [Iowa](/us-ia) |              826 |                     1,524 |                     483 |                        698 |                                       84% |                                 1,005 |                                  2,677 |
|             [Rhode Island](/us-ri) |            1,002 |                     1,177 |                   1,111 |                        175 |                                       17% |                                 1,033 |                                  1,403 |
|               [New Mexico](/us-nm) |              601 |                     1,089 |                     520 |                        488 |                                       81% |                                   682 |                                  1,891 |
|                 [Oklahoma](/us-ok) |              484 |                       979 |                     247 |                        495 |                                      102% |                                   631 |                                  1,649 |
|                   [Oregon](/us-or) |              282 |                       975 |                     231 |                        693 |                                      246% |                                   498 |                                  1,963 |
|                 [Arkansas](/us-ar) |              394 |                       965 |                     320 |                        571 |                                      145% |                                   620 |                                  1,554 |
|                    [Idaho](/us-id) |              144 |                       885 |                     495 |                        741 |                                      515% |                                   415 |                                  1,632 |
|                     [Utah](/us-ut) |              273 |                       872 |                     272 |                        599 |                                      219% |                                   498 |                                  1,515 |
|                 [Delaware](/us-de) |              578 |                       714 |                     733 |                        136 |                                       24% |                                   598 |                                    915 |
|              [Puerto Rico](/us-pr) |              191 |                       696 |                     218 |                        505 |                                      264% |                                   267 |                                  1,721 |
|                   [Kansas](/us-ks) |              330 |                       658 |                     226 |                        328 |                                       99% |                                   417 |                                  1,147 |
|     [District of Columbia](/us-dc) |              581 |                       645 |                     914 |                         64 |                                       11% |                                   594 |                                    756 |
|            [New Hampshire](/us-nh) |              407 |                       542 |                     398 |                        135 |                                       33% |                                   422 |                                    779 |
|                 [Nebraska](/us-ne) |              316 |                       517 |                     267 |                        201 |                                       64% |                                   354 |                                    837 |
|                  [Montana](/us-mt) |               46 |                       251 |                     235 |                        205 |                                      447% |                                   114 |                                    504 |
|             [North Dakota](/us-nd) |               99 |                       231 |                     303 |                        132 |                                      133% |                                   134 |                                    433 |
|             [South Dakota](/us-sd) |              122 |                       226 |                     256 |                        104 |                                       85% |                                   155 |                                    368 |
|            [West Virginia](/us-wv) |              103 |                       190 |                     106 |                         87 |                                       84% |                                   124 |                                    375 |
|                    [Maine](/us-me) |              118 |                       172 |                     128 |                         54 |                                       46% |                                   129 |                                    258 |
|                   [Hawaii](/us-hi) |               26 |                        90 |                      64 |                         64 |                                      248% |                                    37 |                                    230 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     121 |                         20 |                                       35% |                                    62 |                                    101 |
|                   [Alaska](/us-ak) |               19 |                        59 |                      80 |                         40 |                                      209% |                                    30 |                                    126 |
|                  [Wyoming](/us-wy) |               25 |                        52 |                      90 |                         27 |                                      108% |                                    37 |                                     88 |
|           [Virgin Islands](/us-vi) |                7 |                        24 |                     227 |                         17 |                                      240% |                                    10 |                                     56 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                       99% |                                     6 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      102% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,906 |                   202,478 |                     341 |                     15,572 |                                        8% |                               190,904 |                                231,093 |
| [United Kingdom](/united-kingdom) |           45,762 |                    49,530 |                     733 |                      3,768 |                                        8% |                                46,271 |                                 57,207 |
|                   [Italy](/italy) |           35,097 |                    35,700 |                     591 |                        603 |                                        2% |                                35,121 |                                 37,320 |
|                 [France](/france) |           30,195 |                    30,862 |                     461 |                        667 |                                        2% |                                30,224 |                                 34,262 |
|                   [Spain](/spain) |           28,432 |                    28,924 |                     616 |                        492 |                                        2% |                                28,454 |                                 31,155 |
|               [Belgium](/belgium) |            9,817 |                     9,898 |                     864 |                         81 |                                        1% |                                 9,833 |                                 10,194 |
|               [Germany](/germany) |            9,120 |                     9,405 |                     113 |                        285 |                                        3% |                                 9,132 |                                 10,580 |
|       [Netherlands](/netherlands) |            6,158 |                     6,231 |                     361 |                         73 |                                        1% |                                 6,167 |                                  6,463 |
|                 [Sweden](/sweden) |            5,697 |                     6,160 |                     602 |                        463 |                                        8% |                                 5,809 |                                  6,917 |
|               [Romania](/romania) |            2,150 |                     4,585 |                     236 |                      2,435 |                                      113% |                                 3,226 |                                  7,327 |
|               [Ukraine](/ukraine) |            1,591 |                     3,249 |                      74 |                      1,658 |                                      104% |                                 2,258 |                                  5,021 |
|             [Portugal](/portugal) |            1,712 |                     2,207 |                     215 |                        495 |                                       29% |                                 1,767 |                                  2,992 |
|                 [Poland](/poland) |            1,655 |                     2,185 |                      58 |                        530 |                                       32% |                                 1,726 |                                  3,172 |
|       [Switzerland](/switzerland) |            1,977 |                     2,055 |                     239 |                         78 |                                        4% |                                 1,989 |                                  2,252 |
|               [Ireland](/ireland) |            1,763 |                     1,851 |                     377 |                         88 |                                        5% |                                 1,775 |                                  2,149 |
|                 [Serbia](/serbia) |              518 |                     1,614 |                     232 |                      1,096 |                                      212% |                                 1,000 |                                  2,666 |
|               [Moldova](/moldova) |              726 |                     1,474 |                     365 |                        748 |                                      103% |                                   998 |                                  2,167 |
|             [Bulgaria](/bulgaria) |              337 |                       984 |                     141 |                        647 |                                      192% |                                   569 |                                  1,690 |
|               [Belarus](/belarus) |              524 |                       980 |                     104 |                        456 |                                       87% |                                   691 |                                  1,454 |
|               [Austria](/austria) |              711 |                       783 |                      88 |                         72 |                                       10% |                                   727 |                                    908 |
|               [Hungary](/hungary) |              596 |                       697 |                      71 |                        101 |                                       17% |                                   610 |                                    904 |
|               [Denmark](/denmark) |              613 |                       692 |                     119 |                         79 |                                       13% |                                   630 |                                    819 |
|               [Czechia](/czechia) |              369 |                       580 |                      54 |                        211 |                                       57% |                                   411 |                                    994 |
|               [Finland](/finland) |              329 |                       381 |                      69 |                         52 |                                       16% |                                   341 |                                    482 |
|               [Croatia](/croatia) |              128 |                       297 |                      73 |                        169 |                                      132% |                                   188 |                                    506 |
|                 [Norway](/norway) |              255 |                       284 |                      53 |                         29 |                                       11% |                                   263 |                                    330 |
|                 [Greece](/greece) |              201 |                       246 |                      23 |                         45 |                                       23% |                                   211 |                                    305 |
|         [Luxembourg](/luxembourg) |              112 |                       159 |                     259 |                         47 |                                       42% |                                   128 |                                    220 |
|             [Slovenia](/slovenia) |              115 |                       137 |                      66 |                         22 |                                       19% |                                   119 |                                    175 |
|           [Lithuania](/lithuania) |               80 |                       105 |                      38 |                         25 |                                       32% |                                    84 |                                    143 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    77 |                                    123 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       32% |                                    33 |                                     60 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       28% |                                    29 |                                     53 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       52% |                                    22 |                                     43 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       62% |                                    11 |                                     19 |
|               [Iceland](/iceland) |               10 |                        14 |                      40 |                          4 |                                       37% |                                    10 |                                     21 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          289,379 |                   666,846 |                     128 |                    377,467 |                                      130% |                               419,879 |                              1,070,031 |
|                             [Brazil](/brazil) |           85,238 |                   170,652 |                     809 |                     85,414 |                                      100% |                               118,579 |                                263,900 |
|                               [India](/india) |           31,358 |                   138,876 |                     102 |                    107,518 |                                      343% |                                63,724 |                                228,971 |
|                             [Mexico](/mexico) |           42,645 |                    91,768 |                     719 |                     49,123 |                                      115% |                                62,642 |                                158,871 |
|                                 [Peru](/peru) |           17,843 |                    29,553 |                     909 |                     11,710 |                                       66% |                                20,183 |                                 45,709 |
|                         [Colombia](/colombia) |            7,975 |                    28,695 |                     570 |                     20,720 |                                      260% |                                18,546 |                                 41,575 |
|                                 [Iran](/iran) |           15,289 |                    27,580 |                     333 |                     12,291 |                                       80% |                                21,168 |                                 37,421 |
|                 [South Africa](/south-africa) |            6,343 |                    23,695 |                     405 |                     17,352 |                                      274% |                                11,882 |                                 36,251 |
|                             [Russia](/russia) |           13,026 |                    23,203 |                     159 |                     10,177 |                                       78% |                                14,965 |                                 39,703 |
|                       [Indonesia](/indonesia) |            4,665 |                    19,214 |                      71 |                     14,549 |                                      312% |                                10,039 |                                 37,263 |
|                               [Chile](/chile) |            8,914 |                    15,124 |                     798 |                      6,210 |                                       70% |                                 9,793 |                                 26,490 |
|                       [Argentina](/argentina) |            2,807 |                    10,989 |                     245 |                      8,182 |                                      291% |                                 6,047 |                                 17,129 |
|                             [Canada](/canada) |            8,923 |                     9,430 |                     252 |                        507 |                                        6% |                                 8,951 |                                 10,524 |
|                         [Pakistan](/pakistan) |            5,787 |                     8,185 |                      38 |                      2,398 |                                       41% |                                 6,480 |                                 11,730 |
|                           [Ecuador](/ecuador) |            5,468 |                     7,913 |                     455 |                      2,445 |                                       45% |                                 5,694 |                                 11,442 |
|                               [Egypt](/egypt) |            4,518 |                     7,854 |                      78 |                      3,336 |                                       74% |                                 5,224 |                                 13,280 |
|                             [Turkey](/turkey) |            5,580 |                     6,704 |                      80 |                      1,124 |                                       20% |                                 5,707 |                                  8,813 |
|                           [Bolivia](/bolivia) |            2,473 |                     6,452 |                     560 |                      3,979 |                                      161% |                                 4,237 |                                  9,673 |
|                     [Bangladesh](/bangladesh) |            2,836 |                     5,577 |                      34 |                      2,741 |                                       97% |                                 3,311 |                                  9,990 |
|                 [Saudi Arabia](/saudi-arabia) |            2,672 |                     5,207 |                     152 |                      2,535 |                                       95% |                                 3,627 |                                  8,100 |
|                   [Philippines](/philippines) |            1,879 |                     5,161 |                      48 |                      3,282 |                                      175% |                                 2,233 |                                 11,448 |
|                               [China](/china) |            4,650 |                     4,696 |                       3 |                         46 |                                        1% |                                 4,650 |                                  5,033 |
|                         [Honduras](/honduras) |            1,061 |                     3,779 |                     388 |                      2,718 |                                      256% |                                 2,193 |                                  6,178 |
|                             [Panama](/panama) |            1,250 |                     3,476 |                     819 |                      2,226 |                                      178% |                                 2,352 |                                  5,135 |
|                           [Algeria](/algeria) |            1,136 |                     2,324 |                      54 |                      1,188 |                                      105% |                                 1,327 |                                  4,674 |
|     [Dominican Republic](/dominican-republic) |            1,036 |                     2,177 |                     203 |                      1,141 |                                      110% |                                 1,380 |                                  3,531 |
|                           [Nigeria](/nigeria) |              845 |                     1,703 |                       8 |                        858 |                                      101% |                                   941 |                                  3,901 |
|                             [Israel](/israel) |              448 |                     1,556 |                     183 |                      1,108 |                                      247% |                                   819 |                                  2,650 |
|                               [Japan](/japan) |              994 |                     1,451 |                      11 |                        457 |                                       46% |                                 1,003 |                                  3,204 |
|                       [Australia](/australia) |              145 |                     1,172 |                      47 |                      1,027 |                                      708% |                                   395 |                                  2,649 |
|                           [Morocco](/morocco) |              299 |                       901 |                      25 |                        602 |                                      201% |                                   456 |                                  1,856 |
|                             [Kuwait](/kuwait) |              425 |                       657 |                     156 |                        232 |                                       54% |                                   452 |                                  1,197 |
| [United Arab Emirates](/united-arab-emirates) |              343 |                       472 |                      48 |                        129 |                                       37% |                                   353 |                                    801 |
|                   [South Korea](/south-korea) |              298 |                       383 |                       7 |                         85 |                                       29% |                                   300 |                                    620 |
|                         [Malaysia](/malaysia) |              123 |                       160 |                       5 |                         37 |                                       30% |                                   136 |                                    181 |
|                                 [Cuba](/cuba) |               87 |                       107 |                       9 |                         20 |                                       23% |                                    90 |                                    138 |
