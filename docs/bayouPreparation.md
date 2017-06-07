# *bayou* Workshop Preparation
#### Instructor: Josef C Uyeda (josef.uyeda@gmail.com)
***

Before you arrive, please try installing the following software (including verifying they are the appropriate versions!).

### Required Software

1. **R** ([Download page](https://cran.r-project.org/))

    + Please update R to the latest version (at least R 3.3.0 or later). Older versions of R may cause issues during the workshop.
 
2. **Rstudio** ([Download page](https://www.rstudio.com/products/rstudio/download/))

    + I will be using Rstudio to lead this workshop, and I **strongly** recommend you use it too. In particular, we I will be demonstrating code using [R markdown](http://rmarkdown.rstudio.com/) and [R notebooks](http://rmarkdown.rstudio.com/r_notebooks.html). ***R Notebooks are only available in version 1.0 or higher of RStudio***
    
### Install Rtools if using Windows

1. **Rtools** ([Download page](https://cran.r-project.org/bin/windows/Rtools/))

    + If you are on Windows, you will need Rtools to properly compile and install *bayou*. Please make sure that your version of Rtools matches the version of R you are currently running. 
    
### Install Xcode if using Mac OSX

1. **XCode** ([Installation instructions](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/))

    + If you are using Mac OSX, you will need to make sure you have Xcode to properly compile and install *bayou*. 
    
### Install R Packages

1. Run the following code in R to install the packages. ***Do this before coming to the workshop*** as installation can take a while, and it's possible you may hit some snags. 
```
install.packages("devtools") # Required
install.packages("geiger") # Required
install.packages("phytools") # Required
install.packages("knitr") # Required
install.packages("rprojroot") # Required
install.packages("rmarkdown") # Required
install.packages("foreach") # Optional
install.packages("doParallel") # Optional
install.packages("treeplyr") # Optional
devtools::install_github("uyedaj/bayou", ref="dev") ## Note: Not CRAN version
```
Make sure that *bayou* has installed without errors. 

### Optional Software

1. **git** ([Download page](https://help.github.com/articles/set-up-git/))

    + git will allow you to easily clone the directory with workshop materials. 

***
***

