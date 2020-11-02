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

* **November 2 Update:** Our final October 5 projections estimated 231,000 (221-245k) US deaths by November 1, 2020. The true November 1 death toll as reported by Johns Hopkins University was 230,995.
* **October 5 - FINAL UPDATE:** We have released our final update. [Read Youyang Gu's blog post](https://youyanggu.com/blog/six-months-later) to read more about this decision. See our [Weekly Update on Twitter](https://twitter.com/youyanggu/status/1313564063679614982). Thank you for your support over the past six months.
* *September 29:* View our [updated historical performance](/about/#historical-performance).
* *September 28:* We will no longer be extending our projections past November 1. Our last forecast update will be on Monday, October 5.
* *August 27*: See a comprehensive list of our past Twitter threads [here](/about/#twitter-threads).
* *August 10:* See our [new findings](https://twitter.com/youyanggu/status/1292898685173534722) regarding the role of immunity, behavior, and interventions in the spread of COVID-19. We use Louisiana as a case study.
* *August 5:* We released a report, *[Estimating True Infections: A Simple Heuristic to Measure Implied Infection Fatality Rate](/estimating-true-infections)* that explains our findings regarding the relationship between true infections, reported cases, test positivity rate, and infection fatality rate for COVID-19. You can view a summary on [our Twitter](https://twitter.com/youyanggu/status/1291092311045283841).
* *June 24:* We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

## Current US Projections
### Updated Daily - Last Updated: October 5 (10pm ET):
<p align="center">
  Current Total (as of Oct 4): <b>209,791</b> deaths | Projected Total: <b>230,700 deaths by Nov 1, 2020</b> (Range: 221-245k)<br>
  Currently Infected (as of Oct 4): <b>1.2%</b> (1 in 85) | Total Infected (as of Oct 4): <b>16.1%</b> (1 in 6) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: October 5, 2020

|   US deaths surpass: |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|
|              225,000 |         <1% |        78% |
|              250,000 |         <1% |        <1% |
|              275,000 |         <1% |        <1% |
|              300,000 |         <1% |        <1% |

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
|             *[United States](/us)* |          209,791 |                   230,669 |                     695 |                     20,878 |                       63 |                                       10% |                               221,556 |                                244,811 |
|                 [New York](/us-ny) |           33,205 |                    33,671 |                   1,731 |                        466 |                       24 |                                        1% |                                33,219 |                                 35,772 |
|                    [Texas](/us-tx) |           16,320 |                    18,660 |                     644 |                      2,340 |                       81 |                                       14% |                                17,366 |                                 20,446 |
|               [California](/us-ca) |           16,147 |                    17,987 |                     455 |                      1,840 |                       47 |                                       11% |                                16,616 |                                 20,812 |
|                  [Florida](/us-fl) |           14,671 |                    17,153 |                     799 |                      2,482 |                      116 |                                       17% |                                15,698 |                                 19,411 |
|               [New Jersey](/us-nj) |           16,136 |                    16,357 |                   1,842 |                        221 |                       25 |                                        1% |                                16,143 |                                 17,075 |
|            [Massachusetts](/us-ma) |            9,510 |                    10,000 |                   1,439 |                        490 |                       71 |                                        5% |                                 9,553 |                                 10,817 |
|                 [Illinois](/us-il) |            9,040 |                     9,745 |                     769 |                        705 |                       56 |                                        8% |                                 9,201 |                                 10,714 |
|             [Pennsylvania](/us-pa) |            8,195 |                     8,852 |                     691 |                        657 |                       51 |                                        8% |                                 8,301 |                                  9,859 |
|                  [Georgia](/us-ga) |            7,162 |                     7,972 |                     751 |                        810 |                       76 |                                       11% |                                 7,367 |                                  9,172 |
|                 [Michigan](/us-mi) |            7,124 |                     7,456 |                     747 |                        332 |                       33 |                                        5% |                                 7,182 |                                  7,957 |
|                  [Arizona](/us-az) |            5,706 |                     6,050 |                     831 |                        344 |                       47 |                                        6% |                                 5,768 |                                  6,608 |
|                [Louisiana](/us-la) |            5,577 |                     5,998 |                   1,290 |                        421 |                       91 |                                        8% |                                 5,716 |                                  6,520 |
|                     [Ohio](/us-oh) |            4,925 |                     5,671 |                     485 |                        746 |                       64 |                                       15% |                                 5,123 |                                  6,629 |
|              [Connecticut](/us-ct) |            4,513 |                     4,596 |                   1,289 |                         83 |                       23 |                                        2% |                                 4,518 |                                  4,837 |
|           [North Carolina](/us-nc) |            3,634 |                     4,405 |                     420 |                        771 |                       74 |                                       21% |                                 3,945 |                                  5,143 |
|                 [Maryland](/us-md) |            3,958 |                     4,172 |                     690 |                        214 |                       35 |                                        5% |                                 3,982 |                                  4,556 |
|                  [Indiana](/us-in) |            3,674 |                     4,148 |                     616 |                        474 |                       70 |                                       13% |                                 3,732 |                                  4,882 |
|           [South Carolina](/us-sc) |            3,453 |                     3,929 |                     763 |                        476 |                       92 |                                       14% |                                 3,660 |                                  4,330 |
|                 [Virginia](/us-va) |            3,270 |                     3,718 |                     436 |                        448 |                       53 |                                       14% |                                 3,345 |                                  4,506 |
|              [Mississippi](/us-ms) |            3,013 |                     3,367 |                   1,131 |                        354 |                      119 |                                       12% |                                 3,139 |                                  3,788 |
|                [Tennessee](/us-tn) |            2,577 |                     3,176 |                     465 |                        599 |                       88 |                                       23% |                                 2,838 |                                  3,706 |
|                 [Missouri](/us-mo) |            2,259 |                     3,012 |                     491 |                        753 |                      123 |                                       33% |                                 2,579 |                                  3,678 |
|                  [Alabama](/us-al) |            2,558 |                     2,874 |                     586 |                        316 |                       64 |                                       12% |                                 2,667 |                                  3,241 |
|                [Minnesota](/us-mn) |            2,133 |                     2,453 |                     435 |                        320 |                       57 |                                       15% |                                 2,196 |                                  2,904 |
|               [Washington](/us-wa) |            2,142 |                     2,367 |                     311 |                        225 |                       30 |                                       11% |                                 2,171 |                                  2,795 |
|                 [Colorado](/us-co) |            2,068 |                     2,225 |                     386 |                        157 |                       27 |                                        8% |                                 2,079 |                                  2,523 |
|                [Wisconsin](/us-wi) |            1,377 |                     1,977 |                     340 |                        600 |                      103 |                                       44% |                                 1,638 |                                  2,517 |
|                 [Arkansas](/us-ar) |            1,425 |                     1,897 |                     629 |                        472 |                      156 |                                       33% |                                 1,647 |                                  2,294 |
|                   [Nevada](/us-nv) |            1,623 |                     1,796 |                     583 |                        173 |                       56 |                                       11% |                                 1,677 |                                  2,026 |
|                     [Iowa](/us-ia) |            1,387 |                     1,650 |                     523 |                        263 |                       83 |                                       19% |                                 1,476 |                                  1,965 |
|                 [Kentucky](/us-ky) |            1,209 |                     1,466 |                     328 |                        257 |                       57 |                                       21% |                                 1,306 |                                  1,711 |
|                 [Oklahoma](/us-ok) |            1,051 |                     1,308 |                     331 |                        257 |                       65 |                                       24% |                                 1,163 |                                  1,532 |
|             [Rhode Island](/us-ri) |            1,118 |                     1,198 |                   1,131 |                         80 |                       76 |                                        7% |                                 1,128 |                                  1,342 |
|               [New Mexico](/us-nm) |              892 |                       999 |                     476 |                        107 |                       51 |                                       12% |                                   919 |                                  1,160 |
|              [Puerto Rico](/us-pr) |              686 |                       882 |                     276 |                        196 |                       61 |                                       29% |                                   783 |                                  1,029 |
|                   [Kansas](/us-ks) |              690 |                       881 |                     302 |                        191 |                       65 |                                       28% |                                   762 |                                  1,066 |
|                 [Delaware](/us-de) |              645 |                       693 |                     712 |                         48 |                       49 |                                        7% |                                   652 |                                    773 |
|                   [Oregon](/us-or) |              572 |                       686 |                     163 |                        114 |                       27 |                                       20% |                                   610 |                                    815 |
|     [District of Columbia](/us-dc) |              631 |                       657 |                     931 |                         26 |                       36 |                                        4% |                                   635 |                                    713 |
|                 [Nebraska](/us-ne) |              501 |                       614 |                     317 |                        113 |                       58 |                                       22% |                                   536 |                                    744 |
|                     [Utah](/us-ut) |              478 |                       588 |                     183 |                        110 |                       34 |                                       23% |                                   522 |                                    679 |
|                    [Idaho](/us-id) |              482 |                       579 |                     324 |                         97 |                       54 |                                       20% |                                   527 |                                    654 |
|            [West Virginia](/us-wv) |              364 |                       501 |                     279 |                        137 |                       76 |                                       38% |                                   426 |                                    614 |
|             [North Dakota](/us-nd) |              274 |                       475 |                     624 |                        201 |                      264 |                                       74% |                                   384 |                                    626 |
|            [New Hampshire](/us-nh) |              443 |                       459 |                     337 |                         16 |                       12 |                                        4% |                                   445 |                                    511 |
|             [South Dakota](/us-sd) |              248 |                       365 |                     412 |                        117 |                      132 |                                       47% |                                   295 |                                    474 |
|                  [Montana](/us-mt) |              187 |                       294 |                     275 |                        107 |                      100 |                                       57% |                                   241 |                                    360 |
|                   [Hawaii](/us-hi) |              156 |                       220 |                     155 |                         64 |                       45 |                                       41% |                                   186 |                                    277 |
|                    [Maine](/us-me) |              142 |                       154 |                     115 |                         12 |                        9 |                                        9% |                                   144 |                                    179 |
|                   [Alaska](/us-ak) |               58 |                        86 |                     117 |                         28 |                       38 |                                       48% |                                    71 |                                    113 |
|                     [Guam](/us-gu) |               49 |                        77 |                     462 |                         28 |                      167 |                                       56% |                                    61 |                                    102 |
|                  [Wyoming](/us-wy) |               53 |                        71 |                     123 |                         18 |                       31 |                                       34% |                                    62 |                                     85 |
|                  [Vermont](/us-vt) |               58 |                        59 |                      95 |                          1 |                        2 |                                        2% |                                    58 |                                     63 |
|           [Virgin Islands](/us-vi) |               20 |                        22 |                     212 |                          2 |                       21 |                                       11% |                                    20 |                                     25 |
| [Northern Mariana Islands](/us-mp) |                2 |                         2 |                      45 |                          0 |                        9 |                                       24% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          201,470 |                   221,688 |                     374 |                     20,218 |                       34 |                                       10% |                               205,349 |                                272,318 |
| [United Kingdom](/united-kingdom) |           42,440 |                    44,747 |                     663 |                      2,307 |                       34 |                                        5% |                                42,498 |                                 52,905 |
|                   [Italy](/italy) |           35,986 |                    36,802 |                     610 |                        816 |                       14 |                                        2% |                                36,004 |                                 39,450 |
|                   [Spain](/spain) |           32,086 |                    36,769 |                     783 |                      4,683 |                      100 |                                       15% |                                32,754 |                                 47,327 |
|                 [France](/france) |           32,171 |                    35,315 |                     527 |                      3,144 |                       47 |                                       10% |                                32,209 |                                 51,525 |
|               [Belgium](/belgium) |           10,064 |                    10,557 |                     922 |                        493 |                       43 |                                        5% |                                10,097 |                                 12,110 |
|               [Germany](/germany) |            9,533 |                     9,988 |                     120 |                        455 |                        5 |                                        5% |                                 9,547 |                                 11,485 |
|       [Netherlands](/netherlands) |            6,508 |                     7,181 |                     416 |                        673 |                       39 |                                       10% |                                 6,529 |                                  9,150 |
|               [Ukraine](/ukraine) |            4,495 |                     6,660 |                     151 |                      2,165 |                       49 |                                       48% |                                 5,455 |                                  8,008 |
|               [Romania](/romania) |            5,003 |                     6,252 |                     322 |                      1,249 |                       64 |                                       25% |                                 5,547 |                                  7,484 |
|                 [Sweden](/sweden) |            5,895 |                     6,004 |                     587 |                        109 |                       11 |                                        2% |                                 5,901 |                                  6,394 |
|                 [Poland](/poland) |            2,630 |                     3,733 |                      98 |                      1,103 |                       29 |                                       42% |                                 2,995 |                                  5,328 |
|             [Portugal](/portugal) |            2,005 |                     2,275 |                     221 |                        270 |                       26 |                                       13% |                                 2,071 |                                  2,593 |
|       [Switzerland](/switzerland) |            2,077 |                     2,188 |                     255 |                        111 |                       13 |                                        5% |                                 2,103 |                                  2,383 |
|               [Ireland](/ireland) |            1,810 |                     1,890 |                     385 |                         80 |                       16 |                                        4% |                                 1,816 |                                  2,223 |
|               [Moldova](/moldova) |            1,366 |                     1,701 |                     421 |                        335 |                       83 |                                       25% |                                 1,510 |                                  1,999 |
|               [Czechia](/czechia) |              727 |                     1,453 |                     136 |                        726 |                       68 |                                      100% |                                 1,037 |                                  2,132 |
|               [Hungary](/hungary) |              822 |                     1,239 |                     127 |                        417 |                       43 |                                       51% |                                 1,044 |                                  1,543 |
|               [Belarus](/belarus) |              851 |                     1,036 |                     110 |                        185 |                       20 |                                       22% |                                   906 |                                  1,303 |
|             [Bulgaria](/bulgaria) |              844 |                     1,018 |                     145 |                        174 |                       25 |                                       21% |                                   923 |                                  1,168 |
|               [Austria](/austria) |              813 |                       951 |                     107 |                        138 |                       16 |                                       17% |                                   843 |                                  1,144 |
|                 [Serbia](/serbia) |              754 |                       776 |                     111 |                         22 |                        3 |                                        3% |                                   758 |                                    831 |
|               [Denmark](/denmark) |              658 |                       717 |                     123 |                         59 |                       10 |                                        9% |                                   666 |                                    851 |
|                 [Greece](/greece) |              409 |                       571 |                      53 |                        162 |                       15 |                                       40% |                                   480 |                                    730 |
|               [Croatia](/croatia) |              298 |                       389 |                      95 |                         91 |                       22 |                                       31% |                                   328 |                                    519 |
|               [Finland](/finland) |              345 |                       372 |                      67 |                         27 |                        5 |                                        8% |                                   354 |                                    404 |
|                 [Norway](/norway) |              275 |                       306 |                      57 |                         31 |                        6 |                                       11% |                                   285 |                                    338 |
|             [Slovenia](/slovenia) |              155 |                       195 |                      94 |                         40 |                       19 |                                       26% |                                   172 |                                    236 |
|         [Luxembourg](/luxembourg) |              125 |                       135 |                     219 |                         10 |                       16 |                                        8% |                                   127 |                                    156 |
|           [Lithuania](/lithuania) |               94 |                       115 |                      41 |                         21 |                        7 |                                       22% |                                   103 |                                    133 |
|             [Slovakia](/slovakia) |               55 |                       108 |                      20 |                         53 |                       10 |                                       97% |                                    85 |                                    153 |
|               [Estonia](/estonia) |               67 |                        82 |                      62 |                         15 |                       12 |                                       23% |                                    73 |                                     96 |
|                   [Malta](/malta) |               39 |                        78 |                     159 |                         39 |                       80 |                                      101% |                                    55 |                                    121 |
|                 [Latvia](/latvia) |               38 |                        47 |                      24 |                          9 |                        5 |                                       23% |                                    42 |                                     54 |
|                 [Cyprus](/cyprus) |               22 |                        24 |                      28 |                          2 |                        3 |                                       10% |                                    22 |                                     27 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        6 |                                       21% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          585,962 |                   682,035 |                     131 |                     96,073 |                       19 |                                       16% |                               629,860 |                                768,187 |
|                             [Brazil](/brazil) |          146,352 |                   162,887 |                     772 |                     16,535 |                       78 |                                       11% |                               153,103 |                                177,652 |
|                               [India](/india) |          101,782 |                   128,959 |                      94 |                     27,177 |                       20 |                                       27% |                               115,664 |                                144,935 |
|                             [Mexico](/mexico) |           79,088 |                    88,664 |                     695 |                      9,576 |                       75 |                                       12% |                                85,222 |                                 94,732 |
|                                 [Peru](/peru) |           32,609 |                    34,938 |                   1,075 |                      2,329 |                       72 |                                        7% |                                33,060 |                                 38,114 |
|                                 [Iran](/iran) |           26,957 |                    32,153 |                     388 |                      5,196 |                       63 |                                       19% |                                29,662 |                                 36,123 |
|                         [Colombia](/colombia) |           26,712 |                    30,568 |                     607 |                      3,856 |                       77 |                                       14% |                                28,597 |                                 34,544 |
|                       [Argentina](/argentina) |           21,018 |                    30,038 |                     671 |                      9,020 |                      201 |                                       43% |                                25,570 |                                 37,570 |
|                             [Russia](/russia) |           21,260 |                    25,755 |                     177 |                      4,495 |                       31 |                                       21% |                                23,838 |                                 33,154 |
|                 [South Africa](/south-africa) |           16,976 |                    18,349 |                     313 |                      1,373 |                       23 |                                        8% |                                17,334 |                                 20,481 |
|                               [Chile](/chile) |           12,979 |                    14,514 |                     766 |                      1,535 |                       81 |                                       12% |                                13,123 |                                 18,235 |
|                       [Indonesia](/indonesia) |           11,151 |                    14,258 |                      53 |                      3,107 |                       11 |                                       28% |                                12,375 |                                 16,735 |
|                           [Ecuador](/ecuador) |           11,647 |                    12,609 |                     726 |                        962 |                       55 |                                        8% |                                11,712 |                                 14,310 |
|                             [Turkey](/turkey) |            8,441 |                    10,478 |                     126 |                      2,037 |                       24 |                                       24% |                                 8,802 |                                 12,496 |
|                             [Canada](/canada) |            9,533 |                    10,221 |                     273 |                        688 |                       18 |                                        7% |                                 9,601 |                                 11,769 |
|                           [Bolivia](/bolivia) |            8,101 |                     8,927 |                     775 |                        826 |                       72 |                                       10% |                                 8,367 |                                  9,653 |
|                   [Philippines](/philippines) |            5,776 |                     7,575 |                      70 |                      1,799 |                       17 |                                       31% |                                 6,482 |                                  9,481 |
|                         [Pakistan](/pakistan) |            6,513 |                     6,726 |                      31 |                        213 |                        1 |                                        3% |                                 6,549 |                                  7,087 |
|                               [Egypt](/egypt) |            5,981 |                     6,406 |                      64 |                        425 |                        4 |                                        7% |                                 6,021 |                                  7,361 |
|                     [Bangladesh](/bangladesh) |            5,348 |                     6,055 |                      37 |                        707 |                        4 |                                       13% |                                 5,669 |                                  6,962 |
|                 [Saudi Arabia](/saudi-arabia) |            4,875 |                     5,598 |                     163 |                        723 |                       21 |                                       15% |                                 5,067 |                                  6,383 |
|                               [China](/china) |            4,739 |                     4,745 |                       3 |                          6 |                        0 |                                        0% |                                 4,739 |                                  4,798 |
|                           [Morocco](/morocco) |            2,330 |                     3,478 |                      95 |                      1,148 |                       31 |                                       49% |                                 2,855 |                                  4,405 |
|                         [Honduras](/honduras) |            2,422 |                     2,868 |                     294 |                        446 |                       46 |                                       18% |                                 2,529 |                                  3,408 |
|                             [Panama](/panama) |            2,423 |                     2,688 |                     633 |                        265 |                       62 |                                       11% |                                 2,512 |                                  3,020 |
|                             [Israel](/israel) |            1,719 |                     2,483 |                     291 |                        764 |                       90 |                                       44% |                                 1,984 |                                  3,449 |
|     [Dominican Republic](/dominican-republic) |            2,134 |                     2,287 |                     213 |                        153 |                       14 |                                        7% |                                 2,184 |                                  2,468 |
|                           [Algeria](/algeria) |            1,760 |                     1,925 |                      45 |                        165 |                        4 |                                        9% |                                 1,791 |                                  2,188 |
|                               [Japan](/japan) |            1,598 |                     1,757 |                      14 |                        159 |                        1 |                                       10% |                                 1,643 |                                  1,932 |
|                           [Nigeria](/nigeria) |            1,113 |                     1,172 |                       6 |                         59 |                        0 |                                        5% |                                 1,122 |                                  1,275 |
|                       [Australia](/australia) |              894 |                       951 |                      38 |                         57 |                        2 |                                        6% |                                   910 |                                  1,023 |
|                             [Kuwait](/kuwait) |              624 |                       703 |                     167 |                         79 |                       19 |                                       13% |                                   637 |                                    837 |
| [United Arab Emirates](/united-arab-emirates) |              426 |                       509 |                      52 |                         83 |                        8 |                                       19% |                                   430 |                                    650 |
|                   [South Korea](/south-korea) |              422 |                       488 |                      10 |                         66 |                        1 |                                       16% |                                   435 |                                    583 |
|                         [Malaysia](/malaysia) |              137 |                       160 |                       5 |                         23 |                        1 |                                       16% |                                   143 |                                    194 |
|                                 [Cuba](/cuba) |              122 |                       146 |                      13 |                         24 |                        2 |                                       20% |                                   128 |                                    180 |
