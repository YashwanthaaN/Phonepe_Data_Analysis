📊 PhonePe Data Analysis Case Study
📌 Project Overview

This project presents an end-to-end exploratory and analytical study of digital payment transactions using publicly available data from PhonePe.
The analysis focuses on transaction behavior, user adoption, device trends, and regional insights at state and district levels across India.

The objective is to derive actionable business insights using Python, Pandas, Matplotlib, and Seaborn.

🎯 Objectives

Analyze transaction volume and transaction value across states and districts

Study registered user growth and engagement (App Opens)

Understand transaction type distribution

Evaluate device brand usage patterns

Validate data quality by comparing state and district aggregations

Correlate demographic indicators with transaction behavior

🗂 Dataset Description

The dataset contains the following key tables:

Table	Description
State_transaction_and_users	State-level transactions, amounts, users, and app opens
District_txn_and_users	District-level transactions and users
State_txnsplit	Transaction breakdown by type
State_devicedata	Registered users by device brand
District_demographics	Population and density data
🛠️ Tools & Technologies

Python

Pandas & NumPy

Matplotlib & Seaborn

Jupyter Notebook

📈 Key Analysis Performed

State & district-level transaction aggregation

Quarterly and yearly trend analysis

Transaction type distribution (pie & bar charts)

Average transaction amount per user

Device brand penetration per state

Population density vs transaction correlation

Data quality validation checks

🔍 Key Insights

High transaction volume states are not always high-value states

Peer-to-peer and merchant payments dominate transaction types

User adoption is strongly influenced by urban density

Device brand dominance varies regionally

District-level data aggregates consistently to state-level metrics

🚀 Actionable Insights

Increase monetization in high-adoption but low-value states

Target high-value users with premium offerings

Optimize app experience for dominant device brands

Expand merchant onboarding in high-population but low-usage districts

Diversify transaction use cases across regions

📊 Sample Visualizations

Transaction trends over time

Transaction type distribution by state & quarter

Device brand share per state

Population density vs transaction value scatter plots

📁 Project Structure
📦 PhonePe-Data-Analysis
 ┣ 📄 Phonepe(case_study).ipynb
 ┣ 📄 README.md
 ┗ 📁 data

▶️ How to Run

Clone the repository

git clone https://github.com/your-username/phonepe-data-analysis.git


Open the notebook

jupyter notebook Phonepe(case_study).ipynb


Run cells sequentially
