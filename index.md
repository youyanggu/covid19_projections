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
### Updated Daily - Last Updated: July 21 (3am ET):
<p align="center">
  Current Total: <b>140,903</b> deaths | Projected Total: <b>212,800 deaths by Nov 1, 2020</b> (Range: 177-271k)<br>
  Currently Infected: <b>1.6%</b> | Total Infected: <b>8.5%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 21, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 18, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |         Sep 3, 2020 |
|              200,000 |        Oct 27, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        52% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          4% |        46% |         74% |        90% |         96% |        99% |
|              200,000 |        <1% |         <1% |         4% |         15% |        31% |         42% |        53% |
|              225,000 |        <1% |         <1% |        <1% |          2% |         8% |         13% |        20% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         1% |          4% |         8% |
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
|             *[United States](/us)* |          140,903 |                   212,774 |                     641 |                     71,871 |                                       51% |                               177,548 |                                270,597 |
|                 [New York](/us-ny) |           32,506 |                    33,737 |                   1,734 |                      1,231 |                                        4% |                                32,549 |                                 38,362 |
|               [New Jersey](/us-nj) |           15,715 |                    17,170 |                   1,933 |                      1,455 |                                        9% |                                15,809 |                                 19,542 |
|               [California](/us-ca) |            7,770 |                    16,072 |                     407 |                      8,302 |                                      107% |                                 9,854 |                                 26,173 |
|                  [Florida](/us-fl) |            5,072 |                    15,800 |                     736 |                     10,728 |                                      212% |                                 9,321 |                                 26,049 |
|                    [Texas](/us-tx) |            4,106 |                    13,641 |                     470 |                      9,535 |                                      232% |                                 8,258 |                                 24,153 |
|            [Massachusetts](/us-ma) |            8,433 |                     9,477 |                   1,364 |                      1,044 |                                       12% |                                 8,556 |                                 11,835 |
|             [Pennsylvania](/us-pa) |            7,018 |                     8,755 |                     684 |                      1,737 |                                       25% |                                 7,180 |                                 12,550 |
|                 [Illinois](/us-il) |            7,494 |                     8,504 |                     671 |                      1,010 |                                       13% |                                 7,655 |                                  9,746 |
|                 [Michigan](/us-mi) |            6,373 |                     7,672 |                     768 |                      1,299 |                                       20% |                                 6,465 |                                 10,536 |
|                  [Arizona](/us-az) |            2,784 |                     6,492 |                     892 |                      3,708 |                                      133% |                                 4,479 |                                 10,115 |
|                     [Ohio](/us-oh) |            3,189 |                     5,920 |                     506 |                      2,731 |                                       86% |                                 3,710 |                                 11,089 |
|                  [Georgia](/us-ga) |            3,177 |                     5,827 |                     549 |                      2,650 |                                       83% |                                 3,853 |                                 11,152 |
|                [Louisiana](/us-la) |            3,462 |                     5,642 |                   1,214 |                      2,180 |                                       63% |                                 3,962 |                                  9,070 |
|              [Connecticut](/us-ct) |            4,406 |                     4,638 |                   1,301 |                        232 |                                        5% |                                 4,427 |                                  5,057 |
|                 [Maryland](/us-md) |            3,382 |                     4,479 |                     741 |                      1,097 |                                       32% |                                 3,523 |                                  7,010 |
|                  [Indiana](/us-in) |            2,825 |                     3,904 |                     580 |                      1,079 |                                       38% |                                 2,946 |                                  6,575 |
|                  [Alabama](/us-al) |            1,291 |                     3,511 |                     716 |                      2,220 |                                      172% |                                 2,044 |                                  6,137 |
|           [North Carolina](/us-nc) |            1,677 |                     3,370 |                     321 |                      1,693 |                                      101% |                                 2,235 |                                  5,836 |
|                 [Virginia](/us-va) |            2,031 |                     3,331 |                     390 |                      1,300 |                                       64% |                                 2,159 |                                  5,754 |
|           [South Carolina](/us-sc) |            1,164 |                     3,096 |                     601 |                      1,932 |                                      166% |                                 1,813 |                                  5,447 |
|                 [Colorado](/us-co) |            1,758 |                     2,764 |                     480 |                      1,006 |                                       57% |                                 1,866 |                                  5,341 |
|                [Minnesota](/us-mn) |            1,585 |                     2,519 |                     447 |                        934 |                                       59% |                                 1,698 |                                  4,524 |
|              [Mississippi](/us-ms) |            1,358 |                     2,513 |                     844 |                      1,155 |                                       85% |                                 1,721 |                                  3,928 |
|                [Tennessee](/us-tn) |              847 |                     2,398 |                     351 |                      1,551 |                                      183% |                                 1,391 |                                  4,390 |
|               [Washington](/us-wa) |            1,453 |                     2,227 |                     292 |                        774 |                                       53% |                                 1,570 |                                  4,073 |
|                 [Missouri](/us-mo) |            1,138 |                     2,073 |                     338 |                        935 |                                       82% |                                 1,309 |                                  4,161 |
|                 [Kentucky](/us-ky) |              671 |                     1,818 |                     407 |                      1,147 |                                      171% |                                   882 |                                  4,338 |
|                   [Nevada](/us-nv) |              648 |                     1,754 |                     569 |                      1,106 |                                      171% |                                 1,021 |                                  3,310 |
|                [Wisconsin](/us-wi) |              846 |                     1,535 |                     264 |                        689 |                                       81% |                                   963 |                                  3,380 |
|                     [Iowa](/us-ia) |              798 |                     1,239 |                     393 |                        441 |                                       55% |                                   834 |                                  2,267 |
|               [New Mexico](/us-nm) |              578 |                     1,178 |                     562 |                        600 |                                      104% |                                   654 |                                  2,668 |
|             [Rhode Island](/us-ri) |              995 |                     1,124 |                   1,061 |                        129 |                                       13% |                                 1,014 |                                  1,280 |
|                 [Oklahoma](/us-ok) |              452 |                       932 |                     236 |                        480 |                                      106% |                                   584 |                                  1,607 |
|                 [Arkansas](/us-ar) |              363 |                       897 |                     297 |                        534 |                                      147% |                                   551 |                                  1,567 |
|                   [Oregon](/us-or) |              262 |                       829 |                     197 |                        567 |                                      216% |                                   377 |                                  2,018 |
|                     [Utah](/us-ut) |              247 |                       780 |                     243 |                        533 |                                      216% |                                   425 |                                  1,551 |
|     [District of Columbia](/us-dc) |              579 |                       695 |                     985 |                        116 |                                       20% |                                   596 |                                    945 |
|                    [Idaho](/us-id) |              122 |                       660 |                     369 |                        538 |                                      441% |                                   260 |                                  1,589 |
|                 [Delaware](/us-de) |              523 |                       654 |                     672 |                        131 |                                       25% |                                   538 |                                    946 |
|                   [Kansas](/us-ks) |              312 |                       627 |                     215 |                        315 |                                      101% |                                   364 |                                  1,362 |
|                 [Nebraska](/us-ne) |              313 |                       515 |                     266 |                        202 |                                       65% |                                   369 |                                    796 |
|            [New Hampshire](/us-nh) |              398 |                       449 |                     330 |                         51 |                                       13% |                                   403 |                                    504 |
|              [Puerto Rico](/us-pr) |              180 |                       393 |                     123 |                        213 |                                      118% |                                   205 |                                    965 |
|             [South Dakota](/us-sd) |              118 |                       201 |                     227 |                         83 |                                       70% |                                   140 |                                    325 |
|                    [Maine](/us-me) |              117 |                       181 |                     135 |                         64 |                                       55% |                                   126 |                                    333 |
|                  [Montana](/us-mt) |               39 |                       181 |                     169 |                        142 |                                      364% |                                    60 |                                    516 |
|             [North Dakota](/us-nd) |               93 |                       165 |                     217 |                         72 |                                       77% |                                   104 |                                    321 |
|            [West Virginia](/us-wv) |              100 |                       152 |                      85 |                         52 |                                       52% |                                   108 |                                    291 |
|                  [Vermont](/us-vt) |               56 |                        81 |                     130 |                         25 |                                       45% |                                    58 |                                    200 |
|                   [Hawaii](/us-hi) |               24 |                        69 |                      49 |                         45 |                                      188% |                                    26 |                                    236 |
|                   [Alaska](/us-ak) |               18 |                        53 |                      72 |                         35 |                                      194% |                                    22 |                                    174 |
|                  [Wyoming](/us-wy) |               24 |                        52 |                      90 |                         28 |                                      117% |                                    31 |                                    111 |
|           [Virgin Islands](/us-vi) |                6 |                        15 |                     143 |                          9 |                                      150% |                                     6 |                                     45 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     5 |                                     45 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      9 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          185,982 |                   199,695 |                     337 |                     13,713 |                                        7% |                               189,134 |                                220,518 |
| [United Kingdom](/united-kingdom) |           45,397 |                    49,125 |                     727 |                      3,728 |                                        8% |                                45,814 |                                 54,725 |
|                   [Italy](/italy) |           35,058 |                    35,460 |                     587 |                        402 |                                        1% |                                35,094 |                                 35,849 |
|                 [France](/france) |           30,180 |                    30,654 |                     457 |                        474 |                                        2% |                                30,193 |                                 33,200 |
|                   [Spain](/spain) |           28,422 |                    28,639 |                     610 |                        217 |                                        1% |                                28,441 |                                 29,213 |
|               [Belgium](/belgium) |            9,805 |                     9,915 |                     866 |                        110 |                                        1% |                                 9,815 |                                 10,277 |
|               [Germany](/germany) |            9,094 |                     9,338 |                     112 |                        244 |                                        3% |                                 9,116 |                                  9,852 |
|       [Netherlands](/netherlands) |            6,155 |                     6,232 |                     361 |                         77 |                                        1% |                                 6,167 |                                  6,331 |
|                 [Sweden](/sweden) |            5,639 |                     6,013 |                     588 |                        374 |                                        7% |                                 5,752 |                                  6,169 |
|               [Romania](/romania) |            2,038 |                     3,930 |                     202 |                      1,892 |                                       93% |                                 2,827 |                                  5,525 |
|               [Ukraine](/ukraine) |            1,517 |                     2,738 |                      62 |                      1,221 |                                       80% |                                 2,010 |                                  3,720 |
|             [Portugal](/portugal) |            1,691 |                     2,150 |                     209 |                        459 |                                       27% |                                 1,746 |                                  3,068 |
|                 [Poland](/poland) |            1,627 |                     2,144 |                      56 |                        517 |                                       32% |                                 1,820 |                                  2,729 |
|       [Switzerland](/switzerland) |            1,971 |                     2,046 |                     238 |                         75 |                                        4% |                                 1,980 |                                  2,400 |
|                 [Serbia](/serbia) |              482 |                     1,954 |                     281 |                      1,472 |                                      305% |                                   831 |                                  4,253 |
|               [Ireland](/ireland) |            1,753 |                     1,821 |                     371 |                         68 |                                        4% |                                 1,758 |                                  2,198 |
|               [Moldova](/moldova) |              695 |                     1,261 |                     312 |                        566 |                                       81% |                                   926 |                                  1,914 |
|               [Belarus](/belarus) |              503 |                     1,081 |                     114 |                        578 |                                      115% |                                   645 |                                  1,912 |
|             [Bulgaria](/bulgaria) |              308 |                       897 |                     128 |                        589 |                                      191% |                                   470 |                                  1,532 |
|               [Austria](/austria) |              711 |                       816 |                      92 |                        105 |                                       15% |                                   722 |                                  1,050 |
|               [Hungary](/hungary) |              596 |                       680 |                      70 |                         84 |                                       14% |                                   604 |                                    928 |
|               [Denmark](/denmark) |              611 |                       645 |                     111 |                         34 |                                        6% |                                   621 |                                    706 |
|               [Czechia](/czechia) |              359 |                       492 |                      46 |                        133 |                                       37% |                                   366 |                                    737 |
|               [Finland](/finland) |              328 |                       356 |                      65 |                         28 |                                        9% |                                   330 |                                    445 |
|                 [Norway](/norway) |              255 |                       272 |                      51 |                         17 |                                        7% |                                   259 |                                    307 |
|               [Croatia](/croatia) |              122 |                       233 |                      57 |                        111 |                                       91% |                                   137 |                                    377 |
|                 [Greece](/greece) |              195 |                       221 |                      21 |                         26 |                                       13% |                                   203 |                                    272 |
|         [Luxembourg](/luxembourg) |              111 |                       141 |                     230 |                         30 |                                       27% |                                   115 |                                    181 |
|             [Slovenia](/slovenia) |              113 |                       123 |                      59 |                         10 |                                        9% |                                   114 |                                    156 |
|           [Lithuania](/lithuania) |               80 |                       105 |                      38 |                         25 |                                       31% |                                    85 |                                    147 |
|               [Estonia](/estonia) |               69 |                        81 |                      61 |                         12 |                                       17% |                                    73 |                                     99 |
|             [Slovakia](/slovakia) |               28 |                        41 |                       8 |                         13 |                                       46% |                                    28 |                                     79 |
|                 [Latvia](/latvia) |               31 |                        38 |                      20 |                          7 |                                       23% |                                    32 |                                     70 |
|                 [Cyprus](/cyprus) |               19 |                        29 |                      33 |                         10 |                                       53% |                                    20 |                                     61 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     23 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          266,513 |                   585,643 |                     113 |                    319,130 |                                      120% |                               391,831 |                                973,881 |
|                             [Brazil](/brazil) |           80,120 |                   152,808 |                     724 |                     72,688 |                                       91% |                               118,090 |                                223,320 |
|                               [India](/india) |           28,082 |                   112,666 |                      82 |                     84,584 |                                      301% |                                54,351 |                                253,223 |
|                             [Mexico](/mexico) |           39,485 |                    77,604 |                     608 |                     38,119 |                                       97% |                                54,123 |                                117,835 |
|                                 [Iran](/iran) |           14,405 |                    31,422 |                     379 |                     17,017 |                                      118% |                                21,253 |                                 47,778 |
|                                 [Peru](/peru) |           13,187 |                    23,981 |                     738 |                     10,794 |                                       82% |                                17,099 |                                 35,576 |
|                         [Colombia](/colombia) |            6,929 |                    22,295 |                     443 |                     15,366 |                                      222% |                                14,526 |                                 35,304 |
|                             [Russia](/russia) |           12,408 |                    21,230 |                     146 |                      8,822 |                                       71% |                                15,152 |                                 33,969 |
|                 [South Africa](/south-africa) |            5,173 |                    18,173 |                     310 |                     13,000 |                                      251% |                                12,260 |                                 24,860 |
|                       [Indonesia](/indonesia) |            4,239 |                    15,329 |                      57 |                     11,090 |                                      262% |                                 7,531 |                                 28,720 |
|                               [Chile](/chile) |            8,503 |                    12,919 |                     682 |                      4,416 |                                       52% |                                 9,227 |                                 18,695 |
|                             [Canada](/canada) |            8,902 |                     9,479 |                     253 |                        577 |                                        6% |                                 8,953 |                                 10,224 |
|                       [Argentina](/argentina) |            2,373 |                     8,833 |                     197 |                      6,460 |                                      272% |                                 5,652 |                                 13,110 |
|                         [Pakistan](/pakistan) |            5,639 |                     8,558 |                      40 |                      2,919 |                                       52% |                                 6,570 |                                 13,543 |
|                               [Egypt](/egypt) |            4,352 |                     8,502 |                      85 |                      4,150 |                                       95% |                                 5,889 |                                 11,989 |
|                           [Ecuador](/ecuador) |            5,318 |                     7,782 |                     448 |                      2,464 |                                       46% |                                 5,596 |                                 12,382 |
|                             [Turkey](/turkey) |            5,508 |                     6,737 |                      81 |                      1,229 |                                       22% |                                 5,581 |                                 10,108 |
|                           [Bolivia](/bolivia) |            2,218 |                     5,654 |                     491 |                      3,436 |                                      155% |                                 3,706 |                                  7,524 |
|                     [Bangladesh](/bangladesh) |            2,668 |                     5,491 |                      34 |                      2,823 |                                      106% |                                 3,792 |                                  9,544 |
|                   [Philippines](/philippines) |            1,835 |                     5,117 |                      47 |                      3,282 |                                      179% |                                 2,523 |                                 11,085 |
|                 [Saudi Arabia](/saudi-arabia) |            2,523 |                     5,065 |                     148 |                      2,542 |                                      101% |                                 3,716 |                                  6,267 |
|                               [China](/china) |            4,644 |                     4,646 |                       3 |                          2 |                                        0% |                                 4,644 |                                  4,663 |
|                           [Algeria](/algeria) |            1,087 |                     3,869 |                      90 |                      2,782 |                                      256% |                                 1,318 |                                 12,891 |
|                         [Honduras](/honduras) |              935 |                     3,533 |                     363 |                      2,598 |                                      278% |                                 2,033 |                                  6,003 |
|                             [Panama](/panama) |            1,127 |                     3,431 |                     808 |                      2,304 |                                      204% |                                 2,361 |                                  4,930 |
|     [Dominican Republic](/dominican-republic) |              993 |                     3,135 |                     292 |                      2,142 |                                      216% |                                 1,449 |                                  6,013 |
|                               [Japan](/japan) |              988 |                     1,655 |                      13 |                        667 |                                       68% |                                   999 |                                  2,888 |
|                           [Nigeria](/nigeria) |              801 |                     1,639 |                       8 |                        838 |                                      105% |                                 1,006 |                                  3,379 |
|                             [Israel](/israel) |              415 |                     1,415 |                     166 |                      1,000 |                                      241% |                                   663 |                                  2,898 |
|                             [Kuwait](/kuwait) |              408 |                       673 |                     160 |                        265 |                                       65% |                                   441 |                                  1,300 |
|                           [Morocco](/morocco) |              276 |                       563 |                      15 |                        287 |                                      104% |                                   321 |                                    995 |
| [United Arab Emirates](/united-arab-emirates) |              340 |                       483 |                      49 |                        143 |                                       42% |                                   351 |                                    979 |
|                       [Australia](/australia) |              126 |                       366 |                      15 |                        240 |                                      190% |                                   133 |                                  1,132 |
|                   [South Korea](/south-korea) |              296 |                       337 |                       7 |                         41 |                                       14% |                                   297 |                                    441 |
|                         [Malaysia](/malaysia) |              123 |                       150 |                       5 |                         27 |                                       22% |                                   134 |                                    176 |
|                                 [Cuba](/cuba) |               87 |                       103 |                       9 |                         16 |                                       18% |                                    91 |                                    137 |
