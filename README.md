# 📊 PhonePe Data Analysis Case Study

## 📌 Project Overview
This project analyzes digital payment data from **:contentReference[oaicite:0]{index=0}** to understand transaction behavior, user adoption, device usage, and regional patterns across India.  
The analysis follows a structured analytics workflow: data cleaning → data validation → exploratory data analysis → business insights.

---

## 🗂 Data Sources
The project uses multiple datasets at different granularities:
- State-level transactions and users  
- District-level transactions and users  
- Transaction type breakdown  
- Device brand usage  
- District demographics (population and density)

---

## 🧹 Data Cleaning & Preparation
The following cleaning steps were performed:
- Standardized state and district names for consistent joins  
- Corrected data types for Year and Quarter columns  
- Handled missing and null values in transaction and demographic fields  
- Removed zero-value transactions before visualization  
- Ensured column name consistency across tables  
- Created derived metrics such as:
  - Year–Quarter
  - Average Transaction Amount per User
  - Transaction Type Percentage Share

---

## 🔍 Data Quality Validation
To ensure reliability:
- Aggregated district-level metrics to state level  
- Compared results with state-level tables  
- Verified differences were only due to floating-point precision  
- Confirmed no data duplication or loss

---

## 📈 Exploratory Data Analysis (EDA)

### Transaction Trends
- Analyzed transaction count and amount by state, year, and quarter  
- Identified growth patterns and seasonality  

### User Adoption & Engagement
- Compared registered users with app opens  
- Identified states with high adoption but low monetization  

### Transaction Type Distribution
- Studied transaction type mix by state and quarter  
- Identified dominant and underutilized transaction categories  

### Average Transaction Amount per User
- Calculated per-state average transaction value per user  
- Highlighted high-value vs micro-transaction regions  

### Device Brand Analysis
- Analyzed registered users by device brand and state  
- Calculated brand-wise user share per state  

### Demographic Analysis
- Merged population and density data with transactions  
- Studied the relationship between urban density and usage  

---

## 🔑 Key Insights
- High transaction volume does not always imply high revenue per user  
- User behavior varies significantly across regions  
- Device brand dominance influences adoption patterns  
- Urban density increases adoption, but value depends on income and literacy  
- Transaction diversity grows as users mature  

---

## 🚀 Actionable Recommendations
- Improve monetization in high-adoption but low-value states  
- Promote advanced transaction types in low-diversity regions  
- Optimize app experience for dominant device brands  
- Expand merchant onboarding in high-population, low-usage districts  
- Design state-specific engagement strategies  

---

## 📁 Project Structure
PhonePe-Data-Analysis/
│
├── Phonepe(case_study).ipynb
├── README.md
└── data/
