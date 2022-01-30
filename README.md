# Credit_Risk_Analysis

Overview
The purpose of this analysis was to create a supervised 
machine learning model that could accurately predict credit risk. 
In order to complete this task, I used 6 different methods, which are:

- Naive Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Undersampling
- SMOTEENN Sampling
- Balanced Random Forest Classifying
- Easy Ensemble Classifying
Through each of these methods, I split my data into training and testing datasets, and compiled accuracy scores, 
confusion matries, and classification reports as my results.

Results
Naive Random Oversampling:
- Accuracy Score: 65.1%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 70%

SMOTE Oversampling:
- Accuracy Score: 63.7%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 68%

Cluster Centroid Undersampling:
- Accuracy Score: 63.7%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 68%

SMOTEENN Sampling:
- Accuracy Score: 62%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 70%
- Recall Low Risk: 54%

Balanced Random Forest Classifying:
- Accuracy Score: 78.8%
- Precision High Risk: 4%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 91%

Easy Ensemble Classifying
- Accuracy Score: 92.3%
- Precision High Risk: 6%
- Precision Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%

Summary:

Easy Ensemble Classifying (92%)
Balanced Random Forest Classifying(78.8%)
Naive Random Oversampling (65%)
While this is the most important statistic that is pulled from this analysis, 
another important statistic is recall rate for low risk as it shows how many low risk loans are flagged as high risk. 
Looking through the different models, the ones that scored the highest were:

Balanced Random Forest Classifying (78.8%)
Easy Ensemble Classifying (92%)
After taking these two statistics over the others, we can look at the accurary score 
to get a picture of how well the model performs in general. The models with the highest accuracy scores were:

Easy Ensemble Classify (92.3%)
SMOTEENN Sampling (68.1%)
Balanced Random Forest Classifying (65%)
After factoring in these three main statistics, the model that I would recommend to use for predicting high risk 
loans is the Easy Ensemble Classifying model.













