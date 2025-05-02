# SO-IAA School on Bayesian Statistics, Granada 2025

This repo contains materials and notebooks for the Bayesian statistics school in Granada in May of 2025. 

## Lecturers
* Gwen Eadie
* Daniela Huppenkothen

## Required Software Installation

The exercises in this school will be available in both python notebooks (all), and in R markdown (some). Although not required, this is an opportunity to learn some R if you are curious about it. The *R Statistical Software* is the software of choice for applied statisticians, both in industry and academia. It is especially predominant in fields such as biostatistics, biology, and ecology (academia and industry), and in industries like banking, finance, actuarial science, insurance, and healthcare.

Below we have given instructions on what packages and installation requirements are needed for the python notebooks and R markdown documents. 
### Python Packages and Environment

Most of the required Python packages are available in the file `sw_requirements.txt` in this repository. If you're using some version of conda (I'd recommend [`miniforge`](https://github.com/conda-forge/miniforge), which ensures that you get all your packages through open-source channels and are not dependent on Anaconda's somewhat arcane use policies), you can easily generate a new environment with the packages in that file using

```
conda create --name bayes_school --file sw_requirements.txt  
```

and then activate it with 

```
conda activate bayes_school
```

Once you've done that, you'll need to install a few packages that are not available through conda. First, you'll need to install `pytorch`, wwhich you can do with

```
pip install torch==2.6.0 torchvision==0.21.0 torchaudio==2.6.0
```

From here, your python environment should be ready to go!

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

