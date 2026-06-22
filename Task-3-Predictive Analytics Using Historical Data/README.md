# Predictive Analytics Using Historical Data



## Project Overview



This project focuses on predictive analytics using historical sales data to forecast future trends. By applying data preprocessing techniques and a Linear Regression model, the project predicts future sales based on past performance and visualizes historical and forecasted trends.



## Objectives



* Clean and preprocess historical data.

* Perform exploratory data analysis (EDA).

* Build a predictive model using Linear Regression.

* Forecast future sales trends.

* Evaluate model performance using standard metrics.

* Visualize historical and predicted sales.



## Dataset



The project uses the **Sample Superstore Dataset**, which contains retail sales transactions from a superstore.



### Key Features



* Order Date

* Sales

* Profit

* Quantity

* Discount

* Category

* Region



## Technologies Used



* Python

* Pandas

* NumPy

* Matplotlib

* Scikit-learn

* Google Colab / Jupyter Notebook



## Project Workflow



### 1. Data Collection



Load the historical sales dataset.



### 2. Data Preprocessing



* Handle missing values

* Remove duplicate records

* Convert date columns to datetime format

* Sort records chronologically



### 3. Feature Engineering



Create a numerical time feature (`Day_Number`) from the order dates for model training.



### 4. Model Building



Train a Linear Regression model using:



* Input Feature: Day_Number

* Target Variable: Sales



### 5. Model Evaluation



Evaluate performance using:



* Mean Absolute Error (MAE)

* R² Score



### 6. Forecasting



Predict sales for the next 30 days using the trained model.



### 7. Visualization



Generate:



* Historical Sales Trend

* Actual vs Predicted Sales

* Future Sales Forecast



## Results



The model successfully demonstrates the predictive analytics workflow by:



* Identifying sales patterns from historical data.

* Forecasting future sales trends.

* Visualizing historical and predicted values.



## Project Structure



```text

Predictive-Analytics/

│

├── Predictive_Analytics.ipynb

├── Sample - Superstore.csv

├── README.md

└── images/

    ├── sales_trend.png

    ├── actual_vs_predicted.png

    └── forecast.png

```



## Installation



```bash

pip install pandas numpy matplotlib scikit-learn

```











## Future Improvements



* Implement ARIMA for time-series forecasting.

* Use Prophet for advanced forecasting.

* Add Power BI dashboard integration.

* Compare multiple machine learning models.



## Learning Outcomes



* Data preprocessing and cleaning

* Regression-based forecasting

* Model evaluation

* Trend analysis

* Data visualization
