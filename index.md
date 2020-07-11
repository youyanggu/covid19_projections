We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#current-us-projections)
* [US and Global Dashboard](#covid-19-dashboard)
* [View US state-by-state projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates
* **July 11:** See how our [late May projections](/about/#late-may-projections) have performed for Florida, California, Arizona, and Texas, four of the most heavily impacted states post-reopening.
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 11 (3am ET):
<p align="center">
  Current Total: <b>134,089</b> deaths | Projected Total: <b>212,529 deaths by Nov 1, 2020</b> (Range: 172-278k) | 195,600 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.1%</b> | Total Infected: <b>6.9%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 9, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 20, 2020 |
|              150,000 |         Aug 3, 2020 |
|              175,000 |         Sep 3, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        33% |         96% |        99% |         99% |        99% |        >99% |       >99% |
|              175,000 |         <1% |        <1% |         <1% |        39% |         63% |        79% |         88% |        94% |
|              200,000 |         <1% |        <1% |         <1% |         2% |         14% |        30% |         41% |        52% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |          1% |         8% |         14% |        22% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |          5% |         9% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 63 countries (including all 27 European Union countries).

[Back to Top](#top)

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

[Back to Top](#top)

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

[Back to Top](#top)

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

[Back to Top](#top)

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

States are ordered by descending projected deaths (by November 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          134,089 |                   212,529 |                     641 |                     78,440 |                                       58% |                               172,660 |                                277,378 |
|                 [New York](/us-ny) |           32,331 |                    33,660 |                   1,730 |                      1,329 |                                        4% |                                32,373 |                                 39,162 |
|               [California](/us-ca) |            6,955 |                    18,817 |                     476 |                     11,862 |                                      171% |                                 8,957 |                                 36,456 |
|               [New Jersey](/us-nj) |           15,479 |                    16,771 |                   1,888 |                      1,292 |                                        8% |                                15,559 |                                 19,062 |
|                  [Florida](/us-fl) |            4,102 |                    13,679 |                     637 |                      9,577 |                                      233% |                                 7,076 |                                 22,525 |
|                    [Texas](/us-tx) |            3,062 |                    12,193 |                     421 |                      9,131 |                                      298% |                                 7,413 |                                 21,539 |
|             [Pennsylvania](/us-pa) |            6,880 |                     9,394 |                     734 |                      2,514 |                                       37% |                                 7,109 |                                 15,343 |
|                 [Illinois](/us-il) |            7,345 |                     9,095 |                     718 |                      1,750 |                                       24% |                                 7,690 |                                 11,158 |
|            [Massachusetts](/us-ma) |            8,296 |                     9,084 |                   1,307 |                        788 |                                        9% |                                 8,435 |                                 10,704 |
|                 [Michigan](/us-mi) |            6,285 |                     7,861 |                     787 |                      1,576 |                                       25% |                                 6,350 |                                 12,246 |
|                  [Georgia](/us-ga) |            2,965 |                     7,153 |                     674 |                      4,188 |                                      141% |                                 3,843 |                                 13,861 |
|                  [Arizona](/us-az) |            2,082 |                     5,826 |                     800 |                      3,744 |                                      180% |                                 4,214 |                                  7,957 |
|                     [Ohio](/us-oh) |            3,032 |                     5,592 |                     478 |                      2,560 |                                       84% |                                 3,302 |                                 11,374 |
|                [Louisiana](/us-la) |            3,380 |                     5,575 |                   1,199 |                      2,195 |                                       65% |                                 3,689 |                                  7,761 |
|              [Connecticut](/us-ct) |            4,348 |                     4,579 |                   1,284 |                        231 |                                        5% |                                 4,382 |                                  5,007 |
|                 [Maryland](/us-md) |            3,303 |                     4,179 |                     691 |                        876 |                                       27% |                                 3,478 |                                  5,559 |
|                  [Indiana](/us-in) |            2,748 |                     4,094 |                     608 |                      1,346 |                                       49% |                                 2,853 |                                  7,699 |
|                 [Virginia](/us-va) |            1,958 |                     3,595 |                     421 |                      1,637 |                                       84% |                                 2,098 |                                  7,127 |
|                  [Alabama](/us-al) |            1,104 |                     3,587 |                     732 |                      2,483 |                                      225% |                                 1,972 |                                  5,799 |
|           [South Carolina](/us-sc) |              929 |                     3,399 |                     660 |                      2,470 |                                      266% |                                 2,196 |                                  5,427 |
|           [North Carolina](/us-nc) |            1,497 |                     3,031 |                     289 |                      1,534 |                                      102% |                                 1,756 |                                  6,615 |
|                [Tennessee](/us-tn) |              723 |                     2,842 |                     416 |                      2,119 |                                      293% |                                 1,687 |                                  5,446 |
|              [Mississippi](/us-ms) |            1,215 |                     2,758 |                     927 |                      1,543 |                                      127% |                                 1,645 |                                  4,328 |
|               [Washington](/us-wa) |            1,424 |                     2,629 |                     345 |                      1,205 |                                       85% |                                 1,634 |                                  5,280 |
|                 [Colorado](/us-co) |            1,724 |                     2,538 |                     441 |                        814 |                                       47% |                                 1,787 |                                  5,063 |
|                [Minnesota](/us-mn) |            1,533 |                     2,218 |                     393 |                        685 |                                       45% |                                 1,653 |                                  3,485 |
|                 [Missouri](/us-mo) |            1,084 |                     1,947 |                     317 |                        863 |                                       80% |                                 1,177 |                                  4,139 |
|                   [Nevada](/us-nv) |              579 |                     1,936 |                     629 |                      1,357 |                                      234% |                                   960 |                                  3,250 |
|                [Wisconsin](/us-wi) |              814 |                     1,615 |                     277 |                        801 |                                       98% |                                   936 |                                  4,149 |
|                 [Kentucky](/us-ky) |              620 |                     1,438 |                     322 |                        818 |                                      132% |                                   715 |                                  3,211 |
|             [Rhode Island](/us-ri) |              976 |                     1,216 |                   1,148 |                        240 |                                       25% |                                 1,032 |                                  1,500 |
|                 [Arkansas](/us-ar) |              313 |                     1,136 |                     376 |                        823 |                                      263% |                                   468 |                                  2,318 |
|               [New Mexico](/us-nm) |              539 |                     1,037 |                     495 |                        498 |                                       92% |                                   601 |                                  2,052 |
|                     [Iowa](/us-ia) |              743 |                       989 |                     313 |                        246 |                                       33% |                                   766 |                                  1,661 |
|                   [Oregon](/us-or) |              232 |                       851 |                     202 |                        619 |                                      267% |                                   298 |                                  2,011 |
|                 [Oklahoma](/us-ok) |              416 |                       834 |                     211 |                        418 |                                      100% |                                   462 |                                  1,911 |
|                     [Utah](/us-ut) |              207 |                       830 |                     259 |                        623 |                                      301% |                                   347 |                                  1,869 |
|     [District of Columbia](/us-dc) |              568 |                       705 |                     999 |                        137 |                                       24% |                                   589 |                                  1,035 |
|                 [Delaware](/us-de) |              517 |                       684 |                     702 |                        167 |                                       32% |                                   537 |                                  1,064 |
|            [New Hampshire](/us-nh) |              390 |                       597 |                     439 |                        207 |                                       53% |                                   424 |                                    958 |
|                   [Kansas](/us-ks) |              293 |                       489 |                     168 |                        196 |                                       67% |                                   312 |                                  1,061 |
|                 [Nebraska](/us-ne) |              286 |                       473 |                     245 |                        187 |                                       65% |                                   346 |                                    683 |
|                    [Idaho](/us-id) |              101 |                       342 |                     191 |                        241 |                                      239% |                                   128 |                                    776 |
|              [Puerto Rico](/us-pr) |              159 |                       246 |                      77 |                         87 |                                       55% |                                   168 |                                    538 |
|             [South Dakota](/us-sd) |              107 |                       209 |                     236 |                        102 |                                       95% |                                   136 |                                    337 |
|                    [Maine](/us-me) |              111 |                       179 |                     133 |                         68 |                                       61% |                                   120 |                                    379 |
|                  [Montana](/us-mt) |               28 |                       142 |                     133 |                        114 |                                      407% |                                    57 |                                    335 |
|            [West Virginia](/us-wv) |               95 |                       128 |                      71 |                         33 |                                       35% |                                   100 |                                    214 |
|             [North Dakota](/us-nd) |               85 |                       125 |                     164 |                         40 |                                       47% |                                    99 |                                    177 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    150 |
|                   [Alaska](/us-ak) |               17 |                        56 |                      77 |                         39 |                                      229% |                                    19 |                                    169 |
|                  [Wyoming](/us-wy) |               21 |                        43 |                      74 |                         22 |                                      105% |                                    27 |                                     76 |
|                   [Hawaii](/us-hi) |               19 |                        31 |                      22 |                         12 |                                       63% |                                    21 |                                     63 |
|           [Virgin Islands](/us-vi) |                6 |                        14 |                     133 |                          8 |                                      133% |                                     6 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       60% |                                     5 |                                     24 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          184,077 |                   201,492 |                     340 |                     17,415 |                                        9% |                               188,062 |                                226,563 |
| [United Kingdom](/united-kingdom) |           44,735 |                    49,165 |                     728 |                      4,430 |                                       10% |                                45,338 |                                 53,617 |
|                   [Italy](/italy) |           34,938 |                    35,746 |                     592 |                        808 |                                        2% |                                35,039 |                                 36,579 |
|                 [France](/france) |           30,007 |                    30,745 |                     459 |                        738 |                                        2% |                                30,031 |                                 34,128 |
|                   [Spain](/spain) |           28,403 |                    29,007 |                     618 |                        604 |                                        2% |                                28,438 |                                 30,866 |
|               [Belgium](/belgium) |            9,781 |                    10,047 |                     877 |                        266 |                                        3% |                                 9,802 |                                 10,845 |
|               [Germany](/germany) |            9,063 |                     9,483 |                     114 |                        420 |                                        5% |                                 9,107 |                                 10,489 |
|       [Netherlands](/netherlands) |            6,155 |                     6,309 |                     365 |                        154 |                                        3% |                                 6,176 |                                  6,503 |
|                 [Sweden](/sweden) |            5,526 |                     6,020 |                     588 |                        494 |                                        9% |                                 5,693 |                                  6,219 |
|               [Romania](/romania) |            1,847 |                     4,057 |                     209 |                      2,210 |                                      120% |                                 2,678 |                                  5,817 |
|               [Ukraine](/ukraine) |            1,362 |                     3,133 |                      71 |                      1,771 |                                      130% |                                 2,041 |                                  4,792 |
|                 [Poland](/poland) |            1,562 |                     2,928 |                      77 |                      1,366 |                                       87% |                                 1,892 |                                  5,249 |
|             [Portugal](/portugal) |            1,646 |                     2,270 |                     221 |                        624 |                                       38% |                                 1,740 |                                  3,330 |
|       [Switzerland](/switzerland) |            1,966 |                     2,069 |                     241 |                        103 |                                        5% |                                 1,979 |                                  2,480 |
|               [Ireland](/ireland) |            1,744 |                     1,836 |                     374 |                         92 |                                        5% |                                 1,752 |                                  2,264 |
|               [Moldova](/moldova) |              635 |                     1,395 |                     345 |                        760 |                                      120% |                                 1,057 |                                  2,020 |
|               [Belarus](/belarus) |              454 |                     1,158 |                     123 |                        704 |                                      155% |                                   616 |                                  2,389 |
|             [Bulgaria](/bulgaria) |              267 |                       920 |                     131 |                        653 |                                      245% |                                   475 |                                  1,535 |
|               [Austria](/austria) |              706 |                       832 |                      94 |                        126 |                                       18% |                                   722 |                                  1,069 |
|                 [Serbia](/serbia) |              370 |                       753 |                     108 |                        383 |                                      104% |                                   462 |                                  1,266 |
|               [Hungary](/hungary) |              593 |                       727 |                      74 |                        134 |                                       23% |                                   609 |                                  1,118 |
|               [Denmark](/denmark) |              609 |                       686 |                     118 |                         77 |                                       13% |                                   625 |                                    894 |
|               [Czechia](/czechia) |              352 |                       489 |                      46 |                        137 |                                       39% |                                   361 |                                    724 |
|               [Finland](/finland) |              329 |                       375 |                      68 |                         46 |                                       14% |                                   335 |                                    527 |
|                 [Norway](/norway) |              252 |                       275 |                      51 |                         23 |                                        9% |                                   259 |                                    320 |
|               [Croatia](/croatia) |              117 |                       255 |                      63 |                        138 |                                      118% |                                   140 |                                    380 |
|                 [Greece](/greece) |              193 |                       227 |                      21 |                         34 |                                       18% |                                   205 |                                    292 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    161 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    146 |
|           [Lithuania](/lithuania) |               79 |                       115 |                      41 |                         36 |                                       46% |                                    87 |                                    182 |
|               [Estonia](/estonia) |               69 |                        88 |                      66 |                         19 |                                       28% |                                    76 |                                    115 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        39 |                      20 |                          9 |                                       30% |                                    32 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        32 |                      37 |                         13 |                                       68% |                                    21 |                                     68 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     27 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          229,628 |                   606,513 |                     117 |                    376,885 |                                      164% |                               384,560 |                              1,006,401 |
|                             [Brazil](/brazil) |           70,398 |                   147,499 |                     699 |                     77,101 |                                      110% |                               111,930 |                                226,601 |
|                               [India](/india) |           22,123 |                   114,704 |                      84 |                     92,581 |                                      418% |                                47,075 |                                250,515 |
|                             [Mexico](/mexico) |           34,191 |                    87,768 |                     688 |                     53,577 |                                      157% |                                64,834 |                                109,771 |
|                                 [Iran](/iran) |           12,447 |                    25,949 |                     313 |                     13,502 |                                      108% |                                19,626 |                                 40,325 |
|                                 [Peru](/peru) |           11,500 |                    23,302 |                     717 |                     11,802 |                                      103% |                                16,914 |                                 32,486 |
|                             [Russia](/russia) |           11,000 |                    23,146 |                     159 |                     12,146 |                                      110% |                                14,230 |                                 43,257 |
|                         [Colombia](/colombia) |            4,985 |                    21,045 |                     418 |                     16,060 |                                      322% |                                13,798 |                                 32,353 |
|                 [South Africa](/south-africa) |            3,860 |                    18,927 |                     323 |                     15,067 |                                      390% |                                 9,873 |                                 30,359 |
|                               [Egypt](/egypt) |            3,702 |                    14,609 |                     146 |                     10,907 |                                      295% |                                 8,558 |                                 22,476 |
|                       [Indonesia](/indonesia) |            3,469 |                    13,472 |                      50 |                     10,003 |                                      288% |                                 6,150 |                                 25,748 |
|                         [Pakistan](/pakistan) |            5,123 |                    12,731 |                      59 |                      7,608 |                                      149% |                                 7,924 |                                 20,612 |
|                               [Chile](/chile) |            6,781 |                    12,276 |                     648 |                      5,495 |                                       81% |                                 7,882 |                                 16,773 |
|                       [Argentina](/argentina) |            1,774 |                    11,729 |                     262 |                      9,955 |                                      561% |                                 4,501 |                                 20,186 |
|                             [Canada](/canada) |            8,811 |                    10,290 |                     275 |                      1,479 |                                       17% |                                 9,024 |                                 13,611 |
|                           [Ecuador](/ecuador) |            4,939 |                     8,782 |                     505 |                      3,843 |                                       78% |                                 5,335 |                                 14,196 |
|                 [Saudi Arabia](/saudi-arabia) |            2,151 |                     8,764 |                     256 |                      6,613 |                                      307% |                                 5,179 |                                 12,544 |
|                     [Bangladesh](/bangladesh) |            2,275 |                     7,357 |                      45 |                      5,082 |                                      223% |                                 4,440 |                                 13,620 |
|                             [Turkey](/turkey) |            5,323 |                     7,029 |                      84 |                      1,706 |                                       32% |                                 5,435 |                                 12,215 |
|                           [Bolivia](/bolivia) |            1,702 |                     6,979 |                     606 |                      5,277 |                                      310% |                                 3,654 |                                 12,184 |
|                               [China](/china) |            4,641 |                     4,646 |                       3 |                          5 |                                        0% |                                 4,641 |                                  4,676 |
|     [Dominican Republic](/dominican-republic) |              864 |                     4,233 |                     394 |                      3,369 |                                      390% |                                 1,420 |                                  8,850 |
|                         [Honduras](/honduras) |              750 |                     4,210 |                     432 |                      3,460 |                                      461% |                                 2,713 |                                  7,191 |
|                             [Panama](/panama) |              863 |                     3,425 |                     807 |                      2,562 |                                      297% |                                 2,422 |                                  5,479 |
|                   [Philippines](/philippines) |            1,360 |                     3,299 |                      31 |                      1,939 |                                      143% |                                 1,529 |                                  7,069 |
|                           [Algeria](/algeria) |              996 |                     2,966 |                      69 |                      1,970 |                                      198% |                                 1,384 |                                  7,427 |
|                           [Nigeria](/nigeria) |              709 |                     2,310 |                      11 |                      1,601 |                                      226% |                                 1,006 |                                  5,236 |
|                               [Japan](/japan) |              982 |                     1,557 |                      12 |                        575 |                                       59% |                                   989 |                                  2,755 |
|                             [Israel](/israel) |              351 |                     1,075 |                     126 |                        724 |                                      206% |                                   420 |                                  3,461 |
|                             [Kuwait](/kuwait) |              383 |                       709 |                     169 |                        326 |                                       85% |                                   427 |                                  1,359 |
|                           [Morocco](/morocco) |              243 |                       484 |                      13 |                        241 |                                       99% |                                   274 |                                    961 |
| [United Arab Emirates](/united-arab-emirates) |              330 |                       479 |                      49 |                        149 |                                       45% |                                   349 |                                    908 |
|                   [South Korea](/south-korea) |              288 |                       342 |                       7 |                         54 |                                       19% |                                   289 |                                    486 |
|                       [Australia](/australia) |              107 |                       159 |                       6 |                         52 |                                       49% |                                   107 |                                    378 |
|                         [Malaysia](/malaysia) |              121 |                       156 |                       5 |                         35 |                                       29% |                                   137 |                                    188 |
|                                 [Cuba](/cuba) |               86 |                       105 |                       9 |                         19 |                                       22% |                                    91 |                                    145 |
