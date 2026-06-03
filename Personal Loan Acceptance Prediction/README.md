## Personal Loan Acceptance Prediction

## Overview

This project aims to predict whether a customer is likely to accept a personal loan offer using Machine Learning techniques.
The project uses the Bank Marketing Dataset and applies a Logistic Regression model to classify customers based on demographic and financial information.

## Objective

The objective of this project is to identify customers who are more likely to accept a personal loan offer.
Such predictions can help financial institutions improve marketing strategies, reduce campaign costs, and increase conversion rates.

## Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains customer information such as:

* Age
* Job
* Marital Status
* Education
* Account Balance
* Housing Loan Status
* Personal Loan Status
* Contact Type
* Campaign Information
* Previous Marketing Outcomes

**Target Variable:**

* `y`

  * Yes = Customer accepted the loan offer
  * No = Customer did not accept the loan offer

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading and Exploration

* Loaded the Bank Marketing Dataset.
* Examined dataset structure using:

  * `head()`
  * `shape`
  * `info()`
  * `describe()`

### 2. Data Preprocessing

* Checked for missing values.
* Checked for duplicate records.
* Encoded categorical features using Label Encoding.
* Prepared features and target variables for model training.

### 3. Exploratory Data Analysis (EDA)

Created visualizations to understand customer characteristics:

## Age Distribution

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/47108505-4d64-4708-9c51-748bb9cbac5a" />

## Observation
Most customers belong to the middle-aged group between 30 and 50 years.
Very young and very old customers represent a smaller portion of the dataset.

## Job Distribution

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/4c7ec98c-f987-4442-983c-9053efe5949f" />

## Observation
Blue-collar, management, and technician professions constitute a significant portion of the customer base. 
Some job categories contain considerably fewer customers.

## Marital Status Distribution

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/e5bc7302-8310-44d4-8591-faee5bc57a9a" />

## Observatiion
Married customers form the largest customer segment, followed by single customers. 
Divorced customers represent the smallest group


## Education Distribution

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/390ebbf6-5d50-4928-8716-933b708ff534" />

## Observation
Secondary education is the most common education level among customers, followed by tertiary education.

## Loan Acceptance Distribution

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/51f2f3d6-1668-4380-b160-a638126793fe" />

## Observation
The majority of customers did not subscribe to the loan offer, confirming the class imbalance observed earlier.

## Loan Acceptance by Marital Status

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/4fc7851d-8a88-4ed8-835b-937b9731219a" />

## Observation
Loan acceptance varies across marital groups.
Comparing accepted and rejected responses helps identify customer segments that are more responsive to marketing campaigns.


### 4. Model Training

Implemented a Logistic Regression classifier to predict loan acceptance.

### 5. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

## Results

### Model Accuracy

**Accuracy Score: 88.51%**

### Classification Performance

| Metric    | Class 0 (No) | Class 1 (Yes) |
| --------- | ------------ | ------------- |
| Precision | 0.90         | 0.57          |
| Recall    | 0.98         | 0.20          |
| F1-Score  | 0.94         | 0.30          |

### Confusion Matrix

<img width="518" height="393" alt="image" src="https://github.com/user-attachments/assets/be179a48-2f0c-4aef-9db1-49f63a1590a2" />


| Actual / Predicted | No   | Yes |
| ------------------ | ---- | --- |
| No                 | 7785 | 167 |
| Yes                | 872  | 219 |

## Observation
The confusion matrix shows the number of correct and incorrect predictions.
The diagonal values represent correctly classified customers, while off-diagonal values indicate misclassifications.



## Key Insights

* Most customers did not accept the loan offer.
* The dataset is imbalanced, with significantly more "No" responses than "Yes" responses.
* Logistic Regression achieved strong overall accuracy.
* Customer demographics and financial characteristics influence loan acceptance behavior.
* Predictive models can help banks target potential customers more effectively.



## Conclusion

This project successfully developed a Personal Loan Acceptance Prediction model using Logistic Regression.
The model achieved an accuracy of 88.51% and demonstrated the ability to identify customer behavior based on demographic and financial attributes.
The findings show how machine learning can support banks in making data-driven marketing decisions and improving customer targeting strategies.



## Author

**Muneeb ur Rahman**

Data Science & Analytics Internship Tasks
DevelopersHub Corporation
