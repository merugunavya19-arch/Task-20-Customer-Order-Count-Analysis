# Task 20 – Customer Order Count

## Project Overview

This project analyzes the **Sample Superstore dataset** to count the number of orders placed by each customer and identify frequent buyers. The analysis uses **Microsoft Excel and SQL** to summarize customer order activity, compare purchasing frequency, and identify customers who place orders more often.

## Objective

* Count the number of orders placed by each customer.
* Group records by Customer ID and Customer Name.
* Identify frequent buyers based on order count.
* Rank customers by the number of orders.
* Identify the top customers by order frequency.
* Create a customer order summary table and visualization.

## Dataset

**Dataset:** Sample - Superstore.xlsx

* Rows: 9,994
* Columns: 21
* Sheet: `RawData`
* Order ID Column: `B`
* Customer ID Column: `F`
* Customer Name Column: `G`

## Methodology

1. Loaded the Sample Superstore dataset.
2. Selected the **Order ID**, **Customer ID**, and **Customer Name** columns.
3. Created a PivotTable to summarize customer order activity.
4. Grouped the records by Customer ID and Customer Name.
5. Counted the unique Order IDs for each customer to avoid counting the same order multiple times.
6. Sorted customers by order count in descending order.
7. Identified the customers with the highest order frequency.
8. Used SQL with `GROUP BY` and `COUNT(DISTINCT Order ID)` to analyze customer orders.
9. Created a bar chart to compare order counts among frequent buyers.

## Customer Order Count Summary

The summary table contains the following information:

| Customer ID | Customer Name |        Order Count |
| ----------- | ------------- | -----------------: |
| Customer ID | Customer Name | Unique order count |

*Replace the example row above with the actual customer results from your completed Excel PivotTable or SQL query.*

## Key Findings

1. The analysis summarizes the number of unique orders placed by each customer.
2. Customers can be ranked based on their order frequency.
3. Frequent buyers can be identified from the highest order counts.
4. Counting distinct Order IDs avoids counting multiple product rows from the same order as separate orders.
5. Customer order analysis helps businesses understand purchasing behavior and identify customers who order frequently.

## Visualizations

The following visualizations can be created:

* **Customer Order Count – Summary Table**
* **Top Customers by Order Count – Bar Chart**

## Tools Used

* Microsoft Excel
* PivotTable
* Excel Data Model and Distinct Count
* SQL
* `GROUP BY`
* `COUNT(DISTINCT Order ID)`
* Bar Chart
* Sample Superstore Dataset

## Deliverables

* Customer Order Count Excel file
* Customer Order Summary Table
* Top Customers Summary
* SQL Query File, if applicable
* Customer Order Count Bar Chart

## Internship

Completed as part of my **Data Analytics Internship at Veda Technology**.

## Author

**M. Navya Sri**

**Role:** Data Analytics Intern

**Organization:** Veda Technology
