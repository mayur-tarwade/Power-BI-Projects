
# 📊 Global Super Store Power BI Report

## 🗂️ Overview

Global Super Store has migrated its business intelligence from Excel to Power BI to gain real-time, actionable insights across sales, marketing, operations, and finance. This report enables executives and analysts to evaluate performance, track targets, identify trends, and make data-driven decisions efficiently.

---

## 📌 Executive Summary Cards

| KPI                    | Description                                                 |
|------------------------|-------------------------------------------------------------|
| **Total Sales**        | Cumulative sales (fixed and dynamic values)                 |
| **Total Profit**       | Total profit earned (fixed and dynamic values)              |
| **Total Orders**       | Count of orders processed                                   |
| **Total Customers**    | Distinct count of customers served                          |

> 💡 *Fixed metrics are shown in separate cards to remain unaffected by slicer interactions.*

---

## 📅 Yearly and Monthly Analysis

### 📈 Annual Sales & Trend
- Line chart showing yearly sales (2014–2019).
- Includes a trend line for strategic growth observation.

### 📊 Monthly Seasonality (2016–2019)
- Combo chart: Monthly Sales vs Profit.
- Target Line: $1.7M/month.
- Highlights deviation from monthly target.
- Profit fluctuation analysis to reveal seasonal trends.

---

## 🌍 Regional & Market Insights

### 🌐 Regional Performance
- Bar chart comparing **sales and profits by market and region**.
- Region-wise contribution analysis for resource planning.

### 🗺️ Geographic Maps

#### Sales Map
- Conditional coloring based on total sales:
  - `<80k`: Dark Red
  - `80k–200k`: Red
  - `200k–700k`: Green
  - `>700k`: Golden

#### Profit Map
- Gradient color range:
  - **Lowest profit** → Red
  - **Highest profit** → Green

---

## 📆 Time-Based Breakdowns

- **Quarterly Sales**: Sales per financial quarter.
- **Sales from 15-Apr-2019 to 15-Nov-2019**: Card displaying total.

---

## 🔄 Dynamic Interactivity

- **Category** and **Segment slicers** to filter visuals dynamically.
- **Reset Filter Button**: Clears all slicer selections with one click.

---

## 🛒 Product and Sales Insights

- **Top 10 Products by Profit**
- **Top-Selling Product per Country**
- **Category Leader per Year**
- **Product Segment Performance**:
  - Shows % contribution to overall and prior segment.
- **Sales by Year & Region**: 2D bar chart.

---

## 🧑 Customer Analysis

### CLV (Customer Loyalty Value)
Formula:
```
CLV = (Average Order Value × Avg Profit Margin) / Purchase Frequency
```
- **Top 10 Loyal Customers** based on CLV.

### Age Clustering:
- **Age Bins**:
  - 14–19: Teen
  - 20–30: Young
  - 30–40: Adult
  - 40–50: Old Adult
  - >50: Old

- Pie/Bar chart: Customer count & % share by age cluster.

### Gender + Income + Region + Sub-Category
- Interactive analysis of **consumer preferences** based on:
  - Gender
  - Income (Above/Below average)
  - Sub-Category
  - Region

---

## 🧾 Income & Order Matrix

- **Income Grouping**:
  - A: 0–30k
  - B: 30k–60k
  - C: 60k–100k
  - D: 100k–150k
  - E: >150k

- Matrix visual: Region vs Age Group vs Income Group → Order Count

---

## 🚚 Order Fulfillment Insights

### Order Status
- Classification:
  - **Delayed**: `Shipping Date – Order Date > 2 days`
  - **On-Time**: Otherwise

- Visual: On-time vs delayed order ratio.

### Returns
- Count of **returned orders** by **market** and **segment**.

---

## 🧮 Financial & Cost Insights

### Cost Price Calculation
```
Cost Price = Sales - Profit - Shipping Cost
```
- Matrix: Average cost per unit by Category/Sub-Category.

### Monthly + Quarterly Sales (2019)
- Monthly sales for last 2 financial quarters.
- Quarterly comparison for performance review.

---

## 🧠 Smart Customer Intelligence

### High-Value Customers (Per Region)
- Definition: Orders > $1500 with profit margin ≥ 25%
- % of high-value customers per total orders in region.

### Customer Acquisition Analysis
- New customers YoY (2016–2019).
- % growth of customer base over years.

### Churn Analysis
- Churned customers per year (2016–2018).

---

## 📦 Product-Level Metrics

- % Quantity Share:
  - **Routers, Headsets, Keyboards** in Accessories.
  - **Leather Armchair, Rocking Chair, Adjustable Chairs** in Chairs.
  - **iPhone, Samsung, Motorola** in Phones.

---

## 🧑‍💼 Managerial & Sales Team KPIs

- **Top 3 Managers (Yearly)** by total sales.
- **Country Rank Variance**:
  - Show 11th–19th top countries by sales.
  - Gap analysis between #1 and rest of Top 10.

---

## 🧩 Miscellaneous Enhancements

- **Salutation Logic**:
  - Male: Mr.
  - Female Unmarried: Miss.
  - Female Married: Mrs.

- **Company Diversification**:
  - Total distinct companies by Category/Sub-Category.

- **Interactive Country Filter**:
  - Dynamic filter: Show only countries within selected profit % range.

---

## 🧠 Smart Query Support (Future-Ready)
Implementation of:
- **Interactive FAQ Panel**
- **Search-based Q&A** using Power BI Q&A visual
