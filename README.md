# CAUTION: This branch is under heavy construction. Long functions may drop from the ceiling and lead to serious injuries.
# Cancer Classification
This is a repo to trian and test deep learning models for cancer classification.

## Usage
To make this code run on your machine you need to:
* download dataset (see dataset_dependent folders READMEs)
* install miniconda: https://docs.anaconda.com/anaconda/install/linux/ 
* set up a conda environment and activate it:
    * conda env create --file environment.yaml
    * conda activate tensorlfow_2_3
* (optional): edit config.yaml to modify settings
* run the program:
    * python ./src/main.py