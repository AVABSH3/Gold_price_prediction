# Gold Price Prediction System

This project focuses on predicting gold prices using a machine learning model. The system employs the RandomForestRegressor algorithm for its predictive capabilities. The dataset used for training and testing the model contains historical gold price data.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

The Gold Price Prediction System aims to forecast future gold prices based on historical data. The RandomForestRegressor algorithm is utilized for its ability to capture complex relationships within the data, providing accurate predictions.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/gold-price-prediction.git
   cd gold-price-prediction

2. **Install Dependencies:**
   pip install -r requirements.txt

3. **Run the Application:**
    python gold_price_prediction.py

## Usage
Load the historical gold price dataset.
Preprocess the data and split it into training and testing sets.
Train the RandomForestRegressor model on the training set.
Evaluate the model's performance using metrics such as Mean Absolute Error and R-squared.
Make predictions on future gold prices using the trained model.

## Features
Predict gold prices using the RandomForestRegressor algorithm.
Evaluate model performance using metrics from scikit-learn.
Visualize results with matplotlib and seaborn.

## Dependencies
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
## Acknowledgements
The dataset used in this project is credited to Kaggle.
The RandomForestRegressor algorithm is implemented using scikit-learn.

## License
This project is licensed under the MIT License.
