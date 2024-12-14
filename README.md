# Stroke-Prediction---ML-Project-

Problem Statement:

Stroke is a critical cerebrovascular disease caused by an interruption of blood flow to the brain, resulting in severe consequences such as brain cell death and, in many cases, permanent disability or death. According to the American Stroke Association, stroke is one of the leading causes of death and disability in the United States. Early detection and preventive measures are crucial to reduce its impact. This project aims to leverage machine learning techniques to predict the likelihood of a stroke based on patient medical data.

Dataset Overview:

The dataset consists of 5,110 patient records with 12 key attributes, including:

Demographics: Gender, age, marital status, residence type.
Health-related features: Hypertension, heart disease, BMI, average glucose level.
Lifestyle factors: Smoking status, work type.
Target variable: Stroke occurrence (binary: 1 for stroke, 0 for no stroke).

Objectives:

1. Analyze the dataset for missing values, data types, and statistical summaries.
2. Perform data cleaning, including imputing missing values and encoding categorical variables.
3. Explore data through visualizations to identify trends and patterns associated with stroke occurrence.
4. Apply hypothesis testing to identify significant features correlated with stroke.
5. Build and evaluate machine learning models to predict stroke likelihood.

Key Technical Methods:

1. Data Preprocessing:

  1. Imputed missing values for BMI using predictive modeling.
  2. Categorical encoding for features like work_type, smoking_status, and ever_married.
  3. Dropped irrelevant columns to focus on key predictors.
  4. Checked for skewness and kurtosis in features and addressed imbalances.

2. Exploratory Data Analysis (EDA):

  1. Visualized stroke samples by BMI, glucose levels, and age distributions.
  2. Used pie charts and heatmaps to understand smoking categories and feature correlations.
  3. Identified highly correlated features using the correlation matrix.

3. Statistical Analysis:
   Conducted hypothesis testing to determine significant variables affecting stroke outcomes.

4. Machine Learning Modeling:

  1. Split the dataset into training (70%) and testing (30%) sets.
  2. Handled class imbalance using appropriate resampling techniques.
  3. Tried multiple models (e.g., Logistic Regression, Decision Trees, Random Forest, Gradient Boosting).
  4. Fine-tuned hyperparameters to improve model performance.
  5. Evaluated models using metrics like accuracy, precision, recall, and F1-score.

Results:
The project provides insights into key factors influencing stroke risk and delivers a trained machine learning model capable of accurately predicting stroke occurrence. This can aid healthcare professionals in early diagnosis and preventive interventions.
