## Stroke-Prediction-through-Machine-Learning


#### Problem Statement 
Stroke is a major health concern globally and has a significant impact on both individuals and healthcare systems. There are many risk factors for stroke, such as hypertension, heart disease, diabetes, and lifestyle 
factors. This project aims to use machine learning to analyze large datasets and accurately predict stroke risk based on these modifiable risk factors. The ultimate goal is to create a personalized stroke risk warning 
system that provides tailored messages to individuals, suggesting lifestyle modifications to reduce their risk of stroke. This approach has the potential to transform stroke prevention and management, leading to a 
decrease in the impact of this life-threatening condition on individuals and healthcare systems worldwide.

#### Data Description
The "healthcare-dataset-stroke-data" is a dataset available on Kaggle that contains 5110 unique patient observations with 12 attributes, including categorical and quantitative variables. The variables provide insight into 
various social, lifestyle, and medical factors that can influence stroke risk and outcomes. The dataset is a valuable resource for healthcare professionals and researchers seeking to develop more effective prevention and 
treatment strategies for stroke.

#### Attribute Information 
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not

#### Target Variable 
Target 1. Stroke: Stroke history (0 = no stroke risk, 1 = stroke risk; target variable)

#### Assumptions Considered during the project
The dataset at hand, sourced from Care Life hospital, encapsulates information pertaining to the health profiles of a vast array of individuals, encompassing data collected from a total of 5000 patients. In the interest
of leveraging this data to derive valuable insights, we are poised to subject this dataset to a rigorous machine learning-based analysis, in order to glean a nuanced understanding of the underlying patterns and trends. 
Specifically, we will be utilizing machine learning algorithms to glean insights from historical health data, in an effort to inform and support a diverse set of stakeholders, including payers, providers and patients. 
Through the judicious application of machine learning techniques, we anticipate being able to derive meaningful, actionable insights from this rich and complex dataset, enabling us to better understand the health profiles 
of these 5000 patients, and in turn, facilitating more informed, personalized and effective healthcare interventions.
From a pool of 10 variables, we have identified three key predictors: age, hypertension, and heart disease. Our objective is to predict the occurrence of stroke based on these variables.

