# health_care_diabetes

# Context:

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

# Problem Statement:

Build a model to accurately predict whether the patients in the dataset have diabetes or not?

# Dataset Description:

The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.<br><br/>


Pregnancies: Number of times pregnant<br/>
Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test<br/>
BloodPressure: Diastolic blood pressure (mm Hg)<br/>
SkinThickness: Triceps skin fold thickness (mm)<br/>
Insulin: 2-Hour serum insulin (mu U/ml)<br/>
BMI: Body mass index (weight in kg/(height in m)^2)<br/>
DiabetesPedigreeFunction: Diabetes pedigree function<br/>
Age: Age (years)<br/>
Outcome: Class variable (0 or 1) 268 of 768 are 1, the others are 0<br/>
<br/>
# Steps performed for solution<br/>
Technologies used : python (NumPy, Pandas ,scikit-learn)<br/>
Model used        : logistic regression, Decision tree, SVM, KNN, SVC<br/>
Evaluation done   : Truth table, ROC AUC Curve, PR Curve  <br/>
Model accuracy    : 80% [logistic regression]<br/>
