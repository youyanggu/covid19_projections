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

## Current Projection for US - Updated Daily - Last Updated: May 26 (4am ET):
<p align="center">
  Current Total: <b>98,217</b> deaths | Projected Total: <b>212,222 deaths by Sep 1, 2020</b> (Range: 126-372k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 76% chance that the US surpasses 125,000 deaths by July 1, with June 21 being the most likely date.

Last updated: May 26, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 27, 2020 |
|              125,000 |        Jun 21, 2020 |
|              150,000 |        Jul 13, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              100,000 |       >99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         20% |        76% |         90% |        96% |         97% |        98% |
|              150,000 |        <1% |         <1% |        17% |         49% |        68% |         76% |        81% |
|              175,000 |        <1% |         <1% |        <1% |         18% |        43% |         55% |        62% |
|              200,000 |        <1% |         <1% |        <1% |          5% |        24% |         37% |        49% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         6% |         16% |        27% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          5% |        13% |
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
|             *[United States](/us)* |           98,217 |                   212,222 |                     640 |                    114,005 |                                      116% |                               126,296 |                                371,176 |
|                 [New York](/us-ny) |           29,229 |                    33,342 |                   1,714 |                      4,113 |                                       14% |                                30,277 |                                 41,028 |
|                 [Illinois](/us-il) |            4,885 |                    17,530 |                   1,383 |                     12,645 |                                      259% |                                 9,447 |                                 26,857 |
|               [New Jersey](/us-nj) |           11,147 |                    15,781 |                   1,777 |                      4,634 |                                       42% |                                12,459 |                                 21,745 |
|               [California](/us-ca) |            3,769 |                    13,691 |                     347 |                      9,922 |                                      263% |                                 5,258 |                                 31,712 |
|             [Pennsylvania](/us-pa) |            5,146 |                    11,720 |                     915 |                      6,574 |                                      128% |                                 6,409 |                                 21,368 |
|            [Massachusetts](/us-ma) |            6,416 |                    10,386 |                   1,494 |                      3,970 |                                       62% |                                 7,390 |                                 16,442 |
|                     [Ohio](/us-oh) |            1,987 |                     9,031 |                     773 |                      7,044 |                                      355% |                                 3,812 |                                 17,188 |
|                  [Florida](/us-fl) |            2,252 |                     7,957 |                     370 |                      5,705 |                                      253% |                                 3,270 |                                 18,711 |
|                    [Texas](/us-tx) |            1,533 |                     7,086 |                     244 |                      5,553 |                                      362% |                                 2,858 |                                 15,134 |
|                  [Indiana](/us-in) |            1,984 |                     7,003 |                   1,040 |                      5,019 |                                      253% |                                 3,076 |                                 13,466 |
|                 [Michigan](/us-mi) |            5,241 |                     6,938 |                     695 |                      1,697 |                                       32% |                                 5,759 |                                  9,969 |
|                 [Maryland](/us-md) |            2,302 |                     6,069 |                   1,004 |                      3,767 |                                      164% |                                 3,058 |                                 11,507 |
|                  [Georgia](/us-ga) |            1,848 |                     5,793 |                     546 |                      3,945 |                                      213% |                                 2,695 |                                 11,550 |
|              [Connecticut](/us-ct) |            3,742 |                     5,370 |                   1,506 |                      1,628 |                                       44% |                                 4,215 |                                  7,664 |
|                  [Arizona](/us-az) |              807 |                     5,049 |                     694 |                      4,242 |                                      526% |                                 2,141 |                                  9,102 |
|                 [Colorado](/us-co) |            1,333 |                     4,617 |                     802 |                      3,284 |                                      246% |                                 2,033 |                                  9,439 |
|                [Louisiana](/us-la) |            2,691 |                     4,237 |                     911 |                      1,546 |                                       57% |                                 3,074 |                                  7,323 |
|                [Minnesota](/us-mn) |              890 |                     4,016 |                     712 |                      3,126 |                                      351% |                                 1,518 |                                  8,130 |
|                 [Virginia](/us-va) |            1,208 |                     3,918 |                     459 |                      2,710 |                                      224% |                                 1,645 |                                  9,573 |
|              [Mississippi](/us-ms) |              635 |                     3,204 |                   1,077 |                      2,569 |                                      405% |                                 1,433 |                                  5,467 |
|                 [Missouri](/us-mo) |              689 |                     3,108 |                     506 |                      2,419 |                                      351% |                                 1,291 |                                  6,526 |
|           [North Carolina](/us-nc) |              790 |                     2,685 |                     256 |                      1,895 |                                      240% |                                 1,189 |                                  6,002 |
|                     [Iowa](/us-ia) |              456 |                     2,561 |                     812 |                      2,105 |                                      462% |                                 1,062 |                                  4,242 |
|                  [Alabama](/us-al) |              566 |                     2,487 |                     507 |                      1,921 |                                      339% |                                 1,052 |                                  4,768 |
|           [South Carolina](/us-sc) |              440 |                     1,887 |                     366 |                      1,447 |                                      329% |                                   712 |                                  4,269 |
|             [Rhode Island](/us-ri) |              608 |                     1,718 |                   1,622 |                      1,110 |                                      183% |                                   992 |                                  2,975 |
|               [Washington](/us-wa) |            1,070 |                     1,628 |                     214 |                        558 |                                       52% |                                 1,180 |                                  3,057 |
|               [New Mexico](/us-nm) |              320 |                     1,587 |                     757 |                      1,267 |                                      396% |                                   658 |                                  2,964 |
|            [New Hampshire](/us-nh) |              210 |                     1,214 |                     893 |                      1,004 |                                      478% |                                   535 |                                  2,093 |
|                [Wisconsin](/us-wi) |              514 |                     1,212 |                     208 |                        698 |                                      136% |                                   691 |                                  2,421 |
|                 [Delaware](/us-de) |              332 |                     1,113 |                   1,143 |                        781 |                                      235% |                                   552 |                                  2,102 |
|                 [Kentucky](/us-ky) |              391 |                     1,077 |                     241 |                        686 |                                      175% |                                   555 |                                  2,250 |
|                   [Nevada](/us-nv) |              394 |                     1,073 |                     348 |                        679 |                                      172% |                                   570 |                                  2,250 |
|                 [Nebraska](/us-ne) |              147 |                       891 |                     461 |                        744 |                                      506% |                                   359 |                                  1,713 |
|     [District of Columbia](/us-dc) |              440 |                       859 |                   1,217 |                        419 |                                       95% |                                   541 |                                  1,433 |
|                [Tennessee](/us-tn) |              338 |                       847 |                     124 |                        509 |                                      151% |                                   502 |                                  1,826 |
|                 [Oklahoma](/us-ok) |              313 |                       597 |                     151 |                        284 |                                       91% |                                   398 |                                  1,112 |
|                     [Utah](/us-ut) |               98 |                       571 |                     178 |                        473 |                                      483% |                                   201 |                                  1,214 |
|                   [Kansas](/us-ks) |              207 |                       420 |                     144 |                        213 |                                      103% |                                   242 |                                  1,056 |
|                 [Arkansas](/us-ar) |              117 |                       332 |                     110 |                        215 |                                      184% |                                   198 |                                    665 |
|             [South Dakota](/us-sd) |               50 |                       319 |                     361 |                        269 |                                      538% |                                   112 |                                    675 |
|             [North Dakota](/us-nd) |               54 |                       297 |                     390 |                        243 |                                      450% |                                   118 |                                    625 |
|                   [Oregon](/us-or) |              148 |                       241 |                      57 |                         93 |                                       63% |                                   172 |                                    431 |
|              [Puerto Rico](/us-pr) |              129 |                       192 |                      60 |                         63 |                                       49% |                                   151 |                                    287 |
|            [West Virginia](/us-wv) |               72 |                       152 |                      85 |                         80 |                                      111% |                                    95 |                                    322 |
|                    [Maine](/us-me) |               78 |                       128 |                      95 |                         50 |                                       64% |                                   100 |                                    168 |
|                    [Idaho](/us-id) |               79 |                       103 |                      58 |                         24 |                                       30% |                                    92 |                                    120 |
|                  [Vermont](/us-vt) |               54 |                        66 |                     106 |                         12 |                                       22% |                                    60 |                                     73 |
|                  [Wyoming](/us-wy) |               12 |                        42 |                      73 |                         30 |                                      250% |                                    21 |                                     73 |
|                   [Hawaii](/us-hi) |               17 |                        24 |                      17 |                          7 |                                       41% |                                    20 |                                     26 |
|                  [Montana](/us-mt) |               16 |                        20 |                      19 |                          4 |                                       25% |                                    18 |                                     25 |
|                   [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    12 |                                     14 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     8 |                                     10 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     4 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          166,203 |                   216,932 |                     372 |                     50,729 |                                       31% |                               178,176 |                                303,280 |
| [United Kingdom](/united-kingdom) |           36,996 |                    54,082 |                     801 |                     17,086 |                                       46% |                                40,982 |                                 78,755 |
|                   [Italy](/italy) |           32,877 |                    39,732 |                     658 |                      6,855 |                                       21% |                                35,060 |                                 49,082 |
|                   [Spain](/spain) |           28,802 |                    32,692 |                     697 |                      3,890 |                                       14% |                                29,715 |                                 39,990 |
|                 [France](/france) |           28,460 |                    32,417 |                     484 |                      3,957 |                                       14% |                                28,871 |                                 44,392 |
|               [Germany](/germany) |            8,309 |                    11,346 |                     137 |                      3,037 |                                       37% |                                 8,819 |                                 20,028 |
|               [Belgium](/belgium) |            9,312 |                    10,470 |                     914 |                      1,158 |                                       12% |                                 9,561 |                                 12,691 |
|       [Netherlands](/netherlands) |            5,849 |                     7,596 |                     440 |                      1,747 |                                       30% |                                 6,247 |                                 10,271 |
|                 [Sweden](/sweden) |            4,029 |                     5,716 |                     559 |                      1,687 |                                       42% |                                 4,533 |                                  7,557 |
|               [Ukraine](/ukraine) |              623 |                     3,819 |                      87 |                      3,196 |                                      513% |                                 1,289 |                                  7,780 |
|               [Romania](/romania) |            1,205 |                     2,929 |                     151 |                      1,724 |                                      143% |                                 1,790 |                                  4,995 |
|                 [Poland](/poland) |            1,007 |                     2,779 |                      73 |                      1,772 |                                      176% |                                 1,298 |                                  6,741 |
|       [Switzerland](/switzerland) |            1,913 |                     2,210 |                     257 |                        297 |                                       16% |                                 1,975 |                                  2,957 |
|             [Portugal](/portugal) |            1,330 |                     2,027 |                     197 |                        697 |                                       52% |                                 1,541 |                                  3,059 |
|               [Ireland](/ireland) |            1,606 |                     1,950 |                     398 |                        344 |                                       21% |                                 1,677 |                                  2,972 |
|               [Moldova](/moldova) |              261 |                     1,557 |                     385 |                      1,296 |                                      497% |                                   638 |                                  2,889 |
|               [Hungary](/hungary) |              491 |                       911 |                      93 |                        420 |                                       86% |                                   568 |                                  1,824 |
|               [Austria](/austria) |              641 |                       749 |                      85 |                        108 |                                       17% |                                   674 |                                    950 |
|               [Denmark](/denmark) |              563 |                       741 |                     128 |                        178 |                                       32% |                                   622 |                                  1,024 |
|             [Bulgaria](/bulgaria) |              130 |                       694 |                      99 |                        564 |                                      434% |                                   273 |                                  1,465 |
|               [Finland](/finland) |              308 |                       488 |                      88 |                        180 |                                       58% |                                   343 |                                    960 |
|                 [Serbia](/serbia) |              239 |                       396 |                      57 |                        157 |                                       66% |                                   288 |                                    760 |
|               [Czechia](/czechia) |              317 |                       393 |                      37 |                         76 |                                       24% |                                   357 |                                    462 |
|                 [Norway](/norway) |              235 |                       274 |                      51 |                         39 |                                       17% |                                   247 |                                    321 |
|                 [Greece](/greece) |              172 |                       222 |                      21 |                         50 |                                       29% |                                   193 |                                    313 |
|               [Croatia](/croatia) |              100 |                       189 |                      46 |                         89 |                                       89% |                                   123 |                                    365 |
|         [Luxembourg](/luxembourg) |              110 |                       133 |                     217 |                         23 |                                       21% |                                   119 |                                    160 |
|             [Slovenia](/slovenia) |              107 |                       130 |                      62 |                         23 |                                       21% |                                   114 |                                    168 |
|           [Lithuania](/lithuania) |               63 |                        95 |                      34 |                         32 |                                       51% |                                    80 |                                    129 |
|               [Estonia](/estonia) |               65 |                        85 |                      64 |                         20 |                                       31% |                                    79 |                                     95 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    30 |                                     44 |
|                 [Latvia](/latvia) |               22 |                        33 |                      17 |                         11 |                                       50% |                                    31 |                                     36 |
|                 [Cyprus](/cyprus) |               17 |                        22 |                      25 |                          5 |                                       29% |                                    20 |                                     24 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |
|                   [Malta](/malta) |                6 |                         8 |                      16 |                          2 |                                       33% |                                     8 |                                      9 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           79,736 |                   536,543 |                     105 |                    456,807 |                                      573% |                               166,419 |                              1,142,497 |
|                         [Brazil](/brazil) |           23,473 |                   187,940 |                     891 |                    164,467 |                                      701% |                                49,443 |                                463,687 |
|                         [Mexico](/mexico) |            7,633 |                   121,461 |                     952 |                    113,828 |                                     1491% |                                32,200 |                                210,855 |
|                           [India](/india) |            4,172 |                    52,729 |                      39 |                     48,557 |                                     1164% |                                 9,829 |                                118,364 |
|                             [Peru](/peru) |            3,629 |                    27,487 |                     845 |                     23,858 |                                      657% |                                 7,986 |                                 51,142 |
|                         [Russia](/russia) |            3,633 |                    25,478 |                     175 |                     21,845 |                                      601% |                                 6,644 |                                 63,070 |
|             [South Africa](/south-africa) |              481 |                    16,390 |                     280 |                     15,909 |                                     3307% |                                 6,999 |                                 28,059 |
|                         [Canada](/canada) |            6,655 |                    12,991 |                     347 |                      6,336 |                                       95% |                                 7,933 |                                 27,283 |
|                             [Iran](/iran) |            7,451 |                    12,823 |                     155 |                      5,372 |                                       72% |                                 8,436 |                                 23,026 |
|                           [Chile](/chile) |              761 |                    11,303 |                     596 |                     10,542 |                                     1385% |                                 5,421 |                                 18,090 |
|                     [Pakistan](/pakistan) |            1,167 |                     9,355 |                      43 |                      8,188 |                                      702% |                                 2,333 |                                 21,017 |
|                     [Colombia](/colombia) |              750 |                     8,440 |                     168 |                      7,690 |                                     1025% |                                 3,037 |                                 17,324 |
|                       [Ecuador](/ecuador) |            3,203 |                     8,342 |                     480 |                      5,139 |                                      160% |                                 4,124 |                                 21,595 |
|                 [Bangladesh](/bangladesh) |              501 |                     6,945 |                      43 |                      6,444 |                                     1286% |                                 2,050 |                                 13,128 |
|                         [Turkey](/turkey) |            4,369 |                     5,544 |                      66 |                      1,175 |                                       27% |                                 4,655 |                                  8,222 |
|                   [Indonesia](/indonesia) |            1,391 |                     4,843 |                      18 |                      3,452 |                                      248% |                                 2,070 |                                 12,111 |
|                           [Egypt](/egypt) |              783 |                     4,744 |                      47 |                      3,961 |                                      506% |                                 1,463 |                                 10,704 |
|                           [China](/china) |            4,638 |                     4,654 |                       3 |                         16 |                                        0% |                                 4,638 |                                  4,755 |
|                   [Argentina](/argentina) |              467 |                     3,759 |                      84 |                      3,292 |                                      705% |                                 1,141 |                                  7,524 |
|             [Saudi Arabia](/saudi-arabia) |              399 |                     3,444 |                     101 |                      3,045 |                                      763% |                                 1,174 |                                  6,723 |
|               [Philippines](/philippines) |              873 |                     1,575 |                      15 |                        702 |                                       80% |                                 1,002 |                                  2,881 |
|                       [Nigeria](/nigeria) |              233 |                     1,425 |                       7 |                      1,192 |                                      512% |                                   421 |                                  4,426 |
|                           [Japan](/japan) |              830 |                     1,139 |                       9 |                        309 |                                       37% |                                   849 |                                  1,624 |
|                         [Panama](/panama) |              310 |                       959 |                     226 |                        649 |                                      209% |                                   423 |                                  2,367 |
| [Dominican Republic](/dominican-republic) |              460 |                       922 |                      86 |                        462 |                                      100% |                                   565 |                                  1,869 |
|                       [Algeria](/algeria) |              609 |                       788 |                      18 |                        179 |                                       29% |                                   640 |                                  1,293 |
|                         [Israel](/israel) |              281 |                       354 |                      42 |                         73 |                                       26% |                                   309 |                                    473 |
|               [South Korea](/south-korea) |              269 |                       339 |                       7 |                         70 |                                       26% |                                   289 |                                    465 |
|                       [Morocco](/morocco) |              200 |                       229 |                       6 |                         29 |                                       14% |                                   212 |                                    266 |
|                     [Malaysia](/malaysia) |              115 |                       141 |                       4 |                         26 |                                       23% |                                   133 |                                    154 |
