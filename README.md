<img width="1059" height="593" alt="image" src="https://github.com/user-attachments/assets/b92f616b-0082-486a-aa78-1ad7e0271f9e" />



# Customer Satisfaction Analysis 

This project analyzes customer satisfaction trends in Brazil using Olist’s e-commerce review dataset.
The objective is to understand the factors driving positive and negative customer experiences and provide data-driven recommendations for improvement.


# Project Summary

Between 2017 and 2018, Olist in Brazil maintained a strong average review score of 4.08, with most customers reporting positive experiences.
However, 11.4% of customers were highly unsatisfied, indicating recurring issues that required deeper investigation.

A total of approximately 98,000 reviews were analyzed.
Data from 2016 was excluded due to missing months, low review volume, and inconsistencies that could lead to misleading results.


# Data Cleaning (Python)

Data preparation was conducted in Python using Pandas.

Key steps included:
	•	Removing nulls
	•	Adding consolidated product categories
	•	Preparing a clean dataset for Tableau


# Visualizations (Tableau)

All visualizations and dashboards were created in Tableau.

## The analysis included:
	•	Distribution of satisfaction levels
	•	Trends in average review scores over time
	•	Performance comparisons across product categories
	•	Delivery performance and lateness
	•	Seller behavior and its impact on satisfaction
	•	Extraction and translation of all “Highly Unsatisfied” review comments


# Analytical Areas

## 1. Overall Satisfaction Analysis
 •	Customer Satisfaction Overview (KPIs) – includes total reviews, percentage of highly satisfied customers, percentage of highly unsatisfied customers, and the overall average review score.
	•	Customer Satisfaction Distribution – classifies reviews into Highly Unsatisfied, Satisfied, and Others based on score levels.
	•	Average Customer Review Score Over Time – tracks changes in the average review score across the selected years.


## 2. Category Performance
	•	Total Reviews per Category – shows the distribution of customer reviews across all product categories.
	•	Percentage of Highly Unsatisfied per Category – highlights which categories have the highest share of 1-star reviews.
	•	Highly Unsatisfied Comment Classification – categorizes the main reasons behind negative reviews.
	•	Platform-Related Comments Over Time – tracks platform-specific issues mentioned by customers across different time periods.

## 3. Delivery Performance
	•	Mostly Delivered Categories – shows which product categories have the highest proportion of successfully delivered orders.
	•	Highly Unsatisfied Delivery Spam – highlights categories where delivery issues lead to the most 1-star reviews.
	•	Highly Satisfied Delivery Spam – displays the categories where timely and successful deliveries result in 5-star reviews.

## 4. Seller Behavior
	•	Satisfaction variations across sellers
	•	Identification of low-performing sellers
	•	Analysis of seller issues such as late shipping, incorrect items, and lack of response



# Project Goal

The goal of this project is to identify the root causes behind customer dissatisfaction and provide actionable recommendations to improve:
	•	Customer experience
	•	Delivery processes
	•	Product category reliability
	•	Seller performance

