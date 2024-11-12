# AI Stock Prediction Experiment
## Overview
This repository contains a group project developed as part of a master's program in Artificial Intelligence at ISEP, completed in 2023. This experimental project was developed to explore the potential of deep learning in stock price prediction. Using S&P 500 historical data sourced from an API, the model attempts to predict future stock prices. Based on these predictions, an optimization algorithm is employed to select the top-performing stocks, ensuring sector diversity to mitigate risk and maximize returns.

## Methodology
1. **Data Collection**: Historical S&P 500 stock data is obtained via the Yahoo Finance API.

2. **Predictive Model**: An LSTM neural network is used to predict future stock prices based on historical data. 

3. **Optimization Algorithm**: A variation of Particle Swarm Optimization (PSO) algorithm is used to select the top X stocks based on predicted performance while ensuring sector diversity.

# Usage
1. Open and execute `IA_Stock_Prediction_Experiment.ipynb` in a Jupyter environment or in Google Colab.
2. Follow the steps described in the file.
