
<!-- README.md is generated from README.Rmd. Please edit that file -->

# test2022

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![BioC
status](http://www.bioconductor.org/shields/build/release/bioc/test2022.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/test2022)
[![R-CMD-check-bioc](https://github.com/jemilianosf/test2022/workflows/R-CMD-check-bioc/badge.svg)](https://github.com/jemilianosf/test2022/actions)
[![Codecov test
coverage](https://codecov.io/gh/jemilianosf/test2022/branch/master/graph/badge.svg)](https://codecov.io/gh/jemilianosf/test2022?branch=master)
<!-- badges: end -->

The goal of `test2022` is to …

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `test2022` using from
[Bioconductor](http://bioconductor.org/) the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("test2022")
```

And the development version from
[GitHub](https://github.com/jemilianosf/test2022) with:

``` r
BiocManager::install("jemilianosf/test2022")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("test2022")
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
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub\!

## Citation

Below is the citation output from using `citation('test2022')` in R.
Please run this yourself to check for any updates on how to cite
**test2022**.

``` r
print(citation('test2022'), bibtex = TRUE)
#> 
#> To cite package 'test2022' in publications use:
#> 
#>   Emi Sotelo (2021). test2022: Tests for minicourse package.. R package
#>   version 0.99.0. https://github.com/jemilianosf/test2022
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {test2022: Tests for minicourse package.},
#>     author = {Emi Sotelo},
#>     year = {2021},
#>     note = {R package version 0.99.0},
#>     url = {https://github.com/jemilianosf/test2022},
#>   }
```

Please note that the `test2022` was only made possible thanks to many
other R and bioinformatics software authors, which are cited either in
the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the `test2022` project is released with a [Contributor
Code of Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.

## Development tools

  - Continuous code testing is possible thanks to [GitHub
    actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
    through *[usethis](https://CRAN.R-project.org/package=usethis)*,
    *[remotes](https://CRAN.R-project.org/package=remotes)*, and
    *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)*
    customized to use [Bioconductor’s docker
    containers](https://www.bioconductor.org/help/docker/) and
    *[BiocCheck](https://bioconductor.org/packages/3.12/BiocCheck)*.
  - Code coverage assessment is possible thanks to
    [codecov](https://codecov.io/gh) and
    *[covr](https://CRAN.R-project.org/package=covr)*.
  - The [documentation website](http://jemilianosf.github.io/test2022)
    is automatically updated thanks to
    *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
  - The code is styled automatically thanks to
    *[styler](https://CRAN.R-project.org/package=styler)*.
  - The documentation is formatted thanks to
    *[devtools](https://CRAN.R-project.org/package=devtools)* and
    *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.12/biocthis)*.
