# ML aids the discovery of catalytic descriptors 

This repository contains the code for the paper titled Identifying descriptors for promoted rhodium-based catalysts for higher alcohol synthesis via machine learning.

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Data preparation](#data-preparation)
- [Model training](#training)

# Overview

This repository contains the codes and dataset to train random forest and gradient boost regressors to predict the space-time yield (STY) of higher alcohol synthesis catalysts  
This repository contains the following:

* The main jupyter notebook whihc contains the code used to develop the ML models for the research project.
* For the notebook, we include the curated and labelled dataset in clean Excel sheet
* Necessary instructions to run the model and expected outcome are provided as comments in the notebook.

# System Requirements

## Hardware requirements
The code can run on any standard computer and does not require GPUs or clusters.

## Software requirements
The package has been tested on the following systems:
+ Windows 11 Pro for Workstations with 64-bit operating system, x64-based processor

### Python

A Python version of 3.6 or above is recommended. Most of the code is developed using standrad library packages including:

* Pandas 2.0.3 
* Numpy1.24.3 
* Scikit-learn 1.3.0
* Tensorflow 2.12.1
* Shap 0.40.0

## Installation guide

The codes can also be run on an exisiting environment provided the above listed packages are systemically installed using pip or conda commands.
Alternately users can create a dedicated `conda` environment and install the required the packages. The conda environment can be created by, for example:

* conda create -n HAS python=3.6
* conda activate HAS


## Data preparation

We provide the clean and labelled curated data as Excel sheets titled "PNNL data_FinalCurated.xlsx" which includes all the input features and target variables used for model training. 

## Model training

The workflow uses standard training process for implementing the Random forest and we provide detailed instructions for the same. The hyperparameters of the the algorithm are optimized usingthe gridsearch methodology. 

## Referencing

If you find this work relevant, please cite our published paper:

### Identifying Descriptors for Promoted Rhodium-Based Catalysts for Higher Alcohol Synthesis via Machine Learning
 M. Suvarna, P. Preikschas, J. Pérez-Ramírez.
ACS Catal. 2022, 12, 24, 15373–15385. (https://pubs.acs.org/doi/10.1021/acscatal.2c04349)
