# Data-Science-Heart-disease-prediction

## Instructions for Running Python Notebooks Locally
- requiements.txt
-  Use google colab
- use jupyter nootbook

#  Predicting Heart Disease with Classification Machine Learning Algorithms

## 1. Introduction:
###  Scenario:
   predict whether certain patients have Heart Disease. We would like to make a Machine Learning algorithm where we can train our AI to learn & improve from experience. Thus, we would want to classify patients as either positive or negative for Heart Disease.
   
### Goal:
- Predict whether a patient should be diagnosed with Heart Disease. This is a binary outcome.
Positive (+) = 1, patient diagnosed with Heart Disease
Negative (-) = 0, patient not diagnosed with Heart Disease
- Experiment with various Classification Models & see which yields greatest accuracy.
- Examine trends & correlations within our data
- Determine which features are most important to Positive/Negative Heart Disease diagnosis

### Features & Predictor:
Our Predictor (Y, Positive or Negative diagnosis of Heart Disease) is determined by 13 features (X):

1. age (#)
2. sex : 1= Male, 0= Female (Binary)
3. (cp)chest pain type (4 values -Ordinal):Value 1: typical angina ,Value 2: atypical angina, Value 3: non-anginal pain , Value 4: asymptomatic
4. (bps) resting blood pressure (#)
5. (chol) serum cholesterol in mg/dl (#)
6. (fbs)fasting blood sugar > 120 mg/dl(Binary)(1 = true; 0 = false)
7. (restECG) resting electrocardiography results(values 0,1,2)
8. (heart_rate) maximum heart rate achieved (#)
9. (exercise) exercise induced angina (binary) (1 = yes; 0 = no)
10. (oldpeak) = ST depression induced by exercise relative to rest (#)
11. (slope) of the peak exercise ST segment (Ordinal) (Value 1: up sloping , Value 2: flat , Value 3: down sloping )
12. (vessels) number of major vessels (0–3, Ordinal) colored by fluoroscopy
13. (thal) results of thallium stress test measuring blood flow to the heart, with possible values normal, fixed_defect, reversible_defect
  
#### 2. Data Wrangling
  - Importing Libraries
  - Loading Data
  - Renaming the columns
  - Basic Checks
  
#### 3. Exploratory Data Analysis
  - Checking Distribution
     - DistPlot
     - Histogram
  - Correlations
  - Heat Map
  - Pair Plot
  - CatPlot
  - Violin Plot
  - Scatter Plot
  - Checking Outliers
     - Box Plot 
  -  Filtering data by positive & negative Heart Disease patient
  
#### 4. Data processing
  - Transform the skewed data to normally distributed data
  - Label Encoding
  - Removing Outliers
  - One-Hot Encoding
  - Scaling Data
  
#### 5. Machine Learning + Predictive Analytics 
   - Modeling 
   - Splitting into Training and Test Data Set
   1. Logistic Regression 
   2. K-Nearest Neighbors
   3. Support Vector Machine 
   4. Decision Tree Classifier
   5. Random Forest Classifier
   6. XGBoosting Classifier

   
#### 6. Models Hyperparameter Tuning
   1. Logistic Regression 
   2. K-Nearest Neighbors
   3. Support Vector Machine 
   4. Decision Tree Classifier
   5. Random Forest Classifier
   6. XGBoosting Classifier
      ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍
#### 7. Conclusion

 1. Out of the 13 features I examined, the top 4 significant features that helped us classify between a positive & negative Diagnosis were 
      - thal --> Thallium stress test measuring blood flow to the heart.
      - vessels --> Number of major vessels (0–3, Ordinal) colored by fluoroscopy.
      - cp --> Chest pain type.
      - exercise --> exercise induced angina
      
 2. From this model you can check have you any heart disease or not(This project is for fun).
