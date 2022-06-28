
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Welcome to the soundscapeR Tutorial

To install and run the tutorial, follow the instructions below:  
  

**To install this tutorial for the [soundscapeR]() R-package, please
run:**  
  

``` r
devtools::install_github(repo = "ThomasLuypaert/soundscapeR.tutorial")
```

  
**Once the package installed, load the package using:**  
  

``` r
library(soundscapeR.tutorial)
```

  
**Finally, to run the tutorial, use:**  
  

``` r
shiny_args <- list(launch.browser = getOption("shiny.launch.browser", interactive()))

learnr::run_tutorial(name = "soundscapeR_tutorial", package = "soundscapeR.tutorial", shiny_args = shiny_args)
```
