
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rmddmES

## Instalación

Instalar desde github:

``` r
remotes::install_github("anthonySegura/rmddm-es")
```

## Ejemplo

Crea una plantilla RMarkdown con la estructura CRISP-DM:

``` r
library(rmarkdown)
draft("MiReporte.Rmd", template = "crispdm_report_es", package = "rmddmEs", edit=FALSE)
```
