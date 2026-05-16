

# 📊 Online Retail Data Analysis (UK E-Commerce Dataset)

## 🧾 Project Overview

This project presents an exploratory data analysis (EDA) of an online retail dataset from a UK-based e-commerce store. The dataset captures transactions over an eight-month period and includes information such as product descriptions, quantities, invoice details, customer IDs, and pricing.

The goal of this analysis is to uncover meaningful business insights around:

* Sales performance
* Customer behavior
* Product performance
* Returns and losses
* Revenue distribution patterns

---

## 🎯 Objectives

* Clean and prepare raw transactional data for analysis
* Handle missing values and identify data anomalies
* Separate sales, returns, and non-product transactions
* Analyze revenue trends across time, geography, and customers
* Identify top-performing and high-loss products
* Understand customer concentration and purchasing behavior
* Extract business-relevant insights for decision-making

---

## 🛠️ Tools & Libraries Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Dataset Features

Key columns include:

* InvoiceNo
* StockCode
* Description
* Quantity
* InvoiceDate
* UnitPrice
* CustomerID
* Country

---

## 🧹 Data Cleaning & Preparation

Key cleaning steps included:

* Handling missing values in `CustomerID` and `Description`
* Removing non-product transactions (fees, postage, bank charges, discounts, commissions)
* Separating sales and return transactions
* Creating a revenue column (`Quantity × UnitPrice`)
* Filtering out invalid or operational-only entries

---

## 📊 Key Analyses Performed

### 📈 Sales Performance

* Monthly revenue trends showed peak sales during September–December
* November recorded the highest revenue, indicating seasonal demand

### 🌍 Geographic Analysis

* The United Kingdom dominated total revenue
* Other countries contributed significantly less, showing limited international penetration

### 📦 Product Analysis

* A small number of products generated most of the revenue
* Strong product concentration observed among top-performing SKUs

### ↩️ Returns Analysis

* Return losses were concentrated in a few products
* Certain items consistently contributed to high negative revenue impact

### 👤 Customer Analysis

* Revenue is moderately concentrated among top customers
* Top 10 customers contributed ~13% of total revenue

---

## 🔗 Key Insights

* Strong seasonal sales pattern with peak during year-end months
* Heavy reliance on UK market for revenue generation
* Clear product concentration in revenue contribution
* Moderate customer concentration (no extreme dependency)
* Return losses are product-specific rather than evenly distributed

---

## ⚠️ Data Limitations

* Missing `CustomerID` values limited full customer segmentation
* Some transactions were untraceable to individual customers
* Non-product entries required careful filtering to avoid analysis distortion

---

## 📌 Final Conclusion

The analysis reveals a well-performing retail business with strong domestic dominance, seasonal sales behavior, and a small number of products and customers driving a significant share of revenue. While performance is strong, opportunities exist in international expansion, return reduction, and customer base diversification.

---


## 🚀 Future Improvements

* Build predictive sales models
* Customer segmentation (RFM analysis)
* Time series forecasting
* Dashboard creation (Power BI / Tableau)

---

## 👤 Author

**Benita Adakeja**

