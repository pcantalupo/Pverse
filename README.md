
# Pverse

Meta package that installs my commonly used packages

## Installation

You can install Pverse from [GitHub](https://github.com/) with:

``` r
remotes::install_github("pcantalupo/Pverse", upgrade = "never")
```

If you get warnings about gfortran not found like `ld: warning: search path '/opt/gfortran/lib/gcc/x86_64-apple-darwin20.0/12.2.0' not found`, install the packages manually:

``` r
BiocManager::install(c("edgeR", "scmap", "scran"))
```

