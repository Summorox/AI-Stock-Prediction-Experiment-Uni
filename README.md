# AI Stock Prediction Experiment
## Overview
This repository contains a group project developed as part of a master's program in Artificial Intelligence at ISEP, completed in 2023. This experimental project was developed to explore the potential of using time series analysis for stock price prediction. Using S&P 500 historical data sourced from an API, the model attempts to predict future stock prices. Based on these predictions, an optimization algorithm is employed to select the top-performing stocks, ensuring sector diversity to mitigate risk and maximize returns.

## Methodology
1. **Data Collection**: Historical stock data for S&P 500 companies is obtained through the Yahoo Finance API (yfinance), focusing on daily closing prices and other relevant metrics.

2. **Predictive Model**: An ARIMA (Auto-Regressive Integrated Moving Average) model was used for stock price prediction, analyzing the historical price data to forecast future price movements.

3. **Optimization Algorithm**: A modified Particle Swarm Optimization (PSO) algorithm is used to select the top X stocks based on predicted performance while enforcing sector diversity to mitigate sector-specific risks.

## Members
| Name | Institutional Email | 
|-----------------|-----------------|
| Jorge Felício    | 1181244    | 
| Alessandro Cunha    | 1220183    | 
| Gabriel Ribeiro    | 1220189    | 

## Usage
1. Open and execute `IA_Stock_Prediction_Experiment.ipynb` in a Jupyter environment or in Google Colab.
2. Follow the steps described in the file, which guide you through data collection, model training, prediction, and portfolio optimization. Make sure to adjust the date ranges to better fit your needs at the time.

The file also lists the required libraries to run the project.
