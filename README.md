# Financial Analysis of Dabur India Ltd. (FY21–FY25)

An independent financial analysis of **Dabur India Ltd.**, an Indian FMCG company, based on public consolidated financial statements. The Excel workbook covers five fiscal years (March 2021 to March 2025) and works through the balance sheet, the profit and loss statement, leverage and coverage ratios, and a year-by-year estimate of the weighted average cost of capital (WACC). Each step has its own charts.

> This analysis was done for academic and educational purposes using publicly available data. It is not financial or investment advice, and it is not affiliated with Dabur India Ltd.

## Dataset

- **Source:** consolidated balance sheet and P&L as published by Dion Global Solutions Limited (cited in the workbook)
- **Period:** FY ending Mar-21 to Mar-25, five years at 12 months each
- **Units:** ₹ crore unless stated

## Approach

| Sheet | What it does |
|---|---|
| `Dabur BS` | Consolidated balance sheet: shareholders' funds, non-current and current liabilities, fixed assets, investments and current assets. Bar charts track key line items over time. |
| `Dabur P&L` | Consolidated P&L: revenue, expense breakdown, PBT, tax and PAT. Includes a P&L bar chart, an income-statement chart and an expenses chart. |
| `Ratios` | Builds the inputs (total debt, equity, assets, capital employed, EBIT, interest) and computes debt-to-equity, equity, debt, capital gearing, proprietary and interest coverage ratios, plus a waterfall chart. |
| `WACC` | Cost of equity from CAPM (Rf 7%, beta 0.9, market premium 6%), after-tax cost of debt, capital-structure weights and the resulting WACC for each year. Includes a WACC trend chart. |

## Key Figures (from the workbook)

**Income statement (₹ crore)**

| | Mar-21 | Mar-22 | Mar-23 | Mar-24 | Mar-25 |
|---|---|---|---|---|---|
| Total operating revenues | 9,546.60 | 10,888.68 | 11,529.89 | 12,404.01 | 12,563.09 |
| Profit before tax | 2,057.03 | 2,270.48 | 2,220.31 | 2,359.25 | 2,257.34 |
| Profit for the period | 1,695.96 | 1,744.10 | 1,702.96 | 1,811.82 | 1,739.87 |

**Balance sheet and ratios**

| | Mar-21 | Mar-22 | Mar-23 | Mar-24 | Mar-25 |
|---|---|---|---|---|---|
| Total assets (₹ cr) | 10,847.13 | 12,284.53 | 13,654.37 | 15,122.68 | 16,232.28 |
| Total shareholders' funds (₹ cr) | 7,663.53 | 8,381.30 | 8,973.26 | 9,866.30 | 10,800.69 |
| Debt-to-equity | 0.063 | 0.104 | 0.111 | 0.117 | 0.068 |
| Equity ratio | 0.706 | 0.682 | 0.657 | 0.652 | 0.665 |
| Interest coverage (x) | 67.77 | 59.83 | 29.38 | 20.00 | 14.81 |
| WACC | 11.8% | 11.6% | 11.8% | 12.1% | 12.3% |

**Takeaways**

- **Low leverage.** Debt-to-equity stayed between 0.06 and 0.12 over the period, and shareholders' funds funded about two-thirds of total assets.
- **Steady growth.** Operating revenues grew every year, from ₹9,546.60 cr to ₹12,563.09 cr. Profit for the period stayed between ₹1,695.96 cr and ₹1,811.82 cr.
- **Coverage still comfortable but falling.** Interest coverage dropped from 67.77x to 14.81x as finance costs rose from ₹30.81 cr to ₹163.50 cr.
- **Cost of capital driven by equity.** Equity makes up roughly 90–94% of capital in the WACC calculation, so WACC (11.6–12.3%) stays close to the CAPM cost of equity of 12.4%.

## Tools & Tech

- Microsoft Excel (financial statement modelling, ratio analysis, CAPM/WACC, bar, line, pie and waterfall charts)

## Repository Structure

```
.
├── Dabur India Ltd..xlsx   # BS, P&L, ratio and WACC sheets with charts
└── README.md
```

## How to Open

1. Clone the repository:
   ```bash
   git clone https://github.com/anshumantewary-pm/Dabur-India-Ltd.git
   ```
2. Open `Dabur India Ltd..xlsx` in Microsoft Excel. The waterfall and other newer chart types need Excel 2016 or later.
3. Work through the sheets in order: `Dabur BS` → `Dabur P&L` → `Ratios` → `WACC`.

---

**Author:** Anshuman Tewary · [GitHub](https://github.com/anshumantewary-pm) · [LinkedIn](https://www.linkedin.com/in/tewary-anshuman/)
