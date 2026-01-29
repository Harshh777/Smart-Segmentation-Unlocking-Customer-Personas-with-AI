# 🧠 Smart Segmentation: Unlocking Customer Personas with AI

## 📌 Project Overview
This project focuses on **customer segmentation using unsupervised machine learning techniques** to uncover meaningful customer personas based on demographic and behavioral attributes.  
By combining **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and **Clustering Algorithms**, the project demonstrates how AI can be used to drive data-driven business and healthcare marketing decisions.

The analysis is performed using a real-world customer dataset and implemented entirely in **Python using Jupyter Notebook**.

---

## 🎯 Objectives
- Understand customer demographics and spending behavior
- Analyze relationships between key features such as **Gender, Income, and Spending Score**
- Apply **Feature Engineering** to enhance clustering performance
- Identify optimal customer segments using **K-Means Clustering**
- Interpret clusters to derive actionable insights

---

## 📂 Dataset Description
The dataset contains customer-level information including:

| Feature | Description |
|------|------------|
| CustomerID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands |
| Spending Score (1-100) | Spending behavior score |

---

## 🛠️ Technologies & Tools Used
- **Python**
- **Jupyter Notebook**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Scaling and clustering algorithms

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA phase includes:
- Dataset structure and missing value analysis
- Descriptive statistics
- Distribution analysis of Age, Income, and Spending Score
- Gender-based spending behavior analysis
- Pairwise feature visualization

### Key Insight:
- Female customers generally exhibit **higher spending scores**
- Spending Score shows stronger behavioral patterns than income alone

---

## 🔧 Feature Engineering
To improve clustering quality, a new feature was engineered:

### **Spending Efficiency**
\[
Spending\ Efficiency = \frac{Spending\ Score}{Annual\ Income}
\]

#### Why this feature?
- Captures **relative spending behavior**
- Differentiates customers with similar incomes but different spending habits
- Improves cluster separation and interpretability

---

## 📊 Clustering Approach

### Features Used for Clustering
- Annual Income (k$)
- Spending Score (1–100)
- Spending Efficiency (Engineered Feature)

### Scaling
- StandardScaler applied to normalize feature ranges

### Optimal Cluster Selection
- **Elbow Method** used to determine the optimal number of clusters
- Optimal value identified at **K = 5**

### Algorithm
- **K-Means Clustering**

---

## 📈 Cluster Visualization
- Scatter plots used to visualize customer segments
- Clear separation achieved after feature engineering
- Engineered feature significantly improves clustering clarity

---

## 🧩 Cluster Interpretation

| Cluster Type | Description |
|------------|------------|
| High Income – High Spending | Premium customers |
| Low Income – High Spending | Impulsive spenders |
| High Income – Low Spending | Conservative customers |
| Low Income – Low Spending | Budget-conscious customers |
| Moderate Group | Balanced spenders |

---

## ✅ Key Outcomes
- Feature Engineering significantly enhances clustering performance
- Behavioral features outperform raw demographic attributes
- Unsupervised learning effectively reveals hidden customer personas
- Project demonstrates strong practical application of AI in analytics

