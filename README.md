# bat2bat

 <!-- badges: start -->
[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/folkehelseprofil/bat2bat?branch=master&svg=true)](https://ci.appveyor.com/project/folkehelseprofil/bat2bat)
[![Travis build status](https://travis-ci.org/folkehelseprofil/bat2bat.svg?branch=master?style=flat-square&label=TravisCI)](https://travis-ci.org/folkehelseprofil/bat2bat)
[![Codecov test coverage](https://codecov.io/gh/folkehelseprofil/bat2bat/branch/master/graph/badge.svg)](https://codecov.io/gh/folkehelseprofil/bat2bat?branch=master)
 <!-- badges: end -->


Denne R pakke er en shinyApp som brukes til for � sammenlikne batch filer.
Online versjon er tilgjengelig p� [shinyapps.io](https://fhprofil.shinyapps.io/bat2bat/)

## Installasjon

For � installere pakken, kan f�lgende kode kj�res i R:

```r
if (!require("remotes")) install.package("remotes")
remotes::install_github("folkehelseprofil/bat2bat", dependencies=TRUE)
```

Hvis installasjon mislykkes b�r du starte opp R eller RStudio p� nytt og kj�r komandoen p� nytt.

## Bruk

Pakken m� f�rst lasteopp i R og funksjon `run_app()` brukes for � aktivere appen.

```r
library(bat2bat)
run_app()

```
