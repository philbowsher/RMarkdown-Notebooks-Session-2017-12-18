# Intro to R Markdown Notebooks

Live Presentation is here:

https://beta.rstudioconnect.com/content/3194/

Other apps and reports are here:

Requires the following packages from CRAN:

```r
install.packages(c("leaflet", "shiny", "shinydashboard", "rmarkdown", "flex_dashboard", "ggplot2", "plotly", "plyr", "reshape2"))
``` 

To access to the OpenFDA API from R, which uses the jsonlite and magrittr packages, you'll need the devtools package to install it as the library has not yet been added to CRAN, so follow these steps:

```r
install.packages("devtools")
```

Once devtools is installed, you can grab this package:

```r
library("devtools")
devtools::install_github("ropenhealth/openfda")
```
Load it in like any other package:

```r
library("openfda")
```

An up-to-date version of RStudio is also recommended.

R 3.2.5 used for examples.

## **R Markdown**

http://rmarkdown.rstudio.com/
  
    R Markdown provides an authoring framework for data science and documents are fully reproducible and support dozens of static and dynamic output formats.