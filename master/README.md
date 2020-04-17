# Resources for PS209 - Installing `JAGS to` use with `R` 

Caleb Ziolkowski
9/25/2019

Here I've gathered a few things together for our `R` review session. Please have a look through this document to make sure you're ready and we can avoid spending most of our time on installation issues. 

## Installing `R`/`RStudio`

The first order of business is to make sure you have `R` and `RStudio` up and running. If you do not have these set up, do the following, in order.
1. Install `R`.
2. Install `RStudio`.

### Install `R`

**For Windows:** 
1. Download the binary setup file for `R` [here](https://cran.r-project.org/bin/windows/base/).
2. Open the downloaded `.exe` file and Install `R`.

**For Mac:** 
1. Download the appropriate version of `.pkg` file [here](https://cran.r-project.org/bin/macosx/).
2. Open the downloaded `.pkg` file and Install `R`.

**For Linux:**
1. For a complete `R` system installation, try [this](https://cran.r-project.org/bin/linux/ubuntu/README).
2. For Ubuntu with Apt-get installed, execute _sudo apt-get install r-base_ in terminal.

### Install `RStudio`

Go [here](https://rstudio.com/products/rstudio/download/) and get the right installer for your platform. Run the downloaded installer, following the instructions. Open `RStudio` and make sure everything seems kosher. In the `Console` type something like 

```
rnorm(5)
```

to confirm that things are probably as they should be. 

## Install some packages

There are a few different packages that will show up in the review session. I suggest you install them ahead of time. Priority should be given to `tidyverse`.
