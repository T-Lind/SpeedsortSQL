# SpeedsortSQL
#### Script for sorting 10 million items with SQL commands
.csv file is not attached due to the large size (~150MB) however it contains 10 million 32 bit signed integers in random order and randomly assigned to any value within +/- 0x7FFFFFFF.
- Each entry is on a separate line.
- Suprisingly fast, ~2.5s which is faster than mergesort and quicksort in C but not parallel mergesort in C.
- Execution time of sorting in Java is ~17s using Arrays.sort() so for default implementation `ORDER BY` it's very good.
