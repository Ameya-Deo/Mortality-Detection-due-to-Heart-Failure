# Mortality Detection due to Heart Failure
## Introduction
Cardiovascular disorders are the leading cause of death worldwide, with heart failure being the most common complication. There are various factors that influence the illness, such as diabetes, anemia, blood pressure, and others, all of which are directly accountable for heart failure.

## Purpose
The goal of this project is to use several machine learning methods to perform data analysis and model training on the 'Heart Failure' dataset and quantify the probability of heart failure. The features were extensively scrutinized, analyzed, and features that have a direct part in heart failure, which will eventually lead to death, as well as features that can aid in survival, were discovered.

## DataSet
This dataset provides data on 5074 patients who are experiencing heart failure symptoms. The BMC Medical Informatics and Decision link (https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5#Sec2) contains a description of this dataset.

## DataSet details
The dataset contains 12 features:
age : the age of the person with heart failure
anaemia : Decrease of red blood cells or hemoglobin (boolean)
creatinine_phosphokinase : Level of the CPK enzyme in the blood (mcg/L)
diabetes : If the patient has diabetes (boolean)
ejection_fraction : Percentage of blood leaving the heart at each contraction (percentage)
high_blood_pressure : If the patient has hypertension (boolean)
platelets : Platelets in the blood (kiloplatelets/mL)
serum_creatinine : Level of serum creatinine in the blood (mg/dL)
serum_sodium : Level of serum sodium in the blood (mEq/L)
sex : Woman or man (binary)
smoking : If the patient smokes or not (boolean)
time : Follow-up period (days)
DEATH_EVENT : If the patient deceased during the follow-up period (boolean)

## Models Implemented:
1) Logistic Regression
2) Decision Tree
3) Random Forest
4) SVM
5) XGBoost

## Conclusion
The goal of predicting death due to heart failure was effectively assessed using 12 characteristics or health situations. Decision tree outperforms all other models in terms of accuracy, predicting 95% of the time. The project is in the healthcare industry, and it has a lot of potential in terms of predictive analysis and machine learning models.

