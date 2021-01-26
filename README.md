# Predictive Maintenance - TurboFan Engines
Predictive Maintenance using Machine Learning - Master HPC-AI Promo 2020-2021. Fadi BECHARA

The goal of this challenge is to predict whether or not some turbofan engines are going to break down within the next 100 cycles. The dataset consists of different multivariate time-series. These different time-series refer to different engines (engine no. in the dataset).

The sampling of the time series is 1 point per engine cycle ( timein_cycles in the dataset). The dataset is split into train data and test data to evaluate your model. 

In the train dataset: the engine runs until failure. It means that for each data point we can associate the RUL (Remaining Useful Life in cycles). 

This column is present in the train dataset (RUL). In the test dataset: The engine runs until a certain point. What you need to predict is whether or not the engine is going to fail whithin the next 100 cycles. .
