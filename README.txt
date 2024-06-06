== Instructions ==

Below are the five Jupyter Notebook used in this neural computing coursework.

'heart_disease_EDA':
This is used for data cleaning and data exploratory process.
Running this file will create four CSV file (X_train, y_train, X_test, y_test) for training and testing. 

'heart_disease_SVM_training':
For support vector machines (SVM), grid search with 10 fold cross validation is performed. 
The SVM model with the highest accuracy score will be saved as 'best_svm_model.joblib'. 

'heart_disease_MLP_training':
For multilayer perceptron (MLP), grid search with 10 fold cross validation is performed. 
The MLP model with the highest accuracy score will be saved as 'best_mlp_model.joblib'. 

'heart_disease_SVM_test':
This is used to evaluate the performance of the best trained SVM model using the test set.

'heart_disease_MLP_test':
This is used to evaluate the performance of the best trained MLP model using the test set.

== Important Note ==
Please run the 'heart_disease_EDA' Jupyter Notebook first if you do not have the X_train, y_train, X_test, y_test csv files.  

== References ==

The dataset:
Fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from 
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction.