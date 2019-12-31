Dear Prof Sourav, 

We follow a divide-and-conquer approach to the project. Each member took an objective and work on it separately and then combine the results together after we finished our analysis, much like an Ensemble. 
Therefore our team don't have a main.ipynb file where we put together our different analysis. Rather it will be over the place and the results combined in our pptx file. 

Below is the function of each ipynb files:
1. Basic Data Exploration - 
2. Regression on Happy (Root) - contains all Regression Models and the performance. 
3. Clustering_on_2017_Data - contains all clustering methods.
4. Population bubble scatter plot - contains plotly visualization of clusters.
5. Anomaly #1 - are there similar countries but differ starkly in Happiness?
6. Anomaly #2 - are there countries that score very well on the main variables but are not happy?
7. 1817 Sensitivity Analysis - a very simple analysis on which variable change will generate largest change in Life Ladder. 

Each ipynb file works on the following excel file
1. Basic Data Exploration - WHR2018Chapter2OnlineData.xls 
2. Regression on Happy (Root) - Merged Regression Data.xls 
3. Cluster on 2017_Data - Ordered Happy 2017.xls 
4. Population bubble scatter plot - WHR2018Chapter2OnlineData_withpopulation.xls; WHR2018Chapter2OnlineDataClusters15-18.xls
5. Anomaly #1 - MeanAbsoluteDifference among countries.xls; Ordered Happy 2018.xls
6. Anomaly #2 - Ordered happy 2018.xls
7. 1817 Sensitivity Analysis - 1817 Sensitivity Analysis.xlsx

Python Libraries we have used
1. Plotly, pprint
2. Numpy, Pandas, Pyplot, Seaborn (+xldr for excel handling)
3. Sklearn model_selection: train_test_split,RandomizedSearchCV,GridSearchCV 
4. Sklearn feature_selection: SelectFromModel
5. Sklearn metrics 
6. Sklearn linear_model: LinearRegression
7. Sklearn ensemble: RandomForestRegressor
8. XGBRegressor from xgboost
9. Tensorflow and Keras's Sequential, Dense, Activation, Flatten, LeakyRelU
10. Sklearn svm: svr
11. Sklearn cluster: DBSCAN,Kmeans; mixture: GaussianMixture

We would love to hear any comments/feedbacks for our analysis! 
Thank you for making 1015 enjoyable and exciting! We have learnt alot about ML. 

- from Nicholas, Viet and John.