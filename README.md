# Canadian-Real-Estate-Data-Pipeline
End-to-End Data Pipeline for Canadian Real Estate Data
🏡 Canadian Real Estate Data Pipeline & Fraud Detection
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![OOP](https://img.shields.io/badge/Design-OOP-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

Data Cleaning | Outlier Detection | Fraud Analysis | OOP Design

Unlock Housing Insights | Detect Anomalies | Build Scalable Pipelines

## 🌍 Overview

With the rapid growth of Canada’s housing market, analyzing real estate data has become increasingly important for investors, analysts, and policymakers. 
This project focuses on building a data pipeline for Canadian real estate listings, with an emphasis on:

Data cleaning and preprocessing
Outlier detection
Fraudulent listing identification
Object-Oriented Programming (OOP) design

The goal is to transform raw, messy housing data into clean, reliable, and actionable insights.

## 🔍 Dataset Overview

This project uses a synthetic real estate dataset designed to simulate real world housing data across major Canadian cities such as:
* Toronto
* Vancouver
* Mississauga
* Brampton

### 📁 Features Included:

`price: Property price
area: Size (sq ft)
bedrooms: Number of bedrooms
bathrooms: Number of bathrooms
city: Location

### ⚠️ Data Challenges Simulated:

Missing values (nulls)
Extreme outliers (very high prices)
Fraud cases (low price + large area in prime locations)

## 📊 Visualizations

### 📦 Boxplot (Outlier Detection)

![box_plot](https://github.com/user-attachments/assets/8591c3c4-5476-40d5-aef4-f1dc2d4526de)


👉 Helps identify extreme price values


### 📊 Price vs Area Scatter Plot
![scatter_plot](https://github.com/user-attachments/assets/25971269-4b4e-4c20-8233-ab5a4be67adb)

### 📊 Distribution of Rental Prices in Canada

![distribution_of_rent](https://github.com/user-attachments/assets/6a6ce1f9-2e42-4f18-b610-c5162c566487)

### 📊 Average Rental Price by Canadian City

![avg_rent_by_city](https://github.com/user-attachments/assets/f21914c0-659f-4ed2-8638-d85c5fd56a01)



---

### 🧹 Data Cleaning

* Removed null values using:

* Replaced missing values using:

  * Mean / Median strategies


### 📦 Outlier Detection

Used IQR (Interquartile Range) method:

Q1 (25th percentile)
Q3 (75th percentile)
IQR = Q3 - Q1


---

### 🚨 Fraud Detection Logic

Fraud is identified using:

```python
price_per_unit = price / area
```

Listings with unusually low price per unit are flagged as suspicious.


## 🏗️ OOP Architecture

The pipeline is designed using Object-Oriented Programming:

###  Classes Implemented:

Apartment: Represents a single property
Manager Handles null values
Datapipeline Performs:
Null checks
Data Cleaning
Outlier detection
Fraud detection


### 🔐 Encapsulation

Controlled access via getters and setters

---

### ✅ Benefits:

Modular design
Reusable components
Clean and scalable structure

## ⚠️ Limitations

Synthetic dataset may not reflect real-world complexity
Fraud patterns are simplified
Price distribution may be artificially skewed


## 🔐 Ethical Considerations

If applied to real world Canadian data:

Must comply with PIPEDA regulations
Avoid bias in:
Location
Socioeconomic factors
Ensure:
Data anonymization
Transparency in decisions

## 📈 Results & Insights

Outlier detection successfully identified extreme price values
Fraud detection flagged unrealistic listings (cheap large properties)
Log transformation improved detection accuracy

---

## 🚀 Future Work

Integrate real-world datasets (MLS / APIs)
Add machine learning models for prediction
Implement anomaly detection using:
Isolation Forest
DBSCAN
Build dashboard (Tableau/Power BI)


## 🎯 Conclusion

This project demonstrates how a structured data pipeline can:

✔ Clean messy real estate data
✔ Detect anomalies effectively
✔ Identify potential fraud cases
✔ Scale using OOP design principles


## ⭐ If You Like This Project

Give it a ⭐ on GitHub and feel free to connect!

