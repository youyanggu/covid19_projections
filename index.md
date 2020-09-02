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
### Updated Daily - Last Updated: September 2 (2pm ET):
<p align="center">
  Current Total: <b>184,661</b> deaths | Projected Total: <b>219,100 deaths by Nov 1, 2020</b> (Range: 206-239k)<br>
  Currently Infected: <b>1.1%</b> (1 in 85) | Total Infected: <b>14.5%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 2, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |          2% |        89% |         99% |        99% |
|              225,000 |         <1% |        <1% |          3% |        18% |
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
|             *[United States](/us)* |          184,661 |                   219,131 |                     660 |                     34,470 |                      104 |                                       19% |                               206,019 |                                238,771 |
|                 [New York](/us-ny) |           32,966 |                    33,394 |                   1,717 |                        428 |                       22 |                                        1% |                                32,980 |                                 35,845 |
|               [California](/us-ca) |           13,150 |                    18,049 |                     457 |                      4,899 |                      124 |                                       37% |                                15,446 |                                 22,617 |
|                    [Texas](/us-tx) |           12,919 |                    17,929 |                     618 |                      5,010 |                      173 |                                       39% |                                15,690 |                                 21,008 |
|               [New Jersey](/us-nj) |           15,950 |                    16,131 |                   1,816 |                        181 |                       20 |                                        1% |                                15,963 |                                 16,767 |
|                  [Florida](/us-fl) |           11,374 |                    14,459 |                     673 |                      3,085 |                      144 |                                       27% |                                12,835 |                                 16,539 |
|            [Massachusetts](/us-ma) |            9,064 |                     9,613 |                   1,383 |                        549 |                       79 |                                        6% |                                 9,095 |                                 10,725 |
|                 [Illinois](/us-il) |            8,273 |                     9,273 |                     732 |                      1,000 |                       79 |                                       12% |                                 8,388 |                                 10,721 |
|             [Pennsylvania](/us-pa) |            7,678 |                     8,355 |                     653 |                        677 |                       53 |                                        9% |                                 7,711 |                                  9,753 |
|                  [Georgia](/us-ga) |            5,733 |                     7,991 |                     753 |                      2,258 |                      213 |                                       39% |                                 6,890 |                                  9,655 |
|                 [Michigan](/us-mi) |            6,767 |                     7,267 |                     728 |                        500 |                       50 |                                        7% |                                 6,809 |                                  8,138 |
|                  [Arizona](/us-az) |            5,044 |                     5,919 |                     813 |                        875 |                      120 |                                       17% |                                 5,413 |                                  6,656 |
|                [Louisiana](/us-la) |            4,984 |                     5,894 |                   1,268 |                        910 |                      196 |                                       18% |                                 5,367 |                                  6,727 |
|                     [Ohio](/us-oh) |            4,166 |                     4,955 |                     424 |                        789 |                       67 |                                       19% |                                 4,359 |                                  5,933 |
|              [Connecticut](/us-ct) |            4,466 |                     4,555 |                   1,278 |                         89 |                       25 |                                        2% |                                 4,476 |                                  4,828 |
|                 [Maryland](/us-md) |            3,761 |                     4,148 |                     686 |                        387 |                       64 |                                       10% |                                 3,798 |                                  4,892 |
|           [North Carolina](/us-nc) |            2,741 |                     3,866 |                     369 |                      1,125 |                      107 |                                       41% |                                 3,263 |                                  4,902 |
|                  [Indiana](/us-in) |            3,312 |                     3,793 |                     563 |                        481 |                       71 |                                       15% |                                 3,341 |                                  4,751 |
|           [South Carolina](/us-sc) |            2,757 |                     3,739 |                     726 |                        982 |                      191 |                                       36% |                                 3,254 |                                  4,488 |
|              [Mississippi](/us-ms) |            2,493 |                     3,236 |                   1,087 |                        743 |                      250 |                                       30% |                                 2,830 |                                  3,824 |
|                 [Virginia](/us-va) |            2,612 |                     3,200 |                     375 |                        588 |                       69 |                                       23% |                                 2,654 |                                  4,076 |
|                  [Alabama](/us-al) |            2,200 |                     2,868 |                     585 |                        668 |                      136 |                                       30% |                                 2,505 |                                  3,428 |
|                [Tennessee](/us-tn) |            1,781 |                     2,790 |                     408 |                      1,009 |                      148 |                                       57% |                                 2,307 |                                  3,577 |
|               [Washington](/us-wa) |            1,931 |                     2,371 |                     311 |                        440 |                       58 |                                       23% |                                 2,029 |                                  2,950 |
|                [Minnesota](/us-mn) |            1,871 |                     2,276 |                     404 |                        405 |                       72 |                                       22% |                                 1,939 |                                  2,853 |
|                 [Missouri](/us-mo) |            1,562 |                     2,162 |                     352 |                        600 |                       98 |                                       38% |                                 1,811 |                                  2,772 |
|                 [Colorado](/us-co) |            1,946 |                     2,130 |                     370 |                        184 |                       32 |                                        9% |                                 1,958 |                                  2,639 |
|                   [Nevada](/us-nv) |            1,313 |                     1,855 |                     602 |                        542 |                      176 |                                       41% |                                 1,585 |                                  2,235 |
|                     [Iowa](/us-ia) |            1,125 |                     1,753 |                     556 |                        628 |                      199 |                                       56% |                                 1,324 |                                  2,717 |
|                [Wisconsin](/us-wi) |            1,130 |                     1,531 |                     263 |                        401 |                       69 |                                       35% |                                 1,287 |                                  1,946 |
|                 [Kentucky](/us-ky) |              948 |                     1,363 |                     305 |                        415 |                       93 |                                       44% |                                 1,110 |                                  1,765 |
|                 [Arkansas](/us-ar) |              814 |                     1,321 |                     438 |                        507 |                      168 |                                       62% |                                 1,061 |                                  1,708 |
|                 [Oklahoma](/us-ok) |              808 |                     1,261 |                     319 |                        453 |                      114 |                                       56% |                                 1,007 |                                  1,673 |
|             [Rhode Island](/us-ri) |            1,050 |                     1,128 |                   1,065 |                         78 |                       73 |                                        7% |                                 1,059 |                                  1,291 |
|               [New Mexico](/us-nm) |              787 |                       958 |                     457 |                        171 |                       82 |                                       22% |                                   849 |                                  1,129 |
|              [Puerto Rico](/us-pr) |              435 |                       800 |                     251 |                        365 |                      114 |                                       84% |                                   607 |                                  1,099 |
|                   [Oregon](/us-or) |              464 |                       739 |                     175 |                        275 |                       65 |                                       59% |                                   579 |                                  1,014 |
|                 [Delaware](/us-de) |              605 |                       652 |                     670 |                         47 |                       49 |                                        8% |                                   610 |                                    745 |
|                   [Kansas](/us-ks) |              456 |                       648 |                     222 |                        192 |                       66 |                                       42% |                                   534 |                                    852 |
|     [District of Columbia](/us-dc) |              607 |                       637 |                     902 |                         30 |                       42 |                                        5% |                                   611 |                                    695 |
|                    [Idaho](/us-id) |              367 |                       621 |                     348 |                        254 |                      142 |                                       69% |                                   494 |                                    820 |
|                     [Utah](/us-ut) |              409 |                       586 |                     183 |                        177 |                       55 |                                       43% |                                   488 |                                    744 |
|                 [Nebraska](/us-ne) |              399 |                       529 |                     273 |                        130 |                       67 |                                       32% |                                   434 |                                    685 |
|            [New Hampshire](/us-nh) |              432 |                       461 |                     339 |                         29 |                       22 |                                        7% |                                   434 |                                    531 |
|            [West Virginia](/us-wv) |              224 |                       441 |                     246 |                        217 |                      121 |                                       97% |                                   321 |                                    643 |
|                   [Hawaii](/us-hi) |               74 |                       308 |                     217 |                        234 |                      165 |                                      316% |                                   162 |                                    577 |
|             [South Dakota](/us-sd) |              167 |                       263 |                     297 |                         96 |                      108 |                                       57% |                                   179 |                                    485 |
|             [North Dakota](/us-nd) |              145 |                       248 |                     326 |                        103 |                      135 |                                       71% |                                   185 |                                    363 |
|                  [Montana](/us-mt) |              105 |                       191 |                     179 |                         86 |                       81 |                                       82% |                                   142 |                                    271 |
|                    [Maine](/us-me) |              132 |                       149 |                     111 |                         17 |                       13 |                                       13% |                                   136 |                                    174 |
|                   [Alaska](/us-ak) |               39 |                        79 |                     109 |                         40 |                       55 |                                      104% |                                    58 |                                    119 |
|                     [Guam](/us-gu) |               13 |                        76 |                     458 |                         63 |                      380 |                                      484% |                                    40 |                                    150 |
|                  [Vermont](/us-vt) |               58 |                        67 |                     107 |                          9 |                       14 |                                       15% |                                    60 |                                     81 |
|                  [Wyoming](/us-wy) |               37 |                        56 |                      97 |                         19 |                       33 |                                       52% |                                    45 |                                     79 |
|           [Virgin Islands](/us-vi) |               15 |                        43 |                     406 |                         28 |                      263 |                                      184% |                                    28 |                                     65 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      52 |                          1 |                       16 |                                       44% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          189,209 |                   202,474 |                     341 |                     13,265 |                      808 |                                        7% |                               192,431 |                                231,312 |
| [United Kingdom](/united-kingdom) |           41,592 |                    42,243 |                     626 |                        651 |                       10 |                                        2% |                                41,605 |                                 45,179 |
|                   [Italy](/italy) |           35,491 |                    35,961 |                     596 |                        470 |                        8 |                                        1% |                                35,508 |                                 38,038 |
|                 [France](/france) |           30,666 |                    31,773 |                     474 |                      1,107 |                       17 |                                        4% |                                30,703 |                                 36,506 |
|                   [Spain](/spain) |           29,152 |                    30,780 |                     656 |                      1,628 |                       35 |                                        6% |                                29,187 |                                 36,296 |
|               [Belgium](/belgium) |            9,897 |                    10,123 |                     884 |                        226 |                       20 |                                        2% |                                 9,922 |                                 10,873 |
|               [Germany](/germany) |            9,307 |                     9,718 |                     117 |                        411 |                        5 |                                        4% |                                 9,327 |                                 11,183 |
|       [Netherlands](/netherlands) |            6,260 |                     6,472 |                     374 |                        212 |                       12 |                                        3% |                                 6,276 |                                  7,323 |
|               [Romania](/romania) |            3,681 |                     6,100 |                     314 |                      2,419 |                      125 |                                       66% |                                 4,707 |                                  8,549 |
|                 [Sweden](/sweden) |            5,813 |                     5,844 |                     571 |                         31 |                        3 |                                        1% |                                 5,818 |                                  5,926 |
|               [Ukraine](/ukraine) |            2,654 |                     5,409 |                     123 |                      2,755 |                       63 |                                      104% |                                 3,633 |                                  8,493 |
|                 [Poland](/poland) |            2,058 |                     2,780 |                      73 |                        722 |                       19 |                                       35% |                                 2,285 |                                  3,729 |
|       [Switzerland](/switzerland) |            2,011 |                     2,094 |                     244 |                         83 |                       10 |                                        4% |                                 2,025 |                                  2,330 |
|             [Portugal](/portugal) |            1,824 |                     1,988 |                     193 |                        164 |                       16 |                                        9% |                                 1,831 |                                  2,409 |
|               [Ireland](/ireland) |            1,777 |                     1,827 |                     372 |                         50 |                       10 |                                        3% |                                 1,785 |                                  1,975 |
|               [Moldova](/moldova) |            1,008 |                     1,384 |                     342 |                        376 |                       93 |                                       37% |                                 1,154 |                                  1,823 |
|             [Bulgaria](/bulgaria) |              642 |                     1,334 |                     191 |                        692 |                       99 |                                      108% |                                   903 |                                  2,088 |
|               [Belarus](/belarus) |              686 |                       987 |                     104 |                        301 |                       32 |                                       44% |                                   774 |                                  1,440 |
|                 [Serbia](/serbia) |              715 |                       893 |                     128 |                        178 |                       26 |                                       25% |                                   785 |                                  1,052 |
|               [Austria](/austria) |              734 |                       789 |                      89 |                         55 |                        6 |                                        8% |                                   744 |                                    927 |
|               [Denmark](/denmark) |              625 |                       668 |                     115 |                         43 |                        7 |                                        7% |                                   635 |                                    788 |
|               [Hungary](/hungary) |              616 |                       665 |                      68 |                         49 |                        5 |                                        8% |                                   620 |                                    792 |
|               [Czechia](/czechia) |              425 |                       538 |                      51 |                        113 |                       11 |                                       27% |                                   452 |                                    708 |
|                 [Greece](/greece) |              271 |                       533 |                      50 |                        262 |                       24 |                                       97% |                                   369 |                                    859 |
|               [Finland](/finland) |              336 |                       358 |                      65 |                         22 |                        4 |                                        7% |                                   340 |                                    421 |
|                 [Norway](/norway) |              264 |                       290 |                      54 |                         26 |                        5 |                                       10% |                                   270 |                                    354 |
|               [Croatia](/croatia) |              187 |                       288 |                      71 |                        101 |                       25 |                                       54% |                                   223 |                                    429 |
|             [Slovenia](/slovenia) |              133 |                       156 |                      75 |                         23 |                       11 |                                       17% |                                   137 |                                    200 |
|         [Luxembourg](/luxembourg) |              124 |                       149 |                     243 |                         25 |                       41 |                                       20% |                                   132 |                                    184 |
|           [Lithuania](/lithuania) |               86 |                       104 |                      37 |                         18 |                        6 |                                       21% |                                    90 |                                    133 |
|               [Estonia](/estonia) |               64 |                        71 |                      54 |                          7 |                        5 |                                       11% |                                    67 |                                     80 |
|             [Slovakia](/slovakia) |               33 |                        43 |                       8 |                         10 |                        2 |                                       29% |                                    35 |                                     60 |
|                 [Latvia](/latvia) |               34 |                        42 |                      22 |                          8 |                        4 |                                       23% |                                    36 |                                     53 |
|                 [Cyprus](/cyprus) |               21 |                        31 |                      36 |                         10 |                       12 |                                       48% |                                    25 |                                     46 |
|                   [Malta](/malta) |               12 |                        29 |                      58 |                         17 |                       34 |                                      141% |                                    18 |                                     51 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        6 |                                       20% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          453,435 |                   647,184 |                     125 |                    193,749 |                    2,391 |                                       43% |                               530,797 |                                861,065 |
|                             [Brazil](/brazil) |          122,596 |                   162,648 |                     771 |                     40,052 |                      190 |                                       33% |                               139,576 |                                197,880 |
|                               [India](/india) |           66,333 |                   124,438 |                      91 |                     58,105 |                       43 |                                       88% |                                90,304 |                                191,222 |
|                             [Mexico](/mexico) |           65,241 |                    88,226 |                     692 |                     22,985 |                      180 |                                       35% |                                77,334 |                                107,861 |
|                                 [Peru](/peru) |           28,944 |                    34,838 |                   1,072 |                      5,894 |                      181 |                                       20% |                                30,623 |                                 41,844 |
|                         [Colombia](/colombia) |           20,050 |                    31,924 |                     634 |                     11,874 |                      236 |                                       59% |                                25,545 |                                 41,683 |
|                                 [Iran](/iran) |           21,672 |                    26,997 |                     326 |                      5,325 |                       64 |                                       25% |                                23,238 |                                 33,092 |
|                             [Russia](/russia) |           17,250 |                    21,569 |                     148 |                      4,319 |                       30 |                                       25% |                                18,183 |                                 30,136 |
|                 [South Africa](/south-africa) |           14,263 |                    20,021 |                     342 |                      5,758 |                       98 |                                       40% |                                16,667 |                                 27,948 |
|                       [Argentina](/argentina) |            8,919 |                    18,914 |                     422 |                      9,995 |                      223 |                                      112% |                                13,026 |                                 26,647 |
|                               [Chile](/chile) |           11,321 |                    14,483 |                     764 |                      3,162 |                      167 |                                       28% |                                11,829 |                                 21,568 |
|                       [Indonesia](/indonesia) |            7,505 |                    12,385 |                      46 |                      4,880 |                       18 |                                       65% |                                 9,129 |                                 19,378 |
|                             [Canada](/canada) |            9,179 |                     9,458 |                     253 |                        279 |                        7 |                                        3% |                                 9,211 |                                 10,163 |
|                             [Turkey](/turkey) |            6,417 |                     7,898 |                      95 |                      1,481 |                       18 |                                       23% |                                 6,520 |                                 10,616 |
|                           [Bolivia](/bolivia) |            5,101 |                     7,763 |                     674 |                      2,662 |                      231 |                                       52% |                                 6,203 |                                 10,214 |
|                           [Ecuador](/ecuador) |            6,571 |                     7,624 |                     439 |                      1,053 |                       61 |                                       16% |                                 6,666 |                                  9,966 |
|                   [Philippines](/philippines) |            3,597 |                     7,374 |                      68 |                      3,777 |                       35 |                                      105% |                                 4,809 |                                 12,147 |
|                         [Pakistan](/pakistan) |            6,298 |                     6,701 |                      31 |                        403 |                        2 |                                        6% |                                 6,326 |                                  7,635 |
|                     [Bangladesh](/bangladesh) |            4,316 |                     6,241 |                      38 |                      1,925 |                       12 |                                       45% |                                 4,947 |                                  8,661 |
|                               [Egypt](/egypt) |            5,440 |                     6,113 |                      61 |                        673 |                        7 |                                       12% |                                 5,490 |                                  8,574 |
|                 [Saudi Arabia](/saudi-arabia) |            3,929 |                     5,216 |                     152 |                      1,287 |                       38 |                                       33% |                                 4,327 |                                  6,738 |
|                               [China](/china) |            4,724 |                     4,801 |                       3 |                         77 |                        0 |                                        2% |                                 4,724 |                                  5,415 |
|                           [Morocco](/morocco) |            1,184 |                     3,340 |                      92 |                      2,156 |                       59 |                                      182% |                                 1,882 |                                  5,558 |
|                         [Honduras](/honduras) |            1,888 |                     2,783 |                     286 |                        895 |                       92 |                                       47% |                                 2,213 |                                  3,810 |
|     [Dominican Republic](/dominican-republic) |            1,738 |                     2,684 |                     250 |                        946 |                       88 |                                       54% |                                 2,066 |                                  3,775 |
|                             [Panama](/panama) |            2,018 |                     2,542 |                     599 |                        524 |                      123 |                                       26% |                                 2,242 |                                  3,167 |
|                           [Algeria](/algeria) |            1,518 |                     2,136 |                      50 |                        618 |                       14 |                                       41% |                                 1,629 |                                  3,235 |
|                               [Japan](/japan) |            1,313 |                     2,075 |                      16 |                        762 |                        6 |                                       58% |                                 1,481 |                                  3,566 |
|                             [Israel](/israel) |              957 |                     1,868 |                     219 |                        911 |                      107 |                                       95% |                                 1,227 |                                  3,031 |
|                           [Nigeria](/nigeria) |            1,023 |                     1,227 |                       6 |                        204 |                        1 |                                       20% |                                 1,042 |                                  1,523 |
|                       [Australia](/australia) |              663 |                     1,081 |                      43 |                        418 |                       17 |                                       63% |                                   829 |                                  1,437 |
|                             [Kuwait](/kuwait) |              534 |                       665 |                     158 |                        131 |                       31 |                                       25% |                                   556 |                                    929 |
| [United Arab Emirates](/united-arab-emirates) |              384 |                       452 |                      46 |                         68 |                        7 |                                       18% |                                   388 |                                    626 |
|                   [South Korea](/south-korea) |              326 |                       422 |                       8 |                         96 |                        2 |                                       30% |                                   329 |                                    649 |
|                         [Malaysia](/malaysia) |              128 |                       141 |                       4 |                         13 |                        0 |                                       10% |                                   131 |                                    155 |
|                                 [Cuba](/cuba) |               95 |                       137 |                      12 |                         42 |                        4 |                                       44% |                                   105 |                                    216 |
