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

* **August 31:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 9 (3pm ET):
<p align="center">
  Current Total: <b>189,650</b> deaths | Projected Total: <b>218,800 deaths by Nov 1, 2020</b> (Range: 207-236k)<br>
  Currently Infected: <b>1.0%</b> (1 in 95) | Total Infected: <b>15.1%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 8, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        96% |         99% |        99% |
|              225,000 |         <1% |        <1% |          1% |        15% |
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
|             *[United States](/us)* |          189,650 |                   218,754 |                     659 |                     29,104 |                       88 |                                       15% |                               207,479 |                                235,559 |
|                 [New York](/us-ny) |           33,016 |                    33,377 |                   1,716 |                        361 |                       19 |                                        1% |                                33,028 |                                 35,473 |
|               [California](/us-ca) |           13,823 |                    18,040 |                     457 |                      4,217 |                      107 |                                       31% |                                15,703 |                                 21,896 |
|                    [Texas](/us-tx) |           13,792 |                    17,867 |                     616 |                      4,075 |                      141 |                                       30% |                                16,016 |                                 20,414 |
|               [New Jersey](/us-nj) |           15,996 |                    16,156 |                   1,819 |                        160 |                       18 |                                        1% |                                16,007 |                                 16,710 |
|                  [Florida](/us-fl) |           11,915 |                    14,360 |                     669 |                      2,445 |                      114 |                                       21% |                                13,019 |                                 16,114 |
|            [Massachusetts](/us-ma) |            9,141 |                     9,520 |                   1,370 |                        379 |                       55 |                                        4% |                                 9,166 |                                 10,420 |
|                 [Illinois](/us-il) |            8,405 |                     9,292 |                     733 |                        887 |                       70 |                                       11% |                                 8,502 |                                 10,527 |
|             [Pennsylvania](/us-pa) |            7,780 |                     8,377 |                     654 |                        597 |                       47 |                                        8% |                                 7,807 |                                  9,607 |
|                  [Georgia](/us-ga) |            6,070 |                     8,059 |                     759 |                      1,989 |                      187 |                                       33% |                                 7,026 |                                  9,695 |
|                 [Michigan](/us-mi) |            6,811 |                     7,226 |                     724 |                        415 |                       42 |                                        6% |                                 6,845 |                                  7,970 |
|                  [Arizona](/us-az) |            5,221 |                     5,911 |                     812 |                        690 |                       95 |                                       13% |                                 5,485 |                                  6,549 |
|                [Louisiana](/us-la) |            5,118 |                     5,828 |                   1,254 |                        710 |                      153 |                                       14% |                                 5,401 |                                  6,517 |
|                     [Ohio](/us-oh) |            4,298 |                     4,994 |                     427 |                        696 |                       60 |                                       16% |                                 4,464 |                                  5,851 |
|              [Connecticut](/us-ct) |            4,474 |                     4,549 |                   1,276 |                         75 |                       21 |                                        2% |                                 4,483 |                                  4,782 |
|                 [Maryland](/us-md) |            3,807 |                     4,146 |                     686 |                        339 |                       56 |                                        9% |                                 3,836 |                                  4,797 |
|           [North Carolina](/us-nc) |            2,909 |                     3,958 |                     377 |                      1,049 |                      100 |                                       36% |                                 3,391 |                                  4,911 |
|                  [Indiana](/us-in) |            3,380 |                     3,797 |                     564 |                        417 |                       62 |                                       12% |                                 3,404 |                                  4,647 |
|           [South Carolina](/us-sc) |            2,912 |                     3,718 |                     722 |                        806 |                      157 |                                       28% |                                 3,321 |                                  4,327 |
|                 [Virginia](/us-va) |            2,686 |                     3,310 |                     388 |                        624 |                       73 |                                       23% |                                 2,754 |                                  4,211 |
|              [Mississippi](/us-ms) |            2,585 |                     3,176 |                   1,067 |                        591 |                      199 |                                       23% |                                 2,842 |                                  3,658 |
|                  [Alabama](/us-al) |            2,277 |                     2,845 |                     580 |                        568 |                      116 |                                       25% |                                 2,531 |                                  3,339 |
|                [Tennessee](/us-tn) |            1,896 |                     2,697 |                     395 |                        801 |                      117 |                                       42% |                                 2,308 |                                  3,316 |
|               [Washington](/us-wa) |            1,953 |                     2,307 |                     303 |                        354 |                       46 |                                       18% |                                 2,030 |                                  2,776 |
|                 [Missouri](/us-mo) |            1,690 |                     2,301 |                     375 |                        611 |                      100 |                                       36% |                                 1,951 |                                  2,871 |
|                [Minnesota](/us-mn) |            1,914 |                     2,267 |                     402 |                        353 |                       63 |                                       18% |                                 1,971 |                                  2,768 |
|                 [Colorado](/us-co) |            1,973 |                     2,134 |                     371 |                        161 |                       28 |                                        8% |                                 1,983 |                                  2,591 |
|                   [Nevada](/us-nv) |            1,393 |                     1,845 |                     599 |                        452 |                      147 |                                       32% |                                 1,625 |                                  2,163 |
|                     [Iowa](/us-ia) |            1,185 |                     1,705 |                     540 |                        520 |                      165 |                                       44% |                                 1,359 |                                  2,387 |
|                [Wisconsin](/us-wi) |            1,168 |                     1,527 |                     262 |                        359 |                       62 |                                       31% |                                 1,309 |                                  1,887 |
|                 [Arkansas](/us-ar) |              917 |                     1,401 |                     464 |                        484 |                      160 |                                       53% |                                 1,161 |                                  1,753 |
|                 [Kentucky](/us-ky) |              997 |                     1,379 |                     309 |                        382 |                       85 |                                       38% |                                 1,148 |                                  1,740 |
|                 [Oklahoma](/us-ok) |              854 |                     1,242 |                     314 |                        388 |                       98 |                                       45% |                                 1,030 |                                  1,598 |
|             [Rhode Island](/us-ri) |            1,059 |                     1,126 |                   1,063 |                         67 |                       63 |                                        6% |                                 1,067 |                                  1,269 |
|               [New Mexico](/us-nm) |              807 |                       953 |                     454 |                        146 |                       69 |                                       18% |                                   858 |                                  1,102 |
|              [Puerto Rico](/us-pr) |              482 |                       796 |                     249 |                        314 |                       98 |                                       65% |                                   630 |                                  1,062 |
|                   [Kansas](/us-ks) |              484 |                       666 |                     229 |                        182 |                       62 |                                       38% |                                   557 |                                    854 |
|                 [Delaware](/us-de) |              609 |                       650 |                     667 |                         41 |                       42 |                                        7% |                                   613 |                                    730 |
|                   [Oregon](/us-or) |              486 |                       649 |                     154 |                        163 |                       39 |                                       34% |                                   554 |                                    804 |
|     [District of Columbia](/us-dc) |              611 |                       636 |                     902 |                         25 |                       36 |                                        4% |                                   615 |                                    686 |
|                    [Idaho](/us-id) |              389 |                       582 |                     326 |                        193 |                      108 |                                       50% |                                   486 |                                    726 |
|                     [Utah](/us-ut) |              424 |                       571 |                     178 |                        147 |                       46 |                                       35% |                                   487 |                                    702 |
|                 [Nebraska](/us-ne) |              407 |                       518 |                     268 |                        111 |                       57 |                                       27% |                                   435 |                                    653 |
|            [New Hampshire](/us-nh) |              433 |                       458 |                     337 |                         25 |                       18 |                                        6% |                                   435 |                                    519 |
|            [West Virginia](/us-wv) |              252 |                       455 |                     254 |                        203 |                      113 |                                       80% |                                   347 |                                    634 |
|             [South Dakota](/us-sd) |              173 |                       253 |                     286 |                         80 |                       91 |                                       46% |                                   182 |                                    425 |
|             [North Dakota](/us-nd) |              156 |                       246 |                     323 |                         90 |                      118 |                                       58% |                                   194 |                                    330 |
|                   [Hawaii](/us-hi) |               88 |                       228 |                     161 |                        140 |                       99 |                                      159% |                                   154 |                                    352 |
|                  [Montana](/us-mt) |              119 |                       207 |                     193 |                         88 |                       82 |                                       74% |                                   158 |                                    287 |
|                    [Maine](/us-me) |              134 |                       149 |                     111 |                         15 |                       12 |                                       12% |                                   137 |                                    172 |
|                   [Alaska](/us-ak) |               42 |                        75 |                     103 |                         33 |                       45 |                                       79% |                                    57 |                                    109 |
|                  [Wyoming](/us-wy) |               42 |                        67 |                     116 |                         25 |                       44 |                                       61% |                                    54 |                                     94 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     105 |                          8 |                       13 |                                       13% |                                    60 |                                     79 |
|                     [Guam](/us-gu) |               19 |                        52 |                     314 |                         33 |                      199 |                                      174% |                                    35 |                                     81 |
|           [Virgin Islands](/us-vi) |               18 |                        39 |                     373 |                         21 |                      201 |                                      117% |                                    28 |                                     56 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      51 |                          1 |                       14 |                                       40% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          190,989 |                   204,190 |                     344 |                     13,201 |                       22 |                                        7% |                               193,992 |                                236,295 |
| [United Kingdom](/united-kingdom) |           41,675 |                    42,241 |                     626 |                        566 |                        8 |                                        1% |                                41,687 |                                 45,335 |
|                   [Italy](/italy) |           35,563 |                    36,141 |                     599 |                        578 |                       10 |                                        2% |                                35,577 |                                 38,737 |
|                 [France](/france) |           30,770 |                    32,036 |                     478 |                      1,266 |                       19 |                                        4% |                                30,798 |                                 38,731 |
|                   [Spain](/spain) |           29,594 |                    31,880 |                     679 |                      2,286 |                       49 |                                        8% |                                29,622 |                                 40,368 |
|               [Belgium](/belgium) |            9,912 |                    10,067 |                     879 |                        155 |                       13 |                                        2% |                                 9,928 |                                 10,629 |
|               [Germany](/germany) |            9,336 |                     9,672 |                     117 |                        336 |                        4 |                                        4% |                                 9,351 |                                 10,869 |
|       [Netherlands](/netherlands) |            6,279 |                     6,447 |                     373 |                        168 |                       10 |                                        3% |                                 6,292 |                                  7,054 |
|               [Romania](/romania) |            3,967 |                     5,940 |                     306 |                      1,973 |                      102 |                                       50% |                                 4,796 |                                  7,785 |
|                 [Sweden](/sweden) |            5,838 |                     5,879 |                     575 |                         41 |                        4 |                                        1% |                                 5,842 |                                  6,018 |
|               [Ukraine](/ukraine) |            2,988 |                     5,849 |                     133 |                      2,861 |                       65 |                                       96% |                                 4,093 |                                  8,609 |
|                 [Poland](/poland) |            2,136 |                     2,772 |                      73 |                        636 |                       17 |                                       30% |                                 2,321 |                                  3,606 |
|       [Switzerland](/switzerland) |            2,018 |                     2,096 |                     244 |                         78 |                        9 |                                        4% |                                 2,030 |                                  2,275 |
|             [Portugal](/portugal) |            1,846 |                     1,991 |                     194 |                        145 |                       14 |                                        8% |                                 1,852 |                                  2,355 |
|               [Ireland](/ireland) |            1,778 |                     1,816 |                     370 |                         38 |                        8 |                                        2% |                                 1,784 |                                  1,933 |
|               [Moldova](/moldova) |            1,087 |                     1,541 |                     381 |                        454 |                      112 |                                       42% |                                 1,273 |                                  1,983 |
|             [Bulgaria](/bulgaria) |              692 |                     1,148 |                     164 |                        456 |                       65 |                                       66% |                                   879 |                                  1,577 |
|               [Belarus](/belarus) |              721 |                       999 |                     106 |                        278 |                       29 |                                       38% |                                   812 |                                  1,379 |
|                 [Serbia](/serbia) |              727 |                       874 |                     126 |                        147 |                       21 |                                       20% |                                   782 |                                  1,030 |
|               [Austria](/austria) |              747 |                       804 |                      91 |                         57 |                        6 |                                        8% |                                   756 |                                    956 |
|               [Hungary](/hungary) |              626 |                       693 |                      71 |                         67 |                        7 |                                       11% |                                   634 |                                    847 |
|               [Denmark](/denmark) |              628 |                       663 |                     114 |                         35 |                        6 |                                        6% |                                   636 |                                    760 |
|               [Czechia](/czechia) |              441 |                       561 |                      53 |                        120 |                       11 |                                       27% |                                   469 |                                    747 |
|                 [Greece](/greece) |              290 |                       478 |                      45 |                        188 |                       18 |                                       65% |                                   364 |                                    703 |
|               [Finland](/finland) |              336 |                       353 |                      64 |                         17 |                        3 |                                        5% |                                   339 |                                    404 |
|               [Croatia](/croatia) |              203 |                       327 |                      80 |                        124 |                       30 |                                       61% |                                   250 |                                    472 |
|                 [Norway](/norway) |              264 |                       283 |                      53 |                         19 |                        4 |                                        7% |                                   268 |                                    329 |
|             [Slovenia](/slovenia) |              135 |                       154 |                      74 |                         19 |                        9 |                                       14% |                                   138 |                                    191 |
|         [Luxembourg](/luxembourg) |              124 |                       142 |                     231 |                         18 |                       29 |                                       14% |                                   130 |                                    168 |
|           [Lithuania](/lithuania) |               86 |                        97 |                      35 |                         11 |                        4 |                                       12% |                                    88 |                                    115 |
|               [Estonia](/estonia) |               64 |                        70 |                      53 |                          6 |                        4 |                                        9% |                                    67 |                                     75 |
|             [Slovakia](/slovakia) |               37 |                        57 |                      11 |                         20 |                        4 |                                       55% |                                    42 |                                     91 |
|                 [Latvia](/latvia) |               35 |                        43 |                      22 |                          8 |                        4 |                                       22% |                                    36 |                                     53 |
|                 [Cyprus](/cyprus) |               22 |                        32 |                      36 |                         10 |                       11 |                                       45% |                                    26 |                                     44 |
|                   [Malta](/malta) |               14 |                        31 |                      63 |                         17 |                       35 |                                      124% |                                    20 |                                     52 |
|               [Iceland](/iceland) |               10 |                        12 |                      35 |                          2 |                        5 |                                       18% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          485,104 |                   658,380 |                     127 |                    173,276 |                       33 |                                       36% |                               553,088 |                                831,205 |
|                             [Brazil](/brazil) |          127,464 |                   161,762 |                     766 |                     34,298 |                      163 |                                       27% |                               140,373 |                                193,481 |
|                               [India](/india) |           73,890 |                   129,715 |                      95 |                     55,825 |                       41 |                                       76% |                                96,701 |                                184,620 |
|                             [Mexico](/mexico) |           68,484 |                    90,030 |                     706 |                     21,546 |                      169 |                                       31% |                                81,416 |                                102,767 |
|                                 [Peru](/peru) |           29,976 |                    34,489 |                   1,061 |                      4,513 |                      139 |                                       15% |                                31,183 |                                 40,052 |
|                         [Colombia](/colombia) |           21,611 |                    30,370 |                     603 |                      8,759 |                      174 |                                       41% |                                25,242 |                                 38,159 |
|                                 [Iran](/iran) |           22,542 |                    27,200 |                     328 |                      4,658 |                       56 |                                       21% |                                23,868 |                                 32,715 |
|                             [Russia](/russia) |           17,939 |                    22,229 |                     152 |                      4,290 |                       29 |                                       24% |                                18,617 |                                 28,403 |
|                       [Argentina](/argentina) |           10,405 |                    19,573 |                     437 |                      9,168 |                      205 |                                       88% |                                14,691 |                                 26,409 |
|                 [South Africa](/south-africa) |           15,086 |                    18,976 |                     324 |                      3,890 |                       66 |                                       26% |                                15,698 |                                 21,431 |
|                               [Chile](/chile) |           11,682 |                    14,521 |                     766 |                      2,839 |                      150 |                                       24% |                                12,075 |                                 21,115 |
|                       [Indonesia](/indonesia) |            8,230 |                    12,858 |                      48 |                      4,628 |                       17 |                                       56% |                                10,127 |                                 18,918 |
|                           [Ecuador](/ecuador) |           10,627 |                    11,584 |                     667 |                        957 |                       55 |                                        9% |                                10,698 |                                 13,753 |
|                             [Canada](/canada) |            9,203 |                     9,533 |                     255 |                        330 |                        9 |                                        4% |                                 9,229 |                                 10,509 |
|                           [Bolivia](/bolivia) |            7,097 |                     9,483 |                     824 |                      2,386 |                      207 |                                       34% |                                 8,091 |                                 11,574 |
|                             [Turkey](/turkey) |            6,782 |                     8,367 |                     100 |                      1,585 |                       19 |                                       23% |                                 6,907 |                                 11,433 |
|                   [Philippines](/philippines) |            3,916 |                     6,693 |                      62 |                      2,777 |                       26 |                                       71% |                                 4,831 |                                  9,417 |
|                         [Pakistan](/pakistan) |            6,359 |                     6,679 |                      31 |                        320 |                        1 |                                        5% |                                 6,378 |                                  7,465 |
|                     [Bangladesh](/bangladesh) |            4,552 |                     6,222 |                      38 |                      1,670 |                       10 |                                       37% |                                 5,084 |                                  8,276 |
|                               [Egypt](/egypt) |            5,560 |                     6,135 |                      61 |                        575 |                        6 |                                       10% |                                 5,593 |                                  8,218 |
|                 [Saudi Arabia](/saudi-arabia) |            4,137 |                     5,312 |                     155 |                      1,175 |                       34 |                                       28% |                                 4,502 |                                  6,669 |
|                               [China](/china) |            4,733 |                     4,803 |                       3 |                         70 |                        0 |                                        1% |                                 4,733 |                                  5,362 |
|                           [Morocco](/morocco) |            1,427 |                     3,437 |                      94 |                      2,010 |                       55 |                                      141% |                                 2,113 |                                  5,368 |
|                         [Honduras](/honduras) |            2,034 |                     2,815 |                     289 |                        781 |                       80 |                                       38% |                                 2,300 |                                  3,696 |
|     [Dominican Republic](/dominican-republic) |            1,889 |                     2,808 |                     262 |                        919 |                       86 |                                       49% |                                 2,218 |                                  3,753 |
|                             [Panama](/panama) |            2,107 |                     2,526 |                     595 |                        419 |                       99 |                                       20% |                                 2,279 |                                  3,030 |
|                           [Algeria](/algeria) |            1,571 |                     2,103 |                      49 |                        532 |                       12 |                                       34% |                                 1,668 |                                  3,024 |
|                               [Japan](/japan) |            1,398 |                     2,085 |                      16 |                        687 |                        5 |                                       49% |                                 1,572 |                                  3,276 |
|                             [Israel](/israel) |            1,040 |                     1,752 |                     206 |                        712 |                       84 |                                       68% |                                 1,270 |                                  2,653 |
|                           [Nigeria](/nigeria) |            1,067 |                     1,267 |                       6 |                        200 |                        1 |                                       19% |                                 1,121 |                                  1,547 |
|                       [Australia](/australia) |              781 |                     1,196 |                      47 |                        415 |                       16 |                                       53% |                                   952 |                                  1,522 |
|                             [Kuwait](/kuwait) |              548 |                       659 |                     157 |                        111 |                       26 |                                       20% |                                   565 |                                    880 |
| [United Arab Emirates](/united-arab-emirates) |              391 |                       461 |                      47 |                         70 |                        7 |                                       18% |                                   396 |                                    641 |
|                   [South Korea](/south-korea) |              344 |                       451 |                       9 |                        107 |                        2 |                                       31% |                                   350 |                                    688 |
|                                 [Cuba](/cuba) |              104 |                       150 |                      13 |                         46 |                        4 |                                       44% |                                   116 |                                    231 |
|                         [Malaysia](/malaysia) |              128 |                       138 |                       4 |                         10 |                        0 |                                        8% |                                   131 |                                    150 |
