# DataHack_IITG
 Goal is to predict how likely individuals are to receive their xyz and seasonal flu vaccines. Specifically, will be predicting two probabilities: one for xyz_vaccine and one for seasonal_vaccine.
 In this project, we predicted the likelihood of respondents taking the xyz and seasonal vaccines using logistic regression models. We began by loading the datasets and cleaning the data by removing rows with missing target values. Next, we separated the target variables from the features and dropped unnecessary columns. We handled missing values with the SimpleImputer and encoded categorical variables using OneHotEncoder. Numerical features were standardized with StandardScaler, and we combined the processed features into a single dataset. Logistic regression models were trained on the preprocessed data, and we evaluated their performance using AUC-ROC scores. Finally, we generated predictions for the test set and saved the results to a CSV file for submission.






