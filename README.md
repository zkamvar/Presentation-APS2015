# Evidence for at least two introductions of the sudden oak death pathogen into Oregon forests

[**PDF of presentation**](https://github.com/zkamvar/Presentation-APS2015/blob/master/beamer_presi/Kamvar_2015-08-02_APS.pdf)

## About

This repository contains code for my presentation on August 2nd, 2015 at the 
American Phytopathological Society annual conference in Pasadena, CA. This is
rendered via the R package knitr and requires the [Sudden Oak Death In Oregon 
Forests repository](https://github.com/zkamvar/Sudden_Oak_Death_in_Oregon_Forests)
to work. The file `beamer_presi/session_information.txt` contains the 
information about packages used for this presentation.

At th current moment, this is not complete. I will add more detailed notes for
the slides.

## Setup

You will need LaTeX and a few R packages for this to work correctly.

```r
# install these packages
install.packages(c("knitr", "devtools", "dplyr", "ggmap", "cowplot", "rgdal", "poppr"))
devtools::install_github("zkamvar/Sudden_Oak_Death_in_Oregon_Forests/PramCurry")
```
Make sure to change the 9th line in the first R chunk in `beamer\_presi/Kamvar\_2015-08-02\_APS.Rnw` to the correct path of the Sudden Oak Death Repository.

You should be able to render this to PDF in Rstudio.

