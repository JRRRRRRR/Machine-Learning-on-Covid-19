# Phase-3-Project
Machine Learning on Covid-19
# Introduction
* In 2020 and the future, covid-19 will be a hot topic and a big challenge for our humans. For my health and life, I am tracking the covid status all the time. For the machine learning practice, I am going to make a project related to Covid-19. In this project, I'll be working with the Covid-19 dataset until 2020/11/10 from https://covidtracking.com/data/download. 
* Business problems: The dataset are sorted by every state daily. I am going to look for the dangerous states firstly. Then, I will analyze it deeper in New York State to see how the status of this state now. At last, I will use machine learning to make a classification model predict the covid-19 quality grade daily. 
1. The Dangerous States
    * Find some dangerous state by death case rate. 
    * Find some dangerous state by positive case rate.
2. The Status now of New York State
    * Visualization of the death cases increasing daily.
    * Visualization of the positive cases increasing daily.
3. Classification model to predict the covid-19 quality grade daily
    * Use logistic regression, random forest, and XGBoost for three different models
    * Use validation set and gridsearchCV for hyper tuning.
    * Use SMOTE for balancing sample sizes

# Techniques
* Data collecting, Data cleaning, Exploratory data analysis, machine learning and Visualization are all in the Jupyter Notebook.
* A PowerPoint and pdf for presentation
* A 5 minutes recording to review
* https://youtu.be/D8rI45FBxq4
* Blog: https://road2dataanalyst.blogspot.com/2020/11/machine-learning-on-covid-19.html

# Recommendation
* For residents: Even though covid-19 of some states are stable, we still can not relax our guard. Covid-19 is a serious problem in our lives and spreads very quickly. In some dangerous states, such as New York State, there is a risk of rebound. What we can do now is staying at home and keep safe. Do not travel around, especially in some dangerous states.

* For analysts: GridsearchCV is a handy tool to help us tune model parameters, but the shortcoming is costing a long run time.

# Future Work
* Accuracy: Find a better or some better parameters to improve accuracy
* Overfitting: Deal with the overfitting of the random forest model and XGBoost model
* More analyses: Try to analyze other columns of the dataset, such as recover
 
# Summary
From this project, I have a new overview of covid-19 and realize how serious of that. Those not just number and data, but human lives. What's more, I had the experience that applying machine learning and logistic regression in our real world. It provided me a chance to review my knowledge and skills. I found my weakness and make a plan to improve those.
