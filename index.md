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

* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* **August 25:** In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 28 (12pm ET):
<p align="center">
  Current Total: <b>180,821</b> deaths | Projected Total: <b>220,000 deaths by Nov 1, 2020</b> (Range: 205-241k)<br>
  Currently Infected: <b>1.3%</b> (1 in 79) | Total Infected: <b>14.1%</b> (1 in 7) {% include iframe.html %}
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
|              200,000 |        <1% |          7% |        86% |         99% |        99% |
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
|             *[United States](/us)* |          180,821 |                   220,005 |                     663 |                     39,184 |                      118 |                                       22% |                               205,310 |                                240,749 |
|                 [New York](/us-ny) |           32,926 |                    33,131 |                   1,703 |                        205 |                       11 |                                        1% |                                32,936 |                                 34,132 |
|                    [Texas](/us-tx) |           12,365 |                    18,684 |                     644 |                      6,319 |                      218 |                                       51% |                                15,803 |                                 22,321 |
|               [California](/us-ca) |           12,677 |                    18,567 |                     470 |                      5,890 |                      149 |                                       46% |                                15,394 |                                 23,575 |
|               [New Jersey](/us-nj) |           15,921 |                    16,058 |                   1,808 |                        137 |                       15 |                                        1% |                                15,936 |                                 16,478 |
|                  [Florida](/us-fl) |           10,868 |                    14,375 |                     669 |                      3,507 |                      163 |                                       32% |                                12,657 |                                 16,591 |
|            [Massachusetts](/us-ma) |            9,008 |                     9,700 |                   1,396 |                        692 |                      100 |                                        8% |                                 9,078 |                                 11,040 |
|                 [Illinois](/us-il) |            8,186 |                     9,336 |                     737 |                      1,150 |                       91 |                                       14% |                                 8,321 |                                 11,103 |
|             [Pennsylvania](/us-pa) |            7,622 |                     8,432 |                     659 |                        810 |                       63 |                                       11% |                                 7,668 |                                 10,074 |
|                  [Georgia](/us-ga) |            5,393 |                     7,560 |                     712 |                      2,167 |                      204 |                                       40% |                                 6,466 |                                  9,242 |
|                 [Michigan](/us-mi) |            6,706 |                     7,244 |                     725 |                        538 |                       54 |                                        8% |                                 6,757 |                                  8,180 |
|                  [Arizona](/us-az) |            4,929 |                     5,975 |                     821 |                      1,046 |                      144 |                                       21% |                                 5,397 |                                  6,828 |
|                [Louisiana](/us-la) |            4,874 |                     5,905 |                   1,270 |                      1,031 |                      222 |                                       21% |                                 5,309 |                                  6,847 |
|                     [Ohio](/us-oh) |            4,076 |                     4,942 |                     423 |                        866 |                       74 |                                       21% |                                 4,290 |                                  6,029 |
|              [Connecticut](/us-ct) |            4,465 |                     4,535 |                   1,272 |                         70 |                       20 |                                        2% |                                 4,477 |                                  4,738 |
|                 [Maryland](/us-md) |            3,722 |                     4,158 |                     688 |                        436 |                       72 |                                       12% |                                 3,765 |                                  5,001 |
|                  [Indiana](/us-in) |            3,266 |                     4,081 |                     606 |                        815 |                      121 |                                       25% |                                 3,366 |                                  5,262 |
|           [North Carolina](/us-nc) |            2,630 |                     3,868 |                     369 |                      1,238 |                      118 |                                       47% |                                 3,189 |                                  5,037 |
|           [South Carolina](/us-sc) |            2,628 |                     3,777 |                     734 |                      1,149 |                      223 |                                       44% |                                 3,196 |                                  4,639 |
|              [Mississippi](/us-ms) |            2,399 |                     3,261 |                   1,096 |                        862 |                      290 |                                       36% |                                 2,804 |                                  3,931 |
|                 [Virginia](/us-va) |            2,527 |                     3,146 |                     369 |                        619 |                       73 |                                       25% |                                 2,573 |                                  4,110 |
|                [Tennessee](/us-tn) |            1,673 |                     2,777 |                     406 |                      1,104 |                      162 |                                       66% |                                 2,223 |                                  3,594 |
|                  [Alabama](/us-al) |            2,076 |                     2,736 |                     558 |                        660 |                      135 |                                       32% |                                 2,401 |                                  3,305 |
|               [Washington](/us-wa) |            1,890 |                     2,574 |                     338 |                        684 |                       90 |                                       36% |                                 2,047 |                                  3,404 |
|                [Minnesota](/us-mn) |            1,855 |                     2,327 |                     413 |                        472 |                       84 |                                       25% |                                 1,934 |                                  2,990 |
|                 [Colorado](/us-co) |            1,931 |                     2,140 |                     372 |                        209 |                       36 |                                       11% |                                 1,946 |                                  2,716 |
|                 [Missouri](/us-mo) |            1,488 |                     2,037 |                     332 |                        549 |                       89 |                                       37% |                                 1,711 |                                  2,615 |
|                   [Nevada](/us-nv) |            1,271 |                     1,934 |                     628 |                        663 |                      215 |                                       52% |                                 1,604 |                                  2,392 |
|                     [Iowa](/us-ia) |            1,091 |                     1,632 |                     517 |                        541 |                      172 |                                       50% |                                 1,270 |                                  2,237 |
|                [Wisconsin](/us-wi) |            1,111 |                     1,557 |                     267 |                        446 |                       77 |                                       40% |                                 1,287 |                                  2,033 |
|                 [Kentucky](/us-ky) |              910 |                     1,345 |                     301 |                        435 |                       97 |                                       48% |                                 1,078 |                                  1,777 |
|                 [Oklahoma](/us-ok) |              778 |                     1,308 |                     331 |                        530 |                      134 |                                       68% |                                 1,011 |                                  1,798 |
|                 [Arkansas](/us-ar) |              739 |                     1,241 |                     411 |                        502 |                      166 |                                       68% |                                   981 |                                  1,621 |
|             [Rhode Island](/us-ri) |            1,044 |                     1,113 |                   1,051 |                         69 |                       66 |                                        7% |                                 1,054 |                                  1,247 |
|               [New Mexico](/us-nm) |              764 |                     1,031 |                     492 |                        267 |                      127 |                                       35% |                                   862 |                                  1,319 |
|              [Puerto Rico](/us-pr) |              412 |                       862 |                     270 |                        450 |                      141 |                                      109% |                                   626 |                                  1,265 |
|                   [Oregon](/us-or) |              438 |                       728 |                     173 |                        290 |                       69 |                                       66% |                                   557 |                                  1,027 |
|                 [Delaware](/us-de) |              604 |                       673 |                     691 |                         69 |                       70 |                                       11% |                                   612 |                                    799 |
|                   [Kansas](/us-ks) |              444 |                       654 |                     224 |                        210 |                       72 |                                       47% |                                   526 |                                    882 |
|     [District of Columbia](/us-dc) |              605 |                       647 |                     916 |                         42 |                       59 |                                        7% |                                   613 |                                    718 |
|                    [Idaho](/us-id) |              343 |                       639 |                     358 |                        296 |                      166 |                                       86% |                                   490 |                                    866 |
|                     [Utah](/us-ut) |              403 |                       612 |                     191 |                        209 |                       65 |                                       52% |                                   494 |                                    817 |
|                 [Nebraska](/us-ne) |              391 |                       531 |                     274 |                        140 |                       72 |                                       36% |                                   430 |                                    703 |
|            [New Hampshire](/us-nh) |              431 |                       470 |                     346 |                         39 |                       29 |                                        9% |                                   434 |                                    553 |
|            [West Virginia](/us-wv) |              198 |                       412 |                     230 |                        214 |                      119 |                                      108% |                                   289 |                                    626 |
|             [North Dakota](/us-nd) |              139 |                       247 |                     325 |                        108 |                      142 |                                       78% |                                   178 |                                    377 |
|             [South Dakota](/us-sd) |              162 |                       234 |                     265 |                         72 |                       81 |                                       44% |                                   180 |                                    316 |
|                  [Montana](/us-mt) |               98 |                       194 |                     182 |                         96 |                       90 |                                       98% |                                   139 |                                    287 |
|                    [Maine](/us-me) |              132 |                       152 |                     113 |                         20 |                       15 |                                       15% |                                   136 |                                    178 |
|                   [Hawaii](/us-hi) |               55 |                       146 |                     103 |                         91 |                       64 |                                      166% |                                    91 |                                    259 |
|                   [Alaska](/us-ak) |               37 |                        81 |                     111 |                         44 |                       60 |                                      119% |                                    57 |                                    126 |
|                  [Vermont](/us-vt) |               58 |                        71 |                     113 |                         13 |                       20 |                                       22% |                                    60 |                                     96 |
|                  [Wyoming](/us-wy) |               37 |                        64 |                     111 |                         27 |                       47 |                                       73% |                                    48 |                                     95 |
|           [Virgin Islands](/us-vi) |               14 |                        50 |                     479 |                         36 |                      346 |                                      259% |                                    31 |                                     82 |
|                     [Guam](/us-gu) |                9 |                        47 |                     282 |                         38 |                      227 |                                      418% |                                    20 |                                     91 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      53 |                          1 |                       17 |                                       48% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,221 |                   203,840 |                     344 |                     15,619 |                      896 |                                        8% |                               191,656 |                                238,144 |
| [United Kingdom](/united-kingdom) |           41,564 |                    42,265 |                     626 |                        701 |                       10 |                                        2% |                                41,586 |                                 44,805 |
|                   [Italy](/italy) |           35,463 |                    36,168 |                     599 |                        705 |                       12 |                                        2% |                                35,493 |                                 38,986 |
|                 [France](/france) |           30,581 |                    32,118 |                     479 |                      1,537 |                       23 |                                        5% |                                30,628 |                                 38,392 |
|                   [Spain](/spain) |           28,996 |                    31,232 |                     665 |                      2,236 |                       48 |                                        8% |                                29,048 |                                 37,837 |
|               [Belgium](/belgium) |            9,884 |                    10,231 |                     893 |                        347 |                       30 |                                        4% |                                 9,916 |                                 11,529 |
|               [Germany](/germany) |            9,290 |                     9,860 |                     119 |                        570 |                        7 |                                        6% |                                 9,330 |                                 11,649 |
|       [Netherlands](/netherlands) |            6,244 |                     6,575 |                     380 |                        331 |                       19 |                                        5% |                                 6,268 |                                  7,844 |
|               [Romania](/romania) |            3,459 |                     6,211 |                     320 |                      2,752 |                      142 |                                       80% |                                 4,588 |                                  9,025 |
|                 [Sweden](/sweden) |            5,820 |                     5,936 |                     580 |                        116 |                       11 |                                        2% |                                 5,839 |                                  6,014 |
|               [Ukraine](/ukraine) |            2,449 |                     5,062 |                     115 |                      2,613 |                       59 |                                      107% |                                 3,368 |                                  8,515 |
|                 [Poland](/poland) |            2,010 |                     2,962 |                      78 |                        952 |                       25 |                                       47% |                                 2,294 |                                  4,204 |
|       [Switzerland](/switzerland) |            2,003 |                     2,110 |                     246 |                        107 |                       12 |                                        5% |                                 2,020 |                                  2,397 |
|             [Portugal](/portugal) |            1,809 |                     2,017 |                     196 |                        208 |                       20 |                                       12% |                                 1,817 |                                  2,502 |
|               [Ireland](/ireland) |            1,777 |                     1,842 |                     376 |                         65 |                       13 |                                        4% |                                 1,786 |                                  2,027 |
|               [Moldova](/moldova) |              977 |                     1,396 |                     345 |                        419 |                      104 |                                       43% |                                 1,133 |                                  1,885 |
|             [Bulgaria](/bulgaria) |              594 |                     1,243 |                     178 |                        649 |                       93 |                                      109% |                                   821 |                                  2,035 |
|                 [Serbia](/serbia) |              707 |                       912 |                     131 |                        205 |                       29 |                                       29% |                                   788 |                                  1,083 |
|               [Belarus](/belarus) |              662 |                       858 |                      91 |                        196 |                       21 |                                       30% |                                   765 |                                  1,000 |
|               [Austria](/austria) |              733 |                       814 |                      92 |                         81 |                        9 |                                       11% |                                   749 |                                    999 |
|               [Denmark](/denmark) |              624 |                       695 |                     120 |                         71 |                       12 |                                       11% |                                   640 |                                    851 |
|               [Hungary](/hungary) |              614 |                       679 |                      69 |                         65 |                        7 |                                       11% |                                   620 |                                    825 |
|               [Czechia](/czechia) |              418 |                       561 |                      53 |                        143 |                       13 |                                       34% |                                   450 |                                    795 |
|                 [Greece](/greece) |              254 |                       501 |                      47 |                        247 |                       23 |                                       97% |                                   337 |                                    856 |
|               [Finland](/finland) |              335 |                       368 |                      67 |                         33 |                        6 |                                       10% |                                   341 |                                    458 |
|                 [Norway](/norway) |              264 |                       304 |                      56 |                         40 |                        7 |                                       15% |                                   275 |                                    382 |
|               [Croatia](/croatia) |              177 |                       272 |                      67 |                         95 |                       23 |                                       54% |                                   209 |                                    392 |
|             [Slovenia](/slovenia) |              133 |                       165 |                      79 |                         32 |                       16 |                                       24% |                                   138 |                                    218 |
|         [Luxembourg](/luxembourg) |              124 |                       156 |                     253 |                         32 |                       51 |                                       25% |                                   134 |                                    195 |
|           [Lithuania](/lithuania) |               85 |                       109 |                      39 |                         24 |                        9 |                                       28% |                                    90 |                                    147 |
|               [Estonia](/estonia) |               64 |                        72 |                      55 |                          8 |                        6 |                                       13% |                                    68 |                                     87 |
|             [Slovakia](/slovakia) |               33 |                        47 |                       9 |                         14 |                        3 |                                       42% |                                    36 |                                     73 |
|                 [Latvia](/latvia) |               34 |                        46 |                      24 |                         12 |                        6 |                                       35% |                                    37 |                                     65 |
|                 [Cyprus](/cyprus) |               20 |                        27 |                      30 |                          7 |                        7 |                                       33% |                                    22 |                                     33 |
|                   [Malta](/malta) |               10 |                        15 |                      31 |                          5 |                       11 |                                       53% |                                    12 |                                     23 |
|               [Iceland](/iceland) |               10 |                        12 |                      37 |                          2 |                        7 |                                       24% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          434,187 |                   644,198 |                     124 |                    210,011 |                    2,691 |                                       48% |                               516,435 |                                853,944 |
|                             [Brazil](/brazil) |          118,649 |                   169,769 |                     804 |                     51,120 |                      242 |                                       43% |                               139,071 |                                221,286 |
|                               [India](/india) |           61,529 |                   114,529 |                      84 |                     53,000 |                       39 |                                       86% |                                82,831 |                                154,923 |
|                             [Mexico](/mexico) |           62,594 |                    88,064 |                     690 |                     25,470 |                      200 |                                       41% |                                76,051 |                                109,765 |
|                                 [Peru](/peru) |           28,124 |                    34,926 |                   1,074 |                      6,802 |                      209 |                                       24% |                                29,990 |                                 42,892 |
|                         [Colombia](/colombia) |           18,467 |                    30,872 |                     613 |                     12,405 |                      246 |                                       67% |                                23,883 |                                 42,176 |
|                                 [Iran](/iran) |           21,137 |                    27,256 |                     329 |                      6,119 |                       74 |                                       29% |                                23,058 |                                 34,338 |
|                             [Russia](/russia) |           16,758 |                    21,874 |                     150 |                      5,116 |                       35 |                                       31% |                                18,275 |                                 28,830 |
|                 [South Africa](/south-africa) |           13,628 |                    20,864 |                     356 |                      7,236 |                      124 |                                       53% |                                16,062 |                                 28,611 |
|                       [Argentina](/argentina) |            8,050 |                    20,187 |                     451 |                     12,137 |                      271 |                                      151% |                                13,165 |                                 30,660 |
|                               [Chile](/chile) |           11,072 |                    13,826 |                     730 |                      2,754 |                      145 |                                       25% |                                11,552 |                                 19,800 |
|                       [Indonesia](/indonesia) |            7,064 |                    12,069 |                      45 |                      5,005 |                       18 |                                       71% |                                 8,834 |                                 18,006 |
|                             [Canada](/canada) |            9,148 |                     9,521 |                     254 |                        373 |                       10 |                                        4% |                                 9,190 |                                 10,350 |
|                           [Bolivia](/bolivia) |            4,791 |                     7,769 |                     675 |                      2,978 |                      259 |                                       62% |                                 5,983 |                                 10,421 |
|                           [Ecuador](/ecuador) |            6,471 |                     7,723 |                     445 |                      1,252 |                       72 |                                       19% |                                 6,604 |                                 10,361 |
|                             [Turkey](/turkey) |            6,209 |                     7,480 |                      90 |                      1,271 |                       15 |                                       20% |                                 6,325 |                                 10,463 |
|                   [Philippines](/philippines) |            3,234 |                     6,892 |                      64 |                      3,658 |                       34 |                                      113% |                                 4,316 |                                 11,519 |
|                         [Pakistan](/pakistan) |            6,274 |                     6,877 |                      32 |                        603 |                        3 |                                       10% |                                 6,349 |                                  7,793 |
|                     [Bangladesh](/bangladesh) |            4,127 |                     6,007 |                      37 |                      1,880 |                       12 |                                       46% |                                 4,885 |                                  8,682 |
|                               [Egypt](/egypt) |            5,342 |                     5,881 |                      59 |                        539 |                        5 |                                       10% |                                 5,413 |                                  6,828 |
|                 [Saudi Arabia](/saudi-arabia) |            3,785 |                     5,386 |                     157 |                      1,601 |                       47 |                                       42% |                                 4,252 |                                  6,990 |
|                               [China](/china) |            4,715 |                     4,806 |                       3 |                         91 |                        0 |                                        2% |                                 4,715 |                                  5,489 |
|                           [Morocco](/morocco) |            1,011 |                     3,422 |                      94 |                      2,411 |                       66 |                                      239% |                                 1,845 |                                  6,404 |
|                         [Honduras](/honduras) |            1,803 |                     2,779 |                     285 |                        976 |                      100 |                                       54% |                                 2,125 |                                  4,022 |
|                             [Panama](/panama) |            1,948 |                     2,638 |                     621 |                        690 |                      163 |                                       35% |                                 2,224 |                                  3,466 |
|     [Dominican Republic](/dominican-republic) |            1,630 |                     2,567 |                     239 |                        937 |                       87 |                                       58% |                                 1,956 |                                  3,763 |
|                           [Algeria](/algeria) |            1,475 |                     2,163 |                      50 |                        688 |                       16 |                                       47% |                                 1,588 |                                  3,465 |
|                               [Japan](/japan) |            1,241 |                     2,049 |                      16 |                        808 |                        6 |                                       65% |                                 1,389 |                                  3,631 |
|                             [Israel](/israel) |              884 |                     1,943 |                     228 |                      1,059 |                      124 |                                      120% |                                 1,211 |                                  3,212 |
|                           [Nigeria](/nigeria) |            1,011 |                     1,253 |                       6 |                        242 |                        1 |                                       24% |                                 1,057 |                                  1,757 |
|                       [Australia](/australia) |              583 |                     1,013 |                      40 |                        430 |                       17 |                                       74% |                                   762 |                                  1,399 |
|                             [Kuwait](/kuwait) |              522 |                       675 |                     160 |                        153 |                       36 |                                       29% |                                   546 |                                  1,003 |
| [United Arab Emirates](/united-arab-emirates) |              378 |                       460 |                      47 |                         82 |                        8 |                                       22% |                                   382 |                                    666 |
|                   [South Korea](/south-korea) |              316 |                       384 |                       7 |                         68 |                        1 |                                       21% |                                   316 |                                    596 |
|                         [Malaysia](/malaysia) |              125 |                       138 |                       4 |                         13 |                        0 |                                       10% |                                   128 |                                    152 |
|                                 [Cuba](/cuba) |               92 |                       136 |                      12 |                         44 |                        4 |                                       48% |                                   102 |                                    225 |
