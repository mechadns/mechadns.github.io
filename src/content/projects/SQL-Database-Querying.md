---
title: Layoffs Data Cleaning SQL Project
description: This project is focused on cleaning and preparing layoffs data using SQL. The goal is to safely work with raw data by using a staging environment and eliminating duplicate entries before any analysis is performed.
publishDate: 2024-05-14
tags:
  - SQL
seo:
  image:
    src: /portfolio-3.jpg
    alt: SQL Database Query Project
isFeatured: true
---

<p style="text-align: center;">
The GitHub repository for this project can be viewed <a href="https://github.com/mechadns/SQL-Project" target="_blank">here</a>.
</p>


This project is focused on cleaning and preparing layoffs data using SQL. The goal is to safely work with raw data by using a staging environment and eliminating duplicate entries before any analysis is performed.

## 📁 Project Structure
- **layoffs**: The original/raw data table.
- **layoffs_staging**: A staging table created to prevent any modifications to the raw data during the cleaning process.

## 📌 Notes
- The script uses `ROW_NUMBER()` to handle duplicates effectively.
- Staging ensures that the original data remains untouched.
- Manual inspection steps are included for transparency.

## ✅ Next Steps
- Further clean columns (e.g., standardize date formats, handle null values).
- Add indexing for performance.
- Use the cleaned data for analysis or visualization.

---