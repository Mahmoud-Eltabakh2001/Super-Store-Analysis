# Super-Store-Analysis

# 🛒 Store Sales Dashboard – Power BI Project

## 📊 Overview
This Power BI report provides an interactive dashboard to analyze store sales performance across different countries, products, and time periods. It allows stakeholders to gain insights into key performance indicators (KPIs), trends, and comparisons to support data-driven decision-making.


📊 Store Sales Dashboard – Power BI Project

**Tools:** Power BI, DAX, Power Query

**Key Insights:**

- Analyzed 2.3M USD in total sales and identified that the Technology category contributes the highest sales at ~0.84M USD.

- Found that the West region led all regions with 0.73M USD in sales, while the South region was underperforming at 0.39M USD.

- Discovered that Consumer segment accounted for over 50% of total sales.

- Year-over-year trend showed steady growth: from 0.47M in 2015 to 0.73M in 2017 (~55% increase).

- Built custom DAX measures to calculate KPIs: Profit Margin, Total Orders, and Quantities Sold.

- Designed an interactive report used to support strategic decisions in sales and marketing.


## 🔍 Key Features
- **Sales Overview**: Total sales, average sales, and sales trends over time.
- **Geographical Analysis**: Sales breakdown by country.
- **Product Performance**: Top-selling products and product categories.
- **Customer Segmentation**: Insights based on customer type or region (if available).
- **Interactive Filters**:
  - Slicers for Country, Product, Date
  - Dynamic charts responding to user selections

## 📁 File Structure
- `Store Dashboard.pbix`: Main Power BI report file.
- `README.md`: Project description and usage instructions.
- `Data\super_store.xlsx`: Dataset.

## 📈 Visualizations Included
- Bar charts (Sales by Region/Product)
- Line chart (Sales Over Time)
- KPIs (Total Sales, Avg Sales, etc.)
- Pie charts

## 🧾 Data Sources
The dataset appears to be based on sample sales data (`sales_data_sample.csv`) including fields such as:
- `ORDERNUMBER`
- `ORDERDATE`
- `SALES`
- `COUNTRY`
- `PRODUCTLINE`

## 🛠️ Customizations
- The report uses standard Power BI visuals and DAX measures for aggregation and filtering.
- Slicers can be customized to use dropdowns, lists, or buttons based on user preference.

