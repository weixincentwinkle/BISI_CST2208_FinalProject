# BISI_CST2208_FinalProject


Welcome to our CST 2208 final project. In this project we did analyze diabetes data form file "diabetes.csv". the dataset contains 1000 rows of records and following 9 columns for each row: <br />
&nbsp;&nbsp; Pregnancies: number of times pregnant <br />
&nbsp;&nbsp; Glucose: plasma gluconse concentration a 2 hours in an oral glucose tolerance test <br />
&nbsp;&nbsp; Blood pressure: diastolic blood pressure (mm Hg) <br />
&nbsp;&nbsp; SkinThickness: triceps skinfold thickness (mm) <br />
&nbsp;&nbsp; Insulin: 2-Hour serum insulin (mu U/ml) test <br />
&nbsp;&nbsp; BMI: body mass index (weight in kg/(height in m)^2) <br />
&nbsp;&nbsp; DiabetesPedigreeFunction: a function that scores likelihood of diabetes based on family history <br />
&nbsp;&nbsp; Age: age in years <br />
&nbsp;&nbsp; Outcome: class variable (0: person is not diabetic, 1: person is diabetic) <br />

the Outcome will be target variable while the rest of 8 variables are used as dependent variables. After reading from the csv file some statistic summary is displayed for a general view. then the following graphs are shown: <br />
&nbsp;&nbsp; distribution plot for variable 'BloodPressure' <br />
&nbsp;&nbsp; pariplot for variables 'Glucose','Skinthickness','DiabetesPedigreeFuction' along with 'Outcome' <br />
&nbsp;&nbsp; scatterplot between 'Glucose' and 'Insulin' <br />
&nbsp;&nbsp; boxplot for variable 'Age' <br />

The last step of the project will be trainning model using logistic regression and random foresst. 85% of dataset are used as trainning data while the rest of 15% of data are used as test data. After fitting model and predict with x_test values we have the result for accuracy and how many true positives and true negatives for bot models. Finally random forest model is a better choice after comparing the results. 
