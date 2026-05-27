# New-Wheels-SQL-Project
An end-to-end relational database investigation using SQL to diagnose supply chain blockages, calculate customer lifetime value, and generate strategic insights for an automotive retail enterprise.

## Business Objective
Analyze structured enterprise data across customer, inventory, transaction, and shipping tables to isolate severe operational bottlenecks. This project translates raw relational data into high-density commercial insights to optimize shipping fulfillment windows, evaluate regional customer density, and maximize revenue velocity.

## Relational Architecture & Tech Stack
* **RDBMS Engine:** MySQL
* **Core Methodologies:** Multi-Table Joins, Hierarchical Subqueries, Advanced Aggregations, Window Functions, Analytical Feature Engineering, Data Manipulation Language (DML)

## Advanced Query Architectures & Analytical Applications

### 1. Advanced Relational Intersections (Joins & Subqueries)
* Constructed complex `INNER`, `LEFT`, and `RIGHT JOIN` structures across transactional datasets to trace orders from origin fulfillment to final destination delivery.
* Implemented nested subqueries and Common Table Expressions (CTEs) to isolate historical purchasing trends without degrading database execution speeds.

### 2. Analytical Stratification (Window Functions & Aggregations)
* Leveraged Window Functions (`RANK()`, `DENSE_RANK()`, `ROW_NUMBER()`) to classify high-value consumer tiers and partition regional sales performance metrics.
* Applied advanced aggregations (`SUM()`, `AVG()`, `COUNT()`) grouped by temporal dimensions to map seasonal revenue fluctuations.

### 3. Data Transformation & Temporal Calculations
* Utilized native built-in date/time functions to engineer dynamic metrics calculating the exact turnaround latency between order placement and customer arrival.
* Executed targeted Data Manipulation Language (DML) configurations to ensure cross-table data integrity and structural cleanliness.

## Key Business Discoveries & Actionable Insights
* Total Revenue $125,482,804.37, Last Quarter Revenue $23,496,008.10.
* **Fulfillment Bottleneck Identification:** Isolated the specific shipping avenues and fulfillment centers causing severe delivery delays, giving operations a data backed roadmap to renegotiate logistics contracts.
* **Customer Behavior Segmentation:** Stratified the customer database by geographical purchase frequency, revealing high-density, untapped regional hubs ideal for localized marketing spend.
* **Product Performance Analytics:** Calculated individual product-line velocity metrics, identifying high-margin automotive inventory segments that should be prioritized for stocking cycles. Average Days to Ship 

## Repository Blueprint
* **`Queries/`**: Organized production-ready `.sql` files containing clean, formatted, and fully commented script architectures.
* **`Schema/`**: Logical database entity mapping files showcasing data typing, primary keys, and relational foreign constraints.
