# titanic

It wass worked on titanic dataset from kaggle. 

Data was got from https://www.kaggle.com/cities/titanic123 . You can view about data information. Summary, data is 12 column and 891 row. Target is Survived column.

In this study, it was aimed seeing the normalization and oversampling operations effects on accuracy and other evaluation metrics. 

Python 3.7.4 and Jupyter Notebook 6.0.1 was used. 

Used Python libraries : Pandas, Numpy, Seaborn, matplotlib, scikitlearn, imblearn, scipy, xgboost

- Data exploration
- Data visualization
- Handle Null values
- Numerical Feature Standardization
- Feature Engineering
- Label Encoding
- Train and Test split
- Hyperparameter tuning and grid search validation for XGBoost algorithm
- Modelling
- Model Evaluation
- Oversampling and modelling again

Best results is z-transformed and oversampled data



No data transformation and no oversampling data result:
XGB TEST DATA PREDICTIONS
------------------------------------------------------
[[122  12]
 [ 26  63]]
              precision    recall  f1-score   support

           0       0.82      0.91      0.87       134
           1       0.84      0.71      0.77        89

    accuracy                           0.83       223
   macro avg       0.83      0.81      0.82       223
weighted avg       0.83      0.83      0.83       223

0.8295964125560538
XGB TRAIN DATA PREDICTIONS
------------------------------------------------------
[[398  17]
 [ 51 202]]
              precision    recall  f1-score   support

           0       0.89      0.96      0.92       415
           1       0.92      0.80      0.86       253

    accuracy                           0.90       668
   macro avg       0.90      0.88      0.89       668
weighted avg       0.90      0.90      0.90       668

0.8982035928143712





Z data transformed and no oversampling data result :
XGB TEST DATA PREDICTIONS
------------------------------------------------------
[[126  11]
 [ 24  62]]
              precision    recall  f1-score   support

           0       0.84      0.92      0.88       137
           1       0.85      0.72      0.78        86

    accuracy                           0.84       223
   macro avg       0.84      0.82      0.83       223
weighted avg       0.84      0.84      0.84       223

0.8430493273542601
XGB TRAIN DATA PREDICTIONS
------------------------------------------------------
[[384  28]
 [ 70 186]]
              precision    recall  f1-score   support

           0       0.85      0.93      0.89       412
           1       0.87      0.73      0.79       256

    accuracy                           0.85       668
   macro avg       0.86      0.83      0.84       668
weighted avg       0.85      0.85      0.85       668

0.8532934131736527



Z data transformed and oversampling data result :
XGB TEST DATA PREDICTIONS
------------------------------------------------------
[[126  11]
 [ 22  64]]
              precision    recall  f1-score   support

           0       0.85      0.92      0.88       137
           1       0.85      0.74      0.80        86

    accuracy                           0.85       223
   macro avg       0.85      0.83      0.84       223
weighted avg       0.85      0.85      0.85       223

0.852017937219731
XGB TRAIN DATA PREDICTIONS
------------------------------------------------------
[[384  28]
 [ 49 207]]
              precision    recall  f1-score   support

           0       0.89      0.93      0.91       412
           1       0.88      0.81      0.84       256

    accuracy                           0.88       668
   macro avg       0.88      0.87      0.88       668
weighted avg       0.88      0.88      0.88       668

0.8847305389221557
