# Darknet Notebook and Python Script

## Installation 
Tensorflow GPU Requires python 3.6 and associated version specific dependencies which are included in this module. 

To create the required anaconda environment run 

`conda env create -f conda_environment.yml`

This installs the required environment in your default environment path

If you wish to install the conda environment in another location you can use the `-p` flag and run:

`conda env create -f conda_environment.yml -p /home/user/anaconda3/envs/env_name`

where `env_name` is the desired environment name. This is rumored to work, and if it does please let me know.

## Trust but Verify
To see if your installation is correct run:

`conda env list`

This will show all installed environments with an asterisk showing your current one.

## Usage
To use the newly installed environment run:

`source activate tensorflow_gpu`

## Debugging

Before training there is a delay of a vew minutes as experienced by this user:
https://github.com/tensorflow/tensorflow/issues/18652

But it should still work.

