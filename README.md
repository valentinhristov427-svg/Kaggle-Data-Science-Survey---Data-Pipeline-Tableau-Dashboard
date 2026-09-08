# Kaggle Data Science Survey: Data Pipeline & Tableau Dashboard

## Project Overview
This project analyzes a 23,997-row Kaggle survey dataset to uncover key industry trends within the data science and machine learning community. The project features an end-to-end data pipeline that cleans and normalizes the raw survey data into a relational schema, followed by an interactive Tableau dashboard designed to explore trends in programming languages, machine learning frameworks, and preferred learning platforms.

## Key Features
*   **Data Pipeline & Cleaning:** Processed a 23,997-row dataset using Python to handle missing values, normalize survey responses, and aggregate critical metrics including job titles, salary bands, and education levels.
*   **Relational Schema Design:** Restructured flat survey data into a robust relational schema for optimized querying and dashboard performance.
*   **Interactive Tableau Dashboard:** Developed a comprehensive dashboard utilizing calculated fields and parameters to allow dynamic user exploration of the data.
*   **Trend Analysis:** Uncovered actionable insights regarding the adoption rates of specific programming languages, machine learning frameworks, and educational platforms across different salary bands and job titles.

## Repository Structure
```text
├── data/
│   ├── original_data/            # Raw Kaggle survey dataset
│   └── cleaned_data/             # Processed and normalized relational tables
├── notebooks/
│   └── data_cleaning_notebook.ipynb  # Python script for cleaning and schema creation
├── dashboard/
│   ├── project2_dashboard.twb    # Interactive Tableau workbook
│   └── Dashboard Snapshot.png    # Preview image of the final dashboard
├── docs/
│   └── documentation.docx        # Detailed project documentation and methodology
└── README.md
