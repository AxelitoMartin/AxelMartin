---
authors:
- admin
- Karissa Whiting
- Arshi Arora
- Margaret Hannum
categories:
- R Package
date: "2020-11-01"
draft: false
featured: true
lastmod: ""
projects: []
subtitle: 'A consistent framework for genetic data processing, visualization
and analysis.'
summary: ''
tags:
- R package
- Genomics
- Analytics
title: 'gnomeR'
weight: 2
---


# `gnomeR` R package

<!-- badges: start -->

[![Travis build
status](https://travis-ci.com/AxelitoMartin/gnomeR.svg?branch=development)](https://travis-ci.org/AxelitoMartin/gnomeR)
[![Codecov test
coverage](https://codecov.io/gh/AxelitoMartin/gnomeR/branch/development/graph/badge.svg)](https://codecov.io/gh/AxelitoMartin/gnomeR?branch=development)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4171636.svg)](https://doi.org/10.5281/zenodo.4171636)
<!-- badges: end -->

Please find all the package's resources on it's [github repository](https://axelitomartin.github.io/OncoCast).

## Introduction

The `gnomeR` package provides a consistent framework for genetic data
processing, visualization and analysis. This is primarily targeted to
IMPACT datasets but can also be applied to any genomic data provided by
CbioPortal.

  - [**Dowloading and gathering data from
    CbioPortal**](https://github.com/karissawhiting/cbioportalr) through
    an integrated API using simply the sample IDs of the samples of
    interests or the name of the study to retrive all samples in that
    study. A separate package `cbioportalr` was developed independently.
  - [**Processing genomic
    data**](https://axelitomartin.github.io/gnomeR/articles/Data-processing.html)
    retrieved for mutations (MAF file), fusions (MAF file) and
    copy-number alterations (and when available segmentation files) into
    an analysis ready format.
  - [**Visualization of the processed
    data**](https://axelitomartin.github.io/gnomeR/articles/Visualizations.html)
    provided through MAF file summaries, OncoPrints and heatmaps.
  - [**Analyzing the processed
    data**](https://axelitomartin.github.io/gnomeR/articles/Analizing-genomic-data.html)
    for association with binary, continuous and survival outcome.
    Including further visualiztion to improve understanding of the
    results.

## Installation

You can install `gnomeR` from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("AxelitoMartin/gnomeR")
```

Similarly for those who wish to explore the development version of
`gnomeR`:

``` r
devtools::install_github("AxelitoMartin/gnomeR", ref = "development")
```

Along with its companion package for cbioPortal data download:

``` r
devtools::install_github("karissawhiting/cbioportalr")
```
