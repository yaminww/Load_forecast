# Load_forecast

## Table of Contents

* [Description](##Description)
* [Install](##Install)
* [Structure](##Structure)
* [Code](##Code)
* [Data](##Data)
  * [Dataset](###Dataset)
  * [Source](###Source)
  * [Variables](###Variables)

## Description
Load Forecast is a Python-based project aimed at predicting electricity load demand using statistical, machine learning and deep learning models. It leverages historical load data along with weather data to forecast future load demand.

## Install
This project requires **Python 3.10** and the following Python libraries installed:
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [XGBoost](https://xgboost.readthedocs.io/en/stable/)
- [darts](https://unit8co.github.io/darts/)
- [statsmodels](https://www.statsmodels.org/stable/index.html) 
- [Optuna](https://optuna.org/)

## Structure(##Structure)
	├── darts_logs/tcn_model        # loggind data of trained tcn model
	|── dataset                     # dataset folder
	|   |── complete_dataset.csv    # dataset for training and testing
	├── LICENSE
  ├── Presentation.ppts           # key findings of project for presentation 
	├── README.md
 	└── load_forecast.ipynb         # Notebook for project with catalog and explaination 

## Code
Code is provided in the `load_forecast.ipynb` notebook file. 

## Dataset
The project includes a sample dataset (load_dataset.csv) containing historical load data, weather data as well as holiday data. However, only load data and weather data were used as inputs. Detailed description of dataset can be accessed at [Kaggle](https://www.kaggle.com/datasets/aramacus/electricity-demand-in-victoria-australia/data). 

