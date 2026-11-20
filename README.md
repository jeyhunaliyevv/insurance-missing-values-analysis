# Insurance Data Quality & Missing Values Analysis

### Python | Pandas | NumPy | Matplotlib | Seaborn | EDA

## Project Overview

This project demonstrates an end-to-end **data quality assessment and missing value analysis** workflow using a synthetic insurance dataset.

The objective is to identify incomplete records, investigate missing data patterns, and evaluate appropriate data cleaning strategies to improve dataset reliability for downstream analytics and machine learning applications.

The dataset is **fully synthetic and contains no confidential customer or business information**.

## Business Problem

Insurance datasets often contain incomplete information related to policy details, premiums, customer records, and coverage dates.

Missing or inconsistent values can negatively affect reporting accuracy, business insights, and predictive model performance.

This project focuses on detecting data completeness issues and supporting informed data preprocessing decisions before further analysis or modeling.

## Key Analysis & Methodology

- **Data Quality Assessment:** Evaluate dataset completeness and identify columns with missing information.
- **Missing Value Profiling:** Calculate missing value counts and percentages for each feature.
- **Exploratory Data Analysis (EDA):** Examine missingness patterns and data distribution.
- **Missing Data Visualization:** Generate heatmaps to identify incomplete records and potential missingness patterns.
- **Critical Field Validation:** Investigate records with missing policy premiums, dates, or other important attributes.
- **Data Cleaning Strategy:** Assess appropriate approaches, including row removal, statistical imputation, and treating missing values as a separate category.

## Tools & Technologies

- **Python** – Data analysis and processing
- **Pandas & NumPy** – Data manipulation and missing value assessment
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis and documentation

## Analysis Outputs

The notebook includes:

- Column-level missing value summary (count and percentage)
- Visual representation of missing data patterns
- Identification of records with missing critical fields
- Practical considerations for selecting data cleaning strategies

These outputs support more reliable data preparation and help identify potential data quality risks.

## Repository Structure

```text
insurance-missing-values-analysis/
├── .gitignore
├── LICENSE
├── README.md
├── insurance_missing_values_analysis.ipynb
├── insurance_sample.csv
└── requirements.txt
```

## How to Run

**1. Clone the repository**

```bash
git clone https://github.com/jeyhunaliyevv/insurance-missing-values-analysis.git
```

**2. Navigate to the project directory**

```bash
cd insurance-missing-values-analysis
```

**3. Install the required dependencies**

```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook insurance_missing_values_analysis.ipynb
```

## Key Takeaways

This project highlights the importance of systematic data quality checks before statistical analysis or machine learning development.

It demonstrates practical skills in:

- Data quality assessment and validation
- Exploratory data analysis (EDA)
- Missing data detection and visualization
- Data preprocessing and cleaning strategy evaluation
- Preparing structured datasets for downstream analytics

## Data Privacy

All records used in this project are **synthetically generated for educational and portfolio purposes**.

No real insurance company data, personal customer information, or confidential business records are included.
