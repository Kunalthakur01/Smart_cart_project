# 🛒 SmartCart Customer Analytics & Feature Engineering

A data analytics project focused on cleaning, transforming, and engineering customer data to generate meaningful business insights for SmartCart.

---

## 📖 Project Overview

Customer data is one of the most valuable assets for modern businesses.

This project analyzes SmartCart customer data and performs:

- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Customer Profiling
- Data Transformation
- Exploratory Data Analysis (EDA)

The goal is to prepare customer data for future applications such as:

- Customer Segmentation
- Customer Lifetime Value Prediction
- Marketing Campaign Analysis
- Recommendation Systems

---

## 📊 Dataset Information

Dataset Size:

- 2,240 Customers
- 22 Original Features

Features include:

- Customer Income
- Education Level
- Marital Status
- Purchase History
- Web Purchases
- Store Purchases
- Product Spending
- Campaign Response

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading
Imported customer dataset using Pandas.
### 2. Data Cleaning
Identified missing values.
Found missing values in:
- Income
Handled using median imputation.
### 3. Feature Engineering
Created several business-focused features.
#### Customer Age
#### Customer Tenure
Calculated the number of days since customer registration.
#### Total Spending
Combined spending across all product categories.
Includes:
- Wines
- Fruits
- Meat Products
- Fish Products
- Sweet Products
- Gold Products

#### Total Children

### 4. Data Transformation

#### Education Categories

Converted education levels into broader categories:

- Undergraduate
- Graduate
- Postgraduate

#### Living Status
Categories:
- Partner
- Alone
### 5. Feature Selection
Removed unnecessary columns:
- ID
- Year_Birth
- Marital_Status
- Kidhome
- Teenhome
- Dt_Customer
Also removed raw spending columns after creating Total_spending.
---

### 6. Exploratory Data Analysis

Performed relationship analysis using:
Analyzed:
- Income
- Age
- Total Spending
- Customer Response
- Recency
- Total Children

---

## 📂 Project Structure

```text
smartcart-customer-analytics/
│
├── SmartCart_project.ipynb
├── smartcart_customers.csv
├── README.md
└── images/
```

---

## 📈 Engineered Features

| Feature | Description |
|----------|-------------|
| Age | Customer Age |
| customer_tenure_days | Time since registration |
| Total_spending | Overall customer spending |
| Total_Children | Number of children |
| Living_with | Customer relationship status |

---

## 🎯 Business Applications

The processed dataset can be used for:

- Customer Segmentation
- Marketing Analytics
- Churn Prediction
- Spending Behavior Analysis
- Recommendation Systems
- Customer Lifetime Value Prediction

---

## 📚 Skills Demonstrated

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Data Transformation
- Exploratory Data Analysis
- Business Analytics
- Customer Data Processing

---


## 👨‍💻 Author

**Kunal Singh**

Aspiring AI & Machine Learning Developer

GitHub: https://github.com/Kunalthakur01

⭐ If you found this project useful, consider starring the repository.
