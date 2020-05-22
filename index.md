We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 60 countries.

Note that our infections estimate includes all infected individuals, not just those that took a COVID-19 test kit and tested positive. The vast majority of infected individuals do not get tested, and thus do not get reported as a positive case. As of mid-May, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 20:** We added county-level projections for 14 US counties heavily impacted by COVID-19. This includes cities such as [New York City](/us-ny-new-york-city) (5 boroughs), [Los Angeles](/us-ca-los-angeles), and [Chicago](/us-il-cook). See all 14 counties [here](#us-counties). We also added the 2 Canadian provinces accounting for ~85% of cases in Canada: [Ontario](/canada-ontario) and [Quebec](/canada-quebec).

* **May 18:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

* **May 13:** If you add `-noreopen` to the end of any projections page URL, you can see our projections with the assumption that there are no reopenings. E.g. [covid19-projections.com/us](/us) --> [covid19-projections.com/us-noreopen](/us-noreopen). Some caveats [here](https://twitter.com/youyanggu/status/1260678502107344896).

* **May 12:** We added 23 additional countries. The countries our projections cover encompass 6.3 billion people and account for over 99% of all global COVID-19 deaths. View our global projections [here](#global-projections).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 22 (3am ET):
<p align="center">
  Current Total: <b>94,699</b> deaths | Projected Total: <b>190,912</b> deaths by Aug 4, 2020 (Range: 123-321k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>3.6%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 43% chance that the US surpasses 125,000 deaths by June 15, with June 16 being the most likely date.

Last updated: May 22, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 27, 2020 |
|              125,000 |        Jun 16, 2020 |
|              150,000 |         Jul 6, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |        99% |        >99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         43% |        85% |         94% |        97% |
|              150,000 |        <1% |         <1% |        33% |         61% |        76% |
|              175,000 |        <1% |         <1% |         8% |         30% |        52% |
|              200,000 |        <1% |         <1% |        <1% |         13% |        33% |
|              250,000 |        <1% |         <1% |        <1% |          1% |        11% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |         4% |
|              350,000 |        <1% |         <1% |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 63 countries (including all 27 European Union countries).

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

### US Counties

| US Counties |  |  |
| --- | --- | --- |
| [CA - Los Angeles](/us-ca-los-angeles) | [MI - Wayne](/us-mi-wayne) | [NY - New York City](/us-ny-new-york-city) |
| [CA - Santa Clara](/us-ca-santa-clara) | [NJ - Bergen](/us-nj-bergen) | [NY - Suffolk](/us-ny-suffolk) |
| [FL - Miami-Dade](/us-fl-miami-dade) | [NJ - Essex](/us-nj-essex) | [NY - Westchester](/us-ny-westchester) |
| [IL - Cook](/us-il-cook) | [NV - Washoe](/us-nv-washoe) | [PA - Philadelphia](/us-pa-philadelphia) |
| [MA - Middlesex](/us-ma-middlesex) | [NY - Nassau](/us-ny-nassau) |

[Back to Top](#top)

### Global Projections

| [Canada](/canada) |  |  |
| --- | --- | --- |
| [Ontario](/canada-ontario) | [Quebec](/canada-quebec) |

<br />

| Europe |  |  |
| --- | --- | --- |
| [Austria](/austria) | [Hungary](/hungary) | [Portugal](/portugal) |
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
| [Greece](/greece) | [Poland](/poland) |

<br />

| Rest of World |  |  |
| --- | --- | --- |
| [Algeria](/algeria) | [Egypt](/egypt) | [Pakistan](/pakistan) |
| [Argentina](/argentina) | [India](/india) | [Panama](/panama) |
| [Bangladesh](/bangladesh) | [Indonesia](/indonesia) | [Peru](/peru) |
| [Brazil](/brazil) | [Iran](/iran) | [Philippines](/philippines) |
| [Canada](/canada) | [Israel](/israel) | [Russia](/russia) |
| [Chile](/chile) | [Japan](/japan) | [Saudi Arabia](/saudi-arabia) |
| [China](/china) | [Malaysia](/malaysia) | [South Africa](/south-africa) |
| [Colombia](/colombia) | [Mexico](/mexico) | [South Korea](/south-korea) |
| [Dominican Republic](/dominican-republic) | [Morocco](/morocco) | [Turkey](/turkey) |
| [Ecuador](/ecuador) | [Nigeria](/nigeria) |

[Back to Top](#top)

### US Summary

States are ordered by descending projected deaths (by August 4).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|         *[United States](/us)* |           94,699 |                   190,912 |                     575 |                     96,213 |                                      102% |                               123,743 |                                320,259 |
|             [New York](/us-ny) |           28,743 |                    33,289 |                   1,711 |                      4,546 |                                       16% |                                30,267 |                                 40,750 |
|             [Illinois](/us-il) |            4,607 |                    16,373 |                   1,292 |                     11,766 |                                      255% |                                 9,203 |                                 27,932 |
|           [New Jersey](/us-nj) |           10,846 |                    15,932 |                   1,794 |                      5,086 |                                       47% |                                12,360 |                                 22,760 |
|         [Pennsylvania](/us-pa) |            4,869 |                    11,705 |                     914 |                      6,836 |                                      140% |                                 6,842 |                                 19,784 |
|           [California](/us-ca) |            3,583 |                    10,902 |                     276 |                      7,319 |                                      204% |                                 4,964 |                                 24,287 |
|        [Massachusetts](/us-ma) |            6,148 |                     9,948 |                   1,431 |                      3,800 |                                       62% |                                 7,321 |                                 15,837 |
|                 [Ohio](/us-oh) |            1,837 |                     7,471 |                     639 |                      5,634 |                                      307% |                                 3,414 |                                 15,781 |
|             [Michigan](/us-mi) |            5,129 |                     6,875 |                     688 |                      1,746 |                                       34% |                                 5,795 |                                  9,260 |
|              [Indiana](/us-in) |            1,913 |                     6,337 |                     941 |                      4,424 |                                      231% |                                 3,039 |                                 12,057 |
|                [Texas](/us-tx) |            1,460 |                     5,945 |                     205 |                      4,485 |                                      307% |                                 2,836 |                                 11,350 |
|              [Florida](/us-fl) |            2,144 |                     5,617 |                     262 |                      3,473 |                                      162% |                                 2,896 |                                 11,331 |
|             [Maryland](/us-md) |            2,159 |                     5,347 |                     884 |                      3,188 |                                      148% |                                 2,878 |                                 10,406 |
|          [Connecticut](/us-ct) |            3,583 |                     5,278 |                   1,480 |                      1,695 |                                       47% |                                 4,136 |                                  7,590 |
|              [Georgia](/us-ga) |            1,775 |                     4,756 |                     448 |                      2,981 |                                      168% |                                 2,458 |                                  8,901 |
|              [Arizona](/us-az) |              764 |                     4,355 |                     598 |                      3,591 |                                      470% |                                 2,084 |                                  8,156 |
|             [Colorado](/us-co) |            1,310 |                     3,933 |                     683 |                      2,623 |                                      200% |                                 2,098 |                                  7,373 |
|            [Louisiana](/us-la) |            2,629 |                     3,911 |                     841 |                      1,282 |                                       49% |                                 3,104 |                                  5,581 |
|            [Minnesota](/us-mn) |              818 |                     3,460 |                     614 |                      2,642 |                                      323% |                                 1,417 |                                  7,429 |
|             [Virginia](/us-va) |            1,100 |                     2,996 |                     351 |                      1,896 |                                      172% |                                 1,492 |                                  6,979 |
|          [Mississippi](/us-ms) |              580 |                     2,758 |                     927 |                      2,178 |                                      376% |                                 1,264 |                                  5,180 |
|             [Missouri](/us-mo) |              668 |                     2,551 |                     416 |                      1,883 |                                      282% |                                 1,238 |                                  4,805 |
|                 [Iowa](/us-ia) |              410 |                     2,286 |                     725 |                      1,876 |                                      458% |                                 1,161 |                                  3,661 |
|              [Alabama](/us-al) |              529 |                     1,890 |                     385 |                      1,361 |                                      257% |                                 1,005 |                                  3,376 |
|       [North Carolina](/us-nc) |              728 |                     1,650 |                     157 |                        922 |                                      127% |                                 1,011 |                                  3,078 |
|       [South Carolina](/us-sc) |              416 |                     1,441 |                     280 |                      1,025 |                                      246% |                                   669 |                                  2,878 |
|           [Washington](/us-wa) |            1,044 |                     1,440 |                     189 |                        396 |                                       38% |                                 1,166 |                                  2,090 |
|         [Rhode Island](/us-ri) |              556 |                     1,406 |                   1,327 |                        850 |                                      153% |                                   870 |                                  2,373 |
|           [New Mexico](/us-nm) |              294 |                     1,361 |                     649 |                      1,067 |                                      363% |                                   629 |                                  2,664 |
|             [Delaware](/us-de) |              317 |                     1,162 |                   1,193 |                        845 |                                      267% |                                   632 |                                  2,145 |
|             [Kentucky](/us-ky) |              386 |                       916 |                     205 |                        530 |                                      137% |                                   558 |                                  1,670 |
|            [Wisconsin](/us-wi) |              487 |                       907 |                     156 |                        420 |                                       86% |                                   655 |                                  1,472 |
|               [Nevada](/us-nv) |              383 |                       897 |                     291 |                        514 |                                      134% |                                   572 |                                  1,585 |
| [District of Columbia](/us-dc) |              412 |                       891 |                   1,262 |                        479 |                                      116% |                                   563 |                                  1,508 |
|        [New Hampshire](/us-nh) |              199 |                       833 |                     613 |                        634 |                                      319% |                                   455 |                                  1,383 |
|             [Nebraska](/us-ne) |              138 |                       661 |                     342 |                        523 |                                      379% |                                   333 |                                  1,274 |
|            [Tennessee](/us-tn) |              313 |                       629 |                      92 |                        316 |                                      101% |                                   442 |                                    994 |
|             [Oklahoma](/us-ok) |              304 |                       481 |                     122 |                        177 |                                       58% |                                   376 |                                    677 |
|                 [Utah](/us-ut) |               92 |                       380 |                     119 |                        288 |                                      313% |                                   177 |                                    755 |
|               [Kansas](/us-ks) |              204 |                       338 |                     116 |                        134 |                                       66% |                                   234 |                                    617 |
|         [North Dakota](/us-nd) |               51 |                       245 |                     321 |                        194 |                                      380% |                                   116 |                                    491 |
|             [Arkansas](/us-ar) |              110 |                       232 |                      77 |                        122 |                                      111% |                                   168 |                                    363 |
|               [Oregon](/us-or) |              145 |                       217 |                      51 |                         72 |                                       50% |                                   170 |                                    311 |
|         [South Dakota](/us-sd) |               48 |                       202 |                     228 |                        154 |                                      321% |                                    92 |                                    433 |
|          [Puerto Rico](/us-pr) |              126 |                       179 |                      56 |                         53 |                                       42% |                                   150 |                                    237 |
|        [West Virginia](/us-wv) |               70 |                       128 |                      71 |                         58 |                                       83% |                                    93 |                                    210 |
|                [Maine](/us-me) |               73 |                       111 |                      83 |                         38 |                                       52% |                                    92 |                                    140 |
|                [Idaho](/us-id) |               77 |                       103 |                      58 |                         26 |                                       34% |                                    89 |                                    117 |
|              [Vermont](/us-vt) |               54 |                        69 |                     111 |                         15 |                                       28% |                                    62 |                                     75 |
|              [Wyoming](/us-wy) |               12 |                        35 |                      60 |                         23 |                                      192% |                                    23 |                                     51 |
|               [Hawaii](/us-hi) |               17 |                        25 |                      18 |                          8 |                                       47% |                                    21 |                                     30 |
|              [Montana](/us-mt) |               16 |                        21 |                      20 |                          5 |                                       31% |                                    19 |                                     26 |
|               [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    12 |                                     15 |
|       [Virgin Islands](/us-vi) |                6 |                        10 |                      95 |                          4 |                                       67% |                                     9 |                                     11 |
|                 [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     8 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          163,079 |                   209,264 |                     357 |                     46,185 |                                       28% |                               177,350 |                                280,414 |
| [United Kingdom](/united-kingdom) |           36,124 |                    50,432 |                     747 |                     14,308 |                                       40% |                                40,735 |                                 69,642 |
|                   [Italy](/italy) |           32,486 |                    38,755 |                     642 |                      6,269 |                                       19% |                                34,762 |                                 47,155 |
|                 [France](/france) |           28,218 |                    31,812 |                     475 |                      3,594 |                                       13% |                                28,633 |                                 42,990 |
|                   [Spain](/spain) |           27,940 |                    31,570 |                     673 |                      3,630 |                                       13% |                                29,099 |                                 37,566 |
|               [Germany](/germany) |            8,203 |                    10,651 |                     128 |                      2,448 |                                       30% |                                 8,857 |                                 15,697 |
|               [Belgium](/belgium) |            9,186 |                    10,370 |                     905 |                      1,184 |                                       13% |                                 9,473 |                                 12,558 |
|       [Netherlands](/netherlands) |            5,794 |                     7,367 |                     426 |                      1,573 |                                       27% |                                 6,219 |                                  9,742 |
|                 [Sweden](/sweden) |            3,871 |                     6,403 |                     626 |                      2,532 |                                       65% |                                 5,025 |                                  9,849 |
|               [Ukraine](/ukraine) |              579 |                     5,032 |                     114 |                      4,453 |                                      769% |                                 1,796 |                                  9,562 |
|               [Romania](/romania) |            1,156 |                     2,527 |                     130 |                      1,371 |                                      119% |                                 1,669 |                                  4,128 |
|       [Switzerland](/switzerland) |            1,898 |                     2,181 |                     254 |                        283 |                                       15% |                                 1,979 |                                  2,691 |
|                 [Poland](/poland) |              972 |                     2,166 |                      57 |                      1,194 |                                      123% |                                 1,249 |                                  4,177 |
|               [Ireland](/ireland) |            1,583 |                     1,939 |                     395 |                        356 |                                       22% |                                 1,677 |                                  2,738 |
|             [Portugal](/portugal) |            1,277 |                     1,854 |                     180 |                        577 |                                       45% |                                 1,519 |                                  2,591 |
|               [Moldova](/moldova) |              233 |                     1,089 |                     269 |                        856 |                                      367% |                                   496 |                                  2,174 |
|               [Austria](/austria) |              633 |                       757 |                      85 |                        124 |                                       20% |                                   682 |                                    899 |
|               [Hungary](/hungary) |              473 |                       737 |                      75 |                        264 |                                       56% |                                   538 |                                  1,207 |
|               [Denmark](/denmark) |              561 |                       733 |                     126 |                        172 |                                       31% |                                   639 |                                    950 |
|               [Finland](/finland) |              306 |                       494 |                      90 |                        188 |                                       61% |                                   360 |                                    811 |
|             [Bulgaria](/bulgaria) |              120 |                       413 |                      59 |                        293 |                                      244% |                                   231 |                                    764 |
|               [Czechia](/czechia) |              306 |                       396 |                      37 |                         90 |                                       29% |                                   359 |                                    444 |
|                 [Serbia](/serbia) |              237 |                       373 |                      43 |                        136 |                                       57% |                                   296 |                                    609 |
|                 [Norway](/norway) |              235 |                       279 |                      52 |                         44 |                                       19% |                                   251 |                                    319 |
|                 [Greece](/greece) |              168 |                       215 |                      20 |                         47 |                                       28% |                                   191 |                                    252 |
|               [Croatia](/croatia) |               97 |                       162 |                      40 |                         65 |                                       67% |                                   117 |                                    256 |
|         [Luxembourg](/luxembourg) |              109 |                       133 |                     217 |                         24 |                                       22% |                                   121 |                                    149 |
|             [Slovenia](/slovenia) |              106 |                       130 |                      62 |                         24 |                                       23% |                                   114 |                                    156 |
|               [Estonia](/estonia) |               64 |                        89 |                      67 |                         25 |                                       39% |                                    80 |                                    100 |
|           [Lithuania](/lithuania) |               61 |                        87 |                      31 |                         26 |                                       43% |                                    76 |                                    101 |
|                 [Latvia](/latvia) |               22 |                        38 |                      20 |                         16 |                                       73% |                                    34 |                                     46 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    31 |                                     43 |
|                 [Cyprus](/cyprus) |               17 |                        23 |                      26 |                          6 |                                       35% |                                    22 |                                     25 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    12 |                                     13 |
|                   [Malta](/malta) |                6 |                         9 |                      18 |                          3 |                                       50% |                                     8 |                                     10 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           71,507 |                   393,795 |                      77 |                    322,288 |                                      451% |                               140,975 |                                781,681 |
|                         [Brazil](/brazil) |           20,047 |                   147,368 |                     698 |                    127,321 |                                      635% |                                48,334 |                                253,325 |
|                         [Mexico](/mexico) |            6,510 |                    88,206 |                     691 |                     81,696 |                                     1255% |                                24,769 |                                173,687 |
|                           [India](/india) |            3,584 |                    35,341 |                      26 |                     31,757 |                                      886% |                                 8,195 |                                 97,806 |
|                         [Russia](/russia) |            3,099 |                    17,575 |                     120 |                     14,476 |                                      467% |                                 5,060 |                                 53,951 |
|                             [Peru](/peru) |            3,148 |                    16,268 |                     500 |                     13,120 |                                      417% |                                 5,214 |                                 25,647 |
|                         [Canada](/canada) |            6,267 |                    13,484 |                     360 |                      7,217 |                                      115% |                                 8,578 |                                 25,613 |
|                             [Iran](/iran) |            7,249 |                    12,321 |                     149 |                      5,072 |                                       70% |                                 8,256 |                                 22,287 |
|                     [Pakistan](/pakistan) |            1,017 |                     6,844 |                      32 |                      5,827 |                                      573% |                                 1,721 |                                 18,182 |
|             [South Africa](/south-africa) |              369 |                     6,468 |                     110 |                      6,099 |                                     1653% |                                 2,377 |                                 13,146 |
|                       [Ecuador](/ecuador) |            2,939 |                     6,433 |                     370 |                      3,494 |                                      119% |                                 3,730 |                                 14,067 |
|                           [Chile](/chile) |              589 |                     5,814 |                     307 |                      5,225 |                                      887% |                                 2,681 |                                 10,868 |
|                         [Turkey](/turkey) |            4,249 |                     5,446 |                      65 |                      1,197 |                                       28% |                                 4,688 |                                  7,598 |
|                     [Colombia](/colombia) |              652 |                     4,981 |                      99 |                      4,329 |                                      664% |                                 1,968 |                                 10,909 |
|                           [China](/china) |            4,638 |                     4,648 |                       3 |                         10 |                                        0% |                                 4,638 |                                  4,677 |
|                 [Bangladesh](/bangladesh) |              408 |                     3,803 |                      23 |                      3,395 |                                      832% |                                 1,263 |                                  8,124 |
|                           [Egypt](/egypt) |              696 |                     3,322 |                      33 |                      2,626 |                                      377% |                                 1,177 |                                  9,909 |
|                   [Indonesia](/indonesia) |            1,278 |                     3,200 |                      12 |                      1,922 |                                      150% |                                 1,814 |                                  5,743 |
|             [Saudi Arabia](/saudi-arabia) |              351 |                     2,461 |                      72 |                      2,110 |                                      601% |                                   946 |                                  5,805 |
|                   [Argentina](/argentina) |              416 |                     2,378 |                      53 |                      1,962 |                                      472% |                                   854 |                                  6,459 |
|                           [Japan](/japan) |              777 |                     1,742 |                      14 |                        965 |                                      124% |                                   902 |                                  3,163 |
|               [Philippines](/philippines) |              846 |                     1,565 |                      14 |                        719 |                                       85% |                                 1,023 |                                  2,711 |
|                       [Nigeria](/nigeria) |              211 |                       962 |                       5 |                        751 |                                      356% |                                   338 |                                  3,229 |
| [Dominican Republic](/dominican-republic) |              448 |                       731 |                      68 |                        283 |                                       63% |                                   532 |                                  1,262 |
|                         [Panama](/panama) |              291 |                       704 |                     166 |                        413 |                                      142% |                                   382 |                                  1,373 |
|                       [Algeria](/algeria) |              575 |                       689 |                      16 |                        114 |                                       20% |                                   604 |                                    909 |
|                         [Israel](/israel) |              279 |                       353 |                      41 |                         74 |                                       27% |                                   310 |                                    429 |
|               [South Korea](/south-korea) |              264 |                       318 |                       6 |                         54 |                                       20% |                                   282 |                                    388 |
|                       [Morocco](/morocco) |              196 |                       226 |                       6 |                         30 |                                       15% |                                   210 |                                    253 |
|                     [Malaysia](/malaysia) |              114 |                       144 |                       5 |                         30 |                                       26% |                                   129 |                                    161 |
