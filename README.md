# Data_Science_workShop_project
## Problem:
The problem was predicting bank loan will be charged off or not depending on different features. I collected the dataset from kaggle.
## Task:
The task was to build an algorithm that automatically predict a bank loan's status before giving the loan. The dataset gave us different features like current job duration, accounts information, past records etc.
## Dataset Information:
Initially it had 100000 rows and 19 columns. 
## Working process:
### Removed the unnecessary columns like customer id & loan id these are not helpfull for predicting
### Dealing missing values 
* Removed whole column if missing value is more than 50% and can't make missing value a feature
* For neumaric value I used mean value for fill them
* For object value I used most frequent value
### Predicting Model: As it was a classification problem I used classification algorithm like Logistic regrassion, KNN, Random forest ETC.
## Working process:
My future plan about this project is deploying this in web for better user experience.
