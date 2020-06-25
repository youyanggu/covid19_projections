We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of June, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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

* **June 25:** Our analysis shows that having *no* model [is better](/about/#baseline-comparison-c19pro-vs-ihme) than having IHME's model for US state-by-state projections.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.
* *June 11*: We have extended our projections to October 1, 2020.

## Current US Projections
### Updated Daily - Last Updated: June 25 (4pm ET):
<p align="center">
  Current Total: <b>121,977</b> deaths | Projected Total: <b>189,427 deaths by Oct 1, 2020</b> (Range: 154-222k)<br>
  Currently Infected: <b>0.4%</b> | Total Infected: <b>4.9%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 95% chance that the US surpasses 125,000 deaths by July 1, with June 30 being the most likely date.

Last updated: Jun 25, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              120,000 |        Jun 22, 2020 |
|              125,000 |        Jun 30, 2020 |
|              130,000 |         Jul 8, 2020 |
|              140,000 |        Jul 24, 2020 |
|              150,000 |         Aug 7, 2020 |

<br>

|   US deaths surpass: |   By Jul 1 |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |
|----------------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              125,000 |        95% |        >99% |       >99% |        >99% |       >99% |        >99% |       >99% |
|              150,000 |        <1% |         <1% |        23% |         72% |        96% |         99% |        99% |
|              175,000 |        <1% |         <1% |        <1% |         <1% |        31% |         51% |        66% |
|              200,000 |        <1% |         <1% |        <1% |         <1% |        <1% |          9% |        28% |
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
|             *[United States](/us)* |          121,977 |                   189,427 |                     571 |                     67,450 |                                       55% |                               158,109 |                                229,169 |
|                 [New York](/us-ny) |           31,257 |                    33,337 |                   1,714 |                      2,080 |                                        7% |                                31,380 |                                 39,064 |
|               [California](/us-ca) |            5,725 |                    15,563 |                     394 |                      9,838 |                                      172% |                                 8,593 |                                 23,590 |
|               [New Jersey](/us-nj) |           13,076 |                    14,797 |                   1,666 |                      1,721 |                                       13% |                                13,362 |                                 16,258 |
|                 [Illinois](/us-il) |            6,770 |                    10,420 |                     822 |                      3,650 |                                       54% |                                 7,988 |                                 12,813 |
|            [Massachusetts](/us-ma) |            7,937 |                     9,556 |                   1,375 |                      1,619 |                                       20% |                                 8,290 |                                 11,986 |
|             [Pennsylvania](/us-pa) |            6,518 |                     9,200 |                     719 |                      2,682 |                                       41% |                                 6,974 |                                 13,706 |
|                  [Florida](/us-fl) |            3,281 |                     9,073 |                     422 |                      5,792 |                                      177% |                                 5,501 |                                 13,662 |
|                 [Michigan](/us-mi) |            6,114 |                     7,171 |                     718 |                      1,057 |                                       17% |                                 6,247 |                                  8,894 |
|                    [Texas](/us-tx) |            2,270 |                     7,025 |                     242 |                      4,755 |                                      209% |                                 4,210 |                                 10,864 |
|                  [Georgia](/us-ga) |            2,698 |                     6,065 |                     571 |                      3,367 |                                      125% |                                 3,377 |                                  9,407 |
|                     [Ohio](/us-oh) |            2,755 |                     5,323 |                     455 |                      2,568 |                                       93% |                                 3,226 |                                  8,422 |
|                  [Arizona](/us-az) |            1,467 |                     5,015 |                     689 |                      3,548 |                                      242% |                                 3,204 |                                  6,913 |
|              [Connecticut](/us-ct) |            4,287 |                     4,801 |                   1,347 |                        514 |                                       12% |                                 4,395 |                                  5,295 |
|                 [Maryland](/us-md) |            3,108 |                     4,678 |                     774 |                      1,570 |                                       51% |                                 3,452 |                                  6,145 |
|                  [Indiana](/us-in) |            2,578 |                     4,323 |                     642 |                      1,745 |                                       68% |                                 2,826 |                                  7,211 |
|                [Louisiana](/us-la) |            3,152 |                     4,192 |                     902 |                      1,040 |                                       33% |                                 3,343 |                                  5,742 |
|           [North Carolina](/us-nc) |            1,325 |                     3,514 |                     335 |                      2,189 |                                      165% |                                 1,817 |                                  5,654 |
|                [Minnesota](/us-mn) |            1,432 |                     2,938 |                     521 |                      1,506 |                                      105% |                                 1,806 |                                  4,326 |
|                 [Virginia](/us-va) |            1,661 |                     2,771 |                     325 |                      1,110 |                                       67% |                                 1,816 |                                  4,413 |
|                  [Alabama](/us-al) |              891 |                     2,642 |                     539 |                      1,751 |                                      197% |                                 1,382 |                                  4,010 |
|                 [Colorado](/us-co) |            1,667 |                     2,609 |                     453 |                        942 |                                       57% |                                 1,765 |                                  4,261 |
|               [Washington](/us-wa) |            1,293 |                     2,492 |                     327 |                      1,199 |                                       93% |                                 1,488 |                                  5,024 |
|              [Mississippi](/us-ms) |            1,011 |                     2,176 |                     731 |                      1,165 |                                      115% |                                 1,236 |                                  3,416 |
|           [South Carolina](/us-sc) |              683 |                     2,055 |                     399 |                      1,372 |                                      201% |                                 1,064 |                                  3,120 |
|                 [Missouri](/us-mo) |              985 |                     1,770 |                     288 |                        785 |                                       80% |                                 1,105 |                                  3,097 |
|                [Tennessee](/us-tn) |              556 |                     1,749 |                     256 |                      1,193 |                                      215% |                                   803 |                                  2,772 |
|                [Wisconsin](/us-wi) |              757 |                     1,657 |                     285 |                        900 |                                      119% |                                   935 |                                  2,618 |
|             [Rhode Island](/us-ri) |              912 |                     1,401 |                   1,322 |                        489 |                                       54% |                                 1,048 |                                  1,794 |
|                 [Kentucky](/us-ky) |              538 |                     1,093 |                     245 |                        555 |                                      103% |                                   641 |                                  1,779 |
|                     [Iowa](/us-ia) |              690 |                     1,055 |                     334 |                        365 |                                       53% |                                   752 |                                  2,009 |
|                 [Arkansas](/us-ar) |              240 |                       958 |                     317 |                        718 |                                      299% |                                   525 |                                  1,429 |
|               [New Mexico](/us-nm) |              480 |                       952 |                     454 |                        472 |                                       98% |                                   573 |                                  1,537 |
|                   [Nevada](/us-nv) |              489 |                       905 |                     294 |                        416 |                                       85% |                                   562 |                                  1,545 |
|                 [Delaware](/us-de) |              505 |                       742 |                     762 |                        237 |                                       47% |                                   546 |                                  1,143 |
|     [District of Columbia](/us-dc) |              541 |                       723 |                   1,024 |                        182 |                                       34% |                                   579 |                                    955 |
|            [New Hampshire](/us-nh) |              347 |                       707 |                     520 |                        360 |                                      104% |                                   407 |                                  1,154 |
|                 [Nebraska](/us-ne) |              257 |                       678 |                     350 |                        421 |                                      164% |                                   376 |                                  1,172 |
|                 [Oklahoma](/us-ok) |              372 |                       665 |                     168 |                        293 |                                       79% |                                   417 |                                  1,170 |
|                     [Utah](/us-ut) |              163 |                       540 |                     168 |                        377 |                                      231% |                                   276 |                                    849 |
|                   [Oregon](/us-or) |              195 |                       447 |                     106 |                        252 |                                      129% |                                   241 |                                    759 |
|                   [Kansas](/us-ks) |              260 |                       447 |                     153 |                        187 |                                       72% |                                   285 |                                    901 |
|              [Puerto Rico](/us-pr) |              149 |                       201 |                      63 |                         52 |                                       35% |                                   161 |                                    305 |
|             [South Dakota](/us-sd) |               84 |                       196 |                     222 |                        112 |                                      133% |                                   102 |                                    389 |
|                    [Idaho](/us-id) |               89 |                       152 |                      85 |                         63 |                                       71% |                                    95 |                                    230 |
|                    [Maine](/us-me) |              103 |                       147 |                     109 |                         44 |                                       43% |                                   115 |                                    224 |
|            [West Virginia](/us-wv) |               92 |                       140 |                      78 |                         48 |                                       52% |                                   103 |                                    263 |
|             [North Dakota](/us-nd) |               78 |                       131 |                     172 |                         53 |                                       68% |                                    92 |                                    219 |
|                  [Vermont](/us-vt) |               56 |                        77 |                     123 |                         21 |                                       38% |                                    59 |                                    104 |
|                  [Wyoming](/us-wy) |               20 |                        44 |                      76 |                         24 |                                      120% |                                    25 |                                    103 |
|                  [Montana](/us-mt) |               21 |                        43 |                      40 |                         22 |                                      105% |                                    22 |                                     78 |
|                   [Alaska](/us-ak) |               12 |                        24 |                      33 |                         12 |                                      100% |                                    13 |                                     64 |
|                   [Hawaii](/us-hi) |               17 |                        23 |                      16 |                          6 |                                       35% |                                    17 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     17 |
|           [Virgin Islands](/us-vi) |                6 |                         9 |                      86 |                          3 |                                       50% |                                     7 |                                     19 |
| [Northern Mariana Islands](/us-mp) |                2 |                         5 |                      91 |                          3 |                                      150% |                                     3 |                                     13 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-10-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          179,963 |                   200,632 |                     338 |                     20,669 |                                       11% |                               184,198 |                                229,574 |
| [United Kingdom](/united-kingdom) |           43,165 |                    47,687 |                     706 |                      4,522 |                                       10% |                                44,171 |                                 50,818 |
|                   [Italy](/italy) |           34,644 |                    36,841 |                     610 |                      2,197 |                                        6% |                                34,940 |                                 39,119 |
|                 [France](/france) |           29,734 |                    30,756 |                     459 |                      1,022 |                                        3% |                                29,771 |                                 34,896 |
|                   [Spain](/spain) |           28,327 |                    29,395 |                     626 |                      1,068 |                                        4% |                                28,384 |                                 31,976 |
|               [Germany](/germany) |            8,928 |                    10,585 |                     128 |                      1,657 |                                       19% |                                 9,053 |                                 14,176 |
|               [Belgium](/belgium) |            9,722 |                     9,967 |                     870 |                        245 |                                        3% |                                 9,745 |                                 10,547 |
|       [Netherlands](/netherlands) |            6,116 |                     6,627 |                     383 |                        511 |                                        8% |                                 6,172 |                                  7,627 |
|                 [Sweden](/sweden) |            5,209 |                     6,414 |                     627 |                      1,205 |                                       23% |                                 5,525 |                                  8,081 |
|               [Ukraine](/ukraine) |            1,061 |                     3,172 |                      72 |                      2,111 |                                      199% |                                 1,697 |                                  5,178 |
|                 [Poland](/poland) |            1,396 |                     3,170 |                      83 |                      1,774 |                                      127% |                                 1,857 |                                  4,770 |
|               [Romania](/romania) |            1,555 |                     2,659 |                     137 |                      1,104 |                                       71% |                                 1,795 |                                  4,041 |
|       [Switzerland](/switzerland) |            1,958 |                     2,056 |                     239 |                         98 |                                        5% |                                 1,971 |                                  2,328 |
|             [Portugal](/portugal) |            1,543 |                     1,875 |                     182 |                        332 |                                       22% |                                 1,619 |                                  2,476 |
|               [Ireland](/ireland) |            1,726 |                     1,826 |                     372 |                        100 |                                        6% |                                 1,737 |                                  2,253 |
|               [Moldova](/moldova) |              495 |                     1,549 |                     383 |                      1,054 |                                      213% |                                   983 |                                  2,320 |
|               [Belarus](/belarus) |              362 |                       811 |                      86 |                        449 |                                      124% |                                   479 |                                  1,802 |
|               [Hungary](/hungary) |              576 |                       783 |                      80 |                        207 |                                       36% |                                   602 |                                  1,172 |
|               [Austria](/austria) |              693 |                       768 |                      87 |                         75 |                                       11% |                                   707 |                                    949 |
|               [Denmark](/denmark) |              603 |                       679 |                     117 |                         76 |                                       13% |                                   622 |                                    846 |
|             [Bulgaria](/bulgaria) |              209 |                       656 |                      94 |                        447 |                                      214% |                                   342 |                                  1,072 |
|               [Czechia](/czechia) |              343 |                       439 |                      41 |                         96 |                                       28% |                                   353 |                                    566 |
|               [Finland](/finland) |              327 |                       367 |                      67 |                         40 |                                       12% |                                   332 |                                    471 |
|                 [Serbia](/serbia) |              263 |                       332 |                      48 |                         69 |                                       26% |                                   281 |                                    463 |
|                 [Norway](/norway) |              249 |                       274 |                      51 |                         25 |                                       10% |                                   256 |                                    319 |
|                 [Greece](/greece) |              190 |                       223 |                      21 |                         33 |                                       17% |                                   203 |                                    279 |
|               [Croatia](/croatia) |              107 |                       131 |                      32 |                         24 |                                       22% |                                   113 |                                    169 |
|         [Luxembourg](/luxembourg) |              110 |                       120 |                     195 |                         10 |                                        9% |                                   112 |                                    141 |
|             [Slovenia](/slovenia) |              109 |                       119 |                      57 |                         10 |                                        9% |                                   111 |                                    144 |
|           [Lithuania](/lithuania) |               78 |                       116 |                      42 |                         38 |                                       49% |                                    88 |                                    174 |
|               [Estonia](/estonia) |               69 |                        94 |                      71 |                         25 |                                       36% |                                    76 |                                    166 |
|                 [Latvia](/latvia) |               30 |                        53 |                      28 |                         23 |                                       77% |                                    33 |                                     87 |
|             [Slovakia](/slovakia) |               28 |                        36 |                       7 |                          8 |                                       29% |                                    28 |                                     69 |
|                 [Cyprus](/cyprus) |               19 |                        28 |                      32 |                          9 |                                       47% |                                    20 |                                     45 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    10 |                                     22 |
|                   [Malta](/malta) |                9 |                        11 |                      22 |                          2 |                                       22% |                                    10 |                                     12 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-10-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          172,960 |                   590,758 |                     114 |                    417,798 |                                      242% |                               338,223 |                                995,036 |
|                             [Brazil](/brazil) |           53,830 |                   137,272 |                     650 |                     83,442 |                                      155% |                               102,439 |                                218,475 |
|                               [India](/india) |           14,894 |                   111,890 |                      82 |                     96,996 |                                      651% |                                37,073 |                                246,839 |
|                             [Mexico](/mexico) |           24,324 |                   105,546 |                     827 |                     81,222 |                                      334% |                                65,026 |                                138,787 |
|                         [Pakistan](/pakistan) |            3,903 |                    27,412 |                     127 |                     23,509 |                                      602% |                                10,898 |                                 59,630 |
|                                 [Peru](/peru) |            8,586 |                    22,994 |                     707 |                     14,408 |                                      168% |                                15,240 |                                 34,553 |
|                             [Russia](/russia) |            8,503 |                    20,228 |                     139 |                     11,725 |                                      138% |                                12,096 |                                 35,995 |
|                         [Colombia](/colombia) |            2,524 |                    19,684 |                     391 |                     17,160 |                                      680% |                                 9,551 |                                 28,029 |
|                                 [Iran](/iran) |            9,996 |                    19,526 |                     235 |                      9,530 |                                       95% |                                12,722 |                                 27,089 |
|                 [South Africa](/south-africa) |            2,205 |                    18,520 |                     316 |                     16,315 |                                      740% |                                 8,737 |                                 26,931 |
|                               [Chile](/chile) |            4,731 |                    13,253 |                     699 |                      8,522 |                                      180% |                                 7,303 |                                 19,858 |
|                               [Egypt](/egypt) |            2,450 |                    12,608 |                     126 |                     10,158 |                                      415% |                                 6,998 |                                 20,427 |
|                             [Canada](/canada) |            8,544 |                    11,452 |                     306 |                      2,908 |                                       34% |                                 9,083 |                                 18,119 |
|                     [Bangladesh](/bangladesh) |            1,582 |                     9,310 |                      57 |                      7,728 |                                      488% |                                 4,450 |                                 16,188 |
|                       [Indonesia](/indonesia) |            2,573 |                     7,965 |                      29 |                      5,392 |                                      210% |                                 4,010 |                                 13,760 |
|                             [Turkey](/turkey) |            5,025 |                     7,724 |                      93 |                      2,699 |                                       54% |                                 5,451 |                                 13,739 |
|                       [Argentina](/argentina) |            1,116 |                     6,553 |                     146 |                      5,437 |                                      487% |                                 2,458 |                                 12,582 |
|                 [Saudi Arabia](/saudi-arabia) |            1,387 |                     6,271 |                     183 |                      4,884 |                                      352% |                                 3,605 |                                  9,053 |
|                           [Ecuador](/ecuador) |            4,274 |                     5,978 |                     344 |                      1,704 |                                       40% |                                 4,638 |                                 10,513 |
|                           [Bolivia](/bolivia) |              876 |                     5,894 |                     512 |                      5,018 |                                      573% |                                 2,822 |                                  9,685 |
|                               [China](/china) |            4,640 |                     4,650 |                       3 |                         10 |                                        0% |                                 4,640 |                                  4,704 |
|                           [Nigeria](/nigeria) |              542 |                     2,442 |                      12 |                      1,900 |                                      351% |                                   906 |                                  5,109 |
|                   [Philippines](/philippines) |            1,204 |                     2,415 |                      22 |                      1,211 |                                      101% |                                 1,304 |                                  4,369 |
|                           [Algeria](/algeria) |              869 |                     2,178 |                      51 |                      1,309 |                                      151% |                                 1,248 |                                  4,524 |
|                         [Honduras](/honduras) |              417 |                     1,906 |                     196 |                      1,489 |                                      357% |                                   960 |                                  3,213 |
|                             [Panama](/panama) |              547 |                     1,658 |                     390 |                      1,111 |                                      203% |                                   830 |                                  2,874 |
|     [Dominican Republic](/dominican-republic) |              691 |                     1,653 |                     154 |                        962 |                                      139% |                                   858 |                                  4,102 |
|                               [Japan](/japan) |              967 |                     1,291 |                      10 |                        324 |                                       34% |                                   973 |                                  1,865 |
|                             [Kuwait](/kuwait) |              337 |                       607 |                     144 |                        270 |                                       80% |                                   406 |                                  1,022 |
| [United Arab Emirates](/united-arab-emirates) |              307 |                       434 |                      44 |                        127 |                                       41% |                                   335 |                                    767 |
|                             [Israel](/israel) |              308 |                       389 |                      46 |                         81 |                                       26% |                                   323 |                                    614 |
|                   [South Korea](/south-korea) |              282 |                       341 |                       7 |                         59 |                                       21% |                                   285 |                                    538 |
|                         [Malaysia](/malaysia) |              121 |                       251 |                       8 |                        130 |                                      107% |                                   137 |                                    478 |
|                           [Morocco](/morocco) |              216 |                       248 |                       7 |                         32 |                                       15% |                                   224 |                                    324 |
|                       [Australia](/australia) |              104 |                       113 |                       4 |                          9 |                                        9% |                                   104 |                                    151 |
|                                 [Cuba](/cuba) |               85 |                       102 |                       9 |                         17 |                                       20% |                                    90 |                                    130 |
