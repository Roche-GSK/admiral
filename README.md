<!-- Please do not edit the README.md file as it is auto-generated. Only edit the README.Rmd file -->

# admiraldev - ADaM in R Asset Library Development Utilities

<img src="man/figures/admiraldev.png" align="right" width="200" style="margin-left:50px;"/>

<!-- badges: start -->

[<img src="http://pharmaverse.org/shields/admiral.svg">](https://pharmaverse.org)
[![CRAN
status](https://www.r-pkg.org/badges/version/admiral)](https://CRAN.R-project.org/package=admiral)
[![R-CMD-check](https://github.com/pharmaverse/admiraltemplate/actions/workflows/R-CMD-check.yml/badge.svg)](https://github.com/pharmaverse/admiraltemplate/actions/workflows/R-CMD-check.yml)
[![Test
Coverage](https://raw.githubusercontent.com/pharmaverse/admiraltemplate/badges/main/test-coverage.svg)](https://github.com/pharmaverse/admiraltemplate/actions/workflows/code-coverage.yml)

<!-- badges: end -->

## Purpose

Tools for developing functions and maintaining a healthy codebase within
the family of admiral R packages.

## Installation

The package is available from CRAN and can be installed by running
`install.packages("admiral")`.

To install the latest development version of the package directly from
GitHub use the following code:

```
if (!requireNamespace("remotes", quietly = TRUE)) {
  install.packages("remotes")
}

remotes::install_github("pharmaverse/admiral.test", ref = "devel") # This is a required dependency of {admiral}
remotes::install_github("pharmaverse/admiral", ref = "devel")
remotes::install_github("pharmaverse/admiraldev", ref = "devel")
```
