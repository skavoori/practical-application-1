# Exploration of Data Anaysis

This repository hosts a [Jupyter Notedbook](prompt.ipynb) that demonstrates the various ways data analysis can be performed using Pandas, NumPy and Seaborn libraries. Analysis is performed on the [coupons data](data/coupons.csv) taken from  UCI Machine Learning repository. The problem statement for the exploratory phase is outlined below along with data description and key findings.  

## Problem Statement
The [data](data/coupons.csv) provided to us have the information about various users who under a certain context were shown a coupon to nearby establishments. We were also provided a column Y in the data that indicates if the coupon has been accepted by the user or not. The objective of this exercise is to highlight the differences between customers who did and did not accept the coupons.

## Data Description 

At the high level the data consists of the following 3 sections 

### User Attributes 

There are various attributes of the user like their gender, age, marital status, number of children, education, occupation, annual income, their habits related to the bar visits, eating out or buying takeaways, visiting coffehouse etc., Most of these data are categorical data falling into various categories. Age is a numeric data but provided as an object type in the [data file](data/coupons.csv).Income is also provided as a categorical value. 

### Contextual Attributes
Some of the attributes that were provided to us are driving destination, which is categorical data with a limited amount of categories,location of user, coupon and destination, weather data, temperature, time and Passengers in the car when the coupon is shown. 

### Coupon Attibutes 
This data only contains the time before it expires. 

## Key Findings
- Overall acceptance rate of coupons is at 56.84%
- There are more Females who rejected the coupons than Male.
- Acceptance rate is higher for `Carry out & Take away` Coupons.
- Acceptance rate is lower for `Bar` Coupons
- For Bar Coupons 
    - Acceptance rate is higher for people who visit Bar 4 or more times. 
    - 


## Methodology 

Various methods available for DataFrame object from Pandas library have been utilized to get a deeper understanding of the data. Also, Seaborn library has been used to visualize the data using various  plotting methods available in the library. 

