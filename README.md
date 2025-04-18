# Healthcare Fraud Detection Project

## What is this project about?

This project explores healthcare claims data to spot fraudulent activities among medical providers. I used data analysis and machine learning methods to catch suspicious patterns and highlight potential fraud.

## Where did the data come from?

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis/data). It includes a few different CSV files:

- Beneficiary details
- Inpatient claims
- Outpatient claims
- Labels marking claims suspected of fraud

For more details, you can check out the presentation slides available in this [project slides](https://drive.google.com/file/d/1jPnMJNZRz9oQVxCP3VmEwOjEiFoHIbL3/view?usp=sharing).

## What did I try to achieve?

- Understand the data better by exploring and visualizing it.
- Find important features that help in detecting fraud.
- Use machine learning, especially logistic regression, to predict fraud.
- Measure how well my models performed using ROC-AUC, precision, recall, and F1-score.

## How did I approach this?

### Data Cleaning and Preprocessing

- Fixed missing values and removed duplicates.
- Converted categorical data into numerical format and transformed date fields from object type to datetime format.
- Scaled numerical data to make it easier to work with.

### Exploratory Data Analysis (EDA)

- Looked at statistics and visualizations to understand patterns and outliers.
- Created visualizations like scatter plots, histograms, and bar charts to see trends clearly.
- Checked important factors like how long claims lasted, the amounts reimbursed, and provider behavior.

### Feature Engineering

- Created new features like total claim amounts and duration claim.
- Identified potential features for future exploration, such as behaviors indicative of double billing, unbundling, phantom billing, and upcoding.

### Model Building

- Split data into training and testing (80% training, 20% testing).
- Used logistic regression with some hyperparameter tuning.

### How did I measure success?

- Used ROC-AUC to check how effectively my model distinguished between fraudulent and non-fraudulent claims.
- Looked at precision, recall, and F1-score to evaluate the balance between finding fraud and avoiding false alarms.

## Tools I used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
