# AtliQ Hardware - Sales & Finance Analytics

This repository serves as my documentation for the **AtliQ Hardware Sales & Finance Analytics Excel Project**. It was created as a **self-learning project** with guidance from **Codebasics**.

The entire project has been implemented using **Microsoft Excel 2016**.

> **Note:** The project files have not been uploaded to this repository in compliance with Codebasics Data & Content Distribution Policy.

---
## Contents
Below are the sectional links for the project:

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Source and Tools](#Data-Source-and-Tools)
- [Data Model](#Data-Model)
- [Tools Used & Methodologies Implemented](#Tools-Used)
- [About the Dataset](#about-the-dataset)
- [Data Integrity](#data-integrity)
- [Analysis Insights](#Analysis-Insights)

---
## Introduction
**Domain:** FMCG  |  **Functions:** Sales & Finance

AtliQ Hardwares is a company that sells **computer hardware and peripherals** like **PCs, mice, printers**, etc., to clients across the world.

- **Business Model:** Primarily **B2B**, selling to major stores like **Croma, Best Buy, Staples, Flipkart**, which then sell to end consumers.
- **Sales Channels:**
  - **Retailer Channel:**
    - **Brick & Mortar Customers**: Physical stores (e.g., Croma, Best Buy)
    - **E-commerce Customers**: Online platforms (e.g., Amazon, Flipkart)
  - **Direct Channel:**
    - **AtliQ E-store & AtliQ Exclusive** (Owned stores)
  - **Distributor Channel:**
    - Operates in restricted trade countries (e.g., Neptune)

---
## Problem Statement
AtliQ Hardwares has been facing **significant losses** in recent years. Business decisions have been based on **handwritten reports**, making data-driven decision-making difficult. 

### **Business Requirement:**
The **Data Analyst team** has been tasked with preparing an **Excel Analysis Report** focused on **Sales and Financial Performance** by analyzing data from **multiple files containing over 1.5 million records**. The goal is to derive insights that will **boost business growth**.


## Data Source and Tools
![Data Sources](Images/Picture3.png)

### Analysis Tool & Skills
- **Microsoft Excel**:
  - Power Query
  - Pivot Table
  - Power Pivot
  - Data Modelling
  - DAX Measures & Columns
  - Conditional Formatting

---

## Data Model

### Entity Relationship Diagram:
![ERD](Images/image.png)


---
## Tools Used
- **Microsoft Excel** – Data Cleaning, Data Analysis & Visualization
- **Microsoft PowerPoint** – Project Presentation
- **DataWrapper** – Insights Visuals
- **GitHub** – Documentation

---
## Skills & Methodologies Implemented
- **Data Cleaning:** ETL, Power Query
- **Data Manipulation:** VLOOKUP, INDEX-MATCH, XLOOKUP, Table Joining, DAX Measures & Columns
- **Data Modeling & Normalization**
- **Data Visualization:** Pivot Table, Power Pivot, Conditional Formatting
- **Documentation**

---
## About the Dataset
### **Data Sources:** Sales & Finance
| Table Name                      | Records | Columns |
|---------------------------------|---------|---------|
| dim_customer                    | 189     | 5       |
| dim_market                      | 23      | 3       |
| dim_product                     | 298     | 6       |
| fact_sales_monthly              | 799,962 | 5       |
| ns_targets_2021                 | 276     | 3       |
| fact_sales_monthly_with_cost     | 799,962 | 7       |

### **Data Dictionary:** *(To be added)*

---
## Data Integrity
### **ROCCC Evaluation:**
- **Reliability:** MED – Dataset created and updated by Codebasics, consisting of 6 files.
- **Originality:** HIGH – First-party provider (Codebasics).
- **Comprehensiveness:** MED – Contains parameters for Customers, Products & Markets, plus detailed Sales & Finance transaction data.
- **Currentness:** LOW – Last updated in 2021, making it **obsolete** for current analysis.
- **Citation:** LOW – No official citation/reference available.

---

## Analysis Insights

Click on the links below to open the detailed reports:

- [📌 Customer Performance Report](https://github.com/amrit4385/Excel-Sales_Analytics/blob/main/Customer%20Performance%20Report.pdf)
- [📌 Market Performance vs Target Report](https://github.com/amrit4385/Excel-Sales_Analytics/blob/main/Market%20Performance%20vs%20Target%20Report.pdf)
- [📌 P&L Statement by Fiscal Year](https://github.com/amrit4385/Excel-Sales_Analytics/blob/main/P&L%20Statement%20by%20Fiscal%20Year.pdf)
- [📌 P&L Statement by Markets](https://github.com/amrit4385/Excel-Sales_Analytics/blob/main/P&L%20Statement%20by%20Markets.pdf)
- [📌 P&L Statement by Months](https://github.com/amrit4385/Excel-Sales_Analytics/blob/main/P&L%20Statement%20by%20Months.pdf)

📢 **Note:** Ensure all PDFs are placed in the `files` folder in your repository.

