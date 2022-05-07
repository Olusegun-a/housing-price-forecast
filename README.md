# housing-price-forecast

The goal of this machine learning research is to create a prediction model for Perth home prices.
The linear regression model will be developed using data scraped from http://house.speakingsame.com/, which includes data from 322 Perth suburbs, yielding an average of roughly 100 rows per suburb (https://www.kaggle.com/datasets/syuzai/perth-house-prices?resource=download).
Also, a python flask server will save the model to serve HTTP requests. A website is constructed in HTML, CSS, and JavaScript that allows the user to enter parameters and then calls the Python Flask server to get the estimated pricing. 

Components of data mining covers in the project.

Data load and cleaning.
Outlier detection and removal.
Feature engineering.
Dimensionality reduction.
Gridsearchcv for hyperparameter tunning.
K fold cross validation, etc. 
