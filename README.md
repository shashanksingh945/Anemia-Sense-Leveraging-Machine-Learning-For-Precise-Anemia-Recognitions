# Anemia Sense: Leveraging Machine Learning For Precise Anemia Recognitions

Anemiasense leverages machine learning algorithms to provide precise recognition and management of anemia, a condition characterized by a deficiency of red blood cells or hemoglobin. Here are three general scenarios illustrating its use case:

## Scenario 1: Early Detection and Diagnosis:
Anemiasense utilizes machine learning models trained on vast datasets of blood parameters and patient profiles to detect early signs of anemia. By analyzing key indicators such as hemoglobin levels, red blood cell counts, and other relevant biomarkers, the system can flag potential cases for further investigation by healthcare professionals. Early detection enables timely interventions and treatment plans, improving patient outcomes.

## Scenario 2: Personalized Treatment Plans
Machine learning algorithms in Anemiasense can analyze diverse patient data, including genetic factors, lifestyle habits, and medical history, to generate personalized treatment plans. By considering individual variations and responses to different treatments, the system helps healthcare providers tailor interventions for optimal results. This personalized approach enhances the effectiveness of anemia management and reduces the risk of complications.

## Scenario 3: Remote Monitoring and Follow-Up
Anemiasense supports remote monitoring of patients with anemia through wearable devices or digital health platforms. Machine learning algorithms continuously analyze real-time data such as hemoglobin levels, activity levels, and medication adherence to provide insights to both patients and healthcare providers. This remote monitoring capability facilitates proactive management, enables timely adjustments to treatment regimens, and reduces the need for frequent in-person visits, particularly beneficial for patients in rural or underserved areas.

# Project Flow

User interacts with the UI to enter the input. Entered input is analyzed by the model which is integrated. Once the model analyses the input the prediction is showcased on the UI 

To accomplish this, I have to complete all the activities listed below

1. __Data Collection & Preparation__ :- Collected data from anemia.csv file.Handeled Missing values and imbalanced data
   
2. __Exploratory Data Analysis__ :- Visualize the data in univarite , Bivariate, Multivate.Split the data for training.
   
3. __Model Building__ :- Training the models on multiple algorithms
   3.1 `Logistic Regression Model`
   3.2 `Random forest model`
   3.3 `Decision Tree Model`
   3.4 `Gaussian Navies Bayes`
   3.5 `Support Vector Machine`
   3.6 `Gradient Boosting Classifier`

4. __Performance testing and Hyper Parameter Tunning__ :- Tested the model using best algorithm i.e. __Gradient Boosting Classifier__
<img width="587" height="301" alt="ModelEvaluation" src="https://github.com/user-attachments/assets/031fdfe2-073f-4135-b7b1-6347e5736eba" />

6. __Model Deployment__ :- Saved the Best Model using _pickle_. Integrate with Web Framework which includes
   6.1 Building HTML Pages 
   6.2 Building server-side script
   6.3 Run the web application

Link of Badge:
https://www.credly.com/users/shashank-singh.945/badges#credly
   
   

