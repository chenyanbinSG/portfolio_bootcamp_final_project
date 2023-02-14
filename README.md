# Use Power BI to analyse sales orders and provide marketing findings/ recommendations

This capstone team project marked the finale of my 12-week Business Intelligence and Data Analytics Bootcamp. It drew on the theory, knowledge and skills developed during the 3-month program where we were to critically think, plan, execute and deliver our findings and recommendations via Power BI report format. 

The project focus was on the publicly available dataset of orders placed on Olist Store, a Brazilian e-commerce marketplace integrator. It contained 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil.

![image](https://user-images.githubusercontent.com/120662583/217761915-7f000623-1edf-43d5-952c-4d8f8bc79c1c.png)

# Project Scope

To critically analyse the 100k orders. An order can be viewed from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. There is also a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

__Requirements:__
- Create data pipeline to ingest data in PostgreSQL or SQL server database
- Use Power BI to visualise the company’s customers’ demographics, sales trend, orders by categories, orders changes by year, etc
- Analyse relevant data using statistical methods (e.g. Predictive Modelling or Machine Learning)
- Other scopes, where possible: Feedback sentiment analysis, sales prediction

# Resources
- __Project Interface__: Microsoft Power BI Desktop, Microsoft Power BI Web, Juypter Notebook 
- __Python Version__: 3.9.6
- __Database:__ PostgreSQL 
- __Others__: [Brazilian e-commerce public dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

# Simple data pre-processing in Jupyter Notebook using Python 

- Query the dataset from CSV files and store as Pandas DataFrame 
- Check dtypes, data deduplication
- Use unicodedata to degrade accented characters to their non-accented equivalent
- Use google trans to translate reviews in Portuguese to English for better and easier understanding
- Write final DataFrame to PostgreSQLand connect to it via Power BI 

# Data wrangling in Power BI 

- Setting datatypes, data format, etc 
- Features such as Forecasting, etc 
- Metrics such as hierarchy slicer, etc 
- Visuals such as Microsoft Word Cloud, Radar Chart time series, etc 

# Exploratory Data Analysis with Power BI 

### 1. Overview of orders
![image](https://user-images.githubusercontent.com/120662583/218385457-ddba0d3b-a2aa-40e9-b47f-85afc4d844a3.png)


### 2. Trend Analysis of Month-on-Month Sales for individual product category 

Recommend to dive into focus area such as expansion of catalogs for key categories such as "Health Beauty" and "Housewares" to boost top-line revenue exponentially.

![image](https://user-images.githubusercontent.com/120662583/218385598-19792b16-448a-4957-aa56-4fdec2d1cfe8.png)


### 3. Customer Acquisition 

Recommend to launch loyalty programs to boost incremental sales and customer retention while improving customer acquisition.

![image](https://user-images.githubusercontent.com/120662583/218388171-9a8a0afe-6cc0-409a-821b-974f21b31022.png)


### 4. Market Coverage 

Recommend to do market territory expansion.

![image](https://user-images.githubusercontent.com/120662583/218389036-0b2c411a-e5b7-4055-b76c-fdc447a44d96.png)


### 5. Consumer Purchasing Trends
![image](https://user-images.githubusercontent.com/120662583/218389163-c145ade5-c6da-43bd-8a3c-b2341468b491.png)


### 6. Delivery Service 
![image](https://user-images.githubusercontent.com/120662583/218396107-78834abd-a0e8-45fe-a0a9-38afd5a5030a.png)


### 7. Preferred Payment Mode 
![image](https://user-images.githubusercontent.com/120662583/218399005-a4a119d1-e258-47f0-b3dc-6dfcae9e9813.png)


### 8. Sales Forecast 

Capitalised on forecast to plan long term and utilised short term tactics to reach long term goals.

![image](https://user-images.githubusercontent.com/120662583/218399283-7d4c2ef4-f0f8-4c03-8e5d-4cffb58d7426.png)


### 9. Consumer Behaviour & Shopping Trends

To implement advertising sales program for further boost in revenue generation.

![image](https://user-images.githubusercontent.com/120662583/218400406-048ffe6b-25a0-4a30-9559-b6b066a111f9.png)

### 10. Feedback Analysis 

![image](https://user-images.githubusercontent.com/120662583/218411450-38dd7250-4e56-43e1-b887-516a759a4434.png)

# Challenges / Limitations

- Exploring alternative when Google Translate API in python didn't work (operation timed out)
- Text Analytics Sentiment function churned different results for the original reviews in foreign language and our translated reviews in English
- May encounter saving error when more than one teammate is working on Power BI web
- Limited functionality on Power BI web vs. Power BI Desktop , eg: Data Transformation had to be done on Desktop version

# Appreciation 

Thank you to my wonderful team for the hard work and all the effort!

![image](https://user-images.githubusercontent.com/120662583/218418415-4d4215f9-8fc3-4a37-94b5-87c76776584c.png)
