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

Best results is z-transformed and oversampled data. Test data accuracy 0.85, train accuracy is 0.88. 
