# Python-ClimateWins-MachineLearning-Portfolio
## Project Summary
This project applies supervised machine learning techniques to historical European weather data to evaluate whether daily conditions can be classified as pleasant or unpleasant. Working as a data analyst for ClimateWins, a European nonprofit organization, the goal is to assess which machine learning models are most effective for predicting weather patterns and supporting long term climate preparedness planning.

## Key Questions
1. How is machine learning used and is it applicable to long term weather data analysis? 
2. Can supervised learning models accurately predict whether a day will be pleasant or unfavorable? 
3. What have been the historical maximum and minimum temperature trends across stations? 
4. Which supervised learning algorithms provide the most reliable classification performance?
5. Are there ethical risks associated with applying machine learning to climate prediction? 

## Folders

Description of folder contents are as follows:
* 01 Project Management: Project brief 
* 02 Data Sets: Original Data: Raw historical weather datasets
* 03 Scripts: Jupyter notebooks containing preprocessing, scaling, model training and evaluation.
* 04 Sent to Client: Final Presentations and summary of findings.

## Code Overview

All analysis was conducted in Python using Jupyter notebooks.
The following libraries were used:

* Pandas: For data manipulation and cleaning
* NumPy: For numerical operations
* Seaborn: For statistical visualization
* Matplotlib: For plotting and visual outputs
* OS:  For file management
* Operator: For comparison operations
* SciPy: For scientific computing
* Scikit-learn: For machine learning modeling and evaluation, including:
KNeighborsClassifier
DecisionTreeClassifier
MLPClassifier
MultiOutputClassifier
StandardScaler
train_test_split
cross_val_score
accuracy_score
confusion_matrix
multilabel_confusion_matrix
ConfusionMatrixDisplay
metrics module

## Models Evaluated
* K-Nearest Neighbors
* Decision Tree
* Neural Network (MLP Classifier)
Models were evaluated using accuracy scores, confusion matrices and cross validation to compare classification performance across stations.

## Ethical Considerations
Machine learning systems can introduce bias, overfitting and interpretability challenges. Because predictive climate modeling may influence planning and preparedness decisions, validation and transparency are critical 


## About
This project demonstrates an end to end supervised machine learning workflow including data preparation, scaling, model comparison, performance evaluation and strategic interpretation. The objective is to determine which predictive tools are most appropriate for classifying and forecasting European weather conditions.
