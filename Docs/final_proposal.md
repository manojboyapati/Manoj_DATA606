# Stroke Prediction
## Introduction
Stroke is a primary cause of mortality globally, according to the World Health Organization (WHO). In reality, stroke is the world's second greatest cause of mortality, accounting for nearly 11% of all deaths. Furthermore, stroke is a leading cause of disability and can have a considerable influence on an individual's quality of life. The actual percentage of worldwide stroke deaths varies depending on factors such as population age structure, risk factors, and availability to treatment.
It is important to remember that the intensity and result of a stroke can vary widely, and some people may recover completely or have very minor consequences, whilst others may have more severe or long-term consequences.
## Dataset
This dataset has been obtained from https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?datasetId=1120859&language=Python
There are total of 5110 rows and 12 columns
Columns
1.	id: unique identifier
2.	gender: "Male", "Female" or "Other"
3.	 age: age of the patient
4.	 hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5.	 heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6.	 ever_married: "No" or "Yes"
7.	 work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8.	 Residence_type: "Rural" or "Urban"
9.	avg_glucose_level: average glucose level in blood
10.	bmi: body mass index
11.	smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12.	stroke: 1 if the patient had a stroke or 0 if not
Note: "Unknown" in smoking_status means that the information is unavailable for this patient.
## Developing Model
My plan is to use Logistic regression and Random tree classifier as first classification models and choose next models based on results.  I will try to implement and explain different models and find the accuracy to determine the best model.I will try at least two more other classifiers. My main objective of my project is to identify common risk factor of stroke.
