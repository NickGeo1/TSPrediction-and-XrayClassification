# Konnektable assignment

## Installation
1. Install conda using miniconda installer [here](https://www.anaconda.com/download/success)

2. Open Anaconda prompt and install the environment from **environment.yml** by running the following command (make sure the file is located at the specified path):
```
conda env create -f environment.yml
```
This will create a **python 3.9** environment with the required packages and name "konnektable"

3. Use the previously created environment in your **IDE** to run the jupyter notebook at ```\Water_Consumption\timeseries.ipynb```. Please note that the ```*.nb``` files contain the trained neuralprophet models and they have to be at the same directory as timeseries.ipynb
