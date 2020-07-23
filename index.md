We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >97% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5-8x higher than the reported cases.

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
### Updated Daily - Last Updated: July 23 (3am ET):
<p align="center">
  Current Total: <b>143,187</b> deaths | Projected Total: <b>217,600 deaths by Nov 1, 2020</b> (Range: 185-268k)<br>
  Currently Infected: <b>2.0%</b> | Total Infected: <b>9.9%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 23, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              150,000 |        Jul 30, 2020 |
|              175,000 |        Aug 28, 2020 |
|              200,000 |         Oct 8, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        90% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          7% |        66% |         93% |        99% |         99% |        99% |
|              200,000 |        <1% |         <1% |         6% |         22% |        43% |         57% |        70% |
|              225,000 |        <1% |         <1% |        <1% |          2% |         9% |         17% |        26% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          4% |         8% |
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
|             *[United States](/us)* |          143,187 |                   217,623 |                     656 |                     74,436 |                                       52% |                               185,153 |                                267,948 |
|                 [New York](/us-ny) |           32,558 |                    33,053 |                   1,699 |                        495 |                                        2% |                                32,586 |                                 34,960 |
|               [New Jersey](/us-nj) |           15,707 |                    16,458 |                   1,853 |                        751 |                                        5% |                                15,804 |                                 17,799 |
|               [California](/us-ca) |            8,047 |                    16,384 |                     415 |                      8,337 |                                      104% |                                11,109 |                                 24,795 |
|                    [Texas](/us-tx) |            4,439 |                    15,332 |                     529 |                     10,893 |                                      245% |                                 9,482 |                                 24,030 |
|                  [Florida](/us-fl) |            5,345 |                    13,901 |                     647 |                      8,556 |                                      160% |                                 9,114 |                                 21,732 |
|             [Pennsylvania](/us-pa) |            7,077 |                     9,501 |                     742 |                      2,424 |                                       34% |                                 7,399 |                                 14,263 |
|                 [Illinois](/us-il) |            7,540 |                     9,218 |                     727 |                      1,678 |                                       22% |                                 7,880 |                                 11,672 |
|            [Massachusetts](/us-ma) |            8,468 |                     9,093 |                   1,308 |                        625 |                                        7% |                                 8,561 |                                 10,145 |
|                 [Michigan](/us-mi) |            6,388 |                     7,369 |                     738 |                        981 |                                       15% |                                 6,532 |                                  9,342 |
|                  [Georgia](/us-ga) |            3,335 |                     7,171 |                     675 |                      3,836 |                                      115% |                                 4,342 |                                 12,849 |
|                  [Arizona](/us-az) |            2,974 |                     6,735 |                     925 |                      3,761 |                                      126% |                                 4,864 |                                  9,392 |
|                     [Ohio](/us-oh) |            3,235 |                     5,984 |                     512 |                      2,749 |                                       85% |                                 3,882 |                                 10,609 |
|                [Louisiana](/us-la) |            3,558 |                     5,889 |                   1,267 |                      2,331 |                                       66% |                                 4,129 |                                  9,128 |
|              [Connecticut](/us-ct) |            4,406 |                     4,659 |                   1,307 |                        253 |                                        6% |                                 4,448 |                                  5,139 |
|                  [Indiana](/us-in) |            2,863 |                     4,434 |                     659 |                      1,571 |                                       55% |                                 3,133 |                                  7,721 |
|                 [Maryland](/us-md) |            3,405 |                     4,103 |                     679 |                        698 |                                       21% |                                 3,524 |                                  5,374 |
|                 [Virginia](/us-va) |            2,051 |                     3,692 |                     432 |                      1,641 |                                       80% |                                 2,298 |                                  7,182 |
|           [North Carolina](/us-nc) |            1,732 |                     3,667 |                     350 |                      1,935 |                                      112% |                                 2,349 |                                  6,098 |
|           [South Carolina](/us-sc) |            1,285 |                     3,627 |                     704 |                      2,342 |                                      182% |                                 2,359 |                                  5,508 |
|                  [Alabama](/us-al) |            1,364 |                     3,552 |                     724 |                      2,188 |                                      160% |                                 2,352 |                                  5,511 |
|                 [Colorado](/us-co) |            1,771 |                     2,792 |                     485 |                      1,021 |                                       58% |                                 1,977 |                                  4,934 |
|              [Mississippi](/us-ms) |            1,423 |                     2,724 |                     915 |                      1,301 |                                       91% |                                 1,963 |                                  3,959 |
|                [Minnesota](/us-mn) |            1,592 |                     2,503 |                     444 |                        911 |                                       57% |                                 1,791 |                                  4,375 |
|                   [Nevada](/us-nv) |              704 |                     2,357 |                     765 |                      1,653 |                                      235% |                                 1,392 |                                  3,982 |
|                [Tennessee](/us-tn) |              888 |                     2,259 |                     331 |                      1,371 |                                      154% |                                 1,475 |                                  3,661 |
|                 [Missouri](/us-mo) |            1,159 |                     2,129 |                     347 |                        970 |                                       84% |                                 1,366 |                                  3,940 |
|               [Washington](/us-wa) |            1,468 |                     1,992 |                     262 |                        524 |                                       36% |                                 1,543 |                                  2,999 |
|                 [Kentucky](/us-ky) |              677 |                     1,846 |                     413 |                      1,169 |                                      173% |                                   909 |                                  4,100 |
|                [Wisconsin](/us-wi) |              865 |                     1,759 |                     302 |                        894 |                                      103% |                                 1,052 |                                  3,668 |
|                     [Iowa](/us-ia) |              814 |                     1,543 |                     489 |                        729 |                                       90% |                                   995 |                                  2,793 |
|             [Rhode Island](/us-ri) |              997 |                     1,176 |                   1,110 |                        179 |                                       18% |                                 1,030 |                                  1,411 |
|               [New Mexico](/us-nm) |              591 |                     1,132 |                     540 |                        541 |                                       92% |                                   675 |                                  2,088 |
|                 [Oklahoma](/us-ok) |              474 |                       987 |                     249 |                        513 |                                      108% |                                   620 |                                  1,706 |
|                 [Arkansas](/us-ar) |              380 |                       962 |                     319 |                        582 |                                      153% |                                   604 |                                  1,571 |
|                   [Oregon](/us-or) |              271 |                       930 |                     220 |                        659 |                                      243% |                                   453 |                                  1,940 |
|                    [Idaho](/us-id) |              135 |                       893 |                     500 |                        758 |                                      561% |                                   398 |                                  1,684 |
|                     [Utah](/us-ut) |              260 |                       845 |                     264 |                        585 |                                      225% |                                   477 |                                  1,493 |
|                 [Delaware](/us-de) |              527 |                       662 |                     679 |                        135 |                                       26% |                                   554 |                                    902 |
|     [District of Columbia](/us-dc) |              580 |                       651 |                     923 |                         71 |                                       12% |                                   594 |                                    768 |
|                   [Kansas](/us-ks) |              321 |                       638 |                     219 |                        317 |                                       99% |                                   406 |                                  1,153 |
|              [Puerto Rico](/us-pr) |              185 |                       637 |                     200 |                        452 |                                      244% |                                   246 |                                  1,639 |
|            [New Hampshire](/us-nh) |              402 |                       534 |                     393 |                        132 |                                       33% |                                   416 |                                    774 |
|                 [Nebraska](/us-ne) |              311 |                       508 |                     263 |                        197 |                                       63% |                                   346 |                                    836 |
|                  [Montana](/us-mt) |               42 |                       233 |                     218 |                        191 |                                      454% |                                   101 |                                    484 |
|             [South Dakota](/us-sd) |              119 |                       223 |                     252 |                        104 |                                       87% |                                   138 |                                    370 |
|             [North Dakota](/us-nd) |               96 |                       218 |                     287 |                        122 |                                      128% |                                   118 |                                    422 |
|            [West Virginia](/us-wv) |              101 |                       184 |                     102 |                         83 |                                       82% |                                   122 |                                    364 |
|                    [Maine](/us-me) |              118 |                       169 |                     125 |                         51 |                                       43% |                                   128 |                                    247 |
|                   [Hawaii](/us-hi) |               25 |                        79 |                      56 |                         54 |                                      215% |                                    33 |                                    209 |
|                  [Vermont](/us-vt) |               56 |                        75 |                     120 |                         19 |                                       34% |                                    61 |                                     99 |
|                   [Alaska](/us-ak) |               19 |                        71 |                      96 |                         52 |                                      271% |                                    31 |                                    171 |
|                  [Wyoming](/us-wy) |               25 |                        59 |                     102 |                         34 |                                      136% |                                    38 |                                    108 |
|           [Virgin Islands](/us-vi) |                7 |                        21 |                     204 |                         14 |                                      206% |                                    10 |                                     50 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     6 |                                     20 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      74 |                          2 |                                      103% |                                     2 |                                      8 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,435 |                   198,639 |                     335 |                     12,204 |                                        7% |                               190,087 |                                218,436 |
| [United Kingdom](/united-kingdom) |           45,586 |                    46,963 |                     695 |                      1,377 |                                        3% |                                45,674 |                                 49,615 |
|                   [Italy](/italy) |           35,082 |                    35,565 |                     589 |                        483 |                                        1% |                                35,111 |                                 36,389 |
|                 [France](/france) |           30,175 |                    30,647 |                     457 |                        472 |                                        2% |                                30,199 |                                 33,037 |
|                   [Spain](/spain) |           28,426 |                    28,765 |                     613 |                        339 |                                        1% |                                28,447 |                                 30,137 |
|               [Belgium](/belgium) |            9,808 |                     9,894 |                     864 |                         86 |                                        1% |                                 9,824 |                                 10,168 |
|               [Germany](/germany) |            9,102 |                     9,695 |                     117 |                        593 |                                        7% |                                 9,135 |                                 11,682 |
|       [Netherlands](/netherlands) |            6,158 |                     6,212 |                     359 |                         54 |                                        1% |                                 6,168 |                                  6,330 |
|                 [Sweden](/sweden) |            5,667 |                     6,070 |                     593 |                        403 |                                        7% |                                 5,781 |                                  6,520 |
|               [Romania](/romania) |            2,101 |                     4,125 |                     212 |                      2,024 |                                       96% |                                 3,077 |                                  6,081 |
|               [Ukraine](/ukraine) |            1,553 |                     3,099 |                      70 |                      1,546 |                                      100% |                                 2,213 |                                  4,889 |
|                 [Poland](/poland) |            1,642 |                     2,150 |                      57 |                        508 |                                       31% |                                 1,713 |                                  3,095 |
|             [Portugal](/portugal) |            1,702 |                     2,145 |                     209 |                        443 |                                       26% |                                 1,762 |                                  2,809 |
|       [Switzerland](/switzerland) |            1,972 |                     2,039 |                     237 |                         67 |                                        3% |                                 1,984 |                                  2,225 |
|               [Ireland](/ireland) |            1,754 |                     1,825 |                     372 |                         71 |                                        4% |                                 1,765 |                                  2,045 |
|                 [Serbia](/serbia) |              499 |                     1,665 |                     239 |                      1,166 |                                      234% |                                 1,070 |                                  2,663 |
|               [Moldova](/moldova) |              712 |                     1,467 |                     363 |                        755 |                                      106% |                                   974 |                                  2,162 |
|               [Belarus](/belarus) |              513 |                       998 |                     106 |                        485 |                                       95% |                                   803 |                                  1,412 |
|             [Bulgaria](/bulgaria) |              321 |                       884 |                     126 |                        563 |                                      175% |                                   528 |                                  1,534 |
|               [Austria](/austria) |              711 |                       776 |                      88 |                         65 |                                        9% |                                   728 |                                    892 |
|               [Hungary](/hungary) |              596 |                       697 |                      71 |                        101 |                                       17% |                                   608 |                                    914 |
|               [Denmark](/denmark) |              611 |                       686 |                     118 |                         75 |                                       12% |                                   629 |                                    802 |
|               [Czechia](/czechia) |              364 |                       482 |                      45 |                        118 |                                       33% |                                   397 |                                    660 |
|               [Finland](/finland) |              328 |                       379 |                      69 |                         51 |                                       16% |                                   340 |                                    468 |
|                 [Norway](/norway) |              255 |                       284 |                      53 |                         29 |                                       11% |                                   263 |                                    330 |
|               [Croatia](/croatia) |              125 |                       271 |                      66 |                        146 |                                      116% |                                   173 |                                    454 |
|                 [Greece](/greece) |              200 |                       242 |                      23 |                         42 |                                       21% |                                   210 |                                    294 |
|         [Luxembourg](/luxembourg) |              111 |                       156 |                     254 |                         45 |                                       40% |                                   126 |                                    213 |
|             [Slovenia](/slovenia) |              115 |                       136 |                      66 |                         21 |                                       19% |                                   119 |                                    173 |
|           [Lithuania](/lithuania) |               80 |                       102 |                      37 |                         22 |                                       28% |                                    84 |                                    133 |
|               [Estonia](/estonia) |               69 |                        89 |                      67 |                         20 |                                       29% |                                    77 |                                    122 |
|                 [Latvia](/latvia) |               31 |                        40 |                      21 |                          9 |                                       30% |                                    33 |                                     59 |
|             [Slovakia](/slovakia) |               28 |                        35 |                       7 |                          7 |                                       27% |                                    29 |                                     50 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       49% |                                    22 |                                     42 |
|                   [Malta](/malta) |                9 |                        14 |                      28 |                          5 |                                       52% |                                    11 |                                     17 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       34% |                                    10 |                                     20 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          276,620 |                   636,456 |                     123 |                    359,836 |                                      130% |                               420,804 |                                973,408 |
|                             [Brazil](/brazil) |           82,771 |                   158,944 |                     753 |                     76,173 |                                       92% |                               118,487 |                                228,416 |
|                               [India](/india) |           29,861 |                   143,947 |                     105 |                    114,086 |                                      382% |                                74,358 |                                221,790 |
|                             [Mexico](/mexico) |           41,190 |                    86,340 |                     677 |                     45,150 |                                      110% |                                62,499 |                                135,873 |
|                                 [Iran](/iran) |           14,853 |                    27,681 |                     334 |                     12,828 |                                       86% |                                20,813 |                                 37,492 |
|                                 [Peru](/peru) |           13,767 |                    24,772 |                     762 |                     11,005 |                                       80% |                                16,124 |                                 39,819 |
|                         [Colombia](/colombia) |            7,373 |                    24,338 |                     483 |                     16,965 |                                      230% |                                16,368 |                                 34,963 |
|                             [Russia](/russia) |           12,726 |                    22,542 |                     155 |                      9,816 |                                       77% |                                14,620 |                                 37,856 |
|                       [Indonesia](/indonesia) |            4,459 |                    19,568 |                      72 |                     15,109 |                                      339% |                                 9,793 |                                 37,530 |
|                 [South Africa](/south-africa) |            5,940 |                    18,107 |                     309 |                     12,167 |                                      205% |                                10,187 |                                 24,401 |
|                               [Chile](/chile) |            8,677 |                    12,223 |                     645 |                      3,546 |                                       41% |                                 9,412 |                                 20,090 |
|                       [Argentina](/argentina) |            2,588 |                     9,935 |                     222 |                      7,347 |                                      284% |                                 6,133 |                                 15,198 |
|                             [Canada](/canada) |            8,913 |                     9,634 |                     258 |                        721 |                                        8% |                                 8,947 |                                 11,427 |
|                           [Ecuador](/ecuador) |            5,418 |                     8,403 |                     484 |                      2,985 |                                       55% |                                 6,057 |                                 12,278 |
|                         [Pakistan](/pakistan) |            5,709 |                     8,251 |                      38 |                      2,542 |                                       45% |                                 6,488 |                                 11,847 |
|                               [Egypt](/egypt) |            4,440 |                     7,924 |                      79 |                      3,484 |                                       78% |                                 5,196 |                                 12,454 |
|                             [Turkey](/turkey) |            5,545 |                     7,629 |                      91 |                      2,084 |                                       38% |                                 5,789 |                                 11,081 |
|                           [Bolivia](/bolivia) |            2,328 |                     6,093 |                     529 |                      3,765 |                                      162% |                                 4,140 |                                  9,380 |
|                   [Philippines](/philippines) |            1,843 |                     5,424 |                      50 |                      3,581 |                                      194% |                                 2,225 |                                 12,923 |
|                     [Bangladesh](/bangladesh) |            2,751 |                     5,400 |                      33 |                      2,649 |                                       96% |                                 3,225 |                                  9,992 |
|                 [Saudi Arabia](/saudi-arabia) |            2,601 |                     4,961 |                     145 |                      2,360 |                                       91% |                                 3,483 |                                  7,347 |
|                               [China](/china) |            4,648 |                     4,668 |                       3 |                         20 |                                        0% |                                 4,648 |                                  4,797 |
|                         [Honduras](/honduras) |            1,006 |                     3,635 |                     373 |                      2,629 |                                      261% |                                 2,136 |                                  6,113 |
|                             [Panama](/panama) |            1,180 |                     3,512 |                     827 |                      2,332 |                                      198% |                                 2,362 |                                  5,456 |
|                           [Algeria](/algeria) |            1,111 |                     2,366 |                      55 |                      1,255 |                                      113% |                                 1,305 |                                  4,598 |
|     [Dominican Republic](/dominican-republic) |            1,005 |                     2,141 |                     199 |                      1,136 |                                      113% |                                 1,373 |                                  3,656 |
|                           [Nigeria](/nigeria) |              813 |                     1,599 |                       8 |                        786 |                                       97% |                                   952 |                                  3,641 |
|                               [Japan](/japan) |              990 |                     1,572 |                      12 |                        582 |                                       59% |                                 1,010 |                                  3,668 |
|                             [Israel](/israel) |              430 |                     1,463 |                     172 |                      1,033 |                                      240% |                                   768 |                                  2,468 |
|                       [Australia](/australia) |              133 |                       823 |                      33 |                        690 |                                      518% |                                   202 |                                  2,322 |
|                           [Morocco](/morocco) |              285 |                       789 |                      22 |                        504 |                                      177% |                                   381 |                                  1,612 |
|                             [Kuwait](/kuwait) |              417 |                       622 |                     148 |                        205 |                                       49% |                                   441 |                                  1,083 |
| [United Arab Emirates](/united-arab-emirates) |              342 |                       461 |                      47 |                        119 |                                       35% |                                   352 |                                    763 |
|                   [South Korea](/south-korea) |              297 |                       412 |                       8 |                        115 |                                       39% |                                   302 |                                    739 |
|                         [Malaysia](/malaysia) |              123 |                       161 |                       5 |                         38 |                                       31% |                                   136 |                                    183 |
|                                 [Cuba](/cuba) |               87 |                       113 |                      10 |                         26 |                                       29% |                                    92 |                                    152 |
