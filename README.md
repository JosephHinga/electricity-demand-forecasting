
# ⚡ Electricity Demand Forecasting Project

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![Machine Learning](https://img.shields.io/badge/ML-Regression-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 **Project Description**

**End-to-end electricity demand forecasting project using Python. Covers data preprocessing, exploratory analysis, feature engineering, and machine learning models to predict hourly energy consumption from temperature, humidity, and temporal patterns.**

---

## 📁 **Project Structure**

```
Electricity-Demand-Forecasting/
│
├── data/
│   └── Electricity_Demand_Dataset.csv
│
├── notebook/
│   └── Electricity_demand_ipynb.ipynb
│
├── plots/
│   ├── demand_trend.png
│   ├── correlation_heatmap.png
│   └── prediction_vs_actual.png
│
├── README.md
└── requirements.txt
```

---

## 📊 **Project Overview**

Electricity demand forecasting helps utilities and industries plan energy supply, reduce blackouts, and optimize cost distribution. This project applies machine learning techniques to predict hourly demand using:

* Temperature
* Humidity
* Time features (hour, day, month, year)

---

## 🔍 **Key Features**

* ✔️ Full end-to-end data science workflow
* ✔️ Clean and well-structured dataset
* ✔️ Exploratory data analysis (EDA)
* ✔️ Machine learning for demand prediction
* ✔️ Time-based and weather-based feature engineering
* ✔️ Visualized insights and model performance plots

---

## 📥 **Dataset Summary**

| Feature     | Description                          |
| ----------- | ------------------------------------ |
| Timestamp   | Date and time of record              |
| hour        | Hour of the day                      |
| dayofweek   | Day of the week                      |
| month       | Month number                         |
| year        | Year                                 |
| dayofyear   | Numeric day of the year              |
| Temperature | Temperature in Celsius               |
| Humidity    | Humidity percentage                  |
| Demand      | Electricity demand (target variable) |

---

## 🔬 **Exploratory Data Analysis (EDA)**

### 📈 **Sample Visuals**

> (*Replace with real generated visuals from your notebook*)

**Demand Trend Over Time:**
![Demand Trend](plots/demand_trend.png)

**Correlation Heatmap:**
![Heatmap](plots/correlation_heatmap.png)

**Actual vs Predicted:**
![Predictions](plots/prediction_vs_actual.png)

---

## 🧠 **Modeling Approach**

The project uses multiple ML regression models, including:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

Models were evaluated using:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)

---

## 🧰 **Tools & Technologies**

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 🚀 **How to Run the Project**

### 1. Clone the repository

```
git clone https://github.com/yourusername/electricity-demand-forecasting.git
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the notebook

```
jupyter notebook notebook/Electricity_demand_ipynb.ipynb
```

---

## 📌 **Future Enhancements**

* Deploy the model using FastAPI/Flask
* Build a live dashboard in Power BI/Tableau
* Integrate real-time weather API for dynamic forecasting
* Try advanced time-series models (Prophet, LSTM)

---

## 👤 **Author**

**Joseph Hinga Mwangi**
Data & Risk Analyst | Data Scientist
📧 [hingamwangijoseph@gmail.com](mailto:hingamwangijoseph@gmail.com)


---


