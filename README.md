# DSND_Term2_Customer_Visit_Analysis

## Introduction

If anyone has decided to buy a car, usually they will go to 4s shops to acquire more information about the desired car models, e.g the performance and safety parameters, price and discount, etc. Sometimes they also request for test drive.

If you want to have an quick overview of the business findings, please go the Blog: 
https://medium.com/@wuguangxin/can-we-distinguish-the-people-who-might-buy-a-car-in-4s-shop-6fd5fcf1006b


## Data

The data I am using in this repo is `data/visit_history.csv` 
It is an interesting data set open by a auto company, which has recorded customer visit behaviors in 4s shop. 

## Running

There is only one notebook `customer_visit_analysis` which aims to do basic customer analysis based on their visit behavior in 4s shop.

## Observation and findings

#### Question: Does customer usually make appointment before they visit the 4s dealer shop, and prefer to come to a sales consultant for more information? 
Answer: From the charts above, we see whether he/she make an appointment does not bring positive effect. But if there is a sales consultant assigned, the possibility to order will be significantly improved.

#### Question: How long does the customer usually stay in the 4s shop?
Answer: The average time each customer usually stay in the 4s shop is 83 minutes, and almost of them stay in less one hour. we can also have a distribution overview from the charts above. 

#### Question: How many customers request for test drive? Is test drive a significant feature to make an order?
Answer: 21% of people have applied for test drive. But I am a little bit surprised that people who applied test drive has lower possibility to make an order.

#### Question: Can we predict he or she will make an order based on the real-time visit behavior data?
Answer: Yes we can predict using the model above, and the performance looks fine. But the major objective of this notebook is not to build such model, so I do not decide to take much time to refine it.

## Conclusion
The visit history data gives us a better customer insight. By leveraging the machine learning models, we can also distinguish who has high probability to buy a car. 
