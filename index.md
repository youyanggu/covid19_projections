We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject.

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

For regular updates and insights, follow us on Twitter:<br>
<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">@youyanggu</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

* **August 17:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 19 (2pm ET):
<p align="center">
  Current Total: <b>173,174</b> deaths | Projected Total: <b>226,200 deaths by Nov 1, 2020</b> (Range: 205-255k)<br>
  Currently Infected: <b>1.6%</b> (1 in 64) | Total Infected: <b>13.6%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 20, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              175,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |        <1% |         23% |        87% |         99% |        99% |
|              225,000 |        <1% |         <1% |         2% |         17% |        43% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         5% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          173,174 |                   226,235 |                     682 |                     53,061 |                                       31% |                               205,962 |                                254,501 |
|                 [New York](/us-ny) |           32,865 |                    33,416 |                   1,718 |                        551 |                                        2% |                                32,884 |                                 36,195 |
|               [California](/us-ca) |           11,690 |                    18,961 |                     480 |                      7,271 |                                       62% |                                14,935 |                                 24,858 |
|                    [Texas](/us-tx) |           10,934 |                    18,881 |                     651 |                      7,947 |                                       73% |                                15,199 |                                 23,176 |
|                  [Florida](/us-fl) |            9,932 |                    16,880 |                     786 |                      6,948 |                                       70% |                                13,415 |                                 21,012 |
|               [New Jersey](/us-nj) |           15,926 |                    16,183 |                   1,822 |                        257 |                                        2% |                                15,949 |                                 16,849 |
|            [Massachusetts](/us-ma) |            8,876 |                     9,852 |                   1,418 |                        976 |                                       11% |                                 8,950 |                                 11,769 |
|                 [Illinois](/us-il) |            8,017 |                     9,393 |                     741 |                      1,376 |                                       17% |                                 8,194 |                                 11,889 |
|             [Pennsylvania](/us-pa) |            7,508 |                     8,707 |                     680 |                      1,199 |                                       16% |                                 7,629 |                                 11,011 |
|                  [Georgia](/us-ga) |            4,849 |                     7,519 |                     708 |                      2,670 |                                       55% |                                 6,128 |                                  9,565 |
|                 [Michigan](/us-mi) |            6,618 |                     7,277 |                     729 |                        659 |                                       10% |                                 6,679 |                                  8,520 |
|                  [Arizona](/us-az) |            4,634 |                     6,618 |                     909 |                      1,984 |                                       43% |                                 5,580 |                                  8,028 |
|                [Louisiana](/us-la) |            4,609 |                     5,794 |                   1,246 |                      1,185 |                                       26% |                                 5,114 |                                  6,785 |
|                     [Ohio](/us-oh) |            3,907 |                     5,505 |                     471 |                      1,598 |                                       41% |                                 4,444 |                                  7,241 |
|              [Connecticut](/us-ct) |            4,457 |                     4,547 |                   1,275 |                         90 |                                        2% |                                 4,471 |                                  4,781 |
|                 [Maryland](/us-md) |            3,661 |                     4,391 |                     726 |                        730 |                                       20% |                                 3,721 |                                  5,799 |
|                  [Indiana](/us-in) |            3,180 |                     4,204 |                     624 |                      1,024 |                                       32% |                                 3,302 |                                  5,753 |
|           [North Carolina](/us-nc) |            2,431 |                     3,901 |                     372 |                      1,470 |                                       60% |                                 3,036 |                                  5,305 |
|           [South Carolina](/us-sc) |            2,360 |                     3,852 |                     748 |                      1,492 |                                       63% |                                 3,078 |                                  4,906 |
|                 [Virginia](/us-va) |            2,410 |                     3,383 |                     396 |                        973 |                                       40% |                                 2,564 |                                  4,951 |
|              [Mississippi](/us-ms) |            2,163 |                     3,197 |                   1,074 |                      1,034 |                                       48% |                                 2,639 |                                  3,902 |
|                  [Alabama](/us-al) |            1,944 |                     2,845 |                     580 |                        901 |                                       46% |                                 2,347 |                                  3,561 |
|               [Washington](/us-wa) |            1,822 |                     2,841 |                     373 |                      1,019 |                                       56% |                                 2,141 |                                  4,102 |
|                [Tennessee](/us-tn) |            1,452 |                     2,672 |                     391 |                      1,220 |                                       84% |                                 2,018 |                                  3,627 |
|                [Minnesota](/us-mn) |            1,784 |                     2,336 |                     414 |                        552 |                                       31% |                                 1,873 |                                  3,194 |
|                 [Colorado](/us-co) |            1,900 |                     2,306 |                     401 |                        406 |                                       21% |                                 1,939 |                                  3,042 |
|                 [Missouri](/us-mo) |            1,434 |                     2,152 |                     351 |                        718 |                                       50% |                                 1,693 |                                  2,898 |
|                   [Nevada](/us-nv) |            1,134 |                     1,962 |                     637 |                        828 |                                       73% |                                 1,535 |                                  2,509 |
|                [Wisconsin](/us-wi) |            1,060 |                     1,598 |                     274 |                        538 |                                       51% |                                 1,244 |                                  2,261 |
|                     [Iowa](/us-ia) |            1,010 |                     1,483 |                     470 |                        473 |                                       47% |                                 1,161 |                                  1,997 |
|                 [Kentucky](/us-ky) |              842 |                     1,315 |                     294 |                        473 |                                       56% |                                 1,007 |                                  1,826 |
|                 [Oklahoma](/us-ok) |              699 |                     1,296 |                     328 |                        597 |                                       85% |                                   936 |                                  1,843 |
|                 [Arkansas](/us-ar) |              631 |                     1,150 |                     381 |                        519 |                                       82% |                                   858 |                                  1,564 |
|             [Rhode Island](/us-ri) |            1,027 |                     1,109 |                   1,047 |                         82 |                                        8% |                                 1,039 |                                  1,262 |
|               [New Mexico](/us-nm) |              729 |                     1,036 |                     494 |                        307 |                                       42% |                                   837 |                                  1,388 |
|              [Puerto Rico](/us-pr) |              356 |                       991 |                     310 |                        635 |                                      178% |                                   624 |                                  1,550 |
|                   [Oregon](/us-or) |              408 |                       808 |                     192 |                        400 |                                       98% |                                   558 |                                  1,192 |
|                 [Delaware](/us-de) |              595 |                       678 |                     697 |                         83 |                                       14% |                                   604 |                                    832 |
|                   [Kansas](/us-ks) |              415 |                       663 |                     228 |                        248 |                                       60% |                                   504 |                                    955 |
|                     [Utah](/us-ut) |              377 |                       657 |                     205 |                        280 |                                       74% |                                   481 |                                    952 |
|     [District of Columbia](/us-dc) |              600 |                       652 |                     924 |                         52 |                                        9% |                                   610 |                                    742 |
|                    [Idaho](/us-id) |              289 |                       626 |                     350 |                        337 |                                      117% |                                   445 |                                    872 |
|                 [Nebraska](/us-ne) |              371 |                       528 |                     273 |                        157 |                                       42% |                                   433 |                                    731 |
|            [New Hampshire](/us-nh) |              427 |                       494 |                     363 |                         67 |                                       16% |                                   431 |                                    648 |
|            [West Virginia](/us-wv) |              166 |                       396 |                     221 |                        230 |                                      139% |                                   254 |                                    635 |
|             [North Dakota](/us-nd) |              130 |                       238 |                     312 |                        108 |                                       83% |                                   173 |                                    347 |
|             [South Dakota](/us-sd) |              155 |                       228 |                     258 |                         73 |                                       47% |                                   182 |                                    317 |
|                  [Montana](/us-mt) |               84 |                       197 |                     184 |                        113 |                                      135% |                                   128 |                                    311 |
|                    [Maine](/us-me) |              127 |                       154 |                     114 |                         27 |                                       21% |                                   132 |                                    195 |
|                   [Hawaii](/us-hi) |               42 |                       134 |                      95 |                         92 |                                      219% |                                    74 |                                    240 |
|                  [Vermont](/us-vt) |               58 |                        73 |                     117 |                         15 |                                       26% |                                    61 |                                    101 |
|                  [Wyoming](/us-wy) |               34 |                        66 |                     114 |                         32 |                                       94% |                                    49 |                                    103 |
|                   [Alaska](/us-ak) |               29 |                        62 |                      84 |                         33 |                                      112% |                                    41 |                                     98 |
|           [Virgin Islands](/us-vi) |                9 |                        16 |                     156 |                          7 |                                       82% |                                    11 |                                     25 |
|                     [Guam](/us-gu) |                5 |                         8 |                      48 |                          3 |                                       59% |                                     5 |                                     14 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      55 |                          1 |                                       53% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,719 |                   204,024 |                     344 |                     17,305 |                                        9% |                               190,914 |                                241,359 |
| [United Kingdom](/united-kingdom) |           41,483 |                    42,490 |                     629 |                      1,007 |                                        2% |                                41,510 |                                 46,308 |
|                   [Italy](/italy) |           35,412 |                    36,046 |                     597 |                        634 |                                        2% |                                35,436 |                                 38,430 |
|                   [Spain](/spain) |           28,797 |                    32,272 |                     688 |                      3,475 |                                       12% |                                29,688 |                                 39,710 |
|                 [France](/france) |           30,434 |                    31,424 |                     469 |                        990 |                                        3% |                                30,477 |                                 35,744 |
|               [Belgium](/belgium) |            9,969 |                    10,545 |                     921 |                        576 |                                        6% |                                10,012 |                                 12,793 |
|               [Germany](/germany) |            9,249 |                     9,955 |                     120 |                        706 |                                        8% |                                 9,298 |                                 12,202 |
|       [Netherlands](/netherlands) |            6,204 |                     6,565 |                     380 |                        361 |                                        6% |                                 6,229 |                                  7,961 |
|               [Romania](/romania) |            3,106 |                     6,083 |                     313 |                      2,977 |                                       96% |                                 4,208 |                                  9,511 |
|                 [Sweden](/sweden) |            5,802 |                     5,955 |                     582 |                        153 |                                        3% |                                 5,828 |                                  6,055 |
|               [Ukraine](/ukraine) |            2,182 |                     4,650 |                     106 |                      2,468 |                                      113% |                                 3,008 |                                  8,159 |
|                 [Poland](/poland) |            1,913 |                     2,945 |                      78 |                      1,032 |                                       54% |                                 2,205 |                                  4,437 |
|       [Switzerland](/switzerland) |            1,996 |                     2,128 |                     248 |                        132 |                                        7% |                                 2,015 |                                  2,507 |
|             [Portugal](/portugal) |            1,786 |                     2,035 |                     198 |                        249 |                                       14% |                                 1,796 |                                  2,606 |
|               [Ireland](/ireland) |            1,775 |                     1,852 |                     378 |                         77 |                                        4% |                                 1,785 |                                  2,080 |
|               [Moldova](/moldova) |              914 |                     1,321 |                     327 |                        407 |                                       45% |                                 1,063 |                                  1,882 |
|             [Bulgaria](/bulgaria) |              527 |                     1,099 |                     157 |                        572 |                                      109% |                                   724 |                                  1,989 |
|                 [Serbia](/serbia) |              684 |                       965 |                     139 |                        281 |                                       41% |                                   796 |                                  1,215 |
|               [Austria](/austria) |              729 |                       816 |                      92 |                         87 |                                       12% |                                   742 |                                  1,044 |
|               [Belarus](/belarus) |              622 |                       814 |                      86 |                        192 |                                       31% |                                   734 |                                    990 |
|               [Denmark](/denmark) |              621 |                       704 |                     121 |                         83 |                                       13% |                                   638 |                                    916 |
|               [Hungary](/hungary) |              609 |                       686 |                      70 |                         77 |                                       13% |                                   616 |                                    876 |
|               [Czechia](/czechia) |              404 |                       578 |                      54 |                        174 |                                       43% |                                   439 |                                    881 |
|                 [Greece](/greece) |              235 |                       482 |                      45 |                        247 |                                      105% |                                   310 |                                    840 |
|               [Finland](/finland) |              334 |                       372 |                      67 |                         38 |                                       11% |                                   341 |                                    479 |
|                 [Norway](/norway) |              262 |                       313 |                      58 |                         51 |                                       19% |                                   275 |                                    428 |
|               [Croatia](/croatia) |              168 |                       274 |                      67 |                        106 |                                       63% |                                   201 |                                    413 |
|         [Luxembourg](/luxembourg) |              124 |                       168 |                     273 |                         44 |                                       35% |                                   138 |                                    223 |
|             [Slovenia](/slovenia) |              129 |                       160 |                      77 |                         31 |                                       24% |                                   134 |                                    216 |
|           [Lithuania](/lithuania) |               81 |                        93 |                      33 |                         12 |                                       14% |                                    84 |                                    117 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     79 |
|             [Slovakia](/slovakia) |               33 |                        64 |                      12 |                         31 |                                       94% |                                    39 |                                    132 |
|                 [Latvia](/latvia) |               33 |                        44 |                      23 |                         11 |                                       34% |                                    35 |                                     64 |
|                 [Cyprus](/cyprus) |               20 |                        29 |                      33 |                          9 |                                       44% |                                    23 |                                     40 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                                       26% |                                    10 |                                     18 |
|                   [Malta](/malta) |                9 |                        12 |                      23 |                          3 |                                       28% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          401,388 |                   662,986 |                     128 |                    261,598 |                                       65% |                               505,708 |                                939,503 |
|                             [Brazil](/brazil) |          111,100 |                   174,538 |                     827 |                     63,438 |                                       57% |                               135,176 |                                238,996 |
|                               [India](/india) |           53,866 |                   120,578 |                      88 |                     66,712 |                                      124% |                                79,430 |                                177,093 |
|                             [Mexico](/mexico) |           58,481 |                    96,306 |                     755 |                     37,825 |                                       65% |                                82,329 |                                128,444 |
|                                 [Peru](/peru) |           26,658 |                    35,907 |                   1,104 |                      9,249 |                                       35% |                                29,261 |                                 47,170 |
|                         [Colombia](/colombia) |           15,979 |                    30,441 |                     605 |                     14,462 |                                       91% |                                22,234 |                                 45,275 |
|                                 [Iran](/iran) |           20,125 |                    27,773 |                     335 |                      7,648 |                                       38% |                                22,864 |                                 36,769 |
|                 [South Africa](/south-africa) |           12,423 |                    22,027 |                     376 |                      9,604 |                                       77% |                                15,890 |                                 31,933 |
|                             [Russia](/russia) |           15,951 |                    21,812 |                     150 |                      5,861 |                                       37% |                                17,728 |                                 30,406 |
|                       [Argentina](/argentina) |            6,330 |                    19,084 |                     426 |                     12,754 |                                      201% |                                11,473 |                                 30,694 |
|                               [Chile](/chile) |           10,578 |                    14,227 |                     751 |                      3,649 |                                       34% |                                11,141 |                                 22,378 |
|                       [Indonesia](/indonesia) |            6,346 |                    10,671 |                      39 |                      4,325 |                                       68% |                                 7,919 |                                 17,328 |
|                             [Canada](/canada) |            9,095 |                     9,507 |                     254 |                        412 |                                        5% |                                 9,129 |                                 10,491 |
|                             [Turkey](/turkey) |            6,039 |                     7,458 |                      89 |                      1,419 |                                       24% |                                 6,168 |                                 11,081 |
|                           [Ecuador](/ecuador) |            6,146 |                     7,420 |                     427 |                      1,274 |                                       21% |                                 6,281 |                                 10,216 |
|                           [Bolivia](/bolivia) |            4,233 |                     7,038 |                     611 |                      2,805 |                                       66% |                                 5,298 |                                 10,439 |
|                   [Philippines](/philippines) |            2,795 |                     7,023 |                      65 |                      4,228 |                                      151% |                                 3,884 |                                 13,875 |
|                         [Pakistan](/pakistan) |            6,201 |                     6,979 |                      32 |                        778 |                                       13% |                                 6,315 |                                  8,079 |
|                               [Egypt](/egypt) |            5,197 |                     5,853 |                      58 |                        656 |                                       13% |                                 5,297 |                                  6,938 |
|                     [Bangladesh](/bangladesh) |            3,781 |                     5,760 |                      35 |                      1,979 |                                       52% |                                 4,265 |                                  8,940 |
|                 [Saudi Arabia](/saudi-arabia) |            3,506 |                     5,192 |                     152 |                      1,686 |                                       48% |                                 4,032 |                                  7,118 |
|                               [China](/china) |            4,706 |                     4,900 |                       3 |                        194 |                                        4% |                                 4,706 |                                  6,265 |
|                           [Morocco](/morocco) |              743 |                     3,370 |                      92 |                      2,627 |                                      354% |                                 1,559 |                                  7,180 |
|                             [Panama](/panama) |            1,827 |                     2,791 |                     657 |                        964 |                                       53% |                                 2,189 |                                  3,853 |
|     [Dominican Republic](/dominican-republic) |            1,501 |                     2,628 |                     245 |                      1,127 |                                       75% |                                 1,885 |                                  4,127 |
|                         [Honduras](/honduras) |            1,608 |                     2,571 |                     264 |                        963 |                                       60% |                                 1,957 |                                  3,771 |
|                               [Japan](/japan) |            1,148 |                     2,338 |                      18 |                      1,190 |                                      104% |                                 1,264 |                                  5,839 |
|                           [Algeria](/algeria) |            1,402 |                     2,165 |                      50 |                        763 |                                       54% |                                 1,575 |                                  3,507 |
|                             [Israel](/israel) |              781 |                     2,044 |                     240 |                      1,263 |                                      162% |                                 1,177 |                                  3,578 |
|                       [Australia](/australia) |              463 |                     1,482 |                      59 |                      1,019 |                                      220% |                                   791 |                                  2,968 |
|                           [Nigeria](/nigeria) |              985 |                     1,288 |                       6 |                        303 |                                       31% |                                 1,044 |                                  1,935 |
|                             [Kuwait](/kuwait) |              507 |                       738 |                     175 |                        231 |                                       46% |                                   544 |                                  1,247 |
| [United Arab Emirates](/united-arab-emirates) |              367 |                       455 |                      47 |                         88 |                                       24% |                                   372 |                                    684 |
|                   [South Korea](/south-korea) |              307 |                       357 |                       7 |                         50 |                                       16% |                                   307 |                                    526 |
|                         [Malaysia](/malaysia) |              125 |                       140 |                       4 |                         15 |                                       12% |                                   129 |                                    156 |
|                                 [Cuba](/cuba) |               88 |                       125 |                      11 |                         37 |                                       42% |                                    95 |                                    204 |
