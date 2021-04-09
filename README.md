
<!-- README.md is generated from README.Rmd. Please edit that file -->

# BDC <img src="https://github.com/brunobrr/bdc/blob/master/man/figures/logo.png"/>

## A comprehensive and straightforward workflow for standardizing, integrating, and cleaning biodiversity data

<!-- badges: start -->

<!-- badges: end -->

## Installation

You can install the released version of misc from
[github](https://github.com/brunobrr/bdc) with:

``` r
if (!require("remotes")) install.packages("remotes")
if (!require("bdc")) remotes::install_github("brunobrr/bdc")
```

### Why BDC?

Handle biodiversity data from several different sources is not an easy
task. This workflow was created to facilitate i) standardization and
integration of heterogeneous datasets; and ii) to flag, document, clean,
and correct biodiversity data.

The workflow is composed of five main steps:

1\) **Standardization** and **integration** of different datasets;  
2\) **Pre-filter**: flagging and removal of invalid or non-interpretable
information, followed by data amendments (e.g., correct transposed
coordinates and standardize country names);  
3\) **Taxonomy**: cleaning, parsing, and standardization of scientific
names against multiple taxonomic references. The workflow corrects
spelling errors and converts nomenclatural synonyms to currently
accepted names;  
4\) **Space**: flagging of erroneous, suspicious, and low-precision
geographic coordinates;  
5\) **Time**: flagging and, whenever possible, correction of
inconsistent collection date.

Aim to facilitate the interpretation and visualization of results, in
each step of the workflow a report and figures are created. Further,
standardized databases resulting from each step of the workflow as well
as databases containing information needing further inspection are
automatically saved.

### Package website

See BDC package website (<https://brunobrr.github.io/bdc/>) for detailed
explanation on each step of the workflow.

### Getting help

If you encounter a clear bug, please file an issue
[here](https://github.com/brunobrr/bdc/issues). For questions or
suggestion, please send us a email (ribeiro.brr@gmail.com).
