# CreditRiskAnalysis
-> The aim of the project is to analyze the default indicators in the data. 
-> The data is imported from the local computer.
-> The next step is to visualize the data using python libabries such as seaborn and matplot.
-> It is then followed by data cleaning in where the data is manipulated by treating the missing values and removing irrelevant varibales 
and treating categorical variables.
-> After data cleaning the data is split into train and test data. the independent features and the target varaibles are seperated and the data is normalized using Standard Scaler
-> The taget variable in the dataset which is the default indicator is imbalanced.
Thus, to balance the data oversmapling technique is used from the imblearn library.
-> In this project, the SMOTE(Synthetic Minority Oversampling Technique) function is used which is an sampling technique.
-> The next step is to build the models, I have used 4 machine learning models in this paper such as Logistic Regresssion, Decision Tree, Naive Bayes and Artificial Neural Network.
-> After the building and fitting the model, the model needs to be evaluation using evalution metrics such as confusion matrix, accuracy, precision and recall.
-> Once the model evalutaion is completed the accuarcy of each model is compared and the model with the highest accuracy will be choosen as the optimal model to be used to predict the number of defaulters. 
