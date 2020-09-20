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
### Updated Daily - Last Updated: September 20 (7pm ET):
<p align="center">
  Current Total: <b>199,256</b> deaths | Projected Total: <b>224,000 deaths by Nov 1, 2020</b> (Range: 213-239k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.5%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 20, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 22, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |       >99% |        >99% |       >99% |
|              225,000 |        <1% |          1% |        32% |
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
|             *[United States](/us)* |          199,256 |                   224,034 |                     675 |                     24,778 |                       75 |                                       12% |                               213,972 |                                238,767 |
|                 [New York](/us-ny) |           33,081 |                    33,428 |                   1,718 |                        347 |                       18 |                                        1% |                                33,094 |                                 35,075 |
|                    [Texas](/us-tx) |           15,051 |                    18,108 |                     625 |                      3,057 |                      105 |                                       20% |                                16,515 |                                 20,428 |
|               [California](/us-ca) |           15,018 |                    18,054 |                     457 |                      3,036 |                       77 |                                       20% |                                16,071 |                                 21,206 |
|               [New Jersey](/us-nj) |           16,064 |                    16,235 |                   1,828 |                        171 |                       19 |                                        1% |                                16,074 |                                 16,792 |
|                  [Florida](/us-fl) |           13,287 |                    16,129 |                     751 |                      2,842 |                      132 |                                       21% |                                14,595 |                                 18,287 |
|            [Massachusetts](/us-ma) |            9,295 |                     9,658 |                   1,390 |                        363 |                       52 |                                        4% |                                 9,319 |                                 10,336 |
|                 [Illinois](/us-il) |            8,672 |                     9,419 |                     743 |                        747 |                       59 |                                        9% |                                 8,757 |                                 10,367 |
|             [Pennsylvania](/us-pa) |            7,940 |                     8,429 |                     658 |                        489 |                       38 |                                        6% |                                 7,964 |                                  9,360 |
|                  [Georgia](/us-ga) |            6,599 |                     7,881 |                     742 |                      1,282 |                      121 |                                       19% |                                 7,107 |                                  9,130 |
|                 [Michigan](/us-mi) |            6,969 |                     7,357 |                     737 |                        388 |                       39 |                                        6% |                                 7,018 |                                  7,943 |
|                [Louisiana](/us-la) |            5,342 |                     5,944 |                   1,279 |                        602 |                      130 |                                       11% |                                 5,587 |                                  6,540 |
|                  [Arizona](/us-az) |            5,451 |                     5,935 |                     815 |                        484 |                       66 |                                        9% |                                 5,568 |                                  6,611 |
|                     [Ohio](/us-oh) |            4,612 |                     5,494 |                     470 |                        882 |                       75 |                                       19% |                                 4,844 |                                  6,603 |
|              [Connecticut](/us-ct) |            4,492 |                     4,565 |                   1,280 |                         73 |                       20 |                                        2% |                                 4,502 |                                  4,766 |
|           [North Carolina](/us-nc) |            3,235 |                     4,148 |                     395 |                        913 |                       87 |                                       28% |                                 3,658 |                                  4,929 |
|                 [Maryland](/us-md) |            3,876 |                     4,113 |                     680 |                        237 |                       39 |                                        6% |                                 3,895 |                                  4,540 |
|           [South Carolina](/us-sc) |            3,188 |                     3,920 |                     761 |                        732 |                      142 |                                       23% |                                 3,530 |                                  4,539 |
|                  [Indiana](/us-in) |            3,503 |                     3,902 |                     580 |                        399 |                       59 |                                       11% |                                 3,534 |                                  4,596 |
|                 [Virginia](/us-va) |            2,988 |                     3,730 |                     437 |                        742 |                       87 |                                       25% |                                 3,195 |                                  4,532 |
|              [Mississippi](/us-ms) |            2,809 |                     3,263 |                   1,096 |                        454 |                      153 |                                       16% |                                 2,964 |                                  3,814 |
|                [Tennessee](/us-tn) |            2,216 |                     2,964 |                     434 |                        748 |                      109 |                                       34% |                                 2,599 |                                  3,520 |
|                  [Alabama](/us-al) |            2,437 |                     2,861 |                     584 |                        424 |                       87 |                                       17% |                                 2,610 |                                  3,262 |
|                 [Missouri](/us-mo) |            1,825 |                     2,350 |                     383 |                        525 |                       86 |                                       29% |                                 2,046 |                                  2,820 |
|               [Washington](/us-wa) |            2,037 |                     2,343 |                     308 |                        306 |                       40 |                                       15% |                                 2,087 |                                  2,820 |
|                [Minnesota](/us-mn) |            2,015 |                     2,318 |                     411 |                        303 |                       54 |                                       15% |                                 2,068 |                                  2,719 |
|                 [Colorado](/us-co) |            2,013 |                     2,183 |                     379 |                        170 |                       30 |                                        8% |                                 2,024 |                                  2,524 |
|                   [Nevada](/us-nv) |            1,528 |                     1,822 |                     591 |                        294 |                       95 |                                       19% |                                 1,633 |                                  2,139 |
|                [Wisconsin](/us-wi) |            1,238 |                     1,599 |                     275 |                        361 |                       62 |                                       29% |                                 1,369 |                                  1,985 |
|                     [Iowa](/us-ia) |            1,265 |                     1,587 |                     503 |                        322 |                      102 |                                       25% |                                 1,383 |                                  1,909 |
|                 [Arkansas](/us-ar) |            1,181 |                     1,548 |                     513 |                        367 |                      122 |                                       31% |                                 1,369 |                                  1,808 |
|                 [Kentucky](/us-ky) |            1,108 |                     1,448 |                     324 |                        340 |                       76 |                                       31% |                                 1,245 |                                  1,748 |
|                 [Oklahoma](/us-ok) |              943 |                     1,236 |                     312 |                        293 |                       74 |                                       31% |                                 1,082 |                                  1,495 |
|             [Rhode Island](/us-ri) |            1,088 |                     1,143 |                   1,079 |                         55 |                       52 |                                        5% |                                 1,095 |                                  1,263 |
|               [New Mexico](/us-nm) |              847 |                       987 |                     471 |                        140 |                       67 |                                       17% |                                   887 |                                  1,154 |
|              [Puerto Rico](/us-pr) |              605 |                       962 |                     301 |                        357 |                      112 |                                       59% |                                   787 |                                  1,226 |
|                   [Kansas](/us-ks) |              594 |                       820 |                     282 |                        226 |                       78 |                                       38% |                                   691 |                                  1,026 |
|                   [Oregon](/us-or) |              521 |                       674 |                     160 |                        153 |                       36 |                                       29% |                                   580 |                                    838 |
|                 [Delaware](/us-de) |              621 |                       655 |                     673 |                         34 |                       35 |                                        5% |                                   625 |                                    719 |
|     [District of Columbia](/us-dc) |              619 |                       639 |                     905 |                         20 |                       28 |                                        3% |                                   622 |                                    676 |
|                    [Idaho](/us-id) |              441 |                       581 |                     325 |                        140 |                       79 |                                       32% |                                   513 |                                    678 |
|                 [Nebraska](/us-ne) |              442 |                       540 |                     279 |                         98 |                       50 |                                       22% |                                   474 |                                    652 |
|                     [Utah](/us-ut) |              440 |                       537 |                     168 |                         97 |                       30 |                                       22% |                                   479 |                                    614 |
|            [West Virginia](/us-wv) |              311 |                       498 |                     278 |                        187 |                      104 |                                       60% |                                   400 |                                    654 |
|            [New Hampshire](/us-nh) |              438 |                       462 |                     340 |                         24 |                       18 |                                        5% |                                   440 |                                    528 |
|             [North Dakota](/us-nd) |              192 |                       308 |                     404 |                        116 |                      152 |                                       61% |                                   242 |                                    430 |
|             [South Dakota](/us-sd) |              200 |                       296 |                     335 |                         96 |                      109 |                                       48% |                                   215 |                                    443 |
|                  [Montana](/us-mt) |              156 |                       268 |                     251 |                        112 |                      105 |                                       72% |                                   218 |                                    361 |
|                   [Hawaii](/us-hi) |              120 |                       240 |                     169 |                        120 |                       85 |                                      100% |                                   171 |                                    377 |
|                    [Maine](/us-me) |              139 |                       157 |                     116 |                         18 |                       13 |                                       13% |                                   142 |                                    184 |
|                     [Guam](/us-gu) |               31 |                        70 |                     421 |                         39 |                      234 |                                      125% |                                    49 |                                    105 |
|                  [Wyoming](/us-wy) |               49 |                        66 |                     115 |                         17 |                       30 |                                       36% |                                    57 |                                     83 |
|                  [Vermont](/us-vt) |               58 |                        65 |                     105 |                          7 |                       12 |                                       13% |                                    59 |                                     80 |
|                   [Alaska](/us-ak) |               45 |                        64 |                      87 |                         19 |                       26 |                                       42% |                                    54 |                                     79 |
|           [Virgin Islands](/us-vi) |               19 |                        27 |                     260 |                          8 |                       79 |                                       43% |                                    22 |                                     35 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       11 |                                       31% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          194,583 |                   217,875 |                     367 |                     23,292 |                       39 |                                       12% |                               199,115 |                                276,155 |
| [United Kingdom](/united-kingdom) |           41,848 |                    43,877 |                     650 |                      2,029 |                       30 |                                        5% |                                41,889 |                                 52,444 |
|                 [France](/france) |           31,257 |                    37,060 |                     553 |                      5,803 |                       87 |                                       19% |                                32,218 |                                 54,529 |
|                   [Spain](/spain) |           30,495 |                    36,893 |                     786 |                      6,398 |                      136 |                                       21% |                                31,207 |                                 54,111 |
|                   [Italy](/italy) |           35,692 |                    36,631 |                     607 |                        939 |                       16 |                                        3% |                                35,708 |                                 40,471 |
|               [Belgium](/belgium) |            9,944 |                    10,111 |                     883 |                        167 |                       15 |                                        2% |                                 9,958 |                                 10,693 |
|               [Germany](/germany) |            9,388 |                     9,686 |                     117 |                        298 |                        4 |                                        3% |                                 9,400 |                                 10,867 |
|       [Netherlands](/netherlands) |            6,320 |                     6,539 |                     378 |                        219 |                       13 |                                        3% |                                 6,332 |                                  7,259 |
|               [Ukraine](/ukraine) |            3,585 |                     6,438 |                     146 |                      2,853 |                       65 |                                       80% |                                 4,766 |                                  8,929 |
|               [Romania](/romania) |            4,402 |                     6,057 |                     312 |                      1,655 |                       85 |                                       38% |                                 5,112 |                                  7,699 |
|                 [Sweden](/sweden) |            5,865 |                     5,942 |                     581 |                         77 |                        8 |                                        1% |                                 5,872 |                                  6,222 |
|                 [Poland](/poland) |            2,282 |                     2,721 |                      72 |                        439 |                       12 |                                       19% |                                 2,401 |                                  3,413 |
|       [Switzerland](/switzerland) |            2,045 |                     2,148 |                     250 |                        103 |                       12 |                                        5% |                                 2,058 |                                  2,403 |
|             [Portugal](/portugal) |            1,899 |                     2,083 |                     203 |                        184 |                       18 |                                       10% |                                 1,908 |                                  2,532 |
|               [Ireland](/ireland) |            1,792 |                     1,829 |                     373 |                         37 |                        8 |                                        2% |                                 1,797 |                                  1,977 |
|               [Moldova](/moldova) |            1,201 |                     1,641 |                     406 |                        440 |                      109 |                                       37% |                                 1,370 |                                  2,074 |
|               [Belarus](/belarus) |              776 |                     1,004 |                     106 |                        228 |                       24 |                                       29% |                                   852 |                                  1,320 |
|             [Bulgaria](/bulgaria) |              755 |                       994 |                     142 |                        239 |                       34 |                                       32% |                                   871 |                                  1,198 |
|               [Hungary](/hungary) |              675 |                       870 |                      89 |                        195 |                       20 |                                       29% |                                   716 |                                  1,212 |
|               [Austria](/austria) |              765 |                       844 |                      95 |                         79 |                        9 |                                       10% |                                   778 |                                  1,026 |
|                 [Serbia](/serbia) |              740 |                       811 |                     116 |                         71 |                       10 |                                       10% |                                   758 |                                    919 |
|               [Czechia](/czechia) |              499 |                       746 |                      70 |                        247 |                       23 |                                       50% |                                   577 |                                  1,051 |
|               [Denmark](/denmark) |              635 |                       675 |                     116 |                         40 |                        7 |                                        6% |                                   643 |                                    775 |
|                 [Greece](/greece) |              331 |                       545 |                      51 |                        214 |                       20 |                                       65% |                                   416 |                                    797 |
|               [Croatia](/croatia) |              244 |                       442 |                     109 |                        198 |                       49 |                                       81% |                                   326 |                                    683 |
|               [Finland](/finland) |              339 |                       356 |                      64 |                         17 |                        3 |                                        5% |                                   341 |                                    412 |
|                 [Norway](/norway) |              267 |                       284 |                      53 |                         17 |                        3 |                                        6% |                                   270 |                                    323 |
|             [Slovenia](/slovenia) |              141 |                       165 |                      79 |                         24 |                       12 |                                       17% |                                   145 |                                    211 |
|         [Luxembourg](/luxembourg) |              124 |                       138 |                     226 |                         14 |                       24 |                                       12% |                                   128 |                                    161 |
|           [Lithuania](/lithuania) |               87 |                        95 |                      34 |                          8 |                        3 |                                        9% |                                    88 |                                    109 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        3 |                                        7% |                                    66 |                                     75 |
|             [Slovakia](/slovakia) |               39 |                        52 |                      10 |                         13 |                        2 |                                       33% |                                    42 |                                     75 |
|                   [Malta](/malta) |               19 |                        49 |                      99 |                         30 |                       60 |                                      157% |                                    31 |                                     86 |
|                 [Latvia](/latvia) |               36 |                        43 |                      22 |                          7 |                        3 |                                       18% |                                    37 |                                     52 |
|                 [Cyprus](/cyprus) |               22 |                        27 |                      31 |                          5 |                        6 |                                       22% |                                    24 |                                     33 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       13% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          527,343 |                   669,583 |                     129 |                    142,240 |                       27 |                                       27% |                               589,118 |                                789,657 |
|                             [Brazil](/brazil) |          136,532 |                   161,346 |                     764 |                     24,814 |                      118 |                                       18% |                               149,703 |                                180,330 |
|                               [India](/india) |           85,619 |                   136,413 |                     100 |                     50,794 |                       37 |                                       59% |                               107,052 |                                167,521 |
|                             [Mexico](/mexico) |           73,258 |                    89,013 |                     698 |                     15,755 |                      123 |                                       22% |                                82,141 |                                 98,250 |
|                                 [Peru](/peru) |           31,283 |                    34,219 |                   1,053 |                      2,936 |                       90 |                                        9% |                                32,017 |                                 38,227 |
|                         [Colombia](/colombia) |           24,039 |                    29,779 |                     592 |                      5,740 |                      114 |                                       24% |                                26,998 |                                 34,849 |
|                                 [Iran](/iran) |           24,118 |                    28,577 |                     345 |                      4,459 |                       54 |                                       18% |                                25,936 |                                 33,290 |
|                             [Russia](/russia) |           19,270 |                    24,555 |                     168 |                      5,285 |                       36 |                                       27% |                                20,540 |                                 33,786 |
|                       [Argentina](/argentina) |           12,799 |                    20,420 |                     456 |                      7,621 |                      170 |                                       60% |                                16,327 |                                 25,256 |
|                 [South Africa](/south-africa) |           15,940 |                    18,382 |                     314 |                      2,442 |                       42 |                                       15% |                                16,947 |                                 20,953 |
|                               [Chile](/chile) |           12,254 |                    14,577 |                     769 |                      2,323 |                      123 |                                       19% |                                12,531 |                                 19,498 |
|                       [Indonesia](/indonesia) |            9,448 |                    13,559 |                      50 |                      4,111 |                       15 |                                       44% |                                11,343 |                                 18,250 |
|                           [Ecuador](/ecuador) |           11,084 |                    11,902 |                     685 |                        818 |                       47 |                                        7% |                                11,150 |                                 13,708 |
|                             [Canada](/canada) |            9,262 |                     9,525 |                     255 |                        263 |                        7 |                                        3% |                                 9,283 |                                 10,309 |
|                             [Turkey](/turkey) |            7,445 |                     9,189 |                     110 |                      1,744 |                       21 |                                       23% |                                 7,624 |                                 12,246 |
|                           [Bolivia](/bolivia) |            7,586 |                     9,171 |                     797 |                      1,585 |                      138 |                                       21% |                                 8,278 |                                 10,695 |
|                   [Philippines](/philippines) |            4,930 |                     7,987 |                      74 |                      3,057 |                       28 |                                       62% |                                 6,236 |                                 10,653 |
|                         [Pakistan](/pakistan) |            6,416 |                     6,579 |                      30 |                        163 |                        1 |                                        3% |                                 6,425 |                                  6,744 |
|                               [Egypt](/egypt) |            5,750 |                     6,522 |                      65 |                        772 |                        8 |                                       13% |                                 5,844 |                                  8,212 |
|                     [Bangladesh](/bangladesh) |            4,913 |                     6,276 |                      38 |                      1,363 |                        8 |                                       28% |                                 5,345 |                                  7,915 |
|                 [Saudi Arabia](/saudi-arabia) |            4,458 |                     5,490 |                     160 |                      1,032 |                       30 |                                       23% |                                 4,761 |                                  6,591 |
|                               [China](/china) |            4,737 |                     4,792 |                       3 |                         55 |                        0 |                                        1% |                                 4,737 |                                  5,244 |
|                           [Morocco](/morocco) |            1,795 |                     3,431 |                      94 |                      1,636 |                       45 |                                       91% |                                 2,431 |                                  4,924 |
|                         [Honduras](/honduras) |            2,166 |                     2,703 |                     277 |                        537 |                       55 |                                       25% |                                 2,332 |                                  3,285 |
|     [Dominican Republic](/dominican-republic) |            2,044 |                     2,673 |                     249 |                        629 |                       59 |                                       31% |                                 2,282 |                                  3,325 |
|                             [Panama](/panama) |            2,247 |                     2,604 |                     613 |                        357 |                       84 |                                       16% |                                 2,361 |                                  2,964 |
|                             [Israel](/israel) |            1,226 |                     1,947 |                     229 |                        721 |                       85 |                                       59% |                                 1,477 |                                  2,912 |
|                           [Algeria](/algeria) |            1,665 |                     1,932 |                      45 |                        267 |                        6 |                                       16% |                                 1,724 |                                  2,307 |
|                               [Japan](/japan) |            1,504 |                     1,835 |                      14 |                        331 |                        3 |                                       22% |                                 1,597 |                                  2,230 |
|                           [Nigeria](/nigeria) |            1,095 |                     1,230 |                       6 |                        135 |                        1 |                                       12% |                                 1,130 |                                  1,425 |
|                       [Australia](/australia) |              849 |                       992 |                      39 |                        143 |                        6 |                                       17% |                                   898 |                                  1,137 |
|                             [Kuwait](/kuwait) |              581 |                       693 |                     165 |                        112 |                       27 |                                       19% |                                   605 |                                    878 |
|                   [South Korea](/south-korea) |              383 |                       505 |                      10 |                        122 |                        2 |                                       32% |                                   398 |                                    737 |
| [United Arab Emirates](/united-arab-emirates) |              404 |                       474 |                      49 |                         70 |                        7 |                                       17% |                                   410 |                                    648 |
|                                 [Cuba](/cuba) |              113 |                       151 |                      13 |                         38 |                        3 |                                       34% |                                   123 |                                    209 |
|                         [Malaysia](/malaysia) |              130 |                       139 |                       4 |                          9 |                        0 |                                        7% |                                   132 |                                    149 |
