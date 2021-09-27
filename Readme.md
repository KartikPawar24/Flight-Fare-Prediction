# Flight Fare Prediction

# Table of Contents
- [Demo](#demo)
- [Overview](#overview)
- [Motivation](#motivation)
- [Installation](#installation)
  - [Cloning the repository](#1-cloning-the-repository)
  - [ Installing the required dependencies](#2-installing-the-required-dependencies)
- [Run Local](#run-local)
- [Deployment on Heroku](#deployment-on-heroku)
- [Directory Tree](#directory-tree)
- [Bug / Feature Request](#bug--feature-request)
- [Technologies Used](#technologies-used)
- [Author](#author)

# Demo

You can find the deployed app here: https://flight-fare-predict-ml.herokuapp.com

https://user-images.githubusercontent.com/33437982/134840992-5ef3a179-4830-4878-bee2-7df009d2d5d4.mp4

# Overview

This is a Flask web app which predicts the flight fare / price using RandomForestRegressor and RandomizedSearchCV.

The following are the inputs which are to be given:
- Departure Time
- Arrival Time
- Source
- Destination
- Number of Stops
- Name of the Airline
  
# Motivation

As I was searching for datasets to make a prediction model using my knowledge and I ended up finding on Kaggle, you can view / download the datasets from [here](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh?rvi=1). I found this dataset as interesting and tried to make a prediction model using these datasets.

# Installation

The code is written using python 3.8.8 and make sure you have the same version or upgrade your Python version greater than 3.8.0.

- To install Python in Windows machine, you can download the executable file from [here](https://www.python.org/).

- To install Python on MacOS machine, you can find the installation steps [here](https://flaviocopes.com/python-installation-macos/).

- To install Python on Linux machine, you can find the installation guide [here](https://www.geeksforgeeks.org/how-to-install-python-on-linux/).

- For upgrading the Python version you can visit the site and download the specified version you need by clicking [here](https://www.python.org/downloads/).


 ## 1. Cloning the repository

For cloning this repository you can use various methods from [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

 ## 2. Installing the required dependencies

After successful installation and cloning the repository the next step is to install the required dependencies and you need to run the following command to install those dependencies.
 ```bash
    pip install -r requirements.txt

            (or)

    pip3 install -r requirements.txt            
 ```

 # Run Local

 Run the following command to view the app in web browser

 ```bash
    python app.py
   
        (or)
   
    python3 app.py
```    

# Deployment on Heroku
To know about the deployment of app on heroku, you can refer to this documentation from [here](https://devcenter.heroku.com/categories/deployment).

# Directory Tree

```
|
│   .gitignore
│   app.py
│   Data_Train.xlsx
│   flight-fare-prediction.ipynb
│   flight_model.pkl
│   Procfile
│   Readme.md
│   requirements.txt
│   Test_set.xlsx
│   
├───static
│       style.css
│       
└───templates
        home.html
```

# Bug / Feature Request
If you find any issue with the project or you could not get the desirable results, you can raise issue(s) from [here](https://github.com/KartikPawar24/Flight-Fare-Prediction/issues).

# Technologies Used

<a href="https://getbootstrap.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="60" height="60"/> </a> 
<a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="60" height="60"/> </a> 
<a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="60" height="60"/> </a>
<a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="60" height="60"/> </a>

<a href="https://flask.palletsprojects.com/en/1.1.x/" target="_blank"> <img src="https://camo.githubusercontent.com/3638770a498aa8a62be0fb35f9217dbc78a50d739e1f6cdc64ef88def23aa1ec/68747470733a2f2f666c61736b2e70616c6c65747370726f6a656374732e636f6d2f656e2f312e312e782f5f696d616765732f666c61736b2d6c6f676f2e706e67" width="170" data-canonical-src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" style="max-width: 100%"></a>

<a href="https://www.gunicorn.org" target="_blank"> <img src="https://gunicorn.org/images/logo.jpg"/></a>

<a href="https://scikit-learn.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn"/> </a>

# Author
 - [Kartik Pawar](https://www.github.com/KartikPawar24)
