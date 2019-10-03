
# Your discussion about testing

This is where you should provide a description in
[GitHub Markdown](https://guides.github.com/features/mastering-markdown/)
that clearly describes:

* how you did the tests,
* sample outputs from running the tests
* the table and
* a discussion of the results.


# Tests
* I created files TestEverything and Collections.
TestEverything was used to both measure speed and test the implementations of all 3  designs for correctness of the outputs. I compared outputs of the reference design (0) to all the other designs to make sure the outputs are correct. There appeared slight defferences caused by rounding errors, but they are negligeable.

* Sample:
```java
PointCP('C'): 
Design 0 (max: 8718.227ns, median: 32.821ns, min: 14.222ns)
Design 2 (max: 7301.474ns, median: 125.63ns, min: 69.288ns)
Design 3 (max: 2826.577ns, median: 31.362ns, min: 18.963ns)
Design 6 (max: 2572.836ns, median: 30.583ns, min: 20.584ns)
```

* I worked myself without a partner, and got decent results for futher analysis. Design 6 appeared to have the same speed as the corresponding implementations.
