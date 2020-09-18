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

* **September 15:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1305937870075703296).
* **September 14:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 25:* In our update this week, we've lowered our projection for additional deaths in the US by ~10% due to the steady decrease in cases and hospitalizations nationally. See our [Twitter thread](https://twitter.com/youyanggu/status/1298297201626685441). We are now also displaying Rt estimates for the future, as well as daily deaths per 1M (on hover).
* *August 13:* Youyang Gu is giving a virtual talk about the model today (Thursday, August 13) at 2pm ET/11am PT as part of the [Marketplace Algorithms and Design seminar](https://sites.google.com/view/mad-seminar). You can rewatch the recording [on YouTube](https://www.youtube.com/watch?v=f88bYflJYEo).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 18 (2am ET):
<p align="center">
  Current Total: <b>197,630</b> deaths | Projected Total: <b>223,100 deaths by Nov 1, 2020</b> (Range: 212-239k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.3%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 18, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |       >99% |        >99% |       >99% |
|              225,000 |        <1% |          1% |        28% |
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
|             *[United States](/us)* |          197,630 |                   223,141 |                     672 |                     25,511 |                       77 |                                       13% |                               212,847 |                                238,286 |
|                 [New York](/us-ny) |           33,070 |                    33,448 |                   1,719 |                        378 |                       19 |                                        1% |                                33,084 |                                 35,232 |
|                    [Texas](/us-tx) |           14,826 |                    17,999 |                     621 |                      3,173 |                      109 |                                       21% |                                16,357 |                                 20,398 |
|               [California](/us-ca) |           14,804 |                    17,937 |                     454 |                      3,133 |                       79 |                                       21% |                                15,912 |                                 21,160 |
|               [New Jersey](/us-nj) |           16,057 |                    16,241 |                   1,828 |                        184 |                       21 |                                        1% |                                16,068 |                                 16,850 |
|                  [Florida](/us-fl) |           13,086 |                    16,095 |                     749 |                      3,009 |                      140 |                                       23% |                                14,503 |                                 18,350 |
|            [Massachusetts](/us-ma) |            9,260 |                     9,632 |                   1,386 |                        372 |                       53 |                                        4% |                                 9,284 |                                 10,320 |
|                 [Illinois](/us-il) |            8,624 |                     9,395 |                     741 |                        771 |                       61 |                                        9% |                                 8,711 |                                 10,385 |
|             [Pennsylvania](/us-pa) |            7,893 |                     8,373 |                     654 |                        480 |                       38 |                                        6% |                                 7,917 |                                  9,316 |
|                  [Georgia](/us-ga) |            6,474 |                     7,771 |                     732 |                      1,297 |                      122 |                                       20% |                                 7,005 |                                  9,051 |
|                 [Michigan](/us-mi) |            6,955 |                     7,376 |                     739 |                        421 |                       42 |                                        6% |                                 7,010 |                                  7,994 |
|                [Louisiana](/us-la) |            5,313 |                     5,962 |                   1,282 |                        649 |                      140 |                                       12% |                                 5,581 |                                  6,592 |
|                  [Arizona](/us-az) |            5,409 |                     5,914 |                     813 |                        505 |                       69 |                                        9% |                                 5,537 |                                  6,610 |
|                     [Ohio](/us-oh) |            4,580 |                     5,513 |                     472 |                        933 |                       80 |                                       20% |                                 4,827 |                                  6,672 |
|              [Connecticut](/us-ct) |            4,488 |                     4,563 |                   1,280 |                         75 |                       21 |                                        2% |                                 4,498 |                                  4,773 |
|           [North Carolina](/us-nc) |            3,180 |                     4,120 |                     393 |                        940 |                       90 |                                       30% |                                 3,622 |                                  4,931 |
|                 [Maryland](/us-md) |            3,861 |                     4,108 |                     680 |                        247 |                       41 |                                        6% |                                 3,881 |                                  4,554 |
|                  [Indiana](/us-in) |            3,478 |                     3,892 |                     578 |                        414 |                       62 |                                       12% |                                 3,511 |                                  4,613 |
|           [South Carolina](/us-sc) |            3,158 |                     3,813 |                     741 |                        655 |                      127 |                                       21% |                                 3,488 |                                  4,287 |
|                 [Virginia](/us-va) |            2,918 |                     3,662 |                     429 |                        744 |                       87 |                                       26% |                                 3,129 |                                  4,476 |
|              [Mississippi](/us-ms) |            2,780 |                     3,264 |                   1,097 |                        484 |                      163 |                                       17% |                                 2,948 |                                  3,840 |
|                [Tennessee](/us-tn) |            2,164 |                     2,941 |                     430 |                        777 |                      114 |                                       36% |                                 2,563 |                                  3,526 |
|                  [Alabama](/us-al) |            2,401 |                     2,839 |                     579 |                        438 |                       89 |                                       18% |                                 2,583 |                                  3,246 |
|               [Washington](/us-wa) |            2,031 |                     2,359 |                     310 |                        328 |                       43 |                                       16% |                                 2,084 |                                  2,860 |
|                [Minnesota](/us-mn) |            1,994 |                     2,305 |                     409 |                        311 |                       55 |                                       16% |                                 2,049 |                                  2,721 |
|                 [Missouri](/us-mo) |            1,782 |                     2,297 |                     374 |                        515 |                       84 |                                       29% |                                 1,998 |                                  2,776 |
|                 [Colorado](/us-co) |            2,006 |                     2,184 |                     379 |                        178 |                       31 |                                        9% |                                 2,018 |                                  2,541 |
|                   [Nevada](/us-nv) |            1,506 |                     1,809 |                     587 |                        303 |                       99 |                                       20% |                                 1,618 |                                  2,136 |
|                     [Iowa](/us-ia) |            1,250 |                     1,591 |                     504 |                        341 |                      108 |                                       27% |                                 1,376 |                                  1,926 |
|                 [Arkansas](/us-ar) |            1,166 |                     1,565 |                     519 |                        399 |                      132 |                                       34% |                                 1,371 |                                  1,839 |
|                [Wisconsin](/us-wi) |            1,230 |                     1,534 |                     263 |                        304 |                       52 |                                       25% |                                 1,349 |                                  1,830 |
|                 [Kentucky](/us-ky) |            1,093 |                     1,448 |                     324 |                        355 |                       79 |                                       32% |                                 1,238 |                                  1,760 |
|                 [Oklahoma](/us-ok) |              930 |                     1,240 |                     313 |                        310 |                       78 |                                       33% |                                 1,078 |                                  1,515 |
|             [Rhode Island](/us-ri) |            1,085 |                     1,143 |                   1,079 |                         58 |                       55 |                                        5% |                                 1,092 |                                  1,269 |
|               [New Mexico](/us-nm) |              836 |                       977 |                     466 |                        141 |                       67 |                                       17% |                                   877 |                                  1,144 |
|              [Puerto Rico](/us-pr) |              588 |                       959 |                     300 |                        371 |                      116 |                                       63% |                                   776 |                                  1,239 |
|                   [Kansas](/us-ks) |              582 |                       814 |                     279 |                        232 |                       80 |                                       40% |                                   681 |                                  1,025 |
|                   [Oregon](/us-or) |              521 |                       693 |                     164 |                        172 |                       41 |                                       33% |                                   587 |                                    875 |
|                 [Delaware](/us-de) |              619 |                       654 |                     672 |                         35 |                       36 |                                        6% |                                   623 |                                    722 |
|     [District of Columbia](/us-dc) |              619 |                       640 |                     907 |                         21 |                       30 |                                        3% |                                   622 |                                    680 |
|                    [Idaho](/us-id) |              434 |                       584 |                     327 |                        150 |                       84 |                                       35% |                                   511 |                                    687 |
|                 [Nebraska](/us-ne) |              442 |                       549 |                     284 |                        107 |                       55 |                                       24% |                                   477 |                                    669 |
|                     [Utah](/us-ut) |              437 |                       541 |                     169 |                        104 |                       32 |                                       24% |                                   480 |                                    623 |
|            [West Virginia](/us-wv) |              297 |                       481 |                     268 |                        184 |                      103 |                                       62% |                                   385 |                                    638 |
|            [New Hampshire](/us-nh) |              438 |                       464 |                     341 |                         26 |                       19 |                                        6% |                                   440 |                                    533 |
|             [South Dakota](/us-sd) |              193 |                       280 |                     317 |                         87 |                       99 |                                       45% |                                   205 |                                    424 |
|             [North Dakota](/us-nd) |              182 |                       269 |                     354 |                         87 |                      115 |                                       48% |                                   223 |                                    344 |
|                  [Montana](/us-mt) |              143 |                       240 |                     224 |                         97 |                       91 |                                       68% |                                   193 |                                    320 |
|                   [Hawaii](/us-hi) |              107 |                       199 |                     141 |                         92 |                       65 |                                       86% |                                   147 |                                    302 |
|                    [Maine](/us-me) |              138 |                       156 |                     116 |                         18 |                       13 |                                       13% |                                   141 |                                    183 |
|                     [Guam](/us-gu) |               30 |                        78 |                     469 |                         48 |                      288 |                                      159% |                                    53 |                                    119 |
|                  [Wyoming](/us-wy) |               49 |                        69 |                     119 |                         20 |                       34 |                                       40% |                                    58 |                                     87 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     105 |                          8 |                       12 |                                       13% |                                    59 |                                     80 |
|                   [Alaska](/us-ak) |               44 |                        64 |                      87 |                         20 |                       27 |                                       45% |                                    53 |                                     79 |
|           [Virgin Islands](/us-vi) |               19 |                        29 |                     274 |                         10 |                       93 |                                       52% |                                    23 |                                     39 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      48 |                          1 |                       12 |                                       32% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          193,870 |                   216,439 |                     365 |                     22,569 |                       38 |                                       12% |                               198,701 |                                273,078 |
| [United Kingdom](/united-kingdom) |           41,794 |                    43,184 |                     639 |                      1,390 |                       21 |                                        3% |                                41,823 |                                 48,584 |
|                   [Spain](/spain) |           30,405 |                    40,048 |                     853 |                      9,643 |                      205 |                                       32% |                                32,421 |                                 60,852 |
|                   [Italy](/italy) |           35,658 |                    36,504 |                     605 |                        846 |                       14 |                                        2% |                                35,674 |                                 40,370 |
|                 [France](/france) |           31,103 |                    34,197 |                     510 |                      3,094 |                       46 |                                       10% |                                31,142 |                                 51,251 |
|               [Belgium](/belgium) |            9,936 |                    10,088 |                     881 |                        152 |                       13 |                                        2% |                                 9,950 |                                 10,600 |
|               [Germany](/germany) |            9,376 |                     9,635 |                     116 |                        259 |                        3 |                                        3% |                                 9,388 |                                 10,647 |
|       [Netherlands](/netherlands) |            6,310 |                     6,505 |                     376 |                        195 |                       11 |                                        3% |                                 6,321 |                                  7,134 |
|               [Ukraine](/ukraine) |            3,465 |                     6,291 |                     143 |                      2,826 |                       64 |                                       82% |                                 4,621 |                                  8,796 |
|                 [Sweden](/sweden) |            5,864 |                     5,934 |                     580 |                         70 |                        7 |                                        1% |                                 5,871 |                                  6,169 |
|               [Romania](/romania) |            4,312 |                     5,807 |                     299 |                      1,495 |                       77 |                                       35% |                                 4,974 |                                  7,053 |
|                 [Poland](/poland) |            2,253 |                     2,593 |                      68 |                        340 |                        9 |                                       15% |                                 2,360 |                                  2,923 |
|       [Switzerland](/switzerland) |            2,042 |                     2,141 |                     249 |                         99 |                       12 |                                        5% |                                 2,055 |                                  2,369 |
|             [Portugal](/portugal) |            1,888 |                     2,048 |                     199 |                        160 |                       16 |                                        8% |                                 1,896 |                                  2,413 |
|               [Ireland](/ireland) |            1,789 |                     1,822 |                     372 |                         33 |                        7 |                                        2% |                                 1,795 |                                  1,926 |
|               [Moldova](/moldova) |            1,170 |                     1,569 |                     388 |                        399 |                       99 |                                       34% |                                 1,329 |                                  1,964 |
|             [Bulgaria](/bulgaria) |              749 |                     1,037 |                     148 |                        288 |                       41 |                                       39% |                                   884 |                                  1,268 |
|               [Belarus](/belarus) |              771 |                     1,024 |                     108 |                        253 |                       27 |                                       33% |                                   856 |                                  1,379 |
|               [Austria](/austria) |              758 |                       821 |                      93 |                         63 |                        7 |                                        8% |                                   771 |                                    961 |
|               [Hungary](/hungary) |              663 |                       813 |                      83 |                        150 |                       15 |                                       23% |                                   691 |                                  1,067 |
|                 [Serbia](/serbia) |              738 |                       796 |                     114 |                         58 |                        8 |                                        8% |                                   760 |                                    853 |
|               [Czechia](/czechia) |              489 |                       704 |                      66 |                        215 |                       20 |                                       44% |                                   569 |                                    950 |
|               [Denmark](/denmark) |              635 |                       673 |                     116 |                         38 |                        7 |                                        6% |                                   643 |                                    765 |
|                 [Greece](/greece) |              325 |                       533 |                      50 |                        208 |                       19 |                                       64% |                                   413 |                                    726 |
|               [Croatia](/croatia) |              238 |                       420 |                     103 |                        182 |                       45 |                                       76% |                                   327 |                                    612 |
|               [Finland](/finland) |              339 |                       354 |                      64 |                         15 |                        3 |                                        4% |                                   342 |                                    400 |
|                 [Norway](/norway) |              266 |                       282 |                      52 |                         16 |                        3 |                                        6% |                                   269 |                                    319 |
|             [Slovenia](/slovenia) |              136 |                       151 |                      72 |                         15 |                        7 |                                       11% |                                   138 |                                    181 |
|         [Luxembourg](/luxembourg) |              124 |                       138 |                     224 |                         14 |                       22 |                                       11% |                                   128 |                                    157 |
|           [Lithuania](/lithuania) |               87 |                        95 |                      34 |                          8 |                        3 |                                        9% |                                    89 |                                    108 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        3 |                                        7% |                                    66 |                                     73 |
|             [Slovakia](/slovakia) |               39 |                        54 |                      10 |                         15 |                        3 |                                       38% |                                    43 |                                     73 |
|                 [Latvia](/latvia) |               36 |                        43 |                      22 |                          7 |                        4 |                                       19% |                                    37 |                                     53 |
|                   [Malta](/malta) |               16 |                        28 |                      56 |                         12 |                       23 |                                       72% |                                    21 |                                     38 |
|                 [Cyprus](/cyprus) |               22 |                        27 |                      31 |                          5 |                        6 |                                       22% |                                    24 |                                     31 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       12% |                                    10 |                                     13 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          519,339 |                   668,723 |                     129 |                    149,384 |                       29 |                                       29% |                               584,845 |                                796,325 |
|                             [Brazil](/brazil) |          134,935 |                   161,058 |                     763 |                     26,123 |                      124 |                                       19% |                               149,237 |                                181,064 |
|                               [India](/india) |           83,198 |                   135,206 |                      99 |                     52,008 |                       38 |                                       63% |                               103,879 |                                169,167 |
|                             [Mexico](/mexico) |           72,179 |                    88,914 |                     697 |                     16,735 |                      131 |                                       23% |                                81,647 |                                 98,664 |
|                                 [Peru](/peru) |           31,051 |                    34,191 |                   1,052 |                      3,140 |                       97 |                                       10% |                                31,807 |                                 38,434 |
|                         [Colombia](/colombia) |           23,665 |                    29,828 |                     593 |                      6,163 |                      122 |                                       26% |                                26,828 |                                 35,229 |
|                                 [Iran](/iran) |           23,808 |                    28,805 |                     347 |                      4,997 |                       60 |                                       21% |                                26,196 |                                 33,435 |
|                             [Russia](/russia) |           18,996 |                    24,431 |                     167 |                      5,435 |                       37 |                                       29% |                                20,332 |                                 34,217 |
|                       [Argentina](/argentina) |           12,460 |                    21,483 |                     480 |                      9,023 |                      201 |                                       72% |                                17,665 |                                 26,867 |
|                 [South Africa](/south-africa) |           15,772 |                    18,371 |                     314 |                      2,599 |                       44 |                                       16% |                                16,865 |                                 20,996 |
|                               [Chile](/chile) |           12,142 |                    14,556 |                     768 |                      2,414 |                      127 |                                       20% |                                12,442 |                                 19,629 |
|                       [Indonesia](/indonesia) |            9,222 |                    13,432 |                      50 |                      4,210 |                       16 |                                       46% |                                11,119 |                                 18,341 |
|                           [Ecuador](/ecuador) |           11,029 |                    11,886 |                     684 |                        857 |                       49 |                                        8% |                                11,093 |                                 13,784 |
|                             [Canada](/canada) |            9,249 |                     9,521 |                     254 |                        272 |                        7 |                                        3% |                                 9,270 |                                 10,334 |
|                           [Bolivia](/bolivia) |            7,511 |                     9,240 |                     803 |                      1,729 |                      150 |                                       23% |                                 8,257 |                                 10,888 |
|                             [Turkey](/turkey) |            7,315 |                     9,040 |                     108 |                      1,725 |                       21 |                                       24% |                                 7,480 |                                 12,168 |
|                   [Philippines](/philippines) |            4,785 |                     7,992 |                      74 |                      3,207 |                       30 |                                       67% |                                 6,109 |                                 11,039 |
|                         [Pakistan](/pakistan) |            6,408 |                     6,584 |                      30 |                        176 |                        1 |                                        3% |                                 6,418 |                                  6,762 |
|                               [Egypt](/egypt) |            5,715 |                     6,519 |                      65 |                        804 |                        8 |                                       14% |                                 5,814 |                                  8,299 |
|                     [Bangladesh](/bangladesh) |            4,859 |                     6,310 |                      39 |                      1,451 |                        9 |                                       30% |                                 5,322 |                                  8,024 |
|                 [Saudi Arabia](/saudi-arabia) |            4,399 |                     5,464 |                     159 |                      1,065 |                       31 |                                       24% |                                 4,713 |                                  6,609 |
|                               [China](/china) |            4,736 |                     4,794 |                       3 |                         58 |                        0 |                                        1% |                                 4,736 |                                  5,262 |
|                           [Morocco](/morocco) |            1,714 |                     3,336 |                      91 |                      1,622 |                       44 |                                       95% |                                 2,321 |                                  4,824 |
|     [Dominican Republic](/dominican-republic) |            2,022 |                     2,710 |                     252 |                        688 |                       64 |                                       34% |                                 2,284 |                                  3,446 |
|                         [Honduras](/honduras) |            2,122 |                     2,680 |                     275 |                        558 |                       57 |                                       26% |                                 2,301 |                                  3,295 |
|                             [Panama](/panama) |            2,213 |                     2,574 |                     606 |                        361 |                       85 |                                       16% |                                 2,329 |                                  2,942 |
|                           [Algeria](/algeria) |            1,654 |                     1,941 |                      45 |                        287 |                        7 |                                       17% |                                 1,718 |                                  2,338 |
|                               [Japan](/japan) |            1,490 |                     1,850 |                      15 |                        360 |                        3 |                                       24% |                                 1,591 |                                  2,273 |
|                             [Israel](/israel) |            1,169 |                     1,829 |                     215 |                        660 |                       77 |                                       56% |                                 1,403 |                                  2,774 |
|                           [Nigeria](/nigeria) |            1,093 |                     1,238 |                       6 |                        145 |                        1 |                                       13% |                                 1,132 |                                  1,443 |
|                       [Australia](/australia) |              837 |                       994 |                      39 |                        157 |                        6 |                                       19% |                                   891 |                                  1,150 |
|                             [Kuwait](/kuwait) |              575 |                       690 |                     164 |                        115 |                       27 |                                       20% |                                   601 |                                    878 |
|                   [South Korea](/south-korea) |              377 |                       499 |                      10 |                        122 |                        2 |                                       32% |                                   389 |                                    742 |
| [United Arab Emirates](/united-arab-emirates) |              402 |                       476 |                      49 |                         74 |                        8 |                                       18% |                                   408 |                                    664 |
|                                 [Cuba](/cuba) |              109 |                       144 |                      13 |                         35 |                        3 |                                       32% |                                   118 |                                    198 |
|                         [Malaysia](/malaysia) |              128 |                       136 |                       4 |                          8 |                        0 |                                        7% |                                   130 |                                    146 |
