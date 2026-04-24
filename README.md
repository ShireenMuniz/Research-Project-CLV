# Research-Project-CLV
A MACHINE LEARNING FRAMEWORK FOR CUSTOMER LIFETIME VALUE  PREDICTION IN MULTI-CATEGORY RETAIL


## Dataset Description:

1. https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store?select=2019-Oct.csv

2. https://www.kaggle.com/code/bhavinmoriya/customer-lifetime-value-prediction/input


## Abstract
This paper presents a hybrid machine learning framework for Customer Lifetime Value (CLV) in multi-category eCommerce retail, which includes the following techniques K-Means behavioral segmentation, segment-wise XGBoost regression, categorical specialization, cold start evaluation via sessions and LSTM temporal prediction model. This methodology was evaluated on a dataset containing 26,560,622 transaction records of 263,445 unique customers and another validation data containing 805,549 transactions records belonging to 5,878 distinct customers. Five models were compared based on RMSE, MAE and R² scores. The proposed Segmented XGBoost model outperformed all the other models on both databases (R² score = 0.9983 and R² score = 0.8928). The Hybrid LSTM Fusion was the second best on the main data set (R²=0.9949), while cross-data validation shows an improvement in the performance of the session-based cold start model from an R² of −0.057 to an R² of 0.9114 when moving from a one-month period to a two-year period, respectively, thereby establishing that the effectiveness of these models depends on temporal data depth.

