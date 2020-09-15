We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by half.

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

* **September 14:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 14 (9pm ET):
<p align="center">
  Current Total: <b>194,068</b> deaths | Projected Total: <b>218,700 deaths by Nov 1, 2020</b> (Range: 208-234k)<br>
  Currently Infected: <b>0.9%</b> (1 in 110) | Total Infected: <b>15.3%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 14, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        99% |         99% |       >99% |
|              225,000 |         <1% |        <1% |         <1% |        13% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          194,068 |                   218,743 |                     659 |                     24,675 |                       74 |                                       13% |                               208,994 |                                233,050 |
|                 [New York](/us-ny) |           33,023 |                    33,316 |                   1,713 |                        293 |                       15 |                                        1% |                                33,033 |                                 35,025 |
|               [California](/us-ca) |           14,378 |                    17,981 |                     455 |                      3,603 |                       91 |                                       25% |                                15,948 |                                 21,302 |
|                    [Texas](/us-tx) |           14,405 |                    17,197 |                     593 |                      2,792 |                       96 |                                       19% |                                15,872 |                                 18,885 |
|               [New Jersey](/us-nj) |           16,031 |                    16,231 |                   1,827 |                        200 |                       23 |                                        1% |                                16,042 |                                 16,921 |
|                  [Florida](/us-fl) |           12,608 |                    14,841 |                     691 |                      2,233 |                      104 |                                       18% |                                13,605 |                                 16,477 |
|            [Massachusetts](/us-ma) |            9,210 |                     9,605 |                   1,382 |                        395 |                       57 |                                        4% |                                 9,232 |                                 10,374 |
|                 [Illinois](/us-il) |            8,541 |                     9,367 |                     739 |                        826 |                       65 |                                       10% |                                 8,627 |                                 10,442 |
|             [Pennsylvania](/us-pa) |            7,829 |                     8,326 |                     650 |                        497 |                       39 |                                        6% |                                 7,851 |                                  9,360 |
|                  [Georgia](/us-ga) |            6,333 |                     7,566 |                     713 |                      1,233 |                      116 |                                       19% |                                 6,889 |                                  8,580 |
|                 [Michigan](/us-mi) |            6,911 |                     7,378 |                     739 |                        467 |                       47 |                                        7% |                                 6,967 |                                  8,055 |
|                [Louisiana](/us-la) |            5,235 |                     5,820 |                   1,252 |                        585 |                      126 |                                       11% |                                 5,462 |                                  6,416 |
|                  [Arizona](/us-az) |            5,322 |                     5,686 |                     781 |                        364 |                       50 |                                        7% |                                 5,443 |                                  6,054 |
|                     [Ohio](/us-oh) |            4,415 |                     5,379 |                     460 |                        964 |                       82 |                                       22% |                                 4,644 |                                  6,601 |
|              [Connecticut](/us-ct) |            4,480 |                     4,560 |                   1,279 |                         80 |                       22 |                                        2% |                                 4,490 |                                  4,804 |
|                 [Maryland](/us-md) |            3,838 |                     4,107 |                     679 |                        269 |                       45 |                                        7% |                                 3,858 |                                  4,592 |
|           [North Carolina](/us-nc) |            3,052 |                     4,028 |                     384 |                        976 |                       93 |                                       32% |                                 3,514 |                                  4,890 |
|                  [Indiana](/us-in) |            3,438 |                     3,884 |                     577 |                        446 |                       66 |                                       13% |                                 3,469 |                                  4,677 |
|           [South Carolina](/us-sc) |            3,064 |                     3,781 |                     734 |                        717 |                      139 |                                       23% |                                 3,426 |                                  4,302 |
|                 [Virginia](/us-va) |            2,724 |                     3,247 |                     380 |                        523 |                       61 |                                       19% |                                 2,779 |                                  4,011 |
|              [Mississippi](/us-ms) |            2,697 |                     3,131 |                   1,052 |                        434 |                      146 |                                       16% |                                 2,870 |                                  3,560 |
|                [Tennessee](/us-tn) |            2,078 |                     2,947 |                     431 |                        869 |                      127 |                                       42% |                                 2,527 |                                  3,601 |
|                  [Alabama](/us-al) |            2,351 |                     2,828 |                     577 |                        477 |                       97 |                                       20% |                                 2,557 |                                  3,258 |
|                [Minnesota](/us-mn) |            1,971 |                     2,307 |                     409 |                        336 |                       60 |                                       17% |                                 2,024 |                                  2,769 |
|                 [Missouri](/us-mo) |            1,731 |                     2,279 |                     371 |                        548 |                       89 |                                       32% |                                 1,964 |                                  2,787 |
|               [Washington](/us-wa) |            1,991 |                     2,264 |                     297 |                        273 |                       36 |                                       14% |                                 2,036 |                                  2,666 |
|                 [Colorado](/us-co) |            1,988 |                     2,128 |                     370 |                        140 |                       24 |                                        7% |                                 1,997 |                                  2,531 |
|                   [Nevada](/us-nv) |            1,452 |                     1,730 |                     562 |                        278 |                       90 |                                       19% |                                 1,588 |                                  1,937 |
|                     [Iowa](/us-ia) |            1,220 |                     1,603 |                     508 |                        383 |                      121 |                                       31% |                                 1,364 |                                  1,981 |
|                [Wisconsin](/us-wi) |            1,210 |                     1,544 |                     265 |                        334 |                       57 |                                       28% |                                 1,339 |                                  1,883 |
|                 [Kentucky](/us-ky) |            1,060 |                     1,435 |                     321 |                        375 |                       84 |                                       35% |                                 1,214 |                                  1,765 |
|                 [Arkansas](/us-ar) |              981 |                     1,411 |                     468 |                        430 |                      142 |                                       44% |                                 1,207 |                                  1,706 |
|                 [Oklahoma](/us-ok) |              905 |                     1,248 |                     316 |                        343 |                       87 |                                       38% |                                 1,065 |                                  1,562 |
|             [Rhode Island](/us-ri) |            1,071 |                     1,132 |                   1,068 |                         61 |                       57 |                                        6% |                                 1,078 |                                  1,264 |
|               [New Mexico](/us-nm) |              823 |                       945 |                     451 |                        122 |                       58 |                                       15% |                                   862 |                                  1,076 |
|              [Puerto Rico](/us-pr) |              539 |                       882 |                     276 |                        343 |                      108 |                                       64% |                                   707 |                                  1,152 |
|                   [Kansas](/us-ks) |              528 |                       731 |                     251 |                        203 |                       70 |                                       38% |                                   611 |                                    931 |
|                   [Oregon](/us-or) |              509 |                       660 |                     157 |                        151 |                       36 |                                       30% |                                   572 |                                    800 |
|                 [Delaware](/us-de) |              615 |                       652 |                     670 |                         37 |                       38 |                                        6% |                                   619 |                                    725 |
|     [District of Columbia](/us-dc) |              616 |                       639 |                     905 |                         23 |                       32 |                                        4% |                                   619 |                                    683 |
|                    [Idaho](/us-id) |              415 |                       579 |                     324 |                        164 |                       92 |                                       40% |                                   499 |                                    692 |
|                 [Nebraska](/us-ne) |              434 |                       559 |                     289 |                        125 |                       64 |                                       29% |                                   470 |                                    697 |
|                     [Utah](/us-ut) |              433 |                       554 |                     173 |                        121 |                       38 |                                       28% |                                   483 |                                    650 |
|            [New Hampshire](/us-nh) |              436 |                       457 |                     336 |                         21 |                       16 |                                        5% |                                   438 |                                    513 |
|            [West Virginia](/us-wv) |              267 |                       439 |                     245 |                        172 |                       96 |                                       65% |                                   347 |                                    597 |
|             [South Dakota](/us-sd) |              184 |                       265 |                     299 |                         81 |                       91 |                                       44% |                                   193 |                                    418 |
|             [North Dakota](/us-nd) |              168 |                       245 |                     322 |                         77 |                      102 |                                       46% |                                   202 |                                    315 |
|                  [Montana](/us-mt) |              135 |                       238 |                     222 |                        103 |                       96 |                                       76% |                                   186 |                                    324 |
|                   [Hawaii](/us-hi) |               99 |                       176 |                     124 |                         77 |                       54 |                                       78% |                                   137 |                                    236 |
|                    [Maine](/us-me) |              136 |                       150 |                     112 |                         14 |                       10 |                                       10% |                                   139 |                                    170 |
|                   [Alaska](/us-ak) |               44 |                        71 |                      98 |                         27 |                       37 |                                       62% |                                    57 |                                     98 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     76 |
|                     [Guam](/us-gu) |               23 |                        58 |                     353 |                         35 |                      214 |                                      154% |                                    41 |                                     88 |
|                  [Wyoming](/us-wy) |               42 |                        58 |                     101 |                         16 |                       28 |                                       39% |                                    49 |                                     74 |
|           [Virgin Islands](/us-vi) |               19 |                        29 |                     277 |                         10 |                       96 |                                       53% |                                    24 |                                     37 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      49 |                          1 |                       13 |                                       35% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          192,123 |                   206,305 |                     348 |                     14,182 |                       24 |                                        7% |                               194,940 |                                242,153 |
| [United Kingdom](/united-kingdom) |           41,717 |                    42,560 |                     630 |                        843 |                       12 |                                        2% |                                41,740 |                                 46,337 |
|                   [Italy](/italy) |           35,610 |                    36,578 |                     606 |                        968 |                       16 |                                        3% |                                35,628 |                                 40,885 |
|                 [France](/france) |           30,903 |                    32,803 |                     489 |                      1,900 |                       28 |                                        6% |                                30,951 |                                 41,043 |
|                   [Spain](/spain) |           29,747 |                    32,572 |                     694 |                      2,825 |                       60 |                                        9% |                                29,785 |                                 42,035 |
|               [Belgium](/belgium) |            9,925 |                    10,093 |                     881 |                        168 |                       15 |                                        2% |                                 9,941 |                                 10,659 |
|               [Germany](/germany) |            9,354 |                     9,648 |                     116 |                        294 |                        4 |                                        3% |                                 9,367 |                                 10,739 |
|       [Netherlands](/netherlands) |            6,292 |                     6,507 |                     376 |                        215 |                       12 |                                        3% |                                 6,304 |                                  7,253 |
|               [Ukraine](/ukraine) |            3,239 |                     6,013 |                     137 |                      2,774 |                       63 |                                       86% |                                 4,346 |                                  8,526 |
|                 [Sweden](/sweden) |            5,846 |                     5,910 |                     578 |                         64 |                        6 |                                        1% |                                 5,851 |                                  6,109 |
|               [Romania](/romania) |            4,163 |                     5,879 |                     303 |                      1,716 |                       88 |                                       41% |                                 4,917 |                                  7,486 |
|                 [Poland](/poland) |            2,188 |                     2,505 |                      66 |                        317 |                        8 |                                       14% |                                 2,286 |                                  2,806 |
|       [Switzerland](/switzerland) |            2,021 |                     2,104 |                     245 |                         83 |                       10 |                                        4% |                                 2,033 |                                  2,311 |
|             [Portugal](/portugal) |            1,867 |                     2,020 |                     197 |                        153 |                       15 |                                        8% |                                 1,875 |                                  2,399 |
|               [Ireland](/ireland) |            1,784 |                     1,821 |                     371 |                         37 |                        8 |                                        2% |                                 1,790 |                                  1,935 |
|               [Moldova](/moldova) |            1,123 |                     1,494 |                     369 |                        371 |                       92 |                                       33% |                                 1,267 |                                  1,895 |
|             [Bulgaria](/bulgaria) |              720 |                     1,034 |                     148 |                        314 |                       45 |                                       44% |                                   867 |                                  1,314 |
|               [Belarus](/belarus) |              750 |                     1,014 |                     107 |                        264 |                       28 |                                       35% |                                   837 |                                  1,407 |
|               [Austria](/austria) |              756 |                       836 |                      94 |                         80 |                        9 |                                       11% |                                   771 |                                  1,006 |
|                 [Serbia](/serbia) |              733 |                       799 |                     115 |                         66 |                        9 |                                        9% |                                   757 |                                    865 |
|               [Hungary](/hungary) |              637 |                       728 |                      74 |                         91 |                        9 |                                       14% |                                   653 |                                    884 |
|               [Denmark](/denmark) |              631 |                       669 |                     115 |                         38 |                        7 |                                        6% |                                   639 |                                    762 |
|               [Czechia](/czechia) |              456 |                       590 |                      55 |                        134 |                       13 |                                       29% |                                   495 |                                    763 |
|                 [Greece](/greece) |              305 |                       475 |                      44 |                        170 |                       16 |                                       56% |                                   375 |                                    664 |
|               [Croatia](/croatia) |              224 |                       401 |                      98 |                        177 |                       44 |                                       79% |                                   302 |                                    597 |
|               [Finland](/finland) |              337 |                       353 |                      64 |                         16 |                        3 |                                        5% |                                   340 |                                    401 |
|                 [Norway](/norway) |              265 |                       283 |                      53 |                         18 |                        3 |                                        7% |                                   269 |                                    325 |
|             [Slovenia](/slovenia) |              135 |                       151 |                      72 |                         16 |                        8 |                                       12% |                                   137 |                                    183 |
|         [Luxembourg](/luxembourg) |              124 |                       140 |                     227 |                         16 |                       25 |                                       13% |                                   129 |                                    163 |
|           [Lithuania](/lithuania) |               87 |                        96 |                      35 |                          9 |                        3 |                                       11% |                                    89 |                                    112 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        8% |                                    66 |                                     74 |
|             [Slovakia](/slovakia) |               38 |                        52 |                      10 |                         14 |                        3 |                                       37% |                                    42 |                                     72 |
|                 [Latvia](/latvia) |               35 |                        40 |                      21 |                          5 |                        3 |                                       15% |                                    36 |                                     48 |
|                   [Malta](/malta) |               15 |                        29 |                      59 |                         14 |                       29 |                                       94% |                                    20 |                                     46 |
|                 [Cyprus](/cyprus) |               22 |                        28 |                      32 |                          6 |                        7 |                                       29% |                                    25 |                                     35 |
|               [Iceland](/iceland) |               10 |                        11 |                      34 |                          1 |                        4 |                                       14% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          503,713 |                   661,872 |                     128 |                    158,159 |                       30 |                                       31% |                               567,095 |                                803,419 |
|                             [Brazil](/brazil) |          131,625 |                   159,690 |                     757 |                     28,065 |                      133 |                                       21% |                               145,090 |                                181,886 |
|                               [India](/india) |           78,586 |                   133,956 |                      98 |                     55,370 |                       41 |                                       70% |                                99,364 |                                175,672 |
|                             [Mexico](/mexico) |           70,821 |                    89,670 |                     703 |                     18,849 |                      148 |                                       27% |                                81,771 |                                100,441 |
|                                 [Peru](/peru) |           30,526 |                    34,113 |                   1,049 |                      3,587 |                      110 |                                       12% |                                31,407 |                                 38,760 |
|                         [Colombia](/colombia) |           22,924 |                    30,208 |                     600 |                      7,284 |                      145 |                                       32% |                                26,674 |                                 36,535 |
|                                 [Iran](/iran) |           23,157 |                    27,550 |                     332 |                      4,393 |                       53 |                                       19% |                                24,158 |                                 32,962 |
|                             [Russia](/russia) |           18,517 |                    23,371 |                     160 |                      4,854 |                       33 |                                       26% |                                19,067 |                                 29,712 |
|                       [Argentina](/argentina) |           11,352 |                    19,485 |                     435 |                      8,133 |                      182 |                                       72% |                                14,764 |                                 25,786 |
|                 [South Africa](/south-africa) |           15,447 |                    18,509 |                     316 |                      3,062 |                       52 |                                       20% |                                16,773 |                                 21,686 |
|                               [Chile](/chile) |           11,949 |                    14,623 |                     772 |                      2,674 |                      141 |                                       22% |                                12,303 |                                 20,675 |
|                       [Indonesia](/indonesia) |            8,723 |                    13,007 |                      48 |                      4,284 |                       16 |                                       49% |                                10,504 |                                 18,128 |
|                           [Ecuador](/ecuador) |           10,903 |                    11,850 |                     682 |                        947 |                       54 |                                        9% |                                10,972 |                                 13,926 |
|                             [Canada](/canada) |            9,220 |                     9,500 |                     254 |                        280 |                        7 |                                        3% |                                 9,242 |                                 10,352 |
|                           [Bolivia](/bolivia) |            7,344 |                     9,352 |                     812 |                      2,008 |                      174 |                                       27% |                                 8,219 |                                 11,220 |
|                             [Turkey](/turkey) |            7,056 |                     8,777 |                     105 |                      1,721 |                       21 |                                       24% |                                 7,208 |                                 12,058 |
|                   [Philippines](/philippines) |            4,371 |                     7,419 |                      69 |                      3,048 |                       28 |                                       70% |                                 5,576 |                                 10,305 |
|                         [Pakistan](/pakistan) |            6,383 |                     6,586 |                      30 |                        203 |                        1 |                                        3% |                                 6,396 |                                  6,784 |
|                               [Egypt](/egypt) |            5,648 |                     6,521 |                      65 |                        873 |                        9 |                                       15% |                                 5,757 |                                  8,494 |
|                     [Bangladesh](/bangladesh) |            4,733 |                     6,327 |                      39 |                      1,594 |                       10 |                                       34% |                                 5,228 |                                  8,185 |
|                 [Saudi Arabia](/saudi-arabia) |            4,268 |                     5,361 |                     156 |                      1,093 |                       32 |                                       26% |                                 4,608 |                                  6,559 |
|                               [China](/china) |            4,734 |                     4,796 |                       3 |                         62 |                        0 |                                        1% |                                 4,734 |                                  5,291 |
|                           [Morocco](/morocco) |            1,578 |                     3,325 |                      91 |                      1,747 |                       48 |                                      111% |                                 2,191 |                                  4,986 |
|     [Dominican Republic](/dominican-republic) |            1,968 |                     2,763 |                     257 |                        795 |                       74 |                                       40% |                                 2,270 |                                  3,605 |
|                         [Honduras](/honduras) |            2,079 |                     2,708 |                     278 |                        629 |                       65 |                                       30% |                                 2,288 |                                  3,430 |
|                             [Panama](/panama) |            2,166 |                     2,563 |                     604 |                        397 |                       94 |                                       18% |                                 2,303 |                                  2,956 |
|                           [Algeria](/algeria) |            1,612 |                     1,914 |                      44 |                        302 |                        7 |                                       19% |                                 1,682 |                                  2,324 |
|                             [Israel](/israel) |            1,119 |                     1,881 |                     221 |                        762 |                       89 |                                       68% |                                 1,357 |                                  3,000 |
|                               [Japan](/japan) |            1,448 |                     1,856 |                      15 |                        408 |                        3 |                                       28% |                                 1,564 |                                  2,355 |
|                           [Nigeria](/nigeria) |            1,082 |                     1,249 |                       6 |                        167 |                        1 |                                       15% |                                 1,126 |                                  1,482 |
|                       [Australia](/australia) |              816 |                     1,016 |                      40 |                        200 |                        8 |                                       25% |                                   886 |                                  1,208 |
|                             [Kuwait](/kuwait) |              560 |                       675 |                     160 |                        115 |                       27 |                                       21% |                                   586 |                                    869 |
|                   [South Korea](/south-korea) |              363 |                       482 |                       9 |                        119 |                        2 |                                       33% |                                   372 |                                    732 |
| [United Arab Emirates](/united-arab-emirates) |              399 |                       482 |                      49 |                         83 |                        8 |                                       21% |                                   406 |                                    685 |
|                                 [Cuba](/cuba) |              108 |                       150 |                      13 |                         42 |                        4 |                                       39% |                                   119 |                                    222 |
|                         [Malaysia](/malaysia) |              128 |                       137 |                       4 |                          9 |                        0 |                                        7% |                                   130 |                                    148 |
