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

* **August 5:** We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *August 3:* View our [updated historical performance](/about/#historical-performance).
* *July 31:* We added lower and upper bounds to our reproduction number (Rt) estimates. You can now download these values for all of our projections [on GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections).
* *July 23:* We made a major update that tries to better account for the recent increase in cases and deaths. Read our update notes [on Twitter](https://twitter.com/youyanggu/status/1286421296474202115).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 7 (2pm ET):
<p align="center">
  Current Total: <b>160,101</b> deaths | Projected Total: <b>229,300 deaths by Nov 1, 2020</b> (Range: 202-268k)<br>
  Currently Infected: <b>1.9%</b> (1 in 53) | Total Infected: <b>12.5%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 7, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 20, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |         2% |         36% |        78% |         93% |        99% |
|              225,000 |         <1% |        <1% |         <1% |        10% |         28% |        48% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          3% |        11% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         1% |
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
|             *[United States](/us)* |          160,101 |                   229,286 |                     691 |                     69,185 |                                       43% |                               202,224 |                                267,905 |
|                 [New York](/us-ny) |           32,756 |                    33,370 |                   1,715 |                        614 |                                        2% |                                32,788 |                                 36,047 |
|               [California](/us-ca) |           10,021 |                    19,582 |                     496 |                      9,561 |                                       95% |                                14,288 |                                 27,118 |
|                    [Texas](/us-tx) |            8,569 |                    18,820 |                     649 |                     10,251 |                                      120% |                                14,014 |                                 24,942 |
|               [New Jersey](/us-nj) |           15,849 |                    16,693 |                   1,879 |                        844 |                                        5% |                                15,917 |                                 19,164 |
|                  [Florida](/us-fl) |            7,747 |                    15,843 |                     738 |                      8,096 |                                      105% |                                11,922 |                                 20,529 |
|            [Massachusetts](/us-ma) |            8,691 |                     9,928 |                   1,429 |                      1,237 |                                       14% |                                 8,807 |                                 12,579 |
|                 [Illinois](/us-il) |            7,791 |                     9,789 |                     772 |                      1,998 |                                       26% |                                 8,175 |                                 13,029 |
|             [Pennsylvania](/us-pa) |            7,282 |                     8,501 |                     664 |                      1,219 |                                       17% |                                 7,397 |                                 10,701 |
|                 [Michigan](/us-mi) |            6,506 |                     7,415 |                     742 |                        909 |                                       14% |                                 6,586 |                                  9,227 |
|                  [Arizona](/us-az) |            4,002 |                     6,909 |                     949 |                      2,907 |                                       73% |                                 5,443 |                                  8,729 |
|                  [Georgia](/us-ga) |            4,026 |                     6,785 |                     639 |                      2,759 |                                       69% |                                 5,173 |                                  9,157 |
|                [Louisiana](/us-la) |            4,146 |                     5,652 |                   1,216 |                      1,506 |                                       36% |                                 4,742 |                                  7,048 |
|                     [Ohio](/us-oh) |            3,618 |                     5,551 |                     475 |                      1,933 |                                       53% |                                 4,159 |                                  7,911 |
|                 [Maryland](/us-md) |            3,551 |                     4,847 |                     802 |                      1,296 |                                       36% |                                 3,755 |                                  7,493 |
|              [Connecticut](/us-ct) |            4,437 |                     4,578 |                   1,284 |                        141 |                                        3% |                                 4,460 |                                  4,887 |
|           [South Carolina](/us-sc) |            1,942 |                     4,283 |                     832 |                      2,341 |                                      121% |                                 3,120 |                                  5,730 |
|                  [Indiana](/us-in) |            3,013 |                     4,233 |                     629 |                      1,220 |                                       40% |                                 3,159 |                                  6,493 |
|                 [Virginia](/us-va) |            2,299 |                     4,224 |                     495 |                      1,925 |                                       84% |                                 2,627 |                                  7,604 |
|           [North Carolina](/us-nc) |            2,126 |                     4,023 |                     384 |                      1,897 |                                       89% |                                 2,865 |                                  5,808 |
|              [Mississippi](/us-ms) |            1,825 |                     3,393 |                   1,140 |                      1,568 |                                       86% |                                 2,512 |                                  4,639 |
|                  [Alabama](/us-al) |            1,714 |                     3,059 |                     624 |                      1,345 |                                       78% |                                 2,324 |                                  4,082 |
|               [Washington](/us-wa) |            1,653 |                     2,920 |                     383 |                      1,267 |                                       77% |                                 1,955 |                                  4,757 |
|                [Tennessee](/us-tn) |            1,186 |                     2,611 |                     382 |                      1,425 |                                      120% |                                 1,820 |                                  3,651 |
|                 [Colorado](/us-co) |            1,852 |                     2,548 |                     442 |                        696 |                                       38% |                                 1,978 |                                  3,842 |
|                [Minnesota](/us-mn) |            1,677 |                     2,297 |                     407 |                        620 |                                       37% |                                 1,777 |                                  3,425 |
|                 [Missouri](/us-mo) |            1,302 |                     2,254 |                     367 |                        952 |                                       73% |                                 1,555 |                                  3,465 |
|                [Wisconsin](/us-wi) |              978 |                     1,809 |                     311 |                        831 |                                       85% |                                 1,181 |                                  2,998 |
|                   [Nevada](/us-nv) |              900 |                     1,805 |                     586 |                        905 |                                      101% |                                 1,314 |                                  2,466 |
|                     [Iowa](/us-ia) |              912 |                     1,482 |                     470 |                        570 |                                       62% |                                 1,066 |                                  2,254 |
|                 [Kentucky](/us-ky) |              760 |                     1,339 |                     300 |                        579 |                                       76% |                                   930 |                                  2,135 |
|                 [Oklahoma](/us-ok) |              593 |                     1,322 |                     334 |                        729 |                                      123% |                                   860 |                                  2,015 |
|                 [Arkansas](/us-ar) |              515 |                     1,180 |                     391 |                        665 |                                      129% |                                   792 |                                  1,721 |
|             [Rhode Island](/us-ri) |            1,014 |                     1,126 |                   1,063 |                        112 |                                       11% |                                 1,035 |                                  1,301 |
|               [New Mexico](/us-nm) |              669 |                     1,101 |                     525 |                        432 |                                       65% |                                   799 |                                  1,633 |
|              [Puerto Rico](/us-pr) |              258 |                       926 |                     290 |                        668 |                                      259% |                                   488 |                                  1,701 |
|                   [Oregon](/us-or) |              339 |                       813 |                     193 |                        474 |                                      140% |                                   494 |                                  1,323 |
|                     [Utah](/us-ut) |              330 |                       777 |                     242 |                        447 |                                      135% |                                   489 |                                  1,212 |
|                    [Idaho](/us-id) |              223 |                       764 |                     427 |                        541 |                                      243% |                                   466 |                                  1,178 |
|                   [Kansas](/us-ks) |              378 |                       748 |                     257 |                        370 |                                       98% |                                   494 |                                  1,232 |
|                 [Delaware](/us-de) |              587 |                       670 |                     688 |                         83 |                                       14% |                                   601 |                                    809 |
|     [District of Columbia](/us-dc) |              587 |                       649 |                     920 |                         62 |                                       11% |                                   599 |                                    756 |
|            [New Hampshire](/us-nh) |              419 |                       574 |                     422 |                        155 |                                       37% |                                   437 |                                    875 |
|                 [Nebraska](/us-ne) |              340 |                       531 |                     275 |                        191 |                                       56% |                                   410 |                                    828 |
|            [West Virginia](/us-wv) |              124 |                       333 |                     186 |                        209 |                                      168% |                                   178 |                                    658 |
|             [South Dakota](/us-sd) |              141 |                       234 |                     265 |                         93 |                                       66% |                                   173 |                                    352 |
|                  [Montana](/us-mt) |               65 |                       225 |                     211 |                        160 |                                      247% |                                   122 |                                    388 |
|             [North Dakota](/us-nd) |              109 |                       210 |                     275 |                        101 |                                       92% |                                   139 |                                    340 |
|                    [Maine](/us-me) |              124 |                       196 |                     146 |                         72 |                                       58% |                                   142 |                                    323 |
|                   [Hawaii](/us-hi) |               29 |                       131 |                      92 |                        102 |                                      350% |                                    46 |                                    385 |
|                  [Vermont](/us-vt) |               58 |                        78 |                     125 |                         20 |                                       35% |                                    62 |                                    114 |
|                   [Alaska](/us-ak) |               25 |                        73 |                     100 |                         48 |                                      192% |                                    41 |                                    129 |
|                  [Wyoming](/us-wy) |               27 |                        43 |                      74 |                         16 |                                       58% |                                    33 |                                     57 |
|           [Virgin Islands](/us-vi) |                9 |                        29 |                     272 |                         20 |                                      217% |                                    16 |                                     52 |
|                     [Guam](/us-gu) |                5 |                         9 |                      52 |                          4 |                                       71% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       59% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,385 |                   209,153 |                     353 |                     19,768 |                                       10% |                               193,121 |                                253,844 |
| [United Kingdom](/united-kingdom) |           46,498 |                    50,803 |                     752 |                      4,305 |                                        9% |                                46,832 |                                 60,728 |
|                   [Italy](/italy) |           35,187 |                    35,641 |                     590 |                        454 |                                        1% |                                35,215 |                                 37,111 |
|                 [France](/france) |           30,308 |                    31,090 |                     464 |                        782 |                                        3% |                                30,335 |                                 35,330 |
|                   [Spain](/spain) |           28,500 |                    30,130 |                     642 |                      1,630 |                                        6% |                                28,546 |                                 37,348 |
|               [Belgium](/belgium) |            9,861 |                    10,230 |                     893 |                        369 |                                        4% |                                 9,893 |                                 11,886 |
|               [Germany](/germany) |            9,181 |                    10,003 |                     120 |                        822 |                                        9% |                                 9,221 |                                 12,579 |
|       [Netherlands](/netherlands) |            6,173 |                     6,384 |                     369 |                        211 |                                        3% |                                 6,188 |                                  7,200 |
|                 [Sweden](/sweden) |            5,766 |                     6,071 |                     593 |                        305 |                                        5% |                                 5,832 |                                  6,369 |
|               [Romania](/romania) |            2,566 |                     6,063 |                     312 |                      3,497 |                                      136% |                                 3,745 |                                 10,535 |
|               [Ukraine](/ukraine) |            1,846 |                     3,941 |                      90 |                      2,095 |                                      114% |                                 2,465 |                                  6,879 |
|                 [Poland](/poland) |            1,774 |                     3,025 |                      80 |                      1,251 |                                       71% |                                 1,989 |                                  5,134 |
|       [Switzerland](/switzerland) |            1,985 |                     2,086 |                     243 |                        101 |                                        5% |                                 1,998 |                                  2,495 |
|             [Portugal](/portugal) |            1,743 |                     2,032 |                     198 |                        289 |                                       17% |                                 1,756 |                                  2,694 |
|               [Ireland](/ireland) |            1,768 |                     1,843 |                     376 |                         75 |                                        4% |                                 1,780 |                                  2,048 |
|               [Moldova](/moldova) |              828 |                     1,433 |                     355 |                        605 |                                       73% |                                 1,055 |                                  2,135 |
|             [Bulgaria](/bulgaria) |              435 |                     1,368 |                     195 |                        933 |                                      215% |                                   724 |                                  2,765 |
|                 [Serbia](/serbia) |              621 |                     1,229 |                     177 |                        608 |                                       98% |                                   824 |                                  2,112 |
|               [Austria](/austria) |              719 |                       840 |                      95 |                        121 |                                       17% |                                   739 |                                  1,167 |
|               [Belarus](/belarus) |              580 |                       816 |                      86 |                        236 |                                       41% |                                   719 |                                  1,027 |
|               [Denmark](/denmark) |              617 |                       702 |                     121 |                         85 |                                       14% |                                   631 |                                    906 |
|               [Hungary](/hungary) |              600 |                       693 |                      71 |                         93 |                                       16% |                                   609 |                                    922 |
|               [Czechia](/czechia) |              390 |                       639 |                      60 |                        249 |                                       64% |                                   430 |                                  1,198 |
|               [Croatia](/croatia) |              155 |                       387 |                      95 |                        232 |                                      149% |                                   215 |                                    753 |
|               [Finland](/finland) |              331 |                       371 |                      67 |                         40 |                                       12% |                                   340 |                                    448 |
|                 [Greece](/greece) |              210 |                       319 |                      30 |                        109 |                                       52% |                                   232 |                                    525 |
|                 [Norway](/norway) |              256 |                       290 |                      54 |                         34 |                                       13% |                                   263 |                                    379 |
|         [Luxembourg](/luxembourg) |              119 |                       219 |                     356 |                        100 |                                       84% |                                   143 |                                    414 |
|             [Slovenia](/slovenia) |              125 |                       197 |                      95 |                         72 |                                       57% |                                   141 |                                    345 |
|           [Lithuania](/lithuania) |               81 |                       101 |                      36 |                         20 |                                       24% |                                    87 |                                    131 |
|               [Estonia](/estonia) |               63 |                        73 |                      55 |                         10 |                                       16% |                                    69 |                                     86 |
|                 [Latvia](/latvia) |               32 |                        41 |                      22 |                          9 |                                       29% |                                    34 |                                     58 |
|             [Slovakia](/slovakia) |               29 |                        39 |                       7 |                         10 |                                       36% |                                    30 |                                     65 |
|                 [Cyprus](/cyprus) |               19 |                        26 |                      30 |                          7 |                                       37% |                                    21 |                                     35 |
|               [Iceland](/iceland) |               10 |                        14 |                      40 |                          4 |                                       36% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       29% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          343,045 |                   666,812 |                     128 |                    323,767 |                                       94% |                               464,931 |                                989,041 |
|                             [Brazil](/brazil) |           98,493 |                   184,526 |                     874 |                     86,033 |                                       87% |                               128,612 |                                261,982 |
|                               [India](/india) |           41,585 |                   123,507 |                      90 |                     81,922 |                                      197% |                                73,664 |                                179,509 |
|                             [Mexico](/mexico) |           50,517 |                    91,131 |                     714 |                     40,614 |                                       80% |                                72,931 |                                129,394 |
|                         [Colombia](/colombia) |           11,939 |                    32,931 |                     654 |                     20,992 |                                      176% |                                20,881 |                                 51,870 |
|                                 [Peru](/peru) |           20,228 |                    28,844 |                     887 |                      8,616 |                                       43% |                                22,202 |                                 41,375 |
|                                 [Iran](/iran) |           17,976 |                    28,512 |                     344 |                     10,536 |                                       59% |                                21,853 |                                 40,431 |
|                 [South Africa](/south-africa) |            9,604 |                    25,384 |                     433 |                     15,780 |                                      164% |                                16,747 |                                 37,210 |
|                             [Russia](/russia) |           14,579 |                    22,065 |                     151 |                      7,486 |                                       51% |                                16,176 |                                 33,782 |
|                       [Argentina](/argentina) |            4,251 |                    15,198 |                     339 |                     10,947 |                                      258% |                                 8,222 |                                 24,987 |
|                               [Chile](/chile) |            9,889 |                    14,051 |                     741 |                      4,162 |                                       42% |                                10,616 |                                 24,603 |
|                       [Indonesia](/indonesia) |            5,521 |                    12,272 |                      45 |                      6,751 |                                      122% |                                 7,669 |                                 22,800 |
|                             [Canada](/canada) |            9,013 |                     9,459 |                     253 |                        446 |                                        5% |                                 9,053 |                                 10,529 |
|                           [Bolivia](/bolivia) |            3,465 |                     8,204 |                     713 |                      4,739 |                                      137% |                                 5,122 |                                 13,413 |
|                           [Ecuador](/ecuador) |            5,877 |                     7,413 |                     427 |                      1,536 |                                       26% |                                 6,085 |                                 10,358 |
|                         [Pakistan](/pakistan) |            6,035 |                     7,185 |                      33 |                      1,150 |                                       19% |                                 6,243 |                                  8,630 |
|                             [Turkey](/turkey) |            5,798 |                     7,137 |                      86 |                      1,339 |                                       23% |                                 5,913 |                                 10,454 |
|                               [Egypt](/egypt) |            4,951 |                     6,561 |                      65 |                      1,610 |                                       33% |                                 5,139 |                                  8,946 |
|                     [Bangladesh](/bangladesh) |            3,306 |                     5,542 |                      34 |                      2,236 |                                       68% |                                 4,074 |                                  8,995 |
|                               [China](/china) |            4,680 |                     5,088 |                       4 |                        408 |                                        9% |                                 4,680 |                                  7,787 |
|                   [Philippines](/philippines) |            2,150 |                     4,951 |                      46 |                      2,801 |                                      130% |                                 2,448 |                                 11,208 |
|                 [Saudi Arabia](/saudi-arabia) |            3,055 |                     4,857 |                     142 |                      1,802 |                                       59% |                                 3,619 |                                  7,095 |
|                         [Honduras](/honduras) |            1,446 |                     3,310 |                     340 |                      1,864 |                                      129% |                                 2,018 |                                  6,075 |
|                             [Panama](/panama) |            1,574 |                     3,124 |                     736 |                      1,550 |                                       98% |                                 2,129 |                                  4,892 |
|                           [Morocco](/morocco) |              449 |                     3,028 |                      83 |                      2,579 |                                      574% |                                   917 |                                  7,637 |
|     [Dominican Republic](/dominican-republic) |            1,246 |                     2,431 |                     226 |                      1,185 |                                       95% |                                 1,611 |                                  4,238 |
|                           [Algeria](/algeria) |            1,273 |                     2,341 |                      54 |                      1,068 |                                       84% |                                 1,464 |                                  4,422 |
|                               [Japan](/japan) |            1,034 |                     1,750 |                      14 |                        716 |                                       69% |                                 1,051 |                                  4,680 |
|                             [Israel](/israel) |              576 |                     1,513 |                     178 |                        937 |                                      163% |                                   828 |                                  3,221 |
|                           [Nigeria](/nigeria) |              930 |                     1,412 |                       7 |                        482 |                                       52% |                                 1,046 |                                  2,546 |
|                       [Australia](/australia) |              266 |                     1,153 |                      46 |                        887 |                                      333% |                                   509 |                                  2,560 |
|                             [Kuwait](/kuwait) |              469 |                       833 |                     198 |                        364 |                                       78% |                                   516 |                                  1,710 |
| [United Arab Emirates](/united-arab-emirates) |              354 |                       455 |                      47 |                        101 |                                       28% |                                   361 |                                    744 |
|                   [South Korea](/south-korea) |              303 |                       376 |                       7 |                         73 |                                       24% |                                   303 |                                    621 |
|                         [Malaysia](/malaysia) |              125 |                       150 |                       5 |                         25 |                                       20% |                                   135 |                                    169 |
|                                 [Cuba](/cuba) |               88 |                       116 |                      10 |                         28 |                                       32% |                                    94 |                                    168 |
