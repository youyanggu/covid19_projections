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
* **July 21:** View our [updated historical performance](/about/#historical-performance).
* **July 8:** We have extended our projections through November 1, 2020. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 22 (11pm ET):
<p align="center">
  Current Total: <b>141,992</b> deaths | Projected Total: <b>213,600 deaths by Nov 1, 2020</b> (Range: 181-265k)<br>
  Currently Infected: <b>1.9%</b> | Total Infected: <b>9.5%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 22, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |         Aug 1, 2020 |
|              175,000 |         Sep 1, 2020 |
|              200,000 |        Oct 22, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        65% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          5% |        52% |         83% |        97% |         99% |        99% |
|              200,000 |        <1% |         <1% |         4% |         17% |        34% |         48% |        60% |
|              225,000 |        <1% |         <1% |        <1% |          2% |         8% |         13% |        21% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          3% |         7% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |
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
|             *[United States](/us)* |          141,992 |                   213,646 |                     644 |                     71,654 |                                       50% |                               181,439 |                                264,474 |
|                 [New York](/us-ny) |           32,520 |                    33,026 |                   1,698 |                        506 |                                        2% |                                32,549 |                                 34,983 |
|               [New Jersey](/us-nj) |           15,737 |                    16,559 |                   1,864 |                        822 |                                        5% |                                15,848 |                                 17,906 |
|               [California](/us-ca) |            7,888 |                    16,013 |                     405 |                      8,125 |                                      103% |                                10,720 |                                 24,583 |
|                  [Florida](/us-fl) |            5,206 |                    13,940 |                     649 |                      8,734 |                                      168% |                                 8,943 |                                 22,137 |
|                    [Texas](/us-tx) |            4,199 |                    13,762 |                     475 |                      9,563 |                                      228% |                                 8,408 |                                 22,554 |
|             [Pennsylvania](/us-pa) |            7,051 |                     9,459 |                     739 |                      2,408 |                                       34% |                                 7,370 |                                 14,279 |
|                 [Illinois](/us-il) |            7,517 |                     9,165 |                     723 |                      1,648 |                                       22% |                                 7,856 |                                 11,652 |
|            [Massachusetts](/us-ma) |            8,450 |                     9,090 |                   1,308 |                        640 |                                        8% |                                 8,549 |                                 10,171 |
|                 [Michigan](/us-mi) |            6,382 |                     7,383 |                     739 |                      1,001 |                                       16% |                                 6,528 |                                  9,393 |
|                  [Arizona](/us-az) |            2,918 |                     6,877 |                     945 |                      3,959 |                                      136% |                                 4,868 |                                  9,886 |
|                  [Georgia](/us-ga) |            3,254 |                     6,416 |                     604 |                      3,162 |                                       97% |                                 4,071 |                                 11,349 |
|                     [Ohio](/us-oh) |            3,219 |                     6,006 |                     514 |                      2,787 |                                       87% |                                 3,867 |                                 10,805 |
|                [Louisiana](/us-la) |            3,498 |                     5,697 |                   1,225 |                      2,199 |                                       63% |                                 4,005 |                                  8,967 |
|              [Connecticut](/us-ct) |            4,406 |                     4,669 |                   1,310 |                        263 |                                        6% |                                 4,450 |                                  5,153 |
|                  [Indiana](/us-in) |            2,846 |                     4,405 |                     654 |                      1,559 |                                       55% |                                 3,118 |                                  7,711 |
|                 [Maryland](/us-md) |            3,402 |                     4,120 |                     681 |                        718 |                                       21% |                                 3,528 |                                  5,410 |
|                 [Virginia](/us-va) |            2,048 |                     3,721 |                     436 |                      1,673 |                                       82% |                                 2,300 |                                  7,250 |
|           [North Carolina](/us-nc) |            1,705 |                     3,595 |                     343 |                      1,890 |                                      111% |                                 2,253 |                                  6,112 |
|           [South Carolina](/us-sc) |            1,221 |                     3,271 |                     635 |                      2,050 |                                      168% |                                 2,109 |                                  5,045 |
|                  [Alabama](/us-al) |            1,303 |                     3,171 |                     647 |                      1,868 |                                      143% |                                 2,059 |                                  5,046 |
|                 [Colorado](/us-co) |            1,763 |                     2,779 |                     483 |                      1,016 |                                       58% |                                 1,966 |                                  4,931 |
|              [Mississippi](/us-ms) |            1,389 |                     2,623 |                     881 |                      1,234 |                                       89% |                                 1,860 |                                  3,903 |
|                [Minnesota](/us-mn) |            1,588 |                     2,515 |                     446 |                        927 |                                       58% |                                 1,787 |                                  4,410 |
|                [Tennessee](/us-tn) |              871 |                     2,254 |                     330 |                      1,383 |                                      159% |                                 1,457 |                                  3,679 |
|                   [Nevada](/us-nv) |              676 |                     2,147 |                     697 |                      1,471 |                                      218% |                                 1,193 |                                  3,741 |
|                 [Missouri](/us-mo) |            1,148 |                     2,102 |                     343 |                        954 |                                       83% |                                 1,348 |                                  3,938 |
|               [Washington](/us-wa) |            1,465 |                     2,000 |                     263 |                        535 |                                       37% |                                 1,543 |                                  3,028 |
|                 [Kentucky](/us-ky) |              674 |                     1,957 |                     438 |                      1,283 |                                      190% |                                   915 |                                  4,453 |
|                [Wisconsin](/us-wi) |              859 |                     1,770 |                     304 |                        911 |                                      106% |                                 1,046 |                                  3,785 |
|                     [Iowa](/us-ia) |              806 |                     1,539 |                     488 |                        733 |                                       91% |                                   982 |                                  2,845 |
|             [Rhode Island](/us-ri) |              996 |                     1,175 |                   1,109 |                        179 |                                       18% |                                 1,029 |                                  1,409 |
|               [New Mexico](/us-nm) |              588 |                     1,147 |                     547 |                        559 |                                       95% |                                   673 |                                  2,142 |
|                   [Oregon](/us-or) |              269 |                     1,006 |                     239 |                        737 |                                      274% |                                   473 |                                  2,130 |
|                 [Arkansas](/us-ar) |              374 |                       975 |                     323 |                        601 |                                      161% |                                   597 |                                  1,620 |
|                 [Oklahoma](/us-ok) |              461 |                       904 |                     228 |                        443 |                                       96% |                                   575 |                                  1,560 |
|                     [Utah](/us-ut) |              251 |                       792 |                     247 |                        541 |                                      215% |                                   444 |                                  1,407 |
|                    [Idaho](/us-id) |              126 |                       781 |                     437 |                        655 |                                      520% |                                   328 |                                  1,695 |
|                 [Delaware](/us-de) |              525 |                       659 |                     677 |                        134 |                                       26% |                                   552 |                                    902 |
|     [District of Columbia](/us-dc) |              580 |                       654 |                     927 |                         74 |                                       13% |                                   595 |                                    774 |
|                   [Kansas](/us-ks) |              316 |                       622 |                     214 |                        306 |                                       97% |                                   395 |                                  1,142 |
|              [Puerto Rico](/us-pr) |              180 |                       543 |                     170 |                        363 |                                      201% |                                   233 |                                  1,422 |
|            [New Hampshire](/us-nh) |              400 |                       530 |                     390 |                        130 |                                       32% |                                   414 |                                    771 |
|                 [Nebraska](/us-ne) |              310 |                       515 |                     266 |                        205 |                                       66% |                                   347 |                                    860 |
|             [South Dakota](/us-sd) |              118 |                       225 |                     255 |                        107 |                                       91% |                                   148 |                                    378 |
|                  [Montana](/us-mt) |               40 |                       224 |                     210 |                        184 |                                      460% |                                    95 |                                    476 |
|             [North Dakota](/us-nd) |               94 |                       198 |                     260 |                        104 |                                      111% |                                   110 |                                    393 |
|            [West Virginia](/us-wv) |              101 |                       196 |                     109 |                         95 |                                       94% |                                   122 |                                    415 |
|                    [Maine](/us-me) |              118 |                       170 |                     126 |                         52 |                                       44% |                                   128 |                                    252 |
|                  [Vermont](/us-vt) |               56 |                        75 |                     120 |                         19 |                                       33% |                                    61 |                                     99 |
|                   [Hawaii](/us-hi) |               24 |                        73 |                      52 |                         49 |                                      204% |                                    31 |                                    197 |
|                  [Wyoming](/us-wy) |               25 |                        63 |                     109 |                         38 |                                      152% |                                    38 |                                    117 |
|                   [Alaska](/us-ak) |               18 |                        55 |                      75 |                         37 |                                      207% |                                    27 |                                    130 |
|           [Virgin Islands](/us-vi) |                6 |                        18 |                     170 |                         12 |                                      197% |                                     7 |                                     57 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     6 |                                     20 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      73 |                          2 |                                      103% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,215 |                   198,632 |                     335 |                     12,417 |                                        7% |                               189,904 |                                218,797 |
| [United Kingdom](/united-kingdom) |           45,507 |                    46,899 |                     694 |                      1,392 |                                        3% |                                45,600 |                                 49,585 |
|                   [Italy](/italy) |           35,073 |                    35,564 |                     589 |                        491 |                                        1% |                                35,103 |                                 36,393 |
|                 [France](/france) |           30,168 |                    30,648 |                     457 |                        480 |                                        2% |                                30,192 |                                 33,069 |
|                   [Spain](/spain) |           28,424 |                    28,768 |                     613 |                        344 |                                        1% |                                28,445 |                                 30,156 |
|               [Belgium](/belgium) |            9,805 |                     9,892 |                     864 |                         87 |                                        1% |                                 9,821 |                                 10,169 |
|               [Germany](/germany) |            9,099 |                     9,700 |                     117 |                        601 |                                        7% |                                 9,133 |                                 11,700 |
|       [Netherlands](/netherlands) |            6,155 |                     6,210 |                     359 |                         55 |                                        1% |                                 6,165 |                                  6,329 |
|                 [Sweden](/sweden) |            5,646 |                     6,054 |                     592 |                        408 |                                        7% |                                 5,764 |                                  6,515 |
|               [Romania](/romania) |            2,074 |                     4,147 |                     214 |                      2,073 |                                      100% |                                 3,055 |                                  6,161 |
|               [Ukraine](/ukraine) |            1,537 |                     3,116 |                      71 |                      1,579 |                                      103% |                                 2,207 |                                  4,968 |
|                 [Poland](/poland) |            1,636 |                     2,155 |                      57 |                        519 |                                       32% |                                 1,709 |                                  3,143 |
|             [Portugal](/portugal) |            1,697 |                     2,140 |                     208 |                        443 |                                       26% |                                 1,757 |                                  2,815 |
|       [Switzerland](/switzerland) |            1,972 |                     2,040 |                     237 |                         68 |                                        3% |                                 1,984 |                                  2,227 |
|               [Ireland](/ireland) |            1,753 |                     1,824 |                     372 |                         71 |                                        4% |                                 1,764 |                                  2,046 |
|                 [Serbia](/serbia) |              491 |                     1,748 |                     251 |                      1,257 |                                      256% |                                 1,106 |                                  2,799 |
|               [Moldova](/moldova) |              707 |                     1,506 |                     372 |                        799 |                                      113% |                                   956 |                                  2,251 |
|               [Belarus](/belarus) |              507 |                       994 |                     105 |                        487 |                                       96% |                                   799 |                                  1,413 |
|             [Bulgaria](/bulgaria) |              313 |                       835 |                     119 |                        522 |                                      167% |                                   509 |                                  1,470 |
|               [Austria](/austria) |              710 |                       775 |                      87 |                         65 |                                        9% |                                   727 |                                    892 |
|               [Hungary](/hungary) |              596 |                       700 |                      72 |                        104 |                                       17% |                                   609 |                                    928 |
|               [Denmark](/denmark) |              611 |                       687 |                     118 |                         76 |                                       12% |                                   629 |                                    803 |
|               [Czechia](/czechia) |              360 |                       470 |                      44 |                        110 |                                       31% |                                   393 |                                    633 |
|               [Finland](/finland) |              328 |                       380 |                      69 |                         52 |                                       16% |                                   340 |                                    468 |
|                 [Norway](/norway) |              255 |                       284 |                      53 |                         29 |                                       12% |                                   263 |                                    330 |
|               [Croatia](/croatia) |              123 |                       245 |                      60 |                        122 |                                      100% |                                   157 |                                    412 |
|                 [Greece](/greece) |              197 |                       237 |                      22 |                         40 |                                       20% |                                   207 |                                    289 |
|         [Luxembourg](/luxembourg) |              111 |                       156 |                     254 |                         45 |                                       41% |                                   126 |                                    216 |
|             [Slovenia](/slovenia) |              114 |                       135 |                      65 |                         21 |                                       18% |                                   118 |                                    171 |
|           [Lithuania](/lithuania) |               80 |                       103 |                      37 |                         23 |                                       28% |                                    84 |                                    134 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    77 |                                    122 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       31% |                                    33 |                                     60 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       27% |                                    29 |                                     51 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       49% |                                    22 |                                     42 |
|                   [Malta](/malta) |                9 |                        14 |                      29 |                          5 |                                       58% |                                    11 |                                     17 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       35% |                                    10 |                                     20 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          271,442 |                   616,171 |                     119 |                    344,729 |                                      127% |                               400,305 |                                954,297 |
|                             [Brazil](/brazil) |           81,487 |                   158,317 |                     750 |                     76,830 |                                       94% |                               117,785 |                                228,985 |
|                               [India](/india) |           28,732 |                   128,762 |                      94 |                    100,030 |                                      348% |                                58,941 |                                202,944 |
|                             [Mexico](/mexico) |           40,400 |                    84,563 |                     663 |                     44,163 |                                      109% |                                61,894 |                                134,927 |
|                                 [Iran](/iran) |           14,634 |                    27,641 |                     333 |                     13,007 |                                       89% |                                20,657 |                                 37,625 |
|                                 [Peru](/peru) |           13,579 |                    24,737 |                     761 |                     11,158 |                                       82% |                                16,060 |                                 40,239 |
|                         [Colombia](/colombia) |            7,166 |                    24,319 |                     483 |                     17,153 |                                      239% |                                16,268 |                                 35,094 |
|                             [Russia](/russia) |           12,561 |                    22,394 |                     154 |                      9,833 |                                       78% |                                14,498 |                                 38,027 |
|                 [South Africa](/south-africa) |            5,368 |                    17,581 |                     300 |                     12,213 |                                      228% |                                 9,663 |                                 24,079 |
|                       [Indonesia](/indonesia) |            4,320 |                    17,283 |                      64 |                     12,963 |                                      300% |                                 7,904 |                                 34,765 |
|                               [Chile](/chile) |            8,677 |                    12,410 |                     655 |                      3,733 |                                       43% |                                 9,465 |                                 20,310 |
|                             [Canada](/canada) |            8,908 |                     9,632 |                     257 |                        724 |                                        8% |                                 8,942 |                                 11,418 |
|                       [Argentina](/argentina) |            2,490 |                     9,530 |                     213 |                      7,040 |                                      283% |                                 5,353 |                                 15,038 |
|                           [Ecuador](/ecuador) |            5,366 |                     8,326 |                     479 |                      2,960 |                                       55% |                                 5,995 |                                 12,207 |
|                         [Pakistan](/pakistan) |            5,677 |                     8,223 |                      38 |                      2,546 |                                       45% |                                 6,438 |                                 11,908 |
|                               [Egypt](/egypt) |            4,399 |                     8,048 |                      80 |                      3,649 |                                       83% |                                 5,205 |                                 12,853 |
|                             [Turkey](/turkey) |            5,526 |                     7,618 |                      91 |                      2,092 |                                       38% |                                 5,766 |                                 11,130 |
|                           [Bolivia](/bolivia) |            2,273 |                     6,098 |                     530 |                      3,825 |                                      168% |                                 4,091 |                                  9,422 |
|                   [Philippines](/philippines) |            1,837 |                     5,653 |                      52 |                      3,816 |                                      208% |                                 2,234 |                                 13,356 |
|                     [Bangladesh](/bangladesh) |            2,709 |                     5,373 |                      33 |                      2,664 |                                       98% |                                 3,202 |                                 10,124 |
|                 [Saudi Arabia](/saudi-arabia) |            2,557 |                     4,932 |                     144 |                      2,375 |                                       93% |                                 3,445 |                                  7,352 |
|                               [China](/china) |            4,644 |                     4,664 |                       3 |                         20 |                                        0% |                                 4,644 |                                  4,795 |
|                         [Honduras](/honduras) |              988 |                     3,828 |                     393 |                      2,840 |                                      287% |                                 2,189 |                                  6,709 |
|                             [Panama](/panama) |            1,159 |                     3,678 |                     866 |                      2,519 |                                      217% |                                 2,416 |                                  5,730 |
|                           [Algeria](/algeria) |            1,100 |                     2,352 |                      55 |                      1,252 |                                      114% |                                 1,291 |                                  4,642 |
|     [Dominican Republic](/dominican-republic) |              999 |                     2,276 |                     212 |                      1,277 |                                      128% |                                 1,382 |                                  3,956 |
|                           [Nigeria](/nigeria) |              805 |                     1,618 |                       8 |                        813 |                                      101% |                                   939 |                                  3,758 |
|                               [Japan](/japan) |              988 |                     1,570 |                      12 |                        582 |                                       59% |                                 1,008 |                                  3,669 |
|                             [Israel](/israel) |              425 |                     1,519 |                     178 |                      1,094 |                                      257% |                                   768 |                                  2,629 |
|                           [Morocco](/morocco) |              280 |                       760 |                      21 |                        480 |                                      171% |                                   368 |                                  1,590 |
|                       [Australia](/australia) |              128 |                       704 |                      28 |                        576 |                                      450% |                                   177 |                                  2,102 |
|                             [Kuwait](/kuwait) |              412 |                       612 |                     146 |                        200 |                                       49% |                                   436 |                                  1,065 |
| [United Arab Emirates](/united-arab-emirates) |              341 |                       461 |                      47 |                        120 |                                       35% |                                   351 |                                    767 |
|                   [South Korea](/south-korea) |              297 |                       416 |                       8 |                        119 |                                       40% |                                   302 |                                    749 |
|                         [Malaysia](/malaysia) |              123 |                       161 |                       5 |                         38 |                                       31% |                                   136 |                                    182 |
|                                 [Cuba](/cuba) |               87 |                       112 |                      10 |                         25 |                                       29% |                                    92 |                                    151 |
