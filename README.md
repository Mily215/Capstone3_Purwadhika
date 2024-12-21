# Final Capstone Project - Module 3

## Overview
This repository contains the Jupyter Notebook for a project involving a dataset analysis to derive meaningful insights and application of machine learning techniques to solve a defined problem.

## Contents of the Repository
- **Notebook**: `Final_Capstone_Module_3_Hermily.ipynb`
  - Contains all steps of the project, from data loading and cleaning to model building and evaluation.

## Structure of the Notebook

### 1. Introduction
The notebook starts by outlining the project's context, objectives, and problem statement.

### 2. Data Loading
- The dataset is imported using `pandas`, and its structure is examined to understand columns, data types, and dimensions.
- **Data Source**: The dataset was obtained from Kaggle, which provides reliable and comprehensive data for analysis. The choice of this dataset was driven by its relevance to the problem statement and its quality, ensuring a meaningful machine learning application.
- Link to Data Source: https://www.kaggle.com/datasets/samuelsemaya/e-commerce-customer-churn

### 3. Data Cleaning and Preprocessing
- Missing values are handled appropriately.
- Data transformations such as encoding and scaling are performed to prepare the data for modeling.
- **Encoding Used**: Categorical variables were encoded using methods like One-Hot Encoding and Label Encoding, depending on the nature of the variable and its cardinality.
- **Balancing Methods**: To address class imbalance in the dataset, techniques such as SMOTE (Synthetic Minority Oversampling Technique) were employed, ensuring fair model performance across all classes.

### 4. Exploratory Data Analysis (EDA)
- Graphical and statistical methods are employed to uncover trends, patterns, and correlations within the data.
- Visualizations are created using libraries like `matplotlib` and `seaborn`.

### 5. Model Building and Evaluation
- Machine learning models are developed using algorithms suitable for the problem at hand.
- **Reasons for Model Choices**: The choice of models was based on the problem type and dataset characteristics. For instance:
  - Logistic Regression was used for its interpretability and baseline performance in classification tasks.
  - Random Forest was selected for its ability to handle non-linear relationships and its robustness to overfitting.
  - Support Vector Machines were explored for their effectiveness in high-dimensional spaces.
- Evaluation metrics such as accuracy, precision, and recall are calculated to assess model performance.

### 6. Recommendations and Impact
#### Recommendations:
- **Focus on Key Features**: Prioritize features like **Tenure**, **CashbackAmount**, and **Complain history**, as they are crucial for predicting customer behavior.
- **Model Integration**: Use the trained model with a recall score of **0.8033** for decision-making, especially to identify high-risk customers.
- **Feature Refinement**: Enhance less impactful features like **Marital Status** and **Preferred Order Categories** to improve model performance.
- **Automation**: Automate predictions to improve efficiency and accuracy in operations.

#### Effect and Difference of Using the Model:
| **Using the Model**                                      | **Not Using the Model**                                       |
|----------------------------------------------------------|--------------------------------------------------------------|
| Data-driven, accurate decisions.                         | Reliant on intuition, less accurate.                          |
| Automates tasks, saving time and resources.              | Manual processes, slower and error-prone.                     |
| Scales easily with large datasets.                       | Struggles to handle large data efficiently.                   |
| Provides actionable insights with high accuracy.         | Lacks clear insights, leading to inefficiencies.              |

Using the model optimizes decision-making by automating tasks, ensuring accuracy, and efficiently handling large datasets. Without it, decisions are slower, less accurate, and harder to scale.

## Requirements
The notebook uses the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Results
The results of the project include:
- Cleaned and preprocessed data ready for modeling.
- Detailed visualizations to support the exploratory analysis.
- Trained machine learning models with performance metrics.
- Final conclusions derived from the analysis.

