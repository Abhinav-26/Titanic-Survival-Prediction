# Titanic-Survival-Prediction
In this repository I created a model for predicting Survial of passengers in one of the most famous shipwrecks ie, Titanic.
I have downloaded the dataset used in prediction from Kaggle. I used two datasets ie, "titanic_train.csv" and "titanic_test.csv", one for training the model and other for predicting the model. This is one of the most famous dataset which is used for predicting survival rate.

# Methodology Used
You can see that I have created  different jupter notebooks for each different tasks. This is so because, I believe all these phases of Machine Learning Predictions are very critical and we need to understand each phase of the prediction.
Jupyter Notebooks :
* Titanic Feature Selection
* Titanic Feature Engineering
* Feature Engineering Cont..
* Titanic Prediction Model
* Titanic Survival Prediction

In <b>Titanic Feature Selection</b> notebook, I have used graphical method for seleting most relevant features which can be used for training our model. Also dropped some of the columns which were not required for our model. Then in <b>Titanic Feature Engineering</b> notebook applied concepts of feature engineering like analysing null values using graphical method and then removing null values.In<b> Feature Engineering Cont..</b> notebook applied futhure the concept of feature engineering of categorical variable and removed all categorical varable and convert into binary format to begin with training part. In <b> Titanic Prediction Model</b> notebook I used Logistic Regression for making a model and trained that model with "titanic_train.csv" and also after training the model saved the model by using joblib into a file named "TitanicSurvialPrediction.pk1".Then in <b>Titanic Survial Prediction</b> again did all the feature engineering concept to clean and make "titanic_test.csv" ready for prediction part.

# Library Used
* pandas
* seaborn
* from sklearn.linear_model import LogisticRegression
* from sklearn.externals import joblib
