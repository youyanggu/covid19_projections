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
### Updated Daily - Last Updated: August 8 (11am ET):
<p align="center">
  Current Total: <b>161,344</b> deaths | Projected Total: <b>231,400 deaths by Nov 1, 2020</b> (Range: 203-271k)<br>
  Currently Infected: <b>1.9%</b> (1 in 53) | Total Infected: <b>12.6%</b> (1 in 8) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 8, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 21, 2020 |
|              200,000 |        Sep 18, 2020 |

<br>

|   US deaths surpass: |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|
|              175,000 |         <1% |        99% |         99% |       >99% |        >99% |       >99% |
|              200,000 |         <1% |         2% |         42% |        84% |         96% |        99% |
|              225,000 |         <1% |        <1% |         <1% |        12% |         32% |        53% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |          4% |        13% |
|              275,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |
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
|             *[United States](/us)* |          161,344 |                   231,359 |                     697 |                     70,015 |                                       43% |                               203,628 |                                270,621 |
|                 [New York](/us-ny) |           32,760 |                    33,359 |                   1,715 |                        599 |                                        2% |                                32,792 |                                 35,979 |
|                    [Texas](/us-tx) |            8,847 |                    19,543 |                     674 |                     10,696 |                                      121% |                                14,438 |                                 26,168 |
|               [California](/us-ca) |           10,133 |                    19,151 |                     485 |                      9,018 |                                       89% |                                13,807 |                                 26,475 |
|                  [Florida](/us-fl) |            7,927 |                    16,767 |                     781 |                      8,840 |                                      112% |                                12,267 |                                 22,488 |
|               [New Jersey](/us-nj) |           15,849 |                    16,668 |                   1,877 |                        819 |                                        5% |                                15,915 |                                 19,106 |
|            [Massachusetts](/us-ma) |            8,709 |                     9,945 |                   1,431 |                      1,236 |                                       14% |                                 8,828 |                                 12,560 |
|                 [Illinois](/us-il) |            7,822 |                     9,872 |                     779 |                      2,050 |                                       26% |                                 8,203 |                                 13,096 |
|             [Pennsylvania](/us-pa) |            7,296 |                     8,498 |                     664 |                      1,202 |                                       16% |                                 7,408 |                                 10,672 |
|                 [Michigan](/us-mi) |            6,524 |                     7,466 |                     748 |                        942 |                                       14% |                                 6,604 |                                  9,279 |
|                  [Georgia](/us-ga) |            4,117 |                     7,171 |                     675 |                      3,054 |                                       74% |                                 5,405 |                                  9,825 |
|                  [Arizona](/us-az) |            4,081 |                     6,956 |                     956 |                      2,875 |                                       70% |                                 5,501 |                                  8,734 |
|                [Louisiana](/us-la) |            4,207 |                     5,732 |                   1,233 |                      1,525 |                                       36% |                                 4,813 |                                  7,107 |
|                     [Ohio](/us-oh) |            3,652 |                     5,599 |                     479 |                      1,947 |                                       53% |                                 4,207 |                                  7,919 |
|                 [Maryland](/us-md) |            3,565 |                     4,855 |                     803 |                      1,290 |                                       36% |                                 3,767 |                                  7,460 |
|              [Connecticut](/us-ct) |            4,441 |                     4,581 |                   1,285 |                        140 |                                        3% |                                 4,464 |                                  4,887 |
|                 [Virginia](/us-va) |            2,317 |                     4,238 |                     497 |                      1,921 |                                       83% |                                 2,644 |                                  7,559 |
|                  [Indiana](/us-in) |            3,023 |                     4,229 |                     628 |                      1,206 |                                       40% |                                 3,169 |                                  6,411 |
|           [South Carolina](/us-sc) |            1,962 |                     4,189 |                     814 |                      2,227 |                                      113% |                                 3,067 |                                  5,565 |
|           [North Carolina](/us-nc) |            2,160 |                     4,081 |                     389 |                      1,921 |                                       89% |                                 2,916 |                                  5,858 |
|              [Mississippi](/us-ms) |            1,848 |                     3,354 |                   1,127 |                      1,506 |                                       81% |                                 2,512 |                                  4,521 |
|                  [Alabama](/us-al) |            1,735 |                     3,047 |                     621 |                      1,312 |                                       76% |                                 2,328 |                                  4,044 |
|               [Washington](/us-wa) |            1,672 |                     2,963 |                     389 |                      1,291 |                                       77% |                                 1,993 |                                  4,770 |
|                [Tennessee](/us-tn) |            1,206 |                     2,622 |                     384 |                      1,416 |                                      117% |                                 1,844 |                                  3,644 |
|                 [Colorado](/us-co) |            1,857 |                     2,540 |                     441 |                        683 |                                       37% |                                 1,982 |                                  3,805 |
|                 [Missouri](/us-mo) |            1,324 |                     2,351 |                     383 |                      1,027 |                                       78% |                                 1,614 |                                  3,626 |
|                [Minnesota](/us-mn) |            1,681 |                     2,289 |                     406 |                        608 |                                       36% |                                 1,778 |                                  3,391 |
|                [Wisconsin](/us-wi) |              990 |                     1,844 |                     317 |                        854 |                                       86% |                                 1,211 |                                  3,010 |
|                   [Nevada](/us-nv) |              920 |                     1,833 |                     595 |                        913 |                                       99% |                                 1,340 |                                  2,495 |
|                     [Iowa](/us-ia) |              915 |                     1,463 |                     464 |                        548 |                                       60% |                                 1,065 |                                  2,176 |
|                 [Kentucky](/us-ky) |              764 |                     1,318 |                     295 |                        554 |                                       73% |                                   929 |                                  2,088 |
|                 [Oklahoma](/us-ok) |              600 |                     1,312 |                     332 |                        712 |                                      119% |                                   862 |                                  1,980 |
|                 [Arkansas](/us-ar) |              521 |                     1,154 |                     383 |                        633 |                                      122% |                                   786 |                                  1,668 |
|             [Rhode Island](/us-ri) |            1,014 |                     1,125 |                   1,062 |                        111 |                                       11% |                                 1,035 |                                  1,298 |
|               [New Mexico](/us-nm) |              675 |                     1,103 |                     526 |                        428 |                                       63% |                                   805 |                                  1,614 |
|              [Puerto Rico](/us-pr) |              265 |                       932 |                     292 |                        667 |                                      252% |                                   501 |                                  1,679 |
|                   [Oregon](/us-or) |              348 |                       850 |                     201 |                        502 |                                      144% |                                   516 |                                  1,370 |
|                     [Utah](/us-ut) |              335 |                       772 |                     241 |                        437 |                                      130% |                                   492 |                                  1,184 |
|                    [Idaho](/us-id) |              229 |                       747 |                     418 |                        518 |                                      226% |                                   464 |                                  1,126 |
|                   [Kansas](/us-ks) |              379 |                       719 |                     247 |                        340 |                                       90% |                                   487 |                                  1,147 |
|                 [Delaware](/us-de) |              588 |                       670 |                     689 |                         82 |                                       14% |                                   602 |                                    808 |
|     [District of Columbia](/us-dc) |              589 |                       651 |                     922 |                         62 |                                       11% |                                   601 |                                    756 |
|            [New Hampshire](/us-nh) |              419 |                       569 |                     419 |                        150 |                                       36% |                                   437 |                                    860 |
|                 [Nebraska](/us-ne) |              345 |                       540 |                     279 |                        195 |                                       57% |                                   416 |                                    839 |
|            [West Virginia](/us-wv) |              127 |                       350 |                     196 |                        223 |                                      176% |                                   187 |                                    682 |
|                  [Montana](/us-mt) |               70 |                       264 |                     247 |                        194 |                                      277% |                                   142 |                                    449 |
|             [South Dakota](/us-sd) |              144 |                       240 |                     272 |                         96 |                                       67% |                                   178 |                                    358 |
|             [North Dakota](/us-nd) |              110 |                       210 |                     275 |                        100 |                                       91% |                                   140 |                                    336 |
|                   [Hawaii](/us-hi) |               31 |                       197 |                     139 |                        166 |                                      537% |                                    58 |                                    649 |
|                    [Maine](/us-me) |              124 |                       194 |                     145 |                         70 |                                       57% |                                   142 |                                    319 |
|                  [Vermont](/us-vt) |               58 |                        78 |                     125 |                         20 |                                       35% |                                    62 |                                    114 |
|                   [Alaska](/us-ak) |               25 |                        68 |                      93 |                         43 |                                      173% |                                    40 |                                    120 |
|                  [Wyoming](/us-wy) |               28 |                        48 |                      84 |                         20 |                                       73% |                                    35 |                                     74 |
|           [Virgin Islands](/us-vi) |                9 |                        26 |                     250 |                         17 |                                      192% |                                    15 |                                     46 |
|                     [Guam](/us-gu) |                5 |                         9 |                      51 |                          4 |                                       70% |                                     5 |                                     16 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      57 |                          1 |                                       58% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,655 |                   209,637 |                     353 |                     19,982 |                                       11% |                               193,552 |                                253,977 |
| [United Kingdom](/united-kingdom) |           46,596 |                    50,911 |                     754 |                      4,315 |                                        9% |                                46,924 |                                 60,833 |
|                   [Italy](/italy) |           35,190 |                    35,633 |                     590 |                        443 |                                        1% |                                35,217 |                                 37,077 |
|                 [France](/france) |           30,327 |                    31,107 |                     464 |                        780 |                                        3% |                                30,353 |                                 35,322 |
|                   [Spain](/spain) |           28,503 |                    30,095 |                     641 |                      1,592 |                                        6% |                                28,548 |                                 37,106 |
|               [Belgium](/belgium) |            9,866 |                    10,234 |                     893 |                        368 |                                        4% |                                 9,898 |                                 11,885 |
|               [Germany](/germany) |            9,195 |                    10,032 |                     121 |                        837 |                                        9% |                                 9,236 |                                 12,618 |
|       [Netherlands](/netherlands) |            6,174 |                     6,384 |                     369 |                        210 |                                        3% |                                 6,189 |                                  7,195 |
|               [Romania](/romania) |            2,616 |                     6,365 |                     328 |                      3,749 |                                      143% |                                 3,902 |                                 11,095 |
|                 [Sweden](/sweden) |            5,763 |                     6,058 |                     592 |                        295 |                                        5% |                                 5,826 |                                  6,351 |
|               [Ukraine](/ukraine) |            1,879 |                     4,185 |                      95 |                      2,306 |                                      123% |                                 2,560 |                                  7,267 |
|                 [Poland](/poland) |            1,787 |                     3,079 |                      81 |                      1,292 |                                       72% |                                 2,055 |                                  5,186 |
|       [Switzerland](/switzerland) |            1,986 |                     2,086 |                     243 |                        100 |                                        5% |                                 1,999 |                                  2,494 |
|             [Portugal](/portugal) |            1,746 |                     2,031 |                     198 |                        285 |                                       16% |                                 1,759 |                                  2,687 |
|               [Ireland](/ireland) |            1,772 |                     1,850 |                     377 |                         78 |                                        4% |                                 1,785 |                                  2,078 |
|               [Moldova](/moldova) |              835 |                     1,420 |                     351 |                        585 |                                       70% |                                 1,055 |                                  2,102 |
|             [Bulgaria](/bulgaria) |              442 |                     1,319 |                     188 |                        877 |                                      199% |                                   723 |                                  2,584 |
|                 [Serbia](/serbia) |              626 |                     1,176 |                     169 |                        550 |                                       88% |                                   818 |                                  1,890 |
|               [Austria](/austria) |              720 |                       840 |                      95 |                        120 |                                       17% |                                   740 |                                  1,166 |
|               [Belarus](/belarus) |              583 |                       814 |                      86 |                        231 |                                       40% |                                   718 |                                  1,022 |
|               [Hungary](/hungary) |              602 |                       700 |                      72 |                         98 |                                       16% |                                   611 |                                    939 |
|               [Denmark](/denmark) |              617 |                       699 |                     120 |                         82 |                                       13% |                                   631 |                                    902 |
|               [Czechia](/czechia) |              389 |                       588 |                      55 |                        199 |                                       51% |                                   422 |                                  1,019 |
|               [Finland](/finland) |              331 |                       370 |                      67 |                         39 |                                       12% |                                   340 |                                    445 |
|               [Croatia](/croatia) |              155 |                       346 |                      85 |                        191 |                                      123% |                                   210 |                                    654 |
|                 [Greece](/greece) |              210 |                       311 |                      29 |                        101 |                                       48% |                                   228 |                                    517 |
|                 [Norway](/norway) |              256 |                       290 |                      54 |                         34 |                                       13% |                                   262 |                                    379 |
|         [Luxembourg](/luxembourg) |              119 |                       205 |                     333 |                         86 |                                       72% |                                   140 |                                    386 |
|             [Slovenia](/slovenia) |              125 |                       191 |                      92 |                         66 |                                       53% |                                   139 |                                    324 |
|           [Lithuania](/lithuania) |               81 |                       100 |                      36 |                         19 |                                       23% |                                    86 |                                    128 |
|               [Estonia](/estonia) |               63 |                        73 |                      55 |                         10 |                                       16% |                                    69 |                                     86 |
|             [Slovakia](/slovakia) |               31 |                        54 |                      10 |                         23 |                                       73% |                                    35 |                                    112 |
|                 [Latvia](/latvia) |               32 |                        41 |                      21 |                          9 |                                       28% |                                    34 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        26 |                      30 |                          7 |                                       36% |                                    21 |                                     35 |
|               [Iceland](/iceland) |               10 |                        13 |                      40 |                          3 |                                       35% |                                    10 |                                     21 |
|                   [Malta](/malta) |                9 |                        11 |                      23 |                          2 |                                       27% |                                     9 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          347,789 |                   667,620 |                     129 |                    319,831 |                                       92% |                               465,431 |                                985,861 |
|                             [Brazil](/brazil) |           99,572 |                   182,666 |                     866 |                     83,094 |                                       83% |                               124,555 |                                258,814 |
|                               [India](/india) |           42,518 |                   124,156 |                      91 |                     81,638 |                                      192% |                                74,954 |                                179,590 |
|                             [Mexico](/mexico) |           51,311 |                    92,405 |                     724 |                     41,094 |                                       80% |                                73,470 |                                130,408 |
|                         [Colombia](/colombia) |           12,250 |                    32,657 |                     649 |                     20,407 |                                      167% |                                20,942 |                                 51,222 |
|                                 [Peru](/peru) |           20,649 |                    30,771 |                     947 |                     10,122 |                                       49% |                                24,258 |                                 44,692 |
|                                 [Iran](/iran) |           18,132 |                    28,258 |                     341 |                     10,126 |                                       56% |                                21,832 |                                 39,585 |
|                 [South Africa](/south-africa) |            9,909 |                    25,495 |                     435 |                     15,586 |                                      157% |                                16,745 |                                 37,285 |
|                             [Russia](/russia) |           14,698 |                    22,083 |                     151 |                      7,385 |                                       50% |                                16,460 |                                 33,483 |
|                       [Argentina](/argentina) |            4,411 |                    15,449 |                     345 |                     11,038 |                                      250% |                                 8,464 |                                 25,605 |
|                               [Chile](/chile) |            9,958 |                    14,079 |                     743 |                      4,121 |                                       41% |                                10,660 |                                 24,501 |
|                       [Indonesia](/indonesia) |            5,593 |                    12,056 |                      45 |                      6,463 |                                      116% |                                 7,697 |                                 21,928 |
|                             [Canada](/canada) |            9,017 |                     9,456 |                     253 |                        439 |                                        5% |                                 9,056 |                                 10,514 |
|                           [Bolivia](/bolivia) |            3,524 |                     7,960 |                     691 |                      4,436 |                                      126% |                                 5,077 |                                 13,016 |
|                           [Ecuador](/ecuador) |            5,897 |                     7,385 |                     425 |                      1,488 |                                       25% |                                 6,116 |                                 10,248 |
|                         [Pakistan](/pakistan) |            6,052 |                     7,163 |                      33 |                      1,111 |                                       18% |                                 6,247 |                                  8,578 |
|                             [Turkey](/turkey) |            5,813 |                     7,135 |                      86 |                      1,322 |                                       23% |                                 5,924 |                                 10,411 |
|                               [Egypt](/egypt) |            4,971 |                     6,523 |                      65 |                      1,552 |                                       31% |                                 5,145 |                                  8,880 |
|                     [Bangladesh](/bangladesh) |            3,333 |                     5,471 |                      34 |                      2,138 |                                       64% |                                 4,085 |                                  8,854 |
|                               [China](/china) |            4,681 |                     5,082 |                       4 |                        401 |                                        9% |                                 4,681 |                                  7,750 |
|                 [Saudi Arabia](/saudi-arabia) |            3,093 |                     4,907 |                     143 |                      1,814 |                                       59% |                                 3,655 |                                  7,105 |
|                   [Philippines](/philippines) |            2,168 |                     4,890 |                      45 |                      2,722 |                                      126% |                                 2,469 |                                 10,889 |
|                         [Honduras](/honduras) |            1,465 |                     3,211 |                     329 |                      1,746 |                                      119% |                                 2,001 |                                  5,872 |
|                             [Panama](/panama) |            1,591 |                     3,052 |                     719 |                      1,461 |                                       92% |                                 2,099 |                                  4,732 |
|                           [Morocco](/morocco) |              461 |                     2,885 |                      79 |                      2,424 |                                      526% |                                   911 |                                  7,400 |
|     [Dominican Republic](/dominican-republic) |            1,259 |                     2,404 |                     224 |                      1,145 |                                       91% |                                 1,611 |                                  4,200 |
|                           [Algeria](/algeria) |            1,282 |                     2,308 |                      54 |                      1,026 |                                       80% |                                 1,468 |                                  4,243 |
|                               [Japan](/japan) |            1,042 |                     1,779 |                      14 |                        737 |                                       71% |                                 1,059 |                                  4,762 |
|                             [Israel](/israel) |              581 |                     1,429 |                     168 |                        848 |                                      146% |                                   802 |                                  2,938 |
|                           [Nigeria](/nigeria) |              936 |                     1,403 |                       7 |                        467 |                                       50% |                                 1,051 |                                  2,406 |
|                       [Australia](/australia) |              278 |                     1,178 |                      47 |                        900 |                                      324% |                                   525 |                                  2,564 |
|                             [Kuwait](/kuwait) |              471 |                       820 |                     195 |                        349 |                                       74% |                                   516 |                                  1,676 |
| [United Arab Emirates](/united-arab-emirates) |              356 |                       458 |                      47 |                        102 |                                       29% |                                   363 |                                    747 |
|                   [South Korea](/south-korea) |              304 |                       379 |                       7 |                         75 |                                       25% |                                   304 |                                    626 |
|                         [Malaysia](/malaysia) |              125 |                       150 |                       5 |                         25 |                                       20% |                                   135 |                                    169 |
|                                 [Cuba](/cuba) |               88 |                       116 |                      10 |                         28 |                                       32% |                                    94 |                                    168 |
