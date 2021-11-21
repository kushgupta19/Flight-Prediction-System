# Flight-Fare-Prediction-System:

This is a Flight Fare Prediction System.
Link to the Web-Application: [https://flight-price-prediction-api.herokuapp.com/](https://flight-price-prediction-api.herokuapp.com/)

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)

Link: [https://flight-price-prediction-api.herokuapp.com/](https://flight-price-prediction-api.herokuapp.com/)

## Screenshot

### Home Page

[![](https://i.imgur.com/R1g2wvC.png)](https://flight-price-prediction-api.herokuapp.com/)

### Result Page
![image](https://user-images.githubusercontent.com/59951582/142774583-473acf7c-ab2e-4c2c-8001-ccd622b15cf8.png)



***

### Requirements
```
Flask==1.1.1
gunicorn==19.9.0
itsdangerous==1.1.0
Jinja2==2.10.1
MarkupSafe==1.1.1
Werkzeug==0.15.5
numpy>=1.9.2
scipy>=0.15.1
scikit-learn>=0.18
matplotlib>=1.4.3
pandas>=0.19
```

## Overview
This is a Flask web app which predicts fare of Flight ticket.


## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/Mandal-21/Flight-Price-Prediction/issues) here by including your search query and the expected result

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
