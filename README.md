# Superstore Retail & Profitability Analytics Dashboard

## 📊 Project Overview
An executive-level data analytics portfolio project built using **SQL (BigQuery)** for data transformation and **Tableau Public** for visualization. This project evaluates multi-year retail operations (2013–2017) to uncover macroeconomic trends, regional growth opportunities, and critical margin erosion drivers.

## 🏗️ 3-Layer Analytical Architecture
* **Layer 1 (KPI Baseline):** High-level operational health checks tracking Total Sales ($2.30M), Net Profit ($286.40K), Order Volume (5,009), and Average Order Value ($458.61).
* **Layer 2 (Macro Trends & Geography):** Longitudinal analysis highlighting Q4 seasonality spikes alongside geographic performance across the West ($725K), East ($679K), Central ($501K), and South ($392K) regions.
* **Layer 3 (Granular Drivers & Profit Erosion):** Micro-level investigation isolating top margin drivers (Copiers, Phones) against severe loss leaders (Tables, Bookcases) and identifying the **"Discount Cliff"** where orders discounted over 40% consistently incur heavy losses.

## 📁 Repository Contents
* `data/` - Cleaned CSV data exports representing Layer 1, Layer 2, and Layer 3 views.
* `workbook/` - Tableau packaged workbook file (`.twbx`).
* `docs/` - Comprehensive Executive Insights report.
* `sql/` - Modular SQL query scripts and transformation layers used to clean, aggregate, and extract core metrics.

## 🚀 Key Strategic Recommendations
1. **Cap Promotional Discounts:** Enforce a strict maximum discount threshold of 20%–30%.
2. **Restructure Loss-Leader Pricing:** Audit supply chain and shipping costs for Tables and Bookcases.
3. **Double Down on High-Margin Categories:** Reallocate marketing budget toward Copiers and Phones.
