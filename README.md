# Lending Club Project: predicting defaults on loans for online peer-to-peer lending. 


Online P2P lending has gained more and more popularity over these years. The largest online P2P lending platform, Lending Club, has issued over 33 billion loan by the end of 2017. 
It provides a portfolio diversification opportunity and the potential to earn competitive returns. 
Predicting defaults can help the platform to determine the interest rate more accurately and also help investors to make more informed decisions on choosing loans. 

The data I am using is available on Kaggle.com and also provided by the official website of Lending Club. It has more than 1.6M loan entries and hundreds of features. 

Exploratory data analysis has been done and several key indicators for defaulting loans, for example FICO credit scores of the applicants, have been found. 
Credit score has, surprisingly, a much higher correlation with defaulting than interest rate does. 
Also, natural language processing analysis on the text features (such as job titles and the titles of the loan application) has been performed, but there are not any obvious indicators found yet in the preliminary analysis. 
From only a few indicators, a model with high performance (roc 0.94) is created. The plan for later study is to perform more feature engineering, 
especially on the text data, to use a better predictor such as Gradient boost and neural networks instead of simple logistic regression.  
Combining default prediction and interest rate, I will create an application as a final product of the project. 
The application can present return rate and risks to investors, therefore complementing the portfolio analysis tool on the platform.
