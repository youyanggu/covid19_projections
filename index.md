We present an intuitive model that uses machine learning techniques to make COVID-19 projections for infections and deaths for all 50 US states and more than 60 countries.

On this page:
* [View US projections](#view-projections)
* [View global projections](#global-projections)
* [Likelihoods of death milestones in US](#us-deaths-likelihoods)
* [Summary of US projections](#us-summary)
* [Summary of Europe projections](#europe-summary)
* [Summary of Rest of World projections](#rest-of-world-summary)

## Recent Updates

* **May 17:** See how our models have performed historically compared to other models [here](/about/#historical-performance).

* **May 17:** We added a tests-per-day target for each region based on Harvard Global Health Institute's [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual. You can see this estimate above the "Newly Infected" graph on each projection page (e.g. we estimate 1.3 million tests/day are needed for the [US](/us)). Download the raw data [here](https://github.com/youyanggu/covid19_projections/tree/master/tests_target).

* **May 16:** We added a plot of our estimate of the effective reproduction number (R_t) over time to all of our projections. If R_t is greater than 1, it means that the number of cases is growing. The ultimate goal is to keep R_t under 1. BBC provides a [simple explanation](https://www.bbc.com/news/health-52473523) for understanding the importance of the R value.

* **May 14:** See how the US would have fared if everyone began social distancing [one week earlier](/us-1weekearlier) or [one week later](/us-1weeklater).

* **May 13:** If you add `-noreopen` to the end of any projections page URL, you can see our projections with the assumption that there are no reopenings. E.g. [covid19-projections.com/us](/us) --> [covid19-projections.com/us-noreopen](/us-noreopen). Some caveats [here](https://twitter.com/youyanggu/status/1260678502107344896).

* **May 12:** We added 23 additional countries. The countries our projections cover encompass 6.3 billion people and account for over 99% of all global COVID-19 deaths. View our global projections [here](#global-projections).

**State-by-state Reopenings:** To date, we are one of the only models [referenced by the CDC](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/forecasting-us.html) that factors in individual state re-openings. We update each US state's reopening timeline according to [The New York Times](https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html). Learn more about our social distancing assumptions [here](/about/#assumptions).

## Current Projection for US - Updated Daily - Last Updated: May 18 (3am ET):
<p align="center">
  Current Total: <b>89,559</b> deaths | Projected Total: <b>196,642</b> deaths by Aug 4, 2020 (Range: 121-339k)<br>
  Currently Infected: <b>0.6%</b> | Total Infected: <b>3.5%</b> {% include iframe.html %}
</p>

## US Deaths Likelihoods

Below, we present the most likely dates that the US will surpass certain deaths milestones, as well as the probabilities of the US surpassing those milestones by different time horizons. For example, we estimate a 49% chance that the US surpasses 125,000 deaths by June 15, with June 15 being the most likely date.

Last updated: May 18, 2020

|   US deaths surpass: |   Most likely date: |
|----------------------|---------------------|
|               90,000 |        May 18, 2020 |
|              100,000 |        May 25, 2020 |
|              125,000 |        Jun 15, 2020 |

<br>

|   US deaths surpass: |   By Jun 1 |   By Jun 15 |   By Jul 1 |   By Jul 15 |   By Aug 1 |
|----------------------|------------|-------------|------------|-------------|------------|
|               90,000 |       >99% |        >99% |       >99% |        >99% |       >99% |
|              100,000 |        98% |         99% |       >99% |        >99% |       >99% |
|              125,000 |        <1% |         49% |        83% |         92% |        95% |
|              150,000 |        <1% |          3% |        39% |         63% |        77% |
|              175,000 |        <1% |         <1% |        12% |         35% |        55% |
|              200,000 |        <1% |         <1% |         2% |         18% |        37% |
|              250,000 |        <1% |         <1% |        <1% |          3% |        15% |
|              300,000 |        <1% |         <1% |        <1% |         <1% |         6% |
|              350,000 |        <1% |         <1% |        <1% |         <1% |         1% |

[Back to Top](#top)

## View Projections

Below you can find our projections for every US state and 63 countries (including all 27 European Union countries).

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

### Global Projections

| Europe |  |  |
| --- | --- | --- |
| [Austria](/austria) | [Hungary](/hungary) | [Portugal](/portugal) |
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
| [Greece](/greece) | [Poland](/poland) |

<br />

| Rest of World |  |  |
| --- | --- | --- |
| [Algeria](/algeria) | [Egypt](/egypt) | [Pakistan](/pakistan) |
| [Argentina](/argentina) | [India](/india) | [Panama](/panama) |
| [Bangladesh](/bangladesh) | [Indonesia](/indonesia) | [Peru](/peru) |
| [Brazil](/brazil) | [Iran](/iran) | [Philippines](/philippines) |
| [Canada](/canada) | [Israel](/israel) | [Russia](/russia) |
| [Chile](/chile) | [Japan](/japan) | [Saudi Arabia](/saudi-arabia) |
| [China](/china) | [Malaysia](/malaysia) | [South Africa](/south-africa) |
| [Colombia](/colombia) | [Mexico](/mexico) | [South Korea](/south-korea) |
| [Dominican Republic](/dominican-republic) | [Morocco](/morocco) | [Turkey](/turkey) |
| [Ecuador](/ecuador) | [Nigeria](/nigeria) |

[Back to Top](#top)

### US Summary

States are ordered by descending projected deaths (by August 4).

|                                |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|--------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|         *[United States](/us)* |           89,559 |                   196,642 |                     593 |                    107,083 |                                      120% |                               121,081 |                                338,950 |
|             [New York](/us-ny) |           28,232 |                    33,559 |                   1,725 |                      5,327 |                                       19% |                                30,160 |                                 41,628 |
|             [Illinois](/us-il) |            4,177 |                    17,981 |                   1,419 |                     13,804 |                                      330% |                                 9,280 |                                 29,116 |
|           [New Jersey](/us-nj) |           10,363 |                    16,629 |                   1,872 |                      6,266 |                                       60% |                                12,208 |                                 24,099 |
|         [Pennsylvania](/us-pa) |            4,495 |                    12,323 |                     963 |                      7,828 |                                      174% |                                 6,798 |                                 20,710 |
|        [Massachusetts](/us-ma) |            5,797 |                    10,639 |                   1,531 |                      4,842 |                                       84% |                                 7,237 |                                 17,707 |
|           [California](/us-ca) |            3,240 |                     9,819 |                     249 |                      6,579 |                                      203% |                                 4,420 |                                 22,957 |
|                [Texas](/us-tx) |            1,343 |                     7,075 |                     244 |                      5,732 |                                      427% |                                 2,935 |                                 15,073 |
|             [Michigan](/us-mi) |            4,891 |                     6,737 |                     675 |                      1,846 |                                       38% |                                 5,563 |                                  9,299 |
|                 [Ohio](/us-oh) |            1,625 |                     6,707 |                     574 |                      5,082 |                                      313% |                                 2,872 |                                 14,784 |
|              [Indiana](/us-in) |            1,751 |                     6,665 |                     990 |                      4,914 |                                      281% |                                 2,942 |                                 13,891 |
|             [Maryland](/us-md) |            1,992 |                     5,593 |                     925 |                      3,601 |                                      181% |                                 2,760 |                                 10,948 |
|              [Florida](/us-fl) |            1,973 |                     5,458 |                     254 |                      3,485 |                                      177% |                                 2,626 |                                 11,500 |
|          [Connecticut](/us-ct) |            3,408 |                     5,457 |                   1,531 |                      2,049 |                                       60% |                                 4,031 |                                  8,443 |
|              [Arizona](/us-az) |              680 |                     4,671 |                     642 |                      3,991 |                                      587% |                                 2,086 |                                  8,904 |
|              [Georgia](/us-ga) |            1,610 |                     4,034 |                     380 |                      2,424 |                                      151% |                                 2,169 |                                  7,755 |
|             [Colorado](/us-co) |            1,215 |                     3,935 |                     683 |                      2,720 |                                      224% |                                 2,002 |                                  7,518 |
|            [Louisiana](/us-la) |            2,491 |                     3,817 |                     821 |                      1,326 |                                       53% |                                 2,970 |                                  5,603 |
|             [Virginia](/us-va) |            1,010 |                     3,503 |                     410 |                      2,493 |                                      247% |                                 1,464 |                                  8,650 |
|            [Minnesota](/us-mn) |              731 |                     3,448 |                     611 |                      2,717 |                                      372% |                                 1,281 |                                  7,573 |
|          [Mississippi](/us-ms) |              521 |                     2,821 |                     948 |                      2,300 |                                      441% |                                 1,243 |                                  5,296 |
|                 [Iowa](/us-ia) |              351 |                     2,727 |                     864 |                      2,376 |                                      677% |                                 1,359 |                                  4,739 |
|              [Alabama](/us-al) |              488 |                     2,588 |                     528 |                      2,100 |                                      430% |                                 1,250 |                                  4,798 |
|             [Missouri](/us-mo) |              600 |                     2,519 |                     410 |                      1,919 |                                      320% |                                 1,161 |                                  4,861 |
|       [North Carolina](/us-nc) |              686 |                     2,215 |                     211 |                      1,529 |                                      223% |                                 1,093 |                                  4,693 |
|       [South Carolina](/us-sc) |              385 |                     1,732 |                     336 |                      1,347 |                                      350% |                                   696 |                                  3,836 |
|           [New Mexico](/us-nm) |              265 |                     1,501 |                     716 |                      1,236 |                                      466% |                                   663 |                                  2,937 |
|           [Washington](/us-wa) |            1,001 |                     1,435 |                     188 |                        434 |                                       43% |                                 1,136 |                                  2,177 |
|             [Delaware](/us-de) |              290 |                     1,352 |                   1,388 |                      1,062 |                                      366% |                                   690 |                                  2,406 |
|         [Rhode Island](/us-ri) |              499 |                     1,294 |                   1,221 |                        795 |                                      159% |                                   776 |                                  2,316 |
|        [New Hampshire](/us-nh) |              172 |                     1,132 |                     833 |                        960 |                                      558% |                                   552 |                                  2,058 |
| [District of Columbia](/us-dc) |              383 |                       956 |                   1,355 |                        573 |                                      150% |                                   560 |                                  1,583 |
|            [Wisconsin](/us-wi) |              453 |                       907 |                     156 |                        454 |                                      100% |                                   628 |                                  1,537 |
|               [Nevada](/us-nv) |              350 |                       816 |                     265 |                        466 |                                      133% |                                   508 |                                  1,406 |
|             [Kentucky](/us-ky) |              334 |                       632 |                     141 |                        298 |                                       89% |                                   422 |                                  1,049 |
|             [Nebraska](/us-ne) |              123 |                       624 |                     323 |                        501 |                                      407% |                                   293 |                                  1,264 |
|            [Tennessee](/us-tn) |              298 |                       571 |                      84 |                        273 |                                       92% |                                   420 |                                    961 |
|             [Oklahoma](/us-ok) |              288 |                       483 |                     122 |                        195 |                                       68% |                                   363 |                                    748 |
|               [Kansas](/us-ks) |              195 |                       370 |                     127 |                        175 |                                       90% |                                   229 |                                    787 |
|                 [Utah](/us-ut) |               80 |                       317 |                      99 |                        237 |                                      296% |                                   141 |                                    699 |
|         [South Dakota](/us-sd) |               44 |                       236 |                     267 |                        192 |                                      436% |                                   100 |                                    502 |
|               [Oregon](/us-or) |              137 |                       218 |                      52 |                         81 |                                       59% |                                   165 |                                    338 |
|         [North Dakota](/us-nd) |               43 |                       215 |                     282 |                        172 |                                      400% |                                    94 |                                    451 |
|             [Arkansas](/us-ar) |               98 |                       208 |                      69 |                        110 |                                      112% |                                   156 |                                    336 |
|          [Puerto Rico](/us-pr) |              123 |                       195 |                      61 |                         72 |                                       59% |                                   155 |                                    282 |
|        [West Virginia](/us-wv) |               67 |                       140 |                      78 |                         73 |                                      109% |                                    94 |                                    260 |
|                [Maine](/us-me) |               70 |                       114 |                      85 |                         44 |                                       63% |                                    91 |                                    152 |
|                [Idaho](/us-id) |               73 |                        98 |                      55 |                         25 |                                       34% |                                    84 |                                    114 |
|              [Vermont](/us-vt) |               54 |                        71 |                     114 |                         17 |                                       31% |                                    64 |                                     78 |
|               [Hawaii](/us-hi) |               17 |                        27 |                      19 |                         10 |                                       59% |                                    21 |                                     32 |
|              [Montana](/us-mt) |               16 |                        22 |                      21 |                          6 |                                       38% |                                    20 |                                     27 |
|              [Wyoming](/us-wy) |                8 |                        16 |                      28 |                          8 |                                      100% |                                    14 |                                     19 |
|               [Alaska](/us-ak) |               10 |                        14 |                      19 |                          4 |                                       40% |                                    13 |                                     16 |
|                 [Guam](/us-gu) |                5 |                        10 |                      60 |                          5 |                                      100% |                                     8 |                                     14 |
|       [Virgin Islands](/us-vi) |                6 |                        10 |                      95 |                          4 |                                       67% |                                    10 |                                     12 |

[Back to Top](#top)

### Europe Summary

Countries are ordered by descending projected deaths (by 2020-08-04). Our Europe estimates currently include 34 European countries (including the entire European Union).

|                                   |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-----------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                          *Europe* |          159,550 |                   220,242 |                     376 |                     60,692 |                                       38% |                               178,681 |                                309,086 |
| [United Kingdom](/united-kingdom) |           34,716 |                    50,818 |                     753 |                     16,102 |                                       46% |                                38,879 |                                 74,146 |
|                   [Italy](/italy) |           31,908 |                    38,997 |                     646 |                      7,089 |                                       22% |                                34,580 |                                 48,178 |
|                 [France](/france) |           28,111 |                    36,290 |                     542 |                      8,179 |                                       29% |                                30,833 |                                 50,971 |
|                   [Spain](/spain) |           27,563 |                    31,785 |                     677 |                      4,222 |                                       15% |                                28,909 |                                 38,386 |
|               [Germany](/germany) |            7,962 |                    10,901 |                     131 |                      2,939 |                                       37% |                                 8,654 |                                 16,729 |
|               [Belgium](/belgium) |            9,052 |                    10,417 |                     909 |                      1,365 |                                       15% |                                 9,374 |                                 12,841 |
|               [Ukraine](/ukraine) |              514 |                     7,683 |                     175 |                      7,169 |                                     1395% |                                 2,460 |                                 16,810 |
|       [Netherlands](/netherlands) |            5,699 |                     7,604 |                     440 |                      1,905 |                                       33% |                                 6,242 |                                 10,366 |
|                 [Sweden](/sweden) |            3,679 |                     7,516 |                     735 |                      3,837 |                                      104% |                                 5,757 |                                 10,802 |
|               [Romania](/romania) |            1,107 |                     3,010 |                     155 |                      1,903 |                                      172% |                                 1,902 |                                  5,132 |
|                 [Poland](/poland) |              925 |                     2,528 |                      67 |                      1,603 |                                      173% |                                 1,307 |                                  5,189 |
|       [Switzerland](/switzerland) |            1,881 |                     2,217 |                     258 |                        336 |                                       18% |                                 1,981 |                                  2,818 |
|               [Ireland](/ireland) |            1,543 |                     1,964 |                     400 |                        421 |                                       27% |                                 1,656 |                                  2,879 |
|             [Portugal](/portugal) |            1,218 |                     1,846 |                     180 |                        628 |                                       52% |                                 1,476 |                                  2,664 |
|               [Moldova](/moldova) |              211 |                     1,400 |                     346 |                      1,189 |                                      564% |                                   545 |                                  3,393 |
|               [Austria](/austria) |              629 |                       775 |                      87 |                        146 |                                       23% |                                   686 |                                    951 |
|               [Hungary](/hungary) |              451 |                       775 |                      79 |                        324 |                                       72% |                                   523 |                                  1,479 |
|               [Denmark](/denmark) |              547 |                       746 |                     128 |                        199 |                                       36% |                                   634 |                                    981 |
|               [Finland](/finland) |              298 |                       556 |                     101 |                        258 |                                       87% |                                   362 |                                  1,019 |
|               [Czechia](/czechia) |              298 |                       402 |                      38 |                        104 |                                       35% |                                   358 |                                    463 |
|                 [Serbia](/serbia) |              230 |                       395 |                      45 |                        165 |                                       72% |                                   305 |                                    641 |
|             [Bulgaria](/bulgaria) |              108 |                       377 |                      54 |                        269 |                                      249% |                                   207 |                                    692 |
|                 [Norway](/norway) |              232 |                       280 |                      52 |                         48 |                                       21% |                                   249 |                                    328 |
|                 [Greece](/greece) |              163 |                       215 |                      20 |                         52 |                                       32% |                                   188 |                                    260 |
|               [Croatia](/croatia) |               95 |                       187 |                      46 |                         92 |                                       97% |                                   125 |                                    312 |
|         [Luxembourg](/luxembourg) |              107 |                       134 |                     218 |                         27 |                                       25% |                                   121 |                                    152 |
|             [Slovenia](/slovenia) |              104 |                       131 |                      63 |                         27 |                                       26% |                                   113 |                                    164 |
|               [Estonia](/estonia) |               63 |                        92 |                      69 |                         29 |                                       46% |                                    81 |                                    103 |
|           [Lithuania](/lithuania) |               56 |                        82 |                      29 |                         26 |                                       46% |                                    70 |                                     99 |
|             [Slovakia](/slovakia) |               28 |                        38 |                       7 |                         10 |                                       36% |                                    31 |                                     48 |
|                 [Latvia](/latvia) |               19 |                        35 |                      18 |                         16 |                                       84% |                                    30 |                                     40 |
|                 [Cyprus](/cyprus) |               17 |                        24 |                      27 |                          7 |                                       41% |                                    22 |                                     26 |
|               [Iceland](/iceland) |               10 |                        13 |                      38 |                          3 |                                       30% |                                    12 |                                     14 |
|                   [Malta](/malta) |                6 |                         9 |                      18 |                          3 |                                       50% |                                     9 |                                     10 |

[Back to Top](#top)

### Rest of World Summary

Countries are ordered by descending projected deaths (by 2020-08-04).

|                                           |   Current Deaths |   Projected Deaths - Mean |   Projected Deaths / 1M |   Additional Deaths - Mean |   Additional Deaths (% of Current Deaths) |   Projected Deaths - 2.5th Percentile |   Projected Deaths - 97.5th Percentile |
|-------------------------------------------|------------------|---------------------------|-------------------------|----------------------------|-------------------------------------------|---------------------------------------|----------------------------------------|
|                           *Rest of World* |           62,797 |                   372,779 |                      73 |                    309,982 |                                      494% |                               115,446 |                                929,291 |
|                         [Brazil](/brazil) |           16,118 |                   143,834 |                     682 |                    127,716 |                                      792% |                                39,729 |                                353,770 |
|                         [Mexico](/mexico) |            5,177 |                    72,926 |                     572 |                     67,749 |                                     1309% |                                14,099 |                                164,218 |
|                           [India](/india) |            3,025 |                    42,012 |                      31 |                     38,987 |                                     1289% |                                 7,547 |                                159,258 |
|                         [Russia](/russia) |            2,631 |                    17,289 |                     119 |                     14,658 |                                      557% |                                 4,644 |                                 58,041 |
|                         [Canada](/canada) |            5,903 |                    15,079 |                     403 |                      9,176 |                                      155% |                                 8,753 |                                 27,544 |
|                             [Iran](/iran) |            6,988 |                    11,201 |                     135 |                      4,213 |                                       60% |                                 7,769 |                                 18,617 |
|                             [Peru](/peru) |            2,648 |                    10,085 |                     310 |                      7,437 |                                      281% |                                 3,862 |                                 17,783 |
|                       [Ecuador](/ecuador) |            2,736 |                     7,753 |                     446 |                      5,017 |                                      183% |                                 3,755 |                                 15,850 |
|             [South Africa](/south-africa) |              264 |                     5,636 |                      96 |                      5,372 |                                     2035% |                                 1,673 |                                 15,520 |
|                         [Turkey](/turkey) |            4,140 |                     5,628 |                      67 |                      1,488 |                                       36% |                                 4,688 |                                  8,237 |
|                     [Colombia](/colombia) |              574 |                     5,134 |                     102 |                      4,560 |                                      794% |                                 1,589 |                                 11,945 |
|                           [Chile](/chile) |              450 |                     4,831 |                     255 |                      4,381 |                                      974% |                                 1,715 |                                  9,765 |
|                     [Pakistan](/pakistan) |              873 |                     4,676 |                      22 |                      3,803 |                                      436% |                                 1,323 |                                 12,712 |
|                           [China](/china) |            4,638 |                     4,642 |                       3 |                          4 |                                        0% |                                 4,638 |                                  4,667 |
|                           [Egypt](/egypt) |              630 |                     3,625 |                      36 |                      2,995 |                                      475% |                                 1,079 |                                 11,096 |
|                 [Bangladesh](/bangladesh) |              328 |                     3,206 |                      20 |                      2,878 |                                      877% |                                   860 |                                  8,361 |
|             [Saudi Arabia](/saudi-arabia) |              312 |                     2,687 |                      78 |                      2,375 |                                      761% |                                   933 |                                  6,578 |
|                   [Indonesia](/indonesia) |            1,148 |                     2,378 |                       9 |                      1,230 |                                      107% |                                 1,443 |                                  4,380 |
|                   [Argentina](/argentina) |              373 |                     2,345 |                      52 |                      1,972 |                                      529% |                                   752 |                                  6,571 |
|               [Philippines](/philippines) |              824 |                     2,046 |                      19 |                      1,222 |                                      148% |                                 1,015 |                                  3,901 |
|                           [Japan](/japan) |              744 |                     1,821 |                      14 |                      1,077 |                                      145% |                                   890 |                                  3,308 |
|                         [Panama](/panama) |              275 |                       802 |                     189 |                        527 |                                      192% |                                   377 |                                  1,913 |
| [Dominican Republic](/dominican-republic) |              428 |                       775 |                      72 |                        347 |                                       81% |                                   523 |                                  1,386 |
|                       [Nigeria](/nigeria) |              182 |                       656 |                       3 |                        474 |                                      260% |                                   283 |                                  1,695 |
|                       [Algeria](/algeria) |              548 |                       655 |                      15 |                        107 |                                       20% |                                   578 |                                    869 |
|                         [Israel](/israel) |              272 |                       359 |                      42 |                         87 |                                       32% |                                   308 |                                    471 |
|               [South Korea](/south-korea) |              263 |                       326 |                       6 |                         63 |                                       24% |                                   284 |                                    415 |
|                       [Morocco](/morocco) |              192 |                       225 |                       6 |                         33 |                                       17% |                                   208 |                                    255 |
|                     [Malaysia](/malaysia) |              113 |                       147 |                       5 |                         34 |                                       30% |                                   129 |                                    165 |
