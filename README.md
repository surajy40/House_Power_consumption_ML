# ⚡ PowerPulse: Household Energy Usage Forecast

## 📌 Project Overview

PowerPulse is a machine learning project designed to **predict household energy consumption** using historical data. The goal is to help users understand usage patterns and enable better energy management.

---

## 🎯 Objectives

* Predict **Global Active Power consumption**
* Analyze energy usage trends
* Build accurate regression models
* Provide actionable insights for energy optimization

---

## 🧠 Skills Applied

* Data Preprocessing
* Feature Engineering
* Regression Modeling
* Model Evaluation (RMSE, MAE, R²)
* Data Visualization

---

## 📂 Dataset

**Individual Household Electric Power Consumption Dataset**

Contains:

* Date & Time
* Global Active Power
* Voltage, Current
* Sub-metering values

---

## 🔍 Project Workflow

### 1️⃣ Data Understanding & EDA

* Checked dataset structure (`info()`, `describe()`)
* Visualized energy trends over time
* Identified missing values & correlations

---

### 2️⃣ Data Preprocessing

* Combined Date & Time → Datetime
* Handled missing values
* Sorted time-series data
* Scaled features (if applied)

---

### 3️⃣ Feature Engineering

* Extracted:

  * Hour
  * Day
  * Month
* (Optional) Rolling averages / lag features

---

### 4️⃣ Model Building

Models used:

* Linear Regression
* Random Forest Regressor
* (Optional) LSTM / Neural Networks

---

### 5️⃣ Model Evaluation

Metrics used:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² Score

---

## 📊 Visualizations

* 📈 Energy consumption over time
* 🔍 Actual vs Predicted values
* 🔥 Correlation heatmap

---

## 💡 Key Insights

* Energy usage peaks during evening hours
* Weekends show higher consumption
* Certain features strongly influence power usage

---

## 🏆 Results

* Built a predictive model for energy consumption
* Achieved good accuracy using regression models
* Identified key usage patterns

---

## 🌍 Business Use Cases

* 🏠 Household energy optimization
* ⚡ Demand forecasting for power companies
* 🚨 Anomaly detection in energy usage
* 🌱 Reducing carbon footprint

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```
PowerPulse/
│
├── data/
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone <your-repo-link>

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## 📌 Future Improvements

* Add deep learning models (LSTM)
* Deploy using Streamlit dashboard
* Integrate real-time weather data
* Improve feature engineering

---

## 👨‍💻 Author

**Suraj**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
