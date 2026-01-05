📊 PhonePe Data Analysis Case Study
📌 Project Overview

This project analyzes digital payment data from PhonePe to understand user behavior, transaction patterns, device usage, and regional trends across India.

The analysis follows a structured data analytics workflow:

Data Understanding & Cleaning

Data Quality Validation

Exploratory Data Analysis (EDA)

Insight Generation & Business Recommendations

🗂 Data Sources

The project uses multiple structured datasets:

State_transaction_and_users

District_txn_and_users

State_txnsplit

State_devicedata

District_demographics

Each dataset represents a different granularity or dimension of PhonePe usage.

🧹 Data Cleaning & Preparation

The following data cleaning steps were performed:

Standardized state and district names for consistent joins

Handled missing and null values in transaction and demographic fields

Corrected data type mismatches (e.g., Year, Quarter as integers)

Removed or flagged zero-value transactions before visualization

Verified column naming consistency across tables

Created derived columns such as:

Year–Quarter

Average Transaction Amount per User

Transaction Type Percentage Share

🔍 Data Quality Validation

To ensure data reliability:

Aggregated district-level data to state level

Compared totals against state-level datasets

Identified minor differences due to floating-point precision

Confirmed no material data loss or duplication

This step validated the dataset for further analysis.

📈 Exploratory Data Analysis (EDA)
1️⃣ Transaction Trends Over Time

Analyzed transaction count and transaction amount by:

State

Year

Quarter

Identified growth patterns and seasonal trends

2️⃣ User Adoption & Engagement

Studied registered users vs app opens

Identified states with:

High adoption but low transaction value

High engagement but lower monetization

3️⃣ Transaction Type Distribution

Analyzed distribution of transaction types:

State-wise

Quarter-wise

Visualized using bar charts and pie charts

Identified dominant and underutilized transaction types

4️⃣ Average Transaction Amount per User

Calculated per-state average transaction amount per user

Identified:

High-value user regions

Micro-transaction dominant states

5️⃣ Device Brand Analysis

Analyzed registered users by:

State

Device brand

Calculated brand-wise user ratios per state

Identified dominant device ecosystems

6️⃣ Demographic Analysis

Merged demographic data with transaction data

Studied:

Population vs registered users

Population density vs transaction value

Found moderate correlation between urban density and adoption

🔑 Key Insights

High transaction volume does not always imply high revenue per user

User behavior varies significantly across states and districts

Device brand dominance influences digital payment adoption

Urban density boosts adoption, but income and literacy drive value

Transaction type diversity increases with user maturity

🚀 Actionable Business Recommendations

Target high-adoption but low-value states with monetization campaigns

Promote advanced transaction types in low-diversity regions

Optimize app performance for dominant device brands

Expand merchant onboarding in high-population, low-usage districts

Design state-specific user engagement strategies

📁 Project Structure
📦 PhonePe-Data-Analysis
 ┣ 📄 Phonepe(case_study).ipynb
 ┣ 📄 README.md
 ┗ 📁 data
