# bat2bat

[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/folkehelseprofil/bat2bat?branch=master&svg=true)](https://ci.appveyor.com/project/folkehelseprofil/bat2bat)

Denne R pakke er en shinyApp som brukes til for � sammenlikne batch filer.
Online versjon er tilgjengelig [https://fhprofil.shinyapps.io/bat2bat/](Shinyapps.io)

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
