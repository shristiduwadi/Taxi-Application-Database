# 🚖 Taxi Application Database Project

This project showcases the design and implementation of a normalized SQL database system for a taxi service, incorporating real-world data simulation, structured queries, and reporting.

## Project Overview

- **Technology Used:** MySQL, Python (Faker library), Power BI
- **Normalization:** All tables follow Third Normal Form (3NF)
- **Tables:** 11 interrelated entities (customers, drivers, vehicles, payments, etc.)
- **ER Diagram:** Structured schema ensuring referential integrity
- **Data Volume:** Over 2000 rows of synthetic data for robust testing

## Key Features

- **Data Generation:** Python scripts using Faker for dummy customer/driver/trip data
- **Data Manipulation:** Includes SQL scripts for `INSERT`, `UPDATE`, and `DELETE` operations
- **Data Retrieval:**
  - Top drivers by revenue and rating
  - Most loyal customers by trip count
  - Monthly trip and payment summaries
- **Views & Performance:** Views created for reusable business insights
- **Business Insight Reports:** Visualized using Power BI (optional: include screenshots in `/images`)

## Files Included

- `Taxi_Application_Report.pdf`: Full documentation of database creation, manipulation, and analysis
- `Taxi_Application.pptx`: Presentation overview of the project
- `create_database.sql`: Script to generate the database and tables
- `README.md`: This file

## Learnings

- Effective use of SQL CTEs and Views
- Data cleaning and preprocessing
- Realistic data simulation using Python
- Business insight extraction for real-time decision-making

---

*Created as part of coursework at the University of Niagara Falls, Canada.*

