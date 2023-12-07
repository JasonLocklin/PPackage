
<!-- README.md is generated from README.Rmd. Please edit that file -->

# PPackage

<!-- badges: start -->

[![R-CMD-check](https://github.com/JasonLocklin/PPackage/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/JasonLocklin/PPackage/actions/workflows/R-CMD-check.yaml)
[![Codecov test
coverage](https://codecov.io/gh/JasonLocklin/PPackage/branch/master/graph/badge.svg)](https://app.codecov.io/gh/JasonLocklin/PPackage?branch=master)
<!-- badges: end -->

The goal of PPackage is to provide a personal R package of handy
functions and small data sets that can be available to any project I’m
working on.

## Installation

You can install the development version of PPackage from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("JasonLocklin/PPackage", force=TRUE)
#> Downloading GitHub repo JasonLocklin/PPackage@HEAD
#> ── R CMD build ─────────────────────────────────────────────────────────────────
#>      checking for file ‘/private/var/folders/_f/mnsldm313pl88dzjpc5kz3tr0000gq/T/RtmpLZNYxV/remotes4da7f2adb64/JasonLocklin-PPackage-c50eef6/DESCRIPTION’ ...  ✔  checking for file ‘/private/var/folders/_f/mnsldm313pl88dzjpc5kz3tr0000gq/T/RtmpLZNYxV/remotes4da7f2adb64/JasonLocklin-PPackage-c50eef6/DESCRIPTION’
#>   ─  preparing ‘PPackage’:
#>      checking DESCRIPTION meta-information ...  ✔  checking DESCRIPTION meta-information
#>   ─  checking for LF line-endings in source and make files and shell scripts
#>   ─  checking for empty or unneeded directories
#>   ─  building ‘PPackage_0.0.0.9000.tar.gz’
#>      
#> 
```

## Documentation

Full documentation website on: <https://JasonLocklin.github.io/PPackage>

## Documentation

Full documentation website on: <https://JasonLocklin.github.io/PPackage>

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(PPackage)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
#head(schools)
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
