# Air-Quality-Index

# Introduction
Air Quality has been a big factor in many developing countries, as they rely more on fossil fuels for energy purposes. In our model we try to study the air quality index of each year and based on it predict the air quality index for the future years.

# Data
The dataset we’ll use for this python project has been scraped from [here](https://en.tutiempo.net/). In each jupyter notebook feature engineering on the data has been performed. 

# Project Structre
This project has four major parts :

* ML models - This contains code for our Machine Learning models, each algorithm is in its own jupyter notebook. 
* app.py - This contains Flask APIs that receives data through GUI or API calls feeds it to the model saved as a AWS S3 bucket and returns the prediction.
* templates - This folder contains the HTML template to allow user to enter url and displays whether the news is fake or real.
* static - This folder contains the CSS file.
* requirements.txt - It contains the list of libraries required to run the heroku app

# Algo Selection

Used various machine learning algorithms to figure out the most optimial one for our problem has been selected based ono accuracy scores for each algorithms. Check the jupyter notebook for implementations.
