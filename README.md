# SALES-CUSTOMER-INSIGHT-DASHBOARD-USING-POWER-BI

# 1. Introduction

The Sales Customer Insight Dashboard project was developed using Microsoft Power BI to analyze business performance, customer behavior, sales trends, financial metrics, and customer service operations. The project converts raw business data into meaningful visual insights through interactive dashboards and advanced analytics.

Power BI was used to build dynamic and interactive dashboards that enable organizations to monitor key business metrics in real time and support data-driven decision-making.

The dashboard helps businesses:

* Monitor sales performance
* Analyze customer interactions
* Track revenue trends
* Evaluate customer satisfaction
* Identify top-performing products
* Improve operational efficiency

---

# 2. Objectives of the Project

The primary objectives of this project are:

* To analyze sales performance using interactive visual dashboards.
* To monitor financial growth and revenue trends.
* To identify high-performing products and customer preferences.
* To evaluate customer service efficiency.
* To track customer satisfaction metrics.
* To build professional business intelligence reports using Power BI.
* To support data-driven decision-making.

---

# 3. Scope of the Project

This project focuses on:

* Sales analytics
* Revenue analysis
* Customer insights
* Product performance
* Customer service operations
* Business intelligence reporting

The dashboard is useful for:

* Sales Managers
* Business Analysts
* Customer Service Teams
* Operational Managers
* Business Decision-Makers

---

# 4. Tools and Technologies Used

| Tool / Technology               | Purpose                        |
| ------------------------------- | ------------------------------ |
| Microsoft Power BI              | Dashboard Development          |
| Power Query                     | Data Cleaning & Transformation |
| DAX (Data Analysis Expressions) | KPI Calculations               |
| Excel Dataset                   | Data Source                    |
| Data Modeling                   | Relationship Management        |
| Power BI Visualizations         | Reporting & Analytics          |

---

# 5. Dataset Description

The project uses structured datasets containing:

* Customer Details
* Order Information
* Product Sales
* Revenue Data
* Discounts
* Customer Service Records
* Satisfaction Ratings

The customer service dataset contains:

* Customer ID
* Order ID
* Customer Name
* Contact Date
* Contact Type
* Ticket ID
* Agent Handled
* Rating Given

The dataset was imported into Power BI for data modeling and dashboard creation.

---

# 6. Data Cleaning and Transformation

Data preprocessing was performed using Power Query Editor in Power BI.

## Data Cleaning Steps

* Removed duplicate records
* Corrected inconsistent values
* Standardized date formats
* Handled missing data
* Renamed columns properly
* Converted data types

## Data Transformation

* Created calculated columns
* Generated KPI measures using DAX
* Created sales categories and revenue buckets
* Built customer satisfaction calculations
* Established table relationships

---

# 7. Data Modeling

A proper data model was created in Power BI by establishing relationships between:

* Orders Table
* Products Table
* Customer Table
* Revenue Table
* Customer Service Table

Relationships were created using:

* Customer ID
* Order ID
* Product ID

This improved dashboard performance and reporting accuracy.

---

# 8. Dashboard Overview

The Power BI solution contains three major dashboards:

1. Order Fulfillment Dashboard
2. Finance Dashboard
3. Customer Service Dashboard

Each dashboard provides interactive analysis and business insights.

---

# 9. Order Fulfillment Dashboard

## Purpose

The Order Fulfillment Dashboard tracks operational performance and product demand trends.

## Key KPIs

* Total Orders: 794
* Total Revenue: ₹4,38,268
* Average Revenue: ₹551.97
* Average Discount Given: 47%

## Dashboard Components

### Most Ordered Products

Displays top-selling products:

* Crispy Chole Pizzabun
* Paneer Tikka Pizzabun
* Medium Crispy Chole
* Minty Pizzabun

### Daily Sales Trend

Shows sales performance over time.

### Revenue by Product

Displays product-wise revenue contribution.

### Daily Revenue Trend

Tracks daily revenue fluctuations.

### Order Type Analysis

Analyzes:

* Online Orders
* Physical Visit Orders

### Interactive Filters

Users can filter:

* Product Type
* Order Type
* Date
* Revenue Category

## Key Insights

* Crispy Chole Pizzabun generated maximum orders.
* Online orders contributed significantly to total revenue.
* Revenue growth aligned with sales performance.
* Product demand varied across different periods.

---

# 10. Finance Dashboard

## Purpose

The Finance Dashboard evaluates financial performance and revenue trends.

## Dashboard Components

### Total Sales by Day

Shows day-wise sales revenue.

### Average Sales by Day

Displays average transaction value trends.

