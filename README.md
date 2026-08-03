# Assignment 1: Data Exploration

An Excel-based data exploration exercise covering fundamental spreadsheet functions — aggregation, min/max analysis, and conditional calculations — applied to a retail product dataset.

## 📊 Dataset

The workbook contains a 34-row product dataset with the following columns:

| Column | Description |
|---|---|
| Product ID | Encoded ID combining day, month abbreviation, and country code (e.g. `28-JAN-US`) |
| Product Name | Name of the product |
| Brand Name | Manufacturer/brand |
| Price ($) | Unit price in USD |
| Quantity | Units in stock/sold |
| Category | Product category (Electronics, Fashion, Kitchen, Outdoor, Accessories) |
| Price range | Classified as "High Price" or "Standard Price" |
| Day / Country Code / Month | Components parsed out of the Product ID |

## 🧮 Analysis Performed

The workbook answers a series of guided questions using built-in Excel functions:

**1) Sum, Count, Average**
- Total price of all products — `SUM`
- Count of products in the dataset — `COUNTA`
- Average product price — `AVERAGE`

**2) Min and Max**
- Minimum product price — `MIN`
- Maximum product price — `MAX`

**4) SUMIF and COUNTIF**
- Total price of products in the "Electronics" category — `SUMIF`
- Count of products priced under $100 — `COUNTIF`

> Note: Section "3" is not present in the original assignment numbering (jumps from 2 to 4).

## 🛠️ Tools & Functions Used

`SUM` · `COUNTA` · `AVERAGE` · `MIN` · `MAX` · `SUMIF` · `COUNTIF`

## 📁 Files

| File | Description |
|---|---|
| `Assignment_1__Data_Exploration.xlsx` | Source dataset with answers computed via live formulas |

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Assignment_1__Data_Exploration.xlsx` in Excel, LibreOffice Calc, or Google Sheets.
3. Click on any cell in the "Answer" column to view the formula used to derive it.
4. Modify the source data to see the formulas recalculate automatically.

## 📚 Purpose

This assignment serves as an introductory exercise in exploratory data analysis using spreadsheet formulas, demonstrating how to summarize, filter, and conditionally aggregate tabular data without writing code.
