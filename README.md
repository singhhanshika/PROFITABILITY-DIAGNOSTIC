# Profitability Diagnostic — Zomato (FY21–FY23)

> A consulting-style financial analysis identifying margin erosion drivers in Zomato's P&L and recommending operational fixes.

---

## Problem Statement

**"Why is Zomato losing money despite high revenue growth?"**

Despite growing revenues, Zomato has consistently reported negative EBITDA margins. This project applies a hypothesis-driven diagnostic framework to identify the root causes and recommend actionable cost levers — the same approach used by top strategy consulting firms.

---

## Key Findings

| Metric | Finding |
|--------|---------|
| Delivery cost growth | 34% YoY vs revenue growth of 22% |
| Customer Acquisition Cost | Increased 2.1x over 3 years |
| Contribution margin | Negative in core food delivery segment |
| Primary margin killer | Delivery + discounting costs |

---

## Recommendations

1. **B2B Catering Expansion** — Higher order value, lower delivery cost per order
2. **Dynamic Discount Reduction** — Targeted offers vs blanket discounts
3. **Hyperlocal Dark Kitchen Partnerships** — Reduce last-mile delivery distance

Projected EBITDA recovery: **~12%** if all 3 levers implemented

---

## Methodology

```
Step 1 → Pull 3 years of financials from Screener.in (FY21, FY22, FY23)
Step 2 → Build cost waterfall model in Excel
Step 3 → Identify cost lines growing faster than revenue
Step 4 → Benchmark against peers (Swiggy, global comps)
Step 5 → Frame recommendations using Pyramid Principle
```

---

## Files

```
profitability-diagnostic/
├── data/
│   └── zomato_financials_fy21_fy23.csv       # Raw P&L data from Screener.in
├── analysis/
│   └── profitability_analysis.py              # Python analysis script
├── output/
│   └── cost_waterfall.png                     # Cost breakdown visualization
├── docs/
│   └── executive_summary.md                   # Consulting-style recommendation deck
└── README.md
```

---

## Tools Used

- **Python** (Pandas, Matplotlib) — data analysis and visualization
- **Excel** — cost waterfall model
- **Screener.in** — source of financial data
- **PowerPoint** — executive summary deck

---

## Data Source

Financial data sourced from [Screener.in](https://www.screener.in/company/ZOMATO/) — publicly available annual reports.

---

## How to Run

```bash
git clone https://github.com/singhhanshika/PROFITABILITY-DIAGNOSTIC
cd profitability-diagnostic
pip install -r requirements.txt
python analysis/profitability_analysis.py
```

---

*This project was built as a consulting-style case study. All data is publicly available.*
