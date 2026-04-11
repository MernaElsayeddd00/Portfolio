# CallVa Automated Monthly Performance Dashboard

**Automated ETL Pipeline + Executive Looker Studio Dashboard**  
*For the General Manager – Real-time monthly insights across all departments*

![CallVa Logo](https://via.placeholder.com/150x50/6B46C1/FFFFFF?text=CallVa)  
*(Replace with actual logo if you have one)*

## 📋 Project Overview

At **CallVa**, an outsourcing call center company, the General Manager needed a **single source of truth** to track monthly performance across **Sales, Financials, Account Management, and HR**.

Previously, each department director maintained their own Google Sheet, forcing the GM to manually consolidate data every month.  

I designed and built a **fully automated ETL pipeline** that pulls data from the 4 department sheets, cleans and merges it, and feeds a professional **Looker Studio dashboard** — giving the GM instant answers to his most important business questions.

## 🎯 Business Questions Answered for the GM

### Sales
- How many deals did we close this month?
- What is the total revenue and average deal value?
- What are the **Sales Conversion Rate %** vs **Tele Conversion Rate %**?

### Financials
- What is the **Total Revenue**, **Operational Cost**, and **Net Profit**?

### Account Management
- How many **Total Clients**, **New Clients**, and **Churned Clients**?
- What is the **Clients Churn Rate %**?

### HR
- How many **New Employees** and **Active Employees**?
- What is the **Employees Turnover Rate %**?

## 🚀 Key Achievements & Impact

- **Complete automation** of a previously manual 4–6 hour monthly process
- **Zero manual copy-paste** → eliminated human errors
- **One-click monthly refresh** for the GM
- **Saved significant time and resources** for department directors and leadership
- Scalable solution — new months are added automatically
- Professional executive dashboard built in Looker Studio

## 🛠️ Tech Stack

- **Python 3**
- **pandas** – Data cleaning & transformation
- **gspread + Google Sheets API** – Read/write Google Sheets
- **Google Service Account (OAuth2)** – Secure authentication
- **Looker Studio** – Interactive dashboard
- **Google Drive API** – Required for service account access

## 📁 Project Structure
