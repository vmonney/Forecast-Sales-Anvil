# Forecast Sales Anvil

There's two critical aspects to business...making sales and keeping costs down. The former is absolutely critical as it allows you to work out how much money is comming into the company.

Forecast Sales Anvil is a project focused on predicting sales for different products and stores using Facebook's Prophet model. It includes a comprehensive analysis and forecasting of sales data, with a focus on Tesla models in various locations.

## Overview

The project utilizes Facebook's Prophet, a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It's designed to be flexible and to handle missing data and changes in the trend, and typically works best with daily periodicity data with at least one year of historical data.

## Features

- **Data Analysis and Preprocessing**: Includes scripts for loading, filtering, and preprocessing the sales data.
- **Model Training and Evaluation**: Utilizes the Prophet model for forecasting sales, with evaluation metrics to assess performance.
- **Model Serialization**: Demonstrates how to save and load the trained model for future predictions.
- **Anvil App Integration**: Shows how to integrate the model with an Anvil app for easy access and utilization.

## Installation

To use this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/vmonney/Forecast-Sales-Anvil.git
cd Forecast-Sales-Anvil
# Install dependencies (assuming you have Python and pip installed)
pip install pandas seaborn matplotlib prophet sklearn json itertool anvil-uplink
```

## Usage

1. **Data Analysis and Preprocessing**: Explore the `Facebook Prophet.ipynb` notebook for details on data analysis and preprocessing steps.
2. **Model Training**: Follow the steps in the notebook to train the Prophet model on your data.
3. **Model Evaluation**: Evaluate the model's performance using the provided metrics.
4. **Anvil App**: Integrate the model with an Anvil app for making predictions and visualizing results.

## Dataset

The project uses a `dataset.csv` file containing sales data for different Tesla models across various stores.

## Contributing

Contributions to improve the project are welcome. Please feel free to fork the repository, make changes, and submit a pull request.