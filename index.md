We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 60 countries. The countries our projections cover encompass 6.3 billion people and account for over 99% of all global COVID-19 deaths.

Note that our infections estimate includes all infected individuals, not just those that took a COVID-19 test kit and tested positive. The vast majority of infected individuals do not get tested, and thus do not get reported as a positive case. As of mid-May, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 26:** We have extended our projections to September 1, 2020.

* **May 25:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 22:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729), [widespread reopenings](https://www.wsj.com/articles/coronavirus-latest-news-05-20-2020-11589963481), [unreported care home deaths](https://www.economist.com/europe/2020/05/09/many-covid-deaths-in-care-homes-are-unrecorded), [increased efforts for contact tracing](https://www.npr.org/sections/health-shots/2020/04/28/846736937/we-asked-all-50-states-about-their-contact-tracing-capacity-heres-what-we-learne), and [conflated testing numbers](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/).

* **May 20:** We added county-level projections for 14 US counties heavily impacted by COVID-19. This includes cities such as [New York City](/us-ny-new-york-city) (5 boroughs), [Los Angeles](/us-ca-los-angeles), and [Chicago](/us-il-cook). See all 14 counties [here](#us-counties). We also added the 2 Canadian provinces accounting for ~85% of cases in Canada: [Ontario](/canada-ontario) and [Quebec](/canada-quebec).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 27 (4am ET):
<p align="center">
  Current Total: <b>98,910</b> deaths | Projected Total: <b>208,694 deaths by Sep 1, 2020</b> (Range: 124-367k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 73% chance that the US surpasses 125,000 deaths by July 1, with June 22 being the most likely date.

Last updated: May 27, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 27, 2020 |
|              125,000 |        Jun 22, 2020 |
|              150,000 |        Jul 15, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        <1% |         16% |        73% |         89% |        95% |         96% |        97% |
|              150,000 |        <1% |         <1% |        15% |         45% |        65% |         74% |        80% |
|              175,000 |        <1% |         <1% |        <1% |         16% |        40% |         52% |        59% |
|              200,000 |        <1% |         <1% |        <1% |          4% |        22% |         35% |        47% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         5% |         15% |        25% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          4% |        12% |
|              350,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         5% |

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

States are ordered by descending projected deaths (by September 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |           98,910 |                   208,694 |                     629 |                    109,784 |                                      111% |                               124,298 |                                366,884 |
|                 [New York](/us-ny) |           29,302 |                    33,266 |                   1,710 |                      3,964 |                                       14% |                                30,280 |                                 40,683 |
|                 [Illinois](/us-il) |            4,923 |                    17,144 |                   1,353 |                     12,221 |                                      248% |                                 8,627 |                                 26,693 |
|               [New Jersey](/us-nj) |           11,194 |                    15,655 |                   1,763 |                      4,461 |                                       40% |                                12,427 |                                 21,557 |
|               [California](/us-ca) |            3,819 |                    13,343 |                     338 |                      9,524 |                                      249% |                                 5,248 |                                 31,496 |
|             [Pennsylvania](/us-pa) |            5,163 |                    11,467 |                     896 |                      6,304 |                                      122% |                                 6,315 |                                 21,110 |
|            [Massachusetts](/us-ma) |            6,473 |                    10,351 |                   1,489 |                      3,878 |                                       60% |                                 7,418 |                                 16,343 |
|                     [Ohio](/us-oh) |            2,002 |                     8,860 |                     758 |                      6,858 |                                      343% |                                 3,758 |                                 17,093 |
|                  [Florida](/us-fl) |            2,259 |                     7,744 |                     361 |                      5,485 |                                      243% |                                 3,221 |                                 18,496 |
|                    [Texas](/us-tx) |            1,546 |                     6,907 |                     238 |                      5,361 |                                      347% |                                 2,829 |                                 14,525 |
|                 [Michigan](/us-mi) |            5,266 |                     6,894 |                     690 |                      1,628 |                                       31% |                                 5,753 |                                  9,893 |
|                  [Indiana](/us-in) |            2,004 |                     6,822 |                   1,013 |                      4,818 |                                      240% |                                 3,015 |                                 13,243 |
|                 [Maryland](/us-md) |            2,333 |                     6,041 |                     999 |                      3,708 |                                      159% |                                 3,064 |                                 11,473 |
|                  [Georgia](/us-ga) |            1,896 |                     5,787 |                     545 |                      3,891 |                                      205% |                                 2,729 |                                 11,535 |
|              [Connecticut](/us-ct) |            3,769 |                     5,360 |                   1,503 |                      1,591 |                                       42% |                                 4,219 |                                  7,628 |
|                 [Colorado](/us-co) |            1,352 |                     4,512 |                     784 |                      3,160 |                                      234% |                                 2,019 |                                  9,271 |
|                  [Arizona](/us-az) |              810 |                     4,445 |                     611 |                      3,635 |                                      449% |                                 1,723 |                                  8,164 |
|                [Louisiana](/us-la) |            2,702 |                     4,234 |                     911 |                      1,532 |                                       57% |                                 3,073 |                                  7,297 |
|                [Minnesota](/us-mn) |              908 |                     3,971 |                     704 |                      3,063 |                                      337% |                                 1,514 |                                  8,096 |
|                 [Virginia](/us-va) |            1,236 |                     3,961 |                     464 |                      2,725 |                                      220% |                                 1,669 |                                  9,583 |
|                 [Missouri](/us-mo) |              693 |                     3,032 |                     494 |                      2,339 |                                      338% |                                 1,256 |                                  6,245 |
|              [Mississippi](/us-ms) |              652 |                     2,974 |                     999 |                      2,322 |                                      356% |                                 1,208 |                                  5,241 |
|           [North Carolina](/us-nc) |              801 |                     2,632 |                     251 |                      1,831 |                                      229% |                                 1,181 |                                  5,977 |
|                  [Alabama](/us-al) |              580 |                     2,500 |                     510 |                      1,920 |                                      331% |                                 1,101 |                                  4,772 |
|                     [Iowa](/us-ia) |              477 |                     2,109 |                     668 |                      1,632 |                                      342% |                                   869 |                                  3,890 |
|           [South Carolina](/us-sc) |              446 |                     1,859 |                     361 |                      1,413 |                                      317% |                                   710 |                                  4,206 |
|             [Rhode Island](/us-ri) |              634 |                     1,799 |                   1,698 |                      1,165 |                                      184% |                                 1,025 |                                  3,104 |
|               [Washington](/us-wa) |            1,078 |                     1,637 |                     215 |                        559 |                                       52% |                                 1,188 |                                  3,055 |
|               [New Mexico](/us-nm) |              325 |                     1,571 |                     749 |                      1,246 |                                      383% |                                   655 |                                  2,950 |
|            [New Hampshire](/us-nh) |              214 |                     1,203 |                     885 |                        989 |                                      462% |                                   530 |                                  2,066 |
|                [Wisconsin](/us-wi) |              517 |                     1,199 |                     206 |                        682 |                                      132% |                                   687 |                                  2,307 |
|                 [Delaware](/us-de) |              335 |                     1,097 |                   1,127 |                        762 |                                      227% |                                   547 |                                  2,080 |
|                 [Kentucky](/us-ky) |              394 |                     1,078 |                     241 |                        684 |                                      174% |                                   536 |                                  2,501 |
|                   [Nevada](/us-nv) |              394 |                     1,049 |                     341 |                        655 |                                      166% |                                   527 |                                  2,194 |
|                 [Nebraska](/us-ne) |              147 |                       976 |                     505 |                        829 |                                      564% |                                   343 |                                  1,853 |
|                [Tennessee](/us-tn) |              343 |                       846 |                     124 |                        503 |                                      147% |                                   504 |                                  1,824 |
|     [District of Columbia](/us-dc) |              440 |                       843 |                   1,194 |                        403 |                                       92% |                                   534 |                                  1,415 |
|                 [Oklahoma](/us-ok) |              318 |                       601 |                     152 |                        283 |                                       89% |                                   402 |                                  1,115 |
|                     [Utah](/us-ut) |              101 |                       566 |                     177 |                        465 |                                      460% |                                   202 |                                  1,211 |
|                 [Arkansas](/us-ar) |              119 |                       414 |                     137 |                        295 |                                      248% |                                   193 |                                    892 |
|                   [Kansas](/us-ks) |              210 |                       401 |                     138 |                        191 |                                       91% |                                   249 |                                    942 |
|             [South Dakota](/us-sd) |               50 |                       279 |                     315 |                        229 |                                      458% |                                    94 |                                    691 |
|             [North Dakota](/us-nd) |               54 |                       272 |                     357 |                        218 |                                      404% |                                   101 |                                    615 |
|                   [Oregon](/us-or) |              148 |                       237 |                      56 |                         89 |                                       60% |                                   171 |                                    424 |
|              [Puerto Rico](/us-pr) |              129 |                       190 |                      59 |                         61 |                                       47% |                                   150 |                                    285 |
|            [West Virginia](/us-wv) |               72 |                       149 |                      83 |                         77 |                                      107% |                                    94 |                                    315 |
|                    [Maine](/us-me) |               79 |                       128 |                      95 |                         49 |                                       62% |                                   101 |                                    168 |
|                    [Idaho](/us-id) |               79 |                       102 |                      57 |                         23 |                                       29% |                                    89 |                                    131 |
|                  [Vermont](/us-vt) |               54 |                        66 |                     106 |                         12 |                                       22% |                                    60 |                                     73 |
|                  [Wyoming](/us-wy) |               13 |                        44 |                      76 |                         31 |                                      238% |                                    22 |                                     74 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    20 |                                     25 |
|                  [Montana](/us-mt) |               17 |                        22 |                      21 |                          5 |                                       29% |                                    19 |                                     26 |
|                   [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    12 |                                     14 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     8 |                                     10 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          166,950 |                   216,945 |                     366 |                     49,995 |                                       30% |                               178,740 |                                303,654 |
| [United Kingdom](/united-kingdom) |           37,130 |                    53,669 |                     795 |                     16,539 |                                       45% |                                40,912 |                                 78,050 |
|                   [Italy](/italy) |           32,955 |                    39,627 |                     657 |                      6,672 |                                       20% |                                35,089 |                                 48,954 |
|                   [Spain](/spain) |           28,752 |                    32,502 |                     692 |                      3,750 |                                       13% |                                29,596 |                                 39,779 |
|                 [France](/france) |           28,533 |                    32,354 |                     483 |                      3,821 |                                       13% |                                28,916 |                                 44,074 |
|               [Germany](/germany) |            8,372 |                    11,345 |                     137 |                      2,973 |                                       36% |                                 8,875 |                                 19,928 |
|               [Belgium](/belgium) |            9,334 |                    10,448 |                     912 |                      1,114 |                                       12% |                                 9,575 |                                 12,621 |
|       [Netherlands](/netherlands) |            5,875 |                     7,554 |                     437 |                      1,679 |                                       29% |                                 6,255 |                                 10,167 |
|                 [Sweden](/sweden) |            4,125 |                     5,884 |                     575 |                      1,759 |                                       43% |                                 4,699 |                                  7,627 |
|               [Ukraine](/ukraine) |              644 |                     3,886 |                      88 |                      3,242 |                                      503% |                                 1,386 |                                  7,758 |
|               [Romania](/romania) |            1,216 |                     2,817 |                     145 |                      1,601 |                                      132% |                                 1,728 |                                  4,921 |
|                 [Poland](/poland) |            1,024 |                     2,750 |                      72 |                      1,726 |                                      169% |                                 1,314 |                                  6,568 |
|       [Switzerland](/switzerland) |            1,915 |                     2,202 |                     256 |                        287 |                                       15% |                                 1,974 |                                  2,939 |
|             [Portugal](/portugal) |            1,342 |                     2,040 |                     199 |                        698 |                                       52% |                                 1,553 |                                  3,059 |
|               [Ireland](/ireland) |            1,615 |                     1,947 |                     397 |                        332 |                                       21% |                                 1,682 |                                  2,948 |
|               [Moldova](/moldova) |              267 |                     1,611 |                     398 |                      1,344 |                                      503% |                                   657 |                                  3,015 |
|               [Hungary](/hungary) |              499 |                       931 |                      95 |                        432 |                                       87% |                                   578 |                                  2,097 |
|               [Austria](/austria) |              643 |                       747 |                      84 |                        104 |                                       16% |                                   675 |                                    944 |
|               [Denmark](/denmark) |              563 |                       732 |                     126 |                        169 |                                       30% |                                   620 |                                  1,009 |
|               [Belarus](/belarus) |              208 |                       718 |                      76 |                        510 |                                      245% |                                   364 |                                  1,935 |
|             [Bulgaria](/bulgaria) |              130 |                       674 |                      96 |                        544 |                                      418% |                                   253 |                                  1,430 |
|               [Finland](/finland) |              312 |                       488 |                      88 |                        176 |                                       56% |                                   346 |                                    926 |
|               [Czechia](/czechia) |              317 |                       390 |                      37 |                         73 |                                       23% |                                   355 |                                    454 |
|                 [Serbia](/serbia) |              239 |                       383 |                      55 |                        144 |                                       60% |                                   285 |                                    748 |
|                 [Norway](/norway) |              235 |                       273 |                      51 |                         38 |                                       16% |                                   247 |                                    319 |
|                 [Greece](/greece) |              173 |                       223 |                      21 |                         50 |                                       29% |                                   193 |                                    313 |
|               [Croatia](/croatia) |              101 |                       187 |                      46 |                         86 |                                       85% |                                   124 |                                    364 |
|             [Slovenia](/slovenia) |              108 |                       133 |                      64 |                         25 |                                       23% |                                   115 |                                    191 |
|         [Luxembourg](/luxembourg) |              110 |                       129 |                     210 |                         19 |                                       17% |                                   116 |                                    152 |
|           [Lithuania](/lithuania) |               65 |                       106 |                      38 |                         41 |                                       63% |                                    80 |                                    145 |
|               [Estonia](/estonia) |               65 |                        85 |                      64 |                         20 |                                       31% |                                    78 |                                     95 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    30 |                                     44 |
|                 [Latvia](/latvia) |               22 |                        33 |                      17 |                         11 |                                       50% |                                    31 |                                     35 |
|                 [Cyprus](/cyprus) |               17 |                        22 |                      25 |                          5 |                                       29% |                                    20 |                                     24 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |
|                   [Malta](/malta) |                6 |                         8 |                      16 |                          2 |                                       33% |                                     8 |                                      9 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           83,337 |                   552,074 |                     106 |                    468,737 |                                      562% |                               179,993 |                              1,136,844 |
|                             [Brazil](/brazil) |           24,512 |                   184,112 |                     872 |                    159,600 |                                      651% |                                51,675 |                                455,294 |
|                             [Mexico](/mexico) |            8,134 |                   132,501 |                   1,039 |                    124,367 |                                     1529% |                                37,471 |                                212,130 |
|                               [India](/india) |            4,344 |                    55,948 |                      41 |                     51,604 |                                     1188% |                                10,654 |                                118,604 |
|                                 [Peru](/peru) |            3,788 |                    28,994 |                     892 |                     25,206 |                                      665% |                                 8,704 |                                 51,196 |
|                             [Russia](/russia) |            3,807 |                    21,764 |                     149 |                     17,957 |                                      472% |                                 6,301 |                                 53,705 |
|                 [South Africa](/south-africa) |              524 |                    18,074 |                     309 |                     17,550 |                                     3349% |                                 8,398 |                                 29,913 |
|                             [Canada](/canada) |            6,753 |                    12,766 |                     341 |                      6,013 |                                       89% |                                 7,998 |                                 26,748 |
|                                 [Iran](/iran) |            7,508 |                    12,619 |                     152 |                      5,111 |                                       68% |                                 8,469 |                                 22,535 |
|                               [Chile](/chile) |              806 |                    11,815 |                     623 |                     11,009 |                                     1366% |                                 5,735 |                                 18,851 |
|                         [Pakistan](/pakistan) |            1,197 |                     9,011 |                      42 |                      7,814 |                                      653% |                                 2,362 |                                 20,800 |
|                         [Colombia](/colombia) |              776 |                     8,637 |                     172 |                      7,861 |                                     1013% |                                 3,167 |                                 17,381 |
|                           [Ecuador](/ecuador) |            3,203 |                     7,656 |                     441 |                      4,453 |                                      139% |                                 4,031 |                                 18,656 |
|                     [Bangladesh](/bangladesh) |              522 |                     7,194 |                      44 |                      6,672 |                                     1278% |                                 2,226 |                                 13,187 |
|                             [Turkey](/turkey) |            4,397 |                     5,536 |                      66 |                      1,139 |                                       26% |                                 4,671 |                                  8,140 |
|                       [Indonesia](/indonesia) |            1,418 |                     4,771 |                      18 |                      3,353 |                                      236% |                                 2,091 |                                 11,997 |
|                               [Egypt](/egypt) |              797 |                     4,685 |                      47 |                      3,888 |                                      488% |                                 1,464 |                                 10,616 |
|                               [China](/china) |            4,638 |                     4,654 |                       3 |                         16 |                                        0% |                                 4,638 |                                  4,752 |
|                       [Argentina](/argentina) |              484 |                     3,808 |                      85 |                      3,324 |                                      687% |                                 1,197 |                                  7,450 |
|                 [Saudi Arabia](/saudi-arabia) |              411 |                     3,447 |                     101 |                      3,036 |                                      739% |                                 1,191 |                                  6,682 |
|                           [Bolivia](/bolivia) |              274 |                     2,281 |                     198 |                      2,007 |                                      732% |                                   926 |                                  4,258 |
|                   [Philippines](/philippines) |              886 |                     1,571 |                      15 |                        685 |                                       77% |                                 1,022 |                                  2,804 |
|                           [Nigeria](/nigeria) |              249 |                     1,559 |                       8 |                      1,310 |                                      526% |                                   448 |                                  4,519 |
|                             [Kuwait](/kuwait) |              172 |                     1,535 |                     365 |                      1,363 |                                      792% |                                   651 |                                  2,787 |
|                         [Honduras](/honduras) |              188 |                     1,177 |                     121 |                        989 |                                      526% |                                   456 |                                  2,606 |
|                               [Japan](/japan) |              846 |                     1,153 |                       9 |                        307 |                                       36% |                                   865 |                                  1,640 |
|                           [Algeria](/algeria) |              617 |                       989 |                      23 |                        372 |                                       60% |                                   724 |                                  1,966 |
|                             [Panama](/panama) |              313 |                       940 |                     221 |                        627 |                                      200% |                                   424 |                                  2,353 |
|     [Dominican Republic](/dominican-republic) |              468 |                       929 |                      87 |                        461 |                                       99% |                                   573 |                                  1,869 |
| [United Arab Emirates](/united-arab-emirates) |              253 |                       663 |                      68 |                        410 |                                      162% |                                   333 |                                  1,743 |
|                             [Israel](/israel) |              281 |                       349 |                      41 |                         68 |                                       24% |                                   306 |                                    468 |
|                   [South Korea](/south-korea) |              269 |                       325 |                       6 |                         56 |                                       21% |                                   277 |                                    443 |
|                           [Morocco](/morocco) |              202 |                       240 |                       7 |                         38 |                                       19% |                                   218 |                                    293 |
|                         [Malaysia](/malaysia) |              115 |                       148 |                       5 |                         33 |                                       29% |                                   130 |                                    175 |
|                       [Australia](/australia) |              103 |                       114 |                       5 |                         11 |                                       11% |                                   105 |                                    142 |
|                                 [Cuba](/cuba) |               82 |                       109 |                      10 |                         27 |                                       33% |                                    92 |                                    141 |
