# 🚢 Titanic Data Cleaning & Transformation Pipeline

## 📌 Project Overview
This project focuses on the foundational Data Engineering tasks of extracting, cleaning, and transforming raw, unstructured data. Using the famous Titanic dataset, I developed a Python-based pipeline to handle missing values, standardize data formats, and engineer new features, ensuring the dataset is highly structured and ready for downstream analysis.

## 🛠️ Technologies & Tools Used
* **Language:** Python
* **Libraries:** Pandas

## ⚙️ Key Data Processing Steps (ETL)

* **Handling Missing Values:** Imputed missing records systematically to maintain data integrity using `fillna()` and statistical methods like `mode()`.
* **Feature Engineering:** Extracted meaningful information from unstructured text data (e.g., passenger titles) utilizing string manipulation functions like `str.extract()`.
* **Data Standardization:** Corrected data types and formatted temporal/categorical data for consistency using `to_datetime()`.
* **Data Filtering & Structuring:** Applied advanced indexing and conditional filtering utilizing `loc[]` to segment specific data subsets accurately.

## 🚀 Why This Matters
Raw datasets are rarely ready for direct analysis. This project demonstrates the ability to identify data quality issues and apply programmatic solutions to transform messy data into reliable, high-quality data assets—a critical step in any robust Data Engineering workflow.
