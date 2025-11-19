# 🐼 Pandas Data Analysis & Manipulation Portfolio

This repository contains Jupyter Notebooks detailing my foundational work with the **Pandas** library for data manipulation and analysis. All exercises were conducted and solved within the **Google Colab** environment.

These notebooks demonstrate essential techniques for data wrangling, cleaning, exploratory data analysis (EDA), and preparing data for visualization.

## 🎯 Key Concepts & Skills Demonstrated

| Focus Area | Demonstrated Skill | Relevant Files |
| :--- | :--- | :--- |
| **DataFrame Creation & Exploration** | Manually creating DataFrames from Python dictionaries, inspecting properties (`.head()`, `.info()`, `.describe()`), and exporting cleaned data to CSV (`.to_csv()`). | `Pandas day 1 notebook.ipynb`, `PandasDataFrames_01 Zeshan.ipynb` |
| **Data Selection & Assignment** | Selecting single and multiple columns, adding new calculated columns (e.g., `total_revenue`), and renaming columns for clarity. | `PandasDataFrames_01 Zeshan.ipynb`, `PandasDataFrames_02 ZeshanAsif.ipynb` |
| **Data Filtering & Logic** | Mastering **Boolean masking** (using `df[]`) to filter rows based on single or multiple conditions using `AND` (`&`) and `OR` (`\|`) operators. | `Pandas day 1 notebook.ipynb`, `PandasDataFrames_02 ZeshanAsif.ipynb` |
| **Data Cleaning & Aggregation** | Identifying and replacing missing (Null) values, detecting outliers, and calculating summary statistics like `mean()`, `median()`, and `sum()`. | `Pandas Practice Notebook.ipynb`, `PandasDataFrames_02 ZeshanAsif.ipynb` |
| **Sorting & Ordering** | Sorting DataFrames by one or more columns using `sort_values()`, including ascending and descending order. | `Pandas day 1 notebook.ipynb`, `PandasDataFrames_02 ZeshanAsif.ipynb` |

---

## 💻 Practice Session Breakdown

### Module 1: DataFrame Basics and Transformation

This module focused on getting data into Pandas and performing initial clean-up and feature engineering. 

[Image of a Pandas DataFrame structure]


| Exercise / Topic | Description & Techniques Used |
| :--- | :--- |
| **Manual DataFrame Creation** | Practiced initializing DataFrames from nested Python dictionaries and lists. |
| **Descriptive Statistics** | Used `.describe()` to quickly generate summaries (count, mean, min, max) for numeric columns. |
| **Feature Engineering** | Created new columns (e.g., `total_revenue`) by performing element-wise arithmetic operations between existing columns (`price * units_sold`). |
| **Data Export** | Demonstrated saving a manipulated DataFrame back to a new file using the `.to_csv()` method. |

### Module 2: Filtering, Masking, and Analysis

This module focused on extracting specific subsets of data needed for targeted analysis.

| Exercise / Topic | Description & Techniques Used |
| :--- | :--- |
| **Conditional Filtering** | Filtered a student dataset to find specific segments (e.g., 'class Six' and 'male' students) to calculate targeted averages. |
| **Boolean Masking with Operators** | Used Boolean Series to filter vehicles based on calculated fuel economy values, employing `&` (AND) for complex, multi-criteria filtering on the `mpg` dataset. |
| **Weighted Averages** | Created a new `fuel_economy` column by calculating a weighted average from city and highway miles-per-gallon data. |
| **Null and Outlier Handling** | Practiced EDA techniques to identify missing data and extreme outliers in a real-world dataset (GDP per Capita). |

---

## 📚 Notebooks

| File Name | Primary Content |
| :--- | :--- |
| [`Pandas day 1 notebook.ipynb`](./Pandas day 1 notebook.ipynb) | Basics: Importing, manual DataFrame creation, simple filtering, and sorting. |
| [`PandasDataFrames_01 Zeshan.ipynb`](./PandasDataFrames_01 Zeshan.ipynb) | DataFrame properties, single column selection, adding/renaming columns, and descriptive stats. |
| [`PandasDataFrames_02 ZeshanAsif.ipynb`](./PandasDataFrames_02 ZeshanAsif.ipynb) | Advanced filtering using Boolean masking, `&`/`\|` operators, multi-column sorting, and calculated fields (weighted average). |
| [`Pandas Practice Notebook.ipynb`](./Pandas Practice Notebook.ipynb) | Full EDA workflow including null value imputation, outlier detection, and summary statistics on the GDP per Capita dataset. |
