# Profit Analytics — Power BI Dashboard

> Executive dashboard focused on sales performance, profitability analysis, KPIs and interactive business insights.

![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-yellow)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-00AEEF)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📊 Overview

This project presents an interactive **Sales & Profit Analytics Dashboard** developed in Microsoft Power BI.

The dashboard was designed with an executive perspective, combining **KPIs, profitability analysis, business performance indicators and interactive navigation** into a single analytical experience.

The main objective is to transform transactional data into insights that support faster and more effective business decisions.

---

## 🎯 Business Questions

The dashboard was designed to answer questions such as:

- How are sales and profit performing?
- How has profitability evolved over time?
- Which products generate the highest profit?
- Which countries contribute most to profitability?
- Which customer segments generate or compromise profit?
- What is the relationship between sales volume, units sold and profit?
- What are the main drivers behind the company's profitability?

---

## 📈 Key KPIs

The executive layer highlights four core indicators:

| KPI | Purpose |
|---|---|
| **Sales** | Total sales performance |
| **Units Sold** | Sales volume |
| **Profit** | Financial result |
| **Profit Margin** | Profitability efficiency |

Year-over-year comparisons are also presented to provide immediate performance context.

---

## 🔎 Analytics Views

The dashboard uses interactive states to provide different analytical perspectives without creating unnecessary pages.

### Performance

Focuses on profitability evolution and business concentration.

- Profit & Margin Trend
- Top 3 Products by Profit
- Profit Contribution by Country

![Performance](screenshots/02-dashboard-performance.png)

---

### Sales, Units & Profit Relationship

Explores the relationship between:

- Sales
- Units Sold
- Profit
- Customer Segments

This view helps identify patterns between sales volume and financial performance.

![Relationship](screenshots/03-dashboard-relationship.png)

---

### Profitability Analysis

A deeper analytical view focused on the main profit drivers.

- Profit Decomposition Tree
- Segment analysis
- Product analysis
- Country analysis
- Interactive filters

![Profitability](screenshots/04-dashboard-profitability.png)

> Explore the key profit drivers by segment, product, and country. Use the filters to deepen the analysis and identify where profitability is generated, concentrated, or compromised.

---

## 🧭 User Experience

The dashboard was designed with a focus on:

- Clear visual hierarchy
- Consistent layout
- Contrast and readability
- Interactive navigation
- Contextual filtering
- Reduced visual clutter
- Executive-oriented storytelling

Instead of creating several static pages, different analytical perspectives are accessed through an interactive dashboard interface.

This approach keeps the experience compact while allowing the user to move from **executive overview to deeper profitability analysis**.

---

## 🧮 Data & DAX

The project includes DAX measures supporting the main analytical indicators, including:

- Sales
- Units Sold
- Profit
- Profit Margin
- Previous Year calculations
- Year-over-Year variation
- Profitability comparisons
- Analytical support measures for visualizations

The calculations were structured to separate **business logic from visual presentation**, allowing the dashboard to remain flexible under different filters and analytical contexts.

---

## 🎨 Design

The visual identity follows a dark executive dashboard concept with:

- Navy / blue analytical environment
- Cyan highlights
- Green positive indicators
- Red negative indicators
- Card-based KPI structure
- Consistent typography
- Interactive navigation elements

The objective was to balance **visual impact with analytical usability**.

---

## 🖥️ Dashboard Preview

### Home

![Home](screenshots/01-home.png)

### Performance

![Performance](screenshots/02-dashboard-performance.png)

### Sales, Units & Profit Relationship

![Relationship](screenshots/03-dashboard-relationship.png)

### Profitability

![Profitability](screenshots/04-dashboard-profitability.png)

### Interactive Filters

![Filters](screenshots/05-dashboard-filters.png)

---

## 🎥 Dashboard Demo

A short video demonstrating the dashboard navigation and interactive experience is available in the repository:

**[▶ Watch the Dashboard Demo](demo/dashboard-demo.mp4)**

---

## 🗂️ Project Structure

```text
power-bi-profit/
│
├── dashboard/
│   └── Sales_Report.pbix
│
├── demo/
│   └── dashboard-demo.mp4
│
├── screenshots/
│   ├── 01-home.png
│   ├── 02-dashboard-performance.png
│   ├── 03-dashboard-relationship.png
│   ├── 04-dashboard-profitability.png
│   └── 05-dashboard-filters.png
│
└── README.md
