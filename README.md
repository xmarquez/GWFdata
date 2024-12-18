
<!-- README.md is generated from README.Rmd. Please edit that file -->

# GWFdata

<!-- badges: start -->
<!-- badges: end -->

GWFdata archives the data used in Wright (2021) and Geddes, Wright, and
Frantz (2018). It also includes a subset of the personalism indicators
in Weeks (2014). The primary purpose of the package is to replicate the
IRT model described in Wright (2021), based on the Stata .do file
archived at the [Political Science Research and Methods
dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/3BC21O).
An article with detailed instructions on how to do this is [included in
this website](GWFdata/articles/replicating-wright-2019.html).

## Installation

You can install the development version of GWFdata from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("xmarquez/GWFdata")
```

## Examples

This is a data-only package. Just type the name of the dataset you want.
The main dataset is `gwf`.

``` r
library(GWFdata)
gwf
#> # A tibble: 4,591 × 140
#>    cowcode  year gwf_country gwf_casename gwf_caseid gwf_case_duration
#>      <dbl> <dbl> <chr>       <chr>             <dbl>             <dbl>
#>  1      40  1953 Cuba        Cuba 52-59           78                 1
#>  2      40  1954 Cuba        Cuba 52-59           78                 2
#>  3      40  1955 Cuba        Cuba 52-59           78                 3
#>  4      40  1956 Cuba        Cuba 52-59           78                 4
#>  5      40  1957 Cuba        Cuba 52-59           78                 5
#>  6      40  1958 Cuba        Cuba 52-59           78                 6
#>  7      40  1959 Cuba        Cuba 52-59           78                 7
#>  8      40  1960 Cuba        Cuba 59-NA           79                 1
#>  9      40  1961 Cuba        Cuba 59-NA           79                 2
#> 10      40  1962 Cuba        Cuba 59-NA           79                 3
#> # ℹ 4,581 more rows
#> # ℹ 134 more variables: gwf_case_fail <dbl>, gwf_startdate <date>,
#> #   gwf_enddate <date>, gwf_fail_subsregime <dbl>, gwf_fail_type <dbl>,
#> #   gwf_fail_violent <dbl>, gwf_prior <chr>, gwf_firstldr <dbl>,
#> #   gwf_leadername <chr>, gwf_leaderid <dbl>, gwf_leader_duration <dbl>,
#> #   gwf_leader_fail <dbl>, gwf_leader_firstyear <dbl>, region <chr>,
#> #   foreignimposd <dbl>, supportparty <dbl>, partyleader <dbl>, …
```

Documentation on the included variables be accessed by typing `?gwf`.

The package also includes the dataset `weeks` and `gwf_irt`. The latter
includes the replicated factor scores and IRT estimates reported in
Wright (2021).

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0">

<div id="ref-geddesHowDictatorshipsWork2018" class="csl-entry">

Geddes, Barbara, Joseph Wright, and Erica Frantz. 2018. *How
Dictatorships Work*. Cambridge: Cambridge University Press.

</div>

<div id="ref-weeksDictatorsWarPeace2014" class="csl-entry">

Weeks, Jessica L. 2014. *Dictators at War and Peace*. Cornell University
Press.

</div>

<div id="ref-wrightLatentCharacteristicsThat2021" class="csl-entry">

Wright, Joseph. 2021. “The Latent Characteristics That Structure
Autocratic Rule.” *Political Science Research and Methods* 9 (1): 1–19.
<https://doi.org/10.1017/psrm.2019.50>.

</div>

</div>
