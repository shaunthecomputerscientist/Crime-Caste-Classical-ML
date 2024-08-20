# Crime Data Analysis Project

## Introduction

This project aims to analyze crime data through various stages of data processing, feature engineering, and model building. The analysis focuses on understanding the relationships between different features, identifying patterns, and building predictive models to classify crimes. By utilizing advanced techniques like SMOTE, ADASYN, and various machine learning algorithms, this project provides a comprehensive approach to crime data analysis.

## Project Overview

This project includes the following key steps:
1. **Data Loading and Initial Cleaning**: The raw data is loaded, combined, and cleaned to prepare it for further analysis.
2. **Feature Selection and Rejection**: Relevant features are selected based on exploratory data analysis and domain knowledge.
3. **Exploratory Data Analysis (EDA)**: Detailed analysis to understand the distribution and patterns within the data.
4. **Feature Engineering**: Creating new features that improve the model's predictive power.
5. **Handling Class Imbalance and dimension reduction** : Uses kmeans undersampler and pca.
6. **Model Building**: Implementing and testing various machine learning algorithms to classify crimes based on the features.

## Table of Contents

1. **Columns and Their Meaning**
    - Explanation of the dataset's columns and what they represent.

2. **Data Loading and Combining**
    - Loading the dataset and combining different data sources.

3. **Pre Data Cleaning**
    - Initial steps in preparing the data for analysis.

4. **Feature Rejection/Selection and Data Cleaning**
    - **Initial Column Drop**: Removing irrelevant columns.
    - **Exploratory Data Analysis (Crime Cast)**: Analyzing data to understand patterns.

5. **Checkpoint 0**
    - Saving the progress and ensuring data integrity.

6. **Latitude and Longitude Analysis**
    - Analyzing the geographical aspects of the data.

7. **Time Occurred, AREA ID, AREA NAME**
    - Insights into the temporal and spatial distribution of crimes.

8. **Checkpoint 1**
    - A second checkpoint to ensure analysis consistency.

9. **Premise Analysis with Other Important Features**
    - Investigating crimes based on premises and other features.

10. **Visualizing Type of Crimes in Premises**
    - **Type 1 and 2 Crimes in Every Premise with Highest Frequency**: Visual analysis of common crimes in different premises.
    - **SMOTE (Synthetic Minority Over Sampling Technique)**: Handling imbalanced data.
    - **Adaptive Synthetic Sampling (ADASYN)**: Another technique for addressing imbalanced datasets.
    - **Random Oversampling (Naive Approach)**: Basic oversampling method.

11. **Status Description**
    - Analysis of the status of different crimes.

12. **Analyzing Victim Age, Victim Sex, Victim Ethnicity**
    - **Now We Should See What Type of Crime Each Age Group is Involved in**: Age-based crime analysis.

13. **Demographics**
    - Studying the demographic distribution of crime.

14. **Checkpoint 2**
    - Another checkpoint for data analysis.

15. **Date Time Columns**
    - **All Months Almost Have Equal Distribution of Crimes**: Temporal distribution analysis.
    - **Inference: Crimes are Rampant Throughout the Year**: Key insights from temporal data.

16. **Inference**
    - General conclusions drawn from the analysis.

17. **Modus Operandi & Reporting District No.**
    - Detailed analysis based on the modus operandi and reporting districts.

18. **More into Location**
    - Further investigation into the geographical aspects of the data.

19. **Final Feature Rejection**
    - Final steps in feature selection before modeling.

20. **Feature Engineering**
    - Creating new features for better model performance.

21. **Checkpoint 3**
    - Final checkpoint before model building.

22. **Encoding and Scaling**
    - **Undersampling**: Handling class imbalance through undersampling.

23. **KMEANS Clustering**
    - **Problem of Naive Initialization: Centroid Initialization**: Challenges in KMeans clustering.
    - **Encoding**: Preparing data for clustering.
    - **Scaling and Normalizing**: Data preprocessing for clustering.

24. **PCA**
    - **Theory**: Introduction to Principal Component Analysis (PCA).

25. **Data Allocation**
    - Splitting the data for training and testing.

26. **Generic Model Interface**
    - Creating a standardized interface for model building.

27. **Models**
    - **Logistic Regression for Multi-Class Classification**
    - **Theory**

28. **XGBOOST (Boosting Category)**
    - Building a model using XGBoost for classification.

29. **Random Forests (Bagging Category)**
    - Using Random Forests for crime classification.

## Conclusion

This project serves as a comprehensive guide to analyzing crime data using advanced data science techniques. By following the steps outlined in this project, you will gain a deep understanding of how to clean, analyze, and model complex datasets to draw meaningful insights and make informed predictions.

## How to Run the Project

1. **Clone the repository**: 
   ```bash
   git clone https://github.com/shaunthecomputerscientist/Crime-Caste-Classical-ML
