# Data Science for Tabular Data
This repository contains projects involving advanced techniques for dealing with tabular data in Data Science. My objective here is to practice and demonstrate the use of techniques and tools that go beyong what we usually see on basic Data Science and Machine Learning tutorials. As the title suggests, the focus here is on techniques for tabular data, both for classification and regression problems. I will add new notebooks / tutorials over time. Check my other repositories for other topics in Data Science (Deep Learning, Time Series, Unsupervised Learning, etc.).


### Predicting House Prices: Stacking and Pipeline Custom Classes   
[Notebook](https://github.com/diegodebrito/tabular-data-techniques/blob/master/houses-final.ipynb)


In this project, I show how to achieve a score on the **top 1% worldwide** on the Housing Prices Competition on Kaggle (https://www.kaggle.com/c/home-data-for-ml-course/leaderboard). This competition has more than 26000 participants and the approach I present here will lead to the 250th position on the Public Leaderboard approximately. More than achieving a good score on the competition, my objectives were:  
   1. Implement a robust local validation pipeline.
   2. Develop **custom classes using Scikit-Learn structure** (fit/transform and fit/predict) and integrate these custom classes on a pipeline.
   3. Fine tune a state-of-the-art Gradient Boosting model (**XGBoost**).
   4. Implement a **Stacking custom class** without data leakage.  
   5. The final model is a Stacked combination of XGBoost and Lasso model.  
   



### Fraud Detection: IEEE-CIS Fraud Detection  
[Competition Link](https://www.kaggle.com/c/ieee-fraud-detection/overview)  
[Submission Notebook](https://github.com/diegodebrito/tabular-data-techniques/blob/master/houses-final.ipynb)  
[Adversarial Validation](https://github.com/diegodebrito/tabular-data-techniques/blob/master/ieee-adversarial-validation.ipynb)


In this project, I work on a finished complex Kaggle competition and try to understand and implement the winning strategies. As in many Kaggle competitions, one of the main aspects is the extensive feature engineering (leading to the so called 'magic features').  

In this competition, the magic features are varibles that are able to predict if a data point is on the training set or on the test set. I illustrate how to find some of these variables on the adversarial validation notebook (common technique on Kaggle).  

The way the cross-validation is structured and how the predictions are calculated is also unusual. The solution provided here ranks on the **top 1% on the public leaderboard**.   

Obs: The dataset for this competition is too big to be hosted on github (more than 500 thousands transactions). You can download the datasets using the link to the competition provided above.
