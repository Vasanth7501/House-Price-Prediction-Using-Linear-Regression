# 🏠 House Price Prediction using Linear Regression

This project uses Linear Regression to predict house prices based on various features like area, number of bedrooms, bathrooms, furnishing status, and more.

---

## 📌 Project Overview

The objective is to build a machine learning model that accurately predicts the **price of a house** given several input features. This is a classic **supervised regression problem**.

---

## 📂 Dataset

- **File**: `Housing.csv`
- **Features include**:
  - `Area` — Size of the house (in square feet)
  - `Bedrooms` — Number of bedrooms
  - `Bathrooms` — Number of bathrooms
  - `Furnishing Status` — Furnished / Semi-furnished / Unfurnished
  - `Parking` — Parking availability
  - `Price` — Target variable (house price)

---

## 🧹 Data Preprocessing

- Handled missing values and duplicates.
- Converted categorical variables using one-hot encoding.
- Split data into training and testing sets using `train_test_split`.

---

## 📊 Exploratory Data Analysis (EDA)

- Visualized data distribution and outliers using:
  - Histograms
  - Scatter plots (`Area vs Price`)
  - Correlation heatmap using Seaborn

---

## 🤖 Model Used

- **Linear Regression** from `scikit-learn`
- Assumes a linear relationship between input features and house price.

---

## 📈 Model Evaluation

- Evaluated using:
  - **R² Score**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
- Also plotted **actual vs predicted prices** for visual inspection.

---

## ✅ Results

- The model achieved an R² score of approximately **0.80**, meaning it explains 80% of the variance in house prices.
- Predicts price fairly well for most mid-range houses.
- Great baseline model for structured tabular data.

---

## 🔮 Future Work

- Apply **Random Forest**, **XGBoost**, or **Polynomial Regression** for improved accuracy.
- Add more features like `location`, `age of house`, or macroeconomic indicators.
- Deploy model using **Streamlit** or **Flask API**.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 🧑‍💻 Author

**Vasanth B**  
_Machine Learning & Data Analytics Enthusiast_  
[LinkedIn](www.linkedin.com/in/vasanth-b-050778244) 

---

## 📄 License

This project is licensed under the MIT License.

