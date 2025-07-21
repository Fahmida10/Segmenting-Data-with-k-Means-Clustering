
# Customer Segmentation using k-Means Clustering

This project performs customer segmentation using **k-Means Clustering** on mall customer data to identify groups with similar spending and income behavior.

## 📌 Objective

The goal is to divide customers into distinct clusters based on their annual income and spending score. This helps businesses understand customer types and tailor marketing strategies accordingly.

## 📁 Dataset

- **Filename**: `Mall_Customers.csv`
- **Source**: [Kaggle - Mall Customers Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)
- **Features used**:
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## ⚙️ Methodology

1. **Data Preprocessing**
   - Selected only relevant numeric features (`Annual Income`, `Spending Score`)
   - Applied **feature scaling** using `StandardScaler` for better clustering performance

2. **Optimal Cluster Selection**
   - Used **WCSS (Within-Cluster Sum of Squares)
   - Evaluated using **average silhouette score** to validate cluster separation

3. **Modeling**
   - Applied **k-Means Clustering** from `sklearn`
   - Visualized final cluster assignments using scatter plots

## 📊 Results

- Identified **5 distinct customer segments**
- Clusters show clear patterns based on income and spending score
- Insights can inform targeted marketing and product strategies

## 🧠 Tools & Libraries

- Python (Colab)
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn` (KMeans, StandardScaler, silhouette_score)

## 💻 Notebook

👉 [`Customer_segmentation.ipynb`](Customer_segmentation.ipynb)

## 🚀 Future Improvements

- Try other clustering algorithms (DBSCAN, hierarchical)
- Include more features (e.g., Age, Gender, Purchase History)
- Build an interactive Streamlit web app

## 👩‍💻 Author

**Fahmida Ananna**  
[GitHub Profile](https://github.com/Fahmida10)
