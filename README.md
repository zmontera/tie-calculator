# True Interest Expense Calculator

Live calculation of the federal government's True Interest Expense — mandatory obligations as a percentage of tax revenue.

Based on the FFTT framework by Luke Gromen. Pulls live data from FRED (Federal Reserve Bank of St. Louis).

**[→ View the Calculator](https://zmontera.github.io/tie-calculator/)**

## What is TIE?

The True Interest Expense measures five non-discretionary federal obligations:
1. **Net Interest on Debt** (gross payments minus receipts)
2. **Social Security**
3. **Medicare**
4. **Income Security** (Medicaid, SSI, SNAP)
5. **National Defense**

When these exceed 100% of federal tax revenue, the government is in deficit before spending a single discretionary dollar.

## Data Sources
All data from FRED (Federal Reserve Economic Data):
- A091RC1Q027SBEA — Federal Gross Interest Payments
- B094RC1Q027SBEA — Federal Interest Receipts  
- W823RC1Q027SBEA — Social Security Benefits
- W729RC1Q027SBEA — Medicare Benefits
- W824RC1Q027SBEA — Income Security
- FDEFX — National Defense Spending
- FGRECPT — Federal Government Receipts
- GDP — Nominal GDP
- GFDEBTN — Federal Debt Total

Built by [@zmGandalf](https://x.com/zmGandalf)
