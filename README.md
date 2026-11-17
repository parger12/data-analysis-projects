# Data Analysis & Machine Learning: Course Projects

Exercises and projects from a Data Analysis / Data Science course, written in Python
(January – April 2026). The folders follow the course topics; the numbered sub-folders
inside them are exercise numbers. Two larger projects are marked below.

**Stack:** Python · pandas · NumPy · matplotlib · SciPy · scikit-learn · Jupyter · joblib

## Contents

| Folder | Topic | What is inside |
|---|---|---|
| [`01-python-basics`](01-python-basics) | Python fundamentals | Variables, strings, lists, loops, conditionals, functions, dictionaries; first steps with pandas; a closing project on music-listening data (Moscow vs. Saint Petersburg) |
| [`02-data-preprocessing`](02-data-preprocessing) | Cleaning data with pandas | Missing values, data types, duplicates, categorization of data; **project: borrower reliability** |
| [`03-exploratory-data-analysis`](03-exploratory-data-analysis) | Exploratory data analysis | First charts and conclusions, data slices, combining several data sources, relationships between variables, validation of results; **project: real estate listings** |
| [`04-statistical-hypothesis-testing`](04-statistical-hypothesis-testing) | Statistics | Histograms and distributions, normal and binomial distributions, t-tests with SciPy (one-sample, independent, paired) |
| [`05-ml-basics`](05-ml-basics) | Machine learning basics | Decision trees, random forests, linear and logistic regression on real estate data; accuracy and mean squared error; train/test split; saving a model with joblib |
| [`06-ml-practice`](06-ml-practice) | Machine learning in practice | Travel insurance (classification) and flights (regression): one-hot encoding, scaling, precision / recall / F1, confusion matrix, class balancing, mean absolute error |
| [`07-hypothesis-testing-exercises`](07-hypothesis-testing-exercises) | Statistics exercises | Additional t-test exercises on before/after samples |

## Projects

### Borrower reliability — [`02-data-preprocessing/07-project-borrower-reliability`](02-data-preprocessing/07-project-borrower-reliability)
Preparation of a borrower dataset for analysis in a Jupyter notebook:
- data overview;
- filling missing values (median instead of mean, because the mean is distorted by anomalous values);
- checking the data for anomalies and fixing them;
- changing data types and removing duplicates;
- splitting the table into smaller dictionary tables.

### Real estate listings — [`03-exploratory-data-analysis/07-project-real-estate-listings`](03-exploratory-data-analysis/07-project-real-estate-listings)
Exploratory analysis of an archive of apartment listings for Saint Petersburg and nearby towns,
with the goal of finding what determines the market price of a property:
- study of the data file and preprocessing;
- calculation of additional columns;
- exploratory analysis with matplotlib charts.

Status: the analysis steps are in the notebook; the written conclusions have not been added yet.

### Music-listening data — [`01-python-basics/13-project-yandex-music`](01-python-basics/13-project-yandex-music)
First project with pandas: comparison of listening habits in Moscow and Saint Petersburg.

## Skills practiced
- Cleaning and preparing data: missing values, data types, duplicates
- Exploratory analysis and charts with pandas and matplotlib
- Hypothesis testing with SciPy (t-tests)
- Regression and classification models in scikit-learn: linear and logistic regression, decision trees, random forests
- Model evaluation: accuracy, MSE / MAE, precision, recall, F1, confusion matrix

## Notes
- The datasets come from the course.
- Many scripts still contain absolute file paths from the author's computer (`E:\courses\...`).
  Change the path to the CSV file next to the script before running it.
- To run the notebooks: `pip install pandas numpy matplotlib scipy scikit-learn jupyter`
