SUMMARY:
Objective:
Predict will the customer leave the bank or stay?

Appraoch:
Loaded data, cleaned data, and visualized the data.
Visualized data for summarizing, and encoded nominal variables using label encoder and one-hot encoder.
Splitted data into train and test with ratio of 80%(train) and 20%(test).
Loaded and fitted RandomForestClassofoer model on the data.
Predicted the target/dependent variable which is "Excited".
Calculated accuracy score and confusion matrix. 
Visualized confusion matrix using heatmap to observe efficient relation between actual and predicted variable.
Implemented feature_importance function to observe how much each variable is contributing in the prediction.

Insights & Result:
Based on this model prediction,
Almost 6149 users are excited being a user of the bank.
Only 724 users want to leave the bank.
