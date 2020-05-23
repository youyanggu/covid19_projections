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

* **May 22:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729), [widespread reopenings](https://www.wsj.com/articles/coronavirus-latest-news-05-20-2020-11589963481), and [conflated testing numbers](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/).

* **May 20:** We added county-level projections for 14 US counties heavily impacted by COVID-19. This includes cities such as [New York City](/us-ny-new-york-city) (5 boroughs), [Los Angeles](/us-ca-los-angeles), and [Chicago](/us-il-cook). See all 14 counties [here](#us-counties). We also added the 2 Canadian provinces accounting for ~85% of cases in Canada: [Ontario](/canada-ontario) and [Quebec](/canada-quebec).

* **May 18:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

* **May 13:** If you add `-noreopen` to the end of any projections page URL, you can see our projections with the assumption that there are no reopenings. E.g. [covid19-projections.com/us](/us) --> [covid19-projections.com/us-noreopen](/us-noreopen). Some caveats [here](https://twitter.com/youyanggu/status/1260678502107344896).

* **May 12:** We added 23 additional countries. The countries our projections cover encompass 6.3 billion people and account for over 99% of all global COVID-19 deaths. View our global projections [here](#global-projections).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 23 (5am ET):
<p align="center">
  Current Total: <b>95,976</b> deaths | Projected Total: <b>184,015</b> deaths by Aug 4, 2020 (Range: 124-291k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>3.7%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 38% chance that the US surpasses 125,000 deaths by June 15, with June 17 being the most likely date.

Last updated: May 23, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 27, 2020 |
|              125,000 |        Jun 17, 2020 |
|              150,000 |         Jul 9, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |        99% |        >99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         38% |        84% |         93% |        96% |
|              150,000 |        <1% |         <1% |        27% |         56% |        72% |
|              175,000 |        <1% |         <1% |         4% |         25% |        47% |
|              200,000 |        <1% |         <1% |        <1% |          9% |        29% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         8% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
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
|         *[United States](/us)* |           95,976 |                   184,015 |                     555 |                     88,039 |                                       92% |                               123,202 |                                290,078 |
|             [New York](/us-ny) |           28,853 |                    32,851 |                   1,689 |                      3,998 |                                       14% |                                30,272 |                                 39,561 |
|           [New Jersey](/us-nj) |           10,985 |                    15,476 |                   1,742 |                      4,491 |                                       41% |                                12,509 |                                 20,838 |
|             [Illinois](/us-il) |            4,715 |                    15,262 |                   1,204 |                     10,547 |                                      224% |                                 9,105 |                                 22,464 |
|         [Pennsylvania](/us-pa) |            5,010 |                    11,246 |                     878 |                      6,236 |                                      124% |                                 7,059 |                                 16,777 |
|           [California](/us-ca) |            3,666 |                    10,233 |                     259 |                      6,567 |                                      179% |                                 4,977 |                                 20,873 |
|        [Massachusetts](/us-ma) |            6,228 |                     9,645 |                   1,388 |                      3,417 |                                       55% |                                 7,303 |                                 14,403 |
|                 [Ohio](/us-oh) |            1,872 |                     6,885 |                     589 |                      5,013 |                                      268% |                                 3,441 |                                 13,385 |
|             [Michigan](/us-mi) |            5,158 |                     6,715 |                     672 |                      1,557 |                                       30% |                                 5,766 |                                  8,849 |
|              [Indiana](/us-in) |            1,941 |                     5,953 |                     884 |                      4,012 |                                      207% |                                 2,918 |                                 11,750 |
|              [Florida](/us-fl) |            2,190 |                     5,386 |                     251 |                      3,196 |                                      146% |                                 2,894 |                                  9,898 |
|                [Texas](/us-tx) |            1,470 |                     5,287 |                     182 |                      3,817 |                                      260% |                                 2,464 |                                  9,723 |
|          [Connecticut](/us-ct) |            3,637 |                     5,222 |                   1,465 |                      1,585 |                                       44% |                                 4,192 |                                  7,342 |
|             [Maryland](/us-md) |            2,207 |                     5,176 |                     856 |                      2,969 |                                      135% |                                 2,916 |                                  9,274 |
|              [Georgia](/us-ga) |            1,808 |                     4,796 |                     452 |                      2,988 |                                      165% |                                 2,527 |                                  8,862 |
|            [Louisiana](/us-la) |            2,668 |                     3,908 |                     841 |                      1,240 |                                       46% |                                 3,128 |                                  5,297 |
|              [Arizona](/us-az) |              775 |                     3,902 |                     536 |                      3,127 |                                      403% |                                 1,790 |                                  7,167 |
|             [Colorado](/us-co) |            1,324 |                     3,561 |                     618 |                      2,237 |                                      169% |                                 1,991 |                                  6,181 |
|            [Minnesota](/us-mn) |              851 |                     3,471 |                     615 |                      2,620 |                                      308% |                                 1,444 |                                  6,534 |
|             [Virginia](/us-va) |            1,136 |                     3,144 |                     368 |                      2,008 |                                      177% |                                 1,579 |                                  6,975 |
|          [Mississippi](/us-ms) |              595 |                     2,646 |                     889 |                      2,051 |                                      345% |                                 1,216 |                                  4,636 |
|             [Missouri](/us-mo) |              677 |                     2,378 |                     387 |                      1,701 |                                      251% |                                 1,160 |                                  4,217 |
|       [North Carolina](/us-nc) |              775 |                     2,204 |                     210 |                      1,429 |                                      184% |                                 1,184 |                                  4,198 |
|                 [Iowa](/us-ia) |              424 |                     2,177 |                     690 |                      1,753 |                                      413% |                                 1,033 |                                  3,232 |
|              [Alabama](/us-al) |              541 |                     1,894 |                     386 |                      1,353 |                                      250% |                                   979 |                                  3,422 |
|         [Rhode Island](/us-ri) |              579 |                     1,471 |                   1,389 |                        892 |                                      154% |                                   947 |                                  2,276 |
|           [Washington](/us-wa) |            1,050 |                     1,406 |                     185 |                        356 |                                       34% |                                 1,158 |                                  1,986 |
|       [South Carolina](/us-sc) |              419 |                     1,297 |                     252 |                        878 |                                      210% |                                   638 |                                  2,420 |
|           [New Mexico](/us-nm) |              302 |                     1,229 |                     586 |                        927 |                                      307% |                                   612 |                                  2,209 |
|             [Delaware](/us-de) |              322 |                     1,034 |                   1,062 |                        712 |                                      221% |                                   593 |                                  1,812 |
|            [Wisconsin](/us-wi) |              496 |                       909 |                     156 |                        413 |                                       83% |                                   667 |                                  1,475 |
|             [Kentucky](/us-ky) |              391 |                       868 |                     194 |                        477 |                                      122% |                                   554 |                                  1,642 |
|               [Nevada](/us-nv) |              386 |                       850 |                     276 |                        464 |                                      120% |                                   549 |                                  1,564 |
| [District of Columbia](/us-dc) |              418 |                       800 |                   1,134 |                        382 |                                       91% |                                   550 |                                  1,195 |
|        [New Hampshire](/us-nh) |              204 |                       740 |                     544 |                        536 |                                      263% |                                   422 |                                  1,148 |
|             [Nebraska](/us-ne) |              147 |                       694 |                     359 |                        547 |                                      372% |                                   333 |                                  1,178 |
|            [Tennessee](/us-tn) |              315 |                       581 |                      85 |                        266 |                                       84% |                                   431 |                                    927 |
|             [Oklahoma](/us-ok) |              307 |                       471 |                     119 |                        164 |                                       53% |                                   373 |                                    654 |
|                 [Utah](/us-ut) |               93 |                       341 |                     106 |                        248 |                                      267% |                                   161 |                                    647 |
|               [Kansas](/us-ks) |              205 |                       319 |                     109 |                        114 |                                       56% |                                   232 |                                    553 |
|             [Arkansas](/us-ar) |              113 |                       245 |                      81 |                        132 |                                      117% |                                   176 |                                    433 |
|         [North Dakota](/us-nd) |               52 |                       227 |                     298 |                        175 |                                      337% |                                   109 |                                    460 |
|               [Oregon](/us-or) |              147 |                       215 |                      51 |                         68 |                                       46% |                                   172 |                                    308 |
|         [South Dakota](/us-sd) |               50 |                       205 |                     232 |                        155 |                                      310% |                                    96 |                                    434 |
|          [Puerto Rico](/us-pr) |              126 |                       171 |                      54 |                         45 |                                       36% |                                   148 |                                    218 |
|        [West Virginia](/us-wv) |               72 |                       128 |                      71 |                         56 |                                       78% |                                    94 |                                    208 |
|                [Maine](/us-me) |               75 |                       112 |                      83 |                         37 |                                       49% |                                    95 |                                    142 |
|                [Idaho](/us-id) |               79 |                       104 |                      58 |                         25 |                                       32% |                                    92 |                                    118 |
|              [Vermont](/us-vt) |               54 |                        67 |                     107 |                         13 |                                       24% |                                    62 |                                     73 |
|              [Wyoming](/us-wy) |               12 |                        31 |                      54 |                         19 |                                      158% |                                    20 |                                     43 |
|               [Hawaii](/us-hi) |               17 |                        25 |                      18 |                          8 |                                       47% |                                    20 |                                     29 |
|              [Montana](/us-mt) |               16 |                        21 |                      20 |                          5 |                                       31% |                                    19 |                                     25 |
|               [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    12 |                                     15 |
|                 [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     8 |                                     12 |
|       [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     8 |                                     10 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          164,444 |                   207,771 |                     355 |                     43,327 |                                       26% |                               177,340 |                                274,596 |
| [United Kingdom](/united-kingdom) |           36,475 |                    50,972 |                     755 |                     14,497 |                                       40% |                                41,119 |                                 70,819 |
|                   [Italy](/italy) |           32,616 |                    38,604 |                     640 |                      5,988 |                                       18% |                                34,631 |                                 46,296 |
|                   [Spain](/spain) |           28,628 |                    32,032 |                     682 |                      3,404 |                                       12% |                                29,669 |                                 37,612 |
|                 [France](/france) |           28,218 |                    31,510 |                     470 |                      3,292 |                                       12% |                                28,585 |                                 41,460 |
|               [Germany](/germany) |            8,228 |                    10,594 |                     128 |                      2,366 |                                       29% |                                 8,825 |                                 15,476 |
|               [Belgium](/belgium) |            9,212 |                    10,333 |                     902 |                      1,121 |                                       12% |                                 9,457 |                                 12,392 |
|       [Netherlands](/netherlands) |            5,807 |                     7,326 |                     424 |                      1,519 |                                       26% |                                 6,216 |                                  9,591 |
|                 [Sweden](/sweden) |            3,925 |                     5,839 |                     571 |                      1,914 |                                       49% |                                 4,724 |                                  7,752 |
|               [Ukraine](/ukraine) |              588 |                     3,837 |                      87 |                      3,249 |                                      553% |                                 1,410 |                                  7,836 |
|               [Romania](/romania) |            1,166 |                     2,483 |                     128 |                      1,317 |                                      113% |                                 1,658 |                                  4,208 |
|       [Switzerland](/switzerland) |            1,903 |                     2,169 |                     252 |                        266 |                                       14% |                                 1,977 |                                  2,660 |
|                 [Poland](/poland) |              982 |                     2,137 |                      56 |                      1,155 |                                      118% |                                 1,244 |                                  4,171 |
|               [Ireland](/ireland) |            1,592 |                     1,923 |                     392 |                        331 |                                       21% |                                 1,677 |                                  2,663 |
|             [Portugal](/portugal) |            1,289 |                     1,856 |                     181 |                        567 |                                       44% |                                 1,516 |                                  2,497 |
|               [Moldova](/moldova) |              237 |                     1,075 |                     266 |                        838 |                                      354% |                                   483 |                                  2,164 |
|               [Austria](/austria) |              635 |                       751 |                      85 |                        116 |                                       18% |                                   679 |                                    893 |
|               [Hungary](/hungary) |              476 |                       727 |                      74 |                        251 |                                       53% |                                   537 |                                  1,185 |
|               [Denmark](/denmark) |              561 |                       723 |                     125 |                        162 |                                       29% |                                   631 |                                    915 |
|               [Finland](/finland) |              306 |                       482 |                      87 |                        176 |                                       58% |                                   354 |                                    806 |
|             [Bulgaria](/bulgaria) |              125 |                       443 |                      63 |                        318 |                                      254% |                                   246 |                                    791 |
|               [Czechia](/czechia) |              312 |                       399 |                      37 |                         87 |                                       28% |                                   363 |                                    460 |
|                 [Serbia](/serbia) |              237 |                       358 |                      41 |                        121 |                                       51% |                                   289 |                                    503 |
|                 [Norway](/norway) |              235 |                       276 |                      51 |                         41 |                                       17% |                                   250 |                                    313 |
|                 [Greece](/greece) |              169 |                       214 |                      20 |                         45 |                                       27% |                                   192 |                                    249 |
|               [Croatia](/croatia) |               99 |                       162 |                      40 |                         63 |                                       64% |                                   119 |                                    254 |
|         [Luxembourg](/luxembourg) |              109 |                       131 |                     213 |                         22 |                                       20% |                                   120 |                                    151 |
|             [Slovenia](/slovenia) |              106 |                       128 |                      62 |                         22 |                                       21% |                                   113 |                                    154 |
|               [Estonia](/estonia) |               64 |                        87 |                      66 |                         23 |                                       36% |                                    78 |                                     96 |
|           [Lithuania](/lithuania) |               61 |                        85 |                      30 |                         24 |                                       39% |                                    75 |                                     97 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    30 |                                     42 |
|                 [Latvia](/latvia) |               22 |                        36 |                      19 |                         14 |                                       64% |                                    33 |                                     44 |
|                 [Cyprus](/cyprus) |               17 |                        22 |                      25 |                          5 |                                       29% |                                    21 |                                     24 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    11 |                                     13 |
|                   [Malta](/malta) |                6 |                         9 |                      18 |                          3 |                                       50% |                                     8 |                                      9 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           73,988 |                   435,488 |                      85 |                    361,500 |                                      489% |                               155,494 |                                852,336 |
|                         [Brazil](/brazil) |           21,048 |                   164,798 |                     781 |                    143,750 |                                      683% |                                54,079 |                                285,253 |
|                         [Mexico](/mexico) |            6,989 |                   109,970 |                     862 |                    102,981 |                                     1473% |                                31,659 |                                216,395 |
|                           [India](/india) |            3,726 |                    36,377 |                      27 |                     32,651 |                                      876% |                                 7,960 |                                101,679 |
|                         [Russia](/russia) |            3,249 |                    18,290 |                     125 |                     15,041 |                                      463% |                                 5,708 |                                 49,383 |
|                             [Peru](/peru) |            3,244 |                    13,721 |                     422 |                     10,477 |                                      323% |                                 5,427 |                                 22,065 |
|                             [Iran](/iran) |            7,300 |                    12,126 |                     146 |                      4,826 |                                       66% |                                 8,099 |                                 20,544 |
|                         [Canada](/canada) |            6,360 |                    11,720 |                     313 |                      5,360 |                                       84% |                                 7,768 |                                 20,663 |
|             [South Africa](/south-africa) |              397 |                     9,700 |                     166 |                      9,303 |                                     2343% |                                 3,735 |                                 19,371 |
|                           [Chile](/chile) |              630 |                     8,192 |                     432 |                      7,562 |                                     1200% |                                 3,491 |                                 15,286 |
|                       [Ecuador](/ecuador) |            3,056 |                     6,979 |                     402 |                      3,923 |                                      128% |                                 3,806 |                                 16,824 |
|                     [Pakistan](/pakistan) |            1,067 |                     6,874 |                      32 |                      5,807 |                                      544% |                                 1,877 |                                 16,106 |
|                     [Colombia](/colombia) |              682 |                     5,972 |                     119 |                      5,290 |                                      776% |                                 1,921 |                                 15,573 |
|                         [Turkey](/turkey) |            4,276 |                     5,308 |                      64 |                      1,032 |                                       24% |                                 4,662 |                                  7,064 |
|                           [China](/china) |            4,638 |                     4,646 |                       3 |                          8 |                                        0% |                                 4,638 |                                  4,676 |
|                 [Bangladesh](/bangladesh) |              432 |                     3,212 |                      20 |                      2,780 |                                      644% |                                 1,115 |                                  6,818 |
|                   [Indonesia](/indonesia) |            1,326 |                     3,028 |                      11 |                      1,702 |                                      128% |                                 1,862 |                                  4,828 |
|                           [Egypt](/egypt) |              707 |                     2,717 |                      27 |                      2,010 |                                      284% |                                 1,083 |                                  6,937 |
|                   [Argentina](/argentina) |              433 |                     2,447 |                      55 |                      2,014 |                                      465% |                                   886 |                                  5,317 |
|             [Saudi Arabia](/saudi-arabia) |              364 |                     2,428 |                      71 |                      2,064 |                                      567% |                                 1,028 |                                  4,966 |
|                           [Japan](/japan) |              796 |                     1,530 |                      12 |                        734 |                                       92% |                                   889 |                                  2,482 |
|               [Philippines](/philippines) |              857 |                     1,467 |                      14 |                        610 |                                       71% |                                 1,009 |                                  2,486 |
|                       [Nigeria](/nigeria) |              221 |                       872 |                       4 |                        651 |                                      295% |                                   340 |                                  2,841 |
| [Dominican Republic](/dominican-republic) |              456 |                       737 |                      69 |                        281 |                                       62% |                                   538 |                                  1,176 |
|                       [Algeria](/algeria) |              582 |                       687 |                      16 |                        105 |                                       18% |                                   606 |                                    933 |
|                         [Panama](/panama) |              295 |                       667 |                     157 |                        372 |                                      126% |                                   374 |                                  1,474 |
|                         [Israel](/israel) |              279 |                       342 |                      40 |                         63 |                                       23% |                                   307 |                                    420 |
|               [South Korea](/south-korea) |              266 |                       314 |                       6 |                         48 |                                       18% |                                   281 |                                    368 |
|                       [Morocco](/morocco) |              197 |                       224 |                       6 |                         27 |                                       14% |                                   210 |                                    253 |
|                     [Malaysia](/malaysia) |              115 |                       143 |                       4 |                         28 |                                       24% |                                   136 |                                    155 |
