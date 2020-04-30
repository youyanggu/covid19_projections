---
layout: default
title: COVID-19 Infections Tracker
permalink: /infections-tracker/
---

Our model tries to do what no other model currently does (to the best of our knowledge): provide an estimate for the R values and the true number of infected individuals in every region.

## R<sub>0</sub> value estimates

The below [basic reproduction number](https://en.wikipedia.org/wiki/Basic_reproduction_number) (R) estimates are what our model has learned for each state/region. While we present a single value for the purpose of this chart, our model actually uses a weighted range of R values to make its projections. The initial R<sub>0</sub> is the R value in early-to-mid March, right before states began implementing stay-at-home orders. We provide a longer explanation of how our model works [here](/model-details).

Please note that this is merely an estimate based on the data. The true R values can vary widely, even day-to-day. For example, California has a lower-than-expected R<sub>0</sub> partly because there is a significant time lag in their deaths reporting. While this does not significantly affect our projections (assuming the lag is consistent), it will result in a lower R estimate than the true value.

{% include iframe_r_values.html %}

## Number of Total Infected Individuals by Date
This is an estimate of the total number of infected individuals by each date. The infections estimate includes **all** infected individuals, not just those that took a coronavirus test kit and tested positive. The vast majority of infected individuals did not get tested due to 1) they are asymptomatic or only mildly symptomatic or 2) lack of available testing. We estimate that the true number of infections is likely 5-15x higher than reported cases.


