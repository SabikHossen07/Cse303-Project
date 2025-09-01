# 🚕 Taxi Fare Prediction

## 📌 Project Title
**Smart Fare Forecasting: Predicting Taxi Prices with Real-World Conditions**

## 📁 Dataset
This project uses the [Taxi Price Prediction dataset](https://www.kaggle.com/datasets/denkuznetz/taxi-price-prediction) from Kaggle. It contains trip-level data including distance, time, traffic, weather, and fare amount.

## 🎯 Objective
To build a regression model that accurately predicts taxi fare based on trip features such as distance, duration, time of day, traffic conditions, and weather.

## 📊 Data Description

| Column Name             | Type         | Description                                      |
|-------------------------|--------------|--------------------------------------------------|
| Trip_Distance_km        | Continuous   | Distance in kilometers                           |
| Time_of_Day             | Nominal      | Morning, Afternoon, Evening, Night               |
| Day_of_Week             | Nominal      | Weekday or Weekend                               |
| Passenger_Count         | Discrete     | Number of passengers                             |
| Traffic_Conditions      | Ordinal      | Low, Medium, High                                |
| Weather                 | Nominal      | Clear, Rain, Snow                                |
| Base_Fare               | Continuous   | Initial fare                                     |
| Per_Km_Rate             | Continuous   | Rate per kilometer                               |
| Per_Minute_Rate         | Continuous   | Rate per minute                                  |
| Trip_Duration_Minutes   | Continuous   | Duration of trip                                 |
| Fare_Amount             | Continuous   | Target variable: total fare                      |

## 📈 Data Analysis

- Checked for missing values and handled them using mean/mode imputation.
- Converted categorical variables using one-hot and label encoding.
- Verified dataset balance using skewness and histogram of `Fare_Amount`.
- Calculated mean, median, variance, and standard deviation for continuous columns.
- Plotted bar charts, pie charts, and correlation heatmap to visualize relationships.

## 🧠 Machine Learning Approach

- Preprocessed data using pandas and scikit-learn.
- Built regression models (e.g., Linear Regression, Random Forest).
- Evaluated performance using RMSE, MAE, and R² score.

## 📊 Visualizations

- Histogram of Fare Amount
- Pie chart of Weather Conditions
- Bar chart of Traffic Conditions
- Correlation heatmap of numerical features

## 🔄 Feature Engineering

- One-hot encoding for nominal categorical features.
- Label encoding for ordinal features.
- Normalization of continuous variables.

## ❓ Missing Values

- Handled missing values using:
  - Mean imputation for numerical columns
  - Mode imputation for categorical columns

## 📌 Conclusion

This project demonstrates how real-world conditions like traffic and weather influence taxi fares. The dataset is moderately balanced, and the model shows promising accuracy in fare prediction. Future improvements could include geolocation data and surge pricing factors.

## 📎 Repository Link

🔗 [GitHub Repository](https://github.com/SabikHossen07/taxi-fare-prediction)

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Cse303-Project/tree/main/taxi-fare-prediction.gi

#Contact
Feel free to reach out if you have any questions or suggestions!

Author: Md.Sabik Hossen Location: Dhaka, Bangladesh Email:hossenmdsabik@gmail.com
   
