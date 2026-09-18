# Dollarama Inc. (TSX: DOL) — Financial Statement Analysis & DCF Valuation


**Author:** Asley Lopez Robleto
**Date:** September 17, 2026

A financial statement analysis and discounted cash flow (DCF) valuation of **Dollarama Inc.**, covering fiscal years **2021–2026**.

This project was built as an independent student project to develop practical skills in financial statement analysis, financial modelling, valuation, and Excel.

> **Disclaimer:** This is an independent student project for educational purposes only. It is not investment research, financial advice, or a recommendation to buy, sell, or hold any security.

---

## 📌 Project Overview

The project reconstructs Dollarama's audited consolidated financial statements for FY2021–FY2026 in Excel and uses them as the foundation for a broader financial analysis and DCF valuation.

The analysis covers:

* Income statement
* Statement of financial position
* Cash flow statement
* Vertical analysis
* Financial ratio analysis
* DuPont analysis
* Cash flow quality analysis
* Free cash flow analysis
* Weighted Average Cost of Capital (WACC)
* Discounted Cash Flow (DCF) valuation
* DCF sensitivity analysis

The accompanying PDF report explains the methodology, key findings, modelling decisions, and major assumptions behind the valuation.

---

## 📂 Files

| File                                | Description                                             |
| ----------------------------------- | ------------------------------------------------------- |
| `Dollarama Financial Model FY2021-2026.xlsx` | Full Excel financial model, analysis, and DCF valuation |
| `Dollarama Financial Statement Analysis & DCF Valuation Report.pdf`          | Written report explaining the analysis and valuation    |

### Excel Workbook

The workbook contains the underlying financial data, calculations, analyses, and valuation model. All formulas and assumptions are visible and editable.

The model includes:

1. **Financial Statements**

   * FY2021–FY2026 income statements
   * FY2021–FY2026 statements of financial position
   * FY2021–FY2026 cash flow statements

2. **Vertical Analysis**

   * Income statement common-size analysis
   * Balance sheet common-size analysis
   * Historical trend analysis

3. **Ratio Analysis**

   * Profitability ratios
   * Liquidity ratios
   * Efficiency ratios
   * Leverage ratios
   * Other relevant financial ratios

4. **DuPont Analysis**

   * Decomposition of return on equity
   * Examination of profitability, asset utilization, and financial leverage

5. **Cash Flow Quality**

   * Operating cash flow relative to net earnings
   * Free cash flow
   * Cash conversion
   * Relationship between earnings and cash generation
   * Capital allocation observations

6. **DCF Valuation**

   * Revenue projections
   * EBIT / operating margin assumptions
   * NOPAT
   * D&A
   * Capital expenditures
   * Changes in working capital
   * Unlevered free cash flow
   * WACC calculation
   * Terminal value
   * Enterprise value
   * Equity value
   * Implied value per share
   * Sensitivity analysis

---

## 🔎 Key Findings

The six-year financial statements show substantial growth in Dollarama's operations:

| Metric           | FY2021 | FY2026 |
| ---------------- | -----: | -----: |
| Sales            | $4.03B | $7.26B |
| Operating Margin |  21.4% |  26.7% |
| Net Earnings     |  $564M | $1.31B |
| Diluted EPS      |  $1.81 |  $4.73 |
| Free Cash Flow   |  $721M | $1.49B |

One particularly interesting finding was the effect of Dollarama's historical share repurchases on shareholders' equity. Equity became negative in FY2022 and remained unusually low relative to total assets in subsequent years, making equity-based ratios such as **ROE and debt-to-equity difficult to interpret** during portions of the period.

The cash flow analysis also showed that **operating cash flow exceeded net earnings in every year analyzed**, while free cash flow remained positive throughout FY2021–FY2026.

---

## 🧮 DCF Valuation

The valuation uses an **unlevered discounted cash flow model**.

The basic structure is:

```text
Revenue
   ↓
EBIT
   ↓
NOPAT
   ↓
+ Depreciation & Amortization
- Capital Expenditures
- Change in Working Capital
   ↓
Unlevered Free Cash Flow
   ↓
Discount using WACC
   ↓
Enterprise Value
   ↓
- Net Debt
   ↓
Equity Value
   ↓
Implied Value Per Share
```

