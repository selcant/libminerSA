
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminerSA

<!-- badges: start -->
<!-- badges: end -->

The goal of libminerSA is to …

## Installation

You can install the development version of libminerSA from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("selcant/libminerSA")
```

## Example

To get a count of installed packages in each of your library locations
use the `lib_summary()` function:

``` r
library(libminerSA)
## basic example code
lib_summary()
#>                                                                                        Library
#> 1                        /Library/Frameworks/R.framework/Versions/4.3-x86_64/Resources/library
#> 2 /private/var/folders/wq/cd6p77z56bd7x_n52qc8yk81kxjmtr/T/RtmpJVC452/temp_libpath3d1e7644d56a
#> 3                                                   /Users/aydins/Library/R/x86_64/4.3/library
#>   n_packages
#> 1         29
#> 2          1
#> 3        153
```
