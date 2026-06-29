
# Heart Disease Predictor
A machine learning model that predicts the likelihood of heart disease based on medical parameters.
Heart disease prediction system using machine learning algorithms such as Decision Tree, Random Forest, LightGBM , CatBoost, SVM and MLP. Includes data preprocessing, feature scaling, and model evaluation.   IT is a web-based Machine Learning Project with a user-friendly interface that is built with Django and Scikit-learn. It predicts whether the patient has heart disease or not with probability.

In HDPS data is extracted from the patient which includes different 14 parameters like blood pressure, age, sex, Smkr etc. This data is then fed to the trained model which provides the outcome in the form of probability ranging value 0-1.

## Project Objective
The objective of this project was to develop a machine learning-based web application capable of predicting the likelihood of heart disease using patient clinical data. Heart disease is one of the leading causes of mortality worldwide, and early detection can significantly improve treatment outcomes. The project aimed to build an accurate predictive model by comparing multiple machine learning algorithms and deploying the best-performing model through a user-friendly web interface.

## It Includes:
* Data collection, preprocessing, and cleaning, including handling missing values, feature scaling, and preparing the dataset for model training.
* Performing feature importance analysis and correlation analysis to identify the most influential clinical features.
* Training and evaluating multiple machine learning models for heart disease prediction.
* Comparing model performance using Accuracy, Precision, Recall, and F1-score.
* Integrating the trained machine learning model into a Django-based web application.
* Testing the application and validating prediction outputs.



### How to run the project :
 Install python and its libraries NumPy, Pandas and Sklearn along with Django. 
```
pip install django sklearn
```
#### Run following commands:
```
python manage.py collectstatic
python manage.py makemigrations 
python manage.py migrate
python manage.py createsuperuser
```
#### To run the server type the following command:
    python manage.py runserver


