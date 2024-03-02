# Precision Care for the Unborn: A Fetal Health Study
!./images/logo.png
## Project Overview
This project involves the development of a machine learning system to support the diagnosis of fetal patients. The goal is to address the global challenge of reducing fetal mortality rates, particularly in developing countries.

## Data Analysis
The project begins with an initial exploratory data analysis to identify statistical features, leading to the An initial exploratory data analysis was conducted to identify statistical features. This led to the selection of suitable evaluation metrics for the project.

## Data Preprocessing
Various operations were implemented on the data to enhance the performance of the machine learning models. This included handling class imbalance with Synthetic Minority Over-sampling Technique (SMOTE) and Edited Nearest Neighbors (ENN), data scaling, outlier removal, and feature selection.

## Model Selection and Training
Multiple classification models were evaluated, including XGBoost Classifier, Logistic Regression, K-Neighbors Classifier, Random Forest Classifier, and Support Vector Machine. The hyperparameters of these models were optimized using GridSearchCV.

## Performance Metrics
The performance of the models was evaluated using the F1 Score and Matthews’s Correlation Coefficient. These metrics provided a comprehensive measure of the models’ performance, taking into account both false positives and false negatives.

## Results
The project achieved promising results in identifying diseased patients, which is crucial for a diagnostic support system. Although the reduction of features led to a slight deterioration in performance, the benefits of feature selection, such as enhanced interpretability and reduced measurement costs, were considered acceptable.


