# <p align = 'center'> Predicting and Analysing Readmission of Diabetes Patients In Hospital (1999 - 2008)</p>

## PROBLEM DEFINATION
Our aim is to predict if a patient with diabetes will be readmitted to the hospital within 30 days.
In this project I will demonstrate how to build a model predicting readmission in Python using the following steps

1. Data Exploration
2. Feature Engineering
3. Building Training/Validation/Test samples
4. Model selection
5. Performance Evaluation

## DATA DESCRIPTION
The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.

(1) It is an inpatient encounter (a hospital admission).

(2) It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.

(3) The length of stay was at least 1 day and at most 14 days.

(4) Laboratory tests were performed during the encounter.

(5) Medications were administered during the encounter.

The data that is used in this project originally comes from the UCI machine learning repository - https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008

The `data definition` can be found using this link - https://www.hindawi.com/journals/bmri/2014/781670/tab1/

The data consists of over 100000 hospital admissions from patients with diabetes from 130 US hospitals between 1999-2008.
The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.


## CONCLUSION
Through this project, we created a binary classifier to predict the probability that a patient with diabetes would be readmitted to the hospital within 30 days. On held out test data, our best model had an AUC of of 0.67. Using this model, we are able to catch 58% of the readmissions from our model that performs approximately 1.5 times better than randomly selecting patients.