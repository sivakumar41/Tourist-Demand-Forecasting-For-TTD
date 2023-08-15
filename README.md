# Tourist-Demand-Forecasting-For-TTD
Our tourism demand forecasting model to forecast arrivals for the tourist place
Tirumala Tirupati Devasthanam(TTD). We have considered TTD to our model because
it maintains historic data of pilgrim arrivals which we access through TTD.News and
TTD is popular tourist destination attracting large number of tourists every year. We
have considered attributes Day Speciality(weekend or weekday), Weather
condition(Based on temperature), Google Trends(frequency of ttd related keywords
searched on google), Twitter trend(whether opinion of twitter is +ve,-ve or neutral). Our
model uses structured variables to build a tourism demand forecasting model based on
Light Gradient Boosting Machine Regressor. LGBMRegresssion uses a leaf-wise tree
growth strategy which differs from level-wise strategy employed by many other
gradient boosting implementations. In leaf-wise growth, algorithm selects the leaf node
with maximum delta loss as the next node to grow. The ensembling algorithm at last
forms a improved model. In this approach the google trends, day speciality contributed
more information in recognizing the patterns of tourist arrivals. Another three model
multiple linear regression, decision tree regression, xgboost(extreme gradient boosting
algorithm) also tried to train the model, they have performed considerably but LGBMR
gives better results over those three models.
