# 🔍 Fuel Consumption Regression Project

This machine learning project focuses on predicting vehicle fuel consumption based on engine and vehicle features. The goal is to build and evaluate regression models to help estimate CO2 emissions or fuel usage given specifications of a vehicle.

---

## 📊 Dataset Overview

The dataset includes the following features:

- Engine Size
- Cylinders
- Fuel Type
- Fuel Consumption (city & highway)
- CO2 Emissions (target variable)

---

## 🔧 Project Workflow

The complete pipeline includes:

1. *Data Exploration (EDA):
   - Null value detection and handling
   - Outlier detection
   - Distribution analysis

2. Data Preprocessing:
   - Label encoding (for fuel type)
   - Feature scaling with `StandardScaler`

3. Model Building:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor

4. Model Evaluation:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

5. Conclusion & Feature Impact:*
   - Comparison of models
   - Feature importance from tree-based models

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for ML models and metrics)

---

## 📈 Sample Output

Some example output visualizations and performance metrics are available inside the notebook.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt

