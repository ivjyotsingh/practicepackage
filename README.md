
<!-- README.md is generated from README.Rmd. Please edit that file -->

# practicepackage

<!-- badges: start -->
<!-- badges: end -->

The goal of practicepackage is to add new functions for string
manipulation over and above the existing popular packages.

## Installation

You can install the development version of practicepackage from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ivjyotsingh/practicepackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(practicepackage)
(x <- "alfa,bravo,charlie,delta")
#> [1] "alfa,bravo,charlie,delta"
str_split_one(x, pattern = ",")
#> [1] "alfa"    "bravo"   "charlie" "delta"
```
