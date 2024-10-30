# **House Prices Regression Project**
The goal of this project is to predict house prices using various machine learning algorithms. By analyzing different features of houses, we aim to build a predictive model that estimates house prices based on historical data.
 # **Project Aims** 
 ### 1. Data import:
* Download the house price dataset from Kaggle.
* Import and clean data by handling any missing or incorrect values ​​and dealing with outliers.

 ### 2. Data Analysis:
* Explore data and analyze different features.
* Create visualizations to highlight the relationships between different features and house prices.

### 3. Model Building: 
* Try different algorithms like: LinearRegression, polynomial regression, Ridge Regression, Lasso Regression, Random forest, Decision tree.
* Train the model using the data and evaluate its performance using metrics like: R2-Score, MSE, RMSE, MAE, MAPE.

### 4. Model Improvement:
* Improve the model using techniques like cross-validation and feature engineering, and outlier removal.
* Compare different models and select the one that provides the best accuracy.
 
# **Data Set** 
The dataset for this project can be found [here](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/code)

# **Results**
Below is a brief description of the results of the models used 

| Evaloution |Linear Regression | polynomial Regression | Ride Regression | Lasso Regression | Decision tree Regression | Random forest Regression |
|----------|----------|----------|----------|----------|----------|----------|
| R2-Score Train | 0.66 | 0.72 | 0.69 | 0.73 |0.73 | 0.88 |
| R2-Score Test | 0.62  | 0.61 | 0.62 | 0.60| 0.45 | 0.56 |
| MSE Train |1018773982579.8103 | 837439865414.3219 | 938352139392.1793 | 811764892530.3756 | 825392019680.1193 |341794688784.1196 | 
| MSE Test | 1796962748266.6726| 1824469643135.5| 1781266981593.312| 1900768144848.6328 |2614251031337.5366 |2081203581614.247 | 
| RMSE Train | 1009343.34 | 915117.40 | 968685.7794931127 | 900979.9623356647 | 	908510.880331171 | 584632.0969499705| 
| RMSE Test | 1340508.39 |	1350729.30 | 1334641.143376493 |1378683.482474724| 1616864.5680258865|1442637.7166892064|
| MAE Train | 750728.3 | 686198.0400448643 | 717743.1156300461 | 669618.7713911007 | 688614.147712783 |437748.0301181934 |
| MAE Test | 	925856.3 | 	926982.3880949767 | 918681.7804304013 | 919306.2401518777 | 1066740.1631991663 | 972232.389903801 |
| MAPE Train | 	16.9% | 16.13%|16.55% | 15.53% |16.29% | 10.25%| 
| MAPE Test | 19.7% | 19.77% | 19.51% | 18.90%| 22.13%| 20.70%|

# **Summary of the results obtained**

Models  | Conclusion
-------------------|------------------
**Linear Regression**|**Linear regression shows moderate performance with a noticeable gap between training and testing results, indicating some overfitting.**
|
**Polynomial Regression**|**Polynomial regression shows an improvement in training performance but overfits the training data, leading to lower performance on test data.**
|
**Ridge Regression** |**Ridge regression shows a balanced performance between training and testing, indicating a good generalization capability.**
|
**Lasso Regression**|**Lasso regression performs well on training data but shows some overfitting on test data.**
|
**Decision Tree** |**Decision tree shows significant overfitting, with much better performance on training data compared to test data.**
|
**Random Forest** |**Random forest shows excellent performance on training data but overfits the data, leading to a drop in performance on test data.**

# ** Overall Conclusion ** :
Ridge regression and lasso regression show the most balanced performance between training and testing data, indicating good generalization capabilities. While random forest performs well on training data, it suffers from significant overfitting.


 
