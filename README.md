# 🧼 Comprehensive Data Cleaning Report

**Dataset:** `excel_cleaning_template_expanded.xlsx`

## 📊 Data Overview
- **Total Rows:** 100
- **Total Columns:** 29
- **Column Names:**
  - Order ID
  - Customer Name
  - Email
  - Phone
  - Address
  - Console Model
  - Product Category
  - Quantity
  - Unit Price
  - Discount
  - Tax
  - Payment Method
  - Region
  - Shipping Status
  - Order Date
  - Delivery Date
  - Feedback Score
  - Retailer
  - Notes
  - Cleaned Name Formula
  - Cleaned Email Formula
  - Cleaned Console Formula
  - Cleaned Quantity Formula
  - Cleaned Unit Price Formula
  - Total Amount Formula
  - Standardized Region Formula
  - Standardized Payment Formula
  - Standardized Shipping Formula
  - Feedback Numeric Formula

## ❗ Issues Identified
- Missing values detected in several columns.
- Potential inconsistent formatting or data types.
- Some columns may require standardization or type conversion.

### 🔍 Missing Values Summary

| Column | Missing Values |
|--------|----------------|
| Product Category | 19 |
| Quantity | 16 |
| Unit Price | 7 |
| Discount | 18 |
| Tax | 17 |
| Payment Method | 17 |
| Region | 20 |
| Shipping Status | 16 |
| Delivery Date | 36 |
| Feedback Score | 23 |
| Notes | 36 |
| Standardized Region Formula | 20 |
| Standardized Payment Formula | 17 |
| Standardized Shipping Formula | 16 |

### 🧪 Data Types

| Column | Data Type |
|--------|-----------|
| Order ID | object |
| Customer Name | object |
| Email | object |
| Phone | object |
| Address | object |
| Console Model | object |
| Product Category | object |
| Quantity | object |
| Unit Price | object |
| Discount | object |
| Tax | object |
| Payment Method | object |
| Region | object |
| Shipping Status | object |
| Order Date | datetime64[ns] |
| Delivery Date | datetime64[ns] |
| Feedback Score | object |
| Retailer | object |
| Notes | object |
| Cleaned Name Formula | object |
| Cleaned Email Formula | object |
| Cleaned Console Formula | object |
| Cleaned Quantity Formula | int64 |
| Cleaned Unit Price Formula | float64 |
| Total Amount Formula | int64 |
| Standardized Region Formula | object |
| Standardized Payment Formula | object |
| Standardized Shipping Formula | object |
| Feedback Numeric Formula | int64 |

## 🛠️ Cleaning Strategies Applied
- **Missing Values:**
  - Numeric columns: filled with mean or median.
  - Categorical columns: filled with 'Unknown' or mode.
  - Date columns: filled with placeholder or left as-is.
- **Data Type Conversion:**
  - Converted columns to appropriate types (e.g., dates, integers).
- **Standardization:**
  - Trimmed whitespace, standardized text casing, and removed duplicates if any.

## ✅ Final Output
- Cleaned dataset is ready for analysis.
- All missing values have been addressed.
- Data types are consistent and standardized.

## 📁 Files
- `excel_cleaning_template_expanded.xlsx` – Original dataset.
- `cleaned_data.xlsx` – Cleaned version of the dataset.
- `README.md` – This documentation file.

