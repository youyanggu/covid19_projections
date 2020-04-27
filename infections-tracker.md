---
layout: default
title: COVID-19 Infections Tracker
permalink: /infections-tracker/
---

Our model tries to do what no other model currently does (to the best of our knowledge): provide an estimate for the R values and the true number of infected individuals in every region.

## R<sub>0</sub> value estimates

The below [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R) estimates are what our model has learned for each state/region. While we present a single value for the purpose of this chart, our model actually uses a weighted range of R values to make its projections. The initial R<sub>0</sub> is the R value in early-to-mid March, right before states began implementing stay-at-home orders. We provide a longer explanation of how our model works [here](/model-details).

One interesting thing to note is that the 5 states with the lowest initial R0 estimates also happen to be the 5 least densely-populated states in the US: Montana, North Dakota, South Dakota, Alaska, and Wyoming. Our model has zero knowledge of population density, yet it was able to deduce that from the R0.

*Please note that this is merely an estimate. The true R values can vary widely, even day-to-day.*

{% include iframe_r_values.html %}

## Number of Total Infected Individuals by Date
This is an estimate of the total number of infected individuals by each date. The infections estimate includes **all** infected individuals, not just those that took a coronavirus test kit and tested positive. The vast majority of infected individuals did not get tested due to 1) they are asymptomatic or only mildly symptomatic or 2) lack of available testing. We estimate that the true number of infections is likely 5-15x higher than reported cases.


