[![Build Status](https://travis-ci.org/chakri9/GenRank.svg?branch=master)](https://travis-ci.org/chakri9/GenRank)
***
# GenRank

Methods for ranking genes based on convergent evidence obtained from multiple independent evidence layers. Integration of data at gene-level from multiple evidence layers has been shown to be an effective approach to identify and prioritize candidate genes in complex genetic traits. This package implements three methods to integrate gene-level data generated from multiple independent lines of investigation:

- Convergent Evidence (CE) method, which is a variant of the famous   PageRank algorithm
- Rank Product (RP) method, which was earlier proposed to perform differential expression and meta-analysis of microarray-based gene expression data, and
- The traditional methods to combine p-values.

For detailed information and tutorials, see the package vignette.

## Installation

```r
library(devtools)
# if you don't have the package, run install.packages("devtools")
install_github("chakri9/GenRank")
```
***
