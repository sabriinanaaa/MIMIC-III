# Predicting In-Hospital Mortality with Machine Learning: Insights from the MIMIC III Database

University of Pennsylvania, Bioengineering

This is the final project for BE521 Brain Computer Interface.

_Abstract_ — This report investigates the prediction of in-hospital mortality among heart failure (HF) patients utilizing machine learning techniques applied to the MIMIC-III database. 
Heart failure represents a significant public health challenge due to its high morbidity and mortality rates. Despite technological advancements, the complex relationships between demographic characteristics, vital signs, and mortality in HF patients remain insufficiently understood. 
Leveraging the rich dataset available in the MIMIC-III database, this study aims to identify predictors of in-hospital mortality to aid healthcare professionals in early risk assessment and intervention strategies.
The study explores demographic details, vital signs, comorbidities, and laboratory variables to develop predictive models. 
Initial exploratory data analysis reveals that certain laboratory values, such as anion gap, lactic acid, and leukocyte counts, exhibit strong correlations with mortality. 
Model training and prediction involve the evaluation of eight machine learning models, with logistic regression and random forest showing the most promising performance.
Logistic regression achieves an accuracy of 86.02% and exhibits a good balance between precision and recall for patients without heart disease but lacks sensitivity for patients with heart disease. 
Random forest achieves a similar accuracy and demonstrates high precision for patients without heart disease but poor sensitivity for patients with heart disease.
To address the limitations of existing models, a basic neural network is constructed, achieving a testing accuracy of 92.37%. 
However, the study faces limitations such as data from a single institution, retrospective design, and potential missing or inaccurately recorded data.
Future recommendations include expanding the dataset to multiple centers, employing advanced machine learning techniques, and integrating real-time data acquisition. 
Overall, this study demonstrates the potential of machine learning models to aid in early risk stratification and treatment tailoring for HF patients in the ICU, paving the way for further refinement and exploration in critical care settings.






