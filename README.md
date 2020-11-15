# Pharse-3-Project
Machine Learning on Covid-19
# Introduction
* In 2020 and the future, covid-19 will be a hot topic and a big challenge for our human. For my health and life, I am tracking the covid status all the times. For the machine learning practice, I am going to make a project related to Covid-19. In this project, I'll be working with the Covid-19 dataset until 2020/11/10 from https://covidtracking.com/data/download. 
* Business problems: The dateset are sorted by every state daily. I am going to look for the most dangerous state first. Then, I will analyze it deeper to see how the status of this state now. At last, I will use machine learning to make a classification model to predict the covid-19 quality grade daily. 
1. The Most Dangerous State
    * Find the most dangerous state by total death cases and daily death cases. 
    * Find the most dangerous state by total positive cases and daily positive cases.
2. The Status now of this State
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
* https://youtu.be/FNqwf82lGvs

# Recommendation
* For residents: Even though covid-19 of some states are stable, we still can not relax our guard. Covid-19 is a serious problem in our life, and spreads very quickly. In some dangerous states, such as New York State, there is a rick of rebound. What we can do now is staying at home and keep safe. Do not travel around, especially some dangerous states.

* For analysts: GridsearchCV is a very useful tool to help us tune model parameters.

# Future Work
* Accuracy: Find a better or some better parameters to improve accuracy
* Overfitting: Deal with the overfitting of random forest model and XGBoost model
* More analyses: Try analyse other columns of the dataset, such as recover
* Death Rate: The death rate of New York state is high. Try to find some reasons and realted data.
 
# Summary
From this project, I have a new overvie of covid-19 and realize how serious of that. Those not just number and data, but human lives. What's more, I had the experience that applying machine learning and logistic regression in our real world. It provided me a chance to review my knowledge and skills. I found my weakness and make a plan to improve those.
