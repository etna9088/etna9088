# Madina Kanafina | Microsoft Certified Power BI Data Analyst Associate (PL-300) | B.S. Computational and Data Sciences in progress — George Mason University | Inventory & Operations Coordinator

Inventory and operations analytics — stock, pricing, demand, and reporting. Retail, supply chain, wholesale distribution, and manufacturing — built on BigQuery, SQL, Power BI, and DAX.

## 🛠 Tech Stack9

*   **BI & Analytics:** Power BI, Excel, Power Query (M)
*   **Languages & Databases:** SQL, DAX, R, Google BigQuery, MATLAB
*   **Tools & Version Control:** Git, GitHub, Notion

## 📊 Featured Projects

### 👟 StockX Sneaker Resale Analytics
**Tech Stack:** Google BigQuery, SQL, Power BI, DAX
**Focus:** Exit timing, size-curve scarcity, demand risk scoring

99,956 real StockX transactions (2017–2019) across two brands running opposite playbooks — scarcity vs volume — modeled through a BigQuery staging pipeline and a Power BI star schema, with every headline number reconciled across three independent paths (CSV profile, SQL, report).

- Diagnosed a uniform whitespace defect silently breaking 72% of brand joins, and validated the pipeline end-to-end with five checks plus multi-path reconciliation of all published figures.
- Showed the market's apparent premium collapse after year one is a composition artifact: split by brand, aged Off-Whites appreciate to a 578% median premium while Yeezys decay to 31% — making exit timing a brand-specific decision.
- Scored all 50 models on price volatility (CV) vs premium to map hero SKUs and demand risk, and quantified size-curve scarcity: tail sizes carry 3–4x core-size premiums, with size 15 running 100% Off-White.

👉 [View the Full Project](https://github.com/etna9088/stockx-resale-analytics)

### 📊 Retail CapEx & Inventory Operations Analysis
**Tech Stack:** Power BI, DAX, Power Query (M), Excel
**Focus:** SKU profitability, cash velocity, capital payback

A 3-year SKU-level profitability model across 74 assets and 12 selling seasons — star schema, class-aware DAX, and a disconnected 12-period timeline replacing standard Time Intelligence in a non-calendar seasonal model.

- Modeled daily cash velocity across the full catalog, isolating a ~95x spread between the fastest and slowest cash-positive SKUs ($17.11/day vs $0.18/day).
- Engineered class-aware ROI and break-even logic across 4 asset classes, surfacing a 1,048% maximum 3-year ROI and exactly one structurally unprofitable SKU flagged for delisting.
- Mapped capital payback on a 12-period cumulative curve: tree-class assets run Year-1 deficits, break even in Fall of Year 2, and lead all classes by Year 3 — full-catalog 3-year net position of $57,564.

👉 [View the Full Project](https://github.com/etna9088/retail-capex-inventory-analysis)

## 🎓 Academic Projects
- **[College Cost vs. Earnings](https://github.com/etna9088/college_cost_vs_earnings)** — R linear regression on U.S. Dept. of Education data; every $1 in tuition correlated with $4.59 in 10-year earnings (R² = 0.344)
- **[Used Car Price Valuation](https://github.com/etna9088/car_prices)** — R regression comparison; improved R² from 0.33 to 0.94 by adding categorical features
- **[Wheatfield Harvest Simulation](https://github.com/etna9088/matlab-wheatfield-simulation)** — MATLAB stochastic simulation, 3,000 runs, modeling yield variability under random weather

## 📫 Connect with Me
*   [LinkedIn](https://www.linkedin.com/in/etna907)
