# kaggle_forest_cover
Kaggle competition predicting forest cover type.

## My Pipeline
The dataset was complete, there were no missing values. The Wilderness Area and Soil Type features were already one-hot encoded. After some intial EDA I began modelling and doing a bit of hyperparameter tuning. I noticed that the best performing models were random forest and XGBClassifier. An ensemble of both tuned models produced even more accurate results. 
