# Sales Comparison Dashboard – Tableau Project

## Project Description

The director of a leading organisation wants to compare sales performance between two regions. Regional operators were instructed to record their sales, and upper management requires a visual dashboard to compare key metrics between the two regions and suggest areas for improvement.

This project uses Tableau to create an interactive dashboard that displays key sales KPIs for both regions.

---

## Dataset

- **Dataset Used**: Sample Superstore (available from Tableau)
- Location: `/dataset/Sample Superstore.xls`

---

## Steps Performed

1. Selected the **Sample Superstore** dataset
2. Grouped data by **Customer Data**, **Product Data** and **Order Data** using a folder in the data source
3. Created a hierarchy named **Location** using the `Country` field
4. Created two **parameters**:
   - `Primary Region`
   - `Secondary Region`

5. Built **calculated fields** to represent selected regions
6. Created a calculated field: **First Order Date**
7. Designed a dashboard and aligned sheets to compare the following for both regions:
   - First Order Date
   - Total Sales
   - Average Sales per Order
   - Number of Customers
   - Number of Orders
   - Number of Products in Sale

---

## Sample Output

The dashboard includes:
- **Line graphs** for sales trends over time
- **Bar graphs** to compare totals for selected metrics by region

---

## Files Included

- Tableau Workbook: `Sales_Comparison_Dashboard.twbx`
- Dataset: `Sample Superstore.xls`
- Screenshot: `dashboard-view.png` (optional)s

---

## How to Use

1. Download the `.twbx` file and open it using Tableau Desktop
2. Load the dataset if needed
3. Use the parameters to compare any two regions interactively

---
Link to Tableau Public Dashboard: https://public.tableau.com/app/profile/viijeta.r/viz/Project1_17391893929580/Dashboard?publish=yes

## Author

**Vijeta Singh Rajput**  
https://www.linkedin.com/in/viijetar/
