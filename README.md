# **Hospital Waitlist Management Dashboard**

## Problem Statement
Hospitals face ongoing challenges in **managing patient waitlists** effectively.  
Without proper tracking, delays in treatment can occur, leading to **longer waiting times**, reduced operational efficiency, and a poor patient experience.  

The goal of this project is to provide **real-time insights** into patient waitlists by:
- Tracking current status of inpatient and outpatient waitlists.
- Analyzing **24 months of historical data** to identify trends and seasonal peaks.
- Highlighting high-backlog specialties and age groups for better decision-making.

---

## Project Overview
This project delivers an **end-to-end Power BI solution**, transforming raw datasets into actionable healthcare insights.  
The dashboard helps hospital management **visualize and manage patient flow**, ensuring resources are allocated efficiently to reduce delays.

The analysis focuses on:
- Comparing **Inpatient vs. Outpatient** backlog over time.
- Identifying **top 5 specialties** driving the highest backlog.
- Understanding wait times across **age profiles** and **time bands**.
- Monitoring **monthly trends** to predict future capacity needs.

---

## Dataset
- **Source:** [Kaggle - Hospital Waiting List Management Dataset](https://www.kaggle.com/datasets/michaelbeanie/hospital-waiting-list-management-dataset)  
- The dataset contains **8 CSV files**:
  - 4 **Inpatient files** (`2018–2021`)
  - 4 **Outpatient files** (`2018–2021`)

### Main Columns
| Column Name      | Description |
|------------------|-------------|
| **Archive_Date** | Month of record, used for trend analysis |
| **Specialty_Name** | Medical specialty such as Cardiology, Orthopedics, etc. |
| **Case_Type** | Type of case: Inpatient, Day Case, or Outpatient |
| **Age_Profile** | Patient age group (`0-15`, `16-35`, `36-50`, `50+`) |
| **Time_Bands** | Waiting time ranges (`0-3`, `4-6`, `6-12`, `18+` months) |
| **Total** | Total patients in that group and month |

---

## Dashboard Features
The dashboard consists of **two main pages**:

### **1. Executive Summary Page**
- **2 KPIs:**
  - Total Inpatients  
  - Total Outpatients  
- **Visuals:**
  - Donut chart for **case type split**.  
  - Clustered column chart for **Age Profile vs. Time Band**.  
  - **Top 5 Specialties** using a multi-row card.  
  - Line chart showing **historical monthly trend** of patient waitlists.
- **Slicers:** Archive Date, Case Type, Specialty.

---

### **2. Detailed View Page**
- Interactive **matrix visual** showing:
  - Archive Date  
  - Specialty Name  
  - Age Profile  
  - Time Bands  
  - Case Type  
  - Total Patients  
- Dynamic slicers for deeper drill-down analysis.

---

## Key Insights
- **60% of the backlog** is driven by just **5 specialties**, helping prioritize hospital resources effectively.  
- Patients **aged 50+** face the **longest waiting times**, with many exceeding **18 months**, indicating a critical area for improvement.  
- Seasonal peaks in backlog observed during certain months, supporting **proactive planning** for high-demand periods.

---

## Tech Stack
- **Power BI** – Dashboard design and data visualization  
- **DAX** – For KPI calculations and dynamic measures  
- **Excel/CSV** – Source data files from Kaggle  
- **GitHub** – Project documentation and version control

---

## Key Insights
- 60% of total backlog comes from just 5 specialties.
- Patients aged 50+ face the longest wait times, with many waiting over 18 months.
- Seasonal peaks were observed, indicating the need for proactive resource planning.

