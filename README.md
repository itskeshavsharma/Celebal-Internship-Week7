# 🚀 Delta Lake Incremental Data Processing using PySpark

## 📌 Overview

This project demonstrates **incremental data processing using Delta Lake** in **Apache Spark (PySpark)** on **Databricks**. The implementation shows how to update existing records and insert new records efficiently using the **Delta Lake MERGE** operation.

---

## 🎯 Objective

The objective of this assignment is to:

- Load the Sample Superstore dataset.
- Clean and preprocess the data.
- Store the dataset as a Delta Table.
- Create an incremental dataset containing updated and new records.
- Apply the Delta Lake MERGE operation.
- Validate the final output after merging.
- Ensure data consistency without duplicate records.

---

## 🛠️ Technologies Used

- Apache Spark (PySpark)
- Delta Lake
- Databricks Community Edition
- Python
- CSV Dataset

---

## 📂 Project Structure

```
delta-lake-assignment/
│
├── data/
│   ├── Sample - Superstore.csv
│   └── customer_incremental.csv
│
├── notebooks/
│   └── delta_scd_assignment.ipynb
│
├── screenshots/
│   ├── data_loading/
│   ├── data_cleaning/
│   ├── updates/
│   ├── incremental/
│   ├── merge/
│   └── final_output/
│
├── report/
│   └── Delta_Lake_Assignment_Report.pdf
│
└── README.md
```

---

## 🔄 Workflow

### Step 1
Load the Sample Superstore dataset into a PySpark DataFrame.

### Step 2
Clean the dataset by removing duplicate records and validating the schema.

### Step 3
Save the cleaned dataset as a Delta Table.

### Step 4
Create an incremental dataset containing:
- Updated existing records
- Newly inserted customer records

### Step 5
Save the incremental dataset as a Delta Table.

### Step 6
Perform the Delta Lake **MERGE** operation.

### Step 7
Validate the final dataset to verify successful updates and inserts.

---

## 📸 Screenshots Included

- Dataset Loading
- Data Cleaning
- Data Validation
- Updating Existing Records
- Incremental Dataset Creation
- Delta MERGE Operation
- Final Output Validation

---

## 📊 Expected Result

After executing the MERGE operation:

- ✅ Existing customer records are updated.
- ✅ New customer records are inserted.
- ✅ No duplicate Row_ID values are created.
- ✅ Data integrity is maintained using Delta Lake.

---

## 📚 Dataset

**Sample - Superstore.csv**

---

## 🎓 Internship

**Celebal Summer Internship 2026**

**Domain:** Data Engineering

---

## 👨‍💻 Author

**Keshav Sharma**

B.Tech Computer Science Engineering

Poornima Institute of Engineering & Technology

Jaipur, Rajasthan

---

## ⭐ Key Learning Outcomes

- PySpark Data Processing
- Delta Lake Fundamentals
- Incremental Data Processing
- MERGE Operations
- Delta Tables
- Data Cleaning
- Data Validation
- Data Engineering Workflow

---

## 📄 License

This repository is created for educational purposes as part of the **Celebal Summer Internship 2026**.
