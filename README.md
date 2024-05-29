# Product Analysis of Amazon

1. [Project Overview](#ProjectOverview)
2. [Data](#data)
3. [Installation](#installation)
4. [Project Motivation](#ProjectMotivation)
5. [Results](#results)

## 1. Project Overview <a name="ProjectOverview"></a> 

This project conducts a detailed analysis of Amazon's e-commerce data to explore various aspects of customer behaviour and product performance. Through descriptive statistics, trend analysis, sentiment extraction, association rule mining, customer segmentation, and predictive modelling, this project aims to uncover insights that can inform business strategies and improve customer satisfaction.

## 2. Data <a name="data"></a> 

This dataset is from [Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data). Having the data of 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon.

## 3. Installation <a name="installation"></a> 

To run this project, install the required libraries using:
```
pip install pandas numpy matplotlib seaborn scikit-learn nltk mlxtend
```

## 4. Project Motivation <a name="ProjectMotivation"></a> 

**In this project we focused retail analysis with Amazon data and answer the following questions:**
1. Basic Descriptive Statistics: What is the distribution of product prices and ratings across different categories?
2. Trend Analysis: How do product ratings and prices vary by discount percentage?
3. Sentiment Extraction: What are the common phrases or words found in the reviews of the top-rated and lowest-rated products?
4. Association Rules Mining: What are the most common products bought together within certain categories?
5. Customer Segmentation: Can customers be segmented based on their review patterns and purchase behaviors?
6. Predictive Modeling: Can the rating a product will receive be predicted based on its price, category, discount, and textual review sentiment?

## 5. Result<a name="results"></a>
The details of the results are shown in the code.
The best machine learning model to predict product ratings is the Random Forest Regressor.
