data_preprocess_withdataDrop.ipynb: the 1st version of data preprocess, in which I drop the 3 null row(1 null 'fare' and 2 null 'embarked')
Data_preprocess.ipynb: the 2nd version of data preprocess, in which I fill the null value with the medians. However, it shows lower accuracy compared with the 1st version. But I have to remain the data in order to submit the final test ouput to https://www.kaggle.com/competitions/titanic/submissions to evaluate my prediction.
Titanic.ipynb: Using 3 classifers to train model and test, in which I remain the Chinese markdown.
Train&Test.ipynb: Using 3 classifers to train model and test, in which I replace the Chinese markdown with English.

randomforest_predictions.csv: Output file predicted using randomforest classifer from Train&Test.ipynb. 
xgboost_predictions.csv: Output file predicted using xgboost classifer from Train&Test.ipynb. 
best_model.xgb: best saved model to predict the missing ages from Data_preprocess.ipynb.
survived.csv: recording the attribute 'Survived' from both train.csv and test.csv 

To run the project, you can just run Data_preprocess.ipynb and Train&Test.ipynb in sequence.