|                                |     Apr 1 |    Apr 15 |   Apr 26 (today) |     May 1 |    May 15 |   Jun 1 |   Jun 15 |   Jul 1 |    Jul 15 |     Aug 1 |
|--------------------------------|----------:|----------:|-----------------:|----------:|----------:|--------:|---------:|--------:|----------:|----------:|
| [United States](/us)           | 4,557,171 | 7,071,920 |        8,744,185 | 9,220,812 | 10,640,081 | 11,963,040 | 12,978,934 | 14,203,824 | 15,383,255 | 17,029,416 |
| [Alabama](/us-al)              |    18,545 |    30,401 |           39,520 |    42,354 |     51,464 |     60,824 |     68,283 |     76,963 |     84,848 |     95,480 |
| [Alaska](/us-ak)               |     1,420 |     2,069 |            2,544 |     2,686 |      3,115 |      3,496 |      3,715 |      3,842 |      3,880 |      3,898 |
| [Arizona](/us-az)              |    24,976 |    42,279 |           57,444 |    62,501 |     79,976 |    100,320 |    119,190 |    145,729 |    175,163 |    222,483 |
| [Arkansas](/us-ar)             |     4,820 |     7,539 |            9,684 |    10,354 |     12,497 |     14,644 |     16,247 |     17,905 |     19,225 |     20,838 |
| [California](/us-ca)           |   163,399 |   268,020 |          342,588 |   364,864 |    434,797 |    506,868 |    569,500 |    656,662 |    754,332 |    913,965 |
| [Colorado](/us-co)             |    65,955 |   104,803 |          136,516 |   146,721 |    180,839 |    218,710 |    252,602 |    298,950 |    348,302 |    422,014 |
| [Connecticut](/us-ct)          |   165,258 |   289,728 |          369,287 |   391,232 |    453,736 |    506,585 |    542,470 |    579,872 |    609,773 |    642,666 |
| [Delaware](/us-de)             |     9,701 |    18,381 |           25,185 |    27,321 |     34,297 |     41,745 |     48,097 |     56,248 |     64,323 |     75,496 |
| [District of Columbia](/us-dc) |    15,609 |    27,478 |           36,107 |    38,691 |     46,710 |     54,543 |     60,622 |     67,687 |     73,945 |     81,567 |
| [Florida](/us-fl)              |   105,197 |   159,850 |          196,807 |   207,621 |    240,991 |    274,494 |    302,773 |    340,834 |    382,196 |    447,945 |
| [Georgia](/us-ga)              |    80,151 |   120,887 |          148,679 |   157,005 |    187,575 |    228,917 |    268,482 |    322,318 |    378,937 |    460,325 |
| [Guam](/us-gu)                 |     1,028 |     1,547 |            1,931 |     2,047 |      2,410 |      2,755 |      2,994 |      3,214 |      3,364 |      3,519 |
| [Hawaii](/us-hi)               |     1,242 |     2,207 |            2,964 |     3,196 |      3,919 |      4,599 |      5,046 |      5,403 |      5,587 |      5,730 |
| [Idaho](/us-id)                |     5,188 |     8,042 |           10,123 |    10,751 |     12,706 |     14,582 |     15,908 |     17,166 |     18,053 |     19,001 |
| [Illinois](/us-il)             |   171,866 |   284,743 |          368,322 |   393,891 |    475,669 |    561,235 |    634,809 |    733,193 |    836,273 |    988,090 |
| [Indiana](/us-in)              |    72,740 |   115,064 |          145,172 |   154,211 |    182,651 |    211,713 |    236,127 |    268,033 |    301,014 |    349,697 |
| [Iowa](/us-ia)                 |    10,482 |    19,562 |           28,306 |    31,343 |     42,191 |     55,336 |     67,833 |     85,575 |    105,210 |    136,421 |
| [Kansas](/us-ks)               |    12,590 |    19,320 |           24,538 |    26,180 |     31,571 |     37,407 |     42,466 |     49,145 |     56,222 |     67,271 |
| [Kentucky](/us-ky)             |    19,580 |    30,374 |           39,078 |    41,874 |     51,247 |     61,758 |     71,299 |     84,610 |     99,360 |    123,131 |
| [Louisiana](/us-la)            |   157,016 |   234,457 |          292,168 |   309,747 |    365,084 |    420,231 |    463,964 |    516,280 |    564,373 |    625,419 |
| [Maine](/us-me)                |     4,367 |     7,621 |           10,401 |    11,295 |     14,213 |     17,199 |     19,459 |     21,807 |     23,624 |     25,704 |
| [Maryland](/us-md)             |    80,099 |   151,279 |          202,111 |   217,208 |    264,097 |    310,919 |    349,376 |    398,464 |    447,309 |    515,031 |
| [Massachusetts](/us-ma)        |   228,256 |   479,330 |          648,415 |   695,370 |    829,221 |    941,940 |  1,017,834 |  1,095,976 |  1,157,361 |  1,223,476 |
| [Michigan](/us-mi)             |   294,318 |   451,097 |          560,543 |   592,822 |    691,726 |    786,818 |    860,133 |    945,807 |  1,023,121 |  1,120,272 |
| [Minnesota](/us-mn)            |    22,223 |    45,164 |           62,065 |    67,157 |     83,291 |    100,133 |    114,810 |    134,984 |    157,077 |    191,964 |
| [Mississippi](/us-ms)          |    20,097 |    32,204 |           41,340 |    44,173 |     53,362 |     63,172 |     71,690 |     83,080 |     95,143 |    113,617 |
| [Missouri](/us-mo)             |    25,801 |    40,890 |           51,941 |    55,320 |     66,159 |     77,593 |     87,486 |    100,795 |    115,119 |    137,726 |
| [Montana](/us-mt)              |     1,440 |     2,480 |            3,381 |     3,671 |      4,622 |      5,592 |      6,314 |      7,036 |      7,573 |      8,178 |
| [Nebraska](/us-ne)             |     4,929 |     8,557 |           11,487 |    12,405 |     15,332 |     18,224 |     20,327 |     22,386 |     23,838 |     25,318 |
| [Nevada](/us-nv)               |    19,682 |    29,202 |           36,495 |    38,759 |     46,034 |     53,511 |     59,519 |     66,652 |     73,292 |     82,321 |
| [New Hampshire](/us-nh)        |     5,298 |     8,887 |           11,679 |    12,559 |     15,459 |     18,627 |     21,422 |     25,193 |     29,236 |     35,569 |
| [New Jersey](/us-nj)           |   553,697 |   853,113 |        1,042,290 | 1,093,906 |  1,238,420 |  1,356,423 |  1,434,182 |  1,514,464 |  1,578,932 |  1,650,889 |
| [New Mexico](/us-nm)           |     8,278 |    16,154 |           21,746 |    23,404 |     28,559 |     33,697 |     37,839 |     42,918 |     47,815 |     54,685 |
| [New York](/us-ny)             | 1,636,038 | 2,276,925 |        2,650,138 | 2,747,058 |  3,005,050 |  3,198,100 |  3,314,322 |  3,424,046 |  3,504,988 |  3,589,409 |
| [North Carolina](/us-nc)       |    26,203 |    50,037 |           66,711 |    71,650 |     87,070 |    102,797 |    116,108 |    133,778 |    152,633 |    182,298 |
| [North Dakota](/us-nd)         |     1,427 |     2,383 |            3,162 |     3,407 |      4,184 |      4,936 |      5,455 |      5,906 |      6,181 |      6,434 |
| [Ohio](/us-oh)                 |    63,352 |   108,920 |          142,523 |   152,807 |    185,858 |    220,900 |    251,406 |    292,633 |    336,923 |    405,817 |
| [Oklahoma](/us-ok)             |    18,164 |    28,010 |           35,961 |    38,496 |     46,859 |     55,843 |     63,439 |     73,044 |     82,679 |     96,954 |
| [Oregon](/us-or)               |     8,038 |    12,068 |           15,045 |    15,962 |     18,929 |     22,102 |     24,883 |     28,674 |     32,852 |     39,709 |
| [Pennsylvania](/us-pa)         |   162,689 |   275,582 |          347,465 |   367,712 |    427,803 |    484,296 |    528,902 |    584,816 |    640,498 |    719,459 |
| [Puerto Rico](/us-pr)          |     7,728 |    12,094 |           15,403 |    16,433 |     19,787 |     23,390 |     26,532 |     30,760 |     35,342 |     42,741 |
| [Rhode Island](/us-ri)         |    18,869 |    35,576 |           47,532 |    51,098 |     62,155 |     72,954 |     81,217 |     90,446 |     98,221 |    107,345 |
| [South Carolina](/us-sc)       |    15,360 |    23,576 |           29,857 |    31,822 |     38,264 |     45,270 |     51,478 |     59,994 |     69,373 |     84,599 |
| [South Dakota](/us-sd)         |     3,716 |     5,299 |            6,557 |     6,954 |      8,239 |      9,564 |     10,606 |     11,789 |     12,857 |     14,297 |
| [Tennessee](/us-tn)            |    16,494 |    23,546 |           28,401 |    29,821 |     34,120 |     38,087 |     40,816 |     43,352 |     45,110 |     46,968 |
| [Texas](/us-tx)                |    59,393 |    90,263 |          111,308 |   117,504 |    136,698 |    155,942 |    171,882 |    192,585 |    214,417 |    248,855 |
| [Utah](/us-ut)                 |     3,448 |     5,953 |            8,008 |     8,671 |     10,902 |     13,402 |     15,642 |     18,697 |     22,046 |     27,535 |
| [Vermont](/us-vt)              |     3,723 |     5,487 |            6,839 |     7,257 |      8,589 |      9,922 |     10,935 |     12,027 |     12,942 |     14,088 |
| [Virgin Islands](/us-vi)       |       334 |       649 |              897 |       973 |      1,206 |      1,419 |      1,552 |      1,643 |      1,676 |      1,693 |
| [Virginia](/us-va)             |    38,983 |    71,146 |           93,647 |   100,298 |    121,020 |    142,145 |    160,232 |    184,836 |    211,673 |    254,085 |
| [Washington](/us-wa)           |    67,927 |    86,326 |           97,842 |   101,070 |    110,558 |    119,184 |    125,509 |    132,617 |    139,072 |    147,746 |
| [West Virginia](/us-wv)        |     2,946 |     6,221 |            8,909 |     9,768 |     12,626 |     15,774 |     18,531 |     22,175 |     26,002 |     31,965 |
| [Wisconsin](/us-wi)            |    25,336 |    35,349 |           41,648 |    43,413 |     48,593 |     53,255 |     56,563 |     60,015 |     62,875 |     66,482 |
| [Wyoming](/us-wy)              |       636 |     1,820 |            2,864 |     3,192 |      4,222 |      5,192 |      5,813 |      6,273 |      6,456 |      6,558 |
