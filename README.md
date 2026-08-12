# E-Commerce Sales Intelligence

## Project Overview

This project analyses a multi-table e-commerce marketplace dataset to identify commercial opportunities, customer-experience drivers, seller-performance risks, and operational improvement areas.

The analysis follows an end-to-end analytical workflow: understanding the source data, validating relationships and data quality, investigating customer feedback, evaluating product and category performance, analysing seller and delivery performance, and translating the findings into actionable business recommendations.

## Business Questions

The project investigates questions such as:

- Which product categories generate the strongest revenue and sales volume?
- What are the main drivers of customer satisfaction and dissatisfaction?
- Which high-revenue categories may be exposed to customer-experience risk?
- How does delivery performance relate to customer ratings?
- Which sellers contribute the most revenue?
- Which established sellers show weaker operational performance?
- How concentrated is marketplace revenue across sellers and regions?
- What actions could improve commercial and operational performance?

## Analysis Structure

### 01 — Data Understanding
Initial exploration of datasets, tables, columns, and potential analytical use cases.

### 02 — Relationship Investigation
Validation of table granularity, primary keys, foreign keys, and relationships before merging datasets.

### 03 — Data Quality Assessment
Assessment of missing values, duplicates, data types, timestamps, and logical inconsistencies.

### 04 — Customer Review Analysis
Analysis of review scores and customer feedback to identify recurring satisfaction and dissatisfaction themes.

### 05 — Product & Sales Performance Analysis
Analysis of category revenue, sales volume, ratings, delivery performance, and monthly sales trends.

### 06 — Seller & Delivery Performance Analysis
Evaluation of seller revenue, order volume, customer ratings, delivery reliability, regional performance, and seller concentration.

### 07 — Executive Business Summary
Decision-focused consolidation of the project's strongest findings, visualisations, and strategic recommendations.

## Key Findings

- Health & Beauty generates the highest overall category revenue while maintaining relatively strong customer satisfaction.
- Bed Bath Table is one of the strongest categories by sales volume but performs below the overall average review score.
- Watches & Gifts generates strong revenue despite lower unit volume, reflecting a higher-value product mix.
- Office Furniture presents a weaker combination of customer satisfaction and fulfilment performance.
- Seller late-delivery rate has a moderate negative association with average review score of approximately **-0.52**.
- Average seller delivery duration also shows a negative relationship with customer ratings of approximately **-0.57**.
- The top 10 sellers generate approximately **13.15% of item revenue**.
- Approximately **544 sellers generate 80% of item revenue**.
- Seller activity is heavily concentrated in São Paulo.

## Business Recommendations

1. Protect and promote categories that combine strong revenue, volume, and customer satisfaction.
2. Prioritise operational improvements in high-revenue categories and sellers with weaker customer ratings.
3. Introduce seller scorecards combining commercial and customer-experience metrics.
4. Investigate sellers with persistently high late-delivery rates.
5. Use customer-review themes as an ongoing operational monitoring signal.
6. Increase promotion and cross-selling around highly rated categories.
7. Improve inventory and promotional planning around observed seasonal demand.
8. Monitor category and seller performance over time rather than relying only on lifetime averages.

## Tools & Skills Demonstrated

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Data cleaning
- Relational data analysis
- Exploratory data analysis
- Customer feedback analysis
- Revenue and product analysis
- Seller-performance analysis
- Data visualisation
- Business interpretation
- Strategic recommendations

## Dataset

The project uses the Brazilian Olist e-commerce dataset.

Raw CSV files are not included directly in this repository.

After obtaining the dataset, place the source CSV files inside:

```text
data/raw/