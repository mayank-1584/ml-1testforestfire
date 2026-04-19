# FWI Prediction App

This is a Flask-based web application that predicts the Fire Weather Index (FWI) using a machine learning model.

## Features
- Predicts FWI based on Temperature, RH, Ws, Rain, FFMC, DMC, ISI, Classes, and Region.
- Simple web interface using HTML.
- Uses a Ridge Regression model(because it give 97% accuracy for this model training).
- Model is uploded on AWS ElasticBeanStalk using CodePipeline

## Installation and Setup
1.Clone the repository git clone https://github.com/mayank-1584/ml-1testforestfire.git
   cd credit-risk-model

2.Install dependencies
   pip install -r requirements.txt

3.Run the Flask app
   python application.py

4.Open in browser
   http://localhost:5000

## ⚙️ Tech Stack

* Python
* Scikit-learn
* Flask
* NumPy
* HTML/CSS
* AWS ElasticBeanStalk



## 🎯 AWS detail

* Deploy on AWS ElasticBeanStalk
* But due to cost issue the project is not live

---

## 👨‍💻 Author

Mayank Sharma  
Aspiring Software Engineer  
