# Data Cleaning & Preparation [E-Commerce Orders]

**Internship Project | Decode Labs – Data Analytics**  
**Intern:** Oludipe Boluwatife  
**Task:** Task 1 – Data Cleaning and Preparation

---

## Project Overview

This repository contains the cleaned version of a synthetic e-commerce orders dataset. The work was completed as part of my data analytics internship at Decode Labs. The objective was to transform raw order data into an analysis-ready format by handling missing values, standardising data types, and verifying data integrity.

---

## Dataset Summary

- **Original Rows:** 1,201  
- **Final Rows:** 1,201  
- **Columns:** 14  
- **Products:** Laptop, Phone, Monitor, Tablet, Printer, Chair, Desk  

---

## Cleaning Steps

1. **Removed Duplicates**  
   - Method: Data → Remove Duplicates  
   - Result: No duplicate rows found (1,201 rows retained)

2. **Filled Missing Values**  
   - Column: CouponCode  
   - Action: Replaced 309 blank cells with `Nil`  
   - Reason: Made missing coupon codes explicit and consistent for analysis

3. **Converted Data Types**  
   - Columns: UnitPrice, TotalPrice  
   - Action: Changed from General to Currency format  
   - Reason: Enabled correct calculations and consistent monetary formatting

---

## Tools Used

- Microsoft Excel

---

## Author

**Oludipe Boluwatife**  
Data Analytics Intern – Decode Labs
