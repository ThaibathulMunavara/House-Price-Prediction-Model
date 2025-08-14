# 🏠 Housing Price Prediction

## 📌 Project Overview

### This project aims to build a machine learning model that predicts the price of a house based on various features such as area, number of bedrooms, number of bathrooms, and more. The goal is to help real estate agencies, buyers, and sellers estimate fair market prices.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features / What it Does

     - Predicts house prices using machine learning algorithms.

     - Supports multiple property attributes (e.g., area, bedrooms, stories, parking).

     - Handles both numerical and categorical data.

     - Easy to extend with advanced models like Random Forest or XGBoost or Linear Regression model using sklearn.linear_model.

     - Split data into train-test sets.

     - Evaluate model using MAE, MSE, R².

     - Plot regression line and interpret coefficients.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Dataset

### The dataset used is Housing.csv, which contains several attributes about houses:

     area – size of the house in square feet

     bedrooms – number of bedrooms

     bathrooms – number of bathrooms

     stories – number of stories in the house

     mainroad – whether the house is connected to the main road

     guestroom – availability of a guest room

     basement – availability of a basement

     hotwaterheating – whether the house has hot water heating

     airconditioning – availability of air conditioning

     parking – number of parking spaces

     prefarea – whether the house is located in a preferred area

     furnishingstatus – status of furnishing (furnished, semi-furnished, unfurnished)

     price – target variable, price of the house
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ How to Run It

**1. Install Dependencies**

     ```pip install pandas numpy scikit-learn matplotlib seaborn'''

**2. Load the Dataset**

     ```Place Housing.csv in the project folder.```

**3. Run the Script**

     ```python housing_price_prediction.py

        or open the Jupyter Notebook:

        jupyter notebook Housing_Price_Prediction.ipynb```

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 💻 Sample Input & Output

### Input Example:
# Prediction for New House
```
new_data = pd.DataFrame({
 'area': [7200],
 'bedrooms': [3],
 'bathrooms': [2],
 'stories': [2],
 'mainroad': [1],
 'guestroom': [2],
 'basement': [1],
 'airconditioning': [2],
 'parking': [1],
 'prefarea': [1],
 'furnishingstatus': [1]})
prediction = lre.predict(new_data)
print(f"\nPrediction for new House Price: {prediction[0]}")

```

