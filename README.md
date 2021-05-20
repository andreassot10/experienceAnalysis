
<!-- README.md is generated from README.Rmd. Please edit that file -->

# experienceAnalysis

<!-- badges: start -->
<!-- badges: end -->

The goal of `{experienceAnalysis}` is to host a collection of helper functions 
that are mainly concerned with the calculation and visualization of sentiment 
analysis indicators and word counts/frequencies (e.g. TF-IDF for unigrams and bigrams)
for use with other packages, such as [`{pxtextminingdashboard}`](https://github.com/CDU-data-science-team/pxtextminingdashboard). The package can also be used in its own right- most functions are general
enough to suit different needs.


## Installation

You can install the released version of experienceAnalysis from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("experienceAnalysis")
```

## Naming guidelines for functions

### Data manipulations

-   `get_*()`: Get data, e.g. from a database or somewhere else
-   `tidy_*()`: Tidy data (generally from a database), e.g. renaming
    variables, removing duplicates, creating factors, ‘wide’ to ‘long’
    format
-   `collect_*()`: Collect data of specific cases, mainly wrapper
    functions for specific filter commands
-   `prep_*()`: Prepare data for further use, e.g. to create tables,
    sorting vectors, …

### Data analyses

-   `calc_*()`: Calculations or analyses, e.g. counting data,
    regression analyses, …
-   `summary_*()`: Summarise results of calculations, there might be
    some overlap with `prep_*()`

## Visualisations

-   `plot_*()`: Creates a plot
