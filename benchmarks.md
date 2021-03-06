# Speed Evaluation
## Key Encapsulation Schemes
| scheme | implementation | key generation [cycles] | encapsulation [cycles] | decapsulation [cycles] |
| ------ | -------------- | ----------------------- | ---------------------- | ---------------------- |
| bikel1 (100 executions) | m4f | AVG: 25,059,586 <br /> MIN: 25,044,097 <br /> MAX: 25,080,997 | AVG: 3,398,384 <br /> MIN: 3,371,979 <br /> MAX: 3,417,178 | AVG: 54,793,168 <br /> MIN: 54,774,340 <br /> MAX: 54,823,993 |
| bikel1 (100 executions) | ref | AVG: 65,551,874 <br /> MIN: 65,532,779 <br /> MAX: 65,569,765 | AVG: 4,962,214 <br /> MIN: 4,941,128 <br /> MAX: 4,978,626 | AVG: 116,543,558 <br /> MIN: 116,510,779 <br /> MAX: 116,572,274 |
| firesaber (100 executions) | clean | AVG: 3,723,480 <br /> MIN: 3,723,480 <br /> MAX: 3,723,480 | AVG: 4,622,127 <br /> MIN: 4,622,127 <br /> MAX: 4,622,127 | AVG: 5,233,205 <br /> MIN: 5,233,205 <br /> MAX: 5,233,205 |
| firesaber (100 executions) | m4f | AVG: 1,006,981 <br /> MIN: 1,006,981 <br /> MAX: 1,006,981 | AVG: 1,220,602 <br /> MIN: 1,220,602 <br /> MAX: 1,220,602 | AVG: 1,171,348 <br /> MIN: 1,171,348 <br /> MAX: 1,171,348 |
| frodokem640aes (100 executions) | m4 | AVG: 48,348,105 <br /> MIN: 48,348,105 <br /> MAX: 48,348,105 | AVG: 47,130,922 <br /> MIN: 47,130,922 <br /> MAX: 47,130,922 | AVG: 46,594,383 <br /> MIN: 46,594,383 <br /> MAX: 46,594,383 |
| frodokem640shake (100 executions) | m4 | AVG: 79,325,705 <br /> MIN: 79,325,705 <br /> MAX: 79,325,705 | AVG: 79,699,757 <br /> MIN: 79,699,757 <br /> MAX: 79,699,757 | AVG: 79,145,449 <br /> MIN: 79,145,449 <br /> MAX: 79,145,449 |
| frodokem640shake (100 executions) | opt | AVG: 91,896,318 <br /> MIN: 91,896,318 <br /> MAX: 91,896,318 | AVG: 104,912,447 <br /> MIN: 104,912,447 <br /> MAX: 104,912,447 | AVG: 104,638,561 <br /> MIN: 104,638,561 <br /> MAX: 104,638,561 |
| hqc-rmrs-128 (100 executions) | clean | AVG: 2,958,761 <br /> MIN: 2,926,873 <br /> MAX: 3,154,607 | AVG: 5,389,782 <br /> MIN: 5,323,042 <br /> MAX: 5,587,198 | AVG: 7,814,315 <br /> MIN: 7,715,362 <br /> MAX: 8,070,658 |
| kyber1024 (100 executions) | clean | AVG: 1,657,144 <br /> MIN: 1,654,880 <br /> MAX: 1,681,921 | AVG: 2,033,986 <br /> MIN: 2,031,721 <br /> MAX: 2,058,777 | AVG: 2,170,110 <br /> MIN: 2,167,845 <br /> MAX: 2,194,901 |
| kyber1024 (100 executions) | m4 | AVG: 1,216,669 <br /> MIN: 1,212,098 <br /> MAX: 1,252,093 | AVG: 1,406,588 <br /> MIN: 1,402,081 <br /> MAX: 1,441,945 | AVG: 1,326,182 <br /> MIN: 1,321,675 <br /> MAX: 1,361,539 |
| kyber1024-90s (100 executions) | clean | AVG: 3,001,553 <br /> MIN: 3,000,212 <br /> MAX: 3,016,252 | AVG: 3,277,401 <br /> MIN: 3,276,089 <br /> MAX: 3,292,099 | AVG: 3,510,669 <br /> MIN: 3,509,357 <br /> MAX: 3,525,367 |
| kyber1024-90s (100 executions) | m4 | AVG: 1,040,158 <br /> MIN: 1,032,023 <br /> MAX: 1,045,096 | AVG: 1,137,576 <br /> MIN: 1,129,396 <br /> MAX: 1,142,542 | AVG: 1,154,265 <br /> MIN: 1,146,085 <br /> MAX: 1,159,231 |
| kyber512 (100 executions) | clean | AVG: 639,281 <br /> MIN: 638,221 <br /> MAX: 651,734 | AVG: 853,692 <br /> MIN: 852,632 <br /> MAX: 866,145 | AVG: 945,783 <br /> MIN: 944,723 <br /> MAX: 958,236 |
| kyber512 (100 executions) | m4 | AVG: 463,343 <br /> MIN: 462,340 <br /> MAX: 475,943 | AVG: 566,744 <br /> MIN: 565,741 <br /> MAX: 579,344 | AVG: 525,141 <br /> MIN: 524,138 <br /> MAX: 537,741 |
| kyber512-90s (100 executions) | clean | AVG: 945,590 <br /> MIN: 944,948 <br /> MAX: 945,965 | AVG: 1,115,224 <br /> MIN: 1,114,582 <br /> MAX: 1,115,599 | AVG: 1,260,218 <br /> MIN: 1,259,576 <br /> MAX: 1,260,593 |
| kyber512-90s (100 executions) | m4 | AVG: 390,549 <br /> MIN: 382,560 <br /> MAX: 395,061 | AVG: 449,172 <br /> MIN: 441,183 <br /> MAX: 453,684 | AVG: 460,470 <br /> MIN: 452,481 <br /> MAX: 464,982 |
| kyber768 (100 executions) | clean | AVG: 1,060,755 <br /> MIN: 1,059,689 <br /> MAX: 1,073,727 | AVG: 1,363,334 <br /> MIN: 1,362,268 <br /> MAX: 1,376,306 | AVG: 1,475,756 <br /> MIN: 1,474,690 <br /> MAX: 1,488,728 |
| kyber768 (100 executions) | m4 | AVG: 763,979 <br /> MIN: 761,596 <br /> MAX: 788,310 | AVG: 923,856 <br /> MIN: 921,477 <br /> MAX: 948,186 | AVG: 862,176 <br /> MIN: 859,797 <br /> MAX: 886,506 |
| kyber768-90s (100 executions) | clean | AVG: 1,813,167 <br /> MIN: 1,812,309 <br /> MAX: 1,828,332 | AVG: 2,036,400 <br /> MIN: 2,035,542 <br /> MAX: 2,051,565 | AVG: 2,223,819 <br /> MIN: 2,222,961 <br /> MAX: 2,238,984 |
| kyber768-90s (100 executions) | m4 | AVG: 660,765 <br /> MIN: 656,834 <br /> MAX: 665,216 | AVG: 741,256 <br /> MIN: 737,325 <br /> MAX: 745,707 | AVG: 754,570 <br /> MIN: 750,639 <br /> MAX: 759,021 |
| lightsaber (100 executions) | clean | AVG: 1,026,004 <br /> MIN: 1,026,004 <br /> MAX: 1,026,004 | AVG: 1,498,300 <br /> MIN: 1,498,300 <br /> MAX: 1,498,300 | AVG: 1,806,894 <br /> MIN: 1,806,894 <br /> MAX: 1,806,894 |
| lightsaber (100 executions) | m4f | AVG: 359,451 <br /> MIN: 359,451 <br /> MAX: 359,451 | AVG: 490,901 <br /> MIN: 490,901 <br /> MAX: 490,901 | AVG: 464,470 <br /> MIN: 464,470 <br /> MAX: 464,470 |
| ntruhps2048509 (100 executions) | clean | AVG: 68,795,185 <br /> MIN: 68,795,185 <br /> MAX: 68,795,185 | AVG: 1,062,964 <br /> MIN: 1,062,964 <br /> MAX: 1,062,964 | AVG: 2,435,439 <br /> MIN: 2,435,439 <br /> MAX: 2,435,439 |
| ntruhps2048509 (100 executions) | m4f | AVG: 79,658,656 <br /> MIN: 79,658,656 <br /> MAX: 79,658,656 | AVG: 564,411 <br /> MIN: 564,411 <br /> MAX: 564,411 | AVG: 537,473 <br /> MIN: 537,473 <br /> MAX: 537,473 |
| ntruhps2048677 (100 executions) | clean | AVG: 123,029,086 <br /> MIN: 123,029,086 <br /> MAX: 123,029,086 | AVG: 1,796,535 <br /> MIN: 1,796,535 <br /> MAX: 1,796,535 | AVG: 4,287,726 <br /> MIN: 4,287,726 <br /> MAX: 4,287,726 |
| ntruhps2048677 (100 executions) | m4f | AVG: 143,734,184 <br /> MIN: 143,734,184 <br /> MAX: 143,734,184 | AVG: 821,524 <br /> MIN: 821,524 <br /> MAX: 821,524 | AVG: 815,516 <br /> MIN: 815,516 <br /> MAX: 815,516 |
| ntruhps4096821 (100 executions) | clean | AVG: 181,325,162 <br /> MIN: 181,325,162 <br /> MAX: 181,325,162 | AVG: 2,347,265 <br /> MIN: 2,347,265 <br /> MAX: 2,347,265 | AVG: 5,668,286 <br /> MIN: 5,668,286 <br /> MAX: 5,668,286 |
| ntruhps4096821 (100 executions) | m4f | AVG: 208,835,863 <br /> MIN: 208,835,863 <br /> MAX: 208,835,863 | AVG: 1,028,465 <br /> MIN: 1,028,465 <br /> MAX: 1,028,465 | AVG: 1,032,726 <br /> MIN: 1,032,726 <br /> MAX: 1,032,726 |
| ntruhrss701 (100 executions) | clean | AVG: 132,506,447 <br /> MIN: 132,506,447 <br /> MAX: 132,506,447 | AVG: 1,510,371 <br /> MIN: 1,510,371 <br /> MAX: 1,510,371 | AVG: 4,347,522 <br /> MIN: 4,347,522 <br /> MAX: 4,347,522 |
| ntruhrss701 (100 executions) | m4f | AVG: 153,104,418 <br /> MIN: 153,104,418 <br /> MAX: 153,104,418 | AVG: 377,377 <br /> MIN: 377,377 <br /> MAX: 377,377 | AVG: 869,701 <br /> MIN: 869,701 <br /> MAX: 869,701 |
| ntrulpr653 (100 executions) | clean | AVG: 4,097,458 <br /> MIN: 4,097,458 <br /> MAX: 4,097,458 | AVG: 7,821,693 <br /> MIN: 7,821,693 <br /> MAX: 7,821,693 | AVG: 11,273,153 <br /> MIN: 11,273,153 <br /> MAX: 11,273,153 |
| ntrulpr761 (100 executions) | clean | AVG: 5,637,576 <br /> MIN: 5,637,576 <br /> MAX: 5,637,576 | AVG: 10,817,101 <br /> MIN: 10,817,101 <br /> MAX: 10,817,101 | AVG: 15,498,068 <br /> MIN: 15,498,068 <br /> MAX: 15,498,068 |
| ntrulpr761 (100 executions) | m4f | AVG: 736,506 <br /> MIN: 736,506 <br /> MAX: 736,506 | AVG: 1,292,350 <br /> MIN: 1,292,350 <br /> MAX: 1,292,350 | AVG: 1,385,470 <br /> MIN: 1,385,470 <br /> MAX: 1,385,470 |
| ntrulpr857 (100 executions) | clean | AVG: 6,794,314 <br /> MIN: 6,794,314 <br /> MAX: 6,794,314 | AVG: 13,061,118 <br /> MIN: 13,061,118 <br /> MAX: 13,061,118 | AVG: 18,992,752 <br /> MIN: 18,992,752 <br /> MAX: 18,992,752 |
| saber (100 executions) | clean | AVG: 2,132,294 <br /> MIN: 2,132,294 <br /> MAX: 2,132,294 | AVG: 2,814,441 <br /> MIN: 2,814,441 <br /> MAX: 2,814,441 | AVG: 3,279,418 <br /> MIN: 3,279,418 <br /> MAX: 3,279,418 |
| saber (100 executions) | m4f | AVG: 656,540 <br /> MIN: 656,540 <br /> MAX: 656,540 | AVG: 835,504 <br /> MIN: 835,504 <br /> MAX: 835,504 | AVG: 791,138 <br /> MIN: 791,138 <br /> MAX: 791,138 |
| sikep434 (100 executions) | m4 | AVG: 48,264,129 <br /> MIN: 48,264,129 <br /> MAX: 48,264,129 | AVG: 78,911,465 <br /> MIN: 78,911,465 <br /> MAX: 78,911,465 | AVG: 84,276,911 <br /> MIN: 84,276,911 <br /> MAX: 84,276,911 |
| sikep434 (100 executions) | opt | AVG: 643,140,813 <br /> MIN: 643,140,813 <br /> MAX: 643,140,813 | AVG: 1,053,374,539 <br /> MIN: 1,053,374,539 <br /> MAX: 1,053,374,539 | AVG: 1,123,506,035 <br /> MIN: 1,123,506,035 <br /> MAX: 1,123,506,035 |
| sikep503 (100 executions) | m4 | AVG: 67,365,363 <br /> MIN: 67,365,363 <br /> MAX: 67,365,363 | AVG: 110,846,067 <br /> MIN: 110,846,067 <br /> MAX: 110,846,067 | AVG: 117,993,160 <br /> MIN: 117,993,160 <br /> MAX: 117,993,160 |
| sikep503 (100 executions) | opt | AVG: 972,733,846 <br /> MIN: 972,733,846 <br /> MAX: 972,733,846 | AVG: 1,602,886,599 <br /> MIN: 1,602,886,599 <br /> MAX: 1,602,886,599 | AVG: 1,704,605,781 <br /> MIN: 1,704,605,781 <br /> MAX: 1,704,605,781 |
| sikep610 (100 executions) | m4 | AVG: 119,480,622 <br /> MIN: 119,480,622 <br /> MAX: 119,480,622 | AVG: 219,632,058 <br /> MIN: 219,632,058 <br /> MAX: 219,632,058 | AVG: 221,029,700 <br /> MIN: 221,029,700 <br /> MAX: 221,029,700 |
| sikep610 (100 executions) | opt | AVG: 1,815,959,387 <br /> MIN: 1,815,959,387 <br /> MAX: 1,815,959,387 | AVG: 3,341,196,195 <br /> MIN: 3,341,196,195 <br /> MAX: 3,341,196,195 | AVG: 3,360,955,305 <br /> MIN: 3,360,955,305 <br /> MAX: 3,360,955,305 |
| sikep751 (100 executions) | m4 | AVG: 204,646,661 <br /> MIN: 204,646,661 <br /> MAX: 204,646,661 | AVG: 331,934,480 <br /> MIN: 331,934,480 <br /> MAX: 331,934,480 | AVG: 356,425,812 <br /> MIN: 356,425,812 <br /> MAX: 356,425,812 |
| sikep751 (100 executions) | opt | AVG: 3,288,678,781 <br /> MIN: 3,288,678,781 <br /> MAX: 3,288,678,781 | AVG: 5,333,567,877 <br /> MIN: 5,333,567,877 <br /> MAX: 5,333,567,877 | AVG: 5,728,790,883 <br /> MIN: 5,728,790,883 <br /> MAX: 5,728,790,883 |
| sntrup653 (100 executions) | clean | AVG: 107,454,880 <br /> MIN: 105,111,497 <br /> MAX: 144,167,887 | AVG: 4,058,297 <br /> MIN: 4,058,297 <br /> MAX: 4,058,297 | AVG: 11,719,072 <br /> MIN: 11,719,072 <br /> MAX: 11,719,073 |
| sntrup761 (100 executions) | clean | AVG: 140,173,345 <br /> MIN: 140,173,345 <br /> MAX: 140,173,345 | AVG: 5,393,604 <br /> MIN: 5,393,604 <br /> MAX: 5,393,604 | AVG: 15,823,587 <br /> MIN: 15,823,587 <br /> MAX: 15,823,587 |
| sntrup761 (100 executions) | m4f | AVG: 10,831,102 <br /> MIN: 10,831,102 <br /> MAX: 10,831,102 | AVG: 698,959 <br /> MIN: 698,959 <br /> MAX: 698,959 | AVG: 565,281 <br /> MIN: 565,281 <br /> MAX: 565,281 |
| sntrup857 (100 executions) | clean | AVG: 177,668,015 <br /> MIN: 177,668,015 <br /> MAX: 177,668,015 | AVG: 6,739,738 <br /> MIN: 6,739,738 <br /> MAX: 6,739,738 | AVG: 19,262,010 <br /> MIN: 19,262,010 <br /> MAX: 19,262,010 |
## Signature Schemes
| scheme | implementation | key generation [cycles] | sign [cycles] | verify [cycles] |
| ------ | -------------- | ----------------------- | ------------- | --------------- |
| dilithium2 (100 executions) | clean | AVG: 1,948,921 <br /> MIN: 1,948,646 <br /> MAX: 1,949,314 | AVG: 7,209,994 <br /> MIN: 3,263,628 <br /> MAX: 28,544,712 | AVG: 2,129,398 <br /> MIN: 2,128,896 <br /> MAX: 2,129,741 |
| dilithium2 (100 executions) | m4 | AVG: 1,574,432 <br /> MIN: 1,574,139 <br /> MAX: 1,574,935 | AVG: 3,969,997 <br /> MIN: 2,052,227 <br /> MAX: 10,488,178 | AVG: 1,598,582 <br /> MIN: 1,598,246 <br /> MAX: 1,598,971 |
| dilithium3 (100 executions) | clean | AVG: 3,464,369 <br /> MIN: 3,462,937 <br /> MAX: 3,465,485 | AVG: 11,868,693 <br /> MIN: 5,077,074 <br /> MAX: 32,249,347 | AVG: 3,534,606 <br /> MIN: 3,534,142 <br /> MAX: 3,534,933 |
| dilithium3 (100 executions) | m4 | AVG: 2,884,458 <br /> MIN: 2,883,255 <br /> MAX: 2,886,283 | AVG: 7,146,517 <br /> MIN: 3,324,437 <br /> MAX: 20,508,397 | AVG: 2,735,132 <br /> MIN: 2,734,843 <br /> MAX: 2,735,417 |
| falcon-1024 (100 executions) | clean | AVG: 622,175,711 <br /> MIN: 337,571,831 <br /> MAX: 1,880,024,329 | AVG: 133,629,247 <br /> MIN: 133,291,572 <br /> MAX: 133,967,706 | AVG: 1,528,951 <br /> MIN: 1,528,400 <br /> MAX: 1,529,571 |
| falcon-1024 (100 executions) | m4-ct | AVG: 459,534,839 <br /> MIN: 273,177,640 <br /> MAX: 1,047,054,767 | AVG: 85,072,673 <br /> MIN: 84,815,948 <br /> MAX: 85,305,908 | AVG: 980,052 <br /> MIN: 969,152 <br /> MAX: 985,686 |
| falcon-1024 (100 executions) | opt-ct | AVG: 495,167,251 <br /> MIN: 273,177,640 <br /> MAX: 1,379,271,017 | AVG: 85,054,991 <br /> MIN: 84,783,337 <br /> MAX: 85,362,818 | AVG: 977,782 <br /> MIN: 967,975 <br /> MAX: 987,002 |
| falcon-1024 (100 executions) | opt-leaktime | AVG: 405,281,116 <br /> MIN: 244,875,160 <br /> MAX: 891,184,049 | AVG: 76,013,689 <br /> MIN: 75,446,015 <br /> MAX: 76,508,847 | AVG: 979,746 <br /> MIN: 967,632 <br /> MAX: 986,832 |
| falcon-512 (100 executions) | clean | AVG: 208,399,225 <br /> MIN: 130,550,614 <br /> MAX: 472,461,727 | AVG: 61,097,585 <br /> MIN: 60,852,840 <br /> MAX: 61,406,301 | AVG: 766,917 <br /> MIN: 766,489 <br /> MAX: 767,319 |
| falcon-512 (100 executions) | m4-ct | AVG: 171,386,113 <br /> MIN: 102,414,161 <br /> MAX: 578,366,405 | AVG: 38,980,990 <br /> MIN: 38,781,213 <br /> MAX: 39,236,694 | AVG: 474,764 <br /> MIN: 465,756 <br /> MAX: 481,271 |
| falcon-512 (100 executions) | opt-ct | AVG: 177,602,037 <br /> MIN: 102,400,864 <br /> MAX: 714,825,912 | AVG: 38,965,055 <br /> MIN: 38,810,150 <br /> MAX: 39,279,838 | AVG: 473,672 <br /> MIN: 465,686 <br /> MAX: 482,281 |
| falcon-512 (100 executions) | opt-leaktime | AVG: 152,926,229 <br /> MIN: 90,346,571 <br /> MAX: 337,384,529 | AVG: 35,378,639 <br /> MIN: 35,029,929 <br /> MAX: 35,717,852 | AVG: 475,420 <br /> MIN: 465,612 <br /> MAX: 482,310 |
| falcon-512-tree (100 executions) | m4-ct | AVG: 171,727,053 <br /> MIN: 117,531,546 <br /> MAX: 490,748,018 | AVG: 17,669,755 <br /> MIN: 17,432,665 <br /> MAX: 17,857,219 | AVG: 473,783 <br /> MIN: 465,581 <br /> MAX: 481,627 |
| falcon-512-tree (100 executions) | opt-ct | AVG: 182,000,803 <br /> MIN: 117,531,546 <br /> MAX: 537,014,335 | AVG: 17,671,861 <br /> MIN: 17,503,582 <br /> MAX: 17,907,492 | AVG: 474,096 <br /> MIN: 465,021 <br /> MAX: 482,523 |
| falcon-512-tree (100 executions) | opt-leaktime | AVG: 168,338,680 <br /> MIN: 101,826,596 <br /> MAX: 516,678,670 | AVG: 19,213,176 <br /> MIN: 18,918,057 <br /> MAX: 19,567,974 | AVG: 474,214 <br /> MIN: 465,252 <br /> MAX: 481,696 |
| sphincs-haraka-128f-robust (1 executions) | clean | AVG: 104,795,655 <br /> MIN: 104,795,655 <br /> MAX: 104,795,655 | AVG: 3,888,035,253 <br /> MIN: 3,888,035,253 <br /> MAX: 3,888,035,253 | AVG: 167,675,614 <br /> MIN: 167,675,614 <br /> MAX: 167,675,614 |
| sphincs-haraka-128f-simple (1 executions) | clean | AVG: 72,831,240 <br /> MIN: 72,831,240 <br /> MAX: 72,831,240 | AVG: 2,625,107,372 <br /> MIN: 2,625,107,372 <br /> MAX: 2,625,107,372 | AVG: 111,321,990 <br /> MIN: 111,321,990 <br /> MAX: 111,321,990 |
| sphincs-haraka-128s-robust (1 executions) | clean | AVG: 3,336,358,708 <br /> MIN: 3,336,358,708 <br /> MAX: 3,336,358,708 | AVG: 62,524,894,801 <br /> MIN: 62,524,894,801 <br /> MAX: 62,524,894,801 | AVG: 74,236,711 <br /> MIN: 74,236,711 <br /> MAX: 74,236,711 |
| sphincs-haraka-128s-simple (1 executions) | clean | AVG: 2,312,526,371 <br /> MIN: 2,312,526,371 <br /> MAX: 2,312,526,371 | AVG: 41,763,744,956 <br /> MIN: 41,763,744,956 <br /> MAX: 41,763,744,956 | AVG: 49,027,345 <br /> MIN: 49,027,345 <br /> MAX: 49,027,345 |
| sphincs-haraka-192f-robust (1 executions) | clean | AVG: 155,439,216 <br /> MIN: 155,439,216 <br /> MAX: 155,439,216 | AVG: 4,652,177,447 <br /> MIN: 4,652,177,447 <br /> MAX: 4,652,177,447 | AVG: 256,338,061 <br /> MIN: 256,338,061 <br /> MAX: 256,338,061 |
| sphincs-haraka-192f-simple (1 executions) | clean | AVG: 107,283,097 <br /> MIN: 107,283,097 <br /> MAX: 107,283,097 | AVG: 3,085,709,070 <br /> MIN: 3,085,709,070 <br /> MAX: 3,085,709,070 | AVG: 166,164,511 <br /> MIN: 166,164,511 <br /> MAX: 166,164,511 |
| sphincs-haraka-192s-robust (1 executions) | clean | AVG: 4,957,423,580 <br /> MIN: 4,957,423,580 <br /> MAX: 4,957,423,580 | AVG: 154,252,533,152 <br /> MIN: 154,252,533,152 <br /> MAX: 154,252,533,152 | AVG: 109,139,892 <br /> MIN: 109,139,892 <br /> MAX: 109,139,892 |
| sphincs-haraka-192s-simple (1 executions) | clean | AVG: 3,414,973,804 <br /> MIN: 3,414,973,804 <br /> MAX: 3,414,973,804 | AVG: 92,511,052,693 <br /> MIN: 92,511,052,693 <br /> MAX: 92,511,052,693 | AVG: 69,348,483 <br /> MIN: 69,348,483 <br /> MAX: 69,348,483 |
| sphincs-haraka-256f-robust (1 executions) | clean | AVG: 415,505,369 <br /> MIN: 415,505,369 <br /> MAX: 415,505,369 | AVG: 11,565,752,019 <br /> MIN: 11,565,752,019 <br /> MAX: 11,565,752,019 | AVG: 281,617,290 <br /> MIN: 281,617,290 <br /> MAX: 281,617,290 |
| sphincs-haraka-256f-simple (1 executions) | clean | AVG: 285,187,734 <br /> MIN: 285,187,734 <br /> MAX: 285,187,734 | AVG: 7,640,032,455 <br /> MIN: 7,640,032,455 <br /> MAX: 7,640,032,455 | AVG: 180,034,945 <br /> MIN: 180,034,945 <br /> MAX: 180,034,945 |
| sphincs-haraka-256s-robust (1 executions) | clean | AVG: 6,639,678,246 <br /> MIN: 6,639,678,246 <br /> MAX: 6,639,678,246 | AVG: 103,766,698,356 <br /> MIN: 103,766,698,356 <br /> MAX: 103,766,698,356 | AVG: 155,075,291 <br /> MIN: 155,075,291 <br /> MAX: 155,075,291 |
| sphincs-haraka-256s-simple (1 executions) | clean | AVG: 4,553,903,216 <br /> MIN: 4,553,903,216 <br /> MAX: 4,553,903,216 | AVG: 67,655,677,564 <br /> MIN: 67,655,677,564 <br /> MAX: 67,655,677,564 | AVG: 97,032,765 <br /> MIN: 97,032,765 <br /> MAX: 97,032,765 |
| sphincs-sha256-128f-robust (1 executions) | clean | AVG: 30,451,820 <br /> MIN: 30,451,820 <br /> MAX: 30,451,820 | AVG: 913,010,999 <br /> MIN: 913,010,999 <br /> MAX: 913,010,999 | AVG: 40,044,144 <br /> MIN: 40,044,144 <br /> MAX: 40,044,144 |
| sphincs-sha256-128f-simple (1 executions) | clean | AVG: 15,885,652 <br /> MIN: 15,885,652 <br /> MAX: 15,885,652 | AVG: 501,886,187 <br /> MIN: 501,886,187 <br /> MAX: 501,886,187 | AVG: 20,485,450 <br /> MIN: 20,485,450 <br /> MAX: 20,485,450 |
| sphincs-sha256-128s-robust (1 executions) | clean | AVG: 974,418,741 <br /> MIN: 974,418,741 <br /> MAX: 974,418,741 | AVG: 13,492,552,612 <br /> MIN: 13,492,552,612 <br /> MAX: 13,492,552,612 | AVG: 16,136,401 <br /> MIN: 16,136,401 <br /> MAX: 16,136,401 |
| sphincs-sha256-128s-simple (1 executions) | clean | AVG: 508,321,032 <br /> MIN: 508,321,032 <br /> MAX: 508,321,032 | AVG: 7,572,714,561 <br /> MIN: 7,572,714,561 <br /> MAX: 7,572,714,561 | AVG: 8,536,143 <br /> MIN: 8,536,143 <br /> MAX: 8,536,143 |
| sphincs-sha256-192f-robust (1 executions) | clean | AVG: 45,103,023 <br /> MIN: 45,103,023 <br /> MAX: 45,103,023 | AVG: 1,249,764,240 <br /> MIN: 1,249,764,240 <br /> MAX: 1,249,764,240 | AVG: 67,736,254 <br /> MIN: 67,736,254 <br /> MAX: 67,736,254 |
| sphincs-sha256-192f-simple (1 executions) | clean | AVG: 23,383,037 <br /> MIN: 23,383,037 <br /> MAX: 23,383,037 | AVG: 660,342,413 <br /> MIN: 660,342,413 <br /> MAX: 660,342,413 | AVG: 34,796,461 <br /> MIN: 34,796,461 <br /> MAX: 34,796,461 |
| sphincs-sha256-192s-robust (1 executions) | clean | AVG: 1,443,548,267 <br /> MIN: 1,443,548,267 <br /> MAX: 1,443,548,267 | AVG: 32,993,219,079 <br /> MIN: 32,993,219,079 <br /> MAX: 32,993,219,079 | AVG: 27,028,393 <br /> MIN: 27,028,393 <br /> MAX: 27,028,393 |
| sphincs-sha256-192s-simple (1 executions) | clean | AVG: 748,304,420 <br /> MIN: 748,304,420 <br /> MAX: 748,304,420 | AVG: 18,259,605,222 <br /> MIN: 18,259,605,222 <br /> MAX: 18,259,605,222 | AVG: 13,123,397 <br /> MIN: 13,123,397 <br /> MAX: 13,123,397 |
| sphincs-sha256-256f-robust (1 executions) | clean | AVG: 164,746,703 <br /> MIN: 164,746,703 <br /> MAX: 164,746,703 | AVG: 3,845,873,979 <br /> MIN: 3,845,873,979 <br /> MAX: 3,845,873,979 | AVG: 98,213,027 <br /> MIN: 98,213,027 <br /> MAX: 98,213,027 |
| sphincs-sha256-256f-simple (1 executions) | clean | AVG: 61,612,464 <br /> MIN: 61,612,464 <br /> MAX: 61,612,464 | AVG: 1,491,615,665 <br /> MIN: 1,491,615,665 <br /> MAX: 1,491,615,665 | AVG: 33,467,278 <br /> MIN: 33,467,278 <br /> MAX: 33,467,278 |
| sphincs-sha256-256s-robust (1 executions) | clean | AVG: 2,635,813,970 <br /> MIN: 2,635,813,970 <br /> MAX: 2,635,813,970 | AVG: 32,407,251,834 <br /> MIN: 32,407,251,834 <br /> MAX: 32,407,251,834 | AVG: 50,467,208 <br /> MIN: 50,467,208 <br /> MAX: 50,467,208 |
| sphincs-sha256-256s-simple (1 executions) | clean | AVG: 984,061,436 <br /> MIN: 984,061,436 <br /> MAX: 984,061,436 | AVG: 12,706,371,963 <br /> MIN: 12,706,371,963 <br /> MAX: 12,706,371,963 | AVG: 16,953,550 <br /> MIN: 16,953,550 <br /> MAX: 16,953,550 |
| sphincs-shake256-128f-robust (1 executions) | clean | AVG: 123,675,001 <br /> MIN: 123,675,001 <br /> MAX: 123,675,001 | AVG: 3,724,808,782 <br /> MIN: 3,724,808,782 <br /> MAX: 3,724,808,782 | AVG: 155,483,138 <br /> MIN: 155,483,138 <br /> MAX: 155,483,138 |
| sphincs-shake256-128f-simple (1 executions) | clean | AVG: 64,743,271 <br /> MIN: 64,743,271 <br /> MAX: 64,743,271 | AVG: 2,042,275,185 <br /> MIN: 2,042,275,185 <br /> MAX: 2,042,275,185 | AVG: 83,236,499 <br /> MIN: 83,236,499 <br /> MAX: 83,236,499 |
| sphincs-shake256-128s-robust (1 executions) | clean | AVG: 3,958,438,673 <br /> MIN: 3,958,438,673 <br /> MAX: 3,958,438,673 | AVG: 54,970,280,033 <br /> MIN: 54,970,280,033 <br /> MAX: 54,970,280,033 | AVG: 65,831,050 <br /> MIN: 65,831,050 <br /> MAX: 65,831,050 |
| sphincs-shake256-128s-simple (1 executions) | clean | AVG: 2,072,192,474 <br /> MIN: 2,072,192,474 <br /> MAX: 2,072,192,474 | AVG: 30,742,206,291 <br /> MIN: 30,742,206,291 <br /> MAX: 30,742,206,291 | AVG: 33,429,828 <br /> MIN: 33,429,828 <br /> MAX: 33,429,828 |
| sphincs-shake256-192f-robust (1 executions) | clean | AVG: 180,902,667 <br /> MIN: 180,902,667 <br /> MAX: 180,902,667 | AVG: 4,833,042,594 <br /> MIN: 4,833,042,594 <br /> MAX: 4,833,042,594 | AVG: 260,031,324 <br /> MIN: 260,031,324 <br /> MAX: 260,031,324 |
| sphincs-shake256-192f-simple (1 executions) | clean | AVG: 94,781,811 <br /> MIN: 94,781,811 <br /> MAX: 94,781,811 | AVG: 2,587,334,240 <br /> MIN: 2,587,334,240 <br /> MAX: 2,587,334,240 | AVG: 133,725,733 <br /> MIN: 133,725,733 <br /> MAX: 133,725,733 |
| sphincs-shake256-192s-robust (1 executions) | clean | AVG: 5,789,711,895 <br /> MIN: 5,789,711,895 <br /> MAX: 5,789,711,895 | AVG: 111,624,024,828 <br /> MIN: 111,624,024,828 <br /> MAX: 111,624,024,828 | AVG: 100,489,271 <br /> MIN: 100,489,271 <br /> MAX: 100,489,271 |
| sphincs-shake256-192s-simple (1 executions) | clean | AVG: 3,033,412,869 <br /> MIN: 3,033,412,869 <br /> MAX: 3,033,412,869 | AVG: 64,006,211,462 <br /> MIN: 64,006,211,462 <br /> MAX: 64,006,211,462 | AVG: 50,458,310 <br /> MIN: 50,458,310 <br /> MAX: 50,458,310 |
| sphincs-shake256-256f-robust (1 executions) | clean | AVG: 477,486,577 <br /> MIN: 477,486,577 <br /> MAX: 477,486,577 | AVG: 10,553,664,844 <br /> MIN: 10,553,664,844 <br /> MAX: 10,553,664,844 | AVG: 247,555,237 <br /> MIN: 247,555,237 <br /> MAX: 247,555,237 |
| sphincs-shake256-256f-simple (1 executions) | clean | AVG: 250,219,751 <br /> MIN: 250,219,751 <br /> MAX: 250,219,751 | AVG: 5,725,793,871 <br /> MIN: 5,725,793,871 <br /> MAX: 5,725,793,871 | AVG: 129,794,567 <br /> MIN: 129,794,567 <br /> MAX: 129,794,567 |
| sphincs-shake256-256s-robust (1 executions) | clean | AVG: 7,638,845,460 <br /> MIN: 7,638,845,460 <br /> MAX: 7,638,845,460 | AVG: 86,889,397,588 <br /> MIN: 86,889,397,588 <br /> MAX: 86,889,397,588 | AVG: 135,727,574 <br /> MIN: 135,727,574 <br /> MAX: 135,727,574 |
| sphincs-shake256-256s-simple (1 executions) | clean | AVG: 4,002,263,639 <br /> MIN: 4,002,263,639 <br /> MAX: 4,002,263,639 | AVG: 47,704,523,709 <br /> MIN: 47,704,523,709 <br /> MAX: 47,704,523,709 | AVG: 63,640,304 <br /> MIN: 63,640,304 <br /> MAX: 63,640,304 |
# Memory Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | Key Generation [bytes] | Encapsulation [bytes] | Decapsulation [bytes] |
| ------ | -------------- | ---------------------- | --------------------- | --------------------- |
| bikel1 | m4f | 44,108 | 32,156 | 91,400 |
| bikel1 | ref | 35,960 | 25,908 | 78,784 |
| firesaber | clean | 19,524 | 19,628 | 21,108 |
| firesaber | m4f | 7,388 | 7,340 | 7,356 |
| frodokem640aes | m4 | 31,992 | 62,488 | 83,104 |
| frodokem640shake | m4 | 26,600 | 51,976 | 72,592 |
| frodokem640shake | opt | 36,664 | 58,320 | 78,944 |
| hqc-rmrs-128 | clean | 48,348 | 63,932 | 70,676 |
| kyber1024 | clean | 15,164 | 18,836 | 20,412 |
| kyber1024 | m4 | 3,788 | 3,476 | 3,508 |
| kyber1024-90s | clean | 15,340 | 19,020 | 20,596 |
| kyber1024-90s | m4 | 4,636 | 4,000 | 4,032 |
| kyber512 | clean | 6,292 | 8,956 | 9,732 |
| kyber512 | m4 | 2,396 | 2,484 | 2,500 |
| kyber512-90s | clean | 6,548 | 9,212 | 9,988 |
| kyber512-90s | m4 | 2,904 | 2,992 | 3,008 |
| kyber768 | clean | 10,388 | 13,556 | 14,652 |
| kyber768 | m4 | 3,276 | 2,964 | 2,988 |
| kyber768-90s | clean | 10,652 | 13,820 | 14,916 |
| kyber768-90s | m4 | 3,432 | 3,504 | 3,520 |
| lightsaber | clean | 9,332 | 9,436 | 10,180 |
| lightsaber | m4f | 5,332 | 5,292 | 5,308 |
| ntruhps2048509 | clean | 25,532 | 20,680 | 18,996 |
| ntruhps2048509 | m4f | 21,392 | 14,068 | 14,800 |
| ntruhps2048677 | clean | 34,296 | 27,756 | 25,548 |
| ntruhps2048677 | m4f | 28,504 | 9,036 | 19,728 |
| ntruhps4096821 | clean | 40,960 | 33,036 | 30,472 |
| ntruhps4096821 | m4f | 34,504 | 10,924 | 23,952 |
| ntruhrss701 | clean | 32,920 | 26,140 | 25,984 |
| ntruhrss701 | m4f | 27,560 | 7,400 | 20,552 |
| ntrulpr653 | clean | 11,864 | 12,048 | 13,416 |
| ntrulpr761 | clean | 10,784 | 12,376 | 13,864 |
| ntrulpr761 | m4f | 13,168 | 20,000 | 24,032 |
| ntrulpr857 | clean | 15,640 | 15,600 | 17,376 |
| saber | clean | 12,908 | 13,012 | 14,108 |
| saber | m4f | 6,364 | 6,316 | 6,332 |
| sikep434 | m4 | 6,272 | 6,504 | 6,840 |
| sikep434 | opt | 6,752 | 7,040 | 7,376 |
| sikep503 | m4 | 6,992 | 7,344 | 7,720 |
| sikep503 | opt | 6,664 | 7,016 | 7,392 |
| sikep610 | m4 | 10,504 | 10,904 | 11,368 |
| sikep610 | opt | 10,072 | 10,488 | 10,936 |
| sikep751 | m4 | 12,272 | 12,272 | 12,840 |
| sikep751 | opt | 11,616 | 11,728 | 12,296 |
| sntrup653 | clean | 10,664 | 8,096 | 9,656 |
| sntrup761 | clean | 12,280 | 9,256 | 11,200 |
| sntrup761 | m4f | 61,508 | 13,320 | 16,952 |
| sntrup857 | clean | 13,912 | 10,400 | 12,696 |
## Signature Schemes
| Scheme | Implementation | Key Generation [bytes] | Sign [bytes] | Verify [bytes] |
| ------ | -------------- | ---------------------- | ------------ | -------------- |
| dilithium2 | clean | 38,428 | 52,052 | 36,340 |
| dilithium2 | m4 | 38,420 | 52,044 | 36,332 |
| dilithium3 | clean | 60,956 | 79,700 | 57,844 |
| dilithium3 | m4 | 60,948 | 79,692 | 57,836 |
| falcon-1024 | clean | 35,256 | 82,484 | 8,796 |
| falcon-1024 | m4-ct | 1,432 | 2,680 | 492 |
| falcon-1024 | opt-ct | 1,504 | 2,568 | 496 |
| falcon-1024 | opt-leaktime | 1,408 | 2,672 | 492 |
| falcon-512 | clean | 18,392 | 42,460 | 4,700 |
| falcon-512 | m4-ct | 1,480 | 2,480 | 492 |
| falcon-512 | opt-ct | 1,488 | 2,479 | 492 |
| falcon-512 | opt-leaktime | 1,488 | 2,576 | 492 |
| falcon-512-tree | m4-ct | 1,440 | 2,776 | 492 |
| falcon-512-tree | opt-ct | 1,496 | 2,776 | 492 |
| falcon-512-tree | opt-leaktime | 1,400 | 2,792 | 492 |
| sphincs-haraka-128f-robust | clean | 3,612 | 3,704 | 4,068 |
| sphincs-haraka-128f-simple | clean | 3,604 | 3,776 | 4,060 |
| sphincs-haraka-128s-robust | clean | 3,824 | 3,872 | 3,380 |
| sphincs-haraka-128s-simple | clean | 3,788 | 3,864 | 3,372 |
| sphincs-haraka-192f-robust | clean | 5,048 | 5,160 | 5,396 |
| sphincs-haraka-192f-simple | clean | 5,012 | 5,152 | 5,388 |
| sphincs-haraka-192s-robust | clean | 5,312 | 5,296 | 4,732 |
| sphincs-haraka-192s-simple | clean | 5,304 | 5,288 | 4,724 |
| sphincs-haraka-256f-robust | clean | 7,012 | 7,008 | 6,660 |
| sphincs-haraka-256f-simple | clean | 7,032 | 7,000 | 6,652 |
| sphincs-haraka-256s-robust | clean | 7,352 | 7,232 | 6,624 |
| sphincs-haraka-256s-simple | clean | 7,344 | 7,224 | 6,588 |
| sphincs-sha256-128f-robust | clean | 2,256 | 2,320 | 2,712 |
| sphincs-sha256-128f-simple | clean | 2,096 | 2,272 | 2,552 |
| sphincs-sha256-128s-robust | clean | 2,440 | 2,520 | 2,024 |
| sphincs-sha256-128s-simple | clean | 2,280 | 2,360 | 1,864 |
| sphincs-sha256-192f-robust | clean | 3,672 | 3,816 | 4,048 |
| sphincs-sha256-192f-simple | clean | 3,504 | 3,536 | 3,880 |
| sphincs-sha256-192s-robust | clean | 3,976 | 3,952 | 3,384 |
| sphincs-sha256-192s-simple | clean | 3,768 | 3,784 | 3,216 |
| sphincs-sha256-256f-robust | clean | 5,712 | 5,752 | 5,320 |
| sphincs-sha256-256f-simple | clean | 5,496 | 5,576 | 5,144 |
| sphincs-sha256-256s-robust | clean | 5,984 | 5,896 | 5,256 |
| sphincs-sha256-256s-simple | clean | 5,768 | 5,720 | 5,080 |
| sphincs-shake256-128f-robust | clean | 2,180 | 2,236 | 2,628 |
| sphincs-shake256-128f-simple | clean | 2,180 | 2,236 | 2,628 |
| sphincs-shake256-128s-robust | clean | 2,364 | 2,432 | 1,968 |
| sphincs-shake256-128s-simple | clean | 2,364 | 2,432 | 2,048 |
| sphincs-shake256-192f-robust | clean | 3,596 | 3,728 | 3,964 |
| sphincs-shake256-192f-simple | clean | 3,596 | 3,728 | 3,964 |
| sphincs-shake256-192s-robust | clean | 3,896 | 3,864 | 3,300 |
| sphincs-shake256-192s-simple | clean | 3,896 | 3,864 | 3,300 |
| sphincs-shake256-256f-robust | clean | 5,632 | 5,664 | 5,236 |
| sphincs-shake256-256f-simple | clean | 5,596 | 5,664 | 5,236 |
| sphincs-shake256-256s-robust | clean | 5,904 | 5,808 | 5,172 |
| sphincs-shake256-256s-simple | clean | 5,904 | 5,808 | 5,172 |
# Hashing Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | Key Generation [%] | Encapsulation [%] | Decapsulation [%] |
| ------ | -------------- | ------------------ | ----------------- | ----------------- |
| bikel1 | m4f | 0.7% | 15.1% | 1.3% |
| bikel1 | ref | 0.3% | 10.3% | 0.6% |
| firesaber | clean | 19.2% | 19.1% | 14.1% |
| firesaber | m4f | 71.0% | 72.2% | 63.2% |
| frodokem640aes | m4 | 74.3% | 77.8% | 77.1% |
| frodokem640shake | m4 | 85.5% | 86.5% | 86.2% |
| frodokem640shake | opt | 74.2% | 65.7% | 65.2% |
| hqc-rmrs-128 | clean | 53.6% | 41.4% | 33.2% |
| kyber1024 | clean | 54.9% | 54.3% | 43.2% |
| kyber1024 | m4 | 74.8% | 78.4% | 70.7% |
| kyber1024-90s | clean | 73.8% | 70.5% | 64.0% |
| kyber1024-90s | m4 | 66.5% | 69.0% | 62.3% |
| kyber512 | clean | 55.3% | 52.4% | 37.7% |
| kyber512 | m4 | 76.2% | 78.8% | 67.8% |
| kyber512-90s | clean | 68.7% | 62.7% | 52.6% |
| kyber512-90s | m4 | 68.6% | 70.3% | 60.8% |
| kyber768 | clean | 53.4% | 53.0% | 40.3% |
| kyber768 | m4 | 74.2% | 78.2% | 69.0% |
| kyber768-90s | clean | 71.4% | 67.4% | 59.4% |
| kyber768-90s | m4 | 66.0% | 69.0% | 61.1% |
| lightsaber | clean | 25.3% | 24.2% | 15.7% |
| lightsaber | m4f | 72.1% | 73.8% | 61.2% |
| ntruhps2048509 | clean | 0.0% | 2.5% | 4.2% |
| ntruhps2048509 | m4f | 0.0% | 4.7% | 19.2% |
| ntruhps2048677 | clean | 0.0% | 2.2% | 3.3% |
| ntruhps2048677 | m4f | 0.0% | 4.7% | 17.3% |
| ntruhps4096821 | clean | 0.0% | 1.7% | 2.9% |
| ntruhps4096821 | m4f | 0.0% | 3.8% | 16.1% |
| ntruhrss701 | clean | 0.0% | 2.6% | 3.5% |
| ntruhrss701 | m4f | 0.0% | 10.3% | 17.7% |
| ntrulpr653 | clean | 5.4% | 6.0% | 3.5% |
| ntrulpr761 | clean | 7.9% | 8.5% | 5.4% |
| ntrulpr761 | m4f | 23.5% | 41.6% | 38.8% |
| ntrulpr857 | clean | 4.2% | 4.6% | 2.7% |
| saber | clean | 22.0% | 21.7% | 15.2% |
| saber | m4f | 72.2% | 73.6% | 63.1% |
| sikep434 | m4 | 0.0% | 0.1% | 0.1% |
| sikep434 | opt | 0.0% | 0.0% | 0.0% |
| sikep503 | m4 | 0.0% | 0.1% | 0.1% |
| sikep503 | opt | 0.0% | 0.0% | 0.0% |
| sikep610 | m4 | 0.0% | 0.1% | 0.1% |
| sikep610 | opt | 0.0% | 0.0% | 0.0% |
| sikep751 | m4 | 0.0% | 0.0% | 0.0% |
| sikep751 | opt | 0.0% | 0.0% | 0.0% |
| sntrup653 | clean | 0.1% | 4.2% | 1.0% |
| sntrup761 | clean | 0.1% | 3.7% | 0.8% |
| sntrup761 | m4f | 0.0% | 0.0% | 0.0% |
| sntrup857 | clean | 0.1% | 3.2% | 0.7% |
## Signature Schemes
| Scheme | Implementation | Key Generation [%] | Sign [%] | Verify [%] |
| ------ | -------------- | ------------------ | -------- | ---------- |
| dilithium2 | clean | 66.7% | 37.0% | 60.4% |
| dilithium2 | m4 | 82.4% | 64.0% | 80.4% |
| dilithium3 | clean | 70.9% | 37.9% | 64.0% |
| dilithium3 | m4 | 85.0% | 64.0% | 82.6% |
| falcon-1024 | clean | 8.5% | 0.3% | 27.0% |
| falcon-1024 | m4-ct | 11.1% | 0.5% | 34.2% |
| falcon-1024 | opt-ct | 10.7% | 0.5% | 34.3% |
| falcon-1024 | opt-leaktime | 12.6% | 0.5% | 34.2% |
| falcon-512 | clean | 12.8% | 0.4% | 29.4% |
| falcon-512 | m4-ct | 15.9% | 0.5% | 36.0% |
| falcon-512 | opt-ct | 17.1% | 0.5% | 35.9% |
| falcon-512 | opt-leaktime | 18.4% | 0.6% | 36.0% |
| falcon-512-tree | m4-ct | 15.9% | 1.2% | 36.0% |
| falcon-512-tree | opt-ct | 17.0% | 1.2% | 35.9% |
| falcon-512-tree | opt-leaktime | 19.3% | 1.1% | 35.9% |
| sphincs-haraka-128f-robust | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-128f-simple | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-128s-robust | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-128s-simple | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-192f-robust | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-192f-simple | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-192s-robust | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-192s-simple | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-256f-robust | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-256f-simple | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-256s-robust | clean | 0.0% | 0.0% | 0.0% |
| sphincs-haraka-256s-simple | clean | 0.0% | 0.0% | 0.0% |
| sphincs-sha256-128f-robust | clean | 89.0% | 88.6% | 89.0% |
| sphincs-sha256-128f-simple | clean | 87.5% | 86.9% | 87.5% |
| sphincs-sha256-128s-robust | clean | 89.0% | 88.4% | 89.0% |
| sphincs-sha256-128s-simple | clean | 87.5% | 86.7% | 87.4% |
| sphincs-sha256-192f-robust | clean | 88.5% | 88.6% | 88.8% |
| sphincs-sha256-192f-simple | clean | 87.3% | 87.4% | 87.6% |
| sphincs-sha256-192s-robust | clean | 88.5% | 89.0% | 89.0% |
| sphincs-sha256-192s-simple | clean | 87.3% | 87.8% | 87.8% |
| sphincs-sha256-256f-robust | clean | 91.9% | 91.9% | 92.2% |
| sphincs-sha256-256f-simple | clean | 87.0% | 87.2% | 87.3% |
| sphincs-sha256-256s-robust | clean | 91.9% | 92.0% | 92.4% |
| sphincs-sha256-256s-simple | clean | 87.2% | 87.4% | 87.7% |
| sphincs-shake256-128f-robust | clean | 97.8% | 97.6% | 97.8% |
| sphincs-shake256-128f-simple | clean | 96.4% | 96.3% | 96.4% |
| sphincs-shake256-128s-robust | clean | 97.8% | 97.6% | 97.8% |
| sphincs-shake256-128s-simple | clean | 96.4% | 96.2% | 96.3% |
| sphincs-shake256-192f-robust | clean | 97.7% | 97.7% | 97.7% |
| sphincs-shake256-192f-simple | clean | 96.3% | 96.3% | 96.3% |
| sphincs-shake256-192s-robust | clean | 97.7% | 97.4% | 97.7% |
| sphincs-shake256-192s-simple | clean | 96.3% | 96.0% | 96.2% |
| sphincs-shake256-256f-robust | clean | 97.7% | 97.6% | 97.7% |
| sphincs-shake256-256f-simple | clean | 96.3% | 96.2% | 96.2% |
| sphincs-shake256-256s-robust | clean | 97.7% | 97.5% | 97.7% |
| sphincs-shake256-256s-simple | clean | 96.3% | 96.1% | 96.2% |
# Size Evaluation
## Key Encapsulation Schemes
| Scheme | Implementation | .text [bytes] | .data [bytes] | .bss [bytes] | Total [bytes] |
| ------ | -------------- | ------------- | ------------- | ------------ | ------------- |
| bikel1 | m4f | 181,430 | 24 | 49 | 181,503 |
| bikel1 | ref | 35,199 | 24 | 1 | 35,224 |
| firesaber | clean | 10,220 | 0 | 0 | 10,220 |
| firesaber | m4f | 9,556 | 0 | 0 | 9,556 |
| frodokem640aes | m4 | 8,568 | 0 | 0 | 8,568 |
| frodokem640shake | m4 | 8,644 | 0 | 0 | 8,644 |
| frodokem640shake | opt | 6,476 | 0 | 0 | 6,476 |
| hqc-rmrs-128 | clean | 18,460 | 0 | 0 | 18,460 |
| kyber1024 | clean | 6,084 | 0 | 0 | 6,084 |
| kyber1024 | m4 | 11,696 | 0 | 0 | 11,696 |
| kyber1024-90s | clean | 6,468 | 0 | 0 | 6,468 |
| kyber1024-90s | m4 | 11,976 | 0 | 0 | 11,976 |
| kyber512 | clean | 4,900 | 0 | 0 | 4,900 |
| kyber512 | m4 | 10,720 | 0 | 0 | 10,720 |
| kyber512-90s | clean | 5,148 | 0 | 0 | 5,148 |
| kyber512-90s | m4 | 10,932 | 0 | 0 | 10,932 |
| kyber768 | clean | 4,912 | 0 | 0 | 4,912 |
| kyber768 | m4 | 10,872 | 0 | 0 | 10,872 |
| kyber768-90s | clean | 5,172 | 0 | 0 | 5,172 |
| kyber768-90s | m4 | 10,848 | 0 | 0 | 10,848 |
| lightsaber | clean | 10,380 | 0 | 0 | 10,380 |
| lightsaber | m4f | 9,660 | 0 | 0 | 9,660 |
| ntruhps2048509 | clean | 64,644 | 0 | 0 | 64,644 |
| ntruhps2048509 | m4f | 91,656 | 0 | 0 | 91,656 |
| ntruhps2048677 | clean | 17,304 | 0 | 0 | 17,304 |
| ntruhps2048677 | m4f | 142,240 | 0 | 12,288 | 154,528 |
| ntruhps4096821 | clean | 17,064 | 0 | 0 | 17,064 |
| ntruhps4096821 | m4f | 167,356 | 0 | 13,824 | 181,180 |
| ntruhrss701 | clean | 16,724 | 0 | 0 | 16,724 |
| ntruhrss701 | m4f | 145,324 | 0 | 12,288 | 157,612 |
| ntrulpr653 | clean | 7,612 | 0 | 0 | 7,612 |
| ntrulpr761 | clean | 8,096 | 0 | 0 | 8,096 |
| ntrulpr761 | m4f | 130,937 | 128 | 0 | 131,065 |
| ntrulpr857 | clean | 8,340 | 0 | 0 | 8,340 |
| saber | clean | 10,128 | 0 | 0 | 10,128 |
| saber | m4f | 9,412 | 0 | 0 | 9,412 |
| sikep434 | m4 | 29,600 | 0 | 0 | 29,600 |
| sikep434 | opt | 28,232 | 0 | 0 | 28,232 |
| sikep503 | m4 | 31,576 | 0 | 0 | 31,576 |
| sikep503 | opt | 26,432 | 0 | 0 | 26,432 |
| sikep610 | m4 | 29,420 | 0 | 0 | 29,420 |
| sikep610 | opt | 19,420 | 0 | 0 | 19,420 |
| sikep751 | m4 | 33,012 | 0 | 0 | 33,012 |
| sikep751 | opt | 21,064 | 0 | 0 | 21,064 |
| sntrup653 | clean | 12,420 | 0 | 0 | 12,420 |
| sntrup761 | clean | 13,156 | 0 | 0 | 13,156 |
| sntrup761 | m4f | 162,757 | 152 | 3,608 | 166,517 |
| sntrup857 | clean | 13,536 | 0 | 0 | 13,536 |
## Signature Schemes
| Scheme | Implementation | .text [bytes] | .data [bytes] | .bss [bytes] | Total [bytes] |
| ------ | -------------- | ------------- | ------------- | ------------ | ------------- |
| dilithium2 | clean | 7,968 | 0 | 0 | 7,968 |
| dilithium2 | m4 | 10,576 | 0 | 0 | 10,576 |
| dilithium3 | clean | 7,472 | 0 | 0 | 7,472 |
| dilithium3 | m4 | 10,104 | 0 | 0 | 10,104 |
| falcon-1024 | clean | 80,193 | 0 | 0 | 80,193 |
| falcon-1024 | m4-ct | 81,289 | 0 | 79,872 | 161,161 |
| falcon-1024 | opt-ct | 81,289 | 0 | 79,872 | 161,161 |
| falcon-1024 | opt-leaktime | 74,453 | 0 | 79,872 | 154,325 |
| falcon-512 | clean | 80,165 | 0 | 0 | 80,165 |
| falcon-512 | m4-ct | 81,289 | 0 | 39,936 | 121,225 |
| falcon-512 | opt-ct | 81,289 | 0 | 39,936 | 121,225 |
| falcon-512 | opt-leaktime | 74,453 | 0 | 39,936 | 114,389 |
| falcon-512-tree | m4-ct | 81,029 | 0 | 27,648 | 108,677 |
| falcon-512-tree | opt-ct | 81,029 | 0 | 27,648 | 108,677 |
| falcon-512-tree | opt-leaktime | 74,193 | 0 | 27,648 | 101,841 |
| sphincs-haraka-128f-robust | clean | 16,788 | 0 | 0 | 16,788 |
| sphincs-haraka-128f-simple | clean | 16,636 | 0 | 0 | 16,636 |
| sphincs-haraka-128s-robust | clean | 17,100 | 0 | 0 | 17,100 |
| sphincs-haraka-128s-simple | clean | 16,948 | 0 | 0 | 16,948 |
| sphincs-haraka-192f-robust | clean | 16,656 | 0 | 0 | 16,656 |
| sphincs-haraka-192f-simple | clean | 16,472 | 0 | 0 | 16,472 |
| sphincs-haraka-192s-robust | clean | 16,860 | 0 | 0 | 16,860 |
| sphincs-haraka-192s-simple | clean | 16,676 | 0 | 0 | 16,676 |
| sphincs-haraka-256f-robust | clean | 17,140 | 0 | 0 | 17,140 |
| sphincs-haraka-256f-simple | clean | 16,900 | 0 | 0 | 16,900 |
| sphincs-haraka-256s-robust | clean | 17,340 | 0 | 0 | 17,340 |
| sphincs-haraka-256s-simple | clean | 17,096 | 0 | 0 | 17,096 |
| sphincs-sha256-128f-robust | clean | 4,948 | 0 | 0 | 4,948 |
| sphincs-sha256-128f-simple | clean | 4,700 | 0 | 0 | 4,700 |
| sphincs-sha256-128s-robust | clean | 5,260 | 0 | 0 | 5,260 |
| sphincs-sha256-128s-simple | clean | 5,012 | 0 | 0 | 5,012 |
| sphincs-sha256-192f-robust | clean | 5,040 | 0 | 0 | 5,040 |
| sphincs-sha256-192f-simple | clean | 4,672 | 0 | 0 | 4,672 |
| sphincs-sha256-192s-robust | clean | 5,252 | 0 | 0 | 5,252 |
| sphincs-sha256-192s-simple | clean | 4,884 | 0 | 0 | 4,884 |
| sphincs-sha256-256f-robust | clean | 5,620 | 0 | 0 | 5,620 |
| sphincs-sha256-256f-simple | clean | 5,152 | 0 | 0 | 5,152 |
| sphincs-sha256-256s-robust | clean | 5,816 | 0 | 0 | 5,816 |
| sphincs-sha256-256s-simple | clean | 5,344 | 0 | 0 | 5,344 |
| sphincs-shake256-128f-robust | clean | 4,216 | 0 | 0 | 4,216 |
| sphincs-shake256-128f-simple | clean | 4,076 | 0 | 0 | 4,076 |
| sphincs-shake256-128s-robust | clean | 4,532 | 0 | 0 | 4,532 |
| sphincs-shake256-128s-simple | clean | 4,392 | 0 | 0 | 4,392 |
| sphincs-shake256-192f-robust | clean | 4,128 | 0 | 0 | 4,128 |
| sphincs-shake256-192f-simple | clean | 3,956 | 0 | 0 | 3,956 |
| sphincs-shake256-192s-robust | clean | 4,336 | 0 | 0 | 4,336 |
| sphincs-shake256-192s-simple | clean | 4,164 | 0 | 0 | 4,164 |
| sphincs-shake256-256f-robust | clean | 4,628 | 0 | 0 | 4,628 |
| sphincs-shake256-256f-simple | clean | 4,416 | 0 | 0 | 4,416 |
| sphincs-shake256-256s-robust | clean | 4,820 | 0 | 0 | 4,820 |
| sphincs-shake256-256s-simple | clean | 4,612 | 0 | 0 | 4,612 |
