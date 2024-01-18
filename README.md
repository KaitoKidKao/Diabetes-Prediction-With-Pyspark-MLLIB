# Diabetes Prediction
Using Pima Indians diabetes data set to predict whether a patient has diabetes or not based upon patient’s lab test result variables like Glucose, Blood Pressure, etc.

## Problem Statement: Diabetes is one of the deadliest diseases in the world. It is not only a disease but also creator of different kinds of diseases like heart attack, blindness etc. The normal identifying process is that patients need to visit a diagnostic center, consult their doctor, and sit tight for a day or more to get their reports.
So, the objective of this project is to identify whether the patient has diabetes or not based on diagnostic measurements.

# **Data Description**
- **Pregnancies** : No. of times pregnant
- **Glucose** : Plasma Glucose Concentration a 2 hour in an oral glucose tolerance test (mg/dl)
  A 2-hour value between 140 and 200 mg/dL (7.8 and 11.1 mmol/L) is called impaired glucose tolerance. This is called "pre-     diabetes." It means you are at increased risk of developing diabetes over time. A glucose level of 200 mg/dL (11.1 mmol/L)     or higher is used to diagnose diabetes.
- **Blood Pressure** : Diastolic Blood Pressure(mmHg): 
  If Diastolic B.P > 90 means High B.P (High Probability of Diabetes)
  Diastolic B.P < 60 means low B.P (Less Probability of Diabetes)
- **Skin Thickness** : Triceps Skin Fold Thickness (mm) –
  A value used to estimate body fat. Normal Triceps SkinFold Thickness in women is 23mm. Higher thickness leads to obesity and    chances of diabetes increases.
- **Insulin** : 2-Hour Serum Insulin (mu U/ml)
 Normal Insulin Level 16-166 mIU/L
 Values above this range can be alarming.  
- **BMI** : Body Mass Index (weight in kg/ height in m2)
Body Mass Index of 18.5 to 25 is within the normal range
BMI between 25 and 30 then it falls within the overweight range. A BMI of 30 or over falls within the obese range.
- **Diabetes Pedigree Function** : It provides information about diabetes history in relatives and genetic relationship of those relatives with patients. Higher Pedigree Function means patient is more likely to have diabetes.
- **Age** (years) : Age of Patient
- **Outcome** : Class Variable (0 or 1) where ‘0’ denotes patient is not having diabetes and ‘1’ denotes patient having diabetes
The dependent variable is whether the patient is having diabetes or not.

Data Cleaning will take place as data has got lot of missing values. Handling missing values can be done either by replacing null values with mode or mean or replacing the null value with a random variable.
