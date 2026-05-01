# 📊 Customer Behavior & Spending Analysis

## 📌 Overview

This project focuses on analyzing customer data to understand purchasing behavior, spending patterns, and channel preferences. The analysis is performed using Exploratory Data Analysis (EDA), feature engineering, and hypothesis-driven techniques to derive meaningful business insights.

---

## 🎯 Objectives

* Analyze customer demographics and their impact on purchasing behavior
* Identify spending patterns across product categories
* Evaluate customer preferences across different sales channels (web, store, catalog)
* Perform data cleaning and preprocessing on real-world data
* Validate business hypotheses using data-driven analysis

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Power BI

---

## 📂 Dataset Description

The dataset contains customer-level information, including:

* Demographics: Age, Education, Marital Status, Country
* Financial data: Income
* Product spending: Wines, Fruits, Meat, Fish, Sweets, Gold
* Purchase behavior: Web, Catalog, and Store transactions
* Marketing campaign responses

---

## 🔧 Data Preprocessing

* Removed currency symbols and converted the Income column to numeric format
* Handled missing values using group-based imputation (Education and Marital Status)
* Standardized and consolidated categorical variables
* Applied encoding techniques for categorical data

---

## ⚙️ Feature Engineering

* Created **Age** from Year of Birth
* Calculated **Total Spending** across all product categories
* Derived **Total Purchases** across multiple channels
* Computed **Total Children** to represent household composition
* Created additional features to enhance analysis

---

## 📊 Exploratory Data Analysis

* Analyzed data distributions using histograms and boxplots
* Detected and treated outliers using the IQR method
* Generated a correlation heatmap to identify relationships between variables

---

## 🧠 Hypothesis Testing

### 1. Age vs Shopping Preference

Older customers showed higher purchases in both store and online channels.
**Result:** Not fully supported

---

### 2. Customers with Children vs Online Shopping

Customers without children demonstrated higher online purchasing behavior.
**Result:** Not supported

---

### 3. Channel Cannibalization

A positive relationship was observed between store and online purchases.
**Result:** No evidence of cannibalization

---

### 4. Country-wise Purchasing Behavior

Spending varied across countries, with certain regions showing higher average spending.
**Result:** Supported

---

## 📈 Key Insights

* Higher-income customers tend to spend more across multiple product categories
* Customers exhibit multi-channel purchasing behavior
* Increased website visits do not always lead to higher purchases
* Geographic factors influence customer spending patterns

---

## 📊 Dashboard

An interactive dashboard was created using Power BI to visualize:

* Customer segments
* Channel performance
* Country-wise spending
* Key business insights

---

## 🚀 Conclusion

The project provides valuable insights into customer behavior, enabling better decision-making for marketing strategies, customer targeting, and business growth.

---



