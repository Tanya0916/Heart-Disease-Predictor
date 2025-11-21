
# Heart Disease Predictor
A machine learning model that predicts the likelihood of heart disease based on medical parameters.
Heart disease prediction system using machine learning algorithms such as Decision Tree, Random Forest, and MLP. Includes data preprocessing, feature scaling, and model evaluation.   IT is a web-based Machine Learning Project with a user-friendly interface that is built with Django and Scikit-learn. It predicts whether the patient has heart disease or not with probability.

In HDPS data is extracted from the patient which includes different 13 parameters like blood pressure, age, sex, etc. This data is then fed to the trained model which provides the outcome in the form of probability ranging value 0-1.



### How to run the project :
 Install python and its libraries NumPy, Pandas and Sklearn along with Django. 
```
pip install django sklearn
```
#### Run following commands
```
python manage.py collectstatic
python manage.py makemigrations 
python manage.py migrate
python manage.py createsuperuser
```
#### To run the server type the following command
    python manage.py runserver


