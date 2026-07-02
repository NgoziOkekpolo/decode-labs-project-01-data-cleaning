# E-Commerce Data Cleaning and Preparation Using Microsoft Excel

## Project Overview

This project was completed as part of my Decode Labs Data Analytics Internship.

The objective was to clean and prepare an e-commerce dataset using Microsoft Excel by identifying and resolving common data quality issues before analysis.

---

## Dataset Summary

- **Dataset Type:** E-commerce Orders
- **Records:** 1,200
- **Columns:** 14
- **Tool Used:** Microsoft Excel

---

## Project Objectives

- Review the dataset for quality issues.
- Identify duplicate records.
- Handle missing values.
- Ensure consistent formatting.
- Verify correct data types.
- Prepare the dataset for analysis.

---

## Data Cleaning Process

### 1. Column Header Review
- Reviewed all column headers for consistency.
- No issues were identified.
- No changes were required.

### 2. Duplicate Check
- Checked for duplicate records using Excel.
- No duplicate records were found.

### 3. Data Consistency Review
- Reviewed each column for inconsistent text, formatting, and missing values using filters.
- All columns were consistent except the `CouponCode` column.

### 4. Handling Missing Values
- Identified **309** blank values in the `CouponCode` column.
- Replaced blank values with **NO COUPON** using Find & Replace.

**Reason:**
Blank values indicated that no promotional coupon had been applied rather than representing missing information.

### 5. Data Type Verification

| Column | Data Type |
|---------|-----------|
| OrderID | Text |
| CustomerID | Text |
| OrderDate | Date |
| Product | Text |
| Quantity | Whole Number |
| UnitPrice | Currency |
| ShippingAddress | Text |
| PaymentMethod | Text |
| OrderStatus | Text |
| TrackingNumber | Text |
| ItemsInCart | Whole Number |
| CouponCode | Text |
| ReferralSource | Text |
| TotalPrice | Currency |

---

## Results

- No duplicate records found.
- No completely blank rows found.
- Replaced 309 blank coupon codes with **NO COUPON**.
- Verified data types across all columns.
- Prepared the dataset for analysis.

---

## Skills Demonstrated

- Data Cleaning
- Data Preparation
- Microsoft Excel
- Data Quality Assessment
- Documentation

---

## Author

**Ngozi Okekpolo**

Data Analyst | Data Analytics Instructor | Excel | SQL | Power BI | Python
