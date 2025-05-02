# SO-IAA School on Bayesian Statistics, Granada 2025

This repo contains materials and notebooks for the Bayesian statistics school in Granada in May of 2025. 

## Lecturers
* Gwen Eadie
* Daniela Huppenkothen

## Pre-requisites
TBD

## Required Software Installation

The exercises in this school will be available in both python notebooks (all), and in R markdown (some). Although not required, this is an opportunity to learn some R if you are curious about it. The *R Statistical Software* is the software of choice for applied statisticians, both in industry and academia. It is especially predominant in fields such as biostatistics, biology, and ecology (academia and industry), and in industries like banking, finance, actuarial science, insurance, and healthcare.

Below we have given instructions on what packages and installation requirements are needed for the python notebooks and R markdown documents. 
### Python Packages and Environment

### R Statistical Software and packages

**Step 1:** Follow the instructions [here](https://ftp.cixug.es/CRAN/) to download the *R Statistical Software* for your operating system

**Step 1a (if you're on Windows):** Install Rtools [here](https://cran.r-project.org/bin/windows/Rtools/rtools45/rtools.html)

**Step 2 (if you want to learn how to use R):** Follow the instructions [here](https://posit.co/download/rstudio-desktop/) to download R Studio 

**Step 3:** Open up R (either in a console or in R Studio), and install the following packages using the command `install.packages("nameofpackage")`:

- `brms`
- `visreg`
- `ggplot2`
- `tidyverse`
- `tidybayes`

  For example, running `install.packages("brms")` will install the brms package.

**Step 4:** To _use_ the package in R (or R Studio), run the command e.g., `library(brms)`. You need to run the `library` function for a package each time you open up R. But once you have loaded it within a session, you do not need to load it again.

