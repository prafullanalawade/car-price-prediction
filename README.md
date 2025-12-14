# car-price-prediction
# Car Price Prediction System

## 📌 Project Overview
This project aims to predict the selling price of used cars based on various features such as brand, model, mileage, fuel type, transmission, and vehicle age. Machine learning regression techniques were applied to estimate car prices accurately and support data-driven decision-making.

---

## 🎯 Project Objectives
- Understand key factors influencing car prices
- Perform data cleaning and preprocessing
- Apply and compare multiple regression algorithms
- Select the best-performing model based on evaluation metrics
- Predict car prices with high accuracy

---

## 📊 Dataset Description
The dataset contains information about used cars, including:
- Car brand and model
- Year of manufacture
- Mileage
- Fuel type
- Transmission type
- Engine and power specifications

**Target Variable:** Car Price

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- CatBoost  
- Machine Learning  
- Data Preprocessing  
- Data Analysis  

---

## 🧠 Algorithms Implemented
The following regression models were trained and evaluated:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- **CatBoost Regressor**

---

## 🏆 Best Performing Model
- **CatBoost Regressor** achieved the highest performance.
- **R² Score:** **0.96**
- The model effectively captured complex, non-linear relationships in the data and handled categorical features efficiently.

---

## 📂 Project Workflow
1. Data loading and exploration (EDA)
2. Handling missing values and outliers
3. Encoding categorical variables
4. Feature selection and transformation
5. Model training and evaluation
6. Model comparison and final selection
7. Price prediction on test data
8. Model saving using Pickle for reuse

---

## 📈 Model Evaluation
The model was evaluated using regression metrics:
- **R² Score**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

The CatBoost model achieved an **R² score of approximately 0.96**, indicating strong predictive accuracy.

---

## 🔍 Key Insights
- Vehicle age, mileage, and brand significantly impact car prices
- Premium brands tend to retain higher resale value
- CatBoost outperformed other models due to its ability to handle categorical data without extensive encoding

---

## 🚀 Use Case
This system can be used by:
- Used car dealers for price estimation
- Buyers to assess fair market value
- Sellers to price vehicles competitively
- Automotive platforms for automated pricing tools

---

## 💾 Model Deployment
- The trained model was saved using **pickle** for future use.
- The model can be easily integrated into a web application or API for real-time prediction.

