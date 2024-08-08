# F-n-F-Bistro-Suppliers-Analysis
The analysis of supplier performance at Flavours 'n' Forks (F’n’F) Bistro provides valuable insights into the efficiency of the supply chain. The analysis covers crucial aspects such as fulfillment rates, cancellation rates, lead times, and supplier performance, providing a well-rounded view of the supply chain

![](dataanalytics.avif)

## Introduction
Flavours ’n’ Forks Bistro, also known as F”n” F Bistro, is a renowned restaurant in the heart of Lagos. Flavours ’n’ Forks Bistro faces significant challenges in its supply chain due to fluctuations in supplier performance.

This inconsistency impacts the restaurant’s ability to maintain a steady flow of high-quality ingredients. And addressing these supply chain issues is crucial for Flavours ’n’ Forks Bistro to maintain its high standards and ensure a seamless dining experience for its guests.


## Problem Statement
The analysis should address the following:
* Inconsistency in the quality of ingredients sourced from various suppliers
* Flavours ’n’ Forks Bistro encounters occasional delays in the delivery of ingredients
* Price fluctuations among different suppliers have made it challenging to maintain cost efficiency while upholding the bistro’s high-quality standards

## Data Source
The data used for this work is gotten from [Amdari](https://www.amdari.io)

## Skills and Concepts Demonstrated
Power BI concepts like:
*	Created key performance indicators (KPIs) and other business calculations
*	Developed general DAX calculations, performed advanced DAX calculations for solving statistical measures and mathematical formulas
*	Understanding of Business Requirements
*	Performance Optimization
*	Data Visualization

## Data Transformation
I imported the file into Power BI and selected all tables then clicked on Transform Data. In Power Query Editor, I created date table
![](TablesChoosen.PNG)

### Data Cleaning
In Power Query, I checked for Colum quality and converted each column to it appropriate data type.
* Power Query
![](DataFormat.PNG)

I closed and apply after all necessary changes

### Data Modelling
The Star Schema is the 'Order Table' and other 2 tables were connected to it. PowerBI did this intelligently, automatically creating relationships with them.
* Model View

![](AutomatedModel.PNG)

## Data Analysis 
I began creating and defining DAX measures. Numbers of expressions and functions were made to arrive at the desired Key Performance Indicator (KPI). Translated business requirements into report specifications and optimized the report performance by considering the best practices. 
* DAX
![](DAX.PNG)

## Data Visualization
Effective visualizations were created in Power BI using charts and cards. Organizing and arranging visuals were put to play in designing the dashboards for a cohesive view of key performance indicators.
I arrived at a report with two (2) pages named:
* F'n'F Bistro Suppliers Analysis
* F'n'F Bistro Orders Analysis

### First Page
The first page is named F'n'F Bistro Suppliers Analysis and it contains all information in regards to suppliers. 
This page shows -

Suppliers' names by average lead time and fulfillment rate
This shows which suppliers are the quickest in delivering orders and how often they fulfill their orders completely. It helps identify reliable and efficient suppliers


Suppliers by avg lead time and quantity supplied
This indicates the average time each supplier takes to deliver orders and the total amount of goods they supply. It helps assess which suppliers are quick and also handle large quantities of supplies.


Average lead time by quantity supplied by month
This shows how the average delivery time changes with the amount of goods supplied each month. It helps identify patterns in delivery times and supply quantities.


Ingredients by ordered quantity and received quantity
This compares how much of each ingredient was ordered and how much was actually received. It helps evaluate the accuracy and reliability of the supply chain for different ingredients.


* F'n'F Bistro Suppliers Analysis

The second page shows all the details of F'n'F Bistro Orders Analysis in regards to Quantity Ordered 
* F'n'F Bistro Orders Analysis

![](Region.PNG)

## Analysis
* It shows the average time each supplier takes to deliver orders and the total amount of goods they supply.
* It identify suppliers with the lowest lead time in delivering orders and how often they fulfill their orders completely.
* It shows how the average delivery time changes with the amount of goods supplied each month.
* It compares how much of each ingredient was ordered and how much was actually received.
* It shows how long it takes on average to receive different ingredients and how much of each ingredient is supplied.
* It indicates how often orders for each ingredient are canceled and how often they are completely fulfilled.
* It shows how the average delivery time, the amount of goods ordered and the amount of goods supplied vary each month.
* It depict how often each supplier cancels orders and how often they fulfill orders completely.

## Insights
Overall Insights from Analyzing Suppliers Performance at Flavours 'n' Forks Bistro
📌 The overall fulfillment rate is high at 95.14%, which is a positive indicator
📌 The overall cancellation rate is 4.9%, indicating that there's still room for improvement
📌 Vegetables have the highest cancellation rate at 6.8%, suggesting potential issues with supply or quality that need to be addressed
📌 Elizabeth Austin has the highest supplier compliance rate while Jessica Hodges has the lowest compliance rate, indicating a potential need for supplier contract renegotiation
📌 The overall average lead time is 15.6 days
📌 Among all suppliers, Whitney Burch has the highest lead time indicating inefficiency or logistical challenges
📌 Tomatoes have a significantly high lead time and a low quantity supplied compared to other ingredients, pointing to a need to review the tomato supply chain
📌 There is a difference of 3K between the quantity ordered and the quantity received
📌 While the overall fulfillment and cancellation rates are good, specific suppliers like Jessica Hodges and Frances Wilson have low fulfillment rates
📌 There is a noticeable increase in overall average lead time in March and October which should be investigated further

## Recommendations
Recommendations from Analyzing Suppliers Performance at Flavours 'n' Forks Bistro
* Engage with current vegetable suppliers or adjust sourcing strategies to reduce the high cancellation rate
* Investigate the reasons behind the high lead time especially for tomatoes and consider alternative suppliers or improved forecasting methods
* Evaluate the risk of relying on a small number of suppliers and consider diversifying to reduce the potential for supply chain disruptions
* Monitor suppliers with lower fulfillment rates to understand the causes and work with them to increase their fulfillment rates
* Investigate the high lead times in March and October to ensure they do not affect the Bistro's operations and improve inventory planning for these months

## Thank you for reading!








