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

* **June 25:** Our analysis shows that having *no* model [is better](/about/#baseline-comparison-c19pro-vs-ihme) than having IHME's model for US state-by-state projections.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: June 26 (5pm ET):
<p align="center">
  Current Total: <b>124,407</b> deaths | Projected Total: <b>191,883 deaths by Oct 1, 2020</b> (Range: 160-232k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.9%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: Jun 26, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 22, 2020 |
|              125,000 |        Jun 26, 2020 |
|              130,000 |         Jul 5, 2020 |
|              140,000 |        Jul 21, 2020 |
|              150,000 |         Aug 4, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |       >99% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        35% |         81% |        99% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |          2% |        37% |         56% |        70% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         12% |        32% |
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
|             *[United States](/us)* |          124,407 |                   191,883 |                     578 |                     67,476 |                                       54% |                               160,615 |                                231,191 |
|                 [New York](/us-ny) |           31,301 |                    33,386 |                   1,716 |                      2,085 |                                        7% |                                31,426 |                                 39,266 |
|               [New Jersey](/us-nj) |           14,872 |                    16,556 |                   1,864 |                      1,684 |                                       11% |                                15,142 |                                 17,999 |
|               [California](/us-ca) |            5,806 |                    15,685 |                     397 |                      9,879 |                                      170% |                                 8,671 |                                 23,683 |
|                 [Illinois](/us-il) |            6,810 |                    10,424 |                     823 |                      3,614 |                                       53% |                                 8,007 |                                 12,798 |
|            [Massachusetts](/us-ma) |            7,962 |                     9,540 |                   1,373 |                      1,578 |                                       20% |                                 8,309 |                                 11,782 |
|             [Pennsylvania](/us-pa) |            6,557 |                     9,307 |                     727 |                      2,750 |                                       42% |                                 7,022 |                                 13,801 |
|                  [Florida](/us-fl) |            3,327 |                     9,152 |                     426 |                      5,825 |                                      175% |                                 5,632 |                                 13,653 |
|                    [Texas](/us-tx) |            2,317 |                     7,278 |                     251 |                      4,961 |                                      214% |                                 4,322 |                                 10,952 |
|                 [Michigan](/us-mi) |            6,133 |                     7,200 |                     721 |                      1,067 |                                       17% |                                 6,267 |                                  8,912 |
|                  [Georgia](/us-ga) |            2,745 |                     6,234 |                     587 |                      3,489 |                                      127% |                                 3,461 |                                  9,469 |
|                     [Ohio](/us-oh) |            2,772 |                     5,304 |                     454 |                      2,532 |                                       91% |                                 3,241 |                                  8,398 |
|                  [Arizona](/us-az) |            1,495 |                     5,037 |                     692 |                      3,542 |                                      237% |                                 3,276 |                                  6,896 |
|              [Connecticut](/us-ct) |            4,298 |                     4,807 |                   1,348 |                        509 |                                       12% |                                 4,404 |                                  5,296 |
|                 [Maryland](/us-md) |            3,129 |                     4,695 |                     777 |                      1,566 |                                       50% |                                 3,469 |                                  6,148 |
|                  [Indiana](/us-in) |            2,586 |                     4,275 |                     635 |                      1,689 |                                       65% |                                 2,824 |                                  7,153 |
|                [Louisiana](/us-la) |            3,164 |                     4,195 |                     902 |                      1,031 |                                       33% |                                 3,349 |                                  5,729 |
|           [North Carolina](/us-nc) |            1,336 |                     3,461 |                     330 |                      2,125 |                                      159% |                                 1,815 |                                  5,607 |
|                [Minnesota](/us-mn) |            1,441 |                     2,920 |                     518 |                      1,479 |                                      103% |                                 1,806 |                                  4,307 |
|                 [Virginia](/us-va) |            1,675 |                     2,789 |                     327 |                      1,114 |                                       67% |                                 1,831 |                                  4,418 |
|                 [Colorado](/us-co) |            1,669 |                     2,596 |                     451 |                        927 |                                       56% |                                 1,763 |                                  4,238 |
|                  [Alabama](/us-al) |              896 |                     2,576 |                     525 |                      1,680 |                                      188% |                                 1,375 |                                  3,885 |
|               [Washington](/us-wa) |            1,300 |                     2,493 |                     327 |                      1,193 |                                       92% |                                 1,496 |                                  5,012 |
|              [Mississippi](/us-ms) |            1,016 |                     2,141 |                     719 |                      1,125 |                                      111% |                                 1,237 |                                  3,352 |
|           [South Carolina](/us-sc) |              693 |                     2,066 |                     401 |                      1,373 |                                      198% |                                 1,089 |                                  3,118 |
|                [Tennessee](/us-tn) |              567 |                     1,797 |                     263 |                      1,230 |                                      217% |                                   849 |                                  2,781 |
|                 [Missouri](/us-mo) |              987 |                     1,742 |                     284 |                        755 |                                       76% |                                 1,102 |                                  3,025 |
|                [Wisconsin](/us-wi) |              766 |                     1,683 |                     289 |                        917 |                                      120% |                                   942 |                                  2,675 |
|             [Rhode Island](/us-ri) |              920 |                     1,407 |                   1,328 |                        487 |                                       53% |                                 1,056 |                                  1,795 |
|                 [Kentucky](/us-ky) |              546 |                     1,119 |                     250 |                        573 |                                      105% |                                   650 |                                  1,817 |
|                     [Iowa](/us-ia) |              696 |                     1,054 |                     334 |                        358 |                                       51% |                                   757 |                                  1,991 |
|               [New Mexico](/us-nm) |              485 |                       957 |                     456 |                        472 |                                       97% |                                   580 |                                  1,536 |
|                   [Nevada](/us-nv) |              495 |                       928 |                     301 |                        433 |                                       87% |                                   573 |                                  1,566 |
|                 [Arkansas](/us-ar) |              240 |                       915 |                     303 |                        675 |                                      281% |                                   497 |                                  1,387 |
|                 [Delaware](/us-de) |              507 |                       741 |                     761 |                        234 |                                       46% |                                   547 |                                  1,139 |
|            [New Hampshire](/us-nh) |              357 |                       739 |                     543 |                        382 |                                      107% |                                   422 |                                  1,180 |
|     [District of Columbia](/us-dc) |              543 |                       723 |                   1,024 |                        180 |                                       33% |                                   580 |                                    952 |
|                 [Oklahoma](/us-ok) |              375 |                       670 |                     169 |                        295 |                                       79% |                                   421 |                                  1,170 |
|                 [Nebraska](/us-ne) |              260 |                       660 |                     341 |                        400 |                                      154% |                                   375 |                                  1,145 |
|                     [Utah](/us-ut) |              164 |                       527 |                     164 |                        363 |                                      221% |                                   271 |                                    825 |
|                   [Oregon](/us-or) |              197 |                       451 |                     107 |                        254 |                                      129% |                                   243 |                                    764 |
|                   [Kansas](/us-ks) |              262 |                       449 |                     154 |                        187 |                                       71% |                                   287 |                                    899 |
|             [South Dakota](/us-sd) |               87 |                       207 |                     234 |                        120 |                                      138% |                                   112 |                                    403 |
|              [Puerto Rico](/us-pr) |              151 |                       205 |                      64 |                         54 |                                       36% |                                   163 |                                    313 |
|                    [Idaho](/us-id) |               90 |                       154 |                      86 |                         64 |                                       71% |                                    96 |                                    231 |
|                    [Maine](/us-me) |              103 |                       146 |                     109 |                         43 |                                       42% |                                   114 |                                    223 |
|            [West Virginia](/us-wv) |               92 |                       137 |                      76 |                         45 |                                       49% |                                   102 |                                    245 |
|             [North Dakota](/us-nd) |               78 |                       126 |                     165 |                         48 |                                       62% |                                    92 |                                    210 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    59 |                                    103 |
|                  [Montana](/us-mt) |               21 |                        43 |                      40 |                         22 |                                      105% |                                    22 |                                     77 |
|                  [Wyoming](/us-wy) |               20 |                        40 |                      69 |                         20 |                                      100% |                                    25 |                                     94 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    17 |                                     34 |
|                   [Alaska](/us-ak) |               12 |                        23 |                      31 |                         11 |                                       92% |                                    13 |                                     64 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     17 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     3 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          180,284 |                   200,855 |                     339 |                     20,571 |                                       11% |                               184,889 |                                229,480 |
| [United Kingdom](/united-kingdom) |           43,314 |                    47,877 |                     709 |                      4,563 |                                       11% |                                44,758 |                                 50,815 |
|                   [Italy](/italy) |           34,678 |                    36,850 |                     611 |                      2,172 |                                        6% |                                34,976 |                                 39,084 |
|                 [France](/france) |           29,755 |                    30,763 |                     459 |                      1,008 |                                        3% |                                29,791 |                                 34,909 |
|                   [Spain](/spain) |           28,330 |                    29,386 |                     626 |                      1,056 |                                        4% |                                28,386 |                                 31,962 |
|               [Germany](/germany) |            8,940 |                    10,597 |                     128 |                      1,657 |                                       19% |                                 9,060 |                                 14,164 |
|               [Belgium](/belgium) |            9,726 |                     9,967 |                     870 |                        241 |                                        2% |                                 9,748 |                                 10,539 |
|       [Netherlands](/netherlands) |            6,119 |                     6,625 |                     383 |                        506 |                                        8% |                                 6,173 |                                  7,617 |
|                 [Sweden](/sweden) |            5,230 |                     6,381 |                     624 |                      1,151 |                                       22% |                                 5,513 |                                  8,027 |
|                 [Poland](/poland) |            1,412 |                     3,218 |                      85 |                      1,806 |                                      128% |                                 1,875 |                                  4,891 |
|               [Ukraine](/ukraine) |            1,078 |                     3,193 |                      73 |                      2,115 |                                      196% |                                 1,714 |                                  5,157 |
|               [Romania](/romania) |            1,565 |                     2,668 |                     137 |                      1,103 |                                       70% |                                 1,798 |                                  4,033 |
|       [Switzerland](/switzerland) |            1,958 |                     2,055 |                     239 |                         97 |                                        5% |                                 1,971 |                                  2,324 |
|             [Portugal](/portugal) |            1,549 |                     1,888 |                     184 |                        339 |                                       22% |                                 1,624 |                                  2,496 |
|               [Ireland](/ireland) |            1,727 |                     1,826 |                     372 |                         99 |                                        6% |                                 1,738 |                                  2,247 |
|               [Moldova](/moldova) |              502 |                     1,513 |                     374 |                      1,011 |                                      201% |                                   977 |                                  2,267 |
|               [Belarus](/belarus) |              367 |                       807 |                      85 |                        440 |                                      120% |                                   481 |                                  1,796 |
|               [Hungary](/hungary) |              577 |                       781 |                      80 |                        204 |                                       35% |                                   602 |                                  1,168 |
|               [Austria](/austria) |              698 |                       779 |                      88 |                         81 |                                       12% |                                   712 |                                    971 |
|               [Denmark](/denmark) |              603 |                       677 |                     117 |                         74 |                                       12% |                                   622 |                                    842 |
|             [Bulgaria](/bulgaria) |              211 |                       642 |                      92 |                        431 |                                      204% |                                   341 |                                  1,043 |
|               [Czechia](/czechia) |              345 |                       444 |                      42 |                         99 |                                       29% |                                   355 |                                    572 |
|               [Finland](/finland) |              327 |                       367 |                      67 |                         40 |                                       12% |                                   332 |                                    468 |
|                 [Serbia](/serbia) |              264 |                       333 |                      48 |                         69 |                                       26% |                                   282 |                                    463 |
|                 [Norway](/norway) |              249 |                       274 |                      51 |                         25 |                                       10% |                                   256 |                                    319 |
|                 [Greece](/greece) |              191 |                       225 |                      21 |                         34 |                                       18% |                                   204 |                                    283 |
|               [Croatia](/croatia) |              107 |                       131 |                      32 |                         24 |                                       22% |                                   113 |                                    168 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    141 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   111 |                                    144 |
|           [Lithuania](/lithuania) |               78 |                       115 |                      41 |                         37 |                                       47% |                                    87 |                                    172 |
|               [Estonia](/estonia) |               69 |                        93 |                      70 |                         24 |                                       35% |                                    76 |                                    163 |
|                 [Latvia](/latvia) |               30 |                        53 |                      28 |                         23 |                                       77% |                                    33 |                                     87 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    28 |                                     69 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     45 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          176,510 |                   585,992 |                     113 |                    409,482 |                                      232% |                               342,585 |                                980,649 |
|                             [Brazil](/brazil) |           54,971 |                   137,146 |                     650 |                     82,175 |                                      149% |                               102,852 |                                217,131 |
|                               [India](/india) |           15,301 |                   109,834 |                      80 |                     94,533 |                                      618% |                                37,208 |                                245,158 |
|                             [Mexico](/mexico) |           25,060 |                   105,394 |                     826 |                     80,334 |                                      321% |                                66,722 |                                138,124 |
|                         [Pakistan](/pakistan) |            3,962 |                    24,901 |                     115 |                     20,939 |                                      528% |                                10,080 |                                 52,160 |
|                                 [Peru](/peru) |            8,761 |                    22,789 |                     701 |                     14,028 |                                      160% |                                15,250 |                                 34,037 |
|                                 [Iran](/iran) |           10,130 |                    20,385 |                     246 |                     10,255 |                                      101% |                                14,878 |                                 26,389 |
|                             [Russia](/russia) |            8,594 |                    19,561 |                     134 |                     10,967 |                                      128% |                                11,937 |                                 34,917 |
|                         [Colombia](/colombia) |            2,611 |                    19,406 |                     386 |                     16,795 |                                      643% |                                 9,545 |                                 27,812 |
|                 [South Africa](/south-africa) |            2,292 |                    18,533 |                     316 |                     16,241 |                                      709% |                                 8,852 |                                 26,791 |
|                               [Chile](/chile) |            4,903 |                    13,237 |                     698 |                      8,334 |                                      170% |                                 7,436 |                                 19,780 |
|                               [Egypt](/egypt) |            2,533 |                    12,692 |                     126 |                     10,159 |                                      401% |                                 7,062 |                                 20,457 |
|                             [Canada](/canada) |            8,567 |                    11,402 |                     305 |                      2,835 |                                       33% |                                 9,088 |                                 18,014 |
|                     [Bangladesh](/bangladesh) |            1,621 |                     9,097 |                      56 |                      7,476 |                                      461% |                                 4,412 |                                 15,816 |
|                       [Indonesia](/indonesia) |            2,620 |                     8,083 |                      30 |                      5,463 |                                      209% |                                 4,049 |                                 13,784 |
|                             [Turkey](/turkey) |            5,046 |                     7,716 |                      92 |                      2,670 |                                       53% |                                 5,462 |                                 13,694 |
|                       [Argentina](/argentina) |            1,150 |                     6,721 |                     150 |                      5,571 |                                      484% |                                 2,843 |                                 12,618 |
|                 [Saudi Arabia](/saudi-arabia) |            1,428 |                     6,285 |                     183 |                      4,857 |                                      340% |                                 3,638 |                                  9,029 |
|                           [Ecuador](/ecuador) |            4,343 |                     6,099 |                     351 |                      1,756 |                                       40% |                                 4,718 |                                 10,618 |
|                           [Bolivia](/bolivia) |              913 |                     6,073 |                     527 |                      5,160 |                                      565% |                                 2,909 |                                  9,744 |
|                               [China](/china) |            4,641 |                     4,651 |                       3 |                         10 |                                        0% |                                 4,641 |                                  4,703 |
|                   [Philippines](/philippines) |            1,212 |                     2,418 |                      22 |                      1,206 |                                      100% |                                 1,314 |                                  4,358 |
|                           [Nigeria](/nigeria) |              549 |                     2,313 |                      12 |                      1,764 |                                      321% |                                   881 |                                  4,943 |
|                           [Algeria](/algeria) |              878 |                     2,182 |                      51 |                      1,304 |                                      149% |                                 1,253 |                                  4,468 |
|                         [Honduras](/honduras) |              426 |                     1,888 |                     194 |                      1,462 |                                      343% |                                   949 |                                  3,167 |
|                             [Panama](/panama) |              564 |                     1,764 |                     415 |                      1,200 |                                      213% |                                   872 |                                  2,966 |
|     [Dominican Republic](/dominican-republic) |              698 |                     1,655 |                     154 |                        957 |                                      137% |                                   864 |                                  4,096 |
|                               [Japan](/japan) |              971 |                     1,296 |                      10 |                        325 |                                       33% |                                   977 |                                  1,875 |
|                             [Kuwait](/kuwait) |              339 |                       593 |                     141 |                        254 |                                       75% |                                   394 |                                  1,005 |
| [United Arab Emirates](/united-arab-emirates) |              308 |                       433 |                      44 |                        125 |                                       41% |                                   334 |                                    763 |
|                             [Israel](/israel) |              309 |                       390 |                      46 |                         81 |                                       26% |                                   324 |                                    614 |
|                   [South Korea](/south-korea) |              282 |                       341 |                       7 |                         59 |                                       21% |                                   285 |                                    536 |
|                         [Malaysia](/malaysia) |              121 |                       250 |                       8 |                        129 |                                      107% |                                   137 |                                    477 |
|                           [Morocco](/morocco) |              217 |                       249 |                       7 |                         32 |                                       15% |                                   225 |                                    324 |
|                       [Australia](/australia) |              104 |                       113 |                       4 |                          9 |                                        9% |                                   104 |                                    151 |
|                                 [Cuba](/cuba) |               85 |                       102 |                       9 |                         17 |                                       20% |                                    90 |                                    130 |
