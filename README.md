
# 🧠 Mission Readiness Prediction Tool

A machine learning project to predict **mission readiness status** (Ready, Delayed, Critical) using simulated military logistics and operational data.

Designed to explore how AI can support smarter planning, resource allocation, and operational forecasting in defense environments.

---

## 🚀 Project Summary

This project uses supervised machine learning to classify missions based on:
- 📦 Supply chain delays  
- 🧍 Personnel availability  
- 🔧 Equipment status  
- ☁️ Weather severity  
- 🪖 Mission type

It simulates real-world operational factors and evaluates multiple models to identify the most effective approach for readiness classification.

---

## ⚙️ Experiment Details

### 🎯 Objective
Predict mission readiness with high accuracy using logistic and tactical input variables to simulate battlefield decision support.

### 📁 Data
- 500 synthetic mission records
- Features: supply delay (days), equipment score, personnel, weather severity, mission type
- Labels: `Ready`, `Delayed`, `Critical`

### 🧠 Models Tested
- ✅ Random Forest Classifier  
- 🔁 Logistic Regression (baseline)

---

## 🔍 Feature Importance

Understanding what drives mission readiness:

| Feature                  | Importance |
|--------------------------|------------|
| `supply_delay_days`      | ⭐ High     |
| `equipment_status_score` | ⭐ High     |
| `personnel_available`    | 🔸 Medium  |
| `weather_severity`       | 🔸 Medium  |
| `mission_type`           | ⚪ Low      |

📊 **Visual Breakdown:**

![Feature Importance](feature_importance.png)

> Key insights: Supply chain delays and equipment readiness were the top drivers of mission outcomes — matching what defense ops teams experience in the field.

---

## 📊 Model Performance Comparison

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| ✅ Random Forest     | 1.00     | 1.00      | 1.00   | 1.00     |
| 🔁 Logistic Regression | 0.75     | 0.75      | 0.75   | 0.75     |

📉 **Performance Chart:**

![Model Comparison](model_comparison_chart.png)

> Random Forest clearly outperformed Logistic Regression in handling non-linear patterns and critical decision boundaries.

---

## 📁 Project Files

- `MissionReadinessModel.ipynb` – Full notebook with code, metrics, and charts  
- `mission_readiness_data.csv` – Clean, simulated dataset  
- `feature_importance.png` – Top features visual  
- `model_comparison_chart.png` – Performance comparison  
- `README.md`, `SETUP.md`, `.gitignore`, `LICENSE`, `requirements.txt`

---

## 🧭 How to Run

See `SETUP.md` for full installation and notebook instructions.

---

## 💡 Why This Matters

This project demonstrates:
- 🚀 Practical AI application in defense & logistics
- 🔍 Feature engineering and model comparison
- 🧠 Mission-driven problem-solving from a veteran's perspective

---

## 👨‍💻 About the Author

**Corey Elmore**  
Transitioning Navy Corpsman | Ops & Logistics Leader | M.S. CS – AI/ML  
[LinkedIn →](https://www.linkedin.com/in/coreyelmoreusn/) | [GitHub →](https://github.com/coreyelmore-dev)

> “Mission Ready — Again. Just in a New Arena.”
