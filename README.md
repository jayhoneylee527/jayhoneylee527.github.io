## This is Jae Hun's Portfolio.

This is the list of independent projects I have worked on - Machine Learning, Scraping, Visualization and Application. 
Clicking on the title will direct you to the github repositories.

---

# ML

## Classification
### [JobCare Materials Usage Prediction](https://github.com/jayhoneylee527/Job-Recommendation-Manual-Usage-Prediction) - DACON Competition ###

[Korea Employment Information Service](http://www.keis.or.kr) currently operates an AI platform that analyzes potential employees' traits and provides them with proper trainings, consultings and support. In this competition hosted by KEIS, participants are expected to build binary classification models that predict whether people accessing their platform would decide to use the educational materials.

The notebook on the repository walks through the EDA, feature engineering and model trainings. For the classification models, I experimented with Logistic Regression, Random Forest Classifier, SVC, XGB Classifier, LDA and Catboost Classifier. The Catboost outperformed; in order to boost the performances, I used Optuna library for hyperparameter tuning. My submission placed me on the top 20% of the leader board. 

### [Stock Movement Direction Prediction](https://github.com/jayhoneylee527/Stock_Price_Movement_Prediction) ###

---
## Regression
### [Bulldozer Bluebook - Price Prediction](https://github.com/jayhoneylee527/Bulldozer-Price-Prediction) ### 

The project uses datasets from a previous competition on [Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/description), where participants were expected to predict the bluebook prices of bulldozers. 

The most challenging aspect of the project was feature engineering. Some feature columns included erroneous data, while some others had more than 80% missing rows, for which I had to create customized imputation methods that account for different types of missingness. For regression models, I used Random Forest Regressor and XGB Regressor which displayed similar performances. Since this competition ended few years ago, I did not get to observe the model performances of the test data. However, prediction score (Root Mean Squared Logarithmic Error) on the validation set was comparable to the top of leader board.      

---
# Scraping & Visualization
### [Stock Dividend Yield Scraper](https://github.com/jayhoneylee527/Stock-Dividend-Yield-Scraper) ###

I am currently investing in stocks, including Real Estate Investment Trusts (REITs). One of the most significant factors I consider when investing in REITs is their dividend yields. Depending on the types of industries the funds invest and their market capital, their sharing of profits with the investors vary; I needed to build a simple table that will display list of dividend yields, so that I can compare the returns and rebalance my portfolio.  

---

### [Youtube Sentiment on Korean Re-election Scraping](https://github.com/jayhoneylee527/Seoul-Mayor-By-Election-Sentiment-Analysis) ###
---
# Streamlit Application 
###  [FIFA22 Player DB](https://github.com/jayhoneylee527/FIFA22-PlayerDB) ###

As a serious FIFA player (challenge accepted anytime) I have to know the traits of each player to build an ideal team on a career mode. Although everyone hopes to create an an All Star team with Messi and Ronaldo, it is not only expensive but also in fact, not so economical. The App I created through Streamlit helps users with two essential functions:

1) Visualize each player's abilities and their values as well as other players with similar traits.

2) Filter players by the traits including their abilities, age, market value and etc.  

With this tool, users can find a nice replacement for the world-class player at an affordable market value.  

---
### [Stock Ticker Info & Price Charts](https://github.com/jayhoneylee527/Streamlit-TickerInfo_ARIMA) ###
