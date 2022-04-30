# Credit_Risk_Analysis

***Overview of loan prediction analysis***

This project seeks to apply machine learning to solve risks inherent in credit card classification problems of good loans versus bad loans. Using credit card credit dataset from LendingClub, a peer- to-peer lending services, we would deploy techinques to evaluate and train our unbalanced dataset with a view to making predictions and solve credit card risk. We will oversample using Random Over Sampler and SMOTE algorithms, undersample using clustercentroid algorithm; we would use a combination of both oversampling and undersampling by deploying SMOTEENN algorithm, and finally we would use Balanced Random Forent Classifier and Easy Esemble Classifier algorithms to reduce the elemnet of bias and predict credit risk.


***Results***

***Using naive random oversampling technique:

The dataset showed an accuracy score of approximately 50%

Precision and recall for majority of the data scored an even low risk of 1.00 and f1 of 0.99, while the moniroty had a high risk of 1.00 precision and 0.01 recall score.

***The SMOTE oversampling technoque revealed similar scores.

***Using Undersampling technique:

The accurancy report was about average with a score of 51%.

Most of the dataset were low rsik with a high precision score of 1.0 and a recall score of 0.43 and an F1 value of 60%. Pn th eotherhand, the minoritywere high risk with a very low precision and F1 score of 0.01, a slightly above average scoye of 59&.

***The SMOTEENN technique (combination of oversampling and undersampling):

The accurancy was higher at about 64%.

The minority were classified as high risk with a huge disparity between the precision and recall values pr 0.01 and 0.70 respectively, Majority while classified as low risk revealed a closer relationship in velues between precison (1.00) and recall (0.57) and an F1 of 0.73.

**Balanced Random Forest Classifier technique:

The accuracy score was relatively high - 78%.

Majority of the sampled data were low risk with a precison score of 1.0, a recall value of 0.91 and and equally high F1 value of 0.95.

**The Easy Ensemble AdaBoost Classifier technique:

Had a high accuracy score of about 93%

Majority were low risk with a precision score of 1.0, recall value of 0.94 and an f1 value of 0.97.

Minority were classified as high risk with a low precison score of 0.07 and a high recall value of 0.91 and a low f1 value of 0.14.



***Summary***
