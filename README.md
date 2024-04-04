# Loan-Dataset-Preprocessing-for-Credit-Risk-Modeling
# Project Description:
This project involves preprocessing a loan dataset provided by the US office of our bank for the data science team located in our European branch. The dataset contains 10,000 entries and pertains to loans issued in US dollars. The primary objective is to prepare the data for building a credit risk model, which will assist in assessing the likelihood of loan default. You only need the raw data from "loan-data.csv" and resources listed in the tools section for this project

## Data Preprocessing:
Using Python and its NumPy package, the dataset will undergo preprocessing to enhance its suitability for the data science team's modeling efforts. The preprocessing steps include handling missing data, converting string text to numeric data, and addressing potential risks associated with incomplete or unreliable information.

## Risk Aversiveness and Missing Data:
Given the critical nature of credit risk assessment, a risk-averse approach is adopted towards handling missing data. For instance, if essential information such as the loan status is missing, it is assumed to be unverified or potentially negative. This conservative assumption ensures that the model considers the worst-case scenario, mitigating the risk of underestimating credit risk.

## Conversion of String Text to Numeric Data:
Converting string text to numeric data is essential for model development due to the following reasons:

1. Model Compatibility: Many machine learning algorithms require numerical inputs. Converting string text to numeric data ensures compatibility with these algorithms, facilitating model development and analysis.

2. Feature Engineering: Numeric representation enables the incorporation of textual features into the model. For instance, converting loan grades or verification statuses into numerical values allows the model to capture their relative importance in predicting credit risk.

3. Data Standardization: Numeric data simplifies data standardization and normalization processes, making it easier to compare and interpret different features within the dataset.

By converting string text to numeric data, we enhance the dataset's usability and enable the data science team to build robust credit risk models effectively.

Overall, this project aims to optimize the loan dataset for credit risk modeling, leveraging Python and NumPy for efficient data preprocessing. Through meticulous handling of missing data and conversion of textual features to numeric representations, we aim to provide the data science team with a clean and structured dataset conducive to accurate credit risk assessment.



## Tasks
As a data analyst at a European branch of a bank, you are assisting in the development of a Credit Risk Model using loan data from the US branch. These are neccessary tasks to achieve your goal:

1. Examine the dataset.
2. Import the data.
3. Split the data.
4. Convert USD to Euros.
5. Quantify each categorical variable.
6. Change text columns into numbers.
7. Treat missing information with a risk-averse approach.
8. Clean and preprocess the data.
9. Save to an external .csv file.
10. Assist in developing a Credit Risk Model using Probability to determine the likelihood of default.

### Methodology:

1. Import Packages: Begin by importing the necessary Python packages for data analysis and manipulation, including NumPy.
2. Import Data: Load the loan dataset provided by the US branch into your Python environment.
3. Check for Incomplete Data: Identify and handle any missing or incomplete data in the dataset.
4. Split Dataset: Divide the dataset into two subsets - one containing numeric data and the other containing string/text data.
5. Rename Columns: Name the columns in each subset to ensure clarity and descriptiveness.
6. Create Checkpoints: Establish checkpoints throughout the preprocessing steps to backup your progress and facilitate easy recovery.
7. Manipulate String Columns: Process the string/text columns to remove excess data, rename columns for clarity, substitute strings, delete redundant columns, and convert textual data into numeric values for model compatibility.
8. Convert USD to Euros: Add additional columns to the numeric dataset, showing the converted amounts in Euros for enhanced international analysis.
9. Save Preprocessed Data: Save the cleaned and preprocessed dataset to an external .csv file for future use.
10. Assist in Credit Risk Model Development: Collaborate with the data science team to develop a Credit Risk Model using probability methods to predict the likelihood of default.

## Tools

- Notepad++: Use Notepad++ for writing and editing code. [Download here](https://notepad-plus-plus.org/downloads/)
- Anaconda: Install Anaconda for managing Python environments and packages effectively. [Download here](https://www.anaconda.com/download/)


