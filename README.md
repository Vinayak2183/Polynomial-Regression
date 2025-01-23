
# Polynomial vs Linear Regression: A Comparison  

This repository demonstrates the implementation and comparison of **Polynomial Regression** and **Linear Regression** models on a dataset of position salaries. The primary objective is to showcase how Polynomial Regression can better fit non-linear data compared to Linear Regression.  

## Dataset  

The dataset used in this project (`Position_Salaries.csv`) contains the following columns:  
- **Position**: Job title (e.g., Manager, Analyst).  
- **Level**: Job level (numerical representation).  
- **Salary**: Corresponding salary for the position.  

## Project Overview  

### 1. Data Preprocessing  
- Load the dataset and preprocess it to extract relevant features (`Level`) and the target variable (`Salary`).  

### 2. Model Implementation  
- **Linear Regression**: A simple model that assumes a straight-line relationship between `Level` and `Salary`.  
- **Polynomial Regression**: A model that extends Linear Regression by incorporating higher-degree polynomial features to better fit non-linear patterns.  

### 3. Comparison  
- Visualize the results of both models using scatter plots with the best-fit line/curve.  
- Analyze the advantages of using Polynomial Regression for datasets with non-linear trends.  

## Results  

The scatter plots show that the **Linear Regression** model underfits the data due to its simplicity. In contrast, the **Polynomial Regression** model captures the complex non-linear relationships in the data, resulting in a better fit.  

## How to Run  

### Prerequisites  
Make sure you have Python 3.x installed and the following libraries:  
- `NumPy`  
- `Pandas`  
- `Matplotlib`  
- `Scikit-learn`  


## Visualizations
- **Scatter Plot with Linear Regression Line**: Demonstrates how Linear Regression underfits the dataset.  
- **Scatter Plot with Polynomial Regression Curve**: Shows how Polynomial Regression captures the non-linear trends effectively.
 
