# Pairs Trading Strategies

This repository contains Python code for implementing pairs trading strategies using various techniques, including cointegration analysis, Engle-Granger test, KNN regression, and Kalman filter. Pairs trading is a popular strategy in algorithmic trading that involves exploiting price divergences between two related assets.

## Table of Contents

1. [Cointegration Analysis](#cointegration-analysis)
2. [Engle-Granger Test](#engle-granger-test)
3. [KNN Regression](#knn-regression)
4. [Kalman Filter](#kalman-filter)
5. [Pairs Trading Implementation](#pairs-trading-implementation)
6. [Usage](#usage)
7. [Dependencies](#dependencies)
8. [Contributing](#contributing)
9. [License](#license)

## Cointegration Analysis

Cointegration is a statistical property that allows for a long-term relationship between two time series. The code in this section identifies cointegrated pairs among a list of tech stocks.

## Engle-Granger Test

The Engle-Granger test is performed to confirm cointegration between pairs of stocks. The residuals are checked for stationarity.

## KNN Regression

KNN regression is used to find potential pairs of stocks based on their historical price movements.

## Kalman Filter

The Kalman filter is applied to dynamically estimate the hedge ratio between two assets, adapting to changing market conditions.

## Pairs Trading Implementation

The last section demonstrates the implementation of a pairs trading strategy using the identified cointegrated pairs. The strategy includes risk management, transaction cost modeling, and dynamic pairs selection.

## Usage

1. Install the required dependencies using the provided `requirements.txt` file.
   ```bash
   pip install -r requirements.txt
Run the Jupyter notebook or Python script corresponding to each technique.
Dependencies
pandas
numpy
yfinance
matplotlib
statsmodels
scikit-learn
pykalman
scipy
Contributing
Contributions are welcome! If you have suggestions, improvements, or find issues, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Feel free to customize the description further based on additional details specific to your project.
