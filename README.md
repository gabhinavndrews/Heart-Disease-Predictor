# Heart Disease Prediction using Neural Networks
This is the final project for Intro to AI course (CSCI-6660-01) submitted by Abhinav Andrews Giduturi and Nishanth Reddy Gangumalla


Content
Importing the Dataset
Demographic Information
Building and Training the Neural Network
Improving Results - A Binary Classification Problem
Results and Metrics

## Table of Contents:
+ [Description](#Description) </br>
+ [Dataset](#Dataset) </br>
+ [Demographic Information](#demographic_information) </br>
+ [Usage Instructions](#Usage_Instructions) </br>
+ [Steps Followed](#Steps_Followed) </br>
+ [Results and Performance](#results) </br>

## <a name="Description"></a> Description
This study will concentrate on employing AI and neural networks to forecast cardiac disease. Patients will be categorized according to different degrees of coronary artery disease based on characteristics including blood pressure, cholesterol levels, heart rate, and other distinguishing characteristics. The UCI Machine Learning Repository will provide a dataset of 303 patients for this study.

## <a name="Dataset"></a> Dataset
The University of California, Irvine Machine Learning repository has access to the dataset. This is the URL:
[Dataset](http://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data)

This dataset includes patient information related to heart disease diagnosis that was gathered from several international locations. Age, sex, resting blood pressure, cholesterol levels, echocardiography results, exercise habits, and more are among the 76 attributes. We will do the same because, according to the data, all published research employing this data concentrate on a subset of 14 variables. We will use the information gathered by the Cleveland Clinic Foundation in more detail.

## <a name="demographic_information"></a> Demographic Information
**Demographic Information**
1.(age) age in years
2. #4 (sex) here (1 = male; 0 = female)
3. #9 (cp) chest pain type
    -- Value 1: typical angina
    -- Value 2: atypical angina
    -- Value 3: non-anginal pain
    -- Value 4: asymptomatic
4. #10 (trestbps) resting blood pressure (in mm Hg on admission to the hospital)
5. #12 (chol) serum cholestoral in mg/dl
6. #16 (fbs) (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. #19 (restecg) resting electrocardiographic results
    -- Value 0: normal
    -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. #32 (thalach) maximum heart rate achieved
9. #38 (exang) exercise induced angina (1 = yes; 0 = no)
10. #40 (oldpeak) ST depression induced by exercise relative to rest
11. #41 (slope) the slope of the peak exercise ST segment
    -- Value 1: upsloping
    -- Value 2: flat
    -- Value 3: downsloping
12. #44 (ca) number of major vessels (0-3) colored by flourosopy
13. #51 (thal) 3 = normal; 6 = fixed defect; 7 = reversable defect
14. #58 (num) (the predicted attribute)  diagnosis of heart disease (angiographic disease status)
    -- Value 0: < 50% diameter narrowing
    -- Value 1: > 50% diameter narrowing

## <a name="Usage_Instructions"></a> Usage Instructions
To run this project the following libraries must be installed: pandas, numpy, sklearn, matplotlib, keras.
Execute each block in the ipynb file to observe the changes step by step.

## <a name="Steps_Followed"></a> Steps Followed
we are following 4 steps to achieve the project goals:
•	Identifying and importing the dataset.
•	Designed and creating training and testing datasets.
•	Building and training the neural network.
•	Analyzing and improving the obtained results.

## <a name="Results"></a> Results And Performance

Histogram describing characteristics of data
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/histogram.jpg)
Bargraph describing heart disease frequency for ages
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/bargraph.jpg)
Relativity Heatmap
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/heatmap.jpg)
Line graph Age vs Talach
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/graph.jpg)
Model accuracy before using binary model
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/model accuracy bfr.jpg)
Model accuracy after using binary model
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/model accuracy aftr.jpg)
Model loss before using binary model
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/model loss bfr.jpg)
Model loss after using binary model
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/model loss aftr.jpg)
Categorical model results
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/Categorical model.jpg)
Binary model results
![image](https://github.com/gabhinavndrews/Heart-Disease-Predictor/blob/main/binary model.jpg)
