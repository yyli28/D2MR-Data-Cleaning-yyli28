# README for Midwest Data Cleaning Assignment

## 📌 Midwest Data Cleaning Assignment

### 📝 Overview

This Quarto document outlines the process of cleaning and transforming the **Midwest dataset**. The primary objective is to standardize, format, and preprocess the data to align it with the clean reference dataset. This process ensures accuracy, consistency, and reproducibility while leveraging R's data manipulation tools.

### 📂 Files in This Repository

-   **`cleaning-level-2-yyli28.qmd`** → The Quarto document for data cleaning.
-   **`messy-midwest.csv`** → The raw dataset.
-   **`midwest.csv`** → The clean reference dataset used for validation.

### ⚙️ Data Cleaning Process

The **Midwest dataset** was cleaned using the following approaches:

#### **🔹 Step 1: Standardizing Column Names**

-   Used `rename()` to correct inconsistencies and remove typos.

#### **🔹 Step 2: Calculating New Variables**

-   Created **percentage-based columns** such as `percwhite` and `percblack`.
-   Used `mutate()` to calculate percentages based on total population.

#### **🔹 Step 3: Converting Data Types**

-   Converted incorrectly stored numeric columns from `character` to `numeric`.

#### **🔹 Step 4: Cleaning String Data**

-   Used functions like `str_replace_all()` to reformat and standardize names.

#### **🔹 Step 5: Sorting and Organizing Data**

-   Used `arrange(PID)` to ensure consistent ordering.
