We present an intuitive COVID-19 model that adds machine learning techniques on top of a classic infectious disease model to make projections for infections and deaths for the US and 70 other countries. The countries our projections cover encompass 6.4 billion people and account for more than 95% of all global reported COVID-19 deaths.

Our infections estimates include all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of August, we estimate the true number of infected individuals in the US is roughly 4-8x higher than the reported cases. See our writeup, [Estimating True Infections](/estimating-true-infections), for a more detailed look into this subject. To get a sense of the number of individuals that are actively infectious, we recommend dividing the *"currently infected"* estimate by 2-4.

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

* **September 22:** [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1308498742451015680).
* **September 20:** View our [updated historical performance](/about/#historical-performance).
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: September 28 (2pm ET):
<p align="center">
  Current Total: <b>204,753</b> deaths | Projected Total: <b>230,000 deaths by Nov 1, 2020</b> (Range: 218-249k)<br>
  Currently Infected: <b>1.2%</b> (1 in 85) | Total Infected: <b>16.2%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 26, 2020

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              225,000 |        <1% |          2% |        64% |
|              250,000 |        <1% |         <1% |         2% |
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
|             *[United States](/us)* |          204,753 |                   230,054 |                     693 |                     25,301 |                       76 |                                       12% |                               218,891 |                                248,110 |
|                 [New York](/us-ny) |           33,131 |                    33,658 |                   1,730 |                        527 |                       27 |                                        2% |                                33,147 |                                 36,085 |
|               [California](/us-ca) |           15,606 |                    18,663 |                     472 |                      3,057 |                       77 |                                       20% |                                16,511 |                                 22,670 |
|                    [Texas](/us-tx) |           15,745 |                    18,344 |                     633 |                      2,599 |                       90 |                                       17% |                                16,957 |                                 20,658 |
|                  [Florida](/us-fl) |           14,032 |                    16,827 |                     783 |                      2,795 |                      130 |                                       20% |                                15,196 |                                 19,523 |
|               [New Jersey](/us-nj) |           16,106 |                    16,377 |                   1,844 |                        271 |                       30 |                                        2% |                                16,114 |                                 17,271 |
|            [Massachusetts](/us-ma) |            9,404 |                     9,764 |                   1,405 |                        360 |                       52 |                                        4% |                                 9,431 |                                 10,511 |
|                 [Illinois](/us-il) |            8,845 |                     9,622 |                     759 |                        777 |                       61 |                                        9% |                                 8,987 |                                 11,003 |
|             [Pennsylvania](/us-pa) |            8,086 |                     9,091 |                     710 |                      1,005 |                       78 |                                       12% |                                 8,139 |                                 10,707 |
|                  [Georgia](/us-ga) |            6,946 |                     8,385 |                     790 |                      1,439 |                      136 |                                       21% |                                 7,519 |                                  9,895 |
|                 [Michigan](/us-mi) |            7,044 |                     7,421 |                     743 |                        377 |                       38 |                                        5% |                                 7,089 |                                  8,190 |
|                  [Arizona](/us-az) |            5,623 |                     6,229 |                     856 |                        606 |                       83 |                                       11% |                                 5,773 |                                  7,146 |
|                [Louisiana](/us-la) |            5,465 |                     6,002 |                   1,291 |                        537 |                      115 |                                       10% |                                 5,645 |                                  6,725 |
|                     [Ohio](/us-oh) |            4,741 |                     5,572 |                     477 |                        831 |                       71 |                                       18% |                                 4,945 |                                  6,838 |
|              [Connecticut](/us-ct) |            4,501 |                     4,608 |                   1,292 |                        107 |                       30 |                                        2% |                                 4,509 |                                  4,918 |
|           [North Carolina](/us-nc) |            3,441 |                     4,476 |                     427 |                      1,035 |                       99 |                                       30% |                                 3,872 |                                  5,531 |
|                 [Maryland](/us-md) |            3,935 |                     4,173 |                     690 |                        238 |                       39 |                                        6% |                                 3,952 |                                  4,671 |
|                  [Indiana](/us-in) |            3,580 |                     3,975 |                     590 |                        395 |                       59 |                                       11% |                                 3,613 |                                  4,759 |
|           [South Carolina](/us-sc) |            3,326 |                     3,907 |                     759 |                        581 |                      113 |                                       17% |                                 3,586 |                                  4,414 |
|                 [Virginia](/us-va) |            3,157 |                     3,879 |                     454 |                        722 |                       85 |                                       23% |                                 3,346 |                                  4,832 |
|              [Mississippi](/us-ms) |            2,919 |                     3,350 |                   1,126 |                        431 |                      145 |                                       15% |                                 3,070 |                                  3,904 |
|                [Tennessee](/us-tn) |            2,377 |                     3,055 |                     447 |                        678 |                       99 |                                       29% |                                 2,664 |                                  3,750 |
|                  [Alabama](/us-al) |            2,501 |                     2,859 |                     583 |                        358 |                       73 |                                       14% |                                 2,623 |                                  3,281 |
|                 [Missouri](/us-mo) |            2,053 |                     2,815 |                     459 |                        762 |                      124 |                                       37% |                                 2,366 |                                  3,502 |
|               [Washington](/us-wa) |            2,100 |                     2,480 |                     326 |                        380 |                       50 |                                       18% |                                 2,153 |                                  3,133 |
|                [Minnesota](/us-mn) |            2,060 |                     2,388 |                     423 |                        328 |                       58 |                                       16% |                                 2,116 |                                  2,859 |
|                 [Colorado](/us-co) |            2,041 |                     2,228 |                     387 |                        187 |                       32 |                                        9% |                                 2,054 |                                  2,611 |
|                   [Nevada](/us-nv) |            1,585 |                     1,812 |                     588 |                        227 |                       74 |                                       14% |                                 1,659 |                                  2,085 |
|                 [Arkansas](/us-ar) |            1,308 |                     1,737 |                     575 |                        429 |                      142 |                                       33% |                                 1,509 |                                  2,110 |
|                     [Iowa](/us-ia) |            1,316 |                     1,597 |                     506 |                        281 |                       89 |                                       21% |                                 1,408 |                                  1,956 |
|                [Wisconsin](/us-wi) |            1,281 |                     1,594 |                     274 |                        313 |                       54 |                                       24% |                                 1,398 |                                  1,918 |
|                 [Kentucky](/us-ky) |            1,157 |                     1,469 |                     329 |                        312 |                       70 |                                       27% |                                 1,263 |                                  1,830 |
|                 [Oklahoma](/us-ok) |            1,006 |                     1,320 |                     334 |                        314 |                       79 |                                       31% |                                 1,147 |                                  1,619 |
|             [Rhode Island](/us-ri) |            1,107 |                     1,180 |                   1,114 |                         73 |                       69 |                                        7% |                                 1,114 |                                  1,336 |
|               [New Mexico](/us-nm) |              870 |                     1,025 |                     489 |                        155 |                       74 |                                       18% |                                   916 |                                  1,242 |
|              [Puerto Rico](/us-pr) |              644 |                       906 |                     284 |                        262 |                       82 |                                       41% |                                   761 |                                  1,159 |
|                   [Kansas](/us-ks) |              635 |                       858 |                     294 |                        223 |                       76 |                                       35% |                                   717 |                                  1,105 |
|                   [Oregon](/us-or) |              543 |                       697 |                     165 |                        154 |                       37 |                                       28% |                                   598 |                                    865 |
|                 [Delaware](/us-de) |              633 |                       669 |                     687 |                         36 |                       37 |                                        6% |                                   637 |                                    742 |
|     [District of Columbia](/us-dc) |              624 |                       643 |                     911 |                         19 |                       27 |                                        3% |                                   627 |                                    681 |
|                 [Nebraska](/us-ne) |              470 |                       590 |                     305 |                        120 |                       62 |                                       26% |                                   499 |                                    730 |
|                    [Idaho](/us-id) |              460 |                       569 |                     318 |                        109 |                       61 |                                       24% |                                   508 |                                    669 |
|                     [Utah](/us-ut) |              453 |                       554 |                     173 |                        101 |                       31 |                                       22% |                                   489 |                                    643 |
|            [West Virginia](/us-wv) |              339 |                       516 |                     288 |                        177 |                       99 |                                       52% |                                   412 |                                    719 |
|            [New Hampshire](/us-nh) |              439 |                       468 |                     344 |                         29 |                       21 |                                        7% |                                   440 |                                    565 |
|             [North Dakota](/us-nd) |              231 |                       413 |                     542 |                        182 |                      239 |                                       79% |                                   330 |                                    549 |
|             [South Dakota](/us-sd) |              218 |                       320 |                     362 |                        102 |                      116 |                                       47% |                                   244 |                                    445 |
|                  [Montana](/us-mt) |              173 |                       297 |                     278 |                        124 |                      116 |                                       71% |                                   232 |                                    404 |
|                   [Hawaii](/us-hi) |              132 |                       206 |                     145 |                         74 |                       52 |                                       56% |                                   164 |                                    288 |
|                    [Maine](/us-me) |              140 |                       160 |                     119 |                         20 |                       15 |                                       14% |                                   143 |                                    200 |
|                   [Alaska](/us-ak) |               56 |                        87 |                     119 |                         31 |                       43 |                                       56% |                                    70 |                                    126 |
|                     [Guam](/us-gu) |               39 |                        67 |                     406 |                         28 |                      171 |                                       73% |                                    52 |                                     92 |
|                  [Wyoming](/us-wy) |               50 |                        64 |                     111 |                         14 |                       24 |                                       28% |                                    55 |                                     80 |
|                  [Vermont](/us-vt) |               58 |                        61 |                      98 |                          3 |                        5 |                                        5% |                                    58 |                                     69 |
|           [Virgin Islands](/us-vi) |               19 |                        24 |                     229 |                          5 |                       48 |                                       27% |                                    21 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      47 |                          1 |                       11 |                                       30% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          197,629 |                   221,937 |                     374 |                     24,308 |                       41 |                                       12% |                               201,962 |                                283,196 |
| [United Kingdom](/united-kingdom) |           42,060 |                    45,360 |                     672 |                      3,300 |                       49 |                                        8% |                                42,151 |                                 56,731 |
|                   [Spain](/spain) |           31,232 |                    36,892 |                     786 |                      5,660 |                      121 |                                       18% |                                31,952 |                                 49,723 |
|                   [Italy](/italy) |           35,818 |                    36,776 |                     609 |                        958 |                       16 |                                        3% |                                35,839 |                                 40,191 |
|                 [France](/france) |           31,675 |                    35,281 |                     526 |                      3,606 |                       54 |                                       11% |                                31,723 |                                 52,938 |
|               [Belgium](/belgium) |            9,974 |                    10,473 |                     914 |                        499 |                       44 |                                        5% |                                 9,999 |                                 12,449 |
|               [Germany](/germany) |            9,459 |                     9,984 |                     120 |                        525 |                        6 |                                        6% |                                 9,476 |                                 11,769 |
|       [Netherlands](/netherlands) |            6,415 |                     7,472 |                     432 |                      1,057 |                       61 |                                       16% |                                 6,468 |                                 10,064 |
|               [Ukraine](/ukraine) |            3,988 |                     6,519 |                     148 |                      2,531 |                       58 |                                       63% |                                 5,090 |                                  8,656 |
|               [Romania](/romania) |            4,687 |                     6,219 |                     320 |                      1,532 |                       79 |                                       33% |                                 5,393 |                                  7,644 |
|                 [Sweden](/sweden) |            5,880 |                     6,013 |                     588 |                        133 |                       13 |                                        2% |                                 5,893 |                                  6,362 |
|                 [Poland](/poland) |            2,424 |                     3,300 |                      87 |                        876 |                       23 |                                       36% |                                 2,695 |                                  4,333 |
|             [Portugal](/portugal) |            1,944 |                     2,247 |                     219 |                        303 |                       29 |                                       16% |                                 2,014 |                                  2,622 |
|       [Switzerland](/switzerland) |            2,064 |                     2,215 |                     258 |                        151 |                       18 |                                        7% |                                 2,097 |                                  2,482 |
|               [Ireland](/ireland) |            1,802 |                     1,922 |                     392 |                        120 |                       24 |                                        7% |                                 1,810 |                                  2,386 |
|               [Moldova](/moldova) |            1,279 |                     1,683 |                     416 |                        404 |                      100 |                                       32% |                                 1,439 |                                  2,068 |
|               [Czechia](/czechia) |              591 |                     1,419 |                     133 |                        828 |                       78 |                                      140% |                                   931 |                                  2,232 |
|               [Hungary](/hungary) |              730 |                     1,097 |                     112 |                        367 |                       38 |                                       50% |                                   902 |                                  1,407 |
|               [Belarus](/belarus) |              813 |                     1,050 |                     111 |                        237 |                       25 |                                       29% |                                   883 |                                  1,386 |
|             [Bulgaria](/bulgaria) |              789 |                       969 |                     138 |                        180 |                       26 |                                       23% |                                   877 |                                  1,123 |
|               [Austria](/austria) |              787 |                       964 |                     109 |                        177 |                       20 |                                       23% |                                   822 |                                  1,298 |
|                 [Serbia](/serbia) |              746 |                       799 |                     115 |                         53 |                        8 |                                        7% |                                   759 |                                    877 |
|               [Denmark](/denmark) |              648 |                       792 |                     136 |                        144 |                       25 |                                       22% |                                   671 |                                  1,190 |
|                 [Greece](/greece) |              376 |                       696 |                      65 |                        320 |                       30 |                                       85% |                                   500 |                                  1,027 |
|               [Finland](/finland) |              343 |                       379 |                      69 |                         36 |                        6 |                                       10% |                                   355 |                                    431 |
|               [Croatia](/croatia) |              269 |                       368 |                      90 |                         99 |                       24 |                                       37% |                                   303 |                                    516 |
|                 [Norway](/norway) |              270 |                       305 |                      57 |                         35 |                        7 |                                       13% |                                   282 |                                    344 |
|             [Slovenia](/slovenia) |              146 |                       188 |                      90 |                         42 |                       20 |                                       29% |                                   162 |                                    234 |
|         [Luxembourg](/luxembourg) |              124 |                       136 |                     221 |                         12 |                       19 |                                        9% |                                   127 |                                    154 |
|           [Lithuania](/lithuania) |               89 |                       108 |                      39 |                         19 |                        7 |                                       21% |                                    96 |                                    126 |
|               [Estonia](/estonia) |               64 |                        79 |                      60 |                         15 |                       11 |                                       24% |                                    71 |                                     94 |
|             [Slovakia](/slovakia) |               44 |                        78 |                      14 |                         34 |                        6 |                                       78% |                                    60 |                                    110 |
|                   [Malta](/malta) |               31 |                        73 |                     149 |                         42 |                       86 |                                      137% |                                    50 |                                    132 |
|                 [Latvia](/latvia) |               36 |                        44 |                      23 |                          8 |                        4 |                                       22% |                                    39 |                                     51 |
|                 [Cyprus](/cyprus) |               22 |                        25 |                      29 |                          3 |                        4 |                                       15% |                                    23 |                                     30 |
|               [Iceland](/iceland) |               10 |                        13 |                      37 |                          3 |                        8 |                                       26% |                                    10 |                                     16 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          554,273 |                   679,809 |                     131 |                    125,536 |                       24 |                                       23% |                               614,214 |                                784,207 |
|                             [Brazil](/brazil) |          141,406 |                   161,329 |                     764 |                     19,923 |                       94 |                                       14% |                               152,174 |                                176,541 |
|                               [India](/india) |           93,379 |                   134,607 |                      99 |                     41,228 |                       30 |                                       44% |                               111,032 |                                157,266 |
|                             [Mexico](/mexico) |           76,243 |                    89,050 |                     698 |                     12,807 |                      100 |                                       17% |                                84,518 |                                 96,688 |
|                                 [Peru](/peru) |           32,037 |                    34,792 |                   1,070 |                      2,755 |                       85 |                                        9% |                                33,276 |                                 38,101 |
|                                 [Iran](/iran) |           25,394 |                    30,948 |                     373 |                      5,554 |                       67 |                                       22% |                                28,008 |                                 35,413 |
|                         [Colombia](/colombia) |           25,296 |                    29,838 |                     593 |                      4,542 |                       90 |                                       18% |                                27,847 |                                 33,852 |
|                       [Argentina](/argentina) |           15,543 |                    26,136 |                     584 |                     10,593 |                      237 |                                       68% |                                21,536 |                                 34,380 |
|                             [Russia](/russia) |           20,140 |                    25,569 |                     175 |                      5,429 |                       37 |                                       27% |                                23,188 |                                 34,583 |
|                 [South Africa](/south-africa) |           16,376 |                    17,969 |                     307 |                      1,593 |                       27 |                                       10% |                                16,862 |                                 20,200 |
|                       [Indonesia](/indonesia) |           10,308 |                    14,898 |                      55 |                      4,590 |                       17 |                                       45% |                                13,113 |                                 19,552 |
|                               [Chile](/chile) |           12,591 |                    14,517 |                     766 |                      1,926 |                      102 |                                       15% |                                12,789 |                                 18,840 |
|                           [Ecuador](/ecuador) |           11,273 |                    12,349 |                     711 |                      1,076 |                       62 |                                       10% |                                11,359 |                                 14,157 |
|                             [Turkey](/turkey) |            7,929 |                    10,533 |                     126 |                      2,604 |                       31 |                                       33% |                                 8,381 |                                 14,165 |
|                             [Canada](/canada) |            9,313 |                     9,755 |                     261 |                        442 |                       12 |                                        5% |                                 9,347 |                                 11,172 |
|                           [Bolivia](/bolivia) |            7,828 |                     8,754 |                     760 |                        926 |                       80 |                                       12% |                                 8,209 |                                  9,358 |
|                   [Philippines](/philippines) |            5,284 |                     7,520 |                      70 |                      2,236 |                       21 |                                       42% |                                 6,215 |                                  9,497 |
|                         [Pakistan](/pakistan) |            6,457 |                     6,741 |                      31 |                        284 |                        1 |                                        4% |                                 6,505 |                                  7,207 |
|                               [Egypt](/egypt) |            5,869 |                     6,534 |                      65 |                        665 |                        7 |                                       11% |                                 5,945 |                                  7,932 |
|                     [Bangladesh](/bangladesh) |            5,129 |                     6,005 |                      37 |                        876 |                        5 |                                       17% |                                 5,456 |                                  7,015 |
|                 [Saudi Arabia](/saudi-arabia) |            4,655 |                     5,322 |                     155 |                        667 |                       19 |                                       14% |                                 4,879 |                                  6,064 |
|                               [China](/china) |            4,739 |                     4,788 |                       3 |                         49 |                        0 |                                        1% |                                 4,739 |                                  5,186 |
|                           [Morocco](/morocco) |            2,041 |                     3,472 |                      95 |                      1,431 |                       39 |                                       70% |                                 2,625 |                                  4,681 |
|                             [Panama](/panama) |            2,323 |                     2,825 |                     665 |                        502 |                      118 |                                       22% |                                 2,667 |                                  3,132 |
|                         [Honduras](/honduras) |            2,288 |                     2,787 |                     286 |                        499 |                       51 |                                       22% |                                 2,428 |                                  3,336 |
|     [Dominican Republic](/dominican-republic) |            2,093 |                     2,549 |                     237 |                        456 |                       42 |                                       22% |                                 2,259 |                                  3,060 |
|                             [Israel](/israel) |            1,441 |                     2,292 |                     269 |                        851 |                      100 |                                       59% |                                 1,746 |                                  3,431 |
|                           [Algeria](/algeria) |            1,711 |                     1,925 |                      45 |                        214 |                        5 |                                       13% |                                 1,755 |                                  2,242 |
|                               [Japan](/japan) |            1,547 |                     1,788 |                      14 |                        241 |                        2 |                                       16% |                                 1,613 |                                  2,074 |
|                           [Nigeria](/nigeria) |            1,106 |                     1,209 |                       6 |                        103 |                        1 |                                        9% |                                 1,132 |                                  1,367 |
|                       [Australia](/australia) |              872 |                       965 |                      38 |                         93 |                        4 |                                       11% |                                   902 |                                  1,063 |
|                             [Kuwait](/kuwait) |              597 |                       733 |                     174 |                        136 |                       32 |                                       23% |                                   614 |                                    914 |
|                   [South Korea](/south-korea) |              401 |                       509 |                      10 |                        108 |                        2 |                                       27% |                                   415 |                                    699 |
| [United Arab Emirates](/united-arab-emirates) |              411 |                       507 |                      52 |                         96 |                       10 |                                       23% |                                   416 |                                    686 |
|                                 [Cuba](/cuba) |              120 |                       155 |                      14 |                         35 |                        3 |                                       29% |                                   129 |                                    204 |
|                         [Malaysia](/malaysia) |              133 |                       141 |                       4 |                          8 |                        0 |                                        6% |                                   135 |                                    149 |
