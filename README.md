# Insurance Data Analysis & Preprocessing

## Overview

This project explores an insurance dataset using Python, covering Exploratory Data Analysis (EDA), data cleaning, preprocessing, feature engineering, and statistical feature analysis.

The notebook was developed as part of my practical learning journey in Data Science and Machine Learning while following a tutorial.

## Dataset

The original dataset contains 1,338 records and 7 columns.

| Feature | Description |
|---|---|
| `age` | Age of the individual |
| `sex` | Sex of the individual |
| `bmi` | Body Mass Index |
| `children` | Number of children |
| `smoker` | Smoking status |
| `region` | Residential region |
| `charges` | Medical insurance charges |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Examined dataset dimensions, data types, and structure.
- Generated descriptive statistical summaries.
- Explored numerical feature distributions using visualizations.
- Used box plots to inspect potential outliers.
- Investigated relationships between features and insurance charges.

### 2. Data Cleaning

- Checked for missing values.
- Inspected and removed duplicate records using Pandas.
- Reduced the dataset from 1,338 to 1,337 rows after duplicate removal.

### 3. Data Preprocessing

- Encoded categorical variables into numerical representations.
- Applied one-hot encoding to the region and BMI category features.
- Converted selected features into numerical formats.
- Standardized `age`, `bmi`, and `children` using `StandardScaler`.

### 4. Feature Engineering

- Created BMI categories using `pd.cut()`.
- Grouped BMI values into Underweight, Normal, Overweight, and Obese categories.
- Encoded the resulting BMI categories for further analysis.

### 5. Statistical and Feature Analysis

- Calculated Pearson correlation coefficients between selected features and insurance charges.
- Used chi-square statistical tests to examine categorical features.
- Examined statistical relationships to help assess feature relevance.

## Repository Structure

```text
insurance-data-analysis/
├── insurance.csv
├── insurance_eda.ipynb
└── README.md
```

## Getting Started

### Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter
```

### Run the Notebook
1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Open `insurance_eda.ipynb`.
5. Run the notebook cells sequentially.

## Learning Outcomes
- Understanding the EDA workflow.
- Inspecting missing values and duplicate records.
- Encoding categorical variables.
- Creating features from existing data.
- Applying feature scaling.
- Using correlation and chi-square tests for statistical analysis.


## Author
**Suyash Jaiswal**
B.Tech — Computer Science and Engineering (Data Science)
[GitHub Profile](https://github.com/suyash-jaiswal-7)
