# ShopSmart Performance Dashboard --- FY 2025

## Project Overview

This project analyzes ShopSmart's FY 2025 retail data to understand
sales performance, customer segments, product and category performance,
store and regional results, product returns, supplier coverage, and
inventory levels.

The analysis was prepared in Excel using data cleaning, formulas,
monthly reporting fields, PivotTables, summaries, and dashboard
visualizations.

## Business Objectives

-   Measure revenue and order performance.
-   Identify top-performing products, categories, stores, regions, and
    customer segments.
-   Review product return rates and return reasons.
-   Examine inventory levels and highlight potential stock-turnover
    risks.
-   Turn the findings into practical recommendations for marketing,
    customer retention, and inventory planning.

## Datasets

The project documentation describes nine core datasets:

  -----------------------------------------------------------------------
  File                                Description
  ----------------------------------- -----------------------------------
  `Customers.csv`                     Customer profiles, demographics,
                                      location, registration date, and
                                      customer segment.

  `Products.csv`                      Product names, categories,
                                      subcategories, brands, cost prices,
                                      and selling prices.

  `Orders.csv`                        Orders, customer/product/store
                                      references, dates, quantities,
                                      pricing, discounts, shipping,
                                      payment method, sales channel, and
                                      status.

  `Stores.csv`                        Store names, regions, states,
                                      cities, and opening dates.

  `Returns.csv`                       Returned orders, return dates,
                                      reasons, and refund amounts.

  `Employees.csv`                     Employee details, roles, store
                                      assignments, hire dates, and
                                      monthly salaries.

  `Suppliers.csv`                     Supplier details and
                                      contact/location information.

  `Inventory.csv`                     Stock on hand, reorder levels,
                                      product/store references, and last
                                      restock dates.

  `Order_Items.csv`                   Order-line items, product/order
                                      references, quantities, prices,
                                      discounts, and line totals.
  -----------------------------------------------------------------------

> **Important:** The uploaded workbook also contains analysis/helper
> sheets, including `Shopsmart Analysis`, `Pivot table`, and
> `Dashboard`. Export the nine raw source tables as separate CSV files
> if you want the repository to match the dataset list above. Do not
> upload the dashboard or pivot tables as if they were raw datasets.

## Repository Structure

A recommended repository layout is:

``` text
shopsmart-performance-dashboard/
├── data/
│   ├── Customers.csv
│   ├── Products.csv
│   ├── Orders.csv
│   ├── Stores.csv
│   ├── Returns.csv
│   ├── Employees.csv
│   ├── Suppliers.csv
│   ├── Inventory.csv
│   └── Order_Items.csv
├── report/
│   └── Business_Report.pdf
├── Shopsmart_Analysis.xlsx
└── README.md
```

The `data/` CSV files and `report/Business_Report.pdf` are recommended
locations. Create these folders and add the files when uploading to
GitHub.

## Tools Used

-   **Microsoft Excel** --- data cleaning, filtering, formulas, monthly
    reporting fields, PivotTables, summaries, and dashboard visuals.
-   **CSV** --- portable format for the core datasets.
-   **GitHub** --- version control and project presentation.

## Key Findings (as reported in the project)

-   Reported total FY 2025 revenue: **₦7,511,812,249.00**.
-   Reported total orders: **50,000**.
-   Reported average order value: **₦151,505.00**.
-   Reported overall return rate: **1.63%**.
-   Reported inventory value: **₦6,169,984,915.00**.
-   Home Item 400 was identified as the highest-revenue product.
-   ShopSmart Lagos was identified as the best-performing store.
-   Groceries led in revenue and quantity sold.
-   December had the highest combined monthly revenue.
-   Gold membership customers were reported as the highest spenders.
-   Home and Beauty were reported to have return rates of 1.71% and
    1.70%, respectively.
-   The South region was identified as the best-performing region.
-   ShopSmart Kaduna was reported to have the lowest inventory, at 2,570
    items.

## Recommendations

1.  Improve inventory turnover using demand forecasting, stock-ageing
    analysis, and targeted promotions.
2.  Prioritize high-performing categories and regions after validating
    the underlying figures.
3.  Develop membership-tier retention strategies to encourage repeat
    purchases and improve customer lifetime value.
4.  Review return reasons for Home and Beauty products and address
    recurring causes.
5.  Combine store demand, supplier information, stock levels, and
    reorder thresholds to reduce stockouts and excess inventory.

## Data Quality Notes

Please verify these points against the workbook before presenting the
results externally:

-   The project notes refer to both **nine datasets** and **"89
    different tables."** The repository documentation uses the nine
    named CSV datasets.
-   Total revenue divided by 50,000 orders is approximately
    **₦150,236.24**, which differs from the reported average order value
    of ₦151,505.00. Confirm the definitions and calculation basis.
-   Confirm whether `Orders.csv` is at order level or product-line
    level, because `Order_Items.csv` also stores product-level order
    lines.
-   Define the inventory value consistently (for example, cost value or
    selling value).
-   Confirm the exact geographic description associated with ShopSmart
    Kaduna.

## How to Use This Repository

1.  Download or clone the repository.
2.  Open `Shopsmart_Analysis.xlsx` in Microsoft Excel to review the
    analysis and dashboard.
3.  Open the CSV files in Excel, Power BI, Python, SQL, or another
    analytics tool for further analysis.
4.  Read `report/Business_Report.pdf` for the executive summary and
    recommendations.

## Disclaimer

This project is for portfolio and analytical demonstration purposes.
Findings and metrics are based on the supplied project workbook and
report notes and should be validated against the source data before
business decisions are made.
