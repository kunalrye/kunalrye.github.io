---
title: ":chart_with_downwards_trend: Decline Curve Analysis @ Chevron"
layout: post
date: 2019-08-02 22:10
# tag: jekyll
# image: 
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Using ML and feature engineering to produce predictions for seemingly random events"
category: project
author: kunalrai
externalLink: false
---


---

![](https://www.petroskills.com/images/nov18-sub/equation.png)

# What is Decline Curve Analysis?
Decline curve analysis (DCA) is a technique commonly used by oil and gas companies to be able to forecast production of an oil well. DCA typically looks at a plot of rate versus time to find where the production will intersect the x-axis, which is the point at which the production output is no longer of value or significant. The integral of this curve provides the EUR or expected ultimate recovery / reserve.
## How can you do 'decline curve analysis' on non-declining wells?
This was a puzzle for me as well initially. However, as with most ML problems, manipulation of the data was the most important part of cracking the model. Using the data available, I did a lot of feature engineering to determine what data was useful and what data was not in determining future production of these wells. After finding the most valuable features, I ran through multiple regression models such as XGBoost, Random Forest, Ridge Regressor, as well as using Data Robot to streamline the process. 
## Tools I used to create the model
I used a combination of Python (pandas, pyspark, scikit-learn, seaborn), SQL, a linux cluster, Azure, and DataRobot to create the model. 
## Results and Takeaways
By learning about machine learning & data science workflows I was able to figure out best practices and make progress towards creating a model. My model ultimately had a 25% mean absolute error on the future production of wells that were non-declining and will be integrated into the product that handles all forecasting of oil wells. Through the modeling process I was able to learn the importance of understanding the data through visualization, model creation, hyperparameter tuning, and feature engineering. 
