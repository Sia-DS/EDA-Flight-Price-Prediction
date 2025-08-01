# EDA-Flight-Price-Prediction
Exploratory Data Analysis (EDA) and feature engineering on flight price dataset to identify key pricing factors and visualize airline-wise price variations. Includes preprocessing, insights, and model-ready data preparation.
# ✈️ Flight Price Analysis with EDA and Feature Engineering

A detailed exploratory data analysis project on Indian domestic flight data to uncover pricing patterns and travel behavior.

## 📊 Objective
To analyze factors affecting flight ticket prices and identify trends by performing data preprocessing, feature engineering, and visualization.

---

## 📁 Dataset Overview

- **Features**: Airline, Source, Destination, Total Stops, Price, Date of Journey, Arrival Time, etc.
- **Target Variable**: `Price`

---

## 🧪 Key Steps

1. **Data Cleaning**
   - Converted date/time columns to datetime format
   - Extracted day, month, and year for better temporal analysis

2. **Feature Engineering**
   - Derived new features like hour of arrival, day of journey, and number of stops
   - Categorized flights by class and carrier type

3. **Exploratory Data Analysis**
   - Distribution of flight prices
   - Comparison of average prices by airline, city, and month
   - Flight frequency by time of day, date, and airline

---

## 📌 Major Insights

- 🔼 **Jet Airways Business** class has the highest prices.
- ⛔ **More stops = higher median price**; direct flights are generally cheaper.
- 🏙️ **Delhi** has the highest departure fares.
- ⏰ **6 PM** is the most common arrival hour.
- 🗓️ **7th to 9th of the month** has the most flights; **April** sees the lowest activity.
- 📈 **March** shows high price variation; **April** fares are more consistent.

---

## 🧠 Tools & Libraries Used

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 📍 Conclusion

This project gives actionable insights into flight pricing patterns across airlines, stops, and travel times. It sets a foundation for machine learning applications such as flight price prediction or optimization.

## Author 
Sia Thakur
