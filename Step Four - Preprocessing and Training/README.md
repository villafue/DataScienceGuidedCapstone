Best Codes and Notes Within Notebook:

1. Creating x,y train,test sets as dataframes and saving index and column names for analysis
2. DummyRegressor as baseline for analysis (using mean)
3. Simple imputations using mean,median on x-train
4. PIPELINES! for increased speed in modeling
5. SelectKbest and f_regression to find best features using r squared score.
6. Cross Validation with pipeline
7. GridSearch to find best Hyperparameters with pipeline and cross validation.
  8. List comprehension to iterate through each column (feature)
9. Errorbar plot for use with SelectKBest (number of features) for Linear Regression using mean and STD (above and below mean) as error bar
10. best_estimator, best_params_ for results of gridsearch, named_steps to pick out what we're looking for (similar for to pandas .loc)
11. RANDOM FOREST Regressor
  12. Gridsearch Hyperparameters using logspace (list comprehension again) which denotes the number of trees (similar to select # [k] of best features above)
  13. option of scaling or not as a gridsearch parameter
  14. imputing strategy of mean or median as parameter
  15. Plotting order of best features
16. comparing linear regression model and random forest regressor using cross validate and neg MAE. 
17. Plotting whether or not to ask business to get more data using learning_curve.
  18. Plot uses error bars and r squared score. We used it on first boring linear regression pipe.
19. print('\n', '-' * 20) [Place inbetween two print statements to have line spaces inbetween]. It looks nicer
