# Travel Insurance Claims Analysis

## 📝 Description

📊 Comprehensive exploratory data analysis on the Travel Insurance Dataset, focusing on:

- 💰 Claim acceptance patterns and customer behavior
- 🧳 Product performance across agencies & agency types
- ⚠️ Data quality issues affecting business insights
    
This project includes 🧠 a collaborative Colab Notebook, 📂 dataset, and 📘 README for reproducibility and business insights.

## 🔍 Data Overview

This Kaggle dataset is from a third-party travel insurance servicing company that is based in Singapore.

The attributes:
1. Claim Status (Claim.Status)
2. Name of agency (Agency)
3. Type of travel insurance agencies (Agency.Type)
4. Distribution channel of travel insurance agencies (Distribution.Channel)
5. Name of the travel insurance products (Product.Name)
6. Duration of travel (Duration)
7. Destination of travel (Destination)
8. Amount of sales of travel insurance policies (Net.Sales)
9. Commission received for travel insurance agency (Commission)
10. Gender of insured (Gender)
11. Age of insured (Age)

## 🚀 Project Overview
This repository explores customer behavior and claim outcomes in travel insurance data.
With over 63K records, the analysis uncovers imbalances in claim acceptance, highlights top-performing products, and evaluates data reliability.

## 💡🧭📊 Key Findings

### 💰Claims Analysis

#### Based on the number of claims made, what does this tell us about customer behaviour?
- Over **63K claims** & >1K accepted claims
- ✅ **Claim acceptance rate <2%** indicates major imbalance
- The agency **🏢 EPX** accounts for >50% of claims

#### Should the insurance company be concerned?
- Yes the insurance company should be concerned about **>98% of rejections**
- 🌏 Singapore appears most frequently as the destination for claims
- 🏢 EPX agency accounts for ~35K rejections; C2B, CWT, and JZI follow with 6K+ rejections

### 🧳Product Performance

#### Looking at the unique product names, which products appear most frequently?
- ✈️ Top products for airlines: Basic Plan, Bronze Plan & Value Plan
- 🏖️ Top products for travel agencies: Cancellation Plan, 2 Way Comprehensive Plan & Rental Vehicle Excess Plan

#### What recommendation would you make to the marketing team?
- Focus more on ✈️ Airlines
- Acceptance is high for the 🏖️ travel agency top 3 produtcs
- Acceptance in ✈️ Airlines is high for Bronze Plan, Annual Silver Plan & Silver Plan

### ⚠️Data Quality

#### Did you notice anything unusual in the data (missing values, unexpected patterns)?


#### How might this affect business decisions🧠?
- The low quality data is not suitable for modeling & reporting
- This affects the performance of the **marketing team** as the decisions based on Age and gender are can be erroneous due to missing data and unrealistic values. 
- Also it affects the **finance team** to conclude business revenues due to missing & unrealistic sales & commision data.
