# ML_Lab_Regression
Contain code for the Machine Learning Module Lab - Regression
<br>
Kaggle Competition Link : https://www.kaggle.com/competitions/playground-series-s3e11/submissions
<br>
In this approach, for the feature selection correlation coefficients are calculated and the features with 3 lowest scores are dropped. Using the pycaret library the available regression models are trained ,evaluated and ranked based on cross-validation. XGBoost, LightGBM and Gradient boosted tree regressors are selected and then stacked to created the final model.
