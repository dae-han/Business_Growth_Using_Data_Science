# Predictive Customer Analytics for Optimizing Business Growth (Customer Segmentation and Consumer Behavior Prediction)


## Problem Statement

In this project, I provide data-based insights into the consumer behaviors and make predictions on their future behaviors in order to help an online retailer optimize their business growth. The customer behaviors are for example their retention rate, next purchase day and more.

I first define some Key Performance Metrics (KPIs) that represent the company's business goal and segment the customers based on the KPIs. I then predict the behaviors of each customer groups.

## About this Repository

### Data
The data is from an online retailer and it contains information about all sales made during an eight month period. The columns in this data are the following.
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

Source: https://www.kaggle.com/vijayuv/onlineretail


## Executive Summary

### `01_Metrics.ipynb`
This notebook was intended help the business track and analyze their growth. In order to do so, I defined some metrics that best capture the company's core value that their product delivers to the customers.

According to Sean Ellis, CEO of Growth Hackers, the single metric that best captures the core value value is called **The North Star Metric**. For this online retailer, the north start metric was their Monthly Revenue. I also defined some other KPIs that would help the retailer track their growth--such as monthly active customers, monthly order count, average revenue per order.

stretch goal
--> dashboarding these metrics, building pipeline

### `02_Customer_Segmentation.ipynb`
This part of the project is to help the business understand the value of each customers. I gave each customers an overall RFM (Recency, Frequency, and Monetary Value) score. I then executed clustering analysis to segment the customers based on the score into three groups-low, mid and high value customers.

 By segmenting customers into different groups, the business can execute personalized marketing strategies to different user groups. In this example, I speculated that high value customers need marketing strategies that improve their recency, whereas for low value customers, marketing strategies to increase their frequency will work better. The effectiveness of the new actions can be tested and evaluated by using A/B testing frameworks and market respond modeling, which I cover in [another project](https://github.com/dae-han/AB_Testing_Framework_and_Market_Response).

### `03_Lifetime_Value_Prediction.ipynb`
Lifetime Value (LTV) of a customer is gross profit margin the customer brought to the company within a set timeframe.

### `04_Churn_Prediction.ipynb`
### `05_Next_Purchase_Day_Prediction.ipynb`

## Next Step

## Source
