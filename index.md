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

* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* **August 25:** In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* **August 24:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 31 (6pm ET):
<p align="center">
  Current Total: <b>183,063</b> deaths | Projected Total: <b>219,500 deaths by Nov 1, 2020</b> (Range: 205-241k)<br>
  Currently Infected: <b>1.2%</b> (1 in 80) | Total Infected: <b>14.3%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 31, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          4% |        86% |         99% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          5% |        20% |
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
|             *[United States](/us)* |          183,063 |                   219,480 |                     661 |                     36,417 |                      110 |                                       20% |                               205,499 |                                240,208 |
|                 [New York](/us-ny) |           32,951 |                    33,380 |                   1,716 |                        429 |                       22 |                                        1% |                                32,963 |                                 35,607 |
|                    [Texas](/us-tx) |           12,683 |                    18,269 |                     630 |                      5,586 |                      193 |                                       44% |                                15,703 |                                 21,617 |
|               [California](/us-ca) |           12,937 |                    18,111 |                     458 |                      5,174 |                      131 |                                       40% |                                15,303 |                                 22,933 |
|               [New Jersey](/us-nj) |           15,937 |                    16,155 |                   1,819 |                        218 |                       25 |                                        1% |                                15,954 |                                 16,852 |
|                  [Florida](/us-fl) |           11,119 |                    14,366 |                     669 |                      3,247 |                      151 |                                       29% |                                12,687 |                                 16,580 |
|            [Massachusetts](/us-ma) |            9,049 |                     9,682 |                   1,393 |                        633 |                       91 |                                        7% |                                 9,112 |                                 10,919 |
|                 [Illinois](/us-il) |            8,228 |                     9,270 |                     732 |                      1,042 |                       82 |                                       13% |                                 8,347 |                                 10,867 |
|             [Pennsylvania](/us-pa) |            7,658 |                     8,414 |                     657 |                        756 |                       59 |                                       10% |                                 7,700 |                                  9,973 |
|                  [Georgia](/us-ga) |            5,604 |                     7,910 |                     745 |                      2,306 |                      217 |                                       41% |                                 6,760 |                                  9,660 |
|                 [Michigan](/us-mi) |            6,748 |                     7,275 |                     728 |                        527 |                       53 |                                        8% |                                 6,796 |                                  8,177 |
|                  [Arizona](/us-az) |            5,030 |                     5,981 |                     822 |                        951 |                      131 |                                       19% |                                 5,444 |                                  6,783 |
|                [Louisiana](/us-la) |            4,931 |                     5,859 |                   1,260 |                        928 |                      200 |                                       19% |                                 5,313 |                                  6,730 |
|                     [Ohio](/us-oh) |            4,129 |                     4,940 |                     423 |                        811 |                       69 |                                       20% |                                 4,325 |                                  5,969 |
|              [Connecticut](/us-ct) |            4,465 |                     4,570 |                   1,282 |                        105 |                       29 |                                        2% |                                 4,476 |                                  4,886 |
|                 [Maryland](/us-md) |            3,752 |                     4,170 |                     690 |                        418 |                       69 |                                       11% |                                 3,791 |                                  4,971 |
|           [North Carolina](/us-nc) |            2,692 |                     3,856 |                     368 |                      1,164 |                      111 |                                       43% |                                 3,216 |                                  4,960 |
|                  [Indiana](/us-in) |            3,291 |                     3,803 |                     565 |                        512 |                       76 |                                       16% |                                 3,325 |                                  4,802 |
|           [South Carolina](/us-sc) |            2,709 |                     3,758 |                     730 |                      1,049 |                      204 |                                       39% |                                 3,231 |                                  4,556 |
|              [Mississippi](/us-ms) |            2,441 |                     3,206 |                   1,077 |                        765 |                      257 |                                       31% |                                 2,790 |                                  3,824 |
|                 [Virginia](/us-va) |            2,569 |                     3,172 |                     372 |                        603 |                       71 |                                       23% |                                 2,612 |                                  4,089 |
|                  [Alabama](/us-al) |            2,162 |                     2,845 |                     580 |                        683 |                      139 |                                       32% |                                 2,477 |                                  3,431 |
|                [Tennessee](/us-tn) |            1,747 |                     2,830 |                     414 |                      1,083 |                      158 |                                       62% |                                 2,300 |                                  3,675 |
|               [Washington](/us-wa) |            1,905 |                     2,352 |                     309 |                        447 |                       59 |                                       23% |                                 2,006 |                                  2,943 |
|                [Minnesota](/us-mn) |            1,865 |                     2,299 |                     408 |                        434 |                       77 |                                       23% |                                 1,937 |                                  2,913 |
|                 [Colorado](/us-co) |            1,942 |                     2,141 |                     372 |                        199 |                       35 |                                       10% |                                 1,956 |                                  2,692 |
|                 [Missouri](/us-mo) |            1,533 |                     2,131 |                     347 |                        598 |                       97 |                                       39% |                                 1,761 |                                  2,770 |
|                   [Nevada](/us-nv) |            1,302 |                     1,896 |                     616 |                        594 |                      193 |                                       46% |                                 1,600 |                                  2,316 |
|                     [Iowa](/us-ia) |            1,113 |                     1,775 |                     562 |                        662 |                      210 |                                       59% |                                 1,320 |                                  2,825 |
|                [Wisconsin](/us-wi) |            1,122 |                     1,540 |                     264 |                        418 |                       72 |                                       37% |                                 1,286 |                                  1,990 |
|                 [Kentucky](/us-ky) |              929 |                     1,343 |                     301 |                        414 |                       93 |                                       45% |                                 1,090 |                                  1,751 |
|                 [Oklahoma](/us-ok) |              799 |                     1,287 |                     325 |                        488 |                      123 |                                       61% |                                 1,014 |                                  1,727 |
|                 [Arkansas](/us-ar) |              784 |                     1,286 |                     426 |                        502 |                      166 |                                       64% |                                 1,029 |                                  1,689 |
|             [Rhode Island](/us-ri) |            1,046 |                     1,131 |                   1,068 |                         85 |                       81 |                                        8% |                                 1,055 |                                  1,305 |
|               [New Mexico](/us-nm) |              770 |                       938 |                     447 |                        168 |                       80 |                                       22% |                                   829 |                                  1,113 |
|              [Puerto Rico](/us-pr) |              434 |                       857 |                     268 |                        423 |                      132 |                                       97% |                                   625 |                                  1,224 |
|                   [Oregon](/us-or) |              458 |                       750 |                     178 |                        292 |                       69 |                                       64% |                                   576 |                                  1,047 |
|                 [Delaware](/us-de) |              604 |                       656 |                     674 |                         52 |                       54 |                                        9% |                                   610 |                                    753 |
|                   [Kansas](/us-ks) |              449 |                       645 |                     221 |                        196 |                       67 |                                       44% |                                   525 |                                    859 |
|     [District of Columbia](/us-dc) |              606 |                       640 |                     907 |                         34 |                       48 |                                        6% |                                   611 |                                    704 |
|                    [Idaho](/us-id) |              359 |                       636 |                     356 |                        277 |                      155 |                                       77% |                                   497 |                                    855 |
|                     [Utah](/us-ut) |              407 |                       596 |                     186 |                        189 |                       59 |                                       46% |                                   490 |                                    775 |
|                 [Nebraska](/us-ne) |              392 |                       521 |                     269 |                        129 |                       67 |                                       33% |                                   428 |                                    681 |
|            [New Hampshire](/us-nh) |              432 |                       464 |                     341 |                         32 |                       23 |                                        7% |                                   435 |                                    536 |
|            [West Virginia](/us-wv) |              214 |                       428 |                     239 |                        214 |                      120 |                                      100% |                                   305 |                                    638 |
|             [South Dakota](/us-sd) |              167 |                       279 |                     315 |                        112 |                      127 |                                       67% |                                   180 |                                    525 |
|             [North Dakota](/us-nd) |              142 |                       245 |                     322 |                        103 |                      136 |                                       73% |                                   181 |                                    364 |
|                  [Montana](/us-mt) |              104 |                       201 |                     188 |                         97 |                       91 |                                       94% |                                   145 |                                    295 |
|                   [Hawaii](/us-hi) |               63 |                       177 |                     125 |                        114 |                       80 |                                      181% |                                   105 |                                    326 |
|                    [Maine](/us-me) |              132 |                       150 |                     112 |                         18 |                       14 |                                       14% |                                   136 |                                    176 |
|                   [Alaska](/us-ak) |               37 |                        74 |                     101 |                         37 |                       51 |                                      100% |                                    53 |                                    113 |
|                  [Vermont](/us-vt) |               58 |                        67 |                     108 |                          9 |                       15 |                                       16% |                                    60 |                                     82 |
|                  [Wyoming](/us-wy) |               37 |                        59 |                     103 |                         22 |                       39 |                                       60% |                                    46 |                                     86 |
|                     [Guam](/us-gu) |               10 |                        48 |                     289 |                         38 |                      229 |                                      379% |                                    23 |                                    104 |
|           [Virgin Islands](/us-vi) |               14 |                        41 |                     387 |                         27 |                      253 |                                      190% |                                    26 |                                     65 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      53 |                          1 |                       17 |                                       46% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,686 |                   202,438 |                     341 |                     13,752 |                      796 |                                        7% |                               191,736 |                                233,498 |
| [United Kingdom](/united-kingdom) |           41,586 |                    42,439 |                     628 |                        853 |                       13 |                                        2% |                                41,616 |                                 45,762 |
|                   [Italy](/italy) |           35,477 |                    36,053 |                     597 |                        576 |                       10 |                                        2% |                                35,503 |                                 38,343 |
|                 [France](/france) |           30,611 |                    31,863 |                     475 |                      1,252 |                       19 |                                        4% |                                30,652 |                                 37,049 |
|                   [Spain](/spain) |           29,011 |                    30,788 |                     656 |                      1,777 |                       38 |                                        6% |                                29,053 |                                 36,431 |
|               [Belgium](/belgium) |            9,894 |                    10,175 |                     888 |                        281 |                       25 |                                        3% |                                 9,922 |                                 11,188 |
|               [Germany](/germany) |            9,300 |                     9,771 |                     118 |                        471 |                        6 |                                        5% |                                 9,335 |                                 11,395 |
|       [Netherlands](/netherlands) |            6,252 |                     6,534 |                     378 |                        282 |                       16 |                                        5% |                                 6,273 |                                  7,655 |
|                 [Sweden](/sweden) |            5,821 |                     5,901 |                     577 |                         80 |                        8 |                                        1% |                                 5,828 |                                  5,998 |
|               [Romania](/romania) |            3,578 |                     5,878 |                     303 |                      2,300 |                      118 |                                       64% |                                 4,538 |                                  8,390 |
|               [Ukraine](/ukraine) |            2,575 |                     5,309 |                     121 |                      2,734 |                       62 |                                      106% |                                 3,508 |                                  8,633 |
|                 [Poland](/poland) |            2,033 |                     2,773 |                      73 |                        740 |                       19 |                                       36% |                                 2,260 |                                  3,783 |
|       [Switzerland](/switzerland) |            2,005 |                     2,093 |                     244 |                         88 |                       10 |                                        4% |                                 2,019 |                                  2,339 |
|             [Portugal](/portugal) |            1,819 |                     1,999 |                     194 |                        180 |                       17 |                                       10% |                                 1,827 |                                  2,455 |
|               [Ireland](/ireland) |            1,777 |                     1,832 |                     373 |                         55 |                       11 |                                        3% |                                 1,786 |                                  1,989 |
|               [Moldova](/moldova) |              992 |                     1,370 |                     339 |                        378 |                       93 |                                       38% |                                 1,138 |                                  1,815 |
|             [Bulgaria](/bulgaria) |              613 |                     1,144 |                     163 |                        531 |                       76 |                                       87% |                                   809 |                                  1,773 |
|                 [Serbia](/serbia) |              711 |                       898 |                     129 |                        187 |                       27 |                                       26% |                                   783 |                                  1,064 |
|               [Belarus](/belarus) |              676 |                       886 |                      94 |                        210 |                       22 |                                       31% |                                   724 |                                  1,324 |
|               [Austria](/austria) |              733 |                       791 |                      89 |                         58 |                        7 |                                        8% |                                   744 |                                    935 |
|               [Denmark](/denmark) |              624 |                       669 |                     115 |                         45 |                        8 |                                        7% |                                   634 |                                    790 |
|               [Hungary](/hungary) |              614 |                       666 |                      68 |                         52 |                        5 |                                        9% |                                   619 |                                    800 |
|               [Czechia](/czechia) |              423 |                       546 |                      51 |                        123 |                       12 |                                       29% |                                   452 |                                    747 |
|                 [Greece](/greece) |              262 |                       483 |                      45 |                        221 |                       21 |                                       85% |                                   336 |                                    787 |
|               [Finland](/finland) |              335 |                       358 |                      65 |                         23 |                        4 |                                        7% |                                   339 |                                    425 |
|                 [Norway](/norway) |              264 |                       292 |                      54 |                         28 |                        5 |                                       11% |                                   270 |                                    360 |
|               [Croatia](/croatia) |              184 |                       287 |                      70 |                        103 |                       25 |                                       56% |                                   218 |                                    434 |
|             [Slovenia](/slovenia) |              133 |                       158 |                      76 |                         25 |                       12 |                                       19% |                                   137 |                                    204 |
|         [Luxembourg](/luxembourg) |              124 |                       151 |                     246 |                         27 |                       44 |                                       22% |                                   133 |                                    187 |
|           [Lithuania](/lithuania) |               86 |                       109 |                      39 |                         23 |                        8 |                                       26% |                                    92 |                                    143 |
|               [Estonia](/estonia) |               64 |                        72 |                      54 |                          8 |                        6 |                                       12% |                                    68 |                                     81 |
|             [Slovakia](/slovakia) |               33 |                        44 |                       8 |                         11 |                        2 |                                       33% |                                    35 |                                     66 |
|                 [Latvia](/latvia) |               34 |                        43 |                      23 |                          9 |                        5 |                                       27% |                                    36 |                                     59 |
|                   [Malta](/malta) |               12 |                        27 |                      54 |                         15 |                       30 |                                      122% |                                    17 |                                     47 |
|                 [Cyprus](/cyprus) |               20 |                        26 |                      29 |                          6 |                        7 |                                       29% |                                    22 |                                     32 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        6 |                                       21% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          445,533 |                   638,824 |                     123 |                    193,291 |                    2,454 |                                       43% |                               519,785 |                                836,878 |
|                             [Brazil](/brazil) |          120,828 |                   162,317 |                     769 |                     41,489 |                      197 |                                       34% |                               137,168 |                                198,750 |
|                               [India](/india) |           64,469 |                   117,894 |                      86 |                     53,425 |                       39 |                                       83% |                                86,002 |                                161,052 |
|                             [Mexico](/mexico) |           64,158 |                    87,920 |                     689 |                     23,762 |                      186 |                                       37% |                                76,663 |                                107,934 |
|                                 [Peru](/peru) |           28,607 |                    34,684 |                   1,067 |                      6,077 |                      187 |                                       21% |                                30,280 |                                 42,055 |
|                         [Colombia](/colombia) |           19,363 |                    31,022 |                     616 |                     11,659 |                      232 |                                       60% |                                24,340 |                                 41,578 |
|                                 [Iran](/iran) |           21,462 |                    27,088 |                     327 |                      5,626 |                       68 |                                       26% |                                23,108 |                                 33,746 |
|                             [Russia](/russia) |           17,045 |                    21,509 |                     147 |                      4,464 |                       31 |                                       26% |                                18,040 |                                 30,443 |
|                 [South Africa](/south-africa) |           14,028 |                    20,122 |                     344 |                      6,094 |                      104 |                                       43% |                                16,497 |                                 28,510 |
|                       [Argentina](/argentina) |            8,457 |                    18,453 |                     412 |                      9,996 |                      223 |                                      118% |                                12,330 |                                 27,263 |
|                               [Chile](/chile) |           11,244 |                    14,643 |                     773 |                      3,399 |                      179 |                                       30% |                                11,755 |                                 22,222 |
|                       [Indonesia](/indonesia) |            7,343 |                    12,434 |                      46 |                      5,091 |                       19 |                                       69% |                                 9,093 |                                 19,992 |
|                             [Canada](/canada) |            9,164 |                     9,504 |                     254 |                        340 |                        9 |                                        4% |                                 9,201 |                                 10,270 |
|                             [Turkey](/turkey) |            6,326 |                     7,774 |                      93 |                      1,448 |                       17 |                                       23% |                                 6,397 |                                 10,406 |
|                           [Bolivia](/bolivia) |            4,966 |                     7,742 |                     672 |                      2,776 |                      241 |                                       56% |                                 6,066 |                                 10,258 |
|                           [Ecuador](/ecuador) |            6,555 |                     7,710 |                     444 |                      1,155 |                       66 |                                       18% |                                 6,663 |                                 10,175 |
|                   [Philippines](/philippines) |            3,520 |                     7,622 |                      70 |                      4,102 |                       38 |                                      117% |                                 4,770 |                                 13,008 |
|                         [Pakistan](/pakistan) |            6,288 |                     6,743 |                      31 |                        455 |                        2 |                                        7% |                                 6,317 |                                  7,691 |
|                     [Bangladesh](/bangladesh) |            4,248 |                     6,290 |                      39 |                      2,042 |                       13 |                                       48% |                                 4,859 |                                  8,835 |
|                               [Egypt](/egypt) |            5,399 |                     6,119 |                      61 |                        720 |                        7 |                                       13% |                                 5,448 |                                  8,714 |
|                 [Saudi Arabia](/saudi-arabia) |            3,870 |                     5,221 |                     152 |                      1,351 |                       39 |                                       35% |                                 4,287 |                                  6,821 |
|                               [China](/china) |            4,722 |                     4,812 |                       3 |                         90 |                        0 |                                        2% |                                 4,722 |                                  5,481 |
|                           [Morocco](/morocco) |            1,111 |                     3,177 |                      87 |                      2,066 |                       57 |                                      186% |                                 1,761 |                                  5,317 |
|                         [Honduras](/honduras) |            1,858 |                     2,799 |                     287 |                        941 |                       97 |                                       51% |                                 2,198 |                                  3,865 |
|     [Dominican Republic](/dominican-republic) |            1,681 |                     2,583 |                     240 |                        902 |                       84 |                                       54% |                                 1,997 |                                  3,728 |
|                             [Panama](/panama) |            1,995 |                     2,558 |                     602 |                        563 |                      132 |                                       28% |                                 2,231 |                                  3,285 |
|                           [Algeria](/algeria) |            1,501 |                     2,144 |                      50 |                        643 |                       15 |                                       43% |                                 1,626 |                                  3,296 |
|                               [Japan](/japan) |            1,285 |                     2,032 |                      16 |                        747 |                        6 |                                       58% |                                 1,434 |                                  3,575 |
|                             [Israel](/israel) |              919 |                     1,793 |                     211 |                        874 |                      103 |                                       95% |                                 1,182 |                                  2,992 |
|                           [Nigeria](/nigeria) |            1,013 |                     1,226 |                       6 |                        213 |                        1 |                                       21% |                                 1,034 |                                  1,529 |
|                       [Australia](/australia) |              652 |                     1,069 |                      42 |                        417 |                       17 |                                       64% |                                   816 |                                  1,451 |
|                             [Kuwait](/kuwait) |              530 |                       666 |                     158 |                        136 |                       32 |                                       26% |                                   552 |                                    952 |
| [United Arab Emirates](/united-arab-emirates) |              382 |                       454 |                      47 |                         72 |                        7 |                                       19% |                                   386 |                                    644 |
|                   [South Korea](/south-korea) |              324 |                       424 |                       8 |                        100 |                        2 |                                       31% |                                   329 |                                    665 |
|                         [Malaysia](/malaysia) |              126 |                       138 |                       4 |                         12 |                        0 |                                       10% |                                   129 |                                    152 |
|                                 [Cuba](/cuba) |               94 |                       137 |                      12 |                         43 |                        4 |                                       46% |                                   104 |                                    223 |
