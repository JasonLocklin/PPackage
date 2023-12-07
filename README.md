
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
devtools::install_github("JasonLocklin/PPackage")
#> Downloading GitHub repo JasonLocklin/PPackage@HEAD
#> ── R CMD build ─────────────────────────────────────────────────────────────────
#>      checking for file ‘/private/var/folders/_f/mnsldm313pl88dzjpc5kz3tr0000gq/T/RtmpMp5efw/remotes214f4d64b535/JasonLocklin-PPackage-434b82a/DESCRIPTION’ ...  ✔  checking for file ‘/private/var/folders/_f/mnsldm313pl88dzjpc5kz3tr0000gq/T/RtmpMp5efw/remotes214f4d64b535/JasonLocklin-PPackage-434b82a/DESCRIPTION’
#>   ─  preparing ‘PPackage’:
#>      checking DESCRIPTION meta-information ...  ✔  checking DESCRIPTION meta-information
#>   ─  checking for LF line-endings in source and make files and shell scripts
#>   ─  checking for empty or unneeded directories
#>   ─  creating default NAMESPACE file
#>   ─  building ‘PPackage_0.0.0.9000.tar.gz’
#>      
#> 
```

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
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
