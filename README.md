# Olist-Brazil-Ecommerce-Dashboard


## Problem Statement
E-commerce businesses in Brazil generate vast amounts of data from orders, customers, sellers, payments, products, and shipments. Without a consolidated system to manage and analyze this data, it is difficult for businesses to gain visibility into revenue trends, customer behavior, seller contributions, delivery efficiency, and overall performance. Manual reporting is time-consuming, fragmented, and often fails to provide actionable insights.  

This project solves that challenge by building an **integrated Power BI dashboard** powered by a structured data model. It enables business users to explore sales, customers, products, logistics, and reviews in one place, improving strategic and operational decision-making.  

---

## Tools and Technologies Used
- **Power BI Desktop** – dashboard creation and interactivity  
- **Power Query** – data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – custom calculations and KPIs  
- **Relational Data Modeling** – star schema and fact-dimension design  
- **Excel/CSV** – source files for raw e-commerce data  

---

## Data Modeling
The foundation of this project is a well-structured data model that connects multiple datasets:  

- **Orders Dataset**: order details, timestamps, approval and delivery metrics  
- **Order Items Dataset**: product-level details, price, and freight charges  
- **Products Dataset**: product IDs and category mapping  
- **Customers Dataset**: customer details, location, and unique IDs  
- **Sellers Dataset**: seller IDs, locations, and order associations  
- **Payments Dataset**: payment type, installments, and values  
- **Reviews Dataset**: review scores and categories  
- **Geolocation Tables**: mapping of customer and seller zip codes to states  
- **Insights Tables**: orders per state, sellers per state  

This schema ensures accurate relationships across fact tables (orders, items, payments, reviews) and dimension tables (customers, products, sellers, geography). It supports seamless analysis of sales, customer journeys, product performance, and delivery behavior.  

*(Insert Data Model diagram here – e.g., `/images/Data Model.png`)*  

---

## Process Breakdown
1. **Data Preparation**  
   - Cleaned and transformed raw data using Power Query.  
   - Standardized keys (IDs, categories, states) for consistency.  
   - Handled missing values and duplicate entries.  

2. **Data Modeling**  
   - Designed relationships between transactional and dimensional tables.  
   - Built a star schema linking orders, customers, sellers, products, and payments.  
   - Created calculated measures in DAX (Revenue, Freight, Avg Delivery, Review Scores).  

3. **Dashboard Development**  
   - **Sales Dashboard**: Total Revenue (R$16M), Orders (111K), Customers (99K).  
   - **Customer Dashboard**: Monthly trends, average spend (R$134.82).  
   - **Category Dashboard**: 71 categories with top contributors like Health & Beauty and Sports & Leisure.  
   - **Geography Dashboard**: Sales across 27 customer states and 23 seller states (São Paulo leads with R$5.13M).  
   - **Seller Dashboard**: Analysis of 3,095 sellers and their performance.  
   - **Reviews & Price Dashboard**: Customer satisfaction (76K positive reviews) and revenue by price range.  
   - **Shipment Dashboard**: Actual vs. estimated delivery (7 vs. 20 days) and on-time vs. late delivery rates.  

4. **Interactivity**  
   - Slicers for year, quarter, state, category, and seller.  
   - Drill-throughs from state → city, category → product.  
   - Dynamic visuals for monthly and seasonal comparisons.  

---

## Outcome and Impact
- Built a **single source of truth** for Brazil’s e-commerce business performance.  
- Identified São Paulo as the top state (R$5.13M) and São Paulo city as the leading city (R$1.89M).  
- Highlighted Health & Beauty as the top category (14.85% of revenue).  
- Uncovered delivery efficiency insights: average delivery 7 days vs. 20-day estimates.  
- Delivered review sentiment analysis with 76K positive, 15K negative, and 8K neutral ratings.  
- Enabled leaders to monitor KPIs in real time with drill-down flexibility.  

---

## Business Value
- **Revenue Growth**: Clear view of best-performing states, categories, and sellers.  
- **Customer Insights**: Better understanding of buying behavior and satisfaction.  
- **Operational Efficiency**: Shipment analysis improves logistics planning.  
- **Seller Management**: Visibility into top and underperforming sellers.  
- **Strategic Decisions**: Data-driven approach for expansion, marketing, and inventory planning.  

---


---

## Preview
- Data Model Diagram  
- Dashboard Screenshots (Sales, Customer, Seller, Shipment, etc.)  
