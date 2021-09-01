# 30 days to Machine Learning project
# In this project, I explore this "very clean" dataset of 300,000 samples and then apply various techniques to get the best prediction results from a test dataset of 200,000 samples.

The dataset has both categorical and continuous variables. Since there were no missing variables, the data-cleansing step was spared. 

My very first submission (2nd attempt below) was just simple linear regression and I did some exploratory data analysis. Techniques used: visulization with matploblib, seaborn, linear regression, ordinal encoding. You can view the notebook on the link below or you can just open the Jupyter notebook (no software installation required) in this repository
https://www.kaggle.com/lamtrinh259/30-days-of-ml-lam-s-2nd-attempt

My 4th submission is where I used blending to predict the results. Techniques used: Standard Scaler to convert numerical variables to a standard distribution, XGBoost regression, hyperparameters tuning using Randomized Search CV, Gradient Boosting, and LightGBM Regression, and blending of all 3 models to predict the final results. Notebook can be viewed by visiting the link below or open the Jupyter notebook in this repository. 
https://www.kaggle.com/lamtrinh259/30-day-ml-lam-s-4th-attempt-model-blending
