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

Last Updated: May 25, 2020

### US

|                                |     Apr 1 |    Apr 15 |      May 1 |     May 15 |      Jun 1 |     Jun 15 |      Jul 1 |     Jul 15 |      Aug 1 |
|--------------------------------|-----------|-----------|------------|------------|------------|------------|------------|------------|------------|
| [United States](/us)           | 4,708,331 | 7,536,941 | 10,068,364 | 11,900,688 | 14,020,483 | 15,967,162 | 18,507,846 | 20,848,700 | 23,496,609 |
| [Alabama](/us-al)              |    19,061 |    35,739 |     56,518 |     76,168 |    106,463 |    138,960 |    182,714 |    222,761 |    267,851 |
| [Alaska](/us-ak)               |       686 |       878 |      1,049 |      1,170 |      1,276 |      1,326 |      1,345 |      1,346 |      1,347 |
| [Arizona](/us-az)              |    27,309 |    51,397 |     86,435 |    124,173 |    190,268 |    269,365 |    382,046 |    488,093 |    607,832 |
| [Arkansas](/us-ar)             |     4,933 |     8,234 |     11,921 |     14,934 |     18,652 |     21,643 |     24,579 |     26,541 |     28,256 |
| [California](/us-ca)           |   168,826 |   288,411 |    421,264 |    534,288 |    670,746 |    804,260 |  1,013,220 |  1,252,121 |  1,584,678 |
| [Colorado](/us-co)             |    63,104 |   102,387 |    147,143 |    185,881 |    240,670 |    297,995 |    374,819 |    443,818 |    518,494 |
| [Connecticut](/us-ct)          |   167,910 |   296,309 |    394,792 |    450,626 |    494,532 |    521,533 |    547,585 |    566,472 |    583,754 |
| [Delaware](/us-de)             |     9,937 |    21,010 |     34,122 |     45,392 |     58,568 |     70,495 |     86,979 |    103,199 |    122,028 |
| [District of Columbia](/us-dc) |    15,481 |    31,331 |     46,562 |     57,126 |     67,117 |     73,861 |     81,387 |     87,963 |     95,243 |
| [Florida](/us-fl)              |   106,228 |   173,782 |    246,898 |    307,928 |    391,164 |    481,371 |    613,251 |    744,838 |    906,483 |
| [Georgia](/us-ga)              |    88,819 |   140,433 |    194,343 |    246,114 |    321,119 |    391,283 |    472,534 |    537,340 |    603,291 |
| [Guam](/us-gu)                 |       565 |       777 |        975 |      1,109 |      1,226 |      1,287 |      1,316 |      1,320 |      1,322 |
| [Hawaii](/us-hi)               |       966 |     1,504 |      1,971 |      2,288 |      2,566 |      2,719 |      2,798 |      2,812 |      2,815 |
| [Idaho](/us-id)                |     5,239 |     7,074 |      8,410 |      9,278 |     10,084 |     10,520 |     10,731 |     10,769 |     10,779 |
| [Illinois](/us-il)             |   179,978 |   332,883 |    522,176 |    695,808 |    913,847 |  1,127,576 |  1,447,225 |  1,773,882 |  2,150,905 |
| [Indiana](/us-in)              |    79,341 |   141,762 |    212,585 |    275,792 |    371,401 |    473,294 |    604,834 |    716,306 |    828,053 |
| [Iowa](/us-ia)                 |    14,257 |    28,069 |     47,917 |     71,735 |    114,364 |    160,899 |    220,144 |    270,148 |    321,326 |
| [Kansas](/us-ks)               |    12,190 |    18,078 |     22,773 |     26,078 |     29,760 |     32,462 |     34,916 |     36,493 |     37,864 |
| [Kentucky](/us-ky)             |    20,215 |    31,416 |     43,104 |     52,244 |     62,829 |     72,464 |     84,674 |     95,808 |    108,759 |
| [Louisiana](/us-la)            |   162,564 |   232,516 |    288,809 |    324,130 |    360,262 |    387,386 |    414,131 |    432,397 |    448,058 |
| [Maine](/us-me)                |     3,852 |     5,989 |      7,743 |      8,892 |      9,926 |     10,574 |     11,082 |     11,332 |     11,493 |
| [Maryland](/us-md)             |    79,711 |   163,221 |    244,990 |    305,112 |    378,846 |    447,340 |    531,007 |    600,076 |    668,699 |
| [Massachusetts](/us-ma)        |   237,683 |   482,483 |    676,745 |    787,773 |    887,655 |    958,651 |  1,028,118 |  1,075,088 |  1,113,993 |
| [Michigan](/us-mi)             |   299,942 |   445,711 |    549,423 |    607,600 |    654,238 |    683,110 |    709,687 |    727,769 |    743,807 |
| [Minnesota](/us-mn)            |    20,934 |    53,285 |     92,546 |    126,596 |    174,758 |    228,492 |    307,177 |    383,397 |    471,783 |
| [Mississippi](/us-ms)          |    21,887 |    40,388 |     66,036 |     94,287 |    144,917 |    203,357 |    280,153 |    345,696 |    411,336 |
| [Missouri](/us-mo)             |    27,532 |    48,422 |     73,727 |     99,546 |    141,652 |    186,768 |    245,397 |    297,179 |    353,552 |
| [Montana](/us-mt)              |       969 |     1,413 |      1,687 |      1,864 |      2,029 |      2,117 |      2,161 |      2,169 |      2,171 |
| [Nebraska](/us-ne)             |     4,511 |     9,158 |     15,637 |     22,700 |     34,356 |     46,715 |     62,548 |     76,344 |     91,329 |
| [Nevada](/us-nv)               |    20,721 |    31,254 |     41,772 |     50,090 |     60,608 |     69,603 |     79,310 |     86,605 |     93,654 |
| [New Hampshire](/us-nh)        |     6,415 |    13,138 |     22,477 |     31,997 |     47,380 |     66,280 |     95,302 |    123,783 |    156,653 |
| [New Jersey](/us-nj)           |   584,696 |   940,345 |  1,227,424 |  1,397,315 |  1,533,016 |  1,613,357 |  1,692,555 |  1,752,984 |  1,810,832 |
| [New Mexico](/us-nm)           |     8,791 |    19,429 |     33,642 |     47,374 |     65,565 |     84,449 |    114,643 |    148,465 |    192,754 |
| [New York](/us-ny)             | 1,681,883 | 2,309,076 |  2,699,108 |  2,884,777 |  3,010,113 |  3,077,314 |  3,135,163 |  3,173,264 |  3,205,558 |
| [North Carolina](/us-nc)       |    26,350 |    52,919 |     81,470 |    104,350 |    132,096 |    159,250 |    196,739 |    233,517 |    278,948 |
| [North Dakota](/us-nd)         |     1,702 |     3,359 |      5,675 |      8,235 |     12,327 |     16,442 |     21,448 |     25,615 |     30,025 |
| [Ohio](/us-oh)                 |    65,439 |   128,350 |    206,580 |    279,867 |    393,527 |    524,296 |    712,317 |    890,139 |  1,090,896 |
| [Oklahoma](/us-ok)             |    18,781 |    26,751 |     33,610 |     38,805 |     44,505 |     48,370 |     51,416 |     53,010 |     54,146 |
| [Oregon](/us-or)               |     8,450 |    12,226 |     15,440 |     17,578 |     19,555 |     20,941 |     22,380 |     23,510 |     24,681 |
| [Pennsylvania](/us-pa)         |   162,828 |   351,753 |    535,997 |    666,818 |    797,009 |    900,511 |  1,031,383 |  1,154,622 |  1,296,877 |
| [Puerto Rico](/us-pr)          |     7,420 |    10,676 |     13,243 |     14,862 |     16,289 |     17,210 |     18,023 |     18,532 |     18,954 |
| [Rhode Island](/us-ri)         |    17,347 |    37,533 |     61,531 |     81,879 |    106,028 |    128,408 |    156,505 |    179,675 |    201,777 |
| [South Carolina](/us-sc)       |    18,178 |    31,059 |     46,008 |     59,719 |     81,100 |    104,942 |    138,355 |    170,289 |    207,925 |
| [South Dakota](/us-sd)         |     2,264 |     3,711 |      5,973 |      8,726 |     13,607 |     18,947 |     25,891 |     32,048 |     38,844 |
| [Tennessee](/us-tn)            |    16,917 |    25,808 |     34,963 |     42,918 |     52,869 |     60,644 |     67,914 |     72,572 |     76,590 |
| [Texas](/us-tx)                |    62,648 |   107,595 |    162,987 |    222,272 |    320,590 |    425,897 |    563,977 |    688,763 |    830,939 |
| [Utah](/us-ut)                 |     3,310 |     6,211 |     10,111 |     14,502 |     21,987 |     30,100 |     40,796 |     50,536 |     61,781 |
| [Vermont](/us-vt)              |     3,616 |     4,670 |      5,498 |      6,040 |      6,509 |      6,761 |      6,888 |      6,915 |      6,923 |
| [Virgin Islands](/us-vi)       |       297 |       493 |        671 |        793 |        900 |        956 |        983 |        985 |        985 |
| [Virginia](/us-va)             |    41,305 |    82,830 |    127,083 |    161,827 |    200,640 |    235,817 |    286,972 |    341,997 |    414,346 |
| [Washington](/us-wa)           |    74,637 |    96,956 |    115,854 |    128,273 |    139,686 |    147,871 |    157,030 |    165,007 |    174,111 |
| [West Virginia](/us-wv)        |     2,900 |     5,568 |      7,658 |      9,089 |     10,594 |     11,587 |     12,343 |     12,711 |     12,953 |
| [Wisconsin](/us-wi)            |    26,280 |    40,101 |     53,594 |     63,712 |     75,822 |     86,081 |     97,314 |    105,880 |    114,256 |
| [Wyoming](/us-wy)              |       167 |       520 |        970 |      1,395 |      1,922 |      2,303 |      2,614 |      2,770 |      2,871 |

