# India-General-Election-2024-SQL-Analysis

SQL-based analysis of India General Election 2024 using MSSQL Server. Covers data cleaning, joins, CTEs, window functions, and business insights.

## Project Overview

Analyzed constituency-wise, party-wise, and state-wise election data to understand seat distribution, alliance performance, margin analysis, and voting patterns. 

### File Included

- 'India-General-Election-2024-SQL-Analysis' - The project containing datasets:
  - constituencywise_details
  - constituencywise_results
  - partywise_results
  - statewise_results
  - states

 ### Tools Used

 - MS SQL
 - Microsoft Excel for data 
 - ER Diagram
 - SQL Concepts:
     - JOIN
     - GROUP BY
     - CTE
     - Window Functions
     - RANK
     - CASE
     - UPDATE
     - ALTER TABLE
     - Aggregate Function

### Key Features

- Cleaned and normalized tables: candidates, constituencies, parties, states
- Added Party Alliance column using CASE + UPDATE to categorize NDA, I.N.D.I.A, OTHER  
- Wrote SQL queries using JOIN, GROUP BY, CTE, RANK, ROW_NUMBER
- Analyzed EVM vs Postal vote trends and margin analysis across states
- Created ERD diagram showing table relationships via primary/foreign keys

### How to Run

1. Create Database
2. Import CSV files to MsSQL 
3. Run queries 
4. Check outputs in MsSQL Workbench

### Skills Demonstrated

SQL Query Writing, Data Cleaning, Database Design, Analytical Thinking
