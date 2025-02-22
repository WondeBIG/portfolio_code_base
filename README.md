
#  Portfolio Repository for Optimized SQL Queries


### Overview

These queries provide insights into supply chain efficiency, facility utilization, and inventory distribution, making them useful for business intelligence (BI), supply chain management (SCM), and logistics analytics.

### Key Queries & Use Cases

1. Service Utilization Analysis
	* Tracks operational vs. suspended healthcare facilities over time.
	* Links facility activity with order fulfillment trends.

2. Stock & Inventory Management
	* Monitors daily stock levels, order fulfillment, and stock-outs.
	* Provides insights on missed opportunities due to inventory shortages.

3. Medical & Vaccine Distribution
	* Categorizes medicine, vaccines, and medical supplies based on demand & distribution patterns.
	* Analyzes facility-based utilization trends.

### 1. Service Utilization Analysis

 Query Name: service_utilization.sql
 Purpose: Tracks the status of healthcare facilities (operational, suspended) and their correlation with order activity.

#### Key Metrics Tracked
*  Number of active healthcare facilities per month
* Total facilities placing orders per warehouse
* Historical utilization trends (2019 - Present)


			
#### 2. Stock & Inventory Management

Query Name: stock_inventory_management.sql
Purpose: Provides insights on inventory levels, stock-outs, and order fulfillment efficiency.

 #### Key Metrics Tracked

* Days in stock / out of stock per product
* Average daily consumption per SKU
* Number of missed sales opportunities due to stockouts
* Order fulfillment rates per warehouse & facility



### Medical & Vaccine Distribution

Query Name: medical_vaccine_distribution.sql
Purpose: Analyzes healthcare supply chain performance based on product categories.

##### Key Metrics Tracked
* Distribution of medicines, vaccines, and essential supplies
* Order fulfillment by facility and product type
* Tracking of restricted and high-priority supplies



## How to Use These Queries

* Clone the repository & explore queries
* Open SQL queries and modify parameters (start_date, end_date, warehouse_id)
* Run queries in your data warehouse (e.g., Snowflake, Redshift, BigQuery, PostgreSQL, etc.)

## Contributing & Feedback

#### Want to suggest improvements?
* Submit an issue or pull request via GitHub.
* Fork & adapt the queries for your own projects.

#### Contact: osikaniian@gmail.com

