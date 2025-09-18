# Machine learning ensembled methods to predicting houses prices through Scikit-Learn Python library.
Here we used three different ensembled methods to predicting houses prices according to 78 different features. Were also used two datasets (train.csv and test.csv) which contain train data and test data respectively and each one has a dataset surrounding 1460 elements of length. Both dataset were extracted from Kaggle website https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data?select=sample_submission.csv .
Firstly, was made an exploratory data analysis, checking statistical information of the dataset and filling each missing value. In this case several NaN values were relevant and provide information about the home status, then were not dropped. Data was also preprocessed using categorical methods to codify the strings values to numerical values which can be used in our machine learning models.
Secondly data was modeled using three different machine learning models, Random Forest Regressor (RFR), Gradient Boosting Regressor (GBR) and Xtreme Gradient Boosting Regressor (XGBR). Each method was initially trained using the same random hyperparameters and then were improved using the GridSearch method of Scikit-Learn Python library, which found the best hyperparameters (of an inserted list of them) that get a better fit on the train data. Then we made the cross-validation process trying to verify if the model was overfitting the dataset using 5 folds per method. In this case we found similar performance in the three methods, getting an score in cross-validation surrounding 85%.
Finally were made the predictions of house prices on the test dataset.

# Quick overview about the used machine learning models.
1. Random Forest Regressor:
2. Gradient Boosting Regressor:
3. Xtreme Gradient Boosting Regressor:

