# 🧹 Hotel Booking Data Cleaning

> **Oasis Infobyte Data Analytics Internship – Level 1 | Task 3**

## 📖 Project Overview

The objective of this project is to clean and preprocess a real-world hotel booking dataset by identifying and resolving common data quality issues. The cleaned dataset is prepared for further analysis and machine learning applications.

---

## 🎯 Objectives

- Perform a data quality assessment
- Handle missing values using appropriate techniques
- Identify and remove duplicate records
- Standardize text formatting
- Detect outliers using the IQR method
- Correct data types
- Export the cleaned dataset

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📂 Dataset

**Dataset Name:** Hotel Booking Demand Dataset

**Original Dataset**
- Rows: **119,390**
- Columns: **32**

The dataset contains hotel reservation information such as booking details, customer information, room types, pricing, cancellations, and reservation status.

---

## 🔍 Data Cleaning Process

### 1. Data Quality Assessment
- Loaded the dataset
- Examined dataset shape
- Checked data types
- Generated descriptive statistics
- Identified missing values
- Counted duplicate records

### 2. Missing Value Handling

| Column | Technique Used |
|----------|----------------|
| children | Median Imputation |
| country | Mode Imputation |
| agent | Replaced with 0 |
| company | Replaced with 0 |

---

### 3. Duplicate Removal

- Detected duplicate rows
- Removed duplicate records

**Duplicate Rows Removed:** **31,994**

---

### 4. Data Standardization

- Removed unnecessary leading and trailing spaces from text columns
- Ensured consistent formatting across categorical features

---

### 5. Outlier Detection

The **Interquartile Range (IQR)** method was used to identify outliers in numerical columns.

The detected outliers were retained because they represent valid hotel booking scenarios such as premium room prices, long booking lead times, and large group reservations.

---

### 6. Data Type Correction

Converted the following column:

| Column | Before | After |
|---------|---------|-------|
| reservation_status_date | object | datetime |

---

### 7. Export

The cleaned dataset was exported as:

```
cleaned_hotel_bookings.csv
```

---

## 📊 Data Cleaning Summary

| Metric | Before Cleaning | After Cleaning |
|---------|----------------:|---------------:|
| Rows | 119390 | 87377 |
| Columns | 32 | 32 |
| Missing Values | 129425 | 0 |
| Duplicate Rows | 31994 | 0 |

---

## 📁 Project Structure

```
Task3_Data_Cleaning/
│
├── Data_Cleaning.ipynb
├── hotel_bookings.csv
├── cleaned_hotel_bookings.csv
├── README.md
└── screenshots/
    ├── 1_dataset_preview.png
    ├── 2_dataset_info.png
    ├── 3_missing_values.png
    ├── 4_duplicate_rows.png
    ├── 5_outlier_detection.png
    └── 6_before_after_summary.png
```

---

## 📸 Project Screenshots

The `screenshots` folder contains images of:

- Dataset Preview
- Dataset Information
- Missing Values Report
- Duplicate Row Detection
- Outlier Detection using IQR
- Before vs After Cleaning Summary

---

## 📈 Results

✔ Successfully handled missing values.

✔ Removed duplicate records.

✔ Standardized categorical data.

✔ Converted date columns into the correct data type.

✔ Detected and documented outliers using the IQR method.

✔ Exported a clean, analysis-ready dataset.

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Missing value imputation
- Duplicate detection and removal
- Data standardization
- Outlier detection using IQR
- Data type conversion
- Working with real-world datasets using Pandas

---

## 🚀 Future Scope

The cleaned dataset can be used for:

- Exploratory Data Analysis (EDA)
- Hotel booking trend analysis
- Customer behavior analysis
- Booking cancellation prediction
- Machine Learning model development

---

## 👩‍💻 Author

**Nikitha Ashok**

B.Sc. Computer Science with Artificial Intelligence & Machine Learning

Data Analytics Intern – Oasis Infobyte

GitHub: https://github.com/Nikitha-aiml