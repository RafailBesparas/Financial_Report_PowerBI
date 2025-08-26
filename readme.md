# 📊 Project: Financial Reporting & Analysis Dashboard (Power BI)

## 🔎 Description
Developed an **end-to-end Financial Reporting and Analysis solution** in Power BI, enabling executives, finance teams, and stakeholders to monitor **profitability, liquidity, solvency, and equity growth** through automated, interactive dashboards.  

The project consolidates data across **Income Statement, Balance Sheet, Cash Flow, and Equity** into a structured **star-schema data model**, powered by advanced **DAX measures** and time intelligence. This delivers a **real-time, single source of truth** for financial performance and strategic decision-making.

---

## 🎯 Goals & Objectives
- **Centralized Reporting**: Replace static Excel reports with automated, interactive dashboards.
- **Executive Insights**: Provide CFOs and management with instant visibility into KPIs.
- **Comparative Analysis**: Enable monthly, quarterly, and yearly performance tracking across countries.
- **Decision Support**: Deliver clear visibility into **P&L, liquidity, cash flows, and shareholder value**.
- **Efficiency**: Reduce manual reporting effort and ensure data consistency.

---

## 👥 User Stories
### As a **CFO/Executive**
- I want to **see KPIs (Revenue, Gross Profit, Net Income, Margins)** at a glance so that I can track company performance.
- I want to **compare financial trends by year and region** so that I can allocate resources effectively.
  
### As a **Finance Manager**
- I want to **analyze operating vs. non-operating accounts** so I can explain variances in profitability.
- I want to **monitor working capital and cash flow drivers** so I can manage liquidity risk.

### As an **Investor/Shareholder**
- I want to **see equity growth and retained earnings vs. share capital** so I can assess long-term value creation.
- I want to **track key financial ratios (Current Ratio, Debt-to-Equity, Profit Margin)** so I can evaluate solvency and performance.

---

## 🖥️ Key Dashboards & Features

### 1. Profit & Loss Dashboard
- KPI tiles for **Revenue, Gross Profit, EBITDA, Operating Profit, Net Income, Margins**.
- Line chart for **Sales vs. Net Income** trends (monthly & yearly).
- Multi-year Income Statement table (2018–2020).
- Quarterly trend charts for **Gross Profit & Net Profit**.

### 2. Balance Sheet Dashboard
- KPI tiles for **Total Assets, Liabilities, Equity**.
- Breakdown of **Current Assets** (Cash, Receivables, Inventory).
- Treemap showing **asset allocation**.
- Line chart comparing **Equity vs. Liabilities over time**.

### 3. Cash Flow Dashboard
- KPI tiles for **Opening/Closing Cash, Net Cash Movement, Δ Working Capital, Δ Noncurrent Assets**.
- Line chart of **Net Cash Movement trend**.
- Breakdown of **Operating, Investing, Financing Cash Flows**.

### 4. Equity & Ratios Dashboard
- KPI tiles for **Share Capital, Retained Earnings, Net Income, Revenues, Opex**.
- Line chart showing **Equity growth over time**.
- Stacked bar chart for **Retained Earnings vs. Share Capital**.
- Ratio table: **Profit Margin, Current Ratio, Quick Ratio, Debt-to-Equity** by month.

---

## ⚙️ Technical Implementation
- **Data Modeling**: Star schema with fact tables (transactions) and dimension tables (Date, Country, Accounts).
- **DAX Measures**:
  - Time intelligence (`TOTALYTD`, `SAMEPERIODLASTYEAR`).
  - Custom ratios: Current Ratio, Quick Ratio, Debt-to-Equity.
  - Financial KPIs: Gross Profit, EBITDA, Operating Profit, Net Income.
- **ETL Integration**:
  - Connected to financial datasets across multiple regions.
  - Automated refresh for monthly/quarterly updates.

---

## 📈 Impact
- Reduced **manual Excel reporting effort by 10%**.
- Delivered **executive-ready insights** with consistent KPIs across all regions.
- Improved **decision-making speed and accuracy** for strategic planning.
- Provided investors and stakeholders with **transparent, interactive financial health monitoring**.

---
