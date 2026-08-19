# 📊 Statistical Analysis of Brazilian E-Commerce Data

## 📌 Project Overview

This project performs an end-to-end statistical analysis of the Brazilian E-Commerce Public Dataset by Olist.

The analysis focuses on understanding customer purchasing behavior, payment patterns, delivery performance, product categories, seller
performance, freight costs, and customer satisfaction.

The project combines **data cleaning, exploratory data analysis, descriptive statistics, statistical testing, and business interpretation** to transform raw transactional data into actionable business insights.

---

## 🎯 Business Problem

Olist is a major Brazilian e-commerce marketplace with data distributed across multiple relational datasets.

The objective of this project is to understand customer purchasing behavior, payment preferences, delivery performance, and factors associated with customer satisfaction.

The analysis also aims to identify statistically significant relationships and differences that can support data-driven business decisions.

---

## 🎯 Project Objectives

- Import and understand multiple datasets
- Perform data cleaning and preprocessing
- Merge relational datasets
- Conduct Exploratory Data Analysis (EDA)
- Apply descriptive statistics
- Analyze relationships between important variables
- Perform hypothesis testing
- Identify statistically significant relationships and group differences
- Translate statistical findings into business recommendations

---

# 📂 Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**.

The dataset contains multiple related CSV files representing different aspects of the e-commerce business.

### Main Datasets

| Dataset | Description |
|---|---|
| Customers | Customer location details |
| Orders | Order status and timestamps |
| Order Items | Products purchased in each order |
| Payments | Payment methods, installments, and payment values |
| Products | Product information |
| Reviews | Customer review scores |
| Sellers | Seller information |
| Product Category Translation | Portuguese-to-English product category translation |
| Geolocation | Brazilian geographic information |

The datasets are related through identifiers such as `order_id`, `customer_id`, `product_id`, and `seller_id`.

---

# 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Scikit-posthocs**
- **Jupyter Notebook**

---

# 🔄 Project Workflow

```text
Raw E-Commerce Data
        ↓
Data Loading
        ↓
Data Inspection
        ↓
Data Cleaning & Preprocessing
        ↓
Dataset Integration
        ↓
Exploratory Data Analysis
        ↓
Descriptive Statistics
        ↓
Correlation Analysis
        ↓
Hypothesis Testing
        ↓
Post-hoc Analysis
        ↓
Statistical Findings
        ↓
Business Recommendations
