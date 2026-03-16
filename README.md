# retail-demand-forecasting-ml
Hybrid Machine Learning Approach for Retail Demand Forecasting using ARIMA, Random Forest, XGBoost and LSTM

## Project Overview

Retail demand forecasting is essential for effective inventory management, operational planning and financial decision-making in retail organisations. However, retail demand data often contains irregular fluctuations, seasonal patterns and unexpected spikes caused by promotional campaigns or bulk purchases. These characteristics make accurate forecasting challenging.

This project develops a forecasting framework that combines classical statistical techniques, machine learning models and deep learning architectures to analyse and predict retail demand patterns.

The study uses the **UCI Online Retail dataset**, which contains over 500,000 transactional records from a UK-based online retailer between 2010 and 2011.

The objective of this project is to compare different computational approaches and evaluate their ability to model complex retail demand behaviour.

---

## Models Implemented

The following forecasting models were implemented and compared:

- **ARIMA (Autoregressive Integrated Moving Average)** – classical time series forecasting model
- **Random Forest Regressor** – ensemble machine learning model
- **XGBoost Regressor** – gradient boosting machine learning algorithm
- **LSTM Neural Network** – deep learning model designed for sequential data

---

## Methodology

The project follows a structured data science pipeline:

1. **Data Cleaning**
   - Removal of duplicate records
   - Removal of missing values
   - Filtering of negative quantities and prices

2. **Feature Engineering**
   - Creation of TotalPrice feature
   - Aggregation of transactions into daily demand

3. **Exploratory Data Analysis**
   - Time series visualization
   - Demand distribution analysis
   - Seasonal decomposition

4. **Anomaly Detection**
   - Isolation Forest used to detect abnormal demand spikes

5. **Model Training**
   - ARIMA
   - Random Forest
   - XGBoost
   - LSTM Neural Network

6. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)

7. **Visualization**
   - Forecast vs actual comparisons
   - Model performance plots

---

## Dataset

Dataset used in this project:

**UCI Online Retail Dataset**

File included in repository:
Online Retail.xlsx


The dataset contains transactional information including:

- Invoice number
- Product description
- Quantity purchased
- Price per unit
- Transaction timestamp
- Customer information

---

## Technologies Used

The project was implemented using Python and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- statsmodels
- tensorflow (Keras)

---

## Project Structure

---

## Installation

Install the required Python libraries before running the project.

---

## Running the Project

1. Download the repository
2. Open the notebook:

3. Run the notebook cells sequentially.

The notebook performs:

- Data preprocessing
- Exploratory data analysis
- Anomaly detection
- Model training
- Forecast evaluation
- Visualization of forecasting results

---

## Results

The experimental results show that deep learning methods provide stronger predictive performance compared to classical statistical models when dealing with complex retail demand data.

The **LSTM model achieved the best forecasting performance**, producing the lowest error values among the evaluated models.

This demonstrates the advantage of deep learning architectures for modelling nonlinear temporal relationships and long-term dependencies in retail demand datasets.

---



