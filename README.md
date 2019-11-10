
# Module 3 -  Final Project 

## Introduction to Northwind Speciality Foods 

This data set represents a fictional retailer, Northwind, and was created by Microsoft.  

Northwind is a world-wide merchant that sells speciality food and beverages.  It has a sales office in the United Kingdom with 4 sales representatives, one who is also a manager.  The other sales office is located in the United states, has 5 sales people, one who is the VP and one who person who is responsible for inside sales. Inside sales representatives are typically people who work with the customers to find out what they want, create solutions and help smooth the sales process.

The data set runs from July of 2012 until early May of 2014.  Northwind carries a line of 77 products from the following 8 categories:
 - Beverages
 - Condiments
 - Confections
 - Dairy Products
 - Grains/Cereals
 - Meat/Poultry
 - Produce
 - Seafood
 
Northwind has 29 world-wide suppliers and uses 3 different shipping companies.  The schema of the data base can be found in the jupyter notebook.

## Objective
The objective of the project is to access the data, explore it, analysize it and answer for 4 questions using statisical tests.


## The Deliverables


1. My **_Jupyter Notebook_** contains the code I've written for this project. It is in a file labeled: project.ipynb.
2. This **README.md** file in the GitHub repository that describes the contents of the repository. 
3. A **_[Blog Post]** found at: https://www.blogger.com/blogger.g?blogID=1842951420674057543#allposts
4. An **_"Executive Summary" PowerPoint Presentation_** that explains the hypothesis tests, the findings, and the relevance to company stakeholders.  It can be found on youtube at: https://studio.youtube.com/channel/UCou5q5SnTNhH4nvsn_CjhjQ/videos/upload?filter=%5B%5D&sort=%7B"columnType"%3A"date"%2C"sortOrder"%3A"DESCENDING"%7D

##  Conclusion and Business Recommendations

Data collection of the Northwind company was collected from July, 2012 until early May, 2014.  Over that perioed of time, revenue was steadily increasing.  The purpose of this report is to analyze the data and determine if some factors have statistical significance to that growth.  This information about the business model may be helpful to determine the future goals and strategies.

Four questions about the Northwind data set were presented:
- Does discount amount have a statistically significant effect on the quantity of a product in a order? If so, at what level(s) of discount?
- Is there a statistical difference in the average size of orders in dollars per sale between the employees in US and UK offices? 
- Since there may (or may not be) a difference between the US and UK sales office in average revenue per order, does that have to do with the discounting differences between employees?
- Does one category (1 of the 8) of product have a significantly higher impact on sales than others?


Null hypotheses and alternative hypotheses where declared, the data bases were queried to find the supporting data using SQL lite and statistical tests were performed on the data.  Student's t-test, Welch's t-test, ANOVA, the Central Limit Theorem (sampling means), p-value calculations, power calculations and effect size calculations were administered to build the case to accept or reject the null hypotheses.

It is interesting to note that after November, 2013 revenue dramatically increased. The data set provided factual information to explain the increase (increasing number of new customers, increasing sales of product). However, the data set could not provide insight into any business plans that may have been implemented with the goal of increasing sales. For example, was there a positive reference in the news about Northwind that brought new customers? Was there a competitor challenging Northwind's customer base and the employees intensified their efforts or were incentivized to intensify their efforts? Was there a trade show that Northwind attended in order to expose their name to more customers? Was there a marketing campaign implemented?

Based on the statistical testing done, it appears that providing discounts to customers does have an impact on the quantity of products sold.  Discounting at the 15% and 25% level were the most signficant, and can be useful information when developing future marketing campaigns and sales strategies. Northwind may want to develop a company policy on discounting so there is consistency amoung orders and customers, and to minimize lost revenue from using discounts (1-14%, 20%) that are statistically significant. Additionally, it was found that the meal/poutry category of products have the most significant contribution to sales over any other category.  This knowledge can be useful for broadening the product offerings as a goal of increasing sales.  Northwind may want to use that knowledge to develop marketing campaigns to further increase the sales of the meat/poultry category in order to maximize revenues. Finally, regarding the two other queries about employee sales productivity and discouting, there was not enough evidence to suggest that there is a difference between the UK and US sales office.  This is good news that the two offices operate in sync.  However, it would be worthwhile to review sales and marketing plans to be sure both offices are provided the same level of support, education, tools and incentives going forward in the future.