# Customer Segmentation using K-Means Clustering

This project uses unsupervised machine learning to segment customers into distinct groups based on their purchasing behavior. The goal is to help businesses identify and understand different customer types for targeted marketing and personalized engagement strategies.

---

## 📌 Objective

Group customers based on features such as income and spending score using the K-Means clustering algorithm to uncover natural customer segments.

---

## 🧰 Technologies & Tools

- **Programming Language:** Python 3.x  
- **Libraries:**  
  - `pandas` for data manipulation  
  - `matplotlib` & `seaborn` for visualization  
  - `scikit-learn` for clustering and preprocessing  
  - `numpy` for numerical computations  

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Checked and handled missing values
   - Scaled features using `StandardScaler` to normalize data

2. **Feature Selection**
   - Selected relevant numerical features such as `Annual Income` and `Spending Score`

3. **Optimal k Determination**
   - Used the **Elbow Method** by plotting WCSS (Within-Cluster Sum of Squares) to determine the optimal number of clusters

4. **Model Training**
   - Trained a K-Means model using the optimal number of clusters (k)
   - Predicted cluster labels for each customer

5. **Evaluation & Visualization**
   - Visualized clusters using PCA (Principal Component Analysis) to reduce dimensions
   - Evaluated clustering performance using **Silhouette Score**

---

## 📊 Results

- Identified clear and interpretable customer segments, such as:
  - High-income, low-spending (potential targets)
  - High-income, high-spending (loyal customers)
  - Low-income, high-spending (risky customers)
- Visualized clusters to validate separation and business insights



