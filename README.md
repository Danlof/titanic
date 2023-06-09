# titanic

This project is from the famous titanic competition from Kaggle, where one is intended to make predictions for who survived the shipwreck considering factors like: gender, parents, partners and children,age etc.
With python I  did data exploration found missing values , categorical attributes , using seaborn I plotted histograms to show correlation and significance of the features.
During data preprocessing I cleaned the data by dropping columns that were missing too many values and used regression imputation to impute the missing values for the age attribute.
Lastly I checked a few models: Support vector classifier(svc),Random forests,logistic regression ,xgboost and adaboost fine tuned their parameters for better accuracy. Later on ensembled them for my final survival prediction where I was among the top 10% in the competition
