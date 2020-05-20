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

## Current Projection for US - Updated Daily - Last Updated: May 20 (8am ET):
<p align="center">
  Current Total: <b>91,918</b> deaths | Projected Total: <b>188,544</b> deaths by Aug 4, 2020 (Range: 120-322k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>3.6%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 41% chance that the US surpasses 125,000 deaths by June 15, with June 16 being the most likely date.

Last updated: May 20, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              100,000 |        May 26, 2020 |
|              125,000 |        Jun 17, 2020 |
|              150,000 |         Jul 7, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              100,000 |        99% |         99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         41% |        81% |         91% |        95% |
|              150,000 |        <1% |          1% |        32% |         57% |        72% |
|              175,000 |        <1% |         <1% |         9% |         29% |        49% |
|              200,000 |        <1% |         <1% |        <1% |         13% |        31% |
|              250,000 |        <1% |         <1% |        <1% |          2% |        11% |
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
|         *[United States](/us)* |           91,918 |                   188,544 |                     568 |                     96,626 |                                      105% |                               120,183 |                                321,784 |
|             [New York](/us-ny) |           28,558 |                    33,693 |                   1,732 |                      5,135 |                                       18% |                                30,328 |                                 41,951 |
|             [Illinois](/us-il) |            4,379 |                    16,680 |                   1,316 |                     12,301 |                                      281% |                                 8,971 |                                 28,463 |
|           [New Jersey](/us-nj) |           10,587 |                    16,186 |                   1,822 |                      5,599 |                                       53% |                                12,224 |                                 23,372 |
|         [Pennsylvania](/us-pa) |            4,628 |                    11,471 |                     896 |                      6,843 |                                      148% |                                 6,487 |                                 19,792 |
|           [California](/us-ca) |            3,403 |                     9,994 |                     253 |                      6,591 |                                      194% |                                 4,604 |                                 22,641 |
|        [Massachusetts](/us-ma) |            5,938 |                     9,991 |                   1,438 |                      4,053 |                                       68% |                                 7,163 |                                 16,348 |
|             [Michigan](/us-mi) |            5,017 |                     6,828 |                     684 |                      1,811 |                                       36% |                                 5,699 |                                  9,448 |
|                 [Ohio](/us-oh) |            1,720 |                     6,403 |                     548 |                      4,683 |                                      272% |                                 3,002 |                                 13,232 |
|              [Indiana](/us-in) |            1,824 |                     6,354 |                     944 |                      4,530 |                                      248% |                                 2,931 |                                 12,486 |
|                [Texas](/us-tx) |            1,388 |                     6,165 |                     213 |                      4,777 |                                      344% |                                 2,663 |                                 12,438 |
|             [Maryland](/us-md) |            2,081 |                     5,497 |                     909 |                      3,416 |                                      164% |                                 2,816 |                                 10,766 |
|              [Florida](/us-fl) |            2,052 |                     5,373 |                     250 |                      3,321 |                                      162% |                                 2,705 |                                 11,246 |
|          [Connecticut](/us-ct) |            3,472 |                     5,192 |                   1,456 |                      1,720 |                                       50% |                                 4,025 |                                  7,820 |
|              [Arizona](/us-az) |              705 |                     4,173 |                     573 |                      3,468 |                                      492% |                                 1,882 |                                  8,053 |
|              [Georgia](/us-ga) |            1,675 |                     3,987 |                     376 |                      2,312 |                                      138% |                                 2,228 |                                  7,422 |
|            [Louisiana](/us-la) |            2,581 |                     3,961 |                     852 |                      1,380 |                                       53% |                                 3,081 |                                  5,768 |
|             [Colorado](/us-co) |            1,257 |                     3,891 |                     676 |                      2,634 |                                      210% |                                 2,029 |                                  7,406 |
|            [Minnesota](/us-mn) |              757 |                     2,954 |                     524 |                      2,197 |                                      290% |                                 1,178 |                                  6,936 |
|             [Virginia](/us-va) |            1,042 |                     2,954 |                     346 |                      1,912 |                                      183% |                                 1,419 |                                  7,323 |
|          [Mississippi](/us-ms) |              554 |                     2,864 |                     962 |                      2,310 |                                      417% |                                 1,292 |                                  5,297 |
|             [Missouri](/us-mo) |              631 |                     2,457 |                     400 |                      1,826 |                                      289% |                                 1,166 |                                  4,762 |
|                 [Iowa](/us-ia) |              367 |                     2,406 |                     763 |                      2,039 |                                      556% |                                 1,144 |                                  4,323 |
|              [Alabama](/us-al) |              504 |                     2,056 |                     419 |                      1,552 |                                      308% |                                 1,018 |                                  3,887 |
|       [North Carolina](/us-nc) |              693 |                     1,632 |                     156 |                        939 |                                      135% |                                   950 |                                  3,257 |
|       [South Carolina](/us-sc) |              399 |                     1,527 |                     297 |                      1,128 |                                      283% |                                   662 |                                  3,199 |
|           [Washington](/us-wa) |            1,031 |                     1,466 |                     193 |                        435 |                                       42% |                                 1,164 |                                  2,190 |
|         [Rhode Island](/us-ri) |              532 |                     1,440 |                   1,359 |                        908 |                                      171% |                                   854 |                                  2,562 |
|           [New Mexico](/us-nm) |              276 |                     1,388 |                     662 |                      1,112 |                                      403% |                                   601 |                                  2,760 |
|             [Delaware](/us-de) |              304 |                     1,290 |                   1,325 |                        986 |                                      324% |                                   672 |                                  2,350 |
|        [New Hampshire](/us-nh) |              172 |                     1,004 |                     738 |                        832 |                                      484% |                                   466 |                                  1,885 |
| [District of Columbia](/us-dc) |              400 |                       945 |                   1,339 |                        545 |                                      136% |                                   568 |                                  1,563 |
|            [Wisconsin](/us-wi) |              467 |                       865 |                     149 |                        398 |                                       85% |                                   634 |                                  1,335 |
|             [Kentucky](/us-ky) |              366 |                       839 |                     188 |                        473 |                                      129% |                                   510 |                                  1,569 |
|               [Nevada](/us-nv) |              358 |                       759 |                     246 |                        401 |                                      112% |                                   497 |                                  1,316 |
|            [Tennessee](/us-tn) |              305 |                       650 |                      95 |                        345 |                                      113% |                                   443 |                                  1,143 |
|             [Oklahoma](/us-ok) |              293 |                       467 |                     118 |                        174 |                                       59% |                                   358 |                                    665 |
|             [Nebraska](/us-ne) |              123 |                       445 |                     230 |                        322 |                                      262% |                                   248 |                                    859 |
|                 [Utah](/us-ut) |               88 |                       409 |                     128 |                        321 |                                      365% |                                   181 |                                    860 |
|               [Kansas](/us-ks) |              199 |                       344 |                     118 |                        145 |                                       73% |                                   230 |                                    654 |
|         [South Dakota](/us-sd) |               46 |                       224 |                     253 |                        178 |                                      387% |                                    98 |                                    471 |
|               [Oregon](/us-or) |              140 |                       213 |                      51 |                         73 |                                       52% |                                   165 |                                    312 |
|             [Arkansas](/us-ar) |              102 |                       203 |                      67 |                        101 |                                       99% |                                   157 |                                    311 |
|         [North Dakota](/us-nd) |               45 |                       197 |                     259 |                        152 |                                      338% |                                    91 |                                    402 |
|          [Puerto Rico](/us-pr) |              124 |                       185 |                      58 |                         61 |                                       49% |                                   151 |                                    255 |
|        [West Virginia](/us-wv) |               68 |                       129 |                      72 |                         61 |                                       90% |                                    93 |                                    216 |
|                [Maine](/us-me) |               73 |                       117 |                      87 |                         44 |                                       60% |                                    95 |                                    153 |
|                [Idaho](/us-id) |               74 |                       100 |                      56 |                         26 |                                       35% |                                    86 |                                    114 |
|              [Vermont](/us-vt) |               54 |                        70 |                     112 |                         16 |                                       30% |                                    64 |                                     77 |
|               [Hawaii](/us-hi) |               17 |                        26 |                      18 |                          9 |                                       53% |                                    21 |                                     31 |
|              [Montana](/us-mt) |               16 |                        22 |                      21 |                          6 |                                       38% |                                    19 |                                     26 |
|              [Wyoming](/us-wy) |               10 |                        18 |                      31 |                          8 |                                       80% |                                    16 |                                     23 |
|               [Alaska](/us-ak) |               10 |                        14 |                      19 |                          4 |                                       40% |                                    12 |                                     15 |
|       [Virgin Islands](/us-vi) |                6 |                        10 |                      95 |                          4 |                                       67% |                                     9 |                                     11 |
|                 [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     8 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          161,125 |                   213,080 |                     364 |                     51,955 |                                       32% |                               177,480 |                                295,688 |
| [United Kingdom](/united-kingdom) |           35,422 |                    50,637 |                     750 |                     15,215 |                                       43% |                                39,993 |                                 72,288 |
|                   [Italy](/italy) |           32,169 |                    38,870 |                     644 |                      6,701 |                                       21% |                                34,637 |                                 47,821 |
|                 [France](/france) |           28,025 |                    31,865 |                     476 |                      3,840 |                                       14% |                                28,481 |                                 43,863 |
|                   [Spain](/spain) |           27,778 |                    31,710 |                     676 |                      3,932 |                                       14% |                                29,002 |                                 38,123 |
|               [Germany](/germany) |            8,081 |                    10,691 |                     129 |                      2,610 |                                       32% |                                 8,761 |                                 16,126 |
|               [Belgium](/belgium) |            9,108 |                    10,384 |                     906 |                      1,276 |                                       14% |                                 9,421 |                                 12,708 |
|       [Netherlands](/netherlands) |            5,734 |                     7,439 |                     430 |                      1,705 |                                       30% |                                 6,198 |                                 10,031 |
|                 [Sweden](/sweden) |            3,743 |                     7,141 |                     698 |                      3,398 |                                       91% |                                 5,677 |                                 10,313 |
|               [Ukraine](/ukraine) |              548 |                     6,923 |                     157 |                      6,375 |                                     1163% |                                 2,437 |                                 16,726 |
|               [Romania](/romania) |            1,137 |                     2,794 |                     144 |                      1,657 |                                      146% |                                 1,838 |                                  5,013 |
|                 [Poland](/poland) |              948 |                     2,324 |                      61 |                      1,376 |                                      145% |                                 1,258 |                                  4,718 |
|       [Switzerland](/switzerland) |            1,891 |                     2,200 |                     256 |                        309 |                                       16% |                                 1,980 |                                  2,766 |
|               [Ireland](/ireland) |            1,561 |                     1,940 |                     396 |                        379 |                                       24% |                                 1,660 |                                  2,794 |
|             [Portugal](/portugal) |            1,247 |                     1,851 |                     180 |                        604 |                                       48% |                                 1,494 |                                  2,648 |
|               [Moldova](/moldova) |              221 |                     1,135 |                     281 |                        914 |                                      414% |                                   498 |                                  2,295 |
|               [Hungary](/hungary) |              467 |                       791 |                      81 |                        324 |                                       69% |                                   545 |                                  1,461 |
|               [Austria](/austria) |              632 |                       767 |                      87 |                        135 |                                       21% |                                   685 |                                    923 |
|               [Denmark](/denmark) |              551 |                       733 |                     126 |                        182 |                                       33% |                                   630 |                                    965 |
|               [Finland](/finland) |              301 |                       514 |                      93 |                        213 |                                       71% |                                   359 |                                    877 |
|               [Czechia](/czechia) |              302 |                       399 |                      37 |                         97 |                                       32% |                                   358 |                                    449 |
|                 [Serbia](/serbia) |              234 |                       386 |                      44 |                        152 |                                       65% |                                   305 |                                    633 |
|             [Bulgaria](/bulgaria) |              112 |                       360 |                      51 |                        248 |                                      221% |                                   207 |                                    643 |
|                 [Norway](/norway) |              233 |                       280 |                      52 |                         47 |                                       20% |                                   250 |                                    323 |
|                 [Greece](/greece) |              165 |                       214 |                      20 |                         49 |                                       30% |                                   189 |                                    254 |
|               [Croatia](/croatia) |               96 |                       170 |                      42 |                         74 |                                       77% |                                   119 |                                    272 |
|         [Luxembourg](/luxembourg) |              109 |                       135 |                     220 |                         26 |                                       24% |                                   122 |                                    155 |
|             [Slovenia](/slovenia) |              104 |                       129 |                      62 |                         25 |                                       24% |                                   112 |                                    156 |
|               [Estonia](/estonia) |               64 |                        91 |                      69 |                         27 |                                       42% |                                    81 |                                    102 |
|           [Lithuania](/lithuania) |               60 |                        88 |                      31 |                         28 |                                       47% |                                    76 |                                    102 |
|                 [Latvia](/latvia) |               21 |                        38 |                      20 |                         17 |                                       81% |                                    34 |                                     46 |
|             [Slovakia](/slovakia) |               28 |                        37 |                       7 |                          9 |                                       32% |                                    31 |                                     44 |
|                 [Cyprus](/cyprus) |               17 |                        23 |                      26 |                          6 |                                       35% |                                    22 |                                     26 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                                       20% |                                    12 |                                     14 |
|                   [Malta](/malta) |                6 |                         9 |                      18 |                          3 |                                       50% |                                     8 |                                     10 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           66,798 |                   396,793 |                      78 |                    329,995 |                                      494% |                               125,208 |                                925,540 |
|                         [Brazil](/brazil) |           17,983 |                   159,245 |                     755 |                    141,262 |                                      786% |                                43,839 |                                349,975 |
|                         [Mexico](/mexico) |            5,666 |                    73,910 |                     579 |                     68,244 |                                     1204% |                                15,557 |                                161,489 |
|                           [India](/india) |            3,302 |                    44,662 |                      33 |                     41,360 |                                     1253% |                                 8,060 |                                159,009 |
|                         [Russia](/russia) |            2,837 |                    16,643 |                     114 |                     13,806 |                                      487% |                                 4,787 |                                 55,856 |
|                         [Canada](/canada) |            6,028 |                    14,044 |                     375 |                      8,016 |                                      133% |                                 8,506 |                                 26,578 |
|                             [Iran](/iran) |            7,119 |                    13,174 |                     159 |                      6,055 |                                       85% |                                 8,201 |                                 23,566 |
|                             [Peru](/peru) |            2,914 |                    11,030 |                     339 |                      8,116 |                                      279% |                                 4,295 |                                 18,197 |
|             [South Africa](/south-africa) |              312 |                     8,654 |                     148 |                      8,342 |                                     2674% |                                 2,843 |                                 18,553 |
|                       [Ecuador](/ecuador) |            2,839 |                     6,923 |                     398 |                      4,084 |                                      144% |                                 3,718 |                                 14,865 |
|                           [Chile](/chile) |              509 |                     5,616 |                     296 |                      5,107 |                                     1003% |                                 2,493 |                                 10,601 |
|                         [Turkey](/turkey) |            4,199 |                     5,535 |                      66 |                      1,336 |                                       32% |                                 4,698 |                                  7,892 |
|                     [Colombia](/colombia) |              613 |                     5,233 |                     104 |                      4,620 |                                      754% |                                 1,942 |                                 11,866 |
|                     [Pakistan](/pakistan) |              939 |                     4,948 |                      23 |                      4,009 |                                      427% |                                 1,404 |                                 12,611 |
|                           [China](/china) |            4,638 |                     4,649 |                       3 |                         11 |                                        0% |                                 4,638 |                                  4,681 |
|                 [Bangladesh](/bangladesh) |              370 |                     3,735 |                      23 |                      3,365 |                                      909% |                                 1,025 |                                  8,539 |
|                           [Egypt](/egypt) |              659 |                     3,539 |                      35 |                      2,880 |                                      437% |                                 1,135 |                                 10,859 |
|                   [Indonesia](/indonesia) |            1,221 |                     3,080 |                      11 |                      1,859 |                                      152% |                                 1,690 |                                  5,728 |
|             [Saudi Arabia](/saudi-arabia) |              329 |                     2,455 |                      72 |                      2,126 |                                      646% |                                   927 |                                  4,777 |
|                   [Argentina](/argentina) |              393 |                     2,316 |                      52 |                      1,923 |                                      489% |                                   785 |                                  6,528 |
|                           [Japan](/japan) |              768 |                     1,830 |                      14 |                      1,062 |                                      138% |                                   910 |                                  3,282 |
|               [Philippines](/philippines) |              837 |                     1,717 |                      16 |                        880 |                                      105% |                                 1,039 |                                  3,273 |
| [Dominican Republic](/dominican-republic) |              441 |                       772 |                      72 |                        331 |                                       75% |                                   536 |                                  1,360 |
|                         [Panama](/panama) |              281 |                       723 |                     170 |                        442 |                                      157% |                                   372 |                                  1,602 |
|                       [Algeria](/algeria) |              561 |                       674 |                      16 |                        113 |                                       20% |                                   590 |                                    897 |
|                       [Nigeria](/nigeria) |              192 |                       630 |                       3 |                        438 |                                      228% |                                   281 |                                  1,668 |
|                         [Israel](/israel) |              278 |                       363 |                      43 |                         85 |                                       31% |                                   314 |                                    474 |
|               [South Korea](/south-korea) |              263 |                       322 |                       6 |                         59 |                                       22% |                                   283 |                                    400 |
|                       [Morocco](/morocco) |              193 |                       224 |                       6 |                         31 |                                       16% |                                   208 |                                    250 |
|                     [Malaysia](/malaysia) |              114 |                       147 |                       5 |                         33 |                                       29% |                                   132 |                                    164 |
