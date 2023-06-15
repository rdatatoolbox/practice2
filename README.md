
<!-- README.md is generated from README.Rmd. Please edit that file -->

## :mortar_board: Practice 2 - Rmarkdown

<!-- badges: start -->

[![License:
GPL-2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
<!-- badges: end -->

Structure of the research compendium of the [practice
2](https://rdatatoolbox.github.io/ex-rmarkdown.html) of the training
course [**Reproducible Research in Computational
Ecology**](https://rdatatoolbox.github.io/).

### Content

This repository is structured as follow:

- [`data/`](https://github.com/rdatatoolbox/practice2/tree/main/data):
  contains all raw data required to perform analyses

- [`R/`](https://github.com/rdatatoolbox/practice2/tree/main/R):
  contains R functions developed especially for this project

- [`man/`](https://github.com/rdatatoolbox/practice2/tree/main/man):
  contains help files of R functions

- [`DESCRIPTION`](https://github.com/rdatatoolbox/practice2/tree/main/DESCRIPTION):
  contains project metadata (author, date, dependencies, etc.)

- [`index.Rmd`](https://github.com/rdatatoolbox/practice2/tree/main/index.Rmd):
  contains the entire analysis

- [`make.R`](https://github.com/rdatatoolbox/practice2/tree/main/make.R):
  main R script to run the entire project by rendering the
  [`index.Rmd`](https://github.com/rdatatoolbox/practice2/tree/main/index.Rmd)

### Usage

Fork and clone the repository, open R/RStudio and run:

``` r
source("make.R")
```

The final result is
[`index.html`](https://github.com/rdatatoolbox/practice2/tree/main/index.html)
and it is available online
[here](https://rdatatoolbox.github.io/practice2).

### Notes

- All required packages, listed in the `DESCRIPTION` file, will be
  installed (if necessary)
- All required packages and R functions will be loaded

### How to cite

> Casajus N, Bonnici I, Dray S, Gimenez O, Guéry L, Guilhaumon F,
> Schiettekatte NMD & Siberchicot A (2023) Workshop FRB-CESAB & RT
> EcoStat: Reproducible Research in Computational Ecology. Zenodo.
> <http://doi.org/10.5281/zenodo.4262978>.
