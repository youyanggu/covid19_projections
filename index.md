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

* **August 17:** View our [updated historical performance](/about/#historical-performance).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: August 18 (12pm ET):
<p align="center">
  Current Total: <b>170,494</b> deaths | Projected Total: <b>225,000 deaths by Nov 1, 2020</b> (Range: 203-255k)<br>
  Currently Infected: <b>1.6%</b> (1 in 63) | Total Infected: <b>13.5%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: August 18, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              175,000 |        Aug 22, 2020 |
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              175,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              200,000 |        <1% |         20% |        80% |         96% |        99% |
|              225,000 |        <1% |         <1% |         2% |         16% |        40% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |         5% |
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

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          170,494 |                   224,971 |                     678 |                     54,477 |                                       32% |                               203,756 |                                254,595 |
|                 [New York](/us-ny) |           32,846 |                    33,251 |                   1,709 |                        405 |                                        1% |                                32,863 |                                 35,201 |
|               [California](/us-ca) |           11,296 |                    18,654 |                     472 |                      7,358 |                                       65% |                                14,426 |                                 24,857 |
|                    [Texas](/us-tx) |           10,447 |                    18,487 |                     638 |                      8,040 |                                       77% |                                14,623 |                                 23,067 |
|                  [Florida](/us-fl) |            9,539 |                    16,727 |                     779 |                      7,188 |                                       75% |                                13,119 |                                 21,196 |
|               [New Jersey](/us-nj) |           15,916 |                    16,120 |                   1,815 |                        204 |                                        1% |                                15,935 |                                 16,701 |
|            [Massachusetts](/us-ma) |            8,842 |                     9,846 |                   1,417 |                      1,004 |                                       11% |                                 8,928 |                                 11,893 |
|                 [Illinois](/us-il) |            7,967 |                     9,396 |                     741 |                      1,429 |                                       18% |                                 8,150 |                                 12,200 |
|             [Pennsylvania](/us-pa) |            7,453 |                     8,691 |                     679 |                      1,238 |                                       17% |                                 7,558 |                                 11,134 |
|                  [Georgia](/us-ga) |            4,727 |                     7,650 |                     721 |                      2,923 |                                       62% |                                 6,078 |                                 10,053 |
|                 [Michigan](/us-mi) |            6,592 |                     7,289 |                     730 |                        697 |                                       11% |                                 6,655 |                                  8,575 |
|                  [Arizona](/us-az) |            4,506 |                     6,613 |                     909 |                      2,107 |                                       47% |                                 5,525 |                                  8,069 |
|                [Louisiana](/us-la) |            4,526 |                     5,781 |                   1,244 |                      1,255 |                                       28% |                                 5,056 |                                  6,810 |
|                     [Ohio](/us-oh) |            3,832 |                     5,435 |                     465 |                      1,603 |                                       42% |                                 4,341 |                                  7,243 |
|              [Connecticut](/us-ct) |            4,456 |                     4,555 |                   1,278 |                         99 |                                        2% |                                 4,471 |                                  4,805 |
|                 [Maryland](/us-md) |            3,641 |                     4,424 |                     732 |                        783 |                                       22% |                                 3,705 |                                  5,950 |
|                  [Indiana](/us-in) |            3,135 |                     4,181 |                     621 |                      1,046 |                                       33% |                                 3,256 |                                  5,856 |
|           [South Carolina](/us-sc) |            2,288 |                     3,921 |                     762 |                      1,633 |                                       71% |                                 3,069 |                                  5,017 |
|           [North Carolina](/us-nc) |            2,348 |                     3,871 |                     369 |                      1,523 |                                       65% |                                 2,947 |                                  5,365 |
|                 [Virginia](/us-va) |            2,385 |                     3,429 |                     402 |                      1,044 |                                       44% |                                 2,547 |                                  5,157 |
|              [Mississippi](/us-ms) |            2,095 |                     3,184 |                   1,070 |                      1,089 |                                       52% |                                 2,596 |                                  3,945 |
|                  [Alabama](/us-al) |            1,925 |                     2,924 |                     596 |                        999 |                                       52% |                                 2,371 |                                  3,683 |
|               [Washington](/us-wa) |            1,785 |                     2,826 |                     371 |                      1,041 |                                       58% |                                 2,098 |                                  4,156 |
|                [Tennessee](/us-tn) |            1,387 |                     2,539 |                     372 |                      1,152 |                                       83% |                                 1,890 |                                  3,534 |
|                 [Colorado](/us-co) |            1,896 |                     2,334 |                     405 |                        438 |                                       23% |                                 1,938 |                                  3,153 |
|                [Minnesota](/us-mn) |            1,758 |                     2,304 |                     409 |                        546 |                                       31% |                                 1,848 |                                  3,205 |
|                 [Missouri](/us-mo) |            1,415 |                     2,102 |                     343 |                        687 |                                       49% |                                 1,647 |                                  2,865 |
|                   [Nevada](/us-nv) |            1,077 |                     1,899 |                     617 |                        822 |                                       76% |                                 1,459 |                                  2,464 |
|                [Wisconsin](/us-wi) |            1,039 |                     1,600 |                     275 |                        561 |                                       54% |                                 1,223 |                                  2,321 |
|                     [Iowa](/us-ia) |              987 |                     1,461 |                     463 |                        474 |                                       48% |                                 1,131 |                                  2,001 |
|                 [Kentucky](/us-ky) |              818 |                     1,263 |                     283 |                        445 |                                       54% |                                   960 |                                  1,787 |
|                 [Oklahoma](/us-ok) |              665 |                     1,217 |                     308 |                        552 |                                       83% |                                   875 |                                  1,760 |
|                 [Arkansas](/us-ar) |              603 |                     1,136 |                     376 |                        533 |                                       88% |                                   831 |                                  1,566 |
|             [Rhode Island](/us-ri) |            1,023 |                     1,108 |                   1,046 |                         85 |                                        8% |                                 1,035 |                                  1,264 |
|               [New Mexico](/us-nm) |              718 |                     1,033 |                     492 |                        315 |                                       44% |                                   828 |                                  1,404 |
|              [Puerto Rico](/us-pr) |              335 |                     1,002 |                     314 |                        667 |                                      199% |                                   595 |                                  1,664 |
|                   [Oregon](/us-or) |              388 |                       779 |                     185 |                        391 |                                      101% |                                   525 |                                  1,183 |
|                 [Delaware](/us-de) |              593 |                       680 |                     698 |                         87 |                                       15% |                                   602 |                                    838 |
|                   [Kansas](/us-ks) |              406 |                       678 |                     233 |                        272 |                                       67% |                                   500 |                                  1,001 |
|                     [Utah](/us-ut) |              364 |                       655 |                     204 |                        291 |                                       80% |                                   471 |                                    965 |
|     [District of Columbia](/us-dc) |              597 |                       651 |                     922 |                         54 |                                        9% |                                   607 |                                    742 |
|                    [Idaho](/us-id) |              273 |                       608 |                     340 |                        335 |                                      123% |                                   427 |                                    865 |
|                 [Nebraska](/us-ne) |              362 |                       521 |                     269 |                        159 |                                       44% |                                   424 |                                    735 |
|            [New Hampshire](/us-nh) |              423 |                       492 |                     362 |                         69 |                                       16% |                                   427 |                                    648 |
|            [West Virginia](/us-wv) |              160 |                       430 |                     240 |                        270 |                                      169% |                                   262 |                                    716 |
|             [South Dakota](/us-sd) |              153 |                       231 |                     262 |                         78 |                                       51% |                                   181 |                                    327 |
|             [North Dakota](/us-nd) |              126 |                       231 |                     303 |                        105 |                                       83% |                                   165 |                                    344 |
|                  [Montana](/us-mt) |               82 |                       219 |                     205 |                        137 |                                      167% |                                   134 |                                    356 |
|                   [Hawaii](/us-hi) |               40 |                       176 |                     124 |                        136 |                                      340% |                                    78 |                                    391 |
|                    [Maine](/us-me) |              127 |                       154 |                     115 |                         27 |                                       22% |                                   132 |                                    197 |
|                  [Vermont](/us-vt) |               58 |                        74 |                     118 |                         16 |                                       27% |                                    61 |                                    102 |
|                   [Alaska](/us-ak) |               28 |                        62 |                      84 |                         34 |                                      120% |                                    40 |                                    101 |
|                  [Wyoming](/us-wy) |               30 |                        49 |                      84 |                         19 |                                       63% |                                    38 |                                     71 |
|           [Virgin Islands](/us-vi) |                9 |                        18 |                     172 |                          9 |                                      100% |                                    12 |                                     29 |
|                     [Guam](/us-gu) |                5 |                         8 |                      49 |                          3 |                                       62% |                                     5 |                                     15 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      56 |                          1 |                                       54% |                                     2 |                                      5 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          186,232 |                   202,022 |                     341 |                     15,790 |                                        8% |                               189,618 |                                238,547 |
| [United Kingdom](/united-kingdom) |           41,454 |                    42,520 |                     630 |                      1,066 |                                        3% |                                41,489 |                                 46,553 |
|                   [Italy](/italy) |           35,400 |                    36,071 |                     598 |                        671 |                                        2% |                                35,425 |                                 38,522 |
|                 [France](/france) |           30,434 |                    31,495 |                     470 |                      1,061 |                                        3% |                                30,479 |                                 36,056 |
|                   [Spain](/spain) |           28,646 |                    29,907 |                     637 |                      1,261 |                                        4% |                                28,682 |                                 34,580 |
|               [Belgium](/belgium) |            9,944 |                    10,542 |                     920 |                        598 |                                        6% |                                 9,988 |                                 12,881 |
|               [Germany](/germany) |            9,236 |                    10,001 |                     120 |                        765 |                                        8% |                                 9,288 |                                 12,429 |
|       [Netherlands](/netherlands) |            6,194 |                     6,559 |                     380 |                        365 |                                        6% |                                 6,219 |                                  7,984 |
|               [Romania](/romania) |            3,029 |                     6,310 |                     325 |                      3,281 |                                      108% |                                 4,199 |                                 10,087 |
|                 [Sweden](/sweden) |            5,787 |                     5,945 |                     581 |                        158 |                                        3% |                                 5,814 |                                  6,048 |
|               [Ukraine](/ukraine) |            2,122 |                     4,613 |                     105 |                      2,491 |                                      117% |                                 2,886 |                                  8,537 |
|                 [Poland](/poland) |            1,885 |                     2,884 |                      76 |                        999 |                                       53% |                                 2,153 |                                  4,448 |
|       [Switzerland](/switzerland) |            1,991 |                     2,125 |                     247 |                        134 |                                        7% |                                 2,011 |                                  2,518 |
|             [Portugal](/portugal) |            1,779 |                     2,046 |                     199 |                        267 |                                       15% |                                 1,790 |                                  2,644 |
|               [Ireland](/ireland) |            1,774 |                     1,855 |                     378 |                         81 |                                        5% |                                 1,784 |                                  2,090 |
|               [Moldova](/moldova) |              908 |                     1,390 |                     344 |                        482 |                                       53% |                                 1,096 |                                  1,973 |
|             [Bulgaria](/bulgaria) |              512 |                     1,096 |                     157 |                        584 |                                      114% |                                   710 |                                  2,070 |
|                 [Serbia](/serbia) |              677 |                       997 |                     143 |                        320 |                                       47% |                                   807 |                                  1,301 |
|               [Austria](/austria) |              729 |                       824 |                      93 |                         95 |                                       13% |                                   742 |                                  1,064 |
|               [Belarus](/belarus) |              613 |                       806 |                      85 |                        193 |                                       31% |                                   726 |                                    987 |
|               [Denmark](/denmark) |              621 |                       713 |                     123 |                         92 |                                       15% |                                   640 |                                    940 |
|               [Hungary](/hungary) |              608 |                       692 |                      71 |                         84 |                                       14% |                                   616 |                                    898 |
|               [Czechia](/czechia) |              399 |                       548 |                      51 |                        149 |                                       37% |                                   427 |                                    840 |
|                 [Greece](/greece) |              230 |                       467 |                      44 |                        237 |                                      103% |                                   293 |                                    830 |
|               [Finland](/finland) |              334 |                       374 |                      68 |                         40 |                                       12% |                                   341 |                                    483 |
|                 [Norway](/norway) |              261 |                       313 |                      58 |                         52 |                                       20% |                                   274 |                                    430 |
|               [Croatia](/croatia) |              166 |                       284 |                      70 |                        118 |                                       71% |                                   203 |                                    456 |
|         [Luxembourg](/luxembourg) |              124 |                       177 |                     289 |                         53 |                                       43% |                                   141 |                                    256 |
|             [Slovenia](/slovenia) |              129 |                       165 |                      79 |                         36 |                                       28% |                                   134 |                                    228 |
|           [Lithuania](/lithuania) |               81 |                        95 |                      34 |                         14 |                                       17% |                                    84 |                                    124 |
|               [Estonia](/estonia) |               63 |                        71 |                      54 |                          8 |                                       13% |                                    67 |                                     79 |
|             [Slovakia](/slovakia) |               31 |                        45 |                       8 |                         14 |                                       44% |                                    33 |                                     79 |
|                 [Latvia](/latvia) |               32 |                        39 |                      20 |                          7 |                                       21% |                                    33 |                                     51 |
|                 [Cyprus](/cyprus) |               20 |                        31 |                      35 |                         11 |                                       54% |                                    24 |                                     48 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       28% |                                    10 |                                     18 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       30% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          391,691 |                   655,763 |                     126 |                    264,072 |                                       67% |                               490,200 |                                945,195 |
|                             [Brazil](/brazil) |          108,536 |                   170,343 |                     807 |                     61,807 |                                       57% |                               125,771 |                                240,102 |
|                               [India](/india) |           51,797 |                   119,672 |                      88 |                     67,875 |                                      131% |                                77,744 |                                177,180 |
|                             [Mexico](/mexico) |           57,023 |                    97,171 |                     762 |                     40,148 |                                       70% |                                81,630 |                                132,179 |
|                                 [Peru](/peru) |           26,281 |                    36,582 |                   1,125 |                     10,301 |                                       39% |                                29,505 |                                 48,594 |
|                         [Colombia](/colombia) |           15,372 |                    30,752 |                     611 |                     15,380 |                                      100% |                                21,991 |                                 46,249 |
|                                 [Iran](/iran) |           19,804 |                    27,831 |                     336 |                      8,027 |                                       41% |                                22,628 |                                 37,393 |
|                 [South Africa](/south-africa) |           11,982 |                    22,072 |                     377 |                     10,090 |                                       84% |                                15,585 |                                 32,124 |
|                             [Russia](/russia) |           15,707 |                    21,828 |                     150 |                      6,121 |                                       39% |                                17,597 |                                 30,875 |
|                       [Argentina](/argentina) |            5,814 |                    15,627 |                     349 |                      9,813 |                                      169% |                                 9,530 |                                 26,434 |
|                               [Chile](/chile) |           10,513 |                    14,326 |                     756 |                      3,813 |                                       36% |                                11,163 |                                 22,668 |
|                       [Indonesia](/indonesia) |            6,207 |                    10,762 |                      40 |                      4,555 |                                       73% |                                 7,844 |                                 17,732 |
|                             [Canada](/canada) |            9,075 |                     9,484 |                     254 |                        409 |                                        5% |                                 9,109 |                                 10,477 |
|                             [Turkey](/turkey) |            5,996 |                     7,440 |                      89 |                      1,444 |                                       24% |                                 6,102 |                                 11,222 |
|                           [Ecuador](/ecuador) |            6,083 |                     7,384 |                     425 |                      1,301 |                                       21% |                                 6,225 |                                 10,302 |
|                           [Bolivia](/bolivia) |            4,123 |                     7,154 |                     621 |                      3,031 |                                       74% |                                 5,254 |                                 10,845 |
|                         [Pakistan](/pakistan) |            6,175 |                     7,004 |                      32 |                        829 |                                       13% |                                 6,304 |                                  8,147 |
|                   [Philippines](/philippines) |            2,681 |                     6,931 |                      64 |                      4,250 |                                      159% |                                 3,708 |                                 14,591 |
|                               [Egypt](/egypt) |            5,173 |                     5,886 |                      59 |                        713 |                                       14% |                                 5,287 |                                  7,023 |
|                     [Bangladesh](/bangladesh) |            3,694 |                     5,658 |                      35 |                      1,964 |                                       53% |                                 4,184 |                                  8,803 |
|                 [Saudi Arabia](/saudi-arabia) |            3,436 |                     5,141 |                     150 |                      1,705 |                                       50% |                                 3,971 |                                  7,145 |
|                               [China](/china) |            4,703 |                     4,905 |                       3 |                        202 |                                        4% |                                 4,703 |                                  6,308 |
|                           [Morocco](/morocco) |              681 |                     3,267 |                      90 |                      2,586 |                                      380% |                                 1,430 |                                  7,188 |
|                             [Panama](/panama) |            1,788 |                     2,801 |                     660 |                      1,013 |                                       57% |                                 2,140 |                                  3,989 |
|     [Dominican Republic](/dominican-republic) |            1,481 |                     2,734 |                     255 |                      1,253 |                                       85% |                                 1,892 |                                  4,417 |
|                         [Honduras](/honduras) |            1,583 |                     2,639 |                     271 |                      1,056 |                                       67% |                                 1,959 |                                  3,882 |
|                           [Algeria](/algeria) |            1,379 |                     2,165 |                      50 |                        786 |                                       57% |                                 1,537 |                                  3,604 |
|                               [Japan](/japan) |            1,112 |                     1,998 |                      16 |                        886 |                                       80% |                                 1,191 |                                  4,713 |
|                       [Australia](/australia) |              438 |                     1,537 |                      61 |                      1,099 |                                      251% |                                   777 |                                  3,239 |
|                             [Israel](/israel) |              692 |                     1,527 |                     179 |                        835 |                                      121% |                                   956 |                                  2,830 |
|                           [Nigeria](/nigeria) |              977 |                     1,310 |                       7 |                        333 |                                       34% |                                 1,043 |                                  2,033 |
|                             [Kuwait](/kuwait) |              502 |                       755 |                     179 |                        253 |                                       50% |                                   540 |                                  1,321 |
| [United Arab Emirates](/united-arab-emirates) |              364 |                       453 |                      46 |                         89 |                                       24% |                                   370 |                                    691 |
|                   [South Korea](/south-korea) |              306 |                       356 |                       7 |                         50 |                                       16% |                                   306 |                                    524 |
|                         [Malaysia](/malaysia) |              125 |                       140 |                       4 |                         15 |                                       12% |                                   129 |                                    156 |
|                                 [Cuba](/cuba) |               88 |                       127 |                      11 |                         39 |                                       45% |                                    95 |                                    215 |
