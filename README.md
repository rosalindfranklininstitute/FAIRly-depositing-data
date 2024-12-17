# Depositing biological segmentation datasets FAIRly
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rosalindfranklininstitute/FAIRly-depositing-data.git/HEAD)

This repository holds the data of the surveyed studies and Jupyter notebooks for analysis for the publication ["Depositing biological segmentation datasets FAIRly"](https://doi.org/10.1101/2024.12.10.627814).
The notebooks can be launched with the Binder link above or to run locally please follow the instructions below.

## Data

The data for the surveyed studies is in the `FAIRly_Depositing_Segmentation.csv` file.

## Installation

The conda environment with the dependencies to run the notebooks can be recreated by:

1. Cloning this repository

```
git clone https://github.com/rosalindfranklininstitute/FAIRly-depositing-data.git
```

2. Creating a conda environment from the env.yaml file

```
conda env create -f <path_to_cloned_repo>/env.yaml
```

3. Activate the conda environment

```
conda activate analysis
```

4. Launch Jupyter notebooks

```
jupyter notebook
```

## Issues

Please use the [GitHub issue tracker](https://github.com/rosalindfranklininstitute/python-template/issues) to submit bugs.

## License

Copyright Rosalind Franklin Institute, 2024.

Distributed under the terms of the Apache-2.0 license, this repository is free and open source software.
