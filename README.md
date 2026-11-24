
# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project explores the Titanic passenger dataset to identify patterns, relationships, trends, and anomalies using statistical analysis and visualizations.

## Objective

- Understand the structure and quality of the dataset.
- Handle missing values and standardize text fields.
- Explore passenger characteristics and survival patterns.
- Visualize distributions and relationships between variables.
- Summarize findings with evidence from the analysis.

## Dataset

The cleaned dataset contains **891 rows and 27 columns**.

It includes passenger details such as passenger class, sex, age, family information, ticket and fare information, cabin and embarkation information, and survival status.

## Tools and Libraries

- Python
- Google Collab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning and Preparation

The following data cleaning steps were performed:

- Trimmed leading and trailing spaces.
- Standardized selected categorical values.
- Converted relevant columns to numeric data types.
- Replaced missing cabin values with `Unknown`.
- Filled missing embarkation values using the mode.
- Checked for duplicate rows.
- Checked for remaining missing values.
- Recomputed family size and alone-travelling indicators.

### Missing Cabin Values

The `Cabin` column contained 687 missing values. These values were replaced with `Unknown` to preserve passenger records.

## Project Files

- `Titanic_EDA_Cleaned.csv` - Cleaned dataset used for analysis.
- `Titanic_EDA.ipynb` - Google Collab containing the EDA.
- `README.md` - Project documentation.

## How to Run

1. Download or clone the project.
2. Install Python and Jupyter Notebook.
3. Install the required libraries.
4. Place `Titanic_EDA_Cleaned.csv` in the Google Collab.

### Load the Dataset

```python
import pandas as pd

df = pd.read_csv("Titanic_EDA_Cleaned.csv")

df.head()
```

## Exploratory Data Analysis

The following analysis techniques are used:

- Dataset inspection using `head()`, `info()`, and `describe()`.
- Frequency analysis using `value_counts()`.
- Univariate analysis.
- Bivariate analysis.
- Multivariate analysis.
- Histograms and countplots.
- Boxplots and scatterplots.
- Pairplots.
- Correlation heatmaps.
- Outlier detection.

## Questions to Explore

1. Which passenger groups had higher survival rates?
2. How did survival vary by passenger class and sex?
3. What patterns appear in passenger age and fare?
4. Did family size or travelling alone relate to survival?
5. Which numerical variables were correlated?
6. Were there any outliers or unusual patterns?

## Key Findings

The key findings will be identified through statistical analysis and visualizations.

## Deliverables

- Google Collab (`.ipynb`) containing code, visualizations, and observations.
- PDF report summarizing the EDA and key findings.

## Conclusion

This project demonstrates the use of Python libraries for data cleaning, exploratory data analysis, statistical exploration, and visualization.

The analysis helps identify patterns and relationships in the Titanic passenger dataset.
