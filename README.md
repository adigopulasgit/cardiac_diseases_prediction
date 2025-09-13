Cardiac Diseases Prediction
-------------------------------------------------------

🫀 Project Overview
A Django-based machine learning web app that predicts the likelihood of heart disease using patient health parameters. The project uses the UCI Heart Disease dataset and multiple ML algorithms (Logistic Regression, Naïve Bayes, Decision Tree, Random Forest, SVM, AdaBoost, XGBoost) for training and evaluation.
📌 Features
- Web interface to input patient details (age, cholesterol, chest pain, etc.).
- Trains and evaluates multiple ML classifiers.
- Predicts whether a person is likely to have or not have heart disease.
- Dataset: UCI Heart Disease dataset (Heart_train.csv).
⚙️ Requirements
- Python 3.9+
- Django 4.x
- Scikit-learn
- NumPy, Pandas
- XGBoost
- (Optional) django-heroku if deploying to Heroku
  
🚀 Setup & Run Locally

1. Clone repository:
git clone https://github.com/adigopulasgit/cardiac_diseases_prediction.git

cd cardiac_diseases_prediction

3. Create virtual environment:
python -m venv venv

venv\Scripts\activate   # Windows

source venv/bin/activate   # macOS/Linux

5. Install dependencies:
pip install -r requirements.txt

If no requirements.txt is provided:

pip install django numpy pandas scikit-learn matplotlib seaborn xgboost django-heroku

4. Apply migrations:
python manage.py makemigrations

python manage.py migrate

6. Run development server:
   
python manage.py runserver

8. Open in browser: http://127.0.0.1:8000


📊 Dataset
- Source: UCI Heart Disease Dataset
- 303 rows, 14 selected attributes (age, sex, cholesterol, blood pressure, etc.).
🧠 Algorithms Implemented
- Logistic Regression
- Naïve Bayes
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- AdaBoost
- XGBoost
  
📌 Deployment
- Works locally with `python manage.py runserver`.
- Can be deployed on Heroku (requires django-heroku, gunicorn, whitenoise).
  
👨‍💻 Author
Guru Ganesh Adigopula

