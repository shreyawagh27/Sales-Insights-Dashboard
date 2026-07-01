# Sales-Insights-Dashboard

## **Project Title**

**Sales Insights Dashboard**

An interactive Tableau dashboard designed to analyze sales performance, revenue trends, customer behavior, product performance, and market-wise insights using MySQL data.

---

## **Short Purpose**

The Sales Insights Dashboard helps business stakeholders monitor sales performance through interactive KPIs and visual reports.

The dashboard enables decision-makers to analyze revenue trends, identify top-performing markets, customers, and products, and support strategic business decisions with data-driven insights.

---

## **Tech Stack**

The dashboard was built using the following tools and technologies:

* **Tableau Desktop** — Primary platform for dashboard development and visualization.
* **MySQL** — Database used for storing and querying sales data.
* **SQL** — Used for data extraction, filtering, and validation.
* **Data Modeling (Star Schema)** — Created relationships between fact and dimension tables.
* **Calculated Fields** — Used for custom metrics, KPIs, and business calculations.
* **Parameters & Filters** — Implemented dynamic filtering for Year, Month, Top-N Customers, and Top-N Products.
* **Interactive Charts & Dashboards** — Developed business-focused visualizations and KPI cards.

---

## **Data Source**

Source data used in the dashboard:

* Sales Transactions
* Customer Data
* Product Data
* Market Data
* Date/Calendar Data

The dataset includes information such as:

* Customer Name
* Product Code
* Market
* Sales Quantity
* Sales Amount
* Transaction Date
* Currency (INR/USD)

---

## **Data Cleaning & Transformation**

Performed using **Tableau Data Source** and **MySQL**:

* Removed invalid and duplicate records.
* Normalized currency values by converting USD transactions into INR.
* Filtered incomplete and inconsistent transaction records.
* Corrected data types for accurate analysis.
* Created calculated fields for normalized sales amount and business KPIs.
* Built a Date hierarchy (Year → Quarter → Month) for time-based analysis.

---

## **Data Modeling**

Created a relational data model using:

* **Star Schema**
* One-to-many relationships
* Fact and Dimension tables

Tables connected:

* Transactions (Fact Table)
* Customers
* Products
* Markets
* Date

---

## **Calculated Fields / KPIs Created**

Key measures and calculated fields used in the dashboard:

| Measure                  | Purpose                              |
| ------------------------ | ------------------------------------ |
| Total Revenue            | Calculates total sales revenue       |
| Sales Quantity           | Calculates total units sold          |
| Revenue by Market        | Market-wise revenue analysis         |
| Sales Quantity by Market | Market-wise sales quantity           |
| Top Customers            | Highest revenue-generating customers |
| Top Products             | Best-selling products by revenue     |
| Revenue by Year          | Year-wise sales trend analysis       |
| Normalized Sales Amount  | Converts USD transactions into INR   |

---

## **Dashboard Features**

### KPI Cards

* Total Revenue
* Sales Quantity

### Interactive Visuals

* Revenue by Market
* Sales Quantity by Market
* Top 5 Customers by Revenue
* Top 5 Products by Revenue
* Revenue Trend by Year

### Filters / Parameters

* Year
* Month
* Top-N Customers
* Top-N Products

---

## **Business Insights**

Some key insights identified from the dashboard:

* Identified high-performing markets based on revenue and sales quantity.
* Analyzed top revenue-generating customers and best-selling products.
* Tracked year-wise revenue trends to monitor business growth.
* Compared market-wise sales performance to identify profitable regions.
* Standardized multi-currency transactions using currency normalization for accurate reporting.

---

## **Conclusion**

The Sales Insights Dashboard provides a comprehensive view of business performance, enabling stakeholders to monitor sales KPIs, identify growth opportunities, and make data-driven decisions through interactive visual analytics.

The project demonstrates skills in:

* Tableau Dashboard Development
* MySQL & SQL
* Data Cleaning & Transformation
* Data Modeling (Star Schema)
* Calculated Fields
* Interactive Dashboard Design
* KPI Development
* Business Intelligence & Reporting
* Sales Performance Analysis
* Data Visualization
