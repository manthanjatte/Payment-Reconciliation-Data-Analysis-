# Payment-Reconciliation-Data-Analysis

This end-to-end data analytics project focuses on streamlining and visualizing insurance payment reconciliation, premium collection trends, and policy renewals. Built using Power BI, the project integrates data from Excel, SQL Server, and includes Python-based preprocessing for cleaning and automation. The dashboard provides actionable insights into payment gateway performance, reconciliation accuracy, and policy activity.

Project Objective

To create a real-time analytics dashboard that:

Automates the reconciliation of payment transactions.
Identifies and visualizes failed transactions and discrepancies.
Tracks premium collection, renewals, and policy activations.
Improves decision-making for finance and operations teams.

Key Skills & Technologies Used

1. SQL (MS SQL Server)
Wrote complex JOINs, CTEs, and Window Functions to merge transaction logs, policy data, and customer information.
Built stored procedures to filter failed and duplicate payments.
Performed data validation checks to identify missing records or inconsistencies in reconciliation.

2. Python (Pandas, NumPy)
Used Python scripts to automate:
Data cleaning from raw Excel exports.
Merging multi-source datasets (e.g., gateways, bank transactions, policies).
Removing duplicates and filling missing values.

3. Power BI
Created an interactive dashboard using:
Live connection to SQL Server for real-time data updates.
Data Modeling: Built relationships between payments, gateways, and policies.
DAX Measures: For calculating KPIs like:
Total Premium Collected
Payment Success Rate
Failed Transactions by Gateway
Active vs Expired Policies
Features:
Drill-down by month, policy type, and payment method.
Visual alerts on failure rates above threshold.
Filters for region, product, and agent.

Dashboard Pages:
Executive Summary
Premium & Revenue Trends
Payment Reconciliation Status
Gateway Performance

Business Impact:
Simulated a 99% reconciliation accuracy by integrating SQL and Python validations.
Reduced hypothetical manual reconciliation time by 60% through automation.
Showcased how financial teams can track payment delays, mismatch errors, and improve operational response times.


