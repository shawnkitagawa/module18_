# module18_

Analysis:
The purpose fo this analysis is to have a deep understanding of imbalanced classification problem using different resampling method. 




Results:

Oversampling: 

    balanced_accuracy_score: 62.2%
    precision score: high_risk: 1%, low_risk: 100%
    recall score:  high_risk: 59%, low_risk: 66%


SMOTE Oversampling: 

    balanced_accuracy_score: 61.3%
    precision score: high_risk: 1%, low_risk: 100%
    recall score:  high_risk: 59%, low_risk: 64%


Undersampling: 

    balanced_accuracy_score: 49.3%
    precision score: high_risk: 1%, low_risk: 99%
    recall score:  high_risk: 59%, low_risk: 40%


SMOTEENN: 

    balanced_accuracy_score: 60.4%
    precision score: high_risk: 1%, low_risk: 100%
    recall score:  high_risk: 67%, low_risk: 53%

Balanced Random Forest Classifier

    balanced_accuracy_score: 77%
    precision score: high_risk: 4%, low_risk: 100%
    recall score:  high_risk: 63%, low_risk: 91%

Easy Ensemble AdaBoost Classifier

    balanced_accuracy_score: 93%
    precision score: high_risk: 7%, low_risk: 100%
    recall score:  high_risk: 92%, low_risk: 93%






Summary:
Easy Ensemble AdaBoost Classifier has the best balance_accuracy_score and also better precision score and recall score for high risk. I personally would not reccommend Oversampling, SMOTE, SMOTEENN and undersampling just because the precision score for high risk is 1 percent. That means that they only will get 1 percent right for their prediction, which is really low and does not function as a prediction. When compare all the resampling method, Easy Ensemble Adaboost Classifier has the highest results and this is the only method that should be used in order to accomplish this prediciton. 