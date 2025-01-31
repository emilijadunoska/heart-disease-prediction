# Heart Disease Prediction 
A machine learning project focused on predicting heart disease using a variety of health-related attributes. Explore data analysis, feature engineering, and predictive modeling to gain insights into heart disease risk factors and enhance early diagnosis

# Dataset

The dataset used in this project is the **Heart Disease Dataset** from Kaggle, originally collected in 1988. It consists of **13 attributes** along with a target variable indicating whether a person has heart disease (**1**) or not (**0**). The attributes include: 
- **Age**: Age in years  
- **Sex**: (0 = Female, 1 = Male)  
- **Chest Pain Type (cp)**:  
  - 1 = Typical angina  
  - 2 = Atypical angina  
  - 3 = Non-anginal pain  
  - 4 = Asymptomatic  
- **Resting Blood Pressure (trestbps)**: Measured in mmHg  
- **Serum Cholesterol (chol)**: Measured in mg/dL  
- **Fasting Blood Sugar (fbs)**: Above 126 mg/dL (0 = False, 1 = True)  
- **Resting ECG (restecg)**: 3 categories  
- **Maximum Heart Rate Achieved (thalach)**  
- **Exercise-Induced Angina (exang)**: (0 = No, 1 = Yes)  
- **ST Depression (oldpeak)**: Induced by exercise relative to rest  
- **Slope of the ST Segment (slope)**:  
  - 1 = Upsloping  
  - 2 = Flat  
  - 3 = Downsloping  
- **Number of Major Vessels (ca)**: (0–3) colored by fluoroscopy  
- **Thallium Stress Test (thal)**:  
  - 1 = Normal  
  - 2 = Fixed defect  
  - 3 = Reversible defect  
- **Target Variable**:  
  - 0 = No heart disease  
  - 1 = Heart disease present

# Project structure

## 1. Library Import  
We begin by importing the necessary Python libraries for data analysis, visualization, and machine learning.

## 2. Load Dataset  
The dataset is loaded into a Pandas DataFrame for further analysis.

## 3. Data Preparation and Cleaning  
- Checking dataset dimensions  
- Previewing the dataset  
- Describing the data  
- Renaming columns for clarity  
- Checking for missing values  

## 4. Attribute Analysis  
#### Objective of the Analysis  
The goal is to understand patterns in the data and assess which factors contribute to heart disease.  

### Key Areas of Analysis  
- **Distribution of cases based on heart disease presence**  
- **Correlations between attributes**  
- **Visualization of important attributes and their relationship with the target variable**  
  - **Sex**  
  - **Age**  
  - **Distribution by gender and age based on target**  
  - **Chest pain type**  
  - **Major vessel distribution**  
  - **ST segment slope at peak load**  

## 5. Risk Factors for Developing Heart Disease  
We analyze key risk factors that contribute to heart disease, including:  
1. **Fasting Blood Sugar (fbs)**  
2. **Resting Blood Pressure (trestbps)**  
3. **High Cholesterol (chol)**  
4. **Maximum Heart Rate (thalach)**  

## 6. Machine Learning Model  
To predict heart disease, we build a machine learning model using **K-Nearest Neighbors (KNN)**. 
#### Steps:  
- **Standardization of numerical data**  
- **Splitting the data into training and test sets**  
- **Implementing the K-Nearest Neighbors classification algorithm**  
- **Training and evaluating the model**  
- **Predicting results**  
- **Analyzing performance using a Confusion Matrix**  
- **Testing the Stratified K-Fold algorithm**  
- **Parameter optimization using Random Search**  
- **Testing multiple classification models for comparison**  

## 7. Important Findings and Contributions  
- Key insights gained from attribute analysis  
- Identification of the most significant risk factors for heart disease  
- Model performance and accuracy in predicting heart disease  
- Contribution to healthcare by demonstrating how machine learning can assist in early disease detection  

## Prerequisites

Before you clone the repository, make sure you have the following prerequisites installed on your system:

- Python 3.11.2 or higher
- Jupyter Notebook


## Author
- Emilija Dunoska (emilija.dunoska@student.um.si)


**University:** [University of Maribor](https://www.um.si/en/home-page/) </br>
**Faculty:** [Faculty of Electrical Engineering and Computer Science](https://feri.um.si/) </br>
**Program:** Information Systems and Communication Technologies </br>

&copy; 2023 All rights reserved.

