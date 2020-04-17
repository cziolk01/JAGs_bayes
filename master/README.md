# Resources for PS209 - Installing `JAGS to` use with `R` 

Caleb Ziolkowski
9/25/2019

Here I've gathered a few things together to get `JAGS` up and running. 

## Installing `R`/`RStudio`

Hopfeully this is old news. But if you haven't done this, here are some directions.

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

## Install `JAGS`

This will depend a bit on your operating system. If your using Linux, try to figure it out on your own. My prior is that you would like this task. 

**For Windows:**

You can download the correct `.exe` file [here](https://sourceforge.net/projects/mcmc-jags/files/JAGS/4.x/Windows/). Note, you need to be sure to grab the right one, depending on your version of `R`. On starting `R` or `RStudio`, the console will display the current version. Likewise you can type `version` into the console and return. Quoted from the download site:

> Two binary packages are available for the latest release, JAGS 4.2.0. If
you are using R to interface with JAGS then you must ensure that you
download the correct binary: \
\
> If you are using R 3.3.0 or later then install JAGS-4.2.0-Rtools33.exe \
> If you are using R 3.2.4 or earlier then install JAGS-4.2.0.exe \
\
> For more details, see:
https://martynplummer.wordpress.com/2016/04/05/new-windows-binary-for-r-3-3-0/

**For Mac:**

## Install some packages

### General packages you will probably see me use

There are a few different packages that I will use almost all the time in `R`: `tidyverse` and `magrittr`. If you want to use these (and you should, expecially `tidyverse`), use the commands

```
install.packages('tidyverse')
install.packages('magrittr')
```

### `rjags` is how I will pass models to `JAGS` from `R`

