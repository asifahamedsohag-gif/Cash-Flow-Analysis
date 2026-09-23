# Cash Flow Analysis Dashboard

## 📊 Project Overview

The **Cash Flow Analysis Dashboard** is an interactive **Power BI** dashboard designed to analyze cash inflows, outflows, and overall cash flow performance across different categories, account types, and time periods.

The dashboard provides a clear view of the organization's **Operating, Investing, and Financing cash flows**, helping users understand where cash is generated and where it is being utilized.

## 🖼️ Dashboard Preview

![Cash Flow Analysis Dashboard](image/Cash%20Flow.jpg)

> **Note:** Make sure the image is saved inside your GitHub repository's `image` folder with the filename `Cash Flow.jpg`.  
> If your folder is named `images`, change the path to `images/Cash%20Flow.jpg`.

---

## 🎯 Project Objectives

- Analyze overall cash flow performance
- Monitor total cash inflows and outflows
- Compare Operating, Investing, and Financing activities
- Identify major cash outflow accounts
- Analyze monthly cash flow trends
- Understand cash flow by transaction category
- Provide an interactive dashboard for financial decision-making

---

## 📌 Key KPIs

The dashboard includes the following key financial indicators:

| KPI | Description |
|---|---|
| **Total Cash Flow** | Net cash flow generated after considering inflows and outflows |
| **Total Inflow** | Total cash received during the selected period |
| **Outflow Display** | Total cash paid or spent |
| **Operating Cash Flow** | Cash generated or used through operating activities |
| **Investing Cash Flow** | Cash related to investments and capital expenditures |
| **Financing Cash Flow** | Cash related to financing activities |

---

## 📈 Dashboard Features

### 1. Cash Flow Summary

Provides a high-level overview of:

- Total Cash Flow
- Total Inflow
- Total Outflow
- Operating Cash Flow
- Investing Cash Flow
- Financing Cash Flow

### 2. Cash Flow by Category

Visualizes cash flow across:

- Operating
- Financing
- Investing

This allows users to compare the contribution of each cash flow category.

### 3. Outflow by Account Name

The dashboard identifies major cash outflow accounts such as:

- Payroll
- Supplier Payments
- New Delivery Van
- Office Rent
- Warehouse Equipment
- Shareholder Dividends
- Loan Repayment
- Software Subscriptions

This helps highlight the accounts contributing most significantly to cash utilization.

### 4. Monthly Cash Flow Trend

The monthly trend visualization shows how total cash flow changes over time and helps identify increases or decreases in cash generation.

### 5. Transaction-Level Analysis

The dashboard includes transaction-level information such as:

- Month
- Transaction ID
- Account Name
- Category
- Sub Category
- Amount
- Transaction Type

### 6. Interactive Filters

Users can interact with the dashboard using filters for:

- **Category**
- **Type**
- **Day**

These filters allow users to explore specific portions of the cash flow data.

---

## 🗂️ Data Analysis Structure

The analysis is organized around the following dimensions:

```text
Cash Flow
│
├── Category
│   ├── Operating
│   ├── Investing
│   └── Financing
│
├── Transaction Type
│   ├── Inflow
│   └── Outflow
│
├── Account Name
│
├── Sub Category
│
└── Time
    ├── Month
    └── Day
