# Credit_Risk_Analysis
In this analysis we will be using machine learning models to predict credit risk.Evaluating credit risk isn't a linear classification, there are unbalanced factors when it comes to credit risk. Knowing which type of machine learning model to use isn't clear, we must evaluate the machine learning model by resampling to see which model has the better prediction. 

## Roadmap 
- Use Resampling Models to Predict Credit Risk 
- Use SMOTEENN Algorith to Predict Credit Risk 
- Ensemble Classificers to Predict Credit Risk 

## Results
### Oversampling: Naive Random
  
<img width="717" alt="Navie" src="https://user-images.githubusercontent.com/107595578/204163146-fbcaa540-4d59-41de-84a0-59edee37c476.png">

###### The Naive Random oversampling model has a accuracy score of 65%, for high risk a precision score of 1%, recall score of 72 % and a F1 score of 0.02. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk high risk applicants. As for low risk, this model has precision score of 100%, recall score of 59 % and a F1 score of 0.74. Since the F1 value is somewhat close to 1, this model is fair for predicting credit risk low risk applicants.
      
### Oversampling: SMOTE Oversampling 
  
<img width="717" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/107595578/204163178-03cfcc23-793c-4898-b05d-25ba92804a5e.png">

###### The SMOTE oversampling model has a accuracy score of 66%, for high risk a precision score of 1%, recall score of 63 % and a F1 score of 0.02. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk for high risk applicants. As for low risk, this model has precision score of 100%, recall score of 69 % and a F1 score of 0.82. Since the F1 value is closer to 1, this model good for predicting credit risk low risk applicants.
      
### Undersampling
  
<img width="717" alt="Undersampling" src="https://user-images.githubusercontent.com/107595578/204163227-319b1c7b-a9af-4446-afb9-ed63aa7f1667.png">

###### The undersampling model has a accuracy score of 66%, for high risk a precision score of 1%, recall score of 69 % and a F1 score of 0.01. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk for high risk applicants. As for low risk, this model has precision score of 100%, recall score of 40 % and a F1 score of 0.57. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk low risk applicants.

### Combination (over and under) Sampling
  
<img width="717" alt="Combination (over and under) Sampling" src="https://user-images.githubusercontent.com/107595578/204163260-7be8abdd-8954-4293-83f5-6c90863e050f.png">

###### The combination model has a accuracy score of 54%, for high risk a precision score of 1%, recall score of 72 % and a F1 score of 0.02. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk for high risk applicants. As for low risk, this model has precision score of 100%, recall score of 72 % and a F1 score of 0.73. Since the F1 value is closer to 1, this model somewhat good for predicting credit risk low risk applicants.


### Balanced Random Forest Classifier 

<img width="717" alt="Balanced Random Forest Classifier " src="https://user-images.githubusercontent.com/107595578/204164511-ef5ca606-1289-4386-a6ab-c5efbaa2af6c.png">


###### The balanced random forest classifier  model has a accuracy score of 78%, for high risk a precision score of 3%, recall score of 70 % and a F1 score of 0.06. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk for high risk applicants. As for low risk, this model has precision score of 100%, recall score of 87 % and a F1 score of 0.93. Since the F1 value is closer to 1, this model good for predicting credit risk low risk applicants.

### Easy Ensemble AdaBoost Classifier 

<img width="717" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/107595578/204164491-e140a724-5891-4a63-b8ee-8cf4dc6f93a3.png">


###### The easy ensemble AdaBoost classifier  model has a accuracy score of 93%, for high risk a precision score of 9%, recall score of 92 % and a F1 score of 0.16. Since the F1 value isn't close to 1, this model isn't ideal for predicting credit risk for high risk applicants. As for low risk, this model has precision score of 100%, recall score of 94 % and a F1 score of 0.97. Since the F1 value is closer to 1, this model good for predicting credit risk low risk applicants.

## Summary 
In conclusion, the first four models preformed similarly, with a accuracy score ranging from 54-66%. While the last two models showed more promise with higher accuracy score fron 78-93%. The model that I would recommend is the Easy Ensemble AdaBoost Classifier model. This model had an accuracy score of 93% with an F1 score of 0.16, the highest compared to all other models.  
