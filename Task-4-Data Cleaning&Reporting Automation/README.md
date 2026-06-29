# Data Cleaning & Reporting Automation

## 📌 Project Overview

This project automates the process of cleaning raw business data and generating reports using Python. It demonstrates data preprocessing techniques, automation, and reporting workflows commonly used in data analytics.

The project was developed using **Google Colab** and **Python** with the Sample Superstore dataset.

---

## 🎯 Objectives

* Automate data cleaning tasks
* Handle missing values
* Remove duplicate records
* Standardize inconsistent data
* Generate automated reports
* Create visual summaries
* Export cleaned datasets and reports

---

## 📂 Project Structure

```
Data-Cleaning-Automation/

│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── reports/
│   ├── summary_report.xlsx
│   ├── cleaning_report.txt
│   └── sales_chart.png
│
├── notebooks/
│   └── project.ipynb
│
├── scripts/
│   └── automation.py
│
├── requirements.txt
│
└── README.md
```

---

## 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* OpenPyXL
* XlsxWriter

---

## 📊 Dataset

**Dataset Name:** Sample Superstore

The dataset contains information such as:

* Order ID
* Customer Name
* Segment
* Country
* City
* State
* Region
* Category
* Sub-Category
* Sales
* Quantity
* Discount
* Profit
* Order Date
* Ship Date

---

## 🔄 Data Cleaning Process

The automation script performs the following operations:

* Import raw dataset
* Detect missing values
* Fill missing numerical values using median
* Fill missing categorical values using mode
* Remove duplicate records
* Remove extra spaces
* Standardize text formatting
* Convert date columns to DateTime format
* Save cleaned dataset

---

## 📈 Reports Generated

The project automatically generates:

### 1. Cleaned Dataset

* cleaned_data.csv

### 2. Excel Summary Report

Contains:

* Cleaned Dataset
* Summary Statistics

### 3. Cleaning Report

Includes:

* Original rows
* Final rows
* Duplicate rows removed
* Missing values handled
* List of dataset columns

### 4. Sales Chart

Bar chart showing:

* Total Sales by Category

---

## ▶️ How to Run

### Step 1

Open Google Colab.

### Step 2

Upload the dataset:

```
Sample - Superstore.csv
```

### Step 3

Install dependencies:

```bash
pip install pandas numpy matplotlib openpyxl xlsxwriter
```

### Step 4

Run all notebook cells.

### Step 5

The following outputs will be generated automatically:

```
data/raw_data.csv

data/cleaned_data.csv

reports/summary_report.xlsx

reports/cleaning_report.txt

reports/sales_chart.png
```

---

## 📌 Project Features

* Automated Data Cleaning
* Missing Value Handling
* Duplicate Removal
* Data Standardization
* Automated Report Generation
* Excel Report Export
* Data Visualization
* Reusable Python Workflow

---

## 📁 Output Files

| File                | Description             |
| ------------------- | ----------------------- |
| raw_data.csv        | Original dataset        |
| cleaned_data.csv    | Cleaned dataset         |
| summary_report.xlsx | Excel summary report    |
| cleaning_report.txt | Cleaning process report |
| sales_chart.png     | Sales visualization     |

---

## 🚀 Future Enhancements

* Interactive Power BI Dashboard
* Automated Email Report Delivery
* Scheduled Data Cleaning
* Additional Data Quality Checks
* Interactive Dashboard using Streamlit

---

## 📚 Learning Outcomes

This project demonstrates:

* Data preprocessing
* Data cleaning techniques
* Python automation
* Report generation
* Excel automation
* Data visualization
* Business data analysis

---

