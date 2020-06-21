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
### Updated Daily - Last Updated: June 21 (4am ET):
<p align="center">
  Current Total: <b>119,716</b> deaths | Projected Total: <b>183,005 deaths by Oct 1, 2020</b> (Range: 153-219k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.8%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.

*June 18 note:* We moved the R_t Dashboard map to the [Maps](/maps) page and replaced it with our C19Pro Score for deaths.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 88% chance that the US surpasses 125,000 deaths by July 1, with June 29 being the most likely date.

Last updated: Jun 21, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 21, 2020 |
|              125,000 |        Jun 29, 2020 |
|              130,000 |         Jul 8, 2020 |
|              140,000 |        Jul 25, 2020 |
|              150,000 |         Aug 9, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        88% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        17% |         66% |        89% |         97% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        20% |         47% |        61% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          4% |        17% |
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
|                          *Europe* |          178,830 |                   199,634 |                     337 |                     20,804 |                                       12% |                               184,030 |                                226,495 |
| [United Kingdom](/united-kingdom) |           42,674 |                    47,496 |                     703 |                      4,822 |                                       11% |                                44,359 |                                 50,581 |
|                   [Italy](/italy) |           34,610 |                    36,973 |                     613 |                      2,363 |                                        7% |                                34,978 |                                 39,018 |
|                 [France](/france) |           29,636 |                    30,667 |                     458 |                      1,031 |                                        3% |                                29,682 |                                 34,568 |
|                   [Spain](/spain) |           28,322 |                    29,434 |                     627 |                      1,112 |                                        4% |                                28,386 |                                 31,957 |
|               [Germany](/germany) |            8,895 |                    10,299 |                     124 |                      1,404 |                                       16% |                                 9,046 |                                 13,606 |
|               [Belgium](/belgium) |            9,696 |                     9,952 |                     869 |                        256 |                                        3% |                                 9,723 |                                 10,528 |
|       [Netherlands](/netherlands) |            6,108 |                     6,471 |                     374 |                        363 |                                        6% |                                 6,149 |                                  6,982 |
|                 [Sweden](/sweden) |            5,053 |                     6,332 |                     619 |                      1,279 |                                       25% |                                 5,393 |                                  8,136 |
|               [Ukraine](/ukraine) |            1,004 |                     3,236 |                      74 |                      2,232 |                                      222% |                                 1,684 |                                  5,218 |
|                 [Poland](/poland) |            1,346 |                     3,030 |                      80 |                      1,684 |                                      125% |                                 1,814 |                                  4,504 |
|               [Romania](/romania) |            1,500 |                     2,499 |                     129 |                        999 |                                       67% |                                 1,760 |                                  3,746 |
|       [Switzerland](/switzerland) |            1,956 |                     2,055 |                     239 |                         99 |                                        5% |                                 1,970 |                                  2,332 |
|             [Portugal](/portugal) |            1,528 |                     1,869 |                     182 |                        341 |                                       22% |                                 1,614 |                                  2,418 |
|               [Ireland](/ireland) |            1,715 |                     1,812 |                     369 |                         97 |                                        6% |                                 1,727 |                                  2,177 |
|               [Moldova](/moldova) |              464 |                     1,589 |                     393 |                      1,125 |                                      242% |                                   992 |                                  2,242 |
|               [Belarus](/belarus) |              343 |                       827 |                      87 |                        484 |                                      141% |                                   469 |                                  1,824 |
|               [Hungary](/hungary) |              570 |                       778 |                      80 |                        208 |                                       36% |                                   599 |                                  1,134 |
|               [Austria](/austria) |              688 |                       742 |                      84 |                         54 |                                        8% |                                   703 |                                    876 |
|               [Denmark](/denmark) |              600 |                       676 |                     116 |                         76 |                                       13% |                                   621 |                                    843 |
|             [Bulgaria](/bulgaria) |              199 |                       673 |                      96 |                        474 |                                      238% |                                   348 |                                  1,051 |
|               [Finland](/finland) |              326 |                       368 |                      67 |                         42 |                                       13% |                                   332 |                                    472 |
|               [Czechia](/czechia) |              336 |                       361 |                      34 |                         25 |                                        7% |                                   347 |                                    395 |
|                 [Serbia](/serbia) |              260 |                       330 |                      47 |                         70 |                                       27% |                                   279 |                                    461 |
|                 [Norway](/norway) |              244 |                       267 |                      50 |                         23 |                                        9% |                                   251 |                                    308 |
|                 [Greece](/greece) |              190 |                       229 |                      21 |                         39 |                                       21% |                                   204 |                                    296 |
|               [Croatia](/croatia) |              107 |                       131 |                      32 |                         24 |                                       22% |                                   114 |                                    168 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    142 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   111 |                                    144 |
|           [Lithuania](/lithuania) |               76 |                       113 |                      40 |                         37 |                                       49% |                                    86 |                                    166 |
|               [Estonia](/estonia) |               69 |                        77 |                      58 |                          8 |                                       12% |                                    75 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        36 |                      19 |                          6 |                                       20% |                                    33 |                                     42 |
|             [Slovakia](/slovakia) |               28 |                        29 |                       5 |                          1 |                                        4% |                                    28 |                                     32 |
|                 [Cyprus](/cyprus) |               19 |                        22 |                      25 |                          3 |                                       16% |                                    21 |                                     23 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          158,982 |                   587,944 |                     113 |                    428,962 |                                      270% |                               319,863 |                                945,557 |
|                             [Brazil](/brazil) |           49,976 |                   128,232 |                     608 |                     78,256 |                                      157% |                                77,394 |                                197,766 |
|                               [India](/india) |           13,254 |                   125,902 |                      92 |                    112,648 |                                      850% |                                44,933 |                                235,537 |
|                             [Mexico](/mexico) |           20,781 |                    82,840 |                     649 |                     62,059 |                                      299% |                                50,690 |                                106,985 |
|                         [Pakistan](/pakistan) |            3,501 |                    32,602 |                     151 |                     29,101 |                                      831% |                                13,582 |                                 69,156 |
|                                 [Peru](/peru) |            7,861 |                    25,052 |                     771 |                     17,191 |                                      219% |                                14,888 |                                 36,022 |
|                               [Chile](/chile) |            4,295 |                    22,595 |                   1,192 |                     18,300 |                                      426% |                                15,489 |                                 34,533 |
|                             [Russia](/russia) |            7,992 |                    22,354 |                     153 |                     14,362 |                                      180% |                                12,351 |                                 38,344 |
|                         [Colombia](/colombia) |            2,148 |                    20,024 |                     398 |                     17,876 |                                      832% |                                11,468 |                                 26,295 |
|                 [South Africa](/south-africa) |            1,877 |                    18,187 |                     311 |                     16,310 |                                      869% |                                10,064 |                                 25,818 |
|                                 [Iran](/iran) |            9,507 |                    17,875 |                     216 |                      8,368 |                                       88% |                                11,261 |                                 25,521 |
|                             [Canada](/canada) |            8,466 |                    11,667 |                     312 |                      3,201 |                                       38% |                                 9,092 |                                 17,746 |
|                               [Egypt](/egypt) |            2,106 |                    11,079 |                     110 |                      8,973 |                                      426% |                                 5,904 |                                 18,512 |
|                     [Bangladesh](/bangladesh) |            1,425 |                     9,588 |                      59 |                      8,163 |                                      573% |                                 5,190 |                                 15,980 |
|                       [Indonesia](/indonesia) |            2,429 |                     9,040 |                      33 |                      6,611 |                                      272% |                                 4,591 |                                 16,387 |
|                 [Saudi Arabia](/saudi-arabia) |            1,230 |                     7,175 |                     209 |                      5,945 |                                      483% |                                 4,123 |                                 10,734 |
|                       [Argentina](/argentina) |              992 |                     7,145 |                     160 |                      6,153 |                                      620% |                                 3,074 |                                 12,520 |
|                           [Ecuador](/ecuador) |            4,156 |                     6,100 |                     351 |                      1,944 |                                       47% |                                 4,541 |                                 10,646 |
|                             [Turkey](/turkey) |            4,927 |                     5,713 |                      68 |                        786 |                                       16% |                                 4,990 |                                  8,339 |
|                           [Bolivia](/bolivia) |              740 |                     5,510 |                     479 |                      4,770 |                                      645% |                                 3,074 |                                  8,385 |
|                               [China](/china) |            4,639 |                     4,649 |                       3 |                         10 |                                        0% |                                 4,639 |                                  4,704 |
|                           [Nigeria](/nigeria) |              506 |                     2,504 |                      12 |                      1,998 |                                      395% |                                   993 |                                  4,279 |
|                   [Philippines](/philippines) |            1,150 |                     2,311 |                      21 |                      1,161 |                                      101% |                                 1,280 |                                  4,051 |
|                           [Algeria](/algeria) |              837 |                     2,046 |                      48 |                      1,209 |                                      144% |                                 1,192 |                                  4,019 |
|                         [Honduras](/honduras) |              358 |                     1,471 |                     151 |                      1,113 |                                      311% |                                   712 |                                  2,562 |
|     [Dominican Republic](/dominican-republic) |              655 |                     1,366 |                     127 |                        711 |                                      109% |                                   800 |                                  3,055 |
|                             [Panama](/panama) |              493 |                     1,303 |                     307 |                        810 |                                      164% |                                   713 |                                  2,340 |
|                               [Japan](/japan) |              955 |                     1,275 |                      10 |                        320 |                                       34% |                                   961 |                                  1,806 |
|                             [Kuwait](/kuwait) |              319 |                       595 |                     141 |                        276 |                                       87% |                                   394 |                                    930 |
| [United Arab Emirates](/united-arab-emirates) |              301 |                       424 |                      43 |                        123 |                                       41% |                                   327 |                                    717 |
|                             [Israel](/israel) |              305 |                       385 |                      45 |                         80 |                                       26% |                                   320 |                                    612 |
|                   [South Korea](/south-korea) |              280 |                       339 |                       7 |                         59 |                                       21% |                                   283 |                                    538 |
|                           [Morocco](/morocco) |              213 |                       238 |                       7 |                         25 |                                       12% |                                   222 |                                    286 |
|                         [Malaysia](/malaysia) |              121 |                       146 |                       5 |                         25 |                                       21% |                                   136 |                                    165 |
|                       [Australia](/australia) |              102 |                       110 |                       4 |                          8 |                                        8% |                                   102 |                                    140 |
|                                 [Cuba](/cuba) |               85 |                       102 |                       9 |                         17 |                                       20% |                                    90 |                                    127 |
