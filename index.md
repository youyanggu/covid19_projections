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

* **September 15:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1305937870075703296). See how well our US forecasts from late August [have performed](/about/#comparison-of-late-august-us-projections).
* **September 14:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 16 (3pm ET):
<p align="center">
  Current Total: <b>195,912</b> deaths | Projected Total: <b>219,300 deaths by Nov 1, 2020</b> (Range: 209-233k)<br>
  Currently Infected: <b>0.9%</b> (1 in 110) | Total Infected: <b>15.5%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 16, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |        99% |        >99% |       >99% |
|              225,000 |        <1% |         <1% |        14% |
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
|             *[United States](/us)* |          195,912 |                   219,335 |                     661 |                     23,423 |                       71 |                                       12% |                               209,985 |                                232,681 |
|                 [New York](/us-ny) |           33,038 |                    33,317 |                   1,713 |                        279 |                       14 |                                        1% |                                33,049 |                                 34,939 |
|               [California](/us-ca) |           14,594 |                    17,425 |                     441 |                      2,831 |                       72 |                                       19% |                                15,666 |                                 19,872 |
|                    [Texas](/us-tx) |           14,593 |                    17,372 |                     599 |                      2,779 |                       96 |                                       19% |                                16,018 |                                 19,093 |
|               [New Jersey](/us-nj) |           16,043 |                    16,233 |                   1,828 |                        190 |                       21 |                                        1% |                                16,054 |                                 16,884 |
|                  [Florida](/us-fl) |           12,787 |                    15,019 |                     699 |                      2,232 |                      104 |                                       17% |                                13,747 |                                 16,674 |
|            [Massachusetts](/us-ma) |            9,225 |                     9,591 |                   1,380 |                        366 |                       53 |                                        4% |                                 9,246 |                                 10,306 |
|                 [Illinois](/us-il) |            8,564 |                     9,320 |                     736 |                        756 |                       60 |                                        9% |                                 8,646 |                                 10,350 |
|             [Pennsylvania](/us-pa) |            7,860 |                     8,339 |                     651 |                        479 |                       37 |                                        6% |                                 7,882 |                                  9,328 |
|                  [Georgia](/us-ga) |            6,397 |                     7,617 |                     717 |                      1,220 |                      115 |                                       19% |                                 6,934 |                                  8,616 |
|                 [Michigan](/us-mi) |            6,932 |                     7,372 |                     738 |                        440 |                       44 |                                        6% |                                 6,986 |                                  8,019 |
|                [Louisiana](/us-la) |            5,278 |                     5,827 |                   1,254 |                        549 |                      118 |                                       10% |                                 5,489 |                                  6,394 |
|                  [Arizona](/us-az) |            5,344 |                     5,694 |                     782 |                        350 |                       48 |                                        7% |                                 5,456 |                                  6,061 |
|                     [Ohio](/us-oh) |            4,506 |                     5,427 |                     464 |                        921 |                       79 |                                       20% |                                 4,732 |                                  6,605 |
|              [Connecticut](/us-ct) |            4,485 |                     4,563 |                   1,280 |                         78 |                       22 |                                        2% |                                 4,496 |                                  4,796 |
|                 [Maryland](/us-md) |            3,849 |                     4,104 |                     679 |                        255 |                       42 |                                        7% |                                 3,869 |                                  4,569 |
|           [North Carolina](/us-nc) |            3,111 |                     4,052 |                     386 |                        941 |                       90 |                                       30% |                                 3,556 |                                  4,882 |
|                  [Indiana](/us-in) |            3,460 |                     3,888 |                     577 |                        428 |                       64 |                                       12% |                                 3,492 |                                  4,642 |
|           [South Carolina](/us-sc) |            3,098 |                     3,760 |                     730 |                        662 |                      129 |                                       21% |                                 3,431 |                                  4,243 |
|                 [Virginia](/us-va) |            2,837 |                     3,551 |                     416 |                        714 |                       84 |                                       25% |                                 3,020 |                                  4,356 |
|              [Mississippi](/us-ms) |            2,734 |                     3,175 |                   1,067 |                        441 |                      148 |                                       16% |                                 2,903 |                                  3,591 |
|                  [Alabama](/us-al) |            2,521 |                     2,979 |                     608 |                        458 |                       93 |                                       18% |                                 2,716 |                                  3,399 |
|                [Tennessee](/us-tn) |            2,127 |                     2,962 |                     433 |                        835 |                      122 |                                       39% |                                 2,560 |                                  3,587 |
|               [Washington](/us-wa) |            2,015 |                     2,303 |                     302 |                        288 |                       38 |                                       14% |                                 2,063 |                                  2,723 |
|                [Minnesota](/us-mn) |            1,979 |                     2,296 |                     407 |                        317 |                       56 |                                       16% |                                 2,033 |                                  2,732 |
|                 [Missouri](/us-mo) |            1,756 |                     2,281 |                     372 |                        525 |                       86 |                                       30% |                                 1,976 |                                  2,771 |
|                 [Colorado](/us-co) |            1,996 |                     2,136 |                     371 |                        140 |                       24 |                                        7% |                                 2,006 |                                  2,521 |
|                   [Nevada](/us-nv) |            1,482 |                     1,691 |                     549 |                        209 |                       68 |                                       14% |                                 1,574 |                                  1,850 |
|                     [Iowa](/us-ia) |            1,234 |                     1,592 |                     505 |                        358 |                      114 |                                       29% |                                 1,366 |                                  1,947 |
|                 [Arkansas](/us-ar) |            1,150 |                     1,572 |                     521 |                        422 |                      140 |                                       37% |                                 1,371 |                                  1,857 |
|                [Wisconsin](/us-wi) |            1,220 |                     1,540 |                     264 |                        320 |                       55 |                                       26% |                                 1,343 |                                  1,865 |
|                 [Kentucky](/us-ky) |            1,074 |                     1,434 |                     321 |                        360 |                       81 |                                       34% |                                 1,222 |                                  1,751 |
|                 [Oklahoma](/us-ok) |              912 |                     1,228 |                     310 |                        316 |                       80 |                                       35% |                                 1,061 |                                  1,512 |
|             [Rhode Island](/us-ri) |            1,078 |                     1,138 |                   1,074 |                         60 |                       56 |                                        6% |                                 1,085 |                                  1,267 |
|               [New Mexico](/us-nm) |              830 |                       958 |                     457 |                        128 |                       61 |                                       15% |                                   870 |                                  1,093 |
|              [Puerto Rico](/us-pr) |              551 |                       875 |                     274 |                        324 |                      101 |                                       59% |                                   712 |                                  1,126 |
|                   [Kansas](/us-ks) |              557 |                       775 |                     266 |                        218 |                       75 |                                       39% |                                   647 |                                    986 |
|                   [Oregon](/us-or) |              519 |                       681 |                     162 |                        162 |                       39 |                                       31% |                                   585 |                                    828 |
|                 [Delaware](/us-de) |              618 |                       655 |                     672 |                         37 |                       38 |                                        6% |                                   622 |                                    726 |
|     [District of Columbia](/us-dc) |              616 |                       637 |                     903 |                         21 |                       30 |                                        3% |                                   619 |                                    678 |
|                    [Idaho](/us-id) |              423 |                       578 |                     323 |                        155 |                       86 |                                       37% |                                   502 |                                    685 |
|                 [Nebraska](/us-ne) |              436 |                       551 |                     285 |                        115 |                       59 |                                       26% |                                   470 |                                    682 |
|                     [Utah](/us-ut) |              436 |                       549 |                     171 |                        113 |                       35 |                                       26% |                                   484 |                                    639 |
|            [New Hampshire](/us-nh) |              438 |                       461 |                     339 |                         23 |                       17 |                                        5% |                                   440 |                                    521 |
|            [West Virginia](/us-wv) |              283 |                       460 |                     257 |                        177 |                       99 |                                       63% |                                   365 |                                    620 |
|             [South Dakota](/us-sd) |              184 |                       254 |                     287 |                         70 |                       79 |                                       38% |                                   193 |                                    382 |
|             [North Dakota](/us-nd) |              172 |                       247 |                     325 |                         75 |                       99 |                                       44% |                                   205 |                                    313 |
|                  [Montana](/us-mt) |              140 |                       241 |                     225 |                        101 |                       94 |                                       72% |                                   191 |                                    325 |
|                   [Hawaii](/us-hi) |              100 |                       170 |                     120 |                         70 |                       49 |                                       70% |                                   134 |                                    224 |
|                    [Maine](/us-me) |              137 |                       152 |                     113 |                         15 |                       11 |                                       11% |                                   140 |                                    174 |
|                     [Guam](/us-gu) |               28 |                        72 |                     432 |                         44 |                      263 |                                      155% |                                    51 |                                    106 |
|                   [Alaska](/us-ak) |               44 |                        68 |                      92 |                         24 |                       32 |                                       54% |                                    55 |                                     88 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     77 |
|                  [Wyoming](/us-wy) |               42 |                        57 |                      99 |                         15 |                       26 |                                       36% |                                    49 |                                     70 |
|           [Virgin Islands](/us-vi) |               19 |                        28 |                     268 |                          9 |                       87 |                                       48% |                                    23 |                                     35 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      48 |                          1 |                       12 |                                       33% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          192,889 |                   208,991 |                     352 |                     16,102 |                       27 |                                        8% |                               196,671 |                                243,868 |
| [United Kingdom](/united-kingdom) |           41,753 |                    42,789 |                     634 |                      1,036 |                       15 |                                        2% |                                41,773 |                                 47,090 |
|                   [Italy](/italy) |           35,633 |                    36,534 |                     605 |                        901 |                       15 |                                        3% |                                35,650 |                                 40,592 |
|                   [Spain](/spain) |           30,004 |                    34,971 |                     745 |                      4,967 |                      106 |                                       17% |                                31,085 |                                 43,835 |
|                 [France](/france) |           31,007 |                    32,898 |                     491 |                      1,891 |                       28 |                                        6% |                                31,055 |                                 40,900 |
|               [Belgium](/belgium) |            9,930 |                    10,089 |                     881 |                        159 |                       14 |                                        2% |                                 9,945 |                                 10,625 |
|               [Germany](/germany) |            9,367 |                     9,652 |                     116 |                        285 |                        3 |                                        3% |                                 9,379 |                                 10,708 |
|       [Netherlands](/netherlands) |            6,300 |                     6,503 |                     376 |                        203 |                       12 |                                        3% |                                 6,312 |                                  7,185 |
|                 [Sweden](/sweden) |            5,851 |                     5,911 |                     578 |                         60 |                        6 |                                        1% |                                 5,856 |                                  6,103 |
|               [Ukraine](/ukraine) |            3,326 |                     5,870 |                     133 |                      2,544 |                       58 |                                       76% |                                 4,383 |                                  8,282 |
|               [Romania](/romania) |            4,236 |                     5,820 |                     300 |                      1,584 |                       82 |                                       37% |                                 4,937 |                                  7,227 |
|                 [Poland](/poland) |            2,227 |                     2,569 |                      68 |                        342 |                        9 |                                       15% |                                 2,330 |                                  2,916 |
|       [Switzerland](/switzerland) |            2,028 |                     2,113 |                     246 |                         85 |                       10 |                                        4% |                                 2,040 |                                  2,323 |
|             [Portugal](/portugal) |            1,875 |                     2,026 |                     197 |                        151 |                       15 |                                        8% |                                 1,883 |                                  2,395 |
|               [Ireland](/ireland) |            1,787 |                     1,823 |                     372 |                         36 |                        7 |                                        2% |                                 1,793 |                                  1,932 |
|               [Moldova](/moldova) |            1,143 |                     1,504 |                     372 |                        361 |                       89 |                                       32% |                                 1,289 |                                  1,879 |
|             [Bulgaria](/bulgaria) |              736 |                     1,038 |                     148 |                        302 |                       43 |                                       41% |                                   877 |                                  1,291 |
|               [Belarus](/belarus) |              761 |                     1,020 |                     108 |                        259 |                       27 |                                       34% |                                   846 |                                  1,397 |
|               [Austria](/austria) |              757 |                       830 |                      94 |                         73 |                        8 |                                       10% |                                   771 |                                    984 |
|                 [Serbia](/serbia) |              735 |                       796 |                     114 |                         61 |                        9 |                                        8% |                                   758 |                                    855 |
|               [Hungary](/hungary) |              646 |                       753 |                      77 |                        107 |                       11 |                                       17% |                                   664 |                                    937 |
|               [Denmark](/denmark) |              633 |                       671 |                     116 |                         38 |                        7 |                                        6% |                                   641 |                                    764 |
|               [Czechia](/czechia) |              476 |                       666 |                      63 |                        190 |                       18 |                                       40% |                                   540 |                                    904 |
|                 [Greece](/greece) |              313 |                       486 |                      45 |                        173 |                       16 |                                       55% |                                   385 |                                    672 |
|               [Croatia](/croatia) |              230 |                       408 |                     100 |                        178 |                       44 |                                       77% |                                   312 |                                    609 |
|               [Finland](/finland) |              339 |                       356 |                      64 |                         17 |                        3 |                                        5% |                                   342 |                                    405 |
|                 [Norway](/norway) |              265 |                       281 |                      52 |                         16 |                        3 |                                        6% |                                   269 |                                    320 |
|             [Slovenia](/slovenia) |              135 |                       150 |                      72 |                         15 |                        7 |                                       11% |                                   137 |                                    180 |
|         [Luxembourg](/luxembourg) |              124 |                       139 |                     226 |                         15 |                       24 |                                       12% |                                   129 |                                    159 |
|           [Lithuania](/lithuania) |               87 |                        96 |                      34 |                          9 |                        3 |                                       10% |                                    89 |                                    111 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        7% |                                    66 |                                     74 |
|             [Slovakia](/slovakia) |               38 |                        50 |                       9 |                         12 |                        2 |                                       33% |                                    42 |                                     69 |
|                 [Latvia](/latvia) |               35 |                        40 |                      21 |                          5 |                        3 |                                       14% |                                    36 |                                     47 |
|                   [Malta](/malta) |               16 |                        32 |                      66 |                         16 |                       33 |                                      103% |                                    23 |                                     51 |
|                 [Cyprus](/cyprus) |               22 |                        28 |                      31 |                          6 |                        6 |                                       25% |                                    24 |                                     33 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       13% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          512,729 |                   665,296 |                     128 |                    152,567 |                       29 |                                       30% |                               575,367 |                                799,226 |
|                             [Brazil](/brazil) |          133,119 |                   159,831 |                     757 |                     26,712 |                      127 |                                       20% |                               146,471 |                                181,019 |
|                               [India](/india) |           82,066 |                   136,053 |                     100 |                     53,987 |                       40 |                                       66% |                               102,887 |                                174,062 |
|                             [Mexico](/mexico) |           71,678 |                    89,455 |                     701 |                     17,777 |                      139 |                                       25% |                                81,905 |                                 99,711 |
|                                 [Peru](/peru) |           30,812 |                    34,164 |                   1,051 |                      3,352 |                      103 |                                       11% |                                31,627 |                                 38,683 |
|                         [Colombia](/colombia) |           23,288 |                    29,975 |                     595 |                      6,687 |                      133 |                                       29% |                                26,713 |                                 35,814 |
|                                 [Iran](/iran) |           23,453 |                    27,826 |                     336 |                      4,373 |                       53 |                                       19% |                                24,924 |                                 32,941 |
|                             [Russia](/russia) |           18,723 |                    23,437 |                     161 |                      4,714 |                       32 |                                       25% |                                19,365 |                                 29,607 |
|                       [Argentina](/argentina) |           11,852 |                    19,871 |                     444 |                      8,019 |                      179 |                                       68% |                                15,275 |                                 25,535 |
|                 [South Africa](/south-africa) |           15,641 |                    18,485 |                     316 |                      2,844 |                       49 |                                       18% |                                16,854 |                                 21,452 |
|                               [Chile](/chile) |           12,040 |                    14,596 |                     770 |                      2,556 |                      135 |                                       21% |                                12,367 |                                 20,328 |
|                       [Indonesia](/indonesia) |            8,965 |                    13,192 |                      49 |                      4,227 |                       16 |                                       47% |                                10,771 |                                 18,302 |
|                           [Ecuador](/ecuador) |           10,963 |                    11,864 |                     683 |                        901 |                       52 |                                        8% |                                11,023 |                                 13,850 |
|                             [Canada](/canada) |            9,239 |                     9,522 |                     255 |                        283 |                        8 |                                        3% |                                 9,261 |                                 10,360 |
|                           [Bolivia](/bolivia) |            7,447 |                     9,352 |                     812 |                      1,905 |                      165 |                                       26% |                                 8,278 |                                 11,144 |
|                             [Turkey](/turkey) |            7,186 |                     8,913 |                     107 |                      1,727 |                       21 |                                       24% |                                 7,343 |                                 12,139 |
|                   [Philippines](/philippines) |            4,663 |                     8,000 |                      74 |                      3,337 |                       31 |                                       72% |                                 6,014 |                                 11,639 |
|                         [Pakistan](/pakistan) |            6,393 |                     6,580 |                      30 |                        187 |                        1 |                                        3% |                                 6,404 |                                  6,765 |
|                               [Egypt](/egypt) |            5,679 |                     6,522 |                      65 |                        843 |                        8 |                                       15% |                                 5,783 |                                  8,401 |
|                     [Bangladesh](/bangladesh) |            4,802 |                     6,331 |                      39 |                      1,529 |                        9 |                                       32% |                                 5,286 |                                  8,123 |
|                 [Saudi Arabia](/saudi-arabia) |            4,338 |                     5,427 |                     158 |                      1,089 |                       32 |                                       25% |                                 4,672 |                                  6,609 |
|                               [China](/china) |            4,736 |                     4,796 |                       3 |                         60 |                        0 |                                        1% |                                 4,736 |                                  5,274 |
|                           [Morocco](/morocco) |            1,648 |                     3,339 |                      92 |                      1,691 |                       46 |                                      103% |                                 2,252 |                                  4,909 |
|     [Dominican Republic](/dominican-republic) |            1,998 |                     2,744 |                     256 |                        746 |                       69 |                                       37% |                                 2,277 |                                  3,552 |
|                         [Honduras](/honduras) |            2,087 |                     2,674 |                     274 |                        587 |                       60 |                                       28% |                                 2,281 |                                  3,320 |
|                             [Panama](/panama) |            2,187 |                     2,560 |                     603 |                        373 |                       88 |                                       17% |                                 2,312 |                                  2,928 |
|                           [Algeria](/algeria) |            1,632 |                     1,926 |                      45 |                        294 |                        7 |                                       18% |                                 1,698 |                                  2,331 |
|                             [Israel](/israel) |            1,147 |                     1,862 |                     219 |                        715 |                       84 |                                       62% |                                 1,379 |                                  2,895 |
|                               [Japan](/japan) |            1,463 |                     1,831 |                      14 |                        368 |                        3 |                                       25% |                                 1,569 |                                  2,274 |
|                           [Nigeria](/nigeria) |            1,088 |                     1,243 |                       6 |                        155 |                        1 |                                       14% |                                 1,128 |                                  1,458 |
|                       [Australia](/australia) |              824 |                       999 |                      40 |                        175 |                        7 |                                       21% |                                   884 |                                  1,168 |
|                             [Kuwait](/kuwait) |              568 |                       684 |                     163 |                        116 |                       28 |                                       20% |                                   595 |                                    876 |
|                   [South Korea](/south-korea) |              367 |                       483 |                       9 |                        116 |                        2 |                                       32% |                                   377 |                                    723 |
| [United Arab Emirates](/united-arab-emirates) |              401 |                       480 |                      49 |                         79 |                        8 |                                       20% |                                   408 |                                    681 |
|                                 [Cuba](/cuba) |              108 |                       146 |                      13 |                         38 |                        3 |                                       35% |                                   118 |                                    206 |
|                         [Malaysia](/malaysia) |              128 |                       137 |                       4 |                          9 |                        0 |                                        7% |                                   130 |                                    147 |
