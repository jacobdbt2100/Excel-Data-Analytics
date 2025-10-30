# Excel for Data Analysts — 4-Week Roadmap

## Week 1 — Excel Basics, Data Cleaning & Transformation

- Importing data (CSV, TXT, Excel files) 
- Data types, duplicates, missing values, invalid data, etc.
- **Text functions:** TRIM, CLEAN, LEFT, RIGHT, MID, FIND, LEN, TEXTSPLIT
- **Error handling:** IFERROR, ISBLANK, IFNA
- Combining text columns using CONCATENATE
- Data Validation (drop-down lists)
- Flash Fill for quick transformations
- Introduction to **`Power Query`** for automated data cleaning & transformation

## Week 2 — Functions & Conditional Formatting

- **Math & Stats:** SUM, AVERAGE, MEDIAN, MODE, COUNT, MAX, MIN, STDEV, VAR
- **Logical:** IF, IFS, AND, OR
- **Conditional:** SUMIF, SUMIFS, AVERAGEIF, AVERAGEIFS, COUNTIFS
- **Lookup & Reference:** VLOOKUP, XLOOKUP, INDEX-MATCH
- **Dynamic Array Functions:** FILTER, SORT, UNIQUE, SEQUENCE
- **Conditional Formatting:** Highlight trends and outliers

## Week 3 — Data Exploration

- **Pivot Tables & Charts**: a data summarization tool to aggregate and filter data in a spreadsheet. Key features:
  - `Grouping data`
  - `Filtering & Slicing`
  - `Sorting`
  - `Calculated fields:` for quick calculations—ratios, percentages, averages, sums, differences; directly within the pivot table.
  - `Visualization`
- **Descriptive Statistics** (with formulas & Data Analysis ToolPak)
- **Power Query:** combining multiple tables (merge & append)
- **Power Pivot:** to create relationships between multiple tables for advanced analysis. **`VLOOKUP`** or **`XLOOKUP`** become inefficient with large datasets.
- **DAX (Data Analysis Expressions):** enables more omplex, dynamic calculations across related tables than **`Calculated fields`** can handle.

## Week 4 — Visualization & Dashboard Building

- Chart types and use cases:
  - Column, Bar, Line, Pie, Scatter, Histogram, Combo
- Dynamic charts with Excel Tables or named ranges
- Slicers and Timelines for interactive reports
- Dashboard design principles:
  - Layout consistency
  - Minimal colour palette
  - Clear KPI presentation
- Final **interactive dashboard** project

### MISCELLANEOUS

#### `Append vs Merge in Power Query:`

| **Aspect**       | **Append Queries**                                                                         | **Merge Queries**                                                                                       |
| ---------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| **Purpose**      | Combines **rows** from two or more tables.                                                 | Combines **columns** from two tables based on a matching field.                                         |
| **What it does** | Stacks tables **on top of each other** (like adding more records).                         | Joins tables **side by side** using a common key (like a lookup).                                       |
| **When to use**  | When tables have **the same columns** and you want to add more data (e.g., monthly files). | When you need to **bring related details** from another table (e.g., add customer names to sales data). |
