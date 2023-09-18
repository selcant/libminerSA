
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminerSA

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package created as a part of a workshop and not meant for
serious use.

## Installation

You can install the development version of libminerSA from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("selcant/libminerSA")
```

## Example

To get a count of installed packages in each of your library locations,
optionally with the total sizes, use the `lib_summary()` function:

``` r
library(libminerSA)
lib_summary()
#>                                                                                        Library
#> 1                        /Library/Frameworks/R.framework/Versions/4.3-x86_64/Resources/library
#> 2 /private/var/folders/wq/cd6p77z56bd7x_n52qc8yk81kxjmtr/T/RtmpxkkxxR/temp_libpath69a115f099b2
#> 3                                                   /Users/aydins/Library/R/x86_64/4.3/library
#>   n_packages
#> 1         29
#> 2          1
#> 3        153
# specify `sizes = TRUE` to calculate the total size on disk of your packages
lib_summary(sizes = TRUE)
#>                                                                                        Library
#> 1                        /Library/Frameworks/R.framework/Versions/4.3-x86_64/Resources/library
#> 2 /private/var/folders/wq/cd6p77z56bd7x_n52qc8yk81kxjmtr/T/RtmpxkkxxR/temp_libpath69a115f099b2
#> 3                                                   /Users/aydins/Library/R/x86_64/4.3/library
#>   n_packages  lib_size
#> 1         29  73048407
#> 2          1     14575
#> 3        153 422059116
```
