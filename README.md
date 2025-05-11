# PHASE-3-PROJECT

# Predicting Customer Retention for SyriaTel Mobile Telecom

## Overview
Customer churn is a major issue for SyriaTel in the competitive telecom market. With many options available, keeping existing customers is essential. Churn not only results in lost revenue but also increases the cost of acquiring new customers. To effectively retain customers, SyriaTel needs to understand what causes churn and predict it accurately. By analyzing past customer data, the company can identify at-risk customers and tailor retention strategies to improve satisfaction and loyalty.

## Business Understanding
SyriaTel aims to provide top-notch telecom services while expanding its market share, revenue, and customer satisfaction. To achieve these goals, it’s crucial to keep customers from leaving.

The goal of this churn prediction project is to help SyriaTel identify customers likely to churn and take proactive steps to retain them. This involves creating a predictive model based on customer behavior and usage patterns, allowing SyriaTel to offer targeted incentives to keep these customers.

## Data Understanding
The dataset used comes from Kaggle and includes records of 3,333 customers from a fictional company, SyriaTel. It contains 20 attributes, such as customer locations, call usage patterns, and account length, which indicates customer loyalty and lifetime value.

## Data Preparation
The data was cleaned and prepared for analysis, which included removing unnecessary columns, transforming data, and normalizing it. The target variables were set, and the data was split into training and testing sets.

## Modeling
Four models were developed using the prepared data:

Logistic Regression (baseline model)
Decision Tree
Random Forest
K-Nearest Neighbors
Model Evaluation
The Random Forest model performed the best, achieving a recall score of 71%. Key features influencing churn were identified, with total expenditure being a significant factor. Recommendations will follow based on these findings.

## Recommendations

1. Customer Retention Strategy: Implement personalized offers or discounts based on call minutes and charges to address churn factors.
2. Reduce Customer Service Calls: Develop strategies to minimize the need for customer service interactions, as these can lead to churn.
3. Reassess Costs: Consider adjusting pricing to be more budget-friendly for customers, as total expenditure impacts churn.
4. Improve Customer Service: Focus on addressing issues raised in customer service calls and ensure staff are well-trained in customer service best practices.
5. Customer-Centered Plans: Offer flexible plans that cater to diverse customer needs, such as international plans versus voicemail options.

## Summary/Conclusion
This project aimed to create a predictive model to identify SyriaTel customers at risk of churning. By analyzing historical data, various machine learning algorithms were tested to enhance prediction accuracy. The model can be refined with new data and additional features, like sentiment analysis from customer feedback, to improve its effectiveness. This project highlights the importance of data-driven strategies in managing customer churn in the telecom industry.
