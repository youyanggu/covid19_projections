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

* *August 31:* View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 13 (3pm ET):
<p align="center">
  Current Total: <b>193,690</b> deaths | Projected Total: <b>220,000 deaths by Nov 1, 2020</b> (Range: 210-235k)<br>
  Currently Infected: <b>1.0%</b> (1 in 100) | Total Infected: <b>15.5%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 13, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        99% |         99% |       >99% |
|              225,000 |         <1% |        <1% |         <1% |        17% |
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
|             *[United States](/us)* |          193,690 |                   220,046 |                     663 |                     26,356 |                       79 |                                       14% |                               210,182 |                                234,691 |
|                 [New York](/us-ny) |           33,023 |                    33,326 |                   1,713 |                        303 |                       16 |                                        1% |                                33,034 |                                 35,089 |
|               [California](/us-ca) |           14,327 |                    18,105 |                     458 |                      3,778 |                       96 |                                       26% |                                15,986 |                                 21,507 |
|                    [Texas](/us-tx) |           14,332 |                    17,605 |                     607 |                      3,273 |                      113 |                                       23% |                                16,367 |                                 19,349 |
|               [New Jersey](/us-nj) |           16,027 |                    16,176 |                   1,821 |                        149 |                       17 |                                        1% |                                16,038 |                                 16,691 |
|                  [Florida](/us-fl) |           12,600 |                    15,033 |                     700 |                      2,433 |                      113 |                                       19% |                                13,884 |                                 16,708 |
|            [Massachusetts](/us-ma) |            9,196 |                     9,549 |                   1,374 |                        353 |                       51 |                                        4% |                                 9,218 |                                 10,360 |
|                 [Illinois](/us-il) |            8,527 |                     9,388 |                     741 |                        861 |                       68 |                                       10% |                                 8,618 |                                 10,485 |
|             [Pennsylvania](/us-pa) |            7,829 |                     8,347 |                     652 |                        518 |                       40 |                                        7% |                                 7,852 |                                  9,404 |
|                  [Georgia](/us-ga) |            6,287 |                     7,835 |                     738 |                      1,548 |                      146 |                                       25% |                                 7,031 |                                  8,983 |
|                 [Michigan](/us-mi) |            6,911 |                     7,369 |                     738 |                        458 |                       46 |                                        7% |                                 6,947 |                                  8,094 |
|                  [Arizona](/us-az) |            5,315 |                     5,897 |                     810 |                        582 |                       80 |                                       11% |                                 5,533 |                                  6,462 |
|                [Louisiana](/us-la) |            5,202 |                     5,811 |                   1,250 |                        609 |                      131 |                                       12% |                                 5,443 |                                  6,431 |
|                     [Ohio](/us-oh) |            4,411 |                     5,079 |                     435 |                        668 |                       57 |                                       15% |                                 4,565 |                                  5,891 |
|              [Connecticut](/us-ct) |            4,480 |                     4,548 |                   1,276 |                         68 |                       19 |                                        2% |                                 4,488 |                                  4,758 |
|                 [Maryland](/us-md) |            3,836 |                     4,139 |                     685 |                        303 |                       50 |                                        8% |                                 3,862 |                                  4,719 |
|           [North Carolina](/us-nc) |            3,047 |                     4,066 |                     388 |                      1,019 |                       97 |                                       33% |                                 3,532 |                                  4,948 |
|                  [Indiana](/us-in) |            3,437 |                     3,829 |                     569 |                        392 |                       58 |                                       11% |                                 3,459 |                                  4,633 |
|           [South Carolina](/us-sc) |            3,040 |                     3,777 |                     734 |                        737 |                      143 |                                       24% |                                 3,412 |                                  4,309 |
|                 [Virginia](/us-va) |            2,722 |                     3,262 |                     382 |                        540 |                       63 |                                       20% |                                 2,780 |                                  4,046 |
|              [Mississippi](/us-ms) |            2,685 |                     3,203 |                   1,076 |                        518 |                      174 |                                       19% |                                 2,902 |                                  3,638 |
|                [Tennessee](/us-tn) |            2,064 |                     2,958 |                     433 |                        894 |                      131 |                                       43% |                                 2,525 |                                  3,625 |
|                  [Alabama](/us-al) |            2,350 |                     2,851 |                     581 |                        501 |                      102 |                                       21% |                                 2,565 |                                  3,295 |
|               [Washington](/us-wa) |            1,991 |                     2,299 |                     302 |                        308 |                       40 |                                       15% |                                 2,060 |                                  2,712 |
|                 [Missouri](/us-mo) |            1,728 |                     2,295 |                     374 |                        567 |                       92 |                                       33% |                                 1,972 |                                  2,815 |
|                [Minnesota](/us-mn) |            1,958 |                     2,294 |                     407 |                        336 |                       60 |                                       17% |                                 2,013 |                                  2,761 |
|                 [Colorado](/us-co) |            1,988 |                     2,133 |                     370 |                        145 |                       25 |                                        7% |                                 1,998 |                                  2,547 |
|                   [Nevada](/us-nv) |            1,449 |                     1,837 |                     596 |                        388 |                      126 |                                       27% |                                 1,651 |                                  2,108 |
|                     [Iowa](/us-ia) |            1,218 |                     1,669 |                     529 |                        451 |                      143 |                                       37% |                                 1,375 |                                  2,206 |
|                [Wisconsin](/us-wi) |            1,209 |                     1,556 |                     267 |                        347 |                       60 |                                       29% |                                 1,345 |                                  1,911 |
|                 [Kentucky](/us-ky) |            1,057 |                     1,448 |                     324 |                        391 |                       88 |                                       37% |                                 1,220 |                                  1,791 |
|                 [Arkansas](/us-ar) |              969 |                     1,411 |                     467 |                        442 |                      146 |                                       46% |                                 1,202 |                                  1,711 |
|                 [Oklahoma](/us-ok) |              899 |                     1,254 |                     317 |                        355 |                       90 |                                       40% |                                 1,064 |                                  1,576 |
|             [Rhode Island](/us-ri) |            1,071 |                     1,134 |                   1,070 |                         63 |                       59 |                                        6% |                                 1,078 |                                  1,270 |
|               [New Mexico](/us-nm) |              821 |                       951 |                     453 |                        130 |                       62 |                                       16% |                                   865 |                                  1,086 |
|              [Puerto Rico](/us-pr) |              535 |                       900 |                     282 |                        365 |                      114 |                                       68% |                                   718 |                                  1,186 |
|                   [Kansas](/us-ks) |              526 |                       735 |                     252 |                        209 |                       72 |                                       40% |                                   611 |                                    942 |
|                   [Oregon](/us-or) |              505 |                       659 |                     156 |                        154 |                       36 |                                       30% |                                   569 |                                    801 |
|                 [Delaware](/us-de) |              613 |                       650 |                     668 |                         37 |                       38 |                                        6% |                                   617 |                                    723 |
|     [District of Columbia](/us-dc) |              616 |                       640 |                     906 |                         24 |                       33 |                                        4% |                                   620 |                                    686 |
|                    [Idaho](/us-id) |              415 |                       591 |                     331 |                        176 |                       98 |                                       42% |                                   506 |                                    719 |
|                 [Nebraska](/us-ne) |              437 |                       567 |                     293 |                        130 |                       67 |                                       30% |                                   478 |                                    709 |
|                     [Utah](/us-ut) |              433 |                       560 |                     175 |                        127 |                       40 |                                       29% |                                   489 |                                    669 |
|            [New Hampshire](/us-nh) |              435 |                       457 |                     336 |                         22 |                       16 |                                        5% |                                   437 |                                    512 |
|            [West Virginia](/us-wv) |              266 |                       446 |                     249 |                        180 |                      100 |                                       67% |                                   350 |                                    609 |
|             [South Dakota](/us-sd) |              183 |                       269 |                     304 |                         86 |                       98 |                                       47% |                                   194 |                                    435 |
|             [North Dakota](/us-nd) |              167 |                       257 |                     337 |                         90 |                      118 |                                       54% |                                   207 |                                    336 |
|                  [Montana](/us-mt) |              133 |                       237 |                     222 |                        104 |                       98 |                                       78% |                                   185 |                                    325 |
|                   [Hawaii](/us-hi) |               97 |                       197 |                     139 |                        100 |                       71 |                                      103% |                                   147 |                                    277 |
|                    [Maine](/us-me) |              135 |                       149 |                     111 |                         14 |                       10 |                                       10% |                                   138 |                                    169 |
|                   [Alaska](/us-ak) |               44 |                        73 |                      99 |                         29 |                       39 |                                       65% |                                    58 |                                    101 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     77 |
|                     [Guam](/us-gu) |               23 |                        64 |                     383 |                         41 |                      245 |                                      176% |                                    45 |                                     95 |
|                  [Wyoming](/us-wy) |               42 |                        59 |                     102 |                         17 |                       29 |                                       40% |                                    50 |                                     76 |
|           [Virgin Islands](/us-vi) |               19 |                        37 |                     354 |                         18 |                      173 |                                       95% |                                    28 |                                     51 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      49 |                          1 |                       13 |                                       35% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          191,984 |                   204,127 |                     344 |                     12,143 |                       20 |                                        6% |                               194,871 |                                232,714 |
| [United Kingdom](/united-kingdom) |           41,712 |                    42,208 |                     625 |                        496 |                        7 |                                        1% |                                41,723 |                                 44,958 |
|                   [Italy](/italy) |           35,603 |                    36,125 |                     599 |                        522 |                        9 |                                        1% |                                35,616 |                                 38,533 |
|                 [France](/france) |           30,902 |                    32,100 |                     479 |                      1,198 |                       18 |                                        4% |                                30,929 |                                 38,364 |
|                   [Spain](/spain) |           29,747 |                    31,669 |                     675 |                      1,922 |                       41 |                                        6% |                                29,772 |                                 38,379 |
|               [Belgium](/belgium) |            9,923 |                    10,064 |                     879 |                        141 |                       12 |                                        1% |                                 9,938 |                                 10,567 |
|               [Germany](/germany) |            9,352 |                     9,652 |                     116 |                        300 |                        4 |                                        3% |                                 9,365 |                                 10,760 |
|       [Netherlands](/netherlands) |            6,291 |                     6,442 |                     373 |                        151 |                        9 |                                        2% |                                 6,303 |                                  6,984 |
|               [Ukraine](/ukraine) |            3,206 |                     6,082 |                     138 |                      2,876 |                       65 |                                       90% |                                 4,326 |                                  8,849 |
|               [Romania](/romania) |            4,127 |                     5,886 |                     303 |                      1,759 |                       91 |                                       43% |                                 4,898 |                                  7,528 |
|                 [Sweden](/sweden) |            5,846 |                     5,882 |                     575 |                         36 |                        4 |                                        1% |                                 5,850 |                                  6,009 |
|                 [Poland](/poland) |            2,182 |                     2,781 |                      73 |                        599 |                       16 |                                       27% |                                 2,365 |                                  3,514 |
|       [Switzerland](/switzerland) |            2,020 |                     2,087 |                     243 |                         67 |                        8 |                                        3% |                                 2,031 |                                  2,246 |
|             [Portugal](/portugal) |            1,860 |                     2,001 |                     195 |                        141 |                       14 |                                        8% |                                 1,865 |                                  2,343 |
|               [Ireland](/ireland) |            1,783 |                     1,820 |                     371 |                         37 |                        8 |                                        2% |                                 1,789 |                                  1,934 |
|               [Moldova](/moldova) |            1,117 |                     1,504 |                     372 |                        387 |                       96 |                                       35% |                                 1,264 |                                  1,924 |
|             [Bulgaria](/bulgaria) |              717 |                     1,069 |                     153 |                        352 |                       50 |                                       49% |                                   865 |                                  1,401 |
|               [Belarus](/belarus) |              744 |                     1,015 |                     107 |                        271 |                       29 |                                       36% |                                   835 |                                  1,370 |
|                 [Serbia](/serbia) |              731 |                       859 |                     123 |                        128 |                       18 |                                       17% |                                   778 |                                  1,000 |
|               [Austria](/austria) |              754 |                       813 |                      92 |                         59 |                        7 |                                        8% |                                   762 |                                    972 |
|               [Hungary](/hungary) |              633 |                       702 |                      72 |                         69 |                        7 |                                       11% |                                   641 |                                    850 |
|               [Denmark](/denmark) |              630 |                       663 |                     114 |                         33 |                        6 |                                        5% |                                   637 |                                    754 |
|               [Czechia](/czechia) |              453 |                       584 |                      55 |                        131 |                       12 |                                       29% |                                   491 |                                    758 |
|                 [Greece](/greece) |              302 |                       474 |                      44 |                        172 |                       16 |                                       57% |                                   373 |                                    665 |
|               [Croatia](/croatia) |              218 |                       389 |                      95 |                        171 |                       42 |                                       78% |                                   291 |                                    571 |
|               [Finland](/finland) |              337 |                       353 |                      64 |                         16 |                        3 |                                        5% |                                   340 |                                    402 |
|                 [Norway](/norway) |              265 |                       283 |                      53 |                         18 |                        3 |                                        7% |                                   269 |                                    326 |
|             [Slovenia](/slovenia) |              135 |                       151 |                      73 |                         16 |                        8 |                                       12% |                                   137 |                                    184 |
|         [Luxembourg](/luxembourg) |              124 |                       140 |                     228 |                         16 |                       26 |                                       13% |                                   129 |                                    163 |
|           [Lithuania](/lithuania) |               86 |                        94 |                      34 |                          8 |                        3 |                                       10% |                                    88 |                                    108 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        8% |                                    66 |                                     74 |
|             [Slovakia](/slovakia) |               38 |                        54 |                      10 |                         16 |                        3 |                                       42% |                                    43 |                                     77 |
|                 [Latvia](/latvia) |               35 |                        41 |                      21 |                          6 |                        3 |                                       16% |                                    36 |                                     48 |
|                   [Malta](/malta) |               15 |                        31 |                      62 |                         16 |                       32 |                                      105% |                                    21 |                                     49 |
|                 [Cyprus](/cyprus) |               22 |                        29 |                      33 |                          7 |                        8 |                                       31% |                                    25 |                                     36 |
|               [Iceland](/iceland) |               10 |                        12 |                      34 |                          2 |                        5 |                                       16% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          501,962 |                   668,028 |                     129 |                    166,066 |                       32 |                                       33% |                               568,794 |                                818,313 |
|                             [Brazil](/brazil) |          131,210 |                   162,996 |                     772 |                     31,786 |                      151 |                                       24% |                               146,180 |                                190,678 |
|                               [India](/india) |           78,586 |                   134,838 |                      99 |                     56,252 |                       41 |                                       72% |                                99,313 |                                177,862 |
|                             [Mexico](/mexico) |           70,604 |                    90,316 |                     708 |                     19,712 |                      155 |                                       28% |                                82,309 |                                102,023 |
|                                 [Peru](/peru) |           30,470 |                    34,268 |                   1,054 |                      3,798 |                      117 |                                       12% |                                31,415 |                                 39,093 |
|                         [Colombia](/colombia) |           22,734 |                    30,744 |                     611 |                      8,010 |                      159 |                                       35% |                                26,506 |                                 37,114 |
|                                 [Iran](/iran) |           23,029 |                    27,264 |                     329 |                      4,235 |                       51 |                                       18% |                                24,182 |                                 32,469 |
|                             [Russia](/russia) |           18,426 |                    22,769 |                     156 |                      4,343 |                       30 |                                       24% |                                19,360 |                                 28,626 |
|                       [Argentina](/argentina) |           11,263 |                    19,719 |                     440 |                      8,456 |                      189 |                                       75% |                                15,099 |                                 25,939 |
|                 [South Africa](/south-africa) |           15,427 |                    18,836 |                     322 |                      3,409 |                       58 |                                       22% |                                15,916 |                                 21,108 |
|                               [Chile](/chile) |           11,895 |                    14,606 |                     771 |                      2,711 |                      143 |                                       23% |                                12,263 |                                 20,754 |
|                       [Indonesia](/indonesia) |            8,650 |                    13,080 |                      48 |                      4,430 |                       16 |                                       51% |                                10,482 |                                 18,620 |
|                           [Ecuador](/ecuador) |           10,864 |                    11,818 |                     680 |                        954 |                       55 |                                        9% |                                10,945 |                                 13,865 |
|                             [Canada](/canada) |            9,220 |                     9,510 |                     254 |                        290 |                        8 |                                        3% |                                 9,243 |                                 10,379 |
|                           [Bolivia](/bolivia) |            7,297 |                     9,368 |                     814 |                      2,071 |                      180 |                                       28% |                                 8,169 |                                 11,267 |
|                             [Turkey](/turkey) |            6,999 |                     8,692 |                     104 |                      1,693 |                       20 |                                       24% |                                 7,165 |                                 11,605 |
|                   [Philippines](/philippines) |            4,292 |                     8,335 |                      77 |                      4,043 |                       37 |                                       94% |                                 6,343 |                                 12,237 |
|                         [Pakistan](/pakistan) |            6,379 |                     6,657 |                      31 |                        278 |                        1 |                                        4% |                                 6,393 |                                  7,363 |
|                     [Bangladesh](/bangladesh) |            4,702 |                     6,324 |                      39 |                      1,622 |                       10 |                                       35% |                                 5,212 |                                  8,217 |
|                               [Egypt](/egypt) |            5,627 |                     6,151 |                      61 |                        524 |                        5 |                                        9% |                                 5,653 |                                  8,062 |
|                 [Saudi Arabia](/saudi-arabia) |            4,240 |                     5,347 |                     156 |                      1,107 |                       32 |                                       26% |                                 4,588 |                                  6,561 |
|                               [China](/china) |            4,734 |                     4,798 |                       3 |                         64 |                        0 |                                        1% |                                 4,734 |                                  5,311 |
|                           [Morocco](/morocco) |            1,553 |                     3,359 |                      92 |                      1,806 |                       50 |                                      116% |                                 2,188 |                                  5,052 |
|     [Dominican Republic](/dominican-republic) |            1,953 |                     2,766 |                     258 |                        813 |                       76 |                                       42% |                                 2,247 |                                  3,642 |
|                         [Honduras](/honduras) |            2,065 |                     2,713 |                     278 |                        648 |                       66 |                                       31% |                                 2,283 |                                  3,455 |
|                             [Panama](/panama) |            2,155 |                     2,526 |                     595 |                        371 |                       87 |                                       17% |                                 2,304 |                                  2,979 |
|                           [Algeria](/algeria) |            1,605 |                     2,098 |                      49 |                        493 |                       11 |                                       31% |                                 1,687 |                                  2,933 |
|                               [Japan](/japan) |            1,441 |                     2,056 |                      16 |                        615 |                        5 |                                       43% |                                 1,604 |                                  2,973 |
|                             [Israel](/israel) |            1,103 |                     1,805 |                     212 |                        702 |                       82 |                                       64% |                                 1,357 |                                  2,621 |
|                           [Nigeria](/nigeria) |            1,078 |                     1,248 |                       6 |                        170 |                        1 |                                       16% |                                 1,123 |                                  1,487 |
|                       [Australia](/australia) |              810 |                     1,125 |                      45 |                        315 |                       13 |                                       39% |                                   937 |                                  1,402 |
|                             [Kuwait](/kuwait) |              558 |                       661 |                     157 |                        103 |                       24 |                                       18% |                                   573 |                                    867 |
|                   [South Korea](/south-korea) |              358 |                       475 |                       9 |                        117 |                        2 |                                       33% |                                   367 |                                    728 |
| [United Arab Emirates](/united-arab-emirates) |              399 |                       471 |                      48 |                         72 |                        7 |                                       18% |                                   404 |                                    646 |
|                                 [Cuba](/cuba) |              108 |                       152 |                      13 |                         44 |                        4 |                                       41% |                                   120 |                                    227 |
|                         [Malaysia](/malaysia) |              128 |                       138 |                       4 |                         10 |                        0 |                                        7% |                                   130 |                                    148 |
