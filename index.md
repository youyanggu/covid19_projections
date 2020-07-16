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
### Updated Daily - Last Updated: July 16 (2pm ET):
<p align="center">
  Current Total: <b>137,404</b> deaths | Projected Total: <b>225,800 deaths by Nov 1, 2020</b> (Range: 181-300k) | 206,200 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.3%</b> | Total Infected: <b>7.5%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 16, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 19, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |        Aug 30, 2020 |
|              200,000 |         Oct 6, 2020 |

<br>

|   US deaths surpass: |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |        56% |         99% |        99% |        >99% |       >99% |        >99% |       >99% |
|              175,000 |        <1% |          5% |        56% |         83% |        95% |         99% |        99% |
|              200,000 |        <1% |         <1% |         7% |         25% |        45% |         57% |        71% |
|              225,000 |        <1% |         <1% |        <1% |          6% |        15% |         24% |        34% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         5% |         10% |        15% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          4% |         7% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |

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
|             *[United States](/us)* |          137,404 |                   225,816 |                     681 |                     88,412 |                                       64% |                               181,478 |                                299,353 |
|                 [New York](/us-ny) |           32,427 |                    33,830 |                   1,739 |                      1,403 |                                        4% |                                32,482 |                                 38,876 |
|               [California](/us-ca) |            7,375 |                    19,425 |                     492 |                     12,050 |                                      163% |                                 9,389 |                                 35,663 |
|                  [Florida](/us-fl) |            4,521 |                    17,447 |                     812 |                     12,926 |                                      286% |                                 8,651 |                                 30,859 |
|               [New Jersey](/us-nj) |           15,634 |                    16,924 |                   1,905 |                      1,290 |                                        8% |                                15,695 |                                 19,158 |
|                    [Texas](/us-tx) |            3,498 |                    14,669 |                     506 |                     11,171 |                                      319% |                                 9,297 |                                 28,052 |
|            [Massachusetts](/us-ma) |            8,368 |                     9,127 |                   1,313 |                        759 |                                        9% |                                 8,498 |                                 10,654 |
|             [Pennsylvania](/us-pa) |            6,957 |                     9,039 |                     706 |                      2,082 |                                       30% |                                 7,148 |                                 13,974 |
|                 [Illinois](/us-il) |            7,427 |                     8,648 |                     682 |                      1,221 |                                       16% |                                 7,611 |                                 10,114 |
|                 [Michigan](/us-mi) |            6,330 |                     7,928 |                     794 |                      1,598 |                                       25% |                                 6,434 |                                 12,396 |
|                  [Georgia](/us-ga) |            3,091 |                     7,323 |                     690 |                      4,232 |                                      137% |                                 3,951 |                                 14,351 |
|                  [Arizona](/us-az) |            2,434 |                     6,552 |                     900 |                      4,118 |                                      169% |                                 4,813 |                                 10,272 |
|                     [Ohio](/us-oh) |            3,075 |                     5,993 |                     513 |                      2,918 |                                       95% |                                 3,299 |                                 13,594 |
|                [Louisiana](/us-la) |            3,461 |                     5,852 |                   1,259 |                      2,391 |                                       69% |                                 3,752 |                                  8,283 |
|                 [Virginia](/us-va) |            1,992 |                     4,614 |                     541 |                      2,622 |                                      132% |                                 2,174 |                                  9,660 |
|              [Connecticut](/us-ct) |            4,380 |                     4,520 |                   1,268 |                        140 |                                        3% |                                 4,400 |                                  4,689 |
|                  [Alabama](/us-al) |            1,211 |                     4,499 |                     918 |                      3,288 |                                      272% |                                 2,753 |                                  7,013 |
|                 [Maryland](/us-md) |            3,341 |                     4,128 |                     683 |                        787 |                                       24% |                                 3,487 |                                  5,428 |
|                  [Indiana](/us-in) |            2,785 |                     4,053 |                     602 |                      1,268 |                                       46% |                                 2,891 |                                  7,662 |
|           [North Carolina](/us-nc) |            1,589 |                     3,883 |                     370 |                      2,294 |                                      144% |                                 1,888 |                                  9,246 |
|           [South Carolina](/us-sc) |              998 |                     3,684 |                     716 |                      2,686 |                                      269% |                                 2,205 |                                  6,334 |
|                [Tennessee](/us-tn) |              783 |                     3,169 |                     464 |                      2,386 |                                      305% |                                 1,791 |                                  6,193 |
|              [Mississippi](/us-ms) |            1,290 |                     2,943 |                     989 |                      1,653 |                                      128% |                                 1,744 |                                  4,652 |
|                 [Colorado](/us-co) |            1,744 |                     2,526 |                     439 |                        782 |                                       45% |                                 1,801 |                                  4,961 |
|                 [Missouri](/us-mo) |            1,119 |                     2,274 |                     371 |                      1,155 |                                      103% |                                 1,250 |                                  5,119 |
|               [Washington](/us-wa) |            1,421 |                     2,243 |                     295 |                        822 |                                       58% |                                 1,500 |                                  4,509 |
|                   [Nevada](/us-nv) |              618 |                     2,234 |                     725 |                      1,616 |                                      261% |                                 1,247 |                                  3,798 |
|                [Minnesota](/us-mn) |            1,558 |                     2,209 |                     392 |                        651 |                                       42% |                                 1,665 |                                  3,428 |
|                 [Kentucky](/us-ky) |              645 |                     1,911 |                     428 |                      1,266 |                                      196% |                                   874 |                                  4,013 |
|                [Wisconsin](/us-wi) |              827 |                     1,570 |                     270 |                        743 |                                       90% |                                   953 |                                  4,030 |
|                     [Iowa](/us-ia) |              777 |                     1,331 |                     422 |                        554 |                                       71% |                                   817 |                                  2,851 |
|             [Rhode Island](/us-ri) |              987 |                     1,135 |                   1,071 |                        148 |                                       15% |                                 1,009 |                                  1,304 |
|                     [Utah](/us-ut) |              233 |                     1,125 |                     351 |                        892 |                                      383% |                                   411 |                                  2,478 |
|                   [Oregon](/us-or) |              247 |                     1,082 |                     257 |                        835 |                                      338% |                                   383 |                                  2,594 |
|               [New Mexico](/us-nm) |              557 |                     1,069 |                     510 |                        512 |                                       92% |                                   616 |                                  2,161 |
|                 [Arkansas](/us-ar) |              335 |                     1,045 |                     346 |                        710 |                                      212% |                                   652 |                                  1,968 |
|                 [Oklahoma](/us-ok) |              432 |                       834 |                     211 |                        402 |                                       93% |                                   505 |                                  1,676 |
|                   [Kansas](/us-ks) |              304 |                       727 |                     250 |                        423 |                                      139% |                                   342 |                                  1,777 |
|     [District of Columbia](/us-dc) |              571 |                       698 |                     989 |                        127 |                                       22% |                                   588 |                                  1,033 |
|                 [Delaware](/us-de) |              521 |                       673 |                     691 |                        152 |                                       29% |                                   538 |                                  1,016 |
|                    [Idaho](/us-id) |              110 |                       488 |                     273 |                        378 |                                      344% |                                   198 |                                  1,118 |
|                 [Nebraska](/us-ne) |              291 |                       457 |                     236 |                        166 |                                       57% |                                   355 |                                    638 |
|            [New Hampshire](/us-nh) |              394 |                       452 |                     332 |                         58 |                                       15% |                                   400 |                                    518 |
|              [Puerto Rico](/us-pr) |              171 |                       302 |                      95 |                        131 |                                       77% |                                   183 |                                    715 |
|                  [Montana](/us-mt) |               34 |                       216 |                     202 |                        182 |                                      535% |                                    94 |                                    485 |
|             [South Dakota](/us-sd) |              111 |                       207 |                     234 |                         96 |                                       86% |                                   137 |                                    317 |
|                    [Maine](/us-me) |              114 |                       191 |                     142 |                         77 |                                       68% |                                   124 |                                    424 |
|             [North Dakota](/us-nd) |               88 |                       169 |                     222 |                         81 |                                       92% |                                   100 |                                    357 |
|            [West Virginia](/us-wv) |               98 |                       156 |                      87 |                         58 |                                       59% |                                   106 |                                    302 |
|                  [Vermont](/us-vt) |               56 |                        79 |                     127 |                         23 |                                       41% |                                    58 |                                    156 |
|                   [Hawaii](/us-hi) |               22 |                        53 |                      37 |                         31 |                                      141% |                                    24 |                                    129 |
|                   [Alaska](/us-ak) |               17 |                        43 |                      59 |                         26 |                                      153% |                                    18 |                                    112 |
|                  [Wyoming](/us-wy) |               22 |                        41 |                      71 |                         19 |                                       86% |                                    28 |                                     70 |
|           [Virgin Islands](/us-vi) |                6 |                        14 |                     133 |                          8 |                                      133% |                                     6 |                                     33 |
|                     [Guam](/us-gu) |                5 |                        11 |                      66 |                          6 |                                      120% |                                     5 |                                     37 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          185,136 |                   202,870 |                     342 |                     17,734 |                                       10% |                               189,064 |                                228,469 |
| [United Kingdom](/united-kingdom) |           45,138 |                    49,338 |                     731 |                      4,200 |                                        9% |                                45,673 |                                 53,628 |
|                   [Italy](/italy) |           34,997 |                    35,614 |                     590 |                        617 |                                        2% |                                35,060 |                                 36,195 |
|                 [France](/france) |           30,123 |                    30,817 |                     460 |                        694 |                                        2% |                                30,143 |                                 34,038 |
|                   [Spain](/spain) |           28,413 |                    28,781 |                     613 |                        368 |                                        1% |                                28,444 |                                 29,727 |
|               [Belgium](/belgium) |            9,788 |                     9,972 |                     870 |                        184 |                                        2% |                                 9,805 |                                 10,483 |
|               [Germany](/germany) |            9,080 |                     9,433 |                     114 |                        353 |                                        4% |                                 9,111 |                                 10,230 |
|       [Netherlands](/netherlands) |            6,155 |                     6,262 |                     362 |                        107 |                                        2% |                                 6,174 |                                  6,382 |
|                 [Sweden](/sweden) |            5,572 |                     6,004 |                     587 |                        432 |                                        8% |                                 5,711 |                                  6,193 |
|               [Romania](/romania) |            1,952 |                     4,098 |                     211 |                      2,146 |                                      110% |                                 2,760 |                                  5,820 |
|                 [Serbia](/serbia) |              429 |                     3,394 |                     487 |                      2,965 |                                      691% |                                   958 |                                  8,262 |
|               [Ukraine](/ukraine) |            1,444 |                     2,816 |                      64 |                      1,372 |                                       95% |                                 1,996 |                                  4,226 |
|                 [Poland](/poland) |            1,594 |                     2,420 |                      64 |                        826 |                                       52% |                                 1,847 |                                  3,706 |
|             [Portugal](/portugal) |            1,676 |                     2,286 |                     222 |                        610 |                                       36% |                                 1,767 |                                  3,314 |
|       [Switzerland](/switzerland) |            1,968 |                     2,069 |                     241 |                        101 |                                        5% |                                 1,981 |                                  2,473 |
|               [Ireland](/ireland) |            1,748 |                     1,838 |                     375 |                         90 |                                        5% |                                 1,755 |                                  2,266 |
|               [Moldova](/moldova) |              659 |                     1,177 |                     291 |                        518 |                                       79% |                                   969 |                                  1,562 |
|               [Belarus](/belarus) |              480 |                     1,130 |                     120 |                        650 |                                      135% |                                   633 |                                  2,335 |
|             [Bulgaria](/bulgaria) |              289 |                       987 |                     141 |                        698 |                                      242% |                                   522 |                                  1,641 |
|               [Austria](/austria) |              710 |                       842 |                      95 |                        132 |                                       19% |                                   725 |                                  1,089 |
|               [Hungary](/hungary) |              595 |                       706 |                      72 |                        111 |                                       19% |                                   608 |                                  1,035 |
|               [Denmark](/denmark) |              610 |                       656 |                     113 |                         46 |                                        8% |                                   624 |                                    741 |
|               [Czechia](/czechia) |              355 |                       498 |                      47 |                        143 |                                       40% |                                   364 |                                    740 |
|               [Finland](/finland) |              328 |                       366 |                      66 |                         38 |                                       12% |                                   332 |                                    469 |
|                 [Norway](/norway) |              253 |                       275 |                      51 |                         22 |                                        9% |                                   259 |                                    318 |
|               [Croatia](/croatia) |              120 |                       260 |                      64 |                        140 |                                      117% |                                   144 |                                    391 |
|                 [Greece](/greece) |              193 |                       224 |                      21 |                         31 |                                       16% |                                   204 |                                    284 |
|         [Luxembourg](/luxembourg) |              111 |                       148 |                     241 |                         37 |                                       33% |                                   118 |                                    190 |
|             [Slovenia](/slovenia) |              111 |                       122 |                      59 |                         11 |                                       10% |                                   113 |                                    152 |
|           [Lithuania](/lithuania) |               79 |                       110 |                      39 |                         31 |                                       39% |                                    86 |                                    180 |
|               [Estonia](/estonia) |               69 |                        86 |                      65 |                         17 |                                       25% |                                    75 |                                    114 |
|             [Slovakia](/slovakia) |               28 |                        43 |                       8 |                         15 |                                       54% |                                    28 |                                     85 |
|                 [Latvia](/latvia) |               31 |                        42 |                      22 |                         11 |                                       35% |                                    33 |                                     94 |
|                 [Cyprus](/cyprus) |               19 |                        30 |                      34 |                         11 |                                       58% |                                    21 |                                     65 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     27 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          247,632 |                   578,981 |                     112 |                    331,349 |                                      134% |                               382,948 |                                943,965 |
|                             [Brazil](/brazil) |           75,366 |                   148,750 |                     705 |                     73,384 |                                       97% |                               115,218 |                                221,781 |
|                               [India](/india) |           24,914 |                   104,724 |                      77 |                     79,810 |                                      320% |                                51,288 |                                223,065 |
|                             [Mexico](/mexico) |           36,906 |                    81,732 |                     641 |                     44,826 |                                      121% |                                54,316 |                                108,658 |
|                                 [Iran](/iran) |           13,410 |                    30,823 |                     372 |                     17,413 |                                      130% |                                22,026 |                                 45,579 |
|                                 [Peru](/peru) |           12,417 |                    22,947 |                     706 |                     10,530 |                                       85% |                                18,017 |                                 31,266 |
|                             [Russia](/russia) |           11,753 |                    22,359 |                     153 |                     10,606 |                                       90% |                                14,606 |                                 38,403 |
|                 [South Africa](/south-africa) |            4,453 |                    20,342 |                     347 |                     15,889 |                                      357% |                                11,863 |                                 32,122 |
|                         [Colombia](/colombia) |            5,969 |                    20,131 |                     400 |                     14,162 |                                      237% |                                14,460 |                                 27,413 |
|                       [Indonesia](/indonesia) |            3,797 |                    13,734 |                      51 |                      9,937 |                                      262% |                                 6,234 |                                 26,796 |
|                               [Chile](/chile) |            7,186 |                    11,019 |                     581 |                      3,833 |                                       53% |                                 8,106 |                                 13,575 |
|                         [Pakistan](/pakistan) |            5,426 |                    10,683 |                      49 |                      5,257 |                                       97% |                                 7,060 |                                 17,029 |
|                               [Egypt](/egypt) |            4,067 |                     9,970 |                      99 |                      5,903 |                                      145% |                                 5,977 |                                 17,224 |
|                             [Canada](/canada) |            8,857 |                     9,820 |                     262 |                        963 |                                       11% |                                 8,961 |                                 11,133 |
|                       [Argentina](/argentina) |            2,050 |                     8,826 |                     197 |                      6,776 |                                      331% |                                 3,967 |                                 16,905 |
|                           [Ecuador](/ecuador) |            5,158 |                     8,055 |                     464 |                      2,897 |                                       56% |                                 5,542 |                                 12,911 |
|                             [Turkey](/turkey) |            5,419 |                     6,865 |                      82 |                      1,446 |                                       27% |                                 5,510 |                                 11,522 |
|                           [Bolivia](/bolivia) |            1,942 |                     6,199 |                     538 |                      4,257 |                                      219% |                                 3,576 |                                 10,979 |
|                     [Bangladesh](/bangladesh) |            2,457 |                     6,059 |                      37 |                      3,602 |                                      147% |                                 3,762 |                                 10,535 |
|                 [Saudi Arabia](/saudi-arabia) |            2,325 |                     5,901 |                     172 |                      3,576 |                                      154% |                                 3,912 |                                  8,526 |
|                               [China](/china) |            4,644 |                     4,647 |                       3 |                          3 |                                        0% |                                 4,644 |                                  4,672 |
|                   [Philippines](/philippines) |            1,614 |                     3,925 |                      36 |                      2,311 |                                      143% |                                 2,092 |                                  8,406 |
|     [Dominican Republic](/dominican-republic) |              929 |                     3,895 |                     363 |                      2,966 |                                      319% |                                 1,454 |                                  8,469 |
|                         [Honduras](/honduras) |              825 |                     3,595 |                     369 |                      2,770 |                                      336% |                                 2,343 |                                  6,436 |
|                             [Panama](/panama) |              982 |                     3,241 |                     763 |                      2,259 |                                      230% |                                 2,344 |                                  5,259 |
|                           [Algeria](/algeria) |            1,040 |                     3,005 |                      70 |                      1,965 |                                      189% |                                 1,430 |                                  8,176 |
|                           [Nigeria](/nigeria) |              760 |                     1,941 |                      10 |                      1,181 |                                      155% |                                   999 |                                  4,129 |
|                             [Israel](/israel) |              376 |                     1,677 |                     197 |                      1,301 |                                      346% |                                   541 |                                  5,058 |
|                               [Japan](/japan) |              984 |                     1,616 |                      13 |                        632 |                                       64% |                                   992 |                                  2,960 |
|                             [Kuwait](/kuwait) |              399 |                       661 |                     157 |                        262 |                                       66% |                                   434 |                                  1,230 |
|                           [Morocco](/morocco) |              259 |                       480 |                      13 |                        221 |                                       85% |                                   294 |                                    880 |
| [United Arab Emirates](/united-arab-emirates) |              335 |                       474 |                      49 |                        139 |                                       41% |                                   350 |                                    876 |
|                   [South Korea](/south-korea) |              291 |                       341 |                       7 |                         50 |                                       17% |                                   293 |                                    493 |
|                       [Australia](/australia) |              113 |                       276 |                      11 |                        163 |                                      144% |                                   113 |                                  1,119 |
|                         [Malaysia](/malaysia) |              122 |                       151 |                       5 |                         29 |                                       24% |                                   133 |                                    181 |
|                                 [Cuba](/cuba) |               87 |                       117 |                      10 |                         30 |                                       34% |                                    91 |                                    199 |
