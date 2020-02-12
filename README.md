# Prediction of Nitrogen Oxides level in Air Quality
There are many poisonus gases such as CO, NOx, titania, sulfur dioxide, nitrous oxides, methane etc in the polluted air which is harmful not to only humans but also animals and plan lives based on this refereces Air Pollution Effects on health.

This project aims to predict the level of Nitrogen Oxides in Air. The data was acquired from the UCI Machine Learning Repository. You can find all the information about Dataset from here Air Quality Dataset. It's hourly data.

Built a prediction models using various Regression Algorithms with data cleaning, and exploratory data analysis(EDA) with visualization.

Data Cleaning: There were some values -200 which means the machine didn't dictate for some reason. Thus, it was replaced with average values. There were very few missing values, remove it.

Data Analysis: The below statements are from the EDA part in the jupyter notebook.

Gases like CO, NOx, titania, and Benzene are increased in the air over time.
The frequency of Oxides in Nitrogen is increasing.
During the day Nitrogen Oxides' level is high compared to night.

Machine Learning: Used Linear Regression, K-nearest Neighbour(KNN), Decision Tree, Random Forest, SVM Regressor, XGBoost Algorithms for making prediction models. 
