# BISI_CST2208_FinalProject


Welcome to our CST 2208 final project. In this project we did analyze diabetes data form file "diabetes.csv". the dataset contains 1000 rows of records and following 9 columns for each row:

&nbsp Pregnancies: number of times pregnant

Glucose: plasma gluconse concentration a 2 hours in an oral glucose tolerance test

Blood pressure: diastolic blood pressure (mm Hg)

SkinThickness: triceps skinfold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml) test

BMI: body mass index (weight in kg/(height in m)^2)

DiabetesPedigreeFunction: a function that scores likelihood of diabetes based on family history

Age: age in years

Outcome: class variable (0: person is not diabetic, 1: person is diabetic)

the Outcome will be target variable while the rest of 8 variables are used as dependent variables. 

After reading from the csv file some statistic summary is displayed for a general view. then the following graphs are shown: 

distribution plot for variable 'BloodPressure'

pariplot for variables 'Glucose','Skinthickness','DiabetesPedigreeFuction' along with 'Outcome'

scatterplot between 'Glucose' and 'Insulin'

boxplot ofr variable 'Age'

The last step of the project will be trainning model using logistic regression and random foresst. 85% of dataset are used as trainning data while the rest of 15% of data are used as test data. After fitting model and predict with x_test values we have the result for accuracy and how many true positives and true negatives for bot models. Finally random forest model is a better choice after comparing the results. 
