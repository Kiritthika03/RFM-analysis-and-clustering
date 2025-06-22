# RFM-analysis-and-clustering
# 📊 RFM Analysis and Customer Segmentation Using K-Means Clustering

This project uses RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment customers based on their purchasing behavior from a retail transactions dataset.

---

## 🧠 Project Objective

To analyze customer transaction data and uncover meaningful customer segments using:
- 📅 **Recency** – How recently a customer made a purchase  
- 🔁 **Frequency** – How often they make purchases  
- 💵 **Monetary** – How much they spend on average

These insights are then used to create **customer clusters** using the **K-Means algorithm** for targeted marketing and business decision-making.

---

## 🛠️ Tools and Libraries

- Python 🐍
- Pandas & NumPy – Data manipulation
- Seaborn & Matplotlib – Data visualization
- Scikit-learn – KMeans Clustering
- Jupyter Notebook – Analysis platform

---

## 📂 File Overview

- `RFM_analysis_and_clustering.ipynb` – Complete code and visualization notebook
- `Retail_Transactions_Dataset.csv` – Transaction dataset (not included for privacy)
- `README.md` – Project documentation
- `requirements.txt` – Python package dependencies

---

## 📈 Methodology

### 🔍 Step 1: Exploratory Data Analysis (EDA)
- Cleaned and transformed transaction data
- Analyzed trends:
  - Seasonal and yearly total cost
  - Most purchased products
  - Popular payment methods

### 📊 Step 2: RFM Analysis
Calculated:
- **Recency** – Days since last transaction
- **Frequency** – Number of transactions
- **Monetary** – Average amount spent

### 🎯 Step 3: K-Means Clustering
- Applied K-Means on scaled RFM data
- Identified **3 customer segments**:
  - **Cluster 0:** 🛑 Churned Customers
  - **Cluster 1:** 🟡 Potential Customers
  - **Cluster 2:** ✅ Loyal Customers

### 📉 Visuals
- Pairplot of clusters
- Pie chart showing cluster distribution
- RFM distribution histograms

---

## 💡 Key Insights

- Majority of customers fall into "Churned" and "Potential" categories, offering room for retention strategies.
- "Loyal" customers contribute significantly to revenue, justifying personalized marketing.
- Purchase volume peaks during the **Fall season**.
- **Toothpaste** is the most purchased product.

---

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rfm-customer-segmentation.git
cd rfm-customer-segmentation
