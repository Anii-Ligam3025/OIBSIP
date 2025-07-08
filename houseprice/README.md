

# 🏠 Predicting House Prices with Linear Regression

## 📌 Objective

The objective of this project is to develop a predictive model using **Linear Regression** to estimate house prices based on various numerical and categorical features. This project demonstrates essential steps in a machine learning workflow—data cleaning, preprocessing, model training, evaluation, and visualization.

---

## 📂 Dataset

* **File Name**: `Housing.csv`
* **Records**: 545 rows
* **Features**: 12 input features and 1 target variable (`price`)

### 🧾 Key Features:

* **Numerical**: `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
* **Categorical**: `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`
* **Target Variable**: `price` (house price)

---

## 🛠️ Tools and Libraries Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Machine learning model, preprocessing, and metrics

---

## 🔍 Steps Performed

### 1. **Data Exploration & Cleaning**

* Loaded the dataset using Pandas.
* Checked for missing values (none found).
* Explored distributions and relationships between variables.

### 2. **Preprocessing**

* Converted categorical variables to numeric using **one-hot encoding**.
* Ensured all features were suitable for regression modeling.

### 3. **Feature Selection**

* Included all features for initial modeling.
* Optionally, performed correlation analysis to identify strongest predictors.

### 4. **Model Training**

* Split the data into training and test sets (80/20).
* Trained a **Linear Regression** model using Scikit-learn’s `LinearRegression()`.

### 5. **Model Evaluation**

* Evaluated performance using:

  * **Mean Squared Error (MSE)**
  * **R-squared Score (R²)**
* Assessed model accuracy and residual patterns.

### 6. **Visualization**

* Plotted **Actual vs Predicted Prices**.
* Created residual distribution plots to examine prediction errors.

---

## 📈 Outcome

* The linear regression model successfully learned the relationship between house features and prices.
* Example metrics (replace with your actual values after training):

  * **R² Score**: \~0.67
  * **MSE**: \~5.2e+12

These results indicate that the model captures the trend in house pricing moderately well, but can be further improved using feature engineering or advanced models like Ridge/Lasso or tree-based regressors.

---

## ✅ Conclusion

This project demonstrates the end-to-end process of applying linear regression to a real-world problem: **predicting house prices**. It reinforces foundational concepts in data preprocessing, modeling, evaluation, and result interpretation.
