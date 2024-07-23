# Prediction of Virtual Sensor Values in Marine Scrubbers for Efficient Fuel Usage

### Background

Air pollution from shipping is a significant global challenge, contributing to climate change and poor air quality. Marine scrubbers are a promising solution, removing harmful components like sulfur oxides and particulate matter from marine engine exhaust gases. Proper scrubber operation is critical; any sensor malfunction can lead to non-compliance with international regulations, resulting in financial penalties and reputational damage.

Marine scrubbers treat exhaust from engines, auxiliary engines, and boilers, ensuring no harm to human life and the environment. They help ships comply with International Maritime Organization (IMO) regulations, which limit the sulfur content in fuels to 0.50% globally and 0.10% in Emission Control Areas, down from 3.5%.

Compliance requires either using expensive low-sulfur fuel or using high-sulfur fuel with scrubbers. Correct operation is confirmed by measuring four parameters: pH, Polycyclic Aromatic Hydrocarbons (PAHs), Turbidity, and Gas Ratio (SO2/CO2). Malfunctioning sensors force ships to switch to expensive low-sulfur fuel until readings comply.

This project uses machine learning algorithms to predict missing sensor values in marine scrubbers, ensuring regulatory compliance, reducing operational costs, and minimizing environmental impact. By employing traditional and time series algorithms, we aim to predict missing sensor values accurately, resulting in cost savings, improved air quality, reduced greenhouse gas emissions, and enhanced sustainability in the shipping industry.

## Structure

- `data_preprocessing.ipynb`: Code for data preprocessing.
- `eda_and_feature_selection.ipynb`: Code for EDA and feature engineering.
- `models/`: Folder containing scripts for model training with and without hyperparameter tuning.
    - `linear_regression.ipynb`: Code for linear regression model.
    - `Models(tuned).ipynb`: Code for models with tunned hyperparameters
    - `Models(untuned).ipynb`: Predictions with base models
    - `ts_arima.ipynb`: Code for time series analysis using ARIMA.

## Setup

1. Clone the repository.
2. Install the required dependencies.
3. Run the scripts as needed.

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib
- xgboost


