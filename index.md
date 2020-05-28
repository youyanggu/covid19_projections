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

* **May 27:** We added [7 new countries](/#global-projections) (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), [2 Canadian provinces](/#global-projections) (Alberta and British Columbia), and [20 US counties](/#us-counties). We now have projections for 71 countries (>99% of all global COVID-19 deaths), 4 Canadian provinces (99% of Canadian COVID-19 deaths), 56 US states and territories, and 34 US counties (including the top 30 most populous counties).

* **May 26:** We have extended our projections to September 1, 2020.

* **May 25:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 22:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729), [widespread reopenings](https://www.wsj.com/articles/coronavirus-latest-news-05-20-2020-11589963481), [unreported care home deaths](https://www.economist.com/europe/2020/05/09/many-covid-deaths-in-care-homes-are-unrecorded), [increased efforts for contact tracing](https://www.npr.org/sections/health-shots/2020/04/28/846736937/we-asked-all-50-states-about-their-contact-tracing-capacity-heres-what-we-learne), and [conflated testing numbers](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 28 (3am ET):
<p align="center">
  Current Total: <b>100,415</b> deaths | Projected Total: <b>204,626 deaths by Sep 1, 2020</b> (Range: 124-356k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 74% chance that the US surpasses 125,000 deaths by July 1, with June 22 being the most likely date.

Last updated: May 28, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              125,000 |        Jun 22, 2020 |
|              150,000 |        Jul 16, 2020 |
|              175,000 |         Aug 6, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         15% |        74% |         89% |        95% |         97% |        98% |
|              150,000 |         <1% |        13% |         42% |        64% |         73% |        78% |
|              175,000 |         <1% |        <1% |         14% |        38% |         50% |        58% |
|              200,000 |         <1% |        <1% |          2% |        20% |         34% |        44% |
|              250,000 |         <1% |        <1% |         <1% |         3% |         13% |        23% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |          3% |        10% |
|              350,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         3% |

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
|             *[United States](/us)* |          100,415 |                   204,626 |                     617 |                    104,211 |                                      104% |                               124,990 |                                355,674 |
|                 [New York](/us-ny) |           29,484 |                    33,407 |                   1,717 |                      3,923 |                                       13% |                                30,425 |                                 40,662 |
|                 [Illinois](/us-il) |            5,083 |                    16,444 |                   1,298 |                     11,361 |                                      224% |                                 8,539 |                                 26,553 |
|               [New Jersey](/us-nj) |           11,339 |                    15,509 |                   1,746 |                      4,170 |                                       37% |                                12,509 |                                 21,477 |
|               [California](/us-ca) |            3,895 |                    12,342 |                     312 |                      8,447 |                                      217% |                                 5,227 |                                 29,567 |
|             [Pennsylvania](/us-pa) |            5,265 |                    11,056 |                     864 |                      5,791 |                                      110% |                                 6,366 |                                 20,841 |
|            [Massachusetts](/us-ma) |            6,547 |                    10,177 |                   1,464 |                      3,630 |                                       55% |                                 7,455 |                                 15,975 |
|                     [Ohio](/us-oh) |            2,044 |                     8,474 |                     725 |                      6,430 |                                      315% |                                 3,735 |                                 16,568 |
|                  [Florida](/us-fl) |            2,319 |                     7,313 |                     340 |                      4,994 |                                      215% |                                 3,207 |                                 15,619 |
|                 [Michigan](/us-mi) |            5,334 |                     6,919 |                     693 |                      1,585 |                                       30% |                                 5,821 |                                  9,890 |
|                  [Indiana](/us-in) |            2,030 |                     6,251 |                     929 |                      4,221 |                                      208% |                                 2,926 |                                 12,640 |
|                    [Texas](/us-tx) |            1,581 |                     6,105 |                     211 |                      4,524 |                                      286% |                                 2,698 |                                 13,043 |
|                 [Maryland](/us-md) |            2,392 |                     6,073 |                   1,005 |                      3,681 |                                      154% |                                 3,136 |                                 11,475 |
|                  [Georgia](/us-ga) |            1,933 |                     5,810 |                     547 |                      3,877 |                                      201% |                                 2,786 |                                 11,346 |
|              [Connecticut](/us-ct) |            3,803 |                     5,307 |                   1,489 |                      1,504 |                                       40% |                                 4,235 |                                  7,319 |
|                 [Virginia](/us-va) |            1,281 |                     4,548 |                     533 |                      3,267 |                                      255% |                                 1,819 |                                  9,951 |
|                 [Colorado](/us-co) |            1,392 |                     4,364 |                     758 |                      2,972 |                                      214% |                                 2,039 |                                  8,192 |
|                  [Arizona](/us-az) |              834 |                     4,303 |                     591 |                      3,469 |                                      416% |                                 1,691 |                                  7,999 |
|                [Louisiana](/us-la) |            2,723 |                     4,176 |                     898 |                      1,453 |                                       53% |                                 3,076 |                                  6,199 |
|                [Minnesota](/us-mn) |              942 |                     4,074 |                     722 |                      3,132 |                                      332% |                                 1,585 |                                  8,092 |
|              [Mississippi](/us-ms) |              670 |                     2,989 |                   1,004 |                      2,319 |                                      346% |                                 1,232 |                                  5,228 |
|           [North Carolina](/us-nc) |              844 |                     2,983 |                     284 |                      2,139 |                                      253% |                                 1,352 |                                  6,269 |
|                 [Missouri](/us-mo) |              689 |                     2,452 |                     400 |                      1,763 |                                      256% |                                 1,104 |                                  5,314 |
|                  [Alabama](/us-al) |              583 |                     2,366 |                     483 |                      1,783 |                                      306% |                                 1,030 |                                  4,641 |
|                     [Iowa](/us-ia) |              496 |                     2,168 |                     687 |                      1,672 |                                      337% |                                   891 |                                  3,915 |
|           [South Carolina](/us-sc) |              466 |                     2,121 |                     412 |                      1,655 |                                      355% |                                   830 |                                  4,432 |
|             [Rhode Island](/us-ri) |              655 |                     1,926 |                   1,818 |                      1,271 |                                      194% |                                 1,137 |                                  3,172 |
|               [Washington](/us-wa) |            1,095 |                     1,691 |                     222 |                        596 |                                       54% |                                 1,211 |                                  3,104 |
|               [New Mexico](/us-nm) |              329 |                     1,451 |                     692 |                      1,122 |                                      341% |                                   622 |                                  2,873 |
|                [Wisconsin](/us-wi) |              539 |                     1,306 |                     224 |                        767 |                                      142% |                                   751 |                                  2,745 |
|            [New Hampshire](/us-nh) |              223 |                     1,200 |                     883 |                        977 |                                      438% |                                   535 |                                  2,065 |
|                   [Nevada](/us-nv) |              402 |                     1,083 |                     352 |                        681 |                                      169% |                                   544 |                                  2,201 |
|                 [Delaware](/us-de) |              344 |                     1,017 |                   1,044 |                        673 |                                      196% |                                   537 |                                  1,929 |
|                 [Kentucky](/us-ky) |              400 |                     1,007 |                     225 |                        607 |                                      152% |                                   528 |                                  2,283 |
|                 [Nebraska](/us-ne) |              153 |                       951 |                     492 |                        798 |                                      522% |                                   345 |                                  1,818 |
|                [Tennessee](/us-tn) |              353 |                       899 |                     132 |                        546 |                                      155% |                                   516 |                                  1,854 |
|     [District of Columbia](/us-dc) |              445 |                       813 |                   1,152 |                        368 |                                       83% |                                   530 |                                  1,394 |
|                 [Oklahoma](/us-ok) |              322 |                       598 |                     151 |                        276 |                                       86% |                                   405 |                                  1,112 |
|                     [Utah](/us-ut) |              105 |                       578 |                     180 |                        473 |                                      450% |                                   206 |                                  1,209 |
|                 [Arkansas](/us-ar) |              120 |                       408 |                     135 |                        288 |                                      240% |                                   192 |                                    882 |
|                   [Kansas](/us-ks) |              213 |                       396 |                     136 |                        183 |                                       86% |                                   252 |                                    917 |
|             [South Dakota](/us-sd) |               54 |                       301 |                     340 |                        247 |                                      457% |                                    98 |                                    733 |
|             [North Dakota](/us-nd) |               56 |                       268 |                     352 |                        212 |                                      379% |                                   102 |                                    606 |
|                   [Oregon](/us-or) |              148 |                       228 |                      54 |                         80 |                                       54% |                                   168 |                                    403 |
|              [Puerto Rico](/us-pr) |              129 |                       186 |                      58 |                         57 |                                       44% |                                   149 |                                    278 |
|            [West Virginia](/us-wv) |               74 |                       150 |                      84 |                         76 |                                      103% |                                    96 |                                    315 |
|                    [Maine](/us-me) |               81 |                       131 |                      97 |                         50 |                                       62% |                                   103 |                                    171 |
|                    [Idaho](/us-id) |               81 |                       105 |                      59 |                         24 |                                       30% |                                    92 |                                    133 |
|                  [Vermont](/us-vt) |               54 |                        65 |                     104 |                         11 |                                       20% |                                    60 |                                     73 |
|                  [Wyoming](/us-wy) |               14 |                        60 |                     104 |                         46 |                                      329% |                                    30 |                                    109 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    20 |                                     25 |
|                  [Montana](/us-mt) |               17 |                        22 |                      21 |                          5 |                                       29% |                                    19 |                                     26 |
|                   [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    11 |                                     14 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     8 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          167,834 |                   217,275 |                     366 |                     49,441 |                                       29% |                               179,769 |                                301,868 |
| [United Kingdom](/united-kingdom) |           37,542 |                    54,029 |                     800 |                     16,487 |                                       44% |                                41,659 |                                 77,849 |
|                   [Italy](/italy) |           33,072 |                    39,607 |                     656 |                      6,535 |                                       20% |                                35,148 |                                 48,878 |
|                   [Spain](/spain) |           28,752 |                    32,402 |                     690 |                      3,650 |                                       13% |                                29,551 |                                 39,637 |
|                 [France](/france) |           28,599 |                    32,326 |                     482 |                      3,727 |                                       13% |                                28,959 |                                 43,893 |
|               [Germany](/germany) |            8,428 |                    11,378 |                     137 |                      2,950 |                                       35% |                                 8,924 |                                 19,862 |
|               [Belgium](/belgium) |            9,364 |                    10,452 |                     912 |                      1,088 |                                       12% |                                 9,592 |                                 12,605 |
|       [Netherlands](/netherlands) |            5,890 |                     7,532 |                     436 |                      1,642 |                                       28% |                                 6,259 |                                 10,113 |
|                 [Sweden](/sweden) |            4,220 |                     6,141 |                     600 |                      1,921 |                                       46% |                                 4,820 |                                  7,761 |
|               [Ukraine](/ukraine) |              658 |                     3,870 |                      88 |                      3,212 |                                      488% |                                 1,391 |                                  7,693 |
|               [Romania](/romania) |            1,227 |                     2,759 |                     142 |                      1,532 |                                      125% |                                 1,717 |                                  4,881 |
|                 [Poland](/poland) |            1,028 |                     2,613 |                      69 |                      1,585 |                                      154% |                                 1,301 |                                  5,742 |
|       [Switzerland](/switzerland) |            1,917 |                     2,196 |                     256 |                        279 |                                       15% |                                 1,974 |                                  2,925 |
|             [Portugal](/portugal) |            1,356 |                     2,055 |                     200 |                        699 |                                       52% |                                 1,563 |                                  3,062 |
|               [Ireland](/ireland) |            1,631 |                     1,967 |                     401 |                        336 |                                       21% |                                 1,697 |                                  2,956 |
|               [Moldova](/moldova) |              274 |                     1,632 |                     404 |                      1,358 |                                      496% |                                   672 |                                  3,026 |
|               [Hungary](/hungary) |              505 |                       938 |                      96 |                        433 |                                       86% |                                   584 |                                  2,073 |
|               [Austria](/austria) |              645 |                       747 |                      84 |                        102 |                                       16% |                                   676 |                                    942 |
|               [Belarus](/belarus) |              214 |                       731 |                      77 |                        517 |                                      242% |                                   367 |                                  1,936 |
|               [Denmark](/denmark) |              565 |                       729 |                     126 |                        164 |                                       29% |                                   620 |                                    956 |
|             [Bulgaria](/bulgaria) |              133 |                       682 |                      97 |                        549 |                                      413% |                                   257 |                                  1,434 |
|               [Finland](/finland) |              313 |                       483 |                      88 |                        170 |                                       54% |                                   346 |                                    888 |
|               [Czechia](/czechia) |              317 |                       387 |                      36 |                         70 |                                       22% |                                   353 |                                    442 |
|                 [Serbia](/serbia) |              240 |                       377 |                      54 |                        137 |                                       57% |                                   285 |                                    614 |
|                 [Norway](/norway) |              235 |                       272 |                      51 |                         37 |                                       16% |                                   246 |                                    317 |
|                 [Greece](/greece) |              173 |                       221 |                      21 |                         48 |                                       28% |                                   193 |                                    312 |
|               [Croatia](/croatia) |              101 |                       184 |                      45 |                         83 |                                       82% |                                   123 |                                    361 |
|             [Slovenia](/slovenia) |              108 |                       132 |                      63 |                         24 |                                       22% |                                   114 |                                    189 |
|         [Luxembourg](/luxembourg) |              110 |                       129 |                     210 |                         19 |                                       17% |                                   116 |                                    152 |
|           [Lithuania](/lithuania) |               66 |                       107 |                      38 |                         41 |                                       62% |                                    81 |                                    146 |
|               [Estonia](/estonia) |               66 |                        85 |                      64 |                         19 |                                       29% |                                    79 |                                     95 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    30 |                                     44 |
|                 [Latvia](/latvia) |               23 |                        34 |                      18 |                         11 |                                       48% |                                    32 |                                     36 |
|                 [Cyprus](/cyprus) |               17 |                        21 |                      24 |                          4 |                                       24% |                                    20 |                                     24 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |
|                   [Malta](/malta) |                7 |                        10 |                      20 |                          3 |                                       43% |                                     9 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           86,027 |                   578,783 |                     112 |                    492,756 |                                      573% |                               190,742 |                              1,146,779 |
|                             [Brazil](/brazil) |           25,598 |                   195,981 |                     929 |                    170,383 |                                      666% |                                54,735 |                                456,583 |
|                             [Mexico](/mexico) |            8,597 |                   136,769 |                   1,072 |                    128,172 |                                     1491% |                                39,775 |                                215,212 |
|                               [India](/india) |            4,534 |                    60,619 |                      44 |                     56,085 |                                     1237% |                                12,249 |                                119,329 |
|                                 [Peru](/peru) |            3,983 |                    31,695 |                     975 |                     27,712 |                                      696% |                                11,270 |                                 52,598 |
|                             [Russia](/russia) |            3,968 |                    22,642 |                     155 |                     18,674 |                                      471% |                                 6,526 |                                 54,822 |
|                 [South Africa](/south-africa) |              552 |                    18,165 |                     310 |                     17,613 |                                     3191% |                                 8,635 |                                 29,904 |
|                             [Canada](/canada) |            6,876 |                    13,814 |                     369 |                      6,938 |                                      101% |                                 8,218 |                                 29,010 |
|                                 [Iran](/iran) |            7,564 |                    12,568 |                     152 |                      5,004 |                                       66% |                                 8,508 |                                 22,337 |
|                               [Chile](/chile) |              841 |                    11,846 |                     625 |                     11,005 |                                     1309% |                                 5,762 |                                 18,835 |
|                         [Colombia](/colombia) |              803 |                     9,155 |                     182 |                      8,352 |                                     1040% |                                 3,291 |                                 17,647 |
|                         [Pakistan](/pakistan) |            1,225 |                     8,545 |                      39 |                      7,320 |                                      598% |                                 2,318 |                                 20,194 |
|                           [Ecuador](/ecuador) |            3,275 |                     7,679 |                     442 |                      4,404 |                                      134% |                                 4,095 |                                 18,401 |
|                     [Bangladesh](/bangladesh) |              544 |                     7,256 |                      45 |                      6,712 |                                     1234% |                                 2,250 |                                 13,185 |
|                             [Turkey](/turkey) |            4,431 |                     5,568 |                      67 |                      1,137 |                                       26% |                                 4,696 |                                  8,150 |
|                       [Indonesia](/indonesia) |            1,473 |                     5,400 |                      20 |                      3,927 |                                      267% |                                 2,232 |                                 12,219 |
|                               [Egypt](/egypt) |              816 |                     4,816 |                      48 |                      4,000 |                                      490% |                                 1,520 |                                 10,608 |
|                               [China](/china) |            4,638 |                     4,653 |                       3 |                         15 |                                        0% |                                 4,638 |                                  4,748 |
|                       [Argentina](/argentina) |              500 |                     4,104 |                      92 |                      3,604 |                                      721% |                                 1,247 |                                  8,500 |
|                 [Saudi Arabia](/saudi-arabia) |              425 |                     3,563 |                     104 |                      3,138 |                                      738% |                                 1,216 |                                  6,728 |
|                           [Bolivia](/bolivia) |              280 |                     2,209 |                     192 |                      1,929 |                                      689% |                                   903 |                                  4,022 |
|                   [Philippines](/philippines) |              904 |                     1,628 |                      15 |                        724 |                                       80% |                                 1,047 |                                  2,917 |
|                           [Nigeria](/nigeria) |              254 |                     1,538 |                       8 |                      1,284 |                                      506% |                                   448 |                                  4,502 |
|                             [Kuwait](/kuwait) |              175 |                     1,493 |                     355 |                      1,318 |                                      753% |                                   634 |                                  2,669 |
|                         [Honduras](/honduras) |              194 |                     1,167 |                     120 |                        973 |                                      502% |                                   464 |                                  2,602 |
|                               [Japan](/japan) |              858 |                     1,163 |                       9 |                        305 |                                       36% |                                   876 |                                  1,643 |
|                           [Algeria](/algeria) |              623 |                       992 |                      23 |                        369 |                                       59% |                                   728 |                                  1,959 |
|     [Dominican Republic](/dominican-republic) |              474 |                       941 |                      88 |                        467 |                                       99% |                                   585 |                                  1,875 |
|                             [Panama](/panama) |              315 |                       902 |                     212 |                        587 |                                      186% |                                   419 |                                  2,237 |
| [United Arab Emirates](/united-arab-emirates) |              255 |                       634 |                      65 |                        379 |                                      149% |                                   331 |                                  1,692 |
|                             [Israel](/israel) |              281 |                       347 |                      41 |                         66 |                                       23% |                                   305 |                                    466 |
|                   [South Korea](/south-korea) |              269 |                       323 |                       6 |                         54 |                                       20% |                                   277 |                                    440 |
|                           [Morocco](/morocco) |              202 |                       239 |                       7 |                         37 |                                       18% |                                   218 |                                    291 |
|                         [Malaysia](/malaysia) |              115 |                       147 |                       5 |                         32 |                                       28% |                                   129 |                                    174 |
|                       [Australia](/australia) |              103 |                       114 |                       5 |                         11 |                                       11% |                                   105 |                                    140 |
|                                 [Cuba](/cuba) |               82 |                       108 |                      10 |                         26 |                                       32% |                                    92 |                                    140 |
