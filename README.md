# Data Analysis on Data Job Postings in Vietnam

## Introduction
This series of projects aims to provide insights into the Vietnamese job market, focusing on salary predictions and job role classifications based on job descriptions. R
## Dataset
The job dataset was extracted from an [spreadsheet file](https://docs.google.com/spreadsheets/d/1xWtdPaEmi6Voaum_3Ruv-Ise0SKaxVSrs5G2a0V8PLA/edit#gid=0), which contains job posting mined from different job boards and social network posts in Vietnam.
The dataset was processed manually using Excel, but there are still inconsistencies.
This dataset contains 3188 job postings, which originally contains 9 columns and was aggregated into 34 columns. Job descriptions were translated by Google, with minor manual editing.
## Methodology
**Data Preprocessing:** Cleaning and structuring the dataset for analysis.

**EDA:** Skills extracted from job descriptions were visualized using word clouds. Analyzing the dataset to understand the distribution and relationships between dependent and independent variables

**Salary Prediction:** Utilizing machine learning models like XGBoost, Random Forest, and Polynomial Regression to predict salaries.

**Job Role Classification:** Implementing NLP for skill extraction and employing multi-label regression and neural networks for role classification.

## Technologies Used
Python, Pandas, NumPy, spaCy, NLTK, Matplotlib, Seaborn, Sklearn, XGBoost, TensorFlow.

## Results and Conclusion
Achieved up to 77% accuracy in salary predictions.
Demonstrated complexities in role classification, highlighting the need for quality data.
This analysis emphasizes the potential of data science in understanding and predicting job market trends.