### Global

|                                           |     Apr 1 |    Apr 15 |     May 1 |    May 15 |     Jun 1 |    Jun 15 |      Jul 1 |     Jul 15 |      Aug 1 |
|-------------------------------------------|-----------|-----------|-----------|-----------|-----------|-----------|------------|------------|------------|
| [Algeria](/algeria)                       |    43,570 |    54,493 |    61,411 |    65,171 |    68,654 |    70,996 |     73,010 |     74,222 |     75,186 |
| [Argentina](/argentina)                   |    17,069 |    28,468 |    44,506 |    61,457 |    86,439 |   113,514 |    156,672 |    208,352 |    291,040 |
| [Austria](/austria)                       |    71,986 |    86,750 |    96,304 |   101,780 |   107,198 |   110,861 |    113,733 |    115,257 |    116,361 |
| [Bangladesh](/bangladesh)                 |    11,637 |    24,484 |    46,501 |    75,012 |   138,502 |   241,825 |    426,875 |    635,823 |    926,245 |
| [Belgium](/belgium)                       |   922,186 | 1,224,496 | 1,384,860 | 1,452,304 | 1,505,062 | 1,538,990 |  1,568,776 |  1,587,029 |  1,601,145 |
| [Brazil](/brazil)                         |   301,493 |   872,574 | 2,113,988 | 3,546,840 | 5,732,367 | 7,982,381 | 11,099,568 | 14,232,449 | 18,247,738 |
| [Bulgaria](/bulgaria)                     |     7,520 |    12,356 |    18,910 |    25,475 |    37,239 |    53,652 |     80,683 |    109,514 |    147,312 |
| [Canada](/canada)                         |   249,420 |   501,126 |   726,111 |   868,423 |   996,042 | 1,089,183 |  1,200,374 |  1,302,123 |  1,419,206 |
| [Chile](/chile)                           |    15,291 |    34,205 |    67,910 |   112,521 |   202,730 |   327,602 |    536,091 |    773,061 |  1,115,215 |
| [China](/china)                           |   370,927 |   374,011 |   375,506 |   376,077 |   376,383 |   376,486 |    376,535 |    376,552 |    376,561 |
| [Colombia](/colombia)                     |    18,383 |    37,713 |    67,320 |   101,507 |   161,984 |   237,351 |    359,879 |    502,791 |    723,756 |
| [Croatia](/croatia)                       |     7,608 |    11,211 |    14,425 |    16,680 |    19,372 |    21,744 |     24,475 |     26,723 |     29,171 |
| [Cyprus](/cyprus)                         |     1,398 |     1,834 |     2,238 |     2,514 |     2,767 |     2,892 |      2,939 |      2,942 |      2,943 |
| [Czechia](/czechia)                       |    29,635 |    37,864 |    44,630 |    49,173 |    53,707 |    56,400 |     57,948 |     58,410 |     58,606 |
| [Denmark](/denmark)                       |    55,395 |    69,896 |    81,120 |    88,227 |    95,835 |   101,559 |    106,832 |    110,210 |    113,085 |
| [Dominican Republic](/dominican-republic) |    23,832 |    34,364 |    43,416 |    49,541 |    56,290 |    61,731 |     67,663 |     72,512 |     77,999 |
| [Ecuador](/ecuador)                       |    58,127 |   163,463 |   296,833 |   386,384 |   471,536 |   538,788 |    625,774 |    710,379 |    815,593 |
| [Egypt](/egypt)                           |    27,536 |    46,739 |    72,373 |    98,491 |   136,317 |   180,751 |    263,622 |    370,890 |    535,900 |
| [Estonia](/estonia)                       |     5,985 |     7,962 |     9,757 |    10,987 |    12,136 |    12,731 |     12,980 |     13,010 |     13,015 |
| [Finland](/finland)                       |    21,857 |    35,418 |    44,816 |    50,225 |    55,973 |    60,824 |     66,400 |     71,020 |     76,034 |
| [France](/france)                         | 3,527,487 | 4,343,530 | 4,791,516 | 4,990,520 | 5,158,340 | 5,279,150 |  5,400,983 |  5,487,476 |  5,564,023 |
| [Germany](/germany)                       |   769,361 | 1,035,860 | 1,215,204 | 1,312,853 | 1,411,853 | 1,494,955 |  1,592,640 |  1,675,335 |  1,764,935 |
| [Greece](/greece)                         |    17,857 |    21,650 |    24,875 |    27,051 |    29,351 |    30,919 |     32,110 |     32,714 |     33,139 |
| [Hungary](/hungary)                       |    33,711 |    54,268 |    69,963 |    79,583 |    90,544 |   100,868 |    114,325 |    126,817 |    141,611 |
| [Iceland](/iceland)                       |     1,164 |     1,350 |     1,495 |     1,593 |     1,679 |     1,720 |      1,734 |      1,735 |      1,735 |
| [India](/india)                           |    81,198 |   186,644 |   386,438 |   609,188 | 1,034,660 | 1,658,392 |  2,758,996 |  4,094,490 |  6,257,692 |
| [Indonesia](/indonesia)                   |    57,278 |    90,226 |   129,371 |   164,428 |   207,523 |   243,720 |    294,274 |    355,807 |    459,637 |
| [Iran](/iran)                             |   535,600 |   630,049 |   728,544 |   839,463 | 1,018,218 | 1,192,203 |  1,400,872 |  1,574,299 |  1,762,157 |
| [Ireland](/ireland)                       |   129,730 |   209,881 |   250,212 |   267,140 |   281,086 |   290,623 |    299,647 |    305,826 |    311,355 |
| [Israel](/israel)                         |    19,465 |    25,674 |    29,688 |    32,035 |    34,242 |    35,581 |     36,462 |     36,804 |     36,984 |
| [Italy](/italy)                           | 3,671,893 | 4,363,611 | 4,860,927 | 5,136,206 | 5,412,835 | 5,640,371 |  5,888,405 |  6,072,946 |  6,241,710 |
| [Japan](/japan)                           |    84,602 |   117,998 |   142,314 |   156,340 |   167,961 |   175,087 |    181,633 |    186,214 |    190,279 |
| [Latvia](/latvia)                         |     1,456 |     2,374 |     3,242 |     3,843 |     4,403 |     4,695 |      4,823 |      4,835 |      4,836 |
| [Lithuania](/lithuania)                   |     5,167 |     7,095 |     8,866 |    10,099 |    11,380 |    12,196 |     12,737 |     12,947 |     13,064 |
| [Luxembourg](/luxembourg)                 |    11,499 |    13,915 |    15,695 |    16,832 |    17,964 |    18,651 |     19,070 |     19,221 |     19,299 |
| [Malaysia](/malaysia)                     |     8,385 |    10,258 |    11,878 |    12,972 |    13,952 |    14,432 |     14,610 |     14,629 |     14,633 |
| [Malta](/malta)                           |       213 |       397 |       574 |       697 |       813 |       874 |        903 |        906 |        906 |
| [Mexico](/mexico)                         |   100,734 |   308,323 |   704,898 | 1,238,777 | 2,256,321 | 3,663,776 |  6,373,793 |  9,675,195 | 13,923,276 |
| [Moldova](/moldova)                       |     9,285 |    16,659 |    26,981 |    37,684 |    55,798 |    78,251 |    112,769 |    147,949 |    191,569 |
| [Morocco](/morocco)                       |    16,811 |    19,731 |    21,574 |    22,629 |    23,493 |    23,968 |     24,254 |     24,363 |     24,421 |
| [Netherlands](/netherlands)               |   590,181 |   749,719 |   863,847 |   928,252 |   994,508 | 1,049,640 |  1,111,468 |  1,159,746 |  1,206,582 |
| [Nigeria](/nigeria)                       |     5,286 |    12,942 |    23,407 |    32,159 |    45,003 |    60,091 |     83,766 |    110,776 |    152,877 |
| [Norway](/norway)                         |    26,518 |    31,846 |    35,193 |    37,140 |    39,036 |    40,225 |     41,022 |     41,366 |     41,576 |
| [Pakistan](/pakistan)                     |    18,866 |    52,801 |   103,927 |   155,402 |   245,307 |   365,526 |    563,070 |    778,046 |  1,068,434 |
| [Panama](/panama)                         |    15,121 |    22,558 |    30,142 |    36,121 |    43,826 |    51,213 |     60,922 |     70,498 |     83,382 |
| [Peru](/peru)                             |    51,489 |   158,403 |   326,455 |   505,061 |   769,947 | 1,034,680 |  1,395,686 |  1,791,836 |  2,396,239 |
| [Philippines](/philippines)               |    47,710 |    67,611 |    86,323 |    99,925 |   113,568 |   122,849 |    133,144 |    143,113 |    157,213 |
| [Poland](/poland)                         |    69,445 |   107,884 |   145,550 |   174,693 |   216,271 |   264,462 |    336,637 |    409,969 |    502,640 |
| [Portugal](/portugal)                     |   112,516 |   152,548 |   186,392 |   209,025 |   234,859 |   256,421 |    279,429 |    296,596 |    313,155 |
| [Romania](/romania)                       |    75,350 |   119,014 |   164,777 |   200,625 |   247,896 |   294,233 |    353,261 |    405,548 |    464,015 |
| [Russia](/russia)                         |    46,726 |   139,660 |   316,491 |   486,611 |   760,926 | 1,106,530 |  1,646,971 |  2,202,408 |  2,896,767 |
| [Saudi Arabia](/saudi-arabia)             |     9,826 |    20,030 |    35,627 |    53,268 |    86,343 |   131,892 |    207,152 |    288,616 |    397,133 |
| [Serbia](/serbia)                         |    13,071 |    19,073 |    24,141 |    27,561 |    31,136 |    33,636 |     35,718 |     36,862 |     37,688 |
| [Slovakia](/slovakia)                     |     2,192 |     3,551 |     4,245 |     4,642 |     5,024 |     5,248 |      5,377 |      5,410 |      5,421 |
| [Slovenia](/slovenia)                     |    11,534 |    14,273 |    16,064 |    17,128 |    18,180 |    18,855 |     19,327 |     19,543 |     19,683 |
| [South Africa](/south-africa)             |     6,960 |    18,128 |    41,153 |    75,539 |   147,755 |   258,052 |    499,795 |    859,697 |  1,529,065 |
| [South Korea](/south-korea)               |    31,613 |    36,000 |    39,696 |    42,220 |    44,725 |    46,297 |     47,461 |     48,052 |     48,441 |
| [Spain](/spain)                           | 2,412,627 | 2,847,395 | 3,119,485 | 3,254,078 | 3,376,572 | 3,467,565 |  3,560,201 |  3,626,848 |  3,687,296 |
| [Sweden](/sweden)                         |   279,297 |   439,747 |   579,864 |   671,804 |   754,014 |   802,874 |    842,592 |    866,863 |    887,273 |
| [Switzerland](/switzerland)               |   221,440 |   264,306 |   289,949 |   302,803 |   314,694 |   323,261 |    331,449 |    337,089 |    342,180 |
| [Turkey](/turkey)                         |   243,428 |   358,632 |   432,743 |   471,873 |   502,410 |   520,807 |    536,859 |    547,245 |    556,287 |
| [Ukraine](/ukraine)                       |    23,630 |    42,765 |    67,963 |    93,473 |   137,041 |   192,871 |    282,177 |    377,609 |    503,626 |
| [United Kingdom](/united-kingdom)         | 2,058,038 | 2,981,152 | 3,704,189 | 4,137,862 | 4,566,956 | 4,891,095 |  5,222,697 |  5,456,983 |  5,659,840 |
