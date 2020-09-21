We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for >95% of all global reported COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 20:** View our [updated historical performance](/about/#historical-performance).
* **September 15:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1305937870075703296).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 21 (7pm ET):
<p align="center">
  Current Total: <b>199,506</b> deaths | Projected Total: <b>223,400 deaths by Nov 1, 2020</b> (Range: 213-238k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.6%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 21, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |       >99% |        >99% |       >99% |
|              225,000 |        <1% |         <1% |        29% |
|              250,000 |        <1% |         <1% |        <1% |
|              275,000 |        <1% |         <1% |        <1% |
|              300,000 |        <1% |         <1% |        <1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 70 countries (including all 27 European Union countries).

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
|             *[United States](/us)* |          199,506 |                   223,355 |                     673 |                     23,849 |                       72 |                                       12% |                               213,608 |                                237,731 |
|                 [New York](/us-ny) |           33,087 |                    33,428 |                   1,718 |                        341 |                       18 |                                        1% |                                33,100 |                                 35,027 |
|                    [Texas](/us-tx) |           15,088 |                    18,017 |                     621 |                      2,929 |                      101 |                                       19% |                                16,495 |                                 20,267 |
|               [California](/us-ca) |           15,016 |                    17,901 |                     453 |                      2,885 |                       73 |                                       19% |                                16,002 |                                 20,963 |
|               [New Jersey](/us-nj) |           16,067 |                    16,232 |                   1,828 |                        165 |                       19 |                                        1% |                                16,077 |                                 16,777 |
|                  [Florida](/us-fl) |           13,296 |                    16,002 |                     745 |                      2,706 |                      126 |                                       20% |                                14,525 |                                 18,097 |
|            [Massachusetts](/us-ma) |            9,310 |                     9,663 |                   1,390 |                        353 |                       51 |                                        4% |                                 9,333 |                                 10,340 |
|                 [Illinois](/us-il) |            8,686 |                     9,403 |                     742 |                        717 |                       57 |                                        8% |                                 8,768 |                                 10,336 |
|             [Pennsylvania](/us-pa) |            7,960 |                     8,483 |                     663 |                        523 |                       41 |                                        7% |                                 7,990 |                                  9,460 |
|                  [Georgia](/us-ga) |            6,602 |                     7,812 |                     736 |                      1,210 |                      114 |                                       18% |                                 7,074 |                                  9,026 |
|                 [Michigan](/us-mi) |            6,969 |                     7,335 |                     734 |                        366 |                       37 |                                        5% |                                 7,014 |                                  7,909 |
|                [Louisiana](/us-la) |            5,368 |                     5,956 |                   1,281 |                        588 |                      127 |                                       11% |                                 5,605 |                                  6,545 |
|                  [Arizona](/us-az) |            5,477 |                     5,952 |                     818 |                        475 |                       65 |                                        9% |                                 5,589 |                                  6,626 |
|                     [Ohio](/us-oh) |            4,615 |                     5,467 |                     468 |                        852 |                       73 |                                       18% |                                 4,834 |                                  6,550 |
|              [Connecticut](/us-ct) |            4,492 |                     4,563 |                   1,280 |                         71 |                       20 |                                        2% |                                 4,501 |                                  4,759 |
|           [North Carolina](/us-nc) |            3,243 |                     4,121 |                     393 |                        878 |                       84 |                                       27% |                                 3,647 |                                  4,873 |
|                 [Maryland](/us-md) |            3,879 |                     4,108 |                     680 |                        229 |                       38 |                                        6% |                                 3,897 |                                  4,523 |
|           [South Carolina](/us-sc) |            3,199 |                     3,906 |                     759 |                        707 |                      137 |                                       22% |                                 3,526 |                                  4,509 |
|                  [Indiana](/us-in) |            3,506 |                     3,891 |                     578 |                        385 |                       57 |                                       11% |                                 3,536 |                                  4,564 |
|                 [Virginia](/us-va) |            3,013 |                     3,742 |                     438 |                        729 |                       85 |                                       24% |                                 3,218 |                                  4,525 |
|              [Mississippi](/us-ms) |            2,810 |                     3,244 |                   1,090 |                        434 |                      146 |                                       15% |                                 2,955 |                                  3,779 |
|                [Tennessee](/us-tn) |            2,218 |                     2,927 |                     428 |                        709 |                      104 |                                       32% |                                 2,573 |                                  3,471 |
|                  [Alabama](/us-al) |            2,437 |                     2,842 |                     580 |                        405 |                       83 |                                       17% |                                 2,600 |                                  3,232 |
|               [Washington](/us-wa) |            2,037 |                     2,333 |                     306 |                        296 |                       39 |                                       15% |                                 2,085 |                                  2,796 |
|                 [Missouri](/us-mo) |            1,826 |                     2,319 |                     378 |                        493 |                       80 |                                       27% |                                 2,031 |                                  2,740 |
|                [Minnesota](/us-mn) |            2,017 |                     2,309 |                     409 |                        292 |                       52 |                                       14% |                                 2,068 |                                  2,698 |
|                 [Colorado](/us-co) |            2,014 |                     2,194 |                     381 |                        180 |                       31 |                                        9% |                                 2,026 |                                  2,537 |
|                   [Nevada](/us-nv) |            1,531 |                     1,811 |                     588 |                        280 |                       91 |                                       18% |                                 1,630 |                                  2,122 |
|                [Wisconsin](/us-wi) |            1,242 |                     1,596 |                     274 |                        354 |                       61 |                                       28% |                                 1,373 |                                  1,979 |
|                     [Iowa](/us-ia) |            1,265 |                     1,563 |                     495 |                        298 |                       95 |                                       24% |                                 1,377 |                                  1,857 |
|                 [Arkansas](/us-ar) |            1,181 |                     1,530 |                     507 |                        349 |                      116 |                                       30% |                                 1,357 |                                  1,782 |
|                 [Kentucky](/us-ky) |            1,111 |                     1,440 |                     322 |                        329 |                       74 |                                       30% |                                 1,242 |                                  1,734 |
|                 [Oklahoma](/us-ok) |              946 |                     1,219 |                     308 |                        273 |                       69 |                                       29% |                                 1,078 |                                  1,452 |
|             [Rhode Island](/us-ri) |            1,088 |                     1,162 |                   1,097 |                         74 |                       70 |                                        7% |                                 1,095 |                                  1,321 |
|               [New Mexico](/us-nm) |              849 |                       986 |                     470 |                        137 |                       65 |                                       16% |                                   888 |                                  1,149 |
|              [Puerto Rico](/us-pr) |              608 |                       948 |                     297 |                        340 |                      107 |                                       56% |                                   780 |                                  1,226 |
|                   [Kansas](/us-ks) |              595 |                       824 |                     283 |                        229 |                       79 |                                       39% |                                   692 |                                  1,030 |
|                   [Oregon](/us-or) |              526 |                       679 |                     161 |                        153 |                       36 |                                       29% |                                   587 |                                    834 |
|                 [Delaware](/us-de) |              621 |                       654 |                     671 |                         33 |                       34 |                                        5% |                                   625 |                                    716 |
|     [District of Columbia](/us-dc) |              620 |                       639 |                     906 |                         19 |                       27 |                                        3% |                                   623 |                                    675 |
|                    [Idaho](/us-id) |              443 |                       578 |                     323 |                        135 |                       76 |                                       30% |                                   511 |                                    672 |
|                 [Nebraska](/us-ne) |              442 |                       534 |                     276 |                         92 |                       48 |                                       21% |                                   466 |                                    644 |
|                     [Utah](/us-ut) |              440 |                       534 |                     167 |                         94 |                       29 |                                       21% |                                   478 |                                    608 |
|            [West Virginia](/us-wv) |              314 |                       514 |                     287 |                        200 |                      112 |                                       64% |                                   414 |                                    674 |
|            [New Hampshire](/us-nh) |              438 |                       461 |                     339 |                         23 |                       17 |                                        5% |                                   440 |                                    526 |
|             [South Dakota](/us-sd) |              202 |                       297 |                     336 |                         95 |                      107 |                                       47% |                                   221 |                                    441 |
|             [North Dakota](/us-nd) |              192 |                       297 |                     389 |                        105 |                      137 |                                       54% |                                   241 |                                    389 |
|                  [Montana](/us-mt) |              157 |                       261 |                     244 |                        104 |                       98 |                                       66% |                                   214 |                                    343 |
|                   [Hawaii](/us-hi) |              120 |                       233 |                     165 |                        113 |                       80 |                                       94% |                                   168 |                                    363 |
|                    [Maine](/us-me) |              139 |                       156 |                     116 |                         17 |                       13 |                                       12% |                                   142 |                                    182 |
|                     [Guam](/us-gu) |               31 |                        67 |                     404 |                         36 |                      217 |                                      116% |                                    48 |                                     99 |
|                  [Wyoming](/us-wy) |               49 |                        66 |                     113 |                         17 |                       29 |                                       34% |                                    57 |                                     82 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     104 |                          7 |                       11 |                                       12% |                                    59 |                                     78 |
|                   [Alaska](/us-ak) |               45 |                        63 |                      86 |                         18 |                       25 |                                       40% |                                    54 |                                     77 |
|           [Virgin Islands](/us-vi) |               19 |                        27 |                     256 |                          8 |                       75 |                                       41% |                                    22 |                                     35 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       11 |                                       30% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          194,766 |                   217,041 |                     366 |                     22,275 |                       38 |                                       11% |                               199,140 |                                270,549 |
| [United Kingdom](/united-kingdom) |           41,866 |                    43,870 |                     650 |                      2,004 |                       30 |                                        5% |                                41,909 |                                 51,046 |
|                   [Italy](/italy) |           35,707 |                    36,813 |                     610 |                      1,106 |                       18 |                                        3% |                                35,725 |                                 41,001 |
|                   [Spain](/spain) |           30,495 |                    36,679 |                     781 |                      6,184 |                      132 |                                       20% |                                31,128 |                                 54,056 |
|                 [France](/france) |           31,257 |                    35,594 |                     531 |                      4,337 |                       65 |                                       14% |                                31,981 |                                 48,810 |
|               [Belgium](/belgium) |            9,948 |                    10,244 |                     894 |                        296 |                       26 |                                        3% |                                 9,980 |                                 11,102 |
|               [Germany](/germany) |            9,390 |                     9,678 |                     117 |                        288 |                        3 |                                        3% |                                 9,402 |                                 10,832 |
|       [Netherlands](/netherlands) |            6,324 |                     6,635 |                     384 |                        311 |                       18 |                                        5% |                                 6,337 |                                  7,480 |
|               [Ukraine](/ukraine) |            3,626 |                     6,265 |                     142 |                      2,639 |                       60 |                                       73% |                                 4,769 |                                  8,494 |
|               [Romania](/romania) |            4,435 |                     6,002 |                     309 |                      1,567 |                       81 |                                       35% |                                 5,100 |                                  7,488 |
|                 [Sweden](/sweden) |            5,865 |                     5,960 |                     583 |                         95 |                        9 |                                        2% |                                 5,872 |                                  6,220 |
|                 [Poland](/poland) |            2,293 |                     2,986 |                      79 |                        693 |                       18 |                                       30% |                                 2,491 |                                  3,966 |
|       [Switzerland](/switzerland) |            2,045 |                     2,221 |                     258 |                        176 |                       20 |                                        9% |                                 2,082 |                                  2,546 |
|             [Portugal](/portugal) |            1,912 |                     2,213 |                     215 |                        301 |                       29 |                                       16% |                                 1,936 |                                  2,719 |
|               [Ireland](/ireland) |            1,792 |                     1,861 |                     379 |                         69 |                       14 |                                        4% |                                 1,797 |                                  2,064 |
|               [Moldova](/moldova) |            1,203 |                     1,593 |                     394 |                        390 |                       97 |                                       32% |                                 1,363 |                                  1,962 |
|               [Belarus](/belarus) |              780 |                     1,001 |                     106 |                        221 |                       23 |                                       28% |                                   852 |                                  1,311 |
|             [Bulgaria](/bulgaria) |              761 |                       996 |                     142 |                        235 |                       34 |                                       31% |                                   875 |                                  1,195 |
|               [Hungary](/hungary) |              683 |                       982 |                     100 |                        299 |                       31 |                                       44% |                                   797 |                                  1,279 |
|               [Austria](/austria) |              766 |                       886 |                     100 |                        120 |                       14 |                                       16% |                                   782 |                                  1,109 |
|               [Czechia](/czechia) |              503 |                       849 |                      80 |                        346 |                       33 |                                       69% |                                   660 |                                  1,244 |
|                 [Serbia](/serbia) |              741 |                       809 |                     116 |                         68 |                       10 |                                        9% |                                   758 |                                    912 |
|               [Denmark](/denmark) |              638 |                       702 |                     121 |                         64 |                       11 |                                       10% |                                   647 |                                    837 |
|                 [Greece](/greece) |              338 |                       563 |                      53 |                        225 |                       21 |                                       67% |                                   429 |                                    814 |
|               [Finland](/finland) |              339 |                       355 |                      64 |                         16 |                        3 |                                        5% |                                   341 |                                    411 |
|               [Croatia](/croatia) |              248 |                       350 |                      86 |                        102 |                       25 |                                       41% |                                   285 |                                    508 |
|                 [Norway](/norway) |              267 |                       284 |                      53 |                         17 |                        3 |                                        6% |                                   270 |                                    322 |
|             [Slovenia](/slovenia) |              142 |                       167 |                      80 |                         25 |                       12 |                                       18% |                                   146 |                                    224 |
|         [Luxembourg](/luxembourg) |              124 |                       138 |                     225 |                         14 |                       23 |                                       11% |                                   128 |                                    160 |
|           [Lithuania](/lithuania) |               87 |                        95 |                      34 |                          8 |                        3 |                                        9% |                                    88 |                                    108 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        3 |                                        7% |                                    66 |                                     75 |
|             [Slovakia](/slovakia) |               39 |                        51 |                       9 |                         12 |                        2 |                                       30% |                                    42 |                                     72 |
|                   [Malta](/malta) |               20 |                        50 |                     101 |                         30 |                       60 |                                      149% |                                    32 |                                     86 |
|                 [Latvia](/latvia) |               36 |                        42 |                      22 |                          6 |                        3 |                                       18% |                                    37 |                                     51 |
|                 [Cyprus](/cyprus) |               22 |                        26 |                      30 |                          4 |                        5 |                                       19% |                                    23 |                                     31 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       13% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          530,348 |                   672,063 |                     129 |                    141,715 |                       27 |                                       27% |                               588,852 |                                795,564 |
|                             [Brazil](/brazil) |          136,895 |                   160,068 |                     758 |                     23,173 |                      110 |                                       17% |                               147,300 |                                178,664 |
|                               [India](/india) |           86,752 |                   136,051 |                     100 |                     49,299 |                       36 |                                       57% |                               106,553 |                                166,094 |
|                             [Mexico](/mexico) |           73,493 |                    88,701 |                     695 |                     15,208 |                      119 |                                       21% |                                82,007 |                                 97,676 |
|                                 [Peru](/peru) |           31,369 |                    34,137 |                   1,050 |                      2,768 |                       85 |                                        9% |                                31,992 |                                 37,881 |
|                                 [Iran](/iran) |           24,301 |                    30,251 |                     365 |                      5,950 |                       72 |                                       24% |                                26,948 |                                 34,910 |
|                         [Colombia](/colombia) |           24,208 |                    29,760 |                     591 |                      5,552 |                      110 |                                       23% |                                27,084 |                                 34,657 |
|                             [Russia](/russia) |           19,349 |                    24,509 |                     168 |                      5,160 |                       35 |                                       27% |                                20,274 |                                 32,408 |
|                       [Argentina](/argentina) |           13,053 |                    21,097 |                     471 |                      8,044 |                      180 |                                       62% |                                16,452 |                                 31,254 |
|                 [South Africa](/south-africa) |           15,953 |                    18,248 |                     312 |                      2,295 |                       39 |                                       14% |                                16,891 |                                 20,734 |
|                               [Chile](/chile) |           12,286 |                    14,550 |                     768 |                      2,264 |                      119 |                                       18% |                                12,550 |                                 19,388 |
|                       [Indonesia](/indonesia) |            9,553 |                    14,544 |                      54 |                      4,991 |                       18 |                                       52% |                                12,527 |                                 20,025 |
|                           [Ecuador](/ecuador) |           11,090 |                    12,400 |                     714 |                      1,310 |                       75 |                                       12% |                                11,199 |                                 14,508 |
|                             [Turkey](/turkey) |            7,506 |                    10,226 |                     123 |                      2,720 |                       33 |                                       36% |                                 7,959 |                                 14,559 |
|                             [Canada](/canada) |            9,267 |                     9,763 |                     261 |                        496 |                       13 |                                        5% |                                 9,305 |                                 11,324 |
|                           [Bolivia](/bolivia) |            7,617 |                     8,764 |                     761 |                      1,147 |                      100 |                                       15% |                                 8,125 |                                  9,481 |
|                   [Philippines](/philippines) |            4,984 |                     7,913 |                      73 |                      2,929 |                       27 |                                       59% |                                 6,224 |                                 10,411 |
|                         [Pakistan](/pakistan) |            6,420 |                     6,759 |                      31 |                        339 |                        2 |                                        5% |                                 6,473 |                                  7,307 |
|                               [Egypt](/egypt) |            5,770 |                     6,531 |                      65 |                        761 |                        8 |                                       13% |                                 5,862 |                                  8,191 |
|                     [Bangladesh](/bangladesh) |            4,939 |                     5,940 |                      36 |                      1,001 |                        6 |                                       20% |                                 5,335 |                                  7,087 |
|                 [Saudi Arabia](/saudi-arabia) |            4,485 |                     5,243 |                     153 |                        758 |                       22 |                                       17% |                                 4,750 |                                  6,051 |
|                               [China](/china) |            4,737 |                     4,791 |                       3 |                         54 |                        0 |                                        1% |                                 4,737 |                                  5,234 |
|                           [Morocco](/morocco) |            1,830 |                     3,432 |                      94 |                      1,602 |                       44 |                                       88% |                                 2,464 |                                  4,852 |
|                             [Panama](/panama) |            2,257 |                     2,883 |                     679 |                        626 |                      147 |                                       28% |                                 2,678 |                                  3,275 |
|                         [Honduras](/honduras) |            2,184 |                     2,717 |                     279 |                        533 |                       55 |                                       24% |                                 2,347 |                                  3,293 |
|     [Dominican Republic](/dominican-republic) |            2,047 |                     2,646 |                     246 |                        599 |                       56 |                                       29% |                                 2,272 |                                  3,282 |
|                             [Israel](/israel) |            1,256 |                     2,099 |                     246 |                        843 |                       99 |                                       67% |                                 1,516 |                                  3,154 |
|                           [Algeria](/algeria) |            1,672 |                     1,934 |                      45 |                        262 |                        6 |                                       16% |                                 1,729 |                                  2,299 |
|                               [Japan](/japan) |            1,508 |                     1,822 |                      14 |                        314 |                        2 |                                       21% |                                 1,595 |                                  2,203 |
|                           [Nigeria](/nigeria) |            1,098 |                     1,230 |                       6 |                        132 |                        1 |                                       12% |                                 1,131 |                                  1,420 |
|                       [Australia](/australia) |              851 |                       985 |                      39 |                        134 |                        5 |                                       16% |                                   896 |                                  1,123 |
|                             [Kuwait](/kuwait) |              584 |                       752 |                     179 |                        168 |                       40 |                                       29% |                                   609 |                                    981 |
| [United Arab Emirates](/united-arab-emirates) |              404 |                       518 |                      53 |                        114 |                       12 |                                       28% |                                   410 |                                    740 |
|                   [South Korea](/south-korea) |              385 |                       504 |                      10 |                        119 |                        2 |                                       31% |                                   400 |                                    732 |
|                                 [Cuba](/cuba) |              115 |                       155 |                      14 |                         40 |                        4 |                                       35% |                                   126 |                                    218 |
|                         [Malaysia](/malaysia) |              130 |                       139 |                       4 |                          9 |                        0 |                                        7% |                                   132 |                                    148 |
