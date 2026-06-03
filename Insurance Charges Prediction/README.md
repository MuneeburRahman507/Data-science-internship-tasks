## Insurance Charges Prediction (Machine Learning Project)

## Overview

This project focuses on predicting medical insurance charges using Machine Learning techniques. The dataset includes various features such as age, BMI, smoking status, number of children, and region.

The main objective is to analyze how these factors influence insurance costs and build a predictive model to estimate charges.

## Dataset Information

The dataset contains the following features:

age: Age of the individual
sex: Gender (male/female)
bmi: Body Mass Index
children: Number of dependents
smoker: Smoking status (yes/no)
region: Residential region
charges: Medical insurance cost (target variable)

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

## Exploratory Data Analysis (EDA)

Several visualizations were performed to understand the dataset:

## Distribution of insurance charges:
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/3cf97dc5-25ff-46cf-aaa5-90cec9637183" />

## Observation:
Charges are right-skewed → few people have very high medical costs.

## Smoker vs Charges comparison:
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/11d52f85-c7ef-45c9-a13b-c1dc39eeb01c" />

## Observation:
Smokers have significantly higher insurance charges compared to non-smokers, indicating a strong relationship between smoking and medical expenses.

## Age vs Charges relationship:
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/2e5e3865-095b-4b95-8da8-d26d5cd66499" />

## Observation:
As age increases, insurance charges generally increase. Older people tend to have higher medical costs.

## BMI vs Charges relationship:
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/fa389036-0ee5-4026-b8c6-737ec515a0c8" />

## Observation:
Higher BMI is associated with higher insurance charges, indicating obesity impacts medical costs.

## Correlation Heatmap:
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/3b409ea8-2720-4cac-b3a4-75d26a1e8a7d" />

## Observation:
Smoker has the highest correlation with charges
Age and BMI also show positive correlation
Other features have weaker relationships



**Key Insights**

Smoking has the highest impact on insurance charges
Age and BMI are positively correlated with charges
Individuals with higher BMI and older age tend to have higher medical costs
Regional differences have minimal impact compared to other factors

## Model Building

A Linear Regression model was used to predict insurance charges.

**Steps:**
Data preprocessing
Encoding categorical variables
Train-test split
Model training
Prediction

## Model Evaluation

The model was evaluated using:

**Mean Absolute Error (MAE)**
**Mean Squared Error (MSE)**

These metrics help measure how accurately the model predicts insurance charges.

## Conclusion

This project demonstrates how machine learning can be applied to real-world problems such as insurance cost prediction.

Smoking is the most influential factor
Age and BMI significantly affect charges
The Linear Regression model provides a good baseline

**Future improvements can include advanced models like Random Forest or Gradient Boosting for better accuracy.**
