# Heart_disease and Bulldozer price prediction

A learning  project on Machine Learning

In the heart disease project we are predicting whether a person has a heart disease or not on the basis of several features.

Used scikit-learn to build 3 machine learning models namely RandomforestClassifier,KNN neighbors and LinearRegression.

Also tried to improve the efficiency by hypertuning and then also evaluated the model.

For the evaluation metrics,i have calculated precision,recall,accuracy and F1 score.

In the Bulldozer prize prediction we have to predict the price of Bulldozers,we are given the previous years price of Bulldozers(training set), a validation set and a test set in which we have to predict the future prices of Bulldozers.

So in this problem ,I first preprocessed all data(filled all Nan values and converted the types of all objects to categories and suitably encoded all the entries to numerical)

Then i have used RandomForestRegressor()and also hypertuned the parameters using RandomizedSearchCV to find the optimal parameters.

Also for evaluation metric used Root mean square log error(RMSLE).

Also found out the important features which contributed the most to the predictions made by the model

Also saved predictions in predictions.csv which is also uploaded in this repository.

**IMPORTANT**
To be able to see the jupyter notebook all you need is a  conda environment and Pandas,Numpy,Matplotlib,Scikit-learn and Seaborn packages.
