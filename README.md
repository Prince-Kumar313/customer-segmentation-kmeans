# customer-segmentation-kmeans
Customer segmentation using K-means clustering
# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on customer segmentation using K-Means clustering. The goal is to group customers based on their income, spending behavior, and purchasing patterns to help businesses make data-driven decisions.

---

## 📊 Dataset
The dataset contains customer information such as:
- Income
- Total Spending (MntTotal)
- Number of Purchases (Web & Store)
- Recency (Last purchase)

---

## ⚙️ Steps Performed

1. Data Cleaning
   - Removed unnecessary columns
   - Checked for missing values

2. Feature Selection
   - Selected important features:
     - Income
     - MntTotal
     - NumWebPurchases
     - NumStorePurchases
     - Recency

3. Data Scaling
   - Applied StandardScaler to normalize data

4. Clustering
   - Used K-Means algorithm
   - Created 3 clusters

5. Visualization
   - Scatter plot of Income vs Spending

6. Analysis
   - Used groupby to understand each cluster

---

## 🔍 Key Insights

### 🟣 Cluster 0 (Premium Customers)
- High income & high spending
- Frequent buyers

👉 Strategy:
- Loyalty programs
- Premium offers

---

### 🔵 Cluster 1 (Inactive Customers)
- Low spending
- High recency (inactive)

👉 Strategy:
- Discounts & re-engagement campaigns

---

### 🟢 Cluster 2 (Low Spenders)
- Low income & low spending
- Recently active

👉 Strategy:
- Upselling & combo offers

---

## 🚀 Conclusion
Customer segmentation helps businesses target different customer groups effectively, leading to better marketing strategies and increased revenue.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- Matplotlib
- Scikit-learn

---

## 📌 Author
Prince Kumar
