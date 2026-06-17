# Workforce Attrition & Risk Analysis

## Overview
An end-to-end workforce analytics project analyzing employee attrition patterns and predicting flight risk using the IBM HR Analytics dataset (1,470 employee records, 35 variables).

## Business Problem
Organizations often focus on absolute attrition numbers, which can be misleading. This project demonstrates how rate-based analysis reveals different priorities than volume-based analysis — directly relevant to workforce planning and retention strategy decisions.

## What This Project Includes
* **Data Cleaning:** Identified and corrected data quality issues; validated all 1,470 records for completeness
* **Feature Engineering:** Created Age Band, Tenure Band, and a rule-based Flight Risk Score using satisfaction, compensation, and tenure variables
* **Multi-Pivot Analysis:** Built and cross-referenced multiple pivot tables using VLOOKUP to calculate attrition rates by department
* **Predictive Risk Model:** Segmented all employees into High/Medium/Low flight risk categories
* **Dashboard:** Built a single-page executive dashboard with key visuals and insights

## Key Insights
* Sales (20.63%) and HR (19.05%) have higher attrition **rates** than R&D (13.84%), despite R&D having more total leavers in absolute numbers — a rate-based view changes where retention budget should be prioritized
* 41 employees (2.8%) are flagged High Risk based on low satisfaction, low income, and frequent job changes
* 478 employees (32.5%) fall into Medium Risk and are candidates for proactive retention engagement

## Tools Used
Microsoft Excel (Pivot Tables, VLOOKUP, conditional formulas, data visualization)

## Dataset
IBM HR Analytics Employee Attrition Dataset (Kaggle)

## Author
Urvi Shetty | MBA Business Analytics | [LinkedIn](https://linkedin.com/in/urvi-shetty-72a7071a2)
