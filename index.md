We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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

* **June 17:** Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* **June 16:** We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* **June 11**: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: June 23 (2am ET):
<p align="center">
  Current Total: <b>120,399</b> deaths | Projected Total: <b>180,316 deaths by Oct 1, 2020</b> (Range: 152-215k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.8%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 72% chance that the US surpasses 125,000 deaths by July 1, with June 30 being the most likely date.

Last updated: Jun 23, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 22, 2020 |
|              125,000 |         Jul 1, 2020 |
|              130,000 |        Jul 10, 2020 |
|              140,000 |        Jul 27, 2020 |
|              150,000 |        Aug 12, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        64% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |         9% |         59% |        84% |         95% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        14% |         40% |        56% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          2% |        14% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          120,399 |                   180,316 |                     543 |                     59,917 |                                       50% |                               152,509 |                                214,877 |
|                 [New York](/us-ny) |           31,176 |                    32,147 |                   1,652 |                        971 |                                        3% |                                31,248 |                                 34,121 |
|               [California](/us-ca) |            5,566 |                    14,306 |                     362 |                      8,740 |                                      157% |                                 7,422 |                                 22,601 |
|               [New Jersey](/us-nj) |           12,974 |                    14,010 |                   1,577 |                      1,036 |                                        8% |                                13,148 |                                 14,671 |
|                 [Illinois](/us-il) |            6,671 |                    10,226 |                     807 |                      3,555 |                                       53% |                                 7,923 |                                 12,394 |
|            [Massachusetts](/us-ma) |            7,873 |                     9,212 |                   1,326 |                      1,339 |                                       17% |                                 8,245 |                                 10,842 |
|             [Pennsylvania](/us-pa) |            6,426 |                     8,409 |                     657 |                      1,983 |                                       31% |                                 6,771 |                                 11,624 |
|                  [Florida](/us-fl) |            3,173 |                     8,201 |                     382 |                      5,028 |                                      158% |                                 4,582 |                                 12,739 |
|                 [Michigan](/us-mi) |            6,097 |                     6,734 |                     674 |                        637 |                                       10% |                                 6,200 |                                  7,824 |
|                    [Texas](/us-tx) |            2,207 |                     6,693 |                     231 |                      4,486 |                                      203% |                                 3,458 |                                 10,439 |
|                  [Georgia](/us-ga) |            2,648 |                     5,750 |                     542 |                      3,102 |                                      117% |                                 3,338 |                                  8,486 |
|                     [Ohio](/us-oh) |            2,704 |                     5,193 |                     444 |                      2,489 |                                       92% |                                 3,185 |                                  7,930 |
|              [Connecticut](/us-ct) |            4,263 |                     4,770 |                   1,338 |                        507 |                                       12% |                                 4,376 |                                  5,224 |
|                 [Maryland](/us-md) |            3,074 |                     4,624 |                     765 |                      1,550 |                                       50% |                                 3,433 |                                  5,951 |
|                  [Arizona](/us-az) |            1,351 |                     4,402 |                     605 |                      3,051 |                                      226% |                                 2,600 |                                  6,135 |
|                  [Indiana](/us-in) |            2,553 |                     4,301 |                     639 |                      1,748 |                                       68% |                                 2,805 |                                  6,901 |
|                [Louisiana](/us-la) |            3,117 |                     4,227 |                     909 |                      1,110 |                                       36% |                                 3,306 |                                  5,604 |
|           [North Carolina](/us-nc) |            1,278 |                     3,081 |                     294 |                      1,803 |                                      141% |                                 1,756 |                                  4,618 |
|                [Minnesota](/us-mn) |            1,416 |                     2,975 |                     528 |                      1,559 |                                      110% |                                 1,829 |                                  4,188 |
|                 [Virginia](/us-va) |            1,620 |                     2,648 |                     310 |                      1,028 |                                       63% |                                 1,767 |                                  4,149 |
|                 [Colorado](/us-co) |            1,651 |                     2,580 |                     448 |                        929 |                                       56% |                                 1,754 |                                  4,100 |
|               [Washington](/us-wa) |            1,276 |                     2,465 |                     324 |                      1,189 |                                       93% |                                 1,470 |                                  5,031 |
|                  [Alabama](/us-al) |              841 |                     2,275 |                     464 |                      1,434 |                                      171% |                                 1,189 |                                  3,527 |
|              [Mississippi](/us-ms) |              978 |                     2,024 |                     680 |                      1,046 |                                      107% |                                 1,186 |                                  3,150 |
|           [South Carolina](/us-sc) |              659 |                     1,925 |                     374 |                      1,266 |                                      192% |                                 1,021 |                                  2,912 |
|                 [Missouri](/us-mo) |              970 |                     1,724 |                     281 |                        754 |                                       78% |                                 1,093 |                                  2,913 |
|                [Wisconsin](/us-wi) |              745 |                     1,630 |                     280 |                        885 |                                      119% |                                   931 |                                  2,520 |
|                [Tennessee](/us-tn) |              531 |                     1,485 |                     217 |                        954 |                                      180% |                                   739 |                                  2,416 |
|             [Rhode Island](/us-ri) |              903 |                     1,392 |                   1,314 |                        489 |                                       54% |                                 1,046 |                                  1,752 |
|                     [Iowa](/us-ia) |              686 |                     1,120 |                     355 |                        434 |                                       63% |                                   757 |                                  2,153 |
|                 [Kentucky](/us-ky) |              526 |                     1,058 |                     237 |                        532 |                                      101% |                                   630 |                                  1,691 |
|               [New Mexico](/us-nm) |              469 |                       939 |                     448 |                        470 |                                      100% |                                   562 |                                  1,479 |
|                   [Nevada](/us-nv) |              489 |                       933 |                     303 |                        444 |                                       91% |                                   574 |                                  1,507 |
|                 [Arkansas](/us-ar) |              227 |                       877 |                     291 |                        650 |                                      286% |                                   496 |                                  1,282 |
|     [District of Columbia](/us-dc) |              535 |                       693 |                     982 |                        158 |                                       30% |                                   568 |                                    880 |
|            [New Hampshire](/us-nh) |              339 |                       688 |                     506 |                        349 |                                      103% |                                   397 |                                  1,088 |
|                 [Nebraska](/us-ne) |              249 |                       681 |                     352 |                        432 |                                      173% |                                   377 |                                  1,093 |
|                 [Delaware](/us-de) |              435 |                       652 |                     670 |                        217 |                                       50% |                                   478 |                                    980 |
|                 [Oklahoma](/us-ok) |              369 |                       638 |                     161 |                        269 |                                       73% |                                   418 |                                  1,103 |
|                     [Utah](/us-ut) |              158 |                       544 |                     170 |                        386 |                                      244% |                                   279 |                                    836 |
|                   [Kansas](/us-ks) |              258 |                       451 |                     155 |                        193 |                                       75% |                                   284 |                                    880 |
|                   [Oregon](/us-or) |              192 |                       417 |                      99 |                        225 |                                      117% |                                   235 |                                    682 |
|              [Puerto Rico](/us-pr) |              149 |                       201 |                      63 |                         52 |                                       35% |                                   161 |                                    295 |
|             [South Dakota](/us-sd) |               81 |                       197 |                     223 |                        116 |                                      143% |                                   102 |                                    377 |
|                    [Idaho](/us-id) |               89 |                       149 |                      83 |                         60 |                                       67% |                                    95 |                                    218 |
|                    [Maine](/us-me) |              102 |                       147 |                     109 |                         45 |                                       44% |                                   114 |                                    227 |
|             [North Dakota](/us-nd) |               77 |                       143 |                     188 |                         66 |                                       86% |                                    95 |                                    293 |
|            [West Virginia](/us-wv) |               89 |                       133 |                      74 |                         44 |                                       49% |                                   100 |                                    241 |
|                  [Vermont](/us-vt) |               56 |                        76 |                     122 |                         20 |                                       36% |                                    59 |                                    101 |
|                  [Wyoming](/us-wy) |               20 |                        62 |                     107 |                         42 |                                      210% |                                    26 |                                    115 |
|                  [Montana](/us-mt) |               21 |                        41 |                      38 |                         20 |                                       95% |                                    22 |                                     72 |
|                   [Alaska](/us-ak) |               12 |                        24 |                      33 |                         12 |                                      100% |                                    13 |                                     59 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    18 |                                     33 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     6 |                                     16 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     18 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     3 |                                     12 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          179,147 |                   198,802 |                     335 |                     19,655 |                                       11% |                               183,305 |                                225,803 |
| [United Kingdom](/united-kingdom) |           42,731 |                    46,974 |                     696 |                      4,243 |                                       10% |                                43,609 |                                 50,321 |
|                   [Italy](/italy) |           34,657 |                    36,926 |                     612 |                      2,269 |                                        7% |                                34,999 |                                 38,936 |
|                 [France](/france) |           29,666 |                    30,674 |                     458 |                      1,008 |                                        3% |                                29,707 |                                 34,596 |
|                   [Spain](/spain) |           28,324 |                    29,398 |                     626 |                      1,074 |                                        4% |                                28,384 |                                 31,855 |
|               [Germany](/germany) |            8,899 |                    10,256 |                     124 |                      1,357 |                                       15% |                                 9,036 |                                 13,541 |
|               [Belgium](/belgium) |            9,696 |                     9,941 |                     868 |                        245 |                                        3% |                                 9,721 |                                 10,501 |
|       [Netherlands](/netherlands) |            6,109 |                     6,461 |                     374 |                        352 |                                        6% |                                 6,145 |                                  6,967 |
|                 [Sweden](/sweden) |            5,122 |                     6,385 |                     624 |                      1,263 |                                       25% |                                 5,448 |                                  8,107 |
|               [Ukraine](/ukraine) |            1,022 |                     3,030 |                      69 |                      2,008 |                                      196% |                                 1,633 |                                  4,948 |
|                 [Poland](/poland) |            1,359 |                     2,938 |                      77 |                      1,579 |                                      116% |                                 1,782 |                                  4,367 |
|               [Romania](/romania) |            1,523 |                     2,509 |                     129 |                        986 |                                       65% |                                 1,771 |                                  3,744 |
|       [Switzerland](/switzerland) |            1,956 |                     2,054 |                     239 |                         98 |                                        5% |                                 1,970 |                                  2,330 |
|             [Portugal](/portugal) |            1,534 |                     1,868 |                     182 |                        334 |                                       22% |                                 1,614 |                                  2,408 |
|               [Ireland](/ireland) |            1,717 |                     1,813 |                     370 |                         96 |                                        6% |                                 1,729 |                                  2,176 |
|               [Moldova](/moldova) |              480 |                     1,575 |                     390 |                      1,095 |                                      228% |                                   994 |                                  2,212 |
|               [Belarus](/belarus) |              351 |                       799 |                      85 |                        448 |                                      128% |                                   467 |                                  1,792 |
|               [Hungary](/hungary) |              572 |                       773 |                      79 |                        201 |                                       35% |                                   599 |                                  1,128 |
|               [Austria](/austria) |              690 |                       743 |                      84 |                         53 |                                        8% |                                   705 |                                    880 |
|               [Denmark](/denmark) |              602 |                       679 |                     117 |                         77 |                                       13% |                                   622 |                                    847 |
|             [Bulgaria](/bulgaria) |              207 |                       670 |                      96 |                        463 |                                      224% |                                   352 |                                  1,052 |
|               [Czechia](/czechia) |              336 |                       419 |                      39 |                         83 |                                       25% |                                   347 |                                    535 |
|               [Finland](/finland) |              327 |                       368 |                      67 |                         41 |                                       13% |                                   332 |                                    472 |
|                 [Serbia](/serbia) |              262 |                       332 |                      48 |                         70 |                                       27% |                                   281 |                                    464 |
|                 [Norway](/norway) |              248 |                       272 |                      51 |                         24 |                                       10% |                                   255 |                                    316 |
|                 [Greece](/greece) |              190 |                       226 |                      21 |                         36 |                                       19% |                                   204 |                                    288 |
|               [Croatia](/croatia) |              107 |                       131 |                      32 |                         24 |                                       22% |                                   114 |                                    169 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    141 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   111 |                                    143 |
|           [Lithuania](/lithuania) |               76 |                       111 |                      40 |                         35 |                                       46% |                                    85 |                                    164 |
|               [Estonia](/estonia) |               69 |                        94 |                      71 |                         25 |                                       36% |                                    76 |                                    161 |
|                 [Latvia](/latvia) |               30 |                        56 |                      29 |                         26 |                                       87% |                                    33 |                                    100 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    28 |                                     66 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     43 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          165,258 |                   601,938 |                     116 |                    436,680 |                                      264% |                               338,773 |                                969,626 |
|                             [Brazil](/brazil) |           51,271 |                   129,223 |                     612 |                     77,952 |                                      152% |                                89,540 |                                222,954 |
|                               [India](/india) |           14,011 |                   125,156 |                      92 |                    111,145 |                                      793% |                                47,717 |                                230,078 |
|                             [Mexico](/mexico) |           22,584 |                   106,793 |                     837 |                     84,209 |                                      373% |                                61,438 |                                131,821 |
|                         [Pakistan](/pakistan) |            3,695 |                    30,115 |                     139 |                     26,420 |                                      715% |                                13,185 |                                 58,087 |
|                                 [Peru](/peru) |            8,223 |                    24,937 |                     767 |                     16,714 |                                      203% |                                14,917 |                                 35,795 |
|                             [Russia](/russia) |            8,196 |                    21,376 |                     147 |                     13,180 |                                      161% |                                11,953 |                                 36,915 |
|                         [Colombia](/colombia) |            2,426 |                    19,323 |                     384 |                     16,897 |                                      696% |                                10,772 |                                 26,251 |
|                                 [Iran](/iran) |            9,742 |                    18,132 |                     219 |                      8,390 |                                       86% |                                11,681 |                                 25,516 |
|                               [Chile](/chile) |            4,502 |                    18,128 |                     957 |                     13,626 |                                      303% |                                12,003 |                                 29,180 |
|                 [South Africa](/south-africa) |            1,991 |                    16,423 |                     280 |                     14,432 |                                      725% |                                 7,517 |                                 23,374 |
|                             [Canada](/canada) |            8,494 |                    11,515 |                     308 |                      3,021 |                                       36% |                                 9,068 |                                 17,545 |
|                               [Egypt](/egypt) |            2,278 |                    11,343 |                     113 |                      9,065 |                                      398% |                                 6,127 |                                 18,731 |
|                     [Bangladesh](/bangladesh) |            1,502 |                     9,417 |                      58 |                      7,915 |                                      527% |                                 5,029 |                                 15,725 |
|                       [Indonesia](/indonesia) |            2,500 |                     8,856 |                      33 |                      6,356 |                                      254% |                                 4,594 |                                 16,004 |
|                 [Saudi Arabia](/saudi-arabia) |            1,307 |                     7,912 |                     231 |                      6,605 |                                      505% |                                 5,052 |                                 11,022 |
|                       [Argentina](/argentina) |            1,043 |                     6,437 |                     144 |                      5,394 |                                      517% |                                 2,780 |                                 12,414 |
|                           [Ecuador](/ecuador) |            4,223 |                     6,123 |                     352 |                      1,900 |                                       45% |                                 4,578 |                                 10,572 |
|                             [Turkey](/turkey) |            4,974 |                     5,775 |                      69 |                        801 |                                       16% |                                 5,035 |                                  8,449 |
|                           [Bolivia](/bolivia) |              820 |                     5,287 |                     459 |                      4,467 |                                      545% |                                 2,419 |                                  8,218 |
|                               [China](/china) |            4,639 |                     4,649 |                       3 |                         10 |                                        0% |                                 4,639 |                                  4,701 |
|                           [Nigeria](/nigeria) |              525 |                     2,451 |                      12 |                      1,926 |                                      367% |                                   985 |                                  4,211 |
|                   [Philippines](/philippines) |            1,177 |                     2,333 |                      22 |                      1,156 |                                       98% |                                 1,303 |                                  4,055 |
|                           [Algeria](/algeria) |              852 |                     2,054 |                      48 |                      1,202 |                                      141% |                                 1,200 |                                  4,023 |
|                         [Honduras](/honduras) |              395 |                     1,652 |                     170 |                      1,257 |                                      318% |                                   816 |                                  2,713 |
|                             [Panama](/panama) |              521 |                     1,458 |                     343 |                        937 |                                      180% |                                   760 |                                  2,572 |
|     [Dominican Republic](/dominican-republic) |              669 |                     1,381 |                     129 |                        712 |                                      106% |                                   811 |                                  3,143 |
|                               [Japan](/japan) |              955 |                     1,270 |                      10 |                        315 |                                       33% |                                   961 |                                  1,795 |
|                             [Kuwait](/kuwait) |              330 |                       606 |                     144 |                        276 |                                       84% |                                   410 |                                    931 |
| [United Arab Emirates](/united-arab-emirates) |              303 |                       423 |                      43 |                        120 |                                       40% |                                   327 |                                    712 |
|                             [Israel](/israel) |              307 |                       388 |                      46 |                         81 |                                       26% |                                   323 |                                    616 |
|                   [South Korea](/south-korea) |              281 |                       341 |                       7 |                         60 |                                       21% |                                   284 |                                    540 |
|                           [Morocco](/morocco) |              214 |                       239 |                       7 |                         25 |                                       12% |                                   223 |                                    292 |
|                         [Malaysia](/malaysia) |              121 |                       211 |                       7 |                         90 |                                       74% |                                   134 |                                    404 |
|                       [Australia](/australia) |              102 |                       110 |                       4 |                          8 |                                        8% |                                   102 |                                    140 |
|                                 [Cuba](/cuba) |               85 |                       101 |                       9 |                         16 |                                       19% |                                    90 |                                    127 |
