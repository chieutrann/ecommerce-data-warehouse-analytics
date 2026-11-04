# ecommerce-data-warehouse-analytics

# Product Owner Report
## Olist E-Commerce Performance Analytics

### 1. Project Overview
The objective of this project is to develop an interactive business performance dashboard using the Brazilian E-Commerce Public Dataset (Olist).

From a Product Owner perspective, the goal is to transform raw business data into actionable insights that help management monitor sales, delivery performance, and customer satisfaction.

### 2. Business Problem
E-commerce performance depends on several interconnected areas. Without a consolidated overview, management may struggle to identify revenue trends, delivery bottlenecks, and factors affecting customer satisfaction.

The project addresses four key business questions:

- Which product categories generate the highest revenue?
- Which Brazilian states experience the most delivery delays?
- Are late deliveries associated with lower customer review scores?
- What percentage of customers make repeat purchases?

### 3. Product Goals and Prioritisation
Given the limited development time, I prioritised the most valuable features for a Minimum Viable Product (MVP).

The main priorities were:
1. Monitor overall business performance through KPIs.
2. Identify sales trends and top-performing categories.
3. Highlight regional delivery problems.
4. Understand the relationship between delivery performance and customer satisfaction.
5. Measure repeat purchasing behaviour.

Predictive analytics and real-time tracking were excluded from the initial scope.

### 4. Solution
The solution consists of three components:

- **Data preparation:** Databricks SQL to integrate and transform the Olist datasets.
- **Analytical data models:** Sales, delivery, and customer retention datasets.
- **Visualisation:** A single interactive Tableau dashboard providing an executive overview.

### 5. Success Metrics

| Area | KPI |
|---|---:|
| Total Revenue | 13,221,498 |
| Total Orders | 96,478 |
| Total Customers | 93,358 |
| On-Time Delivery Rate | 91.9% |
| Repeat Purchase Rate | 3.003% |

### 6. Expected Business Value
The solution provides management with a consolidated view of business performance, helping stakeholders identify revenue opportunities, prioritise delivery improvements, and investigate customer satisfaction issues.

As a Product Owner, the focus was on translating business questions into measurable requirements, prioritising features based on business value, and delivering a practical MVP within the available timeframe.

### 7. Business Insights & Recommendations

**Delivery Performance**

- **Insight:** Olist achieved an on-time delivery rate of 91.88%, while 8.12% of orders were delivered late. Delivery performance varies significantly by state, with Alagoas (AL) recording the highest late-delivery rate at 23.93%, followed by Maranhão (MA) at 19.67%.
- **Recommendation:** Prioritise logistics improvements in underperforming states, investigate regional delivery bottlenecks, and strengthen carrier performance monitoring to reduce delays.

**Sales Performance**

- **Insight:** Health & Beauty generates the highest revenue (9.33%), followed by Watches & Gifts (8.82%). However, Bed, Bath & Table has the highest order volume (9.53%), showing that the most popular category is not necessarily the highest revenue generator.
- **Recommendation:** Prioritise high-revenue categories while exploring opportunities to increase revenue per order in high-volume categories.

**Customer Satisfaction**

- **Insight:** Comparing review scores for late and on-time deliveries helps identify the relationship between delivery performance and customer satisfaction.
- **Recommendation:** Investigate negative reviews, improve delivery reliability, and monitor product quality to strengthen customer loyalty.

### 8. Limitations
The dataset represents historical transactions (2016–2018), not real-time operations. Furthermore, the available data does not support a fully verified OTIF measurement. Findings should therefore be interpreted within these limitations.