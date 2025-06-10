#  Data Cleaning Report for `clean data.xlsx`

## Summary of Missing Values Before Cleaning

| Column             | Missing Values |
|--------------------|----------------|
| Product Category   | 19             |
| Discount           | 18             |
| Tax                | 17             |
| Payment Method     | 17             |
| Region             | 20             |
| Shipping Status    | 16             |
| Delivery Date      | 36             |
| Notes              | 36             |

---

## 🛠Cleaning Strategy Applied

- **Numeric Columns** (e.g., `Discount`, `Tax`) were filled with their **mean** value.
- **Categorical Columns** (e.g., `Region`, `Payment Method`, `Shipping Status`) were filled with **`Unknown`**.
- **Date Columns** (e.g., `Delivery Date`) were left as-is if not applicable or filled with a placeholder where needed.
- **Text Columns** (e.g., `Notes`) were filled with **`No Notes`** or a similar placeholder.

---

##  Final Output

The cleaned dataset is saved as `cleaned_data.xlsx`. All missing values have been addressed using the strategies above, ensuring the dataset is ready for further analysis, visualization, or modeling.

---

##  Files

- `clean data.xlsx` – Original dataset with missing values.
- `cleaned_data.xlsx` – Cleaned dataset with all missing values handled.
- `README_Data_Cleaning.md` – This documentation file.

---



