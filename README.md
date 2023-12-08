# PortugueseBank

#### <center> <span style="font-size: 20px; background-color: pink; padding: 10px;">This is binary classification goal is to predict if the client will subscribe a bank term deposit
</span>


#### <span style="font-size: 20px; background-color: yellow; padding: 10px;">Dataset import</span>
-----------------------------------------------------------------------------------
-   During importing dataset all the features and value
    were not seprated then we use to sep parameter and we seprate the all features and their valueby using semicolin, also 
    dataet has some unknown value so using na_value parameter we represent in NaN value
------------------------------------------------------------------------------------------------------
#### <span style="font-size: 20px; background-color: orange; padding: 10px;">Basics check
- then we use to perform basics check during this process we see the dataset has some feature are numerical and categorical 
- Also we got some missing value in some column.</span>
------------------------------------------------------------------------------------------------------------
<span style="font-size: 20px; background-color: pink; padding: 10px;">EDA</span>
- OUr dataset is binary class so we performed univariate analysis and bivariate analysis, during this we use some plot like pie-chart and according to the feature we used graph.
- In univariate analysis first we performed analysis on numeical column one-by-one and we wrote insight. 
- In univariate analysis we used to perform two graph of every categorical column for more visulation.
- In bivariate analysis- first we used to perform graph on categorical data then numerical data we selected categorical and nuerical data using for loop then ploted graph after that we wrote insight bellow all graph.
--------------------------------------------------------------------------------------------------
#### <span style="font-size: 20px; background-color: orange; padding: 10px;">Data preprocessing</span>
- MISSING VALUE
    - During data preprocessing we found missing value in many column
    - for missing value we impute missing value manually using mode method, means in column which feature has highest count we assigned missing value into them.
- DUPLICATE VALUE
    - WE found duplicate value in then we droped them.
- OUTLIERS
    - During outliers checking we found outliers in some cloumn then by using IQR method we removed outliers of every column one-by-one.
- DATA CONVERSION
    - iN dataset some column was categorical feature then we assigned some value of every feature of categorica column
- NORMALIZATION CHECKING
    - WE use to check on numerical column of dataset that value of column is normalized or not then we found all column was almost normalize
 ------------------------------------------------------------------------------
<span style="font-size: 20px; background-color: blue; padding: 10px;">Feature Selection</span>
----------------------------------------------------------------------------------------------
 During feature selection we used to check coorelation on input variable only and we found the highly coorelated column then we dropped that column. Then we used train test split.

<span style="font-size: 20px; background-color: green; padding: 10px;">Balancing data</span>
--------------------------------------------------------------------------------------------------
  Target variable was not balanced so we used SMOTE for balancing the data

--------------------------------------------------------------------------------------
    
<span style="font-size: 20px; background-color: gray; padding: 10px;">Model creation</span>

  we perform many models .


**The Output feature colum heve binary class feature so for this reason we have chosen this problem statement as binary class classification and then we use diffrent Algorithm to check the performance of the diffrent Algorithm this can be checked using f1_score and compare it down by with diffrent model accracy , so whichever model showing highest accuracy score w have chosen that model predction.**

### I used diffrent ML algorithm

  - 1. Logistic Regression
  - 2. RandomForest Classifier
  - 3. SVM Classifier
  - 4. Decision Tree Classifier
  - 5. AdaBoostClassifier
  - 6. Gradient Boosting Classifier
  - 7. XGB Classifier
  - 8. Naive Bayes Classifier
  - 9. KNeighbors Classifier


#### Out of these Algorithm there is performed some algorithm better than other:

 - RandomForest classifier
 - ADABoost Classifier
 - GradientBoosting Classifier
 - XGB Classifier


**After Hyperparameter Tuning some model has performed good there was no much variation before and after hyperparmeter tuning that model is Logistic Regression, Random forest classifier and XGBoost classifier but I selected XGBoosting classifier Because it is performing well and accuracy is higher than other**
 
 - XGBoost Classifier


**After Hyperparameter tuning I found that some model has  giving well accuracy on data as compare to all model so We have choose XGB Classifier model for future prediction if the client will subscribe a bank term deposit yes or no.**
