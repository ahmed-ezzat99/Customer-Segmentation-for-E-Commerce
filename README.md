# Customer Segmentation Using Unsupervised Learning

This project applies unsupervised machine learning techniques to segment customers based on their transactional behavior and demographic data. The goal is to identify meaningful customer groups and recommend targeted marketing strategies (e.g., coupon offers) to enhance customer loyalty and satisfaction.

## Table of Contents

- [Project Overview](#project-overview)
- [Libraries Used](#libraries-used)
- [Data](#data)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Clustering Model](#clustering-model)
- [Segment Analysis](#segment-analysis)
- [Recommendations](#recommendations)

## Project Overview

This project involves:
1. **Data Merging**: Combining multiple datasets (e.g., customers, transactions, merchants) into one unified dataset.
2. **Exploratory Data Analysis (EDA)**: Analyzing customer demographics, coupon usage, and transaction behaviors.
3. **Feature Engineering**: Preprocessing and selecting features for the clustering model.
4. **Unsupervised Learning**: Applying K-Means clustering to segment customers into meaningful groups.
5. **Segment Analysis**: Describing the characteristics of each customer group and recommending strategies to improve loyalty.
6. **Model Evaluation**: Using metrics like the Elbow Method and Silhouette Score to determine the optimal number of clusters.

## Libraries Used

The following libraries are required to run this project:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib** & **seaborn**: For data visualization.
- **scikit-learn**: For machine learning (e.g., K-Means clustering, StandardScaler).

## Data

The project uses an e-commerce dataset that includes:
- **Customers**: Demographic information.
- **Transactions**: Transaction details, such as coupon usage, transaction amount, and merchant info.
- **Merchants**: Information about merchants providing services/products.
- **Coupon usage**: Frequency of coupon utilization across different customers.

## Exploratory Data Analysis (EDA)

Several visualizations are created to better understand the data:
1. **Gender Distribution**: Counts of male and female customers.
2. **City Distribution**: Number of customers from different cities.
3. **Transaction Status**: Overview of successful vs. failed transactions.
4. **Coupon Usage**: Frequency distribution of coupons used.
5. **Transaction Amount**: Distribution of transaction amounts.
6. **Correlation Analysis**: Correlation matrix to find relationships between numerical features.

## Clustering Model

We use **K-Means Clustering** to segment customers into groups. The following steps are performed:
- Standardizing the selected features.
- Experimenting with different numbers of clusters (K) using the **Elbow Method** and **Silhouette Score**.
- Determining the optimal number of clusters and fitting the final K-Means model.

## Segment Analysis

Each customer segment (cluster) is analyzed to identify behavioral patterns, such as:
- Coupon usage frequency.
- Transaction amounts.
- Customer demographics.

## Recommendations

Based on the cluster analysis, targeted marketing recommendations are made. For example:
- **High coupon users** with low loyalty should receive special promotions.
- **Moderate coupon users** may benefit from personalized recommendations to increase their engagement.




