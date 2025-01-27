# Bank Loan Analysis Project

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dashboards](#dashboards)
  - [Dashboard 1: Summary](#dashboard-1-summary)
  - [Dashboard 2: Overview](#dashboard-2-overview)
  - [Dashboard 3: Details](#dashboard-3-details)
- [Dataset](#dataset)
- [SQL Queries](#sql-queries)
- [Tableau Dashboards](#tableau-dashboards)
- [Video Demonstration](#video-demonstration)
- [How to Use](#how-to-use)
- [License](#license)

## Overview
This project analyzes a bank's loan performance using SQL for data validation and Tableau for visualization. The aim is to gain insights into loan applications, funded amounts, repayments, and trends, enabling better decision-making and strategy refinement.

## Problem Statement
We aim to create a report to evaluate the bank's lending activities, track loan performance, and identify trends to improve strategies. Key objectives include:
- Monitoring loan application volumes and trends.
- Assessing funded and repaid amounts.
- Evaluating average interest rates and debt-to-income (DTI) ratios.
- Differentiating between good loans (fully paid or current) and bad loans (charged off).

## Dashboards

### Dashboard 1: Summary
Focuses on essential KPIs, including:
- **Total Loan Applications** (Monthly and MoM comparison)
- **Total Funded Amount** (Monthly and MoM comparison)
- **Total Amount Received** (Monthly and MoM comparison)
- **Average Interest Rate** and **Average DTI Ratio**
- **Good Loan KPIs** and **Bad Loan KPIs**
- **Loan Status Grid View** to display detailed loan status metrics.

### Dashboard 2: Overview
Provides visual insights through:
- **Monthly Trends (Line Chart):** Highlights seasonal patterns in loan metrics.
- **Regional Analysis (Map):** Lending data by state.
- **Loan Term Analysis (Donut Chart):** Loan distribution by term length.
- **Employee Length Analysis (Bar Chart):** Job history impact on loans.
- **Loan Purpose Breakdown (Bar Chart):** Categories like debt consolidation, refinancing.
- **Home Ownership Analysis (Tree Map):** Loans grouped by borrowers’ home ownership.

### Dashboard 3: Details
A comprehensive, user-friendly dashboard offering detailed loan performance data to facilitate quick and informed decisions.

## Dataset
The dataset contains critical loan metrics. A PowerPoint presentation (`Dataset_Details.pptx`) is included to explain each column for users unfamiliar with the terminology.

## SQL Queries
The SQL file (`BankLoanAnalysis.sql`) includes all the queries used to validate and verify the Tableau dashboard results.

## Tableau Dashboards
Screenshots of the three Tableau dashboards (`Dashboard_1.png`, `Dashboard_2.png`, `Dashboard_3.png`) are provided for quick reference.

## Video Demonstration
A video guide (`Demo.mp4`) is included to walk through the dashboards and highlight key insights.

## How to Use
1. Clone this repository.
2. Review the dataset details in the PowerPoint file.
3. Run the SQL queries on the provided dataset for validation.
4. Open the Tableau dashboards for interactive data visualization.
5. Watch the video demonstration for a guided tour of the dashboards.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
