zebu 0.1.0
----------------------------------------------------------------

* First release

zebu 0.1.1
----------------------------------------------------------------

* Added control to how dataset should be permuted through group argument

* Added progress bar to parallelized permutation test

* Changed parallelization interface to foreach and parallel

* Corrected typos in vignette

zebu 0.1.2
----------------------------------------------------------------

* When p-value is estimated to be zero by permutations, displays that it is inferior to one over number of permutations and not equal to zero

* Corrected formula for estimating p-values ()

* Added plots describing dataset and corrected typos in vignette

* Removed buggy parallel interface (too many cross-platform problems)

Development
----------------------------------------------------------------

* Added chi-squared residuals to lassie

* Added installation information, chi-squared residuals and p-value formula to vignette
