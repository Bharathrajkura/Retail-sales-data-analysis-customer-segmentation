# Retail-sales-data-analysis-customer-segmentation
This project focuses on customer segmentation using the Online Retail dataset. By applying the RFM model (Recency, Frequency, Monetary) and K-Means clustering, customers are grouped into meaningful segments such as loyal customers, big spenders, occasional buyers, and churn risks. 
# 🛒 Customer Segmentation using RFM & K-Means  

## 📌 Project Overview  
This project applies **data analytics and machine learning** to segment retail customers using the **Online Retail dataset**.  
The workflow is based on the **RFM model (Recency, Frequency, Monetary)** and **K-Means clustering**, enabling businesses to identify different types of customers such as **loyal customers, high spenders, discount seekers, and churn risks**.  

---

## ⚙️ Tech Stack  
- **Python** 🐍  
- **Pandas, NumPy** → Data cleaning & RFM feature engineering  
- **Matplotlib, Seaborn, Plotly** → Data visualization  
- **Scikit-learn** → Standardization, K-Means clustering, PCA  

---

## 📊 Project Workflow  
1. **Data Preprocessing**  
   - Loaded Kaggle dataset directly into Colab  
   - Handled missing values, duplicates, and incorrect records  
   - Created RFM features:  
     - **Recency** = Days since last purchase  
     - **Frequency** = Number of transactions  
     - **Monetary** = Total revenue per customer  

2. **Feature Scaling**  
   - Applied `StandardScaler` to normalize RFM values  

3. **Customer Segmentation**  
   - Used **K-Means clustering** to group customers  
   - Determined optimal clusters using the **Elbow Method**  
   - Assigned cluster labels to each customer  

4. **Visualization & Insights**  
   - 2D visualization of clusters using **PCA**  
   - RFM distribution across clusters  
   - Clear business insights for each customer segment  

---

## 🔑 Key Insights  
- **20% of customers contributed nearly 65% of sales**  
- Found clusters of **loyal customers** with high frequency & spend  
- Identified **churn-prone customers** with low recency scores  
- Electronics & seasonal products showed **spike in sales during festivals**  

---


