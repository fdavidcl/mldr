# CHANGES IN mldr 0.1.70.9000

### New features

* New `mldr_evaluate()` function to assess multilabel classifier performance. Taking as input an `mldr` object and a matrix with predictions this function returns a list of metrics, including Accuracy, AUC, AveragePrecision, Coverage, FMeasure, HammingLoss, MacroAUC, MacroFMeasure, MacroPrecision, MacroRecall, MicroAUC, MicroFMeasure, MicroPrecision, MicroRecall, OneError, Precision, RankingLoss, Recall, and SubsetAccuracy

### Fixes

* Fixed call to `chordDiagram` for newer versions of the [`circlize`](https://github.com/jokergoo/circlize) package.

# mldr 0.1.70

First release of *mldr*. This version includes:

* Ability to read multi-label data sets from ARFF and XML files in Mulan or MEKA format.
* Ability to write to ARFF and XML files in both Mulan and MEKA formats.
* Different ways to display data and relevant measures from data sets.
* Several plots for multi-label data visualisation.
* Functions to operate with `mldr` objects: filtering, joining and structure comparison.
* BR and LP transformations of multi-label datasets.
* Ability to create new `mldr` objects out of `data.frame`s.
* Sample datasets: `birds`, `emotions` and `genbase`.
