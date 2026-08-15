# Customer Segmentation with RFM & K-Means

## Project Overview
This project segments customers based on their purchasing behavior using RFM analysis and K-Means clustering. The goal is to identify meaningful customer groups and provide actionable business recommendations.

## RFM Features
- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer makes purchases.
- **Monetary:** How much a customer spends.

## Method
- Cleaned and prepared transaction data
- Created Recency, Frequency, and Monetary features
- Applied log transformation to reduce skewness
- Standardized the features using StandardScaler
- Evaluated different numbers of clusters using inertia and silhouette scores
- Applied K-Means clustering
- Analyzed and visualized the resulting customer segments

## Customer Segments
- **Cluster 0 – Recent/Occasional Customers:** Recent customers with relatively low purchase frequency and spending.
- **Cluster 1 – Loyal High-Value Customers:** Frequent, high-spending customers who purchased recently.
- **Cluster 2 – Regular Customers:** Moderately active customers with opportunities for increased engagement.
- **Cluster 3 – At-Risk/Inactive Customers:** Customers who have not purchased recently and have low purchase frequency.

## Business Recommendations
- Encourage repeat purchases from recent customers through personalized offers.
- Retain high-value customers using loyalty rewards and exclusive offers.
- Increase engagement among regular customers through targeted promotions and cross-selling.
- Re-engage inactive customers using special discounts and personalized reminders.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn

## Kaggle Notebook
View the complete analysis on [Kaggle](https://www.kaggle.com/code/bolaalonge/customer-segmentation-with-rfm-k-means)
