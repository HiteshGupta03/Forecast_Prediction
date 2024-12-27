# Forecast_Prediction
Forecast Prediction Using Python and Machine Learning

This project demonstrates time series analysis and forecasting using ARIMA and SARIMA models. 
It involves data cleaning, visualization, stationarity testing, and predictive modeling on sales data.

**Table of Contents**
Introduction

Features

Workflow

Technologies Used

Setup Instructions

Usage

Results

Future Enhancements

License

**Introduction**
This project focuses on forecasting monthly sales data using time series analysis. Key steps include:

.  Data preprocessing and cleaning.
.  Checking for seasonality and stationarity.
.  Building predictive models.
.  Generating forecasts for future periods.


**Features**
1.  Data preprocessing and cleaning:
      .   Cleaned the dataset by removing missing values and renaming columns.
      .  Transformed the **Month** column into a datetime format and set it as the index.

2.  Visual Analysis:
     .  Plotted the data to identify trends and seasonality visually.
     . Performed decomposition of the time series into trend, seasonal, and residual components.

3.  Statistical Testing:
     .  Used the Augmented Dickey-Fuller (ADF) test to check for stationarity.
     . Differenced the data to make it stationary.
    
4.  Modeling:
     .  Built ARIMA and SARIMA models for forecasting.
     .  Tuned model parameters (p, d, q) using ACF and PACF plots.
    
5.  Forecasting:
     .  Predicted future sales using the trained models.
     .  Visualized actual vs forecasted sales.



**Workflow**
1.  Data Import:
     . Loaded the dataset perrin-freres-monthly-champagne-.csv using Pandas.

2.  Data Cleaning:
     . Dropped irrelevant rows.
     . Checked the statistical summary of the dataset.

3.  Stationarity Check:
     . Performed ADF test to assess the stationarity of the time series.

4.  Differencing:
     . Used first-order and seasonal differencing to stabilize the series.

5.  Model Training:
     . Trained ARIMA and SARIMA models with specified parameters.

6.  Forecasting:
     . Predicted sales for future timeframes.

**Technologies Used**
  .  Python Libraries:
      **Pandas**: Data manipulation and analysis.
      **NumPy**: Numerical computations.
      **Matplotlib**: Data visualization.
      **Statsmodels**: Statistical analysis and time series modeling.


**Setup Instructions**
1.  Clone the repository:
   git clone https://github.com/HiteshGupta03/time-series-forecasting.git

2.  Navigate to the project folder:
   cd time-series-forecasting

3.  Install dependencies:
   pip install -r requirements.txt

4. Ensure the dataset (perrin-freres-monthly-champagne-.csv) is in the project directory.

**Usage**
1.  Run the script:
   python forecast_prediction.py

2.  Outputs:
   . Plots showing historical data, decomposed components, and forecasts.
   . A statistical summary of the ARIMA and SARIMA models.
   . Future predictions visualized alongside historical data.


**Results**
  .  The project demonstrates:

     . Identification of seasonality and trends in sales data.
     . Application of ARIMA and SARIMA for accurate sales forecasting.
     . Visualization of actual vs predicted values, providing insights into model performance.

**Future Enhancements**
     . Automating parameter selection using grid search or auto-ARIMA.
     . Exploring deep learning approaches like LSTMs for time series forecasting.
     . Integrating the model into a dashboard for real-time forecasting.



**License**
This project is licensed under the MIT License.




