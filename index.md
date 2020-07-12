We present an intuitive model that builds machine learning techniques on top of a classic infectious disease model to make COVID-19 infections and deaths projections for the US, all 50 US states, and more than 70 countries. The countries our projections cover encompass 6.4 billion people and account for 99% of all global COVID-19 deaths.

Our infections estimate includes all infected individuals of the SARS-CoV-2 virus, not just those that took a COVID-19 test and tested positive. The vast majority of infected individuals in our estimates do not get tested, and thus do not get reported as a positive case. As of July, we estimate the true number of infected individuals in the US is ~5x higher than the reported cases.

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
* **July 11:** See how our [late May projections](/about/#late-may-projections) have performed for Florida, California, Arizona, and Texas, four of the most heavily impacted states post-reopening.
* **July 8:** We have extended our projections through November 1, 2020. As we predicted in our June 17 update, deaths decreased until the 4th of July weekend and are now gradually increasing. We are now incorporating a potential for a [fall wave](/about/#fall-wave) as a result of school reopenings and the beginning of influenza season, leading to a wider confidence interval.
* **July 1:** We updated our infections estimate to closer match the observed data. We now estimate there to be around 200k new infections per day in the US, 4-5x higher than the number of reported cases. Because we use [only deaths](/about/#data-and-output) in our model, we believe this estimate may still be an underestimate of the true prevalence.
* **June 24:** We have open-sourced our [SEIR simulator](https://github.com/youyanggu/yyg-seir-simulator). This is the underlying SEIR model without the machine learning layer to learn the parameters. If your system supports Python, you can generate your own simulations in under 5 minutes. No prior Python experience is needed.
* *June 17:* Our latest model update features a tighter confidence interval and improved modeling of reopenings. We incorporated a slower reopening, a greater lag between cases and deaths, and a lower proportion of severe cases. As a result, we now expect deaths to continue to decrease until July 4th weekend.
* *June 16:* We have open-sourced our code to [evaluate COVID-19 models](https://github.com/youyanggu/covid19-forecast-hub-evaluation). The goal of this project is to evaluate various models' historical point forecasts in a transparent, rigorous, and non-biased manner.

<a href="https://twitter.com/youyanggu" class="twitter-follow-button" data-show-count="false">Follow for updates</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Current US Projections
### Updated Daily - Last Updated: July 12 (3am ET):
<p align="center">
  Current Total: <b>134,774</b> deaths | Projected Total: <b>222,100 deaths by Nov 1, 2020</b> (Range: 177-297k) | 203,400 deaths by Oct 1, 2020<br>
  Currently Infected: <b>1.2%</b> | Total Infected: <b>7.2%</b> {% include iframe.html %}
</p>

[Back to Top](#top)

## COVID-19 Dashboard

To see more maps or for more details (including how we calculate the C19Pro Score), visit our [Maps](/maps) page.

{% include iframe_r_map.html %}
[Back to Top](#top)

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons.

Last updated: July 12, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|              140,000 |        Jul 19, 2020 |
|              150,000 |         Aug 1, 2020 |
|              175,000 |        Aug 28, 2020 |

<br>

|   US deaths surpass: |   By Jul 15 |   By Aug 1 |   By Aug 15 |   By Sep 1 |   By Sep 15 |   By Oct 1 |   By Oct 15 |   By Nov 1 |
|----------------------|-------------|------------|-------------|------------|-------------|------------|-------------|------------|
|              150,000 |         <1% |        48% |         99% |        99% |         99% |       >99% |        >99% |       >99% |
|              175,000 |         <1% |        <1% |          6% |        51% |         74% |        88% |         95% |        99% |
|              200,000 |         <1% |        <1% |         <1% |         7% |         24% |        41% |         52% |        63% |
|              225,000 |         <1% |        <1% |         <1% |        <1% |          5% |        14% |         22% |        32% |
|              250,000 |         <1% |        <1% |         <1% |        <1% |         <1% |         4% |          9% |        14% |
|              300,000 |         <1% |        <1% |         <1% |        <1% |         <1% |        <1% |         <1% |         2% |

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

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|             *[United States](/us)* |          134,774 |                   222,113 |                     669 |                     87,339 |                                       65% |                               177,112 |                                296,570 |
|                 [New York](/us-ny) |           32,343 |                    33,651 |                   1,730 |                      1,308 |                                        4% |                                32,384 |                                 39,098 |
|               [California](/us-ca) |            7,027 |                    21,088 |                     534 |                     14,061 |                                      200% |                                 9,297 |                                 43,031 |
|               [New Jersey](/us-nj) |           15,525 |                    16,803 |                   1,892 |                      1,278 |                                        8% |                                15,601 |                                 19,092 |
|                  [Florida](/us-fl) |            4,197 |                    15,474 |                     720 |                     11,277 |                                      269% |                                 7,584 |                                 26,719 |
|                    [Texas](/us-tx) |            3,138 |                    14,071 |                     485 |                     10,933 |                                      348% |                                 8,227 |                                 25,614 |
|             [Pennsylvania](/us-pa) |            6,897 |                     9,311 |                     727 |                      2,414 |                                       35% |                                 7,119 |                                 14,903 |
|            [Massachusetts](/us-ma) |            8,310 |                     9,077 |                   1,306 |                        767 |                                        9% |                                 8,447 |                                 10,665 |
|                 [Illinois](/us-il) |            7,369 |                     8,610 |                     679 |                      1,241 |                                       17% |                                 7,597 |                                 10,114 |
|                 [Michigan](/us-mi) |            6,313 |                     8,235 |                     825 |                      1,922 |                                       30% |                                 6,379 |                                 13,683 |
|                  [Georgia](/us-ga) |            2,996 |                     7,394 |                     696 |                      4,398 |                                      147% |                                 3,873 |                                 14,716 |
|                  [Arizona](/us-az) |            2,151 |                     6,165 |                     847 |                      4,014 |                                      187% |                                 4,361 |                                  8,606 |
|                [Louisiana](/us-la) |            3,403 |                     5,853 |                   1,259 |                      2,450 |                                       72% |                                 3,712 |                                  8,362 |
|                     [Ohio](/us-oh) |            3,036 |                     5,529 |                     473 |                      2,493 |                                       82% |                                 3,295 |                                 11,697 |
|              [Connecticut](/us-ct) |            4,348 |                     4,573 |                   1,283 |                        225 |                                        5% |                                 4,381 |                                  4,998 |
|                 [Maryland](/us-md) |            3,310 |                     4,169 |                     690 |                        859 |                                       26% |                                 3,480 |                                  5,536 |
|                  [Indiana](/us-in) |            2,756 |                     4,095 |                     608 |                      1,339 |                                       49% |                                 2,859 |                                  7,849 |
|                  [Alabama](/us-al) |            1,114 |                     4,075 |                     831 |                      2,961 |                                      266% |                                 2,074 |                                  6,896 |
|           [South Carolina](/us-sc) |              951 |                     4,014 |                     780 |                      3,063 |                                      322% |                                 2,421 |                                  6,541 |
|                 [Virginia](/us-va) |            1,962 |                     3,859 |                     452 |                      1,897 |                                       97% |                                 2,118 |                                  8,139 |
|                [Tennessee](/us-tn) |              738 |                     3,383 |                     495 |                      2,645 |                                      358% |                                 1,839 |                                  6,774 |
|           [North Carolina](/us-nc) |            1,513 |                     3,195 |                     305 |                      1,682 |                                      111% |                                 1,801 |                                  7,408 |
|              [Mississippi](/us-ms) |            1,230 |                     2,844 |                     956 |                      1,614 |                                      131% |                                 1,660 |                                  4,594 |
|               [Washington](/us-wa) |            1,424 |                     2,582 |                     339 |                      1,158 |                                       81% |                                 1,634 |                                  5,212 |
|                 [Colorado](/us-co) |            1,725 |                     2,524 |                     438 |                        799 |                                       46% |                                 1,787 |                                  5,067 |
|                [Minnesota](/us-mn) |            1,537 |                     2,211 |                     392 |                        674 |                                       44% |                                 1,653 |                                  3,466 |
|                   [Nevada](/us-nv) |              592 |                     2,165 |                     703 |                      1,573 |                                      266% |                                 1,152 |                                  3,693 |
|                 [Missouri](/us-mo) |            1,091 |                     1,960 |                     319 |                        869 |                                       80% |                                 1,183 |                                  4,132 |
|                [Wisconsin](/us-wi) |              821 |                     1,759 |                     302 |                        938 |                                      114% |                                   960 |                                  4,821 |
|                 [Kentucky](/us-ky) |              622 |                     1,431 |                     320 |                        809 |                                      130% |                                   714 |                                  3,314 |
|                 [Arkansas](/us-ar) |              319 |                     1,285 |                     426 |                        966 |                                      303% |                                   495 |                                  2,796 |
|             [Rhode Island](/us-ri) |              976 |                     1,211 |                   1,143 |                        235 |                                       24% |                                 1,030 |                                  1,494 |
|               [New Mexico](/us-nm) |              543 |                     1,052 |                     502 |                        509 |                                       94% |                                   604 |                                  2,134 |
|                     [Iowa](/us-ia) |              748 |                     1,030 |                     326 |                        282 |                                       38% |                                   779 |                                  1,797 |
|                   [Oregon](/us-or) |              232 |                       976 |                     231 |                        744 |                                      321% |                                   303 |                                  2,447 |
|                     [Utah](/us-ut) |              212 |                       866 |                     270 |                        654 |                                      308% |                                   323 |                                  2,030 |
|                 [Oklahoma](/us-ok) |              421 |                       848 |                     214 |                        427 |                                      101% |                                   468 |                                  1,920 |
|     [District of Columbia](/us-dc) |              568 |                       704 |                     998 |                        136 |                                       24% |                                   588 |                                  1,045 |
|                 [Delaware](/us-de) |              517 |                       677 |                     695 |                        160 |                                       31% |                                   536 |                                  1,037 |
|            [New Hampshire](/us-nh) |              391 |                       594 |                     437 |                        203 |                                       52% |                                   424 |                                    949 |
|                   [Kansas](/us-ks) |              295 |                       492 |                     169 |                        197 |                                       67% |                                   313 |                                  1,058 |
|                 [Nebraska](/us-ne) |              285 |                       478 |                     247 |                        193 |                                       68% |                                   346 |                                    695 |
|                    [Idaho](/us-id) |              102 |                       409 |                     229 |                        307 |                                      301% |                                   131 |                                  1,032 |
|              [Puerto Rico](/us-pr) |              167 |                       287 |                      90 |                        120 |                                       72% |                                   177 |                                    654 |
|             [South Dakota](/us-sd) |              109 |                       219 |                     248 |                        110 |                                      101% |                                   139 |                                    353 |
|                  [Montana](/us-mt) |               29 |                       197 |                     184 |                        168 |                                      579% |                                    83 |                                    483 |
|                    [Maine](/us-me) |              112 |                       189 |                     141 |                         77 |                                       69% |                                   122 |                                    418 |
|            [West Virginia](/us-wv) |               96 |                       131 |                      73 |                         35 |                                       36% |                                   102 |                                    221 |
|             [North Dakota](/us-nd) |               87 |                       130 |                     171 |                         43 |                                       49% |                                   103 |                                    184 |
|                  [Vermont](/us-vt) |               56 |                        81 |                     130 |                         25 |                                       45% |                                    58 |                                    157 |
|                   [Alaska](/us-ak) |               17 |                        53 |                      72 |                         36 |                                      212% |                                    19 |                                    183 |
|                  [Wyoming](/us-wy) |               21 |                        44 |                      76 |                         23 |                                      110% |                                    27 |                                     81 |
|                   [Hawaii](/us-hi) |               19 |                        33 |                      23 |                         14 |                                       74% |                                    21 |                                     76 |
|           [Virgin Islands](/us-vi) |                6 |                        15 |                     143 |                          9 |                                      150% |                                     6 |                                     34 |
|                     [Guam](/us-gu) |                5 |                         9 |                      54 |                          4 |                                       80% |                                     5 |                                     28 |
| [Northern Mariana Islands](/us-mp) |                2 |                         4 |                      72 |                          2 |                                      100% |                                     2 |                                     11 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-11-01). Our Europe estimates currently include 35 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          184,335 |                   205,078 |                     346 |                     20,743 |                                       11% |                               188,914 |                                234,646 |
| [United Kingdom](/united-kingdom) |           44,883 |                    49,424 |                     732 |                      4,541 |                                       10% |                                45,637 |                                 53,703 |
|                   [Italy](/italy) |           34,945 |                    35,732 |                     592 |                        787 |                                        2% |                                35,042 |                                 36,559 |
|                 [France](/france) |           30,007 |                    30,728 |                     459 |                        721 |                                        2% |                                30,030 |                                 34,050 |
|                   [Spain](/spain) |           28,403 |                    28,997 |                     618 |                        594 |                                        2% |                                28,437 |                                 30,834 |
|               [Belgium](/belgium) |            9,782 |                    10,044 |                     877 |                        262 |                                        3% |                                 9,803 |                                 10,832 |
|               [Germany](/germany) |            9,070 |                     9,492 |                     114 |                        422 |                                        5% |                                 9,113 |                                 10,510 |
|       [Netherlands](/netherlands) |            6,156 |                     6,311 |                     365 |                        155 |                                        3% |                                 6,177 |                                  6,512 |
|                 [Sweden](/sweden) |            5,526 |                     6,009 |                     587 |                        483 |                                        9% |                                 5,689 |                                  6,210 |
|               [Romania](/romania) |            1,871 |                     4,211 |                     217 |                      2,340 |                                      125% |                                 2,742 |                                  5,989 |
|                 [Serbia](/serbia) |              382 |                     3,795 |                     545 |                      3,413 |                                      893% |                                   922 |                                  8,915 |
|               [Ukraine](/ukraine) |            1,389 |                     3,316 |                      75 |                      1,927 |                                      139% |                                 2,066 |                                  4,926 |
|                 [Poland](/poland) |            1,568 |                     2,871 |                      76 |                      1,303 |                                       83% |                                 1,887 |                                  5,210 |
|             [Portugal](/portugal) |            1,654 |                     2,329 |                     227 |                        675 |                                       41% |                                 1,754 |                                  3,413 |
|       [Switzerland](/switzerland) |            1,968 |                     2,076 |                     242 |                        108 |                                        5% |                                 1,982 |                                  2,511 |
|               [Ireland](/ireland) |            1,746 |                     1,842 |                     376 |                         96 |                                        5% |                                 1,754 |                                  2,291 |
|               [Moldova](/moldova) |              640 |                     1,328 |                     328 |                        688 |                                      108% |                                 1,043 |                                  1,906 |
|               [Belarus](/belarus) |              459 |                     1,168 |                     124 |                        709 |                                      154% |                                   620 |                                  2,423 |
|             [Bulgaria](/bulgaria) |              267 |                       905 |                     129 |                        638 |                                      239% |                                   461 |                                  1,545 |
|               [Austria](/austria) |              706 |                       836 |                      94 |                        130 |                                       18% |                                   722 |                                  1,079 |
|               [Hungary](/hungary) |              595 |                       734 |                      75 |                        139 |                                       23% |                                   611 |                                  1,144 |
|               [Denmark](/denmark) |              609 |                       686 |                     118 |                         77 |                                       13% |                                   625 |                                    895 |
|               [Czechia](/czechia) |              352 |                       490 |                      46 |                        138 |                                       39% |                                   361 |                                    733 |
|               [Finland](/finland) |              329 |                       375 |                      68 |                         46 |                                       14% |                                   335 |                                    533 |
|                 [Norway](/norway) |              252 |                       275 |                      51 |                         23 |                                        9% |                                   259 |                                    320 |
|               [Croatia](/croatia) |              118 |                       265 |                      65 |                        147 |                                      125% |                                   143 |                                    395 |
|                 [Greece](/greece) |              193 |                       227 |                      21 |                         34 |                                       18% |                                   205 |                                    296 |
|         [Luxembourg](/luxembourg) |              110 |                       146 |                     238 |                         36 |                                       33% |                                   116 |                                    189 |
|             [Slovenia](/slovenia) |              111 |                       124 |                      60 |                         13 |                                       12% |                                   113 |                                    162 |
|           [Lithuania](/lithuania) |               79 |                       115 |                      41 |                         36 |                                       46% |                                    87 |                                    185 |
|               [Estonia](/estonia) |               69 |                        88 |                      66 |                         19 |                                       28% |                                    76 |                                    116 |
|             [Slovakia](/slovakia) |               28 |                        41 |                       8 |                         13 |                                       46% |                                    28 |                                     88 |
|                 [Latvia](/latvia) |               30 |                        39 |                      20 |                          9 |                                       30% |                                    32 |                                     57 |
|                 [Cyprus](/cyprus) |               19 |                        32 |                      37 |                         13 |                                       68% |                                    21 |                                     72 |
|               [Iceland](/iceland) |               10 |                        14 |                      41 |                          4 |                                       40% |                                    10 |                                     29 |
|                   [Malta](/malta) |                9 |                        13 |                      26 |                          4 |                                       44% |                                    11 |                                     14 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-11-01).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                               *Rest of World* |          233,364 |                   611,565 |                     118 |                    378,201 |                                      162% |                               390,713 |                              1,009,304 |
|                             [Brazil](/brazil) |           71,469 |                   147,237 |                     698 |                     75,768 |                                      106% |                               112,237 |                                224,398 |
|                               [India](/india) |           22,673 |                   115,209 |                      84 |                     92,536 |                                      408% |                                48,244 |                                247,112 |
|                             [Mexico](/mexico) |           34,730 |                    86,966 |                     682 |                     52,236 |                                      150% |                                64,817 |                                109,231 |
|                                 [Iran](/iran) |           12,635 |                    30,034 |                     362 |                     17,399 |                                      138% |                                21,211 |                                 45,011 |
|                             [Russia](/russia) |           11,188 |                    23,672 |                     162 |                     12,484 |                                      112% |                                15,230 |                                 44,377 |
|                                 [Peru](/peru) |           11,682 |                    23,302 |                     717 |                     11,620 |                                       99% |                                17,003 |                                 32,369 |
|                         [Colombia](/colombia) |            5,202 |                    21,622 |                     430 |                     16,420 |                                      316% |                                15,343 |                                 32,726 |
|                 [South Africa](/south-africa) |            3,971 |                    19,031 |                     325 |                     15,060 |                                      379% |                                10,131 |                                 30,373 |
|                               [Egypt](/egypt) |            3,769 |                    14,527 |                     145 |                     10,758 |                                      285% |                                 8,566 |                                 22,386 |
|                       [Indonesia](/indonesia) |            3,535 |                    13,736 |                      51 |                     10,201 |                                      289% |                                 6,225 |                                 26,168 |
|                         [Pakistan](/pakistan) |            5,197 |                    12,613 |                      58 |                      7,416 |                                      143% |                                 7,836 |                                 20,453 |
|                               [Chile](/chile) |            6,881 |                    12,267 |                     647 |                      5,386 |                                       78% |                                 7,956 |                                 16,671 |
|                       [Argentina](/argentina) |            1,810 |                    11,350 |                     253 |                      9,540 |                                      527% |                                 4,492 |                                 20,086 |
|                             [Canada](/canada) |            8,818 |                    10,264 |                     274 |                      1,446 |                                       16% |                                 9,023 |                                 13,554 |
|                           [Ecuador](/ecuador) |            5,031 |                     9,011 |                     519 |                      3,980 |                                       79% |                                 5,467 |                                 14,413 |
|                 [Saudi Arabia](/saudi-arabia) |            2,181 |                     8,679 |                     253 |                      6,498 |                                      298% |                                 5,106 |                                 12,812 |
|                             [Turkey](/turkey) |            5,344 |                     7,025 |                      84 |                      1,681 |                                       31% |                                 5,452 |                                 12,173 |
|                     [Bangladesh](/bangladesh) |            2,305 |                     6,975 |                      43 |                      4,670 |                                      203% |                                 4,243 |                                 12,819 |
|                           [Bolivia](/bolivia) |            1,754 |                     6,960 |                     605 |                      5,206 |                                      297% |                                 3,687 |                                 12,125 |
|                               [China](/china) |            4,641 |                     4,646 |                       3 |                          5 |                                        0% |                                 4,641 |                                  4,675 |
|     [Dominican Republic](/dominican-republic) |              880 |                     4,331 |                     403 |                      3,451 |                                      392% |                                 1,455 |                                  8,892 |
|                         [Honduras](/honduras) |              771 |                     4,207 |                     432 |                      3,436 |                                      446% |                                 2,715 |                                  7,171 |
|                             [Panama](/panama) |              893 |                     3,458 |                     814 |                      2,565 |                                      287% |                                 2,467 |                                  5,495 |
|                   [Philippines](/philippines) |            1,372 |                     3,310 |                      31 |                      1,938 |                                      141% |                                 1,544 |                                  7,048 |
|                           [Algeria](/algeria) |            1,004 |                     2,962 |                      69 |                      1,958 |                                      195% |                                 1,388 |                                  7,420 |
|                           [Nigeria](/nigeria) |              724 |                     2,380 |                      12 |                      1,656 |                                      229% |                                 1,085 |                                  5,275 |
|                               [Japan](/japan) |              982 |                     1,610 |                      13 |                        628 |                                       64% |                                   989 |                                  2,938 |
|                             [Israel](/israel) |              354 |                     1,587 |                     186 |                      1,233 |                                      348% |                                   478 |                                  5,756 |
|                             [Kuwait](/kuwait) |              386 |                       710 |                     169 |                        324 |                                       84% |                                   429 |                                  1,358 |
|                           [Morocco](/morocco) |              245 |                       486 |                      13 |                        241 |                                       98% |                                   276 |                                    962 |
| [United Arab Emirates](/united-arab-emirates) |              331 |                       482 |                      49 |                        151 |                                       46% |                                   349 |                                    919 |
|                   [South Korea](/south-korea) |              289 |                       347 |                       7 |                         58 |                                       20% |                                   291 |                                    502 |
|                       [Australia](/australia) |              108 |                       306 |                      12 |                        198 |                                      183% |                                   108 |                                  1,302 |
|                         [Malaysia](/malaysia) |              122 |                       157 |                       5 |                         35 |                                       29% |                                   137 |                                    188 |
|                                 [Cuba](/cuba) |               87 |                       106 |                       9 |                         19 |                                       22% |                                    92 |                                    146 |
