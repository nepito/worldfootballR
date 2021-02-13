
<!-- README.md is generated from README.Rmd. Please edit that file -->

# worldfootballR <img src="man/figures/logo.png" align="right" width="181" height="201"/>

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/JaseZiv/worldfootballR.svg?branch=main)](https://travis-ci.org/JaseZiv/worldfootballR)
[![codecov](https://codecov.io/gh/JaseZiv/worldfootballR/branch/main/graph/badge.svg?token=WGLU5J34VL)](https://codecov.io/gh/JaseZiv/worldfootballR)
<!-- badges: end -->

## Overview

This package is designed to allow users to extract various world
football results and player statistics data from fbref.com and
valuations and transfer data from transfermarkt.com.

## Installation

You can install the `worldfootballR` package from github with:

``` r
# install.packages("devtools")
devtools::install_github("JaseZiv/worldfootballR")
```

``` r
library(worldfootballR)
```

-----

## Usage

Package vignettes have been built to help you get started with the
package.

  - For match-level data, see
    [here](https://jaseziv.github.io/worldfootballR/articles/extract-match-data.html)
  - For season-level data, see
    [here](https://jaseziv.github.io/worldfootballR/articles/extract-season-data.html)
  - for transfer histories and player market valuations, see
    [here](https://jaseziv.github.io/worldfootballR/articles/extract-valuation-data.html)

-----

## Leagues and Seasons

For fbref.com data (match and season data), a list of leagues and
seasons included in the package can be found in the
`worldfootballR_data` repository and can be found
[here](https://github.com/JaseZiv/worldfootballR_data/blob/master/raw-data/league_seasons/all_tier1_season_URLs.csv)

For transfermarkt.com data (valuations and transfers), a list of leagues
and seasons included in the package can be found in the
`worldfootballR_data` repository and can be found
[here](https://github.com/JaseZiv/worldfootballR_data/blob/master/raw-data/transfermarkt_leagues/main_comp_seasons.csv)

-----

## Contributing

### Issues and Improvements

When creating an issue, please include:

  - Reproducible examples
  - A brief description of what the expected results are
  - If applicable, the fbref.com or transfermarkt.com page the observed
    behaviour is occuring on
  - For improvements, what addiditional features are being requested and
    what problem they will help solve

### Pull Requests

Pull requests are also welcomed. Before doing so, please create an issue
or email me with your idea.

Feel free to get in touch via email or twitter
<https://twitter.com/jaseziv>
