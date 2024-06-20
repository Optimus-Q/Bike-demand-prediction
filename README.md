# Project: Bike-demand-prediction

#### Workflow
![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/f6e60d91-63a9-40c4-897e-331058c65921)

This project utilizes the Seoul bike demand dataset to predict demand using machine learning techniques and conducts statistical analysis to detect anomalies and identify trends.

### Data-Pre-processing:
Initial data pre-processing involved removing unwanted information such as missing values and NaNs. Missing values were imputed using appropriate methods.

### Statistical Analysis:
Various statistical analyses were conducted, including univariate and bivariate analyses on features to identify outliers. Histograms and boxplots were employed to visualize the distribution of datasets and detect outliers. Correlation analysis assessed the relationships between features, examining effects like heteroscedasticity. Variable inflation factor analysis identified multicollinearity issues for regression.

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/5c356bdb-4c34-4733-9bb6-8cc1374f1f9a)

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/2fbada4c-3434-4039-a8f5-f0e5921b82a9)

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/a8ca78a9-0719-4afa-a13f-ca60d23f92db)

### Modeling:
The dataset was split into an 80/20 ratio for training and testing purposes. Kernel Ridge Regression and Support Vector Regression were utilized for modeling bike demand prediction. Models underwent optimization through K-Fold cross-validation and grid search parameter tuning.

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/126772c2-f996-41f1-9d95-313ece6246bd)

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/82e1ff33-7c77-4c61-b3c5-40387cae0f58)

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/4bc2cf1a-a809-431b-84aa-77135b9f253a)

![image](https://github.com/Optimus-Q/Bike-demand-prediction/assets/46313772/66c840a0-d63a-488c-8356-f6d82fddb7ff)


