Machine Learning with Molecular Crystals
========================================


[![DOI](https://zenodo.org/badge/113259999.svg)](https://zenodo.org/badge/latestdoi/113259999)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/malramsay64/MLCrystals-tutorial/master?filepath=01_Data_Ingest.ipynb)


This is a set of notebooks that detail how
machine learning can be used in the detection of 2D molecular crystals.
This work stems from research I am conducting as part of my PhD,
studying the crystal formation of these molecules.

To get started quickly click the badge below.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/malramsay64/MLCrystals-tutorial/master?filepath=01_Data_Ingest.ipynb)


### Environment Setup

These notebooks require a fairly extensive set of dependencies
which can be installed with the command

    conda env update

which will create the conda environment `MLCrystals` containing
all the required packages.

Installation without conda is probably not possible,
it can be downloaded from [here][download conda].
It is also highly likely to be impossible to install on Windows.

### Running the Notebooks

To run the notebook you need to be in the `MLCrystals` environment

    source activate MLCrystals-tutorial

from which you can launch the jupyter server

    jupyter notebook

which will open up jupyter in your default web browser.


[download conda]: [https://conda.io/miniconda.html]
