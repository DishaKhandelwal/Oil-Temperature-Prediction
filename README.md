# Oil-Temperature-Prediction
*This repository contains the code and workflow for building a time series prediction model to forecast oil temperature in power transformers using the Electricity Transformer Dataset (ETDataset). The project involves data preprocessing, exploratory data analysis, feature engineering, and model training using machine learning methods, including ARIMA and LSTM.*

# Project Overview
Power transformers are critical components in electrical grids, and monitoring their oil temperature is essential for detecting faults, optimizing maintenance, and preventing equipment failure. This project aims to predict oil temperature using time series data from the ETDataset, enabling better transformer health monitoring and predictive maintenance.
*ETDataset (Electricity Transformer Dataset) is a repository that provides time series data collected during the operation of power transformers. This dataset contains various parameters of power transformers, among which data related to oil temperature is used to monitor the condition of the transformer, predict failures, and optimize maintenance.*

# Project Structure
data/ - Contains the dataset (ett.csv) used for the prediction models.
notebooks/ - Jupyter notebooks for each stage of the project (EDA, feature engineering, model training, evaluation).
models/ - Contains trained models and model configurations.
results/ - Results from model training, including evaluation metrics (MAE, MSE, RMSE).
src/ - Main source code files for data preprocessing, model training, and evaluation.

# Prerequisites
Make sure you have the following installed:

Python 3.8+
Jupyter Notebook
Required Python packages listed in requirements.txt:
pandas
numpy
scikit-learn
matplotlib
seaborn
statsmodels
tensorflow (for LSTM)
keras
