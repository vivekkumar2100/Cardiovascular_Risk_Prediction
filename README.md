# Cardiovascular_Risk_Prediction
# CLASSIFICATION UNDER SUPERVISED MACHINE LEARNING
Currently cardiovascular diseases (CVDs) are the main cause of death worldwide. Disease risk estimates can be used as prognostic information and support for treating CVDs. The commonly used Framingham risk score (FRS) for CVD prediction is outdated for the modern population, so FRS may not be accurate enough. In this paper, a novel CVD prediction system based on machine learning is proposed.
# Data Description
 Sex: male or female("M" or "F")

 Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
 # Behavioral
  is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

 Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
# Medical( history)
  BP Meds: whether or not the patient was on blood pressure medication (Nominal)

  Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)

  Prevalent Hyp: whether or not the patient was hypertensive (Nominal)

  Diabetes: whether or not the patient had diabetes (Nominal)
  
  # Medical(current)
  
  Tot Chol: total cholesterol level (Continuous)

  Sys BP: systolic blood pressure (Continuous)

  Dia BP: diastolic blood pressure (Continuous)

  BMI: Body Mass Index (Continuous)

  Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in  fact discrete, yet are considered continuous because of large number of possible values.)

  Glucose: glucose level (Continuous)Predict variable (desired target)

  10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) -
  
  # STEPS-
  
 1-Data Import
 
 2-Removing non relevant featues like Id,Education
 
 3-Data exploration then removing not impacting features like Prevalent Stroke,BPMeds,Smoking etc
 
 4-Removing collinerar features like SysBP.
 
 5-Data cleaning (removing null values,outliers)
 
 6-Converting unbalanced data into balanced using SMOTE
 
 7-Applying different models and evaluating them on both Unbalanced and Balanced Data
 
 8-Evaluation of every model
 
 9-Comparison with respect to Recall Score
 
  # Conclusion
  
  1.From the above chart of recall score of various model,we can conclude that KNN Classifier hold the maximum recall score which makes it most desirelable while        logistic regression gives the minimum recall score.
  
   2-While Logistic Regression Model having the least recall score.

   3-Random Forest Classifier and XGBoost Classifier takes more time in training the model.

   4-From analysing the Feature Importance, we can say that Sex and Age play a major role in the determining the results.
