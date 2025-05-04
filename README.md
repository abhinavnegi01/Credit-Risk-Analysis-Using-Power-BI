# Credit-Risk-Analysis-Using-Power-BI
A Data-Driven Approach to Understand Loan Defaults and Borrower Risk

## Overview

This project aims to analyze credit risk by examining historical loan data and uncovering patterns that lead to loan defaults. Built entirely using Microsoft Power BI, the project delivers an interactive dashboard that helps financial analysts and lending institutions assess borrower profiles and improve decision-making processes.

## Objectives

- Identify the key factors that influence loan default rates.
- Segment borrowers by financial and behavioral attributes.
- Develop a custom risk score for evaluating loan applications.
- Simulate interest rate changes using What-If analysis.
- Deliver a business-ready, interactive dashboard with insights.

## Dataset

- *Source*: Provided dataset containing 3,000+ loan records.
- *Fields include*: Loan amount, interest rate, income, credit history length, employment length, home ownership, loan purpose, loan grade, and default status.

## Tools Used

- *Power BI* for data modeling, visualization, DAX, and dashboard design.
- *Power Query* for data cleaning and transformation.
- *DAX* for calculated columns and measures (e.g., risk score, loan-to-income ratio).
- *Power BI Service* for sharing and publishing reports with Row-Level Security.

## Key Features

### 1. *Data Cleaning and Preparation*
- Removed missing values, handled incorrect types.
- Created new metrics such as loan-to-income ratio.

### 2. *Custom Risk Scoring Model*
- Developed a weighted formula using:
  - Loan amount
  - Income ratio
  - Credit history length
  - Employment stability
  - Default history

### 3. *Visualizations & Insights*
- Scatter plots, bar charts, line charts, and slicers.
- Key dashboards:
  - Loan grade vs. default rate and interest.
  - Borrower segmentation by home ownership and employment.
  - Loan intent analysis.
  - Risk trends by credit history.
  - What-If simulation for interest rate adjustments.

### 4. *What-If Analysis*
- Simulated how changes in interest rates impact default risk using a dynamic parameter.

### 5. *Dashboard Design*
- Interactive KPIs and clean layout.
- Color-coded for ease of interpretation (e.g., red = risky loans).
- Tooltips and slicers enhance usability.

## Recommendations

- Target low-risk borrower segments (e.g., Grade A/B).
- Apply stricter filters for business and debt consolidation loans.
- Use risk scoring and credit history insights during underwriting.
- Implement dynamic pricing strategies based on risk level.
