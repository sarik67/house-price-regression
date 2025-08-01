# 🏡 House Price Prediction – Regression Analysis (Task 4)

This project is part of the **Data Analysis & Data Science Using Python Internship** at **Main Flow Services and Technologies Pvt. Ltd.**

---

## 📌 Objective

Build a regression model to predict house prices based on:
- 📏 Property Size (in square feet)
- 🛏️ Number of Rooms
- 📍 Location Type (Urban / Suburban / Rural)

---

## 📊 Dataset Overview

- **Filename**: `house_prices.csv`
- **Features**:
  - `Size` – Numeric (house size in sq. ft.)
  - `Rooms` – Numeric (number of rooms)
  - `Location` – Categorical (urban, suburban, rural)
  - `Price` – Numeric (target variable)

---

## 🔍 Project Workflow

1. **Data Cleaning**
   - Checked for missing values
   - Handled outliers

2. **Preprocessing**
   - Standardized numerical values using `StandardScaler`
   - Encoded `Location` using `OneHotEncoder`

3. **Model Building**
   - Trained a `Linear Regression` model using `scikit-learn`
   - Used 80/20 train-test split

4. **Model Evaluation**
   - Calculated `RMSE` and `R² Score`
   - Visualized results using Matplotlib and Seaborn

---

## ✅ Results

| Metric | Value       |
|--------|-------------|
| RMSE   | 26780.22    |
| R²     | 0.82        |

---

## 📁 Project Files

| File Name               | Description                        |
|------------------------|------------------------------------|
| `house_price_model.ipynb` | Jupyter Notebook with full code |
| `house_prices.csv`        | Dataset used for training        |
| `actual_vs_predicted.png` | Visualization plot               |
| `README.md`               | This file                        |

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/sarik67/house-price-regression.git
cd house-price-regression

# Install required packages
pip install pandas scikit-learn matplotlib seaborn

# Open the notebook
jupyter notebook house_price_model.ipynb
