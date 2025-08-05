# task-1-data-cleaning-and-preprocessing
Data Analyst Internship Task 1: Data Cleaning and Preprocessing using Python (Pandas) – Includes raw dataset, cleaned output, and code with a summary of changes.
# 🧹 Task 1: Data Cleaning and Preprocessing

This repository contains my submission for **Task 1** of the Data Analyst Internship – focused on data cleaning and preprocessing using Python (Pandas).

---

## 📌 Objective

The main goal of this task is to clean and preprocess a raw dataset by addressing the following issues:

- Missing values
- Duplicate rows
- Inconsistent formatting (dates, text)
- Irregular column naming
- Incorrect data types

---

## 📂 Dataset

> **Dataset Used:** Netflix Movies and TV Shows Dataset  
> (You can replace this with your actual dataset name if different)

- 📥 **Raw Dataset:** `dataset/raw_data.csv`
- 🧼 **Cleaned Dataset:** `dataset/cleaned_data.csv`

---

## 🛠 Tools & Technologies Used

- Python 🐍
- Pandas (Data Manipulation)
- Jupyter Notebook / Google Colab
- Excel (optional for initial exploration)

---

## 🔍 Summary of Cleaning Steps

1. **Loaded the raw dataset** using `pandas.read_csv()`.
2. **Identified and handled missing values** using `.isnull()`, `.fillna()` or `.dropna()`.
3. **Removed duplicate entries** with `.drop_duplicates()`.
4. **Standardized text formats** – e.g., title casing for categories, trimming whitespaces.
5. **Formatted date columns** into a consistent `datetime` format.
6. **Renamed columns** to lowercase and removed spaces for uniformity.
7. **Converted data types** (e.g., age as int, date as datetime).
8. Saved the cleaned dataset.
