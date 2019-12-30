# Analyzing High-Order Epistasis from Genotype-Phenotype Maps using 'epistasis' Package
**Junyi Chen and Ka-Chun Wong**

This repository contains Jupyter notebooks that reproduce the results and analysis in the protocol chapter: "Analyzing High-Order Epistasis from Genotype-Phenotype Maps using 'epistasis' Package". It is a step-by-step guide to apply the package in supplementary to the out-of-dated official API documentation.
Methods and data are provided in the avaliability of the original paper "Detecting High-Order Epistasis in Nonlinear Genotype-Phenotype Maps." published in Genetics, March 2017.

See the original paper [here](http://www.genetics.org/content/205/3/1079)
and data [here](https://github.com/harmslab/notebooks-nonlinear-highorder-epistasis).

## Download and Install

If you'd like to run the notebooks locally, clone this repository and make sure you have all the necessary dependencies are installed and are running Python 3. Here's a list of everything you'll need:

```
epistasis==0.7.1
gpmap==0.6.1
notebook
ipython
numpy
scipy
sklearn
matplotlib
ipywidgets
```

All packages can be installed using `pip`.

## Data formats

The following formats are used in to create all data, metadata, and figures for the paper. The point of listing them is the provide documentation for anyone interested in sifting through through the data.

- Experimental data, and final results are saved in JSON format (`.json` files). This makes the data easily accessible to basically any programming language -- an attempt to practice true reproducibility. Also, this format is fairly human-readable.
- Data, analysis, raw-figures, code, etc. were all done in Jupyter Notebooks saved as `.ipynb` files. Guaranteed to work with Python 3.

## Table of Contents
- [Figure 1](figures-notebooks/powertransform.ipynb):  **Experimental genotype-phenotype maps exhibit nonlinear phenotypes.**
- [Figure 2](figures-notebooks/highorder.ipynb): **High-order epistasis is present in genotype-phenotype maps.**