# Excel Inventory Tracking & Analysis

## Project Overview

This project uses Microsoft Excel to organize and analyze inventory data. It explores stock availability, reorder levels, inventory value, suppliers, storage locations, and supplier lead times.

The workbook contains raw data, a cleaned dataset, and analysis worksheets that summarize inventory from different business perspectives.

## Business Questions

- Which products are below their reorder points?
- How is inventory distributed by stock status?
- What is the inventory value by product and category?
- Which storage locations hold the most inventory value?
- How many products are associated with each supplier?
- What is the average supplier lead time?

## Tools & Excel Features

- Microsoft Excel
- Data cleaning and organization
- `XLOOKUP` for looking up product categories
- Conditional logic for stock-status classification
- Pivot tables for summarizing inventory metrics

> The workbook may require a recent version of Excel to calculate `XLOOKUP` formulas correctly.

## Workbook Contents

| Worksheet | Purpose |
|---|---|
| `raw_data` | Original inventory records |
| `cleaned_dataset` | Organized inventory data with additional analysis fields |
| `analysis` | Main inventory analysis worksheet |
| `stock details` | Summary of stock status |
| `inventory value` | Inventory value summarized by category |
| `inv_by_product` | Inventory value summarized by product |
| `location` | Inventory value summarized by storage location |
| `salers analysis` | Product counts by supplier |
| `avg lead time` | Average lead time by supplier |
| `stock level` | Quantity in stock summarized by product |

## Key Findings

Based on the summaries currently in the workbook:

- **500 inventory records** are included in the raw dataset.
- **433 products/records** are classified as having adequate stock.
- **67 products/records** are classified as low stock.
- Low-stock records represent **13.4%** of the 500 records.
- The inventory-value summary compares categories, while separate summaries break value down by product and storage location.
- Supplier analysis includes product counts and average lead-time comparisons.

These figures describe the current workbook summaries; they should be rechecked if the source data or formulas are changed.

## How to Use

1. Download `Inventory-Tracking.xlsx` from this repository.
2. Open it in Microsoft Excel.
3. Review `cleaned_dataset` for the structured inventory records.
4. Explore the summary worksheets to investigate stock status, inventory value, suppliers, lead times, and storage locations.
5. If prompted, allow Excel to recalculate formulas so lookup and stock-status fields display correctly.

## Repository Structure

```text
Excel-Inventory-Tracking-Analysis/
├── Inventory-Tracking.xlsx
├── README.md
└── screenshots/
    ├── inventory_analysis.png
    ├── stock_analysis.png
    └── inventory_value.png
```

Add screenshots only after capturing them from your actual workbook. If you use different filenames, update the names in this section.

## Limitations

- The analysis reflects the data included in this workbook and may not represent a live inventory system.
- Supplier contact details in the dataset should be reviewed before sharing the workbook publicly.
- Formula results can vary depending on Excel version and whether formulas have recalculated.

## Future Improvements

- Add a visual dashboard with KPI cards and slicers.
- Highlight low-stock items and products requiring reorder.
- Add charts for inventory value by category, product, and location.
- Create a refreshable reporting workflow for updated inventory data.

---

**Project type:** Excel Data Analysis  
**Focus:** Inventory tracking, stock monitoring, and inventory-value analysis
