# Task 1

We develop a reliable model for forecasting the daily water consumption in a city for the next two years. We utilize a time-series dataset containing hourly water usage data from 2002 to 2016. The final predictions are for the years 2017-2018.

# Task 2
We develop a binary image classification model for identifying and categorizing COVID-19 images to determine whether a patient has COVID-19 or not. The dataset used in this task consists of chest X-Ray images in JPEG format, which are classified into two categories, COVID-19 and Healthy

# Installation/general
1. Install conda using miniconda installer [here](https://www.anaconda.com/download/success)

2. Open Anaconda prompt and install the environment from **environment.yml** by running the following command (make sure the file is located at the specified path):
```
conda env create -f environment.yml
```
This will create a **python 3.9** environment with the required packages and name "konnektable"

3. Use the previously created environment in your **IDE** to run the jupyter notebook at `\Water_Consumption\timeseries.ipynb`. 
Please note that the `*.nb` files contain the trained neuralprophet models and they have to be at the same directory as `timeseries.ipynb`

4. Use the previously created environment in your **IDE** to run the jupyter notebooks `preprocess.ipynb` and `classification.ipynb` at `\COVID_Classification`. 
Please note that the `*.pth` file contain the trained pytorch model and it has to be at the same directory as `classification.ipynb`

5. It is recommended to not run the validation sample script in `preprocess.ipynb` as it will change the arrangement of the already structured dataset of the image classification task

6. `*.csv` files contain train/validation metrics of the models
