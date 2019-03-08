# Vocal-MNIST
A little interesting project for digital sound processing. This code is written by python3.

# Usage
The main file is named as mfcc.ipynb.
Should use jupyter notebook to open and run the source code. Installation guide can be found in [here](https://jupyter.org/install).
In the project's directory, use the command below to open jupyter notebook:

`jupyter notebook`

Before running the code, Free Spoken Digit Dataset ([FSDD](https://github.com/Jakobovski/free-spoken-digit-dataset)) is required if you would like to retrain this model. Or you can use `model = model_load()` and `X, Y = file2input()` to access our pretrained model and data.

The required packages are mentioned in "requirements.txt". `pip3` or `pip` is an easy way to get all of the packages required.

`pip3 install "requirements.txt"`
