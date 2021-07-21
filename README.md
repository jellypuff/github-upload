# shiny-apps

Examples taken from the ***Shiny in Seven Lessons*** section of the [Shiny Tutorial](https://shiny.rstudio.com/tutorial/) page and both accessible from:

* [**Census App**](https://jellypuff.shinyapps.io/census-app/)
* [**StockVis**](https://jellypuff.shinyapps.io/stockvis/)

## Running in RStudio: ##

An example of how to run a shiny app from this repository in RStudio, just replace the `subdir` argument with the relevant folder name for other apps:  

```
shiny::runGitHub(repo = "shiny-apps", username = "jellypuff",  ref = "main", subdir = "census-app")
```
