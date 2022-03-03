# Flight Fare Prediction:




## Table of Content

 - [Demo]()
 - [Overview]()
 - [Motivation]()
 - [Installation]()
 - [Deployment on Heroku]()
 - [Directory Tree]()
 - [Bug/Feature Request]()
 - [Future Scope of Project]()
 - [Technologies Used]()
 - [Badges]()
 - [Lessons Learned]()

## Demo

-[Link](https://flightfare100predict.herokuapp.com/)
## Overview

This is a Flask web app which predicts fare of Flight ticket.
## Motivation

Data is beautiful.

Data is not monotonous.

I like to discover information.

I love numbers.

Data is everything and everywhere.

And if we learn something from data using tools and techniques i.e. DATA SCIENCE, and one who can learn is DATA SCIENTIST.

With data all you do is discovering truth about the whole universe, big or small, nothing can be better than this.

So, I came across this dataset, and I have to learn more tools and techniques while enjoying my work that's why this is wonderful opportunity to prepeare myself for future endeavours.
## Installation

The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.jetbrains.com/pycharm/download/#section=windows). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning]() the repository:

```bash
  pip install -r requirements.txt
```

## Deployment on Heroku

Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.
[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)


Our next step would be to follow the instruction given on Heroku Documentation to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```
## Bug/Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue]() here by including your search query and the expected result.
## Future Scope of Project

- Use multiple Algorithms
- Optimize Flask app.py
- Front-End

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 



## Badges



[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)


## Lessons Learned

In this project , we saw different aspects of data handling,i.e. Nominal Data and Ordinal Data and how to handle using onehot encoding and label encoding.

Using numpy, pandas and seaborn library helped a lot and having to plot different plots like boxplot, heatmap, plotgraph, sctterplot according to our understanding.

And, I get to know and apply ExtraTrees Regressor from sklearn ensemble module, as ExtraTrees algorithm works by creating a large number of unpruned decision trees from the training dataset. Predictions are made by averaging the prediction of the decision trees in the case of regression or using majority voting in the case of classification.
It uses averaging to improve the predictive accuracy and control over-fitting. Thus, by score of ExtraTrees regressor selection of important features is plotted on plot graph. So, visualization of data is much improved.

Using Random Forest algorithm following steps to train and test, understanding about scaling of data, importing the model, fitting the data, prediction over the train model,and checking what the RMSE(root mean square error) score r2 score.

Overall the learning through this project is great one, and in future the takeaways while working this project is indispensable.

While, analyzing and understanding the dataset and the background of the flight industries I came across my understanding that may be the project is complete from my side but still there is very much scope to make the model more precise and accurate provided the required data is there, as you may thinking when lots of columns are there in the dataset,what 
I am saying? Well, you are absolutely right because when I go through on lots of background, I came across that the fuel prices of aviation industry is also fluctuating which in turn effect the fare. And, as in post covid era we areliving the tourism industry is not flourishing and there are lots of regulations in different countries are still in place. So, 
many of the Airlines are operating in loss or they are charging too much. And many regional reasons which effects the aviation industry.That is why the dataset to maintain all of these things is yet to be done which is again no small task.

Otherwise, everyline execution and finally completing the project is very happy and unforgettable journey.

