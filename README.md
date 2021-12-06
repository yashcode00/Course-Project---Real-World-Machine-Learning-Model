# Real World Machine Learning Model 
*Objectives*

>**_Perform data cleaning & feature engineering_**

>**_Training, compare & tune multiple models_**

## Project Details 
**Benchmark Bond Trade Price Challenge**
_Kaggle Link: [Bond Price Prediction](https://www.kaggle.com/c/benchmark-bond-trade-price-challenge)_

![alt text](https://img.etimg.com/thumb/msid-69920676,width-1070,height-580,imgsize-133370,overlay-etmarkets/photo.jpg )
The Benchmark Bond Trade Price Challenge is a competition to predict the next price that a US corporate bond might trade at. Contestants are given information on the bond including current coupon, time to maturity and a reference price computed by Benchmark Solutions.  Details of the previous 10 trades are also provided.  

## Methods Used
1. Modules used in python
   - pandas
   - os
   - opendatasets
   - numpy
   - matplotlib
   - sklearn
     - Min-Max scaler (*for splitting into train,valid and test sets*)
     - PCA (*for data reduction*)
     - Linear Regression
     - RandomForestRegressor (*for random forest method*)
   - xgboost 
     - XGBRegressor  (*for GBM*)
 2. Models trained
    - Linear Regression ( *Best RMSE loss: 5.0800902042018965 on Validation Set* )
    - Random Forest ( *Best RMSE loss: 2.298014466986494 on Validation Set*)
    - Gradient Boosting Machines, GBM ( *Best RMSE loss: 2.1976847276813976 on Validation Set*)
 3. Along with fitting and predicting using the different models, Hyperparameter tuning has also been done to obtain best results.

Thanks
   
