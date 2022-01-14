# Credit_Risk_Analysis
See *credit_risk_ensemble.ipynb* and *credit_risk_resampling.ipynb*

## Supervised Machine Learning Models

### Naive Random Oversampling

  #### Classification Report<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/NaiveOversamplingClassificationReport.png)
  #### Confusion Matrix<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/NaiveOversamplingConfusion.png)

 - Precision High Risk: 1%
 - Precision Low Risk: 100%
 - Recall High Risk: 66%
 - Recall Low Risk: 62%
 - Balanced Accuracy Score: 64%

### SMOTE Oversampling

  #### Classification Report<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/SmoteClassification.png)
  #### Confusion Matrix<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/SmoteConfusion.png) 

 - Precision High Risk: 1%
 - Precision Low Risk: 100%
 - Recall High Risk: 61%
 - Recall Low Risk: 69%
 - Balanced Accuracy Score: 65%

### Undersampling

  #### Classification Report<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/UndersamplingClassification.png)
  #### Confusion Matrix<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/UndersamplingConfusion.png) 

 - Precision High Risk: 1%
 - Precision Low Risk: 100%
 - Recall High Risk: 69%
 - Recall Low Risk: 40%
 - Balanced Accuracy Score: 54%

### SMOTEENN Sampling

#### Classification Report<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/UndersamplingClassification.png)
  #### Confusion Matrix<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/UndersamplingConfusion.png) 

 - Precision High Risk: 1%
 - Precision Low Risk: 100%
 - Recall High Risk: 72%
 - Recall Low Risk: 57%
 - Balanced Accuracy Score: 64%

### Balanced Random Forest Sampling

#### Classification Report<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/Resources/RandomForestClassification.png)
  #### Confusion Matrix<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/Resources/RandomForestConfusion.png) 

 - Precision High Risk: 3%
 - Precision Low Risk: 100%
 - Recall High Risk: 70%
 - Recall Low Risk: 87%
 - Balanced Accuracy Score: 79%

### Easy Ensemble ADABooster Classifier

#### Classification Report<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/Resources/ADABoostClassification.png)
  #### Confusion Matrix<br>
  
![Alt text](https://github.com/Goddard310/Credit_Risk_Analysis/blob/main/Resources/ADABoostConfusion.png) 

 - Precision High Risk: 9%
 - Precision Low Risk: 100%
 - Recall High Risk: 92%
 - Recall Low Risk: 94%
 - Balanced Accuracy Score: 79%

## Summary

In our analysis it would be fair to say that our algorithms are overfit.  We are not seeing a good balance of recall and precision.  As you can see, our Easy ADABoost Classifier or Random Forest Sampling *(directly above)* models are the best fit of those used.  
