# Credit-Analysis-With-Knn-Dtree-Rf-Bagging

* The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. 
*  Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
* Classifying if the term deposit would be subscribed or not.
* Took a test split of 20%.
* Dataset contains 41188 rows and 21 columns.
* Class imbalance observed for target variable.
* Balancing the classes using SMOTE.
* DOing label encoding and one hot encoding on categorical variables.
* Models trained with KNN, Decision Tree,Randon Forest, and Bagging.
* Tuning the hyperprameters of all the models.
* Plotting precision-recall and roc-auc curves.


## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, nltk, string, imblearn, and seaborn.  

## Data Used
* **Data taken from kaggle** :https://www.kaggle.com/fahadmehfoooz/credit-analysis-with-knn-dtree-rf-bagging/data

## Data Wrangling and Data Visualization
* Modifying the columns: Assigning weights on the basis of importance.
* Dropping irrelevant columns.
* One hot encoding the remaining categorical variables.
* Balancing data using SMOTE.
* Scaling the data.

![alt text](https://github.com/fahadmehfooz/Sentiment-Analysis-Using-SVM-NB/blob/main/images/__results___20_1.png)

## Model Building 

First, I took a split on the data with training data as 80%. I tried to compare all the models listed down.

Models Used:

* KNN
* Decision Tree
* Bagging with KNN as base estimator
* Baggig with Decision Tree as base estimator
* AdaBoost
* RandomForest

## Model performance

**Results:**
* Bagging with Decision tree is performing the best according to recall and roc.For a credit insurance problem, I would want to go with recall here.
