# Stroke-Analysis-Prediction

This mini-project contains data analysis on stroke dataset from Kaggle 
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data

Stroke is the second leading cause of death globally, and this dataset is used to predict if a patient is likely to get a stroke, based on several metrics:
1) id: unique identifier<br>
2) gender: "Male", "Female" or "Other"<br>
3) age: age of the patient<br>
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension<br>
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease<br>
6) ever_married: "No" or "Yes"<br>
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"<br>
8) Residence_type: "Rural" or "Urban"<br>
9) avg_glucose_level: average glucose level in blood<br>
10) bmi: body mass index<br>
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*<br>
12) stroke: 1 if the patient had a stroke or 0 if not<br>
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

The analysis contains- 
1. data cleaning-
   - drop null values
   - drop duplicate values
3. Exploratory Data Analysis (EDA)-
   - value count
   - different bar plots- to identify imbalances
   - different box plots- to identify outliers
   - different distribution plots
4. Data Preprocessing-
   - Normalizing the data
   - encode the data
   - look for correlations
5. Data Modeling-
   - Supervised Learning- including several algorithms- Naive Bayes, Logistic Regression, Decision Tree, Random Forest and XGBoost- with evaluation metrics, synthetic samples generating with SMOTE and ADASYN and class weighting.
   - Unsupervised Learning- K-Means with Silhouette Scores and Inertia evaluation and PCA for dimension reduction.
   - Semi-Supervised Learning- XGBoost for the Supervised algorithm and K-Means Clustering for the Unsupervised algorithm
