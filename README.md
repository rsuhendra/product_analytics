# Product Analytics Project: Optimizing Banner Performance for an Online Sporting Goods Store

### Introduction

In e-commerce, understanding user behavior and optimizing marketing strategies are key to driving sales and revenue. This project analyzes the effectiveness of promotional banners on an online sporting goods store's main page. The store displays one of five randomly selected banners, each advertising a product or the company. Using A/B testing, we aim to determine how well each banner performs in driving user engagement (clicks) and conversions (orders). The insights will help the store manager decide whether to keep, replace, or optimize the banners for better performance.

### Dataset Overview

The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/podsyp/how-to-do-product-analytics/data), contains the following information about user interactions:

- **Time of Interaction**: Timestamp of each user interaction.
- **Banner Interaction**: Whether the user clicked on a banner.
- **Order Placement**: Whether the user placed an order.
- **Banner Type**: The type of banner displayed (one of five options).
- **Site Version**: Whether the desktop or mobile version of the site was accessed.

### Project Objectives

- **Feature Engineering**: Create meaningful features from the raw data, such as time-based metrics (e.g., time of day, day of week) and user engagement patterns.
- **Data Exploration**: Perform exploratory data analysis (EDA) to understand the dataset and identify key trends and patterns.
- **Banner Performance Analysis**: Analyze the performance of each banner in terms of click-through rates (CTR) and conversion rates (orders) using A/B testing to compare the effectiveness of different banners.
- **User Behavior Analysis**: Investigate how user interactions vary by time of day, day of week, and banner type.
- **Actionable Insights**: Provide actionable insights and recommendations to the store manager on which banners perform best and how to optimize their placement and design.

### Tools and Technologies

- **Programming Language**: Python
- **Libraries**: PySpark, XGBoost, Pandas, Scikit-learn
- **Data Visualization**: Matplotlib, Seaborn

### Conclusions

- The clothing banner has the highest clickthrough rate AND highest conversion rate.
- The desktop site has a lower clickthrough rate but a higher conversion rate.
- We find 4 clusters through KMeans. One cluster corresponds to non-buyers, while the other 3 cluster based on time.

For more details, please refer to the [Jupyter Notebook](https://github.com/rsuhendra/product_analytics/blob/main/spark.ipynb) included in this repository.
