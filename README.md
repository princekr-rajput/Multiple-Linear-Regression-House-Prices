# 🏠 Multiple Linear Regression – House Price Prediction

This project implements a **Multiple Linear Regression** model to predict house prices
using multiple input features.  
The project demonstrates the complete workflow of a regression problem, including
data preprocessing, model training, prediction, and evaluation using real-world data.

---

## 📌 Project Objectives
- Understand Multiple Linear Regression in practice
- Work with real-world housing data
- Handle categorical features using encoding
- Build an end-to-end machine learning pipeline
- Evaluate model performance using regression metrics

---

## 📊 Dataset
- **Name:** Housing Dataset (`Housing.csv`)
- **Type:** Real-world housing data
- **Target Variable:** `price`
- **Features:** Combination of numerical and categorical attributes

The dataset is included in this repository for educational and learning purposes.

---

## 🛠️ Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## ⚙️ Data Preprocessing
- Separation of input features and target variable
- Identification of categorical features
- Encoding categorical variables using **OneHotEncoder**
- Avoiding dummy variable trap using `drop='first'`
- Combining preprocessing steps using **ColumnTransformer**

Numerical features are passed directly without scaling.

---

## 🧠 Model Used
- **Multiple Linear Regression**

The model is implemented using a **scikit-learn Pipeline**, ensuring that preprocessing
and model training occur together without data leakage.

---

## 📈 Model Evaluation
The model performance is evaluated using:
- **R² Score**
- **Mean Absolute Error (MAE)**

### 🔢 Result
- **R² Score:** ~0.6529

An R² value of approximately **0.65** indicates that the model explains about **65% of the
variance** in house prices, which is realistic for real-world housing data where many
external factors influence price.

---

## 📊 Visualization
- Actual vs Predicted price scatter plot
- Reference line to assess prediction accuracy visually

These plots help understand how well the model predictions align with actual values.

---

## 🧪 Project Structure
```text
Multiple-Linear-Regression-House-Prices/
│
├── Housing.csv
├── multiple_linear_regression.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE

