---
layout: default
title: COVID-19 Infections Tracker
permalink: /infections-tracker/
---

Our model tries to do what no other model currently does (to the best of our knowledge): provide an estimate for the R values and the true number of infected individuals in every region.

**Please Note: The infections estimate includes ALL infected people, not just those that took a coronavirus test kit and tested positive.** The vast majority of infested individuals did NOT get tested due to 1) lack of available testing, 2) they are only mildly symptomatic or 3) they do not know they are carrying the virus. For example, if the US reported 30,000 new cases, we estimate the true number of infected people to be likely 5-15x higher.

## R<sub>0</sub> value estimates

The below [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R) estimates are what our model has learned for each state/region. While we present a single value for the purpose of this chart, our model actually uses a weighted range of R values to make its projections. We provide a longer explanation of how our model works [here](/model-details).

|                                    |   Initial R<sub>0</sub> |   Current R |
|------------------------------------|-------------------------|-------------|
| [United States](/us)               |                     2.3 |         0.9 |
| [Alaska](/us-ak)                   |                     1.0 |         0.6 |
| [Alabama](/us-al)                  |                     2.0 |         0.9 |
| [Arkansas](/us-ar)                 |                     1.2 |         0.8 |
| [Arizona](/us-az)                  |                     1.6 |         0.9 |
| [California](/us-ca)               |                     1.5 |         0.9 |
| [Colorado](/us-co)                 |                     1.7 |         0.9 |
| [Connecticut](/us-ct)              |                     2.3 |         0.9 |
| [District of Columbia](/us-dc)     |                     1.6 |         0.9 |
| [Delaware](/us-de)                 |                     1.9 |         0.9 |
| [Florida](/us-fl)                  |                     1.5 |         0.9 |
| [Georgia](/us-ga)                  |                     1.8 |         0.9 |
| [Guam](/us-gu)                     |                     1.1 |         0.8 |
| [Hawaii](/us-hi)                   |                     1.8 |         0.7 |
| [Iowa](/us-ia)                     |                     1.3 |         0.9 |
| [Idaho](/us-id)                    |                     1.3 |         0.8 |
| [Illinois](/us-il)                 |                     2.2 |         0.9 |
| [Indiana](/us-in)                  |                     1.9 |         0.9 |
| [Kansas](/us-ks)                   |                     1.1 |         0.9 |
| [Kentucky](/us-ky)                 |                     1.7 |         0.9 |
| [Louisiana](/us-la)                |                     2.1 |         0.9 |
| [Massachusetts](/us-ma)            |                     1.9 |         0.9 |
| [Maryland](/us-md)                 |                     1.9 |         0.9 |
| [Maine](/us-me)                    |                     1.2 |         0.8 |
| [Michigan](/us-mi)                 |                     2.1 |         0.9 |
| [Minnesota](/us-mn)                |                     1.7 |         0.9 |
| [Missouri](/us-mo)                 |                     2.0 |         0.9 |
| [Northern Mariana Islands](/us-mp) |                     1.1 |         0.7 |
| [Mississippi](/us-ms)              |                     1.9 |         0.9 |
| [Montana](/us-mt)                  |                     0.7 |         0.8 |
| [North Carolina](/us-nc)           |                     1.9 |         0.9 |
| [North Dakota](/us-nd)             |                     0.7 |         0.7 |
| [Nebraska](/us-ne)                 |                     1.2 |         0.8 |
| [New Hampshire](/us-nh)            |                     1.9 |         0.9 |
| [New Jersey](/us-nj)               |                     2.7 |         0.9 |
| [New Mexico](/us-nm)               |                     1.7 |         0.9 |
| [Nevada](/us-nv)                   |                     1.5 |         0.9 |
| [New York](/us-ny)                 |                     3.6 |         0.9 |
| [Ohio](/us-oh)                     |                     1.7 |         0.9 |
| [Oklahoma](/us-ok)                 |                     1.6 |         0.9 |
| [Oregon](/us-or)                   |                     1.5 |         0.9 |
| [Pennsylvania](/us-pa)             |                     2.5 |         0.9 |
| [Puerto Rico](/us-pr)              |                     2.4 |         0.9 |
| [Rhode Island](/us-ri)             |                     1.7 |         0.9 |
| [South Carolina](/us-sc)           |                     1.6 |         0.9 |
| [South Dakota](/us-sd)             |                     0.9 |         0.8 |
| [Tennessee](/us-tn)                |                     2.1 |         0.8 |
| [Texas](/us-tx)                    |                     1.9 |         0.9 |
| [Utah](/us-ut)                     |                     1.2 |         0.9 |
| [Virginia](/us-va)                 |                     1.5 |         0.9 |
| [Virgin Islands](/us-vi)           |                     1.2 |         0.6 |
| [Vermont](/us-vt)                  |                     1.4 |         0.8 |
| [Washington](/us-wa)               |                     1.4 |         0.8 |
| [Wisconsin](/us-wi)                |                     2.3 |         0.8 |
| [West Virginia](/us-wv)            |                     1.5 |         0.9 |
| [Wyoming](/us-wy)                  |                     1.5 |         0.8 |

