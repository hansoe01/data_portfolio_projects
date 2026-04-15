# 🚖 NYC Green Taxi Data Analysis (September 2023)

## 📌 Project Overview

This project analyzes real-world trip data from NYC Green Taxis to uncover patterns in transportation behavior, pricing, tipping, and traffic conditions. The dataset was sourced from NYC Taxi & Limousine Commission (TLC). <br>
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## 🎯 Objectives

* Analyze trip distance distribution and find hypothese
* Understand travel patterns by time of day
* Identify airport-related trips
* Build a predictive Machine Learning model for tipping behavior
* Analyze trip behaviors (hourly speeds and tipping patterns)

## 📊 Key Insights

### 🚗 Trip Behavior

* Most trips are short (under 4 miles)
* Distribution is heavily right-skewed
* Indicates localized urban travel patterns

### ✈️ JFK Airport Trips

* Total trips = 806
* Average fares = $53.06
* Trips peak around afternoon.

### 💰 Tipping Behavior

* Tips are influenced by:

  * Fare amount
  * Trip distance
  * Time of day

### 🚦 Traffic Patterns

* Average speed is lower during peak hours
* Higher speeds at night indicate reduced congestion


## 🤖 Machine Learning Model

* Model: Random Forest Regressor
* Target: Tip Percentage
* Features:

  * Trip distance
  * Fare amount
  * Total amount
  * Passenger count
  * Trip_time_min
  * Pickup hour
  * Pickup day

## 🛠 Tools Used

* Python (Pandas, NumPy)
* Matplotlib
* Scikit-learn
* Seaborn
* Jupyter Notebook (Google Colab)


## 🚀 How to Run

1. Download the NYC_greentaxi_analysis.ipynb
2. Open Jupyter Notebook (or) Google Colab
3. Run all cells in order


## 📌 Future Improvements

* Use advanced Machine Learning models (XGBoost)
* Add geospatial visualization (maps)
* Build real-time prediction system


## 👤 Author

Han Soe <br>
Aspiring Data Analyst / Data Scientist
