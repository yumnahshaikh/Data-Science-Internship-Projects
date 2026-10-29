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
├── Week1_Data_Cleaning_Yumnah.ipynb
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



*This project demonstrates foundational data preparation skills that support reliable exploratory data analysis and future data science workflows.*


---



# Week 2 — Exploratory Data Analysis (EDA)

## Project Overview

This project was completed as part of the **Data Science Internship at NextGenLearners**. It focuses on Exploratory Data Analysis (EDA) using Python, Pandas, Matplotlib, and Seaborn to explore applicant data, identify patterns, and extract meaningful insights through data analysis and visualization.

Exploratory Data Analysis is an important stage of the data science workflow that helps understand dataset characteristics, examine distributions, identify trends, and investigate relationships between variables before further analysis.

The objective of this project is to analyze the applicant dataset from different perspectives, understand application patterns, and communicate findings through meaningful visualizations.

## Project Objectives

- **Dataset Exploration:** Examine the dataset structure, dimensions, columns, and data types.
- **Domain Analysis:** Analyze the distribution of applications across different domains.
- **Monthly Trend Analysis:** Examine application trends across different months.
- **Application Status Analysis:** Investigate the distribution of selected, rejected, and under-review applications.
- **University Analysis:** Identify universities contributing the highest number of applicants.
- **Weekday Analysis:** Explore application patterns across different days of the week.
- **Data Visualization:** Create charts to present distributions, comparisons, and trends clearly.
- **Insight Extraction:** Summarize meaningful findings from the exploratory analysis.

## Dataset Description

The dataset contains applicant information associated with internship applications. The analysis examines application domains, dates, universities, and application statuses to understand the distribution and patterns of applicant activity.

The following aspects are explored in the notebook:

| **Analysis Area** | **Description** |
| ----------------- | --------------- |
| Domain Distribution | Number of applications across different domains |
| Monthly Trends | Application counts by month |
| Application Status | Distribution of selected, rejected, and under-review applications |
| University Analysis | Applicant counts across universities |
| Weekday Analysis | Application counts by day of the week |

## Methodology

The project follows a structured exploratory analysis workflow:

1. **Initial Exploration:** Inspected the dataset using Pandas to understand its structure and contents.
2. **Domain Analysis:** Examined application counts across different domains.
3. **Temporal Analysis:** Investigated monthly application trends and weekday-level patterns.
4. **Status Analysis:** Analyzed application outcomes and the distribution of applicant statuses.
5. **University Analysis:** Compared applicant counts across universities.
6. **Data Visualization:** Used Matplotlib and Seaborn to represent findings through charts.
7. **Insight Interpretation:** Interpreted the observed patterns and summarized the key findings.

## Tools and Technologies

- **Python** — programming language used for data analysis.
- **Pandas** — used for data exploration, grouping, aggregation, and analysis.
- **Matplotlib** — used to create data visualizations.
- **Seaborn** — used to create statistical charts and explore distributions.
- **Jupyter Notebook** — used to execute code and document the analysis.

## Key Findings

The exploratory analysis produced the following observations:

- **Domain Analysis:** Machine Learning recorded the highest number of applications, with 105 applicants.
- **Monthly Trends:** June 2026 recorded the highest monthly application count, with 89 applications.
- **Application Status:** Out of 485 applicants, 144 were selected, 166 were rejected, and 175 remained under review.
- **University Analysis:** UET Lahore contributed the highest number of applicants, with 56.
- **Weekday Analysis:** Saturday recorded the highest number of applications, with 79.

## Repository Structure

```text
Week2-EDA/
│
├── Week2_EDA_Yumnah(4).ipynb
└── README.md
```

## Key Learning Outcomes

Through this project, I developed practical experience in:

- Exploring datasets using Pandas.
- Grouping and aggregating data to answer analytical questions.
- Analyzing categorical and time-based application patterns.
- Creating clear visualizations using Matplotlib and Seaborn.
- Interpreting data distributions and identifying trends.
- Communicating analytical findings in a structured format.


*This project demonstrates foundational exploratory data analysis and visualization skills that support data-driven decision-making and further data science workflows.*
