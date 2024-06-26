# Credit_Card_Fraud_Detection

   # `Abstract :`   
   
   This project mainly focuses on handling imbalanced datasets and detecting credit-card frauds using Following Machine Learning Algorithms:      
   a) DecisionTreeClassifier      
   b) Logistic Regression      
   c) LGBM Classifier      
   d) Random Forest Classifier    
   
   ### `ABOUT DATASETS:`   
   
   URL : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud  
   
   The dataset contains transactions made by credit cards in September 2013 by European cardholders.  This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.  
   It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features are not provided and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.  
   Feature `Time` contains the seconds elapsed between each transaction and the first transaction in the dataset.But, we did not consider `Time` for training purpose as it is of no use to build the models and may not impact our target variable.  
   The feature `Amount` is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.  Feature `Class` is the response variable and it takes value 1 in case of fraud and 0 otherwise.  
   
   ### `STEPS : `        
   1) Importing Libraries & Loading Dataset.
   2) Data Preprocessing & Preparing Dataset.
   3) Exploratory Data Analysis(EDA) & Visualization.
   4) Handling Imbalanced Dataset.
   5) Choosing of the best Model (Cross Validation).
   6) Hyperparameter Optimization.
   7) Evaluation of the Model.
     
### CONTACT ME ON:  linkedin --> https://www.linkedin.com/in/doguser-yarar/
