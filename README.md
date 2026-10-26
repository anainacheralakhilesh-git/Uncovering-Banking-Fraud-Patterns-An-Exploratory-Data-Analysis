# Uncovering-Banking-Fraud-Patterns-An-Exploratory-Data-Analysis
Exploratory analysis of 50,000 financial transactions using Python to identify fraud patterns, analyse risk scores, and visualise transaction trends through data cleaning, EDA, and interactive visualisations.

## Project Overview

This project explores transaction data to identify patterns and characteristics associated with fraudulent financial transactions. Using Python in Google Colab, the project covers data cleaning, preprocessing, exploratory data analysis (EDA), and data visualisation.

The objective is to understand how transaction characteristics vary between fraudulent and non-fraudulent transactions and identify patterns that may support further fraud detection analysis.

## Dataset

- **Dataset:** [Fraud Detection Transactions Dataset](https://www.kaggle.com/datasets/samayashar/fraud-detection-transactions-dataset)
- **Source:** Kaggle
- **Original Records:** 50,000
- **Features:** 21 columns
- **Cleaned Records:** 50,000
- **Domain:** Financial transaction analysis

The dataset contains transaction-related information used to explore fraud labels, transaction amounts, account balances, risk scores, failed transaction counts, authentication methods, and other transaction characteristics.

## Objectives

- Clean and preprocess transaction data.
- Handle missing values and check for duplicate records.
- Validate numerical, categorical, binary, and timestamp fields.
- Explore fraudulent and non-fraudulent transaction distributions.
- Analyse relationships between fraud status and numerical variables.
- Compare fraud rates across transaction categories.
- Examine monthly transaction volumes and fraud trends.
- Summarise findings and recommend potential future improvements.

## Tools and Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and programming |
| Google Colab | Notebook environment |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Plotly | Interactive charts |

## Project Workflow

### 1. Data Loading
Loaded the dataset into a Pandas DataFrame in Google Colab and inspected its structure, columns, and data types.

### 2. Data Cleaning and Preprocessing
- Identified and handled missing values.
- Checked for duplicate rows and transaction IDs.
- Validated binary and numerical fields.
- Checked categorical values for inconsistencies.
- Converted timestamps to the appropriate datetime format.
- Performed final data quality checks.

### 3. Exploratory Data Analysis
Analysed transaction distributions, fraud rates, numerical characteristics, category-level patterns, monthly trends, and correlations between numerical variables.

### 4. Data Visualisation
Created visualisations to communicate the findings, including:

- Count plots and histograms
- KDE plots
- Box plots and violin plots
- Bar charts
- Line charts
- Scatter plots
- Correlation heatmaps

### 5. Findings and Recommendations
Interpreted the observed patterns and identified areas for further investigation and future development of fraud detection models.

## Key Findings

- **Fraud distribution:** 16,067 transactions (32.13%) were labelled as fraudulent, while 33,933 (67.87%) were non-fraudulent.
- **Risk score:** The High Risk category had an observed fraud rate of 56.02%, compared with 19.98% for Low Risk and 19.66% for Medium Risk.
- **Failed transaction activity:** The failed transaction count over the previous seven days had a positive correlation of 0.51 with the fraud label.
- **Risk score correlation:** Risk score had a positive correlation of 0.39 with the fraud label.
- **Transaction amounts:** Transaction amounts were right-skewed, with most transactions concentrated at lower values.
- **Category-level analysis:** Fraud rates were relatively similar across locations, transaction types, authentication methods, and card age groups.
- **Monthly trends:** Transaction volumes and fraud rates fluctuated during 2023, without a consistent upward or downward trend in monthly fraud rates.

*Note: These are descriptive findings and observed associations. A predictive machine learning model was not developed or evaluated as part of this project.*

## Limitations

- The analysis is based on one dataset and may not represent fraud patterns across all financial institutions.
- Correlation does not establish causation.
- Some categories contain relatively few records and require cautious interpretation.
- The project focuses on exploratory analysis and visualisation rather than predictive model development.

## Future Scope

Potential extensions include:

- Developing classification models such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
- Evaluating models using precision, recall, F1-score, confusion matrices, and precision-recall curves.
- Exploring additional features and interactions between transaction variables.
- Testing findings on larger and more diverse datasets.
- Developing an interactive dashboard to monitor fraud-related indicators.

## Repository Contents

The repository may include the following project files:

- **Colab Notebook (`.ipynb`):** Data cleaning, analysis, and visualisations.
- **Cleaned Dataset (`.csv`):** Processed data used for analysis, if included.
- **Project Report  (.pdf):** Detailed project report



## How to Run the Project

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Download the original dataset from the [Kaggle dataset page](https://www.kaggle.com/datasets/samayashar/fraud-detection-transactions-dataset).
4. Update the dataset file path in the notebook, if required.
5. Install any missing libraries.
6. Run the notebook cells in order.

Most required libraries are available by default in Google Colab.

## References

- Ashar, S. (n.d.). *Fraud Detection Transactions Dataset*. Kaggle. https://www.kaggle.com/datasets/samayashar/fraud-detection-transactions-dataset
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Plotly Python Documentation](https://plotly.com/python/)

---

**Project Type:** Data Analytics Capstone Project  
**Focus:** Financial Transactions and Fraud Analysis  
**Environment:** Python · Google Colab
