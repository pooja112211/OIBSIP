# Customer Segmentation Analysis

## Overview

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (Task 2)**.

The main objective of this project is to segment customers into different groups based on their purchasing behaviour using the **K-Means Clustering** algorithm. Customer segmentation helps businesses better understand their customers and create targeted marketing strategies.

---

## Objective

- Analyze customer purchasing behaviour.
- Perform RFM (Recency, Frequency, Monetary) analysis.
- Apply K-Means Clustering to group similar customers.
- Visualize customer segments.
- Provide business insights and marketing recommendations.

---

## Dataset

- **Dataset:** Online Retail Dataset
- The dataset contains customer transaction records, including invoice details, quantity, unit price, customer ID, and purchase date.

**Note:**  
To reduce the repository size, the dataset is stored as a compressed **ZIP file** inside the `datasets` folder. The notebook reads the ZIP file directly using Pandas, so no manual extraction is required.

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
6. Determine the optimal number of clusters using the Elbow Method.
7. Apply K-Means Clustering.
8. Visualize customer segments using scatter plots and bar charts.
9. Profile each customer segment.
10. Provide business insights and marketing recommendations.

---

## Project Results

The customers were successfully divided into **three customer segments**:

- **Cluster 0:** Inactive Customers
- **Cluster 1:** Regular Customers
- **Cluster 2:** High Value (VIP) Customers

Each cluster represents a different purchasing behaviour, helping businesses identify inactive customers, regular customers, and their most valuable customers.

---

## Business Insights

- Most customers belong to the **Regular Customer** segment.
- **Inactive Customers** have not purchased recently and may respond well to promotional offers.
- **High Value (VIP) Customers** contribute the highest revenue and should receive exclusive rewards and personalized services.
- Customer segmentation enables businesses to create targeted marketing campaigns and improve customer satisfaction.

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

```text
DataAnalytics-L1-CustomerSegmentation/
│
├── datasets/
│   └── online_retail.zip
│
├── images/
│
├── notebook/
│   └── Customer_Segmentation_Analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries using:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```
notebook/Customer_Segmentation_Analysis.ipynb
```

4. Run all the cells in sequence.

---

## Conclusion

Customer segmentation is an effective technique for understanding customer behaviour. By using **RFM Analysis** and **K-Means Clustering**, businesses can identify valuable customers, improve customer retention, and develop personalized marketing strategies.

---

## Author

**Pooja Kumari**


