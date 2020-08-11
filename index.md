We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject.

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

* **August 10:** See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 10:* View our [updated historical performance](/about/#historical-performance).
* **August 5:** We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 11 (2am ET):
<p align="center">
  Current Total: <b>163,460</b> deaths | Projected Total: <b>228,400 deaths by Nov 1, 2020</b> (Range: 202-265k)<br>
  Currently Infected: <b>1.8%</b> (1 in 55) | Total Infected: <b>13.0%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 11, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |        <1% |         33% |        80% |         95% |        99% |
|              225,000 |         <1% |        <1% |         <1% |         8% |         26% |        47% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          2% |         9% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          163,460 |                   228,423 |                     688 |                     64,963 |                                       40% |                               202,554 |                                264,047 |
|                 [New York](/us-ny) |           32,781 |                    33,258 |                   1,710 |                        477 |                                        1% |                                32,800 |                                 35,557 |
|                    [Texas](/us-tx) |            9,230 |                    19,294 |                     665 |                     10,064 |                                      109% |                                14,329 |                                 24,782 |
|               [California](/us-ca) |           10,476 |                    19,207 |                     486 |                      8,731 |                                       83% |                                14,074 |                                 26,436 |
|                  [Florida](/us-fl) |            8,277 |                    16,452 |                     766 |                      8,175 |                                       99% |                                12,206 |                                 21,753 |
|               [New Jersey](/us-nj) |           15,878 |                    16,285 |                   1,833 |                        407 |                                        3% |                                15,917 |                                 17,375 |
|            [Massachusetts](/us-ma) |            8,741 |                     9,913 |                   1,426 |                      1,172 |                                       13% |                                 8,847 |                                 12,434 |
|                 [Illinois](/us-il) |            7,846 |                     9,736 |                     768 |                      1,890 |                                       24% |                                 8,199 |                                 12,854 |
|             [Pennsylvania](/us-pa) |            7,314 |                     8,448 |                     660 |                      1,134 |                                       16% |                                 7,417 |                                 10,571 |
|                 [Michigan](/us-mi) |            6,526 |                     7,347 |                     736 |                        821 |                                       13% |                                 6,599 |                                  8,966 |
|                  [Georgia](/us-ga) |            4,229 |                     7,031 |                     662 |                      2,802 |                                       66% |                                 5,425 |                                  9,516 |
|                  [Arizona](/us-az) |            4,154 |                     6,775 |                     931 |                      2,621 |                                       63% |                                 5,431 |                                  8,417 |
|                [Louisiana](/us-la) |            4,287 |                     5,752 |                   1,237 |                      1,465 |                                       34% |                                 4,888 |                                  7,034 |
|                     [Ohio](/us-oh) |            3,673 |                     5,513 |                     472 |                      1,840 |                                       50% |                                 4,206 |                                  7,722 |
|                 [Maryland](/us-md) |            3,591 |                     4,666 |                     772 |                      1,075 |                                       30% |                                 3,709 |                                  6,807 |
|              [Connecticut](/us-ct) |            4,444 |                     4,577 |                   1,284 |                        133 |                                        3% |                                 4,465 |                                  4,874 |
|                  [Indiana](/us-in) |            3,044 |                     4,201 |                     624 |                      1,157 |                                       38% |                                 3,180 |                                  6,269 |
|           [South Carolina](/us-sc) |            2,048 |                     4,118 |                     800 |                      2,070 |                                      101% |                                 3,070 |                                  5,456 |
|           [North Carolina](/us-nc) |            2,199 |                     4,054 |                     387 |                      1,855 |                                       84% |                                 2,898 |                                  5,940 |
|                 [Virginia](/us-va) |            2,327 |                     4,014 |                     470 |                      1,687 |                                       73% |                                 2,652 |                                  6,600 |
|              [Mississippi](/us-ms) |            1,912 |                     3,232 |                   1,086 |                      1,320 |                                       69% |                                 2,498 |                                  4,182 |
|                  [Alabama](/us-al) |            1,797 |                     3,002 |                     612 |                      1,205 |                                       67% |                                 2,329 |                                  3,912 |
|               [Washington](/us-wa) |            1,697 |                     2,895 |                     380 |                      1,198 |                                       71% |                                 2,003 |                                  4,560 |
|                [Tennessee](/us-tn) |            1,233 |                     2,547 |                     373 |                      1,314 |                                      107% |                                 1,783 |                                  3,641 |
|                 [Colorado](/us-co) |            1,862 |                     2,369 |                     411 |                        507 |                                       27% |                                 1,910 |                                  3,364 |
|                [Minnesota](/us-mn) |            1,701 |                     2,296 |                     407 |                        595 |                                       35% |                                 1,793 |                                  3,362 |
|                 [Missouri](/us-mo) |            1,341 |                     2,213 |                     361 |                        872 |                                       65% |                                 1,596 |                                  3,231 |
|                   [Nevada](/us-nv) |              963 |                     1,897 |                     616 |                        934 |                                       97% |                                 1,357 |                                  2,584 |
|                [Wisconsin](/us-wi) |              998 |                     1,771 |                     304 |                        773 |                                       77% |                                 1,197 |                                  2,837 |
|                     [Iowa](/us-ia) |              934 |                     1,466 |                     465 |                        532 |                                       57% |                                 1,082 |                                  2,138 |
|                 [Kentucky](/us-ky) |              775 |                     1,282 |                     287 |                        507 |                                       65% |                                   913 |                                  1,949 |
|                 [Oklahoma](/us-ok) |              605 |                     1,244 |                     314 |                        639 |                                      106% |                                   834 |                                  1,854 |
|                 [Arkansas](/us-ar) |              555 |                     1,196 |                     396 |                        641 |                                      115% |                                   834 |                                  1,714 |
|              [Puerto Rico](/us-pr) |              279 |                     1,184 |                     371 |                        905 |                                      324% |                                   572 |                                  2,431 |
|             [Rhode Island](/us-ri) |            1,015 |                     1,122 |                   1,059 |                        107 |                                       10% |                                 1,034 |                                  1,291 |
|               [New Mexico](/us-nm) |              690 |                     1,082 |                     516 |                        392 |                                       57% |                                   823 |                                  1,558 |
|                   [Oregon](/us-or) |              357 |                       820 |                     194 |                        463 |                                      130% |                                   509 |                                  1,308 |
|                     [Utah](/us-ut) |              345 |                       727 |                     227 |                        382 |                                      111% |                                   483 |                                  1,096 |
|                    [Idaho](/us-id) |              239 |                       710 |                     397 |                        471 |                                      197% |                                   452 |                                  1,042 |
|                   [Kansas](/us-ks) |              386 |                       698 |                     239 |                        312 |                                       81% |                                   482 |                                  1,085 |
|                 [Delaware](/us-de) |              591 |                       671 |                     689 |                         80 |                                       14% |                                   604 |                                    805 |
|     [District of Columbia](/us-dc) |              591 |                       651 |                     922 |                         60 |                                       10% |                                   602 |                                    753 |
|                 [Nebraska](/us-ne) |              348 |                       527 |                     272 |                        179 |                                       51% |                                   416 |                                    794 |
|            [New Hampshire](/us-nh) |              419 |                       522 |                     384 |                        103 |                                       25% |                                   429 |                                    776 |
|            [West Virginia](/us-wv) |              141 |                       403 |                     225 |                        262 |                                      186% |                                   222 |                                    759 |
|                  [Montana](/us-mt) |               75 |                       259 |                     242 |                        184 |                                      245% |                                   143 |                                    433 |
|             [South Dakota](/us-sd) |              146 |                       235 |                     266 |                         89 |                                       61% |                                   177 |                                    346 |
|             [North Dakota](/us-nd) |              113 |                       209 |                     274 |                         96 |                                       85% |                                   142 |                                    328 |
|                   [Hawaii](/us-hi) |               34 |                       172 |                     121 |                        138 |                                      405% |                                    61 |                                    479 |
|                    [Maine](/us-me) |              125 |                       154 |                     114 |                         29 |                                       23% |                                   130 |                                    198 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     119 |                         16 |                                       28% |                                    61 |                                    104 |
|                   [Alaska](/us-ak) |               26 |                        70 |                      95 |                         44 |                                      168% |                                    41 |                                    121 |
|                  [Wyoming](/us-wy) |               28 |                        45 |                      78 |                         17 |                                       62% |                                    34 |                                     65 |
|           [Virgin Islands](/us-vi) |                9 |                        24 |                     225 |                         15 |                                      162% |                                    14 |                                     41 |
|                     [Guam](/us-gu) |                5 |                         8 |                      51 |                          3 |                                       69% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       57% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,091 |                   211,627 |                     357 |                     21,536 |                                       11% |                               193,914 |                                262,295 |
| [United Kingdom](/united-kingdom) |           46,611 |                    51,002 |                     755 |                      4,391 |                                        9% |                                46,865 |                                 62,489 |
|                   [Italy](/italy) |           35,209 |                    35,987 |                     596 |                        778 |                                        2% |                                35,239 |                                 38,662 |
|                 [France](/france) |           30,327 |                    31,294 |                     467 |                        967 |                                        3% |                                30,364 |                                 36,252 |
|                   [Spain](/spain) |           28,576 |                    30,123 |                     642 |                      1,547 |                                        5% |                                28,618 |                                 36,693 |
|               [Belgium](/belgium) |            9,879 |                    10,389 |                     907 |                        510 |                                        5% |                                 9,916 |                                 12,415 |
|               [Germany](/germany) |            9,203 |                    10,333 |                     124 |                      1,130 |                                       12% |                                 9,313 |                                 13,677 |
|               [Romania](/romania) |            2,729 |                     6,653 |                     343 |                      3,924 |                                      144% |                                 3,981 |                                 11,782 |
|       [Netherlands](/netherlands) |            6,178 |                     6,565 |                     380 |                        387 |                                        6% |                                 6,205 |                                  8,074 |
|                 [Sweden](/sweden) |            5,766 |                     5,958 |                     582 |                        192 |                                        3% |                                 5,803 |                                  6,078 |
|               [Ukraine](/ukraine) |            1,950 |                     5,086 |                     116 |                      3,136 |                                      161% |                                 2,766 |                                  9,975 |
|                 [Poland](/poland) |            1,809 |                     2,894 |                      76 |                      1,085 |                                       60% |                                 2,014 |                                  4,669 |
|       [Switzerland](/switzerland) |            1,987 |                     2,083 |                     242 |                         96 |                                        5% |                                 2,000 |                                  2,479 |
|             [Portugal](/portugal) |            1,759 |                     2,053 |                     200 |                        294 |                                       17% |                                 1,772 |                                  2,714 |
|               [Ireland](/ireland) |            1,772 |                     1,865 |                     380 |                         93 |                                        5% |                                 1,784 |                                  2,145 |
|               [Moldova](/moldova) |              850 |                     1,345 |                     333 |                        495 |                                       58% |                                 1,034 |                                  1,982 |
|             [Bulgaria](/bulgaria) |              459 |                     1,193 |                     170 |                        734 |                                      160% |                                   695 |                                  2,260 |
|                 [Serbia](/serbia) |              646 |                     1,147 |                     165 |                        501 |                                       78% |                                   822 |                                  1,766 |
|               [Austria](/austria) |              723 |                       821 |                      93 |                         98 |                                       14% |                                   737 |                                  1,071 |
|               [Belarus](/belarus) |              589 |                       803 |                      85 |                        214 |                                       36% |                                   714 |                                  1,001 |
|               [Denmark](/denmark) |              620 |                       733 |                     126 |                        113 |                                       18% |                                   641 |                                  1,046 |
|               [Hungary](/hungary) |              605 |                       701 |                      72 |                         96 |                                       16% |                                   614 |                                    933 |
|               [Czechia](/czechia) |              390 |                       555 |                      52 |                        165 |                                       42% |                                   420 |                                    880 |
|               [Finland](/finland) |              333 |                       379 |                      69 |                         46 |                                       14% |                                   341 |                                    498 |
|                 [Greece](/greece) |              213 |                       337 |                      31 |                        124 |                                       58% |                                   240 |                                    589 |
|               [Croatia](/croatia) |              158 |                       318 |                      78 |                        160 |                                      101% |                                   203 |                                    606 |
|                 [Norway](/norway) |              256 |                       295 |                      55 |                         39 |                                       15% |                                   264 |                                    404 |
|         [Luxembourg](/luxembourg) |              121 |                       201 |                     327 |                         80 |                                       66% |                                   142 |                                    350 |
|             [Slovenia](/slovenia) |              128 |                       198 |                      95 |                         70 |                                       55% |                                   144 |                                    342 |
|           [Lithuania](/lithuania) |               81 |                       100 |                      36 |                         19 |                                       23% |                                    85 |                                    136 |
|               [Estonia](/estonia) |               63 |                        72 |                      54 |                          9 |                                       14% |                                    68 |                                     80 |
|             [Slovakia](/slovakia) |               31 |                        53 |                      10 |                         22 |                                       70% |                                    34 |                                    109 |
|                 [Latvia](/latvia) |               32 |                        41 |                      21 |                          9 |                                       28% |                                    34 |                                     58 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       48% |                                    22 |                                     42 |
|               [Iceland](/iceland) |               10 |                        13 |                      39 |                          3 |                                       33% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        12 |                      25 |                          3 |                                       36% |                                    10 |                                     17 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          359,237 |                   664,008 |                     128 |                    304,771 |                                       85% |                               474,538 |                                980,755 |
|                             [Brazil](/brazil) |          101,752 |                   172,397 |                     817 |                     70,645 |                                       69% |                               121,222 |                                248,430 |
|                               [India](/india) |           45,257 |                   124,377 |                      91 |                     79,120 |                                      175% |                                76,994 |                                178,258 |
|                             [Mexico](/mexico) |           53,003 |                    99,603 |                     781 |                     46,600 |                                       88% |                                81,322 |                                140,282 |
|                         [Colombia](/colombia) |           13,154 |                    31,519 |                     626 |                     18,365 |                                      140% |                                21,016 |                                 48,868 |
|                                 [Peru](/peru) |           21,276 |                    30,823 |                     948 |                      9,547 |                                       45% |                                24,686 |                                 43,431 |
|                                 [Iran](/iran) |           18,616 |                    27,923 |                     337 |                      9,307 |                                       50% |                                22,021 |                                 38,659 |
|                 [South Africa](/south-africa) |           10,621 |                    24,924 |                     426 |                     14,303 |                                      135% |                                16,289 |                                 36,528 |
|                             [Russia](/russia) |           14,973 |                    21,754 |                     149 |                      6,781 |                                       45% |                                17,083 |                                 32,105 |
|                       [Argentina](/argentina) |            4,764 |                    16,588 |                     370 |                     11,824 |                                      248% |                                 9,094 |                                 30,484 |
|                               [Chile](/chile) |           10,139 |                    15,239 |                     804 |                      5,100 |                                       50% |                                10,914 |                                 26,300 |
|                       [Indonesia](/indonesia) |            5,765 |                    11,444 |                      42 |                      5,679 |                                       99% |                                 7,656 |                                 19,961 |
|                             [Canada](/canada) |            9,034 |                     9,463 |                     253 |                        429 |                                        5% |                                 9,071 |                                 10,500 |
|                           [Bolivia](/bolivia) |            3,712 |                     7,671 |                     666 |                      3,959 |                                      107% |                                 5,099 |                                 12,569 |
|                           [Ecuador](/ecuador) |            5,932 |                     7,507 |                     432 |                      1,575 |                                       27% |                                 6,120 |                                 10,929 |
|                             [Turkey](/turkey) |            5,858 |                     7,439 |                      89 |                      1,581 |                                       27% |                                 5,942 |                                 11,720 |
|                         [Pakistan](/pakistan) |            6,097 |                     7,126 |                      33 |                      1,029 |                                       17% |                                 6,272 |                                  8,452 |
|                               [Egypt](/egypt) |            5,035 |                     5,918 |                      59 |                        883 |                                       18% |                                 5,205 |                                  7,246 |
|                     [Bangladesh](/bangladesh) |            3,438 |                     5,531 |                      34 |                      2,093 |                                       61% |                                 3,959 |                                  9,309 |
|                   [Philippines](/philippines) |            2,294 |                     5,132 |                      47 |                      2,838 |                                      124% |                                 2,762 |                                 11,055 |
|                               [China](/china) |            4,689 |                     4,908 |                       3 |                        219 |                                        5% |                                 4,689 |                                  6,406 |
|                 [Saudi Arabia](/saudi-arabia) |            3,199 |                     4,897 |                     143 |                      1,698 |                                       53% |                                 3,725 |                                  7,467 |
|                           [Morocco](/morocco) |              516 |                     3,015 |                      83 |                      2,499 |                                      484% |                                 1,025 |                                  7,338 |
|                             [Panama](/panama) |            1,664 |                     3,011 |                     709 |                      1,347 |                                       81% |                                 2,138 |                                  4,593 |
|                         [Honduras](/honduras) |            1,506 |                     2,988 |                     307 |                      1,482 |                                       98% |                                 1,940 |                                  5,151 |
|     [Dominican Republic](/dominican-republic) |            1,328 |                     2,566 |                     239 |                      1,238 |                                       93% |                                 1,725 |                                  4,399 |
|                           [Algeria](/algeria) |            1,312 |                     2,267 |                      53 |                        955 |                                       73% |                                 1,522 |                                  4,017 |
|                               [Japan](/japan) |            1,052 |                     1,732 |                      14 |                        680 |                                       65% |                                 1,069 |                                  4,361 |
|                       [Australia](/australia) |              331 |                     1,512 |                      60 |                      1,181 |                                      357% |                                   677 |                                  3,568 |
|                             [Israel](/israel) |              613 |                     1,469 |                     172 |                        856 |                                      140% |                                   844 |                                  2,923 |
|                           [Nigeria](/nigeria) |              950 |                     1,388 |                       7 |                        438 |                                       46% |                                 1,038 |                                  2,257 |
|                             [Kuwait](/kuwait) |              482 |                       771 |                     183 |                        289 |                                       60% |                                   524 |                                  1,457 |
| [United Arab Emirates](/united-arab-emirates) |              357 |                       452 |                      46 |                         95 |                                       27% |                                   364 |                                    719 |
|                   [South Korea](/south-korea) |              305 |                       380 |                       7 |                         75 |                                       24% |                                   305 |                                    622 |
|                         [Malaysia](/malaysia) |              125 |                       142 |                       4 |                         17 |                                       14% |                                   130 |                                    160 |
|                                 [Cuba](/cuba) |               88 |                       132 |                      12 |                         44 |                                       50% |                                    96 |                                    231 |
