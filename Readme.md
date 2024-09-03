Crime Category Prediction Challenge
Overview
The Crime Category Prediction Challenge is a machine learning project aimed at predicting the type of crime based on various features related to crime incidents. The dataset includes information about crime locations, victim demographics, and other factors.

Dataset
The dataset consists of the following files:

train.csv: Training set with the target variable crime_category and feature attributes.
test.csv: Test set with similar feature attributes but without the crime_category column.
sample.csv: A sample submission file in the correct format for competition submissions.
Features
The dataset includes the following columns:

Location
Cross_Street
Latitude
Longitude
Date_Reported
Date_Occurred
Time_Occurred
Area_ID
Area_Name
Reporting_District_no
Part 1-2
Modus_Operandi
Victim_Age
Victim_Sex
Victim_Descent
Premise_Code
Premise_Description
Weapon_Used_Code
Weapon_Description
Status
Status_Description
Crime_Category (Target Variable)
Encoding
The Crime_Category feature is encoded as follows:

0: Crimes against Persons
1: Crimes against Public Order
2: Fraud and White-Collar Crimes
3: Other Crimes
4: Property Crimes
5: Violent Crimes
Setup
Clone the Repository

git clone <repository-url>
cd <repository-directory>
Models
The project uses the following machine learning models:

-Scikit-learn models (e.g., Logistic Regression, KNN, SVM) -XGBoost The models are compared to find the best-performing algorithm for the crime category prediction task.

Results
The results of the model evaluation can be found in the Jupyter notebook located in the directory.
