# Coffee Sales Dashboard — Excel Data Analysis Project

## Project Overview
This project presents an interactive **Coffee Sales Dashboard** built using Microsoft Excel to analyze sales performance, customer behavior, and product trends.
The dashboard provides business insights through data preparation, lookup-based data integration, pivot tables, and dynamic visualizations.
The objective of this project was to demonstrate practical data analysis skills including:

- Data cleaning and preparation
- Relational data linking
- Data aggregation
- KPI creation
- Interactive dashboard design
- Business insight generation

## Business Objectives
- Analyze overall coffee sales performance
- Identify top customers and best-performing countries
- Track product demand by coffee type and size
- Monitor customer loyalty behavior
- Provide interactive business insights using a dashboard

## Dataset Structure
The project used multiple related datasets stored in separate Excel sheets:

- **Orders Sheet** — transaction data
- **Customers Sheet** — customer information
- **Products Sheet** — product details and pricing

These datasets were linked to prepare a structured dataset for analysis.

## Data Preparation & Data Enrichment
The dataset required restructuring before analysis. Related data from different sheets were linked to the main Orders dataset using lookup functions.
Instead of merging tables, **column-level data retrieval** was performed to enrich the Orders table.

### Product Data Integration
Product information was retrieved from the Product sheet into the Orders sheet.

- Used **INDEX + MATCH** to retrieve product attributes
- Pulled **Size** into Orders table
- Pulled **Unit Price** into Orders table
- Linked records using product identifiers

This ensured each order had complete product details.

### Customer Data Integration
Customer information was retrieved from the Customer sheet into the Orders sheet.

- Used **INDEX + MATCH** to retrieve Customer Name
- Used **XLOOKUP** to retrieve Loyalty Card status
- Linked customer records to transaction data

This created a structured dataset for customer-level analysis.

### Data Transformation Steps

- Verified data consistency after lookups
- Structured dataset for pivot table analysis
- Standardized column formats
- Ensured accurate relationships between datasets

## Data Analysis Workflow

The project followed a structured data analysis process:

1. Data Understanding — explored dataset structure
2. Data Preparation — retrieved related data using lookup functions
3. Data Transformation — structured dataset for analysis
4. Data Aggregation — used pivot tables to summarize sales data
5. Dashboard Development — built interactive visualizations
6. Insight Generation — identified trends and business patterns

## Dashboard Development
An interactive Excel dashboard was created to visualize key business metrics.

### Dashboard Components
- Total Sales KPI Card
- Sales Trend Over Time
- Top 5 Customers
- Sales by Country
- Coffee Type Filters
- Loyalty Card Filters
- Product Size Filters
- Date Range Slicer

The dashboard updates dynamically based on filter selections.


## KPI Card Development (Total Sales)

A dynamic KPI card was created to display total sales.

### Process:

1. Created a pivot table to aggregate total sales.
2. Used the **GETPIVOTDATA** function to retrieve the total sales value.
3. Stored the KPI value in a worksheet cell.
4. Inserted a shape (card design) in the dashboard.
5. Linked the shape text to the KPI cell using a cell reference.
6. Applied formatting and styling to create a dashboard KPI card.

This approach ensures the KPI updates automatically when filters or slicers change.


##  Tools & Techniques Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- GETPIVOTDATA
- XLOOKUP
- INDEX + MATCH
- Dashboard Design
- Data Visualization
- Data Preparation

---

## Major Generated Insights

- Identified top-performing customers
- Analyzed country-level sales performance
- Tracked sales trends over time
- Evaluated product demand by size and type
- Analyzed customer loyalty impact on sales

## Challenges & Solutions

- Linked multiple datasets using lookup functions
- Built dynamic KPI cards from pivot data
- Ensured dashboard updates automatically
- Designed interactive filters for user-driven analysis

##  Skills Demonstrated

- Data Cleaning & Preparation
- Relational Data Linking
- Excel Lookup Functions
- Data Aggregation
- Dashboard Development
- Business Intelligence Reporting
- Analytical Thinking
- KPI Design

## Dashboard Preview

(Add dashboard screenshot here)

Example:

![Dashboard](dashboard.png)

---

## Author

**Clara (DATASEER) Igwe**

- Data Analyst passionate about turning data into actionable insights
- Skilled in Excel, SQL, Power BI, Python, and Machine Learning
- Interested in financial analytics and predictive modeling


## If you found this project helpful, please give it a star!
