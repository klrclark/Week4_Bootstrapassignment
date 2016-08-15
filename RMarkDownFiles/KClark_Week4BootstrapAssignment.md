The Central Limit Theorem (CLT) states that, given certain conditions
you can expect the arthimetic mean of a large number of iterations of
independent variables and well-definted expected values and variances,
will be fairly normally distributed regardless of the underlying
distribution.

This assignment was to prove the theorem by taking two samples of
differing sample sizes to test this. Basically the CLT states that as
the number of samples increase for any given population, the distrbution
of the averages for those samples will move closer to a normally
distributed.

To test the CLT theorem I have two random datasets. One has a sample
size of 10 and the other is a sample size of 75. Each data set was
created using the bootstrap methodolgy of looping to replicate the
random sampling.

Code used:

Below are the histograms:

![](KClark_Week4BootstrapAssignment_files/figure-markdown_strict/unnamed-chunk-2-1.png)<!-- -->

The original datasets seemed do not appear to be normally distributed
and are hard to evaluate. When the datasets are then processed through
the bootstrap methodolgy for a 1000 iterations, and the averages are
evaluated from these samples, it does appearthat the datasets are
distributed normally.

The next step is to look at the exponentially distrubted datasets to see
if the histogram follows the same pattern as seen above.

![](KClark_Week4BootstrapAssignment_files/figure-markdown_strict/unnamed-chunk-3-1.png)<!-- -->

The original exponential datasets are left skewed and are not normally
distributed. Once the datasets are processed using the bootstrap
methodolgy the datasets again are normally distributed.
