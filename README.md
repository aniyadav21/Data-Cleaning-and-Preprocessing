# 🧹 Task 1 – Data Cleaning and Preprocessing
## 🎯 Objective
Clean and prepare a raw dataset containing customer information for marketing analysis. The goal was to handle missing values, remove duplicates, standardize formats, and make the dataset ready for further analysis or visualization.

---
## 🛠 Tools Used
- **Microsoft Excel** (100% of cleaning done manually)

---

## ✅ Cleaning Steps Performed in Excel

1. **Removed Missing Values**
   - Used filters to identify missing values in the `Income` column.
   - Filled them using the **median income** value calculated manually.

2. **Checked for and Removed Duplicates**
   - Used Excel’s `Remove Duplicates` tool to ensure unique records.

3. **Standardized Text Columns**
   - Cleaned and standardized values in `Education` and `Marital Status` using formulas:
     - `=PROPER()`, `=TRIM()` to fix inconsistent capitalization and spacing.

4. **Formatted Date Column**
   - Converted `Enrollment Date` to `dd-mm-yyyy` format using:
     - Cell formatting: `Format Cells → Custom → dd-mm-yyyy`

5. **Cleaned and Renamed Column Headers**
   - Renamed headers for readability and consistency. Example changes:
     - `year_birth` → `Year of Birth`
     - `mntwines` → `Wine Purchases ($)`
     - `numwebvisitsmonth` → `Monthly Website Visits`

6. **Formatted Sheet for Presentation**
   - Applied bold formatting to all column headers.
   - Auto-adjusted column widths to match content using double-click on column borders.
   - Applied filters to all column widths to match content using double-click on column borders.
   - Applied filters to all columns (`Ctrl + Shift + L`) for easy navigation.

---

## 📁 Files Included
- `cleaned_marketing_campaign.xlsx`: Final cleaned version of the dataset in Excel format.

---

## 📊 Dataset Overview
The dataset contains marketing and demographic data of customers including:
- Age, education, marital status
- Product spending across categories (wine, meat, gold, etc.)
- Marketing campaign acceptance history
- Enrollment date and customer activity

---

## 🔍 Additional Notes
- All changes were done manually using Excel tools and formulas.
- No external scripts, macros, or programming were used.
