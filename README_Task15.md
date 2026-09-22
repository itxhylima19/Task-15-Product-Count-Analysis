# Task 15 – Product Count Analysis

## Dataset
Sample Superstore dataset.

## Objective
Count products by category, identify the category with the largest number of unique products, and practice Excel `COUNTIF` / `COUNTIFS`.

## Approach
- Used `COUNTIF` to count all rows for each category.
- Used `COUNTIFS` to flag the first occurrence of each Category + Product Name combination.
- Used `SUMIFS` to total those unique-product flags by category.
- Used `MAX` with `INDEX/MATCH` to identify the largest category.
- Added a chart for a quick visual comparison.

## Verified Results
- Furniture: 380 unique products
- Office Supplies: 1058 unique products
- Technology: 412 unique products
- Largest category: **Office Supplies**
- Highest unique product count: **1058**

## Interview Questions
**COUNTIF vs COUNTIFS:** COUNTIF applies one condition, while COUNTIFS supports multiple conditions.

**Why count unique products?** The same product may appear in multiple order rows. Counting unique products prevents repeated sales from being treated as different products.
