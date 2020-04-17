# Mexico Datasets - R Package 🇲🇽

The R package datosmx 🇲🇽.

I am in process of building an R package to get data about the Novel Coronavirus COVID-19 pandemic cases in Mexico and other datasets.

* Data comes from official sources, more information [here](https://github.com/mayrop/datos-covid19in-mx)

**Warning:** This package is under construction!! 🚧 🚧 🚧 

## Installation
```R
if (!"remotes" %in% installed.packages()) {
  install.packages("remotes")
}
remotes::install_github("mayrop/datosmx")
```

##  Contributing

### How to perform static code analysis and style checks
Configuration for lintr is in `.lintr` file. Lints are treated as warnings, but we strive to be lint-free.

In RStudio, you can run lintr from the console as follows:

```R
> lintr::lint_package()
> library(roxygen2)
> library("devtools")
> devtools::document()
```

### License
This package is free and open source software, licensed under GPL.

