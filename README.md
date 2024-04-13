# Traffic Volume Prediction Using TCN

## Abstract

This project aims to predict traffic volume in urban environments using Temporal Convolutional Networks (TCNs). We explore the Metro Interstate Traffic Volume dataset spanning 2012-2018, focusing on westbound I-94 in Minneapolis-St Paul, MN. Through deep learning techniques, specifically TCNs, we address the challenge of congestion prediction, crucial for effective traffic management and urban planning.

## Dataset

- **Name:** Metro Interstate Traffic Volume
- **Date Donated:** 5/6/2019
- **Characteristics:** Multivariate, Sequential, Time-Series
- **Subject Area:** Other
- **Associated Tasks:** Regression
- **Features:** 8
- **Instances:** 48204
- **Missing Values:** No

## Files

1. **Trafiic_Volume_Prediction_Using_TCN_Thesis.pdf:** Project thesis outlining methodology, experiments, and findings.
2. **Dataset_Cleaning_And_EDA.ipynb:** Jupyter notebook for data cleaning and exploratory data analysis.
3. **TCN_Optimization.ipynb:** Notebook for hyperparameter tuning using Bayesian optimization.
4. **TCN_Model_Training_&_Predicting.ipynb:** Notebook for TCN model training, validation, and prediction.

## Usage

1. **Thesis:** Understand project methodology, findings, and results.
2. **EDA Notebook:** Explore data cleaning and analysis.
3. **Optimization Notebook:** Optimize TCN model hyperparameters.
4. **Training & Prediction Notebook:** Train TCN model and make predictions.

## Contributors

- Mehdi Smail

## Results

The TCN model demonstrated superior consistency in accuracy, particularly for short-term predictions in the 6-hour time frame. It maintained a low Mean Absolute Error, rising only slightly from 0.04397 to 0.0453 as the forecast time frame increased, underscoring its robustness and consistency. This performance surpassed that of the LSTM and GRU models, indicating TCN's reliability for short- to medium-term forecasting.

## Project Status

This project was conducted to obtain the master's degree from University Technology Malaysia.
