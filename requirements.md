# Financial Reporting Dashboard Project

## 1. Project Overview
The Financial Reporting Dashboard provides executives, finance teams, and stakeholders with a **single source of truth** for monitoring the company’s financial performance, position, cash flows, and shareholder value.  

It consolidates **P&L, Balance Sheet, Cash Flow, and Equity analytics** into a unified interactive report, enabling data-driven decision-making and strategic planning.

---

## 2. Goals & Objectives
- **Transparency:** Provide a clear, accurate, and timely view of financial health.
- **Decision Support:** Enable executives to monitor profitability, liquidity, solvency, and efficiency.
- **Drill-Down Analysis:** Allow users to explore financial KPIs from summary to detail.
- **Comparability:** Track trends over time (monthly, quarterly, yearly).
- **Stakeholder Value:** Demonstrate growth in equity and financial stability to investors and lenders.

---

## 3. High-Level Requirements
1. **Data Integration**
   - Connect to financial ERP/accounting systems (Sales, Expenses, Balance Sheet entries).
   - Support multiple countries (Australia, Canada, France, Germany).
   - Historical data coverage: 2018–2020.

2. **Core Dashboards**
   - **Profit & Loss (Income Statement):**
     - Show KPIs (Revenue, Gross Profit, EBITDA, Operating Profit, Net Profit, Margins).
     - Monthly and yearly trends for Sales and Net Income.
     - Multi-year income statement table (Sales, COGS, Opex, Non-operating items).

   - **Balance Sheet Analytics:**
     - KPIs (Assets, Liabilities, Equity).
     - Breakdown of current assets (cash, receivables, inventory) and liabilities.
     - Asset allocation visual.
     - Equity vs. Liabilities over time.

   - **Cash Flow (Investing & Financing):**
     - KPIs (Opening/Closing Cash, Net Movement, Net Income, Δ Working Capital).
     - Cash Flow by activity (Operating, Investing, Financing).
     - Net Cash Movement trend.

   - **Equity & Ratios:**
     - KPIs (Share Capital, Retained Earnings, Revenues, Opex, Net Income).
     - Equity growth and composition (retained earnings vs. share capital).
     - Financial ratios: Profit Margin, Current Ratio, Quick Ratio, Debt-to-Equity.

3. **Interactivity**
   - Country filter to switch views by market.
   - Time filters (month, quarter, year).
   - Drill-down from high-level KPIs to detailed tables.

4. **Performance**
   - Optimized for sub-2s page load.
   - Aggregations for large fact tables.

---

## 4. User Stories

### As an **Executive (CEO/CFO)**
- I want to **see top-level KPIs** (Revenue, Net Profit, Margins) so that I can monitor financial performance at a glance.
- I want to **track trends over months and years** so that I can spot growth or decline early.
- I want to **compare countries** to understand which markets drive profitability.

### As a **Finance Manager**
- I want to **drill down into P&L line items** (COGS, Opex, Depreciation) so I can explain variances.
- I want to **analyze Balance Sheet composition** so I can manage liquidity and working capital.
- I want to **track cash flows by category** so I know whether operations or investments drive changes.

### As an **Investor/Shareholder**
- I want to **see equity growth** so I can assess long-term value creation.
- I want to **monitor financial ratios** so I can evaluate solvency and risk.
- I want to **understand retained earnings vs. dividends** to know how profits are reinvested.

---

## 5. Expected Deliverables (What Users See)

- **Dashboard 1: Profit & Loss**
  - Large KPI cards (Revenue, Gross Profit, EBITDA, Net Profit, Margins).
  - Line chart: Sales vs. Net Income over time.
  - Table: Multi-year Income Statement with breakdown.
  - Bar charts: Quarterly Gross Profit and Net Profit.

- **Dashboard 2: Balance Sheet**
  - KPI summary (Assets, Liabilities, Equity).
  - Pie/donut or bar chart: Asset allocation (cash, receivables, inventory, PPE, intangibles).
  - Line chart: Liabilities vs. Equity trend.

- **Dashboard 3: Cash Flow**
  - KPI cards (Opening/Closing Cash, Net Movement, Net Income, Working Capital Δ).
  - Line chart: Net Cash Movement trend.
  - Bar chart: Cash Flow breakdown by Operating, Investing, Financing.

- **Dashboard 4: Equity & Ratios**
  - KPI summary (Share Capital, Retained Earnings, Revenues, Opex, Net Income).
  - Line chart: Equity growth over time.
  - Stacked chart: Retained Earnings vs. Share Capital.
  - Table: Monthly Ratios (Profit Margin, Current Ratio, Quick Ratio, Debt-to-Equity).

---

## 6. Why This Project Was Created
This project was created to **replace static financial reporting (Excel, PDF exports)** with a dynamic, real-time, interactive system.  
By consolidating the **Income Statement, Balance Sheet, Cash Flow, and Equity/Ratio analysis** into one platform, it:
- Reduces manual reporting effort.
- Ensures financial accuracy and consistency.
- Empowers management and investors with **self-service analytics**.
- Provides a **360° financial view** for decision-making and planning.
