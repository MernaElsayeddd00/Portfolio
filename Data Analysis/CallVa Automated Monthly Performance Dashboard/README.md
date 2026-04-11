# CallVa Automated Monthly Performance Dashboard

**End-to-End Automated ETL Pipeline + Executive Looker Studio Dashboard**  
Built for the **General Manager** of CallVa – an outsourcing call center company

## Project Overview

The General Manager at CallVa needed a **single, up-to-date monthly overview** covering all key departments: **Sales, Financials, Account Management, and HR**.

Before this project, each department director maintained their own Google Sheet. Consolidating the data manually every month was time-consuming, error-prone, and delayed decision-making.

I designed and implemented a **fully automated ETL pipeline** that:
- Pulls data from the **4 separate department Google Sheets**
- Cleans, standardizes, and merges everything by month
- Writes the combined data into a master sheet
- Feeds a clean, interactive **Looker Studio dashboard** tailored for the GM

This solution eliminated manual work and gave the GM instant visibility into the company’s monthly performance.

## Key Questions Answered for the General Manager

The dashboard directly answers the GM’s most important monthly questions:

### Sales Department
- How many deals were closed this month? (Total Deals)
- What is the total revenue generated from these deals? (Total Deals Value)
- What is the average deal value?
- How do the **Sales Conversion Rate %** and **Tele Conversion Rate %** compare?

### Financials
- What is the **Total Revenue**, **Operational Cost**, and **Net Profit** this month?

### Account Management
- How many **Total Clients**, **New Clients**, and **Churned Clients**?
- What is the **Clients Churn Rate %**?

### HR
- How many **New Employees** were added?
- What is the current number of **Active Employees**?
- What is the **Employees Turnover Rate %**?

## Live Dashboard

** [View Interactive CallVa Performance Dashboard] ([https://lookerstudio.google.com/reporting/YOUR_ACTUAL_LINK_HERE](https://lookerstudio.google.com/reporting/f0fe8a55-f1e8-4ba5-95e6-1118f860536e))**

This link opens the **real-time, fully interactive** Looker Studio dashboard that the General Manager uses.  
You can filter by month, explore the charts, and see all KPIs live.

### Static Preview
[Download Dashboard Preview PDF](CallVa_Performance_Dashboard_Preview.pdf)

## Automation & Business Impact

- **Transformed a manual 4–6 hour monthly process** into a fully automated pipeline that runs in seconds.
- **Eliminated repetitive copy-paste work** and reduced human errors to zero.
- **Saved significant time and resources** for department directors (no longer need to prepare consolidated reports) and for the GM (no more manual gathering of data).
- Department directors now only fill their own sheets — the rest is automatic.
- The GM can now access a professional, always-up-to-date dashboard with one click every month.
- Scalable: New months are automatically added without any extra effort.

This project demonstrates real business value through automation, data integration, and executive reporting.

## Tech Stack

- Python (pandas)
- gspread & Google Sheets API
- Google OAuth2 Service Account (credentials.json)
- Google Drive API
- Looker Studio (for the interactive dashboard)



