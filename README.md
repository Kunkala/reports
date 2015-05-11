reports
=======

[![Build Status](https://travis-ci.org/trinker/reports.png?branch=master)](https://travis-ci.org/trinker/reports)

reports is a package that assists in writing reports and presentations by providing a frame work that brings together existing R, LaTeX/.docx and Pandoc tools.  The package is designed to be used with [RStudio](http://www.rstudio.com/), [MikTex](http://miktex.org/)/[Tex Live](http://www.tug.org/texlive/)/[LibreOffice](http://www.libreoffice.org/), [knitr](http://yihui.name/knitr/), [slidify](http://ramnathv.github.com/slidify/), [knitcitations](http://www.carlboettiger.info/2012/05/30/knitcitations.html), [Pandoc](http://johnmacfarlane.net/pandoc/) and [pander](https://github.com/rapporter/pander).  The user will want to download these free programs to maximize the effectiveness of the reports package.

<p><a href="http://trinker.github.io/reports/dependencies"><img src="https://dl.dropboxusercontent.com/u/61803503/packages/reports.PNG" alt="Image Not Displayed"></a></p>


## Installation

To download the [development version of reports](http://trinker.github.com/reports_dev/):

download the [zip ball](https://github.com/trinker/reports/zipball/master) or [tar ball](https://github.com/trinker/reports/tarball/master), decompress and run `R CMD INSTALL` on it, or use the **devtools** package to install the development version:

```r
if (!require("pacman")) install.packages("pacman")
pacman::p_load_gh(
    "ramnathv/slidify@dev",
    "ramnathv/slidifyLibraries@dev",
    "rstudio/rmarkdown",
    "trinker/reports"
)
```

Note: Windows users need [Rtools](http://www.murdoch-sutherland.com/Rtools/) and [devtools](http://CRAN.R-project.org/package=devtools) to install this way.

## Help

[Web Page](http://trinker.github.com/reports/)      
[Intoductory Video](http://www.youtube.com/watch?v=ArHQjQyIS70)            
[Quick Start Slides](https://dl.dropboxusercontent.com/u/61803503/Slides/reports/index.html)    
[Package Vignette](http://htmlpreview.github.io/?https://github.com/trinker/reports/blob/master/vignettes/reports_vignette.html)     
[Package PDF Help Manual](https://dl.dropbox.com/u/61803503/reports.pdf)          
[click here](http://trinker.github.io/reports/dependencies) for information on the programs/packages reports brings together     

## Contact

You are welcome to:
* submit suggestions and bug-reports at: <https://github.com/trinker/reports/issues>
* send a pull request on: <https://github.com/trinker/reports/>
* compose a friendly e-mail to: <tyler.rinker@gmail.com>
