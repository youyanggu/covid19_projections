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

* **September 20:** View our [updated historical performance](/about/#historical-performance).
* **September 15:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1305937870075703296).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 22 (3am ET):
<p align="center">
  Current Total: <b>199,862</b> deaths | Projected Total: <b>223,000 deaths by Nov 1, 2020</b> (Range: 213-238k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.7%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 22, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |       >99% |        >99% |       >99% |
|              225,000 |        <1% |         <1% |        26% |
|              250,000 |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries).

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
|             *[United States](/us)* |          199,862 |                   222,951 |                     672 |                     23,089 |                       70 |                                       12% |                               213,442 |                                237,038 |
|                 [New York](/us-ny) |           33,092 |                    33,425 |                   1,718 |                        333 |                       17 |                                        1% |                                33,105 |                                 34,975 |
|                    [Texas](/us-tx) |           15,127 |                    17,948 |                     619 |                      2,821 |                       97 |                                       19% |                                16,464 |                                 20,153 |
|               [California](/us-ca) |           15,056 |                    17,841 |                     452 |                      2,785 |                       70 |                                       18% |                                15,994 |                                 20,841 |
|               [New Jersey](/us-nj) |           16,069 |                    16,229 |                   1,827 |                        160 |                       18 |                                        1% |                                16,078 |                                 16,757 |
|                  [Florida](/us-fl) |           13,317 |                    15,905 |                     741 |                      2,588 |                      120 |                                       19% |                                14,479 |                                 17,946 |
|            [Massachusetts](/us-ma) |            9,317 |                     9,657 |                   1,390 |                        340 |                       49 |                                        4% |                                 9,338 |                                 10,316 |
|                 [Illinois](/us-il) |            8,693 |                     9,383 |                     740 |                        690 |                       54 |                                        8% |                                 8,770 |                                 10,300 |
|             [Pennsylvania](/us-pa) |            7,985 |                     8,505 |                     664 |                        520 |                       41 |                                        7% |                                 8,013 |                                  9,488 |
|                  [Georgia](/us-ga) |            6,604 |                     7,762 |                     731 |                      1,158 |                      109 |                                       18% |                                 7,048 |                                  8,947 |
|                 [Michigan](/us-mi) |            6,981 |                     7,347 |                     736 |                        366 |                       37 |                                        5% |                                 7,025 |                                  7,912 |
|                [Louisiana](/us-la) |            5,377 |                     5,943 |                   1,278 |                        566 |                      122 |                                       11% |                                 5,602 |                                  6,518 |
|                  [Arizona](/us-az) |            5,478 |                     5,930 |                     815 |                        452 |                       62 |                                        8% |                                 5,581 |                                  6,583 |
|                     [Ohio](/us-oh) |            4,623 |                     5,451 |                     466 |                        828 |                       71 |                                       18% |                                 4,835 |                                  6,513 |
|              [Connecticut](/us-ct) |            4,495 |                     4,565 |                   1,281 |                         70 |                       20 |                                        2% |                                 4,504 |                                  4,762 |
|                 [Maryland](/us-md) |            3,883 |                     4,106 |                     679 |                        223 |                       37 |                                        6% |                                 3,900 |                                  4,511 |
|           [North Carolina](/us-nc) |            3,247 |                     4,094 |                     390 |                        847 |                       81 |                                       26% |                                 3,635 |                                  4,831 |
|           [South Carolina](/us-sc) |            3,212 |                     3,898 |                     757 |                        686 |                      133 |                                       21% |                                 3,524 |                                  4,491 |
|                  [Indiana](/us-in) |            3,512 |                     3,887 |                     577 |                        375 |                       56 |                                       11% |                                 3,541 |                                  4,544 |
|                 [Virginia](/us-va) |            3,019 |                     3,729 |                     437 |                        710 |                       83 |                                       24% |                                 3,219 |                                  4,500 |
|              [Mississippi](/us-ms) |            2,810 |                     3,224 |                   1,083 |                        414 |                      139 |                                       15% |                                 2,946 |                                  3,745 |
|                [Tennessee](/us-tn) |            2,233 |                     2,920 |                     427 |                        687 |                      101 |                                       31% |                                 2,571 |                                  3,453 |
|                  [Alabama](/us-al) |            2,439 |                     2,827 |                     577 |                        388 |                       79 |                                       16% |                                 2,593 |                                  3,207 |
|               [Washington](/us-wa) |            2,049 |                     2,342 |                     308 |                        293 |                       38 |                                       14% |                                 2,097 |                                  2,802 |
|                 [Missouri](/us-mo) |            1,838 |                     2,322 |                     378 |                        484 |                       79 |                                       26% |                                 2,037 |                                  2,739 |
|                [Minnesota](/us-mn) |            2,021 |                     2,304 |                     409 |                        283 |                       50 |                                       14% |                                 2,070 |                                  2,684 |
|                 [Colorado](/us-co) |            2,018 |                     2,196 |                     381 |                        178 |                       31 |                                        9% |                                 2,030 |                                  2,537 |
|                   [Nevada](/us-nv) |            1,531 |                     1,799 |                     584 |                        268 |                       87 |                                       18% |                                 1,623 |                                  2,101 |
|                [Wisconsin](/us-wi) |            1,244 |                     1,592 |                     273 |                        348 |                       60 |                                       28% |                                 1,371 |                                  1,980 |
|                     [Iowa](/us-ia) |            1,284 |                     1,585 |                     502 |                        301 |                       95 |                                       23% |                                 1,397 |                                  1,881 |
|                 [Arkansas](/us-ar) |            1,197 |                     1,541 |                     511 |                        344 |                      114 |                                       29% |                                 1,372 |                                  1,790 |
|                 [Kentucky](/us-ky) |            1,112 |                     1,430 |                     320 |                        318 |                       71 |                                       29% |                                 1,236 |                                  1,718 |
|                 [Oklahoma](/us-ok) |              948 |                     1,212 |                     306 |                        264 |                       67 |                                       28% |                                 1,074 |                                  1,441 |
|             [Rhode Island](/us-ri) |            1,097 |                     1,173 |                   1,107 |                         76 |                       71 |                                        7% |                                 1,104 |                                  1,331 |
|               [New Mexico](/us-nm) |              851 |                       984 |                     469 |                        133 |                       64 |                                       16% |                                   888 |                                  1,144 |
|              [Puerto Rico](/us-pr) |              609 |                       937 |                     293 |                        328 |                      103 |                                       54% |                                   773 |                                  1,205 |
|                   [Kansas](/us-ks) |              601 |                       826 |                     283 |                        225 |                       77 |                                       37% |                                   696 |                                  1,027 |
|                   [Oregon](/us-or) |              529 |                       683 |                     162 |                        154 |                       36 |                                       29% |                                   590 |                                    842 |
|                 [Delaware](/us-de) |              627 |                       661 |                     679 |                         34 |                       35 |                                        5% |                                   631 |                                    724 |
|     [District of Columbia](/us-dc) |              621 |                       640 |                     907 |                         19 |                       27 |                                        3% |                                   624 |                                    675 |
|                    [Idaho](/us-id) |              447 |                       579 |                     324 |                        132 |                       74 |                                       29% |                                   513 |                                    671 |
|                 [Nebraska](/us-ne) |              452 |                       549 |                     284 |                         97 |                       50 |                                       21% |                                   477 |                                    664 |
|                     [Utah](/us-ut) |              441 |                       533 |                     166 |                         92 |                       29 |                                       21% |                                   477 |                                    606 |
|            [West Virginia](/us-wv) |              315 |                       506 |                     283 |                        191 |                      107 |                                       61% |                                   410 |                                    662 |
|            [New Hampshire](/us-nh) |              438 |                       460 |                     339 |                         22 |                       17 |                                        5% |                                   440 |                                    523 |
|             [South Dakota](/us-sd) |              202 |                       291 |                     329 |                         89 |                      101 |                                       44% |                                   220 |                                    425 |
|             [North Dakota](/us-nd) |              193 |                       290 |                     380 |                         97 |                      127 |                                       50% |                                   237 |                                    376 |
|                  [Montana](/us-mt) |              160 |                       262 |                     245 |                        102 |                       95 |                                       64% |                                   215 |                                    344 |
|                   [Hawaii](/us-hi) |              120 |                       230 |                     162 |                        110 |                       77 |                                       91% |                                   166 |                                    359 |
|                    [Maine](/us-me) |              140 |                       157 |                     117 |                         17 |                       13 |                                       12% |                                   143 |                                    184 |
|                     [Guam](/us-gu) |               35 |                        73 |                     439 |                         38 |                      228 |                                      108% |                                    52 |                                    107 |
|                  [Wyoming](/us-wy) |               49 |                        65 |                     113 |                         16 |                       28 |                                       33% |                                    56 |                                     81 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     78 |
|                   [Alaska](/us-ak) |               45 |                        63 |                      86 |                         18 |                       24 |                                       39% |                                    53 |                                     77 |
|           [Virgin Islands](/us-vi) |               19 |                        27 |                     254 |                          8 |                       73 |                                       40% |                                    22 |                                     35 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       11 |                                       29% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          195,183 |                   217,363 |                     366 |                     22,180 |                       37 |                                       11% |                               199,420 |                                274,082 |
| [United Kingdom](/united-kingdom) |           41,877 |                    43,826 |                     649 |                      1,949 |                       29 |                                        5% |                                41,919 |                                 50,897 |
|                   [Spain](/spain) |           30,663 |                    37,969 |                     809 |                      7,306 |                      156 |                                       24% |                                32,025 |                                 54,807 |
|                   [Italy](/italy) |           35,724 |                    36,812 |                     610 |                      1,088 |                       18 |                                        3% |                                35,741 |                                 40,912 |
|                 [France](/france) |           31,346 |                    34,991 |                     522 |                      3,645 |                       54 |                                       12% |                                31,409 |                                 52,513 |
|               [Belgium](/belgium) |            9,950 |                    10,240 |                     894 |                        290 |                       25 |                                        3% |                                 9,981 |                                 11,080 |
|               [Germany](/germany) |            9,390 |                     9,667 |                     116 |                        277 |                        3 |                                        3% |                                 9,401 |                                 10,792 |
|       [Netherlands](/netherlands) |            6,327 |                     6,630 |                     384 |                        303 |                       18 |                                        5% |                                 6,340 |                                  7,454 |
|               [Ukraine](/ukraine) |            3,652 |                     6,000 |                     136 |                      2,348 |                       53 |                                       64% |                                 4,659 |                                  8,154 |
|                 [Sweden](/sweden) |            5,865 |                     5,957 |                     582 |                         92 |                        9 |                                        2% |                                 5,871 |                                  6,209 |
|               [Romania](/romania) |            4,458 |                     5,912 |                     305 |                      1,454 |                       75 |                                       33% |                                 5,067 |                                  7,278 |
|                 [Poland](/poland) |            2,298 |                     2,947 |                      78 |                        649 |                       17 |                                       28% |                                 2,477 |                                  3,905 |
|             [Portugal](/portugal) |            1,920 |                     2,229 |                     217 |                        309 |                       30 |                                       16% |                                 1,945 |                                  2,725 |
|       [Switzerland](/switzerland) |            2,050 |                     2,226 |                     259 |                        176 |                       20 |                                        9% |                                 2,087 |                                  2,546 |
|               [Ireland](/ireland) |            1,792 |                     1,858 |                     379 |                         66 |                       14 |                                        4% |                                 1,796 |                                  2,053 |
|               [Moldova](/moldova) |            1,211 |                     1,583 |                     391 |                        372 |                       92 |                                       31% |                                 1,365 |                                  1,948 |
|               [Belarus](/belarus) |              785 |                     1,003 |                     106 |                        218 |                       23 |                                       28% |                                   855 |                                  1,308 |
|             [Bulgaria](/bulgaria) |              765 |                       989 |                     141 |                        224 |                       32 |                                       29% |                                   873 |                                  1,185 |
|               [Hungary](/hungary) |              686 |                       969 |                      99 |                        283 |                       29 |                                       41% |                                   795 |                                  1,250 |
|               [Czechia](/czechia) |              522 |                       931 |                      87 |                        409 |                       38 |                                       78% |                                   706 |                                  1,313 |
|               [Austria](/austria) |              767 |                       883 |                     100 |                        116 |                       13 |                                       15% |                                   782 |                                  1,097 |
|                 [Serbia](/serbia) |              743 |                       810 |                     116 |                         67 |                       10 |                                        9% |                                   760 |                                    917 |
|               [Denmark](/denmark) |              640 |                       706 |                     122 |                         66 |                       11 |                                       10% |                                   649 |                                    847 |
|                 [Greece](/greece) |              344 |                       574 |                      54 |                        230 |                       21 |                                       67% |                                   436 |                                    823 |
|               [Finland](/finland) |              341 |                       358 |                      65 |                         17 |                        3 |                                        5% |                                   343 |                                    415 |
|               [Croatia](/croatia) |              253 |                       356 |                      87 |                        103 |                       25 |                                       41% |                                   290 |                                    516 |
|                 [Norway](/norway) |              267 |                       284 |                      53 |                         17 |                        3 |                                        6% |                                   270 |                                    321 |
|             [Slovenia](/slovenia) |              142 |                       166 |                      80 |                         24 |                       11 |                                       17% |                                   146 |                                    211 |
|         [Luxembourg](/luxembourg) |              124 |                       138 |                     225 |                         14 |                       23 |                                       11% |                                   128 |                                    160 |
|           [Lithuania](/lithuania) |               87 |                        94 |                      34 |                          7 |                        3 |                                        8% |                                    88 |                                    107 |
|               [Estonia](/estonia) |               64 |                        68 |                      52 |                          4 |                        3 |                                        7% |                                    66 |                                     75 |
|                   [Malta](/malta) |               23 |                        57 |                     115 |                         34 |                       68 |                                      146% |                                    38 |                                     98 |
|             [Slovakia](/slovakia) |               39 |                        50 |                       9 |                         11 |                        2 |                                       28% |                                    42 |                                     70 |
|                 [Latvia](/latvia) |               36 |                        42 |                      22 |                          6 |                        3 |                                       17% |                                    37 |                                     51 |
|                 [Cyprus](/cyprus) |               22 |                        26 |                      30 |                          4 |                        5 |                                       18% |                                    23 |                                     31 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       12% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          533,437 |                   673,855 |                     130 |                    140,418 |                       27 |                                       26% |                               591,588 |                                792,009 |
|                             [Brazil](/brazil) |          137,272 |                   159,314 |                     755 |                     22,042 |                      104 |                                       16% |                               146,956 |                                177,363 |
|                               [India](/india) |           87,882 |                   135,730 |                      99 |                     47,848 |                       35 |                                       54% |                               106,574 |                                165,034 |
|                             [Mexico](/mexico) |           73,697 |                    88,524 |                     694 |                     14,827 |                      116 |                                       20% |                                82,169 |                                 97,242 |
|                                 [Peru](/peru) |           31,369 |                    33,937 |                   1,044 |                      2,568 |                       79 |                                        8% |                                31,932 |                                 37,429 |
|                                 [Iran](/iran) |           24,478 |                    30,414 |                     367 |                      5,936 |                       72 |                                       24% |                                27,238 |                                 35,137 |
|                         [Colombia](/colombia) |           24,397 |                    29,797 |                     592 |                      5,400 |                      107 |                                       22% |                                27,314 |                                 34,558 |
|                       [Argentina](/argentina) |           13,482 |                    24,567 |                     549 |                     11,085 |                      248 |                                       82% |                                18,747 |                                 32,841 |
|                             [Russia](/russia) |           19,420 |                    24,337 |                     167 |                      4,917 |                       34 |                                       25% |                                20,229 |                                 31,490 |
|                 [South Africa](/south-africa) |           15,992 |                    18,172 |                     310 |                      2,180 |                       37 |                                       14% |                                16,876 |                                 20,517 |
|                       [Indonesia](/indonesia) |            9,677 |                    14,641 |                      54 |                      4,964 |                       18 |                                       51% |                                12,636 |                                 20,044 |
|                               [Chile](/chile) |           12,298 |                    14,457 |                     763 |                      2,159 |                      114 |                                       18% |                                12,541 |                                 19,169 |
|                           [Ecuador](/ecuador) |           11,095 |                    12,337 |                     710 |                      1,242 |                       71 |                                       11% |                                11,181 |                                 14,361 |
|                             [Turkey](/turkey) |            7,574 |                    10,277 |                     123 |                      2,703 |                       32 |                                       36% |                                 8,011 |                                 14,538 |
|                             [Canada](/canada) |            9,279 |                     9,777 |                     261 |                        498 |                       13 |                                        5% |                                 9,316 |                                 11,334 |
|                           [Bolivia](/bolivia) |            7,654 |                     8,759 |                     761 |                      1,105 |                       96 |                                       14% |                                 8,135 |                                  9,454 |
|                   [Philippines](/philippines) |            4,999 |                     7,752 |                      72 |                      2,753 |                       25 |                                       55% |                                 6,144 |                                 10,169 |
|                         [Pakistan](/pakistan) |            6,424 |                     6,753 |                      31 |                        329 |                        2 |                                        5% |                                 6,480 |                                  7,287 |
|                               [Egypt](/egypt) |            5,787 |                     6,535 |                      65 |                        748 |                        7 |                                       13% |                                 5,875 |                                  8,162 |
|                     [Bangladesh](/bangladesh) |            4,979 |                     5,975 |                      37 |                        996 |                        6 |                                       20% |                                 5,369 |                                  7,101 |
|                 [Saudi Arabia](/saudi-arabia) |            4,512 |                     5,250 |                     153 |                        738 |                       22 |                                       16% |                                 4,767 |                                  6,048 |
|                               [China](/china) |            4,737 |                     4,790 |                       3 |                         53 |                        0 |                                        1% |                                 4,737 |                                  5,224 |
|                           [Morocco](/morocco) |            1,855 |                     3,382 |                      93 |                      1,527 |                       42 |                                       82% |                                 2,464 |                                  4,752 |
|                             [Panama](/panama) |            2,272 |                     2,884 |                     679 |                        612 |                      144 |                                       27% |                                 2,685 |                                  3,271 |
|                         [Honduras](/honduras) |            2,204 |                     2,738 |                     281 |                        534 |                       55 |                                       24% |                                 2,367 |                                  3,326 |
|     [Dominican Republic](/dominican-republic) |            2,054 |                     2,630 |                     245 |                        576 |                       54 |                                       28% |                                 2,266 |                                  3,237 |
|                             [Israel](/israel) |            1,273 |                     2,095 |                     246 |                        822 |                       96 |                                       65% |                                 1,534 |                                  3,111 |
|                           [Algeria](/algeria) |            1,679 |                     1,933 |                      45 |                        254 |                        6 |                                       15% |                                 1,734 |                                  2,293 |
|                               [Japan](/japan) |            1,518 |                     1,827 |                      14 |                        309 |                        2 |                                       20% |                                 1,603 |                                  2,197 |
|                           [Nigeria](/nigeria) |            1,100 |                     1,228 |                       6 |                        128 |                        1 |                                       12% |                                 1,132 |                                  1,413 |
|                       [Australia](/australia) |              854 |                       981 |                      39 |                        127 |                        5 |                                       15% |                                   896 |                                  1,112 |
|                             [Kuwait](/kuwait) |              585 |                       745 |                     177 |                        160 |                       38 |                                       27% |                                   608 |                                    965 |
| [United Arab Emirates](/united-arab-emirates) |              405 |                       516 |                      53 |                        111 |                       11 |                                       27% |                                   411 |                                    731 |
|                   [South Korea](/south-korea) |              388 |                       508 |                      10 |                        120 |                        2 |                                       31% |                                   403 |                                    733 |
|                                 [Cuba](/cuba) |              116 |                       156 |                      14 |                         40 |                        3 |                                       34% |                                   126 |                                    218 |
|                         [Malaysia](/malaysia) |              130 |                       138 |                       4 |                          8 |                        0 |                                        7% |                                   132 |                                    148 |
