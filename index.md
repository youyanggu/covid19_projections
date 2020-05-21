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

## Current Projection for US - Updated Daily - Last Updated: May 21 (3am ET):
<p align="center">
  Current Total: <b>93,436</b> deaths | Projected Total: <b>190,358</b> deaths by Aug 4, 2020 (Range: 120-322k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>3.6%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 43% chance that the US surpasses 125,000 deaths by June 15, with June 16 being the most likely date.

Last updated: May 21, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 26, 2020 |
|              125,000 |        Jun 16, 2020 |
|              150,000 |         Jul 6, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |        99% |        >99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         43% |        84% |         93% |        96% |
|              150,000 |        <1% |         <1% |        33% |         60% |        75% |
|              175,000 |        <1% |         <1% |         8% |         30% |        51% |
|              200,000 |        <1% |         <1% |        <1% |         13% |        32% |
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
|         *[United States](/us)* |           93,436 |                   190,358 |                     574 |                     96,922 |                                      104% |                               123,006 |                                320,329 |
|             [New York](/us-ny) |           28,636 |                    33,416 |                   1,718 |                      4,780 |                                       17% |                                30,265 |                                 41,182 |
|             [Illinois](/us-il) |            4,525 |                    17,182 |                   1,356 |                     12,657 |                                      280% |                                 9,686 |                                 28,355 |
|           [New Jersey](/us-nj) |           10,749 |                    16,138 |                   1,817 |                      5,389 |                                       50% |                                12,363 |                                 23,140 |
|         [Pennsylvania](/us-pa) |            4,770 |                    11,683 |                     913 |                      6,913 |                                      145% |                                 6,751 |                                 19,832 |
|           [California](/us-ca) |            3,497 |                    10,635 |                     269 |                      7,138 |                                      204% |                                 4,831 |                                 24,015 |
|        [Massachusetts](/us-ma) |            6,066 |                    10,084 |                   1,451 |                      4,018 |                                       66% |                                 7,294 |                                 16,200 |
|                 [Ohio](/us-oh) |            1,781 |                     7,100 |                     607 |                      5,319 |                                      299% |                                 3,225 |                                 15,211 |
|             [Michigan](/us-mi) |            5,060 |                     6,778 |                     679 |                      1,718 |                                       34% |                                 5,719 |                                  9,171 |
|              [Indiana](/us-in) |            1,864 |                     6,199 |                     921 |                      4,335 |                                      233% |                                 2,961 |                                 11,981 |
|                [Texas](/us-tx) |            1,426 |                     5,993 |                     207 |                      4,567 |                                      320% |                                 2,779 |                                 11,568 |
|             [Maryland](/us-md) |            2,123 |                     5,460 |                     903 |                      3,337 |                                      157% |                                 2,879 |                                 10,661 |
|              [Florida](/us-fl) |            2,096 |                     5,456 |                     254 |                      3,360 |                                      160% |                                 2,790 |                                 11,226 |
|          [Connecticut](/us-ct) |            3,529 |                     5,248 |                   1,472 |                      1,719 |                                       49% |                                 4,092 |                                  7,665 |
|              [Arizona](/us-az) |              747 |                     4,484 |                     616 |                      3,737 |                                      500% |                                 2,097 |                                  8,368 |
|             [Colorado](/us-co) |            1,299 |                     4,077 |                     708 |                      2,778 |                                      214% |                                 2,154 |                                  7,520 |
|            [Louisiana](/us-la) |            2,608 |                     3,954 |                     851 |                      1,346 |                                       52% |                                 3,103 |                                  5,689 |
|              [Georgia](/us-ga) |            1,697 |                     3,838 |                     361 |                      2,141 |                                      126% |                                 2,230 |                                  7,137 |
|            [Minnesota](/us-mn) |              786 |                     3,079 |                     546 |                      2,293 |                                      292% |                                 1,306 |                                  6,929 |
|             [Virginia](/us-va) |            1,075 |                     2,972 |                     348 |                      1,897 |                                      176% |                                 1,468 |                                  7,093 |
|          [Mississippi](/us-ms) |              570 |                     2,853 |                     959 |                      2,283 |                                      401% |                                 1,314 |                                  5,260 |
|             [Missouri](/us-mo) |              640 |                     2,349 |                     383 |                      1,709 |                                      267% |                                 1,147 |                                  4,574 |
|                 [Iowa](/us-ia) |              393 |                     2,230 |                     707 |                      1,837 |                                      467% |                                 1,142 |                                  3,641 |
|              [Alabama](/us-al) |              522 |                     2,045 |                     417 |                      1,523 |                                      292% |                                 1,043 |                                  3,802 |
|       [North Carolina](/us-nc) |              726 |                     1,877 |                     179 |                      1,151 |                                      159% |                                 1,070 |                                  3,564 |
|           [Washington](/us-wa) |            1,037 |                     1,448 |                     190 |                        411 |                                       40% |                                 1,164 |                                  2,117 |
|       [South Carolina](/us-sc) |              407 |                     1,436 |                     279 |                      1,029 |                                      253% |                                   662 |                                  2,887 |
|         [Rhode Island](/us-ri) |              538 |                     1,306 |                   1,233 |                        768 |                                      143% |                                   826 |                                  2,199 |
|           [New Mexico](/us-nm) |              283 |                     1,264 |                     603 |                        981 |                                      347% |                                   559 |                                  2,568 |
|             [Delaware](/us-de) |              310 |                     1,217 |                   1,250 |                        907 |                                      293% |                                   648 |                                  2,261 |
| [District of Columbia](/us-dc) |              407 |                       926 |                   1,312 |                        519 |                                      128% |                                   570 |                                  1,540 |
|            [Wisconsin](/us-wi) |              481 |                       915 |                     157 |                        434 |                                       90% |                                   655 |                                  1,500 |
|               [Nevada](/us-nv) |              377 |                       907 |                     294 |                        530 |                                      141% |                                   570 |                                  1,604 |
|             [Kentucky](/us-ky) |              376 |                       871 |                     195 |                        495 |                                      132% |                                   534 |                                  1,601 |
|        [New Hampshire](/us-nh) |              190 |                       813 |                     598 |                        623 |                                      328% |                                   439 |                                  1,362 |
|             [Nebraska](/us-ne) |              138 |                       723 |                     374 |                        585 |                                      424% |                                   343 |                                  1,323 |
|            [Tennessee](/us-tn) |              305 |                       615 |                      90 |                        310 |                                      102% |                                   434 |                                    984 |
|             [Oklahoma](/us-ok) |              299 |                       473 |                     120 |                        174 |                                       58% |                                   368 |                                    670 |
|                 [Utah](/us-ut) |               90 |                       389 |                     121 |                        299 |                                      332% |                                   178 |                                    773 |
|               [Kansas](/us-ks) |              202 |                       340 |                     117 |                        138 |                                       68% |                                   233 |                                    622 |
|         [North Dakota](/us-nd) |               49 |                       238 |                     312 |                        189 |                                      386% |                                   113 |                                    483 |
|               [Oregon](/us-or) |              144 |                       221 |                      52 |                         77 |                                       53% |                                   172 |                                    324 |
|             [Arkansas](/us-ar) |              107 |                       221 |                      73 |                        114 |                                      107% |                                   162 |                                    356 |
|         [South Dakota](/us-sd) |               46 |                       194 |                     219 |                        148 |                                      322% |                                    86 |                                    413 |
|          [Puerto Rico](/us-pr) |              125 |                       181 |                      57 |                         56 |                                       45% |                                   151 |                                    244 |
|        [West Virginia](/us-wv) |               69 |                       130 |                      73 |                         61 |                                       88% |                                    93 |                                    217 |
|                [Maine](/us-me) |               73 |                       113 |                      84 |                         40 |                                       55% |                                    93 |                                    149 |
|                [Idaho](/us-id) |               77 |                       105 |                      59 |                         28 |                                       36% |                                    90 |                                    120 |
|              [Vermont](/us-vt) |               54 |                        70 |                     112 |                         16 |                                       30% |                                    63 |                                     76 |
|               [Hawaii](/us-hi) |               17 |                        26 |                      18 |                          9 |                                       53% |                                    21 |                                     30 |
|              [Wyoming](/us-wy) |               11 |                        26 |                      45 |                         15 |                                      136% |                                    17 |                                     50 |
|              [Montana](/us-mt) |               16 |                        22 |                      21 |                          6 |                                       38% |                                    19 |                                     26 |
|               [Alaska](/us-ak) |               10 |                        13 |                      18 |                          3 |                                       30% |                                    12 |                                     15 |
|       [Virgin Islands](/us-vi) |                6 |                        10 |                      95 |                          4 |                                       67% |                                     9 |                                     11 |
|                 [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     8 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          162,190 |                   209,866 |                     358 |                     47,676 |                                       29% |                               177,035 |                                283,002 |
| [United Kingdom](/united-kingdom) |           35,786 |                    50,480 |                     748 |                     14,694 |                                       41% |                                40,502 |                                 70,794 |
|                   [Italy](/italy) |           32,330 |                    38,743 |                     642 |                      6,413 |                                       20% |                                34,690 |                                 47,263 |
|                 [France](/france) |           28,135 |                    31,809 |                     475 |                      3,674 |                                       13% |                                28,573 |                                 43,225 |
|                   [Spain](/spain) |           27,888 |                    31,643 |                     674 |                      3,755 |                                       13% |                                29,100 |                                 37,720 |
|               [Germany](/germany) |            8,144 |                    10,652 |                     128 |                      2,508 |                                       31% |                                 8,811 |                                 15,764 |
|               [Belgium](/belgium) |            9,150 |                    10,374 |                     906 |                      1,224 |                                       13% |                                 9,455 |                                 12,592 |
|       [Netherlands](/netherlands) |            5,767 |                     7,387 |                     427 |                      1,620 |                                       28% |                                 6,211 |                                  9,838 |
|                 [Sweden](/sweden) |            3,831 |                     6,510 |                     636 |                      2,679 |                                       70% |                                 5,023 |                                 10,012 |
|               [Ukraine](/ukraine) |              564 |                     5,190 |                     118 |                      4,626 |                                      820% |                                 1,816 |                                  9,687 |
|               [Romania](/romania) |            1,147 |                     2,626 |                     135 |                      1,479 |                                      129% |                                 1,792 |                                  4,283 |
|                 [Poland](/poland) |              962 |                     2,244 |                      59 |                      1,282 |                                      133% |                                 1,265 |                                  4,403 |
|       [Switzerland](/switzerland) |            1,892 |                     2,183 |                     254 |                        291 |                                       15% |                                 1,976 |                                  2,708 |
|               [Ireland](/ireland) |            1,571 |                     1,931 |                     394 |                        360 |                                       23% |                                 1,664 |                                  2,740 |
|             [Portugal](/portugal) |            1,263 |                     1,851 |                     180 |                        588 |                                       47% |                                 1,505 |                                  2,596 |
|               [Moldova](/moldova) |              228 |                     1,120 |                     277 |                        892 |                                      391% |                                   503 |                                  2,188 |
|               [Austria](/austria) |              633 |                       762 |                      86 |                        129 |                                       20% |                                   684 |                                    907 |
|               [Hungary](/hungary) |              470 |                       758 |                      78 |                        288 |                                       61% |                                   543 |                                  1,268 |
|               [Denmark](/denmark) |              554 |                       727 |                     125 |                        173 |                                       31% |                                   631 |                                    906 |
|               [Finland](/finland) |              304 |                       504 |                      91 |                        200 |                                       66% |                                   360 |                                    845 |
|               [Czechia](/czechia) |              304 |                       397 |                      37 |                         93 |                                       31% |                                   358 |                                    445 |
|             [Bulgaria](/bulgaria) |              116 |                       385 |                      55 |                        269 |                                      232% |                                   220 |                                    732 |
|                 [Serbia](/serbia) |              235 |                       377 |                      43 |                        142 |                                       60% |                                   301 |                                    613 |
|                 [Norway](/norway) |              234 |                       279 |                      52 |                         45 |                                       19% |                                   250 |                                    320 |
|                 [Greece](/greece) |              166 |                       214 |                      20 |                         48 |                                       29% |                                   190 |                                    251 |
|               [Croatia](/croatia) |               96 |                       163 |                      40 |                         67 |                                       70% |                                   117 |                                    258 |
|         [Luxembourg](/luxembourg) |              109 |                       134 |                     218 |                         25 |                                       23% |                                   121 |                                    150 |
|             [Slovenia](/slovenia) |              105 |                       129 |                      62 |                         24 |                                       23% |                                   113 |                                    156 |
|               [Estonia](/estonia) |               64 |                        90 |                      68 |                         26 |                                       41% |                                    80 |                                    101 |
|           [Lithuania](/lithuania) |               60 |                        86 |                      31 |                         26 |                                       43% |                                    75 |                                    100 |
|             [Slovakia](/slovakia) |               28 |                        37 |                       7 |                          9 |                                       32% |                                    31 |                                     44 |
|                 [Latvia](/latvia) |               21 |                        37 |                      19 |                         16 |                                       76% |                                    33 |                                     45 |
|                 [Cyprus](/cyprus) |               17 |                        23 |                      26 |                          6 |                                       35% |                                    22 |                                     25 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    12 |                                     13 |
|                   [Malta](/malta) |                6 |                         9 |                      18 |                          3 |                                       50% |                                     8 |                                     10 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           68,970 |                   366,717 |                      72 |                    297,747 |                                      432% |                               134,003 |                                751,174 |
|                         [Brazil](/brazil) |           18,859 |                   132,207 |                     626 |                    113,348 |                                      601% |                                44,366 |                                244,646 |
|                         [Mexico](/mexico) |            6,090 |                    85,358 |                     669 |                     79,268 |                                     1302% |                                24,020 |                                168,004 |
|                           [India](/india) |            3,434 |                    34,155 |                      25 |                     30,721 |                                      895% |                                 7,960 |                                 97,748 |
|                         [Russia](/russia) |            2,972 |                    17,036 |                     117 |                     14,064 |                                      473% |                                 4,924 |                                 53,719 |
|                         [Canada](/canada) |            6,150 |                    13,744 |                     367 |                      7,594 |                                      123% |                                 8,540 |                                 25,969 |
|                             [Iran](/iran) |            7,183 |                    12,302 |                     148 |                      5,119 |                                       71% |                                 8,179 |                                 22,411 |
|                             [Peru](/peru) |            3,024 |                    11,370 |                     350 |                      8,346 |                                      276% |                                 4,476 |                                 18,050 |
|                       [Ecuador](/ecuador) |            2,888 |                     6,641 |                     382 |                      3,753 |                                      130% |                                 3,700 |                                 14,403 |
|             [South Africa](/south-africa) |              339 |                     6,085 |                     104 |                      5,746 |                                     1695% |                                 2,124 |                                 12,403 |
|                           [Chile](/chile) |              544 |                     5,625 |                     297 |                      5,081 |                                      934% |                                 2,569 |                                 10,488 |
|                         [Turkey](/turkey) |            4,222 |                     5,483 |                      66 |                      1,261 |                                       30% |                                 4,691 |                                  7,745 |
|                     [Pakistan](/pakistan) |              985 |                     5,332 |                      25 |                      4,347 |                                      441% |                                 1,473 |                                 12,343 |
|                     [Colombia](/colombia) |              630 |                     4,825 |                      96 |                      4,195 |                                      666% |                                 1,890 |                                 10,859 |
|                           [China](/china) |            4,638 |                     4,649 |                       3 |                         11 |                                        0% |                                 4,638 |                                  4,679 |
|                 [Bangladesh](/bangladesh) |              386 |                     3,633 |                      22 |                      3,247 |                                      841% |                                 1,179 |                                  8,042 |
|                           [Egypt](/egypt) |              680 |                     3,367 |                      34 |                      2,687 |                                      395% |                                 1,148 |                                  9,982 |
|                   [Indonesia](/indonesia) |            1,242 |                     3,069 |                      11 |                      1,827 |                                      147% |                                 1,742 |                                  5,675 |
|             [Saudi Arabia](/saudi-arabia) |              339 |                     2,335 |                      68 |                      1,996 |                                      589% |                                   914 |                                  4,478 |
|                   [Argentina](/argentina) |              403 |                     2,268 |                      51 |                      1,865 |                                      463% |                                   800 |                                  6,435 |
|                           [Japan](/japan) |              768 |                     1,760 |                      14 |                        992 |                                      129% |                                   898 |                                  3,195 |
|               [Philippines](/philippines) |              842 |                     1,635 |                      15 |                        793 |                                       94% |                                 1,033 |                                  2,977 |
| [Dominican Republic](/dominican-republic) |              446 |                       758 |                      71 |                        312 |                                       70% |                                   538 |                                  1,299 |
|                         [Panama](/panama) |              287 |                       729 |                     172 |                        442 |                                      154% |                                   381 |                                  1,677 |
|                       [Algeria](/algeria) |              568 |                       679 |                      16 |                        111 |                                       20% |                                   597 |                                    895 |
|                       [Nigeria](/nigeria) |              200 |                       623 |                       3 |                        423 |                                      212% |                                   288 |                                  1,785 |
|                         [Israel](/israel) |              279 |                       359 |                      42 |                         80 |                                       29% |                                   313 |                                    462 |
|               [South Korea](/south-korea) |              264 |                       320 |                       6 |                         56 |                                       21% |                                   283 |                                    393 |
|                       [Morocco](/morocco) |              194 |                       224 |                       6 |                         30 |                                       15% |                                   208 |                                    250 |
|                     [Malaysia](/malaysia) |              114 |                       146 |                       5 |                         32 |                                       28% |                                   131 |                                    162 |
