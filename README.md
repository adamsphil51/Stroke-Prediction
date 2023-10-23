# Stroke-Prediction

Stroke Prediction Dataset
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

Dataset Information:

healthcare-data-stroke-data.csv: The csv contains data related to patients who may have heart disease and various attributes which determine that :

    id: unique identifier
    gender: "Male", "Female" or "Other"
    age: age of the patient
    hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
    heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
    ever_married: "No" or "Yes"
    work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
    Residence_type: "Rural" or "Urban"
    avg_glucose_level: average glucose level in blood
    bmi: body mass index
    smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
    stroke: 1 if the patient had a stroke or 0 if not
    *Note: "Unknown" in smoking_status means that the information is unavailable for this patient

Objective

Visualize the relationships between various Healthy and Unhealthy habits to Heart Strokes, and there by predict the stroke probability with best model and hypertuned parameters.
Assumptions

    Smoking can induce Stroke, is it true?
    Heart with a Heart Disease is prone to Stroke, is it true?
    Workload results in high blood pressure and that could lead to Stroke, is it true?
    Males are most susceptible to strokes due to high work related stress, is it true?
    Questions to be answered
    
    Does age has impact on strokes? and How is this parameter distributed?
    Does body mass index and glucose levels in a person, propel a heart stroke?
    Is there a difference in the rate of heart stroke for smokers and non smokers?
    Does the type of job, whether stressdul or not, contribute to heart stroke?
