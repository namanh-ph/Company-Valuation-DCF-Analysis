# Company Valuation - DCF Analysis

## Overview

This project presents two complementary approaches to valuing companies using the Discounted Cash Flow (DCF) methodology:

1. **Fundamental Single-Company Valuation** - A deep-dive manual analysis in Excel of REA Group Limited (ASX\:REA), integrating financial statement forecasting, WACC estimation, and sensitivity analysis.
2. **Automated Multi-Firm Valuation** - A scalable Python pipeline that sources financial data from Yahoo Finance, applies normalised DCF models, and conducts cross-sectional valuation.

It is designed to demonstrate both the **rigour of traditional fundamental analysis** and the **efficiency of automated financial data engineering**.

---

## Project Structure

### **Part 1 - Fundamental Valuation (REA.ASX)**

A detailed, single-company valuation of **REA Group Limited**, applying advanced financial analysis techniques in Excel.

**Core components:**

* **Financial Statement Forecasting** - Recasting and projecting income statement, balance sheet, and cash flow statement.
* **DuPont & Ratio Analysis** - Decomposition of Return on Equity (ROE) and evaluation of liquidity, efficiency, leverage, and profitability ratios.
* **Bottom-Up Beta Estimation** - Deriving beta from industry peer comparisons, adjusted for REA’s capital structure.
* **Weighted Average Cost of Capital (WACC)** - Calculation using cost of equity (CAPM) and after-tax cost of debt.
* **Growth & DCF Calculation** - Projecting free cash flows, estimating terminal value, and discounting to present value to determine intrinsic value.

---

### **Part 2 - Automated Multi-Firm Valuation**

A Python-based framework for running DCF analysis across multiple companies, sourcing data automatically from Yahoo Finance.

**Core components:**

* **Automated Data Retrieval** - Using `yfinance` to pull financial statements and market data.
* **Data Normalisation** - Standardising data formats for consistency across firms.
* **DCF Modelling** - Automating free cash flow projection, WACC computation, and valuation output.
* **Sensitivity Analysis** - Running scenario tests on growth rates, discount rates, and margin assumptions.
* **Cross-Sectional Insights** - Comparing intrinsic values to market capitalisations for multiple firms.
