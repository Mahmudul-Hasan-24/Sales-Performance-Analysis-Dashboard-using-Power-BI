# Sales Performance Analysis Dashboard — Power BI

> Interactive Power BI dashboard analyzing $6.2M in sales across 3 product categories, 6 US states, and 5 payment methods — featuring KPI cards, trend analysis, geospatial mapping, and dynamic filters for drill-down business insights.

---

## Dashboard Preview

![Sales Performance Analysis Dashboard](dashboard_screenshot.png)

---

## Project Overview

This project presents a fully interactive **Sales Performance Analysis Dashboard** built in Microsoft Power BI. It analyzes 1,194 sales transactions across 6 US states from 2020 to 2025, covering 3 product categories (Electronics, Furniture, Office Supplies) and 12 sub-categories.

The dashboard enables business stakeholders to monitor sales KPIs, identify top-performing products and regions, track revenue trends over time, and compare profitability across categories — all through interactive slicers and dynamic visuals.

**Tools & Technologies:** Microsoft Power BI · DAX · Power Query · Data Modeling

---

## Dataset

| Field | Details |
|---|---|
| Records | 1,194 transactions |
| Time period | March 2020 – March 2025 |
| Categories | Electronics, Furniture, Office Supplies |
| Sub-categories | 12 (Laptops, Phones, Chairs, Tables, Printers, Markers, Paper, etc.) |
| States | California, Florida, Illinois, New York, Ohio, Texas |
| Cities | Orlando, San Francisco, Buffalo, Rochester, Dallas, Miami, Springfield, Chicago + more |
| Payment modes | Credit Card, Debit Card, UPI, COD, EMI |
| Key fields | Order ID, Amount, Profit, Quantity, Category, Sub-Category, PaymentMode, State, City, Order Date |

---

## Key Metrics (Dashboard Summary)

| KPI | Value |
|---|---|
| Total Sales | $6.2M |
| Total Profit | $1.6M |
| Total Orders | 1,194 |
| Units Sold | 13K |

---

## Dashboard Features

### KPI Cards
- Total Sales, Total Profit, Total Orders, Units Sold — displayed as headline metrics at the top

### Interactive Filters (Slicers)
- Filter by **State**, **Year-Month**, **Payment Mode**, and **Category**
- All visuals update dynamically based on slicer selections

### Visualizations
- **Sales Trend by Year** — area chart showing revenue from 2020–2025 with peak in 2022 ($1.5M)
- **Profit by Category** — bar chart comparing Office Supplies, Furniture, and Electronics
- **Units Sold by Category** — donut chart (Electronics 34.85%, Office Supplies 33.41%, Furniture 31.75%)
- **Sales by Category** — horizontal bar chart comparing total revenue per category
- **Sales by City** — bar chart ranking top cities by sales volume
- **State-wise Sales** — interactive US choropleth map showing geographic sales distribution
- **State Performance** — scatter plot comparing profit vs. sales across California, Florida, Illinois, New York
- **Profit by State** — bar chart ranking Florida, New York, California, Texas, Illinois, Ohio
- **Sales by Payment Mode** — donut chart (Credit Card 22.56%, Debit Card 20.23%, UPI 20%, COD, EMI)
- **Top Profitable Products** — bar chart ranking sub-categories by profitability (Markers, Tables, Paper, Electronics top performers)

---

## Key Insights

- **2022 was the peak sales year** at $1.5M — revenue declined to $0.2M in 2025, suggesting a market shift worth investigating
- **Electronics leads in units sold** (34.85%) but Office Supplies and Furniture are close — well-balanced category mix
- **Florida and New York lead in profit** — California has high sales but relatively lower profit margins
- **Markers and Tables are the most profitable sub-categories** — ahead of higher-ticket items like Laptops and Phones
- **Credit Card is the most used payment method** (22.56%), but payment mode distribution is fairly even across all 5 methods
- **State performance scatter plot** shows New York and California outliers in high-sales territory

---

## Repository Structure

```
├── Sales_Performance_Analysis_Dashboard.pbix    # Power BI dashboard file
├── Sales_Dataset.csv                            # Raw dataset (1,194 rows × 12 columns)
├── dashboard_screenshot.png                     # Dashboard preview image
└── README.md
```

---

## How to Open

1. Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `Sales_Performance_Analysis_Dashboard.pbix` in Power BI Desktop
4. The dashboard loads with all visuals and slicers fully interactive

---

## Skills Demonstrated

- Power BI dashboard design and layout (KPI cards, slicers, multi-visual layout)
- DAX measures for KPI calculations (Total Sales, Total Profit, Units Sold)
- Power Query for data transformation and Year-Month feature engineering
- Geospatial visualization (US choropleth map by state)
- Multi-dimensional analysis (category, geography, time, payment method)
- Business storytelling through data visualization

---

## Author

**Mahmudul Hasan**
M.Sc. Computational Social Systems (Business Analytics)
Technical University of Graz & University of Graz
[LinkedIn](https://www.linkedin.com/in/mahmudul-hasan-764307249/) · [GitHub](https://github.com/Mahmudul-Hasan-24)
