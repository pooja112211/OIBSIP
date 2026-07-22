
# Customer Segmentation Analysis

## Overview

This project is completed as part of the Oasis Infobyte Data Analytics Internship (Task 2).

The main goal of this project is to divide customers into different groups based on their purchasing behaviour using the K-Means Clustering algorithm. Customer segmentation helps businesses understand their customers better and create targeted marketing strategies.

---

## Objective

- Analyze customer purchasing behaviour.
- Perform RFM (Recency, Frequency, Monetary) analysis.
- Apply K-Means clustering to group similar customers.
- Visualize customer segments.
- Provide business insights and marketing recommendations.

---

## Dataset

- **Dataset:** Online Retail Dataset
- The dataset contains customer transaction records, including invoice details, quantity, unit price, customer ID, and purchase date.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

1. Load and inspect the dataset.
2. Clean the data by removing missing values, duplicate records, cancelled orders, and invalid entries.
3. Perform descriptive statistics.
4. Create RFM (Recency, Frequency, Monetary) features.
5. Standardize the data using StandardScaler.
6. Find the optimal number of clusters using the Elbow Method.
7. Apply K-Means Clustering.
8. Visualize customer segments using scatter plots and bar charts.
9. Profile each customer segment.
10. Provide business insights and marketing recommendations.

---

## Project Results

The customers were successfully divided into three different clusters:

- **Cluster 0:** Inactive Customers
- **Cluster 1:** Regular Customers
- **Cluster 2:** High Value (VIP) Customers

Each cluster shows different purchasing behaviour, helping businesses understand which customers need re-engagement and which customers should be rewarded for their loyalty.

---

## Business Insights

- Most customers belong to the Regular Customer segment.
- Inactive customers may return with discounts and promotional offers.
- High Value customers contribute the highest revenue and should receive exclusive benefits.
- Customer segmentation helps businesses improve marketing strategies and customer satisfaction.

---

## Visualizations

The project includes the following visualizations:

- Elbow Method Graph
- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot
- Customers per Cluster Bar Chart
- Cluster Profile Bar Chart

---

## Project Structure

```
DataAnalytics-L1-CustomerSegmentation
│
├── dataset/
├── images/
├── notebook/
├── README.md
└── requirements.txt
```

---

## Conclusion

Customer segmentation is an effective technique for understanding customer behaviour. By using RFM analysis and K-Means clustering, businesses can identify valuable customers, improve customer retention, and create personalized marketing campaigns.

---

## Author

**Pooja Kumari**

Oasis Infobyte Data Analytics Intern
