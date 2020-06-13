We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#current-us-projections)
* [US and Global Dashboard **(New June 6)**](#covid-19-dashboard)
* [View US state-by-state projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **June 12:** We changed how we display our R_t values. Previously, we displayed the R value before factoring in recovered/immune individuals. Now we are displaying the R values after factoring in immunity, which is what our model uses internally. This R value is lower than our previous displayed values. Note that this is merely a cosmetic change, and that our underlying model has not changed.
* **June 11:** We have extended our projections to October 1, 2020.
* **June 10:** We launched the C19Pro Score for both cases and deaths to show where weekly cases and deaths are changing the most. They are shown in the first two maps on our new [Maps](/maps) page.
* **June 8:** We added a map that shows how cases are changing in each state/country. Scroll down below to see it, or click [here](#covid-19-dashboard)

## Current US Projections
### Updated Daily - Last Updated: June 13 (6am ET):
<p align="center">
  Current Total: <b>114,666</b> deaths | Projected Total: <b>180,086 deaths by Sep 1 | 198,560 deaths by Oct 1, 2020</b> (Range: 147-286k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.4%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 88% chance that the US surpasses 125,000 deaths by July 1, with June 26 being the most likely date.

Last updated: Jun 13, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 20, 2020 |
|              125,000 |        Jun 26, 2020 |
|              130,000 |         Jul 3, 2020 |
|              140,000 |        Jul 16, 2020 |
|              150,000 |        Jul 28, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        87% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |         <1% |        <1% |          7% |        52% |         72% |        86% |         91% |        95% |
|              175,000 |         <1% |        <1% |         <1% |         7% |         27% |        47% |         54% |        60% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          5% |        21% |         30% |        38% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |          6% |        12% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |

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
|             *[United States](/us)* |          114,666 |                   198,560 |                     598 |                     83,894 |                                       73% |                               147,054 |                                285,421 |
|                 [New York](/us-ny) |           30,758 |                    34,122 |                   1,754 |                      3,364 |                                       11% |                                31,511 |                                 39,791 |
|               [California](/us-ca) |            4,978 |                    16,852 |                     427 |                     11,874 |                                      239% |                                 7,371 |                                 32,077 |
|               [New Jersey](/us-nj) |           12,489 |                    15,033 |                   1,692 |                      2,544 |                                       20% |                                13,201 |                                 17,741 |
|                 [Illinois](/us-il) |            6,260 |                    12,204 |                     963 |                      5,944 |                                       95% |                                 7,978 |                                 18,328 |
|            [Massachusetts](/us-ma) |            7,538 |                     9,797 |                   1,410 |                      2,259 |                                       30% |                                 8,182 |                                 13,381 |
|             [Pennsylvania](/us-pa) |            6,162 |                     9,715 |                     759 |                      3,553 |                                       58% |                                 6,805 |                                 16,620 |
|                  [Florida](/us-fl) |            2,877 |                     8,809 |                     410 |                      5,932 |                                      206% |                                 4,024 |                                 16,929 |
|                 [Michigan](/us-mi) |            5,990 |                     7,312 |                     732 |                      1,322 |                                       22% |                                 6,313 |                                 10,310 |
|                     [Ohio](/us-oh) |            2,510 |                     6,171 |                     528 |                      3,661 |                                      146% |                                 3,139 |                                 11,873 |
|                 [Maryland](/us-md) |            2,900 |                     5,506 |                     911 |                      2,606 |                                       90% |                                 3,452 |                                  8,552 |
|              [Connecticut](/us-ct) |            4,159 |                     5,236 |                   1,469 |                      1,077 |                                       26% |                                 4,450 |                                  6,914 |
|                  [Georgia](/us-ga) |            2,418 |                     5,230 |                     493 |                      2,812 |                                      116% |                                 3,361 |                                  8,569 |
|                    [Texas](/us-tx) |            1,956 |                     4,825 |                     166 |                      2,869 |                                      147% |                                 2,673 |                                 10,997 |
|                  [Indiana](/us-in) |            2,396 |                     4,607 |                     684 |                      2,211 |                                       92% |                                 2,745 |                                  9,505 |
|                [Louisiana](/us-la) |            2,996 |                     4,344 |                     934 |                      1,348 |                                       45% |                                 3,320 |                                  6,622 |
|                  [Arizona](/us-az) |            1,156 |                     4,298 |                     590 |                      3,142 |                                      272% |                                 1,739 |                                  8,194 |
|           [North Carolina](/us-nc) |            1,121 |                     4,241 |                     404 |                      3,120 |                                      278% |                                 1,848 |                                  8,071 |
|                 [Virginia](/us-va) |            1,534 |                     3,846 |                     451 |                      2,312 |                                      151% |                                 1,919 |                                  7,869 |
|                [Minnesota](/us-mn) |            1,305 |                     3,389 |                     601 |                      2,084 |                                      160% |                                 2,014 |                                  5,159 |
|                 [Colorado](/us-co) |            1,582 |                     2,934 |                     509 |                      1,352 |                                       85% |                                 1,769 |                                  6,118 |
|                 [Missouri](/us-mo) |              881 |                     2,877 |                     469 |                      1,996 |                                      227% |                                 1,332 |                                  5,555 |
|                  [Alabama](/us-al) |              769 |                     2,824 |                     576 |                      2,055 |                                      267% |                                 1,280 |                                  5,111 |
|               [Washington](/us-wa) |            1,204 |                     2,479 |                     326 |                      1,275 |                                      106% |                                 1,350 |                                  5,782 |
|              [Mississippi](/us-ms) |              881 |                     2,312 |                     777 |                      1,431 |                                      162% |                                 1,122 |                                  4,491 |
|           [South Carolina](/us-sc) |              593 |                     2,217 |                     431 |                      1,624 |                                      274% |                                   914 |                                  4,350 |
|                [Wisconsin](/us-wi) |              689 |                     2,059 |                     354 |                      1,370 |                                      199% |                                   985 |                                  4,131 |
|                     [Iowa](/us-ia) |              644 |                     1,591 |                     504 |                        947 |                                      147% |                                 1,036 |                                  2,573 |
|             [Rhode Island](/us-ri) |              833 |                     1,584 |                   1,495 |                        751 |                                       90% |                                 1,063 |                                  2,386 |
|                 [Kentucky](/us-ky) |              497 |                     1,442 |                     323 |                        945 |                                      190% |                                   671 |                                  3,027 |
|                [Tennessee](/us-tn) |              466 |                     1,248 |                     183 |                        782 |                                      168% |                                   669 |                                  2,424 |
|               [New Mexico](/us-nm) |              420 |                     1,129 |                     538 |                        709 |                                      169% |                                   537 |                                  2,282 |
|                   [Nevada](/us-nv) |              461 |                     1,079 |                     350 |                        618 |                                      134% |                                   580 |                                  2,160 |
|            [New Hampshire](/us-nh) |              315 |                     1,013 |                     745 |                        698 |                                      222% |                                   435 |                                  1,963 |
|                 [Arkansas](/us-ar) |              176 |                       857 |                     284 |                        681 |                                      387% |                                   326 |                                  1,563 |
|     [District of Columbia](/us-dc) |              506 |                       771 |                   1,092 |                        265 |                                       52% |                                   564 |                                  1,188 |
|                 [Delaware](/us-de) |              414 |                       770 |                     791 |                        356 |                                       86% |                                   482 |                                  1,436 |
|                     [Utah](/us-ut) |              139 |                       696 |                     217 |                        557 |                                      401% |                                   262 |                                  1,344 |
|                 [Nebraska](/us-ne) |              215 |                       689 |                     356 |                        474 |                                      220% |                                   405 |                                  1,180 |
|                 [Oklahoma](/us-ok) |              360 |                       532 |                     134 |                        172 |                                       48% |                                   417 |                                    836 |
|                   [Kansas](/us-ks) |              243 |                       411 |                     141 |                        168 |                                       69% |                                   275 |                                    843 |
|                   [Oregon](/us-or) |              173 |                       312 |                      74 |                        139 |                                       80% |                                   198 |                                    682 |
|              [Puerto Rico](/us-pr) |              146 |                       221 |                      69 |                         75 |                                       51% |                                   167 |                                    360 |
|             [South Dakota](/us-sd) |               74 |                       219 |                     248 |                        145 |                                      196% |                                   111 |                                    426 |
|                    [Maine](/us-me) |              100 |                       166 |                     123 |                         66 |                                       66% |                                   121 |                                    292 |
|             [North Dakota](/us-nd) |               74 |                       164 |                     215 |                         90 |                                      122% |                                   113 |                                    294 |
|            [West Virginia](/us-wv) |               88 |                       144 |                      80 |                         56 |                                       64% |                                   104 |                                    241 |
|                    [Idaho](/us-id) |               87 |                       110 |                      62 |                         23 |                                       26% |                                    97 |                                    140 |
|                  [Vermont](/us-vt) |               55 |                        67 |                     107 |                         12 |                                       22% |                                    61 |                                     85 |
|                  [Wyoming](/us-wy) |               18 |                        29 |                      50 |                         11 |                                       61% |                                    24 |                                     36 |
|                  [Montana](/us-mt) |               18 |                        22 |                      21 |                          4 |                                       22% |                                    19 |                                     30 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     24 |
|                   [Alaska](/us-ak) |               12 |                        15 |                      21 |                          3 |                                       25% |                                    13 |                                     18 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          174,858 |                   206,214 |                     348 |                     31,356 |                                       18% |                               182,947 |                                252,984 |
| [United Kingdom](/united-kingdom) |           41,566 |                    51,037 |                     756 |                      9,471 |                                       23% |                                44,911 |                                 59,561 |
|                   [Italy](/italy) |           34,223 |                    36,002 |                     596 |                      1,779 |                                        5% |                                34,541 |                                 36,979 |
|                 [France](/france) |           29,377 |                    31,206 |                     466 |                      1,829 |                                        6% |                                29,495 |                                 37,759 |
|                   [Spain](/spain) |           27,136 |                    28,520 |                     608 |                      1,384 |                                        5% |                                27,228 |                                 33,726 |
|               [Germany](/germany) |            8,783 |                    10,735 |                     129 |                      1,952 |                                       22% |                                 9,054 |                                 15,088 |
|               [Belgium](/belgium) |            9,646 |                    10,225 |                     893 |                        579 |                                        6% |                                 9,744 |                                 11,631 |
|                 [Sweden](/sweden) |            4,854 |                     7,285 |                     712 |                      2,431 |                                       50% |                                 5,713 |                                  9,383 |
|       [Netherlands](/netherlands) |            6,072 |                     6,991 |                     405 |                        919 |                                       15% |                                 6,220 |                                  9,193 |
|               [Ukraine](/ukraine) |              880 |                     4,406 |                     100 |                      3,526 |                                      401% |                                 1,754 |                                  7,668 |
|                 [Poland](/poland) |            1,222 |                     3,221 |                      85 |                      1,999 |                                      164% |                                 1,604 |                                  6,511 |
|               [Romania](/romania) |            1,380 |                     2,155 |                     111 |                        775 |                                       56% |                                 1,647 |                                  3,619 |
|             [Portugal](/portugal) |            1,505 |                     2,111 |                     205 |                        606 |                                       40% |                                 1,680 |                                  3,415 |
|       [Switzerland](/switzerland) |            1,938 |                     2,080 |                     242 |                        142 |                                        7% |                                 1,964 |                                  2,365 |
|               [Moldova](/moldova) |              385 |                     2,050 |                     507 |                      1,665 |                                      432% |                                   885 |                                  3,360 |
|               [Ireland](/ireland) |            1,705 |                     1,872 |                     382 |                        167 |                                       10% |                                 1,728 |                                  2,523 |
|               [Belarus](/belarus) |              298 |                       927 |                      98 |                        629 |                                      211% |                                   458 |                                  2,495 |
|               [Hungary](/hungary) |              555 |                       873 |                      89 |                        318 |                                       57% |                                   614 |                                  1,657 |
|             [Bulgaria](/bulgaria) |              172 |                       785 |                     112 |                        613 |                                      356% |                                   334 |                                  1,420 |
|               [Austria](/austria) |              675 |                       746 |                      84 |                         71 |                                       11% |                                   698 |                                    880 |
|               [Denmark](/denmark) |              594 |                       701 |                     121 |                        107 |                                       18% |                                   630 |                                    870 |
|               [Finland](/finland) |              325 |                       389 |                      70 |                         64 |                                       20% |                                   338 |                                    532 |
|               [Czechia](/czechia) |              329 |                       368 |                      35 |                         39 |                                       12% |                                   348 |                                    412 |
|                 [Serbia](/serbia) |              252 |                       322 |                      46 |                         70 |                                       28% |                                   284 |                                    426 |
|                 [Norway](/norway) |              242 |                       273 |                      51 |                         31 |                                       13% |                                   254 |                                    319 |
|                 [Greece](/greece) |              183 |                       226 |                      21 |                         43 |                                       23% |                                   203 |                                    276 |
|               [Croatia](/croatia) |              107 |                       147 |                      36 |                         40 |                                       37% |                                   119 |                                    228 |
|         [Luxembourg](/luxembourg) |              110 |                       125 |                     204 |                         15 |                                       14% |                                   114 |                                    146 |
|             [Slovenia](/slovenia) |              109 |                       123 |                      59 |                         14 |                                       13% |                                   113 |                                    149 |
|           [Lithuania](/lithuania) |               74 |                       120 |                      43 |                         46 |                                       62% |                                    91 |                                    183 |
|               [Estonia](/estonia) |               69 |                        82 |                      62 |                         13 |                                       19% |                                    79 |                                     88 |
|                 [Latvia](/latvia) |               27 |                        34 |                      18 |                          7 |                                       26% |                                    31 |                                     37 |
|             [Slovakia](/slovakia) |               28 |                        32 |                       6 |                          4 |                                       14% |                                    29 |                                     35 |
|                 [Cyprus](/cyprus) |               18 |                        21 |                      24 |                          3 |                                       17% |                                    20 |                                     23 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     15 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          131,229 |                   699,935 |                     135 |                    568,706 |                                      433% |                               350,378 |                              1,133,674 |
|                             [Brazil](/brazil) |           41,828 |                   165,472 |                     784 |                    123,644 |                                      296% |                                82,305 |                                271,402 |
|                               [India](/india) |            8,887 |                   150,670 |                     110 |                    141,783 |                                     1595% |                                50,707 |                                279,921 |
|                             [Mexico](/mexico) |           16,448 |                   108,271 |                     849 |                     91,823 |                                      558% |                                68,763 |                                129,022 |
|                 [South Africa](/south-africa) |            1,354 |                    32,896 |                     562 |                     31,542 |                                     2330% |                                16,425 |                                 48,423 |
|                         [Pakistan](/pakistan) |            2,570 |                    32,689 |                     151 |                     30,119 |                                     1172% |                                14,195 |                                 62,048 |
|                                 [Peru](/peru) |            6,088 |                    26,290 |                     809 |                     20,202 |                                      332% |                                12,080 |                                 39,921 |
|                               [Chile](/chile) |            2,870 |                    24,626 |                   1,299 |                     21,756 |                                      758% |                                15,929 |                                 36,967 |
|                             [Russia](/russia) |            6,705 |                    24,519 |                     168 |                     17,814 |                                      266% |                                11,750 |                                 45,812 |
|                         [Colombia](/colombia) |            1,562 |                    20,342 |                     404 |                     18,780 |                                     1202% |                                11,249 |                                 26,606 |
|                                 [Iran](/iran) |            8,659 |                    15,155 |                     183 |                      6,496 |                                       75% |                                10,191 |                                 25,470 |
|                             [Canada](/canada) |            8,125 |                    14,259 |                     381 |                      6,134 |                                       75% |                                 9,215 |                                 27,125 |
|                     [Bangladesh](/bangladesh) |            1,095 |                    10,438 |                      64 |                      9,343 |                                      853% |                                 5,664 |                                 15,021 |
|                       [Indonesia](/indonesia) |            2,048 |                    10,231 |                      38 |                      8,183 |                                      400% |                                 4,161 |                                 20,172 |
|                               [Egypt](/egypt) |            1,422 |                    10,231 |                     102 |                      8,809 |                                      619% |                                 4,226 |                                 16,082 |
|                 [Saudi Arabia](/saudi-arabia) |              893 |                     7,815 |                     228 |                      6,922 |                                      775% |                                 4,952 |                                 11,453 |
|                       [Argentina](/argentina) |              785 |                     7,250 |                     162 |                      6,465 |                                      824% |                                 2,945 |                                 12,266 |
|                           [Ecuador](/ecuador) |            3,828 |                     6,657 |                     383 |                      2,829 |                                       74% |                                 4,354 |                                 13,702 |
|                           [Bolivia](/bolivia) |              559 |                     6,464 |                     561 |                      5,905 |                                     1056% |                                 3,637 |                                  9,484 |
|                             [Turkey](/turkey) |            4,778 |                     5,686 |                      68 |                        908 |                                       19% |                                 4,928 |                                  8,195 |
|                               [China](/china) |            4,638 |                     4,647 |                       3 |                          9 |                                        0% |                                 4,638 |                                  4,705 |
|                           [Nigeria](/nigeria) |              399 |                     2,501 |                      12 |                      2,102 |                                      527% |                                   721 |                                  5,258 |
|                   [Philippines](/philippines) |            1,052 |                     2,149 |                      20 |                      1,097 |                                      104% |                                 1,226 |                                  4,730 |
|                         [Honduras](/honduras) |              306 |                     1,914 |                     196 |                      1,608 |                                      525% |                                   789 |                                  3,445 |
|                             [Kuwait](/kuwait) |              285 |                     1,723 |                     410 |                      1,438 |                                      505% |                                   757 |                                  2,823 |
|                           [Algeria](/algeria) |              751 |                     1,582 |                      37 |                        831 |                                      111% |                                   861 |                                  4,593 |
|                             [Panama](/panama) |              421 |                     1,423 |                     335 |                      1,002 |                                      238% |                                   600 |                                  2,818 |
|                               [Japan](/japan) |              924 |                     1,207 |                      10 |                        283 |                                       31% |                                   935 |                                  1,632 |
|     [Dominican Republic](/dominican-republic) |              568 |                     1,020 |                      95 |                        452 |                                       80% |                                   676 |                                  1,857 |
| [United Arab Emirates](/united-arab-emirates) |              287 |                       523 |                      54 |                        236 |                                       82% |                                   341 |                                  1,104 |
|                             [Israel](/israel) |              300 |                       372 |                      44 |                         72 |                                       24% |                                   326 |                                    509 |
|                   [South Korea](/south-korea) |              277 |                       323 |                       6 |                         46 |                                       17% |                                   282 |                                    439 |
|                           [Morocco](/morocco) |              212 |                       239 |                       7 |                         27 |                                       13% |                                   223 |                                    273 |
|                         [Malaysia](/malaysia) |              119 |                       146 |                       5 |                         27 |                                       23% |                                   135 |                                    162 |
|                       [Australia](/australia) |              102 |                       106 |                       4 |                          4 |                                        4% |                                   102 |                                    123 |
|                                 [Cuba](/cuba) |               84 |                        99 |                       9 |                         15 |                                       18% |                                    90 |                                    111 |
