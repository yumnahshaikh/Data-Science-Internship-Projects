# Week 1 — Applicant Dataset Cleaning and Exploratory Data Analysis

## Project Overview

This project was completed as part of the **Data Science Internship at NextGenLearners**. It focuses on the foundational stages of the data science workflow: data inspection, data cleaning, preprocessing, and exploratory analysis using Python and Pandas.

Real-world datasets often contain missing information, duplicate records, inconsistent text formats, and invalid values that can affect the accuracy and reliability of subsequent analysis. This project addresses these common data quality challenges using a structured and reproducible data cleaning process.

The objective is to transform a raw applicant dataset into a more consistent, organized, and analysis-ready dataset while documenting the decisions made throughout the process.

## Project Objectives

- **Data Inspection:** Examine the dataset's structure, dimensions, column names, data types, and initial quality issues.
- **Missing Value Management:** Identify missing information and apply appropriate handling strategies based on the purpose and importance of each field.
- **Duplicate Detection:** Identify duplicate records and repeated applications using email addresses as a key identifier, while accounting for missing email values.
- **Data Standardization:** Normalize text formatting and consolidate inconsistent representations of applicant names, email addresses, domains, universities, and application statuses.
- **Data Type Handling:** Standardize application dates, investigate invalid date entries, and preserve phone numbers as text to maintain leading zeros.
- **Data Validation:** Reassess the dataset after cleaning to verify its structure, consistency, missing values, and duplicate records.
- **Documentation and Export:** Record the cleaning methodology and prepare the cleaned dataset for further analysis.

## Dataset Description

The dataset contains applicant information across seven columns:

| Column | Description |
|---|---|
| Applicant Name | Name of the applicant |
| Email | Applicant's email address |
| Phone | Applicant's contact number |
| Domain Applied | Internship or application domain |
| University | Applicant's university |
| Application Date | Date of application |
| Status | Current application status |

The original dataset contains 500 records. The final record count is determined after applying and validating the cleaning procedures.

## Methodology

The project follows a structured data preparation workflow:

1. **Initial Exploration:** Used Pandas methods to inspect the dataset, understand its structure, and identify data quality issues.
2. **Missing Data Handling:** Applied column-specific strategies, including removing records with missing applicant names and assigning meaningful placeholders to selected missing fields.
3. **Duplicate Management:** Examined exact duplicates and repeated applications, using email-based matching where appropriate.
4. **Text Cleaning and Standardization:** Removed unnecessary whitespace, standardized letter casing, and consolidated inconsistent categorical values.
5. **Date and Phone Processing:** Handled inconsistent date formats, investigated invalid entries, and cleaned phone number formatting.
6. **Final Validation:** Reviewed the cleaned data to evaluate its consistency and suitability for subsequent analysis.
7. **Data Export:** Prepared the cleaned dataset as a CSV file for reuse and further exploration.

## Tools and Technologies

- **Python** — programming language used for data processing.
- **Pandas** — used for data manipulation, cleaning, transformation, and validation.
- **Jupyter Notebook** — used to execute code interactively and document the workflow with explanations.
- **CSV** — used for storing the original and cleaned datasets.

## Repository Structure

```text
Week1-Data-Science/
│
├── Week1_Data_Cleaning_YourName.ipynb
├── applicants_cleaned.csv
└── README.md
```

## Key Learning Outcomes

Through this project, I developed practical experience in:

- Inspecting and understanding real-world-style tabular datasets.
- Identifying missing values, duplicates, and inconsistent data.
- Applying Pandas techniques for data cleaning and transformation.
- Making and documenting data preparation decisions.
- Validating data quality before downstream analysis.
- Building a reproducible, notebook-based data preparation workflow.

## Project Deliverables

- **Jupyter Notebook:** Documents the data inspection, cleaning steps, decisions, and validation process.
- **Cleaned CSV Dataset:** Contains the processed applicant records for further exploration and analysis.

## Internship Information

**Program:** Data Science Internship  
**Organization:** NextGenLearners  
**Project:** Week 1 — Data Cleaning and Exploratory Data Analysis

---

*This project demonstrates foundational data preparation skills that support reliable exploratory data analysis and future data science workflows.*
