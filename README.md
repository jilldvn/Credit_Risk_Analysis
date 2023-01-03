# Credit_Risk_Analysis
Module 18
## A. Purpose of the analysis:
### Within this project, we are to evaluate and predict credit risk by employing various machine learning models.  

## B. Results: 
### The balanced accuracy scores and the precision and recall scores of the following six machine learning models.

#### 1. RandomOverSampler
* Blanced Accuracy Score: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/ROS%20balanced%20score.png)
* Imbalanced Classification Report: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/ROS%20imbalanced%20report.png)

#### 2. SMOTE
* Blanced Accuracy Score: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/SMOTE%20balanced%20score.png)
* Imbalanced Classification Report: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/SMOTE%20imbalanced%20report.png)

#### 3. ClusterCentroids
* Blanced Accuracy Score: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/CC%20balanced%20score.png)
* Imbalanced Classification Report: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/CC%20imbalanced%20report.png)

#### 4. SMOTEENN
* Blanced Accuracy Score: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/SMOTEENN%20balanced%20score.png)
* Imbalanced Classification Report: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/SMOTEENN%20imbalanced%20report.png)

#### 5. BalancedRandomForestClassifier
* Blanced Accuracy Score: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/RFC%20balanced%20score.png)
* Imbalanced Classification Report: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/RFC%20imbalanced%20report.png)

#### 6. EasyEnsembleClassifier
* Blanced Accuracy Score: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/EEC%20balanced%20score.png)
* Imbalanced Classification Report: </br>
![image](https://github.com/jilldvn/Credit_Risk_Analysis/blob/main/Image/EEC%20imbalanced%20report.png)

## C. Summary: 
### In this project, a dataset of customers' financial status and outcomes are available, therefore, six common sklearn library modules could be used to predict future customers' high or low credit risk. Comparisons of these six modules with its balanced accuracy score, probability of precision and sensitivity in each high and low risk populations are output. <br>
### Due to the nature of credit score predictions, we would like to have higher sensitivity in each risk level rather than precisions, as the result, a higher balance accuracy score with higher recall score (named as "rec" in classification report) would be a preferable choice of module to be recommended in this project. With the highest balance score of 0.92 and recall (sensitivity) scores in both high (0.89) and low risk (0.94), it is recommended to apply Easy Ensemble AdaBoost Classifier in this case. 
