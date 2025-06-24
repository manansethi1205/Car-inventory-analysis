# Car-inventory-analysis
Project Overview
This project demonstrates data cleaning, transformation, and analysis of a car inventory dataset. The objective was to extract actionable insights from raw vehicle data using Excel functions, PivotTables, and structured reporting.

###Key Deliverables:
Imported and structured raw vehicle data

Created calculated fields for improved analysis

Developed summary reports using PivotTables

Generated key performance metrics

Produced a formatted inventory report

Technical Implementation
1. Data Transformation
Transformed raw text data into structured columns using:

Text extraction: LEFT(), RIGHT(), MID()

Data standardization: UPPER(), LOWER()

Reference lookups: VLOOKUP() and upgraded to XLOOKUP()

2. Data Analysis
PivotTable Reports:

Driver Mileage Summary (Sheet1)

Total miles per driver

Identified high-usage drivers

Vehicle Make Distribution (Sheet2)

Fleet composition by manufacturer

Key Metrics Calculated:

Average vehicle age: =AVERAGE(G2:G53)

Oldest vehicle: =MAX(G2:G53)

Fleet size: =ROWS(A3:A53)

3. Insights Generated
Top 10 High-Mileage Vehicles

Identified using LARGE() with XLOOKUP() pairing

Warranty Coverage Analysis

62% of fleet remains under warranty

Usage Patterns

Toyota vehicles account for 31% of total miles

Skills Demonstrated
Data Management

Structured data transformation

Reference table utilization

Dynamic formula implementation

Analysis

Aggregation using PivotTables

Comparative metrics development

Trend identification

Reporting

Automated dashboard elements

Professional documentation

Clear visualization


