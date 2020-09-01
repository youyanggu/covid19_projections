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
### Updated Daily - Last Updated: September 1 (3pm ET):
<p align="center">
  Current Total: <b>183,594</b> deaths | Projected Total: <b>219,100 deaths by Nov 1, 2020</b> (Range: 205-240k)<br>
  Currently Infected: <b>1.2%</b> (1 in 80) | Total Infected: <b>14.4%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 1, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 24, 2020 |

<br>

|   US deaths surpass: |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|              200,000 |        <1% |          2% |        85% |         99% |        99% |
|              225,000 |        <1% |         <1% |        <1% |          4% |        19% |
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
|             *[United States](/us)* |          183,594 |                   219,110 |                     660 |                     35,516 |                      107 |                                       19% |                               205,391 |                                239,472 |
|                 [New York](/us-ny) |           32,957 |                    33,354 |                   1,715 |                        397 |                       20 |                                        1% |                                32,969 |                                 35,429 |
|                    [Texas](/us-tx) |           12,779 |                    18,199 |                     628 |                      5,420 |                      187 |                                       42% |                                15,684 |                                 21,489 |
|               [California](/us-ca) |           13,022 |                    18,067 |                     457 |                      5,045 |                      128 |                                       39% |                                15,318 |                                 22,805 |
|               [New Jersey](/us-nj) |           15,945 |                    16,159 |                   1,819 |                        214 |                       24 |                                        1% |                                15,961 |                                 16,846 |
|                  [Florida](/us-fl) |           11,187 |                    14,327 |                     667 |                      3,140 |                      146 |                                       28% |                                12,689 |                                 16,502 |
|            [Massachusetts](/us-ma) |            9,060 |                     9,681 |                   1,393 |                        621 |                       89 |                                        7% |                                 9,120 |                                 10,914 |
|                 [Illinois](/us-il) |            8,235 |                     9,260 |                     731 |                      1,025 |                       81 |                                       12% |                                 8,350 |                                 10,843 |
|             [Pennsylvania](/us-pa) |            7,659 |                     8,401 |                     656 |                        742 |                       58 |                                       10% |                                 7,699 |                                  9,944 |
|                  [Georgia](/us-ga) |            5,633 |                     7,873 |                     742 |                      2,240 |                      211 |                                       40% |                                 6,749 |                                  9,597 |
|                 [Michigan](/us-mi) |            6,753 |                     7,266 |                     728 |                        513 |                       51 |                                        8% |                                 6,800 |                                  8,154 |
|                  [Arizona](/us-az) |            5,029 |                     5,946 |                     817 |                        917 |                      126 |                                       18% |                                 5,416 |                                  6,733 |
|                [Louisiana](/us-la) |            4,950 |                     5,853 |                   1,259 |                        903 |                      194 |                                       18% |                                 5,319 |                                  6,705 |
|                     [Ohio](/us-oh) |            4,139 |                     4,932 |                     422 |                        793 |                       68 |                                       19% |                                 4,329 |                                  5,945 |
|              [Connecticut](/us-ct) |            4,465 |                     4,569 |                   1,282 |                        104 |                       29 |                                        2% |                                 4,476 |                                  4,881 |
|                 [Maryland](/us-md) |            3,755 |                     4,166 |                     689 |                        411 |                       68 |                                       11% |                                 3,793 |                                  4,952 |
|           [North Carolina](/us-nc) |            2,702 |                     3,845 |                     367 |                      1,143 |                      109 |                                       42% |                                 3,215 |                                  4,936 |
|                  [Indiana](/us-in) |            3,296 |                     3,798 |                     564 |                        502 |                       75 |                                       15% |                                 3,330 |                                  4,782 |
|           [South Carolina](/us-sc) |            2,720 |                     3,738 |                     726 |                      1,018 |                      198 |                                       37% |                                 3,221 |                                  4,524 |
|              [Mississippi](/us-ms) |            2,473 |                     3,221 |                   1,082 |                        748 |                      251 |                                       30% |                                 2,809 |                                  3,830 |
|                 [Virginia](/us-va) |            2,580 |                     3,175 |                     372 |                        595 |                       70 |                                       23% |                                 2,623 |                                  4,077 |
|                  [Alabama](/us-al) |            2,182 |                     2,850 |                     581 |                        668 |                      136 |                                       31% |                                 2,486 |                                  3,427 |
|                [Tennessee](/us-tn) |            1,754 |                     2,807 |                     411 |                      1,053 |                      154 |                                       60% |                                 2,284 |                                  3,646 |
|               [Washington](/us-wa) |            1,915 |                     2,356 |                     309 |                        441 |                       58 |                                       23% |                                 2,014 |                                  2,940 |
|                [Minnesota](/us-mn) |            1,866 |                     2,291 |                     406 |                        425 |                       75 |                                       23% |                                 1,936 |                                  2,896 |
|                 [Colorado](/us-co) |            1,945 |                     2,141 |                     372 |                        196 |                       34 |                                       10% |                                 1,958 |                                  2,685 |
|                 [Missouri](/us-mo) |            1,547 |                     2,138 |                     348 |                        591 |                       96 |                                       38% |                                 1,771 |                                  2,772 |
|                   [Nevada](/us-nv) |            1,305 |                     1,889 |                     613 |                        584 |                      189 |                                       45% |                                 1,595 |                                  2,305 |
|                     [Iowa](/us-ia) |            1,120 |                     1,775 |                     563 |                        655 |                      208 |                                       58% |                                 1,325 |                                  2,821 |
|                [Wisconsin](/us-wi) |            1,122 |                     1,531 |                     263 |                        409 |                       70 |                                       36% |                                 1,282 |                                  1,974 |
|                 [Kentucky](/us-ky) |              933 |                     1,341 |                     300 |                        408 |                       91 |                                       44% |                                 1,091 |                                  1,745 |
|                 [Arkansas](/us-ar) |              797 |                     1,287 |                     427 |                        490 |                      162 |                                       62% |                                 1,035 |                                  1,684 |
|                 [Oklahoma](/us-ok) |              800 |                     1,277 |                     323 |                        477 |                      120 |                                       60% |                                 1,008 |                                  1,713 |
|             [Rhode Island](/us-ri) |            1,048 |                     1,132 |                   1,068 |                         84 |                       79 |                                        8% |                                 1,057 |                                  1,303 |
|               [New Mexico](/us-nm) |              779 |                       945 |                     451 |                        166 |                       79 |                                       21% |                                   837 |                                  1,118 |
|              [Puerto Rico](/us-pr) |              434 |                       845 |                     265 |                        411 |                      129 |                                       95% |                                   618 |                                  1,204 |
|                   [Oregon](/us-or) |              459 |                       740 |                     175 |                        281 |                       67 |                                       61% |                                   573 |                                  1,030 |
|                 [Delaware](/us-de) |              605 |                       657 |                     674 |                         52 |                       53 |                                        9% |                                   611 |                                    752 |
|                   [Kansas](/us-ks) |              451 |                       644 |                     221 |                        193 |                       66 |                                       43% |                                   526 |                                    856 |
|     [District of Columbia](/us-dc) |              607 |                       640 |                     907 |                         33 |                       47 |                                        5% |                                   612 |                                    704 |
|                    [Idaho](/us-id) |              361 |                       632 |                     354 |                        271 |                      152 |                                       75% |                                   494 |                                    850 |
|                     [Utah](/us-ut) |              407 |                       593 |                     185 |                        186 |                       58 |                                       46% |                                   488 |                                    770 |
|                 [Nebraska](/us-ne) |              397 |                       527 |                     272 |                        130 |                       67 |                                       33% |                                   432 |                                    687 |
|            [New Hampshire](/us-nh) |              432 |                       463 |                     341 |                         31 |                       23 |                                        7% |                                   435 |                                    534 |
|            [West Virginia](/us-wv) |              215 |                       421 |                     235 |                        206 |                      115 |                                       96% |                                   303 |                                    625 |
|             [South Dakota](/us-sd) |              167 |                       275 |                     311 |                        108 |                      122 |                                       65% |                                   179 |                                    516 |
|             [North Dakota](/us-nd) |              143 |                       245 |                     321 |                        102 |                      133 |                                       71% |                                   181 |                                    362 |
|                   [Hawaii](/us-hi) |               70 |                       200 |                     142 |                        130 |                       92 |                                      186% |                                   116 |                                    374 |
|                  [Montana](/us-mt) |              104 |                       199 |                     186 |                         95 |                       89 |                                       91% |                                   144 |                                    291 |
|                    [Maine](/us-me) |              132 |                       150 |                     112 |                         18 |                       13 |                                       14% |                                   136 |                                    175 |
|                   [Alaska](/us-ak) |               37 |                        74 |                     101 |                         37 |                       50 |                                       99% |                                    53 |                                    112 |
|                  [Vermont](/us-vt) |               58 |                        67 |                     108 |                          9 |                       15 |                                       16% |                                    60 |                                     82 |
|                  [Wyoming](/us-wy) |               37 |                        59 |                     102 |                         22 |                       38 |                                       60% |                                    46 |                                     86 |
|                     [Guam](/us-gu) |               10 |                        47 |                     282 |                         37 |                      222 |                                      367% |                                    23 |                                    100 |
|           [Virgin Islands](/us-vi) |               14 |                        40 |                     383 |                         26 |                      249 |                                      187% |                                    26 |                                     64 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      53 |                          1 |                       16 |                                       45% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          188,916 |                   202,582 |                     342 |                     13,666 |                      805 |                                        7% |                               191,950 |                                233,394 |
| [United Kingdom](/united-kingdom) |           41,589 |                    42,421 |                     628 |                        832 |                       12 |                                        2% |                                41,618 |                                 45,690 |
|                   [Italy](/italy) |           35,483 |                    36,046 |                     597 |                        563 |                        9 |                                        2% |                                35,508 |                                 38,297 |
|                 [France](/france) |           30,640 |                    31,872 |                     476 |                      1,232 |                       18 |                                        4% |                                30,680 |                                 36,959 |
|                   [Spain](/spain) |           29,094 |                    30,918 |                     659 |                      1,824 |                       39 |                                        6% |                                29,136 |                                 36,525 |
|               [Belgium](/belgium) |            9,895 |                    10,170 |                     888 |                        275 |                       24 |                                        3% |                                 9,922 |                                 11,161 |
|               [Germany](/germany) |            9,303 |                     9,772 |                     118 |                        469 |                        6 |                                        5% |                                 9,337 |                                 11,404 |
|       [Netherlands](/netherlands) |            6,252 |                     6,524 |                     377 |                        272 |                       16 |                                        4% |                                 6,272 |                                  7,612 |
|               [Romania](/romania) |            3,621 |                     5,891 |                     303 |                      2,270 |                      117 |                                       63% |                                 4,558 |                                  8,404 |
|                 [Sweden](/sweden) |            5,808 |                     5,841 |                     571 |                         33 |                        3 |                                        1% |                                 5,813 |                                  5,922 |
|               [Ukraine](/ukraine) |            2,605 |                     5,229 |                     119 |                      2,624 |                       60 |                                      101% |                                 3,508 |                                  8,546 |
|                 [Poland](/poland) |            2,039 |                     2,747 |                      72 |                        708 |                       19 |                                       35% |                                 2,256 |                                  3,731 |
|       [Switzerland](/switzerland) |            2,006 |                     2,091 |                     243 |                         85 |                       10 |                                        4% |                                 2,020 |                                  2,332 |
|             [Portugal](/portugal) |            1,822 |                     1,999 |                     195 |                        177 |                       17 |                                       10% |                                 1,830 |                                  2,451 |
|               [Ireland](/ireland) |            1,777 |                     1,831 |                     373 |                         54 |                       11 |                                        3% |                                 1,786 |                                  1,985 |
|               [Moldova](/moldova) |              995 |                     1,358 |                     336 |                        363 |                       90 |                                       36% |                                 1,129 |                                  1,810 |
|             [Bulgaria](/bulgaria) |              629 |                     1,248 |                     178 |                        619 |                       88 |                                       98% |                                   853 |                                  1,935 |
|               [Belarus](/belarus) |              681 |                       985 |                     104 |                        304 |                       32 |                                       45% |                                   767 |                                  1,456 |
|                 [Serbia](/serbia) |              713 |                       896 |                     129 |                        183 |                       26 |                                       26% |                                   782 |                                  1,061 |
|               [Austria](/austria) |              733 |                       790 |                      89 |                         57 |                        6 |                                        8% |                                   743 |                                    932 |
|               [Denmark](/denmark) |              624 |                       668 |                     115 |                         44 |                        8 |                                        7% |                                   634 |                                    788 |
|               [Hungary](/hungary) |              615 |                       667 |                      68 |                         52 |                        5 |                                        8% |                                   620 |                                    800 |
|               [Czechia](/czechia) |              424 |                       543 |                      51 |                        119 |                       11 |                                       28% |                                   451 |                                    740 |
|                 [Greece](/greece) |              266 |                       496 |                      46 |                        230 |                       21 |                                       86% |                                   345 |                                    801 |
|               [Finland](/finland) |              336 |                       360 |                      65 |                         24 |                        4 |                                        7% |                                   340 |                                    426 |
|                 [Norway](/norway) |              264 |                       291 |                      54 |                         27 |                        5 |                                       10% |                                   270 |                                    359 |
|               [Croatia](/croatia) |              186 |                       291 |                      71 |                        105 |                       26 |                                       56% |                                   222 |                                    437 |
|             [Slovenia](/slovenia) |              133 |                       157 |                      76 |                         24 |                       12 |                                       18% |                                   137 |                                    203 |
|         [Luxembourg](/luxembourg) |              124 |                       150 |                     245 |                         26 |                       43 |                                       21% |                                   133 |                                    187 |
|           [Lithuania](/lithuania) |               86 |                       107 |                      38 |                         21 |                        7 |                                       24% |                                    91 |                                    140 |
|               [Estonia](/estonia) |               64 |                        71 |                      54 |                          7 |                        6 |                                       11% |                                    68 |                                     81 |
|             [Slovakia](/slovakia) |               33 |                        43 |                       8 |                         10 |                        2 |                                       31% |                                    35 |                                     64 |
|                 [Latvia](/latvia) |               34 |                        43 |                      22 |                          9 |                        5 |                                       26% |                                    36 |                                     57 |
|                   [Malta](/malta) |               12 |                        29 |                      59 |                         17 |                       34 |                                      141% |                                    18 |                                     52 |
|                 [Cyprus](/cyprus) |               20 |                        26 |                      29 |                          6 |                        7 |                                       29% |                                    22 |                                     31 |
|               [Iceland](/iceland) |               10 |                        12 |                      36 |                          2 |                        6 |                                       21% |                                    10 |                                     15 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          448,650 |                   642,405 |                     124 |                    193,755 |                    2,404 |                                       43% |                               522,682 |                                864,425 |
|                             [Brazil](/brazil) |          121,381 |                   161,228 |                     764 |                     39,847 |                      189 |                                       33% |                               137,093 |                                197,009 |
|                               [India](/india) |           65,288 |                   123,368 |                      90 |                     58,080 |                       43 |                                       89% |                                88,356 |                                193,637 |
|                             [Mexico](/mexico) |           64,414 |                    87,289 |                     684 |                     22,875 |                      179 |                                       36% |                                76,374 |                                106,975 |
|                                 [Peru](/peru) |           28,788 |                    34,741 |                   1,069 |                      5,953 |                      183 |                                       21% |                                30,460 |                                 41,907 |
|                         [Colombia](/colombia) |           19,662 |                    31,076 |                     617 |                     11,414 |                      227 |                                       58% |                                24,518 |                                 41,415 |
|                                 [Iran](/iran) |           21,571 |                    27,040 |                     326 |                      5,469 |                       66 |                                       25% |                                23,147 |                                 33,586 |
|                             [Russia](/russia) |           17,128 |                    21,549 |                     148 |                      4,421 |                       30 |                                       26% |                                18,085 |                                 30,416 |
|                 [South Africa](/south-africa) |           14,149 |                    20,061 |                     343 |                      5,912 |                      101 |                                       42% |                                16,552 |                                 28,280 |
|                       [Argentina](/argentina) |            8,660 |                    18,436 |                     412 |                      9,776 |                      218 |                                      113% |                                12,456 |                                 26,862 |
|                               [Chile](/chile) |           11,289 |                    14,645 |                     773 |                      3,356 |                      177 |                                       30% |                                11,796 |                                 22,142 |
|                       [Indonesia](/indonesia) |            7,417 |                    12,362 |                      46 |                      4,945 |                       18 |                                       67% |                                 9,125 |                                 19,743 |
|                             [Canada](/canada) |            9,173 |                     9,512 |                     254 |                        339 |                        9 |                                        4% |                                 9,210 |                                 10,273 |
|                             [Turkey](/turkey) |            6,370 |                     7,823 |                      94 |                      1,453 |                       17 |                                       23% |                                 6,439 |                                 10,461 |
|                           [Bolivia](/bolivia) |            5,027 |                     7,732 |                     672 |                      2,705 |                      235 |                                       54% |                                 6,098 |                                 10,223 |
|                           [Ecuador](/ecuador) |            6,556 |                     7,654 |                     441 |                      1,098 |                       63 |                                       17% |                                 6,656 |                                 10,046 |
|                   [Philippines](/philippines) |            3,558 |                     7,431 |                      69 |                      3,873 |                       36 |                                      109% |                                 4,771 |                                 12,460 |
|                         [Pakistan](/pakistan) |            6,294 |                     6,734 |                      31 |                        440 |                        2 |                                        7% |                                 6,322 |                                  7,660 |
|                     [Bangladesh](/bangladesh) |            4,281 |                     6,279 |                      39 |                      1,998 |                       12 |                                       47% |                                 4,873 |                                  8,777 |
|                               [Egypt](/egypt) |            5,421 |                     6,129 |                      61 |                        708 |                        7 |                                       13% |                                 5,467 |                                  8,695 |
|                 [Saudi Arabia](/saudi-arabia) |            3,897 |                     5,224 |                     152 |                      1,327 |                       39 |                                       34% |                                 4,302 |                                  6,794 |
|                               [China](/china) |            4,723 |                     4,815 |                       3 |                         92 |                        0 |                                        2% |                                 4,723 |                                  5,494 |
|                           [Morocco](/morocco) |            1,141 |                     3,172 |                      87 |                      2,031 |                       56 |                                      178% |                                 1,774 |                                  5,286 |
|                         [Honduras](/honduras) |            1,873 |                     2,794 |                     287 |                        921 |                       95 |                                       49% |                                 2,196 |                                  3,846 |
|     [Dominican Republic](/dominican-republic) |            1,710 |                     2,635 |                     245 |                        925 |                       86 |                                       54% |                                 2,027 |                                  3,775 |
|                             [Panama](/panama) |            2,002 |                     2,541 |                     598 |                        539 |                      127 |                                       27% |                                 2,226 |                                  3,231 |
|                           [Algeria](/algeria) |            1,510 |                     2,142 |                      50 |                        632 |                       15 |                                       42% |                                 1,631 |                                  3,283 |
|                               [Japan](/japan) |            1,298 |                     2,038 |                      16 |                        740 |                        6 |                                       57% |                                 1,446 |                                  3,559 |
|                             [Israel](/israel) |              939 |                     1,849 |                     217 |                        910 |                      107 |                                       97% |                                 1,203 |                                  3,043 |
|                           [Nigeria](/nigeria) |            1,013 |                     1,220 |                       6 |                        207 |                        1 |                                       20% |                                 1,033 |                                  1,518 |
|                       [Australia](/australia) |              657 |                     1,073 |                      43 |                        416 |                       16 |                                       63% |                                   819 |                                  1,431 |
|                             [Kuwait](/kuwait) |              531 |                       663 |                     157 |                        132 |                       31 |                                       25% |                                   553 |                                    939 |
| [United Arab Emirates](/united-arab-emirates) |              384 |                       457 |                      47 |                         73 |                        7 |                                       19% |                                   388 |                                    647 |
|                   [South Korea](/south-korea) |              324 |                       419 |                       8 |                         95 |                        2 |                                       29% |                                   329 |                                    638 |
|                         [Malaysia](/malaysia) |              127 |                       140 |                       4 |                         13 |                        0 |                                       10% |                                   130 |                                    154 |
|                                 [Cuba](/cuba) |               94 |                       136 |                      12 |                         42 |                        4 |                                       44% |                                   104 |                                    220 |
