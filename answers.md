- Question 1: 
  - There are 8 minor (young) GCs and 11 major (full) GCs

- Question 2:
  - The longest GC pause time is 5.748ms

- Question 3
  - The serial collector is used because it has the lowest overhead. It allows more actual allocations when the heap size is small. The G1 is the standard collector as it has some optimizations, but still not too much overhead. The ZGC is a low pause collector, but it has a high overhead.

- Question 4: 
  - The collector did meet the target pause time. The highest pause time was 5.848ms, which is below the target of 100ms.