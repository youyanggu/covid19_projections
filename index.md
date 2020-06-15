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
### Updated Daily - Last Updated: June 15 (8am ET):
<p align="center">
  Current Total: <b>115,729</b> deaths | Projected Total: <b>174,544 deaths by Sep 1 | 192,855 deaths by Oct 1, 2020</b> (Range: 147-286k)<br>
  Currently Infected: <b>0.5%</b> | Total Infected: <b>4.4%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 79% chance that the US surpasses 125,000 deaths by July 1, with June 28 being the most likely date.

Last updated: Jun 15, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 21, 2020 |
|              125,000 |        Jun 28, 2020 |
|              130,000 |         Jul 5, 2020 |
|              140,000 |        Jul 19, 2020 |
|              150,000 |         Aug 1, 2020 |

<br>

|   US deaths surpass: |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |         <1% |        79% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |         <1% |        <1% |          3% |        46% |         66% |        82% |         88% |        91% |
|              175,000 |         <1% |        <1% |         <1% |         3% |         21% |        40% |         49% |        56% |
|              200,000 |         <1% |        <1% |         <1% |        <1% |          2% |        16% |         26% |        33% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |          3% |         9% |
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

States are ordered by descending projected deaths (by October 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          115,729 |                   192,855 |                     581 |                     77,126 |                                       67% |                               144,796 |                                276,020 |
|                 [New York](/us-ny) |           30,825 |                    33,031 |                   1,698 |                      2,206 |                                        7% |                                31,130 |                                 37,430 |
|               [California](/us-ca) |            5,099 |                    16,862 |                     427 |                     11,763 |                                      231% |                                 7,489 |                                 31,893 |
|               [New Jersey](/us-nj) |           12,659 |                    15,250 |                   1,717 |                      2,591 |                                       20% |                                13,356 |                                 17,839 |
|                 [Illinois](/us-il) |            6,308 |                    12,034 |                     950 |                      5,726 |                                       91% |                                 7,916 |                                 18,147 |
|            [Massachusetts](/us-ma) |            7,624 |                     9,839 |                   1,416 |                      2,215 |                                       29% |                                 8,236 |                                 13,393 |
|             [Pennsylvania](/us-pa) |            6,215 |                     9,578 |                     748 |                      3,363 |                                       54% |                                 6,808 |                                 16,412 |
|                  [Florida](/us-fl) |            2,931 |                     8,621 |                     401 |                      5,690 |                                      194% |                                 4,040 |                                 16,623 |
|                 [Michigan](/us-mi) |            6,016 |                     7,107 |                     712 |                      1,091 |                                       18% |                                 6,278 |                                  9,671 |
|                  [Georgia](/us-ga) |            2,451 |                     5,768 |                     543 |                      3,317 |                                      135% |                                 3,371 |                                 11,239 |
|                 [Maryland](/us-md) |            2,939 |                     5,488 |                     908 |                      2,549 |                                       87% |                                 3,469 |                                  8,513 |
|                     [Ohio](/us-oh) |            2,559 |                     5,334 |                     456 |                      2,775 |                                      108% |                                 3,149 |                                  9,410 |
|              [Connecticut](/us-ct) |            4,201 |                     5,280 |                   1,481 |                      1,079 |                                       26% |                                 4,484 |                                  6,986 |
|                    [Texas](/us-tx) |            1,984 |                     4,404 |                     152 |                      2,420 |                                      122% |                                 2,626 |                                  9,920 |
|                [Louisiana](/us-la) |            3,014 |                     4,278 |                     920 |                      1,264 |                                       42% |                                 3,317 |                                  6,534 |
|                  [Arizona](/us-az) |            1,191 |                     4,170 |                     573 |                      2,979 |                                      250% |                                 1,747 |                                  8,079 |
|                  [Indiana](/us-in) |            2,422 |                     4,065 |                     604 |                      1,643 |                                       68% |                                 2,737 |                                  7,681 |
|           [North Carolina](/us-nc) |            1,132 |                     3,941 |                     376 |                      2,809 |                                      248% |                                 1,803 |                                  7,575 |
|                 [Virginia](/us-va) |            1,546 |                     3,762 |                     441 |                      2,216 |                                      143% |                                 1,906 |                                  7,723 |
|                [Minnesota](/us-mn) |            1,329 |                     3,315 |                     588 |                      1,986 |                                      149% |                                 1,993 |                                  4,912 |
|                 [Colorado](/us-co) |            1,598 |                     2,936 |                     510 |                      1,338 |                                       84% |                                 1,780 |                                  6,127 |
|                 [Missouri](/us-mo) |              885 |                     2,549 |                     415 |                      1,664 |                                      188% |                                 1,223 |                                  5,196 |
|               [Washington](/us-wa) |            1,217 |                     2,454 |                     322 |                      1,237 |                                      102% |                                 1,358 |                                  5,645 |
|                  [Alabama](/us-al) |              773 |                     2,396 |                     489 |                      1,623 |                                      210% |                                 1,104 |                                  4,788 |
|              [Mississippi](/us-ms) |              891 |                     2,194 |                     737 |                      1,303 |                                      146% |                                 1,103 |                                  4,354 |
|           [South Carolina](/us-sc) |              600 |                     2,052 |                     399 |                      1,452 |                                      242% |                                   902 |                                  3,956 |
|                [Wisconsin](/us-wi) |              692 |                     1,916 |                     329 |                      1,224 |                                      177% |                                   963 |                                  3,803 |
|             [Rhode Island](/us-ri) |              833 |                     1,536 |                   1,450 |                        703 |                                       84% |                                 1,031 |                                  2,339 |
|                 [Kentucky](/us-ky) |              499 |                     1,334 |                     299 |                        835 |                                      167% |                                   656 |                                  2,769 |
|                [Tennessee](/us-tn) |              474 |                     1,178 |                     172 |                        704 |                                      149% |                                   663 |                                  2,367 |
|               [New Mexico](/us-nm) |              435 |                     1,172 |                     559 |                        737 |                                      169% |                                   558 |                                  2,343 |
|                     [Iowa](/us-ia) |              652 |                     1,143 |                     362 |                        491 |                                       75% |                                   776 |                                  1,998 |
|                   [Nevada](/us-nv) |              463 |                     1,036 |                     336 |                        573 |                                      124% |                                   569 |                                  2,088 |
|            [New Hampshire](/us-nh) |              320 |                       980 |                     721 |                        660 |                                      206% |                                   430 |                                  1,928 |
|     [District of Columbia](/us-dc) |              515 |                       779 |                   1,104 |                        264 |                                       51% |                                   574 |                                  1,190 |
|                 [Delaware](/us-de) |              422 |                       773 |                     794 |                        351 |                                       83% |                                   490 |                                  1,425 |
|                 [Arkansas](/us-ar) |              179 |                       768 |                     254 |                        589 |                                      329% |                                   296 |                                  1,491 |
|                 [Nebraska](/us-ne) |              215 |                       597 |                     309 |                        382 |                                      178% |                                   362 |                                    977 |
|                     [Utah](/us-ut) |              139 |                       577 |                     180 |                        438 |                                      315% |                                   225 |                                  1,214 |
|                 [Oklahoma](/us-ok) |              359 |                       498 |                     126 |                        139 |                                       39% |                                   409 |                                    745 |
|                   [Kansas](/us-ks) |              245 |                       403 |                     138 |                        158 |                                       64% |                                   275 |                                    810 |
|                   [Oregon](/us-or) |              173 |                       319 |                      76 |                        146 |                                       84% |                                   199 |                                    676 |
|              [Puerto Rico](/us-pr) |              147 |                       217 |                      68 |                         70 |                                       48% |                                   167 |                                    353 |
|             [South Dakota](/us-sd) |               75 |                       185 |                     209 |                        110 |                                      147% |                                    99 |                                    399 |
|                    [Maine](/us-me) |              100 |                       162 |                     121 |                         62 |                                       62% |                                   120 |                                    287 |
|             [North Dakota](/us-nd) |               74 |                       154 |                     202 |                         80 |                                      108% |                                   103 |                                    281 |
|            [West Virginia](/us-wv) |               88 |                       137 |                      76 |                         49 |                                       56% |                                   102 |                                    229 |
|                    [Idaho](/us-id) |               87 |                       109 |                      61 |                         22 |                                       25% |                                    96 |                                    138 |
|                  [Vermont](/us-vt) |               55 |                        67 |                     107 |                         12 |                                       22% |                                    60 |                                     85 |
|                  [Wyoming](/us-wy) |               18 |                        28 |                      48 |                         10 |                                       56% |                                    24 |                                     34 |
|                  [Montana](/us-mt) |               19 |                        25 |                      23 |                          6 |                                       32% |                                    20 |                                     32 |
|                   [Hawaii](/us-hi) |               17 |                        21 |                      15 |                          4 |                                       24% |                                    19 |                                     23 |
|                   [Alaska](/us-ak) |               12 |                        14 |                      19 |                          2 |                                       17% |                                    13 |                                     17 |
|           [Virgin Islands](/us-vi) |                6 |                         8 |                      76 |                          2 |                                       33% |                                     7 |                                      9 |
|                     [Guam](/us-gu) |                5 |                         7 |                      42 |                          2 |                                       40% |                                     6 |                                      9 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     3 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          175,420 |                   203,772 |                     344 |                     28,352 |                                       16% |                               181,948 |                                247,746 |
| [United Kingdom](/united-kingdom) |           41,783 |                    50,484 |                     748 |                      8,701 |                                       21% |                                43,935 |                                 59,295 |
|                   [Italy](/italy) |           34,345 |                    36,036 |                     597 |                      1,691 |                                        5% |                                34,643 |                                 36,990 |
|                 [France](/france) |           29,410 |                    30,875 |                     461 |                      1,465 |                                        5% |                                29,503 |                                 36,180 |
|                   [Spain](/spain) |           27,136 |                    28,476 |                     607 |                      1,340 |                                        5% |                                27,225 |                                 33,487 |
|               [Germany](/germany) |            8,801 |                    10,630 |                     128 |                      1,829 |                                       21% |                                 9,052 |                                 14,919 |
|               [Belgium](/belgium) |            9,655 |                    10,120 |                     883 |                        465 |                                        5% |                                 9,734 |                                 11,234 |
|       [Netherlands](/netherlands) |            6,078 |                     6,832 |                     395 |                        754 |                                       12% |                                 6,196 |                                  8,621 |
|                 [Sweden](/sweden) |            4,874 |                     6,318 |                     618 |                      1,444 |                                       30% |                                 5,435 |                                  7,565 |
|               [Ukraine](/ukraine) |              899 |                     3,972 |                      90 |                      3,073 |                                      342% |                                 1,640 |                                  7,366 |
|                 [Poland](/poland) |            1,247 |                     3,287 |                      87 |                      2,040 |                                      164% |                                 1,633 |                                  6,547 |
|               [Romania](/romania) |            1,410 |                     2,284 |                     118 |                        874 |                                       62% |                                 1,667 |                                  3,985 |
|               [Moldova](/moldova) |              406 |                     2,190 |                     542 |                      1,784 |                                      439% |                                 1,154 |                                  3,415 |
|             [Portugal](/portugal) |            1,517 |                     2,085 |                     203 |                        568 |                                       37% |                                 1,681 |                                  3,249 |
|       [Switzerland](/switzerland) |            1,938 |                     2,077 |                     242 |                        139 |                                        7% |                                 1,963 |                                  2,356 |
|               [Ireland](/ireland) |            1,706 |                     1,863 |                     380 |                        157 |                                        9% |                                 1,727 |                                  2,498 |
|               [Belarus](/belarus) |              308 |                       920 |                      97 |                        612 |                                      199% |                                   464 |                                  2,486 |
|               [Hungary](/hungary) |              562 |                       885 |                      91 |                        323 |                                       57% |                                   621 |                                  1,664 |
|               [Austria](/austria) |              677 |                       748 |                      84 |                         71 |                                       10% |                                   701 |                                    886 |
|               [Denmark](/denmark) |              597 |                       705 |                     121 |                        108 |                                       18% |                                   633 |                                    871 |
|             [Bulgaria](/bulgaria) |              174 |                       704 |                     101 |                        530 |                                      305% |                                   295 |                                  1,256 |
|               [Finland](/finland) |              326 |                       388 |                      70 |                         62 |                                       19% |                                   339 |                                    530 |
|               [Czechia](/czechia) |              329 |                       365 |                      34 |                         36 |                                       11% |                                   347 |                                    405 |
|                 [Serbia](/serbia) |              254 |                       325 |                      47 |                         71 |                                       28% |                                   284 |                                    437 |
|                 [Norway](/norway) |              242 |                       272 |                      51 |                         30 |                                       12% |                                   254 |                                    318 |
|                 [Greece](/greece) |              183 |                       225 |                      21 |                         42 |                                       23% |                                   203 |                                    275 |
|               [Croatia](/croatia) |              107 |                       146 |                      36 |                         39 |                                       36% |                                   119 |                                    224 |
|         [Luxembourg](/luxembourg) |              110 |                       124 |                     202 |                         14 |                                       13% |                                   114 |                                    146 |
|             [Slovenia](/slovenia) |              109 |                       123 |                      59 |                         14 |                                       13% |                                   113 |                                    148 |
|           [Lithuania](/lithuania) |               75 |                       120 |                      43 |                         45 |                                       60% |                                    91 |                                    183 |
|               [Estonia](/estonia) |               69 |                        82 |                      62 |                         13 |                                       19% |                                    79 |                                     87 |
|                 [Latvia](/latvia) |               28 |                        35 |                      18 |                          7 |                                       25% |                                    32 |                                     39 |
|             [Slovakia](/slovakia) |               28 |                        32 |                       6 |                          4 |                                       14% |                                    29 |                                     35 |
|                 [Cyprus](/cyprus) |               18 |                        21 |                      24 |                          3 |                                       17% |                                    20 |                                     23 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    11 |                                     14 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    11 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          136,737 |                   636,689 |                     123 |                    499,952 |                                      366% |                               334,529 |                              1,073,488 |
|                             [Brazil](/brazil) |           43,332 |                   138,131 |                     654 |                     94,799 |                                      219% |                                72,372 |                                222,520 |
|                               [India](/india) |            9,520 |                   135,478 |                      99 |                    125,958 |                                     1323% |                                59,250 |                                272,233 |
|                             [Mexico](/mexico) |           17,141 |                    84,329 |                     661 |                     67,188 |                                      392% |                                45,360 |                                116,466 |
|                 [South Africa](/south-africa) |            1,480 |                    32,738 |                     559 |                     31,258 |                                     2112% |                                16,457 |                                 48,231 |
|                         [Pakistan](/pakistan) |            2,729 |                    32,325 |                     149 |                     29,596 |                                     1084% |                                14,167 |                                 64,346 |
|                                 [Peru](/peru) |            6,688 |                    30,647 |                     943 |                     23,959 |                                      358% |                                20,388 |                                 41,581 |
|                               [Chile](/chile) |            3,323 |                    25,070 |                   1,323 |                     21,747 |                                      654% |                                16,582 |                                 37,170 |
|                             [Russia](/russia) |            6,938 |                    24,019 |                     165 |                     17,081 |                                      246% |                                11,634 |                                 48,362 |
|                         [Colombia](/colombia) |            1,670 |                    20,074 |                     399 |                     18,404 |                                     1102% |                                10,695 |                                 26,508 |
|                                 [Iran](/iran) |            8,837 |                    15,972 |                     193 |                      7,135 |                                       81% |                                10,520 |                                 30,322 |
|                             [Canada](/canada) |            8,218 |                    11,562 |                     309 |                      3,344 |                                       41% |                                 9,006 |                                 16,779 |
|                     [Bangladesh](/bangladesh) |            1,171 |                    10,875 |                      67 |                      9,704 |                                      829% |                                 5,694 |                                 17,421 |
|                               [Egypt](/egypt) |            1,575 |                    10,829 |                     108 |                      9,254 |                                      588% |                                 4,523 |                                 17,967 |
|                       [Indonesia](/indonesia) |            2,134 |                    10,488 |                      39 |                      8,354 |                                      391% |                                 4,284 |                                 20,134 |
|                 [Saudi Arabia](/saudi-arabia) |              972 |                     8,249 |                     241 |                      7,277 |                                      749% |                                 5,073 |                                 12,940 |
|                       [Argentina](/argentina) |              833 |                     6,959 |                     155 |                      6,126 |                                      735% |                                 2,990 |                                 12,528 |
|                           [Ecuador](/ecuador) |            3,896 |                     6,668 |                     384 |                      2,772 |                                       71% |                                 4,415 |                                 13,607 |
|                           [Bolivia](/bolivia) |              611 |                     6,535 |                     568 |                      5,924 |                                      970% |                                 3,579 |                                  9,599 |
|                             [Turkey](/turkey) |            4,807 |                     5,704 |                      68 |                        897 |                                       19% |                                 4,948 |                                  8,267 |
|                               [China](/china) |            4,638 |                     4,647 |                       3 |                          9 |                                        0% |                                 4,638 |                                  4,701 |
|                           [Nigeria](/nigeria) |              420 |                     2,544 |                      13 |                      2,124 |                                      506% |                                   771 |                                  5,258 |
|                   [Philippines](/philippines) |            1,088 |                     2,233 |                      21 |                      1,145 |                                      105% |                                 1,276 |                                  4,817 |
|                           [Algeria](/algeria) |              767 |                     2,129 |                      49 |                      1,362 |                                      178% |                                   898 |                                  6,329 |
|                         [Honduras](/honduras) |              312 |                     1,764 |                     181 |                      1,452 |                                      465% |                                   749 |                                  3,278 |
|                             [Panama](/panama) |              437 |                     1,470 |                     346 |                      1,033 |                                      236% |                                   637 |                                  2,844 |
|     [Dominican Republic](/dominican-republic) |              592 |                     1,433 |                     133 |                        841 |                                      142% |                                   747 |                                  3,463 |
|                               [Japan](/japan) |              927 |                     1,201 |                       9 |                        274 |                                       30% |                                   938 |                                  1,620 |
|                             [Kuwait](/kuwait) |              296 |                       867 |                     206 |                        571 |                                      193% |                                   454 |                                  1,595 |
| [United Arab Emirates](/united-arab-emirates) |              289 |                       469 |                      48 |                        180 |                                       62% |                                   327 |                                    998 |
|                             [Israel](/israel) |              300 |                       368 |                      43 |                         68 |                                       23% |                                   324 |                                    502 |
|                   [South Korea](/south-korea) |              277 |                       321 |                       6 |                         44 |                                       16% |                                   281 |                                    435 |
|                           [Morocco](/morocco) |              212 |                       238 |                       7 |                         26 |                                       12% |                                   222 |                                    270 |
|                         [Malaysia](/malaysia) |              121 |                       148 |                       5 |                         27 |                                       22% |                                   138 |                                    164 |
|                       [Australia](/australia) |              102 |                       106 |                       4 |                          4 |                                        4% |                                   102 |                                    122 |
|                                 [Cuba](/cuba) |               84 |                        99 |                       9 |                         15 |                                       18% |                                    90 |                                    111 |
