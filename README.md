# Predicting store segmentation and forecasting the revenue for the new stores
The company currently has 85 grocery stores and is planning to open 10 new stores at the beginning of the year. Currently, all stores use the same store format for selling their products. Up until now, the company has treated all stores similarly, shipping the same amount of product to each store. This is beginning to cause problems as stores are suffering from product surpluses in some product categories and shortages in others. You've been asked to provide analytical support to make decisions about store formats and inventory planning.

## Business Problem

### Determine the segmentation of stores based on revenue data.
To remedy the product surplus and shortages, the company wants to introduce different store segments. Each store format will have a different product selection to better match local demand. The actual building sizes will not change, just the product selection and internal layouts. 

We will determine the optimal number of segmentation based on revenue and use the K-means clustering algorithm to determine it.

### Predict the clusters for the 10 new stores
The grocery store chain has 10 new stores opening up at the beginning of the year. The company wants to determine which store segment each of the new stores should have. However, we don’t have sales data for these new stores yet, so we’ll have to determine the format using each of the new store’s demographic data. To solve this problem we will use a classification model to classify existing stores and use that model to predict the segmentation for the new stores.

### Forecast sales for produce category in both existing and new stores.
Fresh produce has a short life span, and due to increasing costs, the company wants to have an accurate monthly sales forecast. We will be using the time series models for forcasting. 

Please refer to the following link for detailed solution
https://github.com/gmalekar/Combining-Predictive-Techniques/blob/master/ForecastingRevenueForNewStores.pdf
