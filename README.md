Regions of the World
================
*Louis du Plessis*
*Last modified: 19 Apr 2020*

This is a list of admin regions of the world, for easy reference and
automatic parsing of epidemiological and genetic data.

The data were extracted from the [GADM v3.6
database](https://gadm.org/data.html)

The list includes the following divisions:

  - admin0: Country level
  - admin1: Province/state/region level
  - admin2: County/prefecture/district level
  - admin3: …
  - admin4: …
  - admin5: …

Note that higher-level divisions are only present for some countries.

The outputs are stored in `data/admin_*.csv` and
`data/admin_*_ascii.csv` (no diacritics). The script also produces
`data/world_*.csv` files (not on the Github repository) that are direct
csv dumps from the shape files (contain a few extra fields).

## Admin 0

Extracting admin0 regions…

256 admin0 regions successfully extracted.

## Admin 1

Extracting admin1 regions…

3486 admin1 regions extracted from 228 admin0 regions.

## Admin 2

Extracting admin2 regions…

41533 admin2 regions extracted from 2751 admin1 and 166 admin0 regions.

## Admin 3

Extracting admin3 regions…

115437 admin3 regions extracted from 17701 admin2, 1216 admin1 and 65
admin0 regions.

## Admin 4

Extracting admin4 regions…

105470 admin4 regions extracted from 18219 admin3, 1965 admin2, 285
admin1 and 20 admin0 regions.

## Admin 5

Extracting admin4 regions…

40683 admin5 regions extracted from 5196 admin4, 731 admin3, 126 admin2,
18 admin1 and 2 admin0 regions.

## Session info

    ## R version 3.5.3 (2019-03-11)
    ## Platform: x86_64-apple-darwin15.6.0 (64-bit)
    ## Running under: macOS Mojave 10.14.6
    ## 
    ## Matrix products: default
    ## BLAS: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRblas.0.dylib
    ## LAPACK: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRlapack.dylib
    ## 
    ## locale:
    ## [1] en_GB.UTF-8/en_GB.UTF-8/en_GB.UTF-8/C/en_GB.UTF-8/en_GB.UTF-8
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## other attached packages:
    ## [1] stringi_1.4.3 rgdal_1.4-8   sp_1.3-2     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] compiler_3.5.3  magrittr_1.5    tools_3.5.3     htmltools_0.3.6
    ##  [5] yaml_2.2.0      Rcpp_1.0.3      rmarkdown_1.12  grid_3.5.3     
    ##  [9] knitr_1.22      stringr_1.4.0   xfun_0.6        digest_0.6.23  
    ## [13] lattice_0.20-38 evaluate_0.13
