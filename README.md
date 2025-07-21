# ✈️ International Airlines Traffic Analysis by City Pairs

Welcome to a full-scale data analysis and machine learning project focused on **International Airline Passenger Traffic** between global city pairs. This repository contains a well-structured approach to both **exploratory data analysis (EDA)** and **predictive modeling (ML)**, built with Python and popular data science tools.

---

## 📚 Table of Contents

- [📍 Project Objective](#-project-objective)
- [📦 Dataset Description](#-dataset-description)
- [🔎 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [🤖 Machine Learning & Prediction](#-machine-learning--prediction)
- [📊 Visualizations & Key Insights](#-visualizations--key-insights)
- [🛠️ Tools & Technologies Used](#-tools--technologies-used)
- [🚀 Future Scope](#-future-scope)
- [📁 Repository Structure](#-repository-structure)
- [📬 Contact & Credits](#-contact--credits)

---

## 📍 Project Objective

The airline industry serves as a vital pillar for global trade, tourism, and international cooperation. This project aims to:

- Analyze international passenger traffic trends between city pairs over time.
- Identify major hubs, growth patterns, and seasonality in air travel.
- Predict future traffic between city pairs using machine learning models.
- Provide strategic insights useful for airlines, tourism boards, and airport planners.

---

## 📦 Dataset Description

The dataset contains detailed information about the **monthly volume of international passengers** between various global city pairs.

### Key Columns:

- `Year` — Year of travel
- `Month` — Month of travel
- `City_Pair` — Departure and destination cities
- `Passengers` — Number of passengers for that month
- `Segment` — Domestic/International segmentation

🧼 **Preprocessing:**  
The data was carefully cleaned by handling missing values, checking for anomalies, converting date fields, and ensuring consistency in city names.

---

## 🔎 Exploratory Data Analysis (EDA)

EDA was performed to dig deep into the structure, patterns, and distribution of the traffic data. Key analytical steps included:

### ✅ Data Cleaning
- Handled missing values in passenger counts and date columns
- Removed duplicates and corrected inconsistent city-pair naming

### 📊 Trend Analysis
- Monthly and yearly traffic volume over time
- Identified seasonal surges in traffic (e.g., summer & holiday peaks)
- Country-specific trends in air travel

### 🌍 Top City Pair Analysis
- Most trafficked international routes
- Fastest growing city pairs over time
- Busiest months and sharpest drops in passenger volume

### 📈 Correlation & Outliers
- Correlation heatmaps
- Outlier detection using IQR and Z-score methods

📌 **Result:**  
EDA revealed **strong seasonality**, with peak traffic in **June–August** and **December**. Traffic patterns varied based on city regions and external factors like holidays.

---

## 🤖 Machine Learning & Prediction

After understanding the data through EDA, we transitioned into predictive modeling.

### 🧠 Goal:
Forecast the number of passengers between city pairs based on past data and features like month, year, and city pair.

### 🏗 Feature Engineering:
- Extracted time-based features (month, year, season)
- One-hot encoding for categorical columns like city pairs

### 🔧 Models Used:
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

### 📏 Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 🧪 Model Performance Summary:

| Model               | MAE    | RMSE   | R² Score |
|--------------------|--------|--------|----------|
| Linear Regression  | High   | High   | Moderate |
| Random Forest      | Low    | Low    | 0.89     |
| XGBoost Regressor  | Lowest | Lowest | 0.92     |

✅ **XGBoost** provided the best performance in predicting international passenger traffic.

---

## 📊 Visualizations & Key Insights

Visuals were created using **Seaborn**, **Matplotlib**, and **Plotly** for interactive exploration.

### 🖼 Key Charts:
- Heatmaps of monthly trends
- Bar plots for top city pairs
- Line charts showing traffic evolution
- Seasonal decomposition plots

> **Top Insight:**  
> Some city pairs such as `New York ↔ London` and `Los Angeles ↔ Tokyo` remained consistently dominant over the years. Seasonal peaks heavily influenced traffic, aligning with global holiday seasons.

---

## 🛠️ Tools & Technologies Used

- **Python**: Data wrangling, analysis, modeling
- **Jupyter Notebook**: For interactive data exploration
- **Pandas & NumPy**: Data manipulation
- **Matplotlib, Seaborn, Plotly**: Visualization
- **Scikit-learn**: Machine Learning models and preprocessing
- **XGBoost**: Advanced regression modeling

---

## 🚀 Future Scope

Here’s how this project can be extended:

- 📉 **Time Series Models**: Incorporate ARIMA, SARIMA, or LSTM-based models for better time-based forecasting
- 🌐 **External Data**: Use fuel price indices, global events, and weather data to improve model accuracy
- 📊 **Dashboard**: Deploy a Streamlit or Tableau dashboard for real-time monitoring
- 🧭 **Geospatial Mapping**: Integrate mapping tools to visualize city pair traffic geographically

---


