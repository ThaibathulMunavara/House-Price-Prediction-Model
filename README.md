# 🏠 Housing Price Prediction

## 📌 Project Overview

### This project aims to build a machine learning model that predicts the price of a house based on various features such as area, number of bedrooms, number of bathrooms, and more. The goal is to help real estate agencies, buyers, and sellers estimate fair market prices.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

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

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features / What it Does

- Predicts house prices using machine learning algorithms. <br>
- Supports multiple property attributes (e.g., area, bedrooms, stories, parking). <br>
- Handles both numerical and categorical data.<br>
- Easy to extend with advanced models like Random Forest or XGBoost or Linear Regression model using sklearn.linear_model. <br>
- Split data into train-test sets. <br>
- Evaluate model using MAE, MSE, R². <br>
- Plot regression line and interpret coefficients. <br>

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ How to Run It

**1. Install Dependencies**

     pip install pandas numpy scikit-learn matplotlib seaborn

**2. Load the Dataset**

     Place Housing.csv in the project folder.

**3. Run the Script**

     python housing_price_prediction.py

     **or open the Jupyter Notebook** 

     jupyter notebook Housing_Price_Prediction.ipynb

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 💻 Sample Input & Output

### Input Example:

#### Prediction for New House
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

### Output Example:
Prediction for new House Price: 3742558777.808896

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📸 Screenshot

### Heatmap for Correlation 
<img width="990" height="612" alt="download" src="https://github.com/user-attachments/assets/e2fb96d8-2eca-4515-b846-24661c2c32ea" />

### Plot Regression Line & Interpret Coefficients
<img width="554" height="455" alt="download" src="https://github.com/user-attachments/assets/9d87c7f1-9e05-4309-becd-02d58db910bf" />

### Plot Feature coefficient with bar chart
<img width="578" height="533" alt="download" src="https://github.com/user-attachments/assets/005fdf07-2b64-46ce-b8b4-671d668c7f6e" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👨‍💻 Author & GitHub Profile Link

### Author: Thaibathul Munavara N R 
### GitHub: [github.com/yourusername](https://github.com/ThaibathulMunavara)