|                                |     Apr 1 |    Apr 15 |    Apr 28 |     May 1 |     May 15 |      Jun 1 |     Jun 15 |      Jul 1 |     Jul 15 |      Aug 1 |
|--------------------------------|-----------|-----------|-----------|-----------|------------|------------|------------|------------|------------|------------|
| [United States](/us)           | 4,545,903 | 7,028,513 | 8,790,410 | 9,137,262 | 10,526,746 | 11,824,194 | 12,823,264 | 14,030,879 | 15,196,979 | 16,828,370 |
| [Alabama](/us-al)              |    18,558 |    30,419 |    40,256 |    42,371 |     51,475 |     60,822 |     68,269 |     76,927 |     84,786 |     95,374 |
| [Alaska](/us-ak)               |     1,420 |     2,069 |     2,581 |     2,686 |      3,115 |      3,496 |      3,715 |      3,842 |      3,879 |      3,897 |
| [Arizona](/us-az)              |    24,788 |    41,718 |    57,659 |    61,322 |     78,145 |     97,609 |    115,547 |    140,612 |    168,261 |    212,549 |
| [Arkansas](/us-ar)             |     4,819 |     7,518 |     9,806 |    10,299 |     12,410 |     14,517 |     16,083 |     17,691 |     18,959 |     20,499 |
| [California](/us-ca)           |   163,017 |   266,538 |   345,632 |   361,961 |    430,638 |    501,209 |    562,367 |    647,276 |    742,245 |    897,273 |
| [Colorado](/us-co)             |    62,838 |    99,574 |   131,905 |   139,102 |    171,266 |    207,016 |    239,090 |    283,109 |    330,207 |    401,015 |
| [Connecticut](/us-ct)          |   165,080 |   289,119 |   373,938 |   390,114 |    452,251 |    504,772 |    540,437 |    577,621 |    607,361 |    640,100 |
| [Delaware](/us-de)             |     9,680 |    18,315 |    25,614 |    27,199 |     34,126 |     41,519 |     47,820 |     55,900 |     63,900 |     74,970 |
| [District of Columbia](/us-dc) |    15,355 |    27,042 |    36,198 |    38,098 |     46,023 |     53,792 |     59,848 |     66,924 |     73,228 |     80,945 |
| [Florida](/us-fl)              |   104,590 |   157,719 |   195,710 |   203,341 |    234,734 |    265,847 |    291,790 |    326,324 |    363,520 |    422,263 |
| [Georgia](/us-ga)              |    83,114 |   127,801 |   162,683 |   170,229 |    208,407 |    262,971 |    317,753 |    395,200 |    478,845 |    600,742 |
| [Guam](/us-gu)                 |     1,028 |     1,547 |     1,960 |     2,047 |      2,408 |      2,753 |      2,991 |      3,210 |      3,359 |      3,514 |
| [Hawaii](/us-hi)               |     1,242 |     2,210 |     3,030 |     3,205 |      3,933 |      4,619 |      5,071 |      5,434 |      5,622 |      5,769 |
| [Idaho](/us-id)                |     5,161 |     7,981 |    10,187 |    10,647 |     12,566 |     14,401 |     15,691 |     16,904 |     17,748 |     18,640 |
| [Illinois](/us-il)             |   171,612 |   282,166 |   369,004 |   387,252 |    464,957 |    545,435 |    614,020 |    705,038 |    799,845 |    938,974 |
| [Indiana](/us-in)              |    72,695 |   114,760 |   146,851 |   153,508 |    181,559 |    210,134 |    234,067 |    265,254 |    297,415 |    344,816 |
| [Iowa](/us-ia)                 |    10,505 |    19,629 |    29,194 |    31,493 |     42,435 |     55,709 |     68,333 |     86,254 |    106,085 |    137,595 |
| [Kansas](/us-ks)               |    12,593 |    19,360 |    25,044 |    26,285 |     31,745 |     37,674 |     42,831 |     49,663 |     56,923 |     68,283 |
| [Kentucky](/us-ky)             |    19,511 |    30,116 |    39,274 |    41,301 |     50,345 |     60,416 |     69,494 |     82,075 |     95,936 |    118,180 |
| [Louisiana](/us-la)            |   156,058 |   230,051 |   287,578 |   299,517 |    349,272 |    397,884 |    435,725 |    480,177 |    520,435 |    571,052 |
| [Maine](/us-me)                |     4,336 |     7,538 |    10,484 |    11,138 |     13,988 |     16,896 |     19,087 |     21,350 |     23,091 |     25,079 |
| [Maryland](/us-md)             |    79,957 |   150,243 |   204,035 |   215,082 |    261,108 |    307,019 |    344,703 |    392,779 |    440,616 |    506,991 |
| [Massachusetts](/us-ma)        |   227,459 |   472,469 |   647,898 |   681,525 |    810,722 |    919,522 |    992,861 |  1,068,486 |  1,128,027 |  1,192,370 |
| [Michigan](/us-mi)             |   294,073 |   448,992 |   564,143 |   587,529 |    683,367 |    774,862 |    844,922 |    926,229 |    999,174 |  1,090,501 |
| [Minnesota](/us-mn)            |    21,976 |    44,638 |    62,627 |    66,384 |     82,363 |     99,071 |    113,656 |    133,739 |    155,770 |    190,636 |
| [Mississippi](/us-ms)          |    19,987 |    31,836 |    41,366 |    43,401 |     52,191 |     61,498 |     69,514 |     80,148 |     91,341 |    108,412 |
| [Missouri](/us-mo)             |    27,835 |    46,849 |    63,118 |    66,703 |     82,664 |    100,499 |    116,821 |    140,002 |    166,086 |    208,495 |
| [Montana](/us-mt)              |     1,440 |     2,479 |     3,451 |     3,668 |      4,617 |      5,584 |      6,303 |      7,021 |      7,554 |      8,152 |
| [Nebraska](/us-ne)             |     4,860 |     8,424 |    11,528 |    12,201 |     15,072 |     17,905 |     19,964 |     21,974 |     23,388 |     24,824 |
| [Nevada](/us-nv)               |    19,560 |    28,817 |    36,379 |    37,996 |     44,923 |     51,992 |     57,622 |     64,226 |     70,302 |     78,491 |
| [New Hampshire](/us-nh)        |     5,289 |     8,831 |    11,780 |    12,420 |     15,235 |     18,289 |     20,966 |     24,558 |     28,388 |     34,364 |
| [New Jersey](/us-nj)           |   549,845 |   840,531 | 1,034,915 | 1,071,394 |  1,208,753 |  1,320,316 |  1,393,603 |  1,469,161 |  1,529,841 |  1,597,682 |
| [New Mexico](/us-nm)           |     8,140 |    15,635 |    21,312 |    22,474 |     27,315 |     32,120 |     35,969 |     40,649 |     45,124 |     51,369 |
| [New York](/us-ny)             | 1,632,310 | 2,267,070 | 2,659,942 | 2,730,304 |  2,983,540 |  3,172,535 |  3,286,076 |  3,393,074 |  3,471,883 |  3,553,996 |
| [North Carolina](/us-nc)       |    26,180 |    49,954 |    67,835 |    71,503 |     86,874 |    102,549 |    115,823 |    133,459 |    152,295 |    181,958 |
| [North Dakota](/us-nd)         |     1,443 |     2,412 |     3,264 |     3,448 |      4,234 |      4,995 |      5,520 |      5,979 |      6,259 |      6,516 |
| [Ohio](/us-oh)                 |    63,089 |   108,110 |   143,791 |   151,345 |    183,851 |    218,263 |    248,187 |    288,580 |    331,935 |    399,356 |
| [Oklahoma](/us-ok)             |    18,081 |    27,543 |    35,609 |    37,367 |     45,018 |     53,036 |     59,596 |     67,544 |     75,156 |     85,972 |
| [Oregon](/us-or)               |     8,028 |    12,040 |    15,228 |    15,907 |     18,848 |     21,987 |     24,733 |     28,470 |     32,581 |     39,321 |
| [Pennsylvania](/us-pa)         |   162,577 |   275,329 |   352,215 |   367,197 |    427,037 |    483,235 |    527,567 |    583,077 |    638,300 |    716,547 |
| [Puerto Rico](/us-pr)          |     7,697 |    11,968 |    15,421 |    16,161 |     19,370 |     22,786 |     25,735 |     29,663 |     33,879 |     40,644 |
| [Rhode Island](/us-ri)         |    18,763 |    35,018 |    47,320 |    49,839 |     60,246 |     70,291 |     77,882 |     86,238 |     93,180 |    101,256 |
| [South Carolina](/us-sc)       |    15,338 |    23,493 |    30,196 |    31,646 |     37,995 |     44,878 |     50,955 |     59,260 |     68,375 |     83,136 |
| [South Dakota](/us-sd)         |     3,715 |     5,299 |     6,656 |     6,952 |      8,237 |      9,562 |     10,604 |     11,787 |     12,854 |     14,294 |
| [Tennessee](/us-tn)            |    16,464 |    23,490 |    28,682 |    29,733 |     34,004 |     37,940 |     40,643 |     43,146 |     44,871 |     46,679 |
| [Texas](/us-tx)                |    59,267 |    89,833 |   112,106 |   116,632 |    135,401 |    154,111 |    169,511 |    189,378 |    210,193 |    242,855 |
| [Utah](/us-ut)                 |     3,406 |     5,873 |     8,059 |     8,547 |     10,741 |     13,198 |     15,398 |     18,393 |     21,670 |     27,036 |
| [Vermont](/us-vt)              |     3,718 |     5,471 |     6,915 |     7,224 |      8,540 |      9,854 |     10,848 |     11,912 |     12,797 |     13,896 |
| [Virgin Islands](/us-vi)       |       334 |       650 |       917 |       974 |      1,207 |      1,422 |      1,555 |      1,646 |      1,680 |      1,697 |
| [Virginia](/us-va)             |    39,007 |    70,278 |    93,590 |    98,341 |    118,146 |    138,221 |    155,313 |    178,446 |    203,580 |    243,215 |
| [Washington](/us-wa)           |    67,985 |    86,379 |    98,712 |   101,104 |    110,571 |    119,167 |    125,463 |    132,526 |    138,932 |    147,528 |
| [West Virginia](/us-wv)        |     2,926 |     6,131 |     8,951 |     9,573 |     12,330 |     15,345 |     17,963 |     21,387 |     24,948 |     30,457 |
| [Wisconsin](/us-wi)            |    25,406 |    35,476 |    42,290 |    43,615 |     48,857 |     53,584 |     56,946 |     60,465 |     63,391 |     67,090 |
| [Wyoming](/us-wy)              |       629 |     1,802 |     2,913 |     3,154 |      4,167 |      5,119 |      5,729 |      6,176 |      6,352 |      6,447 |
