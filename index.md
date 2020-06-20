We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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

* **June 17:** Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* **June 16:** We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* **June 11**: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: June 20 (4am ET):
<p align="center">
  Current Total: <b>119,109</b> deaths | Projected Total: <b>184,902 deaths by Oct 1, 2020</b> (Range: 155-220k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.7%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.

*June 18 note:* We moved the R_t Dashboard map to the [Maps](/maps) page and replaced it with our C19Pro Score for deaths.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 87% chance that the US surpasses 125,000 deaths by July 1, with June 29 being the most likely date.

Last updated: Jun 20, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 21, 2020 |
|              125,000 |        Jun 29, 2020 |
|              130,000 |         Jul 8, 2020 |
|              140,000 |        Jul 24, 2020 |
|              150,000 |         Aug 8, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        87% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        19% |         69% |        92% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        24% |         49% |        63% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          5% |        20% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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

States are ordered by descending projected deaths (by October 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          119,109 |                   184,902 |                     557 |                     65,793 |                                       55% |                               155,200 |                                219,973 |
|                 [New York](/us-ny) |           31,015 |                    32,291 |                   1,660 |                      1,276 |                                        4% |                                31,113 |                                 35,635 |
|               [California](/us-ca) |            5,426 |                    15,742 |                     398 |                     10,316 |                                      190% |                                 8,348 |                                 23,319 |
|               [New Jersey](/us-nj) |           12,902 |                    14,833 |                   1,670 |                      1,931 |                                       15% |                                13,358 |                                 16,326 |
|                 [Illinois](/us-il) |            6,580 |                    10,311 |                     814 |                      3,731 |                                       57% |                                 7,930 |                                 12,538 |
|            [Massachusetts](/us-ma) |            7,799 |                     9,278 |                   1,335 |                      1,479 |                                       19% |                                 8,239 |                                 10,979 |
|             [Pennsylvania](/us-pa) |            6,399 |                     8,649 |                     676 |                      2,250 |                                       35% |                                 6,838 |                                 11,885 |
|                  [Florida](/us-fl) |            3,104 |                     8,390 |                     391 |                      5,286 |                                      170% |                                 4,630 |                                 12,666 |
|                    [Texas](/us-tx) |            2,158 |                     6,980 |                     241 |                      4,822 |                                      223% |                                 3,562 |                                 10,649 |
|                 [Michigan](/us-mi) |            6,067 |                     6,769 |                     678 |                        702 |                                       12% |                                 6,191 |                                  7,883 |
|                  [Georgia](/us-ga) |            2,636 |                     6,115 |                     576 |                      3,479 |                                      132% |                                 3,489 |                                  8,615 |
|                     [Ohio](/us-oh) |            2,667 |                     5,265 |                     450 |                      2,598 |                                       97% |                                 3,191 |                                  8,037 |
|              [Connecticut](/us-ct) |            4,238 |                     4,857 |                   1,362 |                        619 |                                       15% |                                 4,386 |                                  5,737 |
|                 [Maryland](/us-md) |            3,030 |                     4,649 |                     769 |                      1,619 |                                       53% |                                 3,415 |                                  5,952 |
|                  [Arizona](/us-az) |            1,321 |                     4,625 |                     635 |                      3,304 |                                      250% |                                 2,863 |                                  6,172 |
|                  [Indiana](/us-in) |            2,516 |                     4,381 |                     651 |                      1,865 |                                       74% |                                 2,792 |                                  6,998 |
|                [Louisiana](/us-la) |            3,084 |                     4,155 |                     894 |                      1,071 |                                       35% |                                 3,294 |                                  5,684 |
|                [Minnesota](/us-mn) |            1,393 |                     3,058 |                     542 |                      1,665 |                                      120% |                                 1,854 |                                  4,346 |
|           [North Carolina](/us-nc) |            1,190 |                     2,938 |                     280 |                      1,748 |                                      147% |                                 1,661 |                                  4,460 |
|                 [Virginia](/us-va) |            1,602 |                     2,701 |                     316 |                      1,099 |                                       69% |                                 1,766 |                                  4,203 |
|                 [Colorado](/us-co) |            1,643 |                     2,628 |                     456 |                        985 |                                       60% |                                 1,776 |                                  4,194 |
|                  [Alabama](/us-al) |              822 |                     2,370 |                     483 |                      1,548 |                                      188% |                                 1,221 |                                  3,639 |
|               [Washington](/us-wa) |            1,255 |                     2,255 |                     296 |                      1,000 |                                       80% |                                 1,385 |                                  4,541 |
|              [Mississippi](/us-ms) |              938 |                     2,022 |                     679 |                      1,084 |                                      116% |                                 1,150 |                                  3,298 |
|           [South Carolina](/us-sc) |              639 |                     1,989 |                     386 |                      1,350 |                                      211% |                                 1,040 |                                  2,892 |
|                 [Missouri](/us-mo) |              958 |                     1,949 |                     318 |                        991 |                                      103% |                                 1,156 |                                  3,173 |
|                [Wisconsin](/us-wi) |              730 |                     1,647 |                     283 |                        917 |                                      126% |                                   928 |                                  2,564 |
|                [Tennessee](/us-tn) |              515 |                     1,508 |                     221 |                        993 |                                      193% |                                   739 |                                  2,355 |
|             [Rhode Island](/us-ri) |              894 |                     1,417 |                   1,338 |                        523 |                                       59% |                                 1,056 |                                  1,786 |
|                     [Iowa](/us-ia) |              681 |                     1,174 |                     372 |                        493 |                                       72% |                                   767 |                                  2,309 |
|                 [Kentucky](/us-ky) |              522 |                     1,097 |                     246 |                        575 |                                      110% |                                   637 |                                  1,732 |
|               [New Mexico](/us-nm) |              464 |                       981 |                     468 |                        517 |                                      111% |                                   570 |                                  1,536 |
|                   [Nevada](/us-nv) |              479 |                       940 |                     305 |                        461 |                                       96% |                                   570 |                                  1,520 |
|                 [Arkansas](/us-ar) |              214 |                       855 |                     283 |                        641 |                                      300% |                                   478 |                                  1,251 |
|            [New Hampshire](/us-nh) |              337 |                       777 |                     571 |                        440 |                                      131% |                                   422 |                                  1,248 |
|                 [Nebraska](/us-ne) |              244 |                       738 |                     382 |                        494 |                                      202% |                                   398 |                                  1,150 |
|     [District of Columbia](/us-dc) |              530 |                       703 |                     996 |                        173 |                                       33% |                                   569 |                                    890 |
|                 [Delaware](/us-de) |              433 |                       669 |                     687 |                        236 |                                       55% |                                   481 |                                  1,007 |
|                 [Oklahoma](/us-ok) |              367 |                       624 |                     158 |                        257 |                                       70% |                                   416 |                                  1,067 |
|                     [Utah](/us-ut) |              155 |                       553 |                     172 |                        398 |                                      257% |                                   299 |                                    836 |
|                   [Kansas](/us-ks) |              253 |                       450 |                     154 |                        197 |                                       78% |                                   280 |                                    849 |
|                   [Oregon](/us-or) |              188 |                       364 |                      86 |                        176 |                                       94% |                                   221 |                                    626 |
|             [South Dakota](/us-sd) |               81 |                       210 |                     237 |                        129 |                                      159% |                                   109 |                                    413 |
|              [Puerto Rico](/us-pr) |              147 |                       200 |                      63 |                         53 |                                       36% |                                   159 |                                    294 |
|             [North Dakota](/us-nd) |               76 |                       154 |                     202 |                         78 |                                      103% |                                    96 |                                    297 |
|                    [Maine](/us-me) |              102 |                       150 |                     112 |                         48 |                                       47% |                                   115 |                                    233 |
|            [West Virginia](/us-wv) |               88 |                       135 |                      75 |                         47 |                                       53% |                                    99 |                                    260 |
|                    [Idaho](/us-id) |               89 |                       130 |                      73 |                         41 |                                       46% |                                    96 |                                    219 |
|                  [Wyoming](/us-wy) |               20 |                        74 |                     128 |                         54 |                                      270% |                                    28 |                                    130 |
|                  [Vermont](/us-vt) |               56 |                        71 |                     114 |                         15 |                                       27% |                                    60 |                                    105 |
|                  [Montana](/us-mt) |               20 |                        30 |                      28 |                         10 |                                       50% |                                    21 |                                     73 |
|                   [Hawaii](/us-hi) |               17 |                        20 |                      14 |                          3 |                                       18% |                                    17 |                                     25 |
|                   [Alaska](/us-ak) |               12 |                        15 |                      21 |                          3 |                                       25% |                                    13 |                                     18 |
|           [Virgin Islands](/us-vi) |                6 |                         7 |                      67 |                          1 |                                       17% |                                     7 |                                      8 |
|                     [Guam](/us-gu) |                5 |                         6 |                      36 |                          1 |                                       20% |                                     5 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |  

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          178,543 |                   198,707 |                     335 |                     20,164 |                                       11% |                               183,843 |                                224,914 |
| [United Kingdom](/united-kingdom) |           42,546 |                    47,700 |                     706 |                      5,154 |                                       12% |                                44,453 |                                 50,631 |
|                   [Italy](/italy) |           34,561 |                    35,647 |                     591 |                      1,086 |                                        3% |                                34,652 |                                 36,757 |
|                 [France](/france) |           29,620 |                    30,561 |                     456 |                        941 |                                        3% |                                29,665 |                                 34,163 |
|                   [Spain](/spain) |           28,315 |                    29,282 |                     624 |                        967 |                                        3% |                                28,378 |                                 31,647 |
|               [Germany](/germany) |            8,887 |                    10,553 |                     127 |                      1,666 |                                       19% |                                 9,087 |                                 14,608 |
|               [Belgium](/belgium) |            9,695 |                     9,955 |                     869 |                        260 |                                        3% |                                 9,726 |                                 10,458 |
|       [Netherlands](/netherlands) |            6,100 |                     6,583 |                     381 |                        483 |                                        8% |                                 6,163 |                                  7,341 |
|                 [Sweden](/sweden) |            5,053 |                     6,421 |                     628 |                      1,368 |                                       27% |                                 5,467 |                                  8,210 |
|               [Ukraine](/ukraine) |              995 |                     3,279 |                      75 |                      2,284 |                                      230% |                                 1,671 |                                  4,983 |
|                 [Poland](/poland) |            1,334 |                     3,036 |                      80 |                      1,702 |                                      128% |                                 1,810 |                                  4,490 |
|               [Romania](/romania) |            1,484 |                     2,459 |                     127 |                        975 |                                       66% |                                 1,744 |                                  3,706 |
|       [Switzerland](/switzerland) |            1,956 |                     2,078 |                     242 |                        122 |                                        6% |                                 1,972 |                                  2,459 |
|             [Portugal](/portugal) |            1,527 |                     1,890 |                     184 |                        363 |                                       24% |                                 1,617 |                                  2,481 |
|               [Ireland](/ireland) |            1,714 |                     1,817 |                     370 |                        103 |                                        6% |                                 1,727 |                                  2,223 |
|               [Moldova](/moldova) |              450 |                     1,540 |                     381 |                      1,090 |                                      242% |                                   970 |                                  2,199 |
|               [Belarus](/belarus) |              337 |                       829 |                      88 |                        492 |                                      146% |                                   463 |                                  1,849 |
|               [Hungary](/hungary) |              568 |                       786 |                      80 |                        218 |                                       38% |                                   603 |                                  1,151 |
|               [Austria](/austria) |              688 |                       749 |                      85 |                         61 |                                        9% |                                   704 |                                    913 |
|               [Denmark](/denmark) |              600 |                       682 |                     117 |                         82 |                                       14% |                                   622 |                                    854 |
|             [Bulgaria](/bulgaria) |              193 |                       614 |                      88 |                        421 |                                      218% |                                   333 |                                    960 |
|               [Finland](/finland) |              326 |                       372 |                      67 |                         46 |                                       14% |                                   332 |                                    500 |
|               [Czechia](/czechia) |              335 |                       361 |                      34 |                         26 |                                        8% |                                   347 |                                    396 |
|                 [Serbia](/serbia) |              259 |                       336 |                      48 |                         77 |                                       30% |                                   280 |                                    478 |
|                 [Norway](/norway) |              244 |                       270 |                      50 |                         26 |                                       11% |                                   253 |                                    311 |
|                 [Greece](/greece) |              189 |                       229 |                      21 |                         40 |                                       21% |                                   203 |                                    298 |
|               [Croatia](/croatia) |              107 |                       136 |                      33 |                         29 |                                       27% |                                   115 |                                    182 |
|             [Slovenia](/slovenia) |              109 |                       121 |                      58 |                         12 |                                       11% |                                   111 |                                    147 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    143 |
|           [Lithuania](/lithuania) |               76 |                       115 |                      41 |                         39 |                                       51% |                                    86 |                                    173 |
|               [Estonia](/estonia) |               69 |                        77 |                      58 |                          8 |                                       12% |                                    75 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        36 |                      19 |                          6 |                                       20% |                                    33 |                                     42 |
|             [Slovakia](/slovakia) |               28 |                        29 |                       5 |                          1 |                                        4% |                                    28 |                                     32 |
|                 [Cyprus](/cyprus) |               19 |                        22 |                      25 |                          3 |                                       16% |                                    21 |                                     23 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     13 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          155,687 |                   595,921 |                     115 |                    440,234 |                                      283% |                               326,355 |                                951,621 |
|                               [India](/india) |           12,948 |                   136,056 |                     100 |                    123,108 |                                      951% |                                51,869 |                                245,078 |
|                             [Brazil](/brazil) |           48,954 |                   129,937 |                     616 |                     80,983 |                                      165% |                                78,052 |                                199,684 |
|                             [Mexico](/mexico) |           20,394 |                    82,388 |                     646 |                     61,994 |                                      304% |                                50,526 |                                109,282 |
|                         [Pakistan](/pakistan) |            3,382 |                    31,665 |                     146 |                     28,283 |                                      836% |                                14,013 |                                 62,380 |
|                             [Russia](/russia) |            7,831 |                    22,820 |                     156 |                     14,989 |                                      191% |                                12,453 |                                 39,416 |
|                               [Chile](/chile) |            4,093 |                    22,642 |                   1,195 |                     18,549 |                                      453% |                                15,555 |                                 34,680 |
|                                 [Peru](/peru) |            7,461 |                    22,455 |                     691 |                     14,994 |                                      201% |                                13,590 |                                 34,223 |
|                         [Colombia](/colombia) |            2,046 |                    19,646 |                     390 |                     17,600 |                                      860% |                                11,126 |                                 25,415 |
|                 [South Africa](/south-africa) |            1,831 |                    18,619 |                     318 |                     16,788 |                                      917% |                                10,587 |                                 26,130 |
|                                 [Iran](/iran) |            9,392 |                    17,396 |                     210 |                      8,004 |                                       85% |                                11,606 |                                 24,215 |
|                             [Canada](/canada) |            8,408 |                    11,733 |                     314 |                      3,325 |                                       40% |                                 9,044 |                                 18,002 |
|                               [Egypt](/egypt) |            2,017 |                    10,943 |                     109 |                      8,926 |                                      443% |                                 5,847 |                                 18,213 |
|                     [Bangladesh](/bangladesh) |            1,388 |                     9,995 |                      61 |                      8,607 |                                      620% |                                 5,513 |                                 15,614 |
|                       [Indonesia](/indonesia) |            2,373 |                     8,479 |                      31 |                      6,106 |                                      257% |                                 4,188 |                                 15,983 |
|                       [Argentina](/argentina) |              979 |                     7,383 |                     165 |                      6,404 |                                      654% |                                 3,094 |                                 12,634 |
|                 [Saudi Arabia](/saudi-arabia) |            1,184 |                     7,276 |                     212 |                      6,092 |                                      515% |                                 4,091 |                                 11,016 |
|                           [Ecuador](/ecuador) |            4,156 |                     6,195 |                     357 |                      2,039 |                                       49% |                                 4,555 |                                 10,831 |
|                             [Turkey](/turkey) |            4,905 |                     5,783 |                      69 |                        878 |                                       18% |                                 4,980 |                                  8,551 |
|                           [Bolivia](/bolivia) |              715 |                     5,512 |                     479 |                      4,797 |                                      671% |                                 2,899 |                                  8,418 |
|                               [China](/china) |            4,638 |                     4,650 |                       3 |                         12 |                                        0% |                                 4,638 |                                  4,709 |
|                           [Nigeria](/nigeria) |              487 |                     2,369 |                      12 |                      1,882 |                                      386% |                                   894 |                                  4,172 |
|                   [Philippines](/philippines) |            1,130 |                     2,283 |                      21 |                      1,153 |                                      102% |                                 1,269 |                                  4,028 |
|                           [Algeria](/algeria) |              825 |                     2,018 |                      47 |                      1,193 |                                      145% |                                   958 |                                  5,666 |
|                         [Honduras](/honduras) |              349 |                     1,432 |                     147 |                      1,083 |                                      310% |                                   693 |                                  2,531 |
|     [Dominican Republic](/dominican-republic) |              647 |                     1,339 |                     125 |                        692 |                                      107% |                                   780 |                                  2,989 |
|                             [Panama](/panama) |              485 |                     1,286 |                     303 |                        801 |                                      165% |                                   700 |                                  2,357 |
|                               [Japan](/japan) |              951 |                     1,218 |                      10 |                        267 |                                       28% |                                   957 |                                  1,781 |
|                             [Kuwait](/kuwait) |              313 |                       679 |                     161 |                        366 |                                      117% |                                   397 |                                  1,157 |
| [United Arab Emirates](/united-arab-emirates) |              300 |                       428 |                      44 |                        128 |                                       43% |                                   327 |                                    731 |
|                             [Israel](/israel) |              304 |                       385 |                      45 |                         81 |                                       27% |                                   320 |                                    626 |
|                   [South Korea](/south-korea) |              280 |                       314 |                       6 |                         34 |                                       12% |                                   283 |                                    378 |
|                           [Morocco](/morocco) |              213 |                       239 |                       7 |                         26 |                                       12% |                                   222 |                                    292 |
|                         [Malaysia](/malaysia) |              121 |                       147 |                       5 |                         26 |                                       21% |                                   137 |                                    171 |
|                       [Australia](/australia) |              102 |                       109 |                       4 |                          7 |                                        7% |                                   102 |                                    139 |
|                                 [Cuba](/cuba) |               85 |                       102 |                       9 |                         17 |                                       20% |                                    90 |                                    129 |
