# Baby Products E-Commerce Sales Dashboard

An interactive data visualization dashboard built with **D3.js** that analyzes three years of real-world e-commerce transaction data from a Kenyan baby products retailer. The project transforms 28,755 raw sales records into actionable business insights across two interconnected dashboards.

---

## Business Problem

Despite generating KSh 68.3 million in total sales, the business lacked clear visibility into what was truly driving its revenue, why sales dropped sharply in late 2023, whether its discount strategies were effective, and how return behavior was impacting profitability. This dashboard was built to answer:

> *"How can the business leverage its sales transaction data to identify key revenue drivers, understand customer shopping behavior, and evaluate the effectiveness of its return and discount patterns across products and channels?"*

---

## Dataset

| Detail | Info |
|---|---|
| Source | Kaggle |
| Period | November 2020 – October 2023 |
| Records | 28,755 transactions |
| Attributes | 17 original + 9 derived |
| Business | Kenya-based e-commerce retailer (baby products) |

---

## Dashboards & Charts

### Dashboard 1 — Category and Product-Level Performance Analysis
| Chart | Description |
|---|---|
| KPI Summary | Total sales, return orders, and order count at a glance |
| Gross Sales Trend Over Time | Quarterly sales trend from Q4 2020 to Q4 2023 |
| Peak Shopping Times | Heatmap of order activity by day and hour |
| Top 10 Selling Products | Best-performing products by gross sales |
| Top Selling Product Categories | Revenue contribution by product category |

### Dashboard 2 — Overall Sales Drivers, Performance and Return Analysis
| Chart | Description |
|---|---|
| AOV by Channel | Average order value comparison across online vs. in-store |
| High Return Products Driving Sales | Scatter plot of return volume vs. gross sales |
| Top Products Driving Total Sales | Pareto chart of cumulative product revenue contribution |
| Discount Strategy Impact | Scatter plot of discount rate vs. gross sales by product |

---

## Key Insights

- **KSh 68.3M** total sales across **11,358 orders** with a low return rate of 188 return orders
- Sales peaked in **2023-Q2** then dropped sharply — signaling possible seasonal shifts or demand changes
- **Feeding & Nursing** is the top revenue category; baby formula brands dominate the top 10 products
- Just **20% of products** drive **80% of total revenue** — heavy concentration risk
- **Online store customers** consistently spend more per transaction than in-store customers
- **High discounts do not always drive high sales** — several products achieve strong revenue with minimal discounts
- Products like **Play Tent** and **Colouring Book** show high return rates relative to sales, signaling quality or expectation issues

---

## Tech Stack

- **D3.js** — data-driven visualizations
- **HTML / CSS** — dashboard layout and styling
- **JavaScript** — interactivity and data processing

---

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/baby-products-sales-dashboard.git
   ```
2. Navigate to the project folder
   ```bash
   cd baby-products-sales-dashboard
   ```
3. Open `index.html` in your browser, or serve locally
   ```bash
   npx serve .
   ```

---

## Acknowledgements

Dataset sourced from [Kaggle](https://www.kaggle.com) — real-world retail transaction data from a registered Kenyan e-commerce business.