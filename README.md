# FishSpecies_demo

# Contents of the Repository

The contents of the folder include the files which were used for the completion of the test.
The folder contains 10 files as follows:
1) static/css - Contains the styling sheet code for the index.html
2) templates - Contains the index.html / front-end of the application.
3) Fish.csv - Dataset used for the classification
4) FlaskApp.py - code used for the flask application
5) Model_Train.ipynb - code for model training
6) Procfile - includes start command for the heroku
7) fish_classifier.pkl - pickle file of the trained model
8) requirements.txt - containing libraries required for prediction by Heroku
9) runtime.txt - Since python 3.10 is considered unstable for running heroku hence, python 3.9 was used instead forced using this file

# Heroku
Heroku is a cloud platform as a service supporting several programming languages. For this particular project heroku was used as deployment application for the model.

# Model and Dataset
This dataset is a record of 7 common different fish species in fish market sales. With this dataset, a predictive model can be performed using machine friendly data and estimate the weight of fish can be predicted.
For this classification task, Random Forest Classifier was used and provided with a accuracy of 66%.

# Flask
Flask is considered more Pythonic than the Django web framework because in common situations the equivalent Flask web application is more explicit. Flask is also easy to get started with as a beginner because there is little boilerplate code for getting a simple app up and running.
For this particular task, POST was used within flask api to transfer all the required varibles to the API.

# HTML and Css
Basis frontend was used for the project while static styling sheet was refernced to the html file.

