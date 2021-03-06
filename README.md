
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Welcome to the soundscapeR Tutorial

## 1. Installing the tutorial

  
**To install this tutorial for the [soundscapeR]() R-package, please
run:**  
  

``` r
devtools::install_github(repo = "ThomasLuypaert/soundscapeR.tutorial")
```

  

## 2. Running the tutorial

  
**Once the package installed, load the package using:**  
  

``` r
library(soundscapeR.tutorial)
```

  
**Finally, to run the tutorial, use:**  
  

``` r
shiny_args <- list(launch.browser = getOption("shiny.launch.browser", interactive()))

learnr::run_tutorial(name = "soundscapeR_tutorial", package = "soundscapeR.tutorial", shiny_args = shiny_args)
```

## 3. The accompanying slides

  
If you’re interested in the slide deck that accompanies this tutorial,
you can find the slides on Part I: Collecting acoustic data using
AudioMoth
[here](https://docs.google.com/presentation/d/1NtVe3vXpoF1uVDwj0k0U8TbBa1LmwTGKGmA4fEmlW6I/edit?usp=sharing),
and the slides on Part II: A soundscape approach to analysing big
acoustic data
[here](https://docs.google.com/presentation/d/1yU6hUVBs7OeNlraAe8xGulqO2Yp4gFCd88asXrzaZFM/edit?usp=sharing).
