## Insurance Premium Prediction

By Alonge Daniel

**GitHub**: [Alonge 9500](https://github.com/Alonge9500)  
**LinkedIn**: [Alonge Daniel](https://www.linkedin.com/in/alonge-daniel-27b4b4139/)  
**Email**: [Alonge Daniel](mailto:alongedaniel19@gmail.com)

---

## Overview

This repository contains code for predicting insurance premiums using machine learning models. The project involves data analysis, preprocessing, model building, and hyperparameter tuning to achieve the best possible performance.

## Problem Statement

The objective is to predict the insurance premium for customers based on various factors such as age, sex, BMI, number of children, smoking status, and region. Accurate premium predictions help insurance companies price policies appropriately and manage risk.

## Dataset

The dataset used for this project contains the following columns:

- **age**: Customer's age
- **sex**: Customer's gender (male/female)
- **bmi**: Body mass index (BMI) of the customer
- **children**: Number of children the customer has
- **smoker**: Indicates if the customer is a smoker (yes/no)
- **region**: The region where the customer resides
- **expenses**: The actual medical expenses incurred by the customer

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.6+
- Jupyter Notebook

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Alonge9500/Insurance-Premium-Prediction.git

### Project Structure
* insurance_premium_prediction.ipynb: Jupyter notebook containing the entire codebase for data analysis, preprocessing, and model training.
* insurance_code.log: Log file recording the steps and status of various processes.
* README.md: Project overview and instructions.

### Data Analysis
The notebook includes Exploratory Data Analysis (EDA) with:

* Univariate Analysis: Understanding the distribution of individual features.
* Bivariate Analysis: Exploring relationships between two variables.
* Multivariate Analysis: Examining interactions among multiple variables.

#### Data Preprocessing
Preprocessing steps include:

* Handling missing values.
* Encoding categorical variables using OneHotEncoder and LabelEncoder.
* Scaling numerical features using StandardScaler.
* Splitting the data into training and testing sets.
* Model Training and Evaluation
* The following models were trained on the preprocessed data:

#### Models
- Random Forest Regressor
- XGBoost Regressor
- Linear Regression
The models were evaluated using metrics like R2 Score and RMSE. The Random Forest Regressor performed best with an R2 Score of approximately 0.85 before hyperparameter tuning.

#### Hyperparameter Tuning
Grid Search was used to tune hyperparameters for both Random Forest and XGBoost Regressors. The XGBoost Regressor, after tuning, yielded the best performance with an R2 Score of 0.8601 and an RMSE of 4441.64.

#### Conclusion
The project successfully demonstrates the prediction of insurance premiums using machine learning models. The tuned XGBoost Regressor provided the best results. This project can be further extended by experimenting with more advanced models and techniques.

Feedback
I would appreciate any comments or suggestions on this work. Feel free to reach out via GitHub, LinkedIn, or email.