### Actual vs Rounded Sales

Compares actual and rounded sales values.

### Revenue Bucket Analysis

Categorizes sales into:

* ₹300–₹500
* ₹500–₹700
* ₹700–₹900

### Product Sales vs Average Price

Compares:

* Product revenue
* Product pricing

### Revenue Distribution Analysis

Visualizes revenue contribution by product categories.

## Key Insights

* Premium products generated the highest revenue.
* Revenue concentration was stronger in higher-value products.
* Stable product pricing improved consistent sales performance.
* Financial trends helped identify profitable products.

---

# 11. Customer Service Dashboard

## Purpose

The Customer Service Dashboard evaluates support operations and customer satisfaction performance.

## Dashboard Components

### Agent Satisfaction Analysis

Compares customer ratings for:

* Adrien Martin
* Albain Forestier
* Roch Cousineau

### Agent Interaction Analysis

Displays total customer interactions handled by agents.

### Contact Type Distribution

Analyzes:

* Complaints
* Queries
* Requests

### Customer Satisfaction Analysis

Shows average satisfaction ratings across different interaction types.

### Day-wise Satisfaction Trend

Tracks customer satisfaction trends over time.

### Order-related Contact Analysis

Compares:

* Order-related contacts
* Non-order-related contacts

## Key Insights

* Requests formed the largest share of customer interactions.
* Roch Cousineau handled the maximum number of customer tickets.
* Complaint-related interactions had lower satisfaction ratings.
* Most customer interactions were directly related to orders.

---

# 12. DAX Measures Used

Several DAX measures were created for KPI calculations.

## Sample DAX Measures

### Total Revenue

```DAX
Total Revenue = SUM(Sales[Revenue])
```

### Total Orders

```DAX
Total Orders = COUNT(Orders[Order ID])
```

### Average Revenue

```DAX
Average Revenue = AVERAGE(Sales[Revenue])
```

### Average Customer Rating

```DAX
Average Rating = AVERAGE(CustomerService[Rating Given])
```

### Total Discounts

```DAX
Discount Percentage = AVERAGE(Sales[Discount])
```

---

# 13. Visualizations Used

The following visualizations were used in Power BI:

* KPI Cards
* Bar Charts
* Column Charts
* Pie Charts
* Line Charts
* Donut Charts
* Tables
* Slicers
* Matrix Visuals

These visuals improved dashboard interactivity and analytical capabilities.

---

# 14. Business Insights

## Sales Insights

* Certain products contributed heavily to total sales.
* Online orders generated strong revenue performance.
* Discounts positively influenced order volume.

## Financial Insights

* Premium products generated maximum profit.
* Revenue patterns fluctuated based on customer demand.
* Financial dashboards improved profitability tracking.

## Customer Insights

* Customer satisfaction remained stable overall.
* Complaint handling required operational improvements.
* Faster support response improved ratings.

---

# 15. Challenges Faced

The following challenges were encountered:

* Cleaning inconsistent raw datasets
* Managing relationships between multiple tables
* Creating optimized DAX calculations
* Designing responsive dashboards
* Handling large datasets efficiently

---

# 16. Solutions Implemented

To overcome these challenges:

* Power Query was used for preprocessing.
* Proper data modeling improved performance.
* Optimized DAX measures improved calculations.
* Interactive filters enhanced usability.
* Standardized visual formatting improved readability.

---

# 17. Project Outcomes

The project successfully:

* Converted raw data into actionable business insights
* Improved sales and customer analysis
* Enabled interactive business reporting
* Enhanced operational visibility
* Demonstrated business intelligence capabilities using Power BI

---

# 18. Skills Demonstrated

## Technical Skills

* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* Dashboard Design
* Data Visualization
* KPI Reporting

## Analytical Skills

* Sales Analysis
* Revenue Analysis
* Customer Behavior Analysis
* Customer Satisfaction Analysis
* Business Performance Evaluation

---

# 19. Future Enhancements

Future improvements may include:

* Real-time database connectivity
* Predictive analytics
* AI-powered forecasting
* Automated report refresh
* Mobile dashboard optimization
* Advanced customer segmentation

---

# 20. Conclusion

The Sales Customer Insight Dashboard using Power BI demonstrates the effective implementation of business intelligence and data analytics techniques for sales and customer analysis.

The dashboard provides:

* Real-time business insights
* Interactive visual reporting
* KPI monitoring
* Customer behavior analysis
* Financial performance tracking

The project highlights strong capabilities in:

* Business intelligence
* Power BI dashboard development
* Data analytics
* Data visualization
* Business reporting

Overall, the project supports organizations in making informed, data-driven business decisions.
