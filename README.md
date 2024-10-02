# 🍔 Fast Food Sales Prediction & Customer Segmentation

## 📖 Overview
Analyze and predict sales for a fast food restaurant using linear regression and K-Means clustering to enhance inventory and sales strategies.

## 📊 Features
- **Data Preprocessing**: Clean and prepare sales data.
- **Visualization**: Insights on orders by day, time, and customer demographics.
- **Customer Segmentation**: Cluster customers based on purchasing behavior.
- **Sales Prediction**: Predict item sales using linear regression.

## 📅 Dataset
- **Source**: [Fast Food Sales Dataset](https://drive.google.com/file/d/1Qxw5Ak84PGE416Uyai6ivSxkq9BiiFTa/view?usp=sharing)
- **Key Columns**: 
  - `order_id`: Unique identifier for each order
  - `date`: Date of the order
  - `item_name`: Name of the food item
  - `item_type`: Type of item (e.g., Fastfood, Beverages)
  - `item_price`: Price of the item
  - `quantity`: Quantity sold
  - `transaction_amount`: Total transaction amount
  - `transaction_type`: Type of transaction (e.g., Cash, Online)
  - `gender`: Gender of the customer
  - `time_of_sale`: Time when the order was placed

## 🚀 Getting Started
### Prerequisites
Install the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
