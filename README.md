# Bike-Price-prediction-using-supervised-M-achine-learning
## **Project Summary -**



Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. Bike sharing has been popular in many countries, due to the fact that environmental proception organizations proposed environmental sustainability transportation methods such as electric vehicles and bicycles . It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern.


The main objective of this project is to develop a machine learning model that can accurately predict the demand for bike rentals in Seoul, South Korea, based on historical data and various relevant factors such as weather conditions, time of day, and public holidays. In this project we have used regression analysis techniques to model the bike demand data. The model trained on a large dataset of past bike rental information, along with relevant weather and time data. The model then be tested and evaluated using metrics such as mean squared error and r-squared values. The actual data is from the Seoul city government's open data portal

So, our main goal was to achieve an accuracy of at least 85% in the bike demand predictions, which would help the city's bike sharing service providers plan their fleet operations more effectively and respond to demand changes in real-time. We have performed lots of regression algorithms like linear regression, random forest, decision tree, gradient boosting  also we tried to do hyperparameter tuning and cross validation to improve the accuracy of the model. And finally we have decided to select  gradient boosting algorithm because it gave us high accuracy around 91% and 90% on train and test data resp.

This project not only provided valuable insights into bike demand patterns in Seoul but also demonstrated the practical applications of machine learning in addressing real-world problems. The findings could potentially be extended to other cities with similar bike sharing systems, leading to improved services for bike users and more sustainable transportation systems.

The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:

1)Date : year-month-day

2)Rented Bike count - Count of bikes rented at each hour

3)Hour - Hour of he day

4)Temperature-Temperature in Celsius

5)Humidity - %

6)Windspeed - m/s

7)Visibility - 10m

8)Dew point temperature - Celsius

9)Solar radiation - MJ/m2

10)Rainfall - mm

11)Snowfall - cm

12)Seasons - Winter, Spring, Summer, Autumn

13)Holiday - Holiday/No holiday

14)Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
