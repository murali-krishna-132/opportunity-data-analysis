# 📊 Week 2 – Exploratory Data Analysis (EDA)

> **Data Visualization Trainee – Early Remote Internship – Excelerate**

## 📌 Project Overview

This repository contains my **Week 2** internship work, focused on **Exploratory Data Analysis (EDA)** of the **Excelerate Opportunity Dataset**.

The objective of this project was to explore the cleaned dataset, identify meaningful trends, assess data quality, generate visual insights, and communicate business findings through statistical analysis and visualization.

The analysis was performed using **Python**, **Pandas**, **NumPy**, and **Matplotlib** in Jupyter Notebook.

---

## 🎯 Objectives

- Perform exploratory data analysis on the Opportunity dataset
- Understand dataset structure and quality
- Analyze opportunity creation trends
- Explore opportunity categories and locations
- Examine fee and microscholarship distributions
- Detect missing values and duplicate records
- Identify correlations and outliers
- Validate logical consistency within the dataset
- Generate actionable business insights

---

## 📂 Dataset Information

- **Dataset:** Opportunity Analysis Ready Dataset
- **Records:** 5,730
- **Columns:** 20
- **Dataset Type:** Opportunity Listings
- **Format:** Microsoft Excel (.xlsx)

### Main Features

- Opportunity ID
- Opportunity Name
- Category
- Role
- Location
- Duration
- Fee
- Microscholarship
- Currency Type
- Created Date
- Last Date to Apply
- Modified Date

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- OpenPyXL
- Jupyter Notebook

---

# 📁 Repository Structure

```
Week-2-Exploratory-Data-Analysis/
│
├── data/
│   └── Opportunity_Analysis_Ready.xlsx
│
├── notebook/
│   └── week2.ipynb
│
├── report/
│   ├── WEEK 2 REPORT.pdf
│   └── WEEK 2 REPORT.docx
│
├── charts/
│   ├── missing_values.png
│   ├── opportunity_trend.png
│   ├── location_analysis.png
│   ├── category_analysis.png
│   ├── fee_distribution.png
│   ├── microscholarship_distribution.png
│   ├── correlation_heatmap.png
│   ├── fee_boxplot.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 📊 Exploratory Data Analysis Modules

### ✅ Module 1

Import Libraries & Load Dataset

- Import required Python libraries
- Load Excel dataset
- Dataset preview
- Dataset information

---

### ✅ Module 2

Data Cleaning

- Remove duplicates
- Convert date columns
- Handle missing values
- Data preparation

---

### ✅ Module 3

Dataset Overview

- Dataset dimensions
- Column summary
- Data types
- Descriptive statistics

---

### ✅ Module 4

Opportunity Creation Trend

- Year-wise opportunity creation
- Trend visualization

---

### ✅ Module 5

Location Analysis

- Opportunity distribution by location
- Top locations

---

### ✅ Module 5A

Missing Value Analysis

- Missing value counts
- Missing value percentages
- Missing value visualization

---

### ✅ Module 5B

Duplicate Analysis

- Duplicate row detection
- Duplicate Opportunity ID check
- Duplicate Code check

---

### ✅ Module 5C

Data Type Summary

- Numerical Features
- Categorical Features
- Datetime Features
- Boolean Features
- Text Features

---

### ✅ Module 6

Opportunity Category Analysis

- Category distribution
- Most popular opportunity categories

---

### ✅ Module 7

Fee Analysis

- Fee distribution
- Statistical summary
- Histogram

---

### ✅ Module 8

Microscholarship Analysis

- Scholarship distribution
- Statistical summary

---

### ✅ Module 9

Correlation & Outlier Detection

- Correlation Matrix
- Heatmap
- Boxplot
- Outlier Detection

---

### ✅ Module 9A

Logical Consistency Checks

- Negative Fee Detection
- Invalid Duration Detection
- Deadline Before Creation Date Validation

---

### ✅ Module 10

Key Findings

- Automated business insights
- Dataset summary
- Final observations

---

# 📈 Visualizations Included

- Opportunity Creation Trend
- Opportunity Categories
- Location Distribution
- Missing Value Analysis
- Fee Distribution Histogram
- Microscholarship Distribution
- Correlation Heatmap
- Fee Boxplot

---

# 🔍 Key Findings

- The dataset contains **5,730** unique opportunity records across **20** features.
- Internship opportunities represent the largest category, followed by Career and Competition.
- Most opportunities are offered in remote formats, primarily **Work From Home** and **Virtual**.
- The majority of opportunities are free, with a small number of premium listings creating a right-skewed fee distribution.
- Microscholarship values are generally standardized, with only a few high-value outliers.
- Opportunity creation peaked during **2023–2024**.
- Significant missing values exist in **role**, **role_responsibility**, and **is_archived**, indicating opportunities for improving data quality.
- Correlation analysis revealed only weak relationships among numerical variables.
- Outlier detection identified high-value fee and microscholarship records that should be considered separately during reporting.
- Logical consistency checks identified records with invalid durations and application deadlines preceding creation dates.

---

# 📌 Business Insights

The analysis demonstrates that the platform is primarily focused on career-oriented and remote opportunities. While the dataset is well-suited for descriptive analytics and reporting, improvements in data completeness, validation rules, and text quality would further enhance reporting accuracy and future analytical capabilities.

---


# 🚀 Future Improvements

- Interactive dashboards using Power BI or Tableau
- Time-series analysis of opportunity growth
- Advanced feature engineering
- Predictive analytics for opportunity trends
- Automated reporting pipelines

---

# 👨‍💻 Author

**Murali Krishna M**

AI-Powered Data Analytics Remote Intern

GitHub: https://github.com/YOUR_USERNAME

LinkedIn: https://linkedin.com/in/YOUR_LINKEDIN

---

## ⭐ If you found this project interesting, consider giving the repository a Star!