
# 👥 Customer Segmentation Analysis

## 📌 Objective

The goal of this project is to conduct a **customer segmentation analysis** for an e-commerce business. By analyzing customer demographics, behavior, and purchase patterns, we aim to classify customers into distinct groups using clustering techniques. This segmentation will support personalized marketing and strategic decision-making.

---

## 📂 Dataset

* **File Name**: `ifood_df (1).csv`
* **Description**: Contains information about customer demographics, spending habits, and interactions with the brand.

### 🧾 Example Features:

* `Income`
* `Age`, `Education`, `Marital_Status`
* `Spending on various product categories`
* `Number of purchases and campaign responses`
* `Days since last purchase`

---

## 🛠️ Tools and Libraries Used

* **Python**
* **Pandas** – Data analysis and wrangling
* **NumPy** – Numerical calculations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Clustering algorithms (e.g., K-Means), preprocessing

---

## 🔍 Steps Performed

### 1. **Data Exploration & Cleaning**

* Loaded the dataset and checked for missing or duplicate values.
* Cleaned inconsistent entries (e.g., malformed categories).
* Handled null values appropriately.

### 2. **Descriptive Statistics**

* Computed basic metrics:

  * **Average income**
  * **Total spending by category**
  * **Purchase frequency**
  * **Response to campaigns**
* Visualized distributions and customer behavior trends.

### 3. **Feature Engineering**

* Combined or normalized relevant columns for clustering (e.g., total spending, campaign engagement).
* Scaled features using **StandardScaler**.

### 4. **Customer Segmentation (Clustering)**

* Applied **K-Means Clustering** to segment customers based on behavior.
* Determined optimal number of clusters using the **Elbow Method** and **Silhouette Score**.
* Assigned cluster labels to each customer.

### 5. **Visualization**

* Created:

  * **Scatter plots** to show clusters
  * **Bar plots** for spending comparison across segments
  * **Box plots** to highlight differences in income, age, etc.

### 6. **Insights & Recommendations**

* Profiled each customer segment:

  * **High-income, high-spending customers**
  * **Young, low-engagement customers**
  * **Frequent buyers vs one-time purchasers**
* Suggested:

  * Personalized email campaigns
  * Loyalty programs for top-spenders
  * Re-engagement strategies for inactive customers

---

## 📈 Outcome

* Identified **3–5 unique customer segments** with distinguishable behaviors.
* Enabled **data-driven marketing strategies** tailored to each group.
* Provided a deeper understanding of customer base to boost **retention and conversion**.

---

## ✅ Conclusion

This project highlights the power of **unsupervised learning** and **data analytics** in understanding customer behavior. Effective segmentation can significantly enhance personalization efforts and long-term business growth.


