# Banking-Domain
#  Banking Dashboard Report

## Overview
This repository contains a **Banking Dashboard Report** created using **Power BI** to analyze and visualize key financial metrics in the banking sector.  
The project focuses on **risk analytics**, helping banks make informed decisions when approving loans and understanding customer financial behavior.


#Key Performance Indicators (KPIs)

| KPI                     | Description                                                     | Formula                                                                                 |
| ----------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **Total Clients**       | Number of unique clients                                        | `DISTINCTCOUNT('Clients - Banking'[Client ID])`                                         |
| **Total Loan**          | Sum of all bank loans + business lending + credit card balances | `[Bank Loan] + [Business Lending] + [Credit Cards Balance]`                             |
| **Total Deposit**       | Total money deposited by investors                              | `[Bank Deposit] + [Savings Account] + [Foreign Currency Account] + [Checking Accounts]` |
| **Total Fees**          | Amount charged by the bank for services                         | `SUMX('Clients - Banking', [Total Loan] * 'Clients - Banking'[Processing Fees])`        |
| **Bank Deposit**        | Total deposit amount                                            | `SUM('Clients - Banking'[Bank Deposits])`                                               |
| **Checking Accounts**   | Daily transactional funds                                       | `SUM('Clients - Banking'[Checking Accounts])`                                           |
| **Saving Accounts**     | Interest-bearing accounts                                       | `SUM('Clients - Banking'[Saving Accounts])`                                             |
| **Credit Card Balance** | Amount owed by customers                                        | `SUM('Clients - Banking'[Credit Card Balance])`                                         |
| **Engagement Account**  | Total engagement duration                                       | `SUM('Clients - Banking'[Engagement Days])`                                             |


# Dashboards & Visualizations

The report includes the following dashboards:
1.Home Dashboard – Summary of all metrics.
2.Loan Analysis Dashboard – Detailed loan distribution by income, gender, and nationality.
3.Deposit Analysis Dashboard – Insights into deposits across different account types.
4.Summary Dashboard – Consolidated KPIs and performance indicators.

#Author
Shubham Landkar
📊 Data Analytics Enthusiast | I Used in this project Python, SQL, Power BI, and Business Intelligence
📧 [Shubhamlandkar13@gamil.com]
🔗 [www.linkedin.com/in/shubham-landkar-7ba685219]
