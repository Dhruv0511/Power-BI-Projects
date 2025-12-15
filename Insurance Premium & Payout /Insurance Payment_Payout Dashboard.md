# 📊 Insurance Premium & Payout Dashboard (Power BI)

## 📌 Project Overview
This project is an **enterprise-style Power BI dashboard** designed to analyze **insurance premiums, payouts, investment value, maturity value, and sales performance** across the full insurance policy lifecycle.

The dashboard simulates how insurance stakeholders—such as leadership, finance, sales, and operations—interact with data dynamically to evaluate performance, obligations, and profitability.

> ⚠️ All data used in this project is **synthetic and business-simulated**.  
> No real customer, company, or confidential information is included.

---

## 🎯 Business Objectives
The dashboard is built to help answer key insurance business questions:

- How are premiums distributed across products, regions, and sales agents?
- How do **investment values compare with maturity outcomes** over time?
- How effectively do premiums translate into **coverage and protection value**?
- What trends exist in **premium paid vs premium payable**, especially for long-duration policies?
- How does performance vary across the **sales hierarchy**, from zonal managers to individual agents?

---

## 📂 Dashboard Pages & Features

### 1️⃣ Summary
Provides a high-level snapshot of the insurance portfolio.  
This page helps users quickly orient themselves before exploring detailed analysis.

---

### 2️⃣ Insurance Overview
A highly interactive page driven by a **Visual Parameter (Field Parameter)**.

Users can dynamically switch the metric displayed across visuals without changing the layout.

**Available metrics:**
- Annual Growth Amount  
- Annual Growth Rate  
- Total Annual Premium  
- Total Premium Amount  
- Total Premium Paid  
- Total Premium Payable  
- Underwriting Expense  

**Slicers available:**
- Policy Type  
- Policy Name  
- Sales Agent  
- Year  
- State  
- Occupation  

---

### 3️⃣ Investment Value vs Maturity Value
Focuses on comparing **customer investment value** against **maturity value** over time.

Filters allow analysis by:
- Policy
- Sales Agent
- Geography
- Year

This page helps identify segments where maturity outcomes diverge from invested amounts.

---

### 4️⃣ Annual Premium vs Protection Value
Analyzes the relationship between:
- **Annual premium contributions**
- **Protection / sum assured value**

This view helps assess coverage efficiency across policy types and tenures.

---

### 5️⃣ Premium Analysis (5–20 Years)
Designed for **medium- to long-term policy analysis**.

**Key feature:**
- **Payment Bucket slicer**
  - Payable in 5, 10, 15, 20 years
  - Beyond 20 years

This page compares:
- Total Premium Paid  
- Total Premium Payable  
- Maturity Amount  
- Annualized ROI  

across years and sales agents.

---

### 6️⃣ Sales Hierarchy Performances
Provides a structured performance view across the **organizational sales hierarchy**.

**Key capabilities:**
- Drill-down: **Zonal Manager → Regional Manager → Sales Agent**
- Toggle between **Matrix and Chart** views
- Dynamic **Rows selector** to redefine hierarchy by:
  - Policy Holder
  - Sales Agent
  - Policy Name / Type
  - Regional Manager
  - Zonal Manager
  - Gender
  - State

This page supports performance comparison, cost visibility, and profitability analysis at multiple levels.

---

## 📐 Data Modeling & Calculations
- Star-schema-based data model
- Measures created using **DAX**
- Key calculations include:
  - Total Premium Paid
  - Total Premium Payable
  - Maturity Amount
  - Profit / Gain
  - Annualized ROI (CAGR-based)
  - Growth and underwriting metrics

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- CSV-based synthetic datasets
- Field Parameters for dynamic visuals
- Advanced slicers and hierarchical matrices

---

## 📈 Skills Demonstrated
- Business-focused KPI design
- Advanced Power BI interactivity (Field Parameters, Hierarchies)
- Financial analytics using DAX
- Scalable data modeling
- Executive-level data storytelling

---

## 📬 Contact
If you’d like to discuss this project, the DAX logic, or potential opportunities, feel free to connect with me on LinkedIn.

