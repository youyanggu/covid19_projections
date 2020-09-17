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
### Updated Daily - Last Updated: September 17 (5am ET):
<p align="center">
  Current Total: <b>196,760</b> deaths | Projected Total: <b>222,100 deaths by Nov 1, 2020</b> (Range: 211-238k)<br>
  Currently Infected: <b>1.0%</b> (1 in 105) | Total Infected: <b>15.1%</b> (1 in 7) {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: September 17, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              200,000 |        Sep 21, 2020 |

<br>

|   US deaths surpass: |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|------------|-------------|------------|
|              200,000 |        99% |        >99% |       >99% |
|              225,000 |        <1% |         <1% |        23% |
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
|             *[United States](/us)* |          196,760 |                   222,094 |                     669 |                     25,334 |                       76 |                                       13% |                               211,946 |                                237,022 |
|                 [New York](/us-ny) |           33,042 |                    33,308 |                   1,712 |                        266 |                       14 |                                        1% |                                33,053 |                                 34,830 |
|                    [Texas](/us-tx) |           14,738 |                    17,976 |                     620 |                      3,238 |                      112 |                                       22% |                                16,288 |                                 20,414 |
|               [California](/us-ca) |           14,691 |                    17,812 |                     451 |                      3,121 |                       79 |                                       21% |                                15,816 |                                 21,032 |
|               [New Jersey](/us-nj) |           16,054 |                    16,243 |                   1,829 |                        189 |                       21 |                                        1% |                                16,065 |                                 16,868 |
|                  [Florida](/us-fl) |           12,939 |                    15,925 |                     741 |                      2,986 |                      139 |                                       23% |                                14,336 |                                 18,187 |
|            [Massachusetts](/us-ma) |            9,245 |                     9,618 |                   1,384 |                        373 |                       54 |                                        4% |                                 9,269 |                                 10,312 |
|                 [Illinois](/us-il) |            8,599 |                     9,369 |                     739 |                        770 |                       61 |                                        9% |                                 8,688 |                                 10,367 |
|             [Pennsylvania](/us-pa) |            7,882 |                     8,366 |                     654 |                        484 |                       38 |                                        6% |                                 7,907 |                                  9,318 |
|                  [Georgia](/us-ga) |            6,419 |                     7,722 |                     727 |                      1,303 |                      123 |                                       20% |                                 6,960 |                                  9,006 |
|                 [Michigan](/us-mi) |            6,943 |                     7,367 |                     738 |                        424 |                       42 |                                        6% |                                 6,998 |                                  7,987 |
|                [Louisiana](/us-la) |            5,296 |                     5,962 |                   1,283 |                        666 |                      143 |                                       13% |                                 5,571 |                                  6,599 |
|                  [Arizona](/us-az) |            5,371 |                     5,757 |                     791 |                        386 |                       53 |                                        7% |                                 5,487 |                                  6,208 |
|                     [Ohio](/us-oh) |            4,555 |                     5,491 |                     470 |                        936 |                       80 |                                       21% |                                 4,800 |                                  6,654 |
|              [Connecticut](/us-ct) |            4,487 |                     4,564 |                   1,280 |                         77 |                       22 |                                        2% |                                 4,497 |                                  4,780 |
|                 [Maryland](/us-md) |            3,855 |                     4,105 |                     679 |                        250 |                       41 |                                        6% |                                 3,875 |                                  4,554 |
|           [North Carolina](/us-nc) |            3,149 |                     4,088 |                     390 |                        939 |                       90 |                                       30% |                                 3,592 |                                  4,898 |
|                  [Indiana](/us-in) |            3,472 |                     3,894 |                     578 |                        422 |                       63 |                                       12% |                                 3,506 |                                  4,626 |
|           [South Carolina](/us-sc) |            3,132 |                     3,794 |                     737 |                        662 |                      128 |                                       21% |                                 3,463 |                                  4,273 |
|                 [Virginia](/us-va) |            2,882 |                     3,611 |                     423 |                        729 |                       85 |                                       25% |                                 3,085 |                                  4,422 |
|              [Mississippi](/us-ms) |            2,756 |                     3,240 |                   1,089 |                        484 |                      163 |                                       18% |                                 2,928 |                                  3,804 |
|                [Tennessee](/us-tn) |            2,151 |                     2,969 |                     435 |                        818 |                      120 |                                       38% |                                 2,576 |                                  3,576 |
|                  [Alabama](/us-al) |            2,392 |                     2,843 |                     580 |                        451 |                       92 |                                       19% |                                 2,581 |                                  3,256 |
|               [Washington](/us-wa) |            2,020 |                     2,346 |                     308 |                        326 |                       43 |                                       16% |                                 2,073 |                                  2,843 |
|                [Minnesota](/us-mn) |            1,985 |                     2,298 |                     407 |                        313 |                       56 |                                       16% |                                 2,040 |                                  2,717 |
|                 [Missouri](/us-mo) |            1,765 |                     2,275 |                     371 |                        510 |                       83 |                                       29% |                                 1,979 |                                  2,752 |
|                 [Colorado](/us-co) |            2,002 |                     2,146 |                     373 |                        144 |                       25 |                                        7% |                                 2,012 |                                  2,521 |
|                   [Nevada](/us-nv) |            1,494 |                     1,739 |                     565 |                        245 |                       80 |                                       16% |                                 1,596 |                                  1,950 |
|                     [Iowa](/us-ia) |            1,248 |                     1,602 |                     508 |                        354 |                      112 |                                       28% |                                 1,381 |                                  1,949 |
|                 [Arkansas](/us-ar) |            1,157 |                     1,572 |                     521 |                        415 |                      137 |                                       36% |                                 1,371 |                                  1,861 |
|                [Wisconsin](/us-wi) |            1,227 |                     1,536 |                     264 |                        309 |                       53 |                                       25% |                                 1,348 |                                  1,836 |
|                 [Kentucky](/us-ky) |            1,082 |                     1,435 |                     321 |                        353 |                       79 |                                       33% |                                 1,227 |                                  1,744 |
|                 [Oklahoma](/us-ok) |              924 |                     1,241 |                     314 |                        317 |                       80 |                                       34% |                                 1,075 |                                  1,523 |
|             [Rhode Island](/us-ri) |            1,081 |                     1,140 |                   1,076 |                         59 |                       55 |                                        5% |                                 1,088 |                                  1,267 |
|               [New Mexico](/us-nm) |              832 |                       973 |                     464 |                        141 |                       67 |                                       17% |                                   874 |                                  1,139 |
|              [Puerto Rico](/us-pr) |              570 |                       920 |                     288 |                        350 |                      110 |                                       61% |                                   745 |                                  1,194 |
|                   [Kansas](/us-ks) |              578 |                       814 |                     279 |                        236 |                       81 |                                       41% |                                   680 |                                  1,029 |
|                   [Oregon](/us-or) |              521 |                       701 |                     166 |                        180 |                       43 |                                       35% |                                   591 |                                    891 |
|                 [Delaware](/us-de) |              619 |                       655 |                     673 |                         36 |                       37 |                                        6% |                                   623 |                                    725 |
|     [District of Columbia](/us-dc) |              617 |                       638 |                     904 |                         21 |                       30 |                                        3% |                                   620 |                                    677 |
|                    [Idaho](/us-id) |              429 |                       581 |                     325 |                        152 |                       85 |                                       36% |                                   507 |                                    686 |
|                 [Nebraska](/us-ne) |              439 |                       549 |                     284 |                        110 |                       57 |                                       25% |                                   474 |                                    672 |
|                     [Utah](/us-ut) |              437 |                       546 |                     170 |                        109 |                       34 |                                       25% |                                   483 |                                    630 |
|            [West Virginia](/us-wv) |              293 |                       479 |                     267 |                        186 |                      104 |                                       63% |                                   382 |                                    635 |
|            [New Hampshire](/us-nh) |              438 |                       464 |                     341 |                         26 |                       19 |                                        6% |                                   440 |                                    534 |
|             [South Dakota](/us-sd) |              192 |                       283 |                     320 |                         91 |                      103 |                                       48% |                                   205 |                                    438 |
|             [North Dakota](/us-nd) |              177 |                       259 |                     340 |                         82 |                      108 |                                       47% |                                   216 |                                    328 |
|                  [Montana](/us-mt) |              141 |                       239 |                     224 |                         98 |                       92 |                                       70% |                                   192 |                                    320 |
|                   [Hawaii](/us-hi) |              103 |                       178 |                     125 |                         75 |                       53 |                                       72% |                                   138 |                                    246 |
|                    [Maine](/us-me) |              138 |                       156 |                     116 |                         18 |                       13 |                                       13% |                                   141 |                                    184 |
|                  [Wyoming](/us-wy) |               50 |                        73 |                     126 |                         23 |                       39 |                                       46% |                                    61 |                                     96 |
|                     [Guam](/us-gu) |               28 |                        69 |                     413 |                         41 |                      244 |                                      145% |                                    49 |                                    101 |
|                  [Vermont](/us-vt) |               58 |                        66 |                     105 |                          8 |                       12 |                                       13% |                                    59 |                                     80 |
|                   [Alaska](/us-ak) |               44 |                        65 |                      89 |                         21 |                       29 |                                       48% |                                    54 |                                     83 |
|           [Virgin Islands](/us-vi) |               19 |                        28 |                     266 |                          9 |                       85 |                                       47% |                                    23 |                                     36 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      48 |                          1 |                       12 |                                       32% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          193,434 |                   212,523 |                     358 |                     19,089 |                       32 |                                       10% |                               196,968 |                                266,319 |
| [United Kingdom](/united-kingdom) |           41,773 |                    43,159 |                     639 |                      1,386 |                       21 |                                        3% |                                41,802 |                                 48,582 |
|                   [Italy](/italy) |           35,645 |                    36,505 |                     605 |                        860 |                       14 |                                        2% |                                35,662 |                                 40,415 |
|                   [Spain](/spain) |           30,243 |                    36,452 |                     777 |                      6,209 |                      132 |                                       21% |                                31,026 |                                 54,119 |
|                 [France](/france) |           31,056 |                    34,160 |                     510 |                      3,104 |                       46 |                                       10% |                                31,095 |                                 51,359 |
|               [Belgium](/belgium) |            9,935 |                    10,090 |                     881 |                        155 |                       14 |                                        2% |                                 9,949 |                                 10,612 |
|               [Germany](/germany) |            9,373 |                     9,641 |                     116 |                        268 |                        3 |                                        3% |                                 9,385 |                                 10,678 |
|       [Netherlands](/netherlands) |            6,303 |                     6,497 |                     376 |                        194 |                       11 |                                        3% |                                 6,314 |                                  7,132 |
|               [Ukraine](/ukraine) |            3,404 |                     6,106 |                     139 |                      2,702 |                       61 |                                       79% |                                 4,476 |                                  8,542 |
|                 [Sweden](/sweden) |            5,860 |                     5,922 |                     579 |                         62 |                        6 |                                        1% |                                 5,865 |                                  6,118 |
|               [Romania](/romania) |            4,285 |                     5,920 |                     305 |                      1,635 |                       84 |                                       38% |                                 5,004 |                                  7,343 |
|                 [Poland](/poland) |            2,237 |                     2,572 |                      68 |                        335 |                        9 |                                       15% |                                 2,343 |                                  2,894 |
|       [Switzerland](/switzerland) |            2,039 |                     2,140 |                     249 |                        101 |                       12 |                                        5% |                                 2,052 |                                  2,375 |
|             [Portugal](/portugal) |            1,878 |                     2,026 |                     197 |                        148 |                       14 |                                        8% |                                 1,886 |                                  2,386 |
|               [Ireland](/ireland) |            1,788 |                     1,823 |                     372 |                         35 |                        7 |                                        2% |                                 1,794 |                                  1,930 |
|               [Moldova](/moldova) |            1,159 |                     1,552 |                     384 |                        393 |                       97 |                                       34% |                                 1,308 |                                  1,950 |
|               [Belarus](/belarus) |              767 |                     1,025 |                     108 |                        258 |                       27 |                                       34% |                                   851 |                                  1,390 |
|             [Bulgaria](/bulgaria) |              739 |                     1,009 |                     144 |                        270 |                       39 |                                       37% |                                   870 |                                  1,229 |
|               [Austria](/austria) |              758 |                       828 |                      93 |                         70 |                        8 |                                        9% |                                   772 |                                    977 |
|                 [Serbia](/serbia) |              736 |                       795 |                     114 |                         59 |                        8 |                                        8% |                                   758 |                                    853 |
|               [Hungary](/hungary) |              654 |                       785 |                      80 |                        131 |                       13 |                                       20% |                                   676 |                                  1,020 |
|               [Czechia](/czechia) |              482 |                       688 |                      65 |                        206 |                       19 |                                       43% |                                   558 |                                    923 |
|               [Denmark](/denmark) |              633 |                       670 |                     115 |                         37 |                        6 |                                        6% |                                   641 |                                    758 |
|                 [Greece](/greece) |              316 |                       485 |                      45 |                        169 |                       16 |                                       54% |                                   388 |                                    664 |
|               [Croatia](/croatia) |              236 |                       430 |                     106 |                        194 |                       48 |                                       82% |                                   330 |                                    626 |
|               [Finland](/finland) |              339 |                       355 |                      64 |                         16 |                        3 |                                        5% |                                   342 |                                    402 |
|                 [Norway](/norway) |              265 |                       281 |                      52 |                         16 |                        3 |                                        6% |                                   268 |                                    318 |
|             [Slovenia](/slovenia) |              135 |                       149 |                      72 |                         14 |                        7 |                                       10% |                                   137 |                                    178 |
|         [Luxembourg](/luxembourg) |              124 |                       138 |                     225 |                         14 |                       23 |                                       11% |                                   128 |                                    158 |
|           [Lithuania](/lithuania) |               87 |                        96 |                      34 |                          9 |                        3 |                                       10% |                                    89 |                                    109 |
|               [Estonia](/estonia) |               64 |                        69 |                      52 |                          5 |                        4 |                                        7% |                                    66 |                                     73 |
|             [Slovakia](/slovakia) |               38 |                        50 |                       9 |                         12 |                        2 |                                       31% |                                    41 |                                     68 |
|                 [Latvia](/latvia) |               35 |                        39 |                      21 |                          4 |                        2 |                                       13% |                                    36 |                                     46 |
|                   [Malta](/malta) |               16 |                        30 |                      61 |                         14 |                       29 |                                       89% |                                    22 |                                     46 |
|                 [Cyprus](/cyprus) |               22 |                        27 |                      31 |                          5 |                        6 |                                       23% |                                    24 |                                     32 |
|               [Iceland](/iceland) |               10 |                        11 |                      33 |                          1 |                        4 |                                       13% |                                    10 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                               |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths / 1M |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|--------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          515,532 |                   666,697 |                     128 |                    151,165 |                       29 |                                       29% |                               580,033 |                                797,593 |
|                             [Brazil](/brazil) |          134,106 |                   161,011 |                     763 |                     26,905 |                      127 |                                       20% |                               148,962 |                                181,338 |
|                               [India](/india) |           82,066 |                   135,184 |                      99 |                     53,118 |                       39 |                                       65% |                               102,695 |                                171,348 |
|                             [Mexico](/mexico) |           71,978 |                    89,220 |                     699 |                     17,242 |                      135 |                                       24% |                                81,823 |                                 99,240 |
|                                 [Peru](/peru) |           30,927 |                    34,156 |                   1,051 |                      3,229 |                       99 |                                       10% |                                31,697 |                                 38,478 |
|                         [Colombia](/colombia) |           23,478 |                    29,890 |                     594 |                      6,412 |                      127 |                                       27% |                                26,766 |                                 35,441 |
|                                 [Iran](/iran) |           23,632 |                    28,442 |                     343 |                      4,810 |                       58 |                                       20% |                                25,683 |                                 33,233 |
|                             [Russia](/russia) |           18,853 |                    23,824 |                     163 |                      4,971 |                       34 |                                       26% |                                19,925 |                                 32,466 |
|                       [Argentina](/argentina) |           12,116 |                    20,214 |                     451 |                      8,098 |                      181 |                                       67% |                                15,639 |                                 25,608 |
|                 [South Africa](/south-africa) |           15,705 |                    18,411 |                     314 |                      2,706 |                       46 |                                       17% |                                16,855 |                                 21,189 |
|                               [Chile](/chile) |           12,058 |                    14,477 |                     764 |                      2,419 |                      128 |                                       20% |                                12,366 |                                 19,589 |
|                       [Indonesia](/indonesia) |            9,100 |                    13,347 |                      49 |                      4,247 |                       16 |                                       47% |                                11,024 |                                 18,391 |
|                           [Ecuador](/ecuador) |           10,996 |                    11,873 |                     683 |                        877 |                       50 |                                        8% |                                11,055 |                                 13,821 |
|                             [Canada](/canada) |            9,244 |                     9,518 |                     254 |                        274 |                        7 |                                        3% |                                 9,266 |                                 10,336 |
|                           [Bolivia](/bolivia) |            7,478 |                     9,284 |                     806 |                      1,806 |                      157 |                                       24% |                                 8,258 |                                 11,005 |
|                             [Turkey](/turkey) |            7,249 |                     8,979 |                     108 |                      1,730 |                       21 |                                       24% |                                 7,408 |                                 12,147 |
|                   [Philippines](/philippines) |            4,732 |                     8,060 |                      75 |                      3,328 |                       31 |                                       70% |                                 6,116 |                                 11,552 |
|                         [Pakistan](/pakistan) |            6,399 |                     6,580 |                      30 |                        181 |                        1 |                                        3% |                                 6,410 |                                  6,759 |
|                               [Egypt](/egypt) |            5,696 |                     6,516 |                      65 |                        820 |                        8 |                                       14% |                                 5,797 |                                  8,332 |
|                     [Bangladesh](/bangladesh) |            4,823 |                     6,294 |                      39 |                      1,471 |                        9 |                                       30% |                                 5,292 |                                  8,040 |
|                 [Saudi Arabia](/saudi-arabia) |            4,369 |                     5,444 |                     159 |                      1,075 |                       31 |                                       25% |                                 4,695 |                                  6,610 |
|                               [China](/china) |            4,736 |                     4,795 |                       3 |                         59 |                        0 |                                        1% |                                 4,736 |                                  5,264 |
|                           [Morocco](/morocco) |            1,686 |                     3,373 |                      92 |                      1,687 |                       46 |                                      100% |                                 2,318 |                                  4,927 |
|     [Dominican Republic](/dominican-republic) |            2,009 |                     2,721 |                     253 |                        712 |                       66 |                                       35% |                                 2,279 |                                  3,493 |
|                         [Honduras](/honduras) |            2,102 |                     2,670 |                     274 |                        568 |                       58 |                                       27% |                                 2,287 |                                  3,295 |
|                             [Panama](/panama) |            2,198 |                     2,559 |                     603 |                        361 |                       85 |                                       16% |                                 2,317 |                                  2,914 |
|                           [Algeria](/algeria) |            1,645 |                     1,937 |                      45 |                        292 |                        7 |                                       18% |                                 1,710 |                                  2,341 |
|                             [Israel](/israel) |            1,165 |                     1,886 |                     221 |                        721 |                       85 |                                       62% |                                 1,411 |                                  2,906 |
|                               [Japan](/japan) |            1,481 |                     1,851 |                      15 |                        370 |                        3 |                                       25% |                                 1,586 |                                  2,283 |
|                           [Nigeria](/nigeria) |            1,091 |                     1,241 |                       6 |                        150 |                        1 |                                       14% |                                 1,130 |                                  1,452 |
|                       [Australia](/australia) |              832 |                       998 |                      40 |                        166 |                        7 |                                       20% |                                   889 |                                  1,161 |
|                             [Kuwait](/kuwait) |              571 |                       686 |                     163 |                        115 |                       27 |                                       20% |                                   597 |                                    875 |
|                   [South Korea](/south-korea) |              372 |                       492 |                      10 |                        120 |                        2 |                                       32% |                                   383 |                                    736 |
| [United Arab Emirates](/united-arab-emirates) |              402 |                       479 |                      49 |                         77 |                        8 |                                       19% |                                   409 |                                    673 |
|                                 [Cuba](/cuba) |              109 |                       146 |                      13 |                         37 |                        3 |                                       34% |                                   119 |                                    204 |
|                         [Malaysia](/malaysia) |              128 |                       137 |                       4 |                          9 |                        0 |                                        7% |                                   130 |                                    146 |
