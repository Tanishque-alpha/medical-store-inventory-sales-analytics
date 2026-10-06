# medical-store-inventory-sales-analytics
The medical store has 2,600 records but no summary of what sells, what earns, and what needs restocking. So i do the data cleaning and EDA of the medical store dataset of transactions and master medicine along with its sells analysis.Also made a seperate Pivot table for nearby expiry medicines. 

# Medical Store Inventory & Sales Analytics

A beginner-friendly data analytics project using Google Sheets to analyse
medical-store sales and inventory data.

## Problem
The store has 2,600 transaction records but no summary of what sells, what
earns money, and what needs restocking.

## Data
- transactions: 2,600 rows (Transaction_ID, Date, Medicine_ID, Transaction_Type, Quantity)
- medicine_master: 25 medicines (name, category, expiry date, purchase rate, MRP, selling rate)

## What I did
1. Data cleaning: 18 validation checks, 17 pass, 1 flagged for review
2. Data preparation: sales amount, profit, expiry status, restock priority
3. Analysis: KPIs and pivot-style summary tables
4. Dashboard: 6 KPI cards and 6 charts
5. Insights and recommendations

## Key findings
- Revenue ₹1,811,440, gross margin 29.8%
- Diabetes is 28.6% of revenue from only 3 of 25 medicines
- Insulin Injection earns 20.9% of revenue from 4.5% of units sold
- 9 medicines are high-priority for restocking

## Dashboard
![Dashboard](images/dashboard.png)

## Limitations
No stock column in the data, so restock need uses the sold-to-purchased ratio.

## Tools
Google Sheets (COUNTIF, SUMIFS, INDEX/MATCH, SUMPRODUCT)

## Files
- workbook/: the full analysis workbook
- report/: the project report
- data/: source data
