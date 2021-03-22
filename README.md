
<!-- README.md is generated from README.Rmd. Please edit that file -->

# camapping

<!-- badges: start -->

<!-- badges: end -->

camapping is a collection of commonly used vector data in California.

## Installation

You can install the released version of camapping from GitHub with:

``` r
remotes::install_github("ir-sfsu/camapping")
```

## Counties

``` r
library(camapping)
library(mapview)
mapview(counties)
```

<img src="man/figures/README-unnamed-chunk-2-1.png" width="100%" />

## Cities

``` r
mapview(cities)
```

<img src="man/figures/README-unnamed-chunk-3-1.png" width="100%" />

## Schools

``` r
mapview(schools)
```

<img src="man/figures/README-unnamed-chunk-4-1.png" width="100%" />

## Regions

``` r
mapview(regions)
```

<img src="man/figures/README-unnamed-chunk-5-1.png" width="100%" />
