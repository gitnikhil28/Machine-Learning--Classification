# Crime Category Prediction Challenge

## Overview
The Crime Category Prediction Challenge is a machine learning initiative designed to forecast the type of crime based on various incident-related features. The dataset provides detailed information, including crime locations, victim demographics, and other relevant factors, to support this prediction task.

## Dataset Description
The dataset includes the following key files:

- **train.csv**: The training dataset that includes both feature attributes and the target variable `Crime_Category`.
- **test.csv**: The test dataset containing feature attributes similar to those in the training set but without the `Crime_Category` column.
- **sample.csv**: A sample submission file illustrating the correct format for competition submissions.

### Feature Columns
The dataset features the following columns:

- `Location`
- `Cross_Street`
- `Latitude`
- `Longitude`
- `Date_Reported`
- `Date_Occurred`
- `Time_Occurred`
- `Area_ID`
- `Area_Name`
- `Reporting_District_no`
- `Part 1-2`
- `Modus_Operandi`
- `Victim_Age`
- `Victim_Sex`
- `Victim_Descent`
- `Premise_Code`
- `Premise_Description`
- `Weapon_Used_Code`
- `Weapon_Description`
- `Status`
- `Status_Description`
- `Crime_Category` (Target Variable)

### Target Variable Encoding
The `Crime_Category` target variable is encoded as follows:

- **0**: Crimes against Persons
- **1**: Crimes against Public Order
- **2**: Fraud and White-Collar Crimes
- **3**: Other Crimes
- **4**: Property Crimes
- **5**: Violent Crimes

## Project Setup
To set up the project locally, follow these steps:

Clone the repository:

    ```bash
    git clone https://github.com/gitnikhil28/Machine-Learning--Classification.git
    ```

## Machine Learning Models
The project employs the following machine learning models:

- **Scikit-learn models**:
  - Decision Tree
  - Random Forest Classifier
  - LightGBM
- **XGBoost**

These models are evaluated to determine the most effective algorithm for predicting crime categories.

## Evaluation Results
The outcomes of the model evaluations are documented in the Jupyter notebook available within the project directory.

