We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

On this page:
* [View US projections](#current-us-projections)
* [US and Global Dashboard **(New June 6)**](#covid-19-dashboard)
* [View US state-by-state projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **June 17:** Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* **June 16:** We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* **June 11**: We have extended our projections to October 1, 2020.
* **June 10**: We launched the C19Pro Score for both cases and deaths to show where weekly cases and deaths are changing the most. They are shown in the first two maps on our new [Maps](/maps) page.

## Current US Projections
### Updated Daily - Last Updated: June 19 (2am ET):
<p align="center">
  Current Total: <b>118,431</b> deaths | Projected Total: <b>184,283 deaths by Oct 1, 2020</b> (Range: 154-220k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.7%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details, visit our [Maps](/maps) page.

*June 18 note:* We moved the R_t Dashboard map to the [Maps](/maps) page and replaced it with our C19Pro Score for deaths.
{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 83% chance that the US surpasses 125,000 deaths by July 1, with June 29 being the most likely date.

Last updated: Jun 19, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 21, 2020 |
|              125,000 |        Jun 29, 2020 |
|              130,000 |         Jul 8, 2020 |
|              140,000 |        Jul 25, 2020 |
|              150,000 |         Aug 9, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        83% |         99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        18% |         67% |        91% |         98% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        23% |         48% |        62% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          5% |        20% |
|              250,000 |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |

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

States are ordered by descending projected deaths (by October 1).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          118,431 |                   184,283 |                     555 |                     65,852 |                                       56% |                               157,125 |                                215,732 |
|                 [New York](/us-ny) |           30,974 |                    32,286 |                   1,660 |                      1,312 |                                        4% |                                31,079 |                                 35,699 |
|               [California](/us-ca) |            5,355 |                    15,665 |                     396 |                     10,310 |                                      193% |                                 8,243 |                                 23,305 |
|               [New Jersey](/us-nj) |           12,869 |                    14,880 |                   1,675 |                      2,011 |                                       16% |                                13,353 |                                 16,381 |
|                 [Illinois](/us-il) |            6,537 |                    10,321 |                     814 |                      3,784 |                                       58% |                                 7,912 |                                 12,571 |
|            [Massachusetts](/us-ma) |            7,769 |                     9,285 |                   1,336 |                      1,516 |                                       20% |                                 8,222 |                                 11,011 |
|             [Pennsylvania](/us-pa) |            6,361 |                     8,619 |                     673 |                      2,258 |                                       35% |                                 6,806 |                                 11,912 |
|                  [Florida](/us-fl) |            3,061 |                     8,283 |                     386 |                      5,222 |                                      171% |                                 4,579 |                                 12,560 |
|                    [Texas](/us-tx) |            2,129 |                     6,952 |                     240 |                      4,823 |                                      227% |                                 3,539 |                                 10,652 |
|                 [Michigan](/us-mi) |            6,061 |                     6,786 |                     679 |                        725 |                                       12% |                                 6,213 |                                  7,907 |
|                  [Georgia](/us-ga) |            2,605 |                     6,118 |                     576 |                      3,513 |                                      135% |                                 3,471 |                                  8,639 |
|                     [Ohio](/us-oh) |            2,633 |                     5,189 |                     444 |                      2,556 |                                       97% |                                 3,143 |                                  8,006 |
|              [Connecticut](/us-ct) |            4,226 |                     4,861 |                   1,363 |                        635 |                                       15% |                                 4,380 |                                  5,754 |
|                 [Maryland](/us-md) |            3,016 |                     4,670 |                     772 |                      1,654 |                                       55% |                                 3,413 |                                  5,979 |
|                  [Arizona](/us-az) |            1,283 |                     4,531 |                     622 |                      3,248 |                                      253% |                                 2,761 |                                  6,089 |
|                  [Indiana](/us-in) |            2,491 |                     4,338 |                     644 |                      1,847 |                                       74% |                                 2,768 |                                  6,964 |
|                [Louisiana](/us-la) |            3,062 |                     4,108 |                     884 |                      1,046 |                                       34% |                                 3,272 |                                  5,649 |
|           [North Carolina](/us-nc) |            1,190 |                     3,050 |                     291 |                      1,860 |                                      156% |                                 1,698 |                                  4,618 |
|                [Minnesota](/us-mn) |            1,376 |                     3,040 |                     539 |                      1,664 |                                      121% |                                 1,828 |                                  4,340 |
|                 [Virginia](/us-va) |            1,586 |                     2,674 |                     313 |                      1,088 |                                       69% |                                 1,747 |                                  4,191 |
|                 [Colorado](/us-co) |            1,638 |                     2,642 |                     459 |                      1,004 |                                       61% |                                 1,783 |                                  4,216 |
|                  [Alabama](/us-al) |              810 |                     2,334 |                     476 |                      1,524 |                                      188% |                                 1,184 |                                  3,633 |
|               [Washington](/us-wa) |            1,245 |                     2,221 |                     292 |                        976 |                                       78% |                                 1,370 |                                  4,488 |
|              [Mississippi](/us-ms) |              938 |                     2,082 |                     700 |                      1,144 |                                      122% |                                 1,167 |                                  3,341 |
|                 [Missouri](/us-mo) |              945 |                     1,919 |                     313 |                        974 |                                      103% |                                 1,132 |                                  3,151 |
|           [South Carolina](/us-sc) |              621 |                     1,889 |                     367 |                      1,268 |                                      204% |                                   994 |                                  2,822 |
|                [Wisconsin](/us-wi) |              719 |                     1,620 |                     278 |                        901 |                                      125% |                                   917 |                                  2,545 |
|                [Tennessee](/us-tn) |              508 |                     1,498 |                     219 |                        990 |                                      195% |                                   731 |                                  2,352 |
|             [Rhode Island](/us-ri) |              885 |                     1,412 |                   1,333 |                        527 |                                       60% |                                 1,049 |                                  1,786 |
|                     [Iowa](/us-ia) |              680 |                     1,221 |                     387 |                        541 |                                       80% |                                   774 |                                  2,460 |
|                 [Kentucky](/us-ky) |              520 |                     1,119 |                     250 |                        599 |                                      115% |                                   643 |                                  1,760 |
|               [New Mexico](/us-nm) |              456 |                       959 |                     457 |                        503 |                                      110% |                                   559 |                                  1,523 |
|                   [Nevada](/us-nv) |              475 |                       887 |                     288 |                        412 |                                       87% |                                   561 |                                  1,388 |
|                 [Arkansas](/us-ar) |              208 |                       841 |                     279 |                        633 |                                      304% |                                   469 |                                  1,242 |
|            [New Hampshire](/us-nh) |              331 |                       770 |                     566 |                        439 |                                      133% |                                   414 |                                  1,246 |
|                 [Nebraska](/us-ne) |              239 |                       729 |                     377 |                        490 |                                      205% |                                   395 |                                  1,150 |
|     [District of Columbia](/us-dc) |              527 |                       702 |                     995 |                        175 |                                       33% |                                   567 |                                    892 |
|                 [Delaware](/us-de) |              431 |                       671 |                     689 |                        240 |                                       56% |                                   480 |                                  1,011 |
|                 [Oklahoma](/us-ok) |              366 |                       627 |                     158 |                        261 |                                       71% |                                   416 |                                  1,070 |
|                     [Utah](/us-ut) |              152 |                       545 |                     170 |                        393 |                                      259% |                                   290 |                                    834 |
|                   [Kansas](/us-ks) |              251 |                       447 |                     153 |                        196 |                                       78% |                                   278 |                                    849 |
|                   [Oregon](/us-or) |              187 |                       332 |                      79 |                        145 |                                       78% |                                   213 |                                    584 |
|             [South Dakota](/us-sd) |               78 |                       201 |                     227 |                        123 |                                      158% |                                    98 |                                    403 |
|              [Puerto Rico](/us-pr) |              147 |                       201 |                      63 |                         54 |                                       37% |                                   160 |                                    297 |
|             [North Dakota](/us-nd) |               75 |                       154 |                     202 |                         79 |                                      105% |                                    96 |                                    297 |
|                    [Maine](/us-me) |              102 |                       151 |                     112 |                         49 |                                       48% |                                   116 |                                    238 |
|            [West Virginia](/us-wv) |               88 |                       138 |                      77 |                         50 |                                       57% |                                   100 |                                    278 |
|                    [Idaho](/us-id) |               89 |                       131 |                      73 |                         42 |                                       47% |                                    96 |                                    221 |
|                  [Vermont](/us-vt) |               56 |                        71 |                     114 |                         15 |                                       27% |                                    60 |                                    105 |
|                  [Wyoming](/us-wy) |               18 |                        32 |                      55 |                         14 |                                       78% |                                    23 |                                     52 |
|                  [Montana](/us-mt) |               20 |                        30 |                      28 |                         10 |                                       50% |                                    21 |                                     75 |
|                   [Hawaii](/us-hi) |               17 |                        20 |                      14 |                          3 |                                       18% |                                    18 |                                     25 |
|                   [Alaska](/us-ak) |               12 |                        15 |                      21 |                          3 |                                       25% |                                    13 |                                     18 |
|           [Virgin Islands](/us-vi) |                6 |                         7 |                      67 |                          1 |                                       17% |                                     7 |                                      8 |
|                     [Guam](/us-gu) |                5 |                         6 |                      36 |                          1 |                                       20% |                                     5 |                                      8 |
| [Northern Mariana Islands](/us-mp) |                2 |                         3 |                      54 |                          1 |                                       50% |                                     2 |                                      4 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          177,034 |                   196,932 |                     332 |                     19,898 |                                       11% |                               181,588 |                                223,714 |
| [United Kingdom](/united-kingdom) |           42,373 |                    47,426 |                     702 |                      5,053 |                                       12% |                                43,560 |                                 50,592 |
|                   [Italy](/italy) |           34,514 |                    35,625 |                     590 |                      1,111 |                                        3% |                                34,588 |                                 36,744 |
|                 [France](/france) |           29,606 |                    30,572 |                     456 |                        966 |                                        3% |                                29,654 |                                 34,238 |
|                   [Spain](/spain) |           27,136 |                    27,815 |                     593 |                        679 |                                        3% |                                27,171 |                                 30,201 |
|               [Germany](/germany) |            8,875 |                    10,576 |                     127 |                      1,701 |                                       19% |                                 9,080 |                                 14,741 |
|               [Belgium](/belgium) |            9,683 |                     9,947 |                     868 |                        264 |                                        3% |                                 9,716 |                                 10,463 |
|       [Netherlands](/netherlands) |            6,097 |                     6,587 |                     381 |                        490 |                                        8% |                                 6,162 |                                  7,353 |
|                 [Sweden](/sweden) |            5,053 |                     6,486 |                     634 |                      1,433 |                                       28% |                                 5,489 |                                  8,279 |
|               [Ukraine](/ukraine) |              976 |                     3,223 |                      73 |                      2,247 |                                      230% |                                 1,638 |                                  4,973 |
|                 [Poland](/poland) |            1,316 |                     2,968 |                      78 |                      1,652 |                                      126% |                                 1,772 |                                  4,417 |
|               [Romania](/romania) |            1,473 |                     2,445 |                     126 |                        972 |                                       66% |                                 1,736 |                                  3,694 |
|       [Switzerland](/switzerland) |            1,956 |                     2,080 |                     242 |                        124 |                                        6% |                                 1,972 |                                  2,463 |
|             [Portugal](/portugal) |            1,524 |                     1,895 |                     184 |                        371 |                                       24% |                                 1,618 |                                  2,503 |
|               [Ireland](/ireland) |            1,714 |                     1,819 |                     371 |                        105 |                                        6% |                                 1,727 |                                  2,230 |
|               [Moldova](/moldova) |              444 |                     1,560 |                     386 |                      1,116 |                                      251% |                                   970 |                                  2,234 |
|               [Belarus](/belarus) |              331 |                       819 |                      87 |                        488 |                                      147% |                                   457 |                                  1,857 |
|               [Hungary](/hungary) |              568 |                       796 |                      81 |                        228 |                                       40% |                                   607 |                                  1,159 |
|               [Austria](/austria) |              688 |                       750 |                      85 |                         62 |                                        9% |                                   704 |                                    921 |
|               [Denmark](/denmark) |              600 |                       684 |                     118 |                         84 |                                       14% |                                   623 |                                    857 |
|             [Bulgaria](/bulgaria) |              190 |                       612 |                      87 |                        422 |                                      222% |                                   330 |                                    953 |
|               [Finland](/finland) |              326 |                       373 |                      68 |                         47 |                                       14% |                                   332 |                                    503 |
|               [Czechia](/czechia) |              334 |                       360 |                      34 |                         26 |                                        8% |                                   346 |                                    395 |
|                 [Serbia](/serbia) |              258 |                       335 |                      48 |                         77 |                                       30% |                                   278 |                                    477 |
|                 [Norway](/norway) |              244 |                       270 |                      50 |                         26 |                                       11% |                                   253 |                                    312 |
|                 [Greece](/greece) |              188 |                       226 |                      21 |                         38 |                                       20% |                                   202 |                                    284 |
|               [Croatia](/croatia) |              107 |                       136 |                      33 |                         29 |                                       27% |                                   116 |                                    190 |
|             [Slovenia](/slovenia) |              109 |                       121 |                      58 |                         12 |                                       11% |                                   111 |                                    147 |
|         [Luxembourg](/luxembourg) |              110 |                       121 |                     197 |                         11 |                                       10% |                                   112 |                                    144 |
|           [Lithuania](/lithuania) |               76 |                       116 |                      42 |                         40 |                                       53% |                                    87 |                                    185 |
|               [Estonia](/estonia) |               69 |                        78 |                      59 |                          9 |                                       13% |                                    75 |                                     81 |
|                 [Latvia](/latvia) |               30 |                        36 |                      19 |                          6 |                                       20% |                                    33 |                                     43 |
|             [Slovakia](/slovakia) |               28 |                        30 |                       6 |                          2 |                                        7% |                                    28 |                                     32 |
|                 [Cyprus](/cyprus) |               19 |                        22 |                      25 |                          3 |                                       16% |                                    21 |                                     24 |
|                   [Malta](/malta) |                9 |                        12 |                      24 |                          3 |                                       33% |                                    10 |                                     13 |
|               [Iceland](/iceland) |               10 |                        11 |                      32 |                          1 |                                       10% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          152,085 |                   579,445 |                     112 |                    427,360 |                                      281% |                               326,287 |                                964,613 |
|                               [India](/india) |           12,573 |                   131,329 |                      96 |                    118,756 |                                      945% |                                54,606 |                                276,051 |
|                             [Brazil](/brazil) |           47,748 |                   125,165 |                     593 |                     77,417 |                                      162% |                                76,866 |                                193,151 |
|                             [Mexico](/mexico) |           19,747 |                    77,817 |                     610 |                     58,070 |                                      294% |                                49,375 |                                105,265 |
|                         [Pakistan](/pakistan) |            3,229 |                    30,526 |                     141 |                     27,297 |                                      845% |                                13,517 |                                 61,103 |
|                                 [Peru](/peru) |            7,461 |                    24,682 |                     759 |                     17,221 |                                      231% |                                14,499 |                                 36,085 |
|                             [Russia](/russia) |            7,650 |                    22,803 |                     156 |                     15,153 |                                      198% |                                12,521 |                                 39,598 |
|                               [Chile](/chile) |            3,841 |                    22,085 |                   1,165 |                     18,244 |                                      475% |                                15,007 |                                 32,006 |
|                         [Colombia](/colombia) |            1,955 |                    19,034 |                     378 |                     17,079 |                                      874% |                                10,792 |                                 25,204 |
|                 [South Africa](/south-africa) |            1,737 |                    18,051 |                     308 |                     16,314 |                                      939% |                                 9,986 |                                 25,765 |
|                                 [Iran](/iran) |            9,272 |                    17,089 |                     206 |                      7,817 |                                       84% |                                11,404 |                                 24,142 |
|                               [Egypt](/egypt) |            1,938 |                    10,536 |                     105 |                      8,598 |                                      444% |                                 5,673 |                                 17,532 |
|                             [Canada](/canada) |            8,361 |                    10,484 |                     280 |                      2,123 |                                       25% |                                 8,957 |                                 13,309 |
|                     [Bangladesh](/bangladesh) |            1,343 |                    10,017 |                      61 |                      8,674 |                                      646% |                                 5,484 |                                 15,729 |
|                       [Indonesia](/indonesia) |            2,339 |                     8,602 |                      32 |                      6,263 |                                      268% |                                 4,175 |                                 16,318 |
|                 [Saudi Arabia](/saudi-arabia) |            1,139 |                     7,889 |                     230 |                      6,750 |                                      593% |                                 5,107 |                                 12,218 |
|                       [Argentina](/argentina) |              948 |                     7,152 |                     160 |                      6,204 |                                      654% |                                 3,047 |                                 12,582 |
|                           [Ecuador](/ecuador) |            4,087 |                     6,011 |                     346 |                      1,924 |                                       47% |                                 4,491 |                                 10,613 |
|                           [Bolivia](/bolivia) |              697 |                     5,763 |                     501 |                      5,066 |                                      727% |                                 3,200 |                                  8,516 |
|                             [Turkey](/turkey) |            4,882 |                     5,739 |                      69 |                        857 |                                       18% |                                 4,957 |                                  8,464 |
|                               [China](/china) |            4,638 |                     4,650 |                       3 |                         12 |                                        0% |                                 4,638 |                                  4,711 |
|                           [Nigeria](/nigeria) |              475 |                     2,347 |                      12 |                      1,872 |                                      394% |                                   873 |                                  4,187 |
|                   [Philippines](/philippines) |            1,116 |                     2,262 |                      21 |                      1,146 |                                      103% |                                 1,256 |                                  4,017 |
|                           [Algeria](/algeria) |              811 |                     1,921 |                      45 |                      1,110 |                                      137% |                                   945 |                                  5,346 |
|                         [Honduras](/honduras) |              343 |                     1,464 |                     150 |                      1,121 |                                      327% |                                   700 |                                  2,601 |
|     [Dominican Republic](/dominican-republic) |              635 |                     1,279 |                     119 |                        644 |                                      101% |                                   761 |                                  2,673 |
|                             [Panama](/panama) |              475 |                     1,248 |                     294 |                        773 |                                      163% |                                   641 |                                  2,279 |
|                               [Japan](/japan) |              935 |                     1,193 |                       9 |                        258 |                                       28% |                                   941 |                                  1,747 |
|                             [Kuwait](/kuwait) |              308 |                       629 |                     150 |                        321 |                                      104% |                                   384 |                                  1,190 |
| [United Arab Emirates](/united-arab-emirates) |              298 |                       397 |                      41 |                         99 |                                       33% |                                   329 |                                    596 |
|                             [Israel](/israel) |              303 |                       369 |                      43 |                         66 |                                       22% |                                   321 |                                    509 |
|                   [South Korea](/south-korea) |              280 |                       315 |                       6 |                         35 |                                       12% |                                   283 |                                    380 |
|                           [Morocco](/morocco) |              213 |                       240 |                       7 |                         27 |                                       13% |                                   222 |                                    293 |
|                         [Malaysia](/malaysia) |              121 |                       148 |                       5 |                         27 |                                       22% |                                   137 |                                    173 |
|                       [Australia](/australia) |              102 |                       109 |                       4 |                          7 |                                        7% |                                   102 |                                    139 |
|                                 [Cuba](/cuba) |               85 |                       100 |                       9 |                         15 |                                       18% |                                    90 |                                    121 |
