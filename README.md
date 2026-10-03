# ☀️ Solar Power Generation Prediction using Machine Learning

A machine learning project designed to predict solar power generation (yield) based on weather parameters, irradiation, and environmental metrics collected from solar power plants.

---

## 📌 Project Overview

Solar power generation depends heavily on weather conditions, irradiation, and ambient temperature. Accurate power generation forecasting is essential for:
- Efficient grid management and energy distribution.
- Storage optimization and load balancing.
- Reducing reliance on non-renewable backup power sources.

This project analyzes historical solar plant data, performs Exploratory Data Analysis (EDA), pre-processes features, and trains machine learning models to forecast solar energy output accurately.

---

## 📊 Dataset Overview

The dataset contains measurements from a solar power plant, typically including:

| Feature | Description |
| :--- | :--- |
| **Date & Time** | Timestamp of data recording |
| **Plant ID / Sensor ID** | Unique identifiers for solar plant equipment |
| **Ambient Temperature** | Surrounding air temperature (°C) |
| **Module Temperature** | Temperature of the solar panel module (°C) |
| **Irradiation** | Amount of solar radiation hitting the panels ($W/m^2$) |
| **DC / AC Power** | Direct and Alternating Current output |
| **Daily Yield / Total Yield** | Target variables representing cumulative power generated |

> **Note:** If using the Kaggle *Solar Power Generation Data*, make sure to download and place `Plant_1_Generation_Data.csv` and `Plant_1_Weather_Sensor_Data.csv` inside the `data/` folder.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.8+
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn`, `xgboost`
* **Environment:** Jupyter Notebook / Google Colab

---

## 📁 Repository Structure

```text
Solar-Power-Generation-Prediction-using-ML/
│
├── data/                                 # Dataset files (if within size limits)
│   ├── Plant_1_Generation_Data.csv
│   └── Plant_1_Weather_Sensor_Data.csv
│
├── Solar Power Generation Prediction.ipynb # Main Jupyter Notebook
├── README.md                             # Project Documentation
└── requirements.txt                      # Project Dependencies
