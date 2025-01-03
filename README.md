Heart diseases – using machine learning techniques

Description:
In this repository, you will find code for machine learning to predict heart disease. It loads data, cleans it, and starts data analysis and machine analysis by testing several classifiers one of which is the better classifier. The following data preprocessing methods are used; normalization, one hot encoder, and outliers removal. The results of the models are measured and compared using accuracy measures, and figures are given to help in understanding the outcome further.

Key Features:

Preprocessing:
The previously described processes of normalization were aimed at returning a result to the domain of the features.
Used for converting categorical data into numerical data the one-hot encoding method is best suited.
Outlier detection using the IQR method
Statistical Analysis:
We use T-tests for all the numerical features of the data.
While numerical features were tested for normality and equal variance, categorical features were tested using chi-square tests.
Model Evaluation:
Models compared out of LazyPredict
Structured precise performance comparison between LGBMClassifier, XGBoost, RandomForest, and more
Visualization:
Feature p-value plots
Model performance visualization
Best Model Selection:
Performance comparison for the training, validating, and testing purposes.
