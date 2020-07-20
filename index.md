We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >97% of all global COVID-19 deaths.

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
* **July 13:** View our [updated historical performance](/about/#historical-performance) (commentary [on Twitter](https://twitter.com/youyanggu/status/1283102532236181504)).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 20 (4pm ET):
<p align="center">
  Current Total: <b>140,531</b> deaths | Projected Total: <b>213,600 deaths by Nov 1, 2020</b> (Range: 177-272k)<br>
  Currently Infected: <b>1.6%</b> | Total Infected: <b>8.5%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 20, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 18, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |         Sep 2, 2020 |
|              200,000 |        Oct 25, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        61% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          5% |        49% |         76% |        91% |         97% |        99% |
|              200,000 |        <1% |         <1% |         5% |         16% |        32% |         44% |        54% |
|              225,000 |        <1% |         <1% |        <1% |          2% |         8% |         14% |        21% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         2% |          4% |         8% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          140,531 |                   213,628 |                     644 |                     73,097 |                                       52% |                               177,986 |                                271,988 |
|                 [New York](/us-ny) |           32,495 |                    33,748 |                   1,735 |                      1,253 |                                        4% |                                32,540 |                                 38,415 |
|               [New Jersey](/us-nj) |           15,706 |                    17,174 |                   1,934 |                      1,468 |                                        9% |                                15,802 |                                 19,556 |
|               [California](/us-ca) |            7,715 |                    16,153 |                     409 |                      8,438 |                                      109% |                                 9,838 |                                 26,374 |
|                  [Florida](/us-fl) |            4,982 |                    15,854 |                     738 |                     10,872 |                                      218% |                                 9,304 |                                 26,154 |
|                    [Texas](/us-tx) |            4,012 |                    13,772 |                     475 |                      9,760 |                                      243% |                                 8,290 |                                 24,412 |
|            [Massachusetts](/us-ma) |            8,431 |                     9,500 |                   1,367 |                      1,069 |                                       13% |                                 8,554 |                                 11,883 |
|             [Pennsylvania](/us-pa) |            7,022 |                     8,801 |                     687 |                      1,779 |                                       25% |                                 7,194 |                                 12,637 |
|                 [Illinois](/us-il) |            7,488 |                     8,520 |                     672 |                      1,032 |                                       14% |                                 7,656 |                                  9,773 |
|                 [Michigan](/us-mi) |            6,366 |                     7,674 |                     768 |                      1,308 |                                       21% |                                 6,461 |                                 10,541 |
|                  [Arizona](/us-az) |            2,761 |                     6,612 |                     908 |                      3,851 |                                      139% |                                 4,538 |                                 10,323 |
|                     [Ohio](/us-oh) |            3,174 |                     5,907 |                     505 |                      2,733 |                                       86% |                                 3,695 |                                 11,087 |
|                  [Georgia](/us-ga) |            3,174 |                     5,881 |                     554 |                      2,707 |                                       85% |                                 3,870 |                                 11,264 |
|                [Louisiana](/us-la) |            3,543 |                     5,725 |                   1,232 |                      2,182 |                                       62% |                                 4,048 |                                  9,175 |
|              [Connecticut](/us-ct) |            4,396 |                     4,626 |                   1,298 |                        230 |                                        5% |                                 4,418 |                                  5,051 |
|                 [Maryland](/us-md) |            3,377 |                     4,485 |                     742 |                      1,108 |                                       33% |                                 3,524 |                                  7,033 |
|                  [Indiana](/us-in) |            2,822 |                     3,919 |                     582 |                      1,097 |                                       39% |                                 2,946 |                                  6,616 |
|                  [Alabama](/us-al) |            1,287 |                     3,562 |                     726 |                      2,275 |                                      177% |                                 2,076 |                                  6,214 |
|           [North Carolina](/us-nc) |            1,652 |                     3,347 |                     319 |                      1,695 |                                      103% |                                 2,215 |                                  5,816 |
|                 [Virginia](/us-va) |            2,027 |                     3,337 |                     391 |                      1,310 |                                       65% |                                 2,159 |                                  5,773 |
|           [South Carolina](/us-sc) |            1,155 |                     3,169 |                     615 |                      2,014 |                                      174% |                                 1,840 |                                  5,539 |
|                 [Colorado](/us-co) |            1,752 |                     2,765 |                     480 |                      1,013 |                                       58% |                                 1,862 |                                  5,352 |
|              [Mississippi](/us-ms) |            1,355 |                     2,548 |                     856 |                      1,193 |                                       88% |                                 1,736 |                                  3,981 |
|                [Minnesota](/us-mn) |            1,581 |                     2,523 |                     447 |                        942 |                                       60% |                                 1,697 |                                  4,536 |
|                [Tennessee](/us-tn) |              843 |                     2,439 |                     357 |                      1,596 |                                      189% |                                 1,410 |                                  4,481 |
|               [Washington](/us-wa) |            1,447 |                     2,223 |                     292 |                        776 |                                       54% |                                 1,565 |                                  4,076 |
|                 [Missouri](/us-mo) |            1,136 |                     2,075 |                     338 |                        939 |                                       83% |                                 1,310 |                                  4,172 |
|                 [Kentucky](/us-ky) |              670 |                     1,863 |                     417 |                      1,193 |                                      178% |                                   889 |                                  4,394 |
|                   [Nevada](/us-nv) |              647 |                     1,777 |                     577 |                      1,130 |                                      175% |                                 1,033 |                                  3,344 |
|                [Wisconsin](/us-wi) |              844 |                     1,545 |                     265 |                        701 |                                       83% |                                   964 |                                  3,411 |
|                     [Iowa](/us-ia) |              793 |                     1,229 |                     390 |                        436 |                                       55% |                                   831 |                                  2,256 |
|               [New Mexico](/us-nm) |              571 |                     1,158 |                     552 |                        587 |                                      103% |                                   640 |                                  2,633 |
|             [Rhode Island](/us-ri) |              990 |                     1,119 |                   1,056 |                        129 |                                       13% |                                 1,009 |                                  1,275 |
|                 [Oklahoma](/us-ok) |              451 |                       963 |                     243 |                        512 |                                      114% |                                   587 |                                  1,697 |
|                 [Arkansas](/us-ar) |              357 |                       926 |                     307 |                        569 |                                      159% |                                   552 |                                  1,642 |
|                   [Oregon](/us-or) |              260 |                       838 |                     199 |                        578 |                                      222% |                                   378 |                                  2,035 |
|                     [Utah](/us-ut) |              243 |                       777 |                     242 |                        534 |                                      220% |                                   424 |                                  1,555 |
|     [District of Columbia](/us-dc) |              578 |                       694 |                     983 |                        116 |                                       20% |                                   595 |                                    944 |
|                 [Delaware](/us-de) |              523 |                       655 |                     673 |                        132 |                                       25% |                                   539 |                                    950 |
|                    [Idaho](/us-id) |              119 |                       654 |                     366 |                        535 |                                      450% |                                   256 |                                  1,590 |
|                   [Kansas](/us-ks) |              309 |                       619 |                     212 |                        310 |                                      100% |                                   362 |                                  1,350 |
|                 [Nebraska](/us-ne) |              301 |                       482 |                     249 |                        181 |                                       60% |                                   352 |                                    741 |
|            [New Hampshire](/us-nh) |              398 |                       451 |                     332 |                         53 |                                       13% |                                   404 |                                    507 |
|              [Puerto Rico](/us-pr) |              178 |                       391 |                     122 |                        213 |                                      120% |                                   203 |                                    965 |
|             [South Dakota](/us-sd) |              118 |                       202 |                     228 |                         84 |                                       71% |                                   141 |                                    330 |
|                    [Maine](/us-me) |              117 |                       182 |                     135 |                         65 |                                       56% |                                   126 |                                    334 |
|                  [Montana](/us-mt) |               37 |                       177 |                     166 |                        140 |                                      378% |                                    57 |                                    514 |
|             [North Dakota](/us-nd) |               92 |                       165 |                     217 |                         73 |                                       79% |                                   103 |                                    326 |
|            [West Virginia](/us-wv) |              100 |                       153 |                      85 |                         53 |                                       53% |                                   109 |                                    293 |
|                  [Vermont](/us-vt) |               56 |                        81 |                     130 |                         25 |                                       45% |                                    58 |                                    200 |
|                   [Hawaii](/us-hi) |               24 |                        69 |                      49 |                         45 |                                      188% |                                    26 |                                    236 |
|                  [Wyoming](/us-wy) |               25 |                        55 |                      95 |                         30 |                                      120% |                                    32 |                                    115 |
|                   [Alaska](/us-ak) |               18 |                        37 |                      51 |                         19 |                                      106% |                                    20 |                                     87 |
|           [Virgin Islands](/us-vi) |                6 |                        15 |                     143 |                          9 |                                      150% |                                     6 |                                     45 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     5 |                                     45 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      9 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          185,834 |                   199,783 |                     337 |                     13,949 |                                        8% |                               189,057 |                                220,522 |
| [United Kingdom](/united-kingdom) |           45,385 |                    49,212 |                     729 |                      3,827 |                                        8% |                                45,823 |                                 54,817 |
|                   [Italy](/italy) |           35,045 |                    35,456 |                     587 |                        411 |                                        1% |                                35,082 |                                 35,849 |
|                 [France](/france) |           30,155 |                    30,632 |                     457 |                        477 |                                        2% |                                30,168 |                                 33,024 |
|                   [Spain](/spain) |           28,420 |                    28,642 |                     610 |                        222 |                                        1% |                                28,439 |                                 29,225 |
|               [Belgium](/belgium) |            9,800 |                     9,912 |                     865 |                        112 |                                        1% |                                 9,811 |                                 10,277 |
|               [Germany](/germany) |            9,092 |                     9,339 |                     112 |                        247 |                                        3% |                                 9,115 |                                  9,860 |
|       [Netherlands](/netherlands) |            6,155 |                     6,234 |                     361 |                         79 |                                        1% |                                 6,168 |                                  6,333 |
|                 [Sweden](/sweden) |            5,619 |                     6,003 |                     587 |                        384 |                                        7% |                                 5,738 |                                  6,164 |
|               [Romania](/romania) |            2,026 |                     3,995 |                     206 |                      1,969 |                                       97% |                                 2,847 |                                  5,585 |
|               [Ukraine](/ukraine) |            1,504 |                     2,754 |                      63 |                      1,250 |                                       83% |                                 2,011 |                                  3,740 |
|             [Portugal](/portugal) |            1,689 |                     2,170 |                     211 |                        481 |                                       28% |                                 1,746 |                                  3,108 |
|                 [Poland](/poland) |            1,624 |                     2,155 |                      57 |                        531 |                                       33% |                                 1,825 |                                  2,752 |
|       [Switzerland](/switzerland) |            1,969 |                     2,044 |                     238 |                         75 |                                        4% |                                 1,978 |                                  2,400 |
|                 [Serbia](/serbia) |              472 |                     1,945 |                     279 |                      1,473 |                                      312% |                                   814 |                                  4,258 |
|               [Ireland](/ireland) |            1,753 |                     1,822 |                     372 |                         69 |                                        4% |                                 1,758 |                                  2,201 |
|               [Moldova](/moldova) |              684 |                     1,229 |                     304 |                        545 |                                       80% |                                   912 |                                  1,887 |
|               [Belarus](/belarus) |              499 |                     1,086 |                     115 |                        587 |                                      118% |                                   642 |                                  1,888 |
|             [Bulgaria](/bulgaria) |              300 |                       862 |                     123 |                        562 |                                      187% |                                   455 |                                  1,508 |
|               [Austria](/austria) |              711 |                       818 |                      92 |                        107 |                                       15% |                                   722 |                                  1,057 |
|               [Hungary](/hungary) |              596 |                       681 |                      70 |                         85 |                                       14% |                                   605 |                                    932 |
|               [Denmark](/denmark) |              611 |                       645 |                     111 |                         34 |                                        6% |                                   621 |                                    707 |
|               [Czechia](/czechia) |              359 |                       496 |                      47 |                        137 |                                       38% |                                   366 |                                    739 |
|               [Finland](/finland) |              328 |                       356 |                      65 |                         28 |                                        9% |                                   330 |                                    445 |
|                 [Norway](/norway) |              255 |                       273 |                      51 |                         18 |                                        7% |                                   260 |                                    307 |
|               [Croatia](/croatia) |              120 |                       220 |                      54 |                        100 |                                       83% |                                   133 |                                    360 |
|                 [Greece](/greece) |              194 |                       219 |                      20 |                         25 |                                       13% |                                   202 |                                    266 |
|         [Luxembourg](/luxembourg) |              111 |                       141 |                     230 |                         30 |                                       27% |                                   115 |                                    182 |
|             [Slovenia](/slovenia) |              112 |                       122 |                      59 |                         10 |                                        9% |                                   113 |                                    152 |
|           [Lithuania](/lithuania) |               80 |                       105 |                      38 |                         25 |                                       31% |                                    85 |                                    147 |
|               [Estonia](/estonia) |               69 |                        81 |                      61 |                         12 |                                       17% |                                    73 |                                     99 |
|             [Slovakia](/slovakia) |               28 |                        41 |                       8 |                         13 |                                       46% |                                    28 |                                     79 |
|                 [Latvia](/latvia) |               31 |                        39 |                      20 |                          8 |                                       26% |                                    32 |                                     76 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     62 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     23 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    10 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          263,761 |                   590,853 |                     114 |                    327,092 |                                      124% |                               393,584 |                                990,968 |
|                             [Brazil](/brazil) |           79,488 |                   153,895 |                     729 |                     74,407 |                                       94% |                               118,424 |                                226,667 |
|                               [India](/india) |           27,497 |                   115,024 |                      84 |                     87,527 |                                      318% |                                54,307 |                                263,911 |
|                             [Mexico](/mexico) |           39,184 |                    78,918 |                     619 |                     39,734 |                                      101% |                                54,838 |                                119,197 |
|                                 [Iran](/iran) |           14,188 |                    31,266 |                     377 |                     17,078 |                                      120% |                                21,108 |                                 47,652 |
|                                 [Peru](/peru) |           13,187 |                    24,580 |                     756 |                     11,393 |                                       86% |                                18,484 |                                 35,711 |
|                         [Colombia](/colombia) |            6,736 |                    22,432 |                     446 |                     15,696 |                                      233% |                                14,488 |                                 35,432 |
|                             [Russia](/russia) |           12,323 |                    21,503 |                     147 |                      9,180 |                                       74% |                                15,372 |                                 34,479 |
|                 [South Africa](/south-africa) |            5,033 |                    18,179 |                     310 |                     13,146 |                                      261% |                                12,180 |                                 24,931 |
|                       [Indonesia](/indonesia) |            4,143 |                    14,965 |                      55 |                     10,822 |                                      261% |                                 7,355 |                                 28,400 |
|                               [Chile](/chile) |            8,503 |                    13,107 |                     692 |                      4,604 |                                       54% |                                 9,286 |                                 18,932 |
|                             [Canada](/canada) |            8,896 |                     9,487 |                     254 |                        591 |                                        7% |                                 8,949 |                                 10,239 |
|                         [Pakistan](/pakistan) |            5,599 |                     8,614 |                      40 |                      3,015 |                                       54% |                                 6,581 |                                 13,740 |
|                               [Egypt](/egypt) |            4,302 |                     8,550 |                      85 |                      4,248 |                                       99% |                                 5,855 |                                 12,105 |
|                       [Argentina](/argentina) |            2,260 |                     8,457 |                     189 |                      6,197 |                                      274% |                                 5,472 |                                 12,875 |
|                           [Ecuador](/ecuador) |            5,313 |                     7,889 |                     454 |                      2,576 |                                       48% |                                 5,615 |                                 12,609 |
|                             [Turkey](/turkey) |            5,491 |                     6,733 |                      81 |                      1,242 |                                       23% |                                 5,566 |                                 10,160 |
|                           [Bolivia](/bolivia) |            2,151 |                     5,612 |                     487 |                      3,461 |                                      161% |                                 3,665 |                                  7,513 |
|                     [Bangladesh](/bangladesh) |            2,618 |                     5,466 |                      34 |                      2,848 |                                      109% |                                 3,754 |                                  9,515 |
|                   [Philippines](/philippines) |            1,831 |                     5,241 |                      48 |                      3,410 |                                      186% |                                 2,545 |                                 11,624 |
|                 [Saudi Arabia](/saudi-arabia) |            2,486 |                     5,076 |                     148 |                      2,590 |                                      104% |                                 3,690 |                                  6,294 |
|                               [China](/china) |            4,644 |                     4,646 |                       3 |                          2 |                                        0% |                                 4,644 |                                  4,663 |
|                           [Algeria](/algeria) |            1,078 |                     3,857 |                      90 |                      2,779 |                                      258% |                                 1,311 |                                 12,881 |
|                             [Panama](/panama) |            1,096 |                     3,413 |                     804 |                      2,317 |                                      211% |                                 2,345 |                                  4,922 |
|                         [Honduras](/honduras) |              900 |                     3,380 |                     347 |                      2,480 |                                      276% |                                 1,896 |                                  5,878 |
|     [Dominican Republic](/dominican-republic) |              981 |                     3,196 |                     298 |                      2,215 |                                      226% |                                 1,447 |                                  6,261 |
|                               [Japan](/japan) |              986 |                     1,656 |                      13 |                        670 |                                       68% |                                   997 |                                  2,893 |
|                           [Nigeria](/nigeria) |              789 |                     1,631 |                       8 |                        842 |                                      107% |                                   994 |                                  3,388 |
|                             [Israel](/israel) |              409 |                     1,419 |                     167 |                      1,010 |                                      247% |                                   658 |                                  2,931 |
|                             [Kuwait](/kuwait) |              408 |                       678 |                     161 |                        270 |                                       66% |                                   442 |                                  1,311 |
|                           [Morocco](/morocco) |              273 |                       557 |                      15 |                        284 |                                      104% |                                   319 |                                    988 |
| [United Arab Emirates](/united-arab-emirates) |              339 |                       482 |                      49 |                        143 |                                       42% |                                   350 |                                    981 |
|                       [Australia](/australia) |              123 |                       351 |                      14 |                        228 |                                      185% |                                   125 |                                  1,127 |
|                   [South Korea](/south-korea) |              296 |                       338 |                       7 |                         42 |                                       14% |                                   297 |                                    444 |
|                         [Malaysia](/malaysia) |              123 |                       151 |                       5 |                         28 |                                       23% |                                   134 |                                    177 |
|                                 [Cuba](/cuba) |               87 |                       104 |                       9 |                         17 |                                       20% |                                    91 |                                    137 |
