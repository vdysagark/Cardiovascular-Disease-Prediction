# Cardiovascular-Disease-Prediction

Introduction


According to American Heart Association (AHA), Cardiovascular disease (CVD) is the number one cause of deaths in the US. CVD accounted for 859,125 deaths in the US in 2017. Cardiovascular diseases claim more lives each year than all forms of cancer and Chronic Lower Respiratory Disease combined. In 2017, Coronary Heart Disease was the leading cause (42.6%) of deaths attributable to cardiovascular disease in the US, followed by stroke (17.0%), High Blood Pressure (10.5%), Heart Failure (9.4%), diseases of the arteries (2.9%), and other cardiovascular diseases (17.6%) (AHA, 2020).

CVD is the leading global cause of death and accounted for approximately 17.8 million deaths globally in 2017. This number is expected to grow to more than 22.2 million by 2030, according to a 2014 study. Total direct medical costs of CVD are projected to increase to $749 billion in 2035, according to a 2016 study.

The American Heart Association gauges the cardiovascular health of the nation by tracking seven key health factors and behaviors that increase risks for heart disease and stroke. These key health factors are called "Life's Simple 7" and they are measured to track progress of improving the cardiovascular health. Life's Simple 7 are: not-smoking, physical activity, healthy diet, body weight, and control of cholesterol, blood pressure, and blood sugar.

The silver lining is that CVD is highly preventable and simple lifestyle modifications (such as reducing alcohol and tobacco use; eating healthily and exercising) coupled with early treatment greatly improves its prognosis. It is, however, difficult to identify high risk patients because of the multi-factorial nature of several contributory risk factors such as diabetes, high blood pressure, high cholesterol, etc. This is where machine learning and data mining come to the rescue (Mordecai, n.d.).

Predictive analytics is being slowly and steadily embraced by the healthcare industry. There are many areas in healthcare that are using machine learning methods to improve patient care and reduce costs. One such application of machine learning in healthcare is predictive diagnosis. 
The goal of this project is to predict whether an individual has cardiovascular disease or not based on various parameters and health conditions.

Data sources

The dataset is obtained from Kaggle website. (Link: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset). The dataset has 12 columns and 70,000 rows. The column attributes include age, gender, height, weight, systolic blood pressure, diastolic blood pressure, cholesterol, glucose, smoking, alcohol intake, physical activity and cardiovascular disease. The target variable is the last column which is a binary categorical variable of whether a person will have the heart disease or not. The advantage with this dataset is that it has reasonable amount of data (70,000 rows) to explore and build a really well working classification model. 

Problem statement

The goal of this project is to predict whether an individual has cardiovascular disease or not based on various parameters and health conditions. For the predictive analysis, we will also compare the performance of classification algorithms to understand which one works better. 


Approach

For this project, I will be using Python program, Jupyter notebook and sikit learn classification algorithms for the analysis. First step is to understand the dataset. Next, I will be performing exploratory analysis. The dataset has a few issues that need to be fixed. For example, the age is represented in days instead of years. I will also include the BMI column. Next step will be feature engineering and selecting dependent and independent variables to build a model. I will be using Logistic regression, Support Vector Machine (SVM) and Naïve Bayes Classifier algorithms to fit the data and evaluate performance.
