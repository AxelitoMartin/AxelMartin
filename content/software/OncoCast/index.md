---
authors:
- admin
categories:
- R Package
date: "2020-12-01"
draft: false
featured: true
lastmod: ""
projects: []
subtitle: 'Ensemble learner for delayed-entry survival prediction and stratification with high-dimensional data. Developed with multiple machine learning algorithms, multi-threading functionality and interactive components for exploration'
summary: ''
tags:
- R package
- Survival analysis
- Prediction/Stratification
- Genomics
title: 'OncoCast'
weight: 1
---


# `OncoCast` R package

<!-- badges: start -->

[![Travis build
status](https://travis-ci.com/AxelitoMartin/OncoCast.svg?branch=development)](https://travis-ci.org/AxelitoMartin/OncoCast)
[![Codecov test
coverage](https://codecov.io/gh/AxelitoMartin/OncoCast/branch/development/graph/badge.svg)](https://codecov.io/gh/AxelitoMartin/OncoCast?branch=development)
[![DOI](https://zenodo.org/badge/211392347.svg)](https://zenodo.org/badge/latestdoi/211392347)
<!-- badges: end -->

Please find all the package's resources on it's [github repository](https://axelitomartin.github.io/OncoCast).

## An Ensemble Learning Approach for Outcome Prediction in Precision Oncology Setting

Ensemble learner framework for survival outcome prediction and
stratification for high dimension data. Originally developed for cancer
genomics with delayed entry in the risk set in mind, and thus can adjust
for left-truncation. OncoCast enables users to easily perform one or
multiple machine learning survival analyses at once and explore and
visualize the resulting output.

## Installing `OncoCast`

`OncoCast` has some dependencies that will be installed if they are not
found in your library. When installing from github a prompt in the
console may ask if you want to install the binaries for curl v4.0
instead of 3.3. There is no need to update it for the package to work
properly.

``` r
install.packages("remotes")
remotes::install_github("AxelitoMartin/OncoCast")
```

If you wish to use the development version of the package please use:

``` r
remotes::install_github("AxelitoMartin/OncoCast", ref = "development")
```

## Using `OncoCast`

We recommend users to walk through the companion website to this package
before their first use of the method. They will be guided through:

  - [**Generating data in a ready for analysis
    format**](https://axelitomartin.github.io/OncoCast/articles/OncoCast-Data.html)
    where the users will be guided on how to format their data to use
    `OncoCast`.
  - [**Performing an ensemble learning
    run**](https://axelitomartin.github.io/OncoCast/articles/Ensemble-Learner.html)
    through a guide of the different machine learning algorithms
    available and how to create an ensemble model.
  - [**Generating comprehensible
    results**](https://axelitomartin.github.io/OncoCast/articles/Risk-Prediction.html)
    with a tutorial on how to explore the predicted risk score of
    patients in the dataset, the prognostic power of the ensemble model,
    the importance of each feature of interest and how to optimize
    creation of risk groups in clinically meaningful subsets.
  - [**Using web-based interactive
    applications**](https://axelitomartin.github.io/OncoCast/articles/Online-Tools.html)
    to simplify the exploration of results and sharing them
    collaborators.

## `OncoCast` Online

There exist a version of OncoCast completely web-based requiring no
coding skills and minimal inputs to create and explore an ensemble
model. It can be found through this [**online RShiny
application**](https://axelitomartin.shinyapps.io/OncoCast/?_ga=2.133036616.733046146.1606492754-1896886074.1572897510).
The user will only be asked to input the dataset they wish to study and
the method they want to use to create the emsemble model.
