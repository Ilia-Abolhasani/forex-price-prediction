# Forex Price Prediction using LSTM

![Forex Price Prediction](https://github.com/Ilia-Abolhasani/forex-price-prediction/blob/master/Images/targets.png)

## Overview

Welcome to the Forex Price Prediction project! This repository contains a Jupyter Notebook that utilizes deep learning techniques, specifically Long Short-Term Memory (LSTM) networks, to predict the price of XAU/USD (Gold/US Dollar) for a short period of time. The goal of the prediction is to assist in deciding whether to open a short or long position with target profit (TP) and stop loss (SL) values of 1$ or 2$. Please note that the dataset used for training and testing is simulated and consists of 300,000 minutes' worth of candle data.

## Project Structure

The project repository is organized as follows:

- `notebooks/`: Contains the Jupyter Notebook `forex_price_prediction.ipynb`, where the LSTM model is implemented and the prediction process is explained in detail.
- `data/`: This directory holds the simulated forex data in CSV format. It includes data for training, testing, and validation.
- `images/`: Contains any images used in the README or the Jupyter Notebook.
- `README.md`: The file you are currently reading, providing an overview of the project.

## Requirements

To run the Jupyter Notebook and execute the LSTM model, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- TensorFlow
- Keras

You can install these packages using pip:

```bash
pip install jupyter pandas numpy matplotlib tensorflow keras
