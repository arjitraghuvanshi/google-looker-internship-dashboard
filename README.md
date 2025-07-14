# Google Looker Studio Internship Project – Sales Analytics Dashboard

This repository showcases the final project I completed as part of my internship with **Nullclass**, focused on real-time data analytics using **Google Looker Studio**. 
The goal was to build an interactive, insightful sales dashboard based on provided e-commerce data, applying concepts learned during the training phase.

---

## 🔗 Live Dashboard

📊 [Click here to view the published Looker Studio dashboard](https://lookerstudio.google.com/reporting/4e15bd8a-9196-4473-8e7e-462d3e15c97e)

---

## 📌 Project Objectives

The internship required designing two core dashboards to support business analysis and decision-making:

### 🧩 Task 1: Average Order Value (AOV) Trend – 2022

- **Objective:** Analyze monthly changes in AOV during 2022
- **Calculation:** `SUM(after_discount) / COUNT_DISTINCT(id)`
- **Visualization:** Line chart grouped by month
- **Interactive Filter:** Date range limited to 2022

### 🧩 Task 2: Sales Performance by Payment Method

- **Objective:** Compare different payment methods by total sales, units sold, and profit
- **Metrics Used:**
  - Total Sales → `SUM(before_discount)`
  - Quantity Sold → `SUM(qty_ordered)`
  - Net Profit → `SUM(after_discount - cogs)`
- **Visualization:** Pivot table with heatmap styling
- **Filters Included:** Month selector and custom **quarter grouping**

---

## 🧰 Tools & Technologies

The project involved working across multiple tools, including:

- **SQL Workbench** – for early-stage data querying and inspection
- **Jupyter Notebook** – for dataset exploration and validation
- **Google Looker Studio** – for building final interactive dashboards
- **Microsoft Word / PDF** – for documenting and reporting
- **GitHub** – for organizing and presenting deliverables

---

## 📷 Dashboard Screenshots

### 🔹 Page 1: Campaign Performance Overview  
![Page 1](./screenshots/Page1_Campaign_Overview.png.png)

### 🔹 Page 2: Customer & Sales Summary  
![Page 2](./screenshots/Page2_Customer_Summary.png.png)

### 🔹 Page 3: AOV Monthly Trend – 2022  
![Page 3](./screenshots/Page3_AOV_Trend.png.png)

### 🔹 Page 4: Sales & Profit by Payment Method  
![Page 4](./screenshots/Page4_Payment_Analysis.png.png)

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Google Looker Dashboard.pdf` | Exported dashboard (all 4 pages) |
| `/screenshots/` | Individual PNG files of each dashboard page |
| `README.md` | This document (project summary and links) |

---

## 👨‍💼 Author

**Arjit Raghuvanshi**  
Final Internship Submission  
[Nullclass – Real-Time Analytics Internship](https://nullclass.com)

---

## ✅ Project Status

🟢 **Completed** — Ready for evaluation and stipend review
