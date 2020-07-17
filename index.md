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
* **July 13:** View our [updated historical performance](/about/#historical-performance) (commentary [on Twitter](https://twitter.com/youyanggu/status/1283102532236181504)).
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 17 (4pm ET):
<p align="center">
  Current Total: <b>138,355</b> deaths | Projected Total: <b>211,900 deaths by Nov 1, 2020</b> (Range: 177-273k) | 197,400 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.4%</b> | Total Infected: <b>8.1%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 17, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 19, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |         Sep 5, 2020 |
|              200,000 |        Oct 31, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        52% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          5% |        44% |         69% |        88% |         95% |        99% |
|              200,000 |        <1% |         <1% |         5% |         16% |        29% |         40% |        51% |
|              225,000 |        <1% |         <1% |        <1% |          3% |         9% |         13% |        19% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         2% |          5% |         8% |
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
|             *[United States](/us)* |          138,355 |                   211,938 |                     639 |                     73,583 |                                       53% |                               177,344 |                                272,808 |
|                 [New York](/us-ny) |           32,446 |                    33,756 |                   1,735 |                      1,310 |                                        4% |                                32,498 |                                 38,415 |
|               [New Jersey](/us-nj) |           15,665 |                    16,841 |                   1,896 |                      1,176 |                                        8% |                                15,722 |                                 18,794 |
|               [California](/us-ca) |            7,489 |                    16,142 |                     409 |                      8,653 |                                      116% |                                 9,649 |                                 25,569 |
|                  [Florida](/us-fl) |            4,677 |                    15,156 |                     706 |                     10,479 |                                      224% |                                 9,268 |                                 28,449 |
|                    [Texas](/us-tx) |            3,657 |                    12,534 |                     432 |                      8,877 |                                      243% |                                 8,701 |                                 20,830 |
|            [Massachusetts](/us-ma) |            8,380 |                     9,096 |                   1,309 |                        716 |                                        9% |                                 8,501 |                                 10,520 |
|             [Pennsylvania](/us-pa) |            6,984 |                     8,962 |                     700 |                      1,978 |                                       28% |                                 7,169 |                                 13,342 |
|                 [Illinois](/us-il) |            7,452 |                     8,598 |                     679 |                      1,146 |                                       15% |                                 7,631 |                                  9,943 |
|                 [Michigan](/us-mi) |            6,348 |                     7,853 |                     786 |                      1,505 |                                       24% |                                 6,449 |                                 11,750 |
|                  [Georgia](/us-ga) |            3,105 |                     6,313 |                     595 |                      3,208 |                                      103% |                                 3,854 |                                 12,242 |
|                  [Arizona](/us-az) |            2,492 |                     6,119 |                     841 |                      3,627 |                                      146% |                                 4,587 |                                  9,429 |
|                [Louisiana](/us-la) |            3,485 |                     6,030 |                   1,297 |                      2,545 |                                       73% |                                 3,923 |                                  8,627 |
|                     [Ohio](/us-oh) |            3,103 |                     5,980 |                     512 |                      2,877 |                                       93% |                                 3,328 |                                 15,096 |
|              [Connecticut](/us-ct) |            4,389 |                     4,519 |                   1,267 |                        130 |                                        3% |                                 4,408 |                                  4,685 |
|                 [Maryland](/us-md) |            3,347 |                     4,085 |                     676 |                        738 |                                       22% |                                 3,485 |                                  5,278 |
|                  [Indiana](/us-in) |            2,795 |                     3,962 |                     589 |                      1,167 |                                       42% |                                 2,917 |                                  7,097 |
|                  [Alabama](/us-al) |            1,230 |                     3,856 |                     786 |                      2,626 |                                      213% |                                 2,363 |                                  5,944 |
|                 [Virginia](/us-va) |            2,007 |                     3,475 |                     407 |                      1,468 |                                       73% |                                 2,143 |                                  6,373 |
|           [North Carolina](/us-nc) |            1,607 |                     3,447 |                     329 |                      1,840 |                                      114% |                                 2,195 |                                  6,458 |
|           [South Carolina](/us-sc) |            1,070 |                     3,082 |                     599 |                      2,012 |                                      188% |                                 2,058 |                                  4,996 |
|              [Mississippi](/us-ms) |            1,308 |                     2,775 |                     932 |                      1,467 |                                      112% |                                 1,731 |                                  4,814 |
|                [Tennessee](/us-tn) |              796 |                     2,650 |                     388 |                      1,854 |                                      233% |                                 1,694 |                                  5,038 |
|                [Minnesota](/us-mn) |            1,566 |                     2,641 |                     468 |                      1,075 |                                       69% |                                 1,680 |                                  5,285 |
|                 [Colorado](/us-co) |            1,745 |                     2,572 |                     447 |                        827 |                                       47% |                                 1,852 |                                  4,734 |
|               [Washington](/us-wa) |            1,427 |                     2,204 |                     289 |                        777 |                                       54% |                                 1,503 |                                  4,263 |
|                 [Missouri](/us-mo) |            1,121 |                     2,060 |                     336 |                        939 |                                       84% |                                 1,243 |                                  4,328 |
|                   [Nevada](/us-nv) |              626 |                     1,928 |                     626 |                      1,302 |                                      208% |                                 1,131 |                                  3,070 |
|                 [Kentucky](/us-ky) |              650 |                     1,794 |                     402 |                      1,144 |                                      176% |                                   864 |                                  3,886 |
|                [Wisconsin](/us-wi) |              831 |                     1,679 |                     288 |                        848 |                                      102% |                                   952 |                                  4,324 |
|                     [Iowa](/us-ia) |              781 |                     1,224 |                     388 |                        443 |                                       57% |                                   815 |                                  2,278 |
|             [Rhode Island](/us-ri) |              988 |                     1,127 |                   1,064 |                        139 |                                       14% |                                 1,009 |                                  1,287 |
|               [New Mexico](/us-nm) |              562 |                     1,035 |                     494 |                        473 |                                       84% |                                   626 |                                  1,984 |
|                     [Utah](/us-ut) |              234 |                     1,024 |                     319 |                        790 |                                      338% |                                   458 |                                  2,727 |
|                   [Oregon](/us-or) |              249 |                       955 |                     226 |                        706 |                                      284% |                                   353 |                                  2,522 |
|                 [Arkansas](/us-ar) |              341 |                       911 |                     302 |                        570 |                                      167% |                                   619 |                                  1,492 |
|                 [Oklahoma](/us-ok) |              438 |                       783 |                     198 |                        345 |                                       79% |                                   516 |                                  1,267 |
|     [District of Columbia](/us-dc) |              574 |                       696 |                     986 |                        122 |                                       21% |                                   591 |                                    997 |
|                 [Delaware](/us-de) |              521 |                       661 |                     679 |                        140 |                                       27% |                                   537 |                                    960 |
|                   [Kansas](/us-ks) |              305 |                       635 |                     218 |                        330 |                                      108% |                                   340 |                                  1,500 |
|                 [Nebraska](/us-ne) |              299 |                       463 |                     239 |                        164 |                                       55% |                                   355 |                                    613 |
|                    [Idaho](/us-id) |              114 |                       452 |                     253 |                        338 |                                      296% |                                   220 |                                    897 |
|            [New Hampshire](/us-nh) |              395 |                       450 |                     331 |                         55 |                                       14% |                                   401 |                                    512 |
|              [Puerto Rico](/us-pr) |              172 |                       280 |                      88 |                        108 |                                       63% |                                   182 |                                    598 |
|             [South Dakota](/us-sd) |              115 |                       204 |                     231 |                         89 |                                       77% |                                   140 |                                    305 |
|                  [Montana](/us-mt) |               35 |                       180 |                     168 |                        145 |                                      414% |                                    70 |                                    391 |
|                    [Maine](/us-me) |              114 |                       177 |                     132 |                         63 |                                       55% |                                   122 |                                    346 |
|             [North Dakota](/us-nd) |               89 |                       160 |                     210 |                         71 |                                       80% |                                   100 |                                    311 |
|            [West Virginia](/us-wv) |               99 |                       154 |                      86 |                         55 |                                       56% |                                   107 |                                    282 |
|                  [Vermont](/us-vt) |               56 |                        80 |                     128 |                         24 |                                       43% |                                    58 |                                    180 |
|                   [Hawaii](/us-hi) |               22 |                        57 |                      40 |                         35 |                                      159% |                                    24 |                                    173 |
|                  [Wyoming](/us-wy) |               24 |                        57 |                      98 |                         33 |                                      138% |                                    32 |                                    116 |
|                   [Alaska](/us-ak) |               17 |                        34 |                      46 |                         17 |                                      100% |                                    18 |                                     77 |
|           [Virgin Islands](/us-vi) |                6 |                        16 |                     153 |                         10 |                                      167% |                                     6 |                                     48 |
|                     [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     5 |                                     42 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     10 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          185,363 |                   201,580 |                     340 |                     16,217 |                                        9% |                               189,092 |                                224,921 |
| [United Kingdom](/united-kingdom) |           45,204 |                    49,206 |                     729 |                      4,002 |                                        9% |                                45,710 |                                 53,201 |
|                   [Italy](/italy) |           35,017 |                    35,612 |                     590 |                        595 |                                        2% |                                35,078 |                                 36,164 |
|                 [France](/france) |           30,141 |                    30,817 |                     460 |                        676 |                                        2% |                                30,160 |                                 33,965 |
|                   [Spain](/spain) |           28,416 |                    28,771 |                     613 |                        355 |                                        1% |                                28,446 |                                 29,680 |
|               [Belgium](/belgium) |            9,795 |                     9,968 |                     870 |                        173 |                                        2% |                                 9,811 |                                 10,443 |
|               [Germany](/germany) |            9,087 |                     9,419 |                     113 |                        332 |                                        4% |                                 9,117 |                                 10,146 |
|       [Netherlands](/netherlands) |            6,156 |                     6,256 |                     362 |                        100 |                                        2% |                                 6,174 |                                  6,366 |
|                 [Sweden](/sweden) |            5,593 |                     6,010 |                     587 |                        417 |                                        7% |                                 5,724 |                                  6,186 |
|               [Romania](/romania) |            1,971 |                     3,875 |                     200 |                      1,904 |                                       97% |                                 2,727 |                                  5,293 |
|                 [Serbia](/serbia) |              442 |                     2,920 |                     419 |                      2,478 |                                      561% |                                   934 |                                  7,334 |
|               [Ukraine](/ukraine) |            1,462 |                     2,727 |                      62 |                      1,265 |                                       87% |                                 1,999 |                                  4,015 |
|                 [Poland](/poland) |            1,605 |                     2,386 |                      63 |                        781 |                                       49% |                                 1,855 |                                  3,498 |
|             [Portugal](/portugal) |            1,679 |                     2,196 |                     214 |                        517 |                                       31% |                                 1,762 |                                  3,026 |
|       [Switzerland](/switzerland) |            1,969 |                     2,061 |                     240 |                         92 |                                        5% |                                 1,981 |                                  2,428 |
|               [Ireland](/ireland) |            1,749 |                     1,833 |                     374 |                         84 |                                        5% |                                 1,756 |                                  2,232 |
|               [Moldova](/moldova) |              666 |                     1,152 |                     285 |                        486 |                                       73% |                                   970 |                                  1,499 |
|               [Belarus](/belarus) |              485 |                     1,116 |                     118 |                        631 |                                      130% |                                   635 |                                  2,277 |
|             [Bulgaria](/bulgaria) |              293 |                       900 |                     129 |                        607 |                                      207% |                                   506 |                                  1,446 |
|               [Austria](/austria) |              711 |                       832 |                      94 |                        121 |                                       17% |                                   726 |                                  1,043 |
|               [Hungary](/hungary) |              595 |                       695 |                      71 |                        100 |                                       17% |                                   607 |                                    993 |
|               [Denmark](/denmark) |              610 |                       653 |                     112 |                         43 |                                        7% |                                   623 |                                    732 |
|               [Czechia](/czechia) |              355 |                       480 |                      45 |                        125 |                                       35% |                                   364 |                                    682 |
|               [Finland](/finland) |              328 |                       363 |                      66 |                         35 |                                       11% |                                   332 |                                    458 |
|                 [Norway](/norway) |              254 |                       275 |                      51 |                         21 |                                        8% |                                   260 |                                    317 |
|               [Croatia](/croatia) |              120 |                       239 |                      59 |                        119 |                                       99% |                                   140 |                                    358 |
|                 [Greece](/greece) |              193 |                       222 |                      21 |                         29 |                                       15% |                                   203 |                                    277 |
|         [Luxembourg](/luxembourg) |              111 |                       145 |                     236 |                         34 |                                       31% |                                   117 |                                    181 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   112 |                                    149 |
|           [Lithuania](/lithuania) |               79 |                       108 |                      39 |                         29 |                                       37% |                                    86 |                                    169 |
|               [Estonia](/estonia) |               69 |                        85 |                      64 |                         16 |                                       23% |                                    75 |                                    111 |
|                 [Latvia](/latvia) |               31 |                        41 |                      21 |                         10 |                                       32% |                                    33 |                                     87 |
|             [Slovakia](/slovakia) |               28 |                        40 |                       7 |                         12 |                                       43% |                                    28 |                                     71 |
|                 [Cyprus](/cyprus) |               19 |                        30 |                      34 |                         11 |                                       58% |                                    20 |                                     57 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     24 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    11 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          251,904 |                   586,987 |                     113 |                    335,083 |                                      133% |                               395,749 |                                969,956 |
|                             [Brazil](/brazil) |           76,688 |                   155,616 |                     737 |                     78,928 |                                      103% |                               117,214 |                                239,545 |
|                               [India](/india) |           25,602 |                   107,150 |                      78 |                     81,548 |                                      319% |                                58,646 |                                226,585 |
|                             [Mexico](/mexico) |           37,574 |                    79,288 |                     621 |                     41,714 |                                      111% |                                54,512 |                                114,528 |
|                                 [Iran](/iran) |           13,608 |                    30,970 |                     374 |                     17,362 |                                      128% |                                22,269 |                                 45,656 |
|                                 [Peru](/peru) |           12,615 |                    23,030 |                     708 |                     10,415 |                                       83% |                                18,331 |                                 31,240 |
|                             [Russia](/russia) |           11,920 |                    22,432 |                     154 |                     10,512 |                                       88% |                                14,796 |                                 38,250 |
|                 [South Africa](/south-africa) |            4,669 |                    21,522 |                     368 |                     16,853 |                                      361% |                                13,495 |                                 33,591 |
|                         [Colombia](/colombia) |            6,164 |                    20,231 |                     402 |                     14,067 |                                      228% |                                14,599 |                                 27,809 |
|                       [Indonesia](/indonesia) |            3,873 |                    14,058 |                      52 |                     10,185 |                                      263% |                                 6,694 |                                 27,047 |
|                               [Chile](/chile) |            7,290 |                    11,066 |                     584 |                      3,776 |                                       52% |                                 8,174 |                                 13,566 |
|                         [Pakistan](/pakistan) |            5,426 |                    10,326 |                      48 |                      4,900 |                                       90% |                                 6,957 |                                 16,549 |
|                               [Egypt](/egypt) |            4,120 |                     9,846 |                      98 |                      5,726 |                                      139% |                                 5,981 |                                 17,009 |
|                             [Canada](/canada) |            8,875 |                     9,817 |                     262 |                        942 |                                       11% |                                 8,974 |                                 11,072 |
|                       [Argentina](/argentina) |            2,112 |                     9,151 |                     204 |                      7,039 |                                      333% |                                 4,174 |                                 16,970 |
|                           [Ecuador](/ecuador) |            5,207 |                     8,126 |                     468 |                      2,919 |                                       56% |                                 5,583 |                                 12,974 |
|                             [Turkey](/turkey) |            5,440 |                     6,869 |                      82 |                      1,429 |                                       26% |                                 5,528 |                                 11,450 |
|                           [Bolivia](/bolivia) |            1,984 |                     6,089 |                     529 |                      4,105 |                                      207% |                                 3,546 |                                 10,741 |
|                     [Bangladesh](/bangladesh) |            2,496 |                     5,965 |                      37 |                      3,469 |                                      139% |                                 3,771 |                                 10,314 |
|                 [Saudi Arabia](/saudi-arabia) |            2,370 |                     5,863 |                     171 |                      3,493 |                                      147% |                                 3,928 |                                  8,428 |
|                               [China](/china) |            4,644 |                     4,647 |                       3 |                          3 |                                        0% |                                 4,644 |                                  4,670 |
|                   [Philippines](/philippines) |            1,643 |                     3,987 |                      37 |                      2,344 |                                      143% |                                 2,122 |                                  8,469 |
|     [Dominican Republic](/dominican-republic) |              941 |                     3,821 |                     356 |                      2,880 |                                      306% |                                 1,464 |                                  8,445 |
|                         [Honduras](/honduras) |              835 |                     3,478 |                     357 |                      2,643 |                                      317% |                                 2,279 |                                  6,199 |
|                             [Panama](/panama) |            1,000 |                     3,220 |                     758 |                      2,220 |                                      222% |                                 2,328 |                                  5,238 |
|                           [Algeria](/algeria) |            1,052 |                     3,053 |                      71 |                      2,001 |                                      190% |                                 1,440 |                                  8,197 |
|                           [Nigeria](/nigeria) |              769 |                     1,916 |                      10 |                      1,147 |                                      149% |                                 1,000 |                                  4,154 |
|                               [Japan](/japan) |              985 |                     1,510 |                      12 |                        525 |                                       53% |                                   991 |                                  2,573 |
|                             [Israel](/israel) |              384 |                     1,465 |                     172 |                      1,081 |                                      282% |                                   589 |                                  4,052 |
|                             [Kuwait](/kuwait) |              402 |                       659 |                     157 |                        257 |                                       64% |                                   436 |                                  1,207 |
|                           [Morocco](/morocco) |              263 |                       489 |                      13 |                        226 |                                       86% |                                   300 |                                    900 |
| [United Arab Emirates](/united-arab-emirates) |              335 |                       468 |                      48 |                        133 |                                       40% |                                   349 |                                    856 |
|                   [South Korea](/south-korea) |              293 |                       339 |                       7 |                         46 |                                       16% |                                   295 |                                    460 |
|                       [Australia](/australia) |              116 |                       252 |                      10 |                        136 |                                      117% |                                   116 |                                    834 |
|                         [Malaysia](/malaysia) |              122 |                       151 |                       5 |                         29 |                                       24% |                                   133 |                                    180 |
|                                 [Cuba](/cuba) |               87 |                       117 |                      10 |                         30 |                                       34% |                                    91 |                                    198 |
