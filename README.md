# Heart disease and Bulldozer price prediction-

A learning  project on Machine Learning

1)In the heart disease project we are predicting whether a person has a heart disease or not on the basis of several features.

2)Used scikit-learn to build 3 machine learning models namely RandomforestClassifier,KNN neighbors and LinearRegression.

3)Also tried to improve the efficiency by hypertuning and then also evaluated the model.

4)For the evaluation metrics,i have calculated precision,recall,accuracy and F1 score.

5)In the Bulldozer prize prediction we have to predict the price of Bulldozers,we are given the previous years price of Bulldozers(training set), a validation set and a test set in which we have to predict the future prices of Bulldozers.

6)So in this problem ,I first preprocessed all data(filled all Nan values and converted the types of all objects to categories and suitably encoded all the entries to numerical)

7)Then i have used RandomForestRegressor()and also hypertuned the parameters using RandomizedSearchCV to find the optimal parameters.

8)Also for evaluation metric used Root mean square log error(RMSLE).

9)Also found out the important features which contributed the most to the predictions made by the model

10)Also saved predictions in predictions.csv which is also uploaded in this repository.

**IMPORTANT**
To be able to see the jupyter notebook all you need is a  conda environment and Pandas,Numpy,Matplotlib,Scikit-learn and Seaborn packages.
