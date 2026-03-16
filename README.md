# Financial KPI Dashboard (Excel)

## Overview
This project builds a **single-page Financial KPI Dashboard in Excel** that consolidates financial and operational data into a clear analytical interface.

The dashboard enables users to analyze business performance through comparisons such as:

- Actual vs Plan
- Current Year vs Prior Year
- Performance trends over time
- HR and operational activity

The design follows a structured **financial modeling architecture**:

Raw Data → Calculations → Dashboard

This separation ensures scalability, maintainability, and dynamic updates when underlying data changes.

---

# Dashboard Objectives

The KPI dashboard is designed to:

- Consolidate financial and operational activities
- Track key performance indicators across departments
- Compare planned vs actual performance
- Present insights on a single easy-to-read page
- Enable interactive filtering and metric switching

Core design principle:

> Every chart should communicate the message instantly. If a viewer cannot understand the chart quickly, the design should be simplified.

---

# Workbook Structure

The Excel workbook is divided into **three layers**.

## 1. Raw Data (Input Layer)

These sheets store the original datasets used for calculations.

| Worksheet | Description |
|----------|-------------|
| Current Year Data | Monthly revenue, expense, and EBIT values by state |
| Prior Year Data | Historical financial performance by department |
| Historical Revenue | Multi-year revenue dataset |
| Debtor Days | Accounts receivable aging data |
| HR and Campaign | HR activity and marketing campaign data |
| Customer Satisfaction | Survey metrics and satisfaction targets |

### Current Year Dataset

Includes monthly values (January–December) for each state:

- Actual Revenue
- Planned Revenue
- Actual Expense
- Planned Expense
- Actual EBIT
- Planned EBIT
