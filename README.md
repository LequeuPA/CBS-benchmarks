# CBS-benchmarks
This repository contains the results of the benchmarks and their analysis for the "Composite Balance Score: Leveraging Protected Attributes Balance to Predict and Improve Fairness in Machine Learning" article submitted to the ACM Journal of Responsible Computing.

## Files and Folders
- The _results_ folder contains the files for the two bencharks of the article.
  - _./CBS_ contains the results of the evaluation of the Balance Index, RMSDIR, RMSPMI and CBS for every protected attribute.
  - _./benchmark_ contains the results of the evaluation of the balancing strategies and resampling methods for each dataset.
- The _figures_ folder contains the figures used in the article in a PDF format.
- The _full_benchmark_analysis.ipynb_ notebook contain the anaylsis of the benchmarks that produced the results presented in the article.
- The _requirements.txt_ file gives the versions of the packages used for this analysis.

## Technical Details
The metrics, mitigation methods, data processing, and benchmark are all implemented in python 3.8.18, using pandas 2.0.3, scikit-learn 1.3.2, fairlearn 0.7.0, scipy 1.10.1 and imbalanced-learn 0.9.1. The benchmarks were run on a Ubuntu machine with twenty Intel Xeon E5 CPUs and 32GiB of memory.
