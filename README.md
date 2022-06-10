# Cardiovascular-Risk-Prediction

## Classification Model for Predicting Cardiovascular Risk

![3](https://user-images.githubusercontent.com/89520031/172639887-2b067589-1023-412f-b3ea-40e88d1ce2c2.jpg)

# Dataset Explanation:

The dataset was actually a collection of 3,390 experiences about patients with or without cardiovascular disease with 17 features or dimensions.

# Project Summary:

The task was to explore and analyze the data and to build a classification model for 10 Years Coronary Heart Disease prediction.

Handled all null values in seven columns of the dataset with imputation and thus there was no loss of data.

Employed some of the most widely used classification algorithms for this project namely;

**1.	Random Forest**

**2.	KNN**

**3.	SVC**

Final model was KNN classifier selected from Random Forest, KNN and SVC for predicting 10 Years Coronary heart disease, having low variance in prediction ( test accuracy is 84%, variance 1% ), good f1_score (0.48) , and good ROC_AUC score (0.51) among all three models. Used RandomizedSearchCV for hyperparameter tuning.

## Potential Impact and Future Scope:

The features of the dataset are regarding personal habits and a few general health parameters which are less costly to record. Thus the model can be utilized for early prediction of the risk of coronary heart disease in a cost-effective way.

According to WHO report, cardiovascular diseases are causing nearly about 32% of all global deaths. If the building line of this project is applied to big data, then the model will surely become impactful in reducing the deaths caused by cardiovascular diseases.
