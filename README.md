[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip) [![Travis build status](https://travis-ci.org/maelle/ghrecipes.svg?branch=master)](https://travis-ci.org/maelle/ghrecipes) [![Build status](https://ci.appveyor.com/api/projects/status/8bh3hpjevms1rni0?svg=true)](https://ci.appveyor.com/project/ropensci/ghrecipes)
 [![Coverage status](https://codecov.io/gh/maelle/ghrecipes/branch/master/graph/badge.svg)](https://codecov.io/github/maelle/ghrecipes?branch=master)



# ghrecipes

The goal of ghrecipes is to provide helper functions for usual GitHub _data mining_ tasks, well at least the ones that are usual or useful for us. :smile_cat:

It uses[ GitHub V4 API](https://developer.github.com/v4/) queried thanks to the [`ghql` package](https://github.com/ropensci/ghql). Read more about [GitHub V4 API advantages here](https://developer.github.com/v4/#why-is-github-using-graphql). It then formats results using the [`jqr` package](https://github.com/ropensci/jqr), interface to [jq](https://stedolan.github.io/jq/). Read an intro to `jqr` power [here](http://www.carlboettiger.info/2017/12/11/data-rectangling-with-jq/). :rocket:

## Installation

You can install ghrecipes from GitHub with:


``` r
# install.packages("devtools")
devtools::install_github("maelle/ghrecipes")
```

## Notes on use

* `ghql` creates a client on load, called `ghql_gh_cli`.

* See a very basic use case [here](http://www.masalmon.eu/2018/03/04/hrbrpkgs/).
