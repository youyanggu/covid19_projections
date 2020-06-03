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

* **Jun 1:** We have lowered our US projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), and [slow reopenings](https://twitter.com/youyanggu/status/1267551592837832704).

* **May 29:** We ran a simulation on what would happen if just 20% of infected individuals reduced their own transmission by 25% (such as by self-quarantining immediately after showing symptoms). US deaths would be 30% lower by May 29, and up to 50% lower by September. See the results [here](/us-self-quarantine).

* **May 27:** We added [7 new countries](/#global-projections) (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), [2 Canadian provinces](/#global-projections) (Alberta and British Columbia), and [20 US counties](/#us-counties). We now have projections for 71 countries (>99% of all global COVID-19 deaths), 4 Canadian provinces (99% of Canadian COVID-19 deaths), 56 US states and territories, and 34 US counties (including the top 30 most populous counties).

* **May 26:** We have extended our projections to September 1, 2020.

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: Jun 3 (1am ET):
<p align="center">
  Current Total: <b>106,177</b> deaths | Projected Total: <b>187,171 deaths by Sep 1, 2020</b> (Range: 127-281k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.1%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 26 being the most likely date.

Last updated: Jun 3, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              110,000 |         Jun 7, 2020 |
|              120,000 |        Jun 19, 2020 |
|              125,000 |        Jun 26, 2020 |
|              130,000 |         Jul 2, 2020 |
|              140,000 |        Jul 14, 2020 |
|              150,000 |        Jul 24, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        70% |         91% |        96% |         98% |        98% |
|              150,000 |         <1% |        <1% |         27% |        56% |         67% |        74% |
|              175,000 |         <1% |        <1% |         <1% |        24% |         41% |        53% |
|              200,000 |         <1% |        <1% |         <1% |         5% |         22% |        35% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        12% |
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
|             *[United States](/us)* |          106,177 |                   187,171 |                     564 |                     80,994 |                                       76% |                               127,420 |                                280,129 |
|                 [New York](/us-ny) |           29,968 |                    33,033 |                   1,698 |                      3,065 |                                       10% |                                30,652 |                                 38,033 |
|               [New Jersey](/us-nj) |           11,771 |                    14,285 |                   1,608 |                      2,514 |                                       21% |                                12,605 |                                 16,558 |
|               [California](/us-ca) |            4,305 |                    13,003 |                     329 |                      8,698 |                                      202% |                                 5,979 |                                 24,074 |
|                 [Illinois](/us-il) |            5,525 |                    10,520 |                     830 |                      4,995 |                                       90% |                                 7,344 |                                 14,223 |
|            [Massachusetts](/us-ma) |            7,085 |                     9,508 |                   1,368 |                      2,423 |                                       34% |                                 7,935 |                                 12,498 |
|             [Pennsylvania](/us-pa) |            5,667 |                     9,418 |                     736 |                      3,751 |                                       66% |                                 6,686 |                                 13,902 |
|                  [Florida](/us-fl) |            2,530 |                     7,139 |                     332 |                      4,609 |                                      182% |                                 3,456 |                                 12,273 |
|                 [Michigan](/us-mi) |            5,553 |                     6,991 |                     700 |                      1,438 |                                       26% |                                 6,002 |                                  9,477 |
|                     [Ohio](/us-oh) |            2,259 |                     6,756 |                     578 |                      4,497 |                                      199% |                                 3,581 |                                 10,704 |
|                 [Maryland](/us-md) |            2,597 |                     6,117 |                   1,012 |                      3,520 |                                      136% |                                 3,457 |                                  9,798 |
|                  [Georgia](/us-ga) |            2,102 |                     5,888 |                     555 |                      3,786 |                                      180% |                                 3,078 |                                  9,889 |
|                    [Texas](/us-tx) |            1,716 |                     5,297 |                     183 |                      3,581 |                                      209% |                                 2,599 |                                 10,288 |
|              [Connecticut](/us-ct) |            3,972 |                     5,266 |                   1,477 |                      1,294 |                                       33% |                                 4,301 |                                  6,866 |
|                  [Indiana](/us-in) |            2,197 |                     4,869 |                     723 |                      2,672 |                                      122% |                                 2,852 |                                  8,088 |
|                [Louisiana](/us-la) |            2,835 |                     4,235 |                     911 |                      1,400 |                                       49% |                                 3,221 |                                  6,890 |
|                 [Virginia](/us-va) |            1,407 |                     4,158 |                     487 |                      2,751 |                                      196% |                                 1,915 |                                  7,586 |
|                [Minnesota](/us-mn) |            1,082 |                     4,009 |                     711 |                      2,927 |                                      271% |                                 1,849 |                                  6,362 |
|                 [Colorado](/us-co) |            1,474 |                     3,831 |                     665 |                      2,357 |                                      160% |                                 2,024 |                                  6,515 |
|           [North Carolina](/us-nc) |              961 |                     3,455 |                     329 |                      2,494 |                                      260% |                                 1,693 |                                  5,968 |
|                  [Arizona](/us-az) |              943 |                     3,017 |                     414 |                      2,074 |                                      220% |                                 1,320 |                                  5,746 |
|                 [Missouri](/us-mo) |              786 |                     2,616 |                     426 |                      1,830 |                                      233% |                                 1,310 |                                  4,389 |
|              [Mississippi](/us-ms) |              767 |                     2,548 |                     856 |                      1,781 |                                      232% |                                 1,128 |                                  4,167 |
|                  [Alabama](/us-al) |              653 |                     2,342 |                     478 |                      1,689 |                                      259% |                                 1,191 |                                  3,859 |
|           [South Carolina](/us-sc) |              501 |                     1,793 |                     348 |                      1,292 |                                      258% |                                   820 |                                  3,092 |
|             [Rhode Island](/us-ri) |              732 |                     1,723 |                   1,626 |                        991 |                                      135% |                                 1,155 |                                  2,327 |
|               [Washington](/us-wa) |            1,129 |                     1,718 |                     226 |                        589 |                                       52% |                                 1,233 |                                  2,995 |
|                [Wisconsin](/us-wi) |              607 |                     1,692 |                     291 |                      1,085 |                                      179% |                                   902 |                                  3,036 |
|                     [Iowa](/us-ia) |              561 |                     1,624 |                     515 |                      1,063 |                                      189% |                                 1,072 |                                  2,362 |
|                 [Kentucky](/us-ky) |              442 |                     1,124 |                     252 |                        682 |                                      154% |                                   605 |                                  2,149 |
|               [New Mexico](/us-nm) |              367 |                     1,105 |                     527 |                        738 |                                      201% |                                   578 |                                  1,721 |
|                [Tennessee](/us-tn) |              381 |                     1,029 |                     151 |                        648 |                                      170% |                                   535 |                                  1,946 |
|                 [Delaware](/us-de) |              373 |                       896 |                     920 |                        523 |                                      140% |                                   538 |                                  1,381 |
|                   [Nevada](/us-nv) |              417 |                       891 |                     289 |                        474 |                                      114% |                                   526 |                                  1,596 |
|     [District of Columbia](/us-dc) |              470 |                       764 |                   1,083 |                        294 |                                       63% |                                   537 |                                  1,207 |
|            [New Hampshire](/us-nh) |              256 |                       741 |                     545 |                        485 |                                      189% |                                   341 |                                  1,437 |
|                 [Oklahoma](/us-ok) |              339 |                       579 |                     146 |                        240 |                                       71% |                                   407 |                                  1,068 |
|                 [Nebraska](/us-ne) |              170 |                       492 |                     254 |                        322 |                                      189% |                                   303 |                                    785 |
|                 [Arkansas](/us-ar) |              136 |                       458 |                     152 |                        322 |                                      237% |                                   225 |                                    844 |
|                     [Utah](/us-ut) |              113 |                       450 |                     140 |                        337 |                                      298% |                                   198 |                                    834 |
|                   [Kansas](/us-ks) |              222 |                       385 |                     132 |                        163 |                                       73% |                                   251 |                                    877 |
|                   [Oregon](/us-or) |              157 |                       246 |                      58 |                         89 |                                       57% |                                   177 |                                    423 |
|              [Puerto Rico](/us-pr) |              138 |                       200 |                      63 |                         62 |                                       45% |                                   160 |                                    290 |
|             [South Dakota](/us-sd) |               62 |                       197 |                     223 |                        135 |                                      218% |                                   102 |                                    420 |
|             [North Dakota](/us-nd) |               65 |                       185 |                     243 |                        120 |                                      185% |                                   116 |                                    337 |
|                    [Maine](/us-me) |               94 |                       156 |                     116 |                         62 |                                       66% |                                   117 |                                    270 |
|            [West Virginia](/us-wv) |               78 |                       133 |                      74 |                         55 |                                       71% |                                    95 |                                    215 |
|                    [Idaho](/us-id) |               83 |                       106 |                      59 |                         23 |                                       28% |                                    93 |                                    135 |
|                  [Vermont](/us-vt) |               55 |                        65 |                     104 |                         10 |                                       18% |                                    60 |                                     73 |
|                  [Wyoming](/us-wy) |               17 |                        45 |                      78 |                         28 |                                      165% |                                    32 |                                     75 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     22 |
|                  [Montana](/us-mt) |               17 |                        21 |                      20 |                          4 |                                       24% |                                    18 |                                     24 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     13 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          170,029 |                   202,248 |                     341 |                     32,219 |                                       19% |                               179,873 |                                249,628 |
| [United Kingdom](/united-kingdom) |           39,452 |                    48,188 |                     714 |                      8,736 |                                       22% |                                42,502 |                                 54,934 |
|                   [Italy](/italy) |           33,530 |                    38,174 |                     632 |                      4,644 |                                       14% |                                34,768 |                                 43,914 |
|                 [France](/france) |           28,943 |                    31,020 |                     463 |                      2,077 |                                        7% |                                29,155 |                                 37,830 |
|                   [Spain](/spain) |           27,127 |                    28,824 |                     614 |                      1,697 |                                        6% |                                27,319 |                                 34,261 |
|               [Germany](/germany) |            8,563 |                    10,336 |                     125 |                      1,773 |                                       21% |                                 8,892 |                                 15,157 |
|               [Belgium](/belgium) |            9,505 |                    10,200 |                     890 |                        695 |                                        7% |                                 9,662 |                                 11,529 |
|                 [Sweden](/sweden) |            4,468 |                     7,765 |                     759 |                      3,297 |                                       74% |                                 6,372 |                                 12,116 |
|       [Netherlands](/netherlands) |            5,986 |                     7,001 |                     405 |                      1,015 |                                       17% |                                 6,226 |                                  8,667 |
|               [Ukraine](/ukraine) |              733 |                     3,267 |                      74 |                      2,534 |                                      346% |                                 1,412 |                                  5,436 |
|                 [Poland](/poland) |            1,092 |                     2,212 |                      58 |                      1,120 |                                      103% |                                 1,355 |                                  3,903 |
|             [Portugal](/portugal) |            1,436 |                     2,112 |                     206 |                        676 |                                       47% |                                 1,667 |                                  3,104 |
|       [Switzerland](/switzerland) |            1,920 |                     2,060 |                     240 |                        140 |                                        7% |                                 1,947 |                                  2,321 |
|               [Romania](/romania) |            1,288 |                     2,056 |                     106 |                        768 |                                       60% |                                 1,614 |                                  3,105 |
|               [Ireland](/ireland) |            1,658 |                     1,818 |                     371 |                        160 |                                       10% |                                 1,685 |                                  2,391 |
|               [Moldova](/moldova) |              307 |                     1,391 |                     344 |                      1,084 |                                      353% |                                   691 |                                  2,063 |
|               [Hungary](/hungary) |              532 |                       902 |                      92 |                        370 |                                       70% |                                   614 |                                  1,645 |
|               [Austria](/austria) |              669 |                       743 |                      84 |                         74 |                                       11% |                                   694 |                                    865 |
|               [Belarus](/belarus) |              243 |                       687 |                      73 |                        444 |                                      183% |                                   389 |                                  1,861 |
|               [Denmark](/denmark) |              580 |                       683 |                     118 |                        103 |                                       18% |                                   619 |                                    816 |
|             [Bulgaria](/bulgaria) |              144 |                       522 |                      75 |                        378 |                                      262% |                                   260 |                                    872 |
|               [Finland](/finland) |              320 |                       394 |                      71 |                         74 |                                       23% |                                   339 |                                    537 |
|               [Czechia](/czechia) |              323 |                       371 |                      35 |                         48 |                                       15% |                                   349 |                                    413 |
|                 [Serbia](/serbia) |              245 |                       324 |                      47 |                         79 |                                       32% |                                   278 |                                    423 |
|                 [Norway](/norway) |              237 |                       265 |                      49 |                         28 |                                       12% |                                   247 |                                    303 |
|                 [Greece](/greece) |              179 |                       220 |                      21 |                         41 |                                       23% |                                   200 |                                    256 |
|               [Croatia](/croatia) |              103 |                       139 |                      34 |                         36 |                                       35% |                                   115 |                                    194 |
|           [Lithuania](/lithuania) |               71 |                       136 |                      49 |                         65 |                                       92% |                                    96 |                                    220 |
|         [Luxembourg](/luxembourg) |              110 |                       124 |                     202 |                         14 |                                       13% |                                   114 |                                    142 |
|             [Slovenia](/slovenia) |              109 |                       124 |                      60 |                         15 |                                       14% |                                   113 |                                    145 |
|               [Estonia](/estonia) |               68 |                        81 |                      61 |                         13 |                                       19% |                                    78 |                                     86 |
|             [Slovakia](/slovakia) |               28 |                        32 |                       6 |                          4 |                                       14% |                                    29 |                                     37 |
|                 [Latvia](/latvia) |               24 |                        31 |                      16 |                          7 |                                       29% |                                    30 |                                     33 |
|                 [Cyprus](/cyprus) |               17 |                        20 |                      23 |                          3 |                                       18% |                                    19 |                                     21 |
|                   [Malta](/malta) |                9 |                        15 |                      30 |                          6 |                                       67% |                                    13 |                                     16 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          100,411 |                   433,146 |                      83 |                    332,735 |                                      331% |                               214,445 |                                691,016 |
|                             [Brazil](/brazil) |           31,199 |                   130,279 |                     617 |                     99,080 |                                      318% |                                64,884 |                                245,586 |
|                             [Mexico](/mexico) |           10,637 |                    76,321 |                     598 |                     65,684 |                                      618% |                                36,521 |                                102,522 |
|                               [India](/india) |            5,829 |                    57,757 |                      42 |                     51,928 |                                      891% |                                17,494 |                                 76,653 |
|                             [Russia](/russia) |            5,031 |                    25,497 |                     175 |                     20,466 |                                      407% |                                 9,710 |                                 42,914 |
|                                 [Peru](/peru) |            4,634 |                    22,030 |                     678 |                     17,396 |                                      375% |                                 8,835 |                                 40,340 |
|                             [Canada](/canada) |            7,477 |                    12,962 |                     346 |                      5,485 |                                       73% |                                 8,465 |                                 22,206 |
|                                 [Iran](/iran) |            7,942 |                    12,083 |                     146 |                      4,141 |                                       52% |                                 8,785 |                                 20,024 |
|                               [Chile](/chile) |            1,188 |                    10,931 |                     577 |                      9,743 |                                      820% |                                 9,168 |                                 12,960 |
|                         [Colombia](/colombia) |            1,014 |                    10,143 |                     201 |                      9,129 |                                      900% |                                 6,114 |                                 13,257 |
|                 [South Africa](/south-africa) |              755 |                    10,032 |                     171 |                      9,277 |                                     1229% |                                 6,041 |                                 12,782 |
|                         [Pakistan](/pakistan) |            1,621 |                     8,605 |                      40 |                      6,984 |                                      431% |                                 3,598 |                                 15,485 |
|                     [Bangladesh](/bangladesh) |              709 |                     6,624 |                      41 |                      5,915 |                                      834% |                                 3,600 |                                  8,789 |
|                           [Ecuador](/ecuador) |            3,438 |                     6,118 |                     352 |                      2,680 |                                       78% |                                 4,079 |                                 11,866 |
|                               [Egypt](/egypt) |            1,052 |                     6,093 |                      61 |                      5,041 |                                      479% |                                 2,474 |                                  9,619 |
|                             [Turkey](/turkey) |            4,585 |                     5,502 |                      66 |                        917 |                                       20% |                                 4,767 |                                  7,489 |
|                       [Indonesia](/indonesia) |            1,663 |                     5,418 |                      20 |                      3,755 |                                      226% |                                 2,842 |                                  9,400 |
|                               [China](/china) |            4,638 |                     4,645 |                       3 |                          7 |                                        0% |                                 4,638 |                                  4,685 |
|                 [Saudi Arabia](/saudi-arabia) |              549 |                     4,095 |                     119 |                      3,546 |                                      646% |                                 2,131 |                                  5,292 |
|                           [Bolivia](/bolivia) |              376 |                     2,902 |                     252 |                      2,526 |                                      672% |                                 1,665 |                                  4,398 |
|                       [Argentina](/argentina) |              569 |                     2,653 |                      59 |                      2,084 |                                      366% |                                 1,289 |                                  4,101 |
|                           [Nigeria](/nigeria) |              314 |                     1,877 |                       9 |                      1,563 |                                      498% |                                   615 |                                  3,250 |
|                   [Philippines](/philippines) |              966 |                     1,809 |                      17 |                        843 |                                       87% |                                 1,151 |                                  3,269 |
|                             [Kuwait](/kuwait) |              226 |                     1,477 |                     351 |                      1,251 |                                      554% |                                   746 |                                  2,158 |
|                               [Japan](/japan) |              902 |                     1,429 |                      11 |                        527 |                                       58% |                                   934 |                                  2,124 |
|                         [Honduras](/honduras) |              225 |                     1,114 |                     114 |                        889 |                                      395% |                                   550 |                                  1,918 |
|                           [Algeria](/algeria) |              667 |                     1,076 |                      25 |                        409 |                                       61% |                                   753 |                                  2,052 |
|                             [Panama](/panama) |              352 |                     1,032 |                     243 |                        680 |                                      193% |                                   512 |                                  1,941 |
|     [Dominican Republic](/dominican-republic) |              515 |                       869 |                      81 |                        354 |                                       69% |                                   618 |                                  1,339 |
| [United Arab Emirates](/united-arab-emirates) |              269 |                       512 |                      52 |                        243 |                                       90% |                                   334 |                                  1,047 |
|                             [Israel](/israel) |              290 |                       355 |                      42 |                         65 |                                       22% |                                   314 |                                    464 |
|                   [South Korea](/south-korea) |              273 |                       325 |                       6 |                         52 |                                       19% |                                   280 |                                    434 |
|                           [Morocco](/morocco) |              206 |                       230 |                       6 |                         24 |                                       12% |                                   216 |                                    260 |
|                         [Malaysia](/malaysia) |              115 |                       145 |                       5 |                         30 |                                       26% |                                   130 |                                    158 |
|                       [Australia](/australia) |              102 |                       108 |                       4 |                          6 |                                        6% |                                   103 |                                    125 |
|                                 [Cuba](/cuba) |               83 |                        98 |                       9 |                         15 |                                       18% |                                    89 |                                    109 |
