# kaggle_forest_cover
Kaggle competition predicting forest cover type.

## My Pipeline
The dataset was complete, there were no missing values. The Wilderness Area and Soil Type features were already one-hot encoded. After exploring the data I began modelling and doing a bit of hyperparameter tuning. 

The best performing models were random forest, XGBClassifier and extra tree classifier (extremely random trees). An ensemble of all three models did not improve accuracy. I settled on the extra tree classifier as it was superior to all the other models I tested. To further enhance performance, I created higher order features and found that second degree features slightly improved accuracy.

### Results
The best performing model was an extra trees classifier with 1725 trees which produced an accuracy score of 0.77892. This score would have earned 365th place amongst 1644 submissions on the closed competition had it been active.
