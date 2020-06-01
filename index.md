We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for over 99% of all global COVID-19 deaths.

Note that our infections estimate includes all infected individuals, not just those that took a COVID-19 test kit and tested positive. The vast majority of infected individuals do not get tested, and thus do not get reported as a positive case. As of mid-May, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 31:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), and [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729).

* **May 29:** We ran a simulation on what would happen if just 20% of infected individuals reduced their own transmission by 25% (such as by self-quarantining immediately after showing symptoms). US deaths would be 30% lower by May 29, and up to 50% lower by September. See the results [here](/us-self-quarantine).

* **May 27:** We added [7 new countries](/#global-projections) (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), [2 Canadian provinces](/#global-projections) (Alberta and British Columbia), and [20 US counties](/#us-counties). We now have projections for 71 countries (>99% of all global COVID-19 deaths), 4 Canadian provinces (99% of Canadian COVID-19 deaths), 56 US states and territories, and 34 US counties (including the top 30 most populous counties).

* **May 26:** We have extended our projections to September 1, 2020.

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: Jun 1 (3am ET):
<p align="center">
  Current Total: <b>104,378</b> deaths | Projected Total: <b>192,098 deaths by Sep 1, 2020</b> (Range: 127-287k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.1%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 25 being the most likely date.

Last updated: Jun 1, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              110,000 |         Jun 7, 2020 |
|              120,000 |        Jun 19, 2020 |
|              125,000 |        Jun 25, 2020 |
|              130,000 |         Jul 1, 2020 |
|              140,000 |        Jul 12, 2020 |
|              150,000 |        Jul 22, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        73% |         91% |        97% |         98% |        99% |
|              150,000 |         <1% |        <1% |         32% |        61% |         71% |        78% |
|              175,000 |         <1% |        <1% |          1% |        29% |         46% |        56% |
|              200,000 |         <1% |        <1% |         <1% |         8% |         26% |        40% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          1% |        14% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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

<br />

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

<br />

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

States are ordered by descending projected deaths (by September 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          104,378 |                   192,098 |                     579 |                     87,720 |                                       84% |                               127,777 |                                286,688 |
|                 [New York](/us-ny) |           29,784 |                    33,017 |                   1,697 |                      3,233 |                                       11% |                                30,520 |                                 38,283 |
|               [New Jersey](/us-nj) |           11,698 |                    14,866 |                   1,674 |                      3,168 |                                       27% |                                12,752 |                                 17,759 |
|               [California](/us-ca) |            4,172 |                    12,938 |                     327 |                      8,766 |                                      210% |                                 5,777 |                                 24,341 |
|                 [Illinois](/us-il) |            5,390 |                    10,499 |                     829 |                      5,109 |                                       95% |                                 7,271 |                                 14,262 |
|             [Pennsylvania](/us-pa) |            5,555 |                     9,492 |                     741 |                      3,937 |                                       71% |                                 6,632 |                                 14,027 |
|            [Massachusetts](/us-ma) |            6,846 |                     9,457 |                   1,361 |                      2,611 |                                       38% |                                 7,769 |                                 12,502 |
|                  [Florida](/us-fl) |            2,451 |                     7,059 |                     329 |                      4,608 |                                      188% |                                 3,379 |                                 12,247 |
|                 [Michigan](/us-mi) |            5,491 |                     6,968 |                     698 |                      1,477 |                                       27% |                                 5,968 |                                  9,511 |
|                     [Ohio](/us-oh) |            2,155 |                     6,560 |                     561 |                      4,405 |                                      204% |                                 3,238 |                                 10,605 |
|                 [Maryland](/us-md) |            2,532 |                     6,164 |                   1,020 |                      3,632 |                                      143% |                                 3,423 |                                  9,873 |
|                  [Georgia](/us-ga) |            2,053 |                     6,080 |                     573 |                      4,027 |                                      196% |                                 3,074 |                                  9,943 |
|                    [Texas](/us-tx) |            1,675 |                     5,563 |                     192 |                      3,888 |                                      232% |                                 2,693 |                                 10,527 |
|              [Connecticut](/us-ct) |            3,944 |                     5,377 |                   1,508 |                      1,433 |                                       36% |                                 4,364 |                                  6,958 |
|                  [Indiana](/us-in) |            2,134 |                     4,809 |                     714 |                      2,675 |                                      125% |                                 2,740 |                                  8,063 |
|                 [Virginia](/us-va) |            1,375 |                     4,648 |                     545 |                      3,273 |                                      238% |                                 2,029 |                                  8,072 |
|                [Minnesota](/us-mn) |            1,050 |                     4,278 |                     759 |                      3,228 |                                      307% |                                 1,887 |                                  6,626 |
|                [Louisiana](/us-la) |            2,791 |                     4,188 |                     901 |                      1,397 |                                       50% |                                 3,167 |                                  6,865 |
|                  [Arizona](/us-az) |              907 |                     4,093 |                     562 |                      3,186 |                                      351% |                                 1,941 |                                  6,244 |
|                 [Colorado](/us-co) |            1,445 |                     3,936 |                     683 |                      2,491 |                                      172% |                                 2,023 |                                  6,639 |
|           [North Carolina](/us-nc) |              937 |                     3,643 |                     347 |                      2,706 |                                      289% |                                 1,726 |                                  6,355 |
|              [Mississippi](/us-ms) |              734 |                     2,858 |                     960 |                      2,124 |                                      289% |                                 1,421 |                                  4,133 |
|                 [Missouri](/us-mo) |              776 |                     2,743 |                     447 |                      1,967 |                                      253% |                                 1,331 |                                  4,665 |
|                  [Alabama](/us-al) |              630 |                     2,330 |                     475 |                      1,700 |                                      270% |                                 1,169 |                                  3,891 |
|                     [Iowa](/us-ia) |              535 |                     2,210 |                     700 |                      1,675 |                                      313% |                                 1,074 |                                  3,382 |
|           [South Carolina](/us-sc) |              494 |                     1,943 |                     377 |                      1,449 |                                      293% |                                   848 |                                  3,287 |
|             [Rhode Island](/us-ri) |              718 |                     1,756 |                   1,658 |                      1,038 |                                      145% |                                 1,171 |                                  2,359 |
|               [Washington](/us-wa) |            1,118 |                     1,732 |                     227 |                        614 |                                       55% |                                 1,227 |                                  3,019 |
|                [Wisconsin](/us-wi) |              592 |                     1,697 |                     291 |                      1,105 |                                      187% |                                   890 |                                  3,118 |
|                 [Kentucky](/us-ky) |              431 |                     1,115 |                     250 |                        684 |                                      159% |                                   593 |                                  2,153 |
|               [New Mexico](/us-nm) |              356 |                     1,115 |                     532 |                        759 |                                      213% |                                   575 |                                  1,736 |
|            [New Hampshire](/us-nh) |              245 |                     1,078 |                     793 |                        833 |                                      340% |                                   540 |                                  1,596 |
|                [Tennessee](/us-tn) |              364 |                       962 |                     141 |                        598 |                                      164% |                                   519 |                                  1,887 |
|                   [Nevada](/us-nv) |              417 |                       947 |                     307 |                        530 |                                      127% |                                   540 |                                  1,671 |
|                 [Delaware](/us-de) |              366 |                       925 |                     950 |                        559 |                                      153% |                                   543 |                                  1,400 |
|     [District of Columbia](/us-dc) |              466 |                       801 |                   1,135 |                        335 |                                       72% |                                   544 |                                  1,240 |
|                 [Nebraska](/us-ne) |              170 |                       761 |                     393 |                        591 |                                      348% |                                   338 |                                  1,249 |
|                 [Oklahoma](/us-ok) |              334 |                       595 |                     150 |                        261 |                                       78% |                                   407 |                                  1,082 |
|                     [Utah](/us-ut) |              113 |                       523 |                     163 |                        410 |                                      363% |                                   208 |                                    886 |
|                 [Arkansas](/us-ar) |              133 |                       481 |                     159 |                        348 |                                      262% |                                   227 |                                    864 |
|                   [Kansas](/us-ks) |              215 |                       367 |                     126 |                        152 |                                       71% |                                   241 |                                    830 |
|             [South Dakota](/us-sd) |               62 |                       283 |                     320 |                        221 |                                      356% |                                   106 |                                    556 |
|             [North Dakota](/us-nd) |               61 |                       243 |                     319 |                        182 |                                      298% |                                   112 |                                    485 |
|                   [Oregon](/us-or) |              153 |                       237 |                      56 |                         84 |                                       55% |                                   172 |                                    409 |
|              [Puerto Rico](/us-pr) |              136 |                       197 |                      62 |                         61 |                                       45% |                                   159 |                                    287 |
|                    [Maine](/us-me) |               89 |                       138 |                     103 |                         49 |                                       55% |                                   109 |                                    199 |
|            [West Virginia](/us-wv) |               75 |                       120 |                      67 |                         45 |                                       60% |                                    89 |                                    204 |
|                    [Idaho](/us-id) |               82 |                       104 |                      58 |                         22 |                                       27% |                                    91 |                                    133 |
|                  [Vermont](/us-vt) |               55 |                        65 |                     104 |                         10 |                                       18% |                                    60 |                                     75 |
|                  [Wyoming](/us-wy) |               16 |                        64 |                     111 |                         48 |                                      300% |                                    35 |                                    107 |
|                  [Montana](/us-mt) |               17 |                        21 |                      20 |                          4 |                                       24% |                                    19 |                                     25 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     23 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     13 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          170,219 |                   201,495 |                     340 |                     31,276 |                                       18% |                               178,189 |                                248,243 |
| [United Kingdom](/united-kingdom) |           38,571 |                    47,696 |                     706 |                      9,125 |                                       24% |                                41,731 |                                 54,529 |
|                   [Italy](/italy) |           33,415 |                    38,281 |                     634 |                      4,866 |                                       15% |                                34,764 |                                 44,098 |
|                 [France](/france) |           28,805 |                    30,975 |                     462 |                      2,170 |                                        8% |                                29,049 |                                 37,974 |
|                   [Spain](/spain) |           28,752 |                    28,940 |                     617 |                        188 |                                        1% |                                27,343 |                                 35,121 |
|               [Germany](/germany) |            8,540 |                    10,399 |                     125 |                      1,859 |                                       22% |                                 8,907 |                                 15,316 |
|               [Belgium](/belgium) |            9,467 |                    10,196 |                     890 |                        729 |                                        8% |                                 9,641 |                                 11,570 |
|       [Netherlands](/netherlands) |            5,975 |                     7,038 |                     407 |                      1,063 |                                       18% |                                 6,238 |                                  8,724 |
|                 [Sweden](/sweden) |            4,395 |                     7,028 |                     687 |                      2,633 |                                       60% |                                 5,610 |                                  9,325 |
|               [Ukraine](/ukraine) |              708 |                     3,378 |                      77 |                      2,670 |                                      377% |                                 1,407 |                                  5,611 |
|                 [Poland](/poland) |            1,064 |                     2,133 |                      56 |                      1,069 |                                      100% |                                 1,313 |                                  3,888 |
|               [Romania](/romania) |            1,266 |                     2,101 |                     108 |                        835 |                                       66% |                                 1,617 |                                  3,229 |
|       [Switzerland](/switzerland) |            1,920 |                     2,067 |                     241 |                        147 |                                        8% |                                 1,949 |                                  2,336 |
|             [Portugal](/portugal) |            1,410 |                     2,047 |                     199 |                        637 |                                       45% |                                 1,637 |                                  3,018 |
|               [Ireland](/ireland) |            1,652 |                     1,820 |                     371 |                        168 |                                       10% |                                 1,680 |                                  2,403 |
|               [Moldova](/moldova) |              295 |                     1,426 |                     353 |                      1,131 |                                      383% |                                   696 |                                  2,084 |
|               [Hungary](/hungary) |              526 |                       920 |                      94 |                        394 |                                       75% |                                   616 |                                  1,680 |
|               [Belarus](/belarus) |              235 |                       793 |                      84 |                        558 |                                      237% |                                   395 |                                  1,871 |
|               [Austria](/austria) |              668 |                       746 |                      84 |                         78 |                                       12% |                                   696 |                                    870 |
|               [Denmark](/denmark) |              574 |                       678 |                     117 |                        104 |                                       18% |                                   612 |                                    815 |
|             [Bulgaria](/bulgaria) |              140 |                       536 |                      77 |                        396 |                                      283% |                                   260 |                                    915 |
|               [Finland](/finland) |              320 |                       401 |                      73 |                         81 |                                       25% |                                   340 |                                    558 |
|               [Czechia](/czechia) |              320 |                       370 |                      35 |                         50 |                                       16% |                                   349 |                                    414 |
|                 [Serbia](/serbia) |              243 |                       325 |                      47 |                         82 |                                       34% |                                   278 |                                    425 |
|                 [Norway](/norway) |              236 |                       265 |                      49 |                         29 |                                       12% |                                   246 |                                    303 |
|                 [Greece](/greece) |              175 |                       214 |                      20 |                         39 |                                       22% |                                   195 |                                    253 |
|               [Croatia](/croatia) |              103 |                       144 |                      35 |                         41 |                                       40% |                                   117 |                                    198 |
|           [Lithuania](/lithuania) |               70 |                       138 |                      49 |                         68 |                                       97% |                                    96 |                                    220 |
|         [Luxembourg](/luxembourg) |              110 |                       124 |                     202 |                         14 |                                       13% |                                   114 |                                    143 |
|             [Slovenia](/slovenia) |              108 |                       123 |                      59 |                         15 |                                       14% |                                   112 |                                    145 |
|               [Estonia](/estonia) |               68 |                        82 |                      62 |                         14 |                                       21% |                                    78 |                                     87 |
|             [Slovakia](/slovakia) |               28 |                        33 |                       6 |                          5 |                                       18% |                                    29 |                                     37 |
|                 [Latvia](/latvia) |               24 |                        32 |                      17 |                          8 |                                       33% |                                    31 |                                     34 |
|                 [Cyprus](/cyprus) |               17 |                        20 |                      23 |                          3 |                                       18% |                                    19 |                                     21 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       67% |                                    13 |                                     16 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           95,654 |                   460,435 |                      89 |                    364,781 |                                      381% |                               200,864 |                                758,750 |
|                             [Brazil](/brazil) |           29,314 |                   139,005 |                     659 |                    109,691 |                                      374% |                                63,645 |                                252,635 |
|                             [Mexico](/mexico) |            9,930 |                    97,096 |                     761 |                     87,166 |                                      878% |                                35,408 |                                154,412 |
|                               [India](/india) |            5,408 |                    55,797 |                      41 |                     50,389 |                                      932% |                                16,036 |                                 77,196 |
|                                 [Peru](/peru) |            4,506 |                    27,605 |                     849 |                     23,099 |                                      513% |                                10,200 |                                 42,420 |
|                             [Russia](/russia) |            4,693 |                    23,727 |                     163 |                     19,034 |                                      406% |                                 8,389 |                                 42,812 |
|                             [Canada](/canada) |            7,374 |                    13,227 |                     354 |                      5,853 |                                       79% |                                 8,381 |                                 22,550 |
|                                 [Iran](/iran) |            7,797 |                    11,985 |                     145 |                      4,188 |                                       54% |                                 8,661 |                                 20,466 |
|                               [Chile](/chile) |            1,054 |                    11,290 |                     596 |                     10,236 |                                      971% |                                 6,607 |                                 15,083 |
|                 [South Africa](/south-africa) |              683 |                     9,440 |                     161 |                      8,757 |                                     1282% |                                 5,364 |                                 12,620 |
|                         [Pakistan](/pakistan) |            1,483 |                     8,942 |                      41 |                      7,459 |                                      503% |                                 2,855 |                                 15,600 |
|                         [Colombia](/colombia) |              916 |                     7,650 |                     152 |                      6,734 |                                      735% |                                 3,659 |                                 12,377 |
|                           [Ecuador](/ecuador) |            3,358 |                     6,759 |                     389 |                      3,401 |                                      101% |                                 4,045 |                                 14,807 |
|                     [Bangladesh](/bangladesh) |              650 |                     6,065 |                      37 |                      5,415 |                                      833% |                                 2,449 |                                  8,580 |
|                       [Indonesia](/indonesia) |            1,613 |                     5,654 |                      21 |                      4,041 |                                      251% |                                 2,726 |                                 11,739 |
|                             [Turkey](/turkey) |            4,540 |                     5,566 |                      67 |                      1,026 |                                       23% |                                 4,741 |                                  7,820 |
|                               [Egypt](/egypt) |              959 |                     5,205 |                      52 |                      4,246 |                                      443% |                                 1,996 |                                  8,888 |
|                               [China](/china) |            4,638 |                     4,648 |                       3 |                         10 |                                        0% |                                 4,638 |                                  4,700 |
|                 [Saudi Arabia](/saudi-arabia) |              503 |                     3,701 |                     108 |                      3,198 |                                      636% |                                 1,874 |                                  5,037 |
|                           [Bolivia](/bolivia) |              313 |                     2,648 |                     230 |                      2,335 |                                      746% |                                 1,014 |                                  4,100 |
|                       [Argentina](/argentina) |              539 |                     2,477 |                      55 |                      1,938 |                                      360% |                                 1,203 |                                  4,098 |
|                   [Philippines](/philippines) |              957 |                     1,905 |                      18 |                        948 |                                       99% |                                 1,134 |                                  3,596 |
|                           [Nigeria](/nigeria) |              287 |                     1,543 |                       8 |                      1,256 |                                      438% |                                   494 |                                  3,040 |
|                               [Japan](/japan) |              898 |                     1,464 |                      12 |                        566 |                                       63% |                                   930 |                                  2,222 |
|                             [Kuwait](/kuwait) |              212 |                     1,433 |                     341 |                      1,221 |                                      576% |                                   707 |                                  2,160 |
|                           [Algeria](/algeria) |              653 |                     1,034 |                      24 |                        381 |                                       58% |                                   754 |                                  1,990 |
|                         [Honduras](/honduras) |              212 |                     1,024 |                     105 |                        812 |                                      383% |                                   461 |                                  1,877 |
|                             [Panama](/panama) |              336 |                       910 |                     214 |                        574 |                                      171% |                                   442 |                                  1,888 |
|     [Dominican Republic](/dominican-republic) |              502 |                       841 |                      78 |                        339 |                                       68% |                                   598 |                                  1,350 |
| [United Arab Emirates](/united-arab-emirates) |              264 |                       526 |                      54 |                        262 |                                       99% |                                   331 |                                  1,085 |
|                             [Israel](/israel) |              285 |                       351 |                      41 |                         66 |                                       23% |                                   307 |                                    460 |
|                   [South Korea](/south-korea) |              271 |                       328 |                       6 |                         57 |                                       21% |                                   278 |                                    441 |
|                           [Morocco](/morocco) |              205 |                       232 |                       6 |                         27 |                                       13% |                                   215 |                                    273 |
|                         [Malaysia](/malaysia) |              115 |                       144 |                       5 |                         29 |                                       25% |                                   128 |                                    171 |
|                       [Australia](/australia) |              103 |                       112 |                       4 |                          9 |                                        9% |                                   104 |                                    137 |
|                                 [Cuba](/cuba) |               83 |                       101 |                       9 |                         18 |                                       22% |                                    90 |                                    120 |
