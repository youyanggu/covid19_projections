We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 15:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1305937870075703296).
* **September 14:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 19 (12pm ET):
<p align="center">
  Current Total: <b>198,567</b> deaths | Projected Total: <b>224,000 deaths by Nov 1, 2020</b> (Range: 213-240k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.4%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 19, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |       >99% |        >99% |       >99% |
|              225,000 |        <1% |          1% |        32% |
|              250,000 |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |

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

|                                    |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          198,567 |                   223,976 |                     675 |                     25,409 |                       77 |                                       13% |                               213,689 |                                239,052 |
|                 [New York](/us-ny) |           33,085 |                    33,455 |                   1,720 |                        370 |                       19 |                                        1% |                                33,099 |                                 35,185 |
|                    [Texas](/us-tx) |           14,951 |                    18,086 |                     624 |                      3,135 |                      108 |                                       21% |                                16,464 |                                 20,453 |
|               [California](/us-ca) |           14,893 |                    17,959 |                     455 |                      3,066 |                       78 |                                       21% |                                15,965 |                                 21,127 |
|               [New Jersey](/us-nj) |           16,061 |                    16,238 |                   1,828 |                        177 |                       20 |                                        1% |                                16,072 |                                 16,824 |
|                  [Florida](/us-fl) |           13,225 |                    16,208 |                     755 |                      2,983 |                      139 |                                       23% |                                14,605 |                                 18,460 |
|            [Massachusetts](/us-ma) |            9,269 |                     9,627 |                   1,385 |                        358 |                       52 |                                        4% |                                 9,292 |                                 10,294 |
|                 [Illinois](/us-il) |            8,647 |                     9,405 |                     742 |                        758 |                       60 |                                        9% |                                 8,732 |                                 10,374 |
|             [Pennsylvania](/us-pa) |            7,921 |                     8,411 |                     657 |                        490 |                       38 |                                        6% |                                 7,946 |                                  9,357 |
|                  [Georgia](/us-ga) |            6,536 |                     7,826 |                     737 |                      1,290 |                      121 |                                       20% |                                 7,052 |                                  9,090 |
|                 [Michigan](/us-mi) |            6,954 |                     7,344 |                     735 |                        390 |                       39 |                                        6% |                                 7,003 |                                  7,944 |
|                [Louisiana](/us-la) |            5,342 |                     5,978 |                   1,286 |                        636 |                      137 |                                       12% |                                 5,603 |                                  6,596 |
|                  [Arizona](/us-az) |            5,451 |                     5,957 |                     818 |                        506 |                       70 |                                        9% |                                 5,575 |                                  6,663 |
|                     [Ohio](/us-oh) |            4,608 |                     5,531 |                     473 |                        923 |                       79 |                                       20% |                                 4,849 |                                  6,669 |
|              [Connecticut](/us-ct) |            4,492 |                     4,568 |                   1,281 |                         76 |                       21 |                                        2% |                                 4,502 |                                  4,780 |
|           [North Carolina](/us-nc) |            3,207 |                     4,133 |                     394 |                        926 |                       88 |                                       29% |                                 3,639 |                                  4,928 |
|                 [Maryland](/us-md) |            3,869 |                     4,112 |                     680 |                        243 |                       40 |                                        6% |                                 3,888 |                                  4,548 |
|           [South Carolina](/us-sc) |            3,177 |                     3,944 |                     766 |                        767 |                      149 |                                       24% |                                 3,539 |                                  4,583 |
|                  [Indiana](/us-in) |            3,495 |                     3,906 |                     580 |                        411 |                       61 |                                       12% |                                 3,527 |                                  4,617 |
|                 [Virginia](/us-va) |            2,947 |                     3,684 |                     432 |                        737 |                       86 |                                       25% |                                 3,155 |                                  4,491 |
|              [Mississippi](/us-ms) |            2,792 |                     3,259 |                   1,095 |                        467 |                      157 |                                       17% |                                 2,954 |                                  3,819 |
|                [Tennessee](/us-tn) |            2,196 |                     2,966 |                     434 |                        770 |                      113 |                                       35% |                                 2,587 |                                  3,537 |
|                  [Alabama](/us-al) |            2,428 |                     2,867 |                     585 |                        439 |                       90 |                                       18% |                                 2,608 |                                  3,276 |
|               [Washington](/us-wa) |            2,037 |                     2,356 |                     309 |                        319 |                       42 |                                       16% |                                 2,089 |                                  2,849 |
|                 [Missouri](/us-mo) |            1,810 |                     2,338 |                     381 |                        528 |                       86 |                                       29% |                                 2,034 |                                  2,814 |
|                [Minnesota](/us-mn) |            2,002 |                     2,307 |                     409 |                        305 |                       54 |                                       15% |                                 2,056 |                                  2,713 |
|                 [Colorado](/us-co) |            2,009 |                     2,183 |                     379 |                        174 |                       30 |                                        9% |                                 2,020 |                                  2,531 |
|                   [Nevada](/us-nv) |            1,524 |                     1,831 |                     595 |                        307 |                      100 |                                       20% |                                 1,635 |                                  2,162 |
|                [Wisconsin](/us-wi) |            1,238 |                     1,616 |                     278 |                        378 |                       65 |                                       31% |                                 1,377 |                                  2,035 |
|                     [Iowa](/us-ia) |            1,264 |                     1,604 |                     508 |                        340 |                      108 |                                       27% |                                 1,389 |                                  1,940 |
|                 [Arkansas](/us-ar) |            1,173 |                     1,555 |                     515 |                        382 |                      127 |                                       33% |                                 1,370 |                                  1,821 |
|                 [Kentucky](/us-ky) |            1,101 |                     1,449 |                     324 |                        348 |                       78 |                                       32% |                                 1,244 |                                  1,756 |
|                 [Oklahoma](/us-ok) |              939 |                     1,245 |                     315 |                        306 |                       77 |                                       33% |                                 1,084 |                                  1,516 |
|             [Rhode Island](/us-ri) |            1,088 |                     1,145 |                   1,080 |                         57 |                       53 |                                        5% |                                 1,095 |                                  1,268 |
|               [New Mexico](/us-nm) |              841 |                       982 |                     468 |                        141 |                       67 |                                       17% |                                   882 |                                  1,148 |
|              [Puerto Rico](/us-pr) |              599 |                       969 |                     303 |                        370 |                      116 |                                       62% |                                   788 |                                  1,242 |
|                   [Kansas](/us-ks) |              594 |                       831 |                     285 |                        237 |                       81 |                                       40% |                                   697 |                                  1,043 |
|                   [Oregon](/us-or) |              521 |                       683 |                     162 |                        162 |                       38 |                                       31% |                                   584 |                                    853 |
|                 [Delaware](/us-de) |              620 |                       655 |                     672 |                         35 |                       36 |                                        6% |                                   624 |                                    721 |
|     [District of Columbia](/us-dc) |              619 |                       639 |                     906 |                         20 |                       29 |                                        3% |                                   622 |                                    677 |
|                    [Idaho](/us-id) |              438 |                       584 |                     327 |                        146 |                       82 |                                       33% |                                   513 |                                    685 |
|                 [Nebraska](/us-ne) |              442 |                       544 |                     281 |                        102 |                       52 |                                       23% |                                   475 |                                    658 |
|                     [Utah](/us-ut) |              437 |                       536 |                     167 |                         99 |                       31 |                                       23% |                                   477 |                                    614 |
|            [West Virginia](/us-wv) |              300 |                       478 |                     267 |                        178 |                       99 |                                       59% |                                   385 |                                    634 |
|            [New Hampshire](/us-nh) |              438 |                       463 |                     340 |                         25 |                       18 |                                        6% |                                   440 |                                    530 |
|             [South Dakota](/us-sd) |              195 |                       282 |                     318 |                         87 |                       98 |                                       44% |                                   208 |                                    422 |
|             [North Dakota](/us-nd) |              184 |                       280 |                     368 |                         96 |                      126 |                                       52% |                                   226 |                                    376 |
|                   [Hawaii](/us-hi) |              120 |                       256 |                     181 |                        136 |                       96 |                                      113% |                                   177 |                                    410 |
|                  [Montana](/us-mt) |              146 |                       243 |                     228 |                         97 |                       91 |                                       67% |                                   196 |                                    324 |
|                    [Maine](/us-me) |              138 |                       155 |                     116 |                         17 |                       13 |                                       13% |                                   141 |                                    183 |
|                     [Guam](/us-gu) |               31 |                        76 |                     460 |                         45 |                      273 |                                      146% |                                    53 |                                    115 |
|                  [Wyoming](/us-wy) |               49 |                        68 |                     117 |                         19 |                       32 |                                       38% |                                    57 |                                     86 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     105 |                          8 |                       12 |                                       13% |                                    59 |                                     80 |
|                   [Alaska](/us-ak) |               45 |                        66 |                      90 |                         21 |                       28 |                                       46% |                                    55 |                                     83 |
|           [Virgin Islands](/us-vi) |               19 |                        28 |                     266 |                          9 |                       85 |                                       47% |                                    23 |                                     37 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      48 |                          1 |                       11 |                                       31% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          194,372 |                   218,667 |                     369 |                     24,295 |                       41 |                                       12% |                               199,106 |                                279,374 |
| [United Kingdom](/united-kingdom) |           41,821 |                    43,887 |                     650 |                      2,066 |                       31 |                                        5% |                                41,863 |                                 52,543 |
|                 [France](/france) |           31,257 |                    37,652 |                     562 |                      6,395 |                       95 |                                       20% |                                32,311 |                                 56,117 |
|                   [Spain](/spain) |           30,495 |                    37,100 |                     790 |                      6,605 |                      141 |                                       22% |                                31,304 |                                 55,125 |
|                   [Italy](/italy) |           35,668 |                    36,627 |                     607 |                        959 |                       16 |                                        3% |                                35,684 |                                 40,639 |
|               [Belgium](/belgium) |            9,937 |                    10,106 |                     882 |                        169 |                       15 |                                        2% |                                 9,951 |                                 10,698 |
|               [Germany](/germany) |            9,386 |                     9,696 |                     117 |                        310 |                        4 |                                        3% |                                 9,399 |                                 10,909 |
|       [Netherlands](/netherlands) |            6,318 |                     6,545 |                     379 |                        227 |                       13 |                                        4% |                                 6,330 |                                  7,297 |
|               [Ukraine](/ukraine) |            3,535 |                     6,431 |                     146 |                      2,896 |                       66 |                                       82% |                                 4,712 |                                  9,037 |
|               [Romania](/romania) |            4,360 |                     6,028 |                     311 |                      1,668 |                       86 |                                       38% |                                 5,052 |                                  7,692 |
|                 [Sweden](/sweden) |            5,865 |                     5,945 |                     581 |                         80 |                        8 |                                        1% |                                 5,872 |                                  6,231 |
|                 [Poland](/poland) |            2,270 |                     2,718 |                      72 |                        448 |                       12 |                                       20% |                                 2,394 |                                  3,436 |
|       [Switzerland](/switzerland) |            2,045 |                     2,153 |                     251 |                        108 |                       13 |                                        5% |                                 2,058 |                                  2,419 |
|             [Portugal](/portugal) |            1,894 |                     2,077 |                     202 |                        183 |                       18 |                                       10% |                                 1,903 |                                  2,532 |
|               [Ireland](/ireland) |            1,792 |                     1,831 |                     373 |                         39 |                        8 |                                        2% |                                 1,797 |                                  1,986 |
|               [Moldova](/moldova) |            1,186 |                     1,610 |                     398 |                        424 |                      105 |                                       36% |                                 1,353 |                                  2,025 |
|             [Bulgaria](/bulgaria) |              753 |                     1,020 |                     146 |                        267 |                       38 |                                       36% |                                   881 |                                  1,236 |
|               [Belarus](/belarus) |              773 |                     1,013 |                     107 |                        240 |                       25 |                                       31% |                                   853 |                                  1,347 |
|               [Hungary](/hungary) |              669 |                       856 |                      88 |                        187 |                       19 |                                       28% |                                   705 |                                  1,175 |
|               [Austria](/austria) |              763 |                       843 |                      95 |                         80 |                        9 |                                       11% |                                   776 |                                  1,031 |
|                 [Serbia](/serbia) |              739 |                       813 |                     117 |                         74 |                       11 |                                       10% |                                   758 |                                    926 |
|               [Czechia](/czechia) |              495 |                       749 |                      70 |                        254 |                       24 |                                       51% |                                   574 |                                  1,085 |
|               [Denmark](/denmark) |              635 |                       677 |                     117 |                         42 |                        7 |                                        7% |                                   643 |                                    785 |
|                 [Greece](/greece) |              327 |                       543 |                      51 |                        216 |                       20 |                                       66% |                                   413 |                                    798 |
|               [Croatia](/croatia) |              244 |                       467 |                     115 |                        223 |                       55 |                                       91% |                                   343 |                                    771 |
|               [Finland](/finland) |              339 |                       356 |                      65 |                         17 |                        3 |                                        5% |                                   342 |                                    414 |
|                 [Norway](/norway) |              267 |                       285 |                      53 |                         18 |                        3 |                                        7% |                                   270 |                                    324 |
|             [Slovenia](/slovenia) |              140 |                       164 |                      79 |                         24 |                       11 |                                       17% |                                   144 |                                    211 |
|         [Luxembourg](/luxembourg) |              124 |                       139 |                     226 |                         15 |                       24 |                                       12% |                                   128 |                                    162 |
|           [Lithuania](/lithuania) |               87 |                        95 |                      34 |                          8 |                        3 |                                       10% |                                    89 |                                    111 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        7% |                                    66 |                                     75 |
|             [Slovakia](/slovakia) |               39 |                        53 |                      10 |                         14 |                        3 |                                       36% |                                    43 |                                     77 |
|                 [Latvia](/latvia) |               36 |                        43 |                      22 |                          7 |                        4 |                                       20% |                                    37 |                                     53 |
|                   [Malta](/malta) |               17 |                        37 |                      74 |                         20 |                       40 |                                      115% |                                    24 |                                     60 |
|                 [Cyprus](/cyprus) |               22 |                        27 |                      31 |                          5 |                        6 |                                       23% |                                    24 |                                     33 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       13% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          523,218 |                   668,181 |                     129 |                    144,963 |                       28 |                                       28% |                               585,343 |                                791,103 |
|                             [Brazil](/brazil) |          135,793 |                   161,479 |                     765 |                     25,686 |                      122 |                                       19% |                               149,767 |                                181,037 |
|                               [India](/india) |           84,372 |                   135,693 |                      99 |                     51,321 |                       38 |                                       61% |                               104,869 |                                167,970 |
|                             [Mexico](/mexico) |           72,803 |                    89,063 |                     698 |                     16,260 |                      127 |                                       22% |                                81,989 |                                 98,635 |
|                                 [Peru](/peru) |           31,146 |                    34,138 |                   1,050 |                      2,992 |                       92 |                                       10% |                                31,834 |                                 38,174 |
|                         [Colombia](/colombia) |           23,665 |                    29,348 |                     583 |                      5,683 |                      113 |                                       24% |                                26,402 |                                 34,534 |
|                                 [Iran](/iran) |           23,952 |                    28,455 |                     343 |                      4,503 |                       54 |                                       19% |                                25,770 |                                 33,276 |
|                             [Russia](/russia) |           19,128 |                    24,203 |                     166 |                      5,075 |                       35 |                                       27% |                                20,237 |                                 33,156 |
|                       [Argentina](/argentina) |           12,656 |                    20,871 |                     466 |                      8,215 |                      183 |                                       65% |                                16,749 |                                 25,890 |
|                 [South Africa](/south-africa) |           15,857 |                    18,379 |                     314 |                      2,522 |                       43 |                                       16% |                                16,907 |                                 20,999 |
|                               [Chile](/chile) |           12,199 |                    14,574 |                     769 |                      2,375 |                      125 |                                       19% |                                12,489 |                                 19,562 |
|                       [Indonesia](/indonesia) |            9,336 |                    13,495 |                      50 |                      4,159 |                       15 |                                       45% |                                11,178 |                                 18,299 |
|                           [Ecuador](/ecuador) |           11,044 |                    11,876 |                     684 |                        832 |                       48 |                                        8% |                                11,110 |                                 13,719 |
|                             [Canada](/canada) |            9,256 |                     9,524 |                     255 |                        268 |                        7 |                                        3% |                                 9,277 |                                 10,323 |
|                           [Bolivia](/bolivia) |            7,550 |                     9,211 |                     800 |                      1,661 |                      144 |                                       22% |                                 8,280 |                                 10,802 |
|                             [Turkey](/turkey) |            7,377 |                     9,101 |                     109 |                      1,724 |                       21 |                                       23% |                                 7,551 |                                 12,228 |
|                   [Philippines](/philippines) |            4,830 |                     7,889 |                      73 |                      3,059 |                       28 |                                       63% |                                 6,094 |                                 10,559 |
|                         [Pakistan](/pakistan) |            6,415 |                     6,587 |                      30 |                        172 |                        1 |                                        3% |                                 6,425 |                                  6,760 |
|                               [Egypt](/egypt) |            5,733 |                     6,520 |                      65 |                        787 |                        8 |                                       14% |                                 5,829 |                                  8,243 |
|                     [Bangladesh](/bangladesh) |            4,881 |                     6,278 |                      39 |                      1,397 |                        9 |                                       29% |                                 5,326 |                                  7,958 |
|                 [Saudi Arabia](/saudi-arabia) |            4,430 |                     5,483 |                     160 |                      1,053 |                       31 |                                       24% |                                 4,743 |                                  6,610 |
|                               [China](/china) |            4,737 |                     4,794 |                       3 |                         57 |                        0 |                                        1% |                                 4,737 |                                  5,254 |
|                           [Morocco](/morocco) |            1,755 |                     3,387 |                      93 |                      1,632 |                       45 |                                       93% |                                 2,382 |                                  4,846 |
|                         [Honduras](/honduras) |            2,146 |                     2,696 |                     277 |                        550 |                       56 |                                       26% |                                 2,320 |                                  3,294 |
|     [Dominican Republic](/dominican-republic) |            2,034 |                     2,693 |                     251 |                        659 |                       61 |                                       32% |                                 2,286 |                                  3,395 |
|                             [Panama](/panama) |            2,229 |                     2,586 |                     609 |                        357 |                       84 |                                       16% |                                 2,344 |                                  2,947 |
|                           [Algeria](/algeria) |            1,659 |                     1,935 |                      45 |                        276 |                        6 |                                       17% |                                 1,720 |                                  2,318 |
|                             [Israel](/israel) |            1,196 |                     1,889 |                     222 |                        693 |                       81 |                                       58% |                                 1,447 |                                  2,853 |
|                               [Japan](/japan) |            1,500 |                     1,851 |                      15 |                        351 |                        3 |                                       23% |                                 1,597 |                                  2,261 |
|                           [Nigeria](/nigeria) |            1,094 |                     1,234 |                       6 |                        140 |                        1 |                                       13% |                                 1,131 |                                  1,433 |
|                       [Australia](/australia) |              844 |                       995 |                      39 |                        151 |                        6 |                                       18% |                                   896 |                                  1,145 |
|                             [Kuwait](/kuwait) |              580 |                       697 |                     166 |                        117 |                       28 |                                       20% |                                   606 |                                    888 |
|                   [South Korea](/south-korea) |              378 |                       496 |                      10 |                        118 |                        2 |                                       31% |                                   390 |                                    729 |
| [United Arab Emirates](/united-arab-emirates) |              403 |                       475 |                      49 |                         72 |                        7 |                                       18% |                                   409 |                                    656 |
|                                 [Cuba](/cuba) |              111 |                       148 |                      13 |                         37 |                        3 |                                       33% |                                   121 |                                    203 |
|                         [Malaysia](/malaysia) |              129 |                       137 |                       4 |                          8 |                        0 |                                        6% |                                   131 |                                    147 |
