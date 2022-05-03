# CardiovascularDiseasesClassification
ML Models for Cardiovascular Diseases Classification
----------------------
**Context:**  According to the World Health Organization (WHO), cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 17.9 million lives each year-- a whopping 32% of all deaths worldwide. Also known as the “silent killer,” cardiovascular diseases tend to have no warning signs or symptoms before a patient experiences a cardiac event like a heart attack or stroke. CVDs are fatal medical issues, and prompt treatment is crucial. Early action can significantly reduce complications and deaths worldwide. CVDs classification and prognosis is therefore, important, in order for them to be treated promptly to avoid irreversible damage or death. 

**Dataset:** This dataset is used to predict whether a patient is likely to get a cardiovascular disease based on the input parameters like age, gender, blood pressure, and physical activity. Each row in the data is an instance of a patient's records. 

*Source: https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset*

----------------------
**Dataset Attributes**
There are 3 types of input features:

I. Objective: factual information;

II. Examination: results of medical examination;

III. Subjective: information given by the patient.

Features:
1. ID: Unique Identification Number
2. Age: Objective Feature (age, int (days))
3. Height: Objective Feature (height, int (cm))
4. Weight: Objective Feature (weight, float (kg))
5. Gender: Objective Feature (gender, categorical code, 1: women, 2: men) 
6. Systolic blood pressure: Examination Feature (ap_hi, int)
7. Diastolic blood pressure: Examination Feature (ap_lo, int)
8. Cholesterol: Examination Feature (cholesterol, 1: normal, 2: above normal, 3: well above normal)
9. Glucose: Examination Feature (gluc, 1: normal, 2: above normal, 3: well above normal)
10. Smoking: Subjective Feature (smoke, binary)
11. Alcohol intake: Subjective Feature (alco, binary)
12. Physical activity: Subjective Feature (active, binary)
13. Presence or absence of cardiovascular disease: **Target Variable** (cardio, binary)

**Categorical Features:** gender, cholestrol, gluc, smoke, alco, active, cardio

**Continuous Features:** age, height, weight, ap_hi, ap_lo

*Note: All of the dataset values were collected at the moment of medical examination.*