The base-case model uses:

| Assumption              | Base Case |
| ----------------------- | --------: |
| Explicit Revenue Growth |      8.0% |
| Operating Margin        |     26.5% |
| Effective Tax Rate      |     25.0% |
| Terminal Growth Rate    |      2.5% |
| Cost of Equity          |      6.6% |
| Pre-tax Cost of Debt    |     2.67% |
| WACC                    | **6.17%** |

The resulting base-case DCF valuation produces an **implied value of $168.19 per share**.

The workbook includes a sensitivity analysis showing how changes in key assumptions, particularly the discount rate and terminal growth rate, affect the valuation.

---

## 💡 Modelling Considerations

### Lease Liabilities

One of the more important modelling considerations was Dollarama's lease structure.

Because Dollarama operates a large retail store network, lease liabilities represent a significant component of its capital structure. The DCF therefore considers lease liabilities when bridging from enterprise value to equity value.

In the model, incorporating lease liabilities into net debt reduced the initial implied valuation from approximately **$128 to $118 per share**, illustrating how accounting treatment can materially affect a DCF valuation.

### WACC

Rather than relying on a flat assumed discount rate, the final model builds WACC from the individual components of Dollarama's capital structure:

* Cost of equity using CAPM
* Cost of conventional debt
* Cost of lease financing
* Market-value capital structure weights

The resulting WACC is **6.17%**.

---

## 🇦🇺 Australia Acquisition

The model also considers Dollarama's acquisition of **The Reject Shop** in Australia, which was completed during FY2026.

The acquisition is relevant to the analysis because FY2026 represents the first year in the dataset in which Dollarama's operations include the Australian business.

The report deliberately does **not** attempt to reconstruct the complete purchase price allocation because that would require detailed business-combination disclosures beyond the intended scope of the project.

---

## 🛠️ Tools & Skills

**Primary tool:**

* Microsoft Excel

**Financial analysis:**

* Financial statement analysis
* Common-size / vertical analysis
* Ratio analysis
* DuPont analysis
* Cash flow analysis
* Free cash flow analysis
* Financial modelling
* DCF valuation
* WACC
* Sensitivity analysis

**Accounting concepts:**

* IFRS financial statements
* Lease accounting
* Working capital
* Depreciation & amortization
* Debt and equity
* Cash flow classification
* Capital structure

---

## 📚 Data Sources

The historical financial statements were reconstructed from **Dollarama Inc.'s publicly available audited consolidated financial statements and public disclosures**.

Market-related inputs used in the valuation, such as share price, beta estimates, and analyst information, reflect information available around **September 2026** and may change over time.

The project does not rely on proprietary or non-public company information.

---

## 📖 Accompanying Report

The PDF report provides additional context behind the numbers in the workbook, including:

* What the six-year financial statements reveal
* The effect of share repurchases on Dollarama's capital structure
* Cash flow quality
* The Australia acquisition
* Lease treatment in the DCF
* Construction of WACC
* DCF assumptions
* Valuation sensitivity
* Key risks and modelling uncertainties

The report is intended to be read alongside the Excel workbook rather than as a standalone investment thesis.

---

## 🎯 Project Objective

The goal of this project was not simply to arrive at a valuation.

It was to build a financial model from the **three core financial statements**, understand how the statements interact, and then use that foundation to make a valuation model whose assumptions and calculations can be examined and challenged.

The project was particularly useful for understanding how seemingly small modelling decisions — such as the treatment of leases or the construction of WACC — can materially affect a DCF's output.

> **Build the statements. Understand the business. Challenge the assumptions. Then value it.**

---

## ⚠️ Disclaimer

This repository contains an independent student project created for educational purposes.

It is **not investment research**, is not affiliated with or endorsed by Dollarama Inc. or any financial institution, and does not constitute investment advice or a recommendation to buy, sell, or hold any security.

Historical financial information was obtained from Dollarama's publicly available disclosures. Market data and valuation inputs are time-sensitive and may have changed since the model was created.