## Number of Total Infected Individuals by Date
This is an estimate of the total number of infected individuals by each date. This encompasses all individuals who have ever been infected, including asymtomatic and untested individuals.

|                                |     Apr 1 |    Apr 15 |   Apr 23 (today) |     May 1 |    May 15 |   Jun 1 |   Jun 15 |   Jul 1 |    Jul 15 |     Aug 1 |
|--------------------------------|----------:|----------:|-----------------:|----------:|----------:|--------:|---------:|--------:|----------:|----------:|
| [United States](/us)           | 4,411,263 | 6,595,192 |        7,564,519 | 8,383,971 | 9,554,634 | 10,660,646 | 11,526,016 | 12,587,060 | 13,626,858 | 15,100,173 |
| [Alabama](/us-al)              |    19,628 |    34,743 |           43,549 |    52,378 |    67,656 |     85,489 |    102,031 |    125,184 |    150,598 |    190,772 |
| [Alaska](/us-ak)               |     1,368 |     1,969 |            2,270 |     2,540 |     2,936 |      3,286 |      3,484 |      3,595 |      3,626 |      3,643 |
| [Arizona](/us-az)              |    24,544 |    41,357 |           51,181 |    61,036 |    78,091 |     98,004 |    116,531 |    142,662 |    171,731 |    218,599 |
| [Arkansas](/us-ar)             |     4,703 |     7,168 |            8,451 |     9,639 |    11,483 |     13,293 |     14,604 |     15,898 |     16,880 |     18,052 |
| [California](/us-ca)           |   162,045 |   262,484 |          309,372 |   350,449 |   412,157 |    475,141 |    529,810 |    606,082 |    691,893 |    832,694 |
| [Colorado](/us-co)             |    54,141 |    81,511 |           95,663 |   108,926 |   130,231 |    153,149 |    173,131 |    199,888 |    228,133 |    270,628 |
| [Connecticut](/us-ct)          |   145,843 |   236,512 |          275,658 |   307,994 |   352,182 |    390,382 |    417,054 |    445,545 |    468,989 |    495,710 |
| [Delaware](/us-de)             |     9,147 |    16,581 |           20,348 |    23,821 |    29,290 |     35,002 |     39,764 |     45,731 |     51,537 |     59,516 |
| [District of Columbia](/us-dc) |    13,996 |    23,785 |           28,532 |    32,770 |    39,160 |     45,433 |     50,333 |     56,061 |     61,186 |     67,532 |
| [Florida](/us-fl)              |   100,307 |   141,053 |          157,046 |   169,727 |   186,593 |    201,190 |    211,729 |    223,737 |    234,881 |    250,278 |
| [Georgia](/us-ga)              |    86,236 |   136,640 |          162,436 |   186,643 |   233,440 |    302,829 |    374,729 |    478,742 |    592,353 |    757,313 |
| [Guam](/us-gu)                 |     1,004 |     1,487 |            1,728 |     1,946 |     2,277 |      2,589 |      2,803 |      2,994 |      3,123 |      3,255 |
| [Hawaii](/us-hi)               |     1,203 |     2,092 |            2,557 |     2,984 |     3,628 |      4,228 |      4,614 |      4,908 |      5,049 |      5,157 |
| [Idaho](/us-id)                |     5,304 |     8,169 |            9,584 |    10,868 |    12,821 |     14,707 |     16,052 |     17,352 |     18,298 |     19,348 |
| [Illinois](/us-il)             |   167,518 |   271,548 |          322,829 |   369,409 |   441,694 |    516,746 |    580,922 |    666,365 |    755,690 |    887,305 |
| [Indiana](/us-in)              |    71,436 |   108,234 |          125,063 |   139,727 |   161,469 |    182,901 |    200,333 |    222,439 |    244,768 |    277,262 |
| [Iowa](/us-ia)                 |     9,839 |    17,817 |           22,700 |    27,700 |    36,490 |     46,820 |     56,333 |     69,406 |     83,503 |    105,568 |
| [Kansas](/us-ks)               |    13,630 |    21,043 |           24,814 |    28,320 |    33,924 |     39,939 |     45,152 |     52,081 |     59,480 |     71,074 |
| [Kentucky](/us-ky)             |    20,054 |    31,393 |           37,630 |    43,700 |    53,905 |     65,535 |     76,266 |     91,484 |    108,585 |    136,429 |
| [Louisiana](/us-la)            |   153,906 |   221,011 |          253,058 |   281,389 |   323,375 |    363,484 |    394,018 |    429,043 |    460,158 |    498,863 |
| [Maine](/us-me)                |     4,147 |     6,950 |            8,501 |     9,972 |    12,290 |     14,585 |     16,235 |     17,817 |     18,942 |     20,172 |
| [Maryland](/us-md)             |    67,037 |   123,034 |          150,056 |   174,059 |   210,345 |    246,876 |    277,231 |    316,501 |    356,308 |    412,966 |
| [Massachusetts](/us-ma)        |   214,214 |   393,662 |          478,489 |   551,794 |   656,966 |    753,089 |    823,833 |    903,552 |    972,319 |  1,053,471 |
| [Michigan](/us-mi)             |   281,723 |   412,823 |          471,159 |   520,343 |   589,160 |    650,466 |    694,149 |    740,962 |    779,936 |    826,192 |
| [Minnesota](/us-mn)            |    18,721 |    37,003 |           45,895 |    53,841 |    66,040 |     78,743 |     89,812 |    105,044 |    121,813 |    148,607 |
| [Mississippi](/us-ms)          |    20,232 |    32,536 |           38,891 |    44,849 |    54,452 |     64,879 |     74,091 |     86,629 |    100,121 |    121,014 |
| [Missouri](/us-mo)             |    25,430 |    39,265 |           45,970 |    52,038 |    61,460 |     71,299 |     79,746 |     91,030 |    103,132 |    122,226 |
| [Montana](/us-mt)              |     1,427 |     2,428 |            3,000 |     3,553 |     4,441 |      5,340 |      6,001 |      6,651 |      7,126 |      7,659 |
| [Nebraska](/us-ne)             |     4,112 |     7,031 |            8,624 |    10,123 |    12,468 |     14,770 |     16,419 |     17,986 |     19,054 |     20,119 |
| [Nevada](/us-nv)               |    18,682 |    25,734 |           29,021 |    31,912 |    36,187 |     40,230 |     43,147 |     46,130 |     48,524 |     51,440 |
| [New Hampshire](/us-nh)        |     5,285 |     8,738 |           10,519 |    12,191 |    14,890 |     17,822 |     20,396 |     23,854 |     27,550 |     33,335 |
| [New Jersey](/us-nj)           |   553,160 |   872,026 |        1,014,483 | 1,132,120 | 1,289,108 |  1,417,281 |  1,501,428 |  1,587,821 |  1,656,663 |  1,732,740 |
| [New Mexico](/us-nm)           |     7,746 |    14,750 |           17,991 |    20,798 |    24,932 |     28,947 |     32,107 |     35,891 |     39,470 |     44,439 |
| [New York](/us-ny)             | 1,774,501 | 2,322,385 |        2,515,200 | 2,652,787 | 2,807,643 |  2,910,630 |  2,966,608 |  3,014,437 |  3,046,481 |  3,077,333 |
| [North Carolina](/us-nc)       |    27,391 |    55,691 |           69,451 |    81,724 |   100,547 |    120,155 |    137,233 |    160,673 |    186,444 |    227,797 |
| [North Dakota](/us-nd)         |     1,405 |     2,311 |            2,804 |     3,266 |     3,984 |      4,675 |      5,144 |      5,543 |      5,780 |      5,997 |
| [Ohio](/us-oh)                 |    64,315 |   112,465 |          137,045 |   159,832 |   196,209 |    235,511 |    270,395 |    318,451 |    370,904 |    453,308 |
| [Oklahoma](/us-ok)             |    18,135 |    27,835 |           33,127 |    38,214 |    46,551 |     55,583 |     63,286 |     73,123 |     83,105 |     98,048 |
| [Oregon](/us-or)               |     7,910 |    11,600 |           13,399 |    15,039 |    17,608 |     20,321 |     22,666 |     25,819 |     29,261 |     34,887 |
| [Pennsylvania](/us-pa)         |   146,522 |   240,109 |          280,972 |   315,503 |   365,036 |    412,323 |    450,261 |    498,477 |    547,221 |    617,587 |
| [Puerto Rico](/us-pr)          |     6,869 |     9,727 |           11,001 |    12,092 |    13,662 |     15,114 |     16,152 |     17,222 |     18,102 |     19,243 |
| [Rhode Island](/us-ri)         |    19,475 |    37,238 |           45,831 |    53,476 |    64,972 |     76,193 |     84,788 |     94,408 |    102,526 |    112,019 |
| [South Carolina](/us-sc)       |    14,362 |    20,979 |           24,205 |    27,137 |    31,705 |     36,461 |     40,476 |     45,698 |     51,212 |     59,924 |
| [South Dakota](/us-sd)         |     3,669 |     5,160 |            5,944 |     6,681 |     7,849 |      9,043 |      9,969 |     11,005 |     11,929 |     13,172 |
| [Tennessee](/us-tn)            |    16,694 |    22,929 |           25,762 |    28,205 |    31,712 |     34,854 |     36,892 |     38,561 |     39,525 |     40,373 |
| [Texas](/us-tx)                |    59,097 |    88,726 |          102,406 |   114,452 |   132,632 |    151,087 |    166,624 |    187,183 |    209,323 |    244,971 |
| [Utah](/us-ut)                 |     3,224 |     5,467 |            6,679 |     7,841 |     9,763 |     11,894 |     13,779 |     16,313 |     19,063 |     23,552 |
| [Vermont](/us-vt)              |     3,648 |     5,211 |            5,999 |     6,719 |     7,823 |      8,898 |      9,681 |     10,471 |     11,091 |     11,836 |
| [Virgin Islands](/us-vi)       |       335 |       635 |              792 |       935 |     1,148 |      1,340 |      1,457 |      1,534 |      1,558 |      1,569 |
| [Virginia](/us-va)             |    38,130 |    69,432 |           84,069 |    96,880 |   116,088 |    135,560 |    152,207 |    174,865 |    199,613 |    238,767 |
| [Washington](/us-wa)           |    66,786 |    82,037 |           88,207 |    93,208 |    99,999 |    105,925 |    110,070 |    114,464 |    118,276 |    123,245 |
| [West Virginia](/us-wv)        |     3,002 |     6,620 |            8,522 |    10,297 |    13,158 |     16,287 |     19,068 |     22,868 |     27,011 |     33,676 |
| [Wisconsin](/us-wi)            |    26,072 |    36,359 |           40,897 |    44,764 |    50,325 |     55,527 |     59,420 |     63,808 |     67,809 |     73,357 |
| [Wyoming](/us-wy)              |       699 |     2,339 |            3,388 |     4,433 |     6,151 |      7,923 |      9,239 |     10,526 |     11,395 |     12,237 |
