# Business-Intelligence-Analysis-of-Superstore-Sales
Superstore sales BI pipeline in Python, from data cleaning through OLTP/OLAP modeling to an interactive dashboard.

# Superstore Sales Business Intelligence Project

An end-to-end business intelligence (BI) project that turns raw retail sales data into insights that support decisions. Using the Superstore sales dataset, the project follows the BI progression of **data → information → knowledge → action**: storing transactions, summarizing them for analysis, visualizing the results, and reflecting on the security, privacy, and ethical responsibilities that come with using business data.

## Overview

Business intelligence is the set of processes, technologies, and practices that convert raw operational data into information that supports better decisions (Sharda et al., 2018). This project applies that idea to a retail dataset, with analytics providing the methods that move from raw records to actionable findings.

> **Note:** A machine learning model was not required for this project and was not built.

## BI Process

| Step | Stage | Description |
|------|-------|-------------|
| 1 | **Import** | Load the Superstore sales data into Python using pandas |
| 2 | **Explore & Clean** | Inspect the data, check data types, and handle missing values and duplicates |
| 3 | **OLTP Simulation** | Store individual sales transactions in an OLTP-style database |
| 4 | **OLAP Aggregation** | Summarize transactions by region, category, segment, and time period |
| 5 | **Dashboard & Interpretation** | Present the results in a dashboard and interpret them |

## Tech Stack

- **Python** (pandas)
- **SQLite / SQL** for the OLTP-style transaction store
- **Matplotlib / Seaborn / Plotly** for visualization
- **Jupyter Notebook**

## Dashboard
<img width="2717" height="2267" alt="Week1_BI_OLAP_Dashboard" src="https://github.com/user-attachments/assets/48e81930-c907-4580-99df-a5e167eb0af6" />

## Security, Privacy & Ethics

**Security:** Protecting stored transaction data from unauthorized access
**Privacy:** Handling customer-level information responsibly and limiting exposure of personal details
**Ethics:** Using data transparently and avoiding misleading conclusions or unfair treatment of customer groups

## Reference

Sharda, R., Delen, D., & Turban, E. (2018). *Business intelligence, analytics, and data science: A managerial perspective* (4th ed.). Pearson.

