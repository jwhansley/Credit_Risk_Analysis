# Credit Risk Analysis

## Overview
The purpose of this analysis is to determine what resampling techniques will be most useful to evaluate the data

## Results
![Naive Random Oversampling](https://user-images.githubusercontent.com/16244455/151677386-204f30fa-49d2-4c89-ba72-72f7e5728ceb.png)
Naive Random Oversampling: 
- Accuracy Score: 64%
- High Risk Precision: 101%
- Recall: 66%

![SMOTE Oversampling](https://user-images.githubusercontent.com/16244455/151677442-340ac8c5-5354-4efa-b166-eef97cb03874.png)
SMOTE Oversampling: 
- Accuracy Score: 65%
- High Risk Precision: 101%
- Recall: 61%

![Undersampling](https://user-images.githubusercontent.com/16244455/151677471-61bc8b38-4054-49c8-908f-2c375ddaadc7.png)
Undersampling: 
- Accuracy Score: 65%
- High Risk Precision: 101%
- Recall: 69%

![SMOTEENN](https://user-images.githubusercontent.com/16244455/151677493-9cbebfa0-ae14-4705-8023-43ede1c9c033.png)
SMOTEENN: 
- Accuracy Score: 54%
- High Risk Precision: 101%
- Recall: 72%

![Balanced Random Forest](https://user-images.githubusercontent.com/16244455/151677534-0163282b-0d2f-4cef-9872-774137c1758b.png)
Balanced Random Forest: 
- Accuracy Score: 77%
- High Risk Precision: 104%
- Recall: 66%

![Easy Ensemble](https://user-images.githubusercontent.com/16244455/151677554-bcfbb238-72d6-4f9a-97c4-792f74a23919.png)
Easy Ensemble AdaBoost Classifier: 
- Accuracy Score: 92%
- High Risk Precision: 104%
- Recall: 89%

## Summary
- The precision across all techniques is very similar.
- The accuracy scores for the ensemble methods are considerably higher than the oversampling and undersampling techniques
- The recall is the highest for Easy Ensemble AdaBoost Classifier technique

Because the Easy Ensemble AdaBoost Classifier technique has a balance of precision, and a higher accuracy and recall, this is the best method to use.
