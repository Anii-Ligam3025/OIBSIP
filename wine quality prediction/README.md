
# 🍷 Wine Quality Prediction

## 📌 Objective

The goal of this project is to **predict the quality of wine** based on its **chemical characteristics** using machine learning classification algorithms. This project simulates a real-world application of AI in the field of **viticulture and food sciences**.

---

## 📂 Dataset

* **File Name**: `WineQT.csv`
* **Source**: Contains samples of red/white wines with chemical composition and quality scores.
* **Target Variable**: `quality` (integer rating, typically 0–10)

### 🧪 Example Features:

* `fixed acidity`, `volatile acidity`, `citric acid`
* `residual sugar`, `chlorides`, `free sulfur dioxide`
* `density`, `pH`, `sulphates`, `alcohol`

---

## 🛠️ Tools and Libraries Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models and preprocessing

---

## 🔍 Steps Performed

### 1. **Data Exploration & Cleaning**

* Loaded dataset using Pandas and checked for missing or null values.
* Explored distributions, correlations, and outliers among chemical features.
* Visualized pairwise relationships and quality distribution using Seaborn and Matplotlib.

### 2. **Feature Analysis**

* Analyzed correlation heatmap to identify key predictors of wine quality.
* Standardized features for better model performance using `StandardScaler`.

### 3. **Model Building (Classification)**

Three classification algorithms were trained and evaluated:

* **Random Forest Classifier** – An ensemble method with decision trees
* **Stochastic Gradient Descent (SGD) Classifier** – A linear classifier optimized with SGD
* **Support Vector Classifier (SVC)** – A kernel-based margin classifier

### 4. **Model Evaluation**

* Split data into **training and test sets** (80/20).
* Evaluated models using metrics:

  * **Accuracy**
  * **Confusion Matrix**
  * **Classification Report (Precision, Recall, F1-score)**

### 5. **Visualization**

* Plotted model performance comparison.
* Visualized:

  * **Feature importance** (Random Forest)
  * **Decision boundaries** (for 2D feature combinations)
  * **Confusion matrices**

---

## 📈 Outcome

* All models were trained and evaluated, and performance was compared.

* Example Results (replace with actual results after training):

  * **Random Forest Accuracy**: \~78%
  * **SGD Accuracy**: \~66%
  * **SVC Accuracy**: \~72%

* Random Forest generally provided the best balance of **accuracy and robustness**.

---

## ✅ Conclusion

This project demonstrates the practical application of **classification algorithms** in predicting product quality using measurable features. Insights from this model can assist wine producers in **quality control, product development, and optimization** of chemical compositions for better customer satisfaction.

