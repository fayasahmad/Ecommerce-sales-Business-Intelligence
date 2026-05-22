# 📦 Global E-Commerce Sales Intelligence Dashboard

A multi-page Power BI report built to turn fragmented transactional data into a unified view of sales performance, profitability, and customer behavior — designed for strategic decision-making around inventory and regional growth.

---

## 🎯 What This Project Solves

Raw e-commerce transaction exports are good for record-keeping, but terrible for strategy. This dashboard bridges that gap — consolidating thousands of rows of shipping and sales data into clear, interactive visuals that highlight where revenue is growing, which products are most profitable, and where the business should expand next.

---

## 📂 Project Files

Due to large file sizes, the dataset and Power BI report are hosted externally:

- **[Download Dataset (CSV)](https://drive.google.com/drive/folders/1hNZlC-M1Dv4WjPXFDBQvleKClPAaPEsk?usp=sharing)** 📁
- **[Download Power BI Report (.pbix)](https://drive.google.com/file/d/1eFhU5YJ0sNOS40ycY6X11oXfY_5vJyFz/view?usp=sharing)** 📊

---

## 🖼️ Dashboard Pages

### 1. Executive Summary
Top-level KPIs at a glance — Total Revenue, Profit Margin, and Year-over-Year growth trends.

---

### 2. Geographic Sales Distribution
An interactive map identifying regional hotspots, underperforming territories, and expansion opportunities.

---

### 3. Product & Category Performance
Breaks down which product lines are driving the most revenue and which carry the healthiest margins.

---

### 4. Customer Insights
Segments customers by purchasing behavior and frequency to support targeted marketing efforts.

---

## 🛠️ Technical Approach

### Data Modeling — Star Schema

The report uses a **Star Schema** for clean, performant filtering. A central **Sales Fact Table** connects to dimension tables for Product, Customer, Geography, and a custom **Calendar table** built in Power Query.

---

### DAX Measures

Custom DAX formulas power the core analytics:

- **Time Intelligence** — `TOTALYTD` and `SAMEPERIODLASTYEAR` for accurate period-over-period comparisons
- **Profitability** — Dynamic measures for **Net Profit %** and **Average Order Value (AOV)**
- **Ranking** — `RANKX` to surface the Top 10 products by revenue, filterable by category

---

### Power Query — ETL Pipeline

- Cleaned and standardized messy address fields into structured geographic hierarchies
- Handled null values and outliers in shipping cost columns
- Optimized data types throughout to reduce file size and improve refresh performance

---

## 💡 Key Insights Uncovered

- **Margin vs. Volume Trade-off** — High-volume categories often carry lower margins, requiring a nuanced promotional approach rather than blanket discounting
- **Untapped Markets** — Regional analysis flagged several geographic zones with strong demand signals but low current penetration
- **Logistics Correlation** — Certain shipping methods showed a measurable link to higher return rates, pointing to a logistics optimization opportunity

---

## 🚀 How to Use

1. **Interactive Mode** — Download the `.pbix` file and open in Power BI Desktop to use slicers, drill-throughs, and tooltips
2. **Review Mode** — Browse the screenshots in this repo to explore the dashboard layout and data architecture without Power BI

---

## 🏷️ Tags

`power-bi` · `dax` · `data-modeling` · `star-schema` · `business-intelligence` · `data-visualization` · `ecommerce-analytics`

---

## 📄 License

MIT License — free to use and adapt with attribution.
