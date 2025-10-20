# ETL Data Transformation Project (Excel + Power Query)

> ETL pipeline project using Excel Power Query to clean, transform and combine multiple CSV files into a unified analytical dataset.

---

## 🎯 Project Objective
The goal of this project is to build a simple but practical **ETL (Extract, Transform, Load)** pipeline using **Microsoft Excel Power Query**.  
Raw CSV files were transformed into a **clean and structured dataset** ready for analysis.

---

## 📂 Dataset
| File Name | Description |
|------------|-------------|
| health.csv | Health-related category information |
| film.csv | Film metadata |
| category.csv | Category descriptions |
| film_category.csv | Relationship between films and categories |

**Data Type:** Raw CSV files  
**Source:** Training dataset  
**Final Output:** Clean Excel tables

---

## 🔧 Tools and Technologies
| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data processing environment |
| Power Query | Data cleaning & transformation |
| CSV files | Raw data input |
| Excel Tables | Final data structure |

---

## ETL Process

### Extract
- Imported multiple **CSV files** into Excel Power Query.

### Transform
Performed data preparation steps:
- Converted column types (Text → Number, Date formats)
- Removed duplicates and empty rows
- Removed unnecessary columns
- Cleaned whitespace and special characters
- Normalized column names
- **Merged tables using Power Query (Join/Merge)**

### Load
- Loaded clean data back into Excel as organized tables for future use.

---

## 📊 Example Data Flow

# etl-data-transformation
CSV data cleaning and transformation process using Excel
