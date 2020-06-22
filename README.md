
# R Markdown templates for Classes

<!-- badges: start -->
<!-- badges: end -->

This package provides Rmarkdown templates for classes. It is based off the "MonashEBSTemplates" package for use at Monash University, Department of Econometrics & Business Statistics.

It contains

 * Monash EBS working paper template
 * Monash letter template
 * Monash exam template
 * Monash consulting report template
 * Monash beamer slides (for the Monash Business School)
 * Memo template (nothing to do with Monash, but a nice format)

The `slides()` function is actually a wrapper to use the `monash` template in the [`binb`](https://github.com/eddelbuettel/binb) package.


## Installation


The package can be installed by:

``` r
# install.packages("remotes")
remotes::install_github("ebmwhite/ClassTemplates")
```

## Usage from RStudio

After installation, restart your RStudio then go to File > New File > R Markdown > From Template. Select the template from the list and click OK. It should create a folder (if any external dependencies) and a Rmd file.
