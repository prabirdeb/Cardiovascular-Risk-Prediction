# Cardiovascular-Risk-Prediction-Prabir-Debnath

## Classification Model for Predicting Cardiovascular Risk

![3](https://user-images.githubusercontent.com/89520031/172639887-2b067589-1023-412f-b3ea-40e88d1ce2c2.jpg)

# Summary:

The task was to explore and analyze the data and to build a classification model for 10 Years Coronary Heart Disease prediction.
Handled all null values in seven columns of the dataset with imputation and thus there was no loss of data.
Employed some of the most widely used classification algorithms for this project namely;

### 1.	Random Forest
### 2.	KNN
### 3.	SVC

Final model was KNN classifier selected from Random Forest, KNN and SVC for predicting 10 Years Coronary heart disease, having low variance in prediction ( test accuracy is 84%, variance 1% ), good f1_score (0.48) , and good ROC_AUC score (0.51) among all three models. Used RandomizedSearchCV for hyperparameter tuning.
