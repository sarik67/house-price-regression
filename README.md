# 🏡 House Price Prediction – Regression Analysis (Task 4)

This project is part of the **Data Analysis & Data Science Using Python Internship** at **Main Flow Services and Technologies Pvt. Ltd.**

---

## 📌 Objective

Build a regression model that predicts house prices based on:
- Property Size (in sq. ft.)
- Number of Rooms
- Location Type (Urban, Suburban, Rural)

---

## 📊 Dataset Overview

- **Filename**: `house_prices.csv`
- **Features**:
  - `Size` – Property size (numeric)
  - `Location` – Urban/Suburban/Rural (categorical)
  - `Rooms` – Number of rooms (numeric)
  - `Price` – Target variable (numeric)

---

## 🔍 Project Workflow

1. **Data Cleaning**
   - Handled missing values and removed outliers

2. **Preprocessing**
   - Standardized numerical values
   - Encoded categorical data using OneHotEncoding

3. **Model Building**
   - Trained a **Linear Regression** model using `scikit-learn`

4. **Model Evaluation**
   - Evaluated using:
     - **RMSE** (Root Mean Square Error)
     - **R² Score** (Coefficient of Determination)

5. **Visualization**
   - Actual vs Predicted Price graph
   - Pairplot of features

---

## 📈 Results

- **RMSE**: `26780.22` *(example output)*
- **R² Score**: `0.82` *(example output)*

---

## 📂 Project Files

| File Name                | Description                        |
|--------------------------|------------------------------------|
| `house_price_model.ipynb`| Full code in Jupyter Notebook      |
| `house_prices.csv`       | Dataset used in training           |
| `README.md`              | Project Overview                   |
| `actual_vs_predicted.png`| Visualization of predictions       |

---

## 🚀 How to Run

1. Clone this repository or download ZIP.
2. Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn
