We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are infectious, we recommend dividing the "currently infected" number by half.

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

* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* **August 25:** In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 29 (3pm ET):
<p align="center">
  Current Total: <b>181,797</b> deaths | Projected Total: <b>220,300 deaths by Nov 1, 2020</b> (Range: 205-241k)<br>
  Currently Infected: <b>1.3%</b> (1 in 80) | Total Infected: <b>14.2%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 28, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          7% |        88% |         99% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          5% |        23% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |        <1% |

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
|             *[United States](/us)* |          181,797 |                   220,299 |                     664 |                     38,502 |                      116 |                                       21% |                               205,906 |                                240,627 |
|                 [New York](/us-ny) |           32,934 |                    33,134 |                   1,703 |                        200 |                       10 |                                        1% |                                32,944 |                                 34,111 |
|                    [Texas](/us-tx) |           12,537 |                    18,730 |                     646 |                      6,193 |                      214 |                                       49% |                                15,924 |                                 22,284 |
|               [California](/us-ca) |           12,805 |                    18,587 |                     470 |                      5,782 |                      146 |                                       45% |                                15,478 |                                 23,497 |
|               [New Jersey](/us-nj) |           15,930 |                    16,065 |                   1,809 |                        135 |                       15 |                                        1% |                                15,945 |                                 16,480 |
|                  [Florida](/us-fl) |           10,957 |                    14,333 |                     667 |                      3,376 |                      157 |                                       31% |                                12,679 |                                 16,501 |
|            [Massachusetts](/us-ma) |            9,024 |                     9,698 |                   1,395 |                        674 |                       97 |                                        7% |                                 9,092 |                                 11,004 |
|                 [Illinois](/us-il) |            8,206 |                     9,333 |                     736 |                      1,127 |                       89 |                                       14% |                                 8,337 |                                 11,017 |
|             [Pennsylvania](/us-pa) |            7,642 |                     8,444 |                     660 |                        802 |                       63 |                                       11% |                                 7,687 |                                 10,058 |
|                  [Georgia](/us-ga) |            5,471 |                     7,622 |                     718 |                      2,151 |                      203 |                                       39% |                                 6,533 |                                  9,281 |
|                 [Michigan](/us-mi) |            6,712 |                     7,229 |                     724 |                        517 |                       52 |                                        8% |                                 6,762 |                                  8,126 |
|                  [Arizona](/us-az) |            4,978 |                     6,002 |                     825 |                      1,024 |                      141 |                                       21% |                                 5,428 |                                  6,851 |
|                [Louisiana](/us-la) |            4,904 |                     5,904 |                   1,270 |                      1,000 |                      215 |                                       20% |                                 5,324 |                                  6,820 |
|                     [Ohio](/us-oh) |            4,105 |                     4,960 |                     424 |                        855 |                       73 |                                       21% |                                 4,312 |                                  6,030 |
|              [Connecticut](/us-ct) |            4,465 |                     4,533 |                   1,271 |                         68 |                       19 |                                        2% |                                 4,476 |                                  4,732 |
|                 [Maryland](/us-md) |            3,727 |                     4,151 |                     687 |                        424 |                       70 |                                       11% |                                 3,769 |                                  4,977 |
|                  [Indiana](/us-in) |            3,277 |                     4,072 |                     605 |                        795 |                      118 |                                       24% |                                 3,376 |                                  5,217 |
|           [North Carolina](/us-nc) |            2,652 |                     3,863 |                     368 |                      1,211 |                      115 |                                       46% |                                 3,200 |                                  5,005 |
|           [South Carolina](/us-sc) |            2,655 |                     3,770 |                     732 |                      1,115 |                      217 |                                       42% |                                 3,204 |                                  4,611 |
|              [Mississippi](/us-ms) |            2,413 |                     3,241 |                   1,089 |                        828 |                      278 |                                       34% |                                 2,802 |                                  3,886 |
|                 [Virginia](/us-va) |            2,550 |                     3,171 |                     372 |                        621 |                       73 |                                       24% |                                 2,595 |                                  4,119 |
|                [Tennessee](/us-tn) |            1,701 |                     2,803 |                     410 |                      1,102 |                      161 |                                       65% |                                 2,252 |                                  3,616 |
|                  [Alabama](/us-al) |            2,107 |                     2,776 |                     566 |                        669 |                      137 |                                       32% |                                 2,432 |                                  3,343 |
|               [Washington](/us-wa) |            1,905 |                     2,583 |                     339 |                        678 |                       89 |                                       36% |                                 2,067 |                                  3,393 |
|                [Minnesota](/us-mn) |            1,859 |                     2,315 |                     411 |                        456 |                       81 |                                       25% |                                 1,936 |                                  2,958 |
|                 [Colorado](/us-co) |            1,937 |                     2,144 |                     372 |                        207 |                       36 |                                       11% |                                 1,951 |                                  2,713 |
|                 [Missouri](/us-mo) |            1,500 |                     2,046 |                     333 |                        546 |                       89 |                                       36% |                                 1,726 |                                  2,617 |
|                   [Nevada](/us-nv) |            1,287 |                     1,934 |                     628 |                        647 |                      210 |                                       50% |                                 1,613 |                                  2,380 |
|                     [Iowa](/us-ia) |            1,108 |                     1,657 |                     525 |                        549 |                      174 |                                       50% |                                 1,299 |                                  2,256 |
|                [Wisconsin](/us-wi) |            1,113 |                     1,544 |                     265 |                        431 |                       74 |                                       39% |                                 1,283 |                                  2,003 |
|                 [Kentucky](/us-ky) |              918 |                     1,348 |                     302 |                        430 |                       96 |                                       47% |                                 1,084 |                                  1,775 |
|                 [Oklahoma](/us-ok) |              786 |                     1,306 |                     330 |                        520 |                      131 |                                       66% |                                 1,016 |                                  1,785 |
|                 [Arkansas](/us-ar) |              756 |                     1,267 |                     420 |                        511 |                      169 |                                       68% |                                 1,001 |                                  1,647 |
|             [Rhode Island](/us-ri) |            1,046 |                     1,114 |                   1,052 |                         68 |                       65 |                                        7% |                                 1,056 |                                  1,246 |
|               [New Mexico](/us-nm) |              767 |                     1,028 |                     490 |                        261 |                      125 |                                       34% |                                   863 |                                  1,310 |
|              [Puerto Rico](/us-pr) |              424 |                       887 |                     278 |                        463 |                      145 |                                      109% |                                   651 |                                  1,290 |
|                   [Oregon](/us-or) |              447 |                       747 |                     177 |                        300 |                       71 |                                       67% |                                   570 |                                  1,051 |
|                 [Delaware](/us-de) |              604 |                       670 |                     689 |                         66 |                       68 |                                       11% |                                   612 |                                    793 |
|                    [Idaho](/us-id) |              353 |                       659 |                     369 |                        306 |                      171 |                                       87% |                                   508 |                                    891 |
|                   [Kansas](/us-ks) |              445 |                       648 |                     222 |                        203 |                       70 |                                       46% |                                   524 |                                    869 |
|     [District of Columbia](/us-dc) |              605 |                       646 |                     915 |                         41 |                       57 |                                        7% |                                   613 |                                    715 |
|                     [Utah](/us-ut) |              407 |                       613 |                     191 |                        206 |                       64 |                                       51% |                                   496 |                                    816 |
|                 [Nebraska](/us-ne) |              392 |                       528 |                     273 |                        136 |                       71 |                                       35% |                                   430 |                                    696 |
|            [New Hampshire](/us-nh) |              432 |                       470 |                     346 |                         38 |                       28 |                                        9% |                                   435 |                                    552 |
|            [West Virginia](/us-wv) |              201 |                       411 |                     229 |                        210 |                      117 |                                      104% |                                   290 |                                    622 |
|             [North Dakota](/us-nd) |              139 |                       239 |                     313 |                        100 |                      131 |                                       72% |                                   175 |                                    360 |
|             [South Dakota](/us-sd) |              165 |                       238 |                     269 |                         73 |                       82 |                                       44% |                                   183 |                                    319 |
|                  [Montana](/us-mt) |              100 |                       197 |                     184 |                         97 |                       90 |                                       97% |                                   141 |                                    291 |
|                   [Hawaii](/us-hi) |               59 |                       174 |                     123 |                        115 |                       81 |                                      195% |                                   101 |                                    324 |
|                    [Maine](/us-me) |              132 |                       151 |                     112 |                         19 |                       14 |                                       15% |                                   136 |                                    178 |
|                   [Alaska](/us-ak) |               37 |                        78 |                     106 |                         41 |                       56 |                                      110% |                                    55 |                                    120 |
|                  [Vermont](/us-vt) |               58 |                        70 |                     113 |                         12 |                       20 |                                       21% |                                    60 |                                     96 |
|                  [Wyoming](/us-wy) |               37 |                        62 |                     107 |                         25 |                       43 |                                       68% |                                    47 |                                     91 |
|                     [Guam](/us-gu) |               10 |                        53 |                     317 |                         43 |                      257 |                                      425% |                                    23 |                                     97 |
|           [Virgin Islands](/us-vi) |               14 |                        47 |                     445 |                         33 |                      312 |                                      234% |                                    29 |                                     77 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      53 |                          1 |                       17 |                                       47% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,423 |                   203,863 |                     344 |                     15,440 |                      884 |                                        8% |                               191,870 |                                236,830 |
| [United Kingdom](/united-kingdom) |           41,573 |                    42,258 |                     626 |                        685 |                       10 |                                        2% |                                41,595 |                                 44,756 |
|                   [Italy](/italy) |           35,472 |                    36,137 |                     599 |                        665 |                       11 |                                        2% |                                35,500 |                                 38,694 |
|                 [France](/france) |           30,601 |                    32,088 |                     479 |                      1,487 |                       22 |                                        5% |                                30,647 |                                 38,056 |
|                   [Spain](/spain) |           29,011 |                    31,144 |                     664 |                      2,133 |                       45 |                                        7% |                                29,061 |                                 37,480 |
|               [Belgium](/belgium) |            9,886 |                    10,217 |                     892 |                        331 |                       29 |                                        3% |                                 9,918 |                                 11,411 |
|               [Germany](/germany) |            9,290 |                     9,839 |                     119 |                        549 |                        7 |                                        6% |                                 9,329 |                                 11,602 |
|       [Netherlands](/netherlands) |            6,247 |                     6,569 |                     380 |                        322 |                       19 |                                        5% |                                 6,270 |                                  7,807 |
|               [Romania](/romania) |            3,507 |                     6,278 |                     323 |                      2,771 |                      143 |                                       79% |                                 4,641 |                                  9,013 |
|                 [Sweden](/sweden) |            5,821 |                     5,910 |                     578 |                         89 |                        9 |                                        2% |                                 5,833 |                                  6,002 |
|               [Ukraine](/ukraine) |            2,499 |                     5,273 |                     120 |                      2,774 |                       63 |                                      111% |                                 3,454 |                                  8,679 |
|                 [Poland](/poland) |            2,018 |                     2,907 |                      77 |                        889 |                       23 |                                       44% |                                 2,288 |                                  4,042 |
|       [Switzerland](/switzerland) |            2,004 |                     2,108 |                     245 |                        104 |                       12 |                                        5% |                                 2,020 |                                  2,387 |
|             [Portugal](/portugal) |            1,815 |                     2,031 |                     198 |                        216 |                       21 |                                       12% |                                 1,823 |                                  2,520 |
|               [Ireland](/ireland) |            1,777 |                     1,840 |                     375 |                         63 |                       13 |                                        4% |                                 1,786 |                                  2,020 |
|               [Moldova](/moldova) |              981 |                     1,376 |                     340 |                        395 |                       98 |                                       40% |                                 1,130 |                                  1,862 |
|             [Bulgaria](/bulgaria) |              603 |                     1,249 |                     178 |                        646 |                       92 |                                      107% |                                   833 |                                  2,013 |
|                 [Serbia](/serbia) |              709 |                       908 |                     130 |                        199 |                       29 |                                       28% |                                   787 |                                  1,078 |
|               [Belarus](/belarus) |              667 |                       861 |                      91 |                        194 |                       21 |                                       29% |                                   768 |                                  1,000 |
|               [Austria](/austria) |              733 |                       811 |                      91 |                         78 |                        9 |                                       11% |                                   749 |                                    992 |
|               [Denmark](/denmark) |              624 |                       693 |                     119 |                         69 |                       12 |                                       11% |                                   639 |                                    845 |
|               [Hungary](/hungary) |              614 |                       676 |                      69 |                         62 |                        6 |                                       10% |                                   620 |                                    819 |
|               [Czechia](/czechia) |              419 |                       556 |                      52 |                        137 |                       13 |                                       33% |                                   449 |                                    769 |
|                 [Greece](/greece) |              259 |                       523 |                      49 |                        264 |                       25 |                                      102% |                                   348 |                                    882 |
|               [Finland](/finland) |              335 |                       367 |                      67 |                         32 |                        6 |                                       10% |                                   341 |                                    451 |
|                 [Norway](/norway) |              264 |                       301 |                      56 |                         37 |                        7 |                                       14% |                                   275 |                                    372 |
|               [Croatia](/croatia) |              180 |                       291 |                      71 |                        111 |                       27 |                                       62% |                                   217 |                                    429 |
|             [Slovenia](/slovenia) |              133 |                       163 |                      79 |                         30 |                       15 |                                       23% |                                   138 |                                    213 |
|         [Luxembourg](/luxembourg) |              124 |                       155 |                     252 |                         31 |                       50 |                                       25% |                                   134 |                                    194 |
|           [Lithuania](/lithuania) |               86 |                       114 |                      41 |                         28 |                       10 |                                       33% |                                    94 |                                    154 |
|               [Estonia](/estonia) |               64 |                        72 |                      54 |                          8 |                        6 |                                       13% |                                    68 |                                     84 |
|             [Slovakia](/slovakia) |               33 |                        46 |                       8 |                         13 |                        2 |                                       39% |                                    35 |                                     70 |
|                 [Latvia](/latvia) |               34 |                        45 |                      23 |                         11 |                        6 |                                       33% |                                    36 |                                     63 |
|                 [Cyprus](/cyprus) |               20 |                        26 |                      30 |                          6 |                        7 |                                       31% |                                    22 |                                     33 |
|                   [Malta](/malta) |               10 |                        15 |                      30 |                          5 |                       10 |                                       47% |                                    12 |                                     22 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        7 |                                       24% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          438,272 |                   644,563 |                     124 |                    206,291 |                    2,633 |                                       47% |                               518,583 |                                849,692 |
|                             [Brazil](/brazil) |          119,504 |                   169,024 |                     801 |                     49,520 |                      235 |                                       41% |                               139,265 |                                218,807 |
|                               [India](/india) |           62,550 |                   115,062 |                      84 |                     52,512 |                       38 |                                       84% |                                83,234 |                                154,452 |
|                             [Mexico](/mexico) |           63,146 |                    88,108 |                     691 |                     24,962 |                      196 |                                       40% |                                76,308 |                                109,298 |
|                                 [Peru](/peru) |           28,277 |                    34,799 |                   1,070 |                      6,522 |                      201 |                                       23% |                                30,051 |                                 42,580 |
|                         [Colombia](/colombia) |           18,766 |                    30,907 |                     614 |                     12,141 |                      241 |                                       65% |                                24,049 |                                 41,911 |
|                                 [Iran](/iran) |           21,249 |                    27,228 |                     328 |                      5,979 |                       72 |                                       28% |                                23,120 |                                 34,173 |
|                             [Russia](/russia) |           16,866 |                    21,899 |                     150 |                      5,033 |                       35 |                                       30% |                                18,348 |                                 28,749 |
|                 [South Africa](/south-africa) |           13,743 |                    20,861 |                     356 |                      7,118 |                      122 |                                       52% |                                16,154 |                                 28,369 |
|                       [Argentina](/argentina) |            8,271 |                    20,245 |                     452 |                     11,974 |                      267 |                                      145% |                                13,369 |                                 30,229 |
|                               [Chile](/chile) |           11,132 |                    13,858 |                     731 |                      2,726 |                      144 |                                       24% |                                11,617 |                                 19,780 |
|                       [Indonesia](/indonesia) |            7,169 |                    12,222 |                      45 |                      5,053 |                       19 |                                       70% |                                 8,966 |                                 18,153 |
|                             [Canada](/canada) |            9,155 |                     9,523 |                     255 |                        368 |                       10 |                                        4% |                                 9,196 |                                 10,343 |
|                           [Ecuador](/ecuador) |            6,504 |                     7,735 |                     445 |                      1,231 |                       71 |                                       19% |                                 6,637 |                                 10,336 |
|                           [Bolivia](/bolivia) |            4,846 |                     7,725 |                     671 |                      2,879 |                      250 |                                       59% |                                 5,997 |                                 10,321 |
|                             [Turkey](/turkey) |            6,245 |                     7,532 |                      90 |                      1,287 |                       15 |                                       21% |                                 6,358 |                                 10,565 |
|                   [Philippines](/philippines) |            3,325 |                     7,152 |                      66 |                      3,827 |                       35 |                                      115% |                                 4,436 |                                 12,253 |
|                         [Pakistan](/pakistan) |            6,283 |                     6,866 |                      32 |                        583 |                        3 |                                        9% |                                 6,354 |                                  7,763 |
|                     [Bangladesh](/bangladesh) |            4,174 |                     6,053 |                      37 |                      1,879 |                       12 |                                       45% |                                 4,952 |                                  8,759 |
|                               [Egypt](/egypt) |            5,362 |                     5,891 |                      59 |                        529 |                        5 |                                       10% |                                 5,430 |                                  6,824 |
|                 [Saudi Arabia](/saudi-arabia) |            3,813 |                     5,385 |                     157 |                      1,572 |                       46 |                                       41% |                                 4,270 |                                  6,961 |
|                               [China](/china) |            4,718 |                     4,810 |                       3 |                         92 |                        0 |                                        2% |                                 4,718 |                                  5,495 |
|                           [Morocco](/morocco) |            1,052 |                     3,508 |                      96 |                      2,456 |                       67 |                                      233% |                                 1,889 |                                  6,547 |
|                         [Honduras](/honduras) |            1,827 |                     2,794 |                     287 |                        967 |                       99 |                                       53% |                                 2,140 |                                  4,024 |
|                             [Panama](/panama) |            1,966 |                     2,639 |                     621 |                        673 |                      158 |                                       34% |                                 2,235 |                                  3,430 |
|     [Dominican Republic](/dominican-republic) |            1,648 |                     2,573 |                     240 |                        925 |                       86 |                                       56% |                                 1,971 |                                  3,756 |
|                           [Algeria](/algeria) |            1,483 |                     2,152 |                      50 |                        669 |                       16 |                                       45% |                                 1,601 |                                  3,352 |
|                               [Japan](/japan) |            1,251 |                     2,044 |                      16 |                        793 |                        6 |                                       63% |                                 1,401 |                                  3,562 |
|                             [Israel](/israel) |              894 |                     1,896 |                     223 |                      1,002 |                      118 |                                      112% |                                 1,205 |                                  3,132 |
|                           [Nigeria](/nigeria) |            1,011 |                     1,245 |                       6 |                        234 |                        1 |                                       23% |                                 1,055 |                                  1,735 |
|                       [Australia](/australia) |              600 |                     1,027 |                      41 |                        427 |                       17 |                                       71% |                                   774 |                                  1,403 |
|                             [Kuwait](/kuwait) |              525 |                       674 |                     160 |                        149 |                       35 |                                       28% |                                   549 |                                    984 |
| [United Arab Emirates](/united-arab-emirates) |              379 |                       459 |                      47 |                         80 |                        8 |                                       21% |                                   383 |                                    655 |
|                   [South Korea](/south-korea) |              321 |                       395 |                       8 |                         74 |                        1 |                                       23% |                                   321 |                                    617 |
|                         [Malaysia](/malaysia) |              125 |                       138 |                       4 |                         13 |                        0 |                                       10% |                                   128 |                                    152 |
|                                 [Cuba](/cuba) |               92 |                       134 |                      12 |                         42 |                        4 |                                       46% |                                   102 |                                    222 |
