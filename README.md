# ministat-win
ministat on Windows, port from freebsd

Check freebsd ministat(3) for usage


Sample:
```
ministat.exe a.txt b.txt
x a.txt
+ b.txt
+--------------------------------------------------------------------------+
|xx                                                                       +|
|xx                                                     +                 +|
|xx                                                    ++ + +     +      ++|
||A                                                     |________AM______| |
+--------------------------------------------------------------------------+
    N           Min           Max        Median           Avg        Stddev
x  10      14726.64      14849.31      14827.83     14797.566     44.044047
+  10      20771.65      22854.84      21980.24     21828.123     922.04901
Difference at 95.0% confidence
        7030.56 +/- 613.303
        47.5116% +/- 4.14462%
        (Student's t, pooled s = 652.731)

```
