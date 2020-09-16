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
### Updated Daily - Last Updated: September 15 (1pm ET):
<p align="center">
  Current Total: <b>194,486</b> deaths | Projected Total: <b>218,500 deaths by Nov 1, 2020</b> (Range: 208-233k)<br>
  Currently Infected: <b>0.9%</b> (1 in 110) | Total Infected: <b>15.4%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 15, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 23, 2020 |

<br>

|   US deaths surpass: |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|
|              200,000 |         <1% |        99% |         99% |       >99% |
|              225,000 |         <1% |        <1% |         <1% |        12% |
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
|             *[United States](/us)* |          194,486 |                   218,511 |                     659 |                     24,025 |                       72 |                                       12% |                               208,965 |                                232,491 |
|                 [New York](/us-ny) |           33,030 |                    33,318 |                   1,713 |                        288 |                       15 |                                        1% |                                33,040 |                                 34,993 |
|               [California](/us-ca) |           14,439 |                    18,025 |                     456 |                      3,586 |                       91 |                                       25% |                                16,015 |                                 21,183 |
|                    [Texas](/us-tx) |           14,451 |                    17,123 |                     591 |                      2,672 |                       92 |                                       18% |                                15,838 |                                 18,773 |
|               [New Jersey](/us-nj) |           16,034 |                    16,228 |                   1,827 |                        194 |                       22 |                                        1% |                                16,044 |                                 16,903 |
|                  [Florida](/us-fl) |           12,642 |                    14,771 |                     688 |                      2,129 |                       99 |                                       17% |                                13,579 |                                 16,360 |
|            [Massachusetts](/us-ma) |            9,219 |                     9,602 |                   1,382 |                        383 |                       55 |                                        4% |                                 9,240 |                                 10,361 |
|                 [Illinois](/us-il) |            8,546 |                     9,340 |                     737 |                        794 |                       63 |                                        9% |                                 8,627 |                                 10,398 |
|             [Pennsylvania](/us-pa) |            7,855 |                     8,358 |                     653 |                        503 |                       39 |                                        6% |                                 7,877 |                                  9,392 |
|                  [Georgia](/us-ga) |            6,353 |                     7,538 |                     710 |                      1,185 |                      112 |                                       19% |                                 6,879 |                                  8,528 |
|                 [Michigan](/us-mi) |            6,921 |                     7,380 |                     739 |                        459 |                       46 |                                        7% |                                 6,975 |                                  8,055 |
|                [Louisiana](/us-la) |            5,252 |                     5,816 |                   1,251 |                        564 |                      121 |                                       11% |                                 5,471 |                                  6,397 |
|                  [Arizona](/us-az) |            5,322 |                     5,665 |                     778 |                        343 |                       47 |                                        6% |                                 5,435 |                                  6,019 |
|                     [Ohio](/us-oh) |            4,419 |                     5,355 |                     458 |                        936 |                       80 |                                       21% |                                 4,637 |                                  6,556 |
|              [Connecticut](/us-ct) |            4,485 |                     4,566 |                   1,281 |                         81 |                       23 |                                        2% |                                 4,495 |                                  4,813 |
|                 [Maryland](/us-md) |            3,839 |                     4,100 |                     678 |                        261 |                       43 |                                        7% |                                 3,858 |                                  4,572 |
|           [North Carolina](/us-nc) |            3,060 |                     4,006 |                     382 |                        946 |                       90 |                                       31% |                                 3,502 |                                  4,852 |
|                  [Indiana](/us-in) |            3,439 |                     3,871 |                     575 |                        432 |                       64 |                                       13% |                                 3,469 |                                  4,643 |
|           [South Carolina](/us-sc) |            3,077 |                     3,763 |                     731 |                        686 |                      133 |                                       22% |                                 3,422 |                                  4,272 |
|                 [Virginia](/us-va) |            2,743 |                     3,312 |                     388 |                        569 |                       67 |                                       21% |                                 2,827 |                                  4,112 |
|              [Mississippi](/us-ms) |            2,706 |                     3,123 |                   1,049 |                        417 |                      140 |                                       15% |                                 2,870 |                                  3,541 |
|                [Tennessee](/us-tn) |            2,097 |                     2,942 |                     431 |                        845 |                      124 |                                       40% |                                 2,531 |                                  3,588 |
|                  [Alabama](/us-al) |            2,355 |                     2,813 |                     574 |                        458 |                       93 |                                       19% |                                 2,552 |                                  3,233 |
|                [Minnesota](/us-mn) |            1,974 |                     2,300 |                     408 |                        326 |                       58 |                                       16% |                                 2,025 |                                  2,752 |
|               [Washington](/us-wa) |            2,006 |                     2,275 |                     299 |                        269 |                       35 |                                       13% |                                 2,050 |                                  2,670 |
|                 [Missouri](/us-mo) |            1,738 |                     2,271 |                     370 |                        533 |                       87 |                                       31% |                                 1,961 |                                  2,769 |
|                 [Colorado](/us-co) |            1,990 |                     2,127 |                     369 |                        137 |                       24 |                                        7% |                                 1,999 |                                  2,523 |
|                   [Nevada](/us-nv) |            1,456 |                     1,723 |                     559 |                        267 |                       87 |                                       18% |                                 1,585 |                                  1,925 |
|                     [Iowa](/us-ia) |            1,224 |                     1,596 |                     506 |                        372 |                      118 |                                       30% |                                 1,363 |                                  1,967 |
|                [Wisconsin](/us-wi) |            1,210 |                     1,535 |                     264 |                        325 |                       56 |                                       27% |                                 1,334 |                                  1,864 |
|                 [Kentucky](/us-ky) |            1,065 |                     1,431 |                     320 |                        366 |                       82 |                                       34% |                                 1,214 |                                  1,757 |
|                 [Arkansas](/us-ar) |              992 |                     1,410 |                     467 |                        418 |                      138 |                                       42% |                                 1,210 |                                  1,700 |
|                 [Oklahoma](/us-ok) |              905 |                     1,232 |                     311 |                        327 |                       83 |                                       36% |                                 1,057 |                                  1,533 |
|             [Rhode Island](/us-ri) |            1,075 |                     1,136 |                   1,072 |                         61 |                       57 |                                        6% |                                 1,082 |                                  1,268 |
|               [New Mexico](/us-nm) |              823 |                       941 |                     449 |                        118 |                       56 |                                       14% |                                   860 |                                  1,068 |
|              [Puerto Rico](/us-pr) |              542 |                       873 |                     274 |                        331 |                      104 |                                       61% |                                   702 |                                  1,137 |
|                   [Kansas](/us-ks) |              542 |                       744 |                     255 |                        202 |                       69 |                                       37% |                                   625 |                                    942 |
|                   [Oregon](/us-or) |              509 |                       654 |                     155 |                        145 |                       34 |                                       29% |                                   568 |                                    791 |
|                 [Delaware](/us-de) |              617 |                       654 |                     672 |                         37 |                       38 |                                        6% |                                   621 |                                    727 |
|     [District of Columbia](/us-dc) |              616 |                       638 |                     904 |                         22 |                       31 |                                        4% |                                   619 |                                    681 |
|                    [Idaho](/us-id) |              415 |                       573 |                     321 |                        158 |                       89 |                                       38% |                                   495 |                                    684 |
|                 [Nebraska](/us-ne) |              435 |                       557 |                     288 |                        122 |                       63 |                                       28% |                                   471 |                                    694 |
|                     [Utah](/us-ut) |              436 |                       555 |                     173 |                        119 |                       37 |                                       27% |                                   486 |                                    652 |
|            [New Hampshire](/us-nh) |              436 |                       457 |                     336 |                         21 |                       15 |                                        5% |                                   438 |                                    511 |
|            [West Virginia](/us-wv) |              278 |                       455 |                     254 |                        177 |                       99 |                                       64% |                                   361 |                                    617 |
|             [South Dakota](/us-sd) |              184 |                       260 |                     294 |                         76 |                       86 |                                       41% |                                   192 |                                    407 |
|             [North Dakota](/us-nd) |              170 |                       246 |                     322 |                         76 |                       99 |                                       45% |                                   203 |                                    314 |
|                  [Montana](/us-mt) |              138 |                       239 |                     223 |                        101 |                       94 |                                       73% |                                   188 |                                    325 |
|                   [Hawaii](/us-hi) |               99 |                       172 |                     122 |                         73 |                       52 |                                       74% |                                   134 |                                    231 |
|                    [Maine](/us-me) |              136 |                       150 |                     111 |                         14 |                       10 |                                       10% |                                   139 |                                    170 |
|                   [Alaska](/us-ak) |               44 |                        71 |                      97 |                         27 |                       37 |                                       61% |                                    57 |                                     97 |
|                     [Guam](/us-gu) |               26 |                        65 |                     394 |                         39 |                      237 |                                      151% |                                    46 |                                    100 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     76 |
|                  [Wyoming](/us-wy) |               42 |                        58 |                     100 |                         16 |                       28 |                                       38% |                                    49 |                                     74 |
|           [Virgin Islands](/us-vi) |               19 |                        28 |                     272 |                          9 |                       90 |                                       50% |                                    24 |                                     36 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      49 |                          1 |                       12 |                                       34% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          192,436 |                   206,307 |                     348 |                     13,871 |                       23 |                                        7% |                               195,109 |                                241,846 |
| [United Kingdom](/united-kingdom) |           41,726 |                    42,545 |                     630 |                        819 |                       12 |                                        2% |                                41,749 |                                 46,254 |
|                   [Italy](/italy) |           35,624 |                    36,567 |                     606 |                        943 |                       16 |                                        3% |                                35,642 |                                 40,769 |
|                 [France](/france) |           30,958 |                    32,884 |                     491 |                      1,926 |                       29 |                                        6% |                                31,006 |                                 41,189 |
|                   [Spain](/spain) |           29,848 |                    32,728 |                     697 |                      2,880 |                       61 |                                       10% |                                29,888 |                                 42,122 |
|               [Belgium](/belgium) |            9,927 |                    10,091 |                     881 |                        164 |                       14 |                                        2% |                                 9,942 |                                 10,644 |
|               [Germany](/germany) |            9,356 |                     9,644 |                     116 |                        288 |                        3 |                                        3% |                                 9,369 |                                 10,719 |
|       [Netherlands](/netherlands) |            6,296 |                     6,509 |                     377 |                        213 |                       12 |                                        3% |                                 6,308 |                                  7,242 |
|                 [Sweden](/sweden) |            5,846 |                     5,907 |                     577 |                         61 |                        6 |                                        1% |                                 5,851 |                                  6,101 |
|               [Ukraine](/ukraine) |            3,273 |                     5,837 |                     133 |                      2,564 |                       58 |                                       78% |                                 4,314 |                                  8,351 |
|               [Romania](/romania) |            4,185 |                     5,779 |                     298 |                      1,594 |                       82 |                                       38% |                                 4,866 |                                  7,294 |
|                 [Poland](/poland) |            2,203 |                     2,521 |                      66 |                        318 |                        8 |                                       14% |                                 2,302 |                                  2,826 |
|       [Switzerland](/switzerland) |            2,025 |                     2,109 |                     245 |                         84 |                       10 |                                        4% |                                 2,037 |                                  2,319 |
|             [Portugal](/portugal) |            1,871 |                     2,023 |                     197 |                        152 |                       15 |                                        8% |                                 1,879 |                                  2,398 |
|               [Ireland](/ireland) |            1,784 |                     1,820 |                     371 |                         36 |                        7 |                                        2% |                                 1,790 |                                  1,930 |
|               [Moldova](/moldova) |            1,129 |                     1,483 |                     367 |                        354 |                       88 |                                       31% |                                 1,262 |                                  1,875 |
|             [Bulgaria](/bulgaria) |              729 |                     1,045 |                     149 |                        316 |                       45 |                                       43% |                                   874 |                                  1,324 |
|               [Belarus](/belarus) |              756 |                     1,020 |                     108 |                        264 |                       28 |                                       35% |                                   844 |                                  1,411 |
|               [Austria](/austria) |              757 |                       835 |                      94 |                         78 |                        9 |                                       10% |                                   772 |                                  1,002 |
|                 [Serbia](/serbia) |              733 |                       796 |                     114 |                         63 |                        9 |                                        9% |                                   756 |                                    861 |
|               [Hungary](/hungary) |              642 |                       739 |                      76 |                         97 |                       10 |                                       15% |                                   657 |                                    898 |
|               [Denmark](/denmark) |              633 |                       672 |                     116 |                         39 |                        7 |                                        6% |                                   642 |                                    768 |
|               [Czechia](/czechia) |              465 |                       612 |                      57 |                        147 |                       14 |                                       32% |                                   508 |                                    798 |
|                 [Greece](/greece) |              310 |                       487 |                      45 |                        177 |                       16 |                                       57% |                                   382 |                                    685 |
|               [Croatia](/croatia) |              227 |                       400 |                      98 |                        173 |                       42 |                                       76% |                                   304 |                                    594 |
|               [Finland](/finland) |              337 |                       353 |                      64 |                         16 |                        3 |                                        5% |                                   340 |                                    400 |
|                 [Norway](/norway) |              265 |                       282 |                      52 |                         17 |                        3 |                                        6% |                                   269 |                                    324 |
|             [Slovenia](/slovenia) |              135 |                       150 |                      72 |                         15 |                        7 |                                       11% |                                   137 |                                    182 |
|         [Luxembourg](/luxembourg) |              124 |                       139 |                     227 |                         15 |                       25 |                                       12% |                                   129 |                                    162 |
|           [Lithuania](/lithuania) |               87 |                        97 |                      35 |                         10 |                        3 |                                       11% |                                    89 |                                    113 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        8% |                                    66 |                                     74 |
|             [Slovakia](/slovakia) |               38 |                        51 |                       9 |                         13 |                        2 |                                       35% |                                    42 |                                     70 |
|                 [Latvia](/latvia) |               35 |                        40 |                      21 |                          5 |                        3 |                                       15% |                                    36 |                                     47 |
|                   [Malta](/malta) |               16 |                        33 |                      67 |                         17 |                       34 |                                      106% |                                    23 |                                     52 |
|                 [Cyprus](/cyprus) |               22 |                        28 |                      32 |                          6 |                        7 |                                       27% |                                    24 |                                     34 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       14% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          507,192 |                   665,412 |                     128 |                    158,220 |                       30 |                                       31% |                               570,349 |                                806,482 |
|                             [Brazil](/brazil) |          132,006 |                   158,738 |                     752 |                     26,732 |                      127 |                                       20% |                               143,755 |                                180,382 |
|                               [India](/india) |           79,722 |                   133,798 |                      98 |                     54,076 |                       40 |                                       68% |                                99,650 |                                174,602 |
|                             [Mexico](/mexico) |           71,049 |                    89,367 |                     700 |                     18,318 |                      144 |                                       26% |                                81,600 |                                 99,814 |
|                                 [Peru](/peru) |           30,710 |                    34,243 |                   1,053 |                      3,533 |                      109 |                                       12% |                                31,585 |                                 38,980 |
|                         [Colombia](/colombia) |           23,123 |                    30,156 |                     599 |                      7,033 |                      140 |                                       30% |                                26,730 |                                 36,369 |
|                                 [Iran](/iran) |           23,313 |                    27,770 |                     335 |                      4,457 |                       54 |                                       19% |                                24,820 |                                 33,068 |
|                             [Russia](/russia) |           18,573 |                    23,251 |                     159 |                      4,678 |                       32 |                                       25% |                                19,105 |                                 29,351 |
|                       [Argentina](/argentina) |           11,667 |                    20,042 |                     448 |                      8,375 |                      187 |                                       72% |                                15,190 |                                 25,930 |
|                 [South Africa](/south-africa) |           15,499 |                    18,427 |                     315 |                      2,928 |                       50 |                                       19% |                                16,749 |                                 21,506 |
|                               [Chile](/chile) |           12,013 |                    14,660 |                     774 |                      2,647 |                      140 |                                       22% |                                12,360 |                                 20,632 |
|                       [Indonesia](/indonesia) |            8,841 |                    13,083 |                      48 |                      4,242 |                       16 |                                       48% |                                10,600 |                                 18,264 |
|                           [Ecuador](/ecuador) |           10,922 |                    11,841 |                     682 |                        919 |                       53 |                                        8% |                                10,987 |                                 13,869 |
|                   [Philippines](/philippines) |            4,630 |                    11,537 |                     107 |                      6,907 |                       64 |                                      149% |                                 8,342 |                                 16,972 |
|                             [Canada](/canada) |            9,229 |                     9,509 |                     254 |                        280 |                        7 |                                        3% |                                 9,251 |                                 10,352 |
|                           [Bolivia](/bolivia) |            7,394 |                     9,355 |                     813 |                      1,961 |                      170 |                                       27% |                                 8,239 |                                 11,185 |
|                             [Turkey](/turkey) |            7,119 |                     8,841 |                     106 |                      1,722 |                       21 |                                       24% |                                 7,274 |                                 12,123 |
|                         [Pakistan](/pakistan) |            6,389 |                     6,584 |                      30 |                        195 |                        1 |                                        3% |                                 6,401 |                                  6,775 |
|                               [Egypt](/egypt) |            5,661 |                     6,523 |                      65 |                        862 |                        9 |                                       15% |                                 5,766 |                                  8,457 |
|                     [Bangladesh](/bangladesh) |            4,759 |                     6,312 |                      39 |                      1,553 |                       10 |                                       33% |                                 5,239 |                                  8,143 |
|                 [Saudi Arabia](/saudi-arabia) |            4,305 |                     5,405 |                     158 |                      1,100 |                       32 |                                       26% |                                 4,638 |                                  6,610 |
|                               [China](/china) |            4,735 |                     4,796 |                       3 |                         61 |                        0 |                                        1% |                                 4,735 |                                  5,283 |
|                           [Morocco](/morocco) |            1,614 |                     3,338 |                      92 |                      1,724 |                       47 |                                      107% |                                 2,218 |                                  4,965 |
|     [Dominican Republic](/dominican-republic) |            1,984 |                     2,763 |                     257 |                        779 |                       72 |                                       39% |                                 2,271 |                                  3,596 |
|                         [Honduras](/honduras) |            2,087 |                     2,691 |                     276 |                        604 |                       62 |                                       29% |                                 2,287 |                                  3,381 |
|                             [Panama](/panama) |            2,173 |                     2,555 |                     602 |                        382 |                       90 |                                       18% |                                 2,302 |                                  2,933 |
|                           [Algeria](/algeria) |            1,620 |                     1,916 |                      45 |                        296 |                        7 |                                       18% |                                 1,688 |                                  2,317 |
|                             [Israel](/israel) |            1,136 |                     1,897 |                     223 |                        761 |                       89 |                                       67% |                                 1,379 |                                  3,009 |
|                               [Japan](/japan) |            1,455 |                     1,846 |                      15 |                        391 |                        3 |                                       27% |                                 1,566 |                                  2,328 |
|                           [Nigeria](/nigeria) |            1,083 |                     1,241 |                       6 |                        158 |                        1 |                                       15% |                                 1,125 |                                  1,464 |
|                       [Australia](/australia) |              816 |                     1,000 |                      40 |                        184 |                        7 |                                       23% |                                   879 |                                  1,180 |
|                             [Kuwait](/kuwait) |              563 |                       676 |                     161 |                        113 |                       27 |                                       20% |                                   589 |                                    867 |
|                   [South Korea](/south-korea) |              367 |                       488 |                      10 |                        121 |                        2 |                                       33% |                                   376 |                                    742 |
| [United Arab Emirates](/united-arab-emirates) |              399 |                       478 |                      49 |                         79 |                        8 |                                       20% |                                   405 |                                    677 |
|                                 [Cuba](/cuba) |              108 |                       148 |                      13 |                         40 |                        3 |                                       37% |                                   118 |                                    209 |
|                         [Malaysia](/malaysia) |              128 |                       137 |                       4 |                          9 |                        0 |                                        7% |                                   130 |                                    147 |
