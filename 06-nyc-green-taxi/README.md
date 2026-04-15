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

* Strongly correlated with fare amount and trip distance
* Behavioral variability limits prediction accuracy

### 🚦 Traffic Patterns

* Average speed is lower during peak hours
* Higher speeds at night indicate reduced congestion

### ⚠️ Data Quality Insights
* Detected extreme outliers (e.g., unrealistic distances and speeds)
* Highlights importance of preprocessing in real-world datasets


### 🤖 Machine Learning Model
* Model: Random Forest Regressor
* Target: Tip Percentage
* Train/Test Split: 80% / 20%

#### 📈 Performance
* Moderate predictive power (R² reflects behavioral variability)
* Key drivers:
   * Fare amount
   * Trip distance
   * Time of day

### 📊 Visualizations
* Trip distance distribution (histogram)
<img width="1423" height="780" alt="Screenshot 2026-04-15 at 09 58 41" src="https://github.com/user-attachments/assets/09b893c6-0333-467a-81ff-adc0f1b03ddf" />

* Trips Distance by Hour
<img width="1423" height="780" alt="Screenshot 2026-04-15 at 10 11 07" src="https://github.com/user-attachments/assets/3d1ad26c-66b4-450a-a4f6-1fea280dc632" />

* JFK Airport Trip by Hour

<img width="1423" height="780" alt="Screenshot 2026-04-15 at 10 11 20" src="https://github.com/user-attachments/assets/272c19d7-25a7-4d7f-8372-75c3b5e4875e" />

* Actual and Predicted ML Model Tip Percentage

<img width="1423" height="780" alt="Screenshot 2026-04-15 at 10 11 41" src="https://github.com/user-attachments/assets/d727e469-16fd-4184-8b6e-3e05be1a7f2a" />

* Average Trip Speeds by Hour of the Day

<img width="1423" height="780" alt="Screenshot 2026-04-15 at 10 12 29" src="https://github.com/user-attachments/assets/6b638d6a-75f2-4177-86a8-95c688da7282" />


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

## 🚀 Key Takeaways
This project demonstrates:

* Real-world data cleaning and anomaly handling
* Exploratory data analysis (EDA)
* Feature engineering
* Machine learning modeling
* Business insight generation

## 📌 Future Improvements

* Use advanced Machine Learning models (XGBoost)
* Add geospatial visualization (maps)
* Build real-time prediction system


## 👤 Author

Han Soe <br>
Aspiring Data Analyst / Data Scientist

#### Return to : [Projects Main](https://github.com/hansoe01/data_portfolio_projects)
