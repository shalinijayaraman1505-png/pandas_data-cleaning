# pandas_data-cleaning
# Customer Data Cleaning and PostgreSQL Integration

## Project Overview
This project focuses on cleaning customer data using Python Pandas and storing the cleaned data in a PostgreSQL database.

The project demonstrates basic data cleaning, database connectivity, data insertion, retrieval, and updating records using Python.

## Technologies Used
- Python
- Pandas
- PostgreSQL
- pgAdmin 4
- Psycopg2
- Jupyter Notebook
- Git and GitHub

## Dataset
- Original dataset: `messy-customers-1000.csv`
- Cleaned dataset: `cleaned_customers.csv`
- Total records: 1,000
- Total columns: 15

## Project Workflow

### 1. Data Cleaning Using Pandas
- Loaded the CSV dataset using Pandas.
- Inspected the dataset.
- Handled missing values.
- Removed duplicate records.
- Processed date columns.
- Created a cleaned CSV file.

### 2. PostgreSQL Database Integration
- Connected Python to PostgreSQL using Psycopg2.
- Created a customers table.
- Inserted 1,000 customer records.
- Verified the inserted records.
- Retrieved records using SELECT.
- Updated customer information using UPDATE.

## SQL Operations Practised
- CREATE TABLE
- INSERT
- SELECT
- UPDATE

## Project Structure

```text
python_de_practice/
│
├── cleaned_customers.csv
├── messy-customers-1000.csv
├── data_cleaning.ipynb
├── practice.ipynb
├── python_de_practice.ipynb
└── README.md
```

## Learning Outcome
Through this project, I practised working with real-world-style messy data, cleaning data using Pandas, connecting Python with PostgreSQL, and performing basic database operations.

## Author
Python and Data Engineering Learner
