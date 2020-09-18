# Kaggle-Flightdelay-Proj1
Flight Delay Prediction
**DESCRIPTION**

**Problem Statement**

This is the flight delay prediction for the month of January. 

This data is collected from the Bureau of Transportation Statistics, Govt. of the USA. This data is open-sourced under U.S. Govt. Works. This dataset contains all the flights in the month of January 2019 and January 2020. There are more than 400,000 flights in the month of January itself throughout the United States. 

This data could well be used to predict the flight delay at the destination airport specifically for the month of January in upcoming years as the data is for January only.

This file contains all the flights starting from 1st January 2019 till 31st January 2019. There are around 400,000 rows in this file and 21 feature columns indicating the features of the flight including information about origin airport, destination airport, airplane information, departure time and arrival time.




Following Approaches were used
    1. Data Wrangling and  Data Visualization to remove the redundant features
    3. Feature engineering(Correlation and Chisquare Test for Categorical Features)
    4. Stratified K-Fold Cross Validation
    5. Oversampling Technique
    6. Model Training using Logistic Regression, Decesion Tree, RandomForest, XGBoost Classifiers, Neural Nets

SUMMARY and CONCLUSION:
    1. 10 Fold Cross validation results suggested that there is not much of performance difference between 
       traditional models like Logistic Regression, Decesion Tree , Random Forest and XG Boost. In fact Logistic
       Regression performance was better than others
    2. There is not much of performance difference between Imbalance and Balance dataset.  
