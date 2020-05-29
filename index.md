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

* **May 29:** We ran a simulation on what would happen if just 20% of infected individuals reduced their own transmission by 25% (such as by self-quarantining immediately after showing symptoms). US deaths would be 30% lower by May 29, and up to 50% lower by September. See the results [here](/us-self-quarantine).

* **May 27:** We added [7 new countries](/#global-projections) (Australia, Belarus, Bolivia, Cuba, Honduras, Kuwait, UAE), [2 Canadian provinces](/#global-projections) (Alberta and British Columbia), and [20 US counties](/#us-counties). We now have projections for 71 countries (>99% of all global COVID-19 deaths), 4 Canadian provinces (99% of Canadian COVID-19 deaths), 56 US states and territories, and 34 US counties (including the top 30 most populous counties).

* **May 26:** We have extended our projections to September 1, 2020.

* **May 25:** See how our models have performed historically compared to other CDC models [here](/about/#historical-performance).

* **May 22:** We have updated our projections after an analysis of recent studies showing [promising treatment results](https://www.nejm.org/doi/full/10.1056/NEJMoa2007764), [possible seasonality effects](https://projects.iq.harvard.edu/covid19), [high mask-wearing compliance](https://www.usatoday.com/story/news/politics/2020/05/21/coronavirus-wearing-mask-public-common-nationscape-survey-finds/5215365002/), [slow reopenings](https://twitter.com/youyanggu/status/1263283908914761729), [widespread reopenings](https://www.wsj.com/articles/coronavirus-latest-news-05-20-2020-11589963481), [unreported care home deaths](https://www.economist.com/europe/2020/05/09/many-covid-deaths-in-care-homes-are-unrecorded), [increased efforts for contact tracing](https://www.npr.org/sections/health-shots/2020/04/28/846736937/we-asked-all-50-states-about-their-contact-tracing-capacity-heres-what-we-learne), and [conflated testing numbers](https://www.theatlantic.com/health/archive/2020/05/cdc-and-states-are-misreporting-covid-19-test-data-pennsylvania-georgia-texas/611935/).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 29 (3am ET):
<p align="center">
  Current Total: <b>101,613</b> deaths | Projected Total: <b>201,847 deaths by Sep 1, 2020</b> (Range: 125-346k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>4.0%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 74% chance that the US surpasses 125,000 deaths by July 1, with June 22 being the most likely date.

Last updated: May 29, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              125,000 |        Jun 22, 2020 |
|              150,000 |        Jul 17, 2020 |
|              175,000 |         Aug 8, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         12% |        74% |         90% |        95% |         97% |        98% |
|              150,000 |         <1% |        10% |         41% |        63% |         72% |        77% |
|              175,000 |         <1% |        <1% |         11% |        35% |         49% |        57% |
|              200,000 |         <1% |        <1% |          1% |        18% |         32% |        42% |
|              250,000 |         <1% |        <1% |         <1% |         2% |         11% |        22% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |          2% |         9% |
|              350,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |

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
|             *[United States](/us)* |          101,613 |                   201,847 |                     608 |                    100,234 |                                       99% |                               125,907 |                                345,214 |
|                 [New York](/us-ny) |           29,529 |                    33,246 |                   1,709 |                      3,717 |                                       13% |                                30,401 |                                 40,172 |
|               [New Jersey](/us-nj) |           11,409 |                    15,351 |                   1,728 |                      3,942 |                                       35% |                                12,498 |                                 21,259 |
|                 [Illinois](/us-il) |            5,186 |                    13,670 |                   1,079 |                      8,484 |                                      164% |                                 8,197 |                                 19,843 |
|               [California](/us-ca) |            3,993 |                    12,596 |                     319 |                      8,603 |                                      215% |                                 5,404 |                                 29,274 |
|             [Pennsylvania](/us-pa) |            5,373 |                    11,061 |                     864 |                      5,688 |                                      106% |                                 6,471 |                                 20,771 |
|            [Massachusetts](/us-ma) |            6,640 |                    10,226 |                   1,471 |                      3,586 |                                       54% |                                 7,544 |                                 15,900 |
|                     [Ohio](/us-oh) |            2,098 |                     8,362 |                     715 |                      6,264 |                                      299% |                                 3,806 |                                 16,253 |
|                  [Florida](/us-fl) |            2,364 |                     7,406 |                     345 |                      5,042 |                                      213% |                                 3,295 |                                 15,753 |
|                 [Michigan](/us-mi) |            5,372 |                     6,910 |                     692 |                      1,538 |                                       29% |                                 5,839 |                                  9,845 |
|                 [Maryland](/us-md) |            2,428 |                     6,083 |                   1,006 |                      3,655 |                                      151% |                                 3,180 |                                 11,429 |
|                  [Georgia](/us-ga) |            1,973 |                     6,026 |                     568 |                      4,053 |                                      205% |                                 2,828 |                                 11,345 |
|                    [Texas](/us-tx) |            1,611 |                     5,902 |                     204 |                      4,291 |                                      266% |                                 2,715 |                                 12,844 |
|                  [Indiana](/us-in) |            2,068 |                     5,818 |                     864 |                      3,750 |                                      181% |                                 2,929 |                                 10,796 |
|              [Connecticut](/us-ct) |            3,826 |                     5,234 |                   1,468 |                      1,408 |                                       37% |                                 4,234 |                                  7,221 |
|                 [Virginia](/us-va) |            1,338 |                     5,031 |                     589 |                      3,693 |                                      276% |                                 2,015 |                                 10,195 |
|                [Minnesota](/us-mn) |              977 |                     4,370 |                     775 |                      3,393 |                                      347% |                                 1,757 |                                  8,289 |
|                  [Arizona](/us-az) |              860 |                     4,345 |                     597 |                      3,485 |                                      405% |                                 1,738 |                                  7,997 |
|                 [Colorado](/us-co) |            1,421 |                     4,198 |                     729 |                      2,777 |                                      195% |                                 2,064 |                                  7,897 |
|                [Louisiana](/us-la) |            2,741 |                     4,051 |                     871 |                      1,310 |                                       48% |                                 3,071 |                                  6,001 |
|           [North Carolina](/us-nc) |              876 |                     3,424 |                     326 |                      2,548 |                                      291% |                                 1,453 |                                  7,837 |
|              [Mississippi](/us-ms) |              693 |                     3,081 |                   1,035 |                      2,388 |                                      345% |                                 1,341 |                                  5,262 |
|                 [Missouri](/us-mo) |              708 |                     2,300 |                     375 |                      1,592 |                                      225% |                                 1,100 |                                  4,933 |
|                  [Alabama](/us-al) |              591 |                     2,285 |                     466 |                      1,694 |                                      287% |                                 1,021 |                                  4,551 |
|                     [Iowa](/us-ia) |              506 |                     2,184 |                     692 |                      1,678 |                                      332% |                                   901 |                                  3,904 |
|           [South Carolina](/us-sc) |              470 |                     1,945 |                     378 |                      1,475 |                                      314% |                                   772 |                                  4,206 |
|             [Rhode Island](/us-ri) |              677 |                     1,816 |                   1,714 |                      1,139 |                                      168% |                                 1,133 |                                  2,685 |
|               [Washington](/us-wa) |            1,106 |                     1,711 |                     225 |                        605 |                                       55% |                                 1,224 |                                  3,106 |
|                [Wisconsin](/us-wi) |              550 |                     1,366 |                     235 |                        816 |                                      148% |                                   772 |                                  2,830 |
|               [New Mexico](/us-nm) |              335 |                     1,349 |                     643 |                      1,014 |                                      303% |                                   603 |                                  2,757 |
|            [New Hampshire](/us-nh) |              232 |                     1,222 |                     899 |                        990 |                                      427% |                                   548 |                                  2,072 |
|                [Tennessee](/us-tn) |              356 |                     1,099 |                     161 |                        743 |                                      209% |                                   504 |                                  2,400 |
|                 [Nebraska](/us-ne) |              163 |                     1,037 |                     536 |                        874 |                                      536% |                                   395 |                                  1,848 |
|                   [Nevada](/us-nv) |              406 |                     1,008 |                     327 |                        602 |                                      148% |                                   539 |                                  1,993 |
|                 [Kentucky](/us-ky) |              409 |                     1,002 |                     224 |                        593 |                                      145% |                                   537 |                                  2,206 |
|                 [Delaware](/us-de) |              345 |                       911 |                     936 |                        566 |                                      164% |                                   509 |                                  1,594 |
|     [District of Columbia](/us-dc) |              453 |                       806 |                   1,142 |                        353 |                                       78% |                                   538 |                                  1,386 |
|                 [Oklahoma](/us-ok) |              325 |                       590 |                     149 |                        265 |                                       82% |                                   406 |                                  1,101 |
|                     [Utah](/us-ut) |              106 |                       495 |                     154 |                        389 |                                      367% |                                   204 |                                  1,056 |
|                 [Arkansas](/us-ar) |              125 |                       435 |                     144 |                        310 |                                      248% |                                   199 |                                    908 |
|                   [Kansas](/us-ks) |              214 |                       386 |                     132 |                        172 |                                       80% |                                   252 |                                    868 |
|             [South Dakota](/us-sd) |               54 |                       259 |                     293 |                        205 |                                      380% |                                    92 |                                    568 |
|             [North Dakota](/us-nd) |               57 |                       244 |                     320 |                        187 |                                      328% |                                   100 |                                    530 |
|                   [Oregon](/us-or) |              151 |                       234 |                      55 |                         83 |                                       55% |                                   171 |                                    413 |
|              [Puerto Rico](/us-pr) |              131 |                       188 |                      59 |                         57 |                                       44% |                                   151 |                                    279 |
|                    [Maine](/us-me) |               84 |                       136 |                     101 |                         52 |                                       62% |                                   106 |                                    195 |
|            [West Virginia](/us-wv) |               74 |                       135 |                      75 |                         61 |                                       82% |                                    94 |                                    237 |
|                    [Idaho](/us-id) |               82 |                       106 |                      59 |                         24 |                                       29% |                                    92 |                                    133 |
|                  [Vermont](/us-vt) |               55 |                        66 |                     106 |                         11 |                                       20% |                                    61 |                                     73 |
|                  [Wyoming](/us-wy) |               15 |                        66 |                     114 |                         51 |                                      340% |                                    36 |                                    111 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    20 |                                     25 |
|                  [Montana](/us-mt) |               17 |                        21 |                      20 |                          4 |                                       24% |                                    19 |                                     26 |
|                   [Alaska](/us-ak) |               10 |                        12 |                      16 |                          2 |                                       20% |                                    11 |                                     14 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     8 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-09-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          168,597 |                   214,715 |                     362 |                     46,118 |                                       27% |                               178,638 |                                294,182 |
| [United Kingdom](/united-kingdom) |           37,919 |                    54,238 |                     803 |                     16,319 |                                       43% |                                42,278 |                                 76,311 |
|                   [Italy](/italy) |           33,142 |                    39,334 |                     652 |                      6,192 |                                       19% |                                35,166 |                                 47,410 |
|                 [France](/france) |           28,665 |                    32,066 |                     479 |                      3,401 |                                       12% |                                28,978 |                                 42,534 |
|                   [Spain](/spain) |           28,752 |                    30,319 |                     646 |                      1,567 |                                        5% |                                27,633 |                                 37,636 |
|               [Germany](/germany) |            8,470 |                    11,366 |                     137 |                      2,896 |                                       34% |                                 8,961 |                                 19,404 |
|               [Belgium](/belgium) |            9,388 |                    10,444 |                     912 |                      1,056 |                                       11% |                                 9,607 |                                 12,567 |
|       [Netherlands](/netherlands) |            5,922 |                     7,542 |                     436 |                      1,620 |                                       27% |                                 6,280 |                                 10,083 |
|                 [Sweden](/sweden) |            4,266 |                     6,144 |                     601 |                      1,878 |                                       44% |                                 4,860 |                                  7,717 |
|               [Ukraine](/ukraine) |              669 |                     3,798 |                      86 |                      3,129 |                                      468% |                                 1,352 |                                  7,556 |
|               [Romania](/romania) |            1,235 |                     2,708 |                     139 |                      1,473 |                                      119% |                                 1,707 |                                  4,857 |
|                 [Poland](/poland) |            1,038 |                     2,592 |                      68 |                      1,554 |                                      150% |                                 1,308 |                                  5,508 |
|       [Switzerland](/switzerland) |            1,919 |                     2,189 |                     255 |                        270 |                                       14% |                                 1,974 |                                  2,908 |
|             [Portugal](/portugal) |            1,369 |                     2,067 |                     201 |                        698 |                                       51% |                                 1,571 |                                  3,066 |
|               [Ireland](/ireland) |            1,639 |                     1,968 |                     401 |                        329 |                                       20% |                                 1,702 |                                  2,946 |
|               [Moldova](/moldova) |              282 |                     1,655 |                     409 |                      1,373 |                                      487% |                                   683 |                                  3,041 |
|               [Hungary](/hungary) |              509 |                       930 |                      95 |                        421 |                                       83% |                                   586 |                                  1,785 |
|               [Austria](/austria) |              668 |                       783 |                      88 |                        115 |                                       17% |                                   701 |                                  1,026 |
|               [Denmark](/denmark) |              568 |                       729 |                     126 |                        161 |                                       28% |                                   622 |                                    953 |
|               [Belarus](/belarus) |              219 |                       722 |                      76 |                        503 |                                      230% |                                   372 |                                  1,927 |
|             [Bulgaria](/bulgaria) |              134 |                       642 |                      92 |                        508 |                                      379% |                                   252 |                                  1,358 |
|               [Finland](/finland) |              313 |                       473 |                      86 |                        160 |                                       51% |                                   345 |                                    846 |
|               [Czechia](/czechia) |              319 |                       388 |                      36 |                         69 |                                       22% |                                   354 |                                    442 |
|                 [Serbia](/serbia) |              241 |                       371 |                      53 |                        130 |                                       54% |                                   284 |                                    602 |
|                 [Norway](/norway) |              236 |                       272 |                      51 |                         36 |                                       15% |                                   247 |                                    317 |
|                 [Greece](/greece) |              175 |                       223 |                      21 |                         48 |                                       27% |                                   195 |                                    313 |
|               [Croatia](/croatia) |              102 |                       185 |                      45 |                         83 |                                       81% |                                   124 |                                    360 |
|             [Slovenia](/slovenia) |              108 |                       131 |                      63 |                         23 |                                       21% |                                   114 |                                    188 |
|         [Luxembourg](/luxembourg) |              110 |                       128 |                     209 |                         18 |                                       16% |                                   116 |                                    151 |
|           [Lithuania](/lithuania) |               68 |                       109 |                      39 |                         41 |                                       60% |                                    84 |                                    147 |
|               [Estonia](/estonia) |               66 |                        85 |                      64 |                         19 |                                       29% |                                    79 |                                     94 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    30 |                                     43 |
|                 [Latvia](/latvia) |               24 |                        36 |                      19 |                         12 |                                       50% |                                    33 |                                     39 |
|                 [Cyprus](/cyprus) |               17 |                        21 |                      24 |                          4 |                                       24% |                                    20 |                                     24 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |
|                   [Malta](/malta) |                7 |                        10 |                      20 |                          3 |                                       43% |                                     9 |                                     11 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-09-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |           88,663 |                   556,649 |                     107 |                    467,986 |                                      528% |                               212,387 |                                981,266 |
|                             [Brazil](/brazil) |           26,754 |                   175,646 |                     832 |                    148,892 |                                      557% |                                65,922 |                                312,138 |
|                             [Mexico](/mexico) |            9,044 |                   131,285 |                   1,029 |                    122,241 |                                     1352% |                                49,593 |                                196,513 |
|                               [India](/india) |            4,711 |                    61,755 |                      45 |                     57,044 |                                     1211% |                                12,344 |                                118,437 |
|                                 [Peru](/peru) |            4,099 |                    31,728 |                     976 |                     27,629 |                                      674% |                                 9,766 |                                 52,927 |
|                             [Russia](/russia) |            4,142 |                    24,294 |                     167 |                     20,152 |                                      487% |                                 7,723 |                                 54,442 |
|                 [South Africa](/south-africa) |              577 |                    17,877 |                     305 |                     17,300 |                                     2998% |                                 8,520 |                                 29,458 |
|                             [Canada](/canada) |            6,982 |                    13,999 |                     374 |                      7,017 |                                      101% |                                 8,315 |                                 29,225 |
|                                 [Iran](/iran) |            7,627 |                    12,545 |                     151 |                      4,918 |                                       64% |                                 8,563 |                                 21,823 |
|                               [Chile](/chile) |              890 |                    12,168 |                     642 |                     11,278 |                                     1267% |                                 6,027 |                                 19,273 |
|                         [Colombia](/colombia) |              833 |                     9,626 |                     191 |                      8,793 |                                     1056% |                                 3,409 |                                 17,905 |
|                         [Pakistan](/pakistan) |            1,260 |                     8,556 |                      40 |                      7,296 |                                      579% |                                 2,429 |                                 19,824 |
|                           [Ecuador](/ecuador) |            3,313 |                     7,528 |                     433 |                      4,215 |                                      127% |                                 4,091 |                                 18,150 |
|                     [Bangladesh](/bangladesh) |              559 |                     7,049 |                      43 |                      6,490 |                                     1161% |                                 2,220 |                                 13,010 |
|                             [Turkey](/turkey) |            4,461 |                     5,580 |                      67 |                      1,119 |                                       25% |                                 4,717 |                                  8,105 |
|                       [Indonesia](/indonesia) |            1,496 |                     5,312 |                      20 |                      3,816 |                                      255% |                                 2,237 |                                 12,089 |
|                               [Egypt](/egypt) |              845 |                     5,157 |                      51 |                      4,312 |                                      510% |                                 1,668 |                                 10,875 |
|                               [China](/china) |            4,638 |                     4,652 |                       3 |                         14 |                                        0% |                                 4,638 |                                  4,745 |
|                       [Argentina](/argentina) |              508 |                     3,944 |                      88 |                      3,436 |                                      676% |                                 1,249 |                                  7,314 |
|                 [Saudi Arabia](/saudi-arabia) |              441 |                     3,799 |                     111 |                      3,358 |                                      761% |                                 1,277 |                                  6,994 |
|                           [Bolivia](/bolivia) |              293 |                     2,301 |                     200 |                      2,008 |                                      685% |                                   959 |                                  4,256 |
|                   [Philippines](/philippines) |              921 |                     1,700 |                      16 |                        779 |                                       85% |                                 1,074 |                                  3,097 |
|                             [Kuwait](/kuwait) |              185 |                     1,540 |                     366 |                      1,355 |                                      732% |                                   664 |                                  2,774 |
|                           [Nigeria](/nigeria) |              259 |                     1,521 |                       8 |                      1,262 |                                      487% |                                   448 |                                  4,485 |
|                               [Japan](/japan) |              881 |                     1,184 |                       9 |                        303 |                                       34% |                                   897 |                                  1,682 |
|                         [Honduras](/honduras) |              196 |                     1,098 |                     113 |                        902 |                                      460% |                                   419 |                                  2,526 |
|                           [Algeria](/algeria) |              630 |                       998 |                      23 |                        368 |                                       58% |                                   734 |                                  1,962 |
|     [Dominican Republic](/dominican-republic) |              485 |                       998 |                      93 |                        513 |                                      106% |                                   600 |                                  1,953 |
|                             [Panama](/panama) |              320 |                       923 |                     217 |                        603 |                                      188% |                                   426 |                                  2,313 |
| [United Arab Emirates](/united-arab-emirates) |              258 |                       610 |                      62 |                        352 |                                      136% |                                   332 |                                  1,329 |
|                             [Israel](/israel) |              284 |                       350 |                      41 |                         66 |                                       23% |                                   308 |                                    467 |
|                   [South Korea](/south-korea) |              269 |                       322 |                       6 |                         53 |                                       20% |                                   276 |                                    437 |
|                           [Morocco](/morocco) |              202 |                       238 |                       7 |                         36 |                                       18% |                                   217 |                                    289 |
|                         [Malaysia](/malaysia) |              115 |                       146 |                       5 |                         31 |                                       27% |                                   129 |                                    173 |
|                       [Australia](/australia) |              103 |                       113 |                       4 |                         10 |                                       10% |                                   105 |                                    138 |
|                                 [Cuba](/cuba) |               82 |                       107 |                       9 |                         25 |                                       30% |                                    91 |                                    138 |
