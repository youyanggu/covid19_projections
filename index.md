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
### Updated Daily - Last Updated: June 22 (4am ET):
<p align="center">
  Current Total: <b>119,966</b> deaths | Projected Total: <b>180,604 deaths by Oct 1, 2020</b> (Range: 152-216k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.8%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.

*June 18 note:* We moved the R_t Dashboard map to the [Maps](/maps) page and replaced it with our C19Pro Score for deaths.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 72% chance that the US surpasses 125,000 deaths by July 1, with June 30 being the most likely date.

Last updated: Jun 22, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 22, 2020 |
|              125,000 |        Jun 30, 2020 |
|              130,000 |        Jul 10, 2020 |
|              140,000 |        Jul 27, 2020 |
|              150,000 |        Aug 12, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        72% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        10% |         60% |        85% |         95% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        15% |         40% |        56% |
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
|             *[United States](/us)* |          119,716 |                   183,005 |                     552 |                     63,289 |                                       53% |                               153,838 |                                218,846 |
|                 [New York](/us-ny) |           31,083 |                    32,238 |                   1,657 |                      1,155 |                                        4% |                                31,178 |                                 35,280 |
|               [New Jersey](/us-nj) |           12,924 |                    14,707 |                   1,656 |                      1,783 |                                       14% |                                13,329 |                                 16,254 |
|               [California](/us-ca) |            5,494 |                    14,556 |                     368 |                      9,062 |                                      165% |                                 7,478 |                                 22,859 |
|                 [Illinois](/us-il) |            6,625 |                    10,312 |                     814 |                      3,687 |                                       56% |                                 7,961 |                                 12,504 |
|            [Massachusetts](/us-ma) |            7,827 |                     9,231 |                   1,328 |                      1,404 |                                       18% |                                 8,239 |                                 10,901 |
|                  [Florida](/us-fl) |            3,144 |                     8,557 |                     398 |                      5,413 |                                      172% |                                 4,646 |                                 13,175 |
|             [Pennsylvania](/us-pa) |            6,419 |                     8,509 |                     665 |                      2,090 |                                       33% |                                 6,818 |                                 11,755 |
|                    [Texas](/us-tx) |            2,183 |                     7,037 |                     243 |                      4,854 |                                      222% |                                 3,527 |                                 10,801 |
|                 [Michigan](/us-mi) |            6,087 |                     6,766 |                     677 |                        679 |                                       11% |                                 6,219 |                                  7,900 |
|                  [Georgia](/us-ga) |            2,642 |                     5,906 |                     556 |                      3,264 |                                      124% |                                 3,402 |                                  8,664 |
|                     [Ohio](/us-oh) |            2,697 |                     5,306 |                     454 |                      2,609 |                                       97% |                                 3,213 |                                  8,043 |
|              [Connecticut](/us-ct) |            4,251 |                     4,830 |                   1,355 |                        579 |                                       14% |                                 4,389 |                                  5,652 |
|                 [Maryland](/us-md) |            3,052 |                     4,647 |                     769 |                      1,595 |                                       52% |                                 3,427 |                                  5,991 |
|                  [Arizona](/us-az) |            1,346 |                     4,626 |                     636 |                      3,280 |                                      244% |                                 2,838 |                                  6,318 |
|                  [Indiana](/us-in) |            2,536 |                     4,358 |                     647 |                      1,822 |                                       72% |                                 2,800 |                                  6,987 |
|                [Louisiana](/us-la) |            3,104 |                     4,130 |                     888 |                      1,026 |                                       33% |                                 3,307 |                                  5,587 |
|                [Minnesota](/us-mn) |            1,404 |                     3,021 |                     536 |                      1,617 |                                      115% |                                 1,840 |                                  4,232 |
|           [North Carolina](/us-nc) |            1,215 |                     3,002 |                     286 |                      1,787 |                                      147% |                                 1,691 |                                  4,516 |
|                 [Virginia](/us-va) |            1,607 |                     2,659 |                     312 |                      1,052 |                                       65% |                                 1,765 |                                  4,175 |
|                 [Colorado](/us-co) |            1,647 |                     2,604 |                     452 |                        957 |                                       58% |                                 1,758 |                                  4,146 |
|                  [Alabama](/us-al) |              838 |                     2,412 |                     492 |                      1,574 |                                      188% |                                 1,245 |                                  3,703 |
|               [Washington](/us-wa) |            1,265 |                     2,262 |                     297 |                        997 |                                       79% |                                 1,392 |                                  4,615 |
|           [South Carolina](/us-sc) |              644 |                     1,944 |                     378 |                      1,300 |                                      202% |                                 1,022 |                                  2,940 |
|              [Mississippi](/us-ms) |              938 |                     1,931 |                     649 |                        993 |                                      106% |                                 1,127 |                                  3,080 |
|                 [Missouri](/us-mo) |              965 |                     1,758 |                     286 |                        793 |                                       82% |                                 1,096 |                                  2,973 |
|                [Wisconsin](/us-wi) |              744 |                     1,694 |                     291 |                        950 |                                      128% |                                   949 |                                  2,581 |
|                [Tennessee](/us-tn) |              524 |                     1,574 |                     230 |                      1,050 |                                      200% |                                   761 |                                  2,522 |
|             [Rhode Island](/us-ri) |              894 |                     1,398 |                   1,320 |                        504 |                                       56% |                                 1,045 |                                  1,764 |
|                     [Iowa](/us-ia) |              681 |                     1,123 |                     356 |                        442 |                                       65% |                                   756 |                                  2,179 |
|                 [Kentucky](/us-ky) |              524 |                     1,077 |                     241 |                        553 |                                      106% |                                   635 |                                  1,723 |
|               [New Mexico](/us-nm) |              466 |                       954 |                     455 |                        488 |                                      105% |                                   566 |                                  1,503 |
|                   [Nevada](/us-nv) |              486 |                       953 |                     309 |                        467 |                                       96% |                                   578 |                                  1,532 |
|                 [Arkansas](/us-ar) |              224 |                       905 |                     300 |                        681 |                                      304% |                                   504 |                                  1,320 |
|            [New Hampshire](/us-nh) |              339 |                       763 |                     561 |                        424 |                                      125% |                                   420 |                                  1,198 |
|     [District of Columbia](/us-dc) |              531 |                       694 |                     983 |                        163 |                                       31% |                                   567 |                                    885 |
|                 [Nebraska](/us-ne) |              244 |                       692 |                     358 |                        448 |                                      184% |                                   383 |                                  1,120 |
|                 [Delaware](/us-de) |              434 |                       658 |                     676 |                        224 |                                       52% |                                   480 |                                    992 |
|                 [Oklahoma](/us-ok) |              368 |                       649 |                     164 |                        281 |                                       76% |                                   420 |                                  1,127 |
|                     [Utah](/us-ut) |              155 |                       528 |                     165 |                        373 |                                      241% |                                   282 |                                    807 |
|                   [Kansas](/us-ks) |              256 |                       457 |                     157 |                        201 |                                       79% |                                   283 |                                    890 |
|                   [Oregon](/us-or) |              188 |                       411 |                      97 |                        223 |                                      119% |                                   228 |                                    676 |
|             [South Dakota](/us-sd) |               81 |                       201 |                     227 |                        120 |                                      148% |                                   106 |                                    386 |
|              [Puerto Rico](/us-pr) |              147 |                       199 |                      62 |                         52 |                                       35% |                                   159 |                                    293 |
|                    [Maine](/us-me) |              102 |                       148 |                     110 |                         46 |                                       45% |                                   115 |                                    229 |
|             [North Dakota](/us-nd) |               76 |                       144 |                     189 |                         68 |                                       89% |                                    95 |                                    295 |
|            [West Virginia](/us-wv) |               88 |                       132 |                      74 |                         44 |                                       50% |                                    99 |                                    232 |
|                    [Idaho](/us-id) |               89 |                       129 |                      72 |                         40 |                                       45% |                                    95 |                                    213 |
|                  [Vermont](/us-vt) |               56 |                        69 |                     111 |                         13 |                                       23% |                                    59 |                                     93 |
|                  [Wyoming](/us-wy) |               20 |                        64 |                     111 |                         44 |                                      220% |                                    28 |                                    117 |
|                  [Montana](/us-mt) |               20 |                        29 |                      27 |                          9 |                                       45% |                                    21 |                                     70 |
|                   [Hawaii](/us-hi) |               17 |                        20 |                      14 |                          3 |                                       18% |                                    17 |                                     24 |
|                   [Alaska](/us-ak) |               12 |                        15 |                      21 |                          3 |                                       25% |                                    12 |                                     18 |
|           [Virgin Islands](/us-vi) |                6 |                         7 |                      67 |                          1 |                                       17% |                                     7 |                                      8 |
|                     [Guam](/us-gu) |                5 |                         6 |                      36 |                          1 |                                       20% |                                     5 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          178,953 |                   199,041 |                     336 |                     20,088 |                                       11% |                               183,266 |                                226,205 |
| [United Kingdom](/united-kingdom) |           42,717 |                    47,163 |                     698 |                      4,446 |                                       10% |                                43,664 |                                 50,439 |
|                   [Italy](/italy) |           34,634 |                    36,948 |                     612 |                      2,314 |                                        7% |                                34,989 |                                 38,976 |
|                 [France](/france) |           29,643 |                    30,671 |                     458 |                      1,028 |                                        3% |                                29,687 |                                 34,633 |
|                   [Spain](/spain) |           28,323 |                    29,414 |                     627 |                      1,091 |                                        4% |                                28,385 |                                 31,897 |
|               [Germany](/germany) |            8,895 |                    10,272 |                     124 |                      1,377 |                                       15% |                                 9,038 |                                 13,567 |
|               [Belgium](/belgium) |            9,696 |                     9,946 |                     868 |                        250 |                                        3% |                                 9,722 |                                 10,514 |
|       [Netherlands](/netherlands) |            6,109 |                     6,466 |                     374 |                        357 |                                        6% |                                 6,147 |                                  6,975 |
|                 [Sweden](/sweden) |            5,053 |                     6,287 |                     615 |                      1,234 |                                       24% |                                 5,378 |                                  8,074 |
|               [Ukraine](/ukraine) |            1,012 |                     3,102 |                      71 |                      2,090 |                                      207% |                                 1,642 |                                  5,086 |
|                 [Poland](/poland) |            1,356 |                     2,996 |                      79 |                      1,640 |                                      121% |                                 1,806 |                                  4,434 |
|               [Romania](/romania) |            1,512 |                     2,505 |                     129 |                        993 |                                       66% |                                 1,766 |                                  3,745 |
|       [Switzerland](/switzerland) |            1,956 |                     2,054 |                     239 |                         98 |                                        5% |                                 1,970 |                                  2,333 |
|             [Portugal](/portugal) |            1,530 |                     1,866 |                     182 |                        336 |                                       22% |                                 1,613 |                                  2,411 |
|               [Ireland](/ireland) |            1,715 |                     1,811 |                     369 |                         96 |                                        6% |                                 1,727 |                                  2,174 |
|               [Moldova](/moldova) |              473 |                     1,590 |                     393 |                      1,117 |                                      236% |                                   995 |                                  2,230 |
|               [Belarus](/belarus) |              346 |                       811 |                      86 |                        465 |                                      134% |                                   467 |                                  1,800 |
|               [Hungary](/hungary) |              570 |                       771 |                      79 |                        201 |                                       35% |                                   597 |                                  1,126 |
|               [Austria](/austria) |              690 |                       744 |                      84 |                         54 |                                        8% |                                   705 |                                    882 |
|               [Denmark](/denmark) |              600 |                       675 |                     116 |                         75 |                                       12% |                                   620 |                                    842 |
|             [Bulgaria](/bulgaria) |              199 |                       615 |                      88 |                        416 |                                      209% |                                   333 |                                    974 |
|               [Czechia](/czechia) |              336 |                       420 |                      39 |                         84 |                                       25% |                                   347 |                                    536 |
|               [Finland](/finland) |              326 |                       367 |                      67 |                         41 |                                       13% |                                   331 |                                    471 |
|                 [Serbia](/serbia) |              261 |                       331 |                      48 |                         70 |                                       27% |                                   280 |                                    464 |
|                 [Norway](/norway) |              244 |                       266 |                      49 |                         22 |                                        9% |                                   251 |                                    308 |
|                 [Greece](/greece) |              190 |                       228 |                      21 |                         38 |                                       20% |                                   204 |                                    291 |
|               [Croatia](/croatia) |              107 |                       131 |                      32 |                         24 |                                       22% |                                   114 |                                    169 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    141 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   111 |                                    143 |
|           [Lithuania](/lithuania) |               76 |                       113 |                      40 |                         37 |                                       49% |                                    86 |                                    166 |
|               [Estonia](/estonia) |               69 |                        95 |                      72 |                         26 |                                       38% |                                    77 |                                    161 |
|                 [Latvia](/latvia) |               30 |                        56 |                      29 |                         26 |                                       87% |                                    34 |                                    101 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    28 |                                     66 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     43 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          162,268 |                   591,518 |                     114 |                    429,250 |                                      265% |                               332,831 |                                943,697 |
|                               [India](/india) |           13,699 |                   131,418 |                      96 |                    117,719 |                                      859% |                                50,516 |                                237,502 |
|                             [Brazil](/brazil) |           50,591 |                   122,552 |                     581 |                     71,961 |                                      142% |                                74,849 |                                193,122 |
|                             [Mexico](/mexico) |           21,825 |                    84,914 |                     666 |                     63,089 |                                      289% |                                55,497 |                                109,827 |
|                         [Pakistan](/pakistan) |            3,590 |                    30,785 |                     142 |                     27,195 |                                      758% |                                13,363 |                                 62,041 |
|                         [Colombia](/colombia) |            2,353 |                    28,187 |                     560 |                     25,834 |                                     1098% |                                20,641 |                                 36,086 |
|                                 [Peru](/peru) |            7,861 |                    23,081 |                     710 |                     15,220 |                                      194% |                                14,121 |                                 34,536 |
|                               [Chile](/chile) |            4,479 |                    22,173 |                   1,170 |                     17,694 |                                      395% |                                14,889 |                                 34,217 |
|                             [Russia](/russia) |            8,101 |                    21,829 |                     150 |                     13,728 |                                      169% |                                12,053 |                                 37,604 |
|                                 [Iran](/iran) |            9,623 |                    18,002 |                     217 |                      8,379 |                                       87% |                                11,379 |                                 25,516 |
|                 [South Africa](/south-africa) |            1,930 |                    16,602 |                     284 |                     14,672 |                                      760% |                                 7,673 |                                 23,715 |
|                             [Canada](/canada) |            8,482 |                    11,585 |                     310 |                      3,103 |                                       37% |                                 9,083 |                                 17,643 |
|                               [Egypt](/egypt) |            2,193 |                    11,178 |                     111 |                      8,985 |                                      410% |                                 6,028 |                                 18,564 |
|                     [Bangladesh](/bangladesh) |            1,464 |                     9,515 |                      58 |                      8,051 |                                      550% |                                 5,121 |                                 15,855 |
|                       [Indonesia](/indonesia) |            2,465 |                     8,919 |                      33 |                      6,454 |                                      262% |                                 4,590 |                                 16,252 |
|                 [Saudi Arabia](/saudi-arabia) |            1,267 |                     7,901 |                     231 |                      6,634 |                                      524% |                                 5,027 |                                 11,031 |
|                       [Argentina](/argentina) |            1,011 |                     6,421 |                     143 |                      5,410 |                                      535% |                                 2,747 |                                 12,459 |
|                           [Ecuador](/ecuador) |            4,223 |                     6,208 |                     357 |                      1,985 |                                       47% |                                 4,594 |                                 10,829 |
|                             [Turkey](/turkey) |            4,950 |                     5,749 |                      69 |                        799 |                                       16% |                                 5,014 |                                  8,397 |
|                           [Bolivia](/bolivia) |              773 |                     5,177 |                     450 |                      4,404 |                                      570% |                                 2,453 |                                  7,886 |
|                               [China](/china) |            4,639 |                     4,649 |                       3 |                         10 |                                        0% |                                 4,639 |                                  4,702 |
|                           [Nigeria](/nigeria) |              518 |                     2,498 |                      12 |                      1,980 |                                      382% |                                   998 |                                  4,263 |
|                   [Philippines](/philippines) |            1,169 |                     2,329 |                      22 |                      1,160 |                                       99% |                                 1,297 |                                  4,064 |
|                           [Algeria](/algeria) |              845 |                     2,056 |                      48 |                      1,211 |                                      143% |                                 1,197 |                                  4,030 |
|                         [Honduras](/honduras) |              363 |                     1,419 |                     146 |                      1,056 |                                      291% |                                   696 |                                  2,501 |
|     [Dominican Republic](/dominican-republic) |              662 |                     1,374 |                     128 |                        712 |                                      108% |                                   805 |                                  3,141 |
|                             [Panama](/panama) |              501 |                     1,309 |                     308 |                        808 |                                      161% |                                   718 |                                  2,348 |
|                               [Japan](/japan) |              955 |                     1,273 |                      10 |                        318 |                                       33% |                                   961 |                                  1,801 |
|                             [Kuwait](/kuwait) |              326 |                       603 |                     143 |                        277 |                                       85% |                                   401 |                                    934 |
| [United Arab Emirates](/united-arab-emirates) |              302 |                       424 |                      43 |                        122 |                                       40% |                                   327 |                                    715 |
|                             [Israel](/israel) |              306 |                       386 |                      45 |                         80 |                                       26% |                                   322 |                                    613 |
|                   [South Korea](/south-korea) |              280 |                       339 |                       7 |                         59 |                                       21% |                                   283 |                                    536 |
|                           [Morocco](/morocco) |              214 |                       240 |                       7 |                         26 |                                       12% |                                   223 |                                    293 |
|                         [Malaysia](/malaysia) |              121 |                       212 |                       7 |                         91 |                                       75% |                                   134 |                                    407 |
|                       [Australia](/australia) |              102 |                       110 |                       4 |                          8 |                                        8% |                                   102 |                                    140 |
|                                 [Cuba](/cuba) |               85 |                       101 |                       9 |                         16 |                                       19% |                                    90 |                                    127 |
