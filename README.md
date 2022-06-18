# BoomBikes Sales Predictive analysis
> A case study to predict the sales forecast of boombikes with data collected for two years, 2018 and 2019 using linear regession

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

The project aims to build a linear regression model that will help boombikes reach to a conclusion about which factors are the most significant contributors to the sales of their bikes in the existing market, and also use the same model to forecast the sales in a new market

The dataset being used is uploaded to the project, titled *day.csv* which lists out various factors that contributed to the bike sales in teh years 2018 and 2019.
A lot of these factors are environmentally based, such as season, weather situation etc.

## Technologies Used

- sklearn
- statsmodel.api
- seaborn
- pandas
- matplotlib

## Conclusions
- From the months categorical variable shown above, month_9 (September) has the highest positive coefficient - 0.4203, hence we can conclude that the bike sales   peak in the month of September

- We can also see that windspeed has a significant negatvie coefficient (-0.1979), which means that an increase in
  windspeed lead to decreased bike sales as people find it difficult to ride bikes

- The weather situation also plays a significant role, wherein a light snow + heavy rain causes a dcrese in bike sales

- We can also see that the sales were significantly less in 208 than in 2019, which may mean that in 2019 people came to know about boombikes through word of  mouth and increased sales
