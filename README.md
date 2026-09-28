# Sales-Profit-Analysis-Dashboard-Power-BI
## Project Overview

This project focuses on analyzing sales performance and profitability of a large product distributor operating across the US and international markets.

The goal was to build an interactive multi-page Power BI report that helps identify key sales and profitability patterns, analyze business performance over time, and evaluate factors affecting profit.

## Tools

* Power BI
* DAX
* Power Query
* Data Modeling

## Dataset

The dataset contains information about:

* Orders and sales
* Products and product categories
* Customers
* Shipping locations
* Product returns
* Sales representatives

## Data Model

A relational data model was created using fact and dimension tables, including a dedicated Date table.

Main tables:

* `factOrders`
* `dimProduct`
* `dimCustomers`
* `dimAddress`
* `dimReturns`
* `dimSalesReps`
* `DimDate`

A separate `_measures` table was used to organize DAX measures.

## Key Metrics

The dashboard includes the following key metrics:

* Total Sales
* Total Profit
* Profit Margin
* Total Quantity
* Orders Quantity
* Sales Share

## Dashboard Pages

### 1. Financial Overview

Provides a high-level overview of business performance.

The page includes:

* Sales and Profit trends over time
* Top products
* Sales by region
* Sales by product category
* KPI cards
* Interactive year filters

### 2. Monthly Metrics

Provides a detailed analysis of monthly business performance.

The page includes:

* Monthly Sales
* Monthly Profit
* Quantity
* Orders
* Period-over-period comparisons
* Interactive slicers for deeper analysis

### 3. Discount Analysis

Analyzes the relationship between discount levels, sales volume and profitability.

The page includes:

* Number of orders by discount level
* Sales by discount level
* Profit by discount level
* Interactive filters

### 4. Sub-category Analysis

Analyzes sales and profitability across product sub-categories.

The page helps identify:

* High-performing sub-categories
* Profitability differences
* Sales contribution
* Performance patterns across product groups

### 5. Orders Details

Provides detailed order-level information for deeper analysis.

This page can be used to investigate individual orders based on selected filters and business attributes.

## Key Results

* Identified sales and profitability patterns across products, regions and categories.
* Analyzed monthly changes in Sales and Profit.
* Evaluated the relationship between discount levels, sales volume and profitability.
* Created an interactive reporting solution that allows users to move from high-level KPIs to detailed order-level analysis.

## Skills Demonstrated

* Data Modeling
* DAX
* Power Query
* Data Analysis
* KPI Development
* Business Performance Analysis
* Data Visualization
* Interactive Dashboard Development
