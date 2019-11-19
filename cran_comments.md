## Test environments

* local install: Fedora 30, R 3.6.1
* Ubuntu 16.04 (on travis-ci), R 3.6.2
* win-builder (R-devel)


## R CMD check results

There were no ERRORs, WARNING or NOTEs.


## Resubmission 1

This is a resubmission. In this version I have:

* removed the "R" from the title
* added single quotes to software names in the description
* added examples how to use distributions
* added examples how to use bijectors
* added examples how to use the most important MCMC kernels
* added examples how to use essential state space modeling functionality
* added examples how to use Keras distribution layers


## Resubmission 2

This is a resubmission. In this version I have:

* prevented tests from running on CRAN because even though actual tests were skipped, elapsed time was extraordinarily high (perhaps due to some network issue):

```
      test_check("tfprobability")

== testthat results  ===========================================================
[ OK: 0 | SKIPPED: 224 | WARNINGS: 0 | FAILED: 0 ]
>

    proc.time()

  user  system elapsed
  5.78    1.68  302.47
```

## Resubmission 3

This is a resubmission. In this version I have:

* documented return values of distribution constructors, distribution methods, distribution-related utility functions, bijector constructors, bijector methods, Keras layers, mcmc sampling methods, structural time series models


## Resubmission 4

This is a resubmission. In this version I have:

* documented all remaining return values