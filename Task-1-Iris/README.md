# Iris Dataset Analysis

## Overview

This project focuses on exploring and visualizing the famous Iris Dataset using Python. The objective is to understand the dataset structure, analyze relationships between features, and create meaningful visualizations using data science libraries such as Pandas, Matplotlib, and Seaborn.

## Objective

The goal of this project is to perform Exploratory Data Analysis (EDA) on the Iris Dataset and gain insights into the characteristics of different iris flower species through data visualization.

## Dataset

**Dataset:** Iris Dataset

The dataset contains measurements of iris flowers from three different species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Variable

* Species
  
## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
  
## Project Workflow

### 1. Data Loading

* Loaded the Iris Dataset using Pandas and Seaborn.
* Displayed dataset structure using:

  * `head()`
  * `shape`
  * `columns`

### 2. Data Exploration

* Examined dataset dimensions.
* Identified feature names and data types.
* Generated summary statistics using `describe()`.

### 3. Data Visualization

Created multiple visualizations to understand data distribution and relationships:

#### Scatter Plot

* Analyzed relationships between flower measurements.
* Compared species distributions.

## scatter Plot(Sepal)
<img width="450" height="300" alt="image" src="https://github.com/user-attachments/assets/efffe422-1958-4932-a7ea-d43ad36b2b10" />

## Observation
Setosa is clearly separated, while Versicolor and Virginica slightly overlap.

## Scatter Plot (Petal)
<img width="450" height="300" alt="image" src="https://github.com/user-attachments/assets/5d10ad15-efbd-441f-adec-28508a35e7f9" />

## Observation
Petal features show clear separation between all three species. These features are more useful for classification.

## Box plot (outliers check)
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/467b643a-09e0-4be0-bfd5-c0a1865b0ecb" />

## Observation
No significant outliers are observed. Data is clean and well distributed

## Histogram

* Examined feature distributions.
* Identified common value ranges.
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/32ae5f4e-edcb-491e-ab82-bfdfca494f37" />

## Observation 
Petal features show clear distribution differences between species.

## Key Findings

* Petal measurements are highly effective in distinguishing iris species.
* Iris Setosa is clearly separated from the other species.
* Iris Versicolor and Iris Virginica show some overlap but remain distinguishable.
* The dataset contains well-balanced classes with no significant missing values.
* 
## Conclusion

This project successfully explored and visualized the Iris Dataset using Python. Through exploratory data analysis and visualization techniques, meaningful insights were obtained regarding the characteristics of different iris species. The project demonstrates fundamental data analysis skills including data loading, exploration, and visualization.

## Author

**Muneeb ur Rahman**

Data Science & Analytics Internship Tasks
DevelopersHub Corporation
