# Conda Virtual Environments Recipes
*Maciej_Bak  
Swiss_Institute_of_Bioinformatics*

A small collection of YAML recipes for [conda](https://docs.conda.io/en/latest/) virtual environments which I use in everyday's computational work.

## Current recipes

Currently the repository consist of the following recipes:
* [Python3](https://www.python.org/) and [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)
* [Snakemake](https://snakemake.readthedocs.io/en/stable/)
* [Nextflow](https://www.nextflow.io/) together with [nf-core](https://nf-co.re/)
* [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/)
* various tools and libraries related to code formatting and linting (Python, R, bash, C++ and C, Perl)

## How-to: download and install Miniconda3

Linux:
  ```bash
  wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
  bash Miniconda3-latest-Linux-x86_64.sh
  source .bashrc
  ```

## How-to: build and activate environments

In order to build a conda virtual environment please execute script `create-virtual-environment.sh` of a given recipe directory.
The environment will be constructed inside that location under the name `env`. Activate it with:
  ```bash
  conda activate {directory}/env
  ```

## License

MIT License

