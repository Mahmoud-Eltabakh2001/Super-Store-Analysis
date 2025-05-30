# Power BI Sales Dashboard Project

## 📁 Project Overview

This project demonstrates the process of transforming a flat file (CSV format) into a **Star Schema** data model using Power BI, followed by designing an insightful and interactive **sales dashboard**.

---

## 🧱 Data Source

- **Type**: Flat file (CSV)
- **Records**: 24,000+ sales transactions
- **Content**: Sales data including products, order dates, shipment details, taxes, territories, and order status

---

## 📊 Key Statistics

From the dataset:

- **Total Transactions**: 24,000+
- **Total Orders**: 1,465
- **Total Freight**: $916K
- **Total Tax**: $3M
- **SubTotal Sales**: $30M
- **Total Amount Due**: $34M
- **Top Product Category by Orders**: Bikes (9,141 orders)
- **Top Territory by SubTotal**: Canada

---

## 🗃️ Data Modeling

The CSV data was cleaned and transformed into a **Star Schema** with:

### 🎯 Fact Table:
- `Fct_Order_Sales`: Sales metrics including OrderQty, LineTotal, UnitPrice, Freight, TaxAmt, etc.

### 📐 Dimension Tables:
- `Dim_Product`: Product, ProductCategory, ProductSubCategory
- `Dim_ShipMethod`: ShipMethodID, ShipMethod
- `Dim_Territory`: TerritoryID, TerritoryGroup
- `Dim_Status`: Status of each order (Approved, In process, etc.)
- `Dim_OrderDate`: Calendar table for Order Date


All relationships are implemented as one-to-many between dimensions and the fact table, forming a clean **star schema**.

---

## 📊 Dashboard Features

The dashboard was built using **Power BI Desktop** and includes:

### 📌 KPIs:
- Total Transactions
- Number of Orders
- Total Freight
- Total Tax
- SubTotal
- Total Due

### 📈 Visuals:
- **Orders by Year** (2011 - 2014)
- **Orders by Status** (Approved, In Process, Shipped, etc.)
- **Orders & Transactions by Product Category**
- **Orders and SubTotal by Territory**

---

## 🧰 Tools & Technologies

- Power BI Desktop
- Power Query Editor
- DAX for calculated fields and KPIs

---

## 🎯 Key Learnings

- Transitioning from flat file to star schema modeling
- Creating custom date dimensions and managing relationships
- Building dynamic and interactive dashboards with DAX
- Business storytelling through visuals and KPIs
