---
layout: default
title: COVID-19 Infections Tracker
permalink: /infections-tracker/
---

Our model tries to do what no other model currently does (to the best of our knowledge): provide an estimate for the R values and the true number of infected individuals in every region.

## Testing Targets

You can see our testing targets per day for the [US and all 50 states](https://github.com/youyanggu/covid19_projections/blob/master/tests_target/tests_target_us_by_2020-06-01.csv), [globally](https://github.com/youyanggu/covid19_projections/blob/master/tests_target/tests_target_global_by_2020-06-01.csv), and [select US counties + subregions](https://github.com/youyanggu/covid19_projections/blob/master/tests_target/tests_target_subregion_by_2020-06-01.csv). To make these estimates, we use Harvard Global Health Institute’s [study](https://globalepidemics.org/2020/05/07/hghi-projected-tests-needed-may15/) that recommends 10 contacts per infected individual.

## R<sub>0</sub> value estimates

*May 15 update:* You can now view a graph of our R_t estimates over time in all of our projections (e.g. [US](/us)). You can also download the raw R_t time series on [our GitHub](https://github.com/youyanggu/covid19_projections/tree/master/projections) (starting from May 15 projections).

*May 6 update:* You can now download our R estimates as csv files on [our GitHub](https://github.com/youyanggu/covid19_projections/tree/master/r_values).

The below [reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R) estimates are what our model has learned for each state/country. While we present a single value for the purpose of this chart, our model actually uses a weighted range of R values to make its projections. The initial R<sub>0</sub> is the R value in early-to-mid March, right before states began implementing stay-at-home orders. We provide a longer explanation of how our model works [here](/model-details).

### Notes

* Post-mitigation R is the R value after the initial mitigation strategies. For the US, this is around mid to late March. This does not necessary reflect the current R value in May, although it is a close estimate for regions that have not yet reopened. We are working on releasing estimates for post-reopening R values, although it may take several weeks to have the necessary data to compute those values.
* These are merely best estimates of the R values based on the data. The true R values can vary widely, even day-to-day.
* For example, California has a lower-than-expected R<sub>0</sub> partly because there is a significant time lag in their deaths reporting. While this does not significantly affect our projections (assuming the lag is consistent), it will result in a lower R estimate than the true value.
* Our post-mitigation R estimates may not accurately reflect the true situation for regions where no mitigation was applied, such as in Sweden or South Dakota.

{% include iframe_r_values.html %}

## Number of Total Infected Individuals by Date
This is an estimate of the total number of infected individuals by each date. The infections estimate includes **all** infected individuals, not just those that took a COVID-19 test kit and tested positive. The vast majority of infected individuals did not get tested due to 1) they are asymptomatic or only mildly symptomatic or 2) lack of available testing. As of May 18, we estimate that the true number of infections in the US is likely ~5x higher than reported cases. In March and April, when testing was not as prevalent, we estimate that ratio to be closer to 10-15x.

Last Updated: May 18

### US

|                                |     Apr 1 |    Apr 15 |     May 1 |     May 15 |      Jun 1 |     Jun 15 |      Jul 1 |     Jul 15 |      Aug 1 |
|--------------------------------|-----------|-----------|-----------|------------|------------|------------|------------|------------|------------|
| [United States](/us)           | 4,473,064 | 7,028,259 | 9,333,149 | 11,057,656 | 13,138,601 | 15,081,391 | 17,502,422 | 19,504,269 | 21,457,165 |
| [Alabama](/us-al)              |    17,801 |    34,254 |    56,646 |     79,884 |    119,590 |    164,809 |    220,548 |    264,975 |    308,045 |
| [Alaska](/us-ak)               |       687 |       896 |     1,083 |      1,218 |      1,337 |      1,394 |      1,417 |      1,419 |      1,419 |
| [Arizona](/us-az)              |    26,257 |    49,639 |    84,499 |    123,697 |    196,317 |    284,290 |    394,295 |    481,915 |    566,194 |
| [Arkansas](/us-ar)             |     4,989 |     7,924 |    11,033 |     13,475 |     16,323 |     18,436 |     20,285 |     21,352 |     22,162 |
| [California](/us-ca)           |   146,974 |   250,890 |   360,345 |    450,890 |    558,945 |    664,510 |    828,926 |  1,000,203 |  1,202,189 |
| [Colorado](/us-co)             |    58,884 |    95,082 |   136,275 |    172,300 |    223,924 |    277,894 |    344,061 |    396,096 |    445,458 |
| [Connecticut](/us-ct)          |   160,951 |   277,360 |   367,163 |    419,906 |    463,300 |    491,377 |    519,810 |    540,285 |    557,823 |
| [Delaware](/us-de)             |     9,295 |    19,724 |    33,727 |     47,463 |     65,679 |     84,215 |    112,044 |    137,466 |    161,701 |
| [District of Columbia](/us-dc) |    15,300 |    29,539 |    44,126 |     55,234 |     66,861 |     76,295 |     87,916 |     97,479 |    106,335 |
| [Florida](/us-fl)              |    98,409 |   158,263 |   218,975 |    267,379 |    330,693 |    396,182 |    482,333 |    556,144 |    633,544 |
| [Georgia](/us-ga)              |    84,179 |   130,113 |   175,239 |    216,818 |    274,316 |    322,874 |    372,421 |    407,203 |    439,527 |
| [Guam](/us-gu)                 |       654 |       907 |     1,142 |      1,303 |      1,446 |      1,525 |      1,567 |      1,578 |      1,582 |
| [Hawaii](/us-hi)               |       909 |     1,452 |     1,928 |      2,253 |      2,541 |      2,703 |      2,795 |      2,815 |      2,821 |
| [Idaho](/us-id)                |     5,084 |     6,791 |     7,965 |      8,708 |      9,406 |      9,796 |     10,004 |     10,053 |     10,069 |
| [Illinois](/us-il)             |   169,019 |   309,864 |   491,395 |    666,728 |    899,057 |  1,138,969 |  1,508,482 |  1,851,404 |  2,180,295 |
| [Indiana](/us-in)              |    74,396 |   132,423 |   200,185 |    263,346 |    363,507 |    470,716 |    593,166 |    682,221 |    759,903 |
| [Iowa](/us-ia)                 |    11,935 |    24,599 |    44,970 |     72,093 |    125,026 |    179,218 |    238,087 |    280,235 |    318,195 |
| [Kansas](/us-ks)               |    11,512 |    17,093 |    21,761 |     25,264 |     29,457 |     32,742 |     35,881 |     37,973 |     39,821 |
| [Kentucky](/us-ky)             |    19,471 |    28,875 |    37,447 |     43,499 |     49,880 |     55,122 |     60,969 |     65,537 |     70,058 |
| [Louisiana](/us-la)            |   154,343 |   216,493 |   265,022 |    295,091 |    325,542 |    348,027 |    369,386 |    383,249 |    394,528 |
| [Maine](/us-me)                |     3,464 |     5,436 |     7,205 |      8,428 |      9,557 |     10,283 |     10,872 |     11,177 |     11,385 |
| [Maryland](/us-md)             |    75,792 |   151,799 |   226,553 |    283,410 |    356,438 |    426,573 |    507,066 |    566,312 |    618,620 |
| [Massachusetts](/us-ma)        |   224,381 |   449,197 |   631,213 |    741,031 |    846,631 |    926,554 |  1,005,226 |  1,055,516 |  1,094,229 |
| [Michigan](/us-mi)             |   295,893 |   428,409 |   520,860 |    572,619 |    614,224 |    640,061 |    663,944 |    680,272 |    694,685 |
| [Minnesota](/us-mn)            |    20,089 |    49,652 |    85,182 |    116,708 |    163,243 |    217,113 |    290,627 |    351,671 |    411,955 |
| [Mississippi](/us-ms)          |    20,516 |    37,535 |    60,892 |     86,900 |    134,377 |    186,609 |    245,451 |    288,352 |    326,342 |
| [Missouri](/us-mo)             |    26,587 |    46,158 |    69,917 |     94,533 |    135,212 |    176,208 |    222,657 |    258,030 |    291,988 |
| [Montana](/us-mt)              |       891 |     1,318 |     1,610 |      1,806 |      1,993 |      2,095 |      2,149 |      2,161 |      2,165 |
| [Nebraska](/us-ne)             |     4,408 |     8,666 |    14,524 |     20,924 |     31,509 |     42,116 |     54,157 |     63,323 |     72,166 |
| [Nevada](/us-nv)               |    19,454 |    29,239 |    39,175 |     47,225 |     57,688 |     66,789 |     76,437 |     83,421 |     89,832 |
| [New Hampshire](/us-nh)        |     6,029 |    12,079 |    20,762 |     30,000 |     45,606 |     65,375 |     93,234 |    116,291 |    138,718 |
| [New Jersey](/us-nj)           |   542,349 |   863,306 | 1,126,002 |  1,287,151 |  1,422,863 |  1,512,412 |  1,605,404 |  1,672,371 |  1,728,111 |
| [New Mexico](/us-nm)           |     8,467 |    18,613 |    32,429 |     46,269 |     65,424 |     86,210 |    120,338 |    155,202 |    193,318 |
| [New York](/us-ny)             | 1,600,387 | 2,159,448 | 2,504,754 |  2,670,074 |  2,782,810 |  2,843,979 |  2,897,137 |  2,931,642 |  2,959,683 |
| [North Carolina](/us-nc)       |    25,605 |    50,578 |    77,338 |     99,201 |    126,517 |    154,115 |    191,545 |    224,679 |    260,483 |
| [North Dakota](/us-nd)         |     1,596 |     3,124 |     5,241 |      7,613 |     11,469 |     15,151 |     19,180 |     22,151 |     24,987 |
| [Ohio](/us-oh)                 |    63,846 |   120,682 |   187,384 |    248,052 |    340,758 |    445,153 |    578,892 |    686,826 |    791,602 |
| [Oklahoma](/us-ok)             |    18,011 |    25,411 |    31,784 |     36,648 |     42,007 |     45,637 |     48,483 |     49,962 |     51,010 |
| [Oregon](/us-or)               |     7,970 |    11,403 |    14,310 |     16,259 |     18,078 |     19,361 |     20,698 |     21,740 |     22,800 |
| [Pennsylvania](/us-pa)         |   172,795 |   338,699 |   511,689 |    647,709 |    796,803 |    926,386 |  1,101,281 |  1,259,401 |  1,420,207 |
| [Puerto Rico](/us-pr)          |     7,038 |    10,219 |    12,881 |     14,647 |     16,266 |     17,360 |     18,402 |     19,123 |     19,783 |
| [Rhode Island](/us-ri)         |    18,206 |    36,841 |    56,273 |     71,260 |     87,766 |    102,040 |    118,624 |    130,946 |    141,719 |
| [South Carolina](/us-sc)       |    16,803 |    29,018 |    44,104 |     58,969 |     84,011 |    112,827 |    148,951 |    178,490 |    208,095 |
| [South Dakota](/us-sd)         |     2,632 |     4,166 |     6,312 |      8,789 |     12,981 |     17,093 |     21,683 |     25,153 |     28,537 |
| [Tennessee](/us-tn)            |    17,217 |    24,808 |    32,146 |     38,176 |     45,158 |     50,085 |     54,114 |     56,314 |     57,956 |
| [Texas](/us-tx)                |    57,334 |    99,836 |   155,827 |    221,774 |    342,386 |    466,657 |    609,608 |    721,130 |    833,143 |
| [Utah](/us-ut)                 |     3,358 |     5,993 |     9,187 |     12,513 |     17,724 |     22,662 |     28,136 |     32,289 |     36,407 |
| [Vermont](/us-vt)              |     3,532 |     4,543 |     5,406 |      5,986 |      6,492 |      6,769 |      6,915 |      6,950 |      6,961 |
| [Virgin Islands](/us-vi)       |       299 |       512 |       708 |        844 |        963 |      1,028 |      1,061 |      1,065 |      1,065 |
| [Virginia](/us-va)             |    39,475 |    76,977 |   118,099 |    152,514 |    194,088 |    234,933 |    298,113 |    362,268 |    434,651 |
| [Washington](/us-wa)           |    68,137 |    87,670 |   103,528 |    113,719 |    122,931 |    129,396 |    136,392 |    142,150 |    148,201 |
| [West Virginia](/us-wv)        |     2,707 |     5,216 |     7,365 |      8,959 |     10,772 |     12,073 |     13,176 |     13,797 |     14,268 |
| [Wisconsin](/us-wi)            |    26,214 |    38,501 |    50,049 |     58,522 |     68,493 |     76,790 |     85,568 |     91,964 |     97,892 |
| [Wyoming](/us-wy)              |       162 |       447 |       742 |        970 |      1,194 |      1,320 |      1,393 |      1,409 |      1,413 |

### Global

|                                   |     Apr 1 |    Apr 15 |     May 1 |    May 15 |     Jun 1 |    Jun 15 |     Jul 1 |    Jul 15 |      Aug 1 |
|-----------------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|------------|
| [Algeria](/algeria)                       |    43,897 |    53,099 |    58,363 |    61,103 |    63,554 |    65,104 |     66,346 |     67,104 |     67,805 |
| [Argentina](/argentina)                   |    17,358 |    28,399 |    43,566 |    59,763 |    84,406 |   114,811 |    173,407 |    245,133 |    351,290 |
| [Austria](/austria)                       |    67,826 |    81,613 |    90,813 |    96,162 |   101,158 |   104,221 |    106,394 |    107,482 |    108,299 |
| [Bangladesh](/bangladesh)                 |    11,708 |    23,056 |    39,490 |    58,306 |    95,849 |   150,665 |    237,758 |    332,133 |    474,219 |
| [Belgium](/belgium)                       |   873,643 | 1,143,129 | 1,280,992 | 1,337,700 | 1,377,814 | 1,399,537 |  1,415,752 |  1,424,946 |  1,432,352 |
| [Brazil](/brazil)                         |   313,195 |   900,211 | 2,074,494 | 3,392,879 | 5,495,663 | 7,826,051 | 11,279,611 | 14,912,619 | 19,627,399 |
| [Bulgaria](/bulgaria)                     |     7,451 |    11,638 |    16,812 |    21,482 |    28,137 |    34,941 |     43,686 |     51,947 |     62,870 |
| [Canada](/canada)                         |   236,640 |   457,895 |   677,265 |   840,594 | 1,013,007 | 1,159,478 |  1,356,488 |  1,544,734 |  1,775,141 |
| [Chile](/chile)                           |    14,034 |    28,747 |    51,980 |    80,311 |   139,073 |   226,040 |    360,310 |    497,219 |    684,915 |
| [China](/china)                           |   385,600 |   386,994 |   387,552 |   387,732 |   387,818 |   387,845 |    387,859 |    387,864 |    387,866 |
| [Colombia](/colombia)                     |    19,758 |    38,791 |    66,541 |    98,272 |   160,413 |   249,084 |    387,142 |    533,052 |    744,504 |
| [Croatia](/croatia)                       |     7,269 |    10,857 |    14,241 |    16,694 |    19,460 |    21,625 |     23,822 |     25,515 |     27,419 |
| [Cyprus](/cyprus)                         |     1,399 |     1,863 |     2,292 |     2,586 |     2,852 |     2,985 |      3,038 |      3,044 |      3,046 |
| [Czechia](/czechia)                       |    28,442 |    36,105 |    42,385 |    46,584 |    50,559 |    52,754 |     53,908 |     54,213 |     54,337 |
| [Denmark](/denmark)                       |    52,970 |    66,604 |    77,214 |    83,936 |    90,601 |    94,996 |     98,505 |    100,552 |    102,312 |
| [Dominican Republic](/dominican-republic) |    24,269 |    34,954 |    44,133 |    50,492 |    57,709 |    63,723 |     70,557 |     76,567 |     84,172 |
| [Ecuador](/ecuador)                       |    63,176 |   174,885 |   322,859 |   429,105 |   540,634 |   623,572 |    710,203 |    779,144 |    854,041 |
| [Egypt](/egypt)                           |    28,220 |    46,945 |    70,524 |    94,554 |   137,230 |   194,070 |    281,131 |    374,022 |    511,556 |
| [Estonia](/estonia)                       |     5,840 |     7,832 |     9,636 |    10,871 |    12,003 |    12,586 |     12,840 |     12,875 |     12,883 |
| [Finland](/finland)                       |    20,532 |    33,229 |    43,560 |    50,315 |    57,645 |    63,531 |     69,917 |     75,209 |     81,475 |
| [France](/france)                         | 3,118,288 | 3,973,027 | 4,534,266 | 4,820,003 | 5,062,612 | 5,221,317 |  5,365,476 |  5,465,049 |  5,560,659 |
| [Germany](/germany)                       |   724,781 |   963,808 | 1,127,667 | 1,218,244 | 1,303,162 | 1,364,239 |  1,425,893 |  1,474,367 |  1,528,750 |
| [Greece](/greece)                         |    16,814 |    20,217 |    23,123 |    25,074 |    26,987 |    28,132 |     28,865 |     29,178 |     29,384 |
| [Hungary](/hungary)                       |    31,605 |    50,400 |    64,646 |    73,344 |    82,363 |    89,533 |     97,432 |    104,144 |    112,263 |
| [Iceland](/iceland)                       |     1,102 |     1,325 |     1,498 |     1,613 |     1,717 |     1,768 |      1,789 |      1,791 |      1,791 |
| [India](/india)                           |    81,279 |   186,579 |   383,750 |   606,914 | 1,071,328 | 1,822,954 |  3,062,085 |  4,398,892 |  6,390,358 |
| [Indonesia](/indonesia)                   |    62,025 |    91,489 |   121,003 |   144,121 |   169,159 |   187,634 |    210,078 |    233,798 |    268,168 |
| [Iran](/iran)                             |   540,914 |   640,236 |   726,471 |   794,659 |   881,017 |   955,920 |  1,046,102 |  1,130,455 |  1,241,384 |
| [Ireland](/ireland)                       |   121,476 |   192,204 |   228,845 |   244,756 |   257,143 |   264,616 |    270,877 |    274,961 |    278,851 |
| [Israel](/israel)                         |    18,612 |    24,358 |    28,166 |    30,462 |    32,657 |    34,005 |     34,937 |     35,366 |     35,665 |
| [Italy](/italy)                           | 3,338,469 | 3,940,407 | 4,370,272 | 4,605,912 | 4,818,368 | 4,963,308 |  5,097,744 |  5,191,816 |  5,283,126 |
| [Japan](/japan)                           |    59,032 |    82,362 |   107,370 |   128,843 |   155,065 |   178,853 |    210,894 |    243,773 |    290,621 |
| [Latvia](/latvia)                         |     1,298 |     2,238 |     3,156 |     3,804 |     4,427 |     4,776 |      4,968 |      5,015 |      5,034 |
| [Lithuania](/lithuania)                   |     4,934 |     6,587 |     8,057 |     9,063 |    10,034 |    10,590 |     10,906 |     11,007 |     11,058 |
| [Luxembourg](/luxembourg)                 |    10,906 |    13,098 |    14,753 |    15,815 |    16,814 |    17,371 |     17,674 |     17,773 |     17,823 |
| [Malaysia](/malaysia)                     |     8,383 |    10,336 |    12,028 |    13,181 |    14,236 |    14,770 |     14,991 |     15,026 |     15,035 |
| [Malta](/malta)                           |       219 |       418 |       611 |       746 |       871 |       937 |        970 |        974 |        975 |
| [Mexico](/mexico)                         |   103,921 |   312,387 |   662,416 | 1,083,212 | 1,825,790 | 2,884,794 |  5,115,985 |  7,631,073 | 10,546,507 |
| [Moldova](/moldova)                       |     8,738 |    15,859 |    26,028 |    36,861 |    55,910 |    80,003 |    113,577 |    145,306 |    185,930 |
| [Morocco](/morocco)                       |    16,634 |    19,479 |    21,311 |    22,380 |    23,265 |    23,756 |     24,060 |     24,184 |     24,261 |
| [Netherlands](/netherlands)               |   548,368 |   694,864 |   800,825 |   861,149 |   918,056 |   958,248 |    996,719 |  1,024,658 |  1,053,008 |
| [Nigeria](/nigeria)                       |     5,694 |    14,302 |    25,066 |    32,215 |    40,690 |    48,905 |     59,704 |     70,424 |     85,631 |
| [Norway](/norway)                         |    25,845 |    30,820 |    34,004 |    35,852 |    37,555 |    38,549 |     39,179 |     39,450 |     39,636 |
| [Pakistan](/pakistan)                     |    20,455 |    55,432 |   100,738 |   138,849 |   197,278 |   267,285 |    370,390 |    479,413 |    640,487 |
| [Panama](/panama)                         |    14,917 |    22,419 |    30,390 |    37,125 |    46,547 |    56,313 |     69,316 |     82,082 |     99,526 |
| [Peru](/peru)                             |    53,476 |   162,608 |   310,592 |   435,530 |   588,803 |   719,087 |    872,726 |  1,010,433 |  1,179,380 |
| [Philippines](/philippines)               |    52,785 |    72,799 |    95,034 |   114,285 |   137,365 |   156,340 |    182,359 |    213,196 |    260,604 |
| [Poland](/poland)                         |    63,772 |   100,209 |   137,598 |   167,477 |   207,230 |   246,808 |    297,255 |    344,511 |    406,107 |
| [Portugal](/portugal)                     |   105,668 |   141,159 |   170,584 |   189,956 |   210,018 |   224,243 |    237,007 |    245,516 |    253,721 |
| [Romania](/romania)                       |    72,894 |   116,183 |   164,598 |   204,601 |   256,266 |   303,509 |    359,038 |    407,281 |    465,583 |
| [Russia](/russia)                         |    46,898 |   137,707 |   306,281 |   453,182 |   676,488 |   953,192 |  1,358,098 |  1,768,295 |  2,335,434 |
| [Saudi Arabia](/saudi-arabia)             |    10,145 |    20,252 |    35,451 |    52,831 |    86,039 |   131,882 |    202,619 |    277,748 |    387,717 |
| [Serbia](/serbia)                         |    12,251 |    18,239 |    23,552 |    27,244 |    31,209 |    34,087 |     36,717 |     38,502 |     40,280 |
| [Slovakia](/slovakia)                     |     2,125 |     3,459 |     4,163 |     4,568 |     4,941 |     5,151 |      5,270 |      5,301 |      5,314 |
| [Slovenia](/slovenia)                     |    10,831 |    13,429 |    15,165 |    16,203 |    17,169 |    17,732 |     18,083 |     18,230 |     18,326 |
| [South Africa](/south-africa)             |     6,538 |    15,897 |    33,082 |    57,458 |   118,003 |   224,195 |    401,513 |    590,459 |    865,163 |
| [South Korea](/south-korea)               |    28,726 |    32,539 |    35,809 |    38,070 |    40,315 |    41,723 |     42,841 |     43,520 |     44,108 |
| [Spain](/spain)                           | 2,269,800 | 2,658,986 | 2,898,903 | 3,015,792 | 3,111,238 | 3,170,053 |  3,220,098 |  3,252,837 |  3,283,171 |
| [Sweden](/sweden)                         |   250,763 |   397,614 |   545,050 |   660,959 |   784,635 |   871,456 |    953,626 |  1,011,610 |  1,066,975 |
| [Switzerland](/switzerland)               |   206,655 |   245,769 |   269,643 |   281,799 |   292,270 |   298,819 |    304,218 |    307,653 |    310,847 |
| [Turkey](/turkey)                         |   234,707 |   353,151 |   428,170 |   468,474 |   500,779 |   520,830 |    539,085 |    551,912 |    565,412 |
| [Ukraine](/ukraine)                       |    18,041 |    34,922 |    63,151 |   100,587 |   187,351 |   330,264 |    561,253 |    801,786 |  1,140,212 |
| [United Kingdom](/united-kingdom)         | 1,911,196 | 2,723,263 | 3,341,204 | 3,704,713 | 4,059,943 | 4,324,190 |  4,585,598 |  4,776,631 |  4,967,886 |
