# PROBLEM STATEMENT:

Often times when investing in single family real estate, seller clients are unsure of what factors most impact the sales price of their property in a market. In addition, buyer clients can be unsure of what features to prioritize, or wrong about what features most impact value in a market. We are seeking to give our investor clients clarity what features most impact the value of single family real estate in Ames, Iowa


## Overview of Notebooks

Notebook 1: EDA, Linear Regression Model 1

This notebook was exploratory and admittedly disorganized as I was unclear about modeling workflow. That will continue to improve. Most of the correlation found between my selected features and the target variable was discovered in this notebook and carried over into Notebooks 2 & 3. 

Notebook 2: Linear Regression Model 2

I modified the features. Removing Wood Deck, Master Venir Area, and Open Porch. Adding in their place Year Built, Total Basement SQFT, First Floor SQFT, Gross Living Area, Cars per Garage, and Garage are width. 

Notebook 3: Lasso and Ridge models. 

Fitted the previous features with Lasso and Ridge. 


## Methodology, Inferences, & Assumptions:

* Disclaimer! With more time, I would have dug much deeper into the correlation of neighborhood with sales price. Location is the MOST important value element of real estate. In addition I would have liked to plot the neighborhoods on a map, and done more research on the traffic patterns, major streets, and lifestyle ammenities of the city. 

My initial approach was to investigate which features had the strongest correlation to sales price. From there I began clearning the data. Changing columns, dropping rows, and replacing null/Nan values. 

I observed Overall Quality, Year Built, Total Basement SQFT, First Floor SQFT, Gross Living Area, Cars per Garage, and Garage width had significant correlation with sales price. Aside from location, size plays a significant part in home value. In a city like Ames where from what I read there isn't much to do, and the weather gets extrenely cold; enough space for the family, storage, and a place to keep cars insulated are probably high priorities. 


## Conclusions & Recommendations:

What I found across the various models was that the selected features account for 83% of variability in sales price 
holding all else equal.


Many of the features listed cannot be altered once a home has been purcahsed. Overall quality and condition are two variables that a seller can control and also have significant correlation with sales price. 

For a seller, if the goal is to maximize sales price, these are the two features I would consider most. If budget is an issues it is important to note that quality is prioritized over condition because they are not the same. 

A home can be in great condition, but not show great quality in finish and decor. Buyers may not notice or inquire about the age of the roof, HVAC, or if the plumbing cast iron. The will notice the features and finishes and features of the kitchen and master bathroom. Quality can lead to higher, and more emotional purchases. Conditions can be addressed and negotiated later in the transaction once the property has a contract. 

For a buyer (aside from location), space seems to be the most important factor in this market. First floor space, a place to park cars, and extra space in the garage. Look for a house with a large spacious layout that may not be in the best quality, but has a solid condition (6 or better). This will allow you to negotiate off the price, walk in with equity and widen margins with updates to quality. 
